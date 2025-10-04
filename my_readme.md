
### run build (OOM -> increase node memory)
`NODE_OPTIONS="--max-old-space-size=8192" npm run build`

then normal
`npm run dev`

run backend 
`cd backend`
`sh dev.sh`

thesis start tag created
`git tag v-thesis-start`
`git push origin v-thesis-start`
✅ Once that tag is on GitHub, you’ll always be able to come back to this exact working state (git checkout v-thesis-start).
