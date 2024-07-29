**Cloud Watch metrics**
Metrics belong to namespaces
Up to 30 dimensions per metric

**CloudWatch Metric Streams**
• Amazon Kinesis Data Firehose (and then its destinations)
• 3rd party service provider: Datadog, Dynatrace, New Relic, Splunk, Sumo Logic…

**CloudWatch Custom Metrics**
Use API call **PutMetricData**
Metric resolution (StorageResolution API parameter – two possible value):
• Standard: 1 minute (60 seconds)
• High Resolution: 1/5/10/30 second(s) – **Higher cos**
**Important:** Accepts metric data points **two weeks in the past and two hours in the future** (make sure to configure your EC2 instance time correctly)
