# Create NPM Package Notes
---

### Publish package for name started with "@" 
By default, package name started with "@" will be treated as a private package, but if `npm publish` command adds option `--access public`, the package will be changed to public. 
```
npm publish --access public
```
