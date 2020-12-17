# SUNBURST DGA decoder

## Compiling

Windows: CL.EXE flames\_pub.c (start a Visual Studio Command Propmt)

Linux/Unix: gcc -o flames\_pub flames\_pub.c

## Match the domain requests published by FireEye with target names

1. Compile the binary.

2. Download the datasets.

```
https://raw.githubusercontent.com/fireeye/sunburst_countermeasures/main/indicator_release/Indicator_Release_NBIs.csv
https://github.com/bambenek/research/blob/main/sunburst/uniq-hostnames.txt
```

3. Execute:

Windows: extract\_uids.bat

Linux/Unix: extract\_uids.sh

