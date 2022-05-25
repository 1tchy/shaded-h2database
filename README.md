# shaded-h2database

## Introduction

This project should help to migrate `com.h2database:h2` version `1.4.*` (e.g. `1.4.200`) to `2.*` (e.g. `2.1.212`) by
making it possible to include both versions at the same time under a different package name.

| Item         | Original Value             | New Value                                                                                                  |
|--------------|----------------------------|------------------------------------------------------------------------------------------------------------|
| Group Id     | com.h2database             | io.github.1tchy.shaded.com.h2database                                                                      |
| Artifact Id  | h2                         | h2                                                                                                         |
| Package Name | org.h2                     | io.github._1tchy.shaded.org.h2                                                                             |
| Module Name  | com.h2database             | io.github._1tchy.shaded.com.h2database                                                                     |
| Version      | 1.4.(\d+) (e.g. `1.4.200`) | [1.4.$1.➰](https://mvnrepository.com/artifact/io.github.1tchy.shaded.com.h2database/h2) (e.g. `1.4.200.1`) |

## License

### For the generated artifacts

The generated artifacts are published under the same license as the original artifact.
