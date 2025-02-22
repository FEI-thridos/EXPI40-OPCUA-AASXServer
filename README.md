**Original repository of AASX Server tool - https://github.com/admin-shell/aasx-server**

Current version **augments existing tool with "expi40" namespace** to make OPC UA server created from AAS easily distinguishable.

How to use:
1. In `./src/AasxServerCore/bin/Release/netcoreapp3.1/startForDemo.bat` path to directory with AASs needs to be set.
2. Start OPC UA server via `startForDemo.bat`.

Server configuration, such as *host*, *port*, *application uri* can be modified in `./src/AasxServerCore/bin/Release/netcoreapp3.1/Opc.Ua.SampleServer.Config.xml`
