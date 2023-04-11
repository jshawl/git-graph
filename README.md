# git-graph

```
git log --graph --oneline --decorate
```

## One commit

```
* (main)
```

## Two commits

```
* (main)
|
*
```

## One Branch

```
* (branch-a)
|
| * (main)
|/
*
|
*
```

## Two Branches

```
* (branch-b)
|
| * (branch-a)
|/
| * (main)
|/
*
|
*
```

## One Merge

```
* (main)
|\
| * (branch-a)
| |
* |
|/
| * (branch-b)
|/
*
|
*
```

## Two Merges

```
* (main)
|\
| * (branch-b)
| |
* |
|\ \
| * | (branch-a)
| |/
* /
|/
*
|
*
```
