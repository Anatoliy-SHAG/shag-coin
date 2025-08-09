SHAG Monero-fork scaffold (placeholder)

This folder contains a description and helper templates for forking Monero into SHAG.
It does NOT contain Monero source code (Monero repo is large and must be cloned separately).

Steps you will need to do manually:
1. Clone Monero source locally:
   git clone --recursive https://github.com/monero-project/monero.git
2. Create a branch for SHAG and apply patches from this scaffold (edit parameters in src/cryptonote_config and create genesis block)
3. Adjust emission and premine in emission code (refer to README below).
4. Build Monero with required dependencies (Boost, OpenSSL, etc.)

Files included here:
- genesis_template.txt   : explain fields needed for genesis
- patch_example.patch    : placeholder for changes to be applied
- README.build.txt       : high-level build notes
