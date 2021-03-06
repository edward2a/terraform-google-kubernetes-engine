# Changelog


## [v0.5.0] - 2019-08-02
### Changed (from commit 67fe85a01be2bca7b52826314036f484d4f3747f)
* Workaround additional_zones issue with single-zone configuration for zonal cluster

### Changed (up to commit 67fe85a01be2bca7b52826314036f484d4f3747f)
* Set `horizontal_pod_autoscaling` to `true` by default. #42
* Add `remove_default_node_pool` set to `false` by default #15
* Allow arbitrary key-value pairs to be set on node pool metadata. #52
* Add `initial_node_count` parameter to node_pool block. #60

## [v0.4.0] - 2018-12-19
### Added
* Added support for testing with kitchen-terraform. #33
* Added support for preemptible nodes. #38

### Changed
* Updated default version to `1.10.6`. #31

### Fixed
* `region` argument on google_compute_subnetwork caused errors. #22
* Added check to wait for GKE cluster to be `READY` before completing. #46

## [v0.3.0] - 2018-10-10
### Changed
* Updated network/subnetwork lookup to use data source. #16
* Make zone configuration optional when creating a regional cluster. #19

## [v0.2.0] - 2018-09-26

### Added

* Support for configuring master authorized networks. (#10)
* Support specifying monitoring and logging services. (#9)

## [v0.1.0] - 2018-09-12

### Added

* Initial release of module.
