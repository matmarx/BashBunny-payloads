# Bash Bunny custom payloads

Bash Bunny is USB attack platform that can mimic USB HID device, Ethernet adapters, or mass storage devices. Official community developed payloads can be found at https://github.com/hak5/bashbunny-payloads

## Custom payloads

### [BunnyRunExe](/BunnyRunExe)
Run calc.exe from a Bash Bunny storage. The payload is using standard Windows Run in order to spawn Powershell process with cmd execution of our custom binary. For PoC I am using calc.exe