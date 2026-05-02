# AWS Kinesis (kinesis)
Amazon Kinesis is a family of fully managed AWS services for collecting, processing, and analyzing real-time streaming data. The family includes Kinesis Data Streams for scalable record ingestion, Amazon Data Firehose (formerly Kinesis Data Firehose) for delivery to data lakes and analytics destinations, Amazon Managed Service for Apache Flink (formerly Kinesis Data Analytics) for stateful stream processing, and Kinesis Video Streams for ingest and playback of media from connected devices.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/kinesis/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Analytics, Apache Flink, AWS, Big Data, Data Processing, Real-Time, Streaming, Video

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-28

## APIs

### Amazon Kinesis Data Streams API
Amazon Kinesis Data Streams is a scalable and durable real-time data streaming service that can continuously capture gigabytes of data per second from hundreds of thousands of sources. The API supports stream creation and lifecycle management, record put and get operations, shard discovery and resharding, enhanced fan-out consumers, and stream consumer registration for downstream processing.

**Human URL:** [https://aws.amazon.com/kinesis/data-streams/](https://aws.amazon.com/kinesis/data-streams/)

**Base URL:** https://kinesis.{region}.amazonaws.com

#### Tags:

 - Data Streams, Ingestion, Real-Time, Streaming

#### Properties

- [Documentation](https://docs.aws.amazon.com/kinesis/latest/APIReference/)
- [OpenAPI](openapi/amazon-kinesis-data-streams-openapi-original.yml)
- [Pricing](https://aws.amazon.com/kinesis/data-streams/pricing/)
- [GettingStarted](https://aws.amazon.com/kinesis/data-streams/getting-started/)
- [FAQ](https://aws.amazon.com/kinesis/data-streams/faqs/)
- [DeveloperGuide](https://docs.aws.amazon.com/streams/latest/dev/introduction.html)
- [Security](https://docs.aws.amazon.com/streams/latest/dev/security.html)
- [Customers](https://aws.amazon.com/kinesis/data-streams/customers/)
- [Integrations](https://aws.amazon.com/kinesis/data-streams/integrations/)

### Amazon Data Firehose API
Amazon Data Firehose (formerly Amazon Kinesis Data Firehose) is the easiest way to reliably load streaming data into data lakes, data stores, and analytics services. Firehose can capture, transform with Lambda or built-in conversions, and deliver streaming data to Amazon S3, Amazon Redshift, Amazon OpenSearch Service, Splunk, and supported partner destinations with automatic scaling and retry handling.

**Human URL:** [https://aws.amazon.com/firehose/](https://aws.amazon.com/firehose/)

**Base URL:** https://firehose.{region}.amazonaws.com

#### Tags:

 - Data Delivery, ETL, Streaming

#### Properties

- [Documentation](https://docs.aws.amazon.com/firehose/latest/APIReference/)
- [OpenAPI](openapi/amazon-data-firehose-openapi-original.yml)
- [Pricing](https://aws.amazon.com/kinesis/data-firehose/pricing/)
- [GettingStarted](https://aws.amazon.com/kinesis/data-firehose/getting-started/)
- [FAQ](https://aws.amazon.com/kinesis/data-firehose/faqs/)
- [DeveloperGuide](https://docs.aws.amazon.com/firehose/latest/dev/what-is-this-service.html)

### Amazon Kinesis Data Analytics API
Amazon Kinesis Data Analytics is a managed service for analyzing streaming data using SQL or Apache Flink. The API enables creation and management of streaming applications, input and output stream configuration, application code deployment, and runtime monitoring, enabling near real-time insights and event-driven actions on continuously arriving data.

**Human URL:** [https://aws.amazon.com/kinesis/data-analytics/](https://aws.amazon.com/kinesis/data-analytics/)

**Base URL:** https://kinesisanalytics.{region}.amazonaws.com

#### Tags:

 - Analytics, Apache Flink, SQL, Streaming

#### Properties

- [Documentation](https://docs.aws.amazon.com/kinesisanalytics/latest/apiv2/)
- [OpenAPI](openapi/amazon-kinesis-data-analytics-openapi-original.yml)
- [Pricing](https://aws.amazon.com/kinesis/data-analytics/pricing/)
- [GettingStarted](https://aws.amazon.com/kinesis/data-analytics/getting-started/)
- [FAQ](https://aws.amazon.com/kinesis/data-analytics/faqs/)
- [DeveloperGuide](https://docs.aws.amazon.com/kinesisanalytics/latest/dev/how-it-works.html)
- [Security](https://docs.aws.amazon.com/kinesisanalytics/latest/dev/security.html)

### Amazon Managed Service for Apache Flink API
Amazon Managed Service for Apache Flink (formerly Amazon Kinesis Data Analytics for Apache Flink) is a fully managed service for processing and analyzing streaming data using Apache Flink. Developers build streaming applications in Java, Python, SQL, or Scala, and the service handles infrastructure provisioning, scaling, state management, and high availability for stateful stream processing.

**Human URL:** [https://aws.amazon.com/managed-service-apache-flink/](https://aws.amazon.com/managed-service-apache-flink/)

**Base URL:** https://kinesisanalytics.{region}.amazonaws.com

#### Tags:

 - Analytics, Apache Flink, Real-Time, Streaming

#### Properties

- [Documentation](https://docs.aws.amazon.com/managed-flink/latest/apiv2/Welcome.html)
- [DeveloperGuide](https://docs.aws.amazon.com/managed-flink/latest/java/getting-started.html)
- [Pricing](https://aws.amazon.com/managed-service-apache-flink/pricing/)
- [GettingStarted](https://aws.amazon.com/managed-service-apache-flink/getting-started/)
- [FAQ](https://aws.amazon.com/managed-service-apache-flink/faqs/)

### Amazon Kinesis Video Streams API
Amazon Kinesis Video Streams makes it easy to securely stream video, audio, and time-encoded data from connected devices to AWS for analytics, machine learning, playback, and other processing. The API supports stream lifecycle management, media ingest and retrieval, HLS and DASH playback URL generation, signaling for WebRTC peer connections, and integration with AWS Rekognition for video analysis.

**Human URL:** [https://aws.amazon.com/kinesis/video-streams/](https://aws.amazon.com/kinesis/video-streams/)

**Base URL:** https://kinesisvideo.{region}.amazonaws.com

#### Tags:

 - IoT, Machine Learning, Streaming, Video, WebRTC

#### Properties

- [Documentation](https://docs.aws.amazon.com/kinesisvideostreams/latest/dg/API_Reference.html)
- [OpenAPI](openapi/amazon-kinesis-video-streams-openapi-original.yml)
- [Pricing](https://aws.amazon.com/kinesis/video-streams/pricing/)
- [GettingStarted](https://aws.amazon.com/kinesis/video-streams/getting-started/)
- [FAQ](https://aws.amazon.com/kinesis/video-streams/faqs/)
- [DeveloperGuide](https://docs.aws.amazon.com/kinesisvideostreams/latest/dg/what-is-kinesis-video.html)
- [Security](https://docs.aws.amazon.com/kinesisvideostreams/latest/dg/security.html)
- [Customers](https://aws.amazon.com/kinesis/video-streams/customers/)
- [Features](https://aws.amazon.com/kinesis/video-streams/features/)
- [Resources](https://aws.amazon.com/kinesis/video-streams/resources/)
- [WebRTCGuide](https://docs.aws.amazon.com/kinesisvideostreams-webrtc-dg/latest/devguide/what-is-kvswebrtc.html)

## Common Properties

- [Website](https://aws.amazon.com/kinesis/)
- [Documentation](https://docs.aws.amazon.com/kinesis/)
- [Blog](https://aws.amazon.com/blogs/big-data/category/analytics/amazon-kinesis/)
- [Console](https://console.aws.amazon.com/kinesis/)
- [SDKs](https://aws.amazon.com/tools/)
- [StatusPage](https://status.aws.amazon.com/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [SLA](https://aws.amazon.com/kinesis/sla/)
- [GettingStarted](https://aws.amazon.com/kinesis/getting-started/)
- [Legal](https://aws.amazon.com/legal/service-level-agreements/)
- [Contact](https://aws.amazon.com/contact-us/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
