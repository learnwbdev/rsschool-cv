# Alexandra Paramonova
### Frontend-developer

## Contacts
Yekaterinburg, Russia

* **Phone**: +7-912-605-3781
* **E-mail**: alpar.wb@gmail.com
* **Telegram**: @alexpar_wd

---

## About

## Skills

* Git
* HTML
* CSS
* Javascript

## Code Example
*Convert color in the LAB color space to its polar coordinaties, the LCH format.*
```javascript
export function convertLabToLch(colorLab) {
    // convert radians to degrees
    const toDegrees = radians => radians * (180/Math.PI);

    const [L, a, b] = colorLab; // perceived Lightness, a - how green/red the color is, b - how blue/yellow the color is

    // convert to Lch
    const C = Math.sqrt(a ** 2 + b ** 2) // Chroma
    let H = toDegrees(Math.atan2(b, a));
    H = H >= 0 ? H : H + 360; // Hue, in degrees [0 to 360)

    const colorLch = [L, C, H]; // perceived Lightness, Chroma, Hue

    return colorLch;
}
```

## Education

## English
**B2**
