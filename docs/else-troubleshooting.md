# Troubleshooting

We collect the most common troubleshooting of using Cockpit for your reference:

> Instance troubleshooting is closely related to the Instance provider that is Cloud Platform, refer to [Cloud Platform Documentation](https://support.websoft9.com/docs/faq/tech-instance.html)

#### How can I use the logs?

You can find the keywords **Failed** or **error** from the logs directory: `/data/logs`

#### Cockpit service can't start?

Insufficient disk space and memory, incorrect configuration file may cause the failure to start the service. 

It is recommended to first check through the command.

```shell
# restart Cockpit service
systemctl status cockpit
journalctl -u cockpit

# view disk space
df -lh

# view memory rate
free -lh
```

#### Error in Chrome when modify password?

This error is not attribute to Cockpit server, once you have upgraded you local Chrome, it solved

![chrome error of Cockpit](https://libs.websoft9.com/Websoft9/DocsPicture/zh/cockpit/cockpit-chromeerror-websoft9.png)
