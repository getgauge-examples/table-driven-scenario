# Sample [Gauge](https://gauge.org) Project illustrating table driven scenario.

Refer to [this Pull Request](https://github.com/getgauge/gauge/pull/1202) for change details

Refer to [this issue]() for context on why we need this feature.

- this example illustrates the execution of a scenario against a datatable defined in a scenario.
- this feature is marked experimental, and needs to be toggled on by setting `allow_scenario_datatable=true` as an environment variable.
- in this project `allow_scenario_datatable=true` is set in `env/default/default.properties`
- *note 1* that external scenario is not supported.
- *note 2* no plugins support this, so reports and IDE plugins will not support this feature.