# MindNote 개인정보 처리방침 (Privacy Policy)

최종 업데이트: 2026년 11월 27일

## 요약

- 계정, 로그인, 광고, 추적 도구가 없습니다.
- 모든 기록은 사용자의 기기에만 저장됩니다.
- AI 감정 분석을 직접 요청한 한 줄만 분석을 위해 전송되며, 분석이 끝나면 저장하지 않습니다.

## 수집하지 않는 정보

MindNote는 이름, 이메일, 연락처, 위치, 기기 식별자 같은 개인정보를 수집하지 않습니다. 계정 생성이나 로그인이 필요하지 않으며, 제3자 분석 도구, 광고 SDK, 추적 기술을 사용하지 않습니다.

## 기기에 저장되는 정보

작성한 기록, 분석 결과(감정 라벨), 앱 설정은 사용자의 기기 안에만 저장됩니다. 개발자는 이 정보에 접근할 수 없습니다.

## AI 감정 분석

AI 감정 분석은 기본으로 꺼져 있으며, 사용자가 설정에서 켜고 기록마다 '분석하기'를 직접 누른 경우에만 동작합니다.

- **전송되는 내용**: 분석을 요청한 기록의 한 줄 텍스트만 전송됩니다. 날짜, 다른 기록, 기기 정보는 함께 보내지 않습니다.
- **처리 과정**: 텍스트는 암호화된 연결(HTTPS)로 개발자가 운영하는 분석 서버에 전송되고, 이 서버가 감정 분류를 위해 Anthropic의 AI 모델(Claude)에 전달합니다. 결과로 감정 라벨 하나만 앱에 돌려줍니다.
- **보관**: 분석 서버는 기록 텍스트를 저장하지 않습니다. 다만 분석 중 오류가 나면 원인 확인을 위해 해당 요청이 오류 기록에 남을 수 있으며, 오류 기록은 최근 몇 건만 유지되고 오래된 것부터 자동으로 지워집니다.
- **Anthropic의 처리**: Anthropic에 전달된 텍스트는 Anthropic의 개인정보 처리방침에 따라 처리됩니다. ([Anthropic Privacy Policy](https://www.anthropic.com/legal/privacy))

분석을 요청하지 않은 기록은 기기 밖으로 전송되지 않습니다.

## 보안을 위한 접속 기록

분석 서버는 과도한 요청과 남용을 막기 위해, 분석 요청이 들어온 IP 주소와 요청 시각을 서버 기록에 남길 수 있습니다. 이 정보는 보안과 서비스 안정성 목적으로만 쓰며, 기록 내용이나 다른 정보와 연결하지 않습니다.

## 기록 알림

기록 알림은 iPhone의 로컬 알림 기능으로 기기 안에서만 예약됩니다. 알림을 위해 어떤 정보도 외부로 전송하지 않습니다.

## 데이터 보관 및 삭제

모든 기록은 사용자의 기기에 저장되며, 설정의 **데이터 초기화**나 앱 삭제로 지울 수 있습니다. 설정의 **데이터 내보내기**로 JSON 백업 파일을 만들 수 있으며, 이 파일의 보관과 공유는 사용자가 직접 관리합니다.

## 변경 안내

이 방침이 바뀌면 이 페이지에 내용을 반영하고 최종 업데이트 날짜를 고칩니다.

## 문의

sncom1941@gmail.com

---

## Privacy Policy (English)

Last updated: November 27, 2026

**Summary.** MindNote has no accounts, logins, ads, or tracking. All entries are stored only on your device. Only the one-line entry you explicitly choose to analyze is sent for AI emotion analysis, and it is not stored after the analysis.

**Information we do not collect.** MindNote does not collect personal information such as your name, email, contacts, location, or device identifiers. We do not use third-party analytics, advertising SDKs, or tracking technologies.

**Information stored on your device.** Your entries, analysis results (emotion labels), and app settings are stored only on your device. The developer cannot access them.

**AI emotion analysis.** This feature is off by default. It works only after you turn it on in Settings and tap Analyze on a specific entry.

- *What is sent:* only the text of the entry you chose to analyze. No dates, other entries, or device information are sent.
- *How it is processed:* the text is sent over an encrypted connection (HTTPS) to an analysis server operated by the developer, which forwards it to Anthropic's AI model (Claude) to classify the emotion. Only a single emotion label is returned to the app.
- *Retention:* the analysis server does not store entry text. If an error occurs during analysis, the request may be kept in an error log for troubleshooting; only the most recent few error logs are kept and older ones are deleted automatically.
- *Anthropic:* text forwarded to Anthropic is processed under Anthropic's Privacy Policy (https://www.anthropic.com/legal/privacy).

Entries you do not analyze never leave your device.

**Security logs.** To prevent abuse and excessive requests, the analysis server may log the IP address and time of analysis requests. This information is used only for security and service stability and is not linked to your entries or any other information.

**Reminders.** Daily reminders are scheduled locally on your iPhone. No information is sent for reminders.

**Retention and deletion.** All entries are stored on your device and can be deleted with Settings > Reset Data or by deleting the app. You can create a JSON backup via Settings > Export Data; you are responsible for storing and sharing that file.

**Changes.** If this policy changes, we will update this page and the "Last updated" date.

**Contact:** sncom1941@gmail.com
