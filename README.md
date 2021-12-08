# PL/Mustache

A simple PL/SQL implementation of the [Mustache templating language](https://mustache.github.io).

## Usage

``` plsql
declare
   l_hash clob;
   l_template clob;
begin
   l_hash := '{ name:world }';
   l_template := 'Hello {{name}}!';
   dbms_output.put_line(plmustache.render(l_hash, l_template));
end;
```

## Coverage

The following features have been implimented from the [language documented here](https://mustache.github.io/mustache.5.html).

### Variables

*Not yet implememnted.*

### Sections

*Not yet implememnted.*

### Lambdas

This is not planned to be implemented.

### Non-False Values

*Not yet implememnted.*

### Inverted Sections

*Not yet implememnted.*

### Comments

*Not yet implememnted.*

### Partials

*Not yet implememnted.*

### Set Delimiter

*Not yet implememnted.*
