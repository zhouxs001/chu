/**前端静态页面热更新命令**/
cnpm install -g browser-sync
browser-sync start --server --files "*.html,**/*.css,**/*.js"

/**git命令**/
git add .
git commit -m 'change'
git push
git checkout master
git merge origin/index-swiper
git push