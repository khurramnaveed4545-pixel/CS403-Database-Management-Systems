# Lecture 1 of DBMS ( Database Managment Systems ) 

## Overview of Lecture

Is lecture ka overview ye hai ke hum **Database Management System (DBMS)** ke basic concepts ko samajhne wale hain.  
Sabse pehle course ka introduction hoga, phir hum database ki definitions dekhenge, phir samjhenge ke databases ki importance kya hai aur woh traditional file processing system se kis tarah behtareen hain.  
Akhir mein, hum DBMS ke advantages ko discuss karenge.  

---

## Introduction to the Course

Ye course **DBMS** par hai — yaani *Database Management System*.  
Is course ka maqsad aapko yeh sikhana hai ke database kya hota hai, woh kis tarah design aur manage kiya jata hai, aur usay real-life applications mein kis tarah use kiya jata hai.  

Course ke dauran aap seekhenge:  
- Architecture  
- Queries (SQL)  
- Normalization  
- Transaction management  
- Backup/Recovery  

Ye course students ko ek **base** deta hai jo unhein programming aur real-world projects mein databases ke sahi istemal ki taraf le jata hai.  

---

## Database Definition to remmber for exam point of view 

**Database is a shared collection of logically related data designed to meet the information needs of multiple users of an organziations**

  Database aik shared collection hoti hai logically related data ki, jo kisi organization ke multiple users ki information needs ko poora karne ke liye design ki jati hai.

**Misal:**  

Agar ek university apne students ka record rakhna chahe — unke naam, roll number, courses, marks — to yeh sab aik structured form mein database ke andar rakha jata hai.  

Database ke peeche jo software system hota hai jo data ko manage karta hai, usay **DBMS** kehte hain.  

---

## Importance of the Databases

In today’s world, databases have become extremely important because every organization needs to store and process its data in a structured way.

**Examples include:**

- Banks use databases to store customer information and transaction records.
- Hospitals maintain patients’ medical histories and treatment details in databases.
- E-commerce websites manage their product listings, customer orders, and payment records using databases.

**Without databases** , it would be very difficult to handle information in an organized, secure, and reliable manner. That is why databases are considered the backbone of modern systems.

Aaj ke daur mein database ki ahmiyat bohot zyada hai kyunki har organization apna data store aur process karna chahti hai.  

**Examples:**  

- Banks apna customer aur transaction data database mein store karte hain.  
- Hospitals patients ka medical record database mein rakhte hain.  
- E-commerce websites products aur orders ka data database mein rakhti hain.  

Databases ke bina information ka structured aur secure tariqe se handle karna mushkil ho jata.  
Is liye databases har modern system ki **backbone** ban gaye hain.  

---

## Databases and Traditional File Processing Systems

Before the use of DBMS, people relied on traditional file processing systems. In this approach, data was stored in separate files such as text documents or spreadsheets.

However, this method had several problems:

- **Data redundancy:** The same data was often stored multiple times in different files.
- **Lack of synchronization:** If a change was made in one file, it was not automatically updated in other related files.
- **Poor data consistency:** Maintaining accurate and consistent information across files was difficult.
- **Weak security and sharing:** There was no proper system for controlling access or allowing multiple users to work on data simultaneously.

DBMS solved all these issues. With a database system, data is stored in a centralized and controlled environment where multiple users can work together, while ensuring the data remains consistent, secure, and reliable.

Pehle jab DBMS nahin hota tha to log **file processing system** use karte the. Matlab data alag-alag files mein text form ya spreadsheets mein rakha jata tha.  

**Masail:**  
- Data redundancy barh jati thi (ek hi data bar bar duplicate hota).  
- Agar ek jagah change karen to dusri jagah update nahi hota tha.  
- Data consistency maintain karna mushkil hota tha.  
- Security aur concurrent access ka proper system nahi hota tha.  

DBMS ne in tamam masail ka solution diya.  
Ab data **centralized aur controlled environment** mein rakha jata hai jahan multiple users ek saath kaam karte hain aur data consistent rehta hai.  

---

## Advantages of Databases

- **Reduced Redundancy** – Duplicate data is minimized, preventing unnecessary repetition.
- **Data Consistency** – Every user can access the most updated and accurate data.
- **Enhanced Security** – Access control and authentication ensure that only authorized users can view or modify the data.
- **Concurrent Access** – Multiple users can work with the database at the same time without conflicts.
- **Backup and Recovery** – In case of a system failure, the database allows data to be restored.
- **Data Integrity** – Rules and constraints can be applied to maintain accuracy and validity of the data.

