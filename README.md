# git-graph

```
git log --graph --oneline --decorate
```

## One commit

```
*
```

## Two commits

```
*
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
