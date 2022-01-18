# certify

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/certify) [![Testing Build](https://github.com/rolehippie/certify/workflows/testing/badge.svg)](https://github.com/rolehippie/certify/actions?query=workflow%3Atesting) [![Readme Build](https://github.com/rolehippie/certify/workflows/readme/badge.svg)](https://github.com/rolehippie/certify/actions?query=workflow%3Areadme) [![Galaxy Build](https://github.com/rolehippie/certify/workflows/galaxy/badge.svg)](https://github.com/rolehippie/certify/actions?query=workflow%3Agalaxy) [![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/certify)](https://github.com/rolehippie/certify/blob/master/LICENSE) 

Ansible role to upload certificates to specific paths. 

## Sponsor 

[![Proact Deutschland GmbH](https://proact.eu/wp-content/uploads/2020/03/proact-logo.png)](https://proact.eu) 

Building and improving this Ansible role have been sponsored by my employer **Proact Deutschland GmbH**.

## Table of content

* [Default Variables](#default-variables)
  * [certify_default_certs](#certify_default_certs)
  * [certify_extra_certs](#certify_extra_certs)
  * [certify_reload_services](#certify_reload_services)
* [Dependencies](#dependencies)
* [License](#license)
* [Author](#author)

---

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

## Dependencies

* [rolehippie.docker](https://github.com/rolehippie/docker)

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
