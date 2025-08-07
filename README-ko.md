# Claude Code 서브에이전트 컬렉션

[Claude Code](https://docs.anthropic.com/en/docs/claude-code)를 위한 도메인별 전문 AI 서브에이전트의 포괄적인 컬렉션으로, 특화된 전문성으로 개발 워크플로를 향상시킵니다.

## 개요

이 저장소는 Claude Code의 기능을 확장하는 56개의 전문화된 서브에이전트를 포함하고 있습니다. 각 서브에이전트는 특정 도메인의 전문가로, 컨텍스트에 따라 자동으로 호출되거나 필요시 명시적으로 호출됩니다. 모든 에이전트는 최적의 성능과 비용 효율성을 위해 작업 복잡도에 따라 특정 Claude 모델로 구성되어 있습니다.

## 사용 가능한 서브에이전트

### 개발 및 아키텍처
- **[backend-architect](backend-architect.md)** - RESTful API, 마이크로서비스 경계, 데이터베이스 스키마 설계
- **[frontend-developer](frontend-developer.md)** - React 컴포넌트 구축, 반응형 레이아웃 구현, 클라이언트측 상태 관리
- **[ui-ux-designer](ui-ux-designer.md)** - 인터페이스 디자인, 와이어프레임, 디자인 시스템 생성
- **[mobile-developer](mobile-developer.md)** - 네이티브 통합을 통한 React Native 또는 Flutter 앱 개발
- **[graphql-architect](graphql-architect.md)** - GraphQL 스키마, 리졸버, 페더레이션 설계
- **[architect-reviewer](architect-reviewer.md)** - 아키텍처 일관성과 패턴을 위한 코드 변경 검토

### 언어 전문가
- **[python-pro](python-pro.md)** - 고급 기능과 최적화를 통한 관용적 Python 코드 작성
- **[golang-pro](golang-pro.md)** - 고루틴, 채널, 인터페이스를 사용한 관용적 Go 코드 작성
- **[rust-pro](rust-pro.md)** - 소유권 패턴, 라이프타임, 트레이트 구현을 통한 관용적 Rust 코드 작성
- **[c-pro](c-pro.md)** - 적절한 메모리 관리와 시스템 호출을 통한 효율적 C 코드 작성
- **[cpp-pro](cpp-pro.md)** - 현대적 기능, RAII, 스마트 포인터, STL 알고리즘을 통한 관용적 C++ 코드 작성
- **[javascript-pro](javascript-pro.md)** - ES6+, 비동기 패턴, Node.js API를 통한 현대적 JavaScript 마스터
- **[typescript-pro](typescript-pro.md)** - 고급 타입, 제네릭, 엄격한 타입 안전성을 통한 TypeScript 마스터
- **[php-pro](php-pro.md)** - 현대적 기능과 성능 최적화를 통한 관용적 PHP 코드 작성
- **[java-pro](java-pro.md)** - 스트림, 동시성, JVM 최적화를 통한 현대적 Java 마스터
- **[elixir-pro](elixir-pro.md)** - OTP 패턴, 함수형 프로그래밍, Phoenix 프레임워크를 통한 관용적 Elixir 코드 작성
- **[csharp-pro](csharp-pro.md)** - 고급 기능과 .NET 최적화를 통한 현대적 C# 코드 작성
- **[unity-developer](unity-developer.md)** - 최적화된 스크립트와 성능 튜닝을 통한 Unity 게임 구축
- **[ios-developer](ios-developer.md)** - Swift/SwiftUI를 통한 네이티브 iOS 애플리케이션 개발
- **[sql-pro](sql-pro.md)** - 복잡한 SQL 쿼리 작성, 실행 계획 최적화, 정규화된 스키마 설계

### 인프라 및 운영
- **[devops-troubleshooter](devops-troubleshooter.md)** - 프로덕션 이슈 디버깅, 로그 분석, 배포 실패 수정
- **[deployment-engineer](deployment-engineer.md)** - CI/CD 파이프라인, Docker 컨테이너, 클라우드 배포 구성
- **[cloud-architect](cloud-architect.md)** - AWS/Azure/GCP 인프라 설계 및 클라우드 비용 최적화
- **[database-optimizer](database-optimizer.md)** - SQL 쿼리 최적화, 효율적인 인덱스 설계, 데이터베이스 마이그레이션 처리
- **[database-admin](database-admin.md)** - 데이터베이스 운영, 백업, 복제, 모니터링 관리
- **[terraform-specialist](terraform-specialist.md)** - 고급 Terraform 모듈 작성, 상태 파일 관리, IaC 모범 사례 구현
- **[incident-responder](incident-responder.md)** - 긴급하고 정밀한 프로덕션 인시던트 처리
- **[network-engineer](network-engineer.md)** - 네트워크 연결 디버깅, 로드 밸런서 구성, 트래픽 패턴 분석
- **[dx-optimizer](dx-optimizer.md)** - 툴링, 설정, 워크플로를 개선하는 개발자 경험 전문가

### 품질 및 보안
- **[code-reviewer](code-reviewer.md)** - 깊은 구성 보안 중점과 프로덕션 신뢰성을 갖춘 전문 코드 검토
- **[security-auditor](security-auditor.md)** - 취약점에 대한 코드 검토 및 OWASP 규정 준수 보장
- **[test-automator](test-automator.md)** - 단위, 통합, e2e 테스트를 포함한 포괄적인 테스트 스위트 생성
- **[performance-engineer](performance-engineer.md)** - 애플리케이션 프로파일링, 병목 현상 최적화, 캐싱 전략 구현
- **[debugger](debugger.md)** - 오류, 테스트 실패, 예상치 못한 동작에 대한 디버깅 전문가
- **[error-detective](error-detective.md)** - 오류 패턴, 스택 트레이스, 이상 징후를 위한 로그와 코드베이스 검색
- **[search-specialist](search-specialist.md)** - 고급 검색 기술과 합성을 사용하는 전문 웹 연구원

### 데이터 및 AI
- **[data-scientist](data-scientist.md)** - SQL 쿼리, BigQuery 작업, 데이터 인사이트를 위한 데이터 분석 전문가
- **[data-engineer](data-engineer.md)** - ETL 파이프라인, 데이터 웨어하우스, 스트리밍 아키텍처 구축
- **[ai-engineer](ai-engineer.md)** - LLM 애플리케이션, RAG 시스템, 프롬프트 파이프라인 구축
- **[ml-engineer](ml-engineer.md)** - ML 파이프라인, 모델 서빙, 피처 엔지니어링 구현
- **[mlops-engineer](mlops-engineer.md)** - ML 파이프라인, 실험 추적, 모델 레지스트리 구축
- **[prompt-engineer](prompt-engineer.md)** - LLM과 AI 시스템을 위한 프롬프트 최적화

### 전문 도메인
- **[api-documenter](api-documenter.md)** - OpenAPI/Swagger 스펙 생성 및 개발자 문서 작성
- **[payment-integration](payment-integration.md)** - Stripe, PayPal 및 결제 프로세서 통합
- **[quant-analyst](quant-analyst.md)** - 금융 모델 구축, 트레이딩 전략 백테스트, 시장 데이터 분석
- **[risk-manager](risk-manager.md)** - 포트폴리오 위험, R-배수, 포지션 한계 모니터링
- **[legacy-modernizer](legacy-modernizer.md)** - 레거시 코드베이스 리팩터링 및 점진적 현대화 구현
- **[context-manager](context-manager.md)** - 여러 에이전트와 장기 실행 작업 간 컨텍스트 관리

### 문서화
- **[docs-architect](docs-architect.md)** - 기존 코드베이스에서 포괄적인 기술 문서 생성
- **[reference-builder](reference-builder.md)** - 포괄적인 기술 참조 및 API 문서 생성
- **[tutorial-engineer](tutorial-engineer.md)** - 코드에서 단계별 튜토리얼 및 교육 콘텐츠 생성

### 비즈니스 및 마케팅
- **[business-analyst](business-analyst.md)** - 지표 분석, 보고서 생성, KPI 추적
- **[content-marketer](content-marketer.md)** - 블로그 게시물, 소셜 미디어 콘텐츠, 이메일 뉴스레터 작성
- **[sales-automator](sales-automator.md)** - 콜드 이메일, 후속 조치, 제안서 템플릿 작성
- **[customer-support](customer-support.md)** - 지원 티켓, FAQ 응답, 고객 이메일 처리
- **[legal-advisor](legal-advisor.md)** - 개인정보 보호정책, 서비스 약관, 면책 조항, 법적 고지사항 작성

## 모델 할당

모든 56개 서브에이전트는 작업 복잡도에 따라 특정 Claude 모델로 구성됩니다:

### 🚀 Haiku (빠르고 비용 효율적) - 9개 에이전트
**모델:** `haiku`
- `data-scientist` - SQL 쿼리 및 데이터 분석
- `api-documenter` - OpenAPI/Swagger 문서화
- `reference-builder` - 포괄적인 기술 참조 및 API 문서
- `business-analyst` - 지표 및 KPI 추적
- `content-marketer` - 블로그 게시물 및 소셜 미디어
- `customer-support` - 지원 티켓 및 FAQ
- `sales-automator` - 콜드 이메일 및 제안서
- `search-specialist` - 웹 연구 및 정보 수집
- `legal-advisor` - 개인정보 보호정책 및 규정 준수 문서

### ⚡ Sonnet (균형잡힌 성능) - 34개 에이전트
**모델:** `sonnet`

**개발 및 언어:**
- `python-pro` - 고급 기능을 통한 Python 개발
- `javascript-pro` - 현대적 JavaScript 및 Node.js
- `typescript-pro` - 타입 시스템을 통한 고급 TypeScript
- `golang-pro` - Go 동시성 및 관용적 패턴
- `rust-pro` - Rust 메모리 안전성 및 시스템 프로그래밍
- `c-pro` - C 프로그래밍 및 임베디드 시스템
- `cpp-pro` - STL 및 템플릿을 통한 현대적 C++
- `php-pro` - 고급 기능을 통한 현대적 PHP
- `java-pro` - 스트림 및 동시성을 통한 현대적 Java
- `elixir-pro` - OTP 패턴 및 Phoenix를 통한 Elixir
- `csharp-pro` - .NET 프레임워크 및 패턴을 통한 현대적 C#
- `unity-developer` - Unity 게임 개발 및 최적화
- `ios-developer` - Swift/SwiftUI를 통한 네이티브 iOS 개발
- `frontend-developer` - React 컴포넌트 및 UI
- `ui-ux-designer` - 인터페이스 디자인 및 와이어프레임
- `backend-architect` - API 설계 및 마이크로서비스
- `mobile-developer` - React Native/Flutter 앱
- `sql-pro` - 복잡한 SQL 최적화
- `graphql-architect` - GraphQL 스키마 및 리졸버

**인프라 및 운영:**
- `devops-troubleshooter` - 프로덕션 디버깅
- `deployment-engineer` - CI/CD 파이프라인
- `database-optimizer` - 쿼리 최적화
- `database-admin` - 데이터베이스 운영
- `terraform-specialist` - Infrastructure as Code
- `network-engineer` - 네트워크 구성
- `dx-optimizer` - 개발자 경험
- `data-engineer` - ETL 파이프라인

**품질 및 지원:**
- `test-automator` - 테스트 스위트 생성
- `code-reviewer` - 코드 품질 분석
- `debugger` - 오류 조사
- `error-detective` - 로그 분석
- `ml-engineer` - ML 모델 배포
- `legacy-modernizer` - 프레임워크 마이그레이션
- `payment-integration` - 결제 처리

### 🧠 Opus (최대 역량) - 13개 에이전트
**모델:** `opus`
- `ai-engineer` - LLM 애플리케이션 및 RAG 시스템
- `security-auditor` - 취약점 분석
- `performance-engineer` - 애플리케이션 최적화
- `incident-responder` - 프로덕션 인시던트 처리
- `mlops-engineer` - ML 인프라
- `architect-reviewer` - 아키텍처 일관성
- `cloud-architect` - 클라우드 인프라 설계
- `prompt-engineer` - LLM 프롬프트 최적화
- `context-manager` - 다중 에이전트 조정
- `quant-analyst` - 금융 모델링
- `risk-manager` - 포트폴리오 위험 관리
- `docs-architect` - 코드베이스에서 포괄적인 기술 문서
- `tutorial-engineer` - 단계별 튜토리얼 및 교육 콘텐츠

## 설치

이러한 서브에이전트는 `~/.claude/agents/` 디렉토리에 배치하면 자동으로 사용할 수 있습니다.

```bash
cd ~/.claude
git clone https://github.com/wshobson/agents.git
```

## 사용법

### 자동 호출
Claude Code는 작업 컨텍스트와 서브에이전트의 설명에 따라 적절한 서브에이전트에 자동으로 위임합니다.

### 명시적 호출
요청에서 서브에이전트의 이름을 언급:
```
"code-reviewer를 사용해 최근 변경사항을 확인해주세요"
"security-auditor가 취약점을 스캔하도록 하세요"
"performance-engineer가 이 병목현상을 최적화하도록 하세요"
```

## 사용 예제

### 단일 에이전트 작업
```bash
# 코드 품질 및 검토
"code-reviewer를 사용해 이 컴포넌트의 모범 사례를 분석하세요"
"code-reviewer가 이 구성 변경사항을 면밀히 검토하도록 하세요"
"security-auditor가 OWASP 규정 준수 이슈를 확인하도록 하세요"

# 개발 작업  
"backend-architect가 사용자 인증 API를 설계하도록 하세요"
"frontend-developer를 사용해 반응형 대시보드 레이아웃을 만드세요"

# 인프라 및 운영
"devops-troubleshooter가 이 프로덕션 로그를 분석하도록 하세요"
"cloud-architect를 사용해 확장 가능한 AWS 아키텍처를 설계하세요"
"network-engineer가 SSL 인증서 이슈를 디버깅하도록 하세요"
"database-admin을 사용해 백업 및 복제를 설정하세요"

# 데이터 및 AI
"data-scientist가 이 고객 행동 데이터셋을 분석하도록 하세요"
"ai-engineer를 사용해 문서 검색용 RAG 시스템을 구축하세요"
"mlops-engineer가 MLflow 실험 추적을 설정하도록 하세요"

# 비즈니스 및 마케팅
"business-analyst가 성장 지표로 투자자 덱을 만들도록 하세요"
"content-marketer를 사용해 SEO 최적화된 블로그 게시물을 작성하세요"
"sales-automator가 콜드 이메일 시퀀스를 만들도록 하세요"
"customer-support가 FAQ 문서를 작성하도록 하세요"
```

### 다중 에이전트 워크플로

이 서브에이전트들은 원활하게 함께 작동하며, 더 복잡한 오케스트레이션을 위해서는 이러한 서브에이전트를 정교한 워크플로에서 활용하는 52개의 사전 구축된 슬래시 명령을 제공하는 **[Claude Code Commands](https://github.com/wshobson/commands)** 컬렉션을 사용할 수 있습니다.

```bash
# 기능 개발 워크플로
"사용자 인증 기능 구현"
# 자동으로 사용: backend-architect → frontend-developer → test-automator → security-auditor

# 성능 최적화 워크플로  
"체크아웃 프로세스 성능 최적화"
# 자동으로 사용: performance-engineer → database-optimizer → frontend-developer

# 프로덕션 인시던트 워크플로
"프로덕션에서 높은 메모리 사용량 디버그"
# 자동으로 사용: incident-responder → devops-troubleshooter → error-detective → performance-engineer

# 네트워크 연결 워크플로
"간헐적 API 타임아웃 수정"
# 자동으로 사용: network-engineer → devops-troubleshooter → performance-engineer

# 데이터베이스 유지보수 워크플로
"프로덕션 데이터베이스 재해 복구 설정"
# 자동으로 사용: database-admin → database-optimizer → incident-responder

# ML 파이프라인 워크플로
"모니터링을 포함한 엔드투엔드 ML 파이프라인 구축"
# 자동으로 사용: mlops-engineer → ml-engineer → data-engineer → performance-engineer

# 제품 출시 워크플로
"마케팅 캠페인과 함께 새 기능 출시"
# 자동으로 사용: business-analyst → content-marketer → sales-automator → customer-support
```

### 슬래시 명령을 통한 고급 워크플로

더 정교한 다중 서브에이전트 오케스트레이션을 위해서는 보조 [Commands 저장소](https://github.com/wshobson/commands)를 사용하세요:

```bash
# 복잡한 기능 개발 (8개 이상의 서브에이전트)
/full-stack-feature 실시간 분석이 포함된 사용자 대시보드 구축

# 프로덕션 인시던트 대응 (5개 이상의 서브에이전트) 
/incident-response 데이터베이스 커넥션 풀 소진

# ML 인프라 설정 (6개 이상의 서브에이전트)
/ml-pipeline A/B 테스트가 포함된 추천 엔진 생성

# 보안 중심 구현 (7개 이상의 서브에이전트)
/security-hardening 제로 트러스트 아키텍처로 OAuth2 구현
```

## 어떤 에이전트를 언제 사용할지

### 🏗️ 기획 및 아키텍처
- **backend-architect**: API 설계, 데이터베이스 스키마, 시스템 아키텍처
- **frontend-developer**: UI/UX 기획, 컴포넌트 아키텍처
- **ui-ux-designer**: 인터페이스 디자인, 와이어프레임, 디자인 시스템, 사용자 연구
- **cloud-architect**: 인프라 설계, 확장성 기획

### 🔧 구현 및 개발  
- **python-pro**: Python 특화 개발 작업
- **golang-pro**: Go 특화 개발 작업
- **rust-pro**: Rust 특화 개발, 메모리 안전성, 시스템 프로그래밍
- **c-pro**: C 프로그래밍, 임베디드 시스템, 성능 중요 코드
- **javascript-pro**: 현대적 JavaScript, 비동기 패턴, Node.js/브라우저 코드
- **typescript-pro**: 고급 TypeScript, 제네릭, 타입 추론, 엔터프라이즈 패턴
- **java-pro**: 현대적 Java 개발, 스트림, 동시성, Spring Boot
- **elixir-pro**: Elixir 개발, OTP 패턴, Phoenix 프레임워크, 함수형 프로그래밍
- **csharp-pro**: 현대적 C# 개발, .NET 프레임워크, 엔터프라이즈 패턴
- **unity-developer**: Unity 게임 개발, C# 스크립팅, 성능 최적화
- **ios-developer**: Swift/SwiftUI를 통한 네이티브 iOS 개발
- **sql-pro**: 데이터베이스 쿼리, 스키마 설계, 쿼리 최적화
- **mobile-developer**: React Native/Flutter 개발

### 🛠️ 운영 및 유지보수
- **devops-troubleshooter**: 프로덕션 이슈, 배포 문제
- **incident-responder**: 즉시 대응이 필요한 중대 장애
- **database-optimizer**: 쿼리 성능, 인덱싱 전략
- **database-admin**: 백업 전략, 복제, 사용자 관리, 재해 복구
- **terraform-specialist**: Infrastructure as Code, Terraform 모듈, 상태 관리
- **network-engineer**: 네트워크 연결, 로드 밸런서, SSL/TLS, DNS 디버깅

### 📊 분석 및 최적화
- **performance-engineer**: 애플리케이션 병목현상, 최적화
- **security-auditor**: 취약점 스캐닝, 규정 준수 확인
- **data-scientist**: 데이터 분석, 인사이트, 보고
- **mlops-engineer**: ML 인프라, 실험 추적, 모델 레지스트리, 파이프라인 자동화

### 🧪 품질 보증
- **code-reviewer**: 코드 품질, 구성 보안, 프로덕션 신뢰성
- **test-automator**: 테스트 전략, 테스트 스위트 생성
- **debugger**: 버그 조사, 오류 해결
- **error-detective**: 로그 분석, 오류 패턴 인식, 근본 원인 분석
- **search-specialist**: 심층 웹 연구, 경쟁 분석, 팩트 체킹

### 📚 문서화
- **api-documenter**: OpenAPI/Swagger 스펙, API 문서
- **docs-architect**: 포괄적인 기술 문서, 아키텍처 가이드, 시스템 매뉴얼
- **reference-builder**: 포괄적인 API 참조, 구성 가이드, 매개변수 문서
- **tutorial-engineer**: 단계별 튜토리얼, 학습 경로, 교육 콘텐츠

### 💼 비즈니스 및 전략
- **business-analyst**: KPI, 수익 모델, 성장 예측, 투자자 지표
- **risk-manager**: 포트폴리오 위험, 헤징 전략, R-배수, 포지션 사이징
- **content-marketer**: SEO 콘텐츠, 블로그 게시물, 소셜 미디어, 이메일 캠페인
- **sales-automator**: 콜드 이메일, 후속 조치, 제안서, 리드 육성
- **customer-support**: 지원 티켓, FAQ, 도움말 문서, 문제 해결
- **legal-advisor**: 개인정보 보호정책, 서비스 약관, 면책 조항, 법적 고지사항 작성

## 모범 사례

### 🎯 작업 위임
1. **Claude Code가 자동으로 위임하도록 하기** - 메인 에이전트가 컨텍스트를 분석하고 최적의 에이전트를 선택
2. **요구사항을 구체적으로 명시** - 제약 조건, 기술 스택, 품질 요구사항 포함
3. **에이전트 전문성 신뢰** - 각 에이전트는 해당 도메인에 최적화됨

### 🔄 다중 에이전트 워크플로
4. **고수준 요청으로 시작** - 에이전트들이 복잡한 다단계 작업을 조정하도록 허용
5. **에이전트 간 컨텍스트 제공** - 에이전트들이 필요한 배경 정보를 갖도록 보장
6. **통합 지점 검토** - 다른 에이전트들의 출력이 어떻게 함께 작동하는지 확인

### 🎛️ 명시적 제어
7. **특정 요구에 대해 명시적 호출 사용** - 특정 전문가의 관점이 필요할 때
8. **여러 에이전트를 전략적으로 결합** - 다른 전문가들이 서로의 작업을 검증할 수 있음
9. **특정 검토 패턴 요청** - "security-auditor가 backend-architect의 API 설계를 검토하도록 하세요"

### 📈 최적화
10. **에이전트 효과성 모니터링** - 어떤 에이전트가 사용 사례에 가장 적합한지 학습
11. **복잡한 작업에 대한 반복** - 에이전트 피드백을 사용해 요구사항 개선
12. **에이전트 강점 활용** - 작업 복잡도를 에이전트 역량에 맞춤

## 기여

새로운 서브에이전트를 추가하려면:
1. 위의 형식을 따라 새로운 `.md` 파일 생성
2. 소문자, 하이픈으로 구분된 이름 사용
3. 서브에이전트가 언제 사용되어야 하는지 명확한 설명 작성
4. 시스템 프롬프트에 구체적인 지침 포함

## 문제 해결

### 일반적인 이슈

**에이전트가 자동으로 호출되지 않음:**
- 요청이 도메인을 명확하게 나타내는지 확인 (예: "성능 이슈" → performance-engineer)
- 작업 유형에 대해 구체적으로 명시 (예: "코드 검토" → code-reviewer)

**예상치 못한 에이전트 선택:**
- 기술 스택과 요구사항에 대한 더 많은 컨텍스트 제공
- 특정 에이전트가 필요하면 명시적 호출 사용

**여러 에이전트가 상충하는 조언 제공:**
- 이는 정상적임 - 다른 전문가들은 다른 우선순위를 가질 수 있음
- 명확화 요청: "security-auditor와 performance-engineer의 권장사항을 조율해주세요"

**에이전트가 컨텍스트가 부족해 보임:**
- 요청에 배경 정보 제공
- 이전 대화나 확립된 패턴 참조

### 도움받기

에이전트가 예상대로 작동하지 않는 경우:
1. 개별 파일에서 에이전트 설명 확인
2. 요청에서 더 구체적인 언어 시도
3. 명시적 호출을 사용해 특정 에이전트 테스트
4. 프로젝트와 목표에 대한 더 많은 컨텍스트 제공

## 라이선스

이 프로젝트는 MIT 라이선스에 따라 라이선스가 부여됩니다 - 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

## 더 알아보기

- [Claude Code 문서](https://docs.anthropic.com/en/docs/claude-code)
- [서브에이전트 문서](https://docs.anthropic.com/en/docs/claude-code/sub-agents)
- [Claude Code GitHub](https://github.com/anthropics/claude-code)