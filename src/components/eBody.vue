<template>
   <div id="columns">
      <figure>
        <img src="//s3-us-west-2.amazonaws.com/s.cdpn.io/4273/cinderella.jpg">
        <figcaption>Cinderella wearing European fashion of the mid-1860’s</figcaption>
      </figure>
 
      <figure>
        <img src="//s3-us-west-2.amazonaws.com/s.cdpn.io/4273/rapunzel.jpg">
        <figcaption>Rapunzel, clothed in 1820’s period fashion</figcaption>
      </figure>
 
      <figure>
        <img src="//s3-us-west-2.amazonaws.com/s.cdpn.io/4273/belle.jpg">
        <figcaption>Belle, based on 1770’s French court fashion</figcaption>
      </figure>
 
      <figure>
        <img src="//s3-us-west-2.amazonaws.com/s.cdpn.io/4273/mulan_2.jpg">
        <figcaption>Mulan, based on the Ming Dynasty period</figcaption>
      </figure>
 
      <figure>
        <img src="//s3-us-west-2.amazonaws.com/s.cdpn.io/4273/sleeping-beauty.jpg">
        <figcaption>Sleeping Beauty, based on European fashions in 1485</figcaption>
      </figure>
 
      <figure>
        <img src="//s3-us-west-2.amazonaws.com/s.cdpn.io/4273/pocahontas_2.jpg">
        <figcaption>Pocahontas based on 17th century Powhatan costume</figcaption>
      </figure>
 
      <figure>
        <img src="//s3-us-west-2.amazonaws.com/s.cdpn.io/4273/snow-white.jpg">
        <figcaption>Snow White, based on 16th century German fashion</figcaption>
      </figure>    
 
      <figure>
        <img src="//s3-us-west-2.amazonaws.com/s.cdpn.io/4273/ariel.jpg">
        <figcaption>Ariel wearing an evening gown of the 1890’s</figcaption>
      </figure>
 
      <figure>
        <img src="//s3-us-west-2.amazonaws.com/s.cdpn.io/4273/tiana.jpg">
        <figcaption>Tiana wearing the <i>robe de style</i> of the 1920’s</figcaption>
      </figure>   
    </div>
</template>

<script>
export default {
    
}
</script>

<style>
#columns {
    column-width: 350px;
    column-gap: 15px;
    margin-top: 10px;
}

#columns figure {
    display: inline-block;
    /* border: 1px solid rgba(0,0,0,0.2); */
    border-radius: 10px;
    margin: 0;
    margin-bottom: 15px;
    padding: 10px;
    box-shadow: 2px 2px 5px rgba(0,0,0,0.5);;

}

#columns figure img {
    width:100%;
}

#columns figure figcaption{
    border-top:1px solid rgba(0,0,0,0.2);
    padding:10px;
    margin-top:11px;
}


/* .card-row {
  display: flex;
  justify-content: center;
  align-items: center;  
  min-width: 780px;
  width: 100%;
  height: 500px;
}
.card {
  position: relative;
  background-color: #FFFFFF;
  height: 370px;
  width: 240px;
  margin: 10px;
  overflow: hidden;
  box-shadow: 0px 2px 4px 0px rgba(0,0,0,0.5);
}
.card-image {
  /* center horizontally overflown image */
  /* position: absolute;
  left: -9999px;
  right: -9999px;
  margin: auto;

  height: 220px;
  min-width: 100%;
}
.card-footer {
  position: absolute;
  bottom: 0;
  height: 130px;
  padding: 10px 15px;
  font-family: Helvetica;
}
.card-text {
  font-size: 14px;
  color: rgba(0, 0, 0, 0.7);
}
.card-title {
  font-family: Serif;
}
.card-author {
  font-size: 14px;
  color: #BAB096;
}
.card-author.selected {
  color: #6a6456;
} */ 
</style>
