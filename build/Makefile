all: cargoToMgr cargoToCargo taskToCargo taskToCargoMgr

.PHONY: cargoToMgr cargoToCargo taskToCargo taskToCargoMgr

cargoToMgr:
	protoc -I=protos/ --go_out=plugins=grpc:rpc/cargoToMgr --go_opt=paths=source_relative cargoToMgr.proto

cargoToCargo:
	protoc -I=protos/ --go_out=plugins=grpc:rpc/cargoToCargo --go_opt=paths=source_relative cargoToCargo.proto

taskToCargo:
	protoc -I=protos/ --go_out=plugins=grpc:rpc/taskToCargo --go_opt=paths=source_relative taskToCargo.proto

taskToCargoMgr:
	protoc -I=protos/ --go_out=plugins=grpc:rpc/taskToCargoMgr --go_opt=paths=source_relative taskToCargoMgr.proto