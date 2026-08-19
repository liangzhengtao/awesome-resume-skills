# ATS Optimization Skill

> Maximize your resume's compatibility with Applicant Tracking Systems.

## When to Use

- Submitting resume through any online application portal
- When you suspect your resume is being filtered out before human review
- Applying to large companies that process thousands of applications
- When the job posting specifically mentions applying through their careers page

## Framework

### How ATS Works

```
┌─────────────────────────────────────────────────────────────┐
│                    ATS PROCESSING FLOW                       │
│                                                             │
│  [Resume Upload] → [Parsing] → [Indexing] → [Ranking] →    │
│  [Recruiter Search/Filter] → [Human Review] → [Interview]   │
│                                                             │
│  YOUR GOAL: Ensure your resume is correctly parsed,          │
│  indexed with the right keywords, and ranks highly           │
│  for relevant searches.                                      │
└─────────────────────────────────────────────────────────────┘
```

### ATS Compatibility Rules

| DO | DON'T |
|----|-------|
| Use standard headings | Use creative section names |
| Use simple bullet points (•, -) | Use custom symbols or emojis |
| Use standard fonts | Use decorative fonts |
| Include keywords naturally | Stuff keywords out of context |
| Use both acronym and full form | Use only acronyms |
| Save as PDF or DOCX | Use JPG, PNG, or HTML |
| Use simple tables | Use complex multi-column layouts |
| Put contact info in body | Use headers/footers for key info |
| Use standard date formats | Use ambiguous date formats |

### Common ATS Systems

| ATS | Notes |
|-----|-------|
| **Workday** | Used by Fortune 500; parse PDF well; avoid tables |
| **Greenhouse** | Startup-friendly; good PDF parsing; structured forms |
| **Lever** | Similar to Greenhouse; good with standard formats |
| **Taleo** (Oracle) | Enterprise; older; struggles with fancy formatting |
| **iCIMS** | Enterprise; strict parsing; test your PDF |
| **BambooHR** | SMB; simpler parsing; generally forgiving |
| **SmartRecruiters** | Mid-market; decent parsing |
| **Ashby** | Modern; good PDF parsing |

## Templates

### ATS-Optimized Resume Template

```
[FIRST LAST]
[City, State] | [Phone] | [Email] | [LinkedIn URL]

PROFESSIONAL SUMMARY
[Title] with [X] years of experience in [industry/specialization].
Proven track record of [key achievement 1] and [key achievement 2].
[Key skill] professional with expertise in [area].

WORK EXPERIENCE

[Job Title]
[Company Name] — [City, State]
[Start Date] – [End Date]

• [Achievement with keywords from job description]
• [Achievement with metrics]
• [Achievement demonstrating required skill]
• [Achievement with measurable impact]

[Previous Job Title]
[Company Name] — [City, State]
[Start Date] – [End Date]

• [Achievement with keywords from job description]
• [Achievement with metrics]
• [Achievement demonstrating required skill]

EDUCATION

[Degree Type] in [Major]
[University Name] — [City, State]
[Graduation Date]

SKILLS
[Skill 1], [Skill 2], [Skill 3], [Skill 4], [Skill 5],
[Skill 6], [Skill 7], [Skill 8], [Skill 9], [Skill 10]

CERTIFICATIONS
[Certification Name] — [Issuing Organization] — [Date]
```

### ATS Checklist Template

```
PRE-SUBMISSION ATS CHECKLIST

□ FORMAT
  □ Standard fonts (Calibri, Arial, Times New Roman, Georgia)
  □ Font size 10-12pt for body, 14-16pt for name
  □ 0.5" to 1" margins
  □ Single column layout
  □ Standard bullet points only
  □ No tables for critical content
  □ No text boxes, shapes, or graphics
  □ No headers or footers with important info
  □ File format: PDF (preferred) or DOCX

□ CONTENT
  □ Standard section headings used
  □ Contact info in body (not header)
  □ Keywords from job description included naturally
  □ Both acronyms and full forms (e.g., "Search Engine Optimization (SEO)")
  □ Dates in consistent format (MM/YYYY or Month YYYY)
  □ Quantified achievements (numbers, percentages, dollar amounts)
  □ No spelling or grammar errors
  □ File name: [First]-[Last]-Resume.pdf

□ KEYWORDS
  □ Hard skills from posting included
  □ Soft skills from posting included
  □ Industry terminology included
  □ Required certifications listed
  □ Both spelled-out and abbreviated forms included

□ TESTING
  □ Parsed resume content in a text editor (copy-paste test)
  □ Used ATS score checker (JobScan, ResumeWorded, etc.)
  □ All critical info survived parsing
```

### Keyword Mapping Template

