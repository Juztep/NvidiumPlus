# Notices and attribution

NvidiumPlus combines and adapts rendering code and techniques associated with the following projects. The published JAR declares `LGPL-3.0-only` in `fabric.mod.json`. The upstream projects below also identify their relevant code under LGPL version 3. Preserve these notices when redistributing this source reconstruction.

## Nvidium

- Project: [MCRcortex/nvidium](https://github.com/MCRcortex/nvidium)
- Author/maintainer attribution: MCRcortex and Nvidium contributors
- Upstream license: LGPL-3.0 (see the upstream `LICENSE.txt`)
- Nvidium is the NVIDIA-specific mesh-shader terrain-rendering project whose code and rendering work are part of NvidiumPlus's lineage.

## Meshelium

- Project: [Meshelium](https://github.com/ajz811/Meshelium) (developer credited as ded811)
- Author attribution: ded811
- Upstream license: LGPL-3.0-only (see the upstream `LICENSE`)
- Meshelium's own README states that some shader logic is derived from Nvidium and carries the same LGPL-3.0 license.

## Sodium

- Project: [CaffeineMC/Sodium](https://github.com/CaffeineMC/sodium)
- Author/maintainer attribution: CaffeineMC contributors
- Sodium is declared as a required runtime dependency by this JAR (`sodium` version `0.9.2`). It is not bundled as Sodium implementation classes in the NvidiumPlus JAR inspected for this reconstruction. NvidiumPlus contains integration/mixin code that targets Sodium. Sodium's own source and license are separate; this bundle does not include Sodium source code.

## Scope of this notice

This notice documents upstream attribution visible from the JAR metadata and the referenced upstream project pages. It is not a legal opinion or a substitute for checking the exact file-level notices and license obligations for the release being distributed.
