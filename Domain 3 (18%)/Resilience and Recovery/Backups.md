## Official Definition
The process of copying and archiving data so that it may be used to restore the original after a data loss event.

## Key Characteristics/Technical Details
*   **Backup Types:**
    *   **Full:** Copies everything. Slowest to back up, fastest to restore. Clears the archive bit.
    *   **Incremental:** Copies only data changed since the *last* backup (Full or Incremental). Fast to back up, slowest to restore (requires Full + all Incrementals). Clears the archive bit.
    *   **Differential:** Copies only data changed since the *last Full* backup. Moderate speed. To restore, you only need the Full + the *latest* Differential. Does NOT clear the archive bit.
*   **Snapshot:** A point-in-time "image" of a system (common in VMs). Not a true backup if stored on the same hardware.
*   **3-2-1 Rule:** 3 copies of data, on 2 different media, with 1 copy off-site.
*   **Off-site vs. On-site:** On-site is for fast recovery; Off-site (or Cloud) is for disaster recovery.

## Real-World Examples
*   **Backup Strategy:** A Full backup every Sunday, and Incremental backups Monday through Saturday.
*   **Cloud Backup:** Using Backblaze or AWS S3 to store encrypted copies of server data automatically.
*   **Air-Gapped Backup:** Backing up to a tape drive and physically moving the tapes to a fireproof safe.

## Exam Tips
*   **Keywords:** Full, Incremental, Differential, Snapshot, 3-2-1 Rule, Off-site.
*   **Scenario:** Which backup type is the fastest to *restore*? Full.
*   **Scenario:** Which backup type is the fastest to *perform*? Incremental.
*   **Calculation:** If you have a Full backup from Sunday and Incrementals from Mon/Tue/Wed, and the system fails Wednesday night, how many backups do you need to restore? 4 (Sun Full + Mon Inc + Tue Inc + Wed Inc).

## Relationship to other concepts
*   **Availability:** Backups are the ultimate "Corrective" control for availability.
*   **Integrity:** Backups allow you to restore data to a known-good state if it is corrupted or encrypted by ransomware.
*   **RPO (Recovery Point Objective):** The frequency of backups determines the RPO (how much data you can afford to lose).