# ECE6130_SRAM_Design_Project

## Adding Library to Cadence

```
1. Go to ~/ECE6130_Updated/ECE6130_Lab/Cadence
2. Add 
   "DEFINE SRAM /nethome/$(username)/$(path to repository)/SRAM" to cds.lib
   "DEFINE RegisterFF /nethome/$(username)/$(path to repository)/RegisterFF"
   "DEFINE Decoders /nethome/$(username)/$(path to repository)/Decoders"
   
   Example for One: I have the directory in my home directory so I put this in cds.lib
   "DEFINE ECE6130_SRAM_Design_Project /nethome/gbotkin3/ECE6130_SRAM_Design_Project"
```
## Libraries
- SRAM
- Register FF
- Decoders
