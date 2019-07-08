# ![LOGO](logo.png) Amazon Simple Storage Service **flow**ground Connector

## Description

A generated **flow**ground connector for the Amazon Simple Storage Service API (version 2006-03-01).

Generated from: https://api.apis.guru/v2/specs/amazonaws.com/s3/2006-03-01/swagger.json<br/>
Generated at: 2019-07-08T14:13:20+03:00

## API Description

<p/>

## Authorization

Supported authorization schemes:
- API Key
## Actions

### ListBuckets
> Returns a list of all buckets owned by the authenticated sender of the request.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTServiceGET.html</p><br/>

#### Input Parameters
* `x-amz-security-token` - _optional_

### CreateBucket
> Creates a new bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUT.html</p><br/>

#### Input Parameters
* `Bucket` - _required_

### DeleteBucket
> Deletes the bucket. All objects (including all object versions and Delete Markers) in the bucket must be deleted before the bucket itself can be deleted.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketDELETE.html</p><br/>

#### Input Parameters
* `Bucket` - _required_

### DeleteBucketAnalyticsConfiguration
> Deletes an analytics configuration for the bucket (specified by the analytics configuration ID).<br/>

#### Input Parameters
* `analytics` - _required_
* `Bucket` - _required_

### DeleteBucketCors
> Deletes the CORS configuration information set for the bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketDELETEcors.html</p><br/>

#### Input Parameters
* `cors` - _required_
* `Bucket` - _required_

### DeleteBucketEncryption
> Deletes the server-side encryption configuration from the bucket.<br/>

#### Input Parameters
* `encryption` - _required_
* `Bucket` - _required_

### DeleteBucketInventoryConfiguration
> Deletes an inventory configuration (identified by the inventory ID) from the bucket.<br/>

#### Input Parameters
* `inventory` - _required_
* `Bucket` - _required_

### DeleteBucketLifecycle
> Deletes the lifecycle configuration from the bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketDELETElifecycle.html</p><br/>

#### Input Parameters
* `lifecycle` - _required_
* `Bucket` - _required_

### DeleteBucketMetricsConfiguration
> Deletes a metrics configuration (specified by the metrics configuration ID) from the bucket.<br/>

#### Input Parameters
* `metrics` - _required_
* `Bucket` - _required_

### DeleteBucketPolicy
> Deletes the policy from the bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketDELETEpolicy.html</p><br/>

#### Input Parameters
* `policy` - _required_
* `Bucket` - _required_

### DeleteBucketReplication
> Deletes the replication configuration from the bucket. For information about replication configuration, see <a href=" https://docs.aws.amazon.com/AmazonS3/latest/dev/crr.html">Cross-Region Replication (CRR)</a> in the <i>Amazon S3 Developer Guide</i>.<br/>

#### Input Parameters
* `replication` - _required_
* `Bucket` - _required_

### DeleteBucketTagging
> Deletes the tags from the bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketDELETEtagging.html</p><br/>

#### Input Parameters
* `tagging` - _required_
* `Bucket` - _required_

### DeleteBucketWebsite
> This operation removes the website configuration from the bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketDELETEwebsite.html</p><br/>

#### Input Parameters
* `website` - _required_
* `Bucket` - _required_

### DeleteObjects
> This operation enables you to delete multiple objects from a bucket using a single HTTP request. You may specify up to 1000 keys.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/multiobjectdeleteapi.html</p><br/>

#### Input Parameters
* `delete` - _required_
* `Bucket` - _required_

### DeletePublicAccessBlock
> Removes the <code>PublicAccessBlock</code> configuration from an Amazon S3 bucket.<br/>

#### Input Parameters
* `publicAccessBlock` - _required_
* `Bucket` - _required_

### GetBucketAccelerateConfiguration
> Returns the accelerate configuration of a bucket.<br/>

#### Input Parameters
* `accelerate` - _required_
* `Bucket` - _required_

### GetBucketAcl
> Gets the access control policy for the bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETacl.html</p><br/>

#### Input Parameters
* `acl` - _required_
* `Bucket` - _required_

### GetBucketAnalyticsConfiguration
> Gets an analytics configuration for the bucket (specified by the analytics configuration ID).<br/>

#### Input Parameters
* `analytics` - _required_
* `Bucket` - _required_

