<h1>IMSAIMULTI</h1>
<p>This project is for educational use, and performs multiple functions on the IMSAI 8080 LED Output port ($FF).  For testing, I'm running Z80 mode at 4MHz under CP/M 2.2.</p>
<p>I used Z80ASM to compile this by SLR systems.  Just rename the .asm file to a .z80 file to assemble.  Other compilers may require some minor coding changes, such as TASM.  TASM tends to use a "." before assembler directives such as .ORG, and .DB.</p>  
<ul>
  <li>Switch 0 -- Port Reflector -- Displays the values of switches on the LED's as long as switch 1 is high.</li>
  <li>Switch 1 -- Binary Counter -- Counts in Binary ~1 count per second.  Switch 6 pauses the counter, and switch 7 resets the counter.  You can finely tune this in your code for your own system if you wish.  The tuning labels are in the head of the code.</li>
  <li>Switch 2 -- Cylon Effect -- Lights will move back and forth.   You can set a separate delay for the cylon than what you use for the binary counter.</li>
  <li>Switch 3 -- Simple Counter -- The lights will count by 1 each time you turn on switch 7.</li>
  <li>Switch 4 -- Exit to CP/M.  This is will execute a JP to 00H</li>
</ul>
<p>IMSAIMUL.COM should run directly under CP/M.</p>
<p>--Ricky Bryce</p>
