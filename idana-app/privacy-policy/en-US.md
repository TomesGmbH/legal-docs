## Data protection policy for the Idana app (desktop app and patient app)

Date: 2018-11-08

## Summary

Idana is offered by Tomes GmbH as Software-as-a-Service and is used for the collection and documentation of medical questionnaires, especially for the collection of medical history. 

With the Idana Cloud, Tomes GmbH offers the customer (practice or clinic) a secure infrastructure for storing patient data. The aim is to offer customers the lowest possible risk of downtime/loss and, at the same time, availability regardless of location. For EU customers, the Idana Cloud is operated at data centers within the European Union.

Idana maintains medical confidentiality and ensures that only the customer can read the data provided by his patients. This is realized by encrypting the patient's answers using hybrid encryption algorithms before they are transferred to the Idana Cloud. Only the customer has the key required for decryption - in the form of a freely assigned PIN that is not transmitted at any time. Only encrypted patient data is transferred to and retrieved from the Idana Cloud.

At no time is unencrypted patient data stored on Tomes GmbH servers - except as directed by the customer when using the Idana Email Service. Neither Tomes GmbH nor its contractors (i.e. data center operators) can make encrypted patient data legible.Tomes GmbH does not know the content of the encrypted data packages nor the name of any patient whom they belong to. This guarantees that Tomes GmbH does not have access to personal patient data. From Tomes GmbH's point of view, the encrypted patient data are regarded as anonymous data, since there is no (legal) way to establish a personal reference. Tomes GmbH therefore also does not act as an data processor.

The encrypted patient data in the Idana Cloud is protected by various security systems. They can only be retrieved after successful authentication in the system with user e-mail and user password. The data is additionally encrypted on the server side and backups are automatically created.

The customer can optionally install Idana Local as an extension. New data records (i.e. completed questionnaires) are moved directly into a database operated on the customer's own servers and then deleted from the Idana Cloud. As long as Idana Local is connected to the Idana Cloud, new records can be made available immediately and are usually stored in the Idana Cloud for no longer than one second.  

The Idana E-Mail-Service offers the possibility to send the patient an automated e-mail with instructions for starting the questionnaire. Name, date of birth, gender, e-mail, patient ID as well as the selected questionnaires and language plus an optional message to the patient is sent to the Idana server to send the e-mail to the patient. After the e-mail is sent, all data is deleted immediately - for details see section 3.3.

Tomes GmbH stores and processes personal data about the customer. This includes the registration data (see Section 3.1) and payment data (see Section 3.2). Usage data (see section 3.4) are stored for security reasons during registration and login (IP address, time) and at the start of a new survey (time, selected questionnaires). No usage data is stored in the patient app.

All Internet communication between users, Idana servers and e-mail services is handled exclusively via encrypted HTTPS channels and thus offers eavesdropping protection.


## Detailed data protection policy

### 1\. Information about the collection of personal data and provider identification

Below we provide information about the collection of personal data when using this application. Personal data are all data that are personally identifiable to you, e.g. name, address, e-mail addresses, user behavior.

Service provider according to § 13 Telemediengesetz (TMG) and responsible body according to § 3 Abs. 7 Bundesdatenschutzgesetz (BDSG) and General Data Protection Regulation (GDPR) is Tomes GmbH, Engesserstr. 4a, 79108 Freiburg im Breisgau, Germany, Tel. 0761 6006784-0, E-Mail: contact@idana.one. Imprint: idana.one/impressum.

### 2\. Data security

We maintain current technical measures to guarantee data security, in particular to protect your personal data from the dangers of data transmission and to prevent third parties from gaining knowledge. These are adapted to the current state of the art in each case. The server and system components and all stored data are stored exclusively in ISO 27001-certified data centers.

To protect your data, we rely on the world’s leading hosting and authentication companies. For order data processing, we have concluded contracts that comply with the guidelines of the GDPR. For example, user accounts are managed by Auth0, a company specialising in Internet security.

### 3\. Collection of personal data

#### 3.1 Registration of a user account

Registering a user account in Idana’s desktop app is required to provide Idana as a Software-as-a-Service according to the current performance specification and to provide support in case of malfunctions (service and support). During registration the following data about the user is collected and processed by Tomes GmbH:

   E-mail address, gender, title, first and last name, name of the practice/clinic, address, telephone number.
   date and time of registration

The legal basis for processing the data is the user’s consent pursuant to Art. 6 para. 1 lit. a GDPR. An additional legal basis for the processing of data is the performance of a contract to which the user is a party, pursuant to Art. 6 para. 1 lit. b DSGVO.

