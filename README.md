# mail-auth-spf-dkim-dmarc
# Implementing and Auditing SPF, DKIM, and DMARC Configurations for Domain Protection Monitoring

## Project Overview

This project focuses on implementing and auditing email authentication mechanisms to improve domain protection and reduce email spoofing and phishing attacks.

The project covers the configuration and monitoring of:

- SPF (Sender Policy Framework)

- DKIM (DomainKeys Identified Mail)

- DMARC (Domain-based Message Authentication, Reporting, and Conformance)

## Objectives

- Configure email authentication mechanisms.

- Improve domain security against email spoofing.

- Validate email authenticity using SPF, DKIM, and DMARC.

- Document the implementation process and configuration steps.

## Configuration Details

### OpenDKIM Configuration
The configuration file contains OpenDKIM service settings required for DKIM signing and integration with the mail server.

### SPF Configuration

SPF was configured through DNS TXT records to define authorized mail servers allowed to send emails on behalf of the domain.

### DKIM Configuration

DKIM was implemented using cryptographic keys to allow receiving mail servers to verify message authenticity.

### DMARC Configuration

DMARC was configured through DNS TXT records to define email handling policies and reporting mechanisms.

## Evidence

The repository contains screenshots and documentation showing the implementation process and configuration verification.

## Tools Used

- Ubuntu Linux

- OpenDKIM

- Postfix Mail Server

  

- GitHub

## Repository Contents

- Project documentation

- Configuration evidence

- Screenshots

- Final project report PDF
OpenDKIM was used to provide DKIM email signing functionality.

Main configuration file:
