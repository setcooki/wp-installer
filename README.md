# wp-install

wordpress core + demo data installer script

## Requirements

you need to be able to run at least "wget" command from terminal

## Install

### Linux and Mac OS X

$ curl -O https://raw.githubusercontent.com/setcooki/wp-installer/master/wp-install; bash ./wp-install
$ wget -Nnv https://raw.githubusercontent.com/setcooki/wp-installer/master/wp-install; bash ./wp-install

### Windows

currently not supported!

## Run

$ bash ./wp-install

and follow install steps

## Tips

you can add the "wp-config.php" file manually and the installer will skip this part and take all required
config data from the "wp-config.php" instead.

you can also put a "wp-cli.yml" config file in the root directory and specify install path and other things
see > https://make.wordpress.org/cli/handbook/config/

## Issues

wp-install needs execute permission so you may need to set those with:

$ chmod +x wp-install