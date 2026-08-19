```bash
cd /home/Benchmark_Tool/tool-eval-bench && source .venv/bin/activate && set -a && source /home/vllm/.env && set +a && set -o pipefail && tool-eval-bench run --base-url "http://localhost:7380/v1" --api-key "$VLLM_API_KEY" --backend vllm --model "Qwen3.8-27B-ARA-abliterated-NVFP4" --seed 42 --trials 3 --temperature 0.0 --parallel 1 --reference-date 2026-03-20 --hardmode --no-live --output-dir "/home/vllm/benchmark-results/2026-08-15-qwen3.8-tool-eval-bench/aday777-ara-abliterated-nvfp4" 2>&1 | tee "/home/vllm/benchmark-results/2026-08-15-qwen3.8-tool-eval-bench/aday777-ara-abliterated-nvfp4/tool-eval-bench.log"
```

```bash
cd /home/Benchmark_Tool/tool-eval-bench && source .venv/bin/activate && set -a && source /home/vllm/.env && set +a && set -o pipefail && tool-eval-bench run --base-url "http://localhost:7380/v1" --api-key "$VLLM_API_KEY" --backend vllm --model "Qwen3.8-27B-NVFP4a16-AWQ" --seed 42 --trials 3 --temperature 0.0 --parallel 1 --reference-date 2026-03-20 --hardmode --no-live --output-dir "/home/vllm/benchmark-results/2026-08-15-qwen3.8-tool-eval-bench/cloudnathan5-nvfp4a16-awq" 2>&1 | tee "/home/vllm/benchmark-results/2026-08-15-qwen3.8-tool-eval-bench/cloudnathan5-nvfp4a16-awq/tool-eval-bench.log"
```

```bash
cd /home/Benchmark_Tool/tool-eval-bench && source .venv/bin/activate && set -a && source /home/vllm/.env && set +a && set -o pipefail && tool-eval-bench run --base-url "http://localhost:7380/v1" --api-key "$VLLM_API_KEY" --backend vllm --model "Qwen3.8-27B-int4a16-autoround" --seed 42 --trials 3 --temperature 0.0 --parallel 1 --reference-date 2026-03-20 --hardmode --no-live --output-dir "/home/vllm/benchmark-results/2026-08-15-qwen3.8-tool-eval-bench/dbirks-int4a16-autoround" 2>&1 | tee "/home/vllm/benchmark-results/2026-08-15-qwen3.8-tool-eval-bench/dbirks-int4a16-autoround/tool-eval-bench.log"
```

```bash
cd /home/Benchmark_Tool/tool-eval-bench && source .venv/bin/activate && set -a && source /home/vllm/.env && set +a && set -o pipefail && tool-eval-bench run --base-url "http://localhost:7380/v1" --api-key "$VLLM_API_KEY" --backend vllm --model "Qwen3.8-27B-nvfp4a4-autoround" --seed 42 --trials 3 --temperature 0.0 --parallel 1 --reference-date 2026-03-20 --hardmode --no-live --output-dir "/home/vllm/benchmark-results/2026-08-15-qwen3.8-tool-eval-bench/dbirks-nvfp4a4-autoround" 2>&1 | tee "/home/vllm/benchmark-results/2026-08-15-qwen3.8-tool-eval-bench/dbirks-nvfp4a4-autoround/tool-eval-bench.log"
```

```bash
cd /home/Benchmark_Tool/tool-eval-bench && source .venv/bin/activate && set -a && source /home/vllm/.env && set +a && set -o pipefail && tool-eval-bench run --base-url "http://localhost:7380/v1" --api-key "$VLLM_API_KEY" --backend vllm --model "Qwen3.8-27B-INT4A16-AWQ" --seed 42 --trials 3 --temperature 0.0 --parallel 1 --reference-date 2026-03-20 --hardmode --no-live --output-dir "/home/vllm/benchmark-results/2026-08-15-qwen3.8-tool-eval-bench/philbert440-int4a16-awq" 2>&1 | tee "/home/vllm/benchmark-results/2026-08-15-qwen3.8-tool-eval-bench/philbert440-int4a16-awq/tool-eval-bench.log"
```

```bash
cd /home/Benchmark_Tool/tool-eval-bench && source .venv/bin/activate && set -a && source /home/vllm/.env && set +a && set -o pipefail && tool-eval-bench run --base-url "http://localhost:7380/v1" --api-key "$VLLM_API_KEY" --backend vllm --model "Qwen3.8-27B-PrismaAQUA-5.5bit" --seed 42 --trials 3 --temperature 0.0 --parallel 1 --reference-date 2026-03-20 --hardmode --no-live --output-dir "/home/vllm/benchmark-results/2026-08-15-qwen3.8-tool-eval-bench/rdtand-prismaaqua-5.5bit" 2>&1 | tee "/home/vllm/benchmark-results/2026-08-15-qwen3.8-tool-eval-bench/rdtand-prismaaqua-5.5bit/tool-eval-bench.log"
```

```bash
cd /home/Benchmark_Tool/tool-eval-bench && source .venv/bin/activate && set -a && source /home/vllm/.env && set +a && set -o pipefail && tool-eval-bench run --base-url "http://localhost:7380/v1" --api-key "$VLLM_API_KEY" --backend vllm --model "Qwen3.8-27B-heretic-PrismaAura-5.5bit" --seed 42 --trials 3 --temperature 0.0 --parallel 1 --reference-date 2026-03-20 --hardmode --no-live --output-dir "/home/vllm/benchmark-results/2026-08-15-qwen3.8-tool-eval-bench/trithemius-heretic-prismaura-5.5bit" 2>&1 | tee "/home/vllm/benchmark-results/2026-08-15-qwen3.8-tool-eval-bench/trithemius-heretic-prismaura-5.5bit/tool-eval-bench.log"
```
