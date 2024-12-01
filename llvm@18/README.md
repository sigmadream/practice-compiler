# LLVM@18

## 준비

LLVM 설치 후에 `LLVM-Config.cmake` 파일이 있는 위치를 CMake에 설정해주시면 됩니다. 해당 사항은 CMake 매뉴얼이나 LLVM 매뉴얼 등을 참고하세요. LLVM 설치는 아래 방법을 사용해서 진행하였습니다.

### Windows
```
scoop instal llvm # or winget install --id=LLVM.LLVM -e
```

### macOS

```
brew install llvm
```
