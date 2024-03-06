# RISC-V
RISC-V

In this project I tried to replicate RISC-V architecture. It works with 5 different cycles namely :
1 - Fetch Cycle
2 - Decode Cycle
3 - Execute Cycle
4 - Memory Cycle
5 - Writeback Cycle

Fetch Cycle used to fetch the data and give it to Decode Cycle.
Decode Cycle will take out all the necessary data from input, also generate certain signals to help Execution Cycle work properly.
Execution Cycle will do necessary calculate the obtain result.
Memory Cycle is used to store data in Main Memory. 
Writeback Cycle is used to again give data to Decode and Execution Cycle for further operations.

Now, to remove unwanted delay-errors(Essential Hazards) we created a Hazard Unit.

In this project we will take data from mem.hex file and see result from waveform created at the output.

Hope, this project will find you usefull. 

Thanks !!!
