# ![LOGO](logo.png) Amazon Simple Storage Service MSP Connector

## Description

A generated MSP connector for the Amazon Simple Storage Service API (version 2006-03-01).

Generated from: https://api.apis.guru/v2/specs/amazonaws.com/s3/2006-03-01/swagger.json<br/>
Generated at: 2019-05-07T11:16:35+03:00

## API Description

<p/>

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Returns a list of all buckets owned by the authenticated sender of the request.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTServiceGET.html</p>

#### Input Parameters
* `x-amz-security-token` - _optional_

### Creates a new bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUT.html</p>

#### Input Parameters
* `Bucket` - _required_

### Deletes the bucket. All objects (including all object versions and Delete Markers) in the bucket must be deleted before the bucket itself can be deleted.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketDELETE.html</p>

#### Input Parameters
* `Bucket` - _required_

### Deletes an analytics configuration for the bucket (specified by the analytics configuration ID).

#### Input Parameters
* `analytics` - _required_
* `Bucket` - _required_

### Deletes the CORS configuration information set for the bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketDELETEcors.html</p>

#### Input Parameters
* `cors` - _required_
* `Bucket` - _required_

### Deletes the server-side encryption configuration from the bucket.

#### Input Parameters
* `encryption` - _required_
* `Bucket` - _required_

### Deletes an inventory configuration (identified by the inventory ID) from the bucket.

#### Input Parameters
* `inventory` - _required_
* `Bucket` - _required_

### Deletes the lifecycle configuration from the bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketDELETElifecycle.html</p>

#### Input Parameters
* `lifecycle` - _required_
* `Bucket` - _required_

### Deletes a metrics configuration (specified by the metrics configuration ID) from the bucket.

#### Input Parameters
* `metrics` - _required_
* `Bucket` - _required_

### Deletes the policy from the bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketDELETEpolicy.html</p>

#### Input Parameters
* `policy` - _required_
* `Bucket` - _required_

### Deletes the replication configuration from the bucket. For information about replication configuration, see <a href=" https://docs.aws.amazon.com/AmazonS3/latest/dev/crr.html">Cross-Region Replication (CRR)</a> in the <i>Amazon S3 Developer Guide</i>.

#### Input Parameters
* `replication` - _required_
* `Bucket` - _required_

### Deletes the tags from the bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketDELETEtagging.html</p>

#### Input Parameters
* `tagging` - _required_
* `Bucket` - _required_

### This operation removes the website configuration from the bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketDELETEwebsite.html</p>

#### Input Parameters
* `website` - _required_
* `Bucket` - _required_

### This operation enables you to delete multiple objects from a bucket using a single HTTP request. You may specify up to 1000 keys.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/multiobjectdeleteapi.html</p>

#### Input Parameters
* `delete` - _required_
* `Bucket` - _required_

### Removes the <code>PublicAccessBlock</code> configuration from an Amazon S3 bucket.

#### Input Parameters
* `publicAccessBlock` - _required_
* `Bucket` - _required_

### Returns the accelerate configuration of a bucket.

#### Input Parameters
* `accelerate` - _required_
* `Bucket` - _required_

### Gets the access control policy for the bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETacl.html</p>

#### Input Parameters
* `acl` - _required_
* `Bucket` - _required_

### Gets an analytics configuration for the bucket (specified by the analytics configuration ID).

#### Input Parameters
* `analytics` - _required_
* `Bucket` - _required_

### Returns the CORS configuration for the bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETcors.html</p>

#### Input Parameters
* `cors` - _required_
* `Bucket` - _required_

### Returns the server-side encryption configuration of a bucket.

#### Input Parameters
* `encryption` - _required_
* `Bucket` - _required_

### Returns an inventory configuration (identified by the inventory ID) from the bucket.

#### Input Parameters
* `inventory` - _required_
* `Bucket` - _required_

### No longer used, see the GetBucketLifecycleConfiguration operation.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETlifecycle.html</p>

#### Input Parameters
* `lifecycle` - _required_
* `Bucket` - _required_

### Returns the lifecycle configuration information set on the bucket.

#### Input Parameters
* `lifecycle` - _required_
* `Bucket` - _required_

### Returns the region the bucket resides in.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETlocation.html</p>

#### Input Parameters
* `location` - _required_
* `Bucket` - _required_

### Returns the logging status of a bucket and the permissions users have to view and modify that status. To use GET, you must be the bucket owner.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETlogging.html</p>

#### Input Parameters
* `logging` - _required_
* `Bucket` - _required_

