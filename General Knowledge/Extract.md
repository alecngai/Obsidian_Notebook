# Data Extraction


## Types of Data Extraction


 ### Logical Extractions 
 
#### Update Notification
Automated extraction based on notification or changes to the database 

#### Incremental Extraction
 The changes in source data need to be tracked since the last successful extraction. Only these changes in data will be extracted and then loaded. These changes can be detected from the source data with the last-changed timestamp. Also, a changing table can be created in the source system, which keeps track of the changes in the source data. However, this method does not track deleted records from the source, only additions. 

#### Partial Extraction
-   With Update Notification

Extract data with update notification sent by the source; if some already extracted data has a modification, we only extract the modified data to the staging area.

-  Without update Notification

Extract data with conditions in loading, such as in some daily schedulers extract only that daily data. The rest of the newly added data will be extracted on a respective day.

### Physical Extractions

#### Full Extraction

Extracting and reloading the entire table can cause network stress, so it is not advised unless it is the first time the database is loaded. 

#### Offline Extraction
 The data from the source system is dumped outside of the source system into a flat file. This flat file is used to extract the data. The flat file can be created by a routine process daily.

 #### Online Extraction 

 In online extraction, the data is extracted directly from the source system. The extraction process connects to the source system and removes the source data.

## [[Technologies]] 
- [[SQL ]]

Ref
https://www.stitchdata.com/resources/what-is-data-extraction/
https://medium.com/@supunbandara06/etl-process-9aa283a79565