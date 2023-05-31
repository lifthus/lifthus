
# Basic
1. go mod init goweb # 고 모듈 초기화
2. go get github.com/joho/godotenv # ( .env 사용하는 경우 )
3. go get github.com/lifthus/envbyjson/go # json으로 환경 변수 로딩시
4. go get github.com/labstack/echo/v4 # 고 웹 프레임워크
5. go install github.com/swaggo/swag/cmd/swag@latest # 고 스웨거 (swag init 해줘야함)
6. go get -u github.com/swaggo/echo-swagger # 고 에코 스웨거 
7. go get -u github.com/go-sql-driver/mysql # DB 드라이버 ( 엔트 사용시 _ 로 전역 임포트 )
8. go run -mod=mod entgo.io/ent/cmd/ent new {TableName} # 엔트 고
9. go generate ./ent # 엔트 스키마 생성하기
10. go get github.com/google/uuid # UUID 사용시
11. go get -u github.com/golang-jwt/jwt/v5 # jwt 사용시

# Serverless
* github.com/aws/aws-lambda-go/lambda
* github.com/aws/aws-lambda-go/events
* github.com/awslabs/aws-lambda-go-api-proxy/echo
