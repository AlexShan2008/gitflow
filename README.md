# A Repo to Learn How to Use Gitflow

## Install command tool

```sh
brew install git-flow
```

## Gitflow init

```sh
cd /root
git-flow init
```

## select the default option

```sh
$ git flow init Initialized empty Git repository in ~/project/.git/ No branches exist yet. Base branches must be created now. Branch name for production releases: [master] Branch name for "next release" development: [develop]
 How to name your supporting branch prefixes? Feature branches? [feature/] Release branches? [release/] Hotfix branches? [hotfix/] Support branches? [support/] Version tag prefix? []
 $ git branch * develop  master
```

## Creating a feature branch

```sh
git flow feature start feature_branch
```

## Finishing a feature branch

```sh
git flow feature finish feature_branch
```

## Release Branches

```sh
git flow release start 0.1.0 Switched to a new branch 'release/0.1.0'
```
