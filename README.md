# Digital-electronics-1

## Podnadpis
### Podpodnadpis

https://www.vutbr.cz/

_Link na stránku **školy**_
~~Nejaký prečiarknutý odkaz~~

* Predmet 1
* Predmet 2
  * Predmet 2a
  * Predmet 2b
  
1. Predmet 1
1. Predmet 2
   1. Predmet 2a
   1. Predmet 2b
   
First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column
  
```vhdl
library IEEE;
use IEEE.std_logic_1164.all;

entity ANDGATE is
  port ( 
    I1 : in std_logic;
    I2 : in std_logic;
    O  : out std_logic);
end entity ANDGATE;

architecture RTL of ANDGATE is
begin
  O <= I1 and I2;
end architecture RTL;
```
