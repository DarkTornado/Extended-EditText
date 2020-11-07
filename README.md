# Extended EditText
© 2020 Dark Tornado, All rights reserved.

## Summary / 요약
* Extended EditText for Android.
* 안드로이드의 EditText를 확장시킨거에요.


## Added Constant / 추가된 상수

#### static int DIR_LEFT
* Static constant for moveCursor(); Value is `-1`
* moveCursor(); 메소드에 사용되는 상수. 값은 `-1`.

#### static int DIR_RIGHT
* Static constant for moveCursor(); Value is `1`
* moveCursor(); 메소드에 사용되는 상수. 값은 `1`.


## Added Methods /  함수

#### boolean undo();
* Execute undo.
* 되돌리기 실행.

#### boolean redo();
* Cancel undo.
* 되돌리기 취소.

#### void moveCursor(int dir);
* Move cursor in EditText.
* EditText 내부에서 커서 이동.

#### void insertWord(String word);
* Input word where cursor exists.
* 현재 커서의 위치에 해당 문구 추가.

#### void clearHistory();
* Remove history for undo and redo.
* 되돌리기 및 되돌리기 취소에 사용되는 수정 기록 삭제.

