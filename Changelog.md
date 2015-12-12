Changelog
=========

Current master
--------------

- Transitioned podspec to new remote URL (see [#15](https://github.com/RxSwiftCommunity/Action/issues/15)).

1.0.0
-----

- Unbounded replaying of event values (see [#3](https://github.com/ashfurrow/Action/issues/3)).

0.3.0
-----

Added `UIAlertAction` support.

0.2.1
-----

- Fixes `enabledIf:` parameter to be `Observable<B>`, `where B: BooleanType`. 

0.2.0
-----

- Added tvOS support to UIButton extension.
- Changes `enabledIf` to accept `Observable<BooleanType>` instead of `Bool`.

0.1.0
-----

- Initial release.
