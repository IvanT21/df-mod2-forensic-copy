# df-mod2-forensic-copy

Welcome - this repository is designed to help users develop PowerShell skills for digital forensics purposes. The primary focus is on copying forensic evidence and verifying the copied data with hash values to ensure the integrity of the evidence.

The repository provides a collection of PowerShell scripts and resources to facilitate building practical skills in digital forensics.

## Overview

In Module 2, we focus on creating forensic copies of digital evidence to preserve the original data for investigation and analysis. This process ensures that the integrity of the evidence is maintained and provides a reliable basis for forensic examination.

The scripts included in this repository automate the process of copying evidence files and calculating hash values for verification. By using these scripts, forensic investigators can efficiently create and verify forensic copies of evidence files, ensuring the integrity and authenticity of the data.

## Contents

- `evidence`: Directory containing the original evidence files.
- `evidence_copy`: Directory to store the forensic copies of evidence files.
- `hash_values.txt`: Text file containing the hash values of original evidence files.
- `hash_values_copy.txt`: Text file containing the hash values of copied evidence files.
- `README.md`: This file providing information about the repository and its contents.

## Usage

1. Clone this repository to your local machine.
2. Place the original evidence files in the `evidence` directory within the repository directory.
3. Run the following command in PowerShell to create forensic copies of evidence files:

powershell
.\evidence_copy.ps1
