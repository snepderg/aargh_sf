# aargh_sf
 An interpreter for the esoteric programming language Aargh! by Sascha Wilde, written in StarfallEX.

* Aargh!: https://esolangs.org/wiki/Argh
* Aargh! is a turing-complete version of Argh! which consists of a 2D grid, an instruction pointer, and a stack.
* Commands in Aargh! are provided by way of uppercase and lowercase letters, data can be read/written to/from above or below the instruction pointer.
* Aargh! also does not let users know what went wrong and will simply output "Aargh!"
* In my project, STDIN and STDOUT functionality was mimicked by using variables as input / output buffers, with output printing to the screen and sent to a Wiremod output.
* Wiremod: https://github.com/wiremod/wire
 
* StarfallEX: https://github.com/thegrb93/StarfallEx/
* StarfallEX is a sandboxed version of GLua giving users access to powerful functions within Garry's Mod.
  
* Note: StarfallEX uses TXT files since using Lua files would pose a security risk.
