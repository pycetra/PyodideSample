# PyodideSample

## 動作確認時の環境

- macOS
- python3.9

## 実行

```
python3 -m venv py39
source py39/bin/activate
pip install --upgrade pip
pip install wheel

pip list > requirements.txt
python --version > python_version.txt
python setup.py bdist_wheel


curl -OL https://github.com/pyodide/pyodide/releases/download/0.20.0a1/pyodide-build-0.20.0a1.tar.bz2
tar -jxvf pyodide-build-0.20.0a1.tar.bz2

python -m http.server 5000
```
