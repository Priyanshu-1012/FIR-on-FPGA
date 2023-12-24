# FIR-on-FPGA

> ### Tools Used
> - Octave 8.3.0
> - Vivado 2019,1

### Flow
- generate initial coeff values for n-tap LPF FIR using Octave
- convert the values for use in verilog module for FIR
  
## FIR Filter 
<img width="419" alt="image" src="https://github.com/Priyanshu-1012/FIR-on-FPGA/assets/39450902/77c25208-522a-485e-8314-c862ebf9adeb">

<img width="419" alt="image" src="https://github.com/Priyanshu-1012/FIR-on-FPGA/assets/39450902/40a1e28b-b861-45d6-b0d8-91525176aa83">

$g_k   : real filter impulse response    $  
$h_k   : shifted ideal filter response    $  
$w_k   : window function  $

$$
g_k = h_k \cdot w_k
$$


