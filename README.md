node-dash
=========

A dashboard to monitor nodejs traffic without degrading performance in real time.

1. Request Rates.
2. Error Rates and statuses. 
3. Geographic distribution.
4. Deviice distribution.
5. Popular pagehits

Note: This project is still under construction.

Setup
=====

```bash
sudo apt-get install libpcap-dev #this is not needed on OS X
npm install node-dash
```

##Install pcap
```
git clone https://github.com/mranney/node_pcap pcap
cd pcap
npm install
node-gyp configure build
```
