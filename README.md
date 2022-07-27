# Binary-Memory-Forensics


Malware Analysis using Ensemble Feature Learning Techniques

As we are exposed to the internet our chances of downloaing a malicious files into our system are high. 
While studing the analysis of malware, we come across the analaysing of malware through memory analysis. The approach of static and dynamic analysis,
we can not reach the root of the malware. there are some tools with the help we can analayse them dynamically. 
But cannot find the damge and effect it had when it has exexuted in the background.  

So, In memory analysis we create a dump of the RAM memory. Or to say we take snaps-shot of the process that have been executed or running in the memory.
We have used the dumpit tool to extract the dump files. and then used volatility tool to extract the information.

Our main work is to extract the information from data dump memory file extracted into images and classify it,
The main problem reading and analysing the binary files are bit time taking process. So converting the portable executable code into images
will reduce the time required to analyse the malware.

The structure of PE header file is .text, .rdata, .data and .rsrc and our approach we have also change the grayscale image to RGB image.
