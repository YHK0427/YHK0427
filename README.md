<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=200&section=header&text=Youngheon%20Kim&fontColor=ffffff&fontSize=48&desc=Backend%20Developer%20%26%20Infrastructure%20Engineer&descAlignY=68&descSize=18)

제품을 직접 만들고, 그게 돌아갈 인프라까지 직접 깝니다.<br/>
애플리케이션의 불편에서 출발해 배포·운영까지 책임지는 걸 좋아합니다.

![Sejong](https://img.shields.io/badge/Sejong%20Univ.-CE0E2D?style=flat-square&logoColor=white)
![Focus](https://img.shields.io/badge/Backend-2C5364?style=flat-square) ![Focus2](https://img.shields.io/badge/Cloud%20%C2%B7%20DevOps-203A43?style=flat-square)
[![Gmail](https://img.shields.io/badge/-bleach10905@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:bleach10905@gmail.com)

</div>

## 🧰 Tech Stack

**Cloud & Infra**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)

**Backend**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)

## 🚀 Projects

### 🔒 aesthet — 커머스 플랫폼 _(private)_

프로덕션 서비스의 백엔드 개발과 인프라를 맡고 있습니다.

- **Backend** — NestJS + Prisma + PostgreSQL. 주문·정산·배송추적·클레임 도메인 개발
- **Frontend** — Next.js 기반 구매자 / 판매자 / 관리자 3개 앱, Playwright E2E
- **Infra** — 홈서버 Kubernetes → AWS 이관. Terraform 으로 VPC·EC2·RDS·SSM·CodeBuild 모듈화
- **운영** — Cloudflare Tunnel 무인바운드 구성, SSM Session Manager 접속, RDS TLS·커넥션 풀 튜닝, 롤백 스크립트와 컷오버 런북

`TypeScript` `NestJS` `Next.js` `PostgreSQL` `Terraform` `AWS` `Docker` `Kubernetes`

<br/>

| Repo                                                                      | 설명                                                                               | Tech         |
| :------------------------------------------------------------------------ | :--------------------------------------------------------------------------------- | :----------- |
| [**ops-platform**](https://github.com/YHK0427/ops-platform)               | 유니브 피티 기수 관리 플랫폼. 수기 정산·출결·과제를 자동화, 혼자 설계부터 운영까지 | `TypeScript` |
| [**BookFlowAI-Platform**](https://github.com/YHK0427/BookFlowAI-Platform) | 교보 DTS CDA 4기 팀 프로젝트                                                       | `Python`     |

- [**BookFlowAI-Apps**](https://github.com/YHK0427/BookFlowAI-Apps) — BookFlowAI 배포용 애플리케이션
  | [**cloud-interview**](https://github.com/YHK0427/cloud-interview) | 클라우드 면접 준비 플랫폼 | `CSS` |
  | [**sql-agent**](https://github.com/YHK0427/sql-agent) | 자연어를 DB 쿼리로 바꿔주는 LLM 에이전트 | `Python` |
  | [**auto_selling**](https://github.com/YHK0427/auto_selling) | 키움증권 자동 매도 프로그램 | `Python` |
  | [**daily_report**](https://github.com/YHK0427/daily_report) | 키움증권 골든크로스·데드크로스 일일 판별기 | `Python` |

<details>
<summary><b>그 외</b></summary>

- [**market-watcher**](https://github.com/YHK0427/market-watcher) — LangChain / LangGraph 기반 시장 동향 리서치
- [**NHN-Cloud-API-python-module**](https://github.com/YHK0427/NHN-Cloud-API-python-module) — NHN Cloud API 모듈화
- [**my-notion-quiz-maker**](https://github.com/YHK0427/my-notion-quiz-maker) — Notion 페이지를 퀴즈로 변환
- [**cicd-pipeline**](https://github.com/YHK0427/cicd-pipeline) · [**aws_training_package**](https://github.com/YHK0427/aws_training_package) — AWS CI/CD 실습

</details>

## 📈 Stats

<div align="center">

![stats](https://github-readme-stats.vercel.app/api?username=YHK0427&show_icons=true&hide_border=true&theme=tokyonight&include_all_commits=true&count_private=true)
![langs](https://github-readme-stats.vercel.app/api/top-langs/?username=YHK0427&layout=compact&hide_border=true&theme=tokyonight&langs_count=8)

</div>

<div align="center">

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=120&section=footer)

</div>
