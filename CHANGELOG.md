## 1.0.1

* Fix: `JuneBuilder` now correctly forwards `_creator` as `init` to `Binder`, enabling `global: false` to work with externally-created `JuneState` instances (issue #8)
* Previously, passing a pre-existing instance via the creator function with `global: false` would throw a `BindError` because `BindElement` had no way to access the user-provided instance
* Resolves silent listener mismatch when the same state type was registered multiple times (e.g. across navigation), causing `setState()` to find no updaters

## 1.0.0

* Optimized memory usage efficiency 
* Add http instance example

Thanks to [allasca](https://github.com/allasca)

## 0.8.6

* Improve pub score
* Update License

Thanks to [curogom](https://github.com/curogom)