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

# Lecture No. 03

## Overview of Lecture

- **Database Architecture**  
- **External View of the Database**  
- **Conceptual View of the Database**


# Database Architecture

Database systems ko **standardize** karna future growth ke liye bohot zaroori hai. Matlab agar ek system kisi **standard** ke mutabiq banaya jaye, to usko use karna aur aage expand karna bohot easy ho jata hai.  

---

## Standard ka Fayda

1. **New system banana easy**
   Agar kisi organization ko new system develop karna hai jo same kaam kare, to wo pehle se defined standard ko use karke banayegi. Is se development fast aur easy ho jata hai.  
   🔹 *Example:* Agar universities ek standard follow karein students ke records store karne ka, to har university easily new student management system bana sakti hai.  

3. **Non-standard system expand karna mushkil**  
   Jo systems standards pe based nahi hote, unko expand karna bohot mushkil aur costly hota hai.  
   🔹 *Example:* Agar ek dukaan apna khud ka accounting system bina kisi rule ke banaye, to usme naye features add karna ya new staff ko train karna mushkil hoga.  

4. **Staff training easy**  
   Agar system standard pe bana ho to staff ko train karne ki zaroorat nahi hoti. New staff bhi easily kaam shuru kar sakta hai.  
   🔹 *Example:* Microsoft Excel jesa standard tool seekhna easy hai kyunki har jagah same rules follow hote hain.  

---

## ANSI/SPARC Standard

1975 me **ANSI/SPARC** ne ek database standard propose kiya tha jo aaj tak duniya bhar me use ho raha hai.  
Ye hi wo **3-level database architecture** hai jo sabse popular aur agreed standard hai.  

---

## Three-Level Schema Architecture ke Benefits

<img width="1024" height="1024" alt="Gemini_Generated_Image_hhmlvhhhmlvhhhml" src="https://github.com/user-attachments/assets/4163eb12-59c0-47e1-8a15-9734b273b86f" />

### 1. Different Users, Different Views  

Har user ko database ka har level access karna zaroori nahi hota.  
3-level architecture ye allow karta hai ke physical data storage ko user ke view se alag rakha jaye.  

 *Example (YouTube):* 
 
- Viewer ko recommended videos aur likes count dikhte hain  
- Creator ko analytics aur revenue dikhte hain  
- Admin ko copyright aur policy violations ka data dikhai deta hai  

---

### 2. Same Data, Different Format 

Database me data ek format me stored hota hai, lekin users usko apne requirement ke mutabiq dekh sakte hain.  

 *Example (Date of Birth):*  
- Database me stored: `28-03-1987` (dd-mm-yyyy)  
- Exam Department: `March-28-1987`  
- Registrar: `03/28/1987`  
- Library: `28/03/87`  

 3-level schema ye flexibility deta hai ke internal storage same rahe aur external users apne format me data dekh saken.  

---

### 3. Security aur Hiding Internal Details 

Ye architecture internal system ki details ko users se hide karta hai. Unauthorized log data ya system access nahi kar pate.  

 *Example (Banking):*  
Customer sirf apna balance aur transactions dekh sakta hai, lekin usko system ki database storage details nahi dikhai deti.  

---

### 4. Easy Changes aur Maintenance  

Agar kisi user ki requirement change ho jaye to sirf us user ka **external view** modify karna hota hai, puri database ko nahi.  
Isi tarah agar storage mechanism change karna ho (jaise new server ya indexing technique), to bhi users aur applications effect nahi hote.  

 *Example (Netflix):*  
Netflix agar apna video storage Amazon S3 se kisi aur cloud pe shift kare, to users ke liye koi farq nahi padega — unko videos same tarah stream hongi.  

---

## Recap (Simple Lafzon Me)

- **External Level** → User jo dekh raha hai (custom view)  
- **Conceptual Level** → Logical structure (tables, relationships)  
- **Internal Level** → Data ka asli storage (disk, indexing, compression)  


# Database Architecture 

Database ke andar **schemas** hotay hain jo basically ek **repository (storehouse)** ki tarah kaam karte hain.  
Yani schemas define karte hain ke database me kis tarah ke structures store honge —  
chaahe ek chhoti entity (jaise ek student) ho ya poori organization ka data.  

