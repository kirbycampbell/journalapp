<template>
  <div id="app">
    <Header/>
    <TitleArea/>
    <div class="container">
      <div class="sidebar">
        <ul class="menu" v-scroll-spy-active="{class: 'customActive'}" v-scroll-spy-link>
          <li :key="item" v-for="item in titles" class="menu-item">
            <a>{{item}}</a>
          </li>
        </ul>

        <div class="current-section"></div>
      </div>

      <div class="main" v-scroll-spy="{data: 'section'}">
        <div>
          <h1 class="first-h1">Introduction</h1>
          <p>The North American Free Trade Agreement, or NAFTA, is a three-country accord negotiated by the governments of Canada, Mexico, and the United States that entered into force in January 1994. NAFTA’s terms, which were implemented gradually through January 2008, eliminated most tariffs on products traded between the three countries. Liberalization of trade in agriculture, textiles, and automobile manufacturing was a major focus. The deal also sought to protect intellectual property, establish dispute resolution mechanisms, and, through side agreements, implement labor and environmental safeguards.</p>
          <p>NAFTA fundamentally reshaped North American economic relations, driving unprecedented integration between Canada’s and the United States’ developed economies and Mexico’s developing one. In the United States, NAFTA enjoyed bipartisan backing; it was negotiated by Republican President George H.W. Bush, passed a Democratic-controlled Congress, and was implemented under Democratic President Bill Clinton. It encouraged regional trade to more than triple, and cross-border investment between the three countries also grew significantly.</p>
          <p>Yet NAFTA has remained a perennial target in the broader debate over free trade. President Donald J. Trump says it has undermined U.S. jobs and manufacturing, and in October 2018 his administration struck a deal with Canada and Mexico on an updated version of the pact, to be known as the U.S.-Mexico-Canada Agreement, or USMCA.</p>
        </div>
        <div>
          <h1>How does NAFTA fit into the broader debate over trade policy?</h1>
          <p>When negotiations for NAFTA began in 1991, the goal for all three countries was the integration of Mexico with the highly developed, high-wage economies of the United States and Canada. The hope was that freer trade would bring stronger and steadier economic growth to Mexico, providing new jobs and opportunities for its growing workforce and discouraging illegal migration from Mexico. For the United States and Canada, Mexico was seen both as a promising new market for exports and as a lower cost investment location that could enhance the competitiveness of U.S. and Canadian companies.</p>
          <p>While the United States had completed a free trade agreement with Canada in 1988, the addition of Mexico was unprecedented. Opponents of NAFTA seized on the wage differentials with Mexico, which had a per capita income just 30 percent [PDF] that of the United States. U.S. presidential candidate Ross Perot argued in 1992 that trade liberalization would lead to a “giant sucking sound” of U.S. jobs fleeing across the border. Supporters like Presidents Bush and Clinton countered that the agreement would create hundreds of thousands of new jobs a year, while Mexican President Carlos Salinas de Gortiari saw it as an opportunity to modernize the Mexican economy so that it would “export goods, not people.”</p>
          <p>NAFTA also ushered in a new era of regional and bilateral free trade agreements (FTAs), which have proliferated as the World Trade Organization’s (WTO) global trade talks have stagnated. NAFTA also pioneered the incorporation of labor and environmental provisions in U.S. trade agreements, provisions which have become progressively more comprehensive [PDF] in subsequent FTAs.</p>
          <p>Economists largely agree that NAFTA has provided benefits to the North American economies. Regional trade increased sharply [PDF] over the treaty’s first two decades, from roughly $290 billion in 1993 to more than $1.1 trillion in 2016. Cross-border investment has also surged, with U.S. foreign direct investment (FDI) stock in Mexico increasing in that period from $15 billion to more than $100 billion. But experts also say that it has proven difficult to tease out the deal’s direct effects from other factors, including rapid technological change, expanded trade with other countries such as China, and unrelated domestic developments in each of the countries. Debate persists regarding NAFTA’s legacy on employment and wages, with some workers and industries facing painful disruptions as they lose market share due to increased competition, and others gaining from the new market opportunities that were created.</p>
        </div>
        <div>
          <h1>How has NAFTA affected the U.S. economy?</h1>
          <p>In the years since NAFTA, U.S. trade with its North American neighbors has more than tripled, growing more rapidly than U.S. trade with the rest of the world. Canada and Mexico are the two largest destinations for U.S. exports, accounting for more than a third of the total. Most estimates conclude that the deal had a modest but positive impact on U.S. GDP of less than 0.5 percent, or a total addition of up to $80 billion dollars to the U.S. economy upon full implementation, or several billion dollars of added growth per year.</p>
          <p>Such upsides of trade often escape notice, because while the costs are highly concentrated in specific industries like auto manufacturing, the benefits of a deal like NAFTA are distributed widely across society. Supporters of NAFTA estimate that some fourteen million jobs rely on trade with Canada and Mexico, while the nearly two hundred thousand export-related jobs created annually by the pact pay 15 to 20 percent more on average than the jobs that were lost.</p>
          <p>Critics of the deal, however, argue that it is to blame for job losses and wage stagnation in the United States, driven by low-wage competition, companies moving production to Mexico to lower costs, and a widening trade deficit. The U.S.-Mexico trade balance swung from a $1.7 billion U.S. surplus in 1993 to a $54 billion deficit by 2014. Economists like the Center for Economic and Policy Research’s (CEPR) Dean Baker and the Economic Policy Institute argue that this surge of imports caused the loss of up to 600,000 U.S. jobs over two decades, though they admit that some of this import growth would likely have happened even without NAFTA.</p>
          <p>Many workers and labor leaders point to these numbers to blame trade, including NAFTA, for the decline in U.S. manufacturing jobs. The U.S. auto sector lost some 350,000 jobs since 1994—a third of the industry—while Mexican auto sector employment spiked from 120,000 to 550,000 workers. CEPR’s Baker argues that econometric research shows that increased trade also puts downward pressure on wages for non-college educated workers, who are more likely to face direct competition from low-wage workers in Mexico.</p>
          <p>But other economists like Gary Clyde Hufbauer and Cathleen Cimino-Isaacs of the Peterson Institute for International Economics (PIIE) emphasize that increased trade produces gains for the overall U.S. economy. Some jobs are lost due to imports, but others are created, and consumers benefit significantly from the falling prices and often improved quality of goods created by import competition. A 2014 PIIE study of NAFTA’s effects found that about 15,000 jobs on net are lost each year due to the pact—but that for each of those jobs lost, the economy gains roughly $450,000 in the form of higher productivity and lower consumer prices.</p>
          <img
            class="data-img"
            src="https://www.cfr.org/content/publications/NAFTA-BGR-Timeline-1300x920.jpg"
            alt="data"
          >
          <p>Many economists also assert that the recent troubles of U.S. manufacturing have little to do with NAFTA, arguing that manufacturing in the United States was under stress decades before the treaty. Research by David Autor, David Dorn, and Gordon Hanson published in January 2016 found [PDF] that competition with China had a much bigger negative impact on U.S. jobs since 2001, when China joined the WTO. Hanson, an economist and trade expert at the University of California, San Diego, says that the steepest decline in manufacturing jobs, which fell from seventeen million to eleven million between 2000 and 2010, is mostly attributable to trade with China and underlying technological changes. “China is at the top of the list in terms of the employment impacts that we found since 2000, with technology second, and NAFTA far less important,” he says.</p>
          <p>In fact, says Hanson, NAFTA helped the U.S. auto sector compete with China. By contributing to the development of cross-border supply chains, NAFTA lowered costs, increased productivity, and improved U.S. competitiveness. This meant shedding some jobs in the United States as positions moved to Mexico, he argues, but without the pact, even more would have otherwise been lost. “Because Mexico is so close, you can have a regional industry cluster where goods can go back and forth. The manufacturing industries in the three countries can be very integrated,” he says. These sort of linkages, which have given U.S. automakers an advantage in relation to China, would be much more difficult without NAFTA’s tariff reductions and protections for intellectual property.</p>
          <p>Edward Alden, a senior fellow at the Council on Foreign Relations, says anxiety over trade deals has grown because wages haven’t kept pace with labor productivity while income inequality has risen. To some extent, he says, trade deals have hastened the pace of these changes in that they have “reinforced the globalization of the American economy.”</p>
          <h1>How has it affected the Mexican economy?</h1>
          <p>NAFTA gave a major boost to Mexican farm exports to the United States, which have tripled since NAFTA’s implementation. Hundreds of thousands of auto manufacturing jobs have also been created in the country, and most studies have found [PDF] that the pact had a positive impact on Mexican productivity and consumer prices.</p>
        </div>
      </div>
    </div>
    <div class="footer">
      <div class="footer-logo">Council On Foreign Relations</div>
      <div class="footer-button">
        <div class="btn-item">About CFR</div>
        <div class="btn-item">Support CFR</div>
        <div class="btn-item">Careers</div>
      </div>
      <div class="footer-button">
        <div class="btn-item">Think Tank</div>
        <div class="btn-item">Media</div>
        <div class="btn-item">Contact Us</div>
      </div>
      <div class="news-sec">
        <h2>Daily News Brief</h2>
        <p>Sign up for a morning roundup of news and analysis from around the world.</p>
      </div>
      <div class="form-area">
        <input class="email-form" placeholder="Email Address">
        <input class="email-submit" type="submit">
      </div>
      <div
        class="bottom-of-footer"
      >©2019 Councilon Foreign Relations. All rights reserved. Privacy Policy and Terms of Use. Kirby Campbell Clone.</div>
    </div>
  </div>
