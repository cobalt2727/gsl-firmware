mobiledemand/xtabletflex10a
------------------------------------------------------------------------------------------------

| Item                      | Description                                                      |
|---------------------------|------------------------------------------------------------------|
| Manufacturer              | MobileDemand                                                     |
| Device                    | xTablet Flex 10A                                                 |
| Website                   | https://www.ruggedtabletpc.com/xtablet-flex-10a-with-android     |
| Vendor driver (Windows)   | SileadTouch.sys                                                  |
| Extracted firmware        | firmware.fw                                                      |
| Firmware for gslx680-acpi | silead_ts.fw                                                     |
| Display resolution        | 800x1280                                                         |
| Touch panel resolution    | 1270x1900 (estimated, no official documentation found)           |
| Touch controller          | GSL1680                                                          |
| Multitouch support        | Yes (10)                                                         |
| Finger tracking           | unsure (enabled in driver, no idea if it's actually supported    |
| Mirrored horizontally     | Yes                                                              |
| Mirrored vertically       | No                                                               |
| Axes swapped              | Yes                                                              |
| Comments | ./fwtool -c firmware.fw -m 1680 -w 1140 -h 1720 -t 10 -f xflip,swap,track silead_ts.fw  |
