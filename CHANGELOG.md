# Changelog

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

---
## [3.10.0-bb.2] - 2023-09-29
### Added
- Update patch version of kubectl v1.27.6 -> v1.28.2

## [3.10.0-bb.1] - 2023-09-20
### Added
- Update patch version of kubectl v1.27.3 -> v1.27.6
- Update patch version of addon-resizer 1.8.18 -> 1.8.19 
- Update securityContext to include runAsGroup

## [3.10.0-bb.0]
### Added
- Update patch version of kubectl v1.26.4 -> v1.27.3
- Updated helm chart version and upstream changes.

## [3.9.0-bb.1]
### Added
- Update patch version of addon-resizer v1.8.14 -> 1.8.18
- Update patch version of kubectl v1.26.3 -> 1.26.4

## [3.9.0-bb.0]
### Added
- Updated helm chart version and upstream changes.
- Upgrade metrics server image 0.6.2 -> 0.6.3
- Update patch version of kubectl v1.26.2 -> 1.26.3

## [3.8.4-bb.0]
### Added
- Updated helm chart version. Upstream changes do not apply.

## [3.8.3-bb.2]
### Added
- Updated kubectl image to v1.26.1

## [3.8.3-bb.1]
### Added
- Updated kubectl image to v1.25.6

## [3.8.3-bb.0]
### Added
- Updated to upstream helm chart metrics-server-helm-chart-3.8.3
- Updated metrics-server images to 0.6.2
- Updated kubectl image to v1.25.5

## [3.8.0-bb.6]
### Added
- Updated kubectl image to v1.25.4

## [3.8.0-bb.5]
### Added
- Added bbtests structure and script tests

## [3.8.0-bb.4]
### Added
- Added default Istio `PeerAuthentication` for mTLS

## [3.8.0-bb.3]
### Added
- Added `renovate.json` to packge root for allowing renovate bot to create Issues/MR's for updates

## [3.8.0-bb.2]
### Changed
- Changed the values.yaml to use the Iron Bank metrics server image
- Added a test-values.yaml file for pipeline tests

## [3.8.0-bb.1]
### Added
- Added allow-svc-ingress.yaml for service-access

## [3.8.0-bb.0]
### Added
- Pointing to upstream helm chart 3.8.0
