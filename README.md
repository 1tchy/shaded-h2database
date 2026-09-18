# shaded-h2database

## Introduction

This project should help to migrate `com.h2database:h2` version `2.4.*` (e.g. `2.4.240`) to `2.5.*` (e.g. `2.5.250`) by
making it possible to include both versions at the same time under a different package name.

| Item         | Original Value             | New Value                                                                                                     |
|--------------|----------------------------|---------------------------------------------------------------------------------------------------------------|
| Group Id     | com.h2database             | io.github.1tchy.shaded.com.h2database                                                                         |
| Artifact Id  | h2                         | h2-2.4                                                                                                        |
| Package Name | org.h2                     | io.github._1tchy.shaded.org.h24                                                                               |
| Module Name  | com.h2database             | io.github._1tchy.shaded.com.h2database.h24                                                                    |
| Version      | 2.4.(\d+) (e.g. `2.4.240`) | [2.4.$1.➰](https://mvnrepository.com/artifact/io.github.1tchy.shaded.com.h2database/h2-2.4) (e.g. `2.4.240.1`) |

> 💡 **Tip:** Shaded artifacts for the other H2 versions live on their own branches:
> [`1.4.*`](https://github.com/1tchy/shaded-h2database/tree/master) ·
> [`2.1.*`](https://github.com/1tchy/shaded-h2database/tree/h2-version-2.1.x) ·
> [`2.5.*`](https://github.com/1tchy/shaded-h2database/tree/h2-version-2.5.x)

## License

### For the generated artifacts

The generated artifacts are published under the same license as the original artifact.
