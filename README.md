# reflector
Similar to the watch command, this just sends the output of a command to index.html file that is then made viewable by a python http server. 

```bash
# send the results of the command to <hostname>:<port> every <sleep> seconds
perl reflect --sleep 3 --port 8084 --command "ls -l /my/output/dir"
```
