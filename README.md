# Go-serverless-stack

### Build

```
cd ./cmd && go build -o ../build/main main.go
cd ../build && zip ./main.zip ./main
```


### AWS setup

1) Create lambda ![setup-1.png](./docs/images/setup-1.png) ![setup-2.png](./docs/images/setup-2.png)
2) Change lambda function handlers ![setup-3.png](./docs/images/setup-3.png) ![setup-4.png](./docs/images/setup-4.png)
3) Upload zip file to code source ![setup-5.png](./docs/images/setup-5.png) ![setup-6.png](./docs/images/setup-6.png)
4) Go to ASW DynamoDB and create table ![setup-7.png](./docs/images/setup-7.png) ![setup-8.png](./docs/images/setup-8.png)
5) Go to API Gateway and create REST API ![setup-9.png](./docs/images/setup-9.png) ![setup-10.png](./docs/images/setup-10.png)
6) Create methods in API Gateway actions ![setup-11.png](./docs/images/setup-11.png) ![./images/setup-12.png](./docs/images/setup-12.png)
7) Deploy API in API Gateway actions ![setup-13.png](./docs/images/setup-13.png) ![setup-14.png](./docs/images/setup-14.png)
8) Retrieve URL for testing functionality ![setup-15.png](./docs/images/setup-15.png)

### Test

Import postman collection and send request to endpoints