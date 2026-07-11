| model                                             |             test |              t/s |     peak t/s |          ttfr (ms) |       est_ppt (ms) |      e2e_ttft (ms) |
|:--------------------------------------------------|-----------------:|-----------------:|-------------:|-------------------:|-------------------:|-------------------:|
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm |           pp2048 | 5856.51 ± 717.09 |              |     463.07 ± 47.30 |     355.65 ± 47.30 |     463.07 ± 47.30 |
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm |            tg480 |     75.13 ± 2.16 | 92.33 ± 2.05 |                    |                    |                    |
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm |   pp2048 @ d1000 | 6657.31 ± 235.17 |              |     565.99 ± 16.34 |     458.57 ± 16.34 |     565.99 ± 16.34 |
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm |    tg480 @ d1000 |     72.04 ± 7.78 | 88.67 ± 5.91 |                    |                    |                    |
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm |   pp2048 @ d5000 | 6241.79 ± 108.18 |              |    1237.18 ± 19.42 |    1129.77 ± 19.42 |    1237.18 ± 19.42 |
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm |    tg480 @ d5000 |     70.70 ± 1.92 | 88.33 ± 2.62 |                    |                    |                    |
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm |  pp2048 @ d10000 | 5324.02 ± 168.79 |              |    2372.81 ± 71.23 |    2265.40 ± 71.23 |    2372.81 ± 71.23 |
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm |   tg480 @ d10000 |     71.88 ± 4.87 | 87.33 ± 1.25 |                    |                    |                    |
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm |  pp2048 @ d20000 |  4831.87 ± 20.01 |              |    4670.67 ± 18.94 |    4563.26 ± 18.94 |    4671.97 ± 18.87 |
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm |   tg480 @ d20000 |     68.59 ± 3.03 | 86.67 ± 3.30 |                    |                    |                    |
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm |  pp2048 @ d50000 |   3541.51 ± 2.18 |              |    14804.18 ± 9.14 |    14696.76 ± 9.14 |    14806.50 ± 9.23 |
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm |   tg480 @ d50000 |     69.34 ± 2.55 | 84.00 ± 5.72 |                    |                    |                    |
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm | pp2048 @ d100000 |   2460.18 ± 0.29 |              |    41587.44 ± 4.82 |    41480.03 ± 4.82 |    41591.90 ± 5.14 |
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm |  tg480 @ d100000 |     63.53 ± 4.67 | 79.67 ± 3.68 |                    |                    |                    |
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm | pp2048 @ d150000 |   1883.43 ± 0.66 |              |   80837.23 ± 28.22 |   80729.81 ± 28.22 |   80845.53 ± 29.14 |
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm |  tg480 @ d150000 |     63.47 ± 2.92 | 78.67 ± 3.30 |                    |                    |                    |
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm | pp2048 @ d200000 |   1525.83 ± 0.26 |              |  132525.85 ± 22.57 |  132418.43 ± 22.57 |  132535.59 ± 23.55 |
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm |  tg480 @ d200000 |     61.81 ± 1.34 | 74.00 ± 1.41 |                    |                    |                    |
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm | pp2048 @ d210000 |   1469.93 ± 1.33 |              | 144365.98 ± 130.60 | 144258.56 ± 130.60 | 144372.64 ± 135.28 |
| Qwen3.6-27B-PrismaSCOUT-Blackwell-NVFP4-BF16-vllm |  tg480 @ d210000 |     56.70 ± 2.40 | 74.67 ± 1.70 |                    |                    |                    |