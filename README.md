# SlotBox PCB Files and Documentation

## Merging and Branches
Since this is confusing, here are some tips for that.

## To update a branch
```
git checkout main
git pull main
git checkout <desired branch>
git merge main
git push
```

## To merge from a branch into main
```
git checkout <desired branch>
git pull
git checkout main
git merge <desired branch>
git push
```
