# SJF1.0
==========

ABOUT  SHINEJAVAFRAMEWORK(SJF)  
==============================

SHINEJAVAFRAMEWORK(SJF)   is  invented  by  wilmixjemin  j  

at  Jdk1.8.





SYNTAX
=======

<SJF>




public class <CLASSNAME> {

public  static void  main(String args[])
{

<!  SJFLOGIC !>


}

}


</SJF>














SJFFRAMEWORK  DOCUMENTATION
==============================


ADVANTAGES of USING SJF  Framework Project
==========================================

A)  It   is   used  to integerate with  Spring boot  for  webapplication

B)  It  has  attractive syntax 

c)  It   tells   the  developer  to  study  ony  core  java- jdk1.8 concepts

d) SAVES  TIME  AND  COST

E)  It  is also  used as  a mobile   web  application

F) It  has  SJF - Hiber, SJF - Servlet and  follow  MVC  pattern

MVC  pattern  is  userdefined type.

G) We   can  use   with Jquery ,Javascript  for  validation.




EXAMPLE-1: index.SJF
=====================

<SJF>


public class index {

public  static void  main(String args[])
{


HTML.displayhtml("Register.html"); //  HTML.displayhtml  to   display  //the  contents  of  html;  not  this  is  otherwise known  as  JMF //Servlet 



}

}



SJFFRAMEWORK  DOCUMENTATION


</SJF>



Jquerytest.SJF
==============


<SJF>

import  java.util.*;

import jxl.read.biff.BiffException;
import java.io.*;
public  classJquerytest

{
public  static  void  main(String args[]) throws  BiffException,IOException,Exception

{



ArrayList<String> arm1= new  ArrayList<String>();

arm1.add("name");
arm1.add("uname");arm1.add("password");

//  Add    three  fields   name ,uname ,password  of  Register.html
arm1.add("!");




ArrayList<String>armg=SPLITREQUEST.RESULT(arm1,"index.dsn",3,1);

// SPIT the  JMF Page  Request  and  store it  in  arraylist
//  3  indicates  3  fields  of  Register.html
//  1  indicates  increment  counter  by  1


///  Print   the  data   from  register  form  in  table  format

System.out.println("<table style='width:100%' bgcolor=gold>");
// JMF  Servlet
System.out.println("<tr>");


SJFFRAMEWORK  DOCUMENTATION

System.out.println("  <th>Name</th>");

System.out.println("  <th>Username</th>"); 

System.out.println("  <th>Password</th>");


System.out.println(" </tr>");

System.out.println(" <tr>");



for (inti=0;i<armg.size();i++)
{


System.out.println("<td>"+armg.get(i)+"</td>");

 }


System.out.println(" </tr>");


System.out.println("</table>");





}
}


</SJF>







