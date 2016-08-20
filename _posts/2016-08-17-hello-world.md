---
layout: default
title: 你好，我的世界
featured: img/logo.png
permalink: 
---
<h2>{{ page.title }}</h2>
<p>我的第五篇文章</p>
<p>{{ page.date | date_to_string }}</p>



```php

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



