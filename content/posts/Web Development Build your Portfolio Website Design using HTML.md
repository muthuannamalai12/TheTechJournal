---
title: "Web Development: Build your Portfolio Website Design using HTML"
date: 2021-06-12
description: "In this article we learn about how to build a portfolio website using HTML"
cover:
  image: "images/Web Development - Portfolio.jpg"
  alt: "Web Development - Portfolio"
tags: [webdevelopment, portfolio]
---

Being a web developer and having a portfolio helps a lot while applying for opportunities and acts as a showcase of our talent, so in this article, we will learn how to make a simple portfolio by just using HTML. This portfolio might contain

1. An image displayed as a profile photo
2. Uses emphasis and strong tags for formatting
3. Has tables to better display data
4. Links to other pages like Hobbies and Contact(displayed at bottom of the page)
5. A contact form that emails details.

**File structure**:

- index.html
- hobbies.html
- contact.html
- images folder(You will put your photo into this folder and use it as your profile photo)

**Code Implementation:**

1- For index.html file:

```
<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="utf-8">
  <title>Muthu Annamalai Venkatachalam's Personal Site</title>
</head>
<body>
  <table cellspacing="20">
    <tr>
      <td><img src="images/Muthu Profile Photo.jpeg" alt="Profile Picture" width="200" height="200" /></td>
      <td>
        <h1>Muthu Annamalai Venkatachalam</h1>
        <p><em>An Aspiring Software Developer | Student | <strong>Web Developer</strong></em></p>
        <p>A Engineer who works 24/7 to improve himself. I'm a problem-solver at heart, highly teachable and eager to learn new skills, fun to work with, have a killer work ethic, and above all, extremely curious and ask a lot of questions.My Motto is to Aspire To Inspire Before we Expire</p>
      </td>
    </tr>
  </table>
  <hr />
  <h3>My Education</h3>
  <ul>
    <li>Srimathi Sundaravalli Memorial School</li>
    <li>NSN Matriculation Higher Secondary School</li>
    <li>Panimalar Engineering College</li>
  </ul>
  <hr />
  <h3>Work Experience</h3>
  <table border="1px">
    <tr>
      <th>Dates</th>
      <th>Work</th>
    </tr>
    <tr>
      <td>July2020 To July2020</td>
      <td>Campus Ambassador at IMUN</td>
    </tr>
    <tr>
      <td>August2020 To August 2020</td>
      <td>Campus Ambassador at TechieGen</td>
    </tr>
    <tr>
      <td>February2021 To May2021</td>
      <td>Open Source Contributor at GSSOC'21</td>
    </tr>
  </table>
  <hr />
  <h3>Skills</h3>
  <table cellspacing="10">
    <tr>
      <td>HTML</td>
      <td>⭐⭐⭐</td>
    </tr>
    <tr>
      <td>CSS</td>
      <td>⭐⭐⭐</td>
    </tr>
    <tr>
      <td>Java</td>
      <td>⭐⭐⭐</td>
    </tr>
    <tr>
      <td>JavaScript</td>
      <td>⭐⭐⭐</td>
    </tr>
  </table>
  <hr />
  <a href="hobbies.html">My Hobbies</a>
  <a href="contact.html">Contact Me</a>
</body>

</html>

```

2- For hobbies.html file:

```
<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="utf-8">
  <title>My Hobbies</title>
</head>
<body>
  <h3>My Hobbies</h3>
  <ol>
    <li><a href="https://www.telegraph.co.uk/content/dam/cricket/2019/04/01/TELEMMGLPICT000192546944_trans_NvBQzQNjv4Bq900leoZVuq6ru6F43OqP_mjnRw13ichYxOyPsROrpNM.jpeg">I love Playing Cricket</a></li>
    <li><a href="https://filmdaily.co/wp-content/uploads/2020/05/cbd-lede-1300x813.jpg">I love Watching Movies</a></li>
    <li><a href="https://static.toiimg.com/photo/67625374.cms">I love Listening To Music</a></li>
  </ol>
</body>
</html>

```

3- For the contact.html file

```
<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="utf-8">
  <title>My Contact</title>
</head>
<body>
  <h1>My Contact Details</h1>
  <p>My Address: No:63(A) , Ground Floor, Ramani Illam,2nd Cross Street, Chandran Nagar, Chromepet,Chennai-44</p>
  <p>My Phone Number: 7358833533</p>
  <p>My Gmail: muthuannamalai2002@gmail.com</p>
  <form class="" action="mailto:muthuannamalai2002@gmail.com" method="post" enctype="text/plain">
    <label>Your Name</label>
    <input type="text" name="Your Name" value=""><br />
    <label>Your email</label>
    <input type="email" name="Your Email" value="" /><br />
    <label>Your Message</label><br />
    <textarea name="Your Message" rows="10" columns="30"></textarea><br />
    <input type="submit" name="" />
  </form>
</body>
</html>

```

Now the project is ready!

This is the output:

![Screenshot (1192).png](https://cdn.hashnode.com/res/hashnode/image/upload/v1623473693265/3I4BhSR6y.png)

See it live: https://muthuannamalai12.github.io/CV/

Link To GitHub Repository: https://github.com/muthuannamalai12/CV

**The End**

**I hope you found this article valuable. If yes do let me know in the comments 😊**

**Also if you got any question feel free to ping me on [Twitter](https://twitter.com/muthuannamalai_)**

> You can now extend your support by buying me a Coffee.😊👇

[Buy Me A Coffee](https://www.buymeacoffee.com/muthuannamalai)

Thanks for Reading 😊
