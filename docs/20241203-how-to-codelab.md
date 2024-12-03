summary: How to create a codelab in Github pages
id: 20241203-how-to-codelab
categories: Codelab, github pages
status: Published

# How to make a Codelab in Github Pages

## Introduction
This codelab describe the process that making codelab page in Github pages.

## Pre-requisites
In local machine, `brew` should be installed.

## Step 1: Install `go` and `claat`

### Install `go`:

```shell
brew install go
```

### Add `go` binary to `PATH`:

```shell
echo 'export PATH=$PATH:~/go/bin' >> ~/.zshrc
```
```shell
source ~/.zshrc
```

### Then , install `claat`:
```shell
go install github.com/googlecodelabs/tools/claat@latest
```

## Step 2: Do Something Else
Instructions for step 2.

