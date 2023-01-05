#CONSOLE DEPLOYMENT TO AWS ENV
cd /layers/requests
```
pip install -t python/lib/python3.9/site-packages -r aws_requirements.txt 
```

Deploy:

```sls deploy --aws-profile user-personal --region eu-central-1 --stage dev --verbose```

Remove:  

```sls remove --aws-profile user-personal --region eu-central-1 --stage dev --verbose```


