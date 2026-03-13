# Voicemeeter8x64.exe v. 3.1.2.2 patch

### pass license check
<pre>
RVA: 21BE8
File Offset: 20fe8
  
old instruction: 41 38
new instruction: EB 24
</pre>

### pass checksum verification (kind of)
<pre>
Uses original file in hash calculation
Rename the original Voicemeeter8x64.exe to bak

RVA: 120D8C
File Offset: 12018C

old instruction: C6 85 00 04 00 00 00 FF 15 6F 55 01 00
new instruction: 48 C7 85 00 04 00 00 62 61 6B 00 90 90
</pre>

# Info

I will not provide a ready to use binary file. Use a wrapper script or similar to patch memory at startup. Alternatively, use the checksum bypass to patch a copy<br>
[DLL Proxy Example](https://github.com/Beehemoth/Voicemeeter-3.1.1.9-crack/blob/master/VoicemeeterCrack/dllmain.cpp)
