# HermesRoad
Backend data service for ApolloTrove.

Designed to utilize [Apache Airflow](https://airflow.apache.org/) and [Celery](https://docs.celeryq.dev/en/latest/getting-started/) to schedule data jobs and remove backend effort from Apollo Trove.

# High Level Design
Users that exist in the ApolloTrove user base will have nightly jobs run to refresh their assets.
[excalidraw for userTable -> 3P API Calls -> MongoDB -> Data Tranformations -> MongoDB Analysis Consumption -> ApolloTrove Frontend]


# Airflow Tasks
1. [Operators]

# Systems Interaction
- Mongo DB
- Spotify API
coming soon - Apple Music, LetterBoxd, GoodReads



