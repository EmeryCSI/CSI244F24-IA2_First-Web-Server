# Renton Technical College CSI-244
<br />    

<div align="center">  
    <img src="logo.jpg" alt="Logo">
    <h3 align="center">Independent Activity 2</h3>
</div>

This repository is a part of CSI-244 at Renton Technical College.

## Independent Activity 2 - Intro To Express

### Make sure you have completed Guided Activity 2 first

Your company has decided that the built-in http module that comes with Node.JS is no longer sufficient to meet the needs of the application. Port your Guided Activity 2 assignment over to use Express instead of the built in http module. You may re-use majority of the code from Guided Activity 2 however server.js will require extensive modification.

### Complete the following:

1. Clone the repository via either the terminal or GitHub Desktop.
2. Navigate to the repository folder in the terminal.
3. Make sure that you are in the correct folder. If you are not then your changes will not be tracked by git
4. Create a new node project in the repository folder.
     ```bash
     npm init -y
     ```
5. Install Express via NPM
     ```bash
     npm install express
     ```
7. All of the modules and html you created in for Guided Activity 2 can be re-used here.
8. Modify the server.js so that is uses express instead of HTTP.
9. Test the new application to ensure that it is working.

### Testing Your Server

1. **Run Your Server:**
   - In the terminal, start your server:
     ```bash
     node server.js
     ```
   - Your server is now live on `http://localhost:3000`.

2. **Test Each Endpoint:**
   - Visit `http://localhost:3000/` in a web browser for your student details.
   - Go to `http://localhost:3000/system-info` for system info.
   - Navigate to `http://localhost:3000/log-visit` to log your visit.
   - Check `http://localhost:3000/show-log` to view the log.
   - Verify that the userform functionality is working.

3. **Research the req.query property:**
   - [req.query ](https://www.geeksforgeeks.org/express-js-req-query-property/)
   - Create an endpoint at `/query` that displays returns the query object.
   - Pass at least two values to the query object from the url. Refer to the geeksforgeeks article for help.

Create a new commit with the message Independent Activity 2 Complete and push the changes to GitHub


If you have any questions about this assignment please reach out to myself or our TA for this course.
