# How to run
I used version 5.0.0 of the K-framework tool from https://github.com/kframework/k/releases on WSL Ubuntu Bionic.

Once the tool is installed, type `kompile tinysol-oo.k` in a terminal window and after a couple seconds it should complete (there may be warnings that I can't get rid of). Then, for example, type `krun tests/d1.k` to run the demo files. 

The result of execution will be any log statements executed (at the beginning of the output) and a dump of somewhat readable nested angle brackets representing the final state of the configuration. 
