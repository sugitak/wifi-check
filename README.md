# wifi-check

WiFi health checker for Mac OS X

# usage

Run it. It will give you colorized output.

```
$ ./wifi-check

======== Internet Information
Address: 192.168.0.98
Gateway: 192.168.0.1
Ping: 3.637 ms (100% packets transmitted)
DNS: OK

======== Wireless Information
SSID: your-awesome-ssid
BSSID: 00:00:0c:98:11:10
CHANNEL: 11

======== Radio status
RSSI: -50 / -95 (S/N: 45)
Rate: 54 / 54
MCS: -1
```

Just show it to your system admin and say, "Hey I dunno why but the wifi is so slow, fix it now".

# install

Move it to wherever you want, such like `~/bin`.

# Licensed under the Apache License, Version 2.0

Copyright 2015, sugitak

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
