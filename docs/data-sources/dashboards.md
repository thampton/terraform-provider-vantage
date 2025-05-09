---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "vantage_dashboards Data Source - terraform-provider-vantage"
subcategory: ""
description: |-
  
---

# vantage_dashboards (Data Source)





<!-- schema generated by tfplugindocs -->
## Schema

### Read-Only

- `dashboards` (Attributes List) (see [below for nested schema](#nestedatt--dashboards))

<a id="nestedatt--dashboards"></a>
### Nested Schema for `dashboards`

Read-Only:

- `created_at` (String) The date and time, in UTC, the Dashboard was created. ISO 8601 Formatted.
- `date_bin` (String) Determines how to group costs in the Dashboard.
- `date_interval` (String) Determines the date range for Reports in the Dashboard. Guaranteed to be set to 'custom' if 'start_date' and 'end_date' are set.
- `end_date` (String) The end date for the date range for Reports in the Dashboard. ISO 8601 Formatted. Overwrites 'date_interval' if set.
- `saved_filter_tokens` (List of String) The tokens of the Saved Filters used in the Dashboard.
- `start_date` (String) The start date for the date range for Reports in the Dashboard. ISO 8601 Formatted. Overwrites 'date_interval' if set.
- `title` (String) The title of the Dashboard.
- `token` (String)
- `updated_at` (String) The date and time, in UTC, the Dashboard was created. ISO 8601 Formatted.
- `widgets` (Attributes List) (see [below for nested schema](#nestedatt--dashboards--widgets))
- `workspace_token` (String) The token for the Workspace the Dashboard is a part of.

<a id="nestedatt--dashboards--widgets"></a>
### Nested Schema for `dashboards.widgets`

Read-Only:

- `settings` (Attributes) (see [below for nested schema](#nestedatt--dashboards--widgets--settings))
- `title` (String) The title of the Widget.
- `widgetable_token` (String)

<a id="nestedatt--dashboards--widgets--settings"></a>
### Nested Schema for `dashboards.widgets.settings`

Read-Only:

- `display_type` (String)


