# recon.sh
An Agressive Shell Based Subdomain Recon Enumeration Tool designed for Android Termux (works in Kali Linux).

You must have Tor installed in the terminal for `--stealth` mode to work. 
```
apt-get install tor
-or-
pip install tor
```
## Usage
```
git clone https://github.com/TheOSuite/precon.git

cd recon

# Make it executable
chmod +x recon.sh

# Basic usage
./recon.sh example.com

# Save more hosts
./recon.sh example.com 500

# Full scan mode
./recon.sh example.com 300 --full

# Skip port scanning
./recon.sh example.com 200 --skip-ports

# Stealth mode
./recon.sh example.com --stealth
```
Output will be saved in a folder and include live hosts.

## Only test on Websites you have permission for!
