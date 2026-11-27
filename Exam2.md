# A-SPICE 기반 SW 개발

## 구성도
<img width="433" height="978" alt="image" src="https://github.com/user-attachments/assets/d8fa905e-fa5c-4d65-b7f9-e887f1ae8806" />

## 순서
1. 필요한 스킬, 서브에이전트 설정
   - 어제 Python 용으로 테스트 스킬과 서브에이전트 생성한 것처럼.
   - 단, 어제 생성한 테스트와 TDD는 재사용(복붙)
2. Claude.md 설정
   - 프로세스 (A-SPICE 기반)
     - 리뷰: 매 단계가 끝날 때마다 수행
   - 소스코드 품질 요건(지표: 순환복잡도)
   - 테스트 요건(단위, 통합)
     - 단위: MCDC 100% 할때까지 반복
     - 통합: statement 커버리지 100% 할때까지 반복
   - 정적분석: CppCheck 이용해서 할 것
   - PR/Git Branch 정책: 일반적으로 사용하는 정책 (Git Flow)
   - 개발 환경 (툴체인)
     - 툴체인은 Docker 컨터이너로. 빌드 이상의 작업들은 컨테이너에서 수행
  
