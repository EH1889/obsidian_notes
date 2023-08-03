From a Codewars challenge

Use [[Shell]] to list the most recently modified file in a directory and output only that directory. 

ans=$(ls -ltc | head -n 1)
ans=$(ls -t | sed -n -2p)

The learning points here are you cannot pipe an answer into a variable.
Use sed it pull a specific line, head can cause issues when formatting is at place