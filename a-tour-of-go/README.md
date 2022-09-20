# A Tour of Go
## Packages
- Go is made up of packages
- Programs start running in pakcage main

**packages.go**
- Here we import 2 packages fmt and math/rand
- The env is deterministic, meaning that random will always run the same
- for import we can either use (<import list>) or import <package name>
- exported variables start with a capital letter, for example we use math.Pi, not math.pi, since Pi is from the math package

**functions.go**
- functions can take zero or more input args
- first we defined the var name, then the type, type can be omitted if all use the same one
- finally the fun will also have a return type, if there is one