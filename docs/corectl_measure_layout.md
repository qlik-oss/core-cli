## corectl measure layout

Evaluate the layout of an generic measure

### Synopsis

Evaluate the layout of an generic measure and prints in JSON format

```
corectl measure layout <measure-id> [flags]
```

### Examples

```
corectl measure layout MEASURE-ID
```

### Options

```
  -h, --help   help for layout
```

### Options inherited from parent commands

```
  -a, --app string               App name, if no app is specified a session app is used instead
  -c, --config string            path/to/config.yml where parameters can be set instead of on the command line
  -e, --engine string            URL to the Qlik Associative Engine (default "localhost:9076")
      --headers stringToString   Http headers to use when connecting to Qlik Associative Engine (default [])
      --no-data                  Open app without data
  -t, --traffic                  Log JSON websocket traffic to stdout
      --ttl string               Qlik Associative Engine session time to live in seconds (default "30")
  -v, --verbose                  Log extra information
```

### SEE ALSO

* [corectl measure](corectl_measure.md)	 - Explore and manage measures
