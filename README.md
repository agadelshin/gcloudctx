This repository provides gcloudctx tool. gcloudctx was inspired by [kubectx/kubens](https://github.com/ahmetb/kubectx)

`gcloudctx` helps you create gcloud configurations and switch between them

```
USAGE:
  gcloudctx                       : list the contexts
  gcloudctx <NAME>                : switch to context <NAME>
  gcloudctx -c <NAM               : create context <NAME>
  gcloudctx -d <NAME> [<NAME...>] : delete context <NAME> ('.' for current-context)
  gcloudctx -h,--help             : show this message
```

## TODO:

* swap configurations
* colorized output
* complitions
* interactive mode