### GetBucketCors
> Returns the CORS configuration for the bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETcors.html</p><br/>

#### Input Parameters
* `cors` - _required_
* `Bucket` - _required_

### GetBucketEncryption
> Returns the server-side encryption configuration of a bucket.<br/>

#### Input Parameters
* `encryption` - _required_
* `Bucket` - _required_

### GetBucketInventoryConfiguration
> Returns an inventory configuration (identified by the inventory ID) from the bucket.<br/>

#### Input Parameters
* `inventory` - _required_
* `Bucket` - _required_

### GetBucketLifecycle
> No longer used, see the GetBucketLifecycleConfiguration operation.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETlifecycle.html</p><br/>

#### Input Parameters
* `lifecycle` - _required_
* `Bucket` - _required_

### GetBucketLifecycleConfiguration
> Returns the lifecycle configuration information set on the bucket.<br/>

#### Input Parameters
* `lifecycle` - _required_
* `Bucket` - _required_

### GetBucketLocation
> Returns the region the bucket resides in.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETlocation.html</p><br/>

#### Input Parameters
* `location` - _required_
* `Bucket` - _required_

### GetBucketLogging
> Returns the logging status of a bucket and the permissions users have to view and modify that status. To use GET, you must be the bucket owner.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETlogging.html</p><br/>

#### Input Parameters
* `logging` - _required_
* `Bucket` - _required_

### GetBucketMetricsConfiguration
> Gets a metrics configuration (specified by the metrics configuration ID) from the bucket.<br/>

#### Input Parameters
* `metrics` - _required_
* `Bucket` - _required_

### GetBucketNotification
> No longer used, see the GetBucketNotificationConfiguration operation.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETnotification.html</p><br/>

#### Input Parameters
* `notification` - _required_
* `Bucket` - _required_

### GetBucketNotificationConfiguration
> Returns the notification configuration of a bucket.<br/>

#### Input Parameters
* `notification` - _required_
* `Bucket` - _required_

### GetBucketPolicy
> Returns the policy of a specified bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETpolicy.html</p><br/>

#### Input Parameters
* `policy` - _required_
* `Bucket` - _required_

### GetBucketPolicyStatus
> Retrieves the policy status for an Amazon S3 bucket, indicating whether the bucket is public.<br/>

#### Input Parameters
* `policyStatus` - _required_
* `Bucket` - _required_

### GetBucketReplication
<blockquote><p>Returns the replication configuration of a bucket.</p> <note> <p> It can take a while to propagate the put or delete a replication configuration to all Amazon S3 systems. Therefore, a get request soon after put or delete can return a wrong result. </p> </note></blockquote>

#### Input Parameters
* `replication` - _required_
* `Bucket` - _required_

### GetBucketRequestPayment
> Returns the request payment configuration of a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTrequestPaymentGET.html</p><br/>

#### Input Parameters
* `requestPayment` - _required_
* `Bucket` - _required_

### GetBucketTagging
> Returns the tag set associated with the bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETtagging.html</p><br/>

#### Input Parameters
* `tagging` - _required_
* `Bucket` - _required_

### GetBucketVersioning
> Returns the versioning state of a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETversioningStatus.html</p><br/>

#### Input Parameters
* `versioning` - _required_
* `Bucket` - _required_

### GetBucketWebsite
> Returns the website configuration for a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETwebsite.html</p><br/>

#### Input Parameters
* `website` - _required_
* `Bucket` - _required_

### GetObjectLockConfiguration
> Gets the Object Lock configuration for a bucket. The rule specified in the Object Lock configuration will be applied by default to every new object placed in the specified bucket.<br/>

#### Input Parameters
* `object-lock` - _required_
* `Bucket` - _required_

### GetPublicAccessBlock
> Retrieves the <code>PublicAccessBlock</code> configuration for an Amazon S3 bucket.<br/>

#### Input Parameters
* `publicAccessBlock` - _required_
* `Bucket` - _required_

### HeadBucket
> This operation is useful to determine if a bucket exists and you have permission to access it.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketHEAD.html</p><br/>

#### Input Parameters
* `Bucket` - _required_

### ListBucketAnalyticsConfigurations
> Lists the analytics configurations for the bucket.<br/>

#### Input Parameters
* `analytics` - _required_
* `Bucket` - _required_

