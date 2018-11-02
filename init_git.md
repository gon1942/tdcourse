# Git
버전 관리 시스템중 하나인 Git을 설치 및 사용해보겠습니다.

### 설치
- CentOS
```
# yum install git
```

- macOS에서는 아래처럼 명령어를 입력합니다. Xcode Command Line Tool에 Git이 포함되어 있기 때문입니다.
```
$ xcode-select --install
```

### 최초 셋팅
Git을 최초에 설치하고 사용하기 위해서는 name, e-mail 설정이 필요합니다.

```
$ git config --global user.name "woong"
$ git config --global user.email khw7096@gmail.com
```

### 설정값 확인
```
$ git config user.name
$ git config user.email
```

### GUI Clients
- https://git-scm.com/download/gui/linux