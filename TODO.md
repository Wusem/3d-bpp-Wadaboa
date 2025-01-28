# TODO

- [ ] Review superitems.
  - [x] Do not use horizontal superitems (like now).
  - [x] Remove objects that make up the horizontal superitem from the pool.
- [ ] Add feasibility check (procedural/constraint programming/machine learning) before placement cp
- [x] Final layer rearrangement by density.
- [x] (?) Review s-shaped: review case more than one layer in new bin

# Nice to have
- [ ] Add weight and density management
- [ ] Replace items removed during “select_layers” with unplaced items, using maxrects
  - [x] Temporary solution: “rearrange” with maxrects and re-iterate whole process with unplaced items
- [ ] Product support: spacing management as described in the paper
- [ ] Rotation management

