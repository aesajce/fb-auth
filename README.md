# fb-auth
Firebase Authentication

``` Javascript
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/aesajce/fb-auth@1.0.2/auth-ui.css">

<script src="https://cdn.jsdelivr.net/gh/aesajce/fb-auth@1.0.2/auth-ui.js"></script>

<script>
    initAuth({
         apiKey: "AIzaSy-----------------", //API-KEY
             authDomain: "auth.ajce.in", // Auth Doamin
             policy:false,
             providers:[
                 "google","microsoft","email"
             ]
         },function(user){
             if(user){
                 if(user.isPhone){
                    // Mobile Verification
                 }else{
                    // Non-Mobile Verification
                 }
             }
         })
         verifyPhone();
 </script>
 
 $('#firebaseui-auth').modal('show');

```
