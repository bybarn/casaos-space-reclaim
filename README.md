This script will reclaim storage space used by system logs,<BR>
temporary and cached files, and by pruning the docker system. 

Usage:<BR>./run-reclaim [OPTION]<BR>

  Options:<BR>
  -h&nbsp;&nbsp;&nbsp;&nbsp;Display this help message.<BR>
  -dsp&nbsp;&nbsp;Include the docker system pruning process.<BR>

  Note: any other option will  clear system logs, temporary<BR>
        and cached files, but skip pruning the docker system.
        
