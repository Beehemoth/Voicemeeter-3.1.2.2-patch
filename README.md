# Voicemeeter8x64.exe v. 3.1.2.2 patch

### skip no license popup (not actually registered)
<pre>
RVA: 116b1d

original instruction: 41 81 FD 00 20 00 00 | cmp r13d,2000
new instruction:      41 81 FD FF FF 00 00 | cmp r13d,FFFF
</pre>

### Hide "Unregisted License" label
<pre>
RVA: 12065f

original instruction: 83 BD 5C 9A 06 00 00 | cmp dword ptr ss:[rbp+69A5C],0
new instruction:      83 BD 5C 9A 06 00 01 | cmp dword ptr ss:[rbp+69A5C],1
</pre>
<br>
patch memory at runtime not in file

# Info

I will not provide a ready to use binary file. Use a wrapper script or similar to patch memory at startup. <br>
[DLL Proxy Example](https://github.com/Beehemoth/Voicemeeter-3.1.1.9-crack/blob/master/VoicemeeterCrack/dllmain.cpp)
