# ConcertTicketReservationSystem

<h1>What is it?</h1>

<p>This is a project for 6th semester of my university course in retrieval of data.It's an online ticket reservation system for concerts that it works local.The concerts take place at the most famous stadiums in Greece.Every stadium  has different capacity and is headquartered in a different place.A client can buy one or more tickets.Also, he can cancel the reservation,so his money goes back to him.Every concert have a different cost.</p>


<h1>How it works</h1>

<p>Before run this app change the config.php file with your own informations.</p> 
<code>
<?php
    $host = "127.0.0.1";
    $user = "";   //change it with your username              
    $pass = "";   // change it with your password                            
    $db = "";     // change it with your db name                             
    $port = 3306;
     $con = mysqli_connect($host, $user, $pass, $db, $port)or die(mysql_error());
?>
</code>

<p>Set ut the db from the dump file</p>

<p>If you want to buy a ticket you must log in first.Sign in or use the below data.Be careful 3 times wrong password block your account.<b>TODO block expire</b>.</p> 

<code>
username:ts@hotmail.com
password:ts
</code>



<p>Technology Stack</p><hr>
<ul>

<li>Front-End
   <ul>
     <li>CSS</li>
     <li>Javascript</li>
     <li>Bootstrap 3</li>
     <li>Jquery</li>
     <li>Bootstrap validator</li>
  </ul>
</li>


<li>Server-Side
<ul>
   <li>PHP 5</li>
   </ul>
</li>


<li>DB
<ul>
   <li>MySql</li>
   
   </ul>
</li>
  
</ul>




