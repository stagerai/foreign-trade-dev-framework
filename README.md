# Foreign Trade Customer Development Framework

A systematic, AI-powered framework for B2B overseas customer development. Built around the Yi-Bing 7-Round Email Method + Writer-Critic quality control system.

## Who This Is For

- B2B exporters / manufacturers looking to systematically develop overseas customers
- Sales teams who want a repeatable, quality-controlled cold outreach process
- Anyone using AI (Claude Code, Copilot, etc.) to assist with customer development

## What This Provides

- **Complete SOP** for customer development lifecycle (research → contact → follow-up → close)
- **Yi-Bing 7-Round Email Method** — a proven cold email strategy with differentiated angles per round
- **Writer-Critic Quality System** — mandatory dual-role review ensuring every email meets ≥95/100 before sending
- **Multi-Contact Strategy** — role-based email customization for different stakeholders at the same company
- **Multi-Customer Batch Management** — progress tracking for 20+ customers simultaneously
- **Hypothesis Validation Framework** — data-driven strategy optimization
- **AI Agent Configuration** — drop-in CLAUDE.md and AGENTS.md for Claude Code / OpenClaw

## Quick Start

### 1. Clone & Configure

```bash
git clone https://github.com/stagerai/foreign-trade-dev-framework.git
cd foreign-trade-dev-framework
```

### 2. Fill In Your Product Info

Edit `公司产品档案.md` with your:
- Company/brand name and website
- Core product specs and selling points
- Competitive positioning vs key rivals
- Verified customer cases (anonymized)
- Business terms (lead time, warranty, certifications)

### 3. Set Up AI Agent

The `CLAUDE.md` and `AGENTS.md` files are pre-configured AI agent entry points. Drop this directory into any AI coding tool (Claude Code, OpenClaw, etc.) and the agent will automatically:
- Follow the startup recovery sequence
- Enforce the Writer-Critic review process
- Track all customer progress via `开发状态总览.md`

### 4. Work Through the SOP

```
1. Define your ideal customer profile (01-策略与画像/)
2. Search for target customers in your target market
3. For each customer:
   a. Create customer profile (follow the example at 02-示例市场/)
   b. Draft emails following 00-SOP/邮件起草完整流程.md
   c. Score with Writer self-check → Critic review → ≥95/100 → Send
   d. Archive after sending (log → summary + move to contact records)
4. Track all progress in 开发状态总览.md
```

### 5. Follow Up

- Intervals: 7-7-7-14-14-14 days between rounds
- Check replies on scheduled dates via your email client
- Adjust strategy based on response type

## Methodology Overview

### Yi-Bing 7-Round Email Method

| Round | Strategy | Length | CTA |
|-------|----------|--------|-----|
| 1 | Ultra-short intro | 30-50 words | Interested? |
| 2 | Case proof | 50-70 words | Want details? |
| 3 | Supplier angle | 40-60 words | Want to compare? |
| 4 | Break-the-ice | 30-40 words | Yes or No? |
| 5+ | Soft touch | 30-50 words | Stay in touch |

**Core principle:** Each round uses a completely different angle. Repeating the same angle = customer deletes.

### Writer-Critic Quality System

- **Writer**: Drafts emails only — forbidden from scoring
- **Critic**: Scores independently — forbidden from editing
- **Pass threshold**: ≥95/100 on Critic review
- Red lines: generic subject lines, repeated angles, high-barrier CTAs → automatic rewrite

## File Structure

```
foreign-trade-dev-framework/
├── README.md                    ← You are here
├── CLAUDE.md                    ← AI agent entry point
├── AGENTS.md                    ← OpenClaw entry point
├── 公司产品档案.md                ← YOUR product info (fill this in first!)
├── 开发状态总览.md                ← Master progress tracker
│
├── 00-SOP/                      ← Standard Operating Procedures
│   ├── 客户开发标准作业程序.md
│   ├── 邮件起草完整流程.md         ← Email drafting authority
│   ├── 多联系人开发流程.md
│   └── 多客户批量开发流程.md
│
├── 01-策略与画像/                 ← Strategy & hypothesis testing
│   ├── 客户假设验证框架.md
│   └── 假设验证总表.md
│
├── 02-示例市场/                   ← Example customer (fictional)
│   └── 示例-哥伦比亚/
│       └── ExampleCo/
│           ├── 00_ExampleCo 客户档案.md
│           ├── 01_开发日志.md
│           └── 联系人沟通记录/
│
├── 模板/                         ← All templates & checklists
│   ├── 邮件评分检查表.md          ← Writer self-scoring
│   ├── 邮件Critic评审表.md        ← Critic blind review
│   ├── 邮件归档规则.md
│   └── 邮件模板库/                ← Round-by-round email templates
│
├── .gitignore
└── LICENSE
```

## Key Rules

- **Subject lines must be specific** — mention customer's business, pain point, case city, or numbers. Never use "Partnership opportunity" or "Best price"
- **CTA must be low-barrier** — 1 word to reply (Interested? / Yes or No?)
- **Never repeat angles** — each follow-up email must use a completely different approach
- **Archive after sending** — dev log → summary table, full text → contact record
- **Follow-up intervals**: 7-7-7-14-14-14 days (do not email more frequently)

## Customization

This framework was originally built for industrial hardware (PoE++ switches) sales to Latin America. To adapt for your industry:

1. Replace product info in `公司产品档案.md`
2. Adjust email angles in `00-SOP/邮件起草完整流程.md` if needed
3. Modify the customer profile template in `模板/` to match your ICP fields
4. Update competitive positioning tables
5. The core methodology (7-round emails, Writer-Critic, batch management) is industry-agnostic

## Contributing

Contributions welcome! Areas where help is appreciated:
- Translations (English, Spanish, Portuguese versions of templates)
- Industry-specific email angle packs
- Integration with CRM tools
- A/B testing data and strategy refinements
- Additional SOPs (trade show follow-up, LinkedIn outreach, etc.)

Open an issue or PR.

## License

MIT — see LICENSE file.

## Disclaimer

This is a **framework/template**. All customer names, company names, email addresses, and product details in the example files are **fictional** and for demonstration purposes only. Replace them with your own data before use.
