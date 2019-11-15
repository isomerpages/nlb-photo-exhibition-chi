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
  /**/
    var sgParaTab = document.querySelector('.bp-section:nth-of-type(3) .row.is-hidden-mobile.is-hidden-desktop p:nth-of-type(2)');
    var extraSGOnTab = document.createElement('div');
    extraSGOnTab.setAttribute('class','para-extension');
    extraSGOnTab.innerHTML=`<p>The Singapore component of the exhibition showcases 173 photographs from the 1880s to the 1960s, mainly drawn from the collections of the National Library and the National Archives of Singapore, both institutions under the National Library Board of Singapore. The exhibition comprises six sections – Places of Power and Worship, A Tropical Metropolis, All Walks of Life, Colourful Customs, Centres of Commerce, and A City in Motion. It transports the viewer to early Singapore, featuring its varied architecture, lively streetscapes, cosmopolitan society, and multi-cultural customs.</p>`;
    var readMoreButtonTab = document.createElement('div');
    readMoreButtonTab.innerHTML = 'Read More..';
    readMoreButtonTab.setAttribute('class','read-more-button');
    readMoreButtonTab.setAttribute('id','read-more-sg-tab');
    sgParaTab.parentNode.insertBefore( extraSGOnTab, sgParaTab.nextSibling );
    extraSGOnTab.parentNode.insertBefore( readMoreButtonTab, extraSGOnTab.nextSibling );
  /**/
    var sgParaMob = document.querySelector('.bp-section:nth-of-type(3) .row.is-hidden-desktop.is-hidden-tablet-only p:nth-of-type(2)');
    var extraSGOnMob = document.createElement('div');
    extraSGOnMob.setAttribute('class','para-extension');
    extraSGOnMob.innerHTML=`<p>The Singapore component of the exhibition showcases 173 photographs from the 1880s to the 1960s, mainly drawn from the collections of the National Library and the National Archives of Singapore, both institutions under the National Library Board of Singapore. The exhibition comprises six sections – Places of Power and Worship, A Tropical Metropolis, All Walks of Life, Colourful Customs, Centres of Commerce, and A City in Motion. It transports the viewer to early Singapore, featuring its varied architecture, lively streetscapes, cosmopolitan society, and multi-cultural customs.</p>`;
    var readMoreButtonMob = document.createElement('div');
    readMoreButtonMob.innerHTML = 'Read More..';
    readMoreButtonMob.setAttribute('class','read-more-button');
    readMoreButtonMob.setAttribute('id','read-more-sg-mob');
    sgParaMob.parentNode.insertBefore( extraSGOnMob, sgParaMob.nextSibling );
    extraSGOnMob.parentNode.insertBefore( readMoreButtonMob, extraSGOnMob.nextSibling );
  /**/
  /*beijing*/
    var BeiPara = document.querySelector('.bp-section:nth-of-type(4) .row.is-hidden-mobile.is-hidden-tablet-only p:nth-of-type(2)');
    var extraBei = document.createElement('div');
    extraBei.setAttribute('class','para-extension');
    extraBei.innerHTML=`<p>The Beijing component of this exhibition is curated by the Beijing Local Document Center of the Library, featuring 194 photographs of pre-1949 Beijing. The images are presented in seven sections – Ancient City Walls, Street Scenes, Imperial Palaces and Gardens, Customs and Festivals, Trade and Commerce, Everyday Life, and Transportation. They depict the majestic palaces and city walls, scenic gardens, myriad streets and alleys, and unique customs of old Beijing.</p>`;
    var readMoreButtonBei = document.createElement('div');
    readMoreButtonBei.innerHTML = 'Read More..';
    readMoreButtonBei.setAttribute('class','read-more-button');
    readMoreButtonBei.setAttribute('id','read-more-sg-mob');
    BeiPara.parentNode.insertBefore( extraBei, BeiPara.nextSibling );
    extraBei.parentNode.insertBefore( readMoreButtonBei, extraBei.nextSibling );
  /**/
    var BeiParaTab = document.querySelector('.bp-section:nth-of-type(4) .row.is-hidden-mobile.is-hidden-desktop p:nth-of-type(2)');
    var extraBeiTab = document.createElement('div');
    extraBeiTab.setAttribute('class','para-extension');
    extraBeiTab.innerHTML=`<p>The Beijing component of this exhibition is curated by the Beijing Local Document Center of the Library, featuring 194 photographs of pre-1949 Beijing. The images are presented in seven sections – Ancient City Walls, Street Scenes, Imperial Palaces and Gardens, Customs and Festivals, Trade and Commerce, Everyday Life, and Transportation. They depict the majestic palaces and city walls, scenic gardens, myriad streets and alleys, and unique customs of old Beijing.</p>`;
    var readMoreButtonBeiTab = document.createElement('div');
    readMoreButtonBeiTab.innerHTML = 'Read More..';
    readMoreButtonBeiTab.setAttribute('class','read-more-button');
    readMoreButtonBeiTab.setAttribute('id','read-more-sg-mob');
    BeiParaTab.parentNode.insertBefore( extraBeiTab, BeiParaTab.nextSibling );
    extraBeiTab.parentNode.insertBefore( readMoreButtonBeiTab, extraBeiTab.nextSibling );
    /**/
    var BeiParaMob = document.querySelector('.bp-section:nth-of-type(4) .row.is-hidden-desktop.is-hidden-tablet-only p:nth-of-type(2)');
    var extraBeiMob = document.createElement('div');
    extraBeiMob.setAttribute('class','para-extension');
    extraBeiMob.innerHTML=`<p>The Beijing component of this exhibition is curated by the Beijing Local Document Center of the Library, featuring 194 photographs of pre-1949 Beijing. The images are presented in seven sections – Ancient City Walls, Street Scenes, Imperial Palaces and Gardens, Customs and Festivals, Trade and Commerce, Everyday Life, and Transportation. They depict the majestic palaces and city walls, scenic gardens, myriad streets and alleys, and unique customs of old Beijing.</p>`;
    var readMoreButtonBeiMob = document.createElement('div');
    readMoreButtonBeiMob.innerHTML = 'Read More..';
    readMoreButtonBeiMob.setAttribute('class','read-more-button');
    readMoreButtonBeiMob.setAttribute('id','read-more-sg-mob');
    BeiParaMob.parentNode.insertBefore( extraBeiMob, BeiParaMob.nextSibling );
    extraBeiMob.parentNode.insertBefore( readMoreButtonBeiMob, extraBeiMob.nextSibling );
  
  }
  
  function expandSG(){
    var expandButton = document.getElementsByClassName('read-more-button');
    var hiddenPara = document.getElementsByClassName('para-extension');
    /*expandButton[0].addEventListener('click', function(){hiddenPara[0].classList.toggle('show-this-para');
                                                           expandButton[0].classList.toggle('show-less');
                                                           });
    expandButton[1].addEventListener('click', function(){hiddenPara[1].classList.toggle('show-this-para');
                                                           expandButton[1].classList.toggle('show-less');
                                                           });
    expandButton[2].addEventListener('click', function(){hiddenPara[2].classList.toggle('show-this-para');
                                                           expandButton[2].classList.toggle('show-less');
                                                           });*/
    var i;
    for (i = 0 ; i<hiddenPara.length ; i++ ) {
      (function(){
      var toHiddenPara = document.getElementsByClassName('para-extension')[i];
      var toExpandButton = document.getElementsByClassName('read-more-button')[i];
      toExpandButton.addEventListener('click', function(){toHiddenPara.classList.toggle('show-this-para');
                                                           toExpandButton.classList.toggle('show-less');
                                                           });
    }());}
  }
  
  
  window.onload = function() {addReadMore();expandSG();};
</script>
