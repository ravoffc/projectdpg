<template>
  <main>
    <h2 class="fancy">Materi Design</h2>
    <p>"next update :)" 
    </p>   
    <h2 class="fancy" style="--w: 80px;--c: #C44D58;--b:4px;--g: -5px">Materi Pemrogramman</h2>
    <p>"next update :)" 
    </p>
    <h2 class="fancy" style="--w: 80px;--c: #8A9B0F;--b:4px;--g:-5px">Materi Multimedia</h2>
    <p>"next update :)" 
    </p>
  </main>
</template>

<style scoped>
.fancy {
  --b: 6px;   /* control the border thickness */
  --w: 80px;  /* control the width of the line*/
  --g: -5px;  /* control the gap */
  --c: #0B486B;
 
  width: fit-content;
  padding: 0 1em;
  line-height: 1.6em;
  border: 1px solid;
  color: #fff;
  background: 
    conic-gradient(from   45deg at left ,var(--c) 25%,#0000 0) 0,
    conic-gradient(from -135deg at right,var(--c) 25%,#0000 0) 100%;
  background-size: 51% 100%;
  background-origin: border-box;
  background-repeat: no-repeat;
  border-image: 
     linear-gradient(
       #0000      calc(50% - var(--b)/2),
       var(--c) 0 calc(50% + var(--b)/2),
       #0000    0) 
    1/0 var(--w)/calc(var(--w) + var(--g));
  margin-inline: auto;
}



p {
  font-size: 1.3rem;
  text-align: justify;
  margin-inline: max(20px, 50% - 800px/2);
}
h1 {
  font-size: 2.3rem;
}
h2 {
  font-size: 1.8rem;
}

body {
  font-family: system-ui, sans-serif;
}
</style>
