# SAM commands

- sam init :: initializes SAM with template <br>
- sam build :: builds SAM <br>
- sam local generate-event apigateway aws-proxy > events/apigw-event.json :: generates local event <br>
- sam local invoke -e events/apigw-event.json :: calls single event <br>
- sam local start-api --env-vars env.json -p 9091 --debug<br>
- sam deploy --guided // deploys to aws.(authorization question must be answered with y or fails) <br>

# Curling with Origin

curl -H "Origin: http://localhost:3000" -i -X GET http://localhost:9091/< br>

# Docker

docker.for.mac.localhost

# Commands you can use next

[*] Create pipeline: cd cloudhus && sam pipeline init --bootstrap
[*] Validate SAM template: cd cloudhus && sam validate
[*] Test Function in the Cloud: cd cloudhus && sam sync --stack-name {stack-name} --watch
