# certify

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/certify)
[![General Workflow](https://github.com/rolehippie/certify/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/certify/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/certify/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/certify/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/certify/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/certify/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/certify)](https://github.com/rolehippie/certify/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.certify-blue)](https://galaxy.ansible.com/rolehippie/certify)

Ansible role to upload certificates to specific paths.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [certify_default_certs](#certify_default_certs)
  - [certify_extra_certs](#certify_extra_certs)
  - [certify_reload_services](#certify_reload_services)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`

## Default Variables

### certify_default_certs

List of default certificates to write to server

#### Default value

```YAML
certify_default_certs: []
```

### certify_extra_certs

List of extra certificates to write to server

#### Default value

```YAML
certify_extra_certs: []
```

### certify_reload_services

List of services to reload after cert change

#### Default value

```YAML
certify_reload_services: []
```

## Discovered Tags

**_certify_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
