# claude_something

## Content Abdication (만족스러운 은퇴) — Crusader Kings III 모드

결정(Decision) 하나를 추가합니다. 실행하면:

1. 본인에게 **만족(Content)** 트레잇을 붙입니다. (반대 트레잇인 *야심*이 있으면 먼저 제거)
2. 보유한 **금화 전부**를 후계자에게 넘깁니다.
3. 보유한 **아티팩트 전부**를 후계자에게 넘깁니다.
4. **퇴위**(`depose`)합니다. 모든 작위가 계승법에 따라 후계자에게 넘어가고, 후계자로 이어서 플레이합니다.

### 조건
- 영지를 가진 통치자여야 함
- 주 후계자(primary heir)가 있고, **같은 가문**이어야 함 (다른 가문이면 게임 오버가 되므로 막아둠)
- 투옥 상태가 아니고 행동 가능한 상태여야 함
- AI는 이 결정을 사용하지 않음

모드 파일은 모두 `ck3_content_abdication/` 폴더 안에 있습니다.

### 설치
`ck3_content_abdication/` 폴더 **안에 있는** 다음 두 개를 `Documents/Paradox Interactive/Crusader Kings III/mod/` 폴더에 복사합니다.

```
mod/
├── content_abdication.mod
└── content_abdication/
    ├── descriptor.mod
    ├── common/decisions/content_abdication_decisions.txt
    └── localization/{english,korean}/...
```

그 후 런처의 플레이셋에서 모드를 켭니다. 런처가 버전 경고를 띄우면 `supported_version`을 현재 게임 버전(예: `"1.16.*"`)으로 바꾸세요.
