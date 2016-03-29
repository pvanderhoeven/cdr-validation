## CDR Monitoring 

This test setup was created to show Streaming components usage.

------------------

#### Purpose: Monitor  Network equipments analyzing CDR (call detail record) records.

- Ingest: 
  - Listen for CDR records coming as text file in a directory
- Processing:
  - Monitor dropped calls
  - Monitor networks type change
- Persistence:
  - Hive Streaming ORC (for interactive query) 
  - HBase (for granular events alerts)
  - Solr/Banana (for alerts and reports/dashboards)
- Simulation:
  -  Generate "fake" CDR files every minute 
- Demo setup:
  - Start sandbox and run provided scripts to setup demo 

------------------
	
