
# How to Use "multinational-telephone-input"

A brief description on how to use "multinational-telephone-input"


## Documentation

To use the "intl-tel-input" plugin, you will need to follow these steps:

Create an input field in your HTML code with the appropriate class and ID attributes. For example:

First, clone the project

```bash
  git clone https://github.com/CovenantJunior/multinational-telephone-input
```

Go to the project directory

```bash
  cd multinational-telephone-input
```

Create an input tag

```bash
  <input type="tel" id="phone" name="phone" class="form-control" placeholder="Enter phone number">

```

Initialize the "intl-tel-input" plugin on the input field using JavaScript. For example:

```bash
  var input = document.querySelector("#phone");
  window.intlTelInput(input, {
    utilsScript: "build/js/utils.js",
  });

```

Lastly, if you already have an input tag to recieve phone numbers, just add the ```id = "phone"``` to the input tag or change the id property in the Initialization object. For exmaple:

```bash
  <input type="tel" id="call" name="phone" class="form-control" placeholder="Enter phone number">

  var input = document.querySelector("#call");
  window.intlTelInput(input, {
    utilsScript: "build/js/utils.js",
  });

```