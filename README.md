# A 16 bit Brent–Kung Parallel Prefix adder/subtractor model in Verilog HDL
## by @raunaks42, @sarthak7gupta, @rubenjohn1999 and @AprameyaKulkarni

### To run,

_Prerequisites_

Install Iverilog and GTKWave from http://iverilog.icarus.com/, http://gtkwave.sourceforge.net/ 
- or `apt install iverilog gtkwave`

___Commands___
```
$ git clone https://github.com/sarthak7gupta/VerilogAdderSubtractor16bit.git
$ cd VerilogAdderSubtractor16bit
$ iverilog -o vas PrefixAddSub16.v PrefixAddSub16_tb.v
$ vvp vas
$ gtkwave testbench.vcd &
```
