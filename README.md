```python
pkg update && pkg upgrade
pkg install python
pkg install wget
pkg install git
```
```python
cd $HOME
rm -rf empas-v2
git clone https://github.com/Xenz-11/empas-v2
cd empas-v2
python -m pip install requirements.txt
python empas.py