The data will be deleted as soon as it is no longer necessary to achieve the purpose of its collection. This is the case for the registration data if the user cancels his user account and has not reactivated it for six months. Even thereafter, it may be necessary to store certain personal data of the contractual partner in order to fulfil contractual or legal obligations, e.g. in accounting.

As a user you have the possibility to cancel your registration at any time. You can change the data stored about you at any time. You can arrange for both by e-mail to kontakt@idana.one Premature deletion of the data is only possible if contractual or legal obligations do not prevent deletion.

#### 3.2 Payment details for the purchase of a paid license

To use Idana after the trial period, a paid license is required to provide Idana as Software-as-a-Service according to the current service description. The following additional data is collected:

   Payment information (payment address, bank details, credit card number and other information relevant for settlement)
   Date and time of purchase of the paid license

The legal basis for the processing of data is the fulfilment of a contract to which the user is a party, in accordance with Art. 6 para. 1 lit. b GDPR.

The data will be deleted as soon as it is no longer necessary to achieve the purpose of its collection. This is the case for the payment data if the paid version is cancelled. Even thereafter, however, it may still be necessary to store certain personal data of the contractual partner in order to fulfil contractual or legal obligations, e.g. in accounting.

As a user you have the possibility to cancel your paid license at any time. This is possible in Idana’s desktop app under “My Account”. You can change the data stored about you at any time. You can arrange the latter by e-mail to kontakt@idana.one Premature deletion of the data is only possible if contractual or legal obligations do not prevent deletion.

##### 3.3 Idana Email Service

Idana offers the option of sending the patient an e-mail with instructions on how to complete the questionnaire configured for him. The following additional data is collected:

   Name, gender, date of birth, patient ID and e-mail address of the patient
   Selected questionnaires and questionnaire language
   Optional a personal message to the patient, which is attached to the e-mail template.

These data are transmitted to the Tomes GmbH servers and inserted into an e-mail template. This is sent to the patient via the e-mail provider Mailjet (Mailjet GmbH) as an order processor. The data is then immediately deleted from the servers of Tomes GmbH and is therefore only available there for a few seconds.

The legal basis for the processing of data is the fulfilment of a contract to which the user is a party, in accordance with Art. 6 para. 1 lit. b DSGVO. The user is obliged to ensure that the data is passed on to Tomes GmbH in conformity with data protection regulations, usually with the patient's consent to send the e-mail. Tomes GmbH does not act as a contract processor.

