# dashcam-gpx
Dashcam GPS Video to GPX Extractor. Creates GPX files from Novatek (VIOFO) Dashcamera

# Usage

```
usage: nvtk_mp42gpx.py [-h] [-i input [input ...]] [-o output] [-f] [-d] [-e] [-m] [-s [sorting]]

This script will attempt to extract GPS datafrom a Novatek MP4/MOV/TS file and output it in a GPX format.

options:
  -h, --help            show this help message and exit
  -i input [input ...]  input file(s), globs (eg: *) or directory(ies).
  -o output             output file (single).
  -f                    overwrite output file if exists.
  -d                    deobfuscates coordinates, if the file only works with JMSPlayer use this flag.
  -e                    exclude outliers. Removes impossible coordinates due to errors in the GPS data.
  -m                    multiple output files (default creates a single output file). Note: files will be named after originals.
  -s [sorting]          Specify on what to sort by. The '-s f' will sort the output by the file name. The '-s d' will sort the output by the GPS date (default). The '-s n' will not sort the
                        output.
```



# Credits
Sergei Franco ( https://sergei.nz/?s=nvtk_mp42gpx.py )