### Description
The HDFS to Kafka Application Template continuously reads lines from configured Hadoop HDFS file(s) and writes each line as a message in configured Apache Kafka topic.
- The application scales linearly with the number of record readers and number of Kafka brokers.
- The application is fault tolerant and can withstand node and cluster outages without data loss.
- The application is also highly performant and can process as fast as Kafka broker can consume per topic.
- It is extremely easy to add custom logic to get your business value without worrying about connectivity and operational details of Kafka consumer and HDFS reader.
- The only configuration user needs to provide is source HDFS path and destination Kafka broker list, topic.
- This enterprise grade application template will dramatically reduce your time to market and cost of operations.

Import the application from DataTorrent AppHub and launch it to read your data from HDFS and write to Kafka. Follow the tutorial videos or walkthrough document below to launch the template and add custom logic to process the data during ingestion.

### Tested with external sources
- Output Source:- Kafka (version: 0.9)

### Jumpstart
Import and run application template as an operable proof of concept. Please watch the [walkthrough video](https://www.youtube.com/watch?v=AZ-QnsiNwyg) to import and launch the application.

<iframe src="https://www.youtube.com/embed/AZ-QnsiNwyg?enablejsapi=1" allowfullscreen="allowfullscreen" class="video" id="basicVideo" ga-track="basicVideo"></iframe>

### Productize
Add custom logic to the application template and launch. Please watch the [walkthrough video](https://www.youtube.com/watch?v=ftMiPECgyDQ) to add custom logic to the application template.

<iframe src="https://www.youtube.com/embed/ftMiPECgyDQ?enablejsapi=1" allowfullscreen="allowfullscreen" class="video" id="advancedVideo" ga-track="advancedVideo"></iframe>

### Logical Plan

Here is a preview of the logical plan of the application template

![Logical Plan](http://datatorrent.com/wp-content/uploads/2016/11/HDFS_Kafka_DAG.png)

### Launch App Properties

Here is a preview of the properties to be set at application launch

![Launch App Properties](http://datatorrent.com/wp-content/uploads/2016/11/HDFS_Kafka_properties.png)

### Resources

Please find the walkthrough docs for app template as follows:

&nbsp; <a href="http://docs.datatorrent.com/app-templates/hdfs-to-kafka-sync/"  class="docs" id="docs" ga-track="docs" target="_blank">http://docs.datatorrent.com/app-templates/hdfs-to-kafka-sync/</a>

Please find the GitHub URL for app template as follows:

&nbsp; <a href="https://github.com/DataTorrent/app-templates/tree/master/hdfs-to-kafka-sync"  class="github" id="github" ga-track="github" target="_blank">https://github.com/DataTorrent/app-templates/tree/master/hdfs-to-kafka-sync</a>

Please send feedback or feature requests to:

&nbsp; <a href="mailto:feedback@datatorrent.com"  class="feedback" id="feedback" ga-track="feedback">feedback@datatorrent.com</a>

Please join the user discussion groups:

&nbsp; <a href="mailto:dt-users@googlegroups.com"  class="maillist" id="maillist" ga-track="maillist">dt-users@googlegroups.com</a>
