osx & ios re 101
==========

Work in progress as I am actively collecting these.

#### Must read

1. http://reverse.put.as/
- http://researchcenter.paloaltonetworks.com/tag/mac-os-x/
- https://www.synack.com/r-d-projects/os-x-security-research/
- http://samdmarshall.com/re.html
- https://github.com/bx/machO-tools

#### Keep these handy
1. "OSX Mach-O File Format Reference" http://samdmarshall.com/re/Mach-O_File_Format.pdf
- "OSX ABI" http://samdmarshall.com/re/Mac_OS_X_ABI_Function_Calls.pdf
- Mach-O structures http://www.opensource.apple.com/source/xnu/xnu-2050.18.24/EXTERNAL_HEADERS/mach-o/loader.h
- "OSX BSD system calls" http://dyjakan.sigsegv.pl/osx-bsd-syscalls/
- http://www.opensource.apple.com/source/xnu/xnu-2050.18.24/bsd/kern/syscalls.master

#### Basics

1. "Universal Binary: The Mach-O file format" http://cocoaintheshell.com/2009/07/universal-binary-mach-o-format/
- "Basics of the Mach-O file format" https://samhuri.net/posts/2010/01/basics-of-the-mach-o-file-format/
- "How OS X Executes Applications" http://0xfe.blogspot.de/2006/03/how-os-x-executes-applications.html
- "Infecting Mach-O object format" https://reverse.put.as/wp-content/uploads/2011/06/mach-o_infection.ppt
- "Under the iHood" https://www.defcon.org/images/defcon-16/dc16-presentations/defcon-16-hotchkies.pdf
- "Dissection of minimal Intel 32-bits, 204 bytes, Mach-O "Hello World" executable file" http://seriot.ch/hello_macho.php
- "Crafting a Tiny Mach-O Executable" http://osxbook.com/blog/2009/03/15/crafting-a-tiny-mach-o-executable/
- "Parsing Mach-O files" http://lowlevelbits.org/parse-mach-o-files/
- "ELF vs. Mach-O" http://timetobleed.com/dynamic-linking-elf-vs-mach-o/
- "ELF vs. Mach-O 2" http://timetobleed.com/dynamic-symbol-table-duel-elf-vs-mach-o-round-2/
- "NASM Hello World for x86 and x86_64 Intel Mac OS X" https://gist.github.com/FiloSottile/7125822

#### Anti-debugging, infection techniques, viruses, obfuscation and encryption

1. "Infecting Mach-O" http://reverse.put.as/wp-content/uploads/2013/05/Infecting_Mach-O_Files.pdf
- "Abusing the Mach-O format" http://cocoaintheshell.com/2009/10/abusing-mach-o
- "Multi-Platform Viruses Made Easy - A Case Study" http://vxer.org/lib/vjp00.html
- "Malware persistence techniques on Mac OS X" https://www.virusbtn.com/pdf/conference/vb2014/VB2014-Wardle.pdf

#### Crackmes and challenges

1. https://reverse.put.as/crackmes/
- "Exercises" section in http://beginners.re/Reverse_Engineering_for_Beginners-en.pdf

#### Analyzes, research & "hands-on"

1. "Cracking Tutorial #1 - "Sandwich" CrackMe" http://reverse.put.as/wp-content/uploads/2012/06/Sandwich_crackme_tut_qwertyoruiop.txt
- "Solving crackmes with LDPRELOAD" http://radare.today/solving-crackmes-with-ldpreload/
- "Analyzing Binaries with Hopper’s Decompiler" http://abad1dea.tumblr.com/post/23487860422/analyzing-binaries-with-hoppers-decompiler
- "Reverse Engineering Hopper Disassembler v3.9.9" https://www.youtube.com/watch?v=pCITcLqgS9Q
- "Reverse-Engineering iOS Apps: Hacking on Lyft" https://realm.io/news/conrad-kramer-reverse-engineering-ios-apps-lyft/
- "Jailbreak iOS 8.1.2 and Analyze Related Exploits" http://en.wooyun.io/2016/01/18/38.html
- "The Italian morons are back! What are they up to this time?" https://reverse.put.as/2016/02/29/the-italian-morons-are-back-what-are-they-up-to-this-time/
- "Revisiting Mac OS X Kernel Rootkits" http://phrack.org/issues/69/7.html#article

#### Other

1. "Attacking The XNU Kernel in El Capitan" https://www.blackhat.com/docs/eu-15/materials/eu-15-Todesco-Attacking-The-XNU-Kernal-In-El-Capitain.pdf
- "Shooting the OSX El Capitan Kernel Like a Sniper" https://speakerdeck.com/flankerhqd/shooting-the-osx-el-capitan-kernel-like-a-sniper
- "The Python bites your apple - fuzzing and exploiting OSX Kernel bugs" https://speakerdeck.com/flankerhqd/the-python-bites-your-apple-fuzzing-and-exploiting-osx-kernel-bugs
- "Let's Play: Practical OS X Malware Detection & Analysis" https://www.synack.com/wp-content/uploads/2016/03/RSA_OSX_Malware.pdf
- "Methods of malware persistence on Mac OS X" https://www.virusbulletin.com/uploads/pdf/conference/vb2014/VB2014-Wardle.pdf
- "MachOView is a visual Mach-O file browser" http://sourceforge.net/projects/machoview/
- "0xED is a native OS X hex editor" http://www.suavetech.com/0xed/
- "Hopper is a reverse engineering tool for OS X and Linux" http://www.hopperapp.com/
- "Artefacts and tricks for Mac OS X" http://sud0man.blogspot.fr/2015/05/artefacts-for-mac-os-x.html?m=1
- "Collection of forensics artifacs location for Mac OS X and iOS" https://github.com/pstirparo/mac4n6
- "A curated list of shell commands and tools specific to OS X" https://github.com/herrbischoff/awesome-osx-command-line
- "OS X Security and Privacy Guide" https://github.com/drduh/OS-X-Security-and-Privacy-Guide
- "A launchd tutorial" http://launchd.info/
- https://objective-see.com/index.html
- "OS X malloc introspection tool" https://github.com/blankwall/MacHeap

#### Books

1. "The Mac Hacker's Handbook" by Charlie Miller, Dino Dai Zovi
- "Mac OS X and iOS Internals: To the Apple's Core" by Jonathan Levin
- "Mac OS X Internals: A Systems Approach" by Amit Singh
- "iOS App Reverse Engineering" https://github.com/iosre/iOSAppReverseEngineering
- "iOS Hacker's Handbook" by Charlie Miller, Dion Blazakis, Dino Dai Zovi, Stefan Esser, Vincenzo Iozzo, Ralf-Philip Weinmann 
- "Hacking and Securing iOS Applications" by Jonathan Zdziarski
