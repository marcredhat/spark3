# spark3



```bash
https://spark.apache.org/docs/3.1.1/quick-start.html

wget https://mirrors.ocf.berkeley.edu/apache/spark/spark-3.1.1/spark-3.1.1-bin-hadoop3.2.tgz


cd /root/scala/src
sbt package


[root@marcrhel82 marc]# pwd
/root/scala/marc
wget https://raw.githubusercontent.com/apache/spark/master/README.md

[root@marcrhel82 marc]# /root/spark-3.1.1-bin-hadoop3.2/bin/spark-submit --class "SimpleApp" --master local[4] target/scala-2.12/simple-project_2.12-1.0.jar
```

