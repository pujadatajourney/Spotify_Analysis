# Spotify_Analysis
This project focuses on analyzing a Spotify dataset containing detailed information about tracks, albums, and artists using SQL. It involves the complete process of normalizing a denormalized dataset, writing SQL queries of varying complexity (easy, medium, and advanced), and applying query optimization techniques. The key objective of this project is to strengthen advanced SQL skills while extracting meaningful insights from the dataset

![](https://github.com/pujadatajourney/Spotify_Analysis/blob/main/spotify_logo.jpg)

```sql
create table
DROP TABLE IF EXISTS spotify;
CREATE TABLE spotify (
    artist VARCHAR(255),
    track VARCHAR(255),
    album VARCHAR(255),
    album_type VARCHAR(50),
    danceability FLOAT,
    energy FLOAT,
    loudness FLOAT,
    speechiness FLOAT,
    acousticness FLOAT,
    instrumentalness FLOAT,
    liveness FLOAT,
    valence FLOAT,
    tempo FLOAT,
    duration_min FLOAT,
    title VARCHAR(255),
    channel VARCHAR(255),
    views FLOAT,
    likes BIGINT,
    comments BIGINT,
    licensed BOOLEAN,
    official_video BOOLEAN,
    stream BIGINT,
    energy_liveness FLOAT,
    most_played_on VARCHAR(50)
);
```

## Project Steps

1. Data Exploration

2. Artist: The performer of the track.
   
3. Track: The name of the song.
4. Album: The album to which the track belongs.
5. Album_type: The type of album (e.g., single or album).
6. Various metrics such as danceability, energy, loudness, tempo, and more.

7. Querying the Data
After the data is inserted, various SQL queries can be written to explore and analyze the data. Queries are categorized into easy, medium, and advanced levels to help progressively develop SQL proficiency.

## Easy Queries
Simple data retrieval, filtering, and basic aggregations.
## Medium Queries
More complex queries involving grouping, aggregation functions, and joins.
## Advanced Queries
Nested subqueries, window functions, CTEs, and performance optimization.

## Query Optimization
In advanced stages, the focus shifts to improving query performance. Some optimization strategies include:

>Indexing: Adding indexes on frequently queried columns.

>Query Execution Plan: Using EXPLAIN ANALYZE to review and refine query performance.