### Gets a metrics configuration (specified by the metrics configuration ID) from the bucket.

#### Input Parameters
* `metrics` - _required_
* `Bucket` - _required_

### No longer used, see the GetBucketNotificationConfiguration operation.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETnotification.html</p>

#### Input Parameters
* `notification` - _required_
* `Bucket` - _required_

### Returns the notification configuration of a bucket.

#### Input Parameters
* `notification` - _required_
* `Bucket` - _required_

### Returns the policy of a specified bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETpolicy.html</p>

#### Input Parameters
* `policy` - _required_
* `Bucket` - _required_

### Retrieves the policy status for an Amazon S3 bucket, indicating whether the bucket is public.

#### Input Parameters
* `policyStatus` - _required_
* `Bucket` - _required_

### <p>Returns the replication configuration of a bucket.</p> <note> <p> It can take a while to propagate the put or delete a replication configuration to all Amazon S3 systems. Therefore, a get request soon after put or delete can return a wrong result. </p> </note>

#### Input Parameters
* `replication` - _required_
* `Bucket` - _required_

### Returns the request payment configuration of a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTrequestPaymentGET.html</p>

#### Input Parameters
* `requestPayment` - _required_
* `Bucket` - _required_

### Returns the tag set associated with the bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETtagging.html</p>

#### Input Parameters
* `tagging` - _required_
* `Bucket` - _required_

### Returns the versioning state of a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETversioningStatus.html</p>

#### Input Parameters
* `versioning` - _required_
* `Bucket` - _required_

### Returns the website configuration for a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETwebsite.html</p>

#### Input Parameters
* `website` - _required_
* `Bucket` - _required_

### Gets the Object Lock configuration for a bucket. The rule specified in the Object Lock configuration will be applied by default to every new object placed in the specified bucket.

#### Input Parameters
* `object-lock` - _required_
* `Bucket` - _required_

### Retrieves the <code>PublicAccessBlock</code> configuration for an Amazon S3 bucket.

#### Input Parameters
* `publicAccessBlock` - _required_
* `Bucket` - _required_

### This operation is useful to determine if a bucket exists and you have permission to access it.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketHEAD.html</p>

#### Input Parameters
* `Bucket` - _required_

### Lists the analytics configurations for the bucket.

#### Input Parameters
* `analytics` - _required_
* `Bucket` - _required_

### Returns a list of inventory configurations for the bucket.

#### Input Parameters
* `inventory` - _required_
* `Bucket` - _required_

### Lists the metrics configurations for the bucket.

#### Input Parameters
* `metrics` - _required_
* `Bucket` - _required_

### This operation lists in-progress multipart uploads.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/mpUploadListMPUpload.html</p>

#### Input Parameters
* `MaxUploads` - _optional_ - Pagination limit
* `KeyMarker` - _optional_ - Pagination token
* `UploadIdMarker` - _optional_ - Pagination token
* `uploads` - _required_
* `Bucket` - _required_

### Returns metadata about all of the versions of objects in a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGETVersion.html</p>

#### Input Parameters
* `MaxKeys` - _optional_ - Pagination limit
* `KeyMarker` - _optional_ - Pagination token
* `VersionIdMarker` - _optional_ - Pagination token
* `versions` - _required_
* `Bucket` - _required_

### Returns some or all (up to 1000) of the objects in a bucket. You can use the request parameters as selection criteria to return a subset of the objects in a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketGET.html</p>

#### Input Parameters
* `MaxKeys` - _optional_ - Pagination limit
* `Marker` - _optional_ - Pagination token
* `Bucket` - _required_

### Returns some or all (up to 1000) of the objects in a bucket. You can use the request parameters as selection criteria to return a subset of the objects in a bucket. Note: ListObjectsV2 is the revised List Objects API and we recommend you use this revised API for new application development.

#### Input Parameters
* `MaxKeys` - _optional_ - Pagination limit
* `ContinuationToken` - _optional_ - Pagination token
* `list-type` - _required_
    Possible values: 2.
* `Bucket` - _required_

### Sets the accelerate configuration of an existing bucket.

#### Input Parameters
* `accelerate` - _required_
* `Bucket` - _required_

### Sets the permissions on a bucket using access control lists (ACL).<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUTacl.html</p>

#### Input Parameters
* `acl` - _required_
* `Bucket` - _required_

### Sets an analytics configuration for the bucket (specified by the analytics configuration ID).

#### Input Parameters
* `analytics` - _required_
* `Bucket` - _required_

