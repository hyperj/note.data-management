# Spark

## Environment

- JVM Information
- Spark Properties
- Hadoop Properties
- System Properties
- Classpath Entries

## Application

- App ID
- _YARN App ID_
- App Name
- App Attempt ID
- User
- Status
- Start Time
- End Time
- _Executors_
- _Jobs_
- _Stages_
- _Tasks_
- _CPU_
- _MEMORY_
- _DISK_

## Job

- App ID
- Job ID
- Status
- Start Time
- End Time
- _Executors_
- _Stages_
- _Tasks_
- _CPU_
- _MEMORY_
- _DISK_

## Stage

- App ID
- Job ID
- Executor ID
- Stage ID
- Stage Name
- Stage Attempt ID
- Parent IDs
- Status
- Start Time
- End Time
- _Executors_
- _Tasks_
- _RDDs_
- _SHUFFLE_
- _CPU_
- _MEMORY_
- _DISK_

## Task

- App ID
- Job ID
- Executor ID
- Stage ID
- Task ID
- Task Index
- Task Attempt ID
- Status
- Start Time
- End Time
- _SHUFFLE_
- _BLOCK_
- _CPU_
- _MEMORY_
- _DISK_

## Executor

- App ID
- Executor ID
- Container ID
- Host Port
- _Tasks_
- _SHUFFLE_
- _CPU_
- _MEMORY_
- _DISK_

## Block

## RDD

## Reference

- [Spark Docs: Monitoring and Instrumentation](https://spark.apache.org/docs/latest/monitoring.html)
- [JsonProtocol: Serializes SparkListener events to/from JSON](https://github.com/apache/spark/blob/master/core/src/main/scala/org/apache/spark/util/JsonProtocol.scala)
