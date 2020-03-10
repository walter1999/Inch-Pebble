## Inch Pebble Goals 
	- summary of what sytemC is about 
	- create two systemC modules 
		- MAC ( multiply and accumulate)
		- Decriptor Based DMA MM2S 

## SytemC Summary 
	- The most basic way of decribing SytemC is by comparing it to verilog. SystemC is verilog but in C++
	  syntax. The whole idea behind it is to take advantage of C++ OOP features to mimic verilog's modules. 
	  Like verilog, SystemC has ports that allow for the transfer of information between modules. SytemC also 
	  offers timing primitives that are helpful for testing. 



## Two modules
	- As mentioned above, I'll be creating two SystemC components: a MAC and a Descriptor Based DMA. The purpose 
	 of these two modules is to give me an understanding of how SystemC syntax and communication work. Along with 
	 the two modules, I'll be creating two test benches to validate that the modules are  behaving correctly. 
