# Darts Atlas Status

No issues have been detected or reported.  
Experiencing problems? Reach out through one of our support channels.

- [support@dartsatlas.com](mailto:support@dartsatlas.com)
- [twitter.com/DartsAtlas](https://www.twitter.com/dartsatlas)
- [facebook.com/DartsAtlas](https://www.facebook.com/dartsatlas)

## Status History

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
