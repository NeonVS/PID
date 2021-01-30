# Digital PID
The entire project is implemented in gate level verilog description. Signed 16 bit number format is used. PID parameters K1,K2 and K3 can be changed from pid.v file.

## Different components-
-  Positive edge triggered D flip flops
-  4 4-bit carry look ahead adders 
-  2's complementor
-  a multiplier(output is limited to 16-bits)
-  PIPO registers
-  multiplexers performing the reset function
