# Phishing Email Investigation

## Scenario

A user reported a suspicious email claiming to be from a legitimate organization.

The email requested the user to click on a link and verify account credentials.

## Investigation Steps

### Step 1: Review the Email

The email was reviewed to identify suspicious characteristics.

The following details were checked:

* Sender Email Address
* Subject Line
* Reply-To Address
* Email Content

### Step 2: Email Header Analysis

The email headers were analyzed to identify the actual sending source and verify email authentication.

The following records were reviewed:

* SPF
* DKIM
* DMARC
* Return-Path

### Step 3: URL Analysis

The URL included in the email was extracted and analyzed.

The following details were checked:

* Domain Name
* URL Reputation
* Suspicious Redirects
* Domain Age

### Step 4: Attachment Analysis

Any email attachments were reviewed for suspicious file types or malicious indicators.

### Step 5: IOC Identification

The following Indicators of Compromise were extracted:

* Sender Email Address
* Suspicious URL
* Domain Name
* Source IP Address
* File Hash

### Step 6: Incident Classification

Based on the investigation findings, the email was classified as either:

* Malicious
* Suspicious
* Benign

## Recommended Actions

If the email is confirmed as malicious:

* Block the sender.
* Block the malicious URL or domain.
* Search for similar emails.
* Check whether any users clicked the link.
* Reset affected user credentials if necessary.
* Escalate the incident according to the SOC procedure.

## Conclusion

Phishing investigations require careful analysis of email headers, URLs, attachments, and Indicators of Compromise to determine whether an email is malicious.
