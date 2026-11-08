# ArchiveInspector

Inspect ZIP and TAR archives without extracting them, including size totals, extension stats, and path-safety warnings.

Version: **1.0.0**

## Installation

```bash
git clone https://github.com/bafnayeygian/ArchiveInspector.git
cd ArchiveInspector
python -m pip install .
```

## Usage

```bash
archive-inspector --help
```

## Development

```bash
python -m unittest discover -s tests -v
python -m compileall -q src
```

## License

MIT License.
