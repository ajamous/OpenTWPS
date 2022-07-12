![ad17cc000fd94744a359aa0eefcfc82b](https://user-images.githubusercontent.com/19316784/178379844-24bbfc40-b2c3-48cb-a6c5-0a657568c7c7.png)


# What is OpenTWPS?

The Open Telecom Wholesale Price-list Standard is a simple format for representing structured telecom service price list information: documents, data, configuration, and more.


# Introduction

Our recent research on telecom business to business (b2b) price-list automation for voice, SMS and virtual numbers shows that it is still a dilemma to get full automation integration working between communication service providers (CSPs) with high precision. The obvious reason for this is that there is no standard set for price list formats to help automate this process once and for all. 

We believe that starting an open standard (OS) initiative for telecommunications wholesale price-list formats and exchange methods will provide many benefits to CSPs, businesses, and Telecom application developers immediately, the POC also shows that it can be achieved with very minimal changes on the carrier side they can get compliant with the Open Telecom Wholesale Price-list Standard.

An open standard is a standard that is openly accessible and usable by anyone. It is also a prerequisite to use open license, non-discrimination and extensibility.[1] Typically, anybody can participate in the development.[3] There is no single definition, and interpretations vary with usage.


# What is OpenTWPS Used For?

OpenTWPS is used for helping interconnected communication service providers and businesses automate the processing of regular price-lists updates between two different billing systems with minimal effort and no errors.

**List of OpenTWPS compliant providers**

- [NeuTrafix](https://neutrafix.net)

- [TelecomsXChange (TCXC)](https://www.telecomsxchange.com)


# OpenTWPS Examples

**Voice** 

| Prefix E164 | Price1 | Price N | Valid From | Timezone | Interval 1 | Interval N | Forbidden | Discontinued |
| ----------- | ------ | ------- | ---------- | -------- | ---------- | ---------- | --------- | ------------ |
| 79407       | 0.3000 | 0.3000  | ASAP | UTC      | 1          | 1          | 0         | 0            |
| 79409       | 0.2850 | 0.2850  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 7840        | 0.2850 | 0.2850  | yyyy-mm-dd | UTC      | 1          | 1          | 0         | 0            |
| 9370        | 0.1635 | 0.1635  | yyyy-mm-dd hh:mm:ss | UTC      | 1          | 1          | 0         | 0            |
| 9371        | 0.1635 | 0.1635  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 9374        | 0.1622 | 0.1622  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 9375        | 0.1622 | 0.1622  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 9376        | 0.1154 | 0.1154  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 9377        | 0.1154 | 0.1154  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 9373        | 0.1468 | 0.1468  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 9378        | 0.1468 | 0.1468  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 93          | 0.1622 | 0.1622  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 9372        | 0.1750 | 0.1750  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 9379        | 0.1750 | 0.1750  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 93750       | 0.1650 | 0.1650  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 23670       | 0.4850 | 0.4850  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 23672       | 0.4350 | 0.4350  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 2367        | 1.5000 | 1.5000  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 236         | 1.5000 | 1.5000  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 23621       | 1.5000 | 1.5000  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 23622       | 1.5000 | 1.5000  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 23636       | 1.5000 | 1.5000  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 23674       | 1.5000 | 1.5000  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 2368776     | 1.5000 | 1.5000  | 2022-07-11 | UTC      | 1          | 1          | 0         | 0            |
| 23675       | 0.4950 | 0.4950  | 2022-07-11 | UTC      | 60         | 60         | 0         | 0            |

**SMS** 

| MCCMNC E.212 | Price  | Effective From | forbidden | discontinued |
| ------ | ------ | -------------- | --------- | ------------ |
| 28967  | 0.0129 | ASAP           | 1         | 0            |
| 28988  | 0.0295 | 2022-07-11           | 1         | 0            |
| 41201  | 0.0847 | yyyy-mm-dd           | 1         | 0            |
| 41220  | 0.0836 | yyyy-mm-dd hh:mm:ss           | 1         | 0            |
| 41240  | 0.0763 | ASAP           | 1         | 0            |
| 41250  | 0.0771 | ASAP           | 1         | 0            |
| 41280  | 0.0838 | ASAP           | 0         | 0            |
| 41288  | 0.0838 | ASAP           | 0         | 0            |
| 27601  | 0.0311 | ASAP           | 0         | 0            |
| 27602  | 0.0397 | ASAP           | 0         | 0            |
| 27603  | 0.0315 | ASAP           | 0         | 0            |
| 27604  | 0.0498 | ASAP           | 0         | 0            |

**Parameters**

Supported Effective Date formats: 

- Effective Date: date when record becomes active, sample date: '2015-01-01 01:01:01'. For rates that don`t have 'Forbidden' or 'Discontinued' flag, rates can only be updated after X hours as defined by billing system. Special value supported: ASAP. If ASAP is specified as value, the rate will become immediately blocked if 'Forbidden' or 'Discontinued' flag is set, and now + X hours for rates with traffic allowed.

- Forbidden: flag to disallow traffic to certain prefix, sample usage: payphone destinations. 0 - Allowed, 1 - Forbidden.
- Discontinued: flag to marked prefix rate as deleted (system will delete them after some time as defined by receiving billing system). 0 Allowed, 1 - Discontinued

- Price1: price per minute for first billing interval (Interval1), sample:0.0523

- PriceN: price per minute for next billing interval (IntervalN), sample:0.0523
- Interval1: duration for first interval, sample: 1 for 1/1 billing
- IntervalN: duration for next interval, sample: 1 for 1/1 billing



**Virtual Numbers**

| Number e164 | Inbound Voice Price | Inbound SMS Price | Interval | MRC | NRC | Documents Verification Required | Status | Type | Voice | SMS | Fax | Video | Capacity | Notes                 | Local Requirements |
| ----------- | ------------------- | ----------------- | -------- | --- | --- | ------------------------------- | ------ | ---- | ----- | --- | --- | ----- | -------- | --------------------- | ------------------ |
| 19542305444 | 0.05                | 0.02              | 60       | 10  | 10  | 1                               | 0      | DID  | 1     | 1   | 1   | 0     | 2        | Some notes for buyers | 1                  |

**Parameters**

Supported Effective Date formats: 

- Number e.164: is the full valid virtual phone number 
- MRC:Monthly Reccuring Charge
- NRC: None Reccuring Charge - Onetime fee
- SMS Enabled: 1 is SMS enabled , 0 is not SMS enabled
- Voice Enabled: 1 is voice enabled , 0 is not voice enabled
- Video Enabled: 1 is video enabled , 0 is not video enabled
- Documents Verification Required: 1 if KYC verification is required for the number before it becomes active, 0 if not required and number will immediatley be active after purchase.

- Inbound Voice Price: price per minute

- Inbound SMS price: price per message submission.
- Interval: duration for first interval + second interval , sample: 1 for 1/1 billing, 60 for 60/60.
- Type: is the number type, e.g. ITFS, DID, Shortcode, LongCode etc.. 

# Delivery Channels 

**Email (SMTP)**

Sending an OpenTWPS compliant file `.csv, xls, .xlsx` via email using SMTP protocol with `DKIM` enabled to the buyer(s).

`DKIM` is a standard email authentication method that adds a digital signature to outgoing messages. Receiving mail servers that get messages signed with DKIM can verify messages actually came from the sender, and not someone impersonating the sender.

**API & Webhooks**

**API**

An application programming interface is a way for two or more computer programs to communicate with each other. It is a type of software interface, offering a service to other pieces of software. A document or standard that describes how to build or use such a connection or interface is called an API specification.

**Webhook**

A webhook (also called a web callback or HTTP push API) is a way for an app to provide other applications with real-time information. A webhook delivers data to other applications as it happens, meaning you get data immediately. Unlike typical APIs where you would need to poll for data very frequently in order to get it real-time. This makes webhooks much more efficient for both provider and consumer. The only drawback to webhooks is the difficulty of initially setting them up.

Webhooks are sometimes referred to as “Reverse APIs,” as they give you what amounts to an API spec, and you must design an API for the webhook to use. The webhook will make an HTTP request to your app (typically a POST), and you will then be charged with interpreting it.

**OpenTWPS API/Webhook Examples**

@TODO
