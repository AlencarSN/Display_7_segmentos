module tb_display_7_segmentos;
  logic [3:0] enter_bin;
  logic [0:6] saida_decimal;
  
  initial
    begin
      enter_bin <= 0000;
      #20;
      repeat(9)
        begin
          enter_bin <= enter_bin + 4'd1;
          #20;
        end
    end
  diplay_7_segmentos tb_display_7_segmentos(.bin(enter_bin), .decimal(saida_decimal));
  
endmodule 