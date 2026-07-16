# Controlled Tide Security Laboratory

This repository is owned and operated by the researcher.

Authorized accounts:

- Repository owner and automation operator: XMansor
- External fork and pull request author: r6crsss

Laboratory design:

- weak: no branch protection or required checks
- strong: protected by lab-lint and lab-unit
- weak and strong initially point to the same Git commit
- the external account has no collaborator access

Purpose:

- Evaluate Tide base-retarget behavior.
- Verify GitHub enforcement after retargeting.
- Produce controlled and reproducible evidence.

No production or third-party repositories are tested.
