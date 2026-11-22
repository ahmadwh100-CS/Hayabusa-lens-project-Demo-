# Windows Attack Simulation & Digital Forensics Investigation
### Disclaimer

This project is an educational simulation conducted in a controlled Windows environment. The activities described were intentionally performed for learning and demonstration purposes. They do not represent a real-world security incident or an actual attack against an organization.
## Overview

This project demonstrates a simulated Windows security incident investigated using **Hayabusa** and **Hayabusa-Lens**.

I created my own attack scenario on a Windows machine, simulating several techniques commonly associated with real-world attacks. I then collected and analyzed Windows Event Logs to investigate the activity and reconstruct the sequence of events.

## Objectives

- Simulate suspicious activity on a Windows environment.
- Generate realistic Windows Event Log evidence.
- Investigate suspicious events using Hayabusa and Hayabusa-Lens.
- Reconstruct the attack timeline and identify evidence of attacker activity.

## Tools & Technologies

- Hayabusa
- chainsaw 
- Hayabusa-Lens
- Windows Event Logs (.evtx)
- Windows 11 VM

## Investigation Scenario

The simulated incident includes:

- Password Brute Force / Password Spraying Attempts
- Unauthorized User Account Creation
- Persistence Mechanism
- Windows Event Log Clearing

## Investigation Documentation

The detailed investigation findings, attack timeline, and supporting screenshots are available here:

[View Investigation Findings](Investigation/Findings.md)

## Installing hayabusa-lens

1. Install the Requirements

Hayabusa-Lens requires Python 3.9 or newer.

Download Python from: https://www.python.org/downloads/
2. Installing python
On Windows, open PowerShell and install pipx:
```powershell
py -m pip install --user pipx
py -m pipx ensurepath
```
3. Installing hayabusa-lens
Close and reopen PowerShell, then install Hayabusa-Lens:
```Powershell
pipx install hayabusa-lens
```
4. Launch Hayabusa-Lens
Run:
```Powershell
hayabusa-lens
```
The application should open in your browser.
