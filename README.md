# chs-CompliancePolicyGenerator
Generates configuration hardening scripts based on predefined compliance policies (e.g., CIS benchmarks). Takes a compliance standard as input and outputs a script tailored to that standard. - Focused on Generates platform-specific hardening scripts (e.g., shell scripts, Ansible playbooks) based on security benchmarks (e.g., CIS benchmarks). Takes YAML-based configuration definitions as input, allowing users to customize hardening settings. Helps automate the process of implementing security best practices.

## Install
`git clone https://github.com/ShadowStrikeHQ/chs-compliancepolicygenerator`

## Usage
`./chs-compliancepolicygenerator [params]`

## Parameters
- `-h`: Show help message and exit
- `--compliance-standard`: No description provided
- `--config-file`: The path to the YAML configuration file
- `--output-file`: The path to the output script file
- `--platform`: No description provided

## License
Copyright (c) ShadowStrikeHQ
