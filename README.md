# NvidiumPlus — Minecraft 26.3 / 1.0.0

This repository tree contains a source reconstruction of the NvidiumPlus 26.3-1.0.0 JAR, along with the resources and metadata extracted from that JAR. It is intended for code inspection and as a starting point for restoring the development project.

**Important:** this is decompiled/reconstructed source, not the original author source checkout. One method was reconstructed from bytecode after the decompiler failed, and the original Gradle build files are absent. See [`SOURCE-STATUS.md`](SOURCE-STATUS.md) before treating this as a complete or reproducible source release.

## Layout

- `src/main/java/` — reconstructed Java classes
- `src/main/resources/` — shaders, textures, language data, Fabric metadata, mixin configurations, and access widener
- `LICENSE` — GNU LGPL version 3 text (`LGPL-3.0-only`, as declared in the JAR metadata)
- `NOTICE.md` — upstream attribution and dependency notes
- `BINARY-MANIFEST.txt` — SHA-256 and embedded build identifier for the inspected JAR

## Dependencies recorded in the binary

- Minecraft 26.3
- Fabric Loader >= 0.19.3
- Fabric API
- Sodium 0.9.2
- Java >= 25

Sodium is integrated with, but is not bundled inside, the inspected NvidiumPlus JAR.