</template>

<script>
import Vue from "vue";
import Scrollspy from "vue2-scrollspy";
import Header from "./components/Header";
import TitleArea from "./components/TitleArea";
Vue.use(Scrollspy);
export default {
  methods: {},
  el: "#app",
  components: {
    Header,
    TitleArea
  },
  data() {
    return {
      section: 0,
      titles: [
        "Introduction",
        "How does NAFTA fit into the broader debate over trade policy?",
        "How has NAFTA affected the U.S. economy?",
        "How has it affected the Mexican economy?",
        "What impact has it had on Canada?",
        "What’s next for NAFTA?"
      ]
    };
  }
};
</script>
<style>
@media all and (max-width: 800px) {
  .sidebar {
    display: none;
  }
  .menu {
    display: none;
  }
  .main {
    margin: 0;
    font-size: 20px;
    width: 100%;
  }
  .container {
    display: flex;

    padding-bottom: 26rem;
    margin: 0;
  }
  .current-section {
    padding-top: 0;
  }
  .first-h1 {
    font-family: "Raleway", sans-serif;
    font-size: 40px;
    padding-top: 0;
    margin-top: 0;
  }
}

body {
  margin: 0;
  padding: 0;
  font-stretch: expanded;
  font-family: "Times New Roman", Times, serif;
}
p {
  font-size: 20px;
  padding-top: 20px;
  line-height: 34px;
}

