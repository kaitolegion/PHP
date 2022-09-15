## PHP
PHP Interactive shell

```text
php -a 
Interative shell

php >
```
Output hello kai
```text
php > echo 'hello kai';
hello kai
php >
```
The cli.prompt setting
```text
php > #cli.prompt=hello world  
hello world                    
hello world                    
hello world                    
```
PHP code executed in the prompt:
```text
php > #cli.prompt=`echo date('H:i:s');` php >
12:32:32 php >

```

## Executing code using the interactive shell
```text
php > echo 939+344;
1283
php >
```
PHP Executing Function
```text
php > function x($text)
php > {
php { return $text." kaito coding";
php { }
php > var_dump(x("hello"));
string(18) "hello kaito coding"
php >
```
