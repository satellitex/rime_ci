# rime_ci
[![CircleCI](https://circleci.com/gh/satellitex/rime_ci/tree/master.svg?style=svg)](https://circleci.com/gh/satellitex/rime_ci/tree/master)
Pushするたびに、 `PROBLEM` を持つディレクトリをrime testします。

## How to Use
1. `test_rime_project` を参考にしてください。
2. `all-test.sh` を `PROJECT` のあるディレクトリに起きます。
3. `.circleci` を git directory の root に起きます。
4. `.circleci/config.yml` で `all-test.sh` を呼び出すところをいい感じに変えます。

## 疑問
これの Ci 落ちてるのは、落ちてるケースをやっているから