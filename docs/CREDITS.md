# 출처와 라이선스

## 캐릭터 모델

| 파일 | 원본 | 저작권·조건 |
|---|---|---|
| `models/a.vrm` | AvatarSample_A (VRoid Project, pixiv Inc.) | VRoidPreset A–Z 이용 조건: 누구나 영리 목적 포함 이용 가능, 크레딧 불필요, 편집본 재배포 가능. 모델·VRM 파일 자체를 유료로 재배포, CC0로 바꿔 배포, 캐릭터 제작 서비스로 쓰는 것은 금지 (https://vroid.pixiv.help/hc/en-us/articles/4402394424089-VRoidPreset-A-Z) |
| `models/b.vrm` | AvatarSample_B (VRoid Project, pixiv Inc.) | VRoidPreset A–Z 이용 조건: 누구나 영리 목적 포함 이용 가능, 크레딧 불필요, 편집본 재배포 가능. 모델·VRM 파일 자체를 유료로 재배포, CC0로 바꿔 배포, 캐릭터 제작 서비스로 쓰는 것은 금지 (https://vroid.pixiv.help/hc/en-us/articles/4402394424089-VRoidPreset-A-Z) |
| `models/c.vrm` | AvatarSample_C (VRoid Project, pixiv Inc.) | VRoidPreset A–Z 이용 조건: 누구나 영리 목적 포함 이용 가능, 크레딧 불필요, 편집본 재배포 가능. 모델·VRM 파일 자체를 유료로 재배포, CC0로 바꿔 배포, 캐릭터 제작 서비스로 쓰는 것은 금지 (https://vroid.pixiv.help/hc/en-us/articles/4402394424089-VRoidPreset-A-Z) |
| `models/d.vrm` | VRM1_Constraint_Twist_Sample (© 2022 pixiv Inc.) | VRM Public License 1.0: 재배포·개변·상업 이용 허용, 출처 표기 불필요 (https://vrm.dev/licenses/1.0/) |
| `models/e.vrm` | Seed-san (© VirtualCast, Inc.) | VRM Public License 1.0: 재배포·개변·상업 이용 허용, **출처 표기 필요** (https://vrm.dev/licenses/1.0/) |
| `models/f.vrm` | ニコニ立体ちゃん (Alicia Solid) (©dwango, inc.) | 개인(법인 제외 단체 포함)은 비영리·영리 모두 이용 가능, 개변물 배포 가능, 크레딧 표기 불필요. 폭력·반사회적 용도, 캐릭터 명예·품위 훼손, 공식 상품 오인 이용 금지. 법인 이용은 불가 (https://3d.nicovideo.jp/alicia/rule.html) |

모든 모델은 게임 용량을 줄이려고 텍스처를 최대 1024px로 줄였고, 게임 안에서 머리·눈·옷 색을 바꿔 표시합니다.

**주의:** 니코니 입체짱(f.vrm)은 "캐릭터의 명예·품위를 훼손하는 이용"을 금지합니다. 이 게임에서는 어떤 캐릭터든 무작위로 부정행위자가 될 수 있으므로, 공개 배포 전에 이 조항에 걸리지 않는지 판단하세요. 걱정되면 models/f.vrm을 빼고 index.html의 MODELS 목록에서도 지우면 됩니다. 법인 명의로 배포한다면 반드시 빼야 합니다.

**주의:** AvatarSample A·B·C의 VRM 파일이 게임 파일에 들어 있으므로, 게임 자체를 유료로 판매하면 "모델 파일을 유료로 재배포"하는 것으로 볼 여지가 있습니다. 무료 배포는 문제없습니다. 유료 판매 전에는 이 세 모델을 직접 만든 모델로 교체하세요.

## 라이브러리
- three.js 0.160.0, MIT License (`lib/LICENSE-three.txt`)
- @pixiv/three-vrm 3.1.0, MIT License (`lib/LICENSE-three-vrm.txt`)

## 글꼴
Black Han Sans, Noto Sans KR, IBM Plex Mono (Google Fonts, SIL Open Font License)
