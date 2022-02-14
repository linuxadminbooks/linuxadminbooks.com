# linuxadminbooks.com
[![github pages](https://github.com/linuxadminbooks/linuxadminbooks.com/actions/workflows/gh-pages.yaml/badge.svg?branch=main)](https://github.com/linuxadminbooks/linuxadminbooks.com/actions/workflows/gh-pages.yaml)

Repo and source for [linuxadminbooks.com](https://linuxadminbooks.com)

## What
* Hugo
* Markdown

## How

1. [Install Hugo](https://gohugo.io/getting-started/installing/)
1. check w/ `hugo` in this repo
   ```
   :! hugo
   Start building sites …
   hugo v0.87.0-B0C541E4+extended linux/amd64 BuildDate=2021-08-03T10:57:28Z VendorInfo=gohugoio

                      | EN
   -------------------+-----
     Pages            | 10
     Paginator pages  |  0
     Non-page files   |  0
     Static files     | 78
     Processed images |  0
     Aliases          |  2
     Sitemaps         |  1
     Cleaned          |  0

   Total in 60 ms
   ```

1. Download theme and other mods:
   ```
   hugo mod get -u
   ```

1. Add content with `hugo add docs/myfolder/something.md`
1. Change frontmatter to change from a draft or use --buildDrafts when running hugo server
1. Run live server to view
   ```
   hugo server --minify
   ```



## License
   MIT, The Linux Admin Books Authors
   



Emails should have stamps
