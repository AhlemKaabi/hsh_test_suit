# Simple Shell, Checks

There will be no checks released before the deadline. We **strongly** encourage the whole class to work together and create a suite of checks covering both regular tests and edged cases for each task.

Here is an example on how to check your shell.
Fork this repo and add more checks to help you and the rest of the class build the best simple shell possible.

## Configuration

Open the file `config` and update the variable `SHELL` with your shell executable name!

OR you can move your executable into this repo and change it's name to `simple_shell`

## How it works

The script will send command to your executable like this: `echo "ANY_COMMAND" | ./simple_shell`

the output will be send to a file *checker_output_RANDOM_NUMBER* and if there is errors generated by the command it will be sent to file 
*checker_error_output_RANDOM_NUMBER* or to */dev/null* it depends on the check.

to check the results of tests you will need to remove the `rm` commands in *check_simple_shell.bash* and on each test case you want to verify

## Run

Usage `./check_simple_shell.bash`
