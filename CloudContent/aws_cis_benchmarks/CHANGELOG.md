<a name="unreleased"></a>
## [Unreleased]


<a name="0.11.0"></a>
## [0.11.0] - 2019-06-06

<a name="0.10.0"></a>
## [0.10.0] - 2019-05-25
### Feat
- upgrade to terraform 0.12


<a name="0.9.0"></a>
## [0.9.0] - 2019-04-06
### Feat
- enable SecurityHub and CIS standard subscription
- add eu-north-1 region support


<a name="0.8.0"></a>
## [0.8.0] - 2019-04-03
### Feat
- add eu-north-1 region support

### Fix
- remove a default subnet resource


<a name="0.7.0"></a>
## [0.7.0] - 2019-02-11
### Fix
- create a log group for VPC Flow Logs in each region


<a name="0.6.0"></a>
## [0.6.0] - 2018-11-23
### Feat
- enable managed config rules for benchmark compliance


<a name="0.5.0"></a>
## [0.5.0] - 2018-08-05
### Feat
- enable GuardDuty in Paris region.

### Fix
- Change how to workaround the default ACL issue.


<a name="0.4.1"></a>
## [0.4.1] - 2018-05-27
### Fix
- create a global rule after recorders.


<a name="0.4.0"></a>
## [0.4.0] - 2018-05-27
### Feat
- enable AWS Config rules for monitoring


<a name="0.3.0"></a>
## [0.3.0] - 2018-05-19
### Feat
- automatically archive audit logs into Amazon Glacier


<a name="0.2.1"></a>
## [0.2.1] - 2018-04-01
### Fix
- temporarily disable mfa_delete on secure buckets


<a name="0.2.0"></a>
## [0.2.0] - 2018-04-01
### Feat
- enable versioning with secure buckets


<a name="0.1.1"></a>
## [0.1.1] - 2018-03-20
### Fix
- omit GuardDuty config for eu-west-3 region until supported


<a name="0.1.0"></a>
## [0.1.0] - 2018-03-11
### Feat
- add various outputs

### Fix
- update var names in the CI script


<a name="0.0.5"></a>
## [0.0.5] - 2018-02-17
### Feat
- add IAM baseline module

### Refactor
- use consistent resource namings


<a name="0.0.4"></a>
## [0.0.4] - 2018-02-12
### Feat
- enable GuardDuty in all regions


<a name="0.0.3"></a>
## [0.0.3] - 2018-02-12
### Feat
- output an ID of the audit log bucket

### Fix
- broken output value


<a name="0.0.2"></a>
## [0.0.2] - 2018-02-12

<a name="0.0.1"></a>
## 0.0.1 - 2018-02-12

[Unreleased]: https://github.com/nozaq/terraform-aws-secure-baseline/compare/0.11.0...HEAD
[0.11.0]: https://github.com/nozaq/terraform-aws-secure-baseline/compare/0.10.0...0.11.0
[0.10.0]: https://github.com/nozaq/terraform-aws-secure-baseline/compare/0.9.0...0.10.0
[0.9.0]: https://github.com/nozaq/terraform-aws-secure-baseline/compare/0.8.0...0.9.0
[0.8.0]: https://github.com/nozaq/terraform-aws-secure-baseline/compare/0.7.0...0.8.0
[0.7.0]: https://github.com/nozaq/terraform-aws-secure-baseline/compare/0.6.0...0.7.0
[0.6.0]: https://github.com/nozaq/terraform-aws-secure-baseline/compare/0.5.0...0.6.0
[0.5.0]: https://github.com/nozaq/terraform-aws-secure-baseline/compare/0.4.1...0.5.0
[0.4.1]: https://github.com/nozaq/terraform-aws-secure-baseline/compare/0.4.0...0.4.1
[0.4.0]: https://github.com/nozaq/terraform-aws-secure-baseline/compare/0.3.0...0.4.0
[0.3.0]: https://github.com/nozaq/terraform-aws-secure-baseline/compare/0.2.1...0.3.0
[0.2.1]: https://github.com/nozaq/terraform-aws-secure-baseline/compare/0.2.0...0.2.1
[0.2.0]: https://github.com/nozaq/terraform-aws-secure-baseline/compare/0.1.1...0.2.0
[0.1.1]: https://github.com/nozaq/terraform-aws-secure-baseline/compare/0.1.0...0.1.1
[0.1.0]: https://github.com/nozaq/terraform-aws-secure-baseline/compare/0.0.5...0.1.0
[0.0.5]: https://github.com/nozaq/terraform-aws-secure-baseline/compare/0.0.4...0.0.5
[0.0.4]: https://github.com/nozaq/terraform-aws-secure-baseline/compare/0.0.3...0.0.4
[0.0.3]: https://github.com/nozaq/terraform-aws-secure-baseline/compare/0.0.2...0.0.3
[0.0.2]: https://github.com/nozaq/terraform-aws-secure-baseline/compare/0.0.1...0.0.2
