# Responsive Email Template

This is a Basic Template for Startup Responsive Creative Email

## Usage

### Startup Code:

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <!--[if !mso]><!-->
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <!--<![endif]-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
    <!--[if (gte mso 9)|(IE)]>
    <style type="text/css">
        table {border-collapse: collapse;}
    </style>
    <![endif]-->
</head>
<body>
    <center class="wrapper">
        <div class="webkit">
            [email body]
        </div>
    </center>
</body>
</html>
```

### Basic Css

```html
/* Basics */
body {
    margin: 0 !important;
    padding: 0;
    background-color: #ffffff;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
table {
    border-spacing: 0;
    border: none; 
    border-collapse: collapse;
    font-family: Arial, sans-serif;
    color: #585858;
}
td {
    padding: 0;
}
img {
    border: 0;
}
div[style*="margin: 16px 0"] { 
    margin:0 !important;
}
.wrapper {
    width: 100%;
    table-layout: fixed;
    -webkit-text-size-adjust: 100%;
    -ms-text-size-adjust: 100%;
}
.webkit {
    max-width: 600px;
    margin: 0 auto;
}
```

### Conditional CSS for Outlook

```html
<!--[if (gte mso 9)|(IE)]> and <![endif]--> 
```

This conditional expression targets all versions of Microsoft Outlook (mso) greater than or equal to version 9.
Which is all of them since version 9 is the earliest: Outlook 2000 as well as versions of Outlook that use Internet Explorer to render being Outlook 2000–2003.


### Margin little hack

Always capitalise Margin so that Outlook.com won’t strip it out


## Bring Your Email Styles Inline

- use [inliner](http://foundation.zurb.com/emails/inliner-v2.html) tool


## Demo

 - [email demo](http://yuliyawebdevelopment.com/demos/responsive-email-template/)
 
 


