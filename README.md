# AWS Kinesis (kinesis)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
