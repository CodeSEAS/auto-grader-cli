# auto-grader-cli

### Goal
auto-grader-cli is going to be the client for auto grader server.
When a user finished the assignment, they would run the submit.py to submit their finished work

###
Flow:

1. static analysis (pylint)
2. asking - email, lark id, file name.
3. file read and compress file.
4. send to server with response code.


### Reference
make sure pip intalled
https://stackoverflow.com/questions/12937533/use-pip-install-uninstall-inside-a-python-script
`
import os
os.system('pip install pygame')
`

ststic analysis -
https://stackoverflow.com/questions/2028268/invoking-pylint-programmatically
