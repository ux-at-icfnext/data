<style>
  .collection-hero{
    background: #cccccc;
    padding: 20px;
  }
@media screen and (min-width: 800px){
   .hero-body{
    display: flex;
    flex-flow: space-between;
  }
  .summary {
    width: 80%;
  }
  .summary > p{
    max-width: 500px;
    margin: 0;
    padding:0;
  }
  .stats {

    align-self: flex-end;
  }

}
</style>
<div class="collection-hero">
  <div class="grid-container">
  breadcrumb/would/be/here
  <h1>{{ title }} </h1>
    <div class="hero-body">
      <div class="summary"><p> {{ short }}</p> </div>
      <div class="stats">
        <b>Last Updated</b><br />
        {{ update }} | {{ cycle}}<br />
        <b>Latest Data Available</b><br />
        2021<br />
      </div>
    </div>
  </div>
</div>