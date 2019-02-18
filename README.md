# mal-analysis-tools

## Automated Sandbox evaluation:
VirusTotal - https://www.virustotal.com
Hybrid-Analysis - https://www.hybrid-analysis.com
VMRay - https://www.vmray.com
Sndbox - https://app.sndbox.com
VirusBay - https://beta.virusbay.io
Any.run - https://app.any.run
Intezer - https://analyze.intezer.com
Malwr - https://malwr.com
Metadefender - https://metadefender.opswat.com
Valkyrie - https://valkyrie.comodo.com
Joe Sandbox - https://www.joesandbox.com
Pikker - http://sandbox.pikker.ee
ViCheck - https://www.vicheck.ca
Jotti - https://virusscan.jotti.org
Virscan - http://virscan.org
Anubis - http://anubis.iseclab.org
Wepawet - https://wepawet.cs.ucsb.edu

## Static string analysis:
### Linux:
file
trid
strings
exiftool
imphash
ssdeep
authentihash
uudeview
foremost
scalpel
steghide
stegsnow
zsteg
pev
pescanner.py
AnalyzePE
upx
yara
ripPE - https://github.com/matonis/ripPE
Unipacker - https://github.com/unipacker/unipacker

### Windows:
CFF Explorer - https://ntcore.com/?page_id=388
Resource Hacker - http://www.angusj.com/resourcehacker
XN Resource Hacker - https://stefansundin.github.io/xn_resource_editor
Dependency Walker - http://www.dependencywalker.com/
LordPE - http://www.woodmann.com/collaborative/tools/images/Bin_LordPE_2010-6-29_3.9_LordPE_1.41_Deluxe_b.zip
Scylla - https://github.com/NtQuery/Scylla
Detect It Easy - https://ntinfo.biz/
PE Explorer - http://www.heaventools.com/overview.htm
Import REConstructor - https://github.com/NtQuery/Scylla
LordPE - https://www.aldeid.com/wiki/LordPE
PEiD - https://www.aldeid.com/wiki/PEiD
PEview - https://www.aldeid.com/wiki/PEView
FileAlyzer - https://www.safer-networking.org/products/filealyzer/
PEstudio - https://www.winitor.com/
Chimprec - https://www.aldeid.com/wiki/CHimpREC
PE Insider - https://cerbero.io/peinsider/
PEframe - https://github.com/guelfoweb/peframe
UPX - https://github.com/upx
Manalyze - https://github.com/JusticeRage/Manalyze
PortEx - https://github.com/katjahahn/PortEx
Signsrch - https://aluigi.altervista.org/mytoolz/signsrch.zip
Revelo - http://www.kahusecurity.com/2012/05/revelo-javascript-deobfuscator
UniExtract2 - https://github.com/Bioruebe/UniExtract2
MalUnpack - https://github.com/hasherezade/mal_unpack

## Live dynamic detonation:
### Proxy
Fiddler - https://www.telerik.com/fiddler
Burp Suite - https://portswigger.net/burp/communitydownload
### MitM
FakeDNS - https://www.fireeye.com/services/freeware/apatedns.html
ApateDNS - https://github.com/Crypt0s/FakeDns
### C2
FakeNet - https://github.com/fireeye/flare-fakenet-ng
INetSim - https://www.inetsim.org
netcat - http://netcat.sourceforge.net
TCPView - https://docs.microsoft.com/en-us/sysinternals/downloads/tcpview
Wireshark - https://www.wireshark.org
Imaginary C2 - https://github.com/felixweyne/imaginaryC2
Suricata - https://suricata-ids.org/download/
Emerging Threat SIGs - https://rules.emergingthreats.net/
Tor - https://www.torproject.org/
### Registry
RegShot - https://sourceforge.net/projects/regshot
WhatChanged - https://www.majorgeeks.com/files/details/what_changed.html
CaptureBAT - https://www.honeynet.org/node/315
### Process
Process Hacker - https://github.com/processhacker/processhacker
Process Monitor - https://docs.microsoft.com/en-us/sysinternals/downloads/procmon
Process Explorer - https://docs.microsoft.com/en-us/sysinternals/downloads/process-explorer
ProcessSpawnControl - https://github.com/felixweyne/ProcessSpawnControl
ProcDOT - http://www.procdot.com
### API
API Monitor - http://www.rohitab.com/apimonitor#Download
APISpy - http://www.matcode.com/apis32.htm
### Persistance
Autoruns - https://docs.microsoft.com/en-us/sysinternals/downloads/autoruns
### Memory
volatility - https://github.com/volatilityfoundation/volatility
Memoryze - https://www.fireeye.com/services/freeware/memoryze.html
OSR Driver Loader - https://www.aldeid.com/wiki/OSR-Driver-Loader
The Sleuth Kit - https://github.com/sleuthkit/sleuthkit
Truman - http://nsmwiki.org/Truman_Overview
yara - https://github.com/virustotal/yara
### Frameworks
mastiff - https://github.com/KoreLogicSecurity/mastiff
IRMA - https://github.com/quarkslab/irma
VIPER - https://github.com/viper-framework/viper
Loki - https://github.com/Neo23x0/Loki
Multiscanner - https://github.com/mitre/multiscanner

