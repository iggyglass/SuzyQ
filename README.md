# Suzy Q
A simple implementation of a Chromebook self case closed debugger, allowing the Chromebook USB-CDC debug console to be accessed from the Chromebook itself. Note that this only works on Chromebooks and not Android devices, as Android devices in debug mode can act as USB devices and not hosts (which is how ADB works).

## Manufacturing Notes
Due to the edge-mount USB-C plug used, make sure to have the PCBs fabricated with a $0.8\textrm{ }\mathrm{mm}$ thickness.

## BOM
| Item                                     | Qty |
|------------------------------------------|-----|
| Molex 105444                             | 1   |
| $5.1\textrm{ }\mathrm{k\Omega}$ Resistor | 2   |
