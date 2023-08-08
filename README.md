# cryptospudz.github.io

To run locally -
```commandline
bundle exec jekyll serve --incremental
```

To run with local wifi access -
```commandline
bundle exec jekyll serve --incremental --host 0.0.0.0
```

And browse the local ip, eg -
```
http://192.168.1.18:4000
```

To trigger a [Github pages build](https://docs.github.com/en/rest/pages?apiVersion=2022-11-28#request-a-github-pages-build) -
```commandline
gh api \
  --method POST \
  -H "Accept: application/vnd.github+json" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  /repos/cryptospudz/cryptospudz.github.io/pages/builds
```
