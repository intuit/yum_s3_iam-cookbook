[![Build Status](https://secure.travis-ci.org/intuit/yum_s3_iam-cookbook.png)](http://travis-ci.org/intuit/yum_s3_iam-cookbook)

yum_s3_iam-cookbook
===================

Cookbook for installing yum-s3-iam

# Requirements
* Chef 10.x
* Chef 11.x

Platform:
* CentOS 6.x
* RHEL 6.x

# Attributes
## Default
`node['yum_s3_iam']['repo_name']` - Default value: 'our repo'

`node['yum_s3_iam']['repo_description']` - Default value: 'our package repo'

`node['yum_s3_iam']['repo_bucket']` - Default value: 'http://our-bucket-name.s3.amazonaws.com'

# Recipes
## default
Installs `yum-s3-iam` package and configures a yum repo with S3/IAM support.

# License

See `LICENSE` file
