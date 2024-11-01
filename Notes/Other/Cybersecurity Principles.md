## CIA

![[Fig23.png]]

- **Confidentiality** ensures that only the intended persons or recipients can access the data.

- **Integrity** aims to ensure that the data cannot be altered; moreover, we can detect any alteration if it occurs.

- **Availability** aims to ensure that the system or service is available when needed.
##### Case 1 : Placing an online shopping order.

- **Confidentiality** : During online shopping, you expect your credit card number to be disclosed only to the entity that processes the payment. If you doubt that your credit card information will be disclosed to an untrusted party, you will most likely refrain from continuing with the transaction. Moreover, if a data breach results in the disclosure of personally identifiable information, including credit cards, the company will incur huge losses on multiple levels.

- **Integrity** : After filling out your order, if an intruder can alter the shipping address you have submitted, the package will be sent to someone else. Without data integrity, you might be very reluctant to place your order with this seller.

- **Availability** : To place your online order, you will either browse the store’s website or use its official app. If the service is unavailable, you won’t be able to browse the products or place an order. If you continue to face such technical issues, you might eventually give up and start looking for a different online store.
##### Case 2 : Healthcare and patients data storage systems

- **Confidentiality** : According to various laws in modern countries, healthcare providers must ensure and maintain the confidentiality of medical records. Consequently, healthcare providers can be held legally accountable if they illegally disclose their patients’ medical records.

- **Integrity** : If a patient record is accidentally or maliciously altered, it can lead to the wrong treatment being administered, which, in turn, can lead to a life-threatening situation. Hence, the system would be useless and potentially harmful without ensuring the integrity of medical records.

- **Availability** : When a patient visits a clinic to follow up on their medical condition, the system must be available. An unavailable system would mean that the medical practitioner cannot access the patient’s records and consequently won’t know if any current symptoms are related to the patient’s medical history. This situation can make the medical diagnosis more challenging and error-prone.
### Extended CIA

Going one more step beyond the CIA security triad, we can think of :

- **Authenticity** : Authentic means not fraudulent or counterfeit. Authenticity is about ensuring that the document/file/data is from the claimed source.

- **Nonrepudiation** : Repudiate means refusing to recognize the validity of something. Nonrepudiation ensures that the original source cannot deny that they are the source of a particular document / file / data. This characteristic is indispensable for various domains, such as shopping, patient diagnosis, and banking.
### Parkerian Hexad

- **Availability** : ensure that the system or service is available when needed.

- **Utility** : Utility focuses on the usefulness of the information. For instance, a user might have lost the decryption key to access a laptop with encrypted storage. Although the user still has the laptop with its disk(s) intact, they cannot access them. In other words, although still available, the information is in a form that is not useful.

- **Integrity** : ensure that the data cannot be altered. Moreover, we can detect any alteration if it occurs.

- **Authenticity** : Authentic means not fraudulent or counterfeit. Authenticity is about ensuring that the document / file / data is from the claimed source.

- **Confidentiality** : ensure that only the intended persons or recipients can access the data.

- **Possession** : This security element requires that we protect the information from unauthorized taking, copying, or controlling. For instance, an adversary might take a backup drive, meaning we lose possession of the information as long as they have the drive. Alternatively, the adversary might succeed in encrypting our data using ransomware; this also leads to the loss of possession of the data.
## DAD

![[Fig24.png]]

- **Disclosure** is the opposite of confidentiality. In other words, disclosure of confidential data would be an attack on confidentiality.
- **Alteration** is the opposite of Integrity. For example, the integrity of a cheque is indispensable.
- **Destruction / Denial** is the opposite of Availability.

The opposite of the CIA Triad would be the DAD Triad : Disclosure, Alteration, and Destruction.
##### Healthcare and patients data storage systems case

- Disclosure: As in most modern countries, healthcare providers must maintain medical records’ confidentiality. As a result, if an attacker succeeds in stealing some of these medical records and dumping them online to be viewed publicly, the health care provider will incur a loss due to this data disclosure attack.
- Alteration: Consider the gravity of the situation if the attacker manages to modify patient medical records. This alteration attack might lead to the wrong treatment being administered, and consequently, this alteration attack could be life-threatening.
- Destruction/Denial: Consider the case where a medical facility has gone completely paperless. If an attacker manages to make the database systems unavailable, the facility will not be able to function properly. They can go back to paper temporarily; however, the patient records won’t be available. This denial attack would stall the whole facility.