### ListBucketInventoryConfigurations
> Returns a list of inventory configurations for the bucket.<br/>

#### Input Parameters
* `inventory` - _required_
* `Bucket` - _required_

### ListBucketMetricsConfigurations
> Lists the metrics configurations for the bucket.<br/>

#### Input Parameters
* `metrics` - _required_
* `Bucket` - _required_

### ListMultipartUploads
> This operation lists in-progress multipart uploads.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/mpUploadListMPUpload.html</p><br/>

#### Input Parameters
* `MaxUploads` - _optional_ - Pagination limit<br/>
* `KeyMarker` - _optional_ - Pagination token<br/>
* `UploadIdMarker` - _optional_ - Pagination token<br/>
* `uploads` - _required_
* `Bucket` - _required_

### ListObjectVersions
> Returns metadata about all of the versions of objects in a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETVersion.html</p><br/>

#### Input Parameters
* `MaxKeys` - _optional_ - Pagination limit<br/>
* `KeyMarker` - _optional_ - Pagination token<br/>
* `VersionIdMarker` - _optional_ - Pagination token<br/>
* `versions` - _required_
* `Bucket` - _required_

### ListObjects
> Returns some or all (up to 1000) of the objects in a bucket. You can use the request parameters as selection criteria to return a subset of the objects in a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGET.html</p><br/>

#### Input Parameters
* `MaxKeys` - _optional_ - Pagination limit<br/>
* `Marker` - _optional_ - Pagination token<br/>
* `Bucket` - _required_

### ListObjectsV2
> Returns some or all (up to 1000) of the objects in a bucket. You can use the request parameters as selection criteria to return a subset of the objects in a bucket. Note: ListObjectsV2 is the revised List Objects API and we recommend you use this revised API for new application development.<br/>

#### Input Parameters
* `MaxKeys` - _optional_ - Pagination limit<br/>
* `ContinuationToken` - _optional_ - Pagination token<br/>
* `list-type` - _required_
    Possible values: 2.
* `Bucket` - _required_

### PutBucketAccelerateConfiguration
> Sets the accelerate configuration of an existing bucket.<br/>

#### Input Parameters
* `accelerate` - _required_
* `Bucket` - _required_

### PutBucketAcl
> Sets the permissions on a bucket using access control lists (ACL).<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUTacl.html</p><br/>

#### Input Parameters
* `acl` - _required_
* `Bucket` - _required_

### PutBucketAnalyticsConfiguration
> Sets an analytics configuration for the bucket (specified by the analytics configuration ID).<br/>

#### Input Parameters
* `analytics` - _required_
* `Bucket` - _required_

### PutBucketCors
> Sets the CORS configuration for a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUTcors.html</p><br/>

#### Input Parameters
* `cors` - _required_
* `Bucket` - _required_

### PutBucketEncryption
> Creates a new server-side encryption configuration (or replaces an existing one, if present).<br/>

#### Input Parameters
* `encryption` - _required_
* `Bucket` - _required_

### PutBucketInventoryConfiguration
> Adds an inventory configuration (identified by the inventory ID) from the bucket.<br/>

#### Input Parameters
* `inventory` - _required_
* `Bucket` - _required_

### PutBucketLifecycle
> No longer used, see the PutBucketLifecycleConfiguration operation.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUTlifecycle.html</p><br/>

#### Input Parameters
* `lifecycle` - _required_
* `Bucket` - _required_

### PutBucketLifecycleConfiguration
> Sets lifecycle configuration for your bucket. If a lifecycle configuration exists, it replaces it.<br/>

#### Input Parameters
* `lifecycle` - _required_
* `Bucket` - _required_

### PutBucketLogging
> Set the logging parameters for a bucket and to specify permissions for who can view and modify the logging parameters. To set the logging status of a bucket, you must be the bucket owner.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUTlogging.html</p><br/>

#### Input Parameters
* `logging` - _required_
* `Bucket` - _required_

### PutBucketMetricsConfiguration
> Sets a metrics configuration (specified by the metrics configuration ID) for the bucket.<br/>

#### Input Parameters
* `metrics` - _required_
* `Bucket` - _required_

### PutBucketNotification
> No longer used, see the PutBucketNotificationConfiguration operation.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUTnotification.html</p><br/>

#### Input Parameters
* `notification` - _required_
* `Bucket` - _required_

