# chessboard.js Change Log

All notable changes to this project will be documented in this file.

## [Unreleased]
- Orientation methods now return current orientation. [Issue #64]
- Drop support for IE8
- Do not check for `window.JSON`
- Rename `ChessBoard` to `Chessboard` (`ChessBoard` is still supported, however)
- id query selectors are now supported as the first argument to `Chessboard()`
- Remove Error #1001
- Remove Error #1002

## [0.3.0] - 2013-08-10
- Added `appearSpeed` animation config property
- Added `onSnapbackEnd` event
- Added `onMoveEnd` event

## [0.2.0] - 2013-08-05
- Added `onMouseoverSquare` and `onMouseoutSquare` events
- Added `onSnapEnd` event
- Added square code as CSS class on the squares
- Added [chess.js] integration examples

## [0.1.0] - 2013-05-21
- Initial release

[chess.js]:https://github.com/jhlywa/chess.js
[Issue #64]:https://github.com/oakmac/chessboardjs/issues/64