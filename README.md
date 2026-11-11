# Gatekeeper Operator File-Based Catalog

This repository houses the File-Based Catalog (FBC) for the
[Gatekeeper Operator](https://github.com/stolostron/gatekeeper-operator).

See the Operator Lifecycle Manager (OLM)
[File-based Catalogs documentation](https://olm.operatorframework.io/docs/reference/file-based-catalogs/)
and the [operator-registry repository](https://github.com/operator-framework/operator-registry) for
additional information.

## Maintenance Scripts

See the [docs/](./docs/) directory for documentation on how to manage the catalog files in this
repository using the scripts in the [build/](./build/) directory.

## Catalog Channels

The table shows version channels present in the repository for selected OCP catalogs. It does not
establish production publication, compatibility, or product support. Catalogs for possible future
OCP versions are not included.

|      | 4-14 | 4-16 | 4-18 | 4-19 | 4-20 | 4-21 | 4-22 | 5-0 |
| ---  | ---  | ---  | ---  | ---  | ---  | ---  | ---  | --- |
| 3.21 | ✅   | ✅   | ✅   | ✅   | ✅   | ✅   | ✅   | ✅  |
| 3.20 | ✅   | ✅   | ✅   | ✅   | ✅   | ✅   | ✅   | ✅  |
| 3.19 | ✅   | ✅   | ✅   | ✅   | ✅   | ✅   | ✅   | ✅  |
