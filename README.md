# r9y.dev

here's the map! <https://jamesbrookbank-gcp.github.io/p18g-map/beck/map.html>

and the docs: <https://jamesbrookbank-gcp.github.io/p18g-map/docs/>

see something you want to fix?  want to contribute?:
- contact jamesbrookbank@ for now, under construction

not sure what to do?  write an issue!
- [file a p18g-map issue](https://https://github.com/jamesbrookbank-gcp/p18g-map/issues)

## Local Development

Want to run this locally?  You'll need to run the following commands:

```bash
bundle install
bash topics-to-index.sh
cd docs
bundle exec jekyll s --livereload -w
```

Now visit [http://localhost:4000/](http://localhost:4000/) in a browser.  When you make a change to a file, the browser should automatically reload that page!


### Making changes to the index

If you want to update the index page, you'll need to add your new topic to `topics.txt` and then run `bash topics-to-index.sh`.  This will regenerate the index file and you should see your link in the list.
