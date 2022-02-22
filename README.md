# Bug-Reporting

Below are some bugs reported by me while I was working on my project at **The Informal School of IT** for the Software Testing graduation course by testing www.bigfish.ro application.

-------------

**Summary:**
User can register without having the same password in "Parola" and "Confirma parola" fields.

**Description:**
In "Cont nou" page, if the user enters different values for "Parola" and "Confirma parola" fields,he can register successfully. 

**Steps to reproduce:**
1.User opens the "Bigfish" application
2.User hovers the cursor over the "Autentificare" field and clicks on the "Cont nou" button
3.User fills the required inputs with the next values:
-Nume: Stefan
-Prenume: Radu
-Telefon: 0787633555
-Email: radu.stefanut56@gmail.com
-Date facturare: Fizica
-Adresa: Str.Soseaua Nationala nr.74
-Oras: Bacau
-Cod postal: 607202
-Judet/sector: Bacau
-Tara: Romania
-Date livrare: Completeaza date de livrare cu date personale
-Adresa: Str.Soseaua Nationala nr.74
-Oras: Bacau
-Parola:1234
-Confirma parola: 5648
4.User clicks on the "Inregistrare" button
