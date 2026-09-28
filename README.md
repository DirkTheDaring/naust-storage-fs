# naust-storage-fs

Descriptor-relative filesystem storage adapter for the Naust registry ecosystem.

## Overview
- Linux `openat2` resolution beneath pinned root directory descriptors (`RESOLVE_BENEATH | RESOLVE_NO_SYMLINKS | RESOLVE_NO_MAGICLINKS`).
- Implements `ObjectStore`, `ObjectMetadataReader`, and `ObjectPayloadReader` from `naust-storage-core`.
- Atomic leaf mutations and deterministic fault injection test seams.

## License
MIT