Databases ke kuch major faide ye hain:  

1. **Reduced Redundancy** – Duplicate data avoid hota hai.  
2. **Data Consistency** – Har user ko updated aur correct data milta hai.  
3. **Security** – Access controls aur authentication ki wajah se sirf authorized log hi data dekh ya modify kar sakte hain.  
4. **Concurrent Access** – Multiple users ek waqt par data use kar sakte hain bina conflicts ke.  
5. **Backup and Recovery** – Agar system crash ho jaye to database se data recover ho sakta hai.  
6. **Integrity** – Rules lagaye ja sakte hain jisse data correct aur valid rahe.

# Summary – Database (Exam-Oriented)

**Database (DB)** wo shared collection hai logically related data ki jo kisi organization ke multiple users ki information needs ko poora karne ke liye design ki jati hai.

---

## 1. Basics
- **Data** = kisi bhi cheez ke facts / ma’lumaat.  
- **Logically Related Data** = sirf woh facts jo organization ke maqsad ke liye mufeed hon.  
- **Different Users** = Accounts, Production, Marketing, HR, etc.  
  → Sab ki alag-alag zarooratain aik hi DB se serve hoti hain.

---

## 2. Database Design Steps
1. Requirements gathering  
2. Design stages (conceptual → logical → physical)  
3. Final product

---

## 3. Real-Life Importance
- **Banking** (ATM, online transfer)  
- **Airlines** (reservation, check-in)  
- **Telecom** (billing, call records)  
- **Universities** (registration, exams, library)  
- **Scientific Research** (experiments, results)

---

## 4. Key Definitions *(remember any ONE)*
1. *“A logically related collection of data stored to meet the requirements of different users of an organization.”*  
2. *“A shared collection of integrated records.”*  
3. *“A computerized representation of a particular real-world system in the form of data.”*

---

## 5. File Processing vs Database Approach

| Aspect | File Processing | Database Approach |
|---|---|---|
| **Data Storage** | Separate files per department | Single shared DB |
| **Redundancy** | High (duplicate data) | Low |
| **Consistency** | Risk of inconsistency | Controlled integrity |
| **Program-Data Dependence** | High (change in one → change in both) | Low (independence) |

---

## 6. Advantages of DB Approach
- **Data Sharing**  
- **Minimal Redundancy**  
- **Data Integrity & Constraints**  
- **Program-Data Independence** *(change in data rarely affects programs and vice-versa)*

---

## 7. Exam Tip
- Definition + **Logically Related Data** + **Shared Collection** zaroor likhain.  
- Diagram bhi yaad rakhen: single DB at center, multiple user-groups around it.

--- 

# Lecture 2 of DBMS ( Database Managment Systems )

# Table of Contents

1. **Difference between Data and Information**
2. **Further Advantages of Database Systems** 
3. **Cost Involved**
4. **Importance of Data** 
5. **Levels of Data** 
6. **Users of Database Systems** 

# 1. Difference between Data and Information  

**Data**  
- Data is a collection of raw facts collected from any place or situation for a specific purpose.  
- By itself, data does not give clear meaning or understanding about its environment.  

**Information**  
- When we process data (using methods, rules, or calculations), it becomes useful and meaningful.  
- This meaningful form of data is called **Information**.  

### Example:  
- **Data**: Marks of students in different subjects (e.g., 75, 80, 90).  
- **Information**: A report showing the average marks and overall performance of the class.
  
--- 

# 2. Further Advantages of Database Systems:

Database systems are very much beneficent to enterprises and businesses, some of the advantages are listed below:

- Data consistency
- Better data security
- Faster development of new applications
- Economy of scale
- Better concurrency control
- Better backup and recovery procedures


### Data Consistency  
- Data consistency means that whenever changes are made to data, all copies of that data should be updated in the same way.  
- This ensures that the same data item always has the same value everywhere.  
- If consistency is not maintained, problems like **loss of information** or **wrong results** may occur.  
- In databases, consistency is controlled because data is stored in a shared and managed way.  

---

