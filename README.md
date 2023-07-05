1. `npm install`
2. `npx nx reset && rm -rf dist`
3. `nx run shop-e2e:e2e:ci`
4. you should have a dist folder with a recorded video
5. remove the dist folder, but keep the cache: `rm -rf dist`
6. run the cmd again: `nx run shop-e2e:e2e:ci`
  - it should now finish instantly, and you should have the recorded video back in dist
