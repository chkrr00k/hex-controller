# hex-controller
Simple seven segment display controller for the 4 seven segment displays for the terasic de1 altera FPGA board

## USE

```
CLOCK 		: in std_logic; -- clock in
RESET_N		: in std_logic; -- reset async
		
I_VALUE 		: in integer range 0 to 9999; -- value to print
		
HEX0 : out std_logic_vector(6 downto 0); -- exit of the de1
HEX1 : out std_logic_vector(6 downto 0);
HEX2 : out std_logic_vector(6 downto 0);
HEX3 : out std_logic_vector(6 downto 0)
```
