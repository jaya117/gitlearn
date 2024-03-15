## RISCV-HDP Training week2 
#### This week's training has two sessions , in the following sections I describe my learnings during these sessions and paths to the related assignments.

### What did I learn in Week2_Session1

#### Topics 
<img width="617" alt="topics" src="https://github.com/jaya117/gitlearn_new/assets/139655462/7b67e0a0-a2fa-4005-a9f4-92d0c7833ae8">

#### How fast is your processor? How is CPU performance measured?

##### CPU exexcution time  Vs CPU  response time 
<img width="607" alt="faster_computer" src="https://github.com/jaya117/gitlearn_new/assets/139655462/d5c298fa-8132-484b-9caa-7baec4ebd916">

###### OS is manager of the computer's resources, so it adds overhead to the actual user code 
###### effective length of the code = raw user code + overhead added by OS
###### CPU performance is measure by benchmarks by measuring the the time teaken by the CPU to execute the raw user code. This time is called the execution time of the CPU.

<img width="614" alt="raw_program_performance" src="https://github.com/jaya117/gitlearn_new/assets/139655462/df722cb9-139d-45bc-a2aa-4c4e58c1d2cc">

#### In real world to measure speed of anything a clock is used , Computers are no exception .
##### Clock is given to the computer , which feed the sequential logic of the cpu. Ultimate aim of the CPU designers is to increase the clock speed , that is to reduce clock period by scaling transistors , improving the microarchitecture etc.
<img width="616" alt="clock_speed" src="https://github.com/jaya117/gitlearn_new/assets/139655462/caa10508-72a4-465b-8fd6-dfebef6dce4b">

#### So how do we really measure the CPU performance. Formulas to measure CPU performance 
<img width="620" alt="clock_speed1" src="https://github.com/jaya117/gitlearn_new/assets/139655462/82e553a0-2ef0-4c6d-8ad2-f6e1632111ea">

#### Example of CPU time calculation
<img width="636" alt="cpu_time_calculation" src="https://github.com/jaya117/gitlearn_new/assets/139655462/b9a4b287-4c42-459f-a98b-f368fce3fba6">

#### If in above example each instruction on an average takes 5 cycles to exceute then this system is exceuting 4 billion instructions in 20 second which is a HUGE number










