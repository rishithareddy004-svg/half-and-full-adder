# half-and-full-adder
A dataflow verilog description for a half adder and a full adder using continuous assignment (assign)
module half_adder (input A,B output SUM,CARRY);
assign SUM = A or b;
assign CARRY = A and B;
endmodule
