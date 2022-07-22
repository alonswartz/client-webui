# test wireleap client webui

## usage

```shell
cd $HOME/wireleap
git clone git@github.com:wireleap/testui.git ./webroot
```

```shell
# start controller if not already running
wireleap start
```

Open browser: [http://127.0.0.1:13490](http://127.0.0.1:13490)

## development

```shell
tailwindcss -i index.css -o build/index.css [--watch]
```