```
JOB DESCRIPTION KEYWORD MAP

| Job Requirement        | Resume Location                | Match? |
|----------------------|--------------------------------|--------|
| [Required skill 1]   | [Section + bullet point]       | ✅     |
| [Required skill 2]   | [Section + bullet point]       | ✅     |
| [Required tool 1]    | [Skills section + experience]  | ✅     |
| [Preferred cert]     | [Certifications section]       | ✅     |
| [Years required]     | [Summary + experience dates]   | ✅     |
| [Nice-to-have]       | [Not on resume]                | ❌     |

COVERAGE: [X]/[Y] required keywords matched = [Z]%
TARGET: ≥ 80% keyword coverage for required qualifications
```

## Examples

### Before & After: ATS Formatting

**Before (ATS-unfriendly):**
```
┌─────────────────────────────────────────────────────┐
│  JOHN DOE                    ☎ 555-0123             │
│  ─────────────────────────   ✉ john@email.com       │
│  Senior Developer             🔗 linkedin.com/in/jd  │
│                                                     │
│  ┌─── EXPERIENCE ────┐  ┌─── SKILLS ───────────┐   │
│  │                   │  │                       │   │
│  │  Company A  2022  │  │  ████████ Python      │   │
│  │  - Did stuff      │  │  ██████░░ React       │   │
│  │                   │  │  ████░░░░ AWS         │   │
│  └───────────────────┘  └───────────────────────┘   │
└─────────────────────────────────────────────────────┘
```

**After (ATS-friendly):**
```
John Doe
San Francisco, CA | (555) 555-0123 | john.doe@email.com
linkedin.com/in/johndoe

PROFESSIONAL SUMMARY
Senior Software Developer with 8+ years of experience building
scalable web applications. Expertise in Python, React, and AWS.

WORK EXPERIENCE

Senior Software Developer
Company A — San Francisco, CA
January 2022 – Present

• Developed Python-based microservices handling 50K requests/day
• Built React frontend with TypeScript, improving page load by 40%
• Deployed applications on AWS (EC2, S3, Lambda, RDS)

SKILLS
Python, React, TypeScript, JavaScript, AWS (EC2, S3, Lambda, RDS),
PostgreSQL, Docker, Kubernetes, CI/CD, Agile/Scrum
```

### Before & After: Keyword Optimization

**Before (missing keywords):**
```
Summary: Developer with experience building websites and apps.
```

**After (keyword-rich):**
```
Summary: Senior Full-Stack Software Developer with 8+ years of
experience building scalable web applications using Python, React,
TypeScript, and AWS cloud services. Proven track record in agile
development, REST API design, CI/CD pipeline implementation, and
cross-functional team collaboration.
```

*(Keywords extracted from job posting: "full-stack", "Python", "React", "TypeScript", "AWS", "agile", "REST API", "CI/CD", "cross-functional")*

### ATS Parsing Test

To check if your resume parses correctly:

```
1. Open your PDF resume
2. Select All (Ctrl+A)
3. Copy (Ctrl+C)
4. Paste into a plain text editor (Notepad)
5. Check:
   - Is all text readable?
   - Are sections in correct order?
   - Is contact info present?
   - Are bullets preserved?
   - Is any text missing or garbled?
```

## Common ATS Issues

| Issue | Cause | Fix |
|-------|-------|-----|
| Missing text | Text in headers/footers | Move to body |
| Garbled characters | Unusual fonts/encoding | Use standard fonts |
| Missing sections | Non-standard headings | Use "Experience", "Education" |
| Wrong order | Multi-column layout | Use single column |
| Missing contact | Text box or image | Plain text in body |
| Broken bullets | Custom symbols | Use • or - |
| Date not parsed | Unusual format | Use MM/YYYY |

---

## 中文版本

### 适用场景

- 通过任何在线申请系统提交简历
- 怀疑简历在人工审核前被系统过滤
- 申请大公司（处理大量简历）

### 中文ATS注意事项

国内主流招聘系统（如BOSS直聘、拉勾、猎聘）的简历解析能力较弱：

- **格式要求**：建议使用纯文本或标准Word格式
- **关键词**：使用职位描述中的原词，不要用同义词
- **照片**：国内系统通常支持照片上传
- **排版**：避免复杂的表格和图文混排

### 国内招聘平台ATS特点

| 平台 | 特点 |
|------|------|
| BOSS直聘 | 对话式，简历格式要求低 |
| 拉勾 | 结构化填写，PDF简历辅助 |
| 猎聘 | 中高端，支持附件简历 |
| 前程无忧 | 传统，需要填写在线简历 |
| 智联招聘 | 传统，支持附件简历 |
| 脉脉 | 社交招聘，个人主页很重要 |
