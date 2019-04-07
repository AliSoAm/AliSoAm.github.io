* run it localy:
```
docker run --rm --network=host -v $(pwd):/hugo registry.gitlab.com/pages/hugo:latest /bin/sh -c "cd /hugo; ls;hugo server --bind=0.0.0.0"
```
* generate site
```
docker run --rm --network=host -v $(pwd):/hugo registry.gitlab.com/pages/hugo:latest /bin/sh -c "cd /hugo; ls;hugo"
```
