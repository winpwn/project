<template>
  <div class="img">
    <navbar />
    <div class="card-bg-center">
      <b-card style="width: 80%;">
        <div class="one-image">
          <b-card class="image-center" title="Title" img-src="https://fv.lnwfile.com/_/fv/_raw/r6/ew/wh.jpg"
            img-alt="Image" img-top>
            <b-card-text>
              This is a wider card with supporting text below as a natural lead-in to additional content.
              This content is a little bit longer.
            </b-card-text>

          </b-card>

        </div>

      </b-card>
    </div>

  

  </div>

  
  
</template>

<script>
export default{
  
}
</script>

<style>
.img {
  background-image: url('../image/bg-tree.jpg');
  background-size: cover;
  height: auto;
  background-position: 100%
}

.card-bg-center {
  display: flex;
  justify-content: center;
}

.one-image {
  display: flex;
  justify-content: center;
}

.image-center {
  width: 800px;
  height: 800px;

}</style>


