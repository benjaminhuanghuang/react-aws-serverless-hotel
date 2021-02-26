## Install AWS CLI
```
  $ curl "https://s3.amazonaws.com/aws-cli/awscli-bundle.zip" -o "awscli-bundle.zip"
  
  unzip awscli-bundle.zip

  sudo ./awscli-bundle/install -i /usr/local/aws -b /usr/local/bin/aws

  aws --version
```

## Confif IAM user
Create user in AWS "dynamoDbUser", Attach policy "dynamodb", get `Access key ID` and `Secret access key`

```
  aws config
```

## Install AWS DSK
```
  npm install aws-sdk
```


## Crate DynamoDB table and load data
```
  node scripts/CreateMenuLinksTable.js
  
  node scripts/LoadMenuLinksData.js
```









