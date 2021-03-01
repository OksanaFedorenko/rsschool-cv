
# Oksana Fedorenko.

I'm a junior front-end developer. Now I'm open for new opportunities and looking for a position in a company.

## My skills
```
 ● HTML                      ● Bootstrap              ● React (basics)
 ● CSS                       ● Gulp/Webpack           ● Node.js (basics) 
 ● SASS/SCSS                 ● SQL (basics)           ● Linux
 ● JavaScript                ● Git                    ● npm/yarn
```
## Latest works
 [Landing-page for real estate agency (scss, bootstrap, js)](https://github.com/OksanaFedorenko/real-estate)

[Landing-page for web-designer (scss, Bootstrap, js))](https://github.com/OksanaFedorenko/designer-portfolio)

Code example (for rsschool)
```javascript
subscribeForm.addEventListener("submit", function (e) {
  e.preventDefault();

  removeValidation(subscribeForm);

  if (emailField.value == "") {

    let error = generateError("The field cannot be blank");
    insertError(error, emailField);
    removeError(error, emailField);

  } else if (!email_reg.test(emailField.value)) {

    let error = generateError("Not a valid email");
    insertError(error, subscribeForm);
    removeError(error, emailField);

  }
  
});
```
