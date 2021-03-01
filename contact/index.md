---
layout: layouts/post.njk
title: Get In Touch
templateClass: tmpl-post
eleventyNavigation:
  key: Contact
  order: 4
---
<form name="contact" method="POST" data-netlify="true">
    <p>
        <label><strong>Name:</strong> <input type="text" placeholder="Enter you name"  id="name" name="name" /></label>   
    </p>
    <p>
        <label><strong>Email: </strong><input type="email" placeholder="Enter you Email"id="email" name="email" /></label>
    </p>
    <p>
        <label><strong>Your Role:</strong><br />
       <input type="radio" id="leader" name="Your Role" value="leader">
        <label for="leader">Leader</label><br>
        <input type="radio" id="Follower" name="Your Role" value="follower">
        <label for="follower">Follower</label><br>
        </select></label>
    </p>
    <p>
        <label><strong>Message:</strong><br /> <textarea name="message" placeholder="Type your message"></textarea></label>
    </p>
    <p>
        <button class="form_submit" type="submit">Send</button>
    </p>
</form>
