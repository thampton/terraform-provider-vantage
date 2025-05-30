---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "vantage_cost_alert Resource - terraform-provider-vantage"
subcategory: ""
description: |-
  
---

# vantage_cost_alert (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `interval` (String) The period of time used to compare costs. Options are 'day', 'week', 'month', 'quarter'.
- `threshold` (Number) The threshold value for the Cost Alert.
- `title` (String) The title of the Cost Alert.
- `unit_type` (String) The unit type used to compare costs. Options are 'currency' or 'percentage'.
- `workspace_token` (String) The token of the Workspace to add the Cost Alert to.

### Optional

- `email_recipients` (List of String) The email recipients for the Cost Alert.
- `report_tokens` (List of String) The tokens of the reports to alert on.
- `slack_channels` (List of String) The Slack channels that will receive the alert.
- `teams_channels` (List of String) The Microsoft Teams channels that will receive the alert.

### Read-Only

- `created_at` (String) The date and time, in UTC, for when the alert was created. ISO 8601 Formatted.
- `token` (String) The token of the cost alert
- `updated_at` (String) The date and time, in UTC, for when the alert was last updated. ISO 8601 Formatted.


