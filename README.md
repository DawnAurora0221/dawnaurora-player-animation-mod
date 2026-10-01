# DawnAurora's Player Animation
Short Name: Dapa | Minecraft 1.20.1 Fabric Animation Resource Pack

## 📦 Version Information (Latest: Alpha - v0.0.3)
- Release Type: Alpha Early Preview
- Supported Game Version: Minecraft 1.20.1
- Requirement: Fabric Loader for Minecraft 1.20.1
- Mandatory Dependencies: Entity Model Features (EMF), Entity Texture Features (ETF) (Fabric Mods)
- Resource Pack Format: 15

## ✅ Completed Features
This resource pack completely overhauls vanilla Minecraft player animations, bringing smoother, more natural and detailed movement performance for both first-person and third-person perspectives.
This Alpha v0.0.3 update adds multiple brand-new animation systems and resolves a large number of known bugs from previous releases.

- Custom idle animations
- Custom head yaw & pitch animations
- Custom running animation at default movement speed
- Custom sprint animation
- Custom swimming animation
- Custom walk-on-fence animation for moving on top of fence blocks
- Custom edge-standing animation when player stands on the edge of blocks
- Custom shield blocking animation
- Equipment & hotbar item swap animation
- Armor state animations
- Torch holding animation
- Lantern holding animation
- Player hurt / damage hit reaction animation

## 🚧 Work In Progress / Planned Features
All animation logic is fully implemented. Only the configuration system remains unfinished for future customization.
⏳ Respackopts configuration support for animation customization

## 🛠️ Full Changelog
### Alpha v0.0.3
#### Newly Added Animations & Features
- Added animation for walking on top of fence blocks
- Added player edge standing animation when standing on block borders
- Added custom shield blocking animation
- Added dedicated torch holding animation
- Added dedicated lantern holding animation
- Added player hurt / damage reaction animation when taking damage
- Added animation for equipment and hotbar item swapping
- Added dynamic armor state animations

#### Bug Fixes
- Fixed the resource pack recognition issue within PCL2 and HCL launchers
- Fixed abnormal animation jitter that occurred in some movement scenarios
- Fixed broken animation transition when switching held items
- Fixed multiple JSON parsing errors inside animation controller files
- Fixed incorrect timing of some movement animation blending
- Fixed rare cases where animations would stop playing after dimension switching

### Alpha v0.0.2
#### Newly Added Animations & Features
- Added custom idle animations
- Added custom head yaw & pitch animations
- Added full custom swimming animation
- Built basic weapon animation framework for item interaction

#### Bug Fixes
- Fixed animation blending weight calculation issues
- Fixed incorrect player pose while sprinting
- Fixed minor model offset errors in third-person perspective
- Optimized animation transition smoothness for basic movement

### Alpha v0.0.1
#### Newly Added Animations & Features
- Initial alpha release of Dapa animation resource pack
- Custom running animation at default movement speed
- Custom sprint animation
- Basic overhaul of vanilla player movement animation system

#### Known Issues at Release
- Missing many advanced animation systems
- Animation jitter occurs under certain movement conditions
- Some animation transitions are not smooth

## 📥 Download Links
### Preferred Mirror
https://gh-proxy.com/https://github.com/DawnAurora0221/dawnaurora-player-animation-resource-pack/releases/download/dapa/dawn-aurora-player-animation-resource-pack-add-on-alpha-v0.0.3-1.20.1.zip

### Alternative Mirror
shturl.cc/0FJYcKcsArJhtPG3MW6kVhsT7rZg6LPPiafxWsii04uZYlFMcViWX2DBxhTLPASXyuR7FZoGYtBtIERtlK61tt3ztSwIdFaNNNzhGcf3dBXn0L8yMRZ2y5vmwToWnocQTjdHhYDUgVYHfgmGsXHlaYVTSePUo3at9oxMDXV4981LJsJzTOu66R

### Fallback (Original GitHub Release Page)
https://github.com/DawnAurora0221/dawnaurora-player-animation-resource-pack/releases/tag/dapa

## 📖 Installation Guide
1. Install Fabric Loader for Minecraft 1.20.1 in your game launcher.
2. Download and install the two mandatory Fabric mods: Entity Model Features (EMF) and Entity Texture Features (ETF).
3. Download the Dapa resource pack zip file from one of the links above.
4. Place the downloaded zip file directly into your Minecraft `resourcepacks` folder.
5. Launch Minecraft, open Resource Packs menu, and enable DawnAurora's Player Animation resource pack.
6. Ensure EMF and ETF mods are loaded, otherwise all custom animations will not function.

