### Setup
Install haml-lint:
```
bundle install
```

Run haml-lint against the example file
```
bundle exec haml-lint
```

### Expected output
```
$ bundle exec haml-lint

1 file inspected, 0 lints detected
```

### Actual output
```
$ bundle exec haml-lint
example.html.haml:1 [W] RuboCop: Layout/LineLength: Line is too long. [132/120]

1 file inspected, 1 lint detected
```
