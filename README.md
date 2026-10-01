DawnAurora Player Animation Resource Pack (DAPA)
A high-quality, fully custom player animation overhaul resource pack for Minecraft 1.20.1 Fabric. This pack replaces most vanilla player movement, posture, and interaction animations to create smoother, more natural, and more human-like motion behavior.
Requirement: Fabric Loader 1.20.1 + Entity Model Features (EMF) + Entity Texture Features (ETF)
Release State: Alpha Early Preview (Active Development)
License: Apache-2.0

---
Full Version Changelog (Alpha v0.0.1 – v0.0.4)
Alpha v0.0.4 (Latest Release)
This update focuses on movement detail enrichment, transition smoothing, bug elimination, and official website functionality fixes. This version greatly improves overall animation fluidity and fixes multiple long-standing animation state bugs from previous alpha builds.
New Features
- Added full sneak sway animation: Players will naturally sway left and right while crawling, making slow stealth movement far more organic and lifelike.
- Added block-edge leaning animation: The player’s body physically tilts when standing on the edge of blocks to simulate real-world center-of-gravity balance.
- Added exclusive fence walking animation: Unique posture and balance animations when standing or moving on fences and wall-like thin blocks.
- Added placeholder configuration hint system for future Respackopts customization support.
Optimizations
- Completely remade state transition blending logic for all movement animations, removing rigid frame jumps and motion discontinuity.
- Fine-tuned body swing amplitude, movement rhythm, and pose offset for walking, running, stopping, and turning.
- Optimized frame interpolation for low-FPS environments to reduce choppy motion.
- Unified animation exit and reset rules for all action states.
Bug Fixes
- Fixed critical issue where certain animation states would freeze permanently and fail to exit properly.
- Fixed occasional corrupted 1KB file downloads from certain CDN mirror sources.
- Fixed animation controller priority conflicts that caused overlapping motion layers.
- Corrected multiple bone rotation offset errors in basic player movement animations.
- Fixed resource pack metadata formatting issues that caused recognition failures in PCL2 and HCL launchers.
- Fixed theme toggle functional failure on the official project homepage.
Known Issues (v0.0.4)
- Custom shield blocking animation is still work-in-progress.
- Full armor state transition animations are still under development.
- Complete player damage/hurt reaction animations are not fully finalized.
- Minor animation blending jitter may still occur during extremely fast state switching.

---
Alpha v0.0.3
This is the largest update of the entire early alpha stage, completing nearly all core animation logic and adding a large number of exclusive functional animations, while solving major compatibility problems with mainstream custom launchers.
New Features
- Added complete custom shield blocking animation framework.
- Added dedicated torch holding animation and lantern holding animation.
- Added player hurt and damage reaction animation prototypes.
- Added hotbar item switch animation and armor state change animation logic.
- Added preliminary fence walking and block-edge standing animation systems (improved and finalized in v0.0.4).
Bug Fixes
- Fixed the well-known issue where PCL2 / HMCL launchers could not detect or load the resource pack correctly.
- Fixed random animation jitter in multiple movement scenarios.
- Fixed broken transition frames during quick item switching.
- Fixed JSON animation controller parsing errors.
- Fixed incorrect animation blending timing causing stuck motions.
- Fixed rare animation stop failures after dimension switching.

---
Alpha v0.0.2
This version focused on polishing basic motion fluency, fixing offset errors of v0.0.1, and completing basic idle and environmental animation systems.
New Features
- Added fully customized idle animation sequences for third-person and first-person perspectives.
- Implemented precise head yaw and pitch rotation animations following camera movement.
- Completed full swimming animation system for underwater movement.
- Built basic interactive animation framework for item holding and hand posture adjustment.
Optimizations
- Rebalanced idle breathing subtle body movement amplitude.
- Optimized perspective switch motion smoothing to eliminate sudden posture jumps.
- Upgraded first-person hand base pose and movement synchronization with body motion.
Bug Fixes
- Fixed multiple third-person player model offset errors during running and jumping.
- Fixed abnormal sprint body tilt posture from v0.0.1.
- Removed unfinished unstable shield and idle animation prototypes that caused motion conflicts.

---
Alpha v0.0.1 (Initial Alpha Release)
The first official preview version of the DAPA animation resource pack, rewriting the entire vanilla player basic movement animation system and laying the foundation for all subsequent custom motion logic.
Core Implementations
- Complete overhaul of vanilla walking, running, sprinting, jumping, and falling animations.
- Realized synchronized first-person hand and body movement linkage.
- Implemented basic body tilting, camera follow rotation, and gravity simulation effects.
- Added preliminary animations for climbing, gliding, and underwater floating states.
Known Limitations
- Most advanced functional animations were unimplemented.
- Multiple animation blending logic was incomplete, resulting in obvious jitter in some scenarios.
- State transition smoothing was rough and unpolished.

---
General Alpha Release Notes
- All alpha versions are for testing and preview purposes only, not recommended for long-term survival worlds.
- Animation breaking, jittering, state locking, and model clipping may occur in unfinished features.
- Always install both EMF and ETF mods to ensure full resource pack functionality.
- Future updates will continue adding combat animations, complete armor motions, configurable options, and more detailed posture systems.
