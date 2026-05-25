This script will reclaim storage space used by system logs,
temporary and cached files, and by pruning the docker system. 

Usage: ./run-reclaim [OPTION]\n

  Options:
  -h      Display this help message.
  -dsp    Include the docker system pruning process.

  Note: any other option will  clear system logs, temporary
        and cached files, but skip pruning the docker system.
        