### Better Data Security  
- All application programs access data through the **DBMS**.  
- DBMS checks **which user** is performing **which action** and accessing **which part of the data**.  
- This way, DBMS provides strong **security** and ensures that only authorized people can access sensitive information.  

---

### Faster Application Development  
- Databases allow faster development of new applications because they are designed with **future needs** in mind.  
- When building a new application:  
  - The required data may already exist in the database.  
  - If not, it can often be **derived** from existing data.  
- This means **less effort** is required for system and database design when new applications are developed.  

---

### Economy of Scale  
- Databases store data in **one place** and allow it to be used for **many purposes**.  
- The same data does not need to be stored multiple times in different forms.  
- Example:  
  - Student data collected by the **Admission Department** can also be used for **attendance records** and **exam results**.  
- This saves **time, effort, and cost**, providing **economy of scale**.  

---

### Better Concurrency Control  
- **Concurrency** means many users accessing the database at the same time.  
- DBMS controls this concurrency so that all operations are completed **correctly** without conflicts.  
- Example:  
  - ATMs of a bank are connected to a central database worldwide.  
  - Thousands of users withdraw money at the same time, but the database system handles all requests efficiently without delays or errors.  

---

### Better Backup and Recovery Facility  

- Data is a very **valuable resource** for any organization. Losing it can cause serious damage.  
- DBMS provides excellent facilities for:  
  - **Taking backups** regularly.  
  - **Restoring data** from backups in case of data loss.
    
- **Example:**
  - If a system crashes after important transactions are made, DBMS can recover the database to a **consistent state** so that no important data is lost.
 
--- 

# 3. Cost Involved: 

### High Cost  
 
Database systems come with several built-in costs. One of the major costs is the requirement of specialized software to run the database, additional hardware, and technically skilled staff. To fulfill all these requirements, an organization needs to invest a large amount of money.  

**Simple words men**  
Database systems ke sath kuch built-in kharchay hote hain. Sabse bara kharcha specialized software ka hota hai jo database chalane ke liye chahiye hota hai, phir extra aur specialized hardware ki zarurat hoti hai, aur technically skilled staff ki bhi requirement hoti hai. In sab cheezon ko pura karne ke liye organization ko acha khasa paisa invest karna parta hai.  

---

### Conversion Cost  
 
When an organization decides to move to a database system, it is not only financial and technical manpower that is required. There are also conversion costs involved in switching from the old system to the database system. This stage is very important because the organization must decide how the existing system will be converted into the new database environment.  

**Simple words men**  
Jab ek organization database system par shift karne ka faisla karti hai, to sirf paisa aur technical manpower hi nahi chahiye hota. Conversion costs bhi hoti hain jo purane system ko nayi database environment mein convert karne ke liye lagti hain. Ye stage bohot important hota hai kyunki is waqt decide karna hota hai ke purane system ko database system mein kaise convert kiya jaye.  

---

### Difficult Recovery Procedures  

Although database systems provide efficient methods for data recovery after a disaster, the process of recovering a crashed database is still highly technical. It requires professional skills and expertise to perform proper recovery and bring the system back to a consistent state.  

**Simple words men**  
Halaanke database systems data recovery ke efficient tareeqay dete hain jab koi disaster ho, lekin crashed database ko recover karna phir bhi bohot technical process hota hai. Iske liye professional skills aur expertise ki zarurat hoti hai taake recovery sahi tareeqay se ho aur system wapis consistent state mein aa jaye.  

# 4. Importance of Data 

## Data as a Resource  

A resource is anything that is valuable for an organization. An organization can have many resources, such as buildings, furniture, vehicles, technical staff, managers, supporting staff, and machinery. All these resources are used carefully to get maximum benefit. In the same way, data is also a very important resource and should be considered equally important as other resources.  

Resource woh cheez hoti hai jo organization ke liye valuable ho. Kisi organization ke paas bohot si resources hoti hain jaise buildings, furniture, vehicles, technical staff, managers, supporting staff aur machinery. Ye saari resources carefully use ki jati hain taake maximum faida uthaya ja sake. Usi tarah data bhi ek bohot important resource hai aur isay bhi utna hi important samajhna chahiye jitna baaki resources ko samjha jata hai.  

## Why we call Data a Resource?  

Data is considered a true resource because it helps an organization make the right decisions at the right time. Only data can provide correct information, which allows proper use of other organizational resources. If the required data is not available on time or not in the correct format, the organization cannot make good and effective decisions. Such wrong or delayed decisions can lead to the failure of the organization or business.  

