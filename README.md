# FetchUnread
What is it: Python script for fetching number of unread emails from gmail

### How to run:
1. Follow instructions at [here](https://developers.google.com/gmail/api/quickstart/python) for gmail credentials
2. Generate credentials.json
3. Run `python3 app.py` on Terminal
4. Console will show number of unread messages

### Troubleshooting
* If ModuleNotFoundError: No module named 'googleapiclient.discovery' 
```
pip3 install --upgrade google-api-python-client google-auth-httplib2 google-auth-oauthlib --user
```

