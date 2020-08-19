# Correcting Sqoop-1.4.7 and Hadoop-3X Incompatibility

### Error

```sh
$ Exception in thread "main" java.lang.NoClassDefFoundError: org/apache/commons/lang/StringUtils
```

Copy file .jar for /lib directory of Sqoop

```sh
$ unzip commons-lang-2.6-bin.zip
$ cp commons-lang-2.6 /opt/sqoop/lib/
```
