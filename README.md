### データについて

target_path に対象画像データ, collected_path に取得時系列データのパスを入力.
UNet_ver2 が 3 層 Unet, UNetAdvanced_ver2 が 4 層 Unet

```python
study = optuna.create_study(direction="minimize")
study.optimize(objective, n_trials=1)
```

n_trials の数値の分だけ optuna が試行を行う。
