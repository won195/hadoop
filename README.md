# hadoop

# 자주 사용하는 리눅스 패키지

ubuntu@master:~$ sudo apt install <package_name>

* apt

  * Debian Linux의 패키지 관리자 (MacOS의 brew와 유사)

  * apt-get과 apt-cache 패키지의 결합

   * list
  ```
  # 모든 package 목록 출력
  ubuntu@master:~$ apt list
  # 설치된 package 목록 출력
  ubuntu@master:~$ apt list --installed
  # 업그레이드 가능한 package 목록 출력
  ubuntu@master:~$ apt list --upgradeable
  ```

  * update : package 목록 갱신
  ```
  ubuntu@master:~$ sudo apt update
  ```

  * upgrade : package를 최신 버전으로 업그레이드
