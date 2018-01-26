# simpletests
CosmosDB simple load tests

Usage:
```bash
cosmosdbtest@oath-ne-vm8:~$ java -cp simpletests-0.0.1-jar-with-dependencies.jar SimpleTests --help
log4j:ERROR Could not find value for key log4j.appender.A1.layout
Usage: <main class> [options]
  Options:
    --collection, -col
      CosmosDB collection ID
      Default: testcol
    --connectionMode
      Set the connection mode for the client
      Default: DirectHttps
    --connectionPoolSize, -cps
      Connection pool size
      Default: -1
    --consistency
      Set the consistency level for the client
      Default: Session
    --database, -db
      CosmosDB database ID
      Default: testdb
    --docIdToRead, -idToRead
      The Document ID to read
      Default: <empty string>
    --docIdsFilePath, -idFile
      The file containing the Document IDs to read
      Default: <empty string>
    --endpoint, -e
      CosmosDB endpoint
      Default: <empty string>
    --help
      Show this program usage
    --idleConnectionTimeout
      Set the idle connection timeout time in seconds for the client
      Default: -1
    --key, -k
      CosmosDB key
      Default: <empty string>
    --logBatchEntryCount
      Latency logging: Number of requests to write in one log file
      Default: 250000
    --logLatencyPath
      Latency logging: Log latency from the requests to this path
      Default: <empty string>
    --operation, -o
      Operation (read, write, write-read, read-throughput)
      Default: write-read
    --operations
      Number of operations for each thread to run
      Default: 9223372036854775807
    --partitionKey, -pk
      CosmosDB partition key
      Default: id
    --preferredRegions, -r
      CosmosDB preferred regions
      Default: West US
    --printLatency
      Latency logging: Set to true to print the latency to the console
      Default: false
    --requestTimeout
      Set the request timeout time in seconds for the client
      Default: -1
    --threads, -t
      The number of threads to spawn
      Default: 100
    --warmupRequestCount
      Latency logging: Number of requests which latency is not logged at the
      start of the run
      Default: 1000
``` 
