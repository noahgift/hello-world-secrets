# hello-world-secrets
Example of how to deal with secrets in local development environment

1.  Export secrets in `~/.bashrc`
2.  Allows all new terminals launched to get secrets

## Pros

*   Prevents accidental checkin to Github 

## Gotchas

*  Must never checkin `~/.bashrc`
*  Project may need more complex solution in the future

## Other Solutions

* More [complex secrets manager](https://aws.amazon.com/secrets-manager/)