The data will be deleted as soon as they are no longer necessary to achieve the purpose for which they were collected. This is the case immediately after sending the e-mail. For the processing of the data by Mailjet see their[Privacy Policy](https://www.mailjet.com/security-privacy/).

#### 3.4 Usage data

When using the Idana desktop app, the following usage data is collected for security, billing and evaluation purposes:

   When registering and logging in: time, IP address, software version
   When creating a new survey: time, selected questionnaires

The legal basis for the processing of data is the fulfilment of a contract to which the user is a party, in accordance with Art. 6 para. 1 lit. b GDPR.

The data will be deleted as soon as it is no longer necessary to achieve the purpose of its collection. This is the case when the account is cancelled. Even thereafter, however, it may still be necessary to store certain personal data of the contractual partner in order to fulfil contractual or legal obligations.

The Idana mobile app (“patient app”) does not transmit any personal data, including usage data.

### 4\. Patient data

Patient data entered in Idana is encrypted in such a way that it can only be decrypted with the help of a separate password - called a PIN. This password is to remain within the group of persons authorized to work with patient data.

Neither Tomes GmbH nor the operators of its commissioned data centres have access to the key or unencrypted patient data (exception: see section 3.3 E-mail service). The encrypted patient data can therefore be regarded as anonymous data.

The encrypted data is transmitted to Tomes GmbH to be stored and made available to the customer for retrieval at any time and from any location. The customer can delete encrypted data any time within the desktop app.

Neither Tomes GmbH nor the data center operators can access unencrypted patient data. There is therefore no transfer of personal patient data. Tomes GmbH therefore does not carry out any order data processing of patient data.

An overview of the technical-organizational measures of the Tomes GmbH for the protection of the data can be requested by customers at any time over datenschutz@idana.one

### 5\. Rights of the person affected

If personal data are processed by you, you are affected by the GDPR and you have the following rights against the person responsible:

#### 5.1 Right to information

You can ask the data controller to confirm whether personal data concerning you is being processed by us.

If such processing exists, you can ask the person responsible to provide the following information:

1.  the purposes for which the personal data are processed;
2.  the categories of personal data being processed;
3.  the recipients or categories of recipients to whom the personal information about you has been or will be disclosed;
4.  the planned duration of the storage of personal data concerning you or, if specific information on this is not possible, criteria for the determination of the storage period;
5.  the existence of a right of rectification or deletion of personal data concerning you, of a right of limitation of the processing by the controller or of a right of objection to such processing;
6.  the existence of a right of appeal to a supervisory authority;
7.  all available information on the origin of the data if the personal data is not collected from the data subject;
8.  the existence of automated decision-making including profiling in accordance with Article 22(1) and (4) GDPR and – at least in these cases – meaningful information on the logic involved and the scope and intended effects of such processing for the data subject.

You have the right to request information as to whether the personal data concerning you is transferred to a third country or to an international organisation. In this context, you may request to be informed of the appropriate guarantees pursuant to Art. 46 DSGVO in connection with the transmission.

#### 5.2 Right to correction

You have the right to correct and/or complete any personal data processed concerning you that is incorrect or incomplete. The person responsible shall make the correction without delay.

#### 5.3 Right to limitation of processing

You may request that the processing of personal data concerning you be restricted under the following conditions:

1.  if you dispute the accuracy of personal data concerning you for a period of time that allows the data controller to verify the accuracy of the personal data;
2.  if the processing is unlawful and you refuse to delete the personal data and instead request that the use of the personal data be restricted;
3.  if the data controller no longer needs the personal data for the purposes of the processing, but you need them to assert, exercise or defend legal claims, or
4.  if you have filed an objection against the processing pursuant to Art. 21 para. 1 GDPR and it has not yet been determined whether the legitimate reasons of the person responsible outweigh your reasons.

If the processing of personal data concerning you has been restricted, such data may only be processed – apart from being stored – with your consent or for the purpose of asserting, exercising or defending rights or for the protection of the rights of another natural or legal person or on grounds of an important public interest of the Union or a Member State.

If the processing restriction is restricted according to the above conditions, you will be informed by the person responsible before the restriction is removed.

#### 5.4 Right to deletion

You may request the data controller to delete the personal data concerning you immediately and the data controller is obliged to delete this data immediately if one of the following reasons applies:

1.  The personal information about you is no longer necessary for the purposes for which it was collected or otherwise processed.
2.  You revoke your consent, on which the processing was based pursuant to Article 6(1)(a) or Article 9(2)(a) DSBER, and there is no other legal basis for the processing.
3.  You file an objection against the processing pursuant to Art. 21 para. 1 GDPR and there are no overriding legitimate reasons for the processing, or you file an objection against the processing pursuant to Art. 21 para. 2 GDPR
4.  The personal data concerning you has been processed unlawfully.
5.  The deletion of personal data concerning you is necessary to fulfil a legal obligation under Union law or the law of the Member States to which the data controller is subject.

If the data controller has made the personal data concerning you public and is obliged to delete it pursuant to Art. 17 para. 1 GDPR, he shall take appropriate measures, including technical measures, taking into account the available technology and the implementation costs, to inform data processors who process the personal data that you as the data subject have requested the deletion of all links to this personal data or of copies or replications of this personal data.

#### 5.5 Right to information

If you have exercised your right of rectification, deletion or limitation of processing against the controller, the controller is obliged to notify all recipients to whom the personal data concerning you have been disclosed of such rectification or deletion or restriction of processing, unless this proves impossible or involves disproportionate effort.

You have the right vis-à-vis the person responsible to be informed about these recipients.

#### 5.6 Right to Data Transferability

You have the right to receive the personal information about you that you have provided to the owner in a structured, common and machine-readable format. In addition, you have the right to transmit this data to another person in charge without obstruction by the person in charge to whom the personal data was provided, provided

1.  the processing is based on consent pursuant to Art. 6 para. 1 lit. a GDPR or Art. 9 para. 2 lit. a GDPR or on a contract pursuant to Art. 6 para. 1 lit. b GDPR; and
2.  processing is carried out using automated methods.

In exercising this right, you also have the right to have the personal data concerning you transferred directly from one data controller to another data controller, insofar as this is technically feasible. The freedoms and rights of other persons must not be affected by this.

#### 5.7. Right to revoke the data protection declaration of consent

You have the right to revoke your data protection consent at any time. The revocation of consent shall not affect the legality of the processing carried out on the basis of the consent until revocation.

#### 5.8 Right of appeal to a supervisory authority

Without prejudice to any other administrative or judicial remedy, you have the right of appeal to a supervisory authority, in particular in the Member State where you reside, work or suspect of infringement, if you believe that the processing of personal data concerning you is contrary to the GDPR.  
The supervisory authority to which the complaint has been lodged shall inform the complainant of the status and results of the complaint, including the possibility of a judicial remedy under Article 78 GDPR.