Data ko ek asal resource is liye mana jata hai kyunke yeh organization ko sahi waqt par sahi decisions lene mein madad karta hai. Sirf data hi correct information provide karta hai jo baaki organizational resources ka sahi istemal mumkin banata hai. Agar required data waqt par available na ho ya sahi format mein na ho, to organization achay aur effective decisions nahi le sakti. Aise ghalat ya late decisions organization ya business ki failure ka sabab ban sakte hain.  

# 5.  Levels of Data

## Real World Data

The real world level of data is the level where entities or objects exist in reality. It means that any object in real life has a name and other identifiable features that help us recognize it.  

**Simple words men**  
Real world level ka data wo level hai jahan objects ya entities haqeeqat mein mojood hoti hain. Iska matlab hai ke har object ka naam aur doosre pehchan ke attributes hotay hain jo us object ko pehchan ne mein madad karte hain.  

**Example:**  
Any Student  

---

## Meta Data

Meta data defines how data about real-world entities will be stored in the database. It is also called a schema. Meta data specifies what type of data will be stored, the size of each attribute, and how many attributes will be used.  

**Simple words men**  
Meta data batata hai ke real world entities ka data database mein kaise store hoga. Isay schema bhi kehte hain. Meta data ye specify karta hai ke kis type ka data store hoga, har attribute ka size kya hoga, aur kitne attributes use honge.  

**Example:**  
- Name, Character Type, 25 character size field  
- Age, Date Type, 8 bytes size  
- Class, Alphanumeric, 8 bytes size field  

---

## Existence of Data

Existence of data shows the actual data for entities in the real world according to the rules defined in the Meta data.  

**Simple words men**  
Existence of data asli data dikhata hai jo real world entities ke liye Meta data mein define rules ke mutabiq mojood hota hai.  

**Example:**  

| Name | Age        | Class   |
|------|------------|---------|
| Ali  | 20/8/1979  | MCS-I   |
| Amir | 22/3/1978  | MCS-II  |

# 5.  Users of Database Systems:

## 1. Application Programmers
 
Application programmers are people who create different types of database application programs. They design applications according to the needs of other users in a specific environment. They are skilled and understand the database structure and the organization's requirements.  

**Simple words men**  
Application programmers wo log hain jo mukhtalif database application programs banate hain. Ye applications dusre users ki zarurat ke mutabiq design karte hain. Ye skilled hote hain aur database structure aur organization ki zarurat ko achi tarah samajhte hain.  

---

## 2. End Users

End users are the people who use the database programs created by application programmers. There are two types of end users:  

- **Naïve Users:**  
  These users only use the programs made for them. They do not interact with other parts of the database and do not worry about how the database works.  

- **Sophisticated Users:**  
  These users have more rights than naïve users. They can access data in any way they want using programs or other methods. They must be skilled and careful not to damage data.  

**Simple words men**  
End users wo log hain jo application programmers ke banaye hue programs use karte hain. End users ke do types hain:  

- **Naïve Users:**  
  Ye users sirf un programs ko use karte hain jo un ke liye banaye gaye hain. Ye database ke dusre parts se interact nahi karte aur database ke kaam ki fikar nahi karte.  

- **Sophisticated Users:**  
Ye users naïve users se zyada rights rakhte hain. Ye data kisi bhi tarah access kar sakte hain programs ya dusre tareeqon se. Ye skilled hone chahiye aur data ko damage ya loss se bachana chahiye.  

---

## 3. Database Administrators (DBA)

DBAs are the most technical users. They manage the database and ensure proper functioning of the DBMS. They handle backups, recovery, and database maintenance. A DBA needs vast experience and strong technical skills.  

**Simple words men**  
DBAs sab se technical users hain. Ye database manage karte hain aur DBMS ka proper functioning ensure karte hain. Ye backups, recovery, aur maintenance ka khayal rakhte hain. DBA ko bohot tajurba aur strong technical skills ki zarurat hoti hai.  

---

## Duties of a DBA

Some key duties of a DBA include:  
- Schema definition  
- Granting and revoking data access  
- Routine maintenance such as backups, monitoring disk space, and monitoring running jobs  

**Simple words men** 

