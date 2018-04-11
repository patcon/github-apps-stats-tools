# GitHub Apps: Statistics Tools

A place to store scripts/practices for a third-party understanding bot usage.

(This is just a readme for now, but will be more later.)


## Repos with vocal app installed

_Vocal:_ Participating in issue queue.

   http https://api.github.com/search/issues q=='commenter:app/stale' | jq --raw-output '.items[] | .repository_url' | cut -d'/' -f 5-6
