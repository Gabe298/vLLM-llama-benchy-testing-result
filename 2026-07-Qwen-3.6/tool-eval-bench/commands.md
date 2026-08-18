# Tool Evaluation Benchmark Commands

## Lorbus

```bash
cd /home/Benchmark_Tool/tool-eval-bench && source .venv/bin/activate && set -o pipefail && tool-eval-bench --base-url "http://localhost:7380/v1" --backend vllm --model "Qwen3.6-27B-int4-AutoRound" --seed 42 --trials 3 --temperature 0.0 --parallel 1 --reference-date 2026-03-20 --no-live --output-dir "/home/vllm/benchmark-results/2026-07-10-tool-eval-bench/lorbus-qwen3.6" 2>&1 | tee "/home/vllm/benchmark-results/2026-07-10-tool-eval-bench/lorbus-qwen3.6/tool-eval-bench.log"
```

## PrismaAURA

```bash
cd /home/Benchmark_Tool/tool-eval-bench && source .venv/bin/activate && set -o pipefail && tool-eval-bench --base-url "http://localhost:7380/v1" --backend vllm --model "Qwen3.6-27B-PrismaAURA-5.5bit-vllm" --seed 42 --trials 3 --temperature 0.0 --parallel 1 --reference-date 2026-03-20 --no-live --output-dir "/home/vllm/benchmark-results/2026-07-10-tool-eval-bench/rdtand-prismaaura" 2>&1 | tee "/home/vllm/benchmark-results/2026-07-10-tool-eval-bench/rdtand-prismaaura/tool-eval-bench.log"
```

## Sakamakismile

```bash
cd /home/Benchmark_Tool/tool-eval-bench && source .venv/bin/activate && set -o pipefail && tool-eval-bench --base-url "http://localhost:7380/v1" --backend vllm --model "Huihui-Qwen3.6-27B-abliterated-NVFP4-MTP" --seed 42 --trials 3 --temperature 0.0 --parallel 1 --reference-date 2026-03-20 --no-live --output-dir "/home/vllm/benchmark-results/2026-07-10-tool-eval-bench/sakamakismile-qwen3.6" 2>&1 | tee "/home/vllm/benchmark-results/2026-07-10-tool-eval-bench/sakamakismile-qwen3.6/tool-eval-bench.log"
```

## PrismaSCOUT

```bash
cd /home/Benchmark_Tool/tool-eval-bench && source .venv/bin/activate && set -o pipefail && tool-eval-bench --base-url "http://localhost:7380/v1" --backend vllm --model "Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm" --seed 42 --trials 3 --temperature 0.0 --parallel 1 --reference-date 2026-03-20 --no-live --output-dir "/home/vllm/benchmark-results/2026-07-10-tool-eval-bench/rdtand-prismascout" 2>&1 | tee "/home/vllm/benchmark-results/2026-07-10-tool-eval-bench/rdtand-prismascout/tool-eval-bench.log"
```
