# err-matrix

### install
errbot server in /data/errbot/
```
mkdir -p /data/errbot/backend
cd /data/errbot/backend

git clone --depth 1 -b dev --single-branch https://github.com/nineaiyu/err-matrix.git
```

```
git clone --depth 1 -b master --single-branch https://github.com/matrix-org/matrix-python-sdk.git
cd matrix-python-sdk
python setup.py install
cd ../
rm -rf  matrix-python-sdk
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

BOT_EXTRA_BACKEND_DIR=r'/data/errbot/backend'
```

