# lychee

![Version: 6.6.0](https://img.shields.io/badge/Version-6.6.0-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: auto](https://img.shields.io/badge/AppVersion-auto-informational?style=flat-square)

Lychee is a free photo-management tool, which runs on your server or web-space

**Homepage:** <https://github.com/truecharts/apps/tree/master/charts/incubator/lychee>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| TrueCharts | info@truecharts.org | truecharts.org |

## Source Code

* <https://github.com/LycheeOrg/Lychee>
* <https://hub.docker.com/r/lycheeorg/lychee>

## Requirements

Kubernetes: `>=1.16.0-0`

| Repository | Name | Version |
|------------|------|---------|
| https://truecharts.org/ | common | 6.8.0 |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| env | object | `{}` |  |
| image.pullPolicy | string | `"IfNotPresent"` |  |
| image.repository | string | `"lycheeorg/lychee-laravel"` |  |
| image.tag | string | `"v4.3.4"` |  |
| persistence.config.enabled | bool | `true` |  |
| persistence.config.mountPath | string | `"/config"` |  |
| persistence.config.type | string | `"emptyDir"` |  |
| service.main.ports.main.port | int | `80` |  |
| strategy.type | string | `"Recreate"` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.5.0](https://github.com/norwoodj/helm-docs/releases/v1.5.0)