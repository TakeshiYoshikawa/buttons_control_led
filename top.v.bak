module top(
	input clk,
	output [7:0]led,
	input [3:0]btn
);
	
	pro12_buttons_control_leds u0 (
		.clk_clk 								(clk),   //clk.clk
		.led_external_connection_export  (led),   //led_external_connection.export
		.btn_external_connection_export 	(btn)    //btn_external_connection.export
	);
	
endmodule