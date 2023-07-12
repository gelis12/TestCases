# TestCases
<sub>Below are some test case samples that I wrote while working on previous projects.</sub>


### 1. Login testcases
1. **Title**
   
   Test login with correct credentials
   
   **Description**
   
   Check if the user can login by using correct credentials.
   
   **Steps to reproduce**
   1. Go to wordpress.com/log-in/
   2. Add correct user/pass
   3. Press the Login button
   4. Observe if user can login
      
   **Expected result**
   
   User should be able to login.
   
   **Test data**
   
   User: test
   Pass: 123

2. **Title**
   
   Test login with wrong credentials
   
   **Description**
   
   Check if the user can login by using wrong credentials.
   
   **Steps to reproduce**
   1. Go to wordpress.com/log-in/
   2. Add wrong user/pass
   3. Press the Login button
   4. Observe if user can login
      
   **Expected result**
   
   User should not be able to login.
   
   **Test data**
   
   User: test1
   Pass: 123

3. **Title**
   
   Test login without credentials
   
   **Description**
   
   Check if the user can login by not using any credentials.
   
   **Steps to reproduce**
   1. Go to wordpress.com/log-in/
   2. I asume that user/pass is empty
   3. Press the Login button
   4. Observe if user can login
      
   **Expected result**
   
   User should not be able to login.
   
   **Test data**
   
   User:
   Pass:

4. **Title**
   
   Test login with Remember me checked
   
   **Description**
   
   Check if the user can login by using correct credentials and Remember me checked.
   
   **Steps to reproduce**
   1. Go to wordpress.com/log-in/
   2. Add correct user/pass
   3. Check Remember me checkbox
   4. Press the Login button
   5. Observe if user can login
   6. Leave the page wordpress.com/log-in/
   7. Go to wordpress.com/log-in/
   8. Observe if user is still logged in
      
   **Expected result**
   
   User should be able to login, and if he leave the page and come back later it should be still logged in.
   
   **Test data**
   
   User: test
   Pass: 123

### 2. Searchbar testcase
1. **Title**
   
   Test searchbar with existing product
   
   **Description**
   
   Check if the user can search a product using the searchbar and an existing product.
   
   **Steps to reproduce**
   1. Go to www.emag.ro
   2. Type the product in searchbar
   3. Press enter to search
   4. Observe the expected result
      
   **Expected result**
   
   Searchbar should bring to me all the products that contain what i type in the searchbar.
   
   **Test data**
   
   Searchbar: Iphone

2. **Title**
   
   Test searchbar with nonexisting product
   
   **Description**
   
   Check if the user can search a product using the searchbar and an nonexisting product.
   
   **Steps to reproduce**
   1. Go to www.emag.ro
   2. Type the product in searchbar
   3. Press enter to search
   4. Observe the expected result
      
   **Expected result**
   
   Searchbar should bring me an empty page that tells me that the product doesnt exist.
   
   **Test data**
   
   Searchbar: dsfgseasrsadfrs

3. **Title**
   
   Test searchbar autocomplete function
   
   **Description**
   
   Check if the user can search a product using the searchbar and an existing product using autocomplete function.
   
   **Steps to reproduce**
   1. Go to www.emag.ro
   2. Type half letters from the product
   3. Observe if the site know what I want to type
      
   **Expected result**
   
   Searchbar should type for me the other half of the product name.
   
   **Test data**
   
   Searchbar: Iph

   
