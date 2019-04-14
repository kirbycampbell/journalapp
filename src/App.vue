<template>
  <div>
    <div id="app">
      <div class="container">
        <div class="sidebar">
          <ul class="menu" v-scroll-spy-active="{class: 'customActive'}" v-scroll-spy-link>
            <li :key="item" v-for="item in titles" class="menu-item">
              <a>{{item}}</a>
            </li>
          </ul>

          <div class="current-section">Section: {{section}}</div>
        </div>

        <div class="main" v-scroll-spy="{data: 'section'}">
          <div>
            <h1>Introduction</h1>
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
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Vue from "vue";
import Scrollspy from "vue2-scrollspy";
Vue.use(Scrollspy);
export default {
  methods: {},
  el: "#app",
  data() {
    return {
      section: 0,
      titles: [
        "Introduction",
        "How does NAFTA fit into the broader debate over trade policy?",
        "How has NAFTA affected the U.S. economy?"
      ]
    };
  }
};
</script>
<style>
.sidebar {
  position: fixed;
  top: 30px;
  left: 10px;
  max-width: 230px;
  font-size: 18px;
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
}

.main {
  margin-left: 300px;
  font-size: 25px;
}

.customActive {
  color: #178ce6;
  border-left: 1px solid #178ce6;
  padding-left: 5px;
  transition: all 0.5s;
}
</style>
