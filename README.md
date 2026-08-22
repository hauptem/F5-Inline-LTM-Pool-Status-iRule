# F5 BIG-IP Inline LTM Pool Status iRule

![License](https://img.shields.io/badge/license-MIT-green)
![TMOS Version](https://img.shields.io/badge/TMOS-17.x%20%7C%2021.x-red)
![F5 iRules](https://img.shields.io/badge/F5-iRules%20(Tcl)-FF6600?logo=f5&logoColor=white)

A modern inline LTM "pool status" iRule that displays pool member state information when a client sends an HTTP GET request to /f5poolstatus.

DNS only supports IPv4 at this time.

Ensure to do your own offline testing in your environment before placing on production virtual servers.

## Requirements

- BIG-IP running TMOS 17.x or 21.x series

<img width="1493" height="774" alt="Image" src="https://github.com/user-attachments/assets/a1f68864-e442-4603-8741-d3c613d822ed" />

<img width="1476" height="758" alt="Image" src="https://github.com/user-attachments/assets/ba0d3556-5037-4db3-a852-4983f18007e3" />

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
