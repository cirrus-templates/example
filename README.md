# Example template

An example template that generates a task which prints `Hello, World!`.

## Usage

```
load("github.com/cirrus-templates/example", "hello_world")

def main(ctx):
  return hello_world()
```
