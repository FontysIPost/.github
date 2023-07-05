# 📬 Fontys Internal Post (FIPost)

FIPost is a fast and efficient opensource internal post website and app for Fontys,
this repository contains multiple API which is responsible for different functionality in a microservice architecture.
Keep in mind that this project is broader than just the FHICT.

This project is part of a long term pilot and is supposed to be developed over multiple semesters
by different groups of 6~ software engineer students. Transferability is therefore a must.

6s > s3 > s6 > year pause > s6 team (current)

### ✉️ Contact Us
Mandatory to [join the Discord server!](https://discord.gg/3xFK8ZAA3d) The project overseer will guide you to setup the project if needed and other further inquiries.
There were some bad management and documentations for the past years so this ends now, rapid development for `2023FALL+` made by `2023SPRING` students.

## 🎯 Goals

* This project aims to modernise the internal post system of Fontys. Currently most of the administrative work is done manually.

* This project moves these processes to a semi-automated system with similar functionalities as PostNL.
  Some of the features include: seeing a package status and tracing locations.

* This project is designed with a microservices architecture to scale and manage the administrative post process of the entire Fontys organisation
  with over 5000 employees and 44.000 students. So this allows us to scale our software to support a large user base.

* To separate all concerns and keep the repositories SOLID each domain has been given each own codebase with its own repository.
  This is also to help maintain collaboration efficiently and opensource.

### 📐Stack
- **Node version:** 14.15.5
- **NPM version:** 6.14.11
- **Frontend: **[VueJS](https://vuejs.org/guide/introduction.html) - HTML/[SCSS](https://sass-lang.com/documentation/syntax)/JavaScript and [TypeScript](https://www.typescriptlang.org/docs/)
- **Backend: **[.NET 6](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-aspnetcore-6.0.0-windows-x64-installer)
-  IIS(Internet Information Services)
