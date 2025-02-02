---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "onelogin_rules Resource - terraform-provider-onelogin"
subcategory: ""
description: |-
  
---

# onelogin_rules (Resource)





<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `description` (String)
- `filters` (List of String) A list of IP addresses or country codes or names to evaluate against each event.
- `name` (String) The name of this rule
- `source` (Block List, Max: 1) Used for targeting custom rules based on a group of people, customers, accounts, or even a single user. (see [below for nested schema](#nestedblock--source))
- `target` (String) The target parameter that will be used when evaluating the rule against an incoming event.
- `timeouts` (Block, Optional) (see [below for nested schema](#nestedblock--timeouts))
- `type` (String) The type parameter specifies the type of rule that will be created.

### Read-Only

- `id` (String) The ID of this resource.

<a id="nestedblock--source"></a>
### Nested Schema for `source`

Optional:

- `id` (String) A unique id that represents the source of the event.
- `name` (String) The name of the source


<a id="nestedblock--timeouts"></a>
### Nested Schema for `timeouts`

Optional:

- `default` (String)


