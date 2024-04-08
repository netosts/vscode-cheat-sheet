# Cheat Sheet for VSCODE

## Regex
### Format PHP Getters and Setters + toArray method, to follow psr-4 rules:
```
// format Getters
get(.*)_(.*)\(
get\u$1\u$2(

// format Setters
set(.*)_(.*)\(
set\u$1\u$2(

// format toArray
get(.*)\(
get\u$1(
```
