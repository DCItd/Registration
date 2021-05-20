
<input type="text" name="adress" placeholder="Address Of Participant" data-required data-number>   
<input type="text" name="city" placeholder="city" data-required data-number> <space> <space> <input type="text" name="state" placeholder="State" data-required data-number> <space> <space> <input type="text" name="zCode" placeholder="Zip Code" data-required data-number>   
<space> <space> <space>
<div class="form-item box-item">
<input type="text" name="phoneCell" placeholder="Cell Phone" data-required data-number data-count="10"> <space> <space> <input type="text" name="phoneHome" placeholder="Home Phone" data-required data-number data-count="10">  <space> <space> <input type="text" name="phoneWork" placeholder="Work Phone" data-required data-number data-count="10">
            

<form>  
    <head>  
        <h2>DCI Registration</h2>
    </head>
    <body>
        <h4>    
            <p>
                <input type="text" name="name" placeholder="Frist Name" data-required> <space> <space> <space> <input type="text" name="nameMiddle" placeholder="Middle Name"> <space> <space> <space> <input type="text" name="nameFamily" placeholder="Last Name" data-required>   
            <p>
            </p>
            <p>
                <label> Birthday:<input type="date" name="birthday"></label> <space> <space> <space> <label> Age:<input type="number" id="years" name="Age" placeholder=" - " data-required> <space> <space> <space> <label>Education Level:</label> 
                <select name="Education Level">
                    <option value="Blank"> - </option>
                    <option value="Elementary School">ElementarySchool</option>
                    <option value="Middle School">MiddleSchool</option>
                    <option value="High School">HighSchool</option>
                    <option value="Sum College">SumCollege</option>
                    <option value="Associate Degree">AssociateDegree</option>
                    <option value="Bachelor's Degree">BachelorDegree</option>
                    <option value="Master's Degree">MasterDegree</option>
                    <option value="Doctoral Degree">DoctoralDegree</option>   
                </select>             
            </p>
            <p>
              <div class="radio-label"> 
              <label class="label">Gender</label>
              <div class="form-item"> 
              <input id="Male" type="radio" name="gender" value="Male" data-once>
              <label for="Male">Male</label>
              <div class="form-item"> 
              <input id="Female" type="radio" name="gender" value="Female" data-once>
              <label for="Female">Female</label>
            </p>
            <p>
                <label>Password:<input type="password" name="password"></label>
            </p>
            <p>
                <label> PW Confirm:<input type="password" name="password"></label>
            </p>
            <p>
               <label> PW Confirm:<input type="password" name="password"></label>
            </p>
            <p>
                <lable>Email:<input type="text" name="email"></lable>
            </p>
            <p>
                <label>Password:<input type="password" name="password"></label>
            </p>
            <p>
                <label> PW Confirm:<input type="password" name="password"></label>
            </p>
            <p>
            <div class="radio-label"> 
              <label class="label">Gender</label>
            </div>
            <div class="form-item"> 
              <input id="Male" type="radio" name="gender" value="Male" data-once>
              <label for="Male">Male</label>
            </div>
            <div class="form-item"> 
              <input id="Female" type="radio" name="gender" value="Female" data-once>
              <label for="Female">Female</label>
            </div>
          </div>
                Gender:    
<label>Male <input type="radio" name="gender" value="male"></label>
<label>Female <input type="radio" name="gender" value="female"></label> 
<label>Other <input type="radio" name="gender" value="decline"></label>
                Marriage Status:   
<label>Single <input type="radio" name="marriage" value="Single"></label>
<label>Married <input type="radio" name="marriage" value="Married"></label>
<label>Divorced <input type="radio" name="marriage" value="Divorced"></label>   

            </p>
            <p>
                <label>Male<input type="radio" name="gender" value="male"></label>
                <label>Female<input type="radio" name="gender" value="female"></label>
                <label>Other<input type="radio" name="gender" value="decline"></label>
            <p>
                <label>A short description about yourself:</label>
            </p>
            <p>
                <textarea name="A short description about yourself:"></textarea>
            </p>
            <p>
                <label>Favorite Language</label> 
                <select name="Language">
                    <option value="JavaScript">JavaScript</option>
                    <option value="Python">Python</option>
                    <option value="C++">C++</option>
                </select>
            </p>
        </h3>
    </body>
