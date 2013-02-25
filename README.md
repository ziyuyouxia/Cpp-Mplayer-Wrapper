C++ MPlayer Wrapper
==========
Wrapper to control mplayer with c++
####Compile it!
Just download mplayer_interface.cpp modifiy it or include it or compile it with
```bash
g++ mplayer_interface.cpp -I. -lboost_system -lboost_iostreams -g -o mplayer_wrapper
```
###Use TESTAREA
```bash
./mplayer_wrapper
```
Following commands are available
*play <file>
*pause
*bit - get audio bitrate
*pos - get percent position of playing audio file

C++ MPlayer Wrapper is under heavy development. It may not function as you expect.