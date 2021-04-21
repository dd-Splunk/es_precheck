# ES Precheck

A single Splunk dashboard that checks the various Datamodels expected by Enterprise Security.

There are two macros defined in `es_precheck/default/macros.conf` that can be tailored to alter the check behaviour:

**es-indexes**
Lists all indexes to be searched for relevant data. By default all indexes are searched.

**es-dm**
Lists the relevant ES Datamodels to be included in the checks.

