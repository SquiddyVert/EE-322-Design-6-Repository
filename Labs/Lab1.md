# Lab 1 - GHDL and GTKWave

## Half Adder Example
```console
PS C:\users\samue\vhdl> ghdl -a ha_tb.vhdl
PS C:\users\samue\vhdl> ghdl -e ha_tb
PS C:\users\samue\vhdl> ghdl -r ha_tb
ha_tb.vhdl:47:5:@5ns:(assertion error): Reached end of test
PS C:\users\samue\vhdl> ghdl -r ha_tb --vcd=ha.vcd
ha_tb.vhdl:47:5:@5ns:(assertion error): Reached end of test
PS C:\users\samue\vhdl> gtkwave ha.vcd

GTKWave Analyzer v3.3.100 (w)1999-2019 BSI

[0] start time.
[5000000] end time
```
<img width="255" alt="halfadder code" src="https://github.com/user-attachments/assets/1773b4e8-34eb-4dd8-92fa-c00f48db83c5" />
<img width="748" alt="halfadder gtkwave" src="https://github.com/user-attachments/assets/2c45efe1-3075-42a5-bff0-9f17b72f31ad" />

## D Flip Flop Example
```console
PS C:\users\samue\vhdl> ghdl -a dff.vhdl
PS C:\users\samue\vhdl> ghdl -a dff_tb.vhdl
PS C:\users\samue\vhdl> ghdl -e dff_tb
PS C:\users\samue\vhdl> ghdl -r dff_tb --vcd=dff.vcd
PS C:\users\samue\vhdl> gtkwave dff.vcd

GTKWave Analyzer v3.3.100 (w)1999-2019 BSI

[0] start time.
[210000000] end time.
```
<img width="203" alt="dflipflop code" src="https://github.com/user-attachments/assets/b33c4d9c-cc2d-48d0-af6b-b9faf8f9d530" />

<img width="746" alt="dflipflop gtkwave" src="https://github.com/user-attachments/assets/6377c6c3-78ee-4dda-8b22-d7b7b302ed2b" />
