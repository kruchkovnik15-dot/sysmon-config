# Sysmon Detection Engineering Configuration

Detection-focused Sysmon configuration designed to collect high-value telemetry for threat detection, threat hunting, and incident response.

## Objectives

This project focuses on:

* Credential Access detection
* Defense Evasion detection
* Persistence monitoring
* LOLBin abuse visibility
* PowerShell abuse detection
* Ransomware precursor activity
* Threat hunting telemetry

## Telemetry Strategy

The configuration intentionally prioritizes high-signal events over broad collection to reduce storage consumption and analyst fatigue.

Coverage areas include:

* Process Creation
* Process Access
* Registry Modifications
* File Creation
* DLL Loading

## ATT&CK Coverage

* T1003 Credential Access
* T1059 PowerShell
* T1112 Registry Modification
* T1218 Signed Binary Proxy Execution
* T1490 Inhibit System Recovery
* T1562 Defense Evasion

## Repository Structure

configs/
documentation/
hunting/

## Intended Use

This repository is intended for detection engineering research, telemetry tuning, threat hunting, and lab validation.
