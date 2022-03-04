#LED Controller

Addressable LED Strip controller in python for Raspberry Pi.  

#### List of commands:

| Commands                                  | Paramerters                         | Note                                           |
|-------------------------------------------|-------------------------------------|------------------------------------------------|
| `/`                                       | n/a                                 | This page                                      |
| `/help`                                   | n/a                                 | Help page                                      |
| `/setColor?r=100&g=130&b=200&w=50`        | [r, g, b, w] from 0 to 255          | Sets the whole strip to specified color values |
| `/setLeft?r=0&g=0&b=255&w=0`              | [r, g, b, w] from 0 to 255          | Sets color to the left alcove                  |
| `/setRight?r=0&g=255&b=0&w=0`             | [r, g, b, w] from 0 to 255          | Sets color to the right alcove                 |
| `/setLedColor?id=1&r=100&g=130&b=200&w=0` | [id] and [r, g, b, w] from 0 to 255 | Sets led id to specified color                 |
| `/setRaw?data=_wAA_gAA_QAB_QAB`           | [data]                              | String of color values                         |
| `/getColor`                               | n/a                                 | Returns JSON data with color                   |

Made by xPiTi