## ⚠️ Important Notes
- This is an Alpha early preview version. Some hidden bugs or animation glitches may still exist.
- This is a **resource pack**, NOT a Fabric mod. It only works when EMF and ETF are present.
- This pack only supports Minecraft 1.20.1. It will not work on other game versions.
- If animations do not load, double-check your EMF and ETF versions and resource pack loading order.

## 📜 License
Apache License
Version 2.0, January 2004
http://www.apache.org/licenses/

TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

1. Definitions.
"License" shall mean the terms and conditions for use, reproduction,
and distribution as defined by Sections 1 through 9 of this document.

"Licensor" shall mean the copyright owner or entity authorized by
the copyright owner that is granting the License.

"Legal Entity" shall mean the union of the acting entity and all
other entities that control, are controlled by, or are under common
control with that entity. For the purposes of this definition,
"control" means (i) the power, direct or indirect, to cause the
direction or management of such entity, whether by contract or
otherwise, or (ii) ownership of fifty percent (50%) or more of the
outstanding shares, or (iii) beneficial ownership of such entity.

"You" (or "Your") shall mean an individual or Legal Entity
exercising permissions granted by this License.

"Source" form shall mean the preferred form for making modifications,
including but not limited to software source code, documentation
source, and configuration files.

"Object" form shall mean any form resulting from mechanical
transformation or translation of a Source form, including but
not limited to compiled object code, generated documentation,
and conversions to other media types.

"Work" shall mean the work of authorship, whether in Source or
Object form, made available under the License, as indicated by a
copyright notice that is included in or attached to the work
(an example is provided in the Appendix below).

"Derivative Works" shall mean any work, whether in Source or Object
form, that is based on (or derived from) the Work and for which the
editorial revisions, annotations, elaborations, or other modifications
represent, as a whole, an original work of authorship. For the purposes
of this License, Derivative Works shall not include works that remain
separable from, or merely link (or bind by name) to the interfaces of,
the Work and Derivative Works thereof.

"Contribution" shall mean any work of authorship, including
the original version of the Work and any modifications or additions
to that Work or Derivative Works thereof, that is intentionally
submitted to Licensor for inclusion in the Work by the copyright owner
or by an individual or Legal Entity authorized to submit on behalf of
the copyright owner. For the purposes of this definition, "submitted"
means any form of electronic, verbal, or written communication sent
to the Licensor or its representatives, including but not limited to
communication on electronic mailing lists, source code control systems,
and issue tracking systems that are managed by, or on behalf of, the
Licensor for the purpose of discussing and improving the Work, but
excluding communication that is conspicuously marked or otherwise
designated in writing by the copyright owner as "Not a Contribution."

"Contributor" shall mean Licensor and any individual or Legal Entity
on behalf of whom a Contribution has been received by Licensor and
subsequently incorporated within the Work.

2. Grant of Copyright License. Subject to the terms and conditions of
this License, each Contributor hereby grants to You a perpetual,
worldwide, non-exclusive, no-charge, royalty-free, irrevocable
copyright license to reproduce, prepare Derivative Works of,
publicly display, publicly perform, sublicense, and distribute the
Work and such Derivative Works in Source or Object form.

3. Grant of Patent License. Subject to the terms and conditions of
this License, each Contributor hereby grants to You a perpetual,
worldwide, non-exclusive, no-charge, royalty-free, irrevocable
(except as stated in this section) patent license to make, have made,
use, offer to sell, sell, import, and otherwise transfer the Work,
where such license applies only to those patent claims licensable
by such Contributor that are necessarily infringed by their
Contribution(s) alone or by combination of their Contribution(s)
with the Work to which such Contribution(s) was submitted. If You
institute patent litigation against any entity (including a
cross-claim or counterclaim in a lawsuit) alleging that the Work
or a Contribution incorporated within the Work constitutes direct
or contributory patent infringement, then any patent licenses
granted to You under this License for that Work shall terminate
as of the date such litigation is filed.

4. Redistribution. You may reproduce and distribute copies of the
Work or Derivative Works thereof in any medium, with or without
modifications, and in Source or Object form, provided that You
meet the following conditions:

(a) You must give any other recipients of the Work or
Derivative Works a copy of this License; and

(b) You must cause any modified files to carry prominent notices
stating that You changed the files; and

(c) You must retain, in the Source form of any Derivative Works
that You distribute, all copyright, patent, trademark, and
attribution notices from the Source form of the Work,
excluding those notices that do not pertain to any part of
the Derivative Works; and

(d) If the Work includes a "NOTICE" text file as part of its
distribution, then any Derivative Works that You distribute must
include a readable copy of the attribution notices contained
within such NOTICE file, excluding those notices that do not
pertain to any part of the Derivative Works, in at least one
of the following places: within a NOTICE text file distributed
as part of the Derivative Works; within the Source form or
documentation, if provided along with the Derivative Works; or,
within a display generated by the Derivative Works, if and
wherever such third-party notices normally appear. The contents
of the NOTICE file are for informational purposes only and
do not modify the License. You may add Your own attribution
notices within Derivative Works that You distribute, alongside
or as an addendum to the NOTICE text from the Work, provided
that such additional attribution notices cannot be construed
as modifying the License.