### PutBucketNotificationConfiguration
> Enables notifications of specified events for a bucket.<br/>

#### Input Parameters
* `notification` - _required_
* `Bucket` - _required_

### PutBucketPolicy
> Replaces a policy on a bucket. If the bucket already has a policy, the one in this request completely replaces it.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUTpolicy.html</p><br/>

#### Input Parameters
* `policy` - _required_
* `Bucket` - _required_

### PutBucketReplication
> Creates a replication configuration or replaces an existing one. For more information, see <a href=" https://docs.aws.amazon.com/AmazonS3/latest/dev/crr.html">Cross-Region Replication (CRR)</a> in the <i>Amazon S3 Developer Guide</i>.<br/>

#### Input Parameters
* `replication` - _required_
* `Bucket` - _required_

### PutBucketRequestPayment
> Sets the request payment configuration for a bucket. By default, the bucket owner pays for downloads from the bucket. This configuration parameter enables the bucket owner (only) to specify that the person requesting the download will be charged for the download. Documentation on requester pays buckets can be found at http://docs.aws.amazon.com/AmazonS3/latest/dev/RequesterPaysBuckets.html<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTrequestPaymentPUT.html</p><br/>

#### Input Parameters
* `requestPayment` - _required_
* `Bucket` - _required_

### PutBucketTagging
> Sets the tags for a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUTtagging.html</p><br/>

#### Input Parameters
* `tagging` - _required_
* `Bucket` - _required_

### PutBucketVersioning
> Sets the versioning state of an existing bucket. To set the versioning state, you must be the bucket owner.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUTVersioningStatus.html</p><br/>

#### Input Parameters
* `versioning` - _required_
* `Bucket` - _required_

### PutBucketWebsite
> Set the website configuration for a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUTwebsite.html</p><br/>

#### Input Parameters
* `website` - _required_
* `Bucket` - _required_

### PutObjectLockConfiguration
> Places an Object Lock configuration on the specified bucket. The rule specified in the Object Lock configuration will be applied by default to every new object placed in the specified bucket.<br/>

#### Input Parameters
* `object-lock` - _required_
* `Bucket` - _required_

### PutPublicAccessBlock
> Creates or modifies the <code>PublicAccessBlock</code> configuration for an Amazon S3 bucket.<br/>

#### Input Parameters
* `publicAccessBlock` - _required_
* `Bucket` - _required_

### AbortMultipartUpload
<blockquote><p>Aborts a multipart upload.</p> <p>To verify that all parts have been removed, so you don't get charged for the part storage, you should call the List Parts operation and ensure the parts list is empty.</p><p>http://docs.amazonwebservices.com/AmazonS3/latest/API/mpUploadAbort.html</p></blockquote>

#### Input Parameters
* `Bucket` - _required_
* `Key` - _required_

### CompleteMultipartUpload
> Completes a multipart upload by assembling previously uploaded parts.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/mpUploadComplete.html</p><br/>

#### Input Parameters
* `Bucket` - _required_
* `Key` - _required_

### CopyObject
> Creates a copy of an object that is already stored in Amazon S3.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectCOPY.html</p><br/>

#### Input Parameters
* `Bucket` - _required_
* `Key` - _required_

### CreateMultipartUpload
<blockquote><p>Initiates a multipart upload and returns an upload ID.</p> <p> <b>Note:</b> After you initiate multipart upload and upload one or more parts, you must either complete or abort multipart upload in order to stop getting charged for storage of the uploaded parts. Only after you either complete or abort multipart upload, Amazon S3 frees up the parts storage and stops charging you for the parts storage.</p><p>http://docs.amazonwebservices.com/AmazonS3/latest/API/mpUploadInitiate.html</p></blockquote>

#### Input Parameters
* `uploads` - _required_
* `Bucket` - _required_
* `Key` - _required_

### DeleteObject
> Removes the null version (if there is one) of an object and inserts a delete marker, which becomes the latest version of the object. If there isn't a null version, Amazon S3 does not remove any objects.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectDELETE.html</p><br/>

#### Input Parameters
* `Bucket` - _required_
* `Key` - _required_

### DeleteObjectTagging
> Removes the tag-set from an existing object.<br/>

#### Input Parameters
* `tagging` - _required_
* `Bucket` - _required_
* `Key` - _required_

