# Schema Docs

- [1. Property `root > tool`](#tool)
  - [1.1. Property `root > tool > autoSync`](#tool_autoSync)
    - [1.1.1. Property `root > tool > autoSync > enabled`](#tool_autoSync_enabled)
  - [1.2. Property `root > tool > cluster_git`](#tool_cluster_git)
    - [1.2.1. Property `root > tool > cluster_git > passwordkey`](#tool_cluster_git_passwordkey)
    - [1.2.2. Property `root > tool > cluster_git > username`](#tool_cluster_git_username)
  - [1.3. Property `root > tool > container`](#tool_container)
    - [1.3.1. Property `root > tool > container > registry`](#tool_container_registry)
  - [1.4. Property `root > tool > dashboards`](#tool_dashboards)
    - [1.4.1. Property `root > tool > dashboards > enabled`](#tool_dashboards_enabled)
  - [1.5. Property `root > tool > git`](#tool_git)
    - [1.5.1. Property `root > tool > git > server_url`](#tool_git_server_url)
  - [1.6. Property `root > tool > ha`](#tool_ha)
    - [1.6.1. Property `root > tool > ha > enabled`](#tool_ha_enabled)
  - [1.7. Property `root > tool > helm`](#tool_helm)
    - [1.7.1. Property `root > tool > helm > repository`](#tool_helm_repository)
  - [1.8. Property `root > tool > k8wms_helm`](#tool_k8wms_helm)
    - [1.8.1. Property `root > tool > k8wms_helm > passwordkey`](#tool_k8wms_helm_passwordkey)
    - [1.8.2. Property `root > tool > k8wms_helm > username`](#tool_k8wms_helm_username)
  - [1.9. Property `root > tool > local_admin`](#tool_local_admin)
    - [1.9.1. Property `root > tool > local_admin > enabled`](#tool_local_admin_enabled)
    - [1.9.2. Property `root > tool > local_admin > passwordkey`](#tool_local_admin_passwordkey)
  - [1.10. Property `root > tool > name`](#tool_name)
  - [1.11. Property `root > tool > networkPolicy`](#tool_networkPolicy)
    - [1.11.1. Property `root > tool > networkPolicy > enabled`](#tool_networkPolicy_enabled)
  - [1.12. Property `root > tool > oidc`](#tool_oidc)
    - [1.12.1. Property `root > tool > oidc > subdomain`](#tool_oidc_subdomain)
  - [1.13. Property `root > tool > prometheusRules`](#tool_prometheusRules)
    - [1.13.1. Property `root > tool > prometheusRules > enabled`](#tool_prometheusRules_enabled)
  - [1.14. Property `root > tool > psa`](#tool_psa)
    - [1.14.1. Property `root > tool > psa > audit`](#tool_psa_audit)
    - [1.14.2. Property `root > tool > psa > enforcement`](#tool_psa_enforcement)
    - [1.14.3. Property `root > tool > psa > warning`](#tool_psa_warning)

|                           |                                                         |
| ------------------------- | ------------------------------------------------------- |
| **Type**                  | `object`                                                |
| **Required**              | No                                                      |
| **Additional properties** | [[Not allowed]](# "Additional Properties not allowed.") |

| Property         | Pattern | Type   | Deprecated | Definition | Title/Description |
| ---------------- | ------- | ------ | ---------- | ---------- | ----------------- |
| - [tool](#tool ) | No      | object | No         | -          | -                 |

## <a name="tool"></a>1. Property `root > tool`

|                           |                                                         |
| ------------------------- | ------------------------------------------------------- |
| **Type**                  | `object`                                                |
| **Required**              | No                                                      |
| **Additional properties** | [[Not allowed]](# "Additional Properties not allowed.") |

| Property                                    | Pattern | Type   | Deprecated | Definition | Title/Description |
| ------------------------------------------- | ------- | ------ | ---------- | ---------- | ----------------- |
| - [autoSync](#tool_autoSync )               | No      | object | No         | -          | -                 |
| - [cluster_git](#tool_cluster_git )         | No      | object | No         | -          | -                 |
| - [container](#tool_container )             | No      | object | No         | -          | -                 |
| - [dashboards](#tool_dashboards )           | No      | object | No         | -          | -                 |
| - [git](#tool_git )                         | No      | object | No         | -          | -                 |
| - [ha](#tool_ha )                           | No      | object | No         | -          | -                 |
| - [helm](#tool_helm )                       | No      | object | No         | -          | -                 |
| - [k8wms_helm](#tool_k8wms_helm )           | No      | object | No         | -          | -                 |
| - [local_admin](#tool_local_admin )         | No      | object | No         | -          | -                 |
| - [name](#tool_name )                       | No      | string | No         | -          | -                 |
| - [networkPolicy](#tool_networkPolicy )     | No      | object | No         | -          | -                 |
| - [oidc](#tool_oidc )                       | No      | object | No         | -          | -                 |
| - [prometheusRules](#tool_prometheusRules ) | No      | object | No         | -          | -                 |
| - [psa](#tool_psa )                         | No      | object | No         | -          | -                 |

### <a name="tool_autoSync"></a>1.1. Property `root > tool > autoSync`

|                           |                                                         |
| ------------------------- | ------------------------------------------------------- |
| **Type**                  | `object`                                                |
| **Required**              | No                                                      |
| **Additional properties** | [[Not allowed]](# "Additional Properties not allowed.") |

| Property                             | Pattern | Type             | Deprecated | Definition | Title/Description |
| ------------------------------------ | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [enabled](#tool_autoSync_enabled ) | No      | enum (of string) | No         | -          | -                 |

#### <a name="tool_autoSync_enabled"></a>1.1.1. Property `root > tool > autoSync > enabled`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |
| **Default**  | `""`               |

Must be one of:
* "true"
* "false"
* ""

### <a name="tool_cluster_git"></a>1.2. Property `root > tool > cluster_git`

|                           |                                                         |
| ------------------------- | ------------------------------------------------------- |
| **Type**                  | `object`                                                |
| **Required**              | No                                                      |
| **Additional properties** | [[Not allowed]](# "Additional Properties not allowed.") |

| Property                                        | Pattern | Type   | Deprecated | Definition | Title/Description |
| ----------------------------------------------- | ------- | ------ | ---------- | ---------- | ----------------- |
| - [passwordkey](#tool_cluster_git_passwordkey ) | No      | string | No         | -          | -                 |
| - [username](#tool_cluster_git_username )       | No      | string | No         | -          | -                 |

#### <a name="tool_cluster_git_passwordkey"></a>1.2.1. Property `root > tool > cluster_git > passwordkey`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |
| **Default**  | `""`     |

| Restrictions   |   |
| -------------- | - |
| **Min length** | 1 |

#### <a name="tool_cluster_git_username"></a>1.2.2. Property `root > tool > cluster_git > username`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |
| **Default**  | `""`     |

| Restrictions   |   |
| -------------- | - |
| **Min length** | 1 |

### <a name="tool_container"></a>1.3. Property `root > tool > container`

|                           |                                                         |
| ------------------------- | ------------------------------------------------------- |
| **Type**                  | `object`                                                |
| **Required**              | No                                                      |
| **Additional properties** | [[Not allowed]](# "Additional Properties not allowed.") |

| Property                                | Pattern | Type   | Deprecated | Definition | Title/Description |
| --------------------------------------- | ------- | ------ | ---------- | ---------- | ----------------- |
| - [registry](#tool_container_registry ) | No      | string | No         | -          | -                 |

#### <a name="tool_container_registry"></a>1.3.1. Property `root > tool > container > registry`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |
| **Default**  | `""`     |

### <a name="tool_dashboards"></a>1.4. Property `root > tool > dashboards`

|                           |                                                         |
| ------------------------- | ------------------------------------------------------- |
| **Type**                  | `object`                                                |
| **Required**              | No                                                      |
| **Additional properties** | [[Not allowed]](# "Additional Properties not allowed.") |

| Property                               | Pattern | Type             | Deprecated | Definition | Title/Description |
| -------------------------------------- | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [enabled](#tool_dashboards_enabled ) | No      | enum (of string) | No         | -          | -                 |

#### <a name="tool_dashboards_enabled"></a>1.4.1. Property `root > tool > dashboards > enabled`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |
| **Default**  | `""`               |

Must be one of:
* "true"
* "false"
* ""

### <a name="tool_git"></a>1.5. Property `root > tool > git`

|                           |                                                         |
| ------------------------- | ------------------------------------------------------- |
| **Type**                  | `object`                                                |
| **Required**              | No                                                      |
| **Additional properties** | [[Not allowed]](# "Additional Properties not allowed.") |

| Property                              | Pattern | Type   | Deprecated | Definition | Title/Description |
| ------------------------------------- | ------- | ------ | ---------- | ---------- | ----------------- |
| - [server_url](#tool_git_server_url ) | No      | string | No         | -          | -                 |

#### <a name="tool_git_server_url"></a>1.5.1. Property `root > tool > git > server_url`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |
| **Default**  | `""`     |

| Restrictions   |   |
| -------------- | - |
| **Min length** | 1 |

### <a name="tool_ha"></a>1.6. Property `root > tool > ha`

|                           |                                                         |
| ------------------------- | ------------------------------------------------------- |
| **Type**                  | `object`                                                |
| **Required**              | No                                                      |
| **Additional properties** | [[Not allowed]](# "Additional Properties not allowed.") |

| Property                       | Pattern | Type             | Deprecated | Definition | Title/Description |
| ------------------------------ | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [enabled](#tool_ha_enabled ) | No      | enum (of string) | No         | -          | -                 |

#### <a name="tool_ha_enabled"></a>1.6.1. Property `root > tool > ha > enabled`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |
| **Default**  | `""`               |

Must be one of:
* "true"
* "false"
* ""

### <a name="tool_helm"></a>1.7. Property `root > tool > helm`

|                           |                                                         |
| ------------------------- | ------------------------------------------------------- |
| **Type**                  | `object`                                                |
| **Required**              | No                                                      |
| **Additional properties** | [[Not allowed]](# "Additional Properties not allowed.") |

| Property                               | Pattern | Type   | Deprecated | Definition | Title/Description |
| -------------------------------------- | ------- | ------ | ---------- | ---------- | ----------------- |
| - [repository](#tool_helm_repository ) | No      | string | No         | -          | -                 |

#### <a name="tool_helm_repository"></a>1.7.1. Property `root > tool > helm > repository`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |
| **Default**  | `""`     |

### <a name="tool_k8wms_helm"></a>1.8. Property `root > tool > k8wms_helm`

|                           |                                                         |
| ------------------------- | ------------------------------------------------------- |
| **Type**                  | `object`                                                |
| **Required**              | No                                                      |
| **Additional properties** | [[Not allowed]](# "Additional Properties not allowed.") |

| Property                                       | Pattern | Type   | Deprecated | Definition | Title/Description |
| ---------------------------------------------- | ------- | ------ | ---------- | ---------- | ----------------- |
| - [passwordkey](#tool_k8wms_helm_passwordkey ) | No      | string | No         | -          | -                 |
| - [username](#tool_k8wms_helm_username )       | No      | string | No         | -          | -                 |

#### <a name="tool_k8wms_helm_passwordkey"></a>1.8.1. Property `root > tool > k8wms_helm > passwordkey`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |
| **Default**  | `""`     |

| Restrictions   |   |
| -------------- | - |
| **Min length** | 1 |

#### <a name="tool_k8wms_helm_username"></a>1.8.2. Property `root > tool > k8wms_helm > username`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |
| **Default**  | `""`     |

| Restrictions   |   |
| -------------- | - |
| **Min length** | 1 |

### <a name="tool_local_admin"></a>1.9. Property `root > tool > local_admin`

|                           |                                                         |
| ------------------------- | ------------------------------------------------------- |
| **Type**                  | `object`                                                |
| **Required**              | No                                                      |
| **Additional properties** | [[Not allowed]](# "Additional Properties not allowed.") |

| Property                                        | Pattern | Type    | Deprecated | Definition | Title/Description |
| ----------------------------------------------- | ------- | ------- | ---------- | ---------- | ----------------- |
| - [enabled](#tool_local_admin_enabled )         | No      | boolean | No         | -          | -                 |
| - [passwordkey](#tool_local_admin_passwordkey ) | No      | string  | No         | -          | -                 |

#### <a name="tool_local_admin_enabled"></a>1.9.1. Property `root > tool > local_admin > enabled`

|              |           |
| ------------ | --------- |
| **Type**     | `boolean` |
| **Required** | No        |
| **Default**  | `true`    |

#### <a name="tool_local_admin_passwordkey"></a>1.9.2. Property `root > tool > local_admin > passwordkey`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |
| **Default**  | `""`     |

### <a name="tool_name"></a>1.10. Property `root > tool > name`

|              |                  |
| ------------ | ---------------- |
| **Type**     | `string`         |
| **Required** | No               |
| **Default**  | `"k8wms_argocd"` |

### <a name="tool_networkPolicy"></a>1.11. Property `root > tool > networkPolicy`

|                           |                                                         |
| ------------------------- | ------------------------------------------------------- |
| **Type**                  | `object`                                                |
| **Required**              | No                                                      |
| **Additional properties** | [[Not allowed]](# "Additional Properties not allowed.") |

| Property                                  | Pattern | Type             | Deprecated | Definition | Title/Description |
| ----------------------------------------- | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [enabled](#tool_networkPolicy_enabled ) | No      | enum (of string) | No         | -          | -                 |

#### <a name="tool_networkPolicy_enabled"></a>1.11.1. Property `root > tool > networkPolicy > enabled`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |
| **Default**  | `""`               |

Must be one of:
* "true"
* "false"
* ""

### <a name="tool_oidc"></a>1.12. Property `root > tool > oidc`

|                           |                                                         |
| ------------------------- | ------------------------------------------------------- |
| **Type**                  | `object`                                                |
| **Required**              | No                                                      |
| **Additional properties** | [[Not allowed]](# "Additional Properties not allowed.") |

| Property                             | Pattern | Type   | Deprecated | Definition | Title/Description |
| ------------------------------------ | ------- | ------ | ---------- | ---------- | ----------------- |
| - [subdomain](#tool_oidc_subdomain ) | No      | string | No         | -          | -                 |

#### <a name="tool_oidc_subdomain"></a>1.12.1. Property `root > tool > oidc > subdomain`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | No       |
| **Default**  | `"dex"`  |

### <a name="tool_prometheusRules"></a>1.13. Property `root > tool > prometheusRules`

|                           |                                                         |
| ------------------------- | ------------------------------------------------------- |
| **Type**                  | `object`                                                |
| **Required**              | No                                                      |
| **Additional properties** | [[Not allowed]](# "Additional Properties not allowed.") |

| Property                                    | Pattern | Type             | Deprecated | Definition | Title/Description |
| ------------------------------------------- | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [enabled](#tool_prometheusRules_enabled ) | No      | enum (of string) | No         | -          | -                 |

#### <a name="tool_prometheusRules_enabled"></a>1.13.1. Property `root > tool > prometheusRules > enabled`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |
| **Default**  | `""`               |

Must be one of:
* "true"
* "false"
* ""

### <a name="tool_psa"></a>1.14. Property `root > tool > psa`

|                           |                                                         |
| ------------------------- | ------------------------------------------------------- |
| **Type**                  | `object`                                                |
| **Required**              | No                                                      |
| **Additional properties** | [[Not allowed]](# "Additional Properties not allowed.") |

| Property                                | Pattern | Type             | Deprecated | Definition | Title/Description |
| --------------------------------------- | ------- | ---------------- | ---------- | ---------- | ----------------- |
| - [audit](#tool_psa_audit )             | No      | enum (of string) | No         | -          | -                 |
| - [enforcement](#tool_psa_enforcement ) | No      | enum (of string) | No         | -          | -                 |
| - [warning](#tool_psa_warning )         | No      | enum (of string) | No         | -          | -                 |

#### <a name="tool_psa_audit"></a>1.14.1. Property `root > tool > psa > audit`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |
| **Default**  | `"baseline"`       |

Must be one of:
* "baseline"
* "restricted"
* "privileged"

#### <a name="tool_psa_enforcement"></a>1.14.2. Property `root > tool > psa > enforcement`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |
| **Default**  | `"baseline"`       |

Must be one of:
* "baseline"
* "restricted"
* "privileged"

#### <a name="tool_psa_warning"></a>1.14.3. Property `root > tool > psa > warning`

|              |                    |
| ------------ | ------------------ |
| **Type**     | `enum (of string)` |
| **Required** | No                 |
| **Default**  | `"baseline"`       |

Must be one of:
* "baseline"
* "restricted"
* "privileged"

----------------------------------------------------------------------------------------------------------------------------
Generated using [json-schema-for-humans](https://github.com/coveooss/json-schema-for-humans) on 2024-05-06 at 09:00:15 +0200
