<template>
  <div>
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
          </div>
          <div>
            <h1>How has it affected the Mexican economy?</h1>
            <p>NAFTA gave a major boost to Mexican farm exports to the United States, which have tripled since NAFTA’s implementation. Hundreds of thousands of auto manufacturing jobs have also been created in the country, and most studies have found [PDF] that the pact had a positive impact on Mexican productivity and consumer prices.</p>
            <p>The pact was the continuation of a decade of economic liberalization that saw the country transition from one of the world’s most protectionist economies to one of the most open to trade. Mexico had reduced many of its trade barriers upon joining the General Agreement on Tariffs and Trade (GATT), the precursor to the WTO, in 1986, but still had a pre-NAFTA average tariff level [PDF] of 10 percent.</p>
            <p>Mexican policymakers saw NAFTA as an opportunity to both accelerate and “lock in” these hard won reforms to the Mexican economy. In addition to liberalizing trade, Mexico’s leaders reduced public debt, introduced a balanced budget rule, stabilized inflation, and built up the country’s foreign reserves. Thus while Mexico was hard hit [PDF] by the 2008 U.S. recession due to its dependence on exports to the U.S. market—in 2009 Mexican exports to the United States fell 17 percent while its economy contracted by over 6 percent—its economy was able to bounce back relatively quickly. Mexico returned to growth in 2010, its GDP expanding over 5 percent, and subsequently falling to around 2 percent in 2014 and 2015.</p>
            <p>But Mexico’s NAFTA experience has suffered from a disconnect between the promises of some of its supporters—that the pact would deliver rapid growth, raise wages, and reduce emigration—and the deal’s more mixed outcomes. Between 1993 and 2013, Mexico’s economy grew at an average rate of just 1.3 percent a year during a period when Latin America was undergoing a major expansion. Poverty remains at the same levels as in 1994. And the expected “wage convergence” between U.S. and Mexican wages didn’t happen, with Mexico’s per capita income rising at an annual average of just 1.2 percent in that period—far slower than Latin American countries such as Brazil, Chile, and Peru.</p>
            <p>
              Continue Reading at
              <a
                href="https://www.cfr.org/backgrounder/naftas-economic-impact"
                alt="original-site"
                target="_blank"
                rel="noopener noreferrer"
              >CFR.com</a>
            </p>
          </div>
        </div>
      </div>
    </div>
    <Footer/>
  </div>
</template>

<script>
import Vue from "vue";
import Scrollspy from "vue2-scrollspy";
import Header from "./components/Header";
import TitleArea from "./components/TitleArea";
import Footer from "./components/Footer";
Vue.use(Scrollspy);
export default {
  methods: {},
  el: "#app",
  components: {
    Header,
    TitleArea,
    Footer
  },
  data() {
    return {
      section: 0,
      titles: [
        "Introduction",
        "How does NAFTA fit into the broader debate over trade policy?",
        "How has NAFTA affected the U.S. economy?",
        "How has it affected the Mexican economy?"
      ]
    };
  }
};
</script>
<style scoped>
@import "./App.css";
</style>
