# Baking Bad IDE
A customizable local development environment.

## Better Call Dev + Your sandbox node
1. Ensure your sandbox node is exposed at `172.17.0.1:8732`
2. Make sure ports `8000` and `42000` are not in use
3. Launch BCD (will be available at https://localhost:8000)
```
make bcd
```
4. Stop BCD
```
make bcd-stop
```
5. Delete all data
```
make bcd-clear
```

## Better Call Dev + Flextesa + Jupyter
1. Launch BCD
```
make bbbox
```
2. Stop and delete all
```
make drop
```

## Better Call Dev staging `you.better-call.dev`
1. Create and fill `.env` file (see https://github.com/baking-bad/bcdhub#environment-variables-env)
2. Launch BCD
```
make custom
```
3. Stop and delete all
```
make drop
```

## Proxy targets
Exports all variable from the `.env` file.

#### Contract aliases
See https://github.com/baking-bad/bcdhub#contract-aliases
```bash
make aliases
make migration
```

#### Data migration
See https://github.com/baking-bad/bcdhub#data-migration
```bash
make migration
```

#### Snapshots
See https://github.com/baking-bad/bcdhub#snapshots
``` bash
make s3-creds
make s3-repo
make s3-snapshot
make s3-restore
```

## Contact us
* Telegram: https://t.me/baking_bad_chat
* Twitter: https://twitter.com/TezosBakingBad
* Slack: https://tezos-dev.slack.com/archives/CV5NX7F2L
