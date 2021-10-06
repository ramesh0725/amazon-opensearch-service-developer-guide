# Supported instance types in Amazon OpenSearch Service<a name="supported-instance-types"></a>

Amazon OpenSearch Service supports the following instance types\. Not all Regions support all instance types\. For availability details, see [Amazon OpenSearch Service pricing](https://aws.amazon.com/elasticsearch-service/pricing/)\.

For information about which instance type is appropriate for your use case, see [Sizing Amazon OpenSearch Service domains](sizing-domains.md), [EBS volume size limits](limits.md#ebsresource), and [Network limits](limits.md#network-limits)\.


****  

| Instance type | Restrictions | 
| --- | --- | 
|  C4  |    | 
|  C5  |  The C5 instance types require Elasticsearch 5\.1 or later or any version of OpenSearch\.  | 
| C6G  |  [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/opensearch-service/latest/developerguide/supported-instance-types.html)  | 
|  I2  |    | 
|  I3  | The I3 instance types require Elasticsearch 5\.1 or later or any version of OpenSearch, and do not support EBS storage volumes\. | 
|  M3  |  The M3 instance types do not support encryption of data at rest, fine\-grained access control, or cross\-cluster search\. The M3 instance types have additional restrictions by Elasticsearch version\. To learn more, see [Invalid M3 instance type](handling-errors.md#m3-instance-types)\.  | 
|  M4  |    | 
|  M5  |  The M5 instance types require Elasticsearch 5\.1 or later or any version of OpenSearch\.  | 
| M6G |  [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/opensearch-service/latest/developerguide/supported-instance-types.html)  | 
|  R3  |  The R3 instance types do not support encryption of data at rest or fine\-grained access control\.  | 
|  R4  |    | 
|  R5  |  The R5 instance types require Elasticsearch 5\.1 or later or any version of OpenSearch\.  | 
| R6G |  [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/opensearch-service/latest/developerguide/supported-instance-types.html)  | 
| R6GD |  [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/opensearch-service/latest/developerguide/supported-instance-types.html)  | 
|  T2  |  [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/opensearch-service/latest/developerguide/supported-instance-types.html)  | 
|  T3  |  [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/opensearch-service/latest/developerguide/supported-instance-types.html)  | 

**Tip**  
We often recommend different instance types for [dedicated master nodes](managedomains-dedicatedmasternodes.md) and data nodes\.