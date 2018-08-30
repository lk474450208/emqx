# *EMQ X* - MQTT Broker


*EMQ X* broker is fully a open source, highly scalable, highly available distributed message broker for IoT, M2M and Mobile applications that can handle tens of millions of concurrent clients.

Starting from 3.0 release, *EMQ X* broker fully supports MQTT V5.0 protocol specifications and backward compatible with MQTT V3.1 and V3.1.1,  as well as other communication protocols such as MQTT-SN, CoAP, LwM2M, WebSocket, STOMP and SockJS. The 3.0 release of the *EMQ X* broker can scaled to 10+ million concurrent MQTT connections on one cluster.


- For full list of new features, please read *EMQ X* broker 3.0 [release notes](https://github.com/emqtt/emqttd/releases/).
- For more information, please visit [EMQ X homepage](http://emqtt.io). 



## Installation

The *EMQ* broker is cross-platform, which can be deployed on Linux, Unix, Mac, Windows and even Raspberry Pi.

Download the binary package for your platform from [here](http://emqtt.io/downloads).

-[Single Node Install](http://emqtt.io/docs/v2/install.html)
-[Multi Node Install](http://emqtt.io/docs/v2/cluster.html)


## Build From Source

The *EMQ* broker requires Erlang/OTP R21+ to build since 3.0 release.

```
git clone https://github.com/emqtt/emq-relx.git

cd emq-relx && make

cd _rel/emqttd && ./bin/emqttd console

```

## Quick Start

    # Start emqttd
    ./bin/emqttd start
    
    # Check Status
    ./bin/emqttd_ctl status
    
    # Stop emqttd
    ./bin/emqttd stop

  To view the dashboard after running, use your browser to open: http://localhost:18083


## Roadmap

The [EMQX roadmap uses Github milestones](https://github.com/emqtt/emqttd/milestones) to track the progress of the project.

## Community, discussion, contribution, and support

You can reach the EMQ community and developers via the following channels:
- [EMQX Slack](http://emqx.slack.com)
   -[#emqx-users](https://emqx.slack.com/messages/CBUF2TTB8/)
   -[#emqx-devs](https://emqx.slack.com/messages/CBSL57DUH/)
- [Mailing Lists](<emqtt@googlegroups.com>)
- [Twitter](https://twitter.com/emqtt) 
- [Forum](https://groups.google.com/d/forum/emqtt)
- [Blog](https://medium.com/@emqtt)

Please submit any bugs, issues, and feature requests to [emqtt/emqttd](//github.com/emqtt/emqttd/issues). 


## License
Copyright (c) 2014-2018 [EMQ X Tech, LLC](http://emqtt.io)

Licensed under the Apache License, Version 2.0 (the "License");you may not use this file except in compliance with the License.You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and limitations under the License.




