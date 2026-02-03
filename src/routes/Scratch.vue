<script setup>
import Accordion from 'primevue/accordion';
import AccordionPanel from 'primevue/accordionpanel';
import AccordionHeader from 'primevue/accordionheader';
import AccordionContent from 'primevue/accordioncontent';


</script>

<template>
  <h1 class="c" style="margin-bottom: 4.5rem; font-weight: 400;">Scratch</h1>

  <details class="section" open>
    <summary class="section__title">Движение</summary>

    <div class="section__body section__body--scratch-movement">
      <div>
        <h2 class="section__body__title">идти [10] шагов</h2>
        <figure class="section__body__figure">
          <img src="../assets/img/idti-10-shagov.png">
          <figcaption>(Самый 1-ый блок)</figcaption>
        </figure>
      </div>

      <div>
        <h2 class="section__body__title">изменить x на [10]</h2>
        <figure class="section__body__figure">
          <img src="../assets/img/izmenit-x-na-10.png">
          <figcaption>(10-ый блок)</figcaption>
        </figure>
      </div>

      <div>
        <h2 class="section__body__title">плыть</h2>
        <figure class="section__body__figure">
          <img src="../assets/img/plyt.png">
          <figcaption>(6-ой и 7-ой блоки)</figcaption>
        </figure>
        <p>
          <span class="section__body__warning">Осторожно:</span>
          при использовании этого блока могут возникнуть баги.
          Чтобы их избежать, используй ещё один скрипт (цикл), например, 
          <b>Когда зел. флаг нажат</b> или <b>Когда я получу "сообщение"</b>:
        </p>
        <p style="text-align: center;">
          <a class="pixel-voyager-link" href="/plyt-ostorozhno.png">
            <img src="../assets/img/plyt-ostorozhno.png" style="width: 15rem;">
          </a>
        </p>
      </div>
    </div>
  </details>
</template>