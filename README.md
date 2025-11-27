Terraform module which creates AMQP,RAM and cloudMonitor instance on Alibaba Cloud  

terraform-alicloud-amqp-ram-cloudmonitor
---

English | [简体中文](README-CN.md)

This module is used to create an Alibaba Cloud AMQ,RAM and cloudMonitor

These types of resources are supported:

* [alicloud_amqp_instance](https://registry.terraform.io/providers/aliyun/alicloud/latest/docs/resources/amqp_instance)
* [alicloud_cloud_ram](https://registry.terraform.io/providers/aliyun/alicloud/latest/docs/resources/ram_user)
* [alicloud_cloud_monitor_instance](https://registry.terraform.io/providers/aliyun/alicloud/latest/docs/resources/cms_alarm)



## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | > = 0.13.0 |
| <a name="requirement_alicloud"></a> [alicloud](#requirement\_alicloud) | > = 1.128.0 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_alicloud"></a> [alicloud](#provider\_alicloud) | > = 1.128.0 |

## Usage

<div style="display: block;margin-bottom: 40px;"><div class="oics-button" style="float: right;position: absolute;margin-bottom: 10px;">
  <a href="https://api.aliyun.com/terraform?source=Module&activeTab=document&sourcePath=terraform-alicloud-modules%3A%3Aamqp-ram-cloudmonitor&spm=docs.m.terraform-alicloud-modules.amqp-ram-cloudmonitor&intl_lang=EN_US" target="_blank">
    <img alt="Open in AliCloud" src="https://img.alicdn.com/imgextra/i1/O1CN01hjjqXv1uYUlY56FyX_!!6000000006049-55-tps-254-36.svg" style="max-height: 44px; max-width: 100%;">
  </a>
</div></div>

```hcl
module "tf-amqp-ram-cloudmonitor" {
  source            = "terraform-alicloud-modules/amqp-ram-cloudmonitor/alicloud"
}
```

## Notes

* This module using AccessKey and SecretKey are from `profile` and `shared_credentials_file`. If you have not set them
  yet, please install [aliyun-cli](https://github.com/aliyun/aliyun-cli#installation) and configure it.

## Submit Issues

If you have any problems when using this module, please opening
a [provider issue](https://github.com/aliyun/terraform-provider-alicloud/issues/new) and let us know.

**Note:** There does not recommend to open an issue on this repo.

## Authors

Created and maintained by Alibaba Cloud Terraform Team(terraform@alibabacloud.com)

## License

MIT Licensed. See LICENSE for full details.

## Reference

* [Terraform-Provider-Alicloud Github](https://github.com/aliyun/terraform-provider-alicloud)
* [Terraform-Provider-Alicloud Release](https://releases.hashicorp.com/terraform-provider-alicloud/)
* [Terraform-Provider-Alicloud Docs](https://registry.terraform.io/providers/aliyun/alicloud/latest/docs)