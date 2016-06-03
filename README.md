## [IAMROOT](http://iamroot.org) 13차 Kernel D

### 소스 분석을 위한 tag 설정 방법

리눅스 환경에 vim(emacs), cscope, ctags, make를 설치하고 아래 명령을 입력합니다.

```
make ARCH=arm bcm2709_defconfig
make ARCH=arm -j2 cscope tags
```
