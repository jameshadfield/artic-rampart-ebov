# This repo is currently for testing purposes only

This repo is the rampart protocol for EBOV.

### Steps to run:
1. Clone a published protocol (or create your own)
```
git clone git@github.com:jameshadfield/artic-rampart-ebov.git
cd artic-rampart-ebov
```

2. Install everything via the included conda environment:
```
conda env create -f environment.yml
conda activate artic-rampart-ebov
```
Note that this doesn't yet have `binlorry` etc (it's a work in progress).

3. Get some data.
For testing, i've included some _within_ the protocol, but this is not the plan for the future.

4. Run rampart
```
cd test-ebola-data
rampart --verbose --protocol ../
## localhost:3000 all works :)
```