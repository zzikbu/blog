## 🛠️ 개발환경
- Android Studio (version 2024.1)
- Dart SDK (version 3.4.3)
- Flutter (Channel stable, version 3.22.2)

## Dart Project 생성
![이미지1](img/20240730/스크린샷 2024-07-30 23.08.51.png)
안드로이드 스튜디오를 실행하고, New Flutter Project -> Dart -> Dart SDK path 선택 -> Console Application 선택을 해줍니다.  

⭐️ Flutter 설치 폴더 안에서 dart-sdk를 잘 선택해줍니다 !  

Dart에서 'Console Application'을 선택하여 프로젝트를 생성하는 것은 터미널 또는 명령 프롬프트에서 실행되는 커맨드 라인 애플리케이션을 만드는 것을 의미합니다. 이러한 애플리케이션은 그래픽 사용자 인터페이스(GUI)가 없으며, 텍스트 기반 입출력을 통해 동작합니다.

## Dart Project 구조
![이미지2](img/20240730/스크린샷 2024-07-31 00.04.43.png)
- bin : 바이너리 실행 파일을 의미합니다. 여기에는 애플리케이션의 진입점이 되는 단 하나의 Dart 파일이 포함됩니다. Dart 프로젝트를 실행하면 bin/프로젝트이름.dart의 main 함수가 가장 먼저 실행됩니다.

- lib : 라이브러리란 의미로, 재사용 가능한 Dart 코드를 포함하여 임포트를 통해 사용할 수 있는 파일들이 포함됩니다.

- pubspec.yaml : 의존성 관리 및 패키지 관련 정보를 제공하는 파일입니다. 패키지 이름, 버전, 작성자 정보 등이 포함되며, 프로젝트의 종속성 및 환경 설정을 정의합니다.