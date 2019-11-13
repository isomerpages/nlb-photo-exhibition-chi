---
layout: homepage
title: Isomer Pages Demo
permalink: /
---
<!-- Type your notification here - the notification bar will not appear if this is empty. For other changes, refer to _data/homepage.yml to edit the homepage -->
###### This website is in beta - your valuable [feedback](https://form.sg/#!/forms/govtech/5a9ce876b3a3b6006e6b8335){:target="_blank"} will help us in improving it.

<script>
  function addReadMore() {
    var sgPara = document.querySelector('.bp-section:nth-child(5) p');  
    var readMoreButton = document.createElement('div');
    readMoreButton.innerHTML = 'Read More..';
    readMoreButton.setAttribute('class','read-more-button');
    readMoreButton.setAttribute('id','read-more-sg');
    readMoreButton.setAttribute('onclick','expandSG()');
    sgPara.parentNode.insertBefore( readMoreButton, sgPara.nextSibling );;
  }
  window.onload = function() {addReadMore();};
</script>
