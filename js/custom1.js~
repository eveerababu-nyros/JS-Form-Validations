var barwidth = 0;

var unamecount=0;
function usrname_validation(usr) {
				var username=usr.value;
				var letters = /^[a-z A-Z 0-9]{5,8}$/;  
				if(username.match(letters))
				   {  
					barwidth=barwidth+10;
					//alert(barwidth);
					if(unamecount<=0) {
					document.getElementById('progress').style.width=barwidth+'%';
					unamecount++;
					}
					document.getElementById('username_msg').innerHTML="";
					return true;  
				   }  
				else  
				   {  	
					
					x="Only Alpha Numeric and Length between 5-8 chars ";
					document.getElementById('username_msg').innerHTML ="<img src='./img/error.png'/>" +x;
					usr.focus();  
					return false;  
			   	   }  
			}// Username validations()
var pwdcount=0;

function pwd_validation(pwd)  
			  {  
			       var password = pwd.value;  
			       var letters = /^[a-z A-Z 0-9]{1,6}$/;  
				if(password.match(letters))
				   {  
					if(pwdcount<=0) {
					barwidth=barwidth+10;
					document.getElementById('progress').style.width=barwidth+'%';
					pwdcount++;
					}
					document.getElementById('pwd_msg').innerHTML="";
					return true;  
				   }  
				else  
				   {  	
					
					x="Alpha Numeric only and Password Max length 6 characters";
					document.getElementById('pwd_msg').innerHTML = "<img src='./img/error.png'/>"+x;
					pwd.focus();  
					return false;  
			   	   }  
			 }//pwd-validation()  
var fnamecount=0;

function fname_validation(fname)  
			  {  
			     var minval=2;
			     var maxval=6;
			     var firstname = fname.value;
				var firstname_len = firstname.length;  
				if (firstname_len == 0 || firstname_len > maxval || firstname_len < minval)  
				 {  
			       msg="First Name should not be empty / length be between "+minval+" to "+maxval;
		  		      document.getElementById('fname_msg').innerHTML = "<img src='./img/error.png'/>" +msg; 
				       
					fname.focus();  
					return false;  
				  }  
				else {
					if(fnamecount<=0) {
					barwidth=barwidth+10;
					document.getElementById('progress').style.width=barwidth+'%';
					fnamecount++;
					}
					document.getElementById('fname_msg').innerHTML = "";
					return true;  
				}
			 }//fname-validation()  

var lnamecount=0;
function lname_validation(lname)  
			  {  
			     var minval=2;
			     var maxval=15;
			     var lastname = lname.value;
				var lastname_len = lastname.length;  
				if (lastname_len == 0 || lastname_len >= maxval || lastname_len < minval)  
				 {  
			       msg="Last Name should not be empty / length be between "+minval+" to "+maxval;
		  		      document.getElementById('lname_msg').innerHTML = "<img src='./img/error.png'/>" +msg;  
					lname.focus();  
					return false;  
				  }  
				else {
					if(lnamecount<=0) {
					barwidth=barwidth+10;
					document.getElementById('progress').style.width=barwidth+'%';
					lnamecount++;
					}
					document.getElementById('lname_msg').innerHTML = "";
					return true;  
				}
			 }//lname-validation()  

var propiccount=0;
function propic_validation(profile_pic)  
			  {  
			     var extension=profile_pic.value.split('.').pop('.');
				 //(extension=='jpg' || extension == 'gif' || extension == 'png'))  
			     if (extension != "jpg" && extension != "png" && extension != "gif") 
 				 {  
			              msg="Picture format should be .jpg, .png, .gif only";
		  		      document.getElementById('propic_msg').innerHTML = "<img src='./img/error.png'/>"+msg;  
				      profile_pic.focus();  
				      return false;  
				  }  
			     else {
					if(propiccount<=0) {
					barwidth=barwidth+10;
					document.getElementById('progress').style.width=barwidth+'%';
					propiccount++;
					}
					document.getElementById('propic_msg').innerHTML = "";
					return true;  
				}
			        
			  }//Propic-validation() 

