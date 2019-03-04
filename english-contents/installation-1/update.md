# Update



> Caution!  
> If you are updating from XE 3.0.0-beta.23 or earlier, please refer to the XE 3.0.0-beta.24 Update Guide.

XE3 can be update on a web page. 

## Download the latest version

After downloading the latest version of the XE, unzip it and overwrite it in the directory where the XE is installed.

If you have installed and used the version just before the update, you can overwrite only the files that have changed in the latest version. The changed files can be downloaded from the Github release page. The changed files are `changed.xxx` for each release Attached in the form of zip.

> Caution!  
> If you have modified the Core-source code or plug-in source code, please make a backup in advance.

## 웹 페이지에서 업데이트 적용

You can update it from the Site Management &gt; Plug-in & Update &gt; XE3 Update page.

만약 실제 서비스 서버와 별도로 개발 서버\(또는 스테이지 서버\)를 운영하고 있다면, 개발 서버에서는 'composer update 실행 안 함' 항목을 체크 해제한 상태에서 업데이트 하십시오. `composer update`가 함께 실행되면서 `/vendor` 디렉토리에 설치된 의존 라이브러리들도 최신 상태로 업데이트됩니다.

개발 서버에서 문제없이 업데이트가 됐다면, 개발 서버와 서비스 서버의 소스코드를 동기화 한 다음, 서비스 서버에서 다시 업데이트를 실행하십시오. 이 때에는 'composer update 실행 안 함' 항목을 체크한 다음 업데이트를 실행하시기 바랍니다.



## 설치된 플러그인의 업데이트

XE3 코어를 업데이트할 때, 설치된 플러그인들은 같이 업데이트 되지 않습니다. 업데이트를 완료한 후에는 `사이트 관리자 > 플러그인 > 플러그인 목록`에서 플러그인들도 업데이트 하시기 바랍니다.

