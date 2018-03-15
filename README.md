AWSCLI for docker
=================

***Usage***  
```
docker run --rm mibexx/awscli <command>
```

***Environments***  

| Variable | Description |
| -------- | ----------- |
| AWS_ACCESS_KEY_ID | AWS credential access key id |
| AWS_SECRET_ACCESS_KEY | AWS credential secret access key |

***Example***
```
docker run --rm -e AWS_ACCESS_KEY_ID=123456 -e AWS_SECRET_ACCESS_KEY=d2i3uobzr23 mibexx/awscli s3 cp localfile s3://bucket/remotefile
```