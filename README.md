# Git-Handson-Asciidoc

## How to build

### html

```
$ bundle install --path vendor/bundle
$ bundle exec asciidoctor git-handson.adoc
$ bundle exec asciidoctor git-handson2.adoc
$ bundle exec asciidoctor git-handson3.adoc
```

### pdf

```
$ bundle install --path vendor/bundle
$ bundle exec asciidoctor-pdf git-handson.adoc  -r asciidoctor-pdf-cjk
$ bundle exec asciidoctor-pdf git-handson2.adoc -r asciidoctor-pdf-cjk
$ bundle exec asciidoctor-pdf git-handson3.adoc -r asciidoctor-pdf-cjk
```

## index

- [Git Handson](git-handson.adoc)
- [なんにんかで作業するためのハンズオン](git-handson2.adoc)
- [Git でやり直す方法](git-handson3.adoc)