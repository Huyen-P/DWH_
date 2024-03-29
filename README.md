##<details><summary> 01-Topic Introduction </summary>
<p>
  
- A music streaming startup needs to scale up ****their user base and song database. To achieve this, they’re looking to migrate their processes and data onto the cloud. Their data  currently resides in AWS S3 bucket. This bucket contains two folders: one with JSON files recording user activity within the app, and another with JSON files containing metadata for all the songs available.
- Task is to build an ETL Pipeline that extracts their data from S3, staging it in Amazon Redshift and then transforming data into a set of Dimensional and Fact Tables for their Analytics Team to continue finding insights to what songs their users are listening to.

<img width="925" alt="image" src="https://github.com/Huyen-P/DE_DWH_AWS_S3_RedShift/assets/72473316/88d74bb6-5bbf-4ddd-8393-23268a6560e9">


</p>
</details> 

<details><summary> 02 - Dataset Overview </summary>
<p>
  <details><summary> Data Sample - Song Data Path → s3://udacity-dend/song_data </summary>
<p>
  ```
  {"num_songs": 1, "artist_id": "ARJIE2Y1187B994AB7", "artist_latitude": null, "artist_longitude": null, "artist_location": "", "artist_name": "Line Renaud", "song_id": "SOUPIRU12A6D4FA1E1", "title": "Der Kleine Dompfaff", "duration": 152.92036, "year": 0}

</p>
</details> 

</p>
</details> 
