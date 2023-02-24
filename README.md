# Bug-Reporting

Below are some bugs reported by me while I was working on my project at **The Informal School of IT** for the Software Testing graduation course by testing www.bigfish.ro application.

-------------

**Summary:**

* User can register without having the same password in "Parola" and "Confirma parola" fields.

**Description:**

    In "Cont nou" page, if the user enters different values for "Parola" and "Confirma parola" fields,he can register successfully. 

**Steps to Reproduce:**

1. User goes to www.bigfish.ro application and opens it on main page
2. User hovers the cursor over the "Autentificare" field and clicks on the "Cont nou" button
3. User fills the required inputs with the next values:
  * Nume: Stefan
  * Prenume: Radu
  * Telefon: 0787633555
  * Email: radu.stefanut56@gmail.com
  * Adresa: Str Vulturului nr.74
  * Oras: Buhusi
  * Cod postal: 605302
  * Judet: Bacau
  * Tara: Romania
  * Parola:1234
  * Confirma parola: 5648
4. User clicks on the "Inregistrare" button

**Actual ressults:**

* User is able to register successfully with different values for "Parola" and "Confirma parola" fields.

**Expected results:**

* User should not be able to register with different values for "Parola" and "Confirma parola" fields.

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

**Attachment:**
[link](https://bugs.scoalainformala.ro/file_download.php?file_id=23182&type=bug)

-----------

**Summary:**
A strong password is not required while user is creating a new account.

**Description**
In "Cont nou" page, the user can register with a very weak password which consists in just 3 characters.

**Steps to Reproduce:**
1. User goes to www.bigfish.ro application and opens it on the main page
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
  * Tara: Romania
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
Normal

**Reproducibility:**
Always

**Platform:**
Laptop

**OS:**
Windows

**OS Version:**
10 Home

**Attachment:**

![Alt Text](https://user-images.githubusercontent.com/85682689/155272086-9ea1b880-67a7-4958-bc84-5a40285eb430.jpg)


---------------

**Summary:**
Missing proper validation in "Cont nou" page for email address.

**Description:**
In the Login page, when user is creating a new account,even if he/she enters an invalid email address,the account is successfully registered.

**Steps to Reproduce:**
1. User goes to www.bigfish.ro application and opens it on the main page
2. User hovers the cursor over the "Autentificare" field and clicks on the "Cont nou" button
3. User fills all the required fields with the following values:
  * Nume: Ionescu
  * Prenume: Vlad
  * Telefon: 0787645237
  * Email: abc12@gmail
  * Adresa: Str Vulturului nr 74
  * Oras: Buhusi
  * Cod postal: 123456
  * Judet: Iasi
  * Tara: Romania
  * Parola: calm456
  * Confirma parola: calm456
4. User clicks on "Inregistrare" button

**Actual results:**
The account is successfully registered.

**Expected results:**
A message should warn the user that email address introduced is not in the correct format and enter a valid one.

**Additional Information:**
The same bug is reproducible for next two sections: "Contact" page and "Comanda" page. 

**Priority:**
Normal

**Severity:**
Normal

**Reproducibility:**
Always

**Platform:**
Laptop

**OS:**
Windows

**OS Version:**
10 Home

**Attachment:**

![Alt Text](https://user-images.githubusercontent.com/85682689/155273072-e3c5082d-3288-4157-8f98-146958d0d735.jpg)


---------------

**Summary:**
The content of product in "Cosul meu" page is not properly adapted having overlaps.

**Description:**
When the user checks the shopping cart,in the "Cosul meu" option from the "Comanda" page,the word "Incarca" is truncated by the "Incarca" button and if he/she removes the item from cart, also the content is overlaped.

**Step to reproduce:**
1. User goes to www.bigfish.ro application and opens it on the main page
2. User hovers over "Cosul meu" section and clicks on the"Vezi cos" button
3. User clicks on "Sterge din cos" button

**Actual results:**
When the user checks the shopping cart by clicking on "Vezi cos" button in "Comanda" page, the word "Incarca" is truncated by the "Incarca" button and if he/she removes the item from cart,also the content is overlaped.

**Expected results:**
There should not be incomplete words or overlaped contents.

**Priority:**
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

**Attachment:**

![Alt Text](https://user-images.githubusercontent.com/85682689/155273542-48a24e21-fd94-42fc-84fd-eeabd884997a.jpg)


----------------

**Summary:**
Missing proper redirection between application's pages.

**Description:**
In the "Contact" page,if the user clicks on "Vezi cos" button,he/she is redirected to "Comanda" page,so he/she can see the products added to the cart,but if he/she clicks on "Continua cumparaturile" button,is redirected to "Contact" page instead of being sent to the shopping page.

**Steps to reproduce:**
1. User goes to www.bigfish.ro application and opens it on the main page
2. User clicks on the "Contact" tab
3. User hovers the cursor over "Cosul meu" button and clicks on "Vezi cos" button
4. User clicks on "Continua cumparaturile" button

**Actual results:**
From "Comanda" page,the user is redirected to "Contact" page.

**Expected results:**
From "Comanda" page,the user should be directed to the shopping page to be able to continue the shoppings.

**Priority:**
Normal

**Severity:**
Normal  

**Reproducibility:**
Always

**Platform:**
Laptop

**OS:**
Windows

**OS Version:**
10 Home

**Attachment:**

[link](https://bugs.scoalainformala.ro/file_download.php?file_id=22829&type=bug)

----------------

**Summary:**
"Cele mai vandute" option from dropdown list is not available.

**Description:**
When the user selects to sort the products by the most sold,option is not available.

**Steps to Reproduce:**
1. User goes to www.bigfish.ro application and opens it on the main page
2. User clicks on "Ace Carp" tab from the list of producers "Alege producator"
3. User clicks on "Cele mai noi" dropdown button from "Sortare" section
4. User selects "Cele mai vandute" option

**Actual results:**
By opening the dropdown list from "Sortare" button, "Cele mai vandute" option is not available.

**Expected results:**
By opening the dropdown list from "Sortare" button,"Cele mai vandute" option should be available.

**Priority:**
Normal

**Severity:**
Normal

**Reproducibility:**
Always

**Platform:**
Laptop

**OS:**
Windows

**OS Version:**
10 Home

**Attachment:**

[link](https://bugs.scoalainformala.ro/file_download.php?file_id=22843&type=bug)

----------------

**Summary:**
Missing zoom option for the map of the site.

**Description:**
In the "Contact" feature,the user does not have zoom option for the map of the application.

**Steps to Reproduce:**
1. User goes to www.bigfish.ro application and opens it on the main page
2. User clicks on "Contact" tab
3. User clicks once on the map, doubleclicks on the map or scrolls over the map 

**Actual results:**
Even for singleclick or doubleclick on the map image or scrolling over the map, nothing is happening.

**Expected results:**
User should have an option to be able to zoom the map.

**Priority:**
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

**Attachment:**

![bigfish-missing zoom bug](https://user-images.githubusercontent.com/85682689/155275131-ff0a4bd0-200e-44dd-8a49-bcaf0fcb517f.png)


-----------------

**Summary:**
Missing proper confirmation message for product added to the cart from "Wishlist" page.

**Description:**
After user adds a product to the cart from "Wishlist" page, he/she receives a wrong confirmation message about the product added to the cart.

**Steps to Reproduce:**
1. User goes to www.bigfish.ro application and opens it on the main page
2. User enters valid credentials for e-mail address and password:
  * Email: radu.stefanut77@gmail.com
  * Parola: vara123
3. User clicks on the "Conectare" button
4. User clicks on the "Wishlist" button
5. User selects the product "Ochelari Drennan Aqua Sight" and clicks on the "ADAUGA IN COS" button

**Actual results:**
After user adds the product to the cart, he/she receives a wrong confirmation message which consists information about the previous product that was added to the cart.

**Expected results:**
User should receive the right confirmation nessage about the product added to the cart.

**Priority:**
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

**Attachment:**

![Wishlist-confirmation message bug](https://user-images.githubusercontent.com/85682689/155275546-2a4ccb33-0539-44aa-b9ac-ba4ed6322912.jpg)


-----------------

**Summary:**
Missing proper validation for "Cod postal" field when the user creates a new account.

**Description:**
When the user creates a new account, the "Cod posatal" field is not forbidden for special and alphabetical characters and for length shorter than 4 characters.

**Steps to Reproduce:**
1. User goes to www.bigfish.ro application and opens it on main page
2. User hovers the cursor over the "Autentificare" field and clicks on the "Cont nou" button
3. User fills all the required fields with the following values:
  * Nume: Stefan
  * Prenume: Radu
  * Telefon: 0787633555
  * Email: radu.stefanut112@gmail.com
  * Adresa: Str Vulturului nr.74
  * Oras: Buhusi
  * Cod postal: @#$<>?&!
  * Judet: Bacau
  * Tara: Romania
  * Parola: guru123
  * Confirma parola: guru123
4. User clicks on "Inregistrare" button

**Actual results:**
The account is successfully registered.

**Expected results:**
User should not be able to create a new account with other than numerichal characters and should get an warning message that postal code introduced hasn't the correct format.

**Additional Information:**
The same bug is reproducible for next two sections:
  * In the "Contact" page
  * In the "Comanda" page, more specifically, in the "Inregistrare cont nou" section

**Priority:**
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

**Attachment:**

![PostalCodeRegister-bug](https://user-images.githubusercontent.com/85682689/155277710-3932b921-ace7-4c0c-8f9d-c9a906fa1cb8.jpg)