.first-h1 {
  font-family: "Raleway", sans-serif;
  font-size: 40px;
  padding-top: 20px;
  margin-top: -380px;
}
.sidebar {
  position: -webkit-sticky;
  position: sticky;
  top: 150px;
  width: 15%;
  min-width: 100px;
  margin-left: 40px;
  max-width: 230px;
  margin-right: 0;
  font-size: 14px;
  font-family: "Quicksand", sans-serif;
}

h1 {
  font-family: "Raleway", sans-serif;
  font-size: 40px;
  padding-top: 20px;
}

.menu {
  padding: 0;
  list-style: none;
}

.current-section {
  padding-top: 50px;
}

.current-section input {
  max-width: 3em;
}

.menu-item {
  margin-bottom: 20px;
}

.menu-item a {
  cursor: pointer;
  color: black;
  transition: color 1.5s;
}

.menu-item a:hover {
  color: orange;
  transition: color 0.5s;
}

.main {
  margin-left: 300px;
  font-size: 25px;
  width: 66%;
}

.customActive {
  color: #178ce6;
  border-left: 1px solid #178ce6;
  padding-left: 5px;
  transition: all 0.5s;
}
.data-img {
  height: 80%;
  width: 90%;
}

.container {
  padding-bottom: 26rem;
}

.footer {
  bottom: 0;
  width: 94%;
  align-content: center;
  color: white;
  justify-content: center;
  margin: auto;
  background: #412c26;
  height: 22rem;
  padding: 2rem;
}

.footer-logo {
  margin: 0;
  padding: 0;
  width: 20%;
  float: left;
  font-weight: 100;
  font-size: 27px;
  font-family: "Raleway", sans-serif;
  margin-left: 40px;
  cursor: pointer;
}

.footer-button {
  display: flex;
  margin-bottom: 30px;
  padding-left: 50px;
}
.btn-item {
  width: 20%;
  text-align: center;
  font-weight: bold;
  cursor: pointer;
  color: white;
  transition: color 0.8s;
}

.btn-item:hover {
  color: rgb(255, 113, 19);
  transition: color 0.8s;
}

.news-sec {
  float: right;
  font-size: 14px;
}
.news-sec h2 {
  font-size: 20px;
  font-weight: none;
  padding-bottom: 3px;
  opacity: 0.4;
  margin-bottom: 0;
}
.news-sec p {
  margin-top: 0;
  padding-top: 0;
  font-weight: none;
  font-size: 20px;
  opacity: 0.4;
  width: 70%;
}

.bottom-of-footer {
  margin-top: 10rem;
  font-size: 14px;
  margin-left: 3rem;
}
.form-area {
  margin-top: 6rem;
  margin-left: 3rem;
}
.email-form {
  background: none;
  border: none;
  font-size: 18px;

  border-bottom: 2px solid white;
  margin-right: 10px;
}
</style>
