# Antivirus Compatibility with AMSI

AMSI (Antimalware Scan Interface) is designed for the detection and prevention of malicious commands or scripts by integrating with various antivirus solutions. It enables real-time inspection of all executed PowerShell, JScript, VBScript, VBA, or .NET commands or scripts. Specifically, AMSI captures each command or script at runtime and submits it to the local antivirus software for thorough inspection, ensuring a comprehensive defense mechanism against script-based threats. However, if the local antivirus software is not AMSI-compliant, this security mechanism is compromised, leaving endpoints vulnerable to sophisticated script-based attacks.

## Key Features

- **Compatibility Information**: This table indicates whether each antivirus product supports AMSI.
- **Current as of Last Update**: The information provided is accurate as of the date of the last update. Users are encouraged to verify compatibility with the latest information from antivirus vendors.

## Antivirus Compatibility Table

| Antivirus                      | Compatible with AMSI | Notes                                       |
|--------------------------------|----------------------|---------------------------------------------|
| Windows Defender Antivirus     | Yes                  |                                             |
| Kaspersky                      | Yes                  |                                             |
| Symantec/Norton                | Yes                  |                                             |
| McAfee                         | Yes                  |                                             |
| Trend Micro                    | Yes                  |                                             |
| Sophos                         | Yes                  |                                             |
| Bitdefender                    | Yes                  |                                             |
| ESET                           | Yes                  |                                             |
| Avira                          | Yes                  |                                             |
| CrowdStrike                    | Yes                  |                                             |
| F-Secure                       | Yes                  |                                             |
| Malwarebytes                   | Yes                  |                                             |
| Webroot                        | Yes                  |                                             |
| Check Point                    | Yes                  |                                             |
| G Data                         | Yes                  |                                             |
| Cylance                        | Yes                  |                                             |
| SecureAPlus                    | Yes                  |                                             |
| Immunet                        | Yes                  |                                             |
| Panda Security                 | Yes                  |                                             |
| SentinelOne                    | Yes                  |                                             |
| Norton Antivirus Basic/Standard| No                   | Contact vendor for future support updates.  |
| Avast                          | No                   | Contact vendor for future support updates.  |
| AVG                            | No                   | Contact vendor for future support updates.  |
| Comodo                         | No                   | Contact vendor for future support updates.  |
| ZoneAlarm                      | No                   | Contact vendor for future support updates.  |
| 360 Total Security             | No                   | Contact vendor for future support updates.  |
| Baidu Antivirus                | No                   | Contact vendor for future support updates.  |

## Notes

- AMSI compatibility may vary depending on the versions of the antivirus products. It is recommended to consult the official documentation of the products or contact the technical support of the vendors for up-to-date information.
- This list is subject to change as vendors update their products to support AMSI.

## Update Schedule

- This compatibility table is accurate as of June 11, 2024. Users are encouraged to verify information with the respective vendors for the most recent updates.

## Contributing

Contributions are welcome! For updates or corrections, please open an issue or submit a pull request.

## Disclaimer

The information in this repository is provided "as is" without warranty of any kind. Please consult the official documentation of the antivirus products or contact the vendors for the most accurate and up-to-date information.
