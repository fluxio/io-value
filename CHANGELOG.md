## v1.0.1

Breaking Changes:

  - io-number and io-string are no longer supported. Users can use io-input with `type="float"` attribute instead.
  - 'io-value-set' event does not bubble anymore.

New Features:

  - Added tests and modular demo.

Improvements:

  - Removed dependency on behaviors.

Bugfixes:

  - Fixed CSS bug that caused io-object layout to break.
  - Fixed bug that caused error if setting disabled attribute before editor is ready.