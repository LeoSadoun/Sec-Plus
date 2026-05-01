## Official Definition
* **Password Attack:** An attempt to discover or bypass the password of an authorized user to gain unauthorized access to a system or data.

## Key Characteristics/Technical Details
* **Brute Force:** Trying every possible combination of characters until the correct password is found.
* **Dictionary Attack:** Using a list of common words and previously leaked passwords (a "dictionary") to guess the correct one.
* **Password Spraying:** Trying a few common passwords (e.g., "Password123") against many different accounts to avoid account lockout.
* **Credential Stuffing:** Using large lists of username/password pairs stolen from one site to gain access to other sites (exploiting password reuse).
* **Rainbow Table:** Using pre-computed hashes of passwords to quickly reverse a captured password hash.
* **Offline vs. Online:**
    * **Online:** Attacking the live login interface.
    * **Offline:** Attacking a stolen database of password hashes.

## Real-World Examples
* **RockYou Leak:** A massive database of 32 million plain-text passwords that is frequently used in dictionary attacks.
* **SolarWinds Password:** It was revealed that a SolarWinds update server had the password "password123," which was easily guessable.

## Exam Tips
* **Keywords:** Brute force, Dictionary, Spraying (many accounts), Stuffing (reused credentials), Rainbow table (pre-computed), Salting (mitigation).
* **Scenario:** If an attacker tries "one password against many users," it's spraying. If they use a "list of common passwords," it's a dictionary attack.

## Relationship to other concepts
* **Mitigation:** Multi-Factor Authentication (MFA), account lockout policies, and Password Salting (adding random data to hashes).
* **Identity and Access Management:** Password attacks target the "Authentication" pillar.
