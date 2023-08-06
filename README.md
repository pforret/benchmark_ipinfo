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
Version : v0.0.1 (Apr 22 16:07:13 2023)
Purpose : Test and compare IP Info lookup APIs
Usage   : benchmark_ipinfo [-h] [-q] [-v] [-f] [-l <log_dir>] [-t <tmp_dir>] <action>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] also show debug messages [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: /Users/pforret/log/script]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: /tmp/script]
    <action>         : [choice] action to perform  [options: action1,action2,check,env,update]
                                  
### TIPS & EXAMPLES
* use benchmark_ipinfo action1 to ...
  benchmark_ipinfo action1
* use benchmark_ipinfo action2 to ...
  benchmark_ipinfo action2
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
> benchmark_ipinfo -h 
# get extended usage info
> benchmark_ipinfo env > .env
# create a .env file with default values
```

## 🚀 Installation

with [basher](https://github.com/basherpm/basher)

	$ basher install pforret/benchmark_ipinfo

or with `git`

	$ git clone https://github.com/pforret/benchmark_ipinfo.git
	$ cd benchmark_ipinfo

## 📝 Acknowledgements

* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2023 pforret
