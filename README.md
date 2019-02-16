# Chiangmai TechFest Api 2019
---

## Main picture url

[Say hi to every one](http://178.128.223.52:3001)

[Look for some picture?](http://178.128.223.52:3001/picture)

## LED Strip

LED Strip Api go [here](https://github.com/cmmakerclub/led_mqtt)

Mqtt topic

* TECH\_FEST/LED_STRIP\_000
* TECH\_FEST/LED_STRIP\_001
* TECH\_FEST/LED_STRIP\_002
* TECH\_FEST/LED_STRIP\_003
* TECH\_FEST/LED_STRIP\_004
* TECH\_FEST/LED_STRIP\_005

Strip 000 have 600 led.
Strip 001 - 005 have 150 led.

## Cloud

Same as LED Strip but have led 16.

Mqtt topic

* TECH\_FEST/CLOUD\_001
* TECH\_FEST/CLOUD\_002
* TECH\_FEST/CLOUD\_003

## PLUG

Mqtt topic

* TECH\_FEST/PLUG_004
* TECH\_FEST/PLUG_005
* TECH\_FEST/PLUG_006

Payload

	ON
	OFF

## Thermocouple

Mqtt topic **Subscribe only**

* TECH\_FEST/TERMO_001
* TECH\_FEST/TERMO_002

## LCD

Add line cmmc_messageing

Send image. Done!

Or send data by make **hex String** with 2048 char to **$/command**

1 hex string mean 4 pixal.

Mqtt topic

* TECH\_FEST/LCD\_PICTURE\_001
* TECH\_FEST/LCD\_PICTURE\_002
* TECH\_FEST/LCD\_PICTURE\_003


Example

	TECH_FEST/LCD_PICTURE_001/$/command
	
	Send data
	
	BFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFBFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFBFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFBFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFBFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFBFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFBFFFFFFFFFFFFFFE3FFFFFFFFFFFFFFFBFFFFFFFFFFFFFFC1FFFFFFFFFFFFFFFBFFFFFFFFFFFFFFC1FFFFFFFFFFFFFFFBFFFFFFFFFFFFFFC1FFFFFFFFFFFFFFFBFFFFFFFFFFFFFFC1FFFFFFFFFFFFFFFBFFFFFFFFFFFFFE000FFFFFFFFFFFFFFBFFFFFFFFFFFF8000007FFFFFFFFFFFFBFFFFFFFFFFFC0000000FFFFFFFFFFFFBFFFFFFFFFFF001FFF001FFFFFFFFFFFBFFFFFFFFFFC03FFFFF00FFFFFFFFFFFBFFFFFFFFFF81FFFFFFE03FFFFFFFFFFBFFFFFFFFFF07FFFFFFF81FFFFFFFFFFBFFFFFFFFFC0FFFFFFFFC0FFFFFFFFFFBFFFFFFFFFC1FFFFFFFFE07FFFFFFFFFBFFFFFFFFF83FFFFFFFFF07FFFFFFFFFBFFFFFFFFF87FFFFFFFFF83FFFFFFFFFBFFFFFFFFF07FFFFFFFFF83FFFFFFFFFBFFFFFFFFF07FFFFFFFFF83FFFFFFFFFBFFFFFFFFF07FFFFFFFFFC3FFFFFFFFFBFFFFFFFFF0FFFFFFFFFFC1FFFFFFFFFBFFFFFFFFF0FFFFFFFFFFC1FFFFFFFFFBFFFFFFFFF08FFFFFFFFCC1FFFFFFFFFBFFFFFFFFF400FFFFFFC013FFFFFFFFFBFFFFFFFFF0003FFFFF0003FFFFFFFFFBFFFFFFFFC0300FFFFC0300FFFFFFFFFBFFFFFFFF00FC03FFF00FC03FFFFFFFFBFFFFFFFC047F00FFC03F900FFFFFFFFBFFFFFFE0183FC03F00FF8403FFFFFFFBFFFFFFC0783FF00C03FF0700FFFFFFFBFFFFFF81FC1FFC000FFF07C0FFFFFFFBFFFFFF87FC1FFF003FFE0FF0FFFFFFFBFFFFFF87FE0FFFC0FFFE1FF0FFFFFFFBFFFFFF87FE0FFFF3FFFC1FF0FFFFFFFBFFFFFF87FF07FFFFFFF83FF0FFFFFFFBFFFFFF87FF83FFFFFFF03FF0FFFFFFFBFFFFFF87FF81FFFFFFF07FF0FFFFFFFBFFFFFFFFFFC0FFFFFFE0FFFFFFFFFFFBFFFFFF81FFE07FFFFFC1FFE0FFFFFFFBFFFFFF8000003FFFFF800000FFFFFFFBFFFFFFE000001FFFFE000001FFFFFFFBFFFFFFFFFFFC07FFFC0FFFFFFFFFFFFBFFFFFFFFFFFF01FFF01FFFFFFFFFFFFBFFFFFFFFFFFF803F007FFFFFFFFFFFFBFFFFFFFFFFFFE00001FFFFFFFFFFFFFBFFFFFFFFFFFFF00003FFFFFFFFFFFFFBFFFFFFFFFFFFC00000FFFFFFFFFFFFFBFFFFFFFFFFFF80FFE07FFFFFFFFFFFFBFFFFFFFFFFFF03FFF83FFFFFFFFFFFFBFFFFFFFFFFFE0FFFFC1FFFFFFFFFFFFBFFFFFFFFFFFE0FFFFE1FFFFFFFFFFFFBFFFFFFFFFFFE0FFFFC0FFFFFFFFFFFFBFFFFFFFFFFFE0000000FFFFFFFFFFFFBFFFFFFFFFFFE0000001FFFFFFFFFFFFBFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFBFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFBFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFBFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFBFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF
	

Source code [is here](https://github.com/cmmakerclub/lcd_mqtt)

## Thermal printer

Add line cmmc_messageing

Send image. Done!

Or send form with file name **avatar** type image to 

[Look here](http://178.128.223.52:3001/upload_picture)

[See more here](https://github.com/cmmakerclub/Termal-printer-project)
