<htm>
    <head>
        <title>
            Registration form
        </title>
    </head>
    <body>
<br>
<br>
<form>
    <label>*Firstname</label>
        <input type="firstname" size="15"required><br>
        <label> Middlename: </label>     
        <input type="text" name="middlename" size="15" /> <br> <br>  
        <label> *Lastname: </label>         
        <input type="text" name="lastname" size="15"required/> <br> <br>  
          
        <label> 
             *Gender
            </label><br>
            <input type="radio" name="male"required/> Male <br>  
<input type="radio" name="female"required/> Female <br>  
<input type="radio" name="other"required/> Other  
<br>  
<br>  

<label>   

    <label for="birthday">*Birthday:</label>
    <input type="date" id="birthday" name="birthday" required><br><br>
</label>
<label>
    *Phone :  
    </label>  
    <input type="text" name="country code"  value="+91" size="2" required/>
    <input type="text" name="phone" maxlength="10"required >
     <br> <br>  
    *Address  
    <br> 
    <style>
        .comment{
            resize: none;
            height: 100px;
            width: 350px;
        }
        </style>
    <form action="/form/submit" method="post">
    <textarea class="comment" rows="10" cols="40"required> 
    </textarea>  
    <br> <br>  
    *Email:  
    <input type="email" id="email" name="email" required/> <br>    
    <br> <br>  
    *Password:  
    <input type="Password" id="pass" name="pass" required> <br>   
    <br> <br>  
    *Re-type password:  
    <input type="Password" id="repass" name="repass"required> <br> <br>  
    <input type="button" value="Submit"/>
    <input type="reset" value="reset">  
</form>
    </body>
</htm>
