<template>
  <div class="profile">
    <div class="row">
      <div class="col-md-4">
        <div class="image">
          <img src="../../assets/image/12.jpg" />
        </div>
        <div class="intro">
          <h3>Name</h3>
          <h2>Intro</h2>
          <hr />
          <p>Email.gmail.com</p>
          <p>+8801600000000</p>
          <p>University</p>
          <p>2021-2022</p>
          <p>Green Vet Pharma</p>
          <p>Executive Manager</p>
        </div>
      </div>
      <div class="col-md-8">
        <div class="bio">
          <h3>Profile</h3>
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Repudiandae
            rem fugit nostrum soluta aperiam voluptatem nemo, quidem tenetur
            porro numquam distinctio, obcaecati ea necessitatibus maxime ab
            mollitia veritatis impedit. Ratione.
          </p>
        </div>
        <div class="bio1">
          <div class="first">
            <h4>Present Address</h4>
            <address>
              House No. : 66, Road No. :11,<br />
              DIT Project, Merul-badda,Dhaka-1212.
            </address>
          </div>
          <div class="first">
            <h4>Permanent Address</h4>
            <address>
              House No. : 66, Road No. :11,<br />
              DIT Project, Merul-badda,Dhaka-1212.
            </address>
          </div>
        </div>

        <div class="bio1">
          <div class="first">
            <h4>Personal Information</h4>
            <ul>
              <li>Father Name:<a>Name</a></li>
              <li>Mother Name:<a>Name</a></li>
              <li>Officel Number:<a>+8801600000000</a></li>
              <li>Blood Group:<a>A</a></li>
              <li>National ID:<a>+8801600000000</a></li>
              <li>Date Of Birth:<a>12-12-2022</a></li>
            </ul>
          </div>
          <div class="first">
            <h4>Working Place</h4>
            <div class="intro">
              <h5>COMPANY NAME</h5>
              <p>
                Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Ratione expedita in a quisquam sequi laborum culpa deserunt ut
                aspernatur praesentium distinctio laboriosam, fugiat
                necessitatibus impedit ipsam eligendi quasi minus natus.
              </p>
            </div>
            <div class="intro">
              <h5>COMPANY NAME</h5>
              <p>
                Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                Ratione expedita in a quisquam sequi laborum culpa deserunt ut
                aspernatur praesentium distinctio laboriosam, fugiat
                necessitatibus impedit ipsam eligendi quasi minus natus.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  mounted() {
    window.scrollTo(0, 0);
  },
};
</script>

<style scoped>
.profile {
  width: 100%;
  height: 100%;
  padding: 10px;
  margin: 0;
}
.profile .row {
  width: 100%;
  height: 100%;
  padding: 0;
  margin: 0;
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
.col-md-4 {
  width: 25%;
  height: 800px;
  padding: 0;
  margin: 0;
  background-image: url(../../assets/image/profile.svg);
  background-position: center;
  background-size: cover;
  box-shadow: 0 0 20px red;
}
.col-md-4 .image {
  width: 100%;
  height: 300px;
  padding: 40px;
  margin: 5px;
  display: flex;
  justify-content: center;
}
.col-md-4 .image img {
  width: 300px;
  height: 300px;
  border-radius: 50%;
  border: 2px solid #fff;
}
.col-md-4 .intro {
  width: 100%;
  height: 100%;
  padding: 30px;
  margin: 0;
  display: block;
}
.col-md-4 .intro h3 {
  font-size: 1.5rem;
  font-weight: 600;
  font-family: "Playfair Display", serif;
  padding: 20px;
  margin: 0;
}
.col-md-4 .intro h2 {
  font-size: 1.8rem;
  font-weight: 600;
  font-family: "Playfair Display", serif;
  text-align: center;
  padding: 10px;
  margin: 0;
}
.col-md-4 .intro hr {
  width: 100%;
  height: 2px;
  color: #fff;
}
.col-md-4 .intro p {
  font-size: 1.2rem;
  font-weight: 600;
  font-family: "Playfair Display", serif;
  text-align: center;
  padding: 5px;
  margin: 0;
}
.row .col-md-8 {
  width: 75%;
  height: 100%;
  padding: 30px;
  margin: 0;
  display: block;
}
.row .col-md-8 .bio {
  width: 100%;
  height: 100%;
  padding: 10px;
  margin: 10px;
}
.row .col-md-8 .bio h3 {
  font-size: 1.6rem;
  font-weight: 600;
  font-family: "Playfair Display", serif;
  padding: 20px;
  margin: 0;
  border-bottom: 2px solid gray;
}
.row .col-md-8 .bio p {
  font-size: 1rem;
  font-weight: 600;
  font-family: "Playfair Display", serif;
  padding: 10px;
  margin: 0;
}
.row .col-md-8 .bio1 {
  width: 100%;
  height: 100%;
  padding: 10px;
  margin: 0;
  display: flex;
  justify-content: center;
}
.row .col-md-8 .bio1 .first {
  width: 50%;
  height: 100%;
  padding: 10px;
  margin: 0;
}
.row .col-md-8 .bio1 .first h4 {
  font-size: 1.6rem;
  font-weight: 600;
  font-family: "Playfair Display", serif;
  padding: 10px;
  margin: 0;
  text-align: center;
  border-bottom: 2px solid gray;
}
.row .col-md-8 .bio1 .first address {
  width: 100%;
  height: 100%;
  padding: 10px;
  margin: 0;
  font-size: 1.1rem;
  font-weight: 600;
  font-family: "Playfair Display", serif;
  text-align: center;
}
.row .col-md-8 .bio1 .first ul {
  width: 100%;
  height: 100%;
  padding: 10px;
  margin-left: 20%;
}
.row .col-md-8 .bio1 .first ul li {
  list-style: none;
  font-size: 1.2rem;
  font-weight: 600;
  font-family: "Playfair Display", serif;
  padding: 5px;
  margin: 0;
}
.row .col-md-8 .bio1 .first ul li a {
  font-size: 1rem;
  font-weight: 600;
  font-family: "Playfair Display", serif;
  padding: 5px;
  margin: 0;
}
.row .col-md-8 .bio1 .first .intro {
  width: 100%;
  height: 100%;
  padding: 0;
  margin: 0;
}
.row .col-md-8 .bio1 .first .intro h5 {
  font-size: 1.2rem;
  font-weight: 600;
  font-family: "Playfair Display", serif;
  text-align: center;
  padding: 10px;
  margin: 0;
}
.row .col-md-8 .bio1 .first .intro p {
  font-size: 1rem;
  font-weight: 600;
  font-family: "Playfair Display", serif;
  text-align: justify;
}
</style>