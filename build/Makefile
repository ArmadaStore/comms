.PHONY: cargoToMgr

cargoToMgr:
    protoc -I=../protos/ --go_out=plugins=grpc:../rpc/cargoToMgr --go_opt=paths=source_relative cargoToMgr.proto