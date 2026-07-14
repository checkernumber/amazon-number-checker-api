# Python example

```bash
pip install requests
export CHECKNUMBER_API_KEY="YOUR_API_KEY"
python amazon_checker.py   # reads numbers.txt (one E.164 number per line)
```

Submits `numbers.txt` to `POST /v1/tasks` (`task_type=amazon`), polls `POST /v1/gettasks`, and downloads the result file. Full docs: https://docs.checknumber.ai/amazon-bulk-number-checker
