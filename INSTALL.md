## Installation

### Installing utils3d

The `utils3d` package must be installed separately:

```bash
git clone https://github.com/EasternJournalist/utils3d.git /tmp/utils3d
cd /tmp/utils3d
git checkout b0c3701a116f13bc37c3a110586c7d9b66510cae
# Fix the package name in pyproject.toml
sed -i 's/name = "unknown"/name = "utils3d"/' pyproject.toml
pip install .
```

Or simply copy to site-packages:

```bash
cp -r utils3d /path/to/site-packages/
```
