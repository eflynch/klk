# klk #

This is a command-line tool for tracking hours working on projects

It requires python3 and termcolor

try
```
pip3 install termcolor
```

then try
```
./klk -c myproject
./klk myproject -i
```

## manual ##

```
Usage: klk [options]

Options:
  -h, --help            show this help message and exit
  -p PROJECT, --project=PROJECT
                        project name
  -t DATES, --dates=DATES
                        dates to expand in report
  -e EDIT, --edit=EDIT  stamp edit command c:[s]:[e] d:[i] s:[i]:[s] e:[i]:[e]
  -d, --delete          delete project
  -c, --create          create new project
  -l, --list            list projects
  -r, --report          report project
  -$ RATE, --rate=RATE  rate for project
  -v, --verbose         verbose report
  -i, --in              punch in
  -o, --out             punch out
  ```
