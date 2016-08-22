---
layout: page
title: 你好，我的世界
featured: img/logo.png
permalink:
---




``` php

class snlonGuestbook{
   var $messageDir = 'messages';
   var $dateFormat = 'Y-m-d g:i:s A';
   var $itemsPerPage = 5;
   var $messageList;

function processGuestbook(){
   if (isset($_POST['submit']))
   {
      $this->insertMessage();
   }
}

````
