FreqShow
========

RTL-SDR frequency scanning and display tool

Install
=======

On Kali Rolling :

```bash
apt-get install \
  python-pip\
  python-virtualenv \
  python-pygame

virtualenv -p python2.7 --system-site-packages --prompt='(SDR) ' venv
source venv/bin/activate
git clone https://github.com/roger-/pyrtlsdr.git
cd pyrtlsdr
git checkout v0.2.3
pip install .
```
