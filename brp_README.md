Addendum to the course readme:

1. The following repo contains brp-optics' responses to the homework problems. 
In order to simplify merging the upstream into the repo, solutions will be merged into `main`.

2. Homework problems will be worked in python and in julia.

3. Solutions will be pushed back into my public fork of the repo *after* the main repo commits solutions,
 to avoid spoiling solutions for the class.

To merge from upstream:

```bash
   git fetch upstream
   git merge upstream/main
```

To push to private"

```
git push private
```


To push up to a certain date:

```bash
git push origin $(git log --before="2025-01-01" -1 --format="%H"):main
```

## Initialization log

```bash
git clone https://github.com/brp-optics/stat_rethinking_2026_private
git remote add upstream https://github.com/rmcelreath/stat_rethinking_2026
git remote add private https://github.com/brp-optics/stat_rethinking_2026_private
```

