---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "uptime-kuma_monitor Resource - terraform-provider-uptime-kuma"
subcategory: ""
description: |-
  Monitor Resource
---

# uptime-kuma_monitor (Resource)

Monitor Resource

## Example Usage

```terraform
resource "uptime-kuma_monitor" "my_monitor" {
  accepted_statuscodes = [
    "..."
  ]
  active                     = 3
  auth_domain                = "{ \"see\": \"documentation\" }"
  auth_method                = "...my_auth_method..."
  auth_workstation           = "{ \"see\": \"documentation\" }"
  basic_auth_pass            = "{ \"see\": \"documentation\" }"
  basic_auth_user            = "{ \"see\": \"documentation\" }"
  body                       = "{ \"see\": \"documentation\" }"
  database_connection_string = "{ \"see\": \"documentation\" }"
  database_query             = "{ \"see\": \"documentation\" }"
  dns_last_result            = "{ \"see\": \"documentation\" }"
  dns_resolve_server         = "...my_dns_resolve_server..."
  dns_resolve_type           = "...my_dns_resolve_type..."
  docker_container           = "{ \"see\": \"documentation\" }"
  docker_host                = "{ \"see\": \"documentation\" }"
  expiry_notification        = true
  headers                    = "{ \"see\": \"documentation\" }"
  hostname                   = "{ \"see\": \"documentation\" }"
  id                         = 5
  ignore_tls                 = true
  interval                   = 0
  keyword                    = "{ \"see\": \"documentation\" }"
  maxredirects               = 6
  maxretries                 = 9
  method                     = "...my_method..."
  mqtt_password              = "{ \"see\": \"documentation\" }"
  mqtt_success_message       = "{ \"see\": \"documentation\" }"
  mqtt_topic                 = "{ \"see\": \"documentation\" }"
  mqtt_username              = "{ \"see\": \"documentation\" }"
  name                       = "...my_name..."
  notification_id_list = {
    # ...
  }
  port                      = 6
  proxy_id                  = "{ \"see\": \"documentation\" }"
  push_token                = "{ \"see\": \"documentation\" }"
  radius_called_station_id  = "{ \"see\": \"documentation\" }"
  radius_calling_station_id = "{ \"see\": \"documentation\" }"
  radius_password           = "{ \"see\": \"documentation\" }"
  radius_secret             = "{ \"see\": \"documentation\" }"
  radius_username           = "{ \"see\": \"documentation\" }"
  resend_interval           = 7
  retry_interval            = 8
  tags = [
    "{ \"see\": \"documentation\" }"
  ]
  type        = "...my_type..."
  upside_down = true
  url         = "...my_url..."
  weight      = 1
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `expiry_notification` (Boolean) Requires replacement if changed.
- `ignore_tls` (Boolean) Requires replacement if changed.
- `upside_down` (Boolean) Requires replacement if changed.

### Optional

- `accepted_statuscodes` (List of String) Requires replacement if changed.
- `active` (Number) Requires replacement if changed.
- `auth_domain` (String) Requires replacement if changed.; Parsed as JSON.
- `auth_method` (String) Requires replacement if changed.
- `auth_workstation` (String) Requires replacement if changed.; Parsed as JSON.
- `basic_auth_pass` (String) Requires replacement if changed.; Parsed as JSON.
- `basic_auth_user` (String) Requires replacement if changed.; Parsed as JSON.
- `body` (String) Requires replacement if changed.; Parsed as JSON.
- `database_connection_string` (String) Requires replacement if changed.; Parsed as JSON.
- `database_query` (String) Requires replacement if changed.; Parsed as JSON.
- `dns_last_result` (String) Requires replacement if changed.; Parsed as JSON.
- `dns_resolve_server` (String) Requires replacement if changed.
- `dns_resolve_type` (String) Requires replacement if changed.
- `docker_container` (String) Requires replacement if changed.; Parsed as JSON.
- `docker_host` (String) Requires replacement if changed.; Parsed as JSON.
- `headers` (String) Requires replacement if changed.; Parsed as JSON.
- `hostname` (String) Requires replacement if changed.; Parsed as JSON.
- `id` (Number) Requires replacement if changed.
- `interval` (Number) Requires replacement if changed.
- `keyword` (String) Requires replacement if changed.; Parsed as JSON.
- `maxredirects` (Number) Requires replacement if changed.
- `maxretries` (Number) Requires replacement if changed.
- `method` (String) Requires replacement if changed.
- `mqtt_password` (String) Requires replacement if changed.; Parsed as JSON.
- `mqtt_success_message` (String) Requires replacement if changed.; Parsed as JSON.
- `mqtt_topic` (String) Requires replacement if changed.; Parsed as JSON.
- `mqtt_username` (String) Requires replacement if changed.; Parsed as JSON.
- `name` (String) Requires replacement if changed.
- `notification_id_list` (Attributes) Requires replacement if changed. (see [below for nested schema](#nestedatt--notification_id_list))
- `port` (Number) Requires replacement if changed.
- `proxy_id` (String) Requires replacement if changed.; Parsed as JSON.
- `push_token` (String) Requires replacement if changed.; Parsed as JSON.
- `radius_called_station_id` (String) Requires replacement if changed.; Parsed as JSON.
- `radius_calling_station_id` (String) Requires replacement if changed.; Parsed as JSON.
- `radius_password` (String) Requires replacement if changed.; Parsed as JSON.
- `radius_secret` (String) Requires replacement if changed.; Parsed as JSON.
- `radius_username` (String) Requires replacement if changed.; Parsed as JSON.
- `resend_interval` (Number) Requires replacement if changed.
- `retry_interval` (Number) Requires replacement if changed.
- `tags` (List of String) Requires replacement if changed.
- `type` (String) Requires replacement if changed.
- `url` (String) Requires replacement if changed.
- `weight` (Number) Requires replacement if changed.

### Read-Only

- `data` (String) Parsed as JSON.

<a id="nestedatt--notification_id_list"></a>
### Nested Schema for `notification_id_list`

## Import

Import is supported using the following syntax:

```shell
terraform import uptime-kuma_monitor.my_uptime-kuma_monitor "0"
```