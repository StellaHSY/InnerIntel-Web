### **Inner Intel (Web)**

[![](https://img.shields.io/badge/InnerIntel_Web-V1.0.0-blue.svg)]() [![](https://img.shields.io/badge/InnerIntel_Web-Issues-red.svg)](https://docs.google.com/spreadsheets/d/1npZpFK3Xic6fdqqMUoxf1sFYhxUc4z0dh4f2Bi-TVUE/edit?usp=sharing) [![](https://img.shields.io/badge/Landing_Page-URL-green.svg)](https://personalisednutrition.github.io) 

---

> Web application for nutritionists

#### 01_Development background

The S.A.Y. team has developed Inner Intel, a Java-based app for Android.
After understanding the needs of nutritionists, the team decided to continue to develop an Inner Intel web-based application that would meet the needs of nutritionists to Contact and guide general users in dietetics.

---

#### 02_Technical selection

1. **System environment**
   - Windows
   - (Browser version limit)

2. **Main framework**
   - (if any)

---

#### 03_Main Features.

- Shared database with the Inner Intel java side serving regular users.
- There is a complete permission management system.
- There is a comprehensive privacy protection policy.

---

#### 04_Main Functions

- Allows visual viewing of user-specific data.
- The java side of the specified user can be set up by nutritionists.
- nutritionists can view the system's analysis of the specified user's data.
- nutritionists can upload data analysis reports from nutritionists.

---

#### 05_API

(If any)

---

#### 06_Development Plan

```mermaid
 gantt 
        dateFormat  MM-DD
        title Development Plan 
        section Preparation
        Work handover & Demand communication		:done,p0, 07-25,07-31
        Adjust demands                          	:done,p1, 07-31,08-08
        
        section Web Development 
        Front-end design                        	:active,d0,08-08,08-21
        prototype                                   :active,d1,08-13,08-21
        Back-end design(UML)						:d2,after d1,09-04
        Basic function								:d3,after d2,09-18
        Buffer Week									:d4,after d3,09-25
        Business logic development					:d5,after d4,14d
        Front-end and back-end docking & optimization :d6,after d5,7d
        
        section Database Development 
        Database Development_01						:active,dd0,08-08,09-18
        Buffer Week									:d4,after d3,09-25
        Database Development_02						:active,dd1,after d4,10-23
        
        section Data Collection
        Form creation								:active,c0,08-15,7d
        Form adjustment								:c1,after c0,7d
        Data collection								:c2,after c1,10-28
        Data Cleaning								:c3,09-19,14d
        
        section Test
        Interface testing and functional testing 	:t0,after d6,10-23
        
        section Handover
      	Work handover								:h0,after t0,10-28
```

---

#### 07_Group S.A.Y. Team Members

| Name        | title                         | Email               |
| ----------- | ----------------------------- | ------------------- |
| Shuyi Chen  | Spokesperson, Project Manager | u7175274@anu.edu.au |
| Yuhao Zhai  | Spokesperson, Project Manager | u7152566@anu.edu.au |
| Xinyue Hu   | Database Manager              | u7151386@anu.edu.au |
| Hengtong Wu | Database Engineer             | u7235221@anu.edu.au |
| Tianqi Tang | Techinical Lead               | u7192230@anu.edu.au |
| Shiyun Zhu  | Web Developer                 | u7041419@anu.edu.au |
| Siyuan He   | Web Developer                 | u7344524@anu.edu.au |

---

#### 08_License

None

---

#### 
