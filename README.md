# FIR-on-FPGA

> ### Tools Used
> - Octave 8.3.0
> - Vivado 2019,1

### Flow
- generate initial coeff values for n-tap LPF FIR using Octave
- convert the values for use in verilog module for FIR
  
## FIR Filter 
<img width="419" alt="image" src="https://github.com/Priyanshu-1012/FIR-on-FPGA/assets/39450902/77c25208-522a-485e-8314-c862ebf9adeb">

Its non causal...<br>
Now if we shift and truncate this impulse reponse...<br>
<img width="419" alt="image" src="https://github.com/Priyanshu-1012/FIR-on-FPGA/assets/39450902/7f5da366-ea97-4049-a19c-825bee76ceb7">


$g_k\   :\ real\ filter\ impulse\ response\    $  
$h_k\   : shifted\ ideal\ filter\ response\    $  
$w_k\   : window\ function\  $

$$
g_k\ =\ h_k \cdot w_k
$$


