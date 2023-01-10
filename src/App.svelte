<script>
  import pic from "C:/Users/aksha/Documents/IEEE_Website/src/album.png"
</script>

<main>
    <div class="topic">
      <a href="https://extract.pics/" target="_self" rel="noreferrer"> 
        <img src={pic} alt="Image-Extractor" class="fimg">
      
        <span class="imgnm">Image Extractor</span>
      </a>
      <a href="https://extract.pics/changelog" target="_self" rel="noreferrer"> 
        <span class="imgver">VERSION 2.4.0</span>
      </a>
    </div>
    <div class="headings">
      <a href="https://extract.pics/api" target="_self" rel="noreferrer"> 
        <span class="api">API</span>
      </a>
      <a href="https://www.buymeacoffee.com/pabue" target="_self" rel="noreferrer"> 
        <span class="dnt">Donate</span>
      </a>
      <a href="https://extract.pics/feedback" target="_self" rel="noreferrer"> 
        <span class="fb">Feedback</span>
      </a>
      <a href="https://extract.pics/about" target="_self" rel="noreferrer"> 
        <span class="abt">About</span>
      </a>
    </div>
</main>

<style>
  div.topic{
    position: fixed;
    top:40px;
    right:1250px;
  }
  .fimg{
    height: 25px;
    padding: 1px;
  }
  .fimg:hover{
    filter: drop-shadow(0 0 2em #15ff19aa);
  }
  .imgnm{
    font-family: 'calibri';
    font-size:1.1em;
    position:relative;
    left:8px;
    top:-8px;
    color: white;
  }
  .imgnm:hover{
    filter: drop-shadow(0 0 1em grey);
  }
  .imgver{
    font-family: 'calibri';
    font-size: 0.9em;
    position:relative;
    right:108px;
    top:13px;
    color: #34D399;
  }
  .api:hover{
    text-decoration: underline;
  }
  .dnt:hover{
    text-decoration: underline;
  }
  .fb:hover{
    text-decoration: underline;
  }
  .abt:hover{
    text-decoration: underline;
  }
  .headings{
    color: white;
  }
</style>
