seqrepo was renamed to biocommons.seqrepo.  This package provides a
placeholder to the new name package.  It does not provide any
functionality under the seqrepo name.

Steps:

```
pyvenv venv
source venv/bin/activate
pip install wheel
python setup.py sdist bdist_egg bdist_wheel upload
```

