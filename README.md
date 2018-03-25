# Setup guide for DomainKeeper

[На русском](https://github.com/SilencerWeb/domainkeeper-guide/blob/master/Russian.md)

First you need to choose the versions: *build*(folder `build`) or *inline*(folder `inline`)? 
To understand exactly what you need, you need to answer on one question: Are you going to change the styles (CSS) and / or scripts (JS)?
If yes, so choose *build*, otherwise choose *inline*. In case, *inline* is more optimized than build, so we recommend to use *inine* version.

> In order to make any changes, you need to open the file you need via text editor (for example, [Sublime text 3](https://www.sublimetext.com/3) or [Nodepad++](https://notepad-plus-plus.org/)).
To find the line you need, use CTRL + F on Windows and CMD + F on MacOS. You also need to save the file after all the changes you made.


## Setup contact form

1. Create new [Google account](https://accounts.google.com/SignUp).
2. Open `mail.php`, from `server` folder via any text editor.
3. Find the line with `Google account email`.
4. Replace `Google account email` by new Google account from first step.
5. Find the line with `Google account password`.
6. Replace `Google account password` by password from new Google account from first step.
7. Find the line with `Email from`.
8. Replace `Email from` by an any email, it doesn't matter.
9. Find the line with `Email to`.
10. Replace `Email to` by your email address to which you want to receive messages from this form.
11. Find the line with `From who name`.
12. Replace `From who name` by the sender name you need.
13. Find the line with `Subject text`.
14. Replace `Subject text` by message subject you need.

## HTML pages
> In order to make any changes you need to open the HTML-page via text editor.

### How to change the email address?
1. Find all the lines with `example@gmail.com`.
2. Replace `example @ gmail.com` by the email address you need.
   
### How to change my phone number?
1. Find all the lines with `7861234567`.
2. Replace `7861234567` by your phone number.
   
### How to change any text?
1. Find the text.
2. Replace it.
  
### How do I change the link address?
1. Find the link you need.
2. Replace the value of the `href` attribute with the link you need. 

## Contacts
Do you still have questions? Feel free to create a new ticket here – https://wiwka.freshdesk.com or send us an email – feedback@wiwka.com
