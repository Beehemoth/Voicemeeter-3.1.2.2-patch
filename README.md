# Voicemeeter8x64.exe v. 3.1.2.2 patch

RVA: 116b1d

original instruction: 41 81 FD 00 20 00 00 | cmp r13d,2000 <br>
new instruction:      41 81 FD FF FF 00 00 | cmp r13d,FFFF <br>


=> skip no license popup (not actually registered)

patch memory at runtime not in file

# Info

I will not provide a ready to use binary file. Use a wrapper script or similar to patch memory at startup. <br>
[DLL Proxy Example](https://github.com/Beehemoth/Voicemeeter-3.1.1.9-crack/blob/master/VoicemeeterCrack/dllmain.cpp)
