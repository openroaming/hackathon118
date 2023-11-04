# OpenRoaming at IETF 118 Hackathon
[IETF 118 Hackathon](https://wiki.ietf.org/en/meeting/118/hackathon)

---
## MADINAS Charter

The group will generate a Best Current Practices (BCP) document
recommending means to reduce the impact of RCM on the
documented use cases **while ensuring that the privacy achieved
with RCM is not compromised.**

---
## MADINAS - Wi-Fi OpenRoaming
Champion(s)
* Bruno Tomas <bruno@wballiance.com>

* Mark Grayson <mgrayson@cisco.com>

## Project Info
[OpenRoaming](https://www.ietf.org/archive/id/draft-tomas-openroaming-00.html) works similarly to Eduroam, allowing users to automatically connect to Wi-Fi networks, but with a federated structure that allows multiple Access Network Providers (ANPs) and multiple Identity Providers (IDPs) to interoperate under the same federation. It leverages technologies developed in the IETF, IEEE802 and Wi-Fi Alliance (WFA), such as RADIUS/RADSEC/PKI (RFCs 2865, 3579, 4372, 5280, 6614…), IEEE 802.1X, 802.11, and WFA WPA2/WPA3. 

OpenRoaming is being discussed as a solution to some of the use cases considered by the IETF MADINAS WG. **The project will look for potential areas of improvement to IETF protocols, as well as potential leakage of PIIs.**

NOTE1: Hackathon participants wanting to be issued a test certificate for use in mutually authenticated OpenRoaming signalling exchanges, should email <pki@wballiance.com> with the subject “IETF Hackathon Test Certificate Request”.

NOTE2: The OpenRoaming PKI Certificate Policy and WBA issuing I-CA require specific subject distinguished name values. An example certificate signing request configuration that meets the OpenRoaming Certificate Policy is available [here](https://github.com/wireless-broadband-alliance/openroaming-config/blob/main/OpenRoaming%20CSR%20config.cfg).

### Useful resources
How to enable OpenRoaming on the MikroTik series of devices (by Warren Kumari, based on his setup for IETF 117): https://wkumari.dev/2023/10/16/mikrotik-openroaming

---

## Background RADEXT Working Group and previous MADINAS presentations

RADEXT working group is currently updating on [Deprecating Insecure Practices in RADIUS](https://www.ietf.org/archive/id/draft-dekok-radext-deprecating-radius-05.html), 
including analysing ways to increase RADIUS privacy by minimizing the amount of PII sent in RADIUS packets, including use of the [Chargeable-User-Identity](https://www.ietf.org/archive/id/draft-dekok-radext-deprecating-radius-05.html#name-chargeable-user-identity).

At IETF 117, an initial set of observations were made using credentials from a limited number of OpenRoaming IDPs and [presented](https://datatracker.ietf.org/meeting/117/materials/slides-117-madinas-some-experiences-with-openroaming-v02-00) to the MADINAS WG. 

---

## Hackathon 118

### Aims

Analyse the possible leakage of privacy information by a variety of OpenRoaming Identity Providers (IDPs) for a variety of different OpenRoaming Access Network Provider (ANP) use-cases.

### Use-Cases

1. Tracking between devices - OpenRoaming user with subscription on multiple devices
2. Tracking between access networks - OpenRoaming user with subscription on single device that moves between multiple different OpenRoaming access networks
3. Temporal tracking by a single access network - OpenRoaming user authenticating on day 1 and day 2

#### Impact of IDP Configuration
#1, #2 and #3 for a range of different IDPs

#### Impact of User consent
#1, #2 and #3 when user has consented to share personally identifiable information with the ANP

#### Impact of different device types
#1, #2 and #3 for different device types

#### Impact of different access networks/NAS types
#1, #2 and #3 for different access network vendors



