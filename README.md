# Exercice 1 
# Data Protection Glossary

## 1. Personal Data
**Definition:** Information related to an identified or identifiable person.
**Example:** Name, address, email address, IP address.

## 2. Sensitive Data
**Definition:** Particularly sensitive personal data, such as health status, ethnic origin, or political opinions.
**Example:** Biometric data, medical records.

## 3. Anonymization vs. Pseudonymization
- **Anonymization:** Process by which personal data is modified so that identification is no longer possible.
  **Example:** Removing all direct and indirect identifiers from a database.
- **Pseudonymization:** Replacing personal data with a pseudonym so that identification is only possible with additional information (two keys identification: later only accessible if we associate the name to the pseudonyme).
  **Example:** Replacing customer names with a customer number.
- **Relationship:** Both serve to protect personal data, but anonymization is irreversible while pseudonymization allows re-identification with additional data.

## 4. Data Protection vs. Data Security
- **Data Protection:** Protection of personal data against misuse and unauthorized access.
  **Example:** GDPR (General Data Protection Regulation) regulations for processing personal data.
- **Data Security:** Technical and organizational measures to protect data from loss, manipulation, or unauthorized access.
  **Example:** Encryption, firewalls, access controls.
- **Relationship:** Data protection sets the rules, while data security ensures compliance through technical safeguards.

## 5. Consent and Data Processing Agreement
- **Consent:** Voluntary agreement of a person to the processing of their personal data.
  **Example:** Accepting cookies on a website.
- **Data Processing Agreement:** Processing of personal data by a service provider on behalf of a company.
  **Example:** Cloud services storing and managing customer data.
- **Relationship:** Consent is required for data collection, while a data processing agreement ensures compliance when data is handled by third parties.

## 6. Privacy by Design and Privacy by Default
- **Privacy by Design:** Data protection measures are considered from the outset in the development of IT systems and processes.
  **Example:** Default-enabled privacy settings in an app.
- **Privacy by Default:** Privacy-friendly settings are activated by default.
  **Example:** A social media platform initially displaying only public information.
- **Relationship:** Privacy by Design ensures systems are built with privacy in mind, while Privacy by Default ensures that the most protective settings are the standard.




# Exercise 2
# Data Protection Analysis: FitTrack Pro

## Overview
FitTrack Pro is a mobile app that helps users track their health by recording heart rate, sleep patterns, and activity levels. The app sends this information to a cloud server to create personalized health reports.

## Collected Data
- **Personal Data:** Name and age.
- **Sensitive Data:** Health-related details like heart rate and sleep times.
- **Additional Data:** Location for tracking activities.

## Understanding the Data
- **Personal Data:** This includes any information that can identify a person, like their name and age.
- **Sensitive Data:** Health data is more private and needs extra protection because it reveals details about a person’s well-being (psycologic problems or gender identification).
- **Location Data:** This isn’t always sensitive, but when combined with other details, it can reveal a lot about someone’s habits and behaviours.

## How Data Can Be Protected
### Ways to Keep Data Safe
- **Anonymization:**
  - Removing names or emails so that no one can tell who the data belongs to.
  - Grouping sleep and activity data together in general statistics rather than tracking individuals.
- **Pseudonymization:**
  - Replacing names with unique codes so data can be used without revealing identities.
  - Keeping personal details separate from health data in different secure databases.

## Best Practices
1. **Use Anonymization** where it is possible to protect privacy and still allowing useful analysis.
2. **Apply Pseudonymization** for cases where user-specific tracking is needed (geolocalization for hiking -> estimate altitude, speed...) but should be kept secure.
3. **Follow Data Protection Laws** like GDPR (General Data Protection Regulation) by using strong security measures like encryption and access controls.

## Summatry
Since FitTrack Pro collects personal and sensitive data, it must have strong privacy conditions. By anonymizing and pseudonymizing data, the app can keep user information safe but still providing helpful health views and informations.



