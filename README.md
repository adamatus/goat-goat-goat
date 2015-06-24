# Run unit-test with a watcher

## Install dependencies

The following assumes you are running python behind pyenv

```
pip install pytest pytext-xdist
pyenv rehash
```

## Run the tests (with a watcher)

We now use py.test as our test runner, rather than 'python manage.py test'

```
py.test -v -f [dir or test.py]
```

