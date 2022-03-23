<template>
  <div class="home">
    <div class="row">
      <div class="image">
        <img src="../../assets/image/home.jpg" />
      </div>
      <h3>Home</h3>
      <div class="info">
        <div class="col-md-4" v-for="intro in intros" :key="intro.id">
          <a :href="intro.url">
            <div class="card">
              <img :src="intro.image" />
              <h2>{{ intro.name }}</h2>
            </div>
          </a>
        </div>
      </div>
      <div class="info1">
        <div class="col-md-4">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi
            beatae et ut esse officiis, aliquam laudantium tempore nihil
            molestiae quam assumenda sit earum architecto pariatur illo
            voluptatem eaque quibusdam molestias?
          </p>
        </div>
        <div class="col-md-4">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi
            beatae et ut esse officiis, aliquam laudantium tempore nihil
            molestiae quam assumenda sit earum architecto pariatur illo
            voluptatem eaque quibusdam molestias?
          </p>
        </div>
        <div class="col-md-4">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Quasi
            beatae et ut esse officiis, aliquam laudantium tempore nihil
            molestiae quam assumenda sit earum architecto pariatur illo
            voluptatem eaque quibusdam molestias?
          </p>
        </div>
      </div>
      <div class="contact">
        <div class="col-md-6">
          <h3>Contact Form</h3>
          <form>
            <div class="form-group">
              <label>Full Name</label>
              <input class="form-control" />
            </div>
            <div class="form-group">
              <label>Email</label>
              <input class="form-control" />
            </div>
            <div class="form-group">
              <label>Mobile No</label>
              <input type="number" class="form-control" />
            </div>
            <div class="form-group">
              <label>Subject</label>
              <input class="form-control" />
            </div>
            <div class="form-group">
              <label>Message</label>
              <textarea class="form-control"></textarea>
            </div>
            <div class="my-3">
              <button class="btn btn-primary">Send</button>
            </div>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      intros: [
        {
          id: 1,
          name: "Poultry Bangladesh",
          image: require("../../assets/image/1.jpg"),
          url: "",
        },
        {
          id: 2,
          name: "Membership",
          image: require("../../assets/image/2.jpg"),
          url: "/registration",
        },
        {
          id: 1,
          name: "Poultry show",
          image: require("../../assets/image/3.jpg"),
          url: "",
        },
      ],
    };
  },
  mounted() {
    window.scrollTo(0, 0);
  },
};
</script>

<style scoped>
.home {
  width: 100%;
  height: 100%;
  padding: 2px;
  margin: 0;
}
.home .row {
  width: 100%;
  height: 100%;
  padding: 0;
  margin: 0;
}
.row .image {
  width: 100%;
  height: 700px;
  padding: 0;
  margin: 0;
}
.row .image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  background-position: center;
}
.row h3 {
  font-size: 1.8rem;
  font-weight: 700;
  font-family: "Lobster", cursive;
  letter-spacing: 1px;
  text-align: center;
  padding: 5px;
  margin: 5px;
}
.row .info {
  width: 100%;
  height: 100%;
  padding: 0;
  margin: 0;
  display: flex;
  justify-content: center;
}
.row .info .col-md-4 {
  width: 33%;
  height: 100%;
  padding: 0;
  margin: 0;
}
.row .info .col-md-4 a {
  text-decoration: none;
}
.row .info .col-md-4 .card {
  width: 100%;
  height: 500px;
  padding: 0;
  margin: 0;
  position: relative;
  overflow: hidden;
}
.row .info .col-md-4 .card img {
  width: 100%;
  height: 100%;
  background-position: center;
  background-size: cover;
  opacity: 0.8;
  transform: scale(1);
  transition: 0.5s transform ease-out;
}
.row .info .col-md-4 .card:hover img {
  transform: scale(1.09);
  transition: 0.3s transform ease-out;
  opacity: 1;
}
.row .info .col-md-4 .card h2 {
  position: absolute;
  font-size: 2.5rem;
  font-weight: 600;
  font-family: "Playfair Display", serif;
  top: 45%;
  left: 35%;
  color: #000;
}
.row .info1 {
  width: 100%;
  height: 100%;
  padding: 10px;
  margin: 0;
  display: flex;
  justify-content: center;
}
.row .info1 .col-md-4 {
  padding: 30px;
  margin: 0;
  width: 33%;
  height: 100%;
}
.row .info1 .col-md-4 p {
  font-size: 1.1rem;
  font-weight: 600;
  font-family: "Playfair Display", serif;
  text-align: justify;
}
.row .contact {
  width: 100%;
  height: 100%;
  padding: 10px;
  margin: 0;
  display: flex;
  justify-content: center;
  background-image: url(../../assets/image/ct.jpg);
  background-size: cover;
  background-position: center;
}
.row .col-md-6 {
  width: 40%;
  height: 100%;
}
.row .col-md-6 label {
  font-size: 1.2rem;
  font-weight: 600;
  font-family: "Playfair Display", serif;
  padding: 5px;
  margin: 0;
}
</style>