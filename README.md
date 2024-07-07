# serverless-plugin-typescript-2.1.x 

Forked from https://github.com/serverless/serverless-plugin-typescript at 07-July-2024

Compatible with Serverless v3

Avoid auto-compiling typescript for every update/change in watch files adding a param in serverless offline start command
$ serverless offline start --stage STG_NAME --param="watch=false" --param="other-key:other-value"
