### cc-tree-walk

#### install packages
```
npm install cc-tree-walk --save
```

#### e.g. walk a tree
```javascripts
import treeWalk from "cc-tree-walk";

const tree = {
  active: false,
  children: [
    {active: false}
  ]
};

treeWalk(tree, item => {
  item.active = false;
});
```