Isi wajah se database architecture me **different schemas** ko **different levels** pe rakha jata hai  
taa’ke ek level ki details doosre level se **isolate (alag)** rahen.  

---

##  Internal Level (Core of Database Architecture)

<img width="1024" height="1024" alt="Gemini_Generated_Image_524smp524smp524s" src="https://github.com/user-attachments/assets/4a3d892a-344b-4b67-82c0-01e9ee3ae948" />


Database architecture ka **core** internal schema hota hai.  
Ye level sari **internal details** implement karta hai aur ye hi database ka **intention** define karta hai.  

### Internal Schema kya karta hai?  

- Ye define karta hai ke ek **student** ka data kin attributes (jaise: Name, Roll No, DOB) me store hoga.  
- Ye batata hai ke in attributes ke values kis format me rakhi jayengi (text, numbers, date format etc).  
- Ye ye bhi decide karta hai ke **kon user database ko update/change** kar sakta hai aur kitni had tak.  

 Isko hum database ka **niyat (intention)** kehte hain, jo lagbhag permanent hota hai.  

### Real-world Example  

Ek **hospital database** design karte waqt:  

- Intention hoti hai ke har patient ka **Name, CNIC, DOB, Medical History** store ho.  
- Agar baad me hume lagay ke "Medical History" store karni hi nahi chahiye thi,  
  to is intention ko change karna mushkil aur risky hoga,  
  kyunki uske liye puri database structure aur records ko modify karna parega.  

---

##  Intention aur Extension  

- **Intention** → Database ki **design time definition** (kis kis cheez ko hamesha ke liye store karna zaroori hai).  
- **Extension** → Jab database me actual **data populate** kar diya jata hai (matlab real records dal diye jate hain).  

 Matlab pehle **design decide hoti hai (intention)**, phir usme **data dalna start hota hai (extension)**.  

### Example (University Database)  

- **Intention**: Har student ka Name, Roll No, Department aur DOB store karna zaroori hai.  
- **Extension**: Jab new batch ke 1000 students ka data actual database me enter kar diya jata hai.  

---

##  Changes aur Unke Effects  

Database ke alag-alag levels pe changes karne ke different impacts hotay hain:  

### Change in Extension (Data Records)  

- Sirf ek record effect hoga.  
- Mistake ko easily undo kiya ja sakta hai.  
- **Example**: Ek student ka DOB galti se `2003` ki jagah `2023` enter ho gaya → easy to fix.  

### Change in Intention (Internal Schema)  

- Ye puri database ko effect karta hai.  
- Bohot risky hai, kyunki chhoti si ghalti puri database ko corrupt ya inconsistent kar sakti hai.  
- **Example**: Agar ek organization decide kare ke "DOB store hi nahi karna" →  
  puri database structure change hogi aur saari related queries/reports fail kar sakti hain.  

 Is liye **intention change karna avoid karna chahiye** jab tak bohot hi critical na ho.  

---

##  Recap in Simple Words  

- **Schema** → Database ka blueprint / design.  
- **Internal Schema (Intention)** → Permanent design of *what* & *how* to store.  
- **Extension** → Actual data jo database me enter hota hai.  
- **Change in Data (Extension)** → Easy aur localized effect.  
- **Change in Schema (Intention)** → Risky aur puri database ko effect kar sakta hai.  

# External View (Level, Schema or Model)

<img width="1024" height="1024" alt="Gemini_Generated_Image_524smp524smp524s (1)" src="https://github.com/user-attachments/assets/05411b05-14d2-4885-80cb-0cd5159cf3a5" />

External View database ka **end-user level** hota hai. Is level par data uss form me show kiya jata hai jaisa user ko chahiye hota hai. Har user ka apna requirement alag hota hai, is liye unke hisaab se external views banaye jate hain.  

---

## Database Users

Database users ko do grounds par classify kiya jata hai:  

1. **Section of the Organization** (department ya branch jahan wo kaam karte hain)  
2. **Nature of Job** (kaam ka type, jaise HR, Finance, Student, Admin)  

---

## Features of External Level

