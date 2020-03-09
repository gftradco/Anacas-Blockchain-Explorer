# Anacas Steel Blockchain Explorer
Thank you Nióbio Cash -Blockchain-Explorer
<!---
Block explorer for Nióbio Cash CryptoNote based cryptocurrency.
--->
#### Installation

1) It takes data from daemon anacasd. It should be accessible from the Internet. Run anacasd with open port as follows:
```bash
./anacasd --restricted-rpc --enable-cors=* --enable-blockchain-indexes --rpc-bind-ip=0.0.0.0 --rpc-bind-port=21129
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.

