# Privacy Policy for OO Video Downloader (개인정보 처리방침)

[English Version](#english-version) | [한국어 버전 (Korean Version)](#한국어-버전-korean-version)

---

## English Version

**Last Updated: September 23, 2026**  
**Effective Date: September 23, 2026**

OO Video Downloader ("we", "us", "our") provides the OO Video Downloader application as a free, ad-supported service. This Service is provided at no cost and is intended for use "as is". Our application is designed to help users browse the web, detect public media streams, and download video and audio content for **personal, non-commercial offline use** while strictly adhering to platform policies and copyright regulations.

By choosing to use our Service, you agree to the collection and use of information in accordance with this policy. We value your privacy and are committed to complete transparency regarding how your data is handled.

---

### 1. Information Collection and Use

We prioritize user privacy. **We do not operate external user account databases, and we do not collect, store, or sell any personal identifiable information (such as your name, email address, phone number, contacts, or real-time GPS location).**

All downloaded files, bookmarks, browsing history, and application preferences are stored strictly locally on your device.

#### A. Third-Party Services & SDKs
Our app integrates third-party services that may automatically collect certain diagnostic and non-personally identifiable technical information to facilitate app functionality, crash reporting, and advertising. These third-party providers operate under their own privacy policies:

*   **Google Play Services**: Core Android system functionality, in-app updates, and security checks. ([Google Privacy Policy](https://www.google.com/policies/privacy/))
*   **Google AdMob**: Serving relevant advertisements and monetization. AdMob may process advertising IDs (AAID), IP addresses, and device performance metrics. ([Google AdMob Privacy Policy](https://support.google.com/admob/answer/6128543?hl=en))

#### B. Log & Diagnostic Data
In the event of an error, unexpected behavior, or application crash, diagnostic data (via Google Play Console or user-initiated inquiry) may be collected. This may include device model, operating system version, app version, timestamp of the crash, and system stack traces. This information is used strictly to diagnose bugs and enhance app stability.

---

### 2. Google Play Data Safety Compliance

In accordance with Google Play's Data Safety requirements:

*   **Personal Data**: We do **not** collect or transmit personal user credentials or sensitive personal information.
*   **Data Sharing**: We do **not** sell any data to third parties or data brokers. Data exchange occurs only with verified providers (Google Play Services, AdMob) for functional, analytics, and advertising purposes.
*   **Data Security**: All network communications initiated by the app (including browsing and downloading) utilize industry-standard secure protocols (HTTPS/TLS) where supported by the target website.
*   **Data Retention & User Deletion Rights**: Since all personal media files and preferences reside locally on your device, you have full and immediate control over your data:
    1.  Delete individual downloaded videos or cache within the app.
    2.  Clear the app data and cache via Android **Settings > Apps > OO Video Downloader > Storage > Clear Data**.
    3.  Uninstall the application to permanently remove all application-associated data.

---

### 3. Permissions & System Services

Our app requests only the minimum permissions necessary to deliver core video downloading and media management capabilities:

#### A. Media & Storage Access
*   `READ_MEDIA_VIDEO`, `READ_MEDIA_IMAGES` (Android 13+ / API 33+): Allows the app to access, preview, and manage video and thumbnail files saved on your device.
*   `READ_EXTERNAL_STORAGE`, `WRITE_EXTERNAL_STORAGE` (Android 12 and below): Required on older Android versions to write downloaded media files to your external storage directory.
*   **Scoped Storage & MediaStore**: Downloaded media is automatically registered with Android's MediaStore, enabling files to appear in your gallery app without exposing your entire storage.

#### B. Foreground Service (`FOREGROUND_SERVICE_DATA_SYNC`)
To ensure reliable video downloading and media processing (such as assembling multi-part HLS/M3U8 video segments and audio muxing), the app runs a **Foreground Service** categorized as `dataSync`. This ensures that active downloads are not prematurely killed by Android's battery optimization when you switch apps or turn off the screen. A persistent notification is always visible in your notification bar while this service is running.

#### C. Notifications (`POST_NOTIFICATIONS`)
On Android 13 (API 33) and higher, the app requests permission to display notifications. Notifications are used exclusively to:
*   Show real-time download progress and speeds.
*   Notify you when a download has completed successfully or encountered an error.

#### D. Network Access (`INTERNET`, `ACCESS_NETWORK_STATE`)
Required to browse web pages, detect downloadable media streams, and download video and audio content over Wi-Fi and mobile data networks.

---

### 4. Platform Policy & Copyright Compliance (Policy Guardian)

Our application features a built-in **Policy Guardian** engine:
*   **Copyright Protection**: Users must have the legal right or permission to download any content. The Service is intended strictly for personal, non-commercial archiving and offline viewing.
*   **DRM Protection**: We strictly do not provide means to bypass Digital Rights Management (DRM) or technical protection measures.
*   **Store Policy Compliance**: In full accordance with Google Play Developer Program Policies, downloading from restricted platforms (such as YouTube or protected DRM streaming services) is not permitted.

---

### 5. Links to External Sites & In-App Browser

Our Service features an integrated web browser that connects to third-party websites. We have no control over the content, security, or privacy practices of external sites. We strongly advise you to review the privacy policy and terms of any external website you visit.

---

### 6. Children's Privacy

Our Service is not directed to children under the age of 13. We do not knowingly collect personal information from children. If we become aware that a child under 13 has provided personal information, we will take immediate steps to delete such data.

---

### 7. Changes to This Privacy Policy

We may update this Privacy Policy periodically to reflect changes in our app features, legal guidelines, or store policies. Any modifications become effective immediately upon being published on this page. We encourage you to review this policy periodically.

---

### 8. Contact Information

If you have questions, suggestions, or feedback regarding this Privacy Policy:
*   **Developer**: deepflowdev
*   **Email Support**: You can submit inquiries via the "Email Inquiry" button inside the app settings.
*   **Official Repository**: https://github.com/deepflowdev/OO-Video-Downloader---Fast-Easy-HLS-M3U8-Downloader

---
---

## 한국어 버전 (Korean Version)

**최종 수정일: 2026년 9월 23일**  
**시행일: 2026년 9월 23일**

OO Video Downloader (이하 "당사" 또는 "앱")는 사용자의 편의를 위한 무료 비디오 다운로더 및 미디어 관리 서비스를 제공합니다. 본 앱은 사용자가 웹 브라우징 중 공개된 미디어 스트림을 감지하고, **개인적이고 비상업적인 오프라인 감상 목적**으로 비디오 및 오디오 콘텐츠를 저장할 수 있도록 지원합니다.

당사는 사용자의 개인정보를 소중히 여기며, 구글 플레이(Google Play) 개발자 정책 및 개인정보 보호 규정을 철저히 준수합니다.

---

### 1. 개인정보의 수집 및 이용 목적

당사는 개인정보 보호를 최우선으로 합니다. **당사는 자체적인 회원가입 서버나 데이터베이스를 운영하지 않으며, 사용자의 이름, 이메일, 전화번호, 연락처, 실시간 GPS 위치 등 식별 가능한 어떠한 개인정보도 직접 수집하거나 외부에 저장/판매하지 않습니다.**

다운로드한 파일, 북마크, 브라우징 기록, 앱 설정 등 모든 데이터는 사용자의 기기 내부 로컬 저장소에만 안전하게 저장됩니다.

#### A. 타사 서비스 및 라이브러리(SDK)
앱의 정상적인 구동, 버그 분석 및 광고 송출을 위해 다음과 같은 신뢰할 수 있는 타사 SDK가 포함되어 있습니다. 해당 서비스들은 각 사의 개인정보 처리방침에 따라 운영됩니다.
*   **Google Play Services**: 앱 무결성 확인, 인앱 업데이트 및 핵심 서비스 제공 ([Google 개인정보 처리방침](https://www.google.com/policies/privacy/))
*   **Google AdMob**: 배너 및 전면 광고 제공. 기기 식별자(광고 ID), IP 주소 및 성능 통계가 처리될 수 있습니다. ([AdMob 개인정보 보호 정책](https://support.google.com/admob/answer/6128543?hl=ko))

#### B. 로그 및 진단 데이터
앱 충돌이나 오류 발생 시, 원인 파악 및 안정성 향상을 위해 기술적 진단 정보(기기 모델, OS 버전, 앱 버전, 오류 발생 시점의 스택 트레이스 등)가 구글 플레이 콘솔 또는 사용자의 문의를 통해 수집될 수 있습니다. 이 정보는 오직 앱의 안정화 및 오류 해결 목적으로만 사용됩니다.

---

### 2. 구글 플레이 데이터 보안 규정 준수

*   **데이터 판매 금지**: 당사는 사용자의 어떠한 데이터도 제3자나 데이터 중개업체에 판매하지 않습니다.
*   **데이터 전송 보안**: 앱에서 수행되는 모든 네트워크 통신은 암호화된 표준 보안 프로토콜(HTTPS/TLS)을 따릅니다.
*   **데이터 파기 및 삭제 권한**: 모든 다운로드 미디어 및 설정은 사용자 기기에 로컬로 보관되므로, 사용자는 언제든지 다음과 같이 데이터를 영구 삭제할 수 있습니다.
    1.  앱 내에서 다운로드 완료된 파일 및 캐시 삭제
    2.  안드로이드 **설정 > 애플리케이션 > OO Video Downloader > 저장공간 > 데이터 삭제 및 캐시 삭제**
    3.  앱 삭제(제거)를 통한 기기 내 앱 관련 데이터 영구 삭제

---

### 3. 앱 권한 및 백그라운드 서비스 안내

당사는 앱의 핵심 기능 수행에 꼭 필요한 최소한의 권한만을 요청합니다.

#### A. 미디어 저장소 접근 권한
*   `READ_MEDIA_VIDEO`, `READ_MEDIA_IMAGES` (Android 13+): 다운로드된 동영상 및 썸네일을 앱 내에서 확인하고 재생/관리하기 위해 사용됩니다.
*   `READ_EXTERNAL_STORAGE`, `WRITE_EXTERNAL_STORAGE` (Android 12 이하): 구형 안드로이드 버전에서 다운로드 파일을 저장소에 기록하기 위해 사용됩니다.
*   **MediaStore 연동**: 다운로드된 영상은 시스템 미디어스토어와 즉시 동기화되어 기기의 기본 갤러리 앱에서 편리하게 확인하실 수 있습니다.

#### B. 포그라운드 서비스 (`FOREGROUND_SERVICE_DATA_SYNC`)
분할 다운로드(HLS/M3U8 스트림 병합, 영상 및 음원 합치기 등)가 진행되는 동안, 사용자가 다른 앱으로 전환하거나 화면이 꺼져도 다운로드가 중단되지 않도록 **데이터 동기화(dataSync) 포그라운드 서비스**를 사용합니다. 서비스 동작 중에는 상태 표시줄에 진행률 알림이 상시 표시됩니다.

#### C. 알림 권한 (`POST_NOTIFICATIONS`)
Android 13 이상 기기에서 다운로드 진행 상태와 완료 및 오류 알림을 사용자에게 명확히 전달하기 위해 알림 권한을 요청합니다.

#### D. 네트워크 접근 (`INTERNET`, `ACCESS_NETWORK_STATE`)
웹페이지 탐색, 미디어 감지 및 고속 다운로드 처리를 위해 인터넷 연결을 사용합니다.

---

### 4. 저작권 및 스토어 정책 준수 (Policy Guardian)

*   **저작권 준수**: 사용자는 다운로드하려는 콘텐츠에 대한 적법한 권리 또는 허가를 보유해야 하며, 다운로드된 파일은 개인적 소장 및 오프라인 감상 용도로만 이용해야 합니다.
*   **DRM 보호**: 저작권 보호 기술(DRM)이 적용된 암호화 콘텐츠의 우회 또는 무단 복제 기능을 제공하지 않습니다.
*   **스토어 정책 준수**: 구글 플레이의 정책을 철저히 준수하며, 플랫폼 규정에 의해 제한된 서비스(유튜브 등)에서의 다운로드는 제공되지 않습니다.

---

### 5. 아동의 개인정보 보호

당사의 서비스는 만 13세 미만의 아동을 대상으로 하지 않으며, 아동의 개인 식별 정보를 고의로 수집하지 않습니다.

---

### 6. 개인정보 처리방침의 변경

본 방침은 법령 개정, 구글 스토어 정책 변경 또는 앱 기능 개선에 따라 수시로 갱신될 수 있습니다. 변경된 사항은 본 페이지에 즉시 게시되며 게시된 시점부터 효력이 발생합니다.

---

### 7. 문의처

개인정보 처리방침과 관련된 문의, 제안 또는 피드백이 있으신 경우 아래 채널을 이용해 주시기 바랍니다.
*   **개발자**: deepflowdev
*   **이메일 문의**: 앱 내 설정 메뉴의 '이메일 문의' 버튼을 통해 접수
*   **저장소**: https://github.com/deepflowdev/OO-Video-Downloader---Fast-Easy-HLS-M3U8-Downloader
