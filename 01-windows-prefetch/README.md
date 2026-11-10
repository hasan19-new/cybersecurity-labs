# Windows Prefetch Forensic Analysis

Task: Investigate Windows Prefetch files to find which programs were run.

Tools: WinPrefetchView, PECmd, OSForensics, FTK Imager, Registry Editor

What I did: Checked that prefetch logging was enabled in the registry, read the prefetch records, and compared the results across four tools.

What I learned: Windows keeps a record of the programs it runs, and that record can show what happened on a machine.
