<div align="center">

<img src="https://readme-typing-svg.herokuapp.com/?font=JetBrains+Mono&weight=600&size=26&pause=1000&color=58A6FF&center=true&vCenter=true&width=640&lines=Full-stack+Developer+%C2%B7+Infrastructure+Engineer;%EB%A7%8C%EB%93%A4%EA%B3%A0%2C+%EB%B0%B0%ED%8F%AC%ED%95%98%EA%B3%A0%2C+%EC%9A%B4%EC%98%81%EA%B9%8C%EC%A7%80" alt="typing" />

### Youngheon Kim

제품을 직접 만들고, 그게 돌아갈 인프라까지 직접 깝니다.<br/>
애플리케이션의 불편에서 출발해 배포·운영까지 책임지는 걸 좋아합니다.

<br/>

<a href="mailto:bleach10905@gmail.com"><img src="https://img.shields.io/badge/bleach10905@gmail.com-0D1117?style=flat&logo=gmail&logoColor=EA4335&labelColor=0D1117" height="26" /></a>
<a href="https://github.com/YHK0427"><img src="https://img.shields.io/badge/YHK0427-0D1117?style=flat&logo=github&logoColor=white&labelColor=0D1117" height="26" /></a>

</div>

<br/>

## Stack

<table>
<tr>
<td width="120"><b>Cloud</b></td>
<td><img src="https://skillicons.dev/icons?i=aws,azure,gcp,kubernetes,docker,terraform,linux,githubactions,cloudflare,nginx" height="42" /></td>
</tr>
<tr>
<td><b>Backend</b></td>
<td><img src="https://skillicons.dev/icons?i=ts,nestjs,nodejs,python,fastapi,flask,postgres,redis,prisma" height="42" /></td>
</tr>
<tr>
<td><b>Frontend</b></td>
<td><img src="https://skillicons.dev/icons?i=nextjs,react,tailwind,vite,electron" height="42" /></td>
</tr>
</table>

<br/>

## Projects

### `aesthet` &nbsp;·&nbsp; 커머스 플랫폼 &nbsp;<sup>private</sup>

운영 중인 서비스의 프론트엔드 · 백엔드 · 인프라를 전부 맡고 있습니다.

```
Frontend   Next.js · React · Tailwind — 구매자 / 판매자 / 관리자 3개 앱 전담, Playwright E2E
Backend    NestJS · Fastify · Prisma · PostgreSQL — 주문 / 정산 / 배송추적 / 클레임 도메인
Infra      홈서버 Kubernetes → AWS 이관, Terraform 모듈화 (VPC · EC2 · RDS · SSM · CodeBuild)
Ops        Cloudflare Tunnel 무인바운드, SSM 접속, RDS TLS · 커넥션 풀 튜닝, 롤백 · 컷오버 런북
```

`TypeScript` `Next.js` `NestJS` `Prisma` `PostgreSQL` `Terraform` `AWS` `Docker` `Kubernetes` `Cloudflare` `Playwright`

<br/>

### [`ops-platform`](https://github.com/YHK0427/ops-platform) &nbsp;·&nbsp; 유니브 피티 기수 관리 플랫폼

수기로 하던 정산 · 출결 · 과제 관리를 자동화. 설계부터 배포 · 운영까지 단독으로 맡았습니다.<br/>
WebSocket + Redis pub/sub 으로 멀티 워커 실시간 동기화, Docker Compose 5개 서비스 구성.

`React 19` `TypeScript` `Vite` `Tailwind` `shadcn/ui` `TanStack Query` `FastAPI` `SQLAlchemy 2.0` `Alembic` `PostgreSQL 16` `Redis 7` `ARQ` `Docker Compose` `Nginx` `Cloudflare Tunnel` `R2` `GitHub Actions`

<br/>

### [`BookFlowAI-Platform`](https://github.com/YHK0427/BookFlowAI-Platform) &nbsp;·&nbsp; 멀티클라우드 MSA 인프라

교보 DTS CDA 4기 팀 프로젝트. AWS · Azure · GCP 3개 클라우드에 걸친 마이크로서비스를 IaC 로 매일 자동 프로비저닝.

`CloudFormation` `Terraform` `Bicep` `Ansible` `EKS` `ECS` `Lambda` `RDS` `Kinesis` `Glue` `Step Functions` `Azure Functions` `Key Vault` `BigQuery` `Vertex AI` `CodePipeline` `GitHub Actions OIDC` `Transit Gateway` `WAF`

<br/>

### [`cloud-interview`](https://github.com/YHK0427/cloud-interview) &nbsp;·&nbsp; 클라우드 면접 준비 플랫폼

음성으로 묻고 답하는 모의 면접. AKS 위에 Helm 으로 배포하고 NetworkPolicy · RBAC · ResourceQuota 까지 구성.

`Python` `Flask` `SQLAlchemy` `MySQL 8` `Jinja2` `Gemini 2.5 Flash` `edge-tts` `Web Speech API` `Docker` `Kubernetes(AKS)` `Helm` `Traefik`

<br/>

### [`sql-agent`](https://github.com/YHK0427/sql-agent) &nbsp;·&nbsp; 자연어 → DB 쿼리 에이전트

비개발 직군이 DB 를 직접 조회할 수 있게. 동적 스키마 주입으로 환각을 줄이고 Few-shot 프롬프팅으로 정확도 보강.

`Python` `Flask` `Gemini API` `SQLite` `Mermaid.js` `openpyxl`

<br/>

### [`auto_selling`](https://github.com/YHK0427/auto_selling) &nbsp;·&nbsp; 키움증권 자동 매도 프로그램

조건에 맞으면 자동으로 매도. 데스크톱 앱으로 패키징해 배포.

`Python` `FastAPI` `SQLAlchemy` `Pydantic v2` `키움 OpenAPI` `React` `Electron` `Vite` `Tailwind`

<br/>

### [`daily_report`](https://github.com/YHK0427/daily_report) &nbsp;·&nbsp; 골든크로스 · 데드크로스 일일 판별기

매일 차트 데이터를 수집해 교차 시그널을 판별하고 텔레그램으로 리포트 발송.

`Python` `키움 OpenAPI` `pandas` `SQLite` `Telegram Bot API`

<br/>

<details>
<summary>&nbsp;<b>그 외</b></summary>
<br/>

- [`market-watcher`](https://github.com/YHK0427/market-watcher) — 시장 동향 리서치 · `LangChain` `LangGraph`
- [`BookFlowAI-Apps`](https://github.com/YHK0427/BookFlowAI-Apps) — BookFlowAI 배포용 애플리케이션 · `Python`
- [`NHN-Cloud-API-python-module`](https://github.com/YHK0427/NHN-Cloud-API-python-module) — NHN Cloud API 모듈화 · `Python`
- [`my-notion-quiz-maker`](https://github.com/YHK0427/my-notion-quiz-maker) — Notion 페이지를 퀴즈로 변환 · `JavaScript`
- [`cicd-pipeline`](https://github.com/YHK0427/cicd-pipeline) · [`aws_training_package`](https://github.com/YHK0427/aws_training_package) — AWS CI/CD 실습

</details>
