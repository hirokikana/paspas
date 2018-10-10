paspas
====

## Description
paspas is simple password generator for CLI.

## Install

```
pip install paspas
```

## Usage
```
$ paspas help
```

```
$ paspas --site=google --user=bob --master=secret
```

site settings is yaml format. setting save to `~/.paspas` .
```
google:
 max_length: 30
 unavailable_char: !@#
```

```
--master=master_password, -m master password
```