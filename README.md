lemonchat's client.html is using two webassembly files for audio functionality, this repository aims to provide simple way on how to build the decoder.wasm file, webassembly file that makes it possible to encode mp3 to pcm, so that user can select mp3 file from disk and play it in some channel of choice
<br>
<br>


Simplest way, like with libopusjs.wasm, is to download exported virtual machine file (.ova) and run build there. <br>
The virtual machine contains the all needed source code with dependencies, tools and enviroment variables already set. <br>
download here -> https://mega.nz/file/gz0CjRxA#sYKrSOyxdvbNPedsbIJbXy-pbHdpAfYJ9gqOJZmG-s4<br>



alternatively clone this repository https://github.com/bashi/minimp3-wasm ,setup build environment and build the webassembly file without VM. <br>
Unlike libopus.js, this project has less dependencies and is easier to build manually.
But still I provided virtual machine to build it in more convenient way.
