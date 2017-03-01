# jsoncat
Pretty Simple JSON Formatter Command. There are many kinds of jsoncat developed with many kinds of programming languages (see [Github](https://github.com/search?q=jsoncat)). This is a shell version.

## Usage
You get json from a pipe to stdin like this:

```
curl -s http://unofficialism.info/test/test.json | jsoncat
```
```
{
    "array": [
        1,
        2,
        3
    ],
    "boolean": true,
    "number": 123,
    "object": {
        "a": "b",
        "c": "d"
    },
    "string": "Hello World"
}
```

Or you can simply get as a json file like this:

```
jsoncat | test.json 
```


