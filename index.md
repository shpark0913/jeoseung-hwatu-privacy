---
title: 저승화투 개인정보 처리방침
lang: ko
---

# 저승화투 개인정보 처리방침

시행일: 2026년 11월

dev_sihyun(박시현, 이하 "개발자")은 모바일 게임 「저승화투」(이하 "앱", Android 패키지명 `dev.sihyun.jeoseunghwatu`)를 개인 자격으로 개발·배포합니다. 이 처리방침은 앱이 이용자의 정보를 어떻게 다루는지 설명합니다.

## 1. 요약

- 앱은 **어떤 개인정보도 수집하지 않으며, 누구에게도 제공하지 않습니다.**
- 앱에는 회원가입·로그인·계정이 없습니다. 광고, 분석 도구, 오류 보고 도구도 넣지 않았습니다.
- 앱은 **인터넷 권한(INTERNET)을 요청하지 않습니다.** 앱 스스로는 외부 서버와 통신할 수 없습니다.
- 게임 진행 상황은 **이용자의 기기 안에만** 저장됩니다.

## 2. 수집하는 개인정보

앱은 다음을 포함한 어떤 정보도 수집하지 않습니다.

- 이름, 이메일, 전화번호, 생년월일 등 신원 정보
- 기기 식별자, 광고 ID, IP 주소
- 위치, 연락처, 사진·파일, 마이크·카메라
- 앱 사용 기록, 플레이 통계, 오류(크래시) 기록

## 3. 기기에만 저장되는 정보

게임을 이어 하기 위해 다음 정보를 기기의 앱 전용 저장공간(Android SharedPreferences)에 저장합니다.

- 진행 중인 윤회(게임 상태)와 그 백업본
- 기록과 해금 상태(최고 기록, 열린 덱과 업보 단계, 만난 부적 목록, 오늘의 사십구재 기록)
- 설정(소리, 속도, 흔들림·효과 줄이기, 진동, 안내 표시 여부)

이 정보에는 개인을 알아볼 수 있는 내용이 없습니다. 개발자에게 전송되지도 않습니다. 앱을 삭제하거나 Android 설정에서 앱 데이터를 지우면 함께 삭제됩니다.

이용자가 기기의 **Android 백업(Google 계정 백업)**을 켜 두었다면, Android 시스템이 위 정보를 이용자의 Google 계정 백업에 포함할 수 있습니다. 이 백업은 Google이 Google 개인정보처리방침에 따라 처리합니다. 개발자는 백업에 접근할 수 없습니다.

## 4. 앱이 사용하는 권한과 기능

| 권한·기능 | 용도 | 정보 처리 |
|---|---|---|
| 진동(VIBRATE) | 패를 먹을 때 등의 진동 피드백. 설정에서 끌 수 있습니다. | 정보를 다루지 않습니다. |
| 클립보드 쓰기 | 이용자가 '시드 복사'를 누를 때 시드 문자열만 복사합니다. | 앱은 클립보드를 읽지 않습니다. |
| 공유 | 이용자가 '결과 공유하기'를 누르면 결과 이미지를 기기 안에서 만들어 앱 임시 저장공간(캐시)에 둡니다. 그다음 Android 공유 화면을 엽니다. | 이미지를 받을 앱은 이용자가 직접 고릅니다. 개발자에게는 아무것도 전송되지 않습니다. |

## 5. Google Play를 통한 처리

