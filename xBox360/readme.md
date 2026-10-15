- Bad Update 1.3 - a hypervisor exploit for all xbox360 models. It's instant with almost 100% success rate. It's not persistent - have to run after every boot.
- XeUnshackle 1.02 - a .xex payload invoked by Bad Update, which can invoke further component to initiate customer GUI, e.g., Aurora.
- XeUnshackle Max - a fork of XeUnshackle, with some optimization specifically for BadUpdate.
- Aurora - a customer GUI could be invoked by XeUnshackle. It can temporarily unlock trial game.

## Unlock demo / trial game:
- xm360 - a tool to unlock demo and trial games. However, there are reports this would patch all games, including those has proper signature already, which may break them.
- Set value at address 0x237 to 0x01 on a trial game using a hex editor will unlock it.
- Le Fluffie - a Windows utility tool used for managing, editing, and re-signing Xbox 360 files.