## Manual reverse engineering:
### PE:
Online - https://onlinedisassembler.com/static/home/index.html
IDA - https://www.hex-rays.com/products/ida/
Hex-Rays Decompiler - https://www.hex-rays.com/products/decompiler/
radare2 - https://github.com/radare/radare2
Binary Ninja - https://binary.ninja/
BinDiff - https://www.zynamics.com/bindiff.html
BinNavi - https://github.com/google/binnavi
Bochs - http://bochs.sourceforge.net/getcurrent.html
x64dbg - https://x64dbg.com/#start
WinDbg - https://docs.microsoft.com/en-us/windows-hardware/drivers/debugger/debugger-download-tools
OllyDbg - http://www.ollydbg.de/
ImmunityDbg - https://www.immunityinc.com/products/debugger/
### Shellcode:
xorsearch - https://blog.didierstevens.com/2014/09/29/update-xorsearch-with-shellcode-detector/
scdbg - http://sandsprite.com/blogs/index.php?uid=7&pid=152
shellcode2exe - https://zeltser.com/convert-shellcode-to-assembly/
jmp2it - https://digital-forensics.sans.org/blog/2014/12/30/taking-control-of-the-instruction-pointer/
### .NET:
dnSpy - https://github.com/0xd4d/dnSpy
dotPeek - https://www.jetbrains.com/decompiler
ILSpy - https://github.com/icsharpcode/ILSpy
JustDecompile - https://www.telerik.com/products/decompiler.aspx
JustAssembly - https://www.telerik.com/justassembly
Reflector - https://www.red-gate.com/products/dotnet-development/reflector/index
CodeReflect - http://www.devextras.com/decompiler
Dis# - http://www.netdecompiler.com
IL Disassembler - https://www.dotnetperls.com/il-disassembler
Disassembly Diagnoser - https://adamsitnik.com/Disassembly-Diagnoser
### JS:
V8 - https://isc.sans.edu/diary/V8+as+an+Alternative+to+SpiderMonkey+for+JavaScript+Deobfuscation/12157
box-js - https://github.com/CapacitorSet/box-js
js-detox - https://github.com/svent/jsdetox
### Flash:
SWFDec - https://cgit.freedesktop.org/wiki/swfdec
swf_mastah.py - https://github.com/9b/pdfxray_lite/blob/master/swf_mastah.py
### VBA:
ViperMonkey - https://github.com/decalage2/ViperMonkey
olevba.py - https://github.com/decalage2/oletools/wiki/olevba
### OLE:
OfficeMalScanner - http://www.reconstructer.org/code/OfficeMalScanner.zip
OLETools - https://www.decalage.info/python/oletools
Hachoir - https://bitbucket.org/haypo/hachoir/wiki/hachoir-urwid
EXEFilter - http://www.decalage.info/exefilter
### PDF:
PDF Stream Dumper - http://sandsprite.com/blogs/index.php?uid=7&pid=57
PDF Dissector - https://blog.zynamics.com/2010/09/03/pdf-dissector-1-7-0-released/
PDF Tools - https://blog.didierstevens.com/programs/pdf-tools/
pdfid.py - https://blog.didierstevens.com/programs/pdf-tools/
pdfparser.py - https://blog.didierstevens.com/programs/pdf-tools/
peepdf.py - https://github.com/jesparza/peepdf
qpdf - http://qpdf.sourceforge.net/

## Other:

Kahusecurity Tools - http://www.kahusecurity.com/tools.html
DidierStevensSuite - https://github.com/DidierStevens/DidierStevensSuite
Awesome Malware Analysis list - https://github.com/rshipp/awesome-malware-analysis
Awesome Reversing list - https://github.com/tylerha97/awesome-reversing
