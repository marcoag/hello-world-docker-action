# Hello World Docker action

This is an action created following the defaul ttutorial from github. It prints "Hello World" by thefault or "Hello" + the name of a person to greet to the log. 

It runs the script in a docker machine.

## Example usage

uses: actions/hello-world-docker-action@v1
with:
  who-to-greet: 'Mona the Octocat'
