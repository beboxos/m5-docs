# ATOM FLY Kit
<el-tag effect="plain">SKU:</el-tag>

<div class="product_pic"><img src="assets/img/product_pics/atom_base/atomhub_switch/atomswitch.webp"><img src="assets/img/product_pics/atom_base/atomhub_switch/atomswitch_02.webp"></div>

## Description

**ATOM FLY** is a programmable mini quadcopter that supports ATOM, suitable for flying in indoor. The rack adopts the integrated design of PCB, and directly fixes the motor on the PCB to minimize the take-off weight. The arm adopts X-shaped layout for more flexible control. The fuselage is equipped with a barometer, three-axis accelerometer and gyroscope (IMU)for height setting and attitude maintenance. At the same time, it is equipped with ToF for automatic landing and obstacle avoidance. There is an LED power indicator on the head, and the whole machine is powered by an external 200mAh lithium battery. (There is no firmware program at the factory, users need to write their own programs to control)

## Product Features

- Adapt to ATOM Matrix/ATOM Lite
- Support WiFi, Bluetooth remote control, programmable
- Built-in barometer, accelerometer, gyroscope, ToF
- Small and compact body

## Include

- 1x ATOM FLY frame
- 1x ATOM Lite
- 1x Battery charge
- 1x 200mAh battery
- 2x CW propeller
- 2x CCW propeller

## Applications

- Remote control drone

## Specification

<table class="table-1">
    <thead>
    <tr>
        <th>Specification</th>
        <th>Parameter</th>
    </tr>
    </thead>
    <tbody>
       <tr>
            <td>ToF</td>
            <td>VL53L0x</td>
       </tr>
       <tr>
            <td>IMU</td>
            <td>MPU6886</td>
       </tr>
       <tr>
            <td>Barometer</td>
            <td>BMP280</td>
       </tr>
       <tr>
            <td>Power Battery</td>
            <td>200mAh/1S/25C/JST </td>
        </tr>
        <tr>
            <td>Propeller Diameter</td>
            <td>2 inch</td>
        </tr>
        <tr>
            <td>DC Motor Load Speed</td>
            <td>31000±10%RPM</td>
        </tr>
        <tr>
            <td>DC Motor Stall Current</td>
            <td>4A Max.</td>
        </tr>
        <tr>
            <td>net weight</td>
            <td>g</td>
        </tr>
        <tr>
            <td>Gross weight</td>
            <td>g</td>
        </tr>
        <tr>
            <td>Product Size</td>
            <td>70*70*30mm</td>
        </tr>
        <tr>
            <td>Package Size</td>
            <td>mm</td>
        </tr>
        <tr>
            <td>Case material</td>
            <td>PCB</td>
        </tr>
     </tbody>
</table>

## USAGE

All hardware functions of the AtomFLY Kit are tested before leaving the factory. Atom Lite does not have any built-in firmware. The programs provided below only provide basic function tests. You need to program yourself to achieve the purpose of remote control flight. Please pay attention to safety during the test and keep your body away from the propeller to prevent accidents. Lithium battery is charged using the supplied charging cable, and the battery charging status is observed through the indicator lights. Red led means charging, and green led means charging is completed. Do not continue to charge for a long time after the battery is full to prevent the battery from heating and cause hidden dangers.


## EasyLoader

>EasyLoader is a concise and fast program writer, which has a built-in case program related to the product. It can be burned to the main control by simple steps to perform a series of function verification. Please install the corresponding driver according to the device type. M5Core host [Please click here to view the CP210X driver installation tutorial](en/arduino/arduino_development), M5StickC/V/T/ATOM series can be used without driver)

<div class="easyloader-box">
    <div style="background-color:white;">
        <div><img src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/image/easyloader_intro.webp"></div>
        <div class="easyloader-btn">
            <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/Windows/ATOM_BASE/EasyLoader_QRCODE_ATOM_BASE.exe">Windows</a>
            <a href="https://m5stack.oss-cn-shenzhen.aliyuncs.com/EasyLoader/MacOS/ATOM_BASE/EasyLoader_QRCODE_ATOM_BASE.dmg">MacOS</a>
            <!-- <a>Linux</a>
            <a>MacOS</a> -->
        </div>
    </div>
    <div>
        <video id="example_video" controls>
            <source src="https://m5stack.oss-cn-shenzhen.aliyuncs.com/video/Product_example_video/AtomBase/Atomic_QR.mp4" type="video/mp4">
        </video>
        <div class="easyloader-mask">
        <a>
            <svg id="play-btn" t="1583228776634" class="icon" viewBox="0 0 1024 1024" version="1.1" xmlns="http://www.w3.org/2000/svg" p-id="4152" width="75" height="75"><path d="M512 0C229.216 0 0 229.216 0 512s229.216 512 512 512 512-229.216 512-512S794.784 0 512 0z m0 928C282.24 928 96 741.76 96 512S282.24 96 512 96s416 186.24 416 416-186.24 416-416 416zM384 288l384 224-384 224z" p-id="4153" fill="#007aff"></path></svg></a>
            <p>Description:</p>
            <p>Press the Atom button, the propeller rotates in turn, and the serial monitor outputs the IMU status</p>
        </div>
    </div>
</div>

## Related Link

-  **Datasheet** 
    - [MPU6886](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/MPU-6886-000193%2Bv1.1_GHIC_en.pdf)
    - [BMP280](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/hat/BMP280-DS001-11_en.pdf)
    - [VL53L0X](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/hat/VL53L0X_en.pdf)
    - [DC Moter C.W](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/atombase/AtomFLY/Motor_716-37A-14.pdf)
    - [DC Moter CCW](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/atombase/AtomFLY/Motor_716-37B-14.pdf)

### Pin Map

<table>
 <tr><td>ATOM</td><td>G21</td><td>G25</td><td>G22</td><td>G19</td><td>G23</td><td>G33</td></tr>
 <tr><td>ATOM FLY</td><td>SCL</td><td>SDA</td><td>PWM1</td><td>PWM2</td><td>PWM3</td><td>PWM4</td></tr>
 <tr><td>MPU6886</td><td>SCL</td><td>SDA</td></tr>
 <tr><td>VL53L0X</td><td>SCL</td><td>SDA</td></tr>
 <tr><td>BMP280</td><td>SCL</td><td>SDA</td></tr>
</table>

## Schematic

<img src="assets/img/product_pics/atom_base/atomhub_switch/atomswitch_sch.webp">

## Example

- Arduino test code [Click here to download]()

<img src="assets/img/product_pics/atom_base/atomFly/atomFly_sch.webp>

<script>

   var purchase_link = '';

   anchor_search(purchase_link);
   scrollFunc();

</script>