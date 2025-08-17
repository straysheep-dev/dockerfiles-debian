# dockerfiles-debian

Dockerfiles to build Debian images. See [straysheep-dev/docker-configs](https://github.com/straysheep-dev/docker-configs) for a general overview and references.

> [!NOTE]
> These files were built from a combination of:
> - [geerlingguy's](https://github.com/geerlingguy) `docker-<os>-ansible` templates
> - [Molecule's systemd-enabled container guide](https://ansible.readthedocs.io/projects/molecule/guides/systemd-container/)
> - [Rocky Linux Docker image systemd integration notes](https://hub.docker.com/r/rockylinux/rockylinux#systemd-integration)
> - Searching for, and reviewing, examples and documentation with ChatGPT or AI mode Google Search


## Images

| Version | Components and Software | Status |
| :--- | :---: | :---: |
| `debian:latest` | `systemd` | ![Static Badge](https://img.shields.io/badge/supported-green) |
| `debian:11` | `systemd` | ![Static Badge](https://img.shields.io/badge/planned-gray) |
| `debian:10` | `systemd` | ![Static Badge](https://img.shields.io/badge/planned-gray) |
| `debian:9` | N/A | ![Static Badge](https://img.shields.io/badge/planned-gray) |


## License

[MIT](LICENSE)