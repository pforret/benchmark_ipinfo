![bash_unit CI](https://github.com/pforret/benchmark_ipinfo/workflows/bash_unit%20CI/badge.svg)
![Shellcheck CI](https://github.com/pforret/benchmark_ipinfo/workflows/Shellcheck%20CI/badge.svg)
![GH Language](https://img.shields.io/github/languages/top/pforret/benchmark_ipinfo)
![GH stars](https://img.shields.io/github/stars/pforret/benchmark_ipinfo)
![GH tag](https://img.shields.io/github/v/tag/pforret/benchmark_ipinfo)
![GH License](https://img.shields.io/github/license/pforret/benchmark_ipinfo)
[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://www.basher.it/package/)

# benchmark_ipinfo

Test and compare IP Info lookup APIs

## 🔥 Usage

```
Program : benchmark_ipinfo  by peter@forret.com
Version : v0.2.2 (2023-08-06 20:54)
Purpose : Test and compare IP Info lookup APIs
Usage   : benchmark_ipinfo [-h] [-q] [-v] [-f] [-l <log_dir>] [-t <tmp_dir>] [-O <OUT_DIR>] <action> <input?>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] also show debug messages [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: /home/pforret/log/benchmark_ipinfo]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: /tmp/benchmark_ipinfo]
    -O|--OUT_DIR <?> : [option] output folder  [default: output]
    <action>         : [choice] action to perform  [options: run,ip,list,check,env,update]
    <input>          : [parameter] input ip address (optional)
                                  pforret:pforret/benchmark_ipinfo.git
### TIPS & EXAMPLES
* use benchmark_ipinfo run to check all IP addresses and all IP API services
  benchmark_ipinfo run
* use benchmark_ipinfo ip to check one IP address for all IP API Services
  benchmark_ipinfo ip 1.1.1.1
* use benchmark_ipinfo list to kist all used API services and IP addresses
  benchmark_ipinfo list
* use benchmark_ipinfo check to check if this script is ready to execute and what values the options/flags are
  benchmark_ipinfo check
* use benchmark_ipinfo env to generate an example .env file
  benchmark_ipinfo env > .env
* use benchmark_ipinfo update to update to the latest version
  benchmark_ipinfo update
* >>> bash script created with pforret/bashew
* >>> for bash development, also check out pforret/setver and pforret/progressbar
```

## ⚡️ Examples

```bash
> benchmark_ipinfo list
# list all IPs and APIs

> benchmark_ipinfo run
# lookup all IPs on all APIs

> benchmark_ipinfo ip 8.8.4.4
# lookup 8.8.4.4 on all APIs

> benchmark_ipinfo -h 
# get extended usage info

> benchmark_ipinfo env > .env
# create a .env file with default values
```

## List of APIs

✅  List of IP API services

* abstractapi.com
* db-ip.com
* getgeoapi.com
* ip2location.io
* ip-api.com
* ipapi.co
* ipgeolocation.io
* ipinfo.io
* ipstack.com
* ipwho.is
* whoisxmlapi.com
  
## 🚀 Installation

with [basher](https://github.com/basherpm/basher)

	$ basher install pforret/benchmark_ipinfo

or with `git`

	$ git clone https://github.com/pforret/benchmark_ipinfo.git
	$ cd benchmark_ipinfo

## 📝 Acknowledgements

* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2023 pforret
