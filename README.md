# ACE COMBAT 8 Shadows 저장 도구

## 사용 방법

1. 게임을 완전히 종료하고 Steam Cloud 동기화를 끕니다.
2. `Start AC8 Shadows Save Tool.cmd`를 실행합니다.
3. 도구가 기본 경로의 `Campaign.sav`을 찾으면 `21004001 적용`을 누릅니다.
4. 확인 창에서 동의하면 도구가 백업을 만든 뒤 세이브에 적용합니다.

기본 경로는 `%LOCALAPPDATA%\BANDAI NAMCO Entertainment\ACE COMBAT 8\Saved\SaveGames\Campaign.sav`입니다. 도구는 그 파일이 GVAS 형식이고 체크섬이 유효한지 먼저 확인합니다. 지원하지 않는 파일이면 변경하지 않습니다.

변경 전 원본은 같은 폴더에 `Campaign.sav.backup_날짜_시간` 형식으로 보관합니다. `21004001`이 이미 있으면 파일을 바꾸지 않습니다. 패치는 `UnlockedSkinIdList`에 해당 ID 하나를 추가하고, 필요한 배열 크기와 체크섬만 갱신합니다.

문제가 생기면 게임을 종료한 상태에서 백업 파일을 `Campaign.sav`으로 복원하세요. Steam Cloud는 복원 확인이 끝날 때까지 꺼 두세요.


# ACE COMBAT 8 Shadows Save Tool

## How to Use

1. Close the game completely and disable Steam Cloud synchronization.
2. Run `Start AC8 Shadows Save Tool.cmd`.
3. Once the tool detects `Campaign.sav` at the default location, click "Apply 21004001."
4. Confirm your choice in the prompt; the tool will then create a backup and apply the changes to your save file.

The default file path is `%LOCALAPPDATA%\BANDAI NAMCO Entertainment\ACE COMBAT 8\Saved\SaveGames\Campaign.sav`. The tool first verifies that the file is in GVAS format and contains a valid checksum. If the file is unsupported, no changes will be made.

A backup of the original file will be saved in the same folder, named `Campaign.sav.backup_Date_Time`. If `21004001` is already present, the file will not be modified. The patch adds the specified ID to the `UnlockedSkinIdList` and updates the array size and checksum accordingly.

If any issues arise, close the game and restore your save by renaming the backup file back to `Campaign.sav`. Keep Steam Cloud disabled until you have verified that the restoration was successful.
