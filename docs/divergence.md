Divergences from S3
===================

* We do not list ETag from bucket listings because we don't have the value of
  the md5 of the object available from Manta on directory listings.

* StorageClass maps to durability based on settings in the config file.