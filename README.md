# Portable xmrig for linux, 18 October protocol supported 

Usage
---
Basic example 

xmrig -o xmr-eu.dwarfpool.com:8005 -u YOUR_WALLET -p x -k 

Options 

  -a, --algo=ALGO       cryptonight (default) or cryptonight-lite \
  -o, --url=URL         URL of mining server \
  -b, --backup-url=URL  URL of backup mining server \
  -O, --userpass=U:P    username:password pair for mining server \
  -u, --user=USERNAME   username for mining server \
  -p, --pass=PASSWORD   password for mining server \
  -t, --threads=N       number of miner threads \
  -v, --av=N            algorithm variation, 0 auto select \
  -k, --keepalive       send keepalived for prevent timeout (need pool support) \
  -r, --retries=N       number of times to retry before switch to backup server (default: 5) \
  -R, --retry-pause=N   time to pause between retries (default: 5) \
      --cpu-affinity    set process affinity to cpu core(s), mask 0x3 for cores 0 and 1 \
      --no-color        disable colored output \
      --donate-level=N  donate level, default 5% (5 minutes in 100 minutes) \
  -B, --background      run the miner in the background \
  -c, --config=FILE     load a JSON-format configuration file \
      --max-cpu-usage=N maximum cpu usage for automatic threads mode (default 75) \
      --safe            safe adjust threads and av settings for current cpu \
      --nicehash        enable nicehash support \
  -h, --help            display this help and exit \
  -V, --version         output version information and exit \
  
_Note: this is a latest build of C classic version of the xmrig_

