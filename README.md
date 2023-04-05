# fb-auth
Firebase Authentication

``` Javascript
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/aesajce/fb-auth@1.0.2/auth-ui.css"> <br><br>

<script src="https://cdn.jsdelivr.net/gh/aesajce/fb-auth@1.0.2/auth-ui.js"></script>

<script>
    initAuth({
         apiKey: "AIzaSyDQM5QkMsQ59017uaBz7aNKBQPYaiYOWCA",
             authDomain: "auth.ajce.in",
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