DBA ke kuch important duties ye hain:  
- Schema definition  
- Data access dena aur wapas lena  
- Routine maintenance jaise backups, disk space monitor karna, aur running jobs monitor karna  

---

## Schema Design

DBAs are responsible for designing the database schema, which is the metadata structure. In very large organizations, this task may be done by a database designer and later handed to the DBA.  

**Simple words men**  

DBAs database schema design karte hain, jo metadata ka structure hai. Bohot badi organizations mein ye kaam database designer karta hai aur database kaam shuru hone ke baad DBA ko handover hota hai.  

---

## Granting Access to Users

DBAs grant access rights to users and ensure legal use of these rights. They can also revoke access if needed.  

**Simple words men**  
DBAs users ko access rights dete hain aur ensure karte hain ke ye rights legal use hon. Zarurat parne par ye rights wapas bhi le sakte hain.  

---

## Monitoring Disk Space

As the database grows, DBAs monitor disk space to ensure that no overflow occurs.  

**Simple words men**  
Database ke barhne par DBAs disk space monitor karte hain taake data overflow na ho.  

---

## Monitoring Running Jobs

DBAs continuously monitor database activities to ensure users follow rules and all devices function properly.  

**Simple words men**  
DBAs continuously database activities monitor karte hain taake users rules follow karein aur saare devices properly kaam kar rahe hon.  

--- 

## Lecture 03: The Three-Level Architecture  

**Three-Level Architecture** (jisay **ANSI SPARK architecture** bhi kehte hain, 1975 mein propose hui) ek fundamental standard hai DBMS ka.  

Is ka main goal hai **Data Independence** hasil karna, yani user ki view ko physical storage details se alag karna.  

---

## 1. External View / Level (Bairooni Satah)  

Yeh sabse **upar ka level** hai jo har user ya application program ke liye customized view banata hai.  

- **Customized User Views**: Ek hi database ke multiple external views ho sakte hain.  
- **Abstraction aur Security**: Implementation details (Conceptual aur Internal views) user se chhupa kar rakhta hai.  
- **Derived Data**: Yeh level wo data bhi show kar sakta hai jo stored values se calculate hota hai (jaise DOB se employee ki age nikalna).
- **Goal**: User ko data us tarah dikhana jesa wo chahta hai.

- Yeh woh satah hai jo har alag user ko sirf woh data dikhati hai jiski usko zaroorat hai, bilkul uske Mobile App 📱 ki tarah.

<img width="785" height="349" alt="e" src="https://github.com/user-attachments/assets/13d6329a-84fd-4fb1-8556-dc744f71a0e7" />

---

## 2. Conceptual View / Level (Tasawwurati / Logical Satah)  

Yeh level database ka **overall logical structure** define karta hai jo poore users community ke liye hota hai.  

- **Complete Schema**: Entities, attributes aur unke relationships ki definition hoti hai.  
- **Intention of Database**: Data types, integrity constraints aur security authorizations yahan define hoti hain.  
- **Stability**: Conceptual schema stable hota hai aur frequently change nahi hota.  

- Yeh satah poori university 🏢 ke data ko logically define karti hai. Isay aap University ke "Master Blueprint" 🗺️ ki tarah samajh sakte hain, jo batata hai ki kya-kya data store karna hai aur unka aapas mein kya rishta hai.

<img width="595" height="529" alt="c" src="https://github.com/user-attachments/assets/7c33712e-1a65-45fd-afba-205b077352e2" />

- **Key Point:** Is satah par data structure tay hota hai. Agar University koi naya "Executive MBA" program shuru karti hai, toh uski details is Master Blueprint (Conceptual Schema) mein add hongi.

---

## 3. Internal View / Level (Androoni / Physical Satah)  

Yeh sabse **neeche ka level** hai jo batata hai data storage devices par physically kaise store hota hai.  

- **Storage Details**: Storage efficiency par focus karta hai (compression, indexes, hashing, etc.).  
- **DBMS Control**: DBMS storage aur retrieval mechanisms ko handle karta hai.  
- **Separation from Physical Level**: OS binary format ko handle karta hai, lekin DBMS internal schema ko manage karta hai.

<img width="601" height="306" alt="ex" src="https://github.com/user-attachments/assets/4def4488-91f8-4c28-83b5-f2204f386e5d" />

