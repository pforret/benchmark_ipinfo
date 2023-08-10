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
Version : v0.3.0 (Aug 11 01:00:47 2023)
Purpose : Test and compare IP Info lookup APIs
Usage   : benchmark_ipinfo [-h] [-q] [-v] [-f] [-l <log_dir>] [-t <tmp_dir>] [-O <OUT_DIR>] <action> <input?>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] also show debug messages [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: /Users/pforret/log/benchmark_ipinfo]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: /tmp/benchmark_ipinfo]
    -O|--OUT_DIR <?> : [option] output folder  [default: output]
    <action>         : [choice] action to perform  [options: run,ip,list,check,env,update]
    <input>          : [parameter] input ip address (optional)
```

## ⚡️ Examples

```bash
> benchmark_ipinfo list
# list all IPs and APIs

> benchmark_ipinfo run
# lookup all IPs on all APIs

> benchmark_ipinfo ip 195.142.68.93
     abstractapi.com : TR  Turkey                         Bursa                          Superonline Iletisim Hizmetleri                 
           db-ip.com : TR  Turkey                         Kartal                         -                                              
       getgeoapi.com : --  -                              Bursa                          -                                              
      ip2location.io : TR  Turkey                         Istanbul                       Superonline Iletisim Hizmetleri A.S.                 
          ip-api.com : TR  Turkey                         Bursa                          BNG-SOL                                        
            ipapi.co : TR  Turkey                         Bursa                          Superonline Iletisim Hizmetleri A.S.                 
    ipgeolocation.io : TR  Turkey                         Şişli                        Superonline Iletisim Hizmetleri A.S.                 
           ipify.org : TR  -                              Kartal                         TELLCOM-AS                                     
           ipinfo.io : TR  -                              Bursa                          AS34984 Superonline Iletisim Hizmetleri A.S.                 
  ipqualityscore.com : TR  -                              Bursa                          Turkcell Superonline                           
         ipstack.com : TR  Turkey                         Bursa                          -                                              
            ipwho.is : TR  Turkey                         Bursa                          SOL-Customer-MIX                               
     whoisxmlapi.com : TR  -                              Kartal                         TELLCOM-AS     
            
> benchmark_ipinfo -h 
# get extended usage info

> benchmark_ipinfo env > .env
# create a .env file with default values
```

## ✅ List of APIs

* abstractapi.com (requires API key)
* db-ip.com
* getgeoapi.com (requires API key)
* ip2location.io (requires API key)
* ip-api.com
* ipapi.co
* ipgeolocation.io (requires API key)
* ipinfo.io
* ipqualityscore.com (requires API key)
* ipstack.com (requires API key)
* ipwho.is
* whoisxmlapi.com (requires API key)
  
## 🚀 Installation

with [basher](https://github.com/basherpm/basher)

	$ basher install pforret/benchmark_ipinfo

or with `git`

	$ git clone https://github.com/pforret/benchmark_ipinfo.git
	$ cd benchmark_ipinfo

## 📝 Acknowledgements

* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2023 pforret
