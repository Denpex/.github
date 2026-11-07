# Denpex

Deterministic GPU failure diagnostics for distributed training and inference workloads: CUDA out-of-memory, PyTorch crashes, NCCL collective timeouts, NVIDIA Xid hardware faults, Slurm, and vLLM.

* **Website:** [https://denpex.com](https://denpex.com)
* **Failure Encyclopedia:** [https://denpex.com/failures](https://denpex.com/failures)
* **VS Code Marketplace:** [denpex.denpex-diagnostics](https://marketplace.visualstudio.com/items?itemName=denpex.denpex-diagnostics)
* **Open VSX Registry:** [denpex/denpex-diagnostics](https://open-vsx.org/extension/denpex/denpex-diagnostics)

## Public Repositories

* **[Denpex/denpex-vscode](https://github.com/Denpex/denpex-vscode)**: Offline-capable VS Code and Cursor extension for diagnosing GPU, CUDA, PyTorch, NCCL, Xid, Slurm, and vLLM crashes directly inside your editor.
* **[Denpex/denpex-action](https://github.com/Denpex/denpex-action)**: GitHub Action (`uses: Denpex/denpex-action@main`) and Kubernetes DaemonSet for automated CI/CD preflight checks and crash diagnosis.
* **[Denpex/gpu-failure-cheatsheet](https://github.com/Denpex/gpu-failure-cheatsheet)**: Zero-dependency CLI (`triage.mjs`) and field reference matching GPU crash logs against 471 verified failure signatures and NVIDIA Xid codes.