**Key Point:** Agar University koi naya aur tez SSD storage system lagati hai, toh sirf yeh Internal/Physical View badlega. Upar ke Conceptual View ya students ke External View (Result Card) par koi asar nahi padega. Isi ko Physical Data Independence kehte hain

---

##  Inter-Schema Mappings (Rabt)  

Mappings wo mechanisms hain jo alag alag levels ke darmiyan data aur requests ko transform karte hain.  

| **Mapping Type**        | **Connection**         | **Functionality** |
|--------------------------|------------------------|-------------------|
| External / Conceptual    | External ↔ Conceptual  | User-specific views ko overall logical model mein translate karta hai. |
| Conceptual / Internal    | Conceptual ↔ Internal  | Logical structure ko physical storage strategy se link karta hai. |

---

##  Major Benefit: Data Independence 

Is architecture ki sabse bari strength hai **Data Independence**. Yeh ensure karta hai ke neeche ke level par hone wali changes ka upper levels par *koi ya bohot kam effect* ho.  

- **Logical Data Independence**: Agar conceptual schema mein koi change ho (jaise ek attribute add karna), to users ke external views affect nahi hote.  
- **Physical Data Independence**: Agar internal schema mein koi change ho (jaise file organization ya storage media change karna), to conceptual schema ya external views par asar nahi padta.  

#  Database Mappings (Rabt / Mechanism)

<img width="1024" height="1024" alt="Gemini_Generated_Image_7ljsgb7ljsgb7ljs" src="https://github.com/user-attachments/assets/df4f3551-aaf8-4d86-9ecd-9917b2eee50f" />

**Tareeqa-e-kaar (mechanism)** hai jiske zariye database ke teen alag-alag **satah (levels)** aapas mein rabt (link) qaim karte hain aur ek satah ke data structure ko doosri satah mein **tabdeel (translate)** karte hain.  
Yeh woh *"software glue"* hai jo is baat ko yakeeni banata hai ke:  

- **External View** (jo user dekhte hain)  
- **Conceptual View** (database ka logical design)  
- **Internal View** (data kaise store hota hai)  

hamesha **hum-aahang (consistent)** rahein, chahe andaruni (internal) changes kyon na kiye gaye ho.  

---

##  Mappings Ki Zarurat Aur Kismain  

Mappings ka maqsad hai **Data Independence** qaim rakhna.  
Teen-satah wali architecture mein mappings do bunyadi jagahon par istemaal hoti hain:  

---

### 1. External / Conceptual Mapping (Ext/Con Mapping)  

- **Rabt Kahan**: External Level (user ka view) aur Conceptual Level (database ka logical view) ke darmiyan.  
- **Maqsad**: User ki queries ko logical structure mein tabdeel karna, aur phir wapis user ke liye customized nateeja (result) paida karna.  

** Real-World Misaal:**  
Agar user employee ki **“Umar” (Age)** dekhna chahta hai (External View), to yeh mapping Conceptual View mein store ki gayi **“Tareekh-e-Paidaish (Date of Birth)”** ko current date se calculate karke **Age** mein tabdeel karegi.  

---

### 2. Conceptual / Internal Mapping (Con/Int Mapping)  

- **Rabt Kahan**: Conceptual Level (logical model) aur Internal Level (physical storage model) ke darmiyan.  
- **Maqsad**: Logical records ko disk par unki asli jagah aur format (Internal Schema) se connect karna.  
- **Data Independence**: Agar DBA storage technique badal de (jaise sequential se indexed files mein tabdeeli), to yeh mapping us tabdeeli ko Conceptual Level se chupa legi — taake user programs ko change na karna pade.  

---

##  Mappings Ka Amal (The Process)  

Mappings ka process teen steps mein hota hai:  

1. **Talab (Request):**
   
   Jab user data mangta hai (External Level), yeh request External/Conceptual Mapping ke zariye Conceptual Schema ko samajhti hai.  

3. **Rasta Tay Karna:**
   
   Conceptual/Internal Mapping us logical talab ko disk par data ki asal jagah (Internal Schema) tak pohanchne ke liye instructions mein tabdeel karti hai.  

4. **Nateeja Wapsi:**
   
   Data hasil karne ke baad mappings reverse hoti hain aur result user ke External View tak sahi format mein pohanchta hai.  

---

##  Nateeja  

**Mappings** yeh guarantee karti hain ke:  

