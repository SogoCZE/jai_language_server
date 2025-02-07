# TODO

## 0.3.0
- [ ] support for context
- [ ] goto and autocomplete for struct literals
- [ ] improve context based autocomplete
- [ ] polymorphic types
- [ ] ...

## 0.2.0
- [x] Array, String completions (data, count)
- [x] Do not autocomplete when the full path was not resolved
- [x] Array Subscript
- [x] Deprecated procedures
- [x] Port stuff from completions to go to definition
- [x] Fix enums completions
- [x] Aliased/prefixed modules (`Math :: #import "Math";`)
- [x] Fix goto and completions for procedure calls inside aliased module (`Math.make_matrix4().`)
- [x] Fix signature help with procedures in aliased module or struct
- [x] Autocomplete `it`, `it_index` in loops
- [x] Autocomplete custom loops values (`for name, name_index: names`)
- [x] Support for infered enum values (Go To Definition and autocomplete)
- [-] Fix the problem with incomplete binary operation joining with content on next line (is this even solvable?)
- [-] Fix broken completions for local variables across some boundaries like if-switch
- [-] Using
    - [-] Structs, Enums, Unions
    - [ ] Global scope
    - [ ] Local scope
    - [ ] Modifiers (`except`, `only`, `map`)
    - [x] Unwrap #as
    - [ ] Modules (`using Math :: #import "Math";`)
- [ ] Make root detection more robust - it should work quite well even without `jails.json` and it also shoudl work with multiple entry points.
- [ ] Implement basic procedure overload resolution
- [ ] Autocomplete deref on pointer (`entity.*`)
- [ ] Support for compound declaration (`x,y,z: float;`)
- [ ] Autocomplete buildin procedures (`size_of`, `type_of` ...)
- [ ] Mason registry (nvim)
- [ ] Implement "fake" methods completions for types that are taken as the first argument of some procedures
- [ ] Improve Linux and nvim support

