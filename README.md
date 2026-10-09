![Version](https://img.shields.io/badge/version-1.0-blue.svg)
![PWA](https://img.shields.io/badge/PWA-installable-5A0FC8.svg)
![License](https://img.shields.io/badge/license-AGPL--3.0-green.svg)
![Platform](https://img.shields.io/badge/platform-web-lightgrey.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-vanilla-F7DF1E.svg?logo=javascript&logoColor=black)

# Tap Tempo Pro

**Tap Tempo Pro** is a lightweight web application that measures musical tempo by tapping a beat. It provides an immediate BPM (*beats per minute*) reading, making it useful for musicians, performers, composers, arrangers and anyone who needs to identify the tempo of a piece of music.

The application is available as an installable Progressive Web App (PWA).

**Use it online:** [https://tagtthespellcaster.github.io/TapTempoPro/](https://tagtthespellcaster.github.io/TapTempoPro/)

## Features

- **Tap tempo:** tap the central area of the interface in time with the music to measure its tempo.
- **Keyboard input:** use the spacebar to register beats, making it convenient to measure tempo while working at a computer.
- **Real-time BPM calculation:** the tempo is calculated from the average interval between consecutive taps and displayed in beats per minute.
- **Tempo marking:** the application displays the corresponding traditional musical tempo indication, from *Grave* to *Prestissimo*.
- **Average interval display:** the average time between beats is shown in milliseconds.
- **Adjustable measurement window:** choose between 4, 8 or 16 intervals for the tempo calculation.
- **Visual feedback:** a dynamic display shows the measured BPM and a progress indicator reflects the collection of tap intervals.
- **Automatic measurement reset:** after three seconds without a new tap, the current measurement is reset, allowing a new tempo to be measured.
- **Responsive interface:** the display adapts to different screen sizes and pixel densities.

## How to Use

1. Open [Tap Tempo Pro](https://tagtthespellcaster.github.io/TapTempoPro/).
2. Select the desired number of intervals: 4, 8 or 16.
3. Tap the central area of the interface in time with the music, or press the spacebar at each beat.
4. Read the calculated BPM, the corresponding tempo marking and the average interval in milliseconds.
5. Continue tapping to update the measurement.

For a more stable reading, tap consistently in time with the music and allow the selected measurement window to fill.

## Install as a PWA

Tap Tempo Pro can be installed as a Progressive Web App on supported browsers and devices.

1. Open the application in your browser.
2. Use the browser’s **Install** option, or **Add to Home Screen** on supported mobile devices.
3. Launch Tap Tempo Pro from its installed app icon.

Installation provides convenient access to the application from the device’s home screen or application launcher.

## Tempo Measurement

Tap Tempo Pro calculates the average duration between consecutive taps and converts it into BPM:

\[
\mathrm{BPM} = \frac{60\,000}{\text{average interval in milliseconds}}
\]

The selected interval count determines how many consecutive beat intervals contribute to the calculation. A measurement using more intervals can provide a steadier estimate when tapping consistently.

## Project Information

- **Version:** 1.0
- **Application type:** Progressive Web App (PWA)
- **License:** GNU Affero General Public License v3.0 (AGPL-3.0)
- **Web application:** [tagtthespellcaster.github.io/TapTempoPro](https://tagtthespellcaster.github.io/TapTempoPro/)

## License

Tap Tempo Pro is distributed under the terms of the **GNU Affero General Public License v3.0**.

See the [`LICENSE`](LICENSE) file for the full license text, or visit the [GNU AGPL v3.0 page](https://www.gnu.org/licenses/agpl-3.0.html).