다음은 앱이 아니라 Google이 처리하며, [Google 개인정보처리방침](https://policies.google.com/privacy)이 적용됩니다.

- **구매·결제·환불:** 앱 구매는 Google Play에서 이루어집니다. 개발자는 Google Play Console에서 판매·환불 처리에 필요한 주문 정보(주문 번호, 구매 국가, 금액 등)를 볼 수 있습니다. 이 정보는 환불과 고객 문의 응대 외의 목적으로 쓰지 않습니다.
- **인앱 리뷰:** 앱은 첫 대왕 심판을 통과했을 때 한 번, Google Play 인앱 리뷰 창을 요청할 수 있습니다. 창을 띄울지는 Google Play가 정합니다. 남긴 별점과 리뷰는 Google Play가 수집해 스토어에 게시합니다. 앱은 리뷰 여부나 내용을 전달받지 않습니다.
- **앱 안정성 통계:** 이용자가 기기에서 'Google과 사용 및 진단 정보 공유'를 허용한 경우, Google은 비정상 종료·응답 없음 통계를 수집할 수 있습니다. 개발자는 Google Play Console에서 개인을 알아볼 수 없는 집계 형태로만 이 통계를 봅니다.

## 6. 제3자 제공 및 처리 위탁

개발자는 개인정보를 수집하지 않으므로 제3자에게 제공하거나 처리를 위탁하지 않습니다.

## 7. 이메일 문의

이용자가 shpark097754@gmail.com로 문의하면, 개발자는 이메일 주소와 문의 내용을 받게 됩니다.

- 이 정보는 답변에만 쓰고, 다른 목적으로 쓰거나 제3자에게 제공하지 않습니다.
- 문의 처리가 끝나면 지체 없이 삭제합니다. 다만 관계 법령이 보관을 요구하는 경우에는 그 기간 동안 보관한 뒤 삭제합니다.

## 8. 아동의 개인정보

앱은 만 14세 미만 아동을 포함한 누구의 개인정보도 수집하지 않습니다. 앱은 어린이를 주 대상으로 하지 않습니다.

만 14세 미만 아동이 이메일로 문의한 사실을 알게 된 경우, 법정대리인의 요청이 있거나 처리가 끝나면 지체 없이 그 이메일을 삭제합니다. 법정대리인은 shpark097754@gmail.com로 열람이나 삭제를 요청할 수 있습니다.

## 9. 이용자의 권리

이용자는 개발자가 보관 중인 자신의 정보(문의 이메일)에 대해 열람·정정·삭제·처리정지를 요청할 수 있습니다. shpark097754@gmail.com로 요청하면 지체 없이 처리합니다.

기기에 저장된 게임 데이터는 이용자가 직접 지울 수 있습니다. 앱을 삭제하거나 Android 설정 → 앱 → 저승화투 → 저장공간 → 데이터 삭제를 누르면 됩니다.

## 10. 안전성 확보 조치

앱은 서버를 운영하지 않습니다. 개인정보를 외부로 전송하지 않기 때문에 전송 구간에서 유출될 위험이 없습니다. 문의 이메일을 받는 계정은 2단계 인증으로 보호합니다.

## 11. 개인정보 보호책임자

- 성명: 박시현 (dev_sihyun, 개인 개발자)
- 연락처: shpark097754@gmail.com

## 12. 권익침해 구제 방법

개인정보 침해에 관한 상담이나 신고는 아래 기관에 문의할 수 있습니다.

- 개인정보분쟁조정위원회: (국번없이) 1833-6972 · www.kopico.go.kr
- 개인정보침해신고센터(한국인터넷진흥원): (국번없이) 118 · privacy.kisa.or.kr
- 대검찰청: (국번없이) 1301 · www.spo.go.kr
- 경찰청: (국번없이) 182 · ecrm.police.go.kr

## 13. 처리방침의 변경

이 처리방침을 바꾸면 이 페이지에 게시하고 시행일을 고칩니다. 앞으로 앱이 정보를 수집하거나 외부와 통신하는 기능을 추가하게 되면 다음 순서를 따릅니다.

1. 해당 버전을 배포하기 전에 이 처리방침과 Google Play 데이터 보안 정보를 먼저 고칩니다.
2. 시행 7일 전까지 이 페이지에 알립니다.

**변경 이력**
- 2026년 10월: 최초 제정

---

# Jeoseung Hwatu Privacy Policy (English)

Effective: November 2026

dev_sihyun (Sihyun Park, "the developer") makes and publishes the mobile game *Jeoseung Hwatu* ("the app", Android package `dev.sihyun.jeoseunghwatu`) as an individual.

**Summary**
- The app does **not collect, store off-device, or share any personal data.**
- There are no accounts and no ads. There are no analytics or crash-reporting SDKs.
- The app does not request the INTERNET permission. It cannot send data anywhere.

**Data stored on your device only.** Your game progress is kept in the app's private storage on your device (Android SharedPreferences). This includes the current run, unlocks and records, and settings. It contains nothing that identifies you and is never sent to the developer. It is deleted when you uninstall the app or clear its data. If you have turned on Android backup to your Google Account, Android may include this data in your backup. Google handles that backup under its own privacy policy, and the developer cannot access it.

**Permissions and features**
- Vibration: used for haptic feedback. You can turn it off in settings.
- Clipboard: written only when you tap "copy seed". The app never reads it.
- Sharing: when you tap "share result", the app creates an image on your device and opens the Android share sheet. You choose where it goes, and nothing is sent to the developer.

**Google Play.** Google processes the following under the [Google Privacy Policy](https://policies.google.com/privacy):
- Purchases, payments and refunds. The developer can see order details in Google Play Console, such as order number, country and amount. These are used only to handle refunds and support requests.
- The in-app review prompt. Your rating and review go to Google Play, not to the app.
- Aggregated crash and ANR statistics, if you have allowed your device to share usage and diagnostics with Google.

**Contacting the developer.** If you email shpark097754@gmail.com, your email address and message are used only to reply. They are deleted once your request is resolved, unless a law requires keeping them.

**Children.** The app collects no personal data from anyone, including children, and is not directed at children.

**Your rights.** You may ask to access, correct or delete any email correspondence the developer holds about you by writing to shpark097754@gmail.com. You can delete your game data on your device at any time.

**Changes.** Changes will be posted on this page with a new effective date. If a future version adds any data collection or network features, this policy and the Google Play Data safety section will be updated before that version is released.

Contact: dev_sihyun (Sihyun Park) · shpark097754@gmail.com
