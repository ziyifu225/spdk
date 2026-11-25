# Patch Archive and Provenance

This directory stores original upstream patches and their provenance. The patches below are archived and have not been applied to the working tree.

## ef52ff8675a00b9039fc211ba4c67b1d6fd7c4ac

- Patch file: [ef52ff8675a00b9039fc211ba4c67b1d6fd7c4ac.patch](ef52ff8675a00b9039fc211ba4c67b1d6fd7c4ac.patch)
- Upstream repository: https://github.com/spdk/spdk
- Commit page: https://github.com/spdk/spdk/commit/ef52ff8675a00b9039fc211ba4c67b1d6fd7c4ac
- Original patch download URL: https://github.com/spdk/spdk/commit/ef52ff8675a00b9039fc211ba4c67b1d6fd7c4ac.patch
- Full commit SHA: `ef52ff8675a00b9039fc211ba4c67b1d6fd7c4ac`
- Subject: `nvmf/vfio_user: add vfio-user live migration (v2) support`
- Author: Hugo Komatsu <hugo.komatsu@nutanix.com>
- Date in patch header: `Fri, 17 Jul 2026 15:58:55 +0000`
- Change-Id: `I34e96ae09a88660b63df85a0d33d63ee32df2891`
- Archive date: 2026-11-25 (Europe/Berlin)
- Changes: 725 lines added to `lib/nvmf/vfio_user.c`.
- File size: 25479 bytes.
- SHA-256: `5ae6ff2effe7a4907e3ad47d1d3820ec0262d28a07072a15432ddd8cce37f5de`
- Archive method: Downloaded the original `.patch` content directly from GitHub without modification.
- Validation: The commit SHA in the patch header matches the requested commit; `git apply --stat` successfully parses the patch.

## 8d4518833f7980935a4513b05f316b4e6ec8057c

- Patch file: [8d4518833f7980935a4513b05f316b4e6ec8057c.patch](8d4518833f7980935a4513b05f316b4e6ec8057c.patch)
- Upstream repository: https://github.com/spdk/spdk
- Commit page: https://github.com/spdk/spdk/commit/8d4518833f7980935a4513b05f316b4e6ec8057c
- Original patch download URL: https://github.com/spdk/spdk/commit/8d4518833f7980935a4513b05f316b4e6ec8057c.patch
- Full commit SHA: `8d4518833f7980935a4513b05f316b4e6ec8057c`
- Subject: `nvmf/vfio_user: mark CQ and shadow doorbell pages dirty for migration`
- Author: Hugo Komatsu <hugo.komatsu@nutanix.com>
- Date in patch header: `Wed, 29 Jul 2026 14:28:29 +0000`
- Change-Id: `If0f23c8ba14e592b94597e5fd586304c8dd36e32`
- Archive date: 2026-11-25 (Europe/Berlin)
- Parent commit: `ef52ff8675a00b9039fc211ba4c67b1d6fd7c4ac` (archived above).
- Changes: 49 lines added to `lib/nvmf/vfio_user.c`.
- File size: 4091 bytes.
- SHA-256: `694a62020283aa536d91731288fb13699b89849c5b4be243ea6c5498b2542a12`
- Archive method: Downloaded the original `.patch` content directly from GitHub without modification.
- Validation: The commit SHA in the patch header matches the requested commit; `git apply --stat` successfully parses the patch.

## Integrity Verification

Verify file integrity from the project root:

```sh
sha256sum -c patches/SHA256SUMS
```
