# GROMY


<p align="center"><img width="80%" src="Gromy.png" alt="Grmoy"/></p>


## What?
So by default chrom(ium) bookmarks are oldest on the top. Well that sucks. I dont want to install yet another extension. Hence **gromy** was born.

## Install

`go get github.com/mintyowl/gromy`

`dep ensure`

## Usage

Flag | Action
--- | ---
-loc | Full path to the google-chrom(ium) bookmark json file
-gc | switches to "Google Chrome" instead of the default "Chromium"
-order | Sort by oldest/latest
-y | bypass the prompt completely
-restore | Restore old backups by date

## Help
`gromy -h`