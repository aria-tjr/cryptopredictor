# CryptoPredictor

> 🚧 **Work in progress — no prediction or signal code yet.** The repository currently holds the BeeWare/Briefcase app scaffold: `src/cryptopredictor/app.py` opens an empty window, and `tests/test_app.py` is a placeholder test. The features below describe the planned app, not what is implemented.

A cross-platform desktop application that analyzes cryptocurrency markets with ML models and surfaces investment signals. Built with **BeeWare / Briefcase** — the same Python codebase runs natively on macOS, Linux, Windows, Android, and iOS.

## Planned features

- **Cross-platform native builds** — single codebase for desktop and mobile via Briefcase
- **ML-driven signals** — price prediction and investment-grade signal scoring
- **Modular architecture** — clean separation of data, models, UI, and signal logic
- **Tested** — pytest suite (currently a placeholder test only)

## Project Layout

```
cryptopredictor/
├── src/cryptopredictor/    # application source
├── tests/                  # pytest suite
├── pyproject.toml          # Briefcase + packaging config
├── CHANGELOG
└── LICENSE
```

## Development

```bash
pip install briefcase
briefcase dev
```

Build a native installer for your OS:

```bash
briefcase create
briefcase build
briefcase package
```

Run the test suite:

```bash
pip install pytest
pytest
```

## Status

Active development. Core scaffolding (Briefcase 0.3.22), test harness, and packaging pipeline are in place. UI, signal engine, and ML model integration are the active work streams.

## License

MIT — see [LICENSE](LICENSE).

## Disclaimer

This software is provided for educational and research purposes only. Signals or selections produced by this application are **not financial advice**. Trading cryptocurrencies carries substantial risk of loss. Use at your own risk.
