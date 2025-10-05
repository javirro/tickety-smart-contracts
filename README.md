## tICKETY

### Commands to install everything

```shell
forge init
```

The following commands will install the git submodules. However, in Windows there is a problem with the "/" and "\". Before running any command, go to the file .gitmodules and modified to be something to this:

```
[submodule "lib/forge-std"]
	path = lib/forge-std
	url = https://github.com/foundry-rs/forge-std
```

```shell
forge install foundry-rs/forge-std
```

```shell
forge install OpenZeppelin/openzeppelin-foundry-upgrades
```

```shell
forge install OpenZeppelin/openzeppelin-contracts-upgradeable
```