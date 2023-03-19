# TRADELOG SCRIPT
First project of IOS (Operating systems) @FIT VUT BRNO. 
Author: Jakub Phan
# ABOUT
A script that acts as a tool to variously filter tradelogs. Project uses knowladge of bash, awk command line. 
# Usage 
USAGE OF SCRIPT: ``tradelog [-h|--help] [flag] [command] [LOG [LOG2 [...]]``

Included are testing files ``stock-2.log``, ``stock-4.log.gz`` and ``stock-6.log``

# Here are some example calls of this script:

```cat stock-2.log | head -n 5 | ./tradelog

./tradelog -t TSLA -t V stock-2.log

./tradelog list-tick stock-2.log

./tradelog profit stock-2.log

./tradelog pos stock-2.log

./tradelog hist-ord stock-2.log

./tradelog -w 100 graph-pos stock-6.log
```
