# sparkemr

Modified Amazon EMR script to support new features like Apache Arrow.

EMR bootstrap action:

```
s3://sparklyrec2/rstudio_sparklyr_emr5.sh
```

EMR bootstrap parameters:

```
--rstudio --user-pw rmultiverse! --nopackages --arrow --arrow-version 0.14.1
```
