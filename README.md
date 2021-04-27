# grpc-gateway-sample
grpc-gateway go sample code

http://jeremyko.blogspot.com/2021/04/go-grpc-gateway.html

protoc -I ./proto --go_out ./proto --go_opt paths=source_relative --go-grpc_out ./proto --go-grpc_opt paths=source_relative --grpc-gateway_out ./proto --grpc-gateway_opt paths=source_relative ./proto/helloworld/hello_world.proto