- Har user ko sirf wahi data dikhaya jata hai jo uske kaam ka ho.  
- Kuch users sirf **view** kar sakte hain, aur kuch ko full **access** hota hai (insert, update, delete).  
- Ek database me **multiple external views** ho sakte hain, aur har view ek specific user ya group ke liye design hota hai.  
- User ki **rights & restrictions** carefully decide ki jati hain.  

---

## Examples

### 1. Missing Data Handling

Agar ek **Customer ka Phone Number** database me store hai, lekin area code store nahi kiya gaya,  
to system automatically **City ID** se area code pick karke full phone number bana sakta hai.  

### 2. Derived Data

Agar **Student ka Date of Birth (DOB)** stored hai, lekin admission ke waqt hume student ki **Age** chahiye,  
to user view DOB se automatically **Age calculate** kar sakta hai aur bata dega ke student admission ke liye eligible hai ya nahi.  

---

## Importance of External View

- External view ek **interface** hota hai jiske through user database ko use karta hai.  
- Ye **easy to use, self-explanatory, aur simple navigation** ke sath design hona chahiye.  
- External view **facilitator** bhi hota hai aur **barrier** bhi:  
  - Facilitator → User ko required data easy aur understandable form me provide kare.  
  - Barrier → User ko wo data access karne se rokay jo uske liye allowed nahi hai.  

---

## Flexibility

- Jaise-jaise system grow karta hai, external views ko **modify** kiya ja sakta hai (design, structure, access rights).  
- Ye changes **logical aur internal schema** ko affect nahi karte.  

---

## Diagram Example (Concept)
Ek hi data record different users ke external views me alag dikh sakta hai.  

- **User A (Student)**: Sirf apne marks aur attendance dekhega.  
- **User B (Teacher)**: Puri class ke results aur attendance dekh sakta hai.  

 Matlab data same hai, lekin presentation aur access user-specific hoti hai.  

---

# Conceptual / Logical View (Roman Urdu Version with Examples)

Conceptual ya Logical View database architecture ka wo level hai jismein **poori database ki definition** hoti hai.  
Yani ye batata hai ke database me kaunsa data store hoga, uska type kya hoga, aur us data par kaunse rules apply honge.  

---

## Kya hota hai Conceptual View?

<img width="1024" height="1024" alt="Gemini_Generated_Image_itqb69itqb69itqb" src="https://github.com/user-attachments/assets/13e641da-d620-4f14-b0f0-0640d6b2f1b4" />

- Ye **organization ka complete data** store karta hai, is liye isse **community view** bhi kaha jata hai.  
- Isme har entity (jaise Student, Customer, Product) ke attributes (Name, Age, Price, Stock) aur unke beech ke **relationships** define kiye jate hain.  

---

## Real-world Example: Company Database

Ek company ka conceptual schema me ye sab details hongi:  
- Customers  
- Products (jo stock me hain aur jo deliver hone wale hain)  
- Retail Stores  
- Salespersons  
- Managers  

Aur phir inke relationships:  

- Customer → Products kharidta hai store se.  
- Customer → Associate hota hai Salesperson se.  
- Salesperson → Assign hota hai ek Outlet pe.  
- Outlet → Manage karte hain Managers.  

 Matlab conceptual schema entities aur unke relationships ko logically manage karta hai.  

---

## Relation with External View

External View me user sirf apni zarurat ka data dekhta hai.  
Conceptual View ek **base layer** hai jo saare user views ko support karta hai.  

Example:  

- Student apne marks aur attendance dekhta hai.  
- Teacher puri class ka data dekhta hai.  

Lekin actual data **sirf ek hi copy** me conceptual schema me stored hota hai.  

---

## Features of Conceptual Schema

- Entities, Attributes aur Relationships define karta hai.  
- Data types aur constraints (jaise age > 18, price > 0) hold karta hai.  
- **Authorization aur Authentication** handle karta hai → sirf authorized users hi data access/change kar sakte hain.  
- Conceptual Schema **stable hota hai** (baar baar change nahi hota). Agar change karna pare to carefully karna padta hai kyunki iska effect doosre levels par bhi padta hai.  

---

## Recap in Simple Words

- **External View** → User ko data uski zarurat ke mutabiq show karta hai.  
- **Conceptual View** → Database ka **poora logical design** rakhta hai (entities, relationships, constraints, rules, authorization).  
- Ye hi wo layer hai jisse external views banaye jate hain.  


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


