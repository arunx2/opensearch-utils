# OpenSearch Utils
Tools for OpenSearch cluster

### Transfer users

``os-util transfer-users``

A command line utility to transfer users from one OpenSearch cluster to another.  

**Required parameters**
```
-cluster -c  -- the source opensearch cluster url
-target-cluster -t  -- the target opensearch cluster url
-target-default-pwd -- the default password for all the users, it can be changed later by the user.
```
**Optional paramters**
```-source-user -su    -- source user
-source-pwd - sp    -- source password
-target-user -su    -- target user for access
-target-pwd - sp    -- target password for access
-include -i         -- regex pattern for usernames
-exclude -e         -- regex pattern for exclude users
```

### Publish query templates
``os-util publish query-templates``

### Publish index templates
``os-util publish index-templates``
<!--
### Analyze shards
``os-util analyze indices``
-->