# K8s-introduction

Application for educational purposes. As a result application needs to be containerised, kubernetised and then helmitised. 

## Set-up environment

```shell
python3 -m venv .venv
. .venv/bin/activate
pip install -r requirements.txt
```

## Test if it works

```shell
. .venv/bin/activate

python3 cli.py
Hello world from CLI

flask run
curl localhost:5000
Hello, World!
```
