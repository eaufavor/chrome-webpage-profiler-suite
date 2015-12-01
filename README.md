# chrome-webpage-profiler-suite
Chrome webpage profiler suite


# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is CWP suite  ###

TDB

### How do I get set up? ###

```
git clone https://github.com/eaufavor/chrome-webpage-profiler-suite.git
cd chrome-webpage-profiler-suite
git submodule init
git submodule update
cd cwp-suite-setup
./configure.py
./install.sh
```

### How to update ###

In `chrome-webpage-profiler-suite`
```
git submodule foreach git pull origin master
cd cwp-suite-setup
./configure.py --no-tshark
./install.sh
```
