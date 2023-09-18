# shaded-h2database

## Introduction

This project should help to migrate `com.h2database:h2` version `2.1.*` (e.g. `2.1.214`) to `2.2.*` (e.g. `2.2.222`) by
making it possible to include both versions at the same time under a different package name.

| Item         | Original Value             | New Value                                                                                                  |
|--------------|----------------------------|------------------------------------------------------------------------------------------------------------|
| Group Id     | com.h2database             | io.github.1tchy.shaded.com.h2database                                                                      |
| Artifact Id  | h2                         | h2-2.1                                                                                                     |
| Package Name | org.h2                     | io.github._1tchy.shaded.org.h21                                                                            |
| Module Name  | com.h2database             | io.github._1tchy.shaded.com.h2database.h21                                                                 |
| Version      | 2.1.(\d+) (e.g. `2.1.214`) | [2.1.$1.➰](https://mvnrepository.com/artifact/io.github.1tchy.shaded.com.h2database/h2) (e.g. `2.1.214.1`) |

> 💡 **Tip:** For migration from version `1.4.200`, checkout the [master branch](https://github.com/1tchy/shaded-h2database/tree/master).

## License

### For the generated artifacts

The generated artifacts are published under the same license as the original artifact.
