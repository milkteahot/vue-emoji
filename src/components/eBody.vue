<template>
   <div id="columns">
      <figure>
        <img src="http://mblogthumb2.phinf.naver.net/MjAxODAzMDNfOCAg/MDAxNTIwMDQ4OTU2NTE5.UQnF4whjRdhKDSjJZN7FU-oqhnd_rWmze92ffRz8XJsg._FkO9Gaho_RDHCyIrpsUF_-LZVHvzC_AYl9TZnfnjYwg.JPEG.wjdgoxhxh/downloadfile.jpeg?type=w800">
        
        <figcaption>
        <div class="header">Title </div>
        <div class="meta">
          <a>by Friends</a></div>
        <div class="extra content">
                        <span class="right floated">
                      
      <i class="fas fa-heart"></i>
   
      50 likes
    </span></div> 
        
        <div class="description">
                    
        </div>
        </figcaption>
      </figure>
 
      <figure>
        <img src="//s3-us-west-2.amazonaws.com/s.cdpn.io/4273/rapunzel.jpg">
        <figcaption>Rapunzel, clothed in 1820’s period fashion</figcaption>
      </figure>
 
      <figure>
        <img src="//s3-us-west-2.amazonaws.com/s.cdpn.io/4273/belle.jpg">
        <figcaption><div class="header">Title </div>
        <div class="meta">
          <a>by Friends</a></div>
        <div class="extra content">
                        <span class="right floated">
      <div class=heart>               
      <i class="fas fa-heart"></i></div>
   
      50 likes
    </span></div> 
        
        <div class="description">
                    
        </div></figcaption>
      </figure>
 
      <figure>
        <img src="//s3-us-west-2.amazonaws.com/s.cdpn.io/4273/mulan_2.jpg">
        <figcaption><div class="header">Title </div>
        <div class="meta">
          <a>by Friends</a></div>
        <div class="extra content">
                        <span class="right floated">
                      
      <i class="fas fa-heart"></i>
   
      50 likes
    </span></div> 
        
        <div class="description">
                    
        </div></figcaption>
      </figure>
 
      <figure>
        <img src="//s3-us-west-2.amazonaws.com/s.cdpn.io/4273/sleeping-beauty.jpg">
        <figcaption><div class="header">Title </div>
        <div class="meta">
          <a>by Friends</a></div>
        <div class="extra content">
                        <span class="right floated">
                      
      <i class="fas fa-heart"></i>
   
      50 likes
    </span></div> 
        
        <div class="description">
                    
        </div></figcaption>
      </figure>
 
      <figure>
        <img src="//s3-us-west-2.amazonaws.com/s.cdpn.io/4273/pocahontas_2.jpg">
        <figcaption><div class="header">Title </div>
        <div class="meta">
          <a>by Friends</a></div>
        <div class="extra content">
                        <span class="right floated">
                      
      <i class="fas fa-heart"></i>
   
      50 likes
    </span></div> 
        
        <div class="description">
                    
        </div></figcaption>
      </figure>
 
      <figure>
        <img src="//s3-us-west-2.amazonaws.com/s.cdpn.io/4273/snow-white.jpg">
        <figcaption><div class="header">Title </div>
        <div class="meta">
          <a>by Friends</a></div>
        <div class="extra content">
                        <span class="right floated">
                      
      <i class="fas fa-heart"></i>
   
      50 likes
    </span></div> 
        
        <div class="description">
                    
        </div></figcaption>
      </figure>    
 
      <figure>
        <img src="//s3-us-west-2.amazonaws.com/s.cdpn.io/4273/ariel.jpg">
        <figcaption><div class="header">Title </div>
        <div class="meta">
          <a>by Friends</a></div>
        <div class="extra content">
                        <span class="right floated">
                      
      <i class="fas fa-heart"></i>
   
      50 likes
    </span></div> 
        
        <div class="description">
                    
        </div></figcaption>
      </figure>
 
      <figure>
        <img src="//s3-us-west-2.amazonaws.com/s.cdpn.io/4273/tiana.jpg">
        <figcaption><div class="header">Title </div>
        <div class="meta">
          <a>by Friends</a></div>
        <div class="extra content">
                        <span class="right floated">
                      
      <i class="fas fa-heart"></i>
   
      50 likes
    </span></div> 
        
        <div class="description">
                    
        </div></figcaption>
      </figure>   
    </div>
</template>

<script>

export default {
  
    
}
</script>

<style>
#columns {
    column-width: 250px;
    column-gap: 15px;
    margin-top: 10px;
}

#columns figure {
    display: inline-block;
    /* border: 1px solid rgba(0,0,0,0.2); */
    border-radius: 10px;
    margin: 1;
    margin-bottom: 15px;
    padding: 10px;
    

}

#columns figure:hover {
  box-shadow: 2px 2px 5px rgba(0,0,0,0.5);
  transform: scale(1.1);
    transition: 0.4s;
}

#columns figure img {
    width:100%;
}

#columns figure figcaption{
    border-top:1px solid rgba(0,0,0,0.2);
    padding:10px;
    margin-top:11px;
}

.header {
  display: flex;
  margin: '';
  font-family: 'Lato', 'Helvetica Neue', Arial, Helvetica, sans-serif;
  color: rgba(0, 0, 0, 0.85);

  font-weight: bold;
  font-size: 1.28571429em;
  /* margin-top: -0.21425em; */
  line-height: 1.28571429em;

  /* margin-top: 0.5em; */
}

.meta {
  /* margin-top: 0.5em; */

  font-size: 1em;
  color: rgba(0, 0, 0, 0.4);

  float: left;
}

.description {
  clear: both;
  color: rgba(0, 0, 0, 0.68);
  margin-top: 0.5em;
  text-align:center;

}

.extra {
  max-width: 100%;
  min-height: 0em !important;
  -webkit-box-flex: 0;
      -ms-flex-positive: 0;
          flex-grow: 0;
  /* border-top: 1px solid rgba(0, 0, 0, 0.05) !important; */
  position: static;
  background: none;
  width: auto;
  margin: 0em 0em;


}

.fas.fa-heart {
  color:red;

}

.fas.fa-heart:hover {
  transform: scale(2);
    transition: 1s;
}

.right {
  float: right;
}

.heart2 {

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
