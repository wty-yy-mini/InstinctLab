
启动LAFAN1训练

```bash
CUDA_VISIBLE_DEVICES=1 python scripts/instinct_rl/train.py \
  --task=Instinct-BeyondMimic-Plane-G1-v0 \
  --headless \
  --num_envs=4096 \
  --run_name=lafan1_g1
```