<template>
<div>
  <div class="search">
    <input type="text" placeholder=" Search" size="50" class="bar">
    <select name="sort" id="sort">
      <option value=" Recently Added">&nbsp;&nbsp;Recently Added</option>
      <option value=" Oldest">&nbsp;&nbsp;Oldest</option>
    </select>
    <br><br>
    </div>
      <div class="gallery">
          <img src="@/assets/212.png" alt="monkey1" class="profile_photo">
        <div class="desc">monkey1</div>
      </div>

      <div class="gallery">
          <img src="@/assets/1859.png" alt="monkey2" class="profile_photo">
        <div class="desc">monkey2</div>
      </div>

      <div class="gallery">
          <img src="@/assets/1957.png" alt="monkey3" class="profile_photo">
        <div class="desc">monkey3</div>
      </div>

      <div class="gallery">
          <img src="@/assets/2180.png" alt="monkey4" class="profile_photo">
        <div class="desc">monkey4</div>
      </div>

      <div class="gallery">
          <img src="@/assets/3368.png" alt="monkey5" class="profile_photo">
        <div class="desc">monkey5</div>
      </div>

      <div class="gallery">
          <img src="@/assets/4671.png" alt="monkey6" class="profile_photo">
        <div class="desc">monkey7</div>
      </div>

      <div class="gallery">
          <img src="@/assets/5465.png" alt="monkey6" class="profile_photo">
        <div class="desc">monkey8</div>
      </div>

      <div class="gallery">
          <img src="@/assets/7981.png" alt="monkey6" class="profile_photo">
        <div class="desc">monkey9</div>
      </div>

      <div class="gallery">
          <img src="@/assets/8520.png" alt="monkey6" class="profile_photo">
        <div class="desc">monkey10</div>
      </div>

      <div class="gallery">
          <img src="@/assets/1.png" alt="monkey6" class="profile_photo">
        <div class="desc">monkey11</div>
      </div>

      <div class="gallery">
          <img src="@/assets/2.png" alt="monkey6" class="profile_photo">
        <div class="desc">monkey12</div>
      </div>

      <div class="gallery">
          <img src="@/assets/3.png" alt="monkey6" class="profile_photo">
        <div class="desc">monkey13</div>
      </div>
    
</div>
    
</template>

<script>

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  div.gallery {
    margin: 30px;
    margin-top: 10px;
    border-radius: 25px;
    border: solid 1px #e5e8eb;
    float: left;
    height: 400px;
    width: 361px;
  }
  div.search {
    margin: 15px 0 0 25px;
  }
  
  input.bar {
    margin: 7px;
    border-radius: 10px;
    border: solid 1px #e5e8eb;
    height: 50px;
    width: 50%;
  }

  #sort{
    margin: 7px;
    border-radius: 10px;
    border: solid 1px #e5e8eb;
    height: 50px;
    width: 15%;
  }

  div.gallery:hover {
    border: 1px solid #777;
    opacity: 0.6;
    transition: 0.3s;
  }

  div.gallery img {
    border-top-left-radius: 25px;
    border-top-right-radius: 25px;
    width: 100%;
    height: 300px;
  }

  div.desc {
    padding: 15px;
    text-align: center;
  }
</style>
