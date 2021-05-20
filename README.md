# Registration
#XXX
<!DOCTYPE html>
<html>
    <head>
        <title>Venture Garden Registration Form</title>
        <meta charset="utf-8"/>
        <link rel="stylesheet" type = "text/css" href="form.css"/>
    </head>
    <body>
        <h1 id="caption">Venture Garden Registration Form</h1>
        <div class="formstage">
            <form id = "venture-form"  onsubmit=" return validate()">
                <p class ="description">Let Us know you better</p>
                <div class = "row-tab">
                    <div class="label-venture">
                        <label>*Name</label>
                    </div>
                    <div class="input-venture">
                        <input id = "name" type = "text" placeholder="Name"></input>
                    </div>
                </div>
                <div class = "row-tab">
                    <div class="label-venture">
                        <label>*Email</label>
                    </div>
                    <div class="input-venture">
                        <input id = "email" type = "text" placeholder="Email">
                    </div>
                </div>
                
                <div class = "row-tab">
                    <div class="label-venture">
                        <label>*Age</label>
                    </div>
                    <div class="input-venture">
                        <input id = "age" type = "number" placeholder="Age">
                    </div>
                </div>
                <div class = "row-tab">
                    <div class="label-venture">
                        <label>*Password</label>
                    </div>
                    <div class="input-venture">
                        <input id = "password" type = "password" placeholder="Password">
                    </div>
                </div>
                <div class = "row-tab">
                    <div class="label-venture">
                        <label>*Confirm Password</label>
                    </div>
                    <div class="input-venture">
                        <input id = "confirm_password" type = "password" placeholder="Confirm Password">
                    </div>
                </div>
                <div class = "row-tab">
                    <div class="label-select">
                        <label>Which option best describes your technology stack?</label>
                    </div>
                    <div class="select-input">
                        <select id = "dropdown">
                            <option value ="select stack"></option>
                            <option value="frontend">FrontEnd</option>
                            <option value= "backend"> Backend</option>
                            <option value = "devops">Devops</option>
                            <option value = " Qualityassurance">Quality Assurance</option>
                        </select>
                    </div>

                </div>
                <div class="row-tab">
                    <div class="label-radio">
                        What is your Proficiency Level?
                    </div>
                    <div class="input-radio">
                        <div>
                            <label>
                                <input type="radio" name="feedback" value = "beginner">
                            </label> Beginner
                        </div>
                        <div>
                            <label>
                                <input type="radio" name="feedback" value = "intermediate">
                            </label>Intermediate
                        </div>
                        <div>
                            <label>
                                <input type="radio" name="feedback" value = "advanced">
                            </label> Advanced
                        </div>
                        <div>
                            <label>
                                <input type="radio" name="feedback" value = "expert">
                            </label> Expert
                        </div>
                    </div>
                </div>

                <div class="row-tab">
                    <div class="text-area">
                        Any comments or observation?
                    </div>
                    <textarea id="comment" type></textarea>
                </div>
                <div class="row-tab">
                    <div class="submit-button">Submit Here: </div>
                    <input class = "button" type = "submit"> 
                </div>
            </form>
        </div>
    </body>
    <script src="logic.js"></script>
</html>
#xxx
<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>
	<h1>My Registration Form</h1>

	<form>
		<label for="first_name">First Name:</label>
		<input type="text" id="first_name" name="first_name">

		<p></p>
		<label for="last_name">Last Name:</label>
		<input type="text" id="last_name" name="last_name">

		<p></p>
		<label for="email">Email</label>
		<input type="text" id=email name="email">

		<p></p>
		<label for="password">Password</label>
		<input type="password" id="password" name="password">

		<p></p>
		<label for="pwconfirm">PW Confirm</label>
		<input type="password" id="pwconfirm" name="pwconfirm">

		<p></p>
		<label for="datetime-local">Birthday</label>
		<input type="datetime-local" id="datetime-local" name="datetime-local">

		<p></p>
		<label for="male">Male</label>
		<input type="radio" id=male name="gender" value="male">
		<label for="female">Female</label>
		<input type="radio" id=female name="gender" value="female">
		<label for="other">Other</label>
		<input type="radio" id=decline name="gender" value="decline">

		<p>Say a few words about yourself:</p>
		<textarea name="description"></textarea>

		<p></p>
		Favorite Language	<select>
			
			<option value="javascript">Javascript</option>
			<option value="testing">Testing</option>
		</select>

		<p></p>
		<input type="submit" value="Submit">




	</form>

</body>
</html>

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
            <input type="text" name="strNumber" placeholder="Str Number" data-required data-number>
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
