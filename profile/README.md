# nonagenticai

Open tools for running AI on hardware you own.

We build in the open where it is useful: an MLX inference server for Apple Silicon, an
organisational operating model for autonomous work, n8n community nodes for the services we
run, and the storage and analysis plumbing underneath them. The rest of the estate is
internal; what is here is meant to be read, run and contributed to.

## What we maintain

| Project | What it is |
|---|---|
| [mlx_inference](https://github.com/nonagenticai/mlx_inference) | OpenAI- and Anthropic-compatible inference server for Apple Silicon, built on MLX |
| [conveyor](https://github.com/nonagenticai/conveyor) | The organisational operating model for autonomous work — [design site](https://nonagentic.ai/design/) |
| [fr](https://github.com/nonagenticai/fr) | Control plane and communication hub for an autonomous-agent workflow system (Bun + SvelteKit) |
| [portoser](https://github.com/nonagenticai/portoser) | Declarative service registry, web UI and MCP server for Docker across heterogeneous hosts |
| [artifact_service](https://github.com/nonagenticai/artifact_service) · [storage_service](https://github.com/nonagenticai/storage_service) | Multi-tenant artifact and object-storage services (FastAPI + PostgreSQL + MinIO) |
| [n8n nodes](https://github.com/nonagenticai?q=n8n-nodes&type=all) | Community nodes for Planka, Keycloak, Prometheus/Loki/Grafana, n8n workflows and artifact storage |
| [coding-ai](https://github.com/nonagenticai/coding-ai) · [coding-client](https://github.com/nonagenticai/coding-client) · [coding-realtime](https://github.com/nonagenticai/coding-realtime) | Analysis and test-intelligence services for the coding platform |

## How we work

- **Apache-2.0** unless a dependency forces otherwise; the licence is in each repository.
- **CI runs on GitHub-hosted runners**, with no repository secrets. If a check is red, it is
  reported, not worked around.
- **Security reports go through GitHub's private advisory flow**, never a public issue — see
  [`SECURITY.md`](SECURITY.md).
- **Contributions** start with an issue for anything large, carry DCO sign-off, and arrive as
  one concern per pull request — see [`CONTRIBUTING.md`](CONTRIBUTING.md).

## A note on forks

This organisation carries forks of other projects for its own deployment use. A fork is not
the upstream project and is not its support channel: report bugs and vulnerabilities to the
upstream repository.
