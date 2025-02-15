# php-tasks

### Task 1
1. Create `config.json` file to store basic details of website like: `version, title, address, phone, email, logo_url`
2. Create a php file named `api.php`, using the `config.json` file data add the following request parameters -
3. $_REQUEST['version'] // it should reutrn as : `{"version": "1.0.0"}`
4. $_REQUEST['GET_APP_NAME'] // it should return the app name
5. $_REQUEST['GET_SUPPORT'] // it should return phone, email, address as json like 3 no.

   Estimated time duration 2 days 

### Task 2
1. Create a form with textarea (where user will paste base64 hash of file)
2. Upload and save as jpeg file in public/img/user/
3. Create entry on database
4. And on completing the submission form return a JSON header with a response like - `{ "resp": 200, "msg": "File uploaded successfully!" }`

   Estimated time duration 1 days
