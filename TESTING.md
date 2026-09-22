# Quality Assurance & Testing Report

This document outlines the testing strategy, defect lifecycle, and test execution matrix executed during the development of our Unreal Engine 5 third-person action project.

## 1. Testing Strategy & Cadence
Testing was conducted iteratively across four distinct development stages:
- **Phase 1 (Week 3 - Task Testing):** Individual functional playtests validating isolated mechanics (movement, pickups, level geometry) against initial specifications.
- **Phase 2 (Week 4 - Integration Testing):** Multi-system interaction validation, focusing on projectile collisions, damage application, and AI aggro ranges.
- **Phase 3 (Week 5 - Demo Testing):** Full-flow gameplay passes evaluating progression from Room 1 through the final Boss arena.
- **Phase 4 (Week 6 - Code Release Testing):** Comprehensive regression pass to catch blocking defects, verify patched Blueprint logic, and finalize build stability.

---

## 2. Configuration Management & Defect Prevention
To safeguard build integrity across a 5-developer Git repository, our team executed specific configuration management protocols:
- **Temporary Integration Branch:** All feature branches were merged and validated in a temporary staging branch prior to merging into `main`, isolating compile errors and merge conflicts.
- **Workspace Sanitization:** Resolved severe working tree lockups by identifying background cloud-storage (OneDrive) sync collisions and enforcing local drive paths for clean Git execution.

---

## 3. Defect Tracking Matrix

| Defect ID | Feature / System | Test Phase | Severity | Defect Description | Root Cause & Resolution Plan | Status | Tester |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **DEF-01** | Player Damage Logic | Beta | **High** | Character health calculation failed to register damage correctly, leading to negative values. | **Root Cause:** Node connection inverted; damage subtracted from health input node. Re-wired pin logic to subtract damage from current health pool. | **Resolved / Verified** | Robert |
| **DEF-02** | Knockback Turret | Alpha | **Medium** | Impact projectile drove character mesh directly into the ground collider, cancelling perceived knockback. | **Root Cause:** Vector lacked Z-axis elevation. Applied upward impulse vector to projectile hit response. | **Resolved / Verified** | Julie |
| **DEF-03** | Damage Turret | Beta | **High** | Turret killed player in a single hit regardless of configured damage variable; projectile spawned at irregular angles. | **Root Cause:** Socket transform misaligned with actor rotation; damage event fired per tick rather than per hit instance. Corrected socket offset and added hit-gate logic. | **Resolved / Verified** | Julie |
| **DEF-04** | Boss Death State | Beta | **Medium** | Boss enemy HP depleted to 0 but death animation montage failed to trigger reliably. | **Root Cause:** Behavior tree execution loop failed to abort lower-priority tasks upon state flag change. Added dynamic abort condition to Blackboard tree. | **Resolved / Verified** | Drew |
| **DEF-05** | Enemy Perception | Alpha | **Medium** | AI failed to detect player character across specific room sightlines. | **Root Cause:** AI perception sight radius blocked by uncleared bounding box collisions. Adjusted perception query channels. | **Resolved / Verified** | Steve |

---

## 4. Test Execution Summary
- **Total Development Tasks Tracked:** 16 Modules (81% completed on schedule)
- **Documented Test Items:** 14 Primary Mechanics
- **Initial First-Pass Rate:** 57%
- **Post-Fix Regression Pass Rate:** 100% of tested core combat and navigation mechanics verified prior to final submission.
