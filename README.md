Protractor Parallel test runner
-------------------------------

Will run any number of protractor suites in parallel

```bash
protractor-parallel pctr.conf.js test/someSuite.js test/suites/*{.*/*}.js
```

Each instance will run in a separate browser. If any test fails, the runner
will exit with an exit code other than zero.
