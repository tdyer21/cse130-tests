# How to use

Be sure to check back often, tests may be added or fixed over time.

Download the test folder and put it into your asgn3 directory. You can add "test/" to .gitignore and the test folder will not be tracked by git. You no longer need to add `./` to your path for this script to work.

The script needs your makefile to support the `all` and `spotless` target.  

Finally, from your asgn2 directory `cd test` and type `a3test`. You may need to do `chmod +x a3test` so that the script will be executable. Do not run `loadbalancer` on your own, the script will handle that for you. The tests also uses the given `httpserver` binary, so there is no need to supply your own.

With no arguments, the script will run all test cases. Users may also specify which tests to run in the command line arguments. `a3test args get put` will only run the `args`, `get`, and `put` test classes. Non-existent test classes are ignored.

The script will run and give outputs of failed tests. Failed tests also created fail logs in the test directory. It contains some notes about what the test is testing for, as well as the test output and expected output. These fail logs are deleted when the test is re run, so save them if you need them.

