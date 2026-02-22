# Library, Protocol, and Asset Installation

1. Download the libraries from the [Client](https://github.com/Hytale-Client-C/Client) repository and unzip it to the same folder.

2. In the `Game` folder, create a folder named `Interface`. It should look like this:
   `release\package\game\latest\Client\Game\Interface`

3. Download the archive from the [Interface](https://github.com/Hytale-Client-C/Interface/releases) repository and extract it into this folder (`Game\Interface`).

4. Download [SDL2-CS](https://github.com/Hytale-Client-C/SDL2-CS). This project is a C# wrapper for SDL2. Download the latest release or build the project yourself, then extract it into the `latest` folder with replacement.

5. Download [Wwise_CS](https://github.com/Hytale-Client-C/Wwise_CS). This project is a C# wrapper for Wwise. Download the latest release or build the project yourself, then extract it into the `latest` folder with replacement.

6. Download [HytaleProtocol](https://github.com/Hytale-Client-C/HytaleProtocol). This repository contains all the protocols used by the client to communicate with the server. It is updated frequently, so download the latest version or build the project yourself, then extract it into the `latest` folder with replacement. **Keep an eye on updates and make sure to update it regularly!**

7. Download the latest version of [Zlib](https://github.com/Hytale-Client-C/Zlib/releases) and add it to the `Client` folder with replacement.

8. Download the latest version of [AuthProtocol](https://github.com/Hytale-Client-C/AuthProtocol/releases) and add it to the `Client` folder with replacement.

9. Download the latest version of [HytaleAPI](https://github.com/Hytale-Client-C/CommonStub/releases) and add it to the `Client` folder with replacement.

10. Download the shaders from [Hytale-Shaders](https://github.com/Hytale-Client-C/Hytale-Shaders) and extract them to:
    `release\HytaleClient\Graphics\Shaders`
    **Keep an eye on updates and make sure to update them regularly!**

Almost ready to launch ✨ Just a couple of small steps left!

NEXT: [03_configuration_and_finalization.md](03_configuration_and_finalization.md)