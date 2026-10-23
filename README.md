# gtm-image-mirror

Copies Google's server-side tagging image (`gcr.io/cloud-tagging-10302018/gtm-cloud-image:stable`)
to `ghcr.io/mobinamindm/gtm-cloud-image`, because gcr.io answers 403 to the Tehran Dokploy host.
Runs weekly and on demand (Actions -> mirror-gtm-image -> Run workflow).
