Download Link: https://assignmentchef.com/product/solved-csc365-project1
<br>



<strong>Q1</strong> Consider a table ​           <strong>Payment</strong>​              . It has the following fields:​          <strong>payment_id</strong>​, ​<strong>customer_id</strong>​, ​<strong>staff_id</strong>, ​ <strong>amount</strong>​      ​, <strong>payment_date</strong>​               . The ​     <strong>payment_id</strong>​       field identifies the tuple.​    The ​<strong>customer_id</strong>​ and ​<strong>staff_id</strong>​ fields are foreign keys to the ​<strong>Customer</strong>​ and ​<strong>Staff</strong>​ table, respectively. It tells us which customer made the payment and which staff member processed the payment. The last field denotes the date when the payment was made.  Obviously, a customer can make several payments on the same date. Complete the following picture by putting checkmarks where appropriate. The picture is for the <strong>Payment</strong>​          table. For example, there is a checkmark for ​               <strong>payment_id</strong>​       and ​      <strong>Primary key</strong>​        because​              <strong>payment_id</strong>​ is the primary key for the ​<strong>Payment</strong>​ table.

<table width="469">

 <tbody>

  <tr>

   <td width="164"> </td>

   <td width="95">Primary key</td>

   <td width="120">Candidate Key</td>

   <td width="90">Super key</td>

  </tr>

  <tr>

   <td width="164">payment_id</td>

   <td width="95"> </td>

   <td width="120"> </td>

   <td width="90"> </td>

  </tr>

  <tr>

   <td width="164">customer_id</td>

   <td width="95"> </td>

   <td width="120"> </td>

   <td width="90"> </td>

  </tr>

  <tr>

   <td width="164">payment_id,customer_id</td>

   <td width="95"> </td>

   <td width="120"> </td>

   <td width="90"> </td>

  </tr>

  <tr>

   <td width="164">amount, payment_date</td>

   <td width="95"> </td>

   <td width="120"> </td>

   <td width="90"> </td>

  </tr>

  <tr>

   <td width="164">payment_id,staff_id</td>

   <td width="95"> </td>

   <td width="120"> </td>

   <td width="90"> </td>

  </tr>

 </tbody>

</table>




<strong>For the following questions, download the assignment1.zip file from Polylearn. </strong>

<strong>Q2</strong>Suppose you want to record information about soccer players, their teams, the games where they played, and events (such as ‘a goal scored’) in each game. Create a ​<strong>Player</strong> table that​ stores information about the soccer players. Create a ​<strong>Game</strong>​ table that stores information about the games. Every game is between two teams. Create a ​<strong>Event</strong>​ table recording all events occurred in each game. Create a ​<strong>Team</strong>​ table that stores information about all the teams. Every soccer player belongs to exactly one team (i.e., add a ​<strong>team_id</strong>​ field to the ​<strong>Player</strong>​ table).

Submit the ​<strong>create table</strong>​ statements for the four tables. Include primary key and foreign key constraints.

<strong>Q3[</strong>Create INSERT statements to insert all the data given in supplied text files containing json data to the tables (statements for two of the tables are given. Your task it to crate statements for the remaining two tables). It is recommended that you use Python rather than Java. You need to create a file containing insert statements just like the provided teams.sql and players.sql files.

<strong>Q4[</strong>Create the tables in MySQL and populate them with the data using the insert statements including the ones you created. ​<strong>You should be able to insert all the data into the 4 tables without an error or warning. If you get an error or warning, that means that your table schema needs to be changed.</strong>

You can execute sql statements in a file from mysql shell with the following command: source [filename];

Replace the [filename] with a file name containing sql statements. You might need to prepend the path to the file to the filename if the file is not in your current directory on your machine.




<strong>Q5</strong>write, test, and submit the SQL for the following queries. Add the ​          <strong>distinct</strong>​ keyword if you want to eliminate duplicates.

<ol>

 <li>Print the names of soccer players that have scored a hat-trick (3 or more goals per game).</li>

 <li>Print the names of teams that have one or more players that have scored a hat-trick.</li>

 <li>Print the names of teams that have scored more than 3 goals in a single game.</li>

 <li>Suppose that a team that won the most games win the championship. Write a query to find out which team won the most games. i.e. find the champion team.</li>

 <li>Write a query to list all the teams that beat the champion team.</li>

</ol>

<strong><u>Zip your files containing the answer to Q1 and sql statements and submit it to polylearn. Do not forget</u> <u>to include your name in the files.</u> </strong>