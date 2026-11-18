# Geekbench AI — Laptop Performance Analysis

University group project comparing **image-classification AI inference performance across three laptops** using Geekbench AI with the ONNX framework.

## Objective
Compare single-precision (SP), half-precision (HP), and quantized (Q) benchmark scores and discuss how processor generation, number of cores and memory affect inference performance.

## Summary of reported scores
| CPU | SP | HP | Quantized |
|---|---:|---:|---:|
| Intel Core i3-3120M | 311 | 193 | 282 |
| Intel Core i7-8565U | 689 | 376 | 1178 |
| Intel Core i5-13420H | 1490 | 791 | 2823 |

**Finding:** The Intel Core i5-13420H laptop achieved the highest scores of the tested devices. Its image-classification quantized workload reached 492.7 inferences per second (IPS) in the project report.

## Repository content
- `benchmark_summary.csv` — scores transcribed from the university project report
- `README.md` — overview of the experiment, approach, and findings

This repository contains **analysis and results, not a trained AI model or AI application source code**. The source report and benchmarking methodology should be attached only after removing personal student IDs and confirming team permission.
