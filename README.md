# Bug-Reporting

Below are some bugs reported by me while I was working on my project at **The Informal School of IT** for the Software Testing graduation course by testing www.bigfish.ro application.

-------------

**Summary:**
User can register without having the same password in "Parola" and "Confirma parola" fields.

**Description:**
In "Cont nou" page, if the user enters different values for "Parola" and "Confirma parola" fields,he can register successfully. 

**Steps to reproduce:**

1. User goes to www.bigfish.ro application and opens it on main page
2. User hovers the cursor over the "Autentificare" field and clicks on the "Cont nou" button
3. User fills the required inputs with the next values:
  * Nume: Stefan
  * Prenume: Radu
  * Telefon: 0787633555
  * Email: radu.stefanut77@gmail.com
  * Adresa: Str Vulturului nr.74
  * Oras: Buhusi
  * Cod postal: 605302
  * Judet: Bacau
  * Parola:1234
  * Confirma parola: 5648
4. User clicks on the "Inregistrare" button

**Actual ressults:**
User is able to register successfully with different values for "Parola" and "Confirma parola" fields.

**Expected results:**
User should not be able to register with different values for "Parola" and "Confirma parola" fields.

**Priority:**
Normal

**Severity:**
Major

**Reproducibility:**
Always

**Platform:**
Laptop

**OS:**
Windows

**OS Version:**
10 Home

-----------

**Summary:**
A strong password is not required while user is creating a new account.

**Description**
In "Cont nou" page, the user can register with a very weak password which consists in just 3 characters

**Steps to reproduce:**
1. User opens the "Bigfish" application
2. User hovers the cursor over the "Autentificare" field and clicks on the "Cont nou" button
3. User fills the required inputs with the next values:
  * Nume: Stefan
  * Prenume: Radu
  * Telefon: 0787633555
  * Email: radu.stefanut777@gmail.com
  * Adresa: Str Vulturului nr.74
  * Oras: Buhusi
  * Cod postal: 605302
  * Judet: Bacau
  * Parola: 123
  * Confirma parola: 123
4.User clicks on the "Inregistrare" button

**Actual results:**
The user can register successfully with a very weak password.

**Expected results:**
The user should not be able to register with such a weak password which consists in just 3 characters.

**Prority:**
Normal

**Severity:**
Minor

**Reproducibility:**
Always

**Platform:**
Laptop

**OS:**
Windows

**OS Version:**
10 Home


