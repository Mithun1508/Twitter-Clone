# Twitter Clone


## Services

1. [Edge Service (GraphQL)](./edge/)
2. [Media Service](./media/)
3. [Notifications Service](./notifications/)
4. [Search Service](./search/)
5. [Timeline Service](./timeline/)
6. [Tweet Service](./tweet/)
7. [Web UI Service](./website/)


## Features:
Features ✨
NOTE: Not all features from twitter are implemented because of how big Twitter is, Only the main features are implemented atm

1 Modular Architecture

2 Database migration tool using migrate

3 Golang Hot-reloading using air

4 Supports dark-mode and light-mode with TailwindCSS

5 Database seeding script using NodeJS

6 Authentication using JWT Refresh token flow and Redis for token blacklisting

7 Strongly typed Vuex store

8 List Tweets feed

9 Create Tweets with images

10Retweets

11 Reply to Tweets or reply to another reply!

12 Like Tweets

13 Follow users

14 Images & Media uploads stored in AWS S3 Buckets

15 Up to 4 images in a single tweet with the same layout as Twitter

16Crop profile image

17 Edit Profile Details

18 Edit Profile Image

19 See who a user is following and see their followers

## Technologies Used

1. Golang (Internal Services)

2. Next.JS (Website UI)

3. Kafka (Pub/Sub)

4. Apache Spark (Analytics)

5. PostgreSQL (Main Database)

6. PgPool II (Database Load Balancer)

7. Redis (Caching)

8. Docker (Containerization)

9. Nginx (Load Balancer)

10. GraphQL (Edge Server / Frontend for Backend)

11. ElasticSearch (Searching & Indexing)

12. Firebase Cloud Messenger (Notification Service)

## Other languages& Frameworks
1 Golang

2 Fiber HTTP framework

3 PostgreSQL

4 Redis

5 NodeJS

6 igrate

7 air

8 Amazon Web Service S3

9 Vue 3

10 Vite 2.0

11 Vuex 4

12 Vue Router 4

13TailwindCSS

## System Design

### Functional Requirements
1. Create Tweets (text, images, videos, etc)

2. View Timeline

3. Like tweets

4. Retweet / Quote Retweet

5. Follow others

### Non-Functional Requirements
1. Scalable & Efficient

2. High Availability

### Optional Requirements
1. Metrics and analytics

2. Notifications

3. Observability & Monitoring (Prometheus, Grafana, Jaeger, etc)

## Improvements
1 Hashtags and mentions

2 Notifications

3 Bookmarks

4 Lists

5 Trending section
