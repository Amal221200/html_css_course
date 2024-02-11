# Colors

Colors are displayed combining RED, GREEN, and BLUE light.

## CSS Color Values

With CSS, colors can be specified in different ways:

- By color names
- As RGB values
- As hexadecimal values
- As HSL values (CSS3)
- As HWB values (CSS4)
- With the currentcolor keyword

## RGB Colors

**An RGB color value is specified with: rgb( RED , GREEN , BLUE ).**

Each parameter defines the intensity of the color as an integer between 0 and 255.

For example, rgb(0,0,255) is rendered as blue, because the blue parameter is set to its highest value (255) and the others are set to 0.

```
    color: rgb(12 21 21);
    background-color: rgb(12 21 21);
```

## Hexadecimal Colors

RGB color values are supported in all browsers.

**A hexadecimal color is specified with: #RRGGBB**

RR (red), GG (green) and BB (blue) are hexadecimal integers between 00 and FF specifying the intensity of the color.

For example, #0000FF is displayed as blue, because the blue component is set to its highest value (FF) and the others are set to 00.

```
    color: #0000FF;
    background-color: #0000FF;
```

## HSL Colors

**An HSL color value is specified with: hsl( HUE , SATURATION , LIGHT ).**

```
    color: rgb(12 21 21);
    background-color: rgb(12 21 21);
```

The **`<hue>`** CSS data type represents the hue angle of a color.

<div align="center">

### Color Wheel

![](./color_wheel.svg)

</div>

**`<saturation>`** is a percentage or the keyword none, which represents saturation. Here 100% is completely saturated, while 0% is completely unsaturated (gray).

**`<light>`** percentage or the keyword none, which represents lightness. Here 100% is white, 0% is black, and 50% is "normal"

