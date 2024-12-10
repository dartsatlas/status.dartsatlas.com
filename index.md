# Darts Atlas Status

Experiencing problems? Reach out through one of our support channels.

- [support@dartsatlas.com](mailto:support@dartsatlas.com)
- [twitter.com/DartsAtlas](https://www.twitter.com/dartsatlas)
- [facebook.com/DartsAtlas](https://www.facebook.com/dartsatlas)

## Status History

### 11-December, 2024

7:00pm - 8:00pm Central Time (U.S. & Canada) (12-December 1:00am - 2:00am GMT)

**Type:**  
Planned Maintenance

**Reason(s):**  
Darts Atlas will be undergoing an extensive data migration in preparation for upcoming feature releases. The platform will be unavailable during this migration window.

---

### 07-October, 2024

2:27pm - 2:52pm Central Time (U.S. & Canada) (07-October 8:27pm - 8:52pm BST)

**Type:**
Service Disruption

**Reason(s):**
Amazon Web Services (AWS) exprienced a system failure with one of the services that Darts Atlas uses for file hosting and delivery. Darts Atlas pages containing profile photos or banner images may have experienced slow load times or load failures. The incident was identified and addressed by the AWS team and all Darts Atlas systems returned to their normal operational statuses.

AWS provided the following details about the incident:

> Oct 07 1:19 PM PDT Between 12:27 PM and 12:52 PM PDT we experienced increased API error rates for PUT and GET requests to S3 in the US-EAST-2 Region. Other AWS Services that use PUT and GET S3 APIs were also affected. The error rates have recovered and all services are operating normally. Engineers were automatically engaged immediately and began mitigating the impact and investigating the root cause in parallel. We will post a final update as we validate root cause.

---

### 28-April, 2024

8:00pm - 9:00pm Central Time (U.S. & Canada) (29-April 2:00am - 3:00am BST)

**Type:**
Planned Maintenance

**Reason(s):**
Darts Atlas will be performing a database upgrade. The platform will be unavailable during this maintenance window.

---

### 01-January, 2024

9:00pm - 10:00pm Central Time (U.S. & Canada)

**Type:**
Planned Maintenance

**Reason(s):**
The release of Darts Atlas v3 includes a number of database migrations that will require a cessation of platform traffic in order to ensure data integrity.

Happy New Year!

---

### 29-October, 2023 

9:45am - 10:20am Central Time (U.S. & Canada)

**Type:**  
Service Disruption

**Reason(s):**  
Darts Atlas experienced sitewide service degradation. The cause was identified as a database configuration which was fixed after a brief maintenance window.

No data was lost during this incident.

---

### 07-April, 2023

6:30am Central Time (U.S. & Canada)

**Type:**  
Temporary Feature Removal

**Reason(s):**  
We have temporarily disabled profile photo support while we conduct performance testing. Already-uploaded images will reappear once our testing has concluded.

---

### 17-March, 2023

6:30pm-8:30pm Central Time (U.S. & Canada)

**Type:**  
Service Disruption

**Reason(s):**  
A bug was discovered that triggered an infinite loop when creating new matches. This was the result of legacy code which was not intended to accommodate the current volume of Darts Atlas activity. This limitation of scale has been removed and all features are now behaving as normal.

---

### 15-January, 2023

6:30pm Central Time (U.S. & Canada)

**Type:**  
Data Migration

**Reason(s):**  
We noticed an issue with errant ranking points on the ADC tables following a previous data migration. Specifically, players who had played an ADC-sanctioned event *before* creating or renewing their membership had been incorrectly awarded points for their performance in that event. This migration reset the ADC tables to accurately reflect points earned by active members *at the time the tournament was played*.

---

### 23-August, 2022

6:30pm - 10:52am Central Time (U.S. & Canada)

**Type:**  
Platform Outage

**Reason(s):**  
Darts Atlas's primary platform provider, Heroku, is experiencing an upstream DNS issue that is affecting a significant portion of the internet. The site may not be reachable until the issue is fixed.

[Heroku Incident](https://status.heroku.com/incidents/2453)

---

### 24-February, 2022

10:30am - 10:52am Central Time (U.S. & Canada)

**Type:**  
Platform Outage

**Reason(s):**  
Darts Atlas's primary platform provider, Heroku, experienced a widespread outage. Darts Atlas became available again following their platform-side fix.

[Heroku Incident](https://status.heroku.com/incidents/2402)

**Note(s):**  
No data was lost during the outage.

---

### 24-January, 2021

13:00 - 13:20 Central Time (U.S. & Canada)

**Type:**  
Database Interruption

**Reason(s):**  
Darts Atlas experienced what we believe to be an automated, untargeted attack attempting to expose a vulnerability in our infrastructure. Thousands of connection requests flooded our databse, resulting in failed responses for a number of players.

**Note(s):**  
No player data was exposed during the attack, and all data and backups remain unaffected.

---

### 22-January, 2021

17:00 - 17:30 Central Time (U.S. & Canada)

**Type:**  
Planned Maintenance

**Reason(s):**  
Darts Atlas v1 will be released, which will include several database migrations and a redesign of the interface.

**Note(s):**  
All data will be backed up before the migration begins.

---

### 29-October, 2020

12:15 - 12:25 Central Time (U.S. & Canada)

**Type:**  
High response times

**Notes:**  
Abnormally high response times were observed during a brief period. After investigation this appears to have been an isolated incident related to an individual player's websocket connection during a match.

---

### 22-October, 2020

16:40 - 16:50 Central Time (U.S. & Canada)

**Type:**  
Planned Maintenance

**Reason(s):**

- Add "First 9" data for all completed matches
- Add "First 9" data for all player season stats

**Notes:**  
The addition of the "First 9" match average statistic required us to re-process the all match and season stats on the platform. Before undergoing this migration we first captured a backup of the production database to allow us to rollback in the event of any data corruption.

---

[DartsAtlas.com](dartsatlas.com)
