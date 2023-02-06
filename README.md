Steps to reproduce:

1. Install Wrangler: `npm i wrangler -g`
2. Login to Wrangler: `wrangler login`
3. Clone repo: `git clone https://github.com/rhino88/graphql-yoga-cloudflare-sofa-issue.git`
4. Change directory: `cd graphql-yoga-cloudflare-sofa-issue/`
5. Install dependencies: `npm i`
6. `wrangler publish` or `wrangler dev`

Error:

```
Uncaught ReferenceError: process is not defined\n' +
          '  at worker.js:19716:131\n' +
          '  at worker.js:20750:3\n' +
          ' [code: 10021]'
```
