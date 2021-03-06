---
title: "TransIP"
date: 2019-03-03T16:39:46+01:00
draft: false
slug: transip
---

<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->
<!-- providers/dns/transip/transip.toml -->
<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->


Configuration for [TransIP](https://www.transip.nl/).


<!--more-->

- Code: `transip`

{{% notice note %}}
_Please contribute by adding a CLI example._
{{% /notice %}}




## Credentials

| Environment Variable Name | Description |
|-----------------------|-------------|
| `TRANSIP_ACCOUNT_NAME` | Account name |
| `TRANSIP_PRIVATE_KEY_PATH` | Private key path |

The environment variable names can be suffixed by `_FILE` to reference a file instead of a value.
More information [here](/lego/dns/#configuration-and-credentials).


## Additional Configuration

| Environment Variable Name | Description |
|--------------------------------|-------------|
| `TRANSIP_POLLING_INTERVAL` | Time between DNS propagation check |
| `TRANSIP_PROPAGATION_TIMEOUT` | Maximum waiting time for DNS propagation |
| `TRANSIP_TTL` | The TTL of the TXT record used for the DNS challenge |

The environment variable names can be suffixed by `_FILE` to reference a file instead of a value.
More information [here](/lego/dns/#configuration-and-credentials).




## More information

- [API documentation](https://api.transip.nl/docs/transip.nl/package-Transip.html)
- [Go client](https://github.com/transip/gotransip)

<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->
<!-- providers/dns/transip/transip.toml -->
<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->
