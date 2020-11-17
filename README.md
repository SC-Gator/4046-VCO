# 4046-VCO
A v/oct VCO based on the CD4046 ic

## Description
This is the first prototype of a v/oct VCO I designed. It has a sawtooth output and a squarewave output that is one octave lower and can be used as sub oscillator. The main functions are working well. However there are some issues with the fm input, also the sync input doesn't work as expected. The ring modulation just effects the squarewave output and works well.

New version without linear fm (and maybe without sync) but with a voltage controlled pwm option is coming spring 2021 or so...

Pitch tracking is not super precise but works fine over a few octaves with some cents of tuning error (Please see this thread for more information. After a more proper calibration I get a bit better results than the ones showed here: https://electro-music.com/forum/viewtopic.php?p=446122#446122)

In order to get okay tracking it is crucial to use Philips or NXP branded 4046 ics. TI and other brands will not work well.

*Licenced under CC BY-SA 3.0*

## Images

![BOARD](https://raw.githubusercontent.com/diysynth/4046-VCO/main/4046vco.jpg)

## Schematics

![BOARD](https://raw.githubusercontent.com/diysynth/4046-VCO/main/vco4046schematic_406.png)

*Sebastian Jazura, 2020, CC BY-SA 3.0*

*Build at your own risk, I give no warranties...*
