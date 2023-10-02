
#  Boost your email swag with <span style="color: #f4a301;">HTML  Signatures</span>

Tired of your email signature looking as dull as dishwater?
 Your signature is your personal brand statement. And HTML email signatures are your ticket to adding a dash of personality to your emails

But here's the catch - crafting a HTML email signature is a nightmare. There are compatibility quirks, design challenges, and no support from the big email providers. This readMe is a quick overview of the important lessons I learned and the pitfalls to avoid. 

<div style="display: flex; gap: 10px;">  <img src="https://res.cloudinary.com/dyneqi48f/image/upload/v1696125706/light-mode-signature_c50rry.png" alt="" width="48%" />  <img src="https://res.cloudinary.com/dyneqi48f/image/upload/v1696125706/dark-mode-signature_pidmq5.png" alt="" width="48%" />  </div>



## Things that will save you time:

- **Don't Use Media Queries**: They often don't work across all email clients.
- **Stick to a Mobile Version**: Without reliable media query support, stick to a mobile version.
- **Don't Use SVGs**: Gmail has limited support for SVG images.
- **Images Need Transparent Backgrounds**: Ensure your images have transparent backgrounds to accommodate dark mode. A white backgrounded image will be email suicide at night time. 
- **Use Referenced Images**: Support for referenced images is generally good. ie: /<*img src="link" />* 
- **KISS (Keep it Simple, Stupid)**: Complexity will lead to headaches.
- **Tables**: Tables are the standard for compatibility.

<br>

## How to Inject Your Signature into Apple, Gmail & Outlook

### Apple Mail:
You can't simply drag and drop into the signature box in preferences. Follow these [instructions](https://www.hubspot.com/email-signature-generator/add-html-signature-mail-mac).

### Gmail: 
Install the Chrome extension *"[Insert HTML by Designmodo](https://chrome.google.com/webstore/detail/insert-html-by-designmodo/bcflbfdlpegakpncdgmejelcolhmfkjh)"* to copy and paste your HTML code into Gmail's signature box.

### Outlook: 
Install the Microsoft extension *"[Insert HTML by Designmodo](https://appsource.microsoft.com/en-us/product/office/wa200002918?tab=overview)"* to copy and paste your HTML code into Outlook signature box.


Note: With both Outlook and Gmail, the extension adds a little mailbox icon to the signature boxes toolbar. Click on that and a window will open to allow the copy/paste of html code. 
<br> <br> 
## Ready to make your own? Read these 2 first 
This article is amazing - [The 17 DOs and DON’Ts of email signatures](https://exclaimer.com/email-signature-handbook/the-17-email-signature-dos-and-donts/) 
<br> 
And these wonderful people have amalgamated every CSS types compatibility with email browsers.  [The Ultimate Guide to CSS](https://exclaimer.com/email-signature-handbook/using-the-right-email-signature-size/) 
