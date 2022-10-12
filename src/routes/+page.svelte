<!-- ~/src/routes/index.svelte -->

<script>
    import * as prismicH from '@prismicio/helpers';
    export let data;
  </script>
  
  <main>
    <div class="container">
      <h1>Homepage</h1>
      <pre>{JSON.stringify(data.document, null, 2)}</pre>
    </div>
  </main>

  
  
  <style>
    main {
      font-family: sans-serif;
    }
  
    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 0px 20px;
    }
  
    .container > * {
      width: 100%;
      max-width: 700px;
    }
  </style>
  