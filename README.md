This script automatically replies email according to pre-established filter. Each replies made will also out to Slack as a notif/logging purpose.
Combine with orchestration such as Jenkins/Azure DevOps/AWS Pipeline (Zabbix in my case) to cycle reply execution to mailbox.
![image](https://user-images.githubusercontent.com/101460772/158055400-1ad2b800-ab27-4882-80c0-fddb46056bc5.png)
Can be used conceptually for similiar use case to other email principal where email response time is critical as well or other querying case.

Refference used/related in this repo:
- [Outlook API](https://docs.microsoft.com/en-us/outlook/rest/get-started)
- [jq lib](https://stedolan.github.io/jq/)
