---
layout: page
title: Home
id: home
permalink: /
---


<SCRIPT>
function passWord() {
var testV = 1;
var pass1 = prompt('Denne siden krever et passord',' ');
while (testV < 3) {
if (!pass1)
history.go(-1);
if (pass1.toLowerCase() == "grodaas22") {
window.open('index');
break;
}
testV+=1;
var pass1 =
prompt('Feil passord','Password');
}
if (pass1.toLowerCase()!="password" & testV ==3)
history.go(-1);
return " ";
}
</SCRIPT>

<CENTER>
<FORM>
<input type="button" value="Enter Protected Area" onClick="passWord()">
</FORM>
</CENTER>

# Welcome! 🌱

<p style="padding: 3em 1em; background: #f5f7ff; border-radius: 4px;">
  Take a look at <span style="font-weight: bold">[[Your first note]]</span> to get started on your exploration.
</p>

This digital garden template is free, open-source, and [available on GitHub here](https://github.com/maximevaillancourt/digital-garden-jekyll-template).

The easiest way to get started is to read this [step-by-step guide explaining how to set this up from scratch](https://maximevaillancourt.com/blog/setting-up-your-own-digital-garden-with-jekyll). If you need any help, my [DMs are open on Twitter (@vaillancourtmax)](https://twitter.com/vaillancourtmax). 👋

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
