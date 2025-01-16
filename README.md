# wazuh-snoopy-rules-decoders

Hello, here are some decoders (at least 7) and one rule that can be used with the [Snoopy Command Logger](https://github.com/a2o/snoopy).

## Installation

1. Copy the decoders and rules to your Wazuh Manager

Copy 0751-snoopy_decoders.xml to /var/ossec/etc/decoders/
Copy 0751-snoopy_rules.xml to /var/ossec/etc/rules/

2. Restart Wazuh Manager
`systemctl restart wazuh-manager`

3. Check if the service has no failure
`systemctl status wazuh-manager`
