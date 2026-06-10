# Project 02 - Windows Failed Login Detection with Wazuh

## Objective

Detect and monitor failed Windows login attempts using Wazuh SIEM to identify potential brute-force or unauthorized authentication activities.

## Lab Environment

* Wazuh Server
* Windows 10 Endpoint
* Wazuh Agent
* Windows Security Event Logs

## Tasks Performed

1. Configured Windows Audit Policy for failed logon events
2. Verified Windows Security Log collection through Wazuh Agent
3. Generated multiple failed login attempts for testing
4. Monitored authentication events in Wazuh
5. Analyzed Event ID 4625 logs in Threat Hunting

## Results

* Failed login attempts were successfully captured
* Event ID 4625 was detected and logged by Wazuh
* Authentication failure events were visible in the dashboard
* Log collection and monitoring were functioning correctly

## Screenshots

See attached screenshots inside this project folder.

## Conclusion

Successfully configured and tested Windows failed login detection using Wazuh SIEM. The lab demonstrated the ability to monitor authentication failures and detect suspicious login activity, providing a foundation for brute-force attack detection and security monitoring.