- Database mein hone wali changes user ke liye *painful* ya *problematic* na banain.  
- Yeh issue traditional file processing systems mein aam tha, magar 3-Level Architecture isay solve karti hai.  


# Three-Level Database Architecture (with YouTube Example)

| Feature                | Internal View (Physical)                                   | Conceptual View (Logical)                                                | External View (User)                                             | YouTube Example |
|-------------------------|------------------------------------------------------------|---------------------------------------------------------------------------|------------------------------------------------------------------|-----------------|
| **Definition**          | Data ka physical storage aur hardware-level details        | Puri database ka logical design (entities, attributes, relationships)     | User-specific view jisme sirf required data show hota hai        | Internal = Servers & storage, Conceptual = Data model, External = App UI |
| **Scope**               | Hard disks, indexes, file organization, compression, etc. | Organization ka complete data (community view)                           | Individual user/group ki zarurat ka data                         | Internal: Video file stored in data centers, Conceptual: Videos + Users schema, External: Home feed |
| **Data Storage**        | Kaise data disk pe save hota hai aur kaunsa format use hota hai | Ek hi copy of data logical level pe define hoti hai                      | Same data alag formats/views me dikhaya jata hai                 | Internal: Video in binary format, Conceptual: Video entity (title, ID, tags), External: Recommendations |
| **Examples**            | Data blocks, file paths, indexes, cache management        | Customers, Products, Salespersons, Managers, Outlets                     | Student → apne marks; Teacher → puri class ke results            | Internal: Raw video file, Conceptual: Video + Comments + Likes, External: Watch page showing views, likes |
| **Constraints & Rules** | Focus on efficiency (speed, storage, backup)              | Rules on data types & relationships (e.g. Age > 18, Stock ≥ 0)           | Sirf data ko filter/format karna                                 | Rule: "18+ restriction" stored in conceptual schema, applied in external views |
| **Authorization**       | Backup, recovery aur admin-level access handle karta hai  | Define karta hai kaun data dekh/modify kar sakta hai                     | User ko sirf unhi data tak access hota hai jo uske liye allowed hai | Internal: Only YouTube engineers access servers, Conceptual: Only channel owner edit kar sakta hai, External: User can only like/comment |
| **Change Frequency**    | Rarely change hota hai (hardware ya storage upgrade)      | Rarely change hota hai (stable design)                                   | Frequently change ho sakta hai (UI/format updates)               | Internal: Data center upgrade, Conceptual: Schema stable, External: YouTube app design updates |
| **Analogy**             | Ghar ki **foundation aur bricks**                         | Ghar ka **blueprint/naqsha**                                             | Ghar ka **user ka view** (living room, kitchen, etc.)            | Internal: Servers, Conceptual: YouTube schema, External: App interface |


# 📚 Overview of Lecture  4 

- Internal Schema of the Database Architecture  
- Data Independence  
- Different aspects of the DBMS  

---

##  Internal / Physical View (Schema) ki Tafseel  

**Internal View** Three-Level Architecture ki **teesri aur sabse nichli satah (lowest level)** hai.  
Iska kaam hai decide karna ke **data storage media** par data kaise rakha jaayega.  

---

### 1️⃣ Bunyadi Zimmedari aur Maqsad  

- **Data Storage Format:** Data ko aise format mein store karna jo sirf DBMS padh sake.  
- **DBMS ka Ikhtiyar:** DBMS faisla karta hai ke data ko disk par kaise store karna hai, aur yeh faisla **DBA (Database Administrator)** ke requirements par mabni hota hai.  

---

### 2️⃣ Internal View aur Physical View mein Farq  

Aksar in dono terms ko ek hi maana jaata hai,  
lekin asal mein unke darmiyan ek **bareek sa farq** hota hai.  

<img width="589" height="330" alt="bb" src="https://github.com/user-attachments/assets/d523540f-7a27-4c35-92b3-7c5867f29c51" />

---

### 3️⃣ DBMS ki taraf se Izaafi Maloomat  

DBMS data ko store karte waqt apni taraf se kuch **extra information** add karta hai taake performance aur retrieval behtar ho sake:  

- **Indexing:** File Organization ko implement karne ke liye DBMS indexes banata hai.  
- **Data Retrieval:** Jab data wapas manga jata hai, DBMS unhi indexes ko use karke fast retrieval karta hai.  

---

