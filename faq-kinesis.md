
# AWS Kinesis FAQs

[https://aws.amazon.com/kinesis/streams/faqs/](https://aws.amazon.com/kinesis/streams/faqs/)

- The throughput of an Amazon Kinesis stream is designed to scale without limits via increasing the number of shards within a stream. 
- By default, Records of a stream are accessible for up to 24 hours from the time they are added to the stream. You can raise this limit to up to 7 days by enabling extended data retention.
- The maximum size of a data blob (the data payload before Base64-encoding) within one record is 1 megabyte (MB). 
- Each shard can support up to 1000 PUT records per second.

