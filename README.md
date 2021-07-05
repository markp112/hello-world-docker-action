# hello-world-docker-action

This action prints "hello world" or "hello" + the name of the person to greet to the log.

## inputs
## `who-to-greet`
**Required** The name of the person to greet. Default `"world"`.

## outputs
## `time`

the time we greeted you

uses: actions/heelow-world-docker-action@v1
with:
who-to-greet: 'mona the Octocat'
