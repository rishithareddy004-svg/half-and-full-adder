module half_adder (
    input wire A,
    input wire B,
    output wire Sum_H,
    output wire Carry_H
);
    assign Sum_H   = A ^ B;
    assign Carry_H = A & B;
endmodule

module full_adder (
    input  wire C,
    input  wire D,
    input  wire Cin,
    output wire Sum_F,
    output wire Cout
);
    assign Sum_F  = C ^ D ^ Cin;
    assign Cout = (C & D) | (C & Cin) | (D & Cin);
endmodule
