# MedCare POS - Auto-Update Feed

This repository publishes **release installers only**. It contains no source code.

Installed MedCare POS applications check here periodically for new versions by
fetching `latest.yml` anonymously. Updates are downloaded and installed only
after the user confirms them in-app; the application works fully offline if
this repository is unreachable.

## Verifying a download

Each release lists a SHA-512 hash. The in-app updater verifies the downloaded
installer against it before installing.

## Reporting issues

Please do not open issues in this repository. For support, contact
RapidAi Services & Solutions.
