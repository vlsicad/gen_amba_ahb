
[Preparing gen_amba_ahb]

1. Clean directory
   $ make cleanupall

2. Compile
   $ make

3. Testing
   $ ./gen_amba_ahb -h
   $ ./gen_amba_ahb --mst=3 --slv=4 --out=amba_ahb_m3s4.v

[Verification]

1. Go to "verification/sim/xsim" or 'verification/sim/iverilog' directory

2. Clean directory
   $ make cleanupall

3. Run simulation
   $ make
   or
   $ make MST=3 SLV=4

4. Check wave.vcd
----------------------------------------------------------
