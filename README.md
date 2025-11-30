<h1 align="center">🏥 ELANIS - Elderly Care Services Platform</h1>
<h3 align="center">🔗 Connecting Families with Trusted Home Care Providers</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&width=535&lines=Nursing+%E2%80%A2+Elderly+Care+%E2%80%A2+Nannies+%E2%80%A2+Home+Care;Secure+Booking+%E2%80%A2+Verified+Providers+%E2%80%A2+Electronic+Payments;Transparent+Pricing+%E2%80%A2+Quality+Assurance+%E2%80%A2+Rating+System" alt="Typing SVG" />
</p>

---

## 📋 Table of Contents
- [Executive Summary](#-executive-summary)
- [Problem Analysis](#-problem-analysis)
- [Solution Overview](#-solution-overview)
- [Technical Architecture](#-technical-architecture)
- [Core Features](#-core-features)
- [Database Design](#-database-design)
- [Competitive Analysis](#-competitive-analysis)
- [Live Demo](#-live-demo)

---

## 🚀 Executive Summary

**Project Name:** ElAnis – Digital Platform for Home Care Services  
**Project Type:** Web Platform + API + Mobile-ready Architecture  
**Development Duration:** 8–10 weeks  
**Team Size:** 5 developers  
**Project Stage:** In Development  

### Vision
Create a One-Stop Shop platform combining:
- 👵 Elderly care
- 🏥 Home nursing 
- 👶 Nanny services
- 🏠 General home care services

Providing security, transparency, electronic payment, and accountability system.

---

## 🎯 Problem Analysis & Market Opportunity

### Current Market Challenges
- ❌ Difficulty in verifying service provider qualifications
- ❌ Absence of unified platform for nursing + care + nannies  
- ❌ Lack of transparency in pricing and availability
- ❌ Trust issues in sending individuals into homes
- ❌ Weak genuine rating system
- ❌ Disorganized payment methods

### Demographic Drivers
- 📊 Over 6.5 million citizens over 65 years in Egypt
- 👨‍👩‍👧‍👦 Working families need nannies and elderly caregivers
- 🦠 Preference for home care post-pandemic
- 💊 Chronic diseases requiring continuous monitoring

### Market Size
- 💰 Home Healthcare: $160.4M (2024) → $272.2M (2030) | 9.2% CAGR
- 👵 Elderly Care: $0.5B (2024) → $1.03B (2033)

---

## 💡 Solution Overview

### Business Model
<p align="center">
  <img src="https://via.placeholder.com/600x200/4F46E5/FFFFFF?text=Customers+%E2%86%92+Platform+%E2%86%92+Service+Providers" alt="Business Model" />
</p>

### Value Proposition
**For Customers:**
- ✅ Verified service providers
- 💰 Clear pricing
- 🔒 Secure booking & payment
- ⭐ Post-service ratings

**For Service Providers:**
- 📊 Full dashboard
- 📅 Availability scheduling  
- 💸 Income management
- ✅ Profile verification

**For Admin:**
- 👁️ Operational oversight
- ⚙️ Pricing & order control
- 📈 Performance monitoring
- 🛡️ Dispute management

---

## 🛠️ Technical Architecture

### Tech Stack
```yaml
Backend: ASP.NET Core 8 Web API
Frontend: React 18 + TypeScript + Tailwind
Database: SQL Server 2022
Authentication: JWT + Refresh Tokens
Payments: Stripe Gateway
File Storage: Cloudinary
Logging: Serilog
Email: SMTP / SendGrid
Hosting: Vercel (Frontend) + Railway (Backend)
Monitoring: Azure Application Insights
Key Technical Features
🔐 Secure Authentication with OTP verification

💳 Multiple Payment Methods (Stripe, Fawry, Vodafone Cash)

📁 Secure File Upload for documents & certificates

📧 Email Notifications for bookings & updates

📊 Real-time Dashboard for providers & admin

⚡ Core Features
Authentication & Security
csharp
// JWT Authentication with Refresh Tokens
services.AddAuthentication(JwtBearerDefaults.AuthenticationScheme)
    .AddJwtBearer(options => {
        options.TokenValidationParameters = new TokenValidationParameters {
            ValidateIssuer = true,
            ValidateAudience = true,
            ValidateLifetime = true,
            ValidateIssuerSigningKey = true
        };
    });
Service Management
🎯 Provider Verification (Documents, Certificates, Background checks)

📅 Availability Scheduling (90-day calendar, 3 shifts)

🔍 Advanced Search (Location, Rating, Price, Availability)

📱 Mobile-Responsive design

Booking & Payments






🗃️ Database Design
Key Entities
sql
-- Core Tables
Users (Id, Email, Phone, Role, ...)
ServiceProviders (Id, UserId, Bio, Experience, ...)  
ServiceRequests (Id, UserId, ProviderId, Status, ...)
Payments (Id, RequestId, Amount, Status, ...)
Reviews (Id, UserId, ProviderId, Rating, ...)
Categories (Id, Name, Description, ...)
Relationships
👥 Users ↔ ServiceProviders (One-to-One)

📋 Users → ServiceRequests (One-to-Many)

💰 ServiceRequests → Payments (One-to-One)

⭐ ServiceProviders → Reviews (One-to-Many)

📊 Competitive Analysis
Platform	Services	Focus
7keema	Home nursing, elderly care, nanny	Advanced medical care
Medical Care	Nursing, physical therapy, nanny	Medical + care services
Tamreed.net	24-hour nursing, ICU care	Critical cases
Home Care Egypt	Nannies, elderly caregivers	Supportive care
ElAnis Competitive Advantages
🎯 Comprehensive platform - All services under one roof

✅ Full verification + customer ratings + transparency

💳 Integrated booking & payment

🗺️ Geographical expansion potential

🏆 Higher training & quality standards

🎮 Live Demo
Test Accounts
yaml
Provider:
  Email: speezqndtotywxnohf@xfavaj.com
  Phone: 01020404892
  Password: P@ssw0rd123Pass

User:
  Email: xedrrvyzohqznrheif@fxavaj.com  
  Phone: 01027404829
  Password: P@ssw0rd123Pass

Admin:
  Email: admin@gmail.com
  Phone: 01224309198
  Password: P@ssw0rd123Pass
Live Application
🌐 Production Website: https://el-anis.vercel.app

⚙️ Admin Dashboard: https://el-anis.vercel.app/admin

📈 Future Roadmap
📱 Mobile App Development

🏥 Physical Therapy Services

🏠 Comprehensive Home Care expansion

🗺️ Geographical Expansion

🎓 Partnerships with Nursing Colleges

🏆 Summary
✅ Huge unsaturated market

✅ Ready development team

✅ Robust technical infrastructure

✅ Secure payment system

✅ Scalable platform architecture

✅ Clear vision for growth

<p align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=120&section=footer"/> <br /> <strong>Built with ❤️ for better home care in Egypt</strong> </p> ```
This README provides:

Professional presentation suitable for stakeholders

Comprehensive technical overview for developers

Business context for investors/clients

Live demo information with test accounts

Visual elements with badges, diagrams, and structured sections

Competitive analysis showing market positioning

Future roadmap for growth planning

The format follows GitHub best practices with proper markdown styling and includes all the key information from your comprehensive document in an engaging, easy-to-read format.

