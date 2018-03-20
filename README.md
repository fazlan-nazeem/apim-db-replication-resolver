# apim-db-replication-resolver
Some of the database tables in WSO2 API Manager, do not have primary keys. The following scripts will add primary keys for those tables.

**Tables Fixed**

```
AM_API_SCOPES
REG_RESOURCE_PROPERTY
REG_RESOURCE_TAG
REG_RESOURCE_COMMENT
REG_RESOURCE_RATING
UM_SHARED_USER_ROLE
```

**Supported Databases**

<b>Mysql</b>

```
run wso2am_db.sql against the apim db
run wso2reg_db.sql against registry db and userstore db
```
