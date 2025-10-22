# maxpower-frontend-config

Argo CD configuration repo for the public-facing MaxPower site.

Pattern:
- `base/` – namespace, deployment, service
- `overlays/dev/` – image tag patch

No direct DB connectivity; consumes backend APIs. Add ConfigMap/Secret later for API base URLs.