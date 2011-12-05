This repo means we can now set up pages to show off our open source projects under __http://forward.github.com__. To do so, as in set up __http://forward.github.com/repo-name__, you need to create a separate branch called **gh-pages**.

    cd /path/to/repo-name
    git symbolic-ref HEAD refs/heads/gh-pages
    rm .git/index
    git clean -fdx
    echo "My GitHub Page" > index.html
    git add .
    git commit -a -m "First pages commit"
    git push origin gh-pages