### Sets the CORS configuration for a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUTcors.html</p>

#### Input Parameters
* `cors` - _required_
* `Bucket` - _required_

### Creates a new server-side encryption configuration (or replaces an existing one, if present).

#### Input Parameters
* `encryption` - _required_
* `Bucket` - _required_

### Adds an inventory configuration (identified by the inventory ID) from the bucket.

#### Input Parameters
* `inventory` - _required_
* `Bucket` - _required_

### No longer used, see the PutBucketLifecycleConfiguration operation.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUTlifecycle.html</p>

#### Input Parameters
* `lifecycle` - _required_
* `Bucket` - _required_

### Sets lifecycle configuration for your bucket. If a lifecycle configuration exists, it replaces it.

#### Input Parameters
* `lifecycle` - _required_
* `Bucket` - _required_

### Set the logging parameters for a bucket and to specify permissions for who can view and modify the logging parameters. To set the logging status of a bucket, you must be the bucket owner.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUTlogging.html</p>

#### Input Parameters
* `logging` - _required_
* `Bucket` - _required_

### Sets a metrics configuration (specified by the metrics configuration ID) for the bucket.

#### Input Parameters
* `metrics` - _required_
* `Bucket` - _required_

### No longer used, see the PutBucketNotificationConfiguration operation.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUTnotification.html</p>

#### Input Parameters
* `notification` - _required_
* `Bucket` - _required_

### Enables notifications of specified events for a bucket.

#### Input Parameters
* `notification` - _required_
* `Bucket` - _required_

### Replaces a policy on a bucket. If the bucket already has a policy, the one in this request completely replaces it.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUTpolicy.html</p>

#### Input Parameters
* `policy` - _required_
* `Bucket` - _required_

### Creates a replication configuration or replaces an existing one. For more information, see <a href=" https://docs.aws.amazon.com/AmazonS3/latest/dev/crr.html">Cross-Region Replication (CRR)</a> in the <i>Amazon S3 Developer Guide</i>.

#### Input Parameters
* `replication` - _required_
* `Bucket` - _required_

### Sets the request payment configuration for a bucket. By default, the bucket owner pays for downloads from the bucket. This configuration parameter enables the bucket owner (only) to specify that the person requesting the download will be charged for the download. Documentation on requester pays buckets can be found at http://docs.aws.amazon.com/AmazonS3/latest/dev/RequesterPaysBuckets.html<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTrequestPaymentPUT.html</p>

#### Input Parameters
* `requestPayment` - _required_
* `Bucket` - _required_

### Sets the tags for a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUTtagging.html</p>

#### Input Parameters
* `tagging` - _required_
* `Bucket` - _required_

### Sets the versioning state of an existing bucket. To set the versioning state, you must be the bucket owner.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUTVersioningStatus.html</p>

#### Input Parameters
* `versioning` - _required_
* `Bucket` - _required_

### Set the website configuration for a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTBucketPUTwebsite.html</p>

#### Input Parameters
* `website` - _required_
* `Bucket` - _required_

### Places an Object Lock configuration on the specified bucket. The rule specified in the Object Lock configuration will be applied by default to every new object placed in the specified bucket.

#### Input Parameters
* `object-lock` - _required_
* `Bucket` - _required_

### Creates or modifies the <code>PublicAccessBlock</code> configuration for an Amazon S3 bucket.

#### Input Parameters
* `publicAccessBlock` - _required_
* `Bucket` - _required_

### <p>Aborts a multipart upload.</p> <p>To verify that all parts have been removed, so you don't get charged for the part storage, you should call the List Parts operation and ensure the parts list is empty.</p><p>http://docs.amazonwebservices.com/AmazonS3/latest/API/mpUploadAbort.html</p>

#### Input Parameters
* `Bucket` - _required_
* `Key` - _required_

### Completes a multipart upload by assembling previously uploaded parts.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/mpUploadComplete.html</p>

#### Input Parameters
* `Bucket` - _required_
* `Key` - _required_

### Creates a copy of an object that is already stored in Amazon S3.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectCOPY.html</p>

#### Input Parameters
* `Bucket` - _required_
* `Key` - _required_

### <p>Initiates a multipart upload and returns an upload ID.</p> <p> <b>Note:</b> After you initiate multipart upload and upload one or more parts, you must either complete or abort multipart upload in order to stop getting charged for storage of the uploaded parts. Only after you either complete or abort multipart upload, Amazon S3 frees up the parts storage and stops charging you for the parts storage.</p><p>http://docs.amazonwebservices.com/AmazonS3/latest/API/mpUploadInitiate.html</p>

