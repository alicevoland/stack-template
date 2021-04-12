# stack-template
Web stack template with 2 git submodules

## Git submodules

How to create a repo with "sub repos" (submodules):

1. Create the main repo (e.g. stack-template)
2. Create the sub repos (e.g. *-back and *-front)
3. Add the sub repos as git submodules

```bash
git clone git@github.com:mvoland/stack-template.git
cd stack-template

git submodule add git@github.com:mvoland/stack-template-back.git
git submodule add git@github.com:mvoland/stack-template-front.git
```
