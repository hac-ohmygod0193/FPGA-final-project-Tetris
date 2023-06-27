# FPGA-final-project-Tetris

This report presents the final project on Tetris game development by using Verilog and
implementing it on an FPGA(Nexys DDR 4). Our project focuses on implementing a Tetris game
with a unique feature called "rocker," which allows players to control the game using the FPGA
board's tilting motion.
Traditional Tetris is controlled by buttons. What we have done is that we can control
Tetris by not only the physical buttons on the board but also by tilting the FPGA board. By
realizing this function, players now no longer need to keep their hands on the board forever;
instead, players only need to control the button that rotates the Tetris, and other manipulation can
be done by tilting the board.
In this project, we integrate the built-in IMU and the built-in VGA output port to realize
the Tetris game. The IMU will detect the acceleration of the three axes and pass the input to the
main Tetris module. After the calculation, the main module will pass the data to the module
responsible for VGA display and ultimately display on the LCD monitor.
