

<h2 align='center' color='#f4a301;'>
Shaun  Pickett
</h2>
<h1 align='center'> HTML Email Signatures  </h1>

<div style='display: flex; gap:0'>
<img src='https://res.cloudinary.com/dyneqi48f/image/upload/v1696125706/light-mode-signature_c50rry.png' 
  alt='' width='48%'/>
<img src='https://res.cloudinary.com/dyneqi48f/image/upload/v1696125706/dark-mode-signature_pidmq5.png' 
  alt='' width='48%'/>
</div>

<h3>HTML email signatures look great but theres an abundance of compatibility and support issues.  </h3>

<p>Why isn't html signature support uniform across all the email giants?
  For example, where Apple mail supports SVG's, gmail doesn't. 
  Where some providers strip the head out of the code and others don't. <br>
  Why is HTML email support so flimsy? I don't know. What I do know is a few do's and donts after strumbling my way through my own design. 
  <br>
  <br> 
  <h2>Things that will save you time. </h2>

 - <strong>Don't Use Media Queries</strong>: Save yourself the headache. Usually, they don't work at all, but when they do, parts won't work in all email browsers. <br> 

 - <strong>Stick to a Mobile Version</strong>: Again without safe media queries, you are likely going to have shrinking and font dilation on mobile. Just make a mobile version and be happy it works. <br>

 - <strong>Don't Use SVG's</strong>:  I learned the hard way. Gmail support just isn't there. <br>
 - <strong>Images Need Transparent BG's</strong>: Dark mode is going to happen whether you like it or not. But do not fear, an email provider like Outlook will automatically change the background color's in all of your code. What you have to watch out for is if your referenced images have a transparent background. Your signature needs to be dark and light friendly. 
 - <strong>Use Referenced Images</strong>: Support is very good for referenced images. I have experienced bugs with apple mail however, I haven't been able to replicate them. 
 - <strong>KISS</strong>: Keep it simple stupid. Everytime I introduced complexity I was punished.
 - <strong>Tables</strong>: Although support for div's and other tags exist, I wouldn't bother. As far as I know, everything for tables just works. You won't find that comfort with a flexbox div across all email clients. And tables keep the code small so play it safe and use table tags. 
</p>
<br>
<h3>How do I inject my signature into my preferred email client? </h3>

 - <strong>Apple mail</strong>: You can't simply drop and drag into the preferences. Its a whole process, almost like they don't want you to do it. The instructions are simple enough though - https://www.hubspot.com/email-signature-generator/add-html-signature-mail-mac#:~:text=Open%20Apple%20Mail%20on%20your,click%20the%20%E2%80%9C%2B%E2%80%9D%20button. 
 - <strong>Gmail</strong>: My method was to install the chrome extension <i>Insert HTML by Designmodo</i>. This nifty little tool adds a html feature that allows you to copy and paste your code into the gmail suite signature box. 
