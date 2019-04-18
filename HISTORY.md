## Release History

### Version next

* Remove pspermgen from netuitive.jvm.non-heap.utilizationpercent and netuitive.jvm.totalmemory.utilizationpercent computation.

### Version 2.0.0

* Refresh JVM Element Details.
* Refresh Cluster Element Details.
* Refresh JVM Summary.

### Version 1.9.0

* Change elementType to elementTypes array.

### Version 1.8.0

* Add Cluster elementType to metric_meta in order to persist unit configurations.

### Version 1.7.0

* Convert computed metrics to new format
* Adjusted build to use metricly-cli for validation

### Version 1.6.0

* Added computed metrics for jvm non-heap and total memory utilization

### Version 1.5.0

* Updated element details dashboard layout
* Updated summary dashboard for new widget configs

### Version 1.4.0

* Updated gridstack layout for dashboards

### Version 1.3.0

* Removed the computed metric for average response time, since this is now included as a collected metric from the Java Agent.

### Version 1.2.4

* Updated package compatibilities.

### Version 1.2.3

* Added a lower threshold to the elevated CPU policy.

### Version 1.2.2

* Fixed bug with the Events widget on the Element Detail Page.

### Version 1.2.1

* Bug fix: Updated garbage collection time metrics to be of type COUNTER.

### Version 1.2.0

* Added Java-specific element detail page.
* Defined units for the metrics.

### Version 1.1.0

* Added summary dashboard.

### Version 1.0.0

* Initial production release of the package for monitoring Java method and JVM resources.
