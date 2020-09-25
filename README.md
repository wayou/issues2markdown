# issues2markdown

Export github issues into markdown files, then using them as jekyll posts.

## usage

- clone repo
- `yarn`
- `echo <github personal token> >> token.ts`
- edit [issues.ts](./issues.ts) replace `REPO` and `OWNER`
- `yarn load`

if everything goes well, files will be created at `_posts` directory.



