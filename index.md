---
layout: homepage
title: Isomer Pages Demo
permalink: /
---
<!-- Type your notification here - the notification bar will not appear if this is empty. For other changes, refer to _data/homepage.yml to edit the homepage -->
###### This website is in beta - your valuable [feedback](https://form.sg/#!/forms/govtech/5a9ce876b3a3b6006e6b8335){:target="_blank"} will help us in improving it.

<script>
  function addReadMore() {
    var sgPara = document.querySelector('.bp-section:nth-of-type(3) .row.is-hidden-mobile.is-hidden-tablet-only p:nth-of-type(2)');
    var extraSGOnDesktop = document.createElement('div');
    extraSGOnDesktop.setAttribute('class','para-extension');
    extraSGOnDesktop.innerHTML=`<p>The Singapore component of the exhibition showcases 173 photographs from the 1880s to the 1960s, mainly drawn from the collections of the National Library and the National Archives of Singapore, both institutions under the National Library Board of Singapore. The exhibition comprises six sections – Places of Power and Worship, A Tropical Metropolis, All Walks of Life, Colourful Customs, Centres of Commerce, and A City in Motion. It transports the viewer to early Singapore, featuring its varied architecture, lively streetscapes, cosmopolitan society, and multi-cultural customs.</p>`;
    var readMoreButton = document.createElement('div');
    readMoreButton.innerHTML = 'Read More..';
    readMoreButton.setAttribute('class','read-more-button');
    readMoreButton.setAttribute('id','read-more-sg');
    sgPara.parentNode.insertBefore( extraSGOnDesktop, sgPara.nextSibling );
    extraSGOnDesktop.parentNode.insertBefore( readMoreButton, extraSGOnDesktop.nextSibling );
  }
  
  function expandSG(){
    var expandButton = document.getElementsByClassName('read-more-button');
    var hiddenPara = document.getElementsByClassName('para-extension');
    var i;
    var j;
    for (i = j = 0 ; i<hiddenPara.length && j<expandButton.length ; i++ , j++) {
      var toHiddenPara = document.getElementsByClassName('para-extension')[i];
      expandButton[j].addEventListener('click', function(){toHiddenPara.classList.toggle('show-this-para')});
    }
  }
  
  
  window.onload = function() {addReadMore();expandSG();};
</script>
