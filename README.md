# grbl-MITM-pendant
A basic arduino sketch that allows you to use a rotary encoder and other Arduino inputs, along with a separate Arduino, as jog controls for grbl CNC while maintaining a serial connection to a PC

<i> Bear in mind that this is a work in progress. Key features missing are use of the proper jog commands for grbl controllers - currently uses rapid movements; also missing is a reset of the Arduino running grbl once the pendant Arduino has established a serial connection with the PC gcode sender application. Some, i.e. Universal Gcode Sender, listen for the grbl initialisation message before allowing commands to be send.
  
  DO NOT USE WHEN PC IS SENDING GCODE FILES AND COMMANDS TO THE GRBL ARDUINO.</i>
