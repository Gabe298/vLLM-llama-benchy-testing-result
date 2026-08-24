# Tool-Eval Commands

PrismaScout AQUA:

```bash
cd /home/Benchmark_Tool/tool-eval-bench && source .venv/bin/activate && set -a && source /home/vllm/.env && set +a && set -o pipefail && tool-eval-bench run --base-url "http://localhost:7380/v1" --api-key "$VLLM_API_KEY" --backend vllm --model "Qwen3.8-27B" --seed 42 --trials 3 --temperature 0.0 --parallel 1 --reference-date 2026-03-20 --hardmode --no-live --output-dir "/home/vllm/benchmark-results/2026-08-24-qwen3.8-tool-eval-bench/rdtand-prismascout-aqua" 2>&1 | tee "/home/vllm/benchmark-results/2026-08-24-qwen3.8-tool-eval-bench/rdtand-prismascout-aqua/tool-eval-bench.log"
```

Gorbatjovy Heretic INT4A16 AutoRound:

```bash
cd /home/Benchmark_Tool/tool-eval-bench && source .venv/bin/activate && set -a && source /home/vllm/.env && set +a && set -o pipefail && tool-eval-bench run --base-url "http://localhost:7380/v1" --api-key "$VLLM_API_KEY" --backend vllm --model "Qwen3.8-27B" --seed 42 --trials 3 --temperature 0.0 --parallel 1 --reference-date 2026-03-20 --hardmode --no-live --output-dir "/home/vllm/benchmark-results/2026-08-24-qwen3.8-tool-eval-bench/gorbatjovy-heretic-int4a16-autoround" 2>&1 | tee "/home/vllm/benchmark-results/2026-08-24-qwen3.8-tool-eval-bench/gorbatjovy-heretic-int4a16-autoround/tool-eval-bench.log"
```

CloudNathan5 NVFP4A16 AWQ Nightly Retest:

```bash
cd /home/Benchmark_Tool/tool-eval-bench && source .venv/bin/activate && set -a && source /home/vllm/.env && set +a && set -o pipefail && tool-eval-bench run --base-url "http://localhost:7380/v1" --api-key "$VLLM_API_KEY" --backend vllm --model "Qwen3.8-27B" --seed 42 --trials 3 --temperature 0.0 --parallel 1 --reference-date 2026-03-20 --hardmode --no-live --output-dir "/home/vllm/benchmark-results/2026-08-24-qwen3.8-tool-eval-bench/cloudnathan5-nvfp4a16-awq-nightly" 2>&1 | tee "/home/vllm/benchmark-results/2026-08-24-qwen3.8-tool-eval-bench/cloudnathan5-nvfp4a16-awq-nightly/tool-eval-bench.log"
```

Trithemius PrismaAura Code Fusion GAIN:

```bash
cd /home/Benchmark_Tool/tool-eval-bench && source .venv/bin/activate && set -a && source /home/vllm/.env && set +a && set -o pipefail && tool-eval-bench run --base-url "http://localhost:7380/v1" --api-key "$VLLM_API_KEY" --backend vllm --model "Qwen3.8-27B" --seed 42 --trials 3 --temperature 0.0 --parallel 1 --reference-date 2026-03-20 --hardmode --no-live --output-dir "/home/vllm/benchmark-results/2026-08-24-qwen3.8-tool-eval-bench/trithemius-prismaura-code-fusion-gain" 2>&1 | tee "/home/vllm/benchmark-results/2026-08-24-qwen3.8-tool-eval-bench/trithemius-prismaura-code-fusion-gain/tool-eval-bench.log"
```
