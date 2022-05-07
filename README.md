# `slocncdu`

`slocncdu` generates `ncdu`-compatible reports, but uses SLOC count instead of file size.

## Usage

```
apt-get install -y ncdu
pip install --user pygount
PATH="$PATH:$PWD"
cd $MYPROJECT
slocncdu $(git ls-files) | ncdu -f-
```
