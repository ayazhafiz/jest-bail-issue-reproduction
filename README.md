Expected:

```
rm -f out.json
node_modules/.bin/jest --json --output-file out.json
file out.json # OKAY
```

```
rm -f out.json
node_modules/.bin/jest --json --output-file out.json --bail
file out.json # FAIL
```
