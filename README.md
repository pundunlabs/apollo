#Apollo: Binary Protocol that implements Pundun Procedures.
Apollo protocol is defined in Protocol Buffers format.

To compile apollo.proto when using pundun go package:
```shell
$ go generate .
```

To generate python code:
```shell
$ protoc --proto_path=<APOLLO_PATH> --python_out=<OUT_PATH> apollo.proto
```
