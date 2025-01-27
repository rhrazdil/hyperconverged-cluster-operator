# Hyperconverged Cluster Operator metrics
This document aims to help users that are not familiar with metrics exposed by the Hyperconverged Cluster Operator.
All metrics documented here are auto-generated by the utility tool `tools/metricsdocs` and reflects exactly what is being exposed.

## Hyperconverged Cluster Operator Metrics List
### kubevirt_hco_out_of_band_modifications_count
Count of out-of-band modifications overwritten by HCO
### kubevirt_hco_unsafe_modification_count
Count of unsafe modifications in the HyperConverged annotations
## Developing new metrics
After developing new metrics or changing old ones, please run `make generate-doc` to regenerate this document.

If you feel that the new metric doesn't follow these rules, please change `tools/metricsdocs` with your needs.
