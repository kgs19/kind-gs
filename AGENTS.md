# Project guidance

- KGS19 beginner-friendly Kind tutorial; keep examples minimal and commands explicit.
- Preserve the three-tab editable diagram and use relative PNG paths in Markdown.
- Keep ports 8080 (host), 30080 (NodePort and Kind container port), 8040 (Service), and 8020 (application and targetPort) aligned across YAML, README, transcript and diagrams.
- Treat reference IPs as examples, not fixed cluster settings. Do not add IPv6, per-node Pod CIDRs or networking implementation internals to the first episode.
- Keep README standalone and transcript chronological. Use official documentation links.
- Validate manifests and links; ask before deleting a cluster or pushing changes. Do not claim runtime tests that were not performed.
