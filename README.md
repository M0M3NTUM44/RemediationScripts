
# Remediation Scripts for Incident Response and Security Enhancement

## Overview

This repository contains a collection of remediation scripts designed for use during incident responses (IRs) and for improving security postures in various environments. These scripts are developed to provide 
quick, efficient, and reliable solutions to common security challenges faced in today's dynamic cyber landscape.

## Installation

`git clone https://github.com/yourusername/remediation-scripts.git`
`cd remediation-scripts`

## Script Catalogue

- FindADClearTextPasswords.ps1: For enumerationg AD users with clear-text credentials in thier description. Usage:
  `.\FindADClearTextPasswords.ps1 -MinLength 8 -Complexity $true`

## Disclaimer

You are responsible for using these scripts at their own risk and should test them in a controlled environment before deployment.
