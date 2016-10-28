# Bash

## Case Statements

```sh
case <varname> in
  <opt1>) 
    code 
    ;;
  <opt2>) 
    code
    more code
    ;;
  <opt3>) code ;;               # Not Recommended for readability
  <opt4>) code; more code;;     # Not Recommended for readability
  *) 
    catchall
    ;;
esac
```
