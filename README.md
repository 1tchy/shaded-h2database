# shaded-h2database

## Introduction

This project should help to migrate `com.h2database:h2` version `2.5.*` (e.g. `2.5.250`) to a newer version by
making it possible to include both versions at the same time under a different package name.

| Item         | Original Value             | New Value                                                                                                     |
|--------------|----------------------------|---------------------------------------------------------------------------------------------------------------|
| Group Id     | com.h2database             | io.github.1tchy.shaded.com.h2database                                                                         |
| Artifact Id  | h2                         | h2-2.5                                                                                                        |
| Package Name | org.h2                     | io.github._1tchy.shaded.org.h25                                                                               |
| Module Name  | com.h2database             | io.github._1tchy.shaded.com.h2database.h25                                                                    |
| Version      | 2.5.(\d+) (e.g. `2.5.250`) | [2.5.$1.➰](https://mvnrepository.com/artifact/io.github.1tchy.shaded.com.h2database/h2-2.5) (e.g. `2.5.250.1`) |

> 💡 **Tip:** Shaded artifacts for the other H2 versions live on their own branches:
> [`1.4.*`](https://github.com/1tchy/shaded-h2database/tree/master) ·
> [`2.1.*`](https://github.com/1tchy/shaded-h2database/tree/h2-version-2.1.x) ·
> [`2.4.*`](https://github.com/1tchy/shaded-h2database/tree/h2-version-2.4.x)

## License

### For the generated artifacts

The generated artifacts are published under the same license as the original artifact.
