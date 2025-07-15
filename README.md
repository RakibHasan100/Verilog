Complie it:
iverilog -o objectfilename testbenchfilename(.v.txt) designfilename(.v.txt)
Run it:
vvp object_file_name
Look at the dumpfile.vcd waveform:
gtkwave dumpfilename.vcd
