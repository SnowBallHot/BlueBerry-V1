# poker44-signal-detector

Poker44 (SN126) bot-detection miner. Scores 100-hand chunks with an aggregate
signal model over sanitized behavioral statistics.

## Run
```
pip install -e .
python neurons/miner.py --netuid 126 --wallet.name <coldkey> --wallet.hotkey <hotkey>
```

Model weights ship in `models/current.joblib`; integrity fields are published
in `model_manifest.json`.
