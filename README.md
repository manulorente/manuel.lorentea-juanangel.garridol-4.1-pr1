# DevOps-P01

## Tips

### Install git flow on Ubuntu

```bash
sudo apt-get install git-flow
```

### Initialize git flow

```bash
git flow init -d
```

### Create a new release

```bash
git flow release start <release_name>
```

### Create a new feature

```bash
git flow feature start <feature_name>
```

### Create a new hotfix

```bash
git flow hotfix start <hotfix_name>
```

### Create a new bugfix

```bash
git flow bugfix start <bugfix_name>
```

### Finish a release

```bash
git flow release finish -k <release_name>
```

### Finish a feature

```bash
git flow feature finish <feature_name>
```

### Finish a hotfix

```bash
git flow hotfix finish <hotfix_name>
```

### Push the changes

```bash
git push --all
```  

or

```bash
git push origin develop
git push origin main --tags
```
