# Component-Accordion

This is an accordion!
You can view it [here](https://mediativecreative.github.io/Component-Accordion/)

CSS:
```
@import url(https://fonts.googleapis.com/css?family=Lato:400,700);*{-webkit-box-sizing:border-box;box-sizing:border-box}body{font-family:'Lato'}.accordion dl,.accordion-list{border:1px solid #ddd}.accordion dl:after,.accordion-list:after{content:"";display:block;height:1em;width:100%;background-color:#5f7279}.accordion dd,.accordion__panel{background-color:#fff;font-size:1em;line-height:1.5em}.accordion p{padding:1em 2em 1em 2em}.accordion{position:relative;background-color:#fff}.container{max-width:960px;margin:0 auto;padding:2em 0 2em 0}.accordionTitle,.accordion__Heading{background-color:#f6f6f6;text-align:center;font-weight:700;padding:2em;display:block;text-decoration:none;color:#333;-webkit-transition:background-color 0.5s,color 0.5s ease-in-out;transition:background-color 0.5s,color 0.5s ease-in-out;border-bottom:1px solid #5f7279}.accordionTitle:before,.accordion__Heading:before{content:"+";font-size:1.5em;line-height:.5em;float:left;-webkit-transition:-webkit-transform 0.3s ease-in-out;transition:-webkit-transform 0.3s ease-in-out;transition:transform 0.3s ease-in-out;transition:transform 0.3s ease-in-out,-webkit-transform 0.3s ease-in-out}.accordionTitle:hover,.accordion__Heading:hover{background-color:#1267a4;color:#fff}.accordionTitleActive,.accordionTitle.is-expanded{background-color:#1267a4;color:#fff}.accordionTitleActive:before,.accordionTitle.is-expanded:before{-webkit-transform:rotate(-225deg);transform:rotate(-225deg)}.accordionItem{height:auto;overflow:hidden;-webkit-transition:height 1s;transition:max-height 1s}@media screen and (min-width:48em){.accordionItem{-webkit-transition:max-height 0.5s;transition:max-height 0.5s}}.accordionItem.is-collapsed{max-height:0!important}.no-js .accordionItem.is-collapsed{max-height:auto}.animateIn{-webkit-animation:accordionIn 0.45s normal ease-in-out both 1;animation:accordionIn 0.45s normal ease-in-out both 1}.animateOut{-webkit-animation:accordionOut 0.45s alternate ease-in-out both 1;animation:accordionOut 0.45s alternate ease-in-out both 1}@-webkit-keyframes accordionIn{0%{opacity:0;-webkit-transform:scale(.9) rotateX(-60deg);transform:scale(.9) rotateX(-60deg);-webkit-transform-origin:50% 0;transform-origin:50% 0}100%{opacity:1;-webkit-transform:scale(1);transform:scale(1)}}@keyframes accordionIn{0%{opacity:0;-webkit-transform:scale(.9) rotateX(-60deg);transform:scale(.9) rotateX(-60deg);-webkit-transform-origin:50% 0;transform-origin:50% 0}100%{opacity:1;-webkit-transform:scale(1);transform:scale(1)}}@-webkit-keyframes accordionOut{0%{opacity:1;-webkit-transform:scale(1);transform:scale(1)}100%{opacity:0;-webkit-transform:scale(.9) rotateX(-60deg);transform:scale(.9) rotateX(-60deg)}}@keyframes accordionOut{0%{opacity:1;-webkit-transform:scale(1);transform:scale(1)}100%{opacity:0;-webkit-transform:scale(.9) rotateX(-60deg);transform:scale(.9) rotateX(-60deg)}}
```

HTML:
```
<div class="container">
  <div class="accordion">
    <dl>
      <dt>
        <a href="#accordion1" aria-expanded="false" aria-controls="accordion1" class="accordion-title accordionTitle js-accordionTrigger">First Accordion heading</a>
      </dt>
      <dd class="accordion-content accordionItem is-collapsed" id="accordion1" aria-hidden="true"><p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi eu interdum diam. Donec interdum porttitor risus non bibendum. Maecenas sollicitudin eros in quam imperdiet placerat. Cras justo purus, rhoncus nec lobortis ut, iaculis vel ipsum. Donec dignissim arcu nec elit faucibus condimentum. Donec facilisis consectetur enim sit amet varius. Pellentesque justo dui, sodales quis luctus a, iaculis eget mauris. </p>
        <p>Aliquam dapibus, ante quis fringilla feugiat, mauris risus condimentum massa, at elementum libero quam ac ligula. Pellentesque at rhoncus dolor. Duis porttitor nibh ut lobortis aliquam. Nullam eu dolor venenatis mauris placerat tristique eget id dolor. Quisque blandit adipiscing erat vitae dapibus. Nulla aliquam magna nec elementum tincidunt.</p>
      </dd>
      <dt>
        <a href="#accordion2" aria-expanded="false" aria-controls="accordion2" class="accordion-title accordionTitle js-accordionTrigger">
          Second Accordion heading</a>
      </dt>
      <dd class="accordion-content accordionItem is-collapsed" id="accordion2" aria-hidden="true">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi eu interdum diam. Donec interdum porttitor risus non bibendum. Maecenas sollicitudin eros in quam imperdiet placerat. Cras justo purus, rhoncus nec lobortis ut, iaculis vel ipsum. Donec dignissim arcu nec elit faucibus condimentum. Donec facilisis consectetur enim sit amet varius. Pellentesque justo dui, sodales quis luctus a, iaculis eget mauris. </p>
        <p>Aliquam dapibus, ante quis fringilla feugiat, mauris risus condimentum massa, at elementum libero quam ac ligula. Pellentesque at rhoncus dolor. Duis porttitor nibh ut lobortis aliquam. Nullam eu dolor venenatis mauris placerat tristique eget id dolor. Quisque blandit adipiscing erat vitae dapibus. Nulla aliquam magna nec elementum tincidunt.</p>
      </dd>
      <dt>
        <a href="#accordion3" aria-expanded="false" aria-controls="accordion3" class="accordion-title accordionTitle js-accordionTrigger">
          Third Accordion heading
        </a>
      </dt>
      <dd class="accordion-content accordionItem is-collapsed" id="accordion3" aria-hidden="true">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi eu interdum diam. Donec interdum porttitor risus non bibendum. Maecenas sollicitudin eros in quam imperdiet placerat. Cras justo purus, rhoncus nec lobortis ut, iaculis vel ipsum. Donec dignissim arcu nec elit faucibus condimentum. Donec facilisis consectetur enim sit amet varius. Pellentesque justo dui, sodales quis luctus a, iaculis eget mauris. </p>
        <p>Aliquam dapibus, ante quis fringilla feugiat, mauris risus condimentum massa, at elementum libero quam ac ligula. Pellentesque at rhoncus dolor. Duis porttitor nibh ut lobortis aliquam. Nullam eu dolor venenatis mauris placerat tristique eget id dolor. Quisque blandit adipiscing erat vitae dapibus. Nulla aliquam magna nec elementum tincidunt.</p>
      </dd>
      <dt>
        <a href="#accordion3" aria-expanded="false" aria-controls="accordion3" class="accordion-title accordionTitle js-accordionTrigger">
          Third Accordion heading
        </a>
      </dt>
      <dd class="accordion-content accordionItem is-collapsed" id="accordion3" aria-hidden="true">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi eu interdum diam. Donec interdum porttitor risus non bibendum. Maecenas sollicitudin eros in quam imperdiet placerat. Cras justo purus, rhoncus nec lobortis ut, iaculis vel ipsum. Donec dignissim arcu nec elit faucibus condimentum. Donec facilisis consectetur enim sit amet varius. Pellentesque justo dui, sodales quis luctus a, iaculis eget mauris. </p>
        <p>Aliquam dapibus, ante quis fringilla feugiat, mauris risus condimentum massa, at elementum libero quam ac ligula. Pellentesque at rhoncus dolor. Duis porttitor nibh ut lobortis aliquam. Nullam eu dolor venenatis mauris placerat tristique eget id dolor. Quisque blandit adipiscing erat vitae dapibus. Nulla aliquam magna nec elementum tincidunt.</p>
      </dd>
      <dt>
        <a href="#accordion3" aria-expanded="false" aria-controls="accordion3" class="accordion-title accordionTitle js-accordionTrigger">
          Third Accordion heading
        </a>
      </dt>
      <dd class="accordion-content accordionItem is-collapsed" id="accordion3" aria-hidden="true">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi eu interdum diam. Donec interdum porttitor risus non bibendum. Maecenas sollicitudin eros in quam imperdiet placerat. Cras justo purus, rhoncus nec lobortis ut, iaculis vel ipsum. Donec dignissim arcu nec elit faucibus condimentum. Donec facilisis consectetur enim sit amet varius. Pellentesque justo dui, sodales quis luctus a, iaculis eget mauris. </p>
        <p>Aliquam dapibus, ante quis fringilla feugiat, mauris risus condimentum massa, at elementum libero quam ac ligula. Pellentesque at rhoncus dolor. Duis porttitor nibh ut lobortis aliquam. Nullam eu dolor venenatis mauris placerat tristique eget id dolor. Quisque blandit adipiscing erat vitae dapibus. Nulla aliquam magna nec elementum tincidunt.</p>
      </dd>
      <dt>
        <a href="#accordion3" aria-expanded="false" aria-controls="accordion3" class="accordion-title accordionTitle js-accordionTrigger">
          Third Accordion heading
        </a>
      </dt>
      <dd class="accordion-content accordionItem is-collapsed" id="accordion3" aria-hidden="true">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi eu interdum diam. Donec interdum porttitor risus non bibendum. Maecenas sollicitudin eros in quam imperdiet placerat. Cras justo purus, rhoncus nec lobortis ut, iaculis vel ipsum. Donec dignissim arcu nec elit faucibus condimentum. Donec facilisis consectetur enim sit amet varius. Pellentesque justo dui, sodales quis luctus a, iaculis eget mauris. </p>
        <p>Aliquam dapibus, ante quis fringilla feugiat, mauris risus condimentum massa, at elementum libero quam ac ligula. Pellentesque at rhoncus dolor. Duis porttitor nibh ut lobortis aliquam. Nullam eu dolor venenatis mauris placerat tristique eget id dolor. Quisque blandit adipiscing erat vitae dapibus. Nulla aliquam magna nec elementum tincidunt.</p>
      </dd>
      <dt>
        <a href="#accordion3" aria-expanded="false" aria-controls="accordion3" class="accordion-title accordionTitle js-accordionTrigger">
          Third Accordion heading
        </a>
      </dt>
      <dd class="accordion-content accordionItem is-collapsed" id="accordion3" aria-hidden="true">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Morbi eu interdum diam. Donec interdum porttitor risus non bibendum. Maecenas sollicitudin eros in quam imperdiet placerat. Cras justo purus, rhoncus nec lobortis ut, iaculis vel ipsum. Donec dignissim arcu nec elit faucibus condimentum. Donec facilisis consectetur enim sit amet varius. Pellentesque justo dui, sodales quis luctus a, iaculis eget mauris. </p>
        <p>Aliquam dapibus, ante quis fringilla feugiat, mauris risus condimentum massa, at elementum libero quam ac ligula. Pellentesque at rhoncus dolor. Duis porttitor nibh ut lobortis aliquam. Nullam eu dolor venenatis mauris placerat tristique eget id dolor. Quisque blandit adipiscing erat vitae dapibus. Nulla aliquam magna nec elementum tincidunt.</p>
      </dd>
    </dl>
  </div>
</div>
```

JS (must go after html):
```
(function(){var d=document,accordionToggles=d.querySelectorAll('.js-accordionTrigger'),setAria,setAccordionAria,switchAccordion,touchSupported=('ontouchstart' in window),pointerSupported=('pointerdown' in window);skipClickDelay=function(e){e.preventDefault();e.target.click()}
setAriaAttr=function(el,ariaType,newProperty){el.setAttribute(ariaType,newProperty)};setAccordionAria=function(el1,el2,expanded){switch(expanded){case "true":setAriaAttr(el1,'aria-expanded','true');setAriaAttr(el2,'aria-hidden','false');break;case "false":setAriaAttr(el1,'aria-expanded','false');setAriaAttr(el2,'aria-hidden','true');break;default:break}};window.onload=function(){var mdElements=document.getElementsByClassName("accordionItem");for(var i=0,max=mdElements.length;i<max;i++){mdElements[i].style.maxHeight=mdElements[i].scrollHeight+"px"}};switchAccordion=function(e){console.log("triggered");e.preventDefault();var thisAnswer=e.target.parentNode.nextElementSibling;var thisQuestion=e.target;if(thisAnswer.classList.contains('is-collapsed')){setAccordionAria(thisQuestion,thisAnswer,'true')}else{setAccordionAria(thisQuestion,thisAnswer,'false')}
thisQuestion.classList.toggle('is-collapsed');thisQuestion.classList.toggle('is-expanded');thisAnswer.classList.toggle('is-collapsed');thisAnswer.classList.toggle('is-expanded');thisAnswer.style.maxHeight="0"?thisAnswer.style.maxHeight=(thisAnswer.scrollHeight+"px"):thisAnswer.style.maxHeight="0";thisAnswer.classList.toggle('animateIn')};for(var i=0,len=accordionToggles.length;i<len;i++){if(touchSupported){accordionToggles[i].addEventListener('touchstart',skipClickDelay,!1)}
if(pointerSupported){accordionToggles[i].addEventListener('pointerdown',skipClickDelay,!1)}
accordionToggles[i].addEventListener('click',switchAccordion,!1)}})()
```
