```
grunt demo
vim demo/index.html '+:source test.vim | wq!'
rm -rf docs
cp -R demo docs
```

For an http server in python3, run `(cd demo; python -m http.server)` then open `localhost:8000` in a web browser.
