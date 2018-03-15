# Component-Accordion

This is an accordion!

Simply place all your content in the dd tags and your titles in the dt tags of the HTML.
You can view it [here](https://mediativecreative.github.io/Component-Accordion/)

CSS:
```
<style>.mdaccordion dl,.mdaccordion-list{border:1px solid #ddd}.mdaccordion dl:after,.mdaccordion-list:after{content:"";display:block;height:1em;width:100%;background-color:#5f7279}.mdaccordion dd,.mdaccordion__panel{background-color:#fff;font-size:1em;line-height:1.5em}.mdaccordion p{padding:1em 2em 1em 2em}.mdaccordion{position:relative;background-color:#fff}.mdaccordion_container{max-width:100%;margin:0 auto;padding:2em 0 2em 0}.mdaccordionTitle,.mdaccordion__Heading{background-color:#f6f6f6;text-align:center;font-weight:700;padding:2em;display:block;text-decoration:none;color:#333;-webkit-transition:background-color 0.5s,color 0.5s ease-in-out;transition:background-color 0.5s,color 0.5s ease-in-out;border-bottom:1px solid #5f7279}.mdaccordionTitle:before,.mdaccordion__Heading:before{content:"+";font-size:1.5em;line-height:1em;float:left;-webkit-transition:-webkit-transform 0.3s ease-in-out;transition:-webkit-transform 0.3s ease-in-out;transition:transform 0.3s ease-in-out;transition:transform 0.3s ease-in-out,-webkit-transform 0.3s ease-in-out}.mdaccordionTitle:focus,.mdaccordion__Heading:focus{text-decoration:none!important;font-weight:bold!important;outline:0;color:initial}.mdaccordionTitle:hover,.mdaccordion__Heading:hover{background-color:#1267a4;color:#fff;text-decoration:none!important;font-weight:bold!important}.mdaccordionTitleActive,.mdaccordionTitle.md-is-expanded{background-color:#1267a4;color:#fff}.mdaccordionTitleActive:before,.mdaccordionTitle.md-is-expanded:before{-webkit-transform:rotate(-225deg);transform:rotate(-225deg)}.mdaccordionItem{height:auto;overflow:hidden;-webkit-transition:height 1s;transition:max-height 1s}@media screen and (min-width:48em){.mdaccordionItem{-webkit-transition:max-height 0.5s;transition:max-height 0.5s}}.mdaccordionItem.md-is-collapsed{max-height:0!important}.no-js .mdaccordionItem.md-is-collapsed{max-height:auto}.md-animateIn{-webkit-animation:accordionIn 0.45s normal ease-in-out both 1;animation:accordionIn 0.45s normal ease-in-out both 1}.md-animateOut{-webkit-animation:accordionOut 0.45s alternate ease-in-out both 1;animation:accordionOut 0.45s alternate ease-in-out both 1}@-webkit-keyframes accordionIn{0%{opacity:0;-webkit-transform:scale(.9) rotateX(-60deg);transform:scale(.9) rotateX(-60deg)}100%{opacity:1;-webkit-transform:scale(1);transform:scale(1)}}@keyframes accordionIn{0%{opacity:0;-webkit-transform:scale(.9) rotateX(-60deg);transform:scale(.9) rotateX(-60deg)}100%{opacity:1;-webkit-transform:scale(1);transform:scale(1)}}@-webkit-keyframes accordionOut{0%{opacity:1;-webkit-transform:scale(1);transform:scale(1)}100%{opacity:0;-webkit-transform:scale(.9) rotateX(-60deg);transform:scale(.9) rotateX(-60deg)}}@keyframes accordionOut{0%{opacity:1;-webkit-transform:scale(1);transform:scale(1)}100%{opacity:0;-webkit-transform:scale(.9) rotateX(-60deg);transform:scale(.9) rotateX(-60deg)}}</style>
```

HTML:
```

<div class="mdaccordion_container">
  <div class="mdaccordion">
    <dl>
      <dt>
        <a href="" aria-expanded="false" aria-controls="accordion1" class="mdaccordion-title mdaccordionTitle js-mdaccordionTrigger">Accordion heading</a>
      </dt>
      <dd class="mdaccordion-content mdaccordionItem md-is-collapsed" id="mdaccordion1" aria-hidden="true"><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi eu interdum diam. Donec interdum porttitor risus non bibendum. Maecenas sollicitudin eros in quam imperdiet placerat. Cras justo purus, rhoncus nec lobortis ut, iaculis vel ipsum. Donec dignissim arcu nec elit faucibus condimentum. Donec facilisis consectetur enim sit amet varius. Pellentesque justo dui, sodales quis luctus a, iaculis eget mauris. </p>
        <p>Aliquam dapibus, ante quis fringilla feugiat, mauris risus condimentum massa, at elementum libero quam ac ligula. Pellentesque at rhoncus dolor. Duis porttitor nibh ut lobortis aliquam. Nullam eu dolor venenatis mauris placerat tristique eget id dolor. Quisque blandit adipiscing erat vitae dapibus. Nulla aliquam magna nec elementum tincidunt.</p>
      </dd>

      <dt>
        <a href="" aria-expanded="false" aria-controls="accordion1" class="mdaccordion-title mdaccordionTitle js-mdaccordionTrigger">Accordion heading</a>
      </dt>
      <dd class="mdaccordion-content mdaccordionItem md-is-collapsed" id="mdaccordion1" aria-hidden="true"><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi eu interdum diam. Donec interdum porttitor risus non bibendum. Maecenas sollicitudin eros in quam imperdiet placerat. Cras justo purus, rhoncus nec lobortis ut, iaculis vel ipsum. Donec dignissim arcu nec elit faucibus condimentum. Donec facilisis consectetur enim sit amet varius. Pellentesque justo dui, sodales quis luctus a, iaculis eget mauris. </p>
        <p>Aliquam dapibus, ante quis fringilla feugiat, mauris risus condimentum massa, at elementum libero quam ac ligula. Pellentesque at rhoncus dolor. Duis porttitor nibh ut lobortis aliquam. Nullam eu dolor venenatis mauris placerat tristique eget id dolor. Quisque blandit adipiscing erat vitae dapibus. Nulla aliquam magna nec elementum tincidunt.</p>
      </dd>

      <dt>
        <a href="" aria-expanded="false" aria-controls="accordion1" class="mdaccordion-title mdaccordionTitle js-mdaccordionTrigger">Accordion heading</a>
      </dt>
      <dd class="mdaccordion-content mdaccordionItem md-is-collapsed" id="mdaccordion1" aria-hidden="true"><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi eu interdum diam. Donec interdum porttitor risus non bibendum. Maecenas sollicitudin eros in quam imperdiet placerat. Cras justo purus, rhoncus nec lobortis ut, iaculis vel ipsum. Donec dignissim arcu nec elit faucibus condimentum. Donec facilisis consectetur enim sit amet varius. Pellentesque justo dui, sodales quis luctus a, iaculis eget mauris. </p>
        <p>Aliquam dapibus, ante quis fringilla feugiat, mauris risus condimentum massa, at elementum libero quam ac ligula. Pellentesque at rhoncus dolor. Duis porttitor nibh ut lobortis aliquam. Nullam eu dolor venenatis mauris placerat tristique eget id dolor. Quisque blandit adipiscing erat vitae dapibus. Nulla aliquam magna nec elementum tincidunt.</p>
      </dd>

      <dt>
        <a href="" aria-expanded="false" aria-controls="accordion1" class="mdaccordion-title mdaccordionTitle js-mdaccordionTrigger">Accordion heading</a>
      </dt>
      <dd class="mdaccordion-content mdaccordionItem md-is-collapsed" id="mdaccordion1" aria-hidden="true"><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi eu interdum diam. Donec interdum porttitor risus non bibendum. Maecenas sollicitudin eros in quam imperdiet placerat. Cras justo purus, rhoncus nec lobortis ut, iaculis vel ipsum. Donec dignissim arcu nec elit faucibus condimentum. Donec facilisis consectetur enim sit amet varius. Pellentesque justo dui, sodales quis luctus a, iaculis eget mauris. </p>
        <p>Aliquam dapibus, ante quis fringilla feugiat, mauris risus condimentum massa, at elementum libero quam ac ligula. Pellentesque at rhoncus dolor. Duis porttitor nibh ut lobortis aliquam. Nullam eu dolor venenatis mauris placerat tristique eget id dolor. Quisque blandit adipiscing erat vitae dapibus. Nulla aliquam magna nec elementum tincidunt.</p>
      </dd>
    </dl>
  </div>
</div>
```

JS (must go after html):
```
<script>(function(){var d=document,accordionToggles=d.querySelectorAll('.js-mdaccordionTrigger'),setAria,setAccordionAria,switchAccordion,touchSupported=('ontouchstart' in window),pointerSupported=('pointerdown' in window);skipClickDelay=function(e){e.preventDefault();e.target.click()}
setAriaAttr=function(el,ariaType,newProperty){el.setAttribute(ariaType,newProperty)};setAccordionAria=function(el1,el2,expanded){switch(expanded){case "true":setAriaAttr(el1,'aria-expanded','true');setAriaAttr(el2,'aria-hidden','false');break;case "false":setAriaAttr(el1,'aria-expanded','false');setAriaAttr(el2,'aria-hidden','true');break;default:break}};window.onload=function(){var mdElements=document.getElementsByClassName("mdaccordionItem");for(var i=0,max=mdElements.length;i<max;i++){mdElements[i].style.maxHeight=mdElements[i].scrollHeight+"px"}};switchAccordion=function(e){console.log("triggered");e.preventDefault();var thisAnswer=e.target.parentNode.nextElementSibling;var thisQuestion=e.target;if(thisAnswer.classList.contains('md-is-collapsed')){setAccordionAria(thisQuestion,thisAnswer,'true')}else{setAccordionAria(thisQuestion,thisAnswer,'false')}
thisQuestion.classList.toggle('md-is-collapsed');thisQuestion.classList.toggle('md-is-expanded');thisAnswer.classList.toggle('md-is-collapsed');thisAnswer.classList.toggle('md-is-expanded');thisAnswer.style.maxHeight="0"?thisAnswer.style.maxHeight=(thisAnswer.scrollHeight+"px"):thisAnswer.style.maxHeight="0";thisAnswer.classList.toggle('md-animateIn')};for(var i=0,len=accordionToggles.length;i<len;i++){if(touchSupported){accordionToggles[i].addEventListener('touchstart',skipClickDelay,!1)}
if(pointerSupported){accordionToggles[i].addEventListener('pointerdown',skipClickDelay,!1)}
accordionToggles[i].addEventListener('click',switchAccordion,!1)}})()</script>
```
