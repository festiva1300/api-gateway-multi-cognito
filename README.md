# api-gateway-multi-cognito

## はじめに

これはAPI Gatewayで、複数のCognitoユーザープールのいずれかで認証を行うためのサンプルです。

## deploy
aws cloudformation deploy \
    --template-file template.yml \
    --stack-name cognito-api-sample \
    --capabilities CAPABILITY_NAMED_IAM