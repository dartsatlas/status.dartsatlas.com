# Darts Atlas Status

Players are reporting issues with missing ADC points. The current standings reflect a recent _correction_ to the ADC tables. See the latest Incident Report below for details.

Experiencing problems? Reach out through one of our support channels.

- [support@dartsatlas.com](mailto:support@dartsatlas.com)
- [twitter.com/DartsAtlas](https://www.twitter.com/dartsatlas)
- [facebook.com/DartsAtlas](https://www.facebook.com/dartsatlas)

## Status History

### 17-March, 2023

6:30pm Central Time (U.S. & Canada)

**Type:**  
Service Disruption

**Reason(s):**  
We are investigating the cause of this issue.

### 15-January, 2023

6:30pm Central Time (U.S. & Canada)

**Type:**  
Data Migration

**Reason(s):**  
We noticed an issue with errant ranking points on the ADC tables following a previous data migration. Specifically, players who had played an ADC-sanctioned event *before* creating or renewing their membership had been incorrectly awarded points for their performance in that event. This migration reset the ADC tables to accurately reflect points earned by active members *at the time the tournament was played*.

### 23-August, 2022

6:30pm - 10:52am Central Time (U.S. & Canada)

**Type:**  
Platform Outage

**Reason(s):**  
Darts Atlas's primary platform provider, Heroku, is experiencing an upstream DNS issue that is affecting a significant portion of the internet. The site may not be reachable until the issue is fixed.

[Heroku Incident](https://status.heroku.com/incidents/2453)

### 24-February, 2022

10:30am - 10:52am Central Time (U.S. & Canada)

**Type:**  
Platform Outage

**Reason(s):**  
Darts Atlas's primary platform provider, Heroku, experienced a widespread outage. Darts Atlas became available again following their platform-side fix.

[Heroku Incident](https://status.heroku.com/incidents/2402)

**Note(s):**  
No data was lost during the outage.

### 24-January, 2021

13:00 - 13:20 Central Time (U.S. & Canada)

**Type:**  
Database Interruption

**Reason(s):**  
Darts Atlas experienced what we believe to be an automated, untargeted attack attempting to expose a vulnerability in our infrastructure. Thousands of connection requests flooded our databse, resulting in failed responses for a number of players.

**Note(s):**  
No player data was exposed during the attack, and all data and backups remain unaffected.

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
