# Lab 2: Michael Dolezel 230241

### 2-bit comparator

1. Karnaugh maps for other two functions:

   Greater than:
   
   <img src="https://github.com/MichaelDolezel/digital-electronic-1/blob/d3aefe12061293ee34bf47f212ee85cf962a730b/labs/02-logic/Images/Greater.png" width=30% height=30%>


   Less than:
   
   <img src="https://github.com/MichaelDolezel/digital-electronic-1/blob/c037a44ecb923b85a68d7d72d007216c2d3600bc/labs/02-logic/Images/Less.png" width=30% height=30%>


2. Equations of simplified SoP (Sum of the Products) form of the "greater than" function and simplified PoS (Product of the Sums) form of the "less than" function.

   <img src="https://github.com/MichaelDolezel/digital-electronic-1/blob/c037a44ecb923b85a68d7d72d007216c2d3600bc/labs/02-logic/Images/Sop.png" width=30% height=30%>
   <img src="https://github.com/MichaelDolezel/digital-electronic-1/blob/c037a44ecb923b85a68d7d72d007216c2d3600bc/labs/02-logic/Images/pos.png" width=30% height=30%>
   

### 4-bit comparator

1. Listing of VHDL stimulus process from testbench file (`testbench.vhd`) with at least one assert (use BCD codes of your student ID digits as input combinations). Always use syntax highlighting, meaningful comments, and follow VHDL guidelines:

   Last two digits of my student ID: **xxxx41**

```vhdl
    p_stimulus : process
    begin
        -- Report a note at the beginning of stimulus process
        report "Stimulus process started" severity note;

        -- First test case ...
       			s_b <= "0100"; -- 230241(4)
        		s_a <= "0001";  -- 230241(1)
        		wait for 100 ns;
        -- ... and its expected outputs
        assert ((s_B_greater_A = '1') and
                (s_B_equals_A  = '0') and
                (s_B_less_A    = '0'))
        -- If false, then report an error
        report "Input combination 0100, 0001 FAILED" severity error

        -- Report a note at the end of stimulus process
        report "Stimulus process finished" severity note;
        wait; -- Data generation process is suspended forever
    end process p_stimulus;
    
    
```

2. Text console screenshot during your simulation, including reports.

    <img src="https://github.com/MichaelDolezel/digital-electronic-1/blob/fa60068d039650a82b01cd0df4e79eead37479f9/labs/02-logic/Images/123.png" width=50% height=50%>

3. Link to your public EDA Playground example:

   [https://www.edaplayground.com/x/D8fG](https://www.edaplayground.com/x/D8fG)
