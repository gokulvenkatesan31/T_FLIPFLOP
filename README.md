# T_FLIPFLOP
![image](https://github.com/RESMIRNAIR/T_FLIPFLOP/assets/154305926/74140ea2-0b93-4ffc-b38b-527fb2ece133)
# Truth Table
![image](https://github.com/RESMIRNAIR/T_FLIPFLOP/assets/154305926/1d4afa40-166a-4690-ab1a-179948b9b550)
# Program
```
module tff(clk,reset,t,q);
input clk,reset,t;
output reg q;
always @(posedge clk
begin
if(reset==1)
q=0;
else
begin
if(t==0)
q=q;
else
q=~q;
end
end
endmodule
```
# Output
![WhatsApp Image 2024-04-08 at 13 52 55_aec5a90b](https://github.com/gokulvenkatesan31/T_FLIPFLOP/assets/123715763/55c4c06f-9f26-450d-b1c4-837223d27077)
