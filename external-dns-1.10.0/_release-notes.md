### Added

- Added `commonLabels` value to allow the addition of labels to all resources. [@stevehipwell](https://github.com/stevehipwell)
- Added support for [Process Namespace Sharing](https://kubernetes.io/docs/tasks/configure-pod-container/share-process-namespace/) via the `shareProcessNamespace`
 value. ([#2715](https://github.com/kubernetes-sigs/external-dns/pull/2715)) [@wolffberg](https://github.com/wolffberg)

### Changed

- Update _ExternalDNS_ version to [v0.12.0](https://github.com/kubernetes-sigs/external-dns/releases/tag/v0.12.0). [@vojtechmares](https://github.com/vojtechmares)
- Set resource namespaces to `{{ .Release.Namespace }}` in the templates instead of waiting until apply time for inference. [@stevehipwell](https://github.com/stevehipwell)
- Fixed `rbac.additionalPermissions` default value.([#2796](https://github.com/kubernetes-sigs/external-dns/pull/2796)) [@tamalsaha](https://github.com/tamalsaha)
