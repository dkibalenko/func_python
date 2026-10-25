# Progress

## Foundations

### Variables & memory
- [x] Variables are memory references
- [x] Reference counting
- [x] Garbage collection
- [x] Dynamic vs static typing
- [x] Variable re-assignment
- [x] Object mutability
- [x] Function arguments and mutability
- [x] Shared references and mutability
- [x] Variable equality (`is` vs `==`)
- [x] Everything is an object
- [x] Interning (integers and strings)
- [x] Peephole optimisations

### Function parameters
- [x] Positional arguments
- [x] Unpacking iterables and extended unpacking
- [x] `*args`
- [x] Keyword arguments
- [x] `**kwargs`
- [x] Putting it all together
- [x] A simple function timer
- [x] Default values — mutable-default pitfalls
- [x] Sentinel values for parameter defaults
- [x] Naming `*args` / `**kwargs` deliberately

## Functional programming

### Phase 1 — Core concepts
- [ ] Pure functions and the purity test
- [ ] Side effects — taxonomy, when acceptable
- [ ] Immutability in Python
- [ ] Referential transparency
- [ ] First-class functions
- [ ] Higher-order functions

### Phase 2 — Built-ins
- [ ] `lambda` — when to use vs `def`
- [ ] `map()`, `filter()`, `zip()`
- [ ] `sorted()` with `key=`
- [ ] Comprehensions and generator expressions as FP
- [ ] `any()`, `all()`

### Phase 3 — Closures as FP tools
- [ ] Function factories
- [ ] Encapsulation without classes
- [ ] Stateful closures (counter, accumulator)

### Phase 4 — `functools`
- [ ] `partial`
- [ ] `reduce`
- [ ] `lru_cache` / `cache`
- [ ] `singledispatch`
- [ ] `total_ordering`
- [ ] `cached_property`

### Phase 5 — `itertools`
- [ ] Infinite: `count`, `cycle`, `repeat`
- [ ] Finite: `chain`, `islice`, `takewhile`, `dropwhile`, `groupby`, `starmap`, `pairwise`
- [ ] Combinatoric: `product`, `permutations`, `combinations`

### Phase 6 — `operator`
- [ ] `itemgetter`, `attrgetter`, `methodcaller`

### Phase 7 — Advanced patterns
- [ ] Function composition and pipelines
- [ ] Currying
- [ ] Lazy generator pipelines
- [ ] Decorators as HOFs
- [ ] Tail recursion and Python's limits
- [ ] When *not* to use FP
