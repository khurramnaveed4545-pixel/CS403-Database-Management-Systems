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

## Database Definitions

An organized collection of information in computerized format.

**A database is an organized collection of data that is systematically stored in a computer system so that it can be efficiently accessed, managed, and updated.**

Database asal mein aik **organized collection of data** hoti hai jo computer system par systematically store ki jati hai taake usay efficiently access, manage aur update kiya ja sake.  

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

# Lecture 2 of DBMS ( Database Managment Systems )

## 1. Difference between Data and Information  

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

## 2. Further Advantages of Database Systems:

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

