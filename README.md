# phantomjs

# run
```
$ docker run -v `pwd`:/data ieee0824/phantomjs --queue_url=${SQS_URL} --aws_access_key_id=${ACCESS_KEY} --aws_secret_access_key_id=${SECRET_KEY} --s3_bucket_name=${S3_BUCKET_NAME} --path=${S3_PATH}
```