</form>

</html>







<div class="row">
  <section class="section">
    <header>
      <h3>Register</h3>
      <h4>Please fill your information bellow</h4>
    </header>
    <main>
      <form>
        <div class="form-item box-item">
          <input type="text" name="name" placeholder="Name" data-required>
          <small class="errorReq"><i class="fa fa-asterisk" aria-hidden="true"></i> required field</small>
        </div>
        <div class="form-item box-item">
          <input type="email" name="email" placeholder="Email" data-email data-required>
          <small class="errorReq"><i class="fa fa-asterisk" aria-hidden="true"></i> required field</small>
          <small class="errorEmail"><i class="fa fa-asterisk" aria-hidden="true"></i> email is not valid</small>
        </div>
        <div class="form-item box-item">
          <div class="form-item-triple">
            <div class="radio-label"> 
              <label class="label">Gender</label>
            </div>
            <div class="form-item"> 
              <input id="Male" type="radio" name="gender" value="Male" data-once>
              <label for="Male">Male</label>
            </div>
            <div class="form-item"> 
              <input id="Female" type="radio" name="gender" value="Female" data-once>
              <label for="Female">Female</label>
            </div>
          </div>
          <small class="errorOnce"><i class="fa fa-asterisk" aria-hidden="true"></i> choose at least one</small>
        </div>
        <div class="form-item box-item">
          <div class="form-item-triple">
            <div class="radio-label"> 
              <label class="label">Type</label>
            </div>
            <div class="form-item"> 
              <input id="sponsored" type="radio" name="gender2" value="sponsored" data-once>
              <label for="sponsored">sponsored</label>
            </div>
            <div class="form-item"> 
              <input id="paid" type="radio" name="gender2" value="paid" data-once>
              <label for="paid">paid</label>
            </div>
          </div>
          <small class="errorOnce"><i class="fa fa-asterisk" aria-hidden="true"></i> choose at least one</small>
        </div>
        <div class="form-item box-item">
          <input type="text" name="address" placeholder="Address" data-required>
          <small class="errorReq"><i class="fa fa-asterisk" aria-hidden="true"></i> required field</small>
        </div>
        <div class="form-item-double box-item">
          <div class="form-item ">
            <input type="text" name="strNumber" placeholder="Street Number" data-required data-number>
            <small class="errorReq"><i class="fa fa-asterisk" aria-hidden="true"></i> required field</small>
            <small class="errorNum"><i class="fa fa-asterisk" aria-hidden="true"></i> must be a number</small>
          </div>
          <div class="form-item">
            <input type="text" name="zCode" placeholder="Zip Code" data-required data-number>
            <small class="errorReq"><i class="fa fa-asterisk" aria-hidden="true"></i> required field</small>
            <small class="errorNum"><i class="fa fa-asterisk" aria-hidden="true"></i> must be a number</small>
          </div>
        </div>
        <div class="form-item box-item">
          <input type="text" name="phone" placeholder="Phone" data-required data-number data-count="10">
          <small class="errorReq"><i class="fa fa-asterisk" aria-hidden="true"></i> required field</small>
          <small class="errorNum"><i class="fa fa-asterisk" aria-hidden="true"></i> must be a number</small>
          <small class="errorChar"><i class="fa fa-asterisk" aria-hidden="true"></i> must be 10 digits</small>
        </div>
        <div class="form-item">
          <span id="submit" class="submit">Submit</span>
        </div>
      </form>
    </main>
    <footer>
      <p>Already have an account? <a href="#">Login here</a></p>
    </footer>
    <i class="wave"></i>
  </section>
</div>

