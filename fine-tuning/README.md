# Testing Results

## Clusters (1 GPU per Machine)

| VM-Type       | Machines | Approx Time (hours) | Ratio | Cost/hr | Total Cost |
|---------------|----------|---------------------|-------|---------|------------|
| g2-standard-4 | 1        | 141                 | 100%  | $0.84   | $118       |
| g2-standard-4 | 2        | 96                  | 73%   | $1.55   | $149       |
| g2-standard-4 | 4        | 52                  | 68%   | $2.95   | $153       |
| g2-standard-4 | 8        | 27                  | 65%   | $5.79   | $156       |
| g2-standard-4 | 16       | 14.5                | 61%   | $11.44  | $166       |
| g2-standard-4 | 32       | 7.5                 | 59%   | $22.75  | $171       |

## Single Machines

| VM-type        | GPUs | Approx Time (hours) | Ratio  | Cost/hr | Total Cost |
|----------------|------|---------------------|--------|---------|------------|
| g2-standard-4  | 1    | 141                 | 100%   | $0.84   | $118       |
| g2-standard-8  | 1    | 140                 | 101%   | $0.99   | $139       |
| g2-standard-12 | 1    | 137                 | 103%   | $1.13   | $155       |
| g2-standard-24 | 2    | 72                  | 98%    | $2.13   | $153       |
| g2-standard-48 | 4    | ERROR               |        | $4.13   |            |
| g2-standard-96 | 8    | ERROR               |        | $8.14   |            |