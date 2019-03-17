# MP2300-Tools

This repo contains Tools and informations on how to control Graphtec MP2300 plotters (and possibly other).

[![example](https://pbs.twimg.com/media/D10XChTWkAEfoFP.jpg:large)](https://twitter.com/JanHenrikH/status/1107066424982417409)

## Software

Convert hpgl to gpgl with `hpgl2gpgl.py`.

  ```bash
  ./hpgl2serial.py <input-file> <output-file> <speed>
  ./hpgl2serial.py test.hpgl test.gpgl 99
  ```

Convert and send hpgl to your gpgl plotter with `hpgl2serial.py`.

  ```bash
  ./hpgl2serial.py <input-file> <output> <speed>
  ./hpgl2serial.py test.hpgl /dev/ttyUSB0 99
  ```


## Hardware

3D printable pen holder files in `CAD/`.
