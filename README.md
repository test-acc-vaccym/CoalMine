### Coal Mine
![Canary Image](https://i.imgur.com/P4sowyT.png)

Coal Mine is a tool that checks various VPN providers [Canary notices](https://en.wikipedia.org/wiki/Warrant_canary) and reports any changes that have been found to the back to the user.

**Supported Platforms**:
- Windows
- Linux

**Supported VPNs**:
- Nord
- VPNSecure
- Lokun
- SlickVPN
- IVPN
- Proxy.sh

**To run** (I'll streamline this at some point):
- Clone project
- Install dependencies
- Add _canary.py_ to a cronjob or scheduled task

**Usage Examples**:
>python canary.py -nord

>python canary.py -slickvpn

>python canary.py -proxy.sh

**Notification Examples** (hopefully you never see these):

Windows:

![Windows Alert](https://i.imgur.com/ot59THn.png)

Linux:

![Linux Alert](https://i.imgur.com/fdM5caR.png)
