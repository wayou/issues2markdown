# issues2markdown

Export github issues into markdown files, then using them as jekyll posts.

## usage

- clone repo
- `yarn`
- create a file with name of `token.ts` with the following content

```ts
export const TOKEN = "<your github personal token>";
```

- edit [issues.ts](./issues.ts) replace `REPO` and `OWNER`
- `yarn load`

if everything goes well, files will be created at `_posts` directory.
