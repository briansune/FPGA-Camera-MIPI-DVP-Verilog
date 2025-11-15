# Possibly the most best Verilog-Based Camera and FPGA Examples

## If this project is constructive, welcome to donate a drink to PayPal.

<img src="https://github.com/briansune/FPGA-Camera-MIPI-DVP-Verilog/assets/29487339/75ccc568-4f17-48a1-b2af-20211f98896c" width="200"/>

or 

paypal.me/briansune

## Example projects are based on commonly found CMOS sensor and FPGA

### The sensors example - Altera

| Idx | Sensor | Project Status | Interface | Project Link | FPGA | IDE | FPS (MAX) | <p>Resolution<br>W<br>H</p> | <p>Target<br>FPS<br>Resolution<br>Color</p> |
| - | - |  - | - | - | - | - | - | - | - |
|  1 | IMX415  | 🟢 DONE    | MIPI | [IMX415](https://github.com/briansune/Cyclone-V-MIPI-IMX415)   | Cyclone V SoC | Quartus Prime | 60 | <p>3840<br>2160</p> | <p>60<br>1080P<br>debayer</p>           |
|  2 | IMX291  | 🟢 DONE    | MIPI | [IMX291](https://github.com/briansune/Cyclone-V-MIPI-IMX291)   | Cyclone V SoC | Quartus Prime | 60 | <p>1920<br>1080</p> | <p>60<br>qHD<br>debayer</p>             |
|  3 | OV4689  | 🟢 DONE    | MIPI | [OV4689](https://github.com/briansune/Cyclone-V-MIPI-OV4689)   | Cyclone V SoC | Quartus Prime | 60 | <p>1344<br>760</p>  | <p>60<br>CMOS Resoultion<br>debayer</p> |
|  4 | OV13850 | 🟢 DONE    | MIPI | [OV4689](https://github.com/briansune/Cyclone-V-MIPI-OV13850)  | Cyclone V SoC | Quartus Prime | 30 | <p>3840<br>2160</p> | <p>30<br>1080p<br>debayer</p>           |

### The sensors example - Xilinx

#### Vivado Version & Kindly Reminds

For Vivado, using block diagram method is very userfriendly!

However, please pay GOOD attention to the reset polarity!

| Idx | Sensor | Project Status | Interface | Project Link | FPGA | IDE | FPS (MAX) | <p>Resolution<br>W<br>H</p> | <p>Target<br>FPS<br>Resolution<br>Color</p> |
| - | - |  - | - | - | - | - | - | - | - |
|  1 | OV13850 | 🟢 DONE    | MIPI | [OV13850](https://github.com/briansune/Kintex-7-OV13850-Verilog)         | <p>Xilinx<br>7 Series Above</p> | <p>Vivado<br>2020.2</p>     | 30  | <p>4224<br>3136</p> | <p>30<br>4K<br>Color</p>      |
|  2 | OV4689  | 🟢 DONE    | MIPI | [OV4689](https://github.com/briansune/kintex-7-OV4689-Verilog)           | <p>Xilinx<br>7 Series Above</p> | <p>Vivado<br>2020.2</p>     | 90  | <p>2688<br>1520</p> | <p>30<br>2688<br>Color</p>    |
|  3 | IMX291  | 🟢 DONE    | MIPI | [IMX291](https://github.com/briansune/Kintex-7-IMX291-Verilog)           | <p>Xilinx<br>7 Series Above</p> | <p>Vivado<br>2020.2</p>     | 120 | <p>1920<br>1080</p> | <p>60<br>1080P<br>Color</p>   |
|  4 | OV5640  | 🟢 DONE    | DVP  | [OV5640](https://github.com/briansune/Artix-7-Parallel-OV5640)           | <p>Xilinx<br>7 Series Above</p> | <p>Vivado<br>2020.2</p>     | 30  | <p>1920<br>1080</p> | <p>30<br>XGA<br>Color</p>     |
|  5 | OV5640  | 🟢 DONE    | DVP  | [OV5640](https://github.com/briansune/Artix-7-Parallel-OV5640)           | <p>Xilinx<br>7 Series Above</p> | <p>Vivado<br>2020.2</p>     | 30  | <p>1920<br>1080</p> | <p>30<br>WQVGA<br>Color</p>   |
|  6 | OV5640  | 🟢 DONE    | DVP  | [OV5640](https://github.com/briansune/Artix-7-Parallel-OV5640)           | <p>Xilinx<br>7 Series Above</p> | <p>Vivado<br>2020.2</p>     | 30  | <p>1920<br>1080</p> | <p>60<br>720p<br>Color</p>    |
|  7 | OV5640  | 🟢 DONE    | DVP  | [OV5640](https://github.com/briansune/Artix-7-Parallel-OV5640)           | <p>Xilinx<br>7 Series Above</p> | <p>Vivado<br>2020.2</p>     | 30  | <p>1920<br>1080</p> | <p>30<br>QuadVGA<br>Color</p> |
|  8 | OV5640  | 🟢 Done    | DVP  | [OV5640](https://github.com/briansune/Artix-7-Parallel-OV5640)           | <p>Xilinx<br>7 Series Above</p> | <p>Vivado<br>2020.2</p>     | 30  | <p>1920<br>1080</p> | <p>30<br>1080p<br>Gray</p>    |
|  9 | OV5640  | 🟢 Done    | DVP  | [OV5640](https://github.com/briansune/Artix-7-Parallel-OV5640)           | <p>Xilinx<br>7 Series Above</p> | <p>Vivado<br>2020.2</p>     | 30  | <p>1920<br>1080</p> | <p>30<br>1080p<br>DeBayer</p> |
| 10 | OV2640  | 🟢 DONE    | DVP  | [OV2640](https://github.com/briansune/Artix-7-Parallel-OV2640)           | <p>Xilinx<br>7 Series Above</p> | <p>Vivado<br>2020.2</p>     | 30  | <p>800<br>600</p>   | <p>30<br>SVGA<br>Color</p>    |
| 11 | OV7670  | 🟢 DONE    | DVP  | [OV7670](https://github.com/briansune/Artix-7-Parallel-OV7670)           | <p>Xilinx<br>7 Series Above</p> | <p>Vivado<br>2020.2</p>     | 30  | <p>640<br>480</p>   | <p>30<br>VGA<br>Color</p>     |
| 12 | OV9655  | 🟢 DONE    | DVP  | [OV9655](https://github.com/briansune/Artix-7-Parallel-OV9655)           | <p>Xilinx<br>7 Series Above</p> | <p>Vivado<br>2020.2</p>     | 30  | <p>640<br>480</p>   | <p>30<br>VGA<br>Color</p>     |
| 13 | OV7740  | 🟢 DONE    | DVP  | [OV7740](https://github.com/briansune/Artix-7-Parallel-OV7740)           | <p>Xilinx<br>7 Series Above</p> | <p>Vivado<br>2020.2</p>     | 60  | <p>640<br>480</p>   | <p>60<br>VGA<br>DeBayer</p>   |
