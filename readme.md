# Server Status Monitor Client

This is the client that sends status information to [Server Monitor](https://servermonitor.offlineml.com). It is used to integrate your servers with the [Server Monitor](https://servermonitor.offlineml.com) application.

## Change API Key, other configurations and verify configurations

### Linux

```bash
sudo nano /opt/server-status-client/api_configs.json
sudo systemctl restart server-status-client
```

### Windows

```bash
cd 'C:\Program Files\Server-Status-Client'
.\windows_client.exe stop
notepad.exe 'C:\Program Files\Server-Status-Client\api_configs.json'
.\windows_client.exe start
```
