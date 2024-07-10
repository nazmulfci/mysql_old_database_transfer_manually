# How to import large database file in php myadmin
<ol>
  <li> create a new database in localhost/phpmyadmin in browser like "personal_blog" </li>
  <li> put your .sql file in specific folder  </li>
  <li> open xampp control panel & click shell button from right side </li>
  <li> type this command " mysql -u root -p personal_blog < G:\personal_blog.sql" </li>
  <li> Lets enjoy........</li>
  <li> if face this problem : ERROR 1813 (HY000) at line 164704: Tablespace for table 'cashbook_live.stock_summeries' exists. Please DISCARD the tablespace before IMPORT </li>
  <li> create a new database another name and try ageain. from step 1 ..... </li>
</ol>


# How to transfer old database file in xampp manually
<ol>
  <li> copy only folder from old mysql->data folder </li>
  <li> Paste this in new mysql->data folder clt+a  </li>
  <li> go to phpmyadmin in browser and click empty session data </li>
  <li> stop php & mysql in xampp server </li>
  <li> copy ibdata1 from old data to new data folder </li>
  <li> stop php & mysql in xampp server </li>
  <li> Lets enjoy........</li>
</ol>
