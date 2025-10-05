# F5 BIG-IP Inline LTM Pool Status iRule

![License](https://img.shields.io/badge/license-MIT-green)
![F5 Compatible](https://img.shields.io/badge/F5%20BIG--IP-compatible-orange)
![TMOS Version](https://img.shields.io/badge/TMOS-15.0%2B-red)
![F5 iRules](https://img.shields.io/badge/F5-iRules%20(Tcl)-FF6600?logo=f5&logoColor=white)

A modern LTM iRule that displays pool member state information when a client sends an HTTP GET request to /f5poolstatus.

Version 1.1 has been updated to work with IPv6 addresses. Ensure to do your own offline testing in your environment for IPv6 functionality before placing on production virtual servers.

<img width="1221" height="896" alt="Image" src="https://github.com/user-attachments/assets/7107bdae-c955-4049-a0b4-0f224ef329dd" />

<img width="1221" height="896" alt="Image" src="https://github.com/user-attachments/assets/046a033b-0c52-4ccd-a210-39c3ebd5b31a" />

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

