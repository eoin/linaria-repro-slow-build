# linaria-repro-slow-build

This repros an issue with Linaria and/or Webpack resulting in slow builds. Repro as follows:

On main branch:

```
$ yarn && time yarn build
yarn build 1.66s user 0.14s system 88% cpu 2.032 total
```

On webpack5:

```
$ yarn && time yarn build
yarn build 16.68s user 0.87s system 103% cpu 16.979 total
```
