# nextnotes
Next 13 tutorial to discover changes between versions
Tutorial Video URL: https://www.youtube.com/watch?v=__mSgDEOyv8&amp;t=403s

1) NVM install 18.11
2) NVM use 18.11
3) Create a new Next.js app: npx create-next-app@13 --ts
4) Download Pocketbase from pocketbase.io
5) Navigate to the unzipped directory cd pocketbase_0.7.9_darwin_arm64
6) Start Pocketbase: ./pocketbase serve [if you get the error on mac, follow these instructions: https://www.reddit.com/r/pocketbase/comments/ypcsqh/need_help_pocketbase_executable_wont_run_on_an_m1/]
7) Open the Admin UI, create collection, and update security rules to allow read/write access.
8) Add experimental: { appDir: true } to next.config.js
