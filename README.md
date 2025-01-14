# cray-nls-charts
This deploys cray-nls and argo-workflow

# Versioning

The version numbers to be used must follow the format given in the table below. Note that the format is different for
CSM 1.4.x releases because this convention is decided after the CSM 1.4.0 release but before the 1.5.0 release, so it was
not possible to change the convention for a previously released product.

| CSM Version | .version file in cray-nls | Helm chart version in cray-nls-charts |
|-------------|---------------------------|---------------------------------------|
| 1.4.x       | 0.(10+x).y                | 2.(10+x).y                            |
| 1.5.x       | 3.(1+x).y                 | 3.(1+x).y                             |
| 1.6.x       | 4.x.y                     | 4.x.y                                 |
| 1.7.x       | 5.x.y                     | 5.x.y                                 |

PLEASE FOLLOW SEMANTIC VERSIONING GUIDELINES FROM CSM VERSION.

This means that:
1. You should not be updating minor or major versions of cray-nls in a patch update of CSM.
2. You should not be updating major versions of cray-nls in a minor update of CSM.
3. An update of dependencies does not change the public interfaces of cray-nls, so need to update minor/major version.