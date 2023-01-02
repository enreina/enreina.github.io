# enreina.com

Personal blog. Published using Ghost CMS and the [ghost-static-site-generator](https://github.com/Fried-Chicken/ghost-static-site-generator).

To publish:
1. If not already, install [ghost](https://ghost.org/docs/install/local/) and [gssg](https://github.com/Fried-Chicken/ghost-static-site-generator))
2. Run ghost locally
```
ghost start
```
3. Update content using the admin panel which by default should be accessible from `http://localhost:2368/ghost/`
4. Publish and push to repo
```
# in root dir of this repo
gssg --url https://enreina.com --dest . 
git push master
```

