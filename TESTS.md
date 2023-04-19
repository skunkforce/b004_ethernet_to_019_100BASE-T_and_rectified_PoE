# 100Mbit communication test
## setup
```mermaid
graph LR
    PC -- usb --> b051
    b051 --> b016
    b016 --> b004
    b004 -- ethernet --> internet
```
## results
The PC was able to communicate with the internet through the chain.
