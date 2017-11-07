Scripts to run the benchmarks and plot the graphs of the OSDI 2014 [https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-belay.pdf] and SOCC 2015 [http://dl.acm.org/citation.cfm?id=2806848] publications.

Instructions:

On IX client and server, load all required kernel modules and hugepage setup, etc. 

On IX client and server, copy the ix.conf file to /etc directory.

Setup passwordless ssh between machine running the script (e.g. the client) and the client and server machines. User must have passwordless sudo access. 

Command:
./bench_pingpong.py --target [ix,linux] --ix [directory of repo with binaries, top-level dir] [hostname of server] [hostname of client] 


