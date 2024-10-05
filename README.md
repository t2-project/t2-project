# T2-Project

This repository acts as a parent for all repositories related to the T2-Project:

- [devops](https://github.com/t2-project/devops/)
- [documentation](https://github.com/t2-project/documentation)
- [microservices](https://github.com/t2-project/microservices) (another parent repository for all microservices)
- [modulith](https://github.com/t2-project/modulith)

## Documentation

Available on https://t2-documentation.readthedocs.io/ or in the corresponding repositories.

## Cloning the project

Via _HTTPS_:
```bash
git clone --recurse-submodules -j8 https://github.com/t2-project/t2-project.git
```

Via _SSH_:
```bash
git clone --recurse-submodules -j8 git@github.com:t2-project/t2-project.git
```

## Update Submodules

```bash
git submodule update --recursive --remote
```