### GetObject
> Retrieves objects from Amazon S3.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectGET.html</p><br/>

#### Input Parameters
* `Bucket` - _required_
* `Key` - _required_

### GetObjectAcl
> Returns the access control list (ACL) of an object.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectGETacl.html</p><br/>

#### Input Parameters
* `acl` - _required_
* `Bucket` - _required_
* `Key` - _required_

### GetObjectLegalHold
> Gets an object's current Legal Hold status.<br/>

#### Input Parameters
* `legal-hold` - _required_
* `Bucket` - _required_
* `Key` - _required_

### GetObjectRetention
> Retrieves an object's retention settings.<br/>

#### Input Parameters
* `retention` - _required_
* `Bucket` - _required_
* `Key` - _required_

### GetObjectTagging
> Returns the tag-set of an object.<br/>

#### Input Parameters
* `tagging` - _required_
* `Bucket` - _required_
* `Key` - _required_

### GetObjectTorrent
> Return torrent files from a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectGETtorrent.html</p><br/>

#### Input Parameters
* `torrent` - _required_
* `Bucket` - _required_
* `Key` - _required_

### HeadObject
> The HEAD operation retrieves metadata from an object without returning the object itself. This operation is useful if you're only interested in an object's metadata. To use HEAD, you must have READ access to the object.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectHEAD.html</p><br/>

#### Input Parameters
* `Bucket` - _required_
* `Key` - _required_

### ListParts
> Lists the parts that have been uploaded for a specific multipart upload.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/mpUploadListParts.html</p><br/>

#### Input Parameters
* `MaxParts` - _optional_ - Pagination limit<br/>
* `PartNumberMarker` - _optional_ - Pagination token<br/>
* `Bucket` - _required_
* `Key` - _required_

### PutObject
> Adds an object to a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectPUT.html</p><br/>

#### Input Parameters
* `Bucket` - _required_
* `Key` - _required_

### PutObjectAcl
> uses the acl subresource to set the access control list (ACL) permissions for an object that already exists in a bucket<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectPUTacl.html</p><br/>

#### Input Parameters
* `acl` - _required_
* `Bucket` - _required_
* `Key` - _required_

### PutObjectLegalHold
> Applies a Legal Hold configuration to the specified object.<br/>

#### Input Parameters
* `legal-hold` - _required_
* `Bucket` - _required_
* `Key` - _required_

### PutObjectRetention
> Places an Object Retention configuration on an object.<br/>

#### Input Parameters
* `retention` - _required_
* `Bucket` - _required_
* `Key` - _required_

### PutObjectTagging
> Sets the supplied tag-set to an object that already exists in a bucket<br/>

#### Input Parameters
* `tagging` - _required_
* `Bucket` - _required_
* `Key` - _required_

### RestoreObject
> Restores an archived copy of an object back into Amazon S3<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectRestore.html</p><br/>

#### Input Parameters
* `restore` - _required_
* `Bucket` - _required_
* `Key` - _required_

### SelectObjectContent
> This operation filters the contents of an Amazon S3 object based on a simple Structured Query Language (SQL) statement. In the request, along with the SQL expression, you must also specify a data serialization format (JSON or CSV) of the object. Amazon S3 uses this to parse object data into records, and returns only records that match the specified SQL expression. You must also specify the data serialization format for the response.<br/>

#### Input Parameters
* `select` - _required_
* `select-type` - _required_
    Possible values: 2.
* `Bucket` - _required_
* `Key` - _required_

### UploadPart
<blockquote><p>Uploads a part in a multipart upload.</p> <p> <b>Note:</b> After you initiate multipart upload and upload one or more parts, you must either complete or abort multipart upload in order to stop getting charged for storage of the uploaded parts. Only after you either complete or abort multipart upload, Amazon S3 frees up the parts storage and stops charging you for the parts storage.</p><p>http://docs.amazonwebservices.com/AmazonS3/latest/API/mpUploadUploadPart.html</p></blockquote>

#### Input Parameters
* `Bucket` - _required_
* `Key` - _required_

### UploadPartCopy
> Uploads a part by copying data from an existing object as data source.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/mpUploadUploadPartCopy.html</p><br/>

#### Input Parameters
* `Bucket` - _required_
* `Key` - _required_

## License

**flow**ground :- Telekom iPaaS / amazonaws-com-s-3-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