#### Input Parameters
* `uploads` - _required_
* `Bucket` - _required_
* `Key` - _required_

### Removes the null version (if there is one) of an object and inserts a delete marker, which becomes the latest version of the object. If there isn't a null version, Amazon S3 does not remove any objects.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectDELETE.html</p>

#### Input Parameters
* `Bucket` - _required_
* `Key` - _required_

### Removes the tag-set from an existing object.

#### Input Parameters
* `tagging` - _required_
* `Bucket` - _required_
* `Key` - _required_

### Retrieves objects from Amazon S3.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectGET.html</p>

#### Input Parameters
* `Bucket` - _required_
* `Key` - _required_

### Returns the access control list (ACL) of an object.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectGETacl.html</p>

#### Input Parameters
* `acl` - _required_
* `Bucket` - _required_
* `Key` - _required_

### Gets an object's current Legal Hold status.

#### Input Parameters
* `legal-hold` - _required_
* `Bucket` - _required_
* `Key` - _required_

### Retrieves an object's retention settings.

#### Input Parameters
* `retention` - _required_
* `Bucket` - _required_
* `Key` - _required_

### Returns the tag-set of an object.

#### Input Parameters
* `tagging` - _required_
* `Bucket` - _required_
* `Key` - _required_

### Return torrent files from a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectGETtorrent.html</p>

#### Input Parameters
* `torrent` - _required_
* `Bucket` - _required_
* `Key` - _required_

### The HEAD operation retrieves metadata from an object without returning the object itself. This operation is useful if you're only interested in an object's metadata. To use HEAD, you must have READ access to the object.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectHEAD.html</p>

#### Input Parameters
* `Bucket` - _required_
* `Key` - _required_

### Lists the parts that have been uploaded for a specific multipart upload.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/mpUploadListParts.html</p>

#### Input Parameters
* `MaxParts` - _optional_ - Pagination limit
* `PartNumberMarker` - _optional_ - Pagination token
* `Bucket` - _required_
* `Key` - _required_

### Adds an object to a bucket.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectPUT.html</p>

#### Input Parameters
* `Bucket` - _required_
* `Key` - _required_

### uses the acl subresource to set the access control list (ACL) permissions for an object that already exists in a bucket<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectPUTacl.html</p>

#### Input Parameters
* `acl` - _required_
* `Bucket` - _required_
* `Key` - _required_

### Applies a Legal Hold configuration to the specified object.

#### Input Parameters
* `legal-hold` - _required_
* `Bucket` - _required_
* `Key` - _required_

### Places an Object Retention configuration on an object.

#### Input Parameters
* `retention` - _required_
* `Bucket` - _required_
* `Key` - _required_

### Sets the supplied tag-set to an object that already exists in a bucket

#### Input Parameters
* `tagging` - _required_
* `Bucket` - _required_
* `Key` - _required_

### Restores an archived copy of an object back into Amazon S3<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/RESTObjectRestore.html</p>

#### Input Parameters
* `restore` - _required_
* `Bucket` - _required_
* `Key` - _required_

### This operation filters the contents of an Amazon S3 object based on a simple Structured Query Language (SQL) statement. In the request, along with the SQL expression, you must also specify a data serialization format (JSON or CSV) of the object. Amazon S3 uses this to parse object data into records, and returns only records that match the specified SQL expression. You must also specify the data serialization format for the response.

#### Input Parameters
* `select` - _required_
* `select-type` - _required_
    Possible values: 2.
* `Bucket` - _required_
* `Key` - _required_

### <p>Uploads a part in a multipart upload.</p> <p> <b>Note:</b> After you initiate multipart upload and upload one or more parts, you must either complete or abort multipart upload in order to stop getting charged for storage of the uploaded parts. Only after you either complete or abort multipart upload, Amazon S3 frees up the parts storage and stops charging you for the parts storage.</p><p>http://docs.amazonwebservices.com/AmazonS3/latest/API/mpUploadUploadPart.html</p>

#### Input Parameters
* `Bucket` - _required_
* `Key` - _required_

### Uploads a part by copying data from an existing object as data source.<p>http://docs.amazonwebservices.com/AmazonS3/latest/API/mpUploadUploadPartCopy.html</p>

#### Input Parameters
* `Bucket` - _required_
* `Key` - _required_

## License

flowground :- Telekom iPaaS / amazonaws-com-s-3-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