You may add Your own copyright statement to Your modifications and
may provide additional or different license terms and conditions
for use, reproduction, or distribution of Your modifications, or
for any such Derivative Works as a whole, provided Your use,
reproduction, and distribution of the Work otherwise complies with
the conditions stated in this License.

5. Submission of Contributions. Unless You explicitly state otherwise,
any Contribution intentionally submitted for inclusion in the Work
by You to the Licensor shall be under the terms and conditions of
this License, without any additional terms or conditions.
Notwithstanding the above, nothing herein shall supersede or modify
the terms of any separate license agreement you may have executed
with Licensor regarding such Contributions.

6. Trademarks. This License does not grant permission to use the trade
names, trademarks, service marks, or product names of the Licensor,
except as required for reasonable and customary use in describing the
origin of the Work and reproducing the content of the NOTICE file.

7. Disclaimer of Warranty. Unless required by applicable law or
agreed to in writing, Licensor provides the Work (and each
Contributor provides its Contributions) on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
implied, including, without limitation, any warranties or conditions
of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A
PARTICULAR PURPOSE. You are solely responsible for determining the
appropriateness of using or redistributing the Work and assume any
risks associated with Your exercise of permissions under this License.

8. Limitation of Liability. In no event and under no legal theory,
whether in tort (including negligence), contract, or otherwise,
unless required by applicable law (such as deliberate and grossly
negligent acts) or agreed to in writing, shall any Contributor be
liable to You for damages, including any direct, indirect, special,
incidental, or consequential damages arising out of the use or
inability to use the Work (including but not limited to damages for
loss of goodwill, work stoppage, computer failure or malfunction, or
any and all other commercial damages or losses), even if such
Contributor has been advised of the possibility of such damages.

9. Accepting Warranty or Additional Liability. While redistributing
the Work or Derivative Works thereof, You may choose to offer,
and charge a fee for, acceptance of support, warranty, indemnity,
or other liability obligations and/or rights consistent with this
License. However, in accepting such obligations, You may act only
on Your own behalf and on Your sole responsibility, not on behalf
of any other Contributor, and only if You agree to indemnify,
defend, and hold each Contributor harmless for any liability
incurred by, or claims asserted against, such Contributor by reason
of your accepting any such warranty or additional liability.

# DawnAurora's Player Animation - Alpha v0.0.2
Short Name: Dapa
Minecraft 1.20.1 Fabric Animation Resource Pack

## Overview
Alpha v0.0.2 brings more player animations and fixes multiple animation issues from v0.0.1.
More natural player motion and improved animation blending.

## Added
- Custom idle animations
- Custom head yaw & pitch animations
- Full custom swimming animation
- Basic weapon animation framework for item interaction

## Bug Fixes
- Fixed animation blending weight calculation issues
- Fixed incorrect player pose while sprinting
- Fixed minor model offset errors in third-person perspective
- Optimized transition smoothness for basic movement animations

## Dependencies
- Minecraft 1.20.1
- Fabric Loader
- Entity Model Features (EMF)
- Entity Texture Features (ETF)

## Notice
This is still an alpha preview. Some animations remain unfinished.

# DawnAurora's Player Animation - Alpha v0.0.3
Short Name: Dapa
Minecraft 1.20.1 Fabric Animation Resource Pack

## Overview
Alpha v0.0.3 is the largest update so far. Almost all planned animation logic has been fully implemented, including shield blocking animation.
Only Respackopts configuration support remains work-in-progress.

## Added
- Walk-on-fence animation
- Player edge standing animation
- Custom shield blocking animation
- Torch holding animation
- Lantern holding animation
- Player hurt / damage hit reaction animation
- Equipment & hotbar item swap animation
- Dynamic armor state animations

## Bug Fixes
- Fixed resource pack recognition issue in PCL2 and HCL launchers
- Fixed abnormal animation jitter in some movement scenarios
- Fixed broken animation transition when switching held items
- Fixed multiple JSON parsing errors inside animation controller files
- Fixed incorrect timing of some movement animation blending
- Fixed rare cases where animations stop playing after dimension switching

## Work In Progress
⏳ Respackopts configuration support for animation customization

## Dependencies
- Minecraft 1.20.1
- Fabric Loader
- Entity Model Features (EMF)
- Entity Texture Features (ETF)

## Notice
This is an alpha early preview. A small number of hidden bugs may still exist.
This is a resource pack, NOT a Fabric mod.


END OF TERMS AND CONDITIONS
