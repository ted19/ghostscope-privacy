# GHOST SCOPE — Privacy Policy / 개인정보처리방침

**[English](#english) · [한국어](#한국어)**

App: **GHOST SCOPE: Ghost Camera & Box** (`com.dalcomsoft.ghost`)
Last updated / 최종 수정일: **1 September 2026**

---

## English

### Summary

GHOST SCOPE has no account system and no analytics. We operate no servers and
receive nothing from the app. Nothing it records — camera frames, coordinates,
photos, or saved sessions — is ever sent anywhere by us.

The app can read your device's location, but only if you allow it. Location is
shown on screen and kept on your device with the records you choose to save.

The app includes Google's AdMob advertising library. **Advertising is switched
off in the current version, no ads are shown, and the library is not started.**
If that changes in a future version, this policy will be updated before it
ships and the section below will describe what AdMob does.

### The app in one line

GHOST SCOPE analyses the live camera image for motion and unusual patterns and
draws what it finds on screen, and generates a radio-scan style soundscape. It
is an entertainment app. It does not detect ghosts or any paranormal
phenomenon.

### What we collect

**Nothing.** We operate no servers and receive no data from the app. There is
no way for us to identify you or your device. Everything described below stays
on your device.

### Camera

The app requests the `CAMERA` permission because analysing the camera image is
its main function.

- Camera frames are processed in memory on your device and discarded
  immediately.
- Frames are never written to storage, never uploaded, and never shared.
- The Ghost Box mode does not use the camera at all and never asks for the
  permission.

You can revoke camera access at any time in the Android system settings. The
Ghost Box will keep working; the camera features will not.

### Location

The app declares `ACCESS_FINE_LOCATION` and `ACCESS_COARSE_LOCATION`. Both are
**optional**.

- The app asks for location only when you tap the coordinate line on the Ghost
  Camera or Ghost Box screen. It does not ask on first launch.
- Location is read only while one of those screens is open. The app never reads
  your location in the background.
- It is used for two things: showing the coordinates on screen, and storing
  them with records you choose to save.
- Coordinates are read through Android's own location service. GHOST SCOPE
  never transmits them. They go to the screen and, if you save a record, to the
  app's own storage on your device.
- **If you decline, both features work exactly as before.** Records are simply
  saved without coordinates.

You can revoke location access at any time in the Android system settings.

### Photos you choose to save

When you press the capture button, the app saves a single image to your
device's own photo gallery, under `Pictures/Ghost`. This happens only when you
press that button. The image stays on your device and is yours to keep, share,
or delete. The app does not read your existing photos.

**Coordinates inside the photo file.** If you have allowed location and left
*Include location in photos* switched on (it is on by default, in Settings),
the coordinates are written into the photo's own EXIF metadata. That means if
you send the photo to someone, the place it was taken travels with it. Switch
that setting off to keep saved photos free of coordinates — records inside the
app keep their coordinates either way.

### Records kept on your device

The Records screen lists photos you captured and Ghost Box sessions you chose
to save. Each entry holds the time, the coordinates if there were any, and —
for a session — the words that were spoken.

- This list lives in the app's own private storage. Other apps cannot read it.
- It is removed when you uninstall the app.
- You can delete any entry, or all of them, from the Records screen. Deleting
  an entry does not delete the photo from your gallery.

### Settings stored on your device

The app stores a few small values in its own private storage: whether you have
seen the introduction screen, your chosen detection sensitivity, the Ghost Box
scan speed and volume, and whether to include location in saved photos. These
never leave your device and are removed when you uninstall the app.

### Speech synthesis

The Ghost Box speaks short word fragments. To produce them, the app asks the
text-to-speech engine already installed on your device to synthesise a fixed
list of ordinary words, and caches the resulting audio in its own private
storage. The word list is built into the app and does not change based on
anything you do.

The text-to-speech engine is separate software provided by your device
manufacturer or by Google, and it is governed by its own privacy policy. Some
engines synthesise speech over the network. GHOST SCOPE sends it only the fixed
word list built into the app — nothing about you, and nothing you typed — but we
cannot control how a separate speech engine behaves. If this concerns you, use
an offline voice or do not use the Ghost Box.

### Advertising

The app includes Google's AdMob library so that advertising can be enabled in a
later version without rebuilding the app from scratch.

**In this version advertising is off.** No ad is requested, no ad is displayed,
and the AdMob library is never started — its automatic start-up component is
removed from the app at build time, not merely skipped at runtime.

If advertising is switched on in a future version, that version's policy will
say so plainly. AdMob would then receive your device's advertising ID and
technical information about your device in order to select ads, under
[Google's own privacy policy](https://policies.google.com/privacy). We would
still receive nothing ourselves.

### Network access

The app holds the `INTERNET` and `ACCESS_NETWORK_STATE` permissions because the
bundled AdMob library requires them. **GHOST SCOPE does not use them.** It
sends no camera frames, no coordinates, no photos, and no saved records — there
is no server for them to go to.

The app asks the Google Play Store app — separate software already on your
device — whether a newer version of GHOST SCOPE exists, so it can tell you to
update. GHOST SCOPE itself makes no network connection for this; the Play Store
app does that work, under Google's own privacy policy.

The app contains no analytics library and no crash reporting library.

Permissions the app declares:

| Permission | Why |
| --- | --- |
| `CAMERA` | Required. Analysing the camera image is the main function. |
| `ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION` | Optional. Coordinates on screen and in records. |
| `INTERNET`, `ACCESS_NETWORK_STATE` | Required by the bundled AdMob library. Unused while advertising is off. |
| `AD_ID`, `ACCESS_ADSERVICES_*`, `FOREGROUND_SERVICE`, `WAKE_LOCK` | Added by the AdMob library. Unused while advertising is off. |

### Children

The app is intended for a general audience and is not directed at children. It
collects no data from anyone, including children.

### Changes to this policy

If this policy changes, the updated text will be published at this address and
the date above will be revised.

### Contact

For questions about this policy, please use the developer contact details
shown on the Google Play listing for GHOST SCOPE.

---

## 한국어

### 요약

GHOST SCOPE는 계정 기능과 분석 도구가 없습니다. 저희는 서버를 운영하지 않으며
앱으로부터 어떤 데이터도 받지 않습니다. 앱이 기록하는 것 - 카메라 프레임,
좌표, 사진, 저장한 세션 - 은 저희에게 전송되지 않습니다.

앱은 사용자가 허용한 경우에 한해 기기의 위치를 읽습니다. 위치는 화면에
표시되고, 사용자가 저장한 기록과 함께 기기 안에 보관됩니다.

앱에는 Google AdMob 광고 라이브러리가 포함되어 있습니다. **현재 버전에서는
광고가 꺼져 있어 광고가 표시되지 않으며, 라이브러리가 시작되지도 않습니다.**
향후 버전에서 이것이 바뀐다면 배포 전에 이 방침을 먼저 갱신하고, 아래 항목에
AdMob이 무엇을 하는지 설명합니다.

### 앱 소개

GHOST SCOPE는 카메라 영상에서 움직임과 이상 패턴을 실시간으로 분석해 화면에
표시하고, 라디오 스캔을 모사한 소리를 생성합니다. 엔터테인먼트 목적의
앱이며, 유령이나 초자연 현상을 탐지하지 않습니다.

### 수집하는 정보

**없습니다.** 저희는 서버를 운영하지 않으며 앱으로부터 어떤 데이터도 받지
않습니다. 사용자나 기기를 식별할 수 있는 수단이 없습니다. 아래에 설명하는
모든 것은 사용자 기기 안에만 남습니다.

### 카메라

영상 분석이 이 앱의 핵심 기능이므로 `CAMERA` 권한을 요청합니다.

- 카메라 프레임은 기기 메모리에서 처리된 뒤 즉시 폐기됩니다.
- 저장하거나 업로드하거나 공유하지 않습니다.
- 고스트 박스 모드는 카메라를 전혀 사용하지 않으며 권한을 요청하지도
  않습니다.

안드로이드 시스템 설정에서 언제든 카메라 권한을 회수할 수 있습니다. 고스트
박스는 계속 사용할 수 있고, 카메라 기능만 동작하지 않습니다.

### 위치

앱은 `ACCESS_FINE_LOCATION`과 `ACCESS_COARSE_LOCATION`을 선언합니다. 두 권한
모두 **선택 사항**입니다.

- 고스트 카메라 또는 고스트 박스 화면에서 좌표 자리를 눌렀을 때만 위치
  권한을 요청합니다. 첫 실행 시에는 묻지 않습니다.
- 위치는 해당 화면이 열려 있는 동안에만 읽습니다. 백그라운드에서는 절대
  읽지 않습니다.
- 두 가지 용도로만 씁니다. 화면에 좌표를 표시하는 것과, 사용자가 저장한
  기록에 좌표를 함께 남기는 것입니다.
- 좌표는 안드로이드의 위치 서비스를 통해 읽습니다. GHOST SCOPE는 이 값을
  전송하지 않습니다. 화면에 표시하고, 기록을 저장하면 기기 안의 앱 전용
  저장 공간에 남길 뿐입니다.
- **거부해도 두 기능은 그대로 동작합니다.** 기록에 좌표가 남지 않을 뿐입니다.

안드로이드 시스템 설정에서 언제든 위치 권한을 회수할 수 있습니다.

### 사용자가 저장한 사진

촬영 버튼을 누르면 앱이 이미지 한 장을 기기의 사진 갤러리
(`Pictures/Ghost`)에 저장합니다. 이 동작은 사용자가 버튼을 누를 때만
일어납니다. 저장된 이미지는 사용자 기기에 남으며 보관·공유·삭제 모두 사용자
권한입니다. 앱은 기존 사진을 읽지 않습니다.

**사진 파일 안의 좌표.** 위치 권한을 허용했고 설정의 *사진에 위치 정보
포함*이 켜져 있으면(기본값은 켜짐), 좌표가 사진 파일 자체의 EXIF 메타데이터에
기록됩니다. 즉 그 사진을 다른 사람에게 보내면 촬영 위치도 함께 전달됩니다.
사진에 좌표를 남기고 싶지 않다면 이 설정을 끄십시오. 앱 안의 지난 기록에는
이 설정과 무관하게 좌표가 남습니다.

### 기기에 남는 기록

지난 기록 화면에는 사용자가 촬영한 사진과 저장하기로 선택한 고스트 박스
세션이 표시됩니다. 각 항목에는 시각, 좌표가 있었다면 그 좌표, 그리고 세션의
경우 들린 말이 담깁니다.

- 이 목록은 앱 전용 저장 공간에 있습니다. 다른 앱은 읽을 수 없습니다.
- 앱을 삭제하면 함께 사라집니다.
- 지난 기록 화면에서 항목을 개별로, 또는 전체를 삭제할 수 있습니다. 항목을
  지워도 갤러리에 저장된 사진은 지워지지 않습니다.

### 기기에 저장되는 설정

앱은 자체 저장 공간에 몇 가지 작은 값만 보관합니다. 소개 화면을 봤는지 여부,
선택한 감지 감도, 고스트 박스의 스캔 속도와 볼륨, 그리고 저장하는 사진에
위치를 포함할지 여부입니다. 이 값들은 기기를 벗어나지 않으며 앱을 삭제하면
함께 사라집니다.

### 음성 합성

고스트 박스는 짧은 단어 파편을 재생합니다. 이를 위해 앱은 **기기에 이미
설치된** 음성 합성(TTS) 엔진에 고정된 일반 단어 목록의 합성을 요청하고, 그
결과 오디오를 자체 저장 공간에 캐시합니다. 단어 목록은 앱에 내장되어 있으며
사용자의 행동에 따라 바뀌지 않습니다.

음성 합성 엔진은 기기 제조사 또는 Google이 제공하는 별도의 소프트웨어이며
자체 개인정보처리방침을 따릅니다. 일부 엔진은 네트워크를 통해 음성을
합성합니다. GHOST SCOPE가 엔진에 넘기는 것은 앱에 내장된 고정 단어 목록뿐이며
사용자에 관한 정보나 사용자가 입력한 내용은 넘기지 않습니다. 다만 별도 음성
엔진의 동작까지 저희가 통제할 수는 없습니다. 이 점이 우려되신다면 오프라인
음성을 사용하시거나 고스트 박스를 사용하지 마십시오.

### 광고

앱에는 Google AdMob 라이브러리가 포함되어 있습니다. 이후 버전에서 앱을 다시
만들지 않고도 광고를 켤 수 있도록 미리 넣어 둔 것입니다.

**이 버전에서 광고는 꺼져 있습니다.** 광고를 요청하지도, 표시하지도 않으며,
AdMob 라이브러리는 시작되지 않습니다. 실행 중에 건너뛰는 정도가 아니라,
라이브러리의 자동 시작 구성요소를 빌드 시점에 앱에서 제거합니다.

향후 버전에서 광고를 켜게 되면 해당 버전의 방침에 그 사실을 명시합니다. 그때
AdMob은 광고 선택을 위해 기기의 광고 ID와 기기에 관한 기술 정보를 수집하며,
이는 [Google의 개인정보처리방침](https://policies.google.com/privacy)을
따릅니다. 그 경우에도 저희가 받는 데이터는 없습니다.

### 네트워크 접근

앱은 포함된 AdMob 라이브러리가 요구하기 때문에 `INTERNET`과
`ACCESS_NETWORK_STATE` 권한을 보유합니다. **GHOST SCOPE는 이 권한을 사용하지
않습니다.** 카메라 프레임, 좌표, 사진, 저장한 기록 중 어느 것도 전송하지
않습니다. 보낼 서버 자체가 없습니다.

앱은 기기에 이미 설치된 별도 소프트웨어인 Google Play 스토어 앱에 GHOST
SCOPE의 새 버전이 있는지 물어, 사용자에게 업데이트를 안내합니다. 이 확인을
위해 GHOST SCOPE 자체가 네트워크에 연결하지는 않으며, 그 통신은 Play 스토어
앱이 Google의 개인정보처리방침에 따라 수행합니다.

앱은 분석 라이브러리와 크래시 리포팅 라이브러리를 포함하지 않습니다.

앱이 선언하는 권한:

| 권한 | 이유 |
| --- | --- |
| `CAMERA` | 필수. 카메라 영상 분석이 앱의 핵심 기능입니다. |
| `ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION` | 선택. 화면과 기록에 좌표를 남기는 데 씁니다. |
| `INTERNET`, `ACCESS_NETWORK_STATE` | 포함된 AdMob 라이브러리가 요구합니다. 광고가 꺼져 있는 동안 사용되지 않습니다. |
| `AD_ID`, `ACCESS_ADSERVICES_*`, `FOREGROUND_SERVICE`, `WAKE_LOCK` | AdMob 라이브러리가 추가합니다. 광고가 꺼져 있는 동안 사용되지 않습니다. |

### 아동

이 앱은 일반 이용자를 대상으로 하며 아동을 대상으로 하지 않습니다. 아동을
포함한 누구로부터도 데이터를 수집하지 않습니다.

### 방침 변경

방침이 변경되면 이 주소에 갱신된 내용을 게시하고 위 날짜를 수정합니다.

### 문의

방침 관련 문의는 GHOST SCOPE의 Google Play 스토어 등록정보에 표시된
개발자 연락처를 이용해 주십시오.
