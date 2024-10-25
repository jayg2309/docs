---
title: kestra_group
editLink: false
description: |-
  Use this data source to access information about an existing Kestra Group.
---

# kestra_group (Data Source)

Use this data source to access information about an existing Kestra Group.

## Example Usage

```hcl
data "kestra_group" "example" {
  group_id = "68xAawPfiJPkTkZJIPX6jQ"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `group_id` (String) The group.

### Optional

- `namespace` (String) The linked namespace.

### Read-Only

- `description` (String) The group description.
- `id` (String) The ID of this resource.
- `name` (String) The group name.
- `tenant_id` (String) The tenant id.
