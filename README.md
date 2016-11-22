#Apollo: Binary Protocol that implements Pundun Procedures.
Apollo protocol is defined both in Protocol Buffers and Asn.1 formats.

To compile apollo.proto when using go package pundun, use protoc as below.
```shell
$ protoc --proto_path=<APOLLO_PATH> --go_out=<APOLLO_PATH> <APOLLO_PATH>/apollo.proto
```
