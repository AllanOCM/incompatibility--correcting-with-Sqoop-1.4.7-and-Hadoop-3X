# Correcting Sqoop-1.4.7 and Hadoop-3.X Incompatibility

### Error

```sh
$ Exception in thread "main" java.lang.NoClassDefFoundError: org/apache/commons/lang/StringUtils
```

Copy file .jar for /lib directory of Sqoop

```sh
$ wget https://github.com/AllanOCM/incompatibility--correcting-with-Sqoop-1.4.7-and-Hadoop-3X/raw/master/commons-lang-2.6-bin.zip
$ unzip commons-lang-2.6-bin.zip
$ cp commons-lang-2.6 /opt/sqoop/lib/
```
