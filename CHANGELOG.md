## 1.3.0 (Unreleased)
## 1.2.0 (November 02, 2018)

FEATURES:

* **New Data Source** `newrelic_alert_policy` ([#34](https://github.com/terraform-providers/terraform-provider-newrelic/issues/34))

IMPROVEMENTS:

* `newrelic_infra_alert_condition`: Add support for `integration_provider` ([#48](https://github.com/terraform-providers/terraform-provider-newrelic/issues/48))
* `newrelic_dashboard`: Add support for `filter` ([#46](https://github.com/terraform-providers/terraform-provider-newrelic/issues/46))

## 1.1.0 (October 16, 2018)

FEATURES:

* **New Resource** `newrelic_synthetics_alert_condition` ([#22](https://github.com/terraform-providers/terraform-provider-newrelic/pull/22))
* **New Data Source** `newrelic_synthetics_monitor` ([#22](https://github.com/terraform-providers/terraform-provider-newrelic/pull/22))

BUG FIXES:

* `newrelic_alert_policy` int64 bug ([#42](https://github.com/terraform-providers/terraform-provider-newrelic/pull/42))
* Missing doc links ([#49](https://github.com/terraform-providers/terraform-provider-newrelic/pull/49))

## 1.0.1 (June 06, 2018)

FEATURES:

* **New Resource** `newrelic_infra_alert_condition` ([#30](https://github.com/terraform-providers/terraform-provider-newrelic/pull/30))

## 1.0.0 (February 12, 2018)

FEATURES:

* **New Resource** `newrelic_dashboard` ([#26](https://github.com/terraform-providers/terraform-provider-newrelic/pull/26))
* **New Data Source** `newrelic_key_transaction` ([#21](https://github.com/terraform-providers/terraform-provider-newrelic/pull/21))

IMPROVEMENTS:

* resource/newrelic_alert_condition: Add support for `apm_jvm_metric` and instance scope alerts ([#24](https://github.com/terraform-providers/terraform-provider-newrelic/pull/24))

## 0.1.1 (August 02, 2017)

FEATURES:

* **New Resource:** `newrelic_nrql_alert_condition` ([#15](https://github.com/terraform-providers/terraform-provider-newrelic/issues/15))

IMPROVEMENTS:

* resource/newrelic_alert_condition: Allow zero threshold value for terms ([#13](https://github.com/terraform-providers/terraform-provider-newrelic/issues/13))

## 0.1.0 (June 21, 2017)

NOTES:

* Same functionality as that of Terraform 0.9.8. Repacked as part of [Provider Splitout](https://www.hashicorp.com/blog/upcoming-provider-changes-in-terraform-0-10/)
