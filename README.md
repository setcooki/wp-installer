# wp-installer

wordpress core + demo data installer script

## Requirements

you need to be able to run at least "wget" command from terminal

## Install

### Linux and Mac OS X

``` sh
$ curl -O https://raw.githubusercontent.com/setcooki/wp-installer/master/wp-installer; bash ./wp-installer
```
``` sh
$ wget -Nnv https://raw.githubusercontent.com/setcooki/wp-installer/master/wp-installer; bash ./wp-installer
```

### Windows

currently not supported!

## Run

``` sh
$ bash ./wp-installer
```

and follow install steps. Script can be executed with command line arguments - see script header.

## Tips

you can add the "wp-config.php" file manually and the installer will skip this part and take all required
config data from the "wp-config.php" instead.

you can also put a "wp-cli.yml" config file in the root directory and specify install path and other things
see > https://make.wordpress.org/cli/handbook/config/

## Issues

wp-installer needs execute permission so you may need to set those with:

``` sh
$ chmod +x wp-installer
```