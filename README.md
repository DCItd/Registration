# Registration

<html>
<form>  
    <head>  
        <h1>Dean Counseling Inc. Registration Information</h1>
    </head>
    <body>
         <h4>
<input type="text" name="name" placeholder="Frist Name" data-required> <space> <space> <space> <input type="text" name="nameMiddle" placeholder="Middle Name"> <space> <space> <space> <input type="text" name="nameFamily" placeholder="Last Name" data-required>    
    
Gender:
<label>Male<input type="radio" name="gender"  value="male"></label>
<label>Female<input type="radio" name="gender"  value="female"></label>
<label>Other<input type="radio" name="gender"  value="decline"></label>

Marriage Status:
<label>Male<input type="radio" name="marriage"  value="Single"></label>
<label>Female<input type="radio" name="marriage"  value="Married"></label>
<label>Other<input type="radio" name="marriage"  value="Divorced"></label>   


<input type="text" name="adress" placeholder="Adress Of Participant" data-required data-number>   
<input type="text" name="city" placeholder="city" data-required data-number> <space> <space> <input type="text" name="state" placeholder="State" data-required data-number> <space> <space> <input type="text" name="zCode" placeholder="Zip Code" data-required data-number>   
<space> <space> <space>
<div class="form-item box-item">
<input type="text" name="phoneCell" placeholder="Cell Phone" data-required data-number data-count="10"> <space> <space> <input type="text" name="phoneHome" placeholder="Home Phone" data-required data-number data-count="10">  <space> <space> <input type="text" name="phoneWork" placeholder="Work Phone" data-required data-number data-count="10">
          <small class="errorReq"><i class="fa fa-asterisk" aria-hidden="true"></i> required field</small>
          <small class="errorNum"><i class="fa fa-asterisk" aria-hidden="true"></i> must be a number</small>
          <small class="errorChar"><i class="fa fa-asterisk" aria-hidden="true"></i> must be 10 digits</small>
        </div>
        <div class="form-item">
          <span id="submit" class="submit">Submit</span>
        </div>
    </form>
            
                
## XXXX
<!DOCTYPE html>
<html>
<form>  
    <head>  
        <h1>My Registration Form</h1>
    </head>
    <body>
        <h3>    
            <p>
                <label>First Name:<input type="text" name="first name"></label>
            </p>
            <p>
                <label>Last Name:<input type="text" name="last name"></label>
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
                <label> Birthday:<input type="date" name="birthday"></label>
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

You can use the [editor on GitHub](https://github.com/DCItd/RegistrationInfo/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/DCItd/RegistrationInfo/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
