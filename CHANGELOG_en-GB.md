# 0.1.0

* First release in Store

# 0.1.1

* Added positive status message for the production mode check. 
* Administration view improvements.
* Added Max-Execution-Time check to system status.
* Adjusted sorting of Tasks and Caches.
* Added buttons to refresh data in all components.
* Added Diff-Function in Shopware-Files-Checker.
* Added Restore-Function in Shopware-Files-Checker.
* Added Feature Flag Manager

# 0.1.2

* Exclude inactive tasks from health check
* Sort feature-flags, add refresh-button onto feature-flags tab
* Added support for the new message incrementer

# 0.1.3

* New command "frosh:dev:robots-txt" to stop crawers in test environments
* New command "frosh:plugin:update" to update plugins with available updates at once
* Improve url of files in Shopware-Files-Checker

# 0.1.4

* New command "frosh:composer-plugin:update" to update plugins installed with composer
* Show IndexerName for TaskLogger
* Add manager for Elasticsearch
* Add performance checks

# 0.1.5

* Fix QueueChecker to show correct message

# 0.1.6

* Show formatted date in logs
* Correct empty Console body for newer Elasticsearch version

# 0.1.7

* Fixed theme compile button in Administration

# 0.2.0

* Fixed reschedule Task to not stack the nextExecutionTime
* Added env FROSH_TOOLS_TASK_LOGGING_INFO to log everything in tasks
* Changed FROSH_TOOLS_TASK_LOGGING to just log exceptions
* Fixed recommended value for IncrementStorage

# 0.2.1

* Fixed support to Enterprise Search

# 0.2.2

* Added more recommendations for performance
* Fix Redis for newer shopware versions

# 0.2.3

* Fix deprecation messages with 6.4.11 and higher for api
* Fix ini-check not to throw error when is has not set

# 0.2.4

* Fix support for restricted envirnments

# 0.2.5
* Added a first version of order, transaction and delivery state machine visualisations
