What would a CONFidence CTF be without a Windows-hosted exploitation challenge? :) This time you're facing a fast, greatly optimized calculator capable of concurrently evaluating multiple expressions. In fact it is so technically advanced that it will only run on CPUs supporting the cutting-edge SSE2 extension. Do you think you can hack it?

Don't be scared too easily by the scoring -- it is mostly meant to encourage pwning this exotic "Windows" system. :-)

The service is running at fastcalc.hackable.software:4141. The flag is in the "flag.txt" file.

The platform is Windows Server 2012 R2. You can reproduce the task's environment by running: AppJailLauncher.exe /outbound /port:4141 /timeout:1000000000 /key:flag.txt fastcalc.exe
