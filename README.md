Sanity for Experitest Cloud
=========

This role will perform sanity tests on Experitest Cloud

Requirements
------------
This role needs to run on dedicated Linux machine that has UI.

Role Variables
--------------
To run this role - need to provide the following parameters of Experitet Cloud

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| url | cloud full URL to access (including https) | string |  | yes |
| username | cloud admin username | string |  | yes |
| password | cloud admin password | string |  | yes |

