# Mimic

启动LAFAN1训练

```bash
CUDA_VISIBLE_DEVICES=0 python scripts/instinct_rl/train.py \
  --task=Instinct-BeyondMimic-Plane-G1-v0 \
  --headless \
  --num_envs=4096 \
  --run_name=lafan1_g1
```

```bash
CUDA_VISIBLE_DEVICES=0 python scripts/instinct_rl/play.py \
  --task=Instinct-BeyondMimic-Plane-G1-Play-v0 \
  --num_envs=4 \
  --load_run=20260608_145134_G1BeyondMimic_linVelObs_LAFAN1G1_GmrMotion_lafan1_g1 \
  --checkpoint=model_30000.pt
```