var count=0;
function dob_validation(day)  
			  {  
			    // alert("out" +count);
			     if(day.name=="year" && count<=0) {
					//alert("in"+count);
					barwidth=barwidth+10;
					document.getElementById('progress').style.width=barwidth+'%';
					count++;
			     }			
			     var day=day.value;
			     if (day=="sel") 
 				 {  
			              msg="Please Select Date/ Month / Year";
		  		      document.getElementById('dob_msg').innerHTML = "<img src='./img/error.png'/>"+msg;  
				      this.focus();  
				      return false;  
				  }  
			     else {
					document.getElementById('dob_msg').innerHTML = "";
					return true;  
				}
			        
			  }//Dob-validation() 


function hobby_validation(hobby) 
			  {  
				
				var painting=document.getElementById('optionsRadios1');
				var singing=document.getElementById('optionsRadios2');
				var traveling=document.getElementById('optionsRadios3');
				var dancing=document.getElementById('optionsRadios4');
				var gardening=document.getElementById('optionsRadios5');
				var other=document.getElementById('optionsRadios6');

				

				if(hobby.name==painting.name)
				    {
					if(painting.checked==false)
					    {
						msg="Please Select any Hobby First one is Manadatory";
		  		      		document.getElementById('hob_msg').innerHTML = "<img src='./img/error.png'/>"+msg;  
				      		this.focus();  
					    }
					 else {
						barwidth=barwidth+3;
					document.getElementById('progress').style.width=barwidth+'%';
						document.getElementById('hob_msg').innerHTML="";
					 }
					return true;	
				
				    }

				else if(hobby.name==singing.name)
				    {
					if(singing.checked==false && painting.checked==false)
					    {
						msg="Please Select any Hobby";
		  		      		document.getElementById('hob_msg').innerHTML = "<img src='./img/error.png'/>"+msg;  
				      		this.focus();  
					    }
					 else{
						barwidth=barwidth+3;
					document.getElementById('progress').style.width=barwidth+'%';
						document.getElementById('hob_msg').innerHTML="";
					 }
									
					return true;	
				
				    }

				else if(hobby.name==traveling.name)
				    {
					if(traveling.checked==false && singing.checked==false && painting.checked==false)
					    {
						msg="Please Select any Hobby";
		  		      		document.getElementById('hob_msg').innerHTML = "<img src='./img/error.png'/>"+msg;  
				      		this.focus();  
					    }
					 else{

						barwidth=barwidth+3;
					document.getElementById('progress').style.width=barwidth+'%';
						document.getElementById('hob_msg').innerHTML="";
					 }
									
					return true;	
				
				    }

				else if(hobby.name==dancing.name)
				    {
					if(dancing.checked==false && traveling.checked==false && singing.checked==false && painting.checked==false)
					    {
						msg="Please Select any Hobby";
		  		      		document.getElementById('hob_msg').innerHTML = "<img src='./img/error.png'/>"+msg;  
				      		this.focus();  
					    }
					 else{

						barwidth=barwidth+3;
					document.getElementById('progress').style.width=barwidth+'%';
						document.getElementById('hob_msg').innerHTML="";
					 }
									
					return true;	
				
				    }
				 else if(hobby.name==gardening.name)
				    {
					if(gardening.checked==false && dancing.checked==false && traveling.checked==false && singing.checked==false && painting.checked==false)
					    {
						msg="Please Select any Hobby";
		  		      		document.getElementById('hob_msg').innerHTML = "<img src='./img/error.png'/>"+msg;  
				      		this.focus();  
					    }
					 else{

						barwidth=barwidth+3;
					document.getElementById('progress').style.width=barwidth+'%';
						document.getElementById('hob_msg').innerHTML="";
					 }
									
					return true;	
				
				    }
				
				 else if(hobby.name==other.name)
				    {
					if(other.checked==false && gardening.checked==false && dancing.checked==false && traveling.checked==false && singing.checked==false && painting.checked==false)
					    {
						msg="Please Select any Hobby";
		  		      		document.getElementById('hob_msg').innerHTML = "<img src='./img/error.png'/>"+msg;  
				      		this.focus();  
					    }
					 else{

						barwidth=barwidth+3;
					document.getElementById('progress').style.width=barwidth+'%';
						document.getElementById('hob_msg').innerHTML="";
					 }
									
					return true;	
				
				    }
			} // Hobby validation


