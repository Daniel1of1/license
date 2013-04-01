license
=======

npm module to generate common FOSS licenses with a cli
```
Usage: license [-h]
license [-l]
license [ -o [OWNER] -p [PROJECT] -y [YEAR] ] [license]
license [--config[.key <VALUE>]]
license [--header]

Options:
  -h, --help          show this help menu                                                                                     
  -l, --list          list all available license templates                                                                    
  -o, --organization  the organisation/owner that holds the copy[right,left]                                                    [default: "Daniel Haight\n"]
  -p, --project       the name of the project                                                                                   [default: "bin"]
  -y, --year          copyright year                                                                                            [default: 2013]
  --config            set default values: usage --config.key value
 available:[year], [project], [licenseType], [organisation]
  --header            just get the license header                                                                             
```
