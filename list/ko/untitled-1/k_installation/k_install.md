---
description: '누구나 쉽게 따라하면서, 적응할 수 있는 설치 방법!'
---

# 설치

## 설치 파일 다운로드

* [http://start.xpressengine.io/latest.zip](http://start.xpressengine.io/latest.zip) 을 [다운로드](http://start.xpressengine.io/latest.zip) 합니다.
* 다운로드 받은 zip 파일의 압축을 풀고 서버에 업로드 합니다. \(약 100MB\)

### 설치 동영상

이해를 위해 짧은 이미지를 준비했습니다.

![&#xC124;&#xCE58;&#xB97C; &#xC704;&#xD55C; &#xBAA8;&#xB4E0; &#xB2E8;&#xACC4;&#xB97C; &#xB2F4;&#xACE0; &#xC788;&#xC2B5;&#xB2C8;&#xB2E4;. &#xCC38;&#xACE0;&#xD574;&#xC8FC;&#xC138;&#xC694; &#x3147;\_&amp;lt;](../../../../.gitbook/assets/install_xe.gif)

### FileZila

FTP는 FileZila 를 사용해서 설명합니다. FileZila 는 무료로 사용이 가능한 프로그램 입니다. [다운로드](https://filezilla-project.org/download.php?type=client)

### 디렉토리 권한 설정

#### bootstrap/cache, config/production, storage 폴더 설정

상단의 폴더들을 707 권한으로 변경해주세요.

> 권한 설정할 때 `하위 디렉터리로 이동`, `모든 파일과 디렉터리에 적용` 을 반드시 체크해 주세요.

![&#xB2E4;&#xC911; &#xC120;&#xD0DD;&#xC740; &#xCEE8;&#xD2B8;&#xB864; &#xD0A4; + &#xB9C8;&#xC6B0;&#xC2A4; &#xC88C; &#xD074;&#xB9AD;&#xC744; &#xD558;&#xBA74; &#xD074;&#xB9AD;&#xD560; &#xC218; &#xC788;&#xC5B4;&#xC694;. &#xD55C;&#xBC88;&#xC5D0; &#xC5EC;&#xB7EC; &#xD3F4;&#xB354;&#xB97C; &#xD074;&#xB9AD;&#xD574;&#xC11C; &#xC27D;&#xAC8C;~](../../../../.gitbook/assets/permission.gif)

## 웹 인스톨러 실행

설치할 사이트에 접속하면 인스톨 화면으로 이동됩니다.

웹 서버가 파일을 쓸 수 있도록 권한을 설정합니다.

> 만약 하위 디렉토리에 설치할 경우는 해당 디렉토리로 접속해 주세요.

### 설치 진행하기

![&#xC815;&#xC0C1;&#xC801;&#xC73C;&#xB85C; &#xAD8C;&#xD55C; &#xC124;&#xC815; &#xBC0F; &#xD30C;&#xC77C;&#xC774; &#xC5C5;&#xB85C;&#xB4DC; &#xB418;&#xBA74; &#xC774; &#xD654;&#xBA74;&#xC744; &#xBCF4;&#xAC8C; &#xB429;&#xB2C8;&#xB2E4;.](../../../../.gitbook/assets/1.PNG)

![START&#xB97C; &#xB20C;&#xB7EC; &#xC124;&#xCE58;&#xB97C; &#xC9C4;&#xD589;&#xD558;&#xAE30; &#xC804;, XE&#xC5D0; &#xD544;&#xC694;&#xD55C; &#xAE30;&#xBCF8; &#xAE30;&#xB2A5; &#xBC0F; &#xBAA8;&#xB4C8;&#xC774; &#xC124;&#xCE58; &#xB418;&#xC5C8;&#xB294;&#xC9C0; &#xAC80;&#xC0AC;&#xD569;&#xB2C8;&#xB2E4;.](../../../../.gitbook/assets/step_1_edited.png)

![&#xADF8; &#xC774;&#xD6C4; &#xC2DC;&#xC2A4;&#xD15C; &#xAC1C;&#xC120; &#xBC0F; &#xD658;&#xACBD; &#xC218;&#xC9D1;&#xC744; &#xC704;&#xD55C; &#xC57D;&#xAD00;&#xC744; &#xB3D9;&#xC758; &#xD574;&#xC8FC;&#xC2DC;&#xACE0;, NEXT&#xB97C; &#xB20C;&#xB7EC;&#xC8FC;&#xC138;&#xC694;.](../../../../.gitbook/assets/step_2-edited.png)

![&#xAC01; &#xD56D;&#xBAA9;&#xC5D0; &#xB9DE;&#xB294; &#xC815;&#xBCF4;&#xB97C; &#xC785;&#xB825;&#xD6C4; NEXT&#xB97C; &#xB204;&#xB974;&#xBA74;, &#xC7A0;&#xC2DC;&#xD6C4; &#xC124;&#xCE58;&#xAC00; &#xC644;&#xB8CC; &#xB429;&#xB2C8;&#xB2E4;.](../../../../.gitbook/assets/step_3_editied.png)

{% hint style="info" %}
DB 접속 정보를 모르거나, 정확히 입력해도 진행되지 않는다면, 사용하고 있는 호스팅 회사에 접속 방법을 문의하시기 바라며, 기본 포트와 호스트, DB 이름과 사용자 계정명이 다를 수 있습니다.
{% endhint %}

## 알려진 문제점

### FTP의 파일 업로드 오류

파일 업로드 및 디렉토리 설정을 완료하고 웹 인스톨러 접근할 때 오류가 발생하는 경우가 있습니다. 이 문제는 FTP 파일 업로드 중 누락된 파일이 있어 발생할 수 있는 문제 입니다. 해결하기 위해서 FTP로 다시 업로드 해야합니다. 동일 조건을 업로드할 경우 비슷한 오류가 계속해서 발생할 수 있으므로 중복파일 `건너뛰기` 옵션으로 업로드 해보는걸 권장합니다. 

### 웹 서버 타임아웃

서버 성능에 따라 웹 서버 타임아웃 설정에 의해 설치에 실패할 가능성이 있습니다. 이 문제는 사용하고 있는 호스팅 회사 또는 서버 관리자에게 문의하시기 바랍니다.