var countrycount=0;
function country_validation(country)  
			  {  
			     //var country=country.value;
				
			     if (country.selectedIndex<0) 
 				 {  
				      msg="Please Select any Country";
		  		      document.getElementById('country_msg').innerHTML = "<img src='./img/error.png'/>"+msg;  
				      this.focus();  
				      return false;  
				  }  
			     else {
					if(countrycount<=0) {
					barwidth=barwidth+4;
					document.getElementById('progress').style.width=barwidth+'%';
					countrycount++;
					}
					document.getElementById('country_msg').innerHTML = "";
					return true;  
				}
			        
			  }//country-validation() 

var phcount=0;
function phone_validation(ph) {
				
				var phnumber=ph.value; 
				//var phone_pattern = /^[7-9]\d{3}-\d{3}-\d{4}$/;
				//var phone_pattern = /^(\+)(\d{2})(\s)(\d{3}-)(\d{3}-)(\d{4})$/;
				//var phone_pattern = ^\(?([0-9]{3})\)?[-. ]?([0-9]{3})[-. ]?([0-9]{4})$;
		var phone_pattern = /^(\+)(\d{2})(\s)(\({1})(\d{3})(\){1})(\-{1})(\d{3}-)(\d{4})$/;
				

				if(phnumber.match(phone_pattern))
				   {  	
					if(phcount<=0) {
					barwidth=barwidth+10;
					document.getElementById('progress').style.width=barwidth+'%';
					phcount++;
					}
					document.getElementById('phone_msg').innerHTML="";
					return true;  
				   }  
				else  
				   {  	
					
					x="Phone Format should be +91 (990)-824-7888";
					document.getElementById('phone_msg').innerHTML = "<img src='./img/error.png'/>"+x;
					ph.focus();  
					return false; 
			   	   } 
				
			}// Phone validations()


			/** Individual Element Validation is completed */


		/* submit button Validation */

function validateForm(regForm) {
		var username = document.getElementById('inputname');
		var password = document.getElementById('inputPassword');
		var fname = document.getElementById('inputfname');
		var lname = document.getElementById('inputlname');
		var propic = document.getElementById('inputpropic');
		var gender = document.getElementById('inputradio');
		var dob = document.getElementById('day');
		var month = document.getElementById('mon');
		var year = document.getElementById('year');			
		var hobby1 = regForm.painting;
		var hobby2 = document.getElementById('optionsRadios2');
		var hobby3 = document.getElementById('optionsRadios3');
		var hobby4 = document.getElementById('optionsRadios4');
		var hobby5 = document.getElementById('optionsRadios5');
		var hobby6 = document.getElementById('optionsRadios6');
		var country = document.getElementById('inputcountry');
		var phnum = document.getElementById('inputPhone');

		var extension=propic.value.split('.').pop('.');

		var phone_pattern = /^(\+)(\d{2})(\s)(\({1})(\d{3})(\){1})(\-{1})(\d{3}-)(\d{4})$/;

		if(username.value==null || username.value=="") {
				usrname_validation(username);
			}
			else if(password.value==null || password.value=="") {
				pwd_validation(password);
			}
			else if(fname.value==null || fname.value=="") {
				fname_validation(fname);
			}					
			else if(lname.value==null || lname.value=="") {
				lname_validation(lname);
			}
			else if(propic.value==null || propic.value=="") {
				propic_validation(propic);
			}
			else if(extension != "jpg" && extension != "png" && extension != "gif") {
				propic_validation(propic);
			}
			else if(dob.value=="sel") {
				dob_validation(dob);	
			}
			else if(month.value=="sel") {
				dob_validation(month);
			}	
			else if(year.value=="sel") {
				dob_validation(year);				  
			}
			
			else if(hobby1.checked==false) {
				hobby_validation(hobby1);
			}
			else if(country.selectedIndex<0) {
				country_validation(country);
			}
			else if(phnum.value==null || phnum.value=="") {
				phone_validation(phnum);	
			}
			else if(!(phnum.value.match(phone_pattern))) {
				phone_validation(phnum);
			}
			else {
				document.getElementById('alertmessage').style.display="block";
			}
					
			
return false;
}

function reloading() {
	
	window.location.reload();
	return true;
}
