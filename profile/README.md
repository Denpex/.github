# Denpex: GPU, CUDA, PyTorch & NCCL Failure Diagnostics

[Denpex](https://denpex.com) helps engineering teams investigate GPU training, fine-tuning, and inference failures across PyTorch, CUDA, NCCL, NVIDIA Xid hardware faults, Slurm, Kubernetes, DeepSpeed, and vLLM workloads.

* **Instant Web Console:** [denpex.com/console](https://denpex.com/console)
* **VS Code Extension:** [denpex.com/vscode](https://denpex.com/vscode)
* **Open VSX Extension (Cursor, Windsurf, VSCodium):** [denpex.com/openvsx](https://denpex.com/openvsx)
* **Python Agent & CLI (`pip install denpex`):** [denpex.com/docs/agent](https://denpex.com/docs/agent)
* **MCP Server (`npx -y denpex-mcp`):** [denpex.com/docs/integrations](https://denpex.com/docs/integrations)
* **GitHub Action (`Denpex/denpex-action`):** [denpex.com/docs/ci](https://denpex.com/docs/ci)

---

## Official Denpex Ecosystem & Documentation

| Resource | Description | Link |
| :--- | :--- | :--- |
| **Denpex Platform** | Deterministic GPU and ML training failure diagnostics | [denpex.com](https://denpex.com) |
| **Documentation Hub** | Quickstart guides, architecture, and operational reference | [denpex.com/docs](https://denpex.com/docs) |
| **Quickstart Guide** | Get your first local or cloud diagnosis in under 60 seconds | [denpex.com/docs/quickstart](https://denpex.com/docs/quickstart) |
| **Python Agent & CLI** | On-host monitoring, evidence capture, and zero-egress CLI | [denpex.com/docs/agent](https://denpex.com/docs/agent) |
| **REST API Reference** | Programmatic `/api/diagnose` and preflight endpoints | [denpex.com/docs/api](https://denpex.com/docs/api) |
| **CI & GitHub Action** | Automated preflight gates and CI crash diagnosis | [denpex.com/docs/ci](https://denpex.com/docs/ci) |
| **VS Code Extension** | Offline GPU crash diagnostics in VS Code | [denpex.com/vscode](https://denpex.com/vscode) |
| **Open VSX Extension** | Extension for Cursor, Windsurf, VSCodium, and Gitpod | [denpex.com/openvsx](https://denpex.com/openvsx) |
| **Failure Encyclopedia** | 500+ documented CUDA, NCCL, Xid, Slurm, and vLLM failures | [denpex.com/failures](https://denpex.com/failures) |
| **Free GPU Tools** | VRAM, NCCL, DeepSpeed ZeRO, and Slurm calculators | [denpex.com/tools](https://denpex.com/tools) |
| **NVIDIA Xid Reference** | Hardware vs software Xid fault routing table | [denpex.com/xid](https://denpex.com/xid) |
| **NCCL Error Guide** | Collective timeout and first-failed-rank triage | [denpex.com/nccl-errors](https://denpex.com/nccl-errors) |
| **CUDA Error Guide** | CUDA out-of-memory and device-side assert triage | [denpex.com/cuda-errors](https://denpex.com/cuda-errors) |
| **vLLM Error Guide** | KV-cache exhaustion and inference worker failure triage | [denpex.com/vllm-errors](https://denpex.com/vllm-errors) |
| **Slurm GPU Error Guide** | Slurm step cancellation, cgroup, and prolog/epilog triage | [denpex.com/slurm-gpu-errors](https://denpex.com/slurm-gpu-errors) |
| **Release Changelog** | Platform, agent, SDK, and extension release notes | [denpex.com/changelog](https://denpex.com/changelog) |

---

## Official Packages & Registries

| Package | Registry | Install Command | Source & Docs |
| :--- | :--- | :--- | :--- |
| **`denpex`** | [PyPI](https://pypi.org/project/denpex/) | `pip install denpex` | [denpex.com/docs/agent](https://denpex.com/docs/agent) |
| **`denpex-sdk`** | [PyPI](https://pypi.org/project/denpex-sdk/) | `pip install denpex-sdk` | [denpex.com/docs/integrations](https://denpex.com/docs/integrations) |
| **`denpex-mcp`** | [npm](https://www.npmjs.com/package/denpex-mcp) | `npx -y denpex-mcp` | [denpex.com/docs/integrations](https://denpex.com/docs/integrations) |
| **`@denpex/sdk`** | [npm](https://www.npmjs.com/package/@denpex/sdk) | `npm install @denpex/sdk` | [denpex.com/docs/integrations](https://denpex.com/docs/integrations) |
| **`denpex.denpex-diagnostics`** | [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=denpex.denpex-diagnostics) | `code --install-extension denpex.denpex-diagnostics` | [denpex.com/vscode](https://denpex.com/vscode) |
| **`denpex/denpex-diagnostics`** | [Open VSX Registry](https://open-vsx.org/extension/denpex/denpex-diagnostics) | `ovsx get denpex.denpex-diagnostics` | [denpex.com/openvsx](https://denpex.com/openvsx) |
| **`Denpex/denpex-action`** | [GitHub Marketplace](https://github.com/Denpex/denpex-action) | `uses: Denpex/denpex-action@main` | [denpex.com/docs/ci](https://denpex.com/docs/ci) |
| **`Denpex/gpu-failure-cheatsheet`** | [GitHub](https://github.com/Denpex/gpu-failure-cheatsheet) | `node triage.mjs training.log` | [denpex.com/failures](https://denpex.com/failures) |

