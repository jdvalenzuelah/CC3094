# Labs CC3094

## Usage

Each lab uses its own virtualenv and comes with a different requirements.txt

Go to lab
```
$ cd labs/lab01
```

Create and activate virtualenv
```sh
$ virtualenv venv
$ source venv/bin/activate
```

Install requirements
```
pip install -r requirements.txt
```

Add virtualenv kernel to ipython
```
python -m ipykernel install --user --name=lab01
```

To remove kernel
```
jupyter kernelspec uninstall lab01
```