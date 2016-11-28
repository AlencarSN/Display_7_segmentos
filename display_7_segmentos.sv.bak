module display_7_segmentos(input logic [3:0] bin,
                           output logic [0:6] decimal);

	always_comb
		begin
			case(bin)
				4'd0: decimal = 7'b1111110;
				4'd1: decimal = 7'b0110000;
				4'd2: decimal = 7'b1101101;
				4'd3: decimal = 7'b1111001;
				4'd4: decimal = 7'b0110011;
				4'd5: decimal = 7'b1011011;
				4'd6: decimal = 7'b1011111;
				4'd7: decimal = 7'b1110000;
				4'd8: decimal = 7'b1111111;
				4'd9: decimal = 7'b1111011;
				default: decimal = 7'b0000001;
			endcase
		end
endmodule


				
