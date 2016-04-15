# ansible-playbooks
Playbooks I want to track. Some I wrote, most I did not.

#### /junos_version.yml
Simple get Junos version. 

#### /junos_serial.yml
Simple get serial numbers from Junos devices. 

#### /junos_multiple_ex_upgrade.yml
Play to upgrade multiple models of EX switches in one playbook.
Technically this will work for more than just the EX but I focused on EX testing for this. If want to use it on say an SRX it will work but the LLDP tests will fail so adjust accordingly.