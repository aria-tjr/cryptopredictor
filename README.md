# cryptopredictor

A cross-platform desktop application that selects a cryptocurrency to consider for investment and surfaces a signal for it. Built with [BeeWare / Briefcase](https://beeware.org/) so the same codebase runs on macOS, Linux, Windows, Android, and iOS.

## Status

Early-stage scaffold generated with Briefcase 0.3.22. The UI, signal logic, and model integration are under development.

## Project layout

```
cryptopredictor/
├── src/cryptopredictor/   # application source
├── tests/                 # pytest suite
├── pyproject.toml         # Briefcase + packaging config
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

Run tests:

```bash
pip install pytest
pytest
```

## License

MIT — see [LICENSE](LICENSE).

## Disclaimer

This software is provided for educational and research purposes only. Any signals or selections produced by this application are **not** financial advice. Trading cryptocurrencies carries substantial risk of loss. Use at your own risk.
