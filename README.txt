Final Code Review

A site to return the second half of a dna helix and test an ajax article viewer.

By Casey Heitz

Description
Users are able to use a form and input one hald of a dna helix sequence, and the other half will be returned to them.  Also, users can click on articles, which will be displayed on the front page using ajax.  This is currently returning an error.

Setup
-Clone the repository from GitHub
-Open MAMP, direct the path to the root project folder, and start the servers
-Go to localhost:8888/phpmyadmin
-Select Import->Choose File, then select the database final_drupal_db.sql.zip in sites/db-backup, and click Go
-Under Privileges, select Add User and add the database user listed below
-Open the site in your browser from your localhost

Database Information:
Database name: final_drupal_db
Database user: final_admin
Password: password

Admin user: admin
Password: password

Technologies Used
Drupal 7.41

Legal

Copyright (c) 2015 Casey Heitz

This software is licensed under the MIT license.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
