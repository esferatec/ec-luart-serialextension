# ec-luart-serialextension

This project provides various extension serial functions and properties for [LuaRT](https://www.luart.org/).

[![LuaRT 2.1.0](https://badgen.net/badge/LuaRT/2.1.0/blue)](https://github.com/samyeyo/LuaRT)

## Features

The module provides the following extension functions and properties:

| Name | Description
| --- | --- |
| baudrates | List of supported baud rates for serial communication. |
| bytesize | List of supported byte sizes for serial communication. |
| comports() | Get a list of all current available com ports.
| dtrmode | List of supported DTR (Data Terminal Ready) modes. |
| parity | List of supported parity settings for serial communication. |
| rtsmode | List of supported RTS (Request to Send) modes. |
|stopbits | List of supported stop bits settings for serial communication. |

More detailed descriptions and usage examples can be found in the docs folder.

## Installation

1. Create a folder called "ecluart" in your application.
2. Copy the "serialextension.lua" file into this folder.

```text
[application]
|
|----ecluart
|   |
|   |----serialextension.lua
|   |----...
|
|----app.wlua
```

## Usage

The extension module can be loaded using the function *require()*:

```lua
local serialex = require("ecluart.serialextension") 
```

## License

Copyright (c) 2023 by esferatec.
It is open source, released under the MIT License.
See full copyright notice in the LICENSE.md file.
