# err-matrix

### install
errbot server in /opt/
```
mkdir -p /opt/backend
cd /opt/backend
git clone https://github.com/nineaiyu/err-matrix.git
pip install matrix-client
```

### setting

vim config.py
```
BACKEND = 'Matrix'  # Errbot will start in text mode (console onLy mode) and will answer commands from there.
BOT_IDENTITY ={
        'token':'MDAxN2xvY2F0aW9uIG1heGpveS5jYwowMDEzaWRlbnRpZmllciBrZXkKMDAxMGNpZCBnZW4gPSAxCjAwMzJjaWQgdXNlcl9pZCA9IEBxb3lybHBlY3dzbmZobWRnYnR6dTptYXhqb3kuY2MKMDAxNmNpZCB0eXBlID0gYWNjZXNzCjAwMjFjaWQgbm9uY2UgPSBGWTJhdVByUHBBVmZGczNNCjAwMmZzaWduYXR1cmUgBqqb1w7uoBD2p3xo8yX3HXKAKivp3pMzQFpIZqNHZLsK',
        'url':'https://maxjoy.cc',
        'user':'@qoyrlpecwsnfhmdgbtzu:maxjoy.cc'
        }

BOT_EXTRA_BACKEND_DIR=r'/opt/backend'
```

