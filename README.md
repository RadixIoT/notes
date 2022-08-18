# Purpose of repository

Public notes and general information about [Radix IoT](https://radixiot.com/) and its products.

## Open source licenses

Radix IoT uses open source software in its products. This is a list of open source software which
has been modified by Radix IoT.

| Project                                        | License                                         | Notice                             | Modifications                                                                                            |
|------------------------------------------------|-------------------------------------------------|:-----------------------------------|----------------------------------------------------------------------------------------------------------|
| [grpc-java](https://github.com/grpc/grpc-java) | [Apache 2.0 license](grpc-java/LICENSE-2.0.txt) | [NOTICE.txt](grpc-java/NOTICE.txt) | Modify ProtoReflectionService to allow for returning a static list of services from a FileDescriptorSet. |