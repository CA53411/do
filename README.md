# Corolas 网络调查团队

ordo.corolas.top | Corolas子项目

## 简介
网络调查与舆情分析团队平台，提供数据采集、分析和报告生成工具。

## 技术栈
- Frontend: React 19 + TypeScript + Vite
- Styling: Tailwind CSS + shadcn/ui
- Backend: Supabase (Auth + PostgreSQL + Edge Functions)
- Deploy: Vercel (GitHub Push → Auto Deploy)
- CI/CD: GitHub Actions

## 环境变量
| 变量 | 说明 |
|------|------|
| VITE_SUPABASE_URL | Supabase项目URL |
| VITE_SUPABASE_ANON_KEY | Supabase Anon Key |

## 数据库
Supabase项目: https://supabase.com/dashboard/project/corolas-do

## 本地开发
```bash
git clone https://github.com/CA53411/do.git
cd do
npm install
npm run dev
```

## 部署
Push到main分支自动触发Vercel部署
