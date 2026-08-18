# Text-Editor
Simple Text Editor using FLTK
had quite some fun making this
fully made with C++ referring the official FLTK tutorial

Requirements
- C++ Compiler with C++ support(specifically MinGW/G++)
- FLTK 1.4.5
- Windows

Build
Compile with:
g++ main.cpp -I"<path-to-fltk>" -L"<path-to-fltk>/lib" -lfltk -lgdi32 -luser32 -lcomdlg32 -lole32 -luuid -lws2_32 -lgdiplus -lwinspool -o main.exe
