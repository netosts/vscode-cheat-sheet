# Cheat Sheet for VSCODE

## Regex
### Format PHP Getters and Setters + toArray method, to follow psr-4 rules:
```
// format Getters
get(.*)_(.*)\(
get\u$1\u$2(

get([A-Za-z]+)_([A-Za-z]+)(?:_id)?\(
get\u$1\u$2(

// format Setters
set(.*)_(.*)\(
set\u$1\u$2(

set([A-Za-z]+)_([A-Za-z]+)(?:_id)?\(
set\u$1\u$2(

// format toArray
get(.*)\(
get\u$1(
```
