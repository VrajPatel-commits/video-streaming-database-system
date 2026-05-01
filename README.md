
Note: Due to institutional access restrictions, the original Microsoft Access database file is not included. However, the full system design, schema, SQL queries, and interface implementation are documented in this repository.


# Video Streaming Database System

## Overview
This project implements a full database system for a video streaming platform, designed using PostgreSQL and Microsoft Access.

The system manages:
- Actors, Directors, Videos (Movies & Shows)
- Accounts and Viewer Profiles
- Watch History and Viewing Intervals

## Key Features
- ER Model - Relational Schema conversion
- BCNF normalization
- Complex SQL queries (joins, aggregation, filtering)
- Watch history tracking with time constraints
- Actor–genre impact analysis
- Top-viewed content analytics

## Database Design
The system includes relations such as:
- Actor, Director, Account, ViewerShares
- VideoD, Movie, Show, EpisodeOf
- ActsIn, Watches

(Full schema available in the report)

## Queries Implemented
- Actors in a given movie (with role and pay)
- Episodes of a show
- Monthly watch history per account
- Actor impact on genres
- Top 5 most-watched videos

## User Interface (Microsoft Access)
- Forms for data entry and management
- Interactive menu system
- Reports for query visualization

## Note on Implementation Files
Due to university database access restrictions, the original Microsoft Access .accdb file and SQL scripts are not publicly available.

However, the complete system design, schema, and queries are fully documented in the report provided.

## Report
See full project documentation here:  
  Video-Streaming-Database-System-Report.pdf

## Author
Vraj Patel  
B.Sc. (Honours) Computer Science, Brock University
