# F5 BIG-IP Inline LTM Pool Status iRule

![License](https://img.shields.io/badge/license-MIT-green)
![TMOS Version](https://img.shields.io/badge/TMOS-17.x%20%7C%2021.x-red)
![F5 iRules](https://img.shields.io/badge/F5-iRules%20(Tcl)-FF6600?logo=f5&logoColor=white)

A modern inline LTM "pool status" iRule that displays pool member state information when a client sends an HTTP GET request to /f5poolstatus.

DNS only supports IPv4 at this time.

Ensure to do your own offline testing in your environment before placing on production virtual servers.

## Requirements

- BIG-IP running TMOS 17.x or 21.x series

<img width="1051" height="809" alt="Image" src="https://github.com/user-attachments/assets/e3b35e6e-4272-4d20-ac25-1e9be575581a" />

<img width="1040" height="800" alt="Image" src="https://github.com/user-attachments/assets/b1b93edf-2397-4a2f-8ba7-9f8fbbfeff29" />

<img width="1041" height="853" alt="Image" src="https://github.com/user-attachments/assets/8be3c99f-68a5-48a0-8f07-def963fb4b7a" />

## License

MIT License - see [LICENSE](LICENSE) file for details.

## Disclaimer

- This solution is **NOT** officially endorsed, supported, or maintained by F5 Inc.
- F5 Inc. retains all rights to their trademarks, including but not limited to "F5", "BIG-IP", "LTM", "APM", and related marks
- This is an independent, community-developed solution that utilizes F5 products but is not affiliated with F5 Inc.
- For official F5 support and solutions, please contact F5 Inc. directly

**Technical Disclaimer:**

- This software is provided "AS IS" without warranty of any kind
- The authors and contributors are not responsible for any damages or issues that may arise from its use
- Always test thoroughly in non-production environments before deployment
- Backup your F5 configuration before implementing any changes
- Review and understand all code before deploying to production systems

By using this software, you acknowledge that you have read and understood these disclaimers and agree to use this solution at your own risk.
