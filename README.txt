!! ABOUT !!

This is a modified version of [[ https://glenthemes.tumblr.com/post/708014819571302400/unblue-polls ]] that I made for my own ease of use. The original uses variables which cannot be directly modified via the "Edit theme" menu on Tumblr and instead have to be modified by editing the HTML; this version takes care of that problem. I also added the option to customise the fonts for the poll question and poll options
I made this for myself; I'm posting the .css and the meta tags here in case I miss them or such. I don't know the first thing about css/html, I did this by looking up a bunch of posts and doing educated guesses. I included a pastebin link with the original version of the code in case the original link becomes invalid (like OP changing usernames etc).
Ps: The comments that are not about giving credit (poll start/end) are for my own comfort.


Copypaste this before <head>:

<!--✻✻✻✻✻✻  UN-BLUE POLLS by @glenthemes  ✻✻✻✻✻✻-->
<!--**See original at https://pastebin.com/MgSGenCR **-->
<!-- modified by @wachi-delectrico -->
<meta name="text:Poll question size" content="font-size:16px">
<meta name="color:Poll option color" content="#fcfcfc">
<meta name="color:Poll border color" content="#efefef">
<meta name="text:Poll option size" content="13px">
<meta name="font:Poll option font" content="'Montserrat', sans-serif">
<meta name="font:Poll question font" content="'Montserrat', sans-serif">
<meta name="color:Poll text color" content="#666666">

<meta name="color:Poll background hover" content="#ebf0f4">
<meta name="color:Poll text hover" content="#1a1b1d">
<meta name="color:Poll border hover" content="#cfdae4">

<meta name="text:Poll hover speed" content="0.4s">
<meta name="text:Poll round borders" content="18px">
<meta name="text:Poll border size" content="2px">
<meta name="text:Poll border padding" content="15px">
<meta name="text:Poll option spacing" content="10px">

<link href='//fonts.googleapis.com/css?family=Montserrat' rel='stylesheet' type='text/css'>
<!-- Poll customization menu ends here -->

Copypaste ends here.

Then copypaste the contents of the .css before </head> like so:

<!-- POLLS START -->
<style type="text/css">
--(copypaste goes here)--
</style>
<!-- POLLS END -->
