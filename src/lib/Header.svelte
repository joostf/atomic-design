<script>

</script>

<header>
  <svg class="fdnd-logo" viewBox="0 0 94 53" xmlns="http://www.w3.org/2000/svg">
    <rect class="logo-background" x=".5" y="3.5" width="89" height="48" rx="7.5" />
    <path d="M82 3H8a8 8 0 0 0-8 8v33a8 8 0 0 0 8 8h74a8 8 0 0 0 8-8V11a8 8 0 0 0-8-8Zm0 1a7 7 0 0 1 7 7v33a7 7 0 0 1-7 7H8a7 7 0 0 1-7-7V11a7 7 0 0 1 7-7h74Z"/>
    <rect class="logo-background" x="3.5" y=".5" width="89" height="48" rx="7.5" />
    <path d="M85 0H11a8 8 0 0 0-8 8v33a8 8 0 0 0 8 8h74a8 8 0 0 0 8-8V8a8 8 0 0 0-8-8Zm0 1a7 7 0 0 1 7 7v33a7 7 0 0 1-7 7H11a7 7 0 0 1-7-7V8a7 7 0 0 1 7-7h74Z"/>
    <polygon points="22.3945 33 18 33 18 16 27.7604 16 27.7604 19.686 22.3945 19.686 22.3945 22.9302 27.3425 22.9302 27.3425 26.6163 22.3945 26.6163"/>
    <path d="M43.566 24.14c0 1.976-.358 3.62-1.074 4.93-.715 1.31-1.724 2.294-3.027 2.953-1.296.651-2.82.977-4.575.977h-5.344V16h5.716c1.778 0 3.284.314 4.52.942a6.37 6.37 0 0 1 2.812 2.756c.648 1.209.972 2.69.972 4.442Zm-4.632.162c0-1.03-.136-1.883-.407-2.558-.263-.682-.663-1.19-1.197-1.523-.535-.341-1.209-.512-2.022-.512h-1.3v9.524h.995c1.355 0 2.35-.404 2.982-1.21.633-.814.949-2.054.949-3.72Z"/>
    <path d="M61.336 33h-5.851l-6.033-11.977h-.102c.038.365.072.803.102 1.314.03.512.057 1.035.08 1.57.022.527.033 1.004.033 1.43V33h-3.954V16h5.83l6.01 11.814h.067a90.938 90.938 0 0 1-.068-1.29l-.068-1.5a45.56 45.56 0 0 1-.022-1.338V16h3.976v17Z"/>
    <path d="M78 24.14c0 1.976-.358 3.62-1.073 4.93-.716 1.31-1.725 2.294-3.028 2.953-1.295.651-2.82.977-4.575.977h-5.343V16h5.716c1.777 0 3.284.314 4.519.942a6.371 6.371 0 0 1 2.813 2.756c.647 1.209.971 2.69.971 4.442Zm-4.632.162c0-1.03-.135-1.883-.406-2.558-.264-.682-.663-1.19-1.198-1.523-.534-.341-1.209-.512-2.022-.512h-1.3v9.524h.995c1.356 0 2.35-.404 2.982-1.21.633-.814.95-2.054.95-3.72Z" />
  </svg>

  <nav>
    <ul>
      <li><a href="/">Home</a></li>
      <li><a href="/about">About</a></li>
      <li><a href="/blog">Blog</a></li>
      <li><a href="/contact">Contact</a></li>
    </ul>
  </nav>

  <form action="/">
    <fieldset>
      <legend class="visually-hidden">Search form</legend>

      <div>
        <label for="query">Search the site</label>
        
        <input type="search" name="query" id="query" placeholder="enter keyword to search the site">
        <button>
          <span>Search</span>
          <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-search" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M10 10m-7 0a7 7 0 1 0 14 0a7 7 0 1 0 -14 0" /><path d="M21 21l-6 -6" /></svg>
        </button>
      </div>
    </fieldset>
  </form>
</header>


<style>

  header {
    display: flex;
    flex-flow: row nowrap;
    justify-content: flex-start;
    align-items: center;
    gap:1rem;
  }
  svg {
    height: 100%;
    fill: var(--color);
    width:8rem;
    flex-shrink: 0;
  }
  .logo-background {
    fill: var(--background);
  }


  ul {
    display: flex;
    flex-flow: row nowrap;
    list-style: none;
    align-items:end;
    gap: .5rem;
  }
  a {
    color: var(--color);
    text-decoration: none;
    font-weight: bold;
    font-size: 1.5rem;
  }


  form {
    width: 100%;
    container-type: inline-size;
  }
  fieldset {
    border:0;
    display: flex;
    justify-content: end;
    padding:0;
  }
  div {
    display: flex;
    flex-flow: row wrap;
    gap:.5rem
  }
  label {
    flex-basis: 100%;
    font-weight: bold;
  }
  input {
    border:2px solid var(--color-blue)
  }
  button {
      all:unset;
      background:var(--color-green);
      display:flex;
      align-items:center;
      gap:.25rem;
      
    }
  button svg {
    width:1.25rem;
    fill: none;
    display:none
  }
  input, button {
    padding:.25rem;
    text-transform:uppercase;
    font-size: .8rem;
    box-shadow:3px 3px 0 0 var(--color-blue);
    border-radius: .25rem;
    font-family: inherit;
    color: inherit
  }

  @container (width > 5rem) and (width < 10rem) {
    label {
      display: none;
    }
    input[type='search'] {
      width: 6rem;
    }
    button > span {
      display: none;
    }
    button > svg {
      display: block;
    }
  }
  @container (width > 10rem) {
    div{
      width: 10rem;
    }
    input[type='search'] {
      width: 6rem;
    }
    
  }
  @container (width > 20rem) {
    div{
      width: 20rem;
    }
    input[type='search'] {
      width: 16rem;
    }
  }

  @container (width > 25rem) {
    div{
      width: 25rem;
    }
    input[type='search'] {
      width: 18rem;
    }
    button svg {
      display: block
    }
  }

  
</style>