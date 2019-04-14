<template>
  <div>
    <div class="title-section">
      <div class="left-chunk">
        <h1>NAFTA’s Economic Impact</h1>
        <p
          class="par"
        >President Trump has reached a deal with Canada and Mexico to restructure the North American Free Trade Agreement, hoping a new trilateral accord will reinvigorate the U.S. manufacturing sector.</p>
        <h5>Backgrounder by James McBride and Mohammed Aly Sergie</h5>
        <p class="ital">Last updated October 1, 2018</p>
      </div>
      <div class="right-chunk">
        <img
          src="https://cfrd8-files.cfr.org/sites/default/files/styles/article_header_m_480px/public/image/2017/04/NAFTA-Header-1280x720.jpg"
          alt="trucks"
        >
        <p
          class="ital"
        >Mexican commercial trucks cross the border into the United States at Laredo, Texas. (Josue Gonzalez/Reuters)</p>
      </div>
    </div>
    <div class="divide">
      <div class="line">{{'o'}}</div>
      <div class="friendStuff">
        <i class="fab fa-facebook-f soc"></i>
        <i class="fab fa-twitter soc"></i>
        <i class="fab fa-linkedin-in soc"></i>
        <i class="fas fa-envelope soc"></i>
        <i class="fas fa-print soc"></i>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "TitleArea"
};
</script>

<style scoped>
.line {
  display: grid;
  background: grey;
  border-radius: 6px;
  font-size: 1.7px;
  opacity: 0.5;
  width: 60%;
}
.friendStuff {
  margin-top: 10px;
  margin-left: 10px;
}
.soc {
  margin-right: 40px;
  font-size: 20px;
  color: black;
  transition: color 1.2s;
}
.soc:hover {
  color: orange;
  cursor: pointer;
  transition: color 0.5s;
}

.divide {
  width: 50%;
  margin-left: 10%;
  margin-bottom: 80px;
}
.title-section {
  width: 100%;
  margin: auto;
  display: flex;
  margin-top: 16px;
}

.left-chunk {
  width: 40%;
  padding-left: 10%;
  margin-right: 6%;
  overflow: hidden;
  float: left;
}
.right-chunk {
  width: 60%;
  margin-top: 14px;
  padding-right: 3%;
  float: right;
}

p {
  padding-top: 0px;
  line-height: 20px;
}

h1 {
  padding-top: 0px;
  font-size: 40px;
  font-weight: thin;
  font-family: "Raleway", sans-serif;
}

.par {
  font-size: 15px;
  font-family: "Quicksand", sans-serif;
}
h5 {
  font-family: "Quicksand", sans-serif;
}
.ital {
  font-style: italic;
  font-family: "Quicksand", sans-serif;
  font-size: 14px;
}
</style>
