# HistInsights

A lightweight CLI for assessing historical source reliability from a local text corpus.

Repository: https://github.com/ethancarter-ai/histinsights

## Install

```bash
python3 -m pip install .
```

## Usage

```bash
histinsights --source-dir ./corpus
```

Run `histinsights --help` for all options.

## Project structure

```
histinsights/
  src/histinsights/
    __init__.py
    __main__.py
    cli.py
  corpus/
    ancient.txt
    modern.txt
  tests/
    test_cli.py
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
