 <template>
  <div class="home">
    <div class="feature-card">
      <router-link to="/movie/tt0409591">
        <img src="naruto boy.jpeg" alt="Naruto Uzumaki"
        class="featured-img" width="359" height="250"/>

        <div class="detail">
          <h3>Naruto</h3>
          <p>
            Naruto Uzumaki, a mishievous adolescent
            ninja, struggles as he searches for
            recognition and dreams of becoming the
            Hokage, the village's leader
            and strongest ninja. 
          </p>
        </div>
      </router-link>
    </div>
  </div>
</template>

<script>

</script>

<style lang="scss">
.home {
  .featured-card {
    position: relative;

    .feature-img {
      display: block;
      width: 100%;
      height: 300px;
      object-fit: cover;

      position: relative;
      z-index: 0;
    }

    .detail {
      position: absolute;
      left: 0;
      right: 0;
      bottom: 0;
      background-color: rgba(0, 0, 0, 0.6);
      padding: 16px;
      z-index: 1;

      h3 {
        color: #FFF;
        margin-bottom: 16px;
      }

      p {
        color:#FFF;
      }
    }
  }
}
</style>
