### AWS Sig v4 authorization example

#### Install

```bash
$ pip install -r requirements.txt
```

#### Usage

Invoice prediction:

```bash
$ python src/main.py https://xxx.api.lucidtech.ai/v1 <api_key> <access_key_id> <secret_access_key> invoice_prediction invoice.pdf application/pdf
```

Document split:

```bash
$ python src/main.py https://xxx.api.lucidtech.ai/v1 <api_key> <access_key_id> <secret_access_key> document_split document.pdf application/pdf
```