### 4️⃣ Ahem Faisle aur Khasiyatain (Features)  

Is satah par DBMS kuch important decisions leta hai jo **performance aur security** se mutaliq hote hain:  

- **Space Optimization:** Storage space ko efficiently use karna (jaise data compression) bina performance compromise kiye.
- 
- **Security:** Data ko secure rakhne ke liye **encryption algorithms** ka istemaal.  
- **Internal vs External Boundary:**  
  - Internal Level: Data ko kaise physically store karna hai.  
  - External Level: Data ko user ko kaise represent karna hai.  

---

#  Inter-Schema Mapping (Maanpaniyaan)  

**Mr. Naveed**, yahan **Inter-Schema Mapping** ki tafseeli wazahat di gayi hai, jaisa ke aapne farmaya.  
Yeh woh *"invisible bridge"* hai jo database ke mukhtalif **nazariyon (views)** ko aapas mein jode rakhta hai.  

---

##  Inter-Schema Mapping Kya Hai?  

**Mapping** ek aisa mechanism hai jiske zariye database ke ek **satah (level)** ke records ya data ko doosri satah ke **badle hue format** se joda jaata hai.  

**Maqsad:**  
- Yeh ensure karta hai ke har user ko data uski zaroorat ke mutabiq mile,  
- Bhale hi andaruni storage format kuch bhi ho.  

---

##  Buniyadi Mappings ki Qismain  

Three-Level Architecture mein do ahem qisam ki mappings hoti hain:  

1. **External / Conceptual Mapping (Ext/Con Mapping)**  
   - Jab **External Level** ka data (user ka view) **Conceptual Level** ke data se joda jaata hai.  

2. **Conceptual / Internal Mapping (Con/Int Mapping)**  
   - Jab **Conceptual Level** ka data **Internal Level** ke data se joda jaata hai.  

---

##  Mappings Ka Amal (The Hidden Mechanism)  

- Yeh mappings **Mapping Functions** ke zariye perform hoti hain.  
- Mapping Functions ek tarah ka **conversion system ya formula** hote hain jo:  
  - Data ko ek format se doosre mein **tabdeel** karte hain.  
  - User ko hamesha **consistent aur relevant view** faraham karte hain.  

---

#  Data Independence ki Wazahat (Explanation)  

**Data Independence** ka matlab hai ke:  
- **Data**, **Database**, aur **Data Applications** ek doosre se **azaad (independent)** hote hain.  

---

##  Three-Level Architecture se Pehle  

Traditional **file processing systems** mein:  
- Application programs aur data ek doosre par **depend** karte the.  
- Agar data mein koi tabdeeli hoti thi, to related applications ko bhi modify karna padta tha.  

**Masla (Problem):**  
- Agar **Internal / Physical Level** mein ya **data access strategy** mein koi tabdeeli aati thi,  
- To **External Level** par chalne wale applications us changed data ko access nahi kar paate the.  
- Natija: Applications fail ho jate the aur kabhi kabhi **poora system crash** ho sakta tha.  

---

##  Three-Level Architecture ka Maqsad  

**Data Independence** is architecture ka **buniyadi maqsad (major most objective)** hai.  

- Jab **data aur applications** ek doosre se azaad hote hain:  
  - System ke kisi bhi component mein aasani se tabdeeli ki ja sakti hai.  
  - Doosre components ki functionality par iska koi asar nahi padta.  

**Result:**  

- Is architecture ke zariye hum **External/Conceptual** aur **Conceptual/Internal** independence dono hasil karte hain.  

---

##  Data Independence ki Do Aqsaam (Two Types)  

Data Independence ko do qisam mein taqseem kiya jaata hai:  

1. **Logical Data Independence**  
   - External aur Conceptual levels ke darmiyan azaadi.  
   - Agar Conceptual Schema mein changes kiye jayein (jaise naya attribute add karna),  
     to External Views aur user applications par asar nahi padta.

<img width="635" height="305" alt="nnnnn" src="https://github.com/user-attachments/assets/5b4445a7-74db-4e76-8498-8fd33363dbac" />


2. **Physical Data Independence**  
   - Conceptual aur Internal levels ke darmiyan azaadi.  
   - Agar Internal Schema mein koi tabdeeli hoti hai (jaise file organization ya storage device badalna),  
     to Conceptual Schema aur External Views par iska koi asar nahi hota.  

---


