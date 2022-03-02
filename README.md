## GO: Print ENV Variablevs

### GoLang Script file
get_environment_vars.go

### Created an alias in BASH:
alias env\(1\)="go run get_environment_vars.go"

### Usage:
#### It prints all env variables as requested.
env(1)

### Script details:
1. In Go everything managed by packages, we named our package as main
2. Imported fmt and os packages.
3. Function to run for loop, and replaces ':' with =
```
fmt: Default package of GO. For formatting.
os: Is the package get OS environment variables and other OS related stuff.
```
### Online Go lang compiler: 
https://go.dev/play/

### References:
[geeksforgeeks](https://www.geeksforgeeks.org/golang-environment-variables/)

[YouTube](https://www.youtube.com/watch?v=yyUHQIec83I&t=939s)

[zetacode](https://zetcode.com/golang/env/#:~:text=Go%20os.&text=The%20Getenv%20retrieves%20the%20value,an%20unset%20value%2C%20use%20LookupEnv%20.&text=The%20example%20prints%20the%20name%20of%20the%20current%20user%20shell.)