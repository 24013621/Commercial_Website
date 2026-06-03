# Ex02 Commercial Website
## Date: 26/05/2026

## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.6);
  }
  .about p {
    font-size: 1.1em;
    line-height: 1.8;
    padding: 0 30px;
  }
  .contact {
    padding: 80px 0;
    background-color: #222222;
    border-radius: 10px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
    margin: 30px 20px;
  }
  .contact .container {
    max-width: 600px;
    text-align: center;
  }
  .contact h2 {
    color: #64b5f6;
    margin-bottom: 30px;
    text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.6);
  }
  .contact p {
    font-size: 1.1em;
    margin-bottom: 20px;
    display: flex;
    justify-content: center;
    align-items: center;
  }
  .contact p::before {
    content: "";
    display: inline-block;
    width: 20px;
    height: 20px;
    background-size: contain;
    background-repeat: no-repeat;
    margin-right: 10px;
  }
  .contact p:nth-child(2)::before {
    background-image: url('email-icon.png');
  }
  .contact p:nth-child(3)::before {
    background-image: url('phone-icon.png');
  }
```

## OUTPUT

<img width="1919" height="705" alt="image" src="https://github.com/user-attachments/assets/2884bdb0-13b1-4461-94e8-36030c147567" />

<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/b21aa84b-4c4a-4171-878b-533f7135a61d" />

<img width="1916" height="358" alt="image" src="https://github.com/user-attachments/assets/c8413481-53e4-4685-94f3-82070af72590" />

<img width="1919" height="449" alt="image" src="https://github.com/user-attachments/assets/27733547-8527-468f-b115-b7eacbcb6073" />

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
