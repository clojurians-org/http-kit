# HTTP Kit

### A high-performance event-driven HTTP client+server for Clojure

[CHANGELOG](https://github.com/http-kit/http-kit/blob/master/history.md) | Current [semantic](http://semver.org/) version/s:

```clojure
[http-kit "2.1.19"]       ; Last release published by @shenfeng
[http-kit "2.2.0-alpha1"] ; Dev release, published by contributors
```

[![Build Status](https://travis-ci.org/http-kit/http-kit.svg?branch=master)](https://travis-ci.org/http-kit/http-kit)

See [http-kit.org](http://http-kit.org) for documentation, examples, benchmarks, etc. (may be a little out of date).

## Project status

http-kit's author ([@shenfeng]) unfortunately hasn't had much time to maintain http-kit recently. To help out I'll be doing basic issue triage, accepting minor/obvious PRs, etc.

A big thank you to the **[current contributors](https://github.com/http-kit/http-kit/graphs/contributors)** for keeping the project going! **Additional contributors welcome**: please ping me if you'd be interested in lending a hand.

\- [@ptaoussanis]

### Hack locally

Hacker friendly: zero dependencies, written from the ground-up with only ~3.5k lines of code (including java), clean and tidy.

```sh
# Modify as you want, unit tests back you up:
lein test

# May be useful (more info), see `server_test.clj`:
./scripts/start_test_server

# Some numbers on how fast can http-kit's client can run:
lein test :benchmark
```

### Contact & Contribution

Please use the [GitHub issues page](https://github.com/http-kit/http-kit/issues) for feature suggestions, bug reports, or general discussions. Current contributors are listed [here](https://github.com/http-kit/http-kit/graphs/contributors). The http-kit.org website is also on GitHub [here](https://github.com/http-kit/http-kit.github.com).

### License

Copyright &copy; 2012-2016 [Feng Shen](http://shenfeng.me/). Distributed under the [Apache License Version 2.0](http://www.apache.org/licenses/LICENSE-2.0.html).

[@shenfeng]: https://github.com/shenfeng
[@ptaoussanis]: https://github.com/ptaoussanis