# Simple-Notepad-DLL-Injection

간단한 방식으로 특정 프로세스(메모장)에 외부 DLL을 삽입 인젝션을 수행하는 예제

## 코드 기능
인젠션 할 수 있는 인젝터
인젝션 할 DLL 

**본 리포지토리는 [tistory](https://wendys.tistory.com/23)를 참고해서 만들었습니다.**

## 에러 해결
dll 빌드할때 `미리 컴파일된 헤더 파일을 열 수 없습니다` 해당 에러가 발생 할 경우 `프로젝트 속성` > `C/C++` > `미리 컴파일된 헤더` > `미리 컴파일된 헤더 사용 안 함`을 하시면 됩니다.
Notepad 말고 다른 프로세스에도 인젝션이 됩니다.

## 사용법
기본적으로 DLL 인젝터는 `C:\\my_dll.dll`에 있는 DLL 을 사용합니다.
즉, DLL 빌드후 빌드된 DLL을 C:\\my_dll.dll 해당 경로에 해당 이름으로 옮겨 놓으세요.
