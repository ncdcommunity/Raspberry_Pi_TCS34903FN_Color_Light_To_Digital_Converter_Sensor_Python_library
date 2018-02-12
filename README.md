[![ TCS34903FN](TCS34903FN_I2C.png)](https://store.ncd.io/product/tcs34903fn-color-light-to-digital-converter-i2c-mini-module/).

#  TCS34903FN

The TCS3490 provides color and IR (red, green, blue, clear and IR) light sensing using I2C communications. The color sensing provides for improved accuracy lux and color temperature measurements typically used to adjust the backlight intensity and correct the display color gamut. Additionally it can be used for light source type detection as it reports the IR content of the light.
This Device is available from www.ncd.io 

[SKU: TCS34903FN]

(https://store.ncd.io/product/tcs34903fn-color-light-to-digital-converter-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface TCS34903FN color light to digital converter sensor With Raspberry Pi :
1. <a href="https://store.ncd.io/product/tcs34903fn-color-light-to-digital-converter-i2c-mini-module/">TCS34903FN color light to digital converter sensor</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python TCS34903FN.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
