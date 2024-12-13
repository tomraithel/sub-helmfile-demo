### Demo showcasing incorrect values templating for sub-helmfiles

To test, just run:

```
helmfile template
```

You should see an error, because the access to `.Values.foo` in `.values.yaml.gotmpl` does not work.
