## Ruggedized DeFi
Problem statement :
DeFi apps have exploded in use but have also proved unreliable. Stress testing of DeFi apps for the Cardano environment is required.

## Describe your solution to the problem
Tools to assist developers in the verification of DeFi design and agent-based simulation of DeFi prototypes will stress-test proposed apps.

## Relevant experience
The Photrek team provides expertise in the design, analysis, and evaluation of complex open-source software systems.

## Website/GitHub repository (not required) 
https://photrek.world
## Detailed plan (not required) - Fill in here any additional details
Plan Impact

The Ruggedized DeFi project will provide developers with tools and analysis to assess the potential vulnerabilities of their decentralized financial applications.
Two domains of analysis will be the initial focus
Use of Category Theory to translate proposed applications into structured models which can be developed in Plutus and Haskell.
Use of agent-based simulations to stress test the dynamics of the application in a complex marketplace.

Proposed Outcome
To demonstrate the effectiveness of the tools and analysis, the Photrek team will complete a stress-test of the Uniswap type decentralized exchange. Uniswap creates a liquidity pool by maintaining the ratio between assets. Makers add an equal value of two assets rather than specify buy and sell prices. The exchange price is determined by the impact of a proposed trade on the maintenance of the ratio between the two assets. As the demand to buy one asset increases, thus reducing the quantity of that asset in the pool, the exchange price is adjusted to maintain an equal valuation of the two assets in the pool.

As Cardano developers consider implementing Uniswap-type decentralized exchanges and related DeFi apps, the rigorous quality which the Cardano community has applied to the Cardano network needs to be maintained in the apps' development. While Uniswap has been enormously successful as a decentralized exchange with $1 Million in daily transactions, this is still orders of magnitude smaller than centralized exchanges such as Binance $16 Billion in daily transactions. Two questions that our analysis will address is:

How can the rigor of functional programming and its related modeling with Category Theory be used to improve the long-term reliability of the codebase for a decentralized exchange such as Uniswap?
How will the Uniswap-type liquidity pools react in a stressed market? While the mathematics of maintaining equally valued assets in each pool has been demonstrated to be operational, will this formulation be robust to the stresses of a severe change in the value of a particular asset? Are there modified formulations that can make the markets more resilient?

Project Tasks, Budget, & KPI

Identify Decentralized Exchanges Vulnerabilities ($7,000 - Month 1)
Describe 5 potential software vulnerabilities and identify 2 for further analysis
Describe 5 marketplace stressing scenarios and identify 2 for further analysis
Specify how these vulnerabilities impact Uniswap-type decentralized exchanges

Prototype model and simulation of Uniswap-type vulnerabilities ($18,000 - Month 3)
Develop agent-based simulation of the 2 marketplace stressing scenarios
Develop system model using category theory to address the two software vulnerabilities

Complete experiments analyzing Uniswap-type vulnerabilities ($18,000 - Month 5)
What are the financial risks of software vulnerabilities relative to the market size?
What are the financial risks of the trading dynamics relative to the market size?

Final report including the availability of vulnerability analysis for other DeFi projects ($6,000 - Month 6)
Have we identified two DeFi development teams that can utilize and incorporate the analysis?
Have we provided adequate open-source tools for teams to build upon the results of the project.

## Team Member Roles
Dr. Kenric Nelson - President, Photrek - Nelson will apply his expertise in leading open-source software development and in the modeling and analysis of complex systems.
Dr. Andre Vilela - Associate Professor, University of Pernambuco, Brazil - Vilela will develop an agent-based simulation of the marketplace vulnerabilities in decentralized exchanges.
We are seeking an expert in the use of category theory to model complex software systems. An individual with experience with Haskell programming experience and relevant experiment in decentralized markets is preferred.

Bibliography
G. Angeris, H.-T. Kao, R. Chiang, C. Noyes, and T. Chitra, "An analysis of Uniswap markets," arXiv: 1911.03380 [q-fin.TR], 2019.
H. Adams, N. Zinsmeister, and D. Robinson, "Uniswap v2 Core," https://uniswap.org/whitepaper.pdf, 2020.
M. Healy and K. Williamson, Applying Category Theory to Derive Engineering Software from Encoded Knowledge, Vol. 1816. Springer, Berlin, Heidelberg, 2000.
B. Goodspeed, "Formal Methods for Secure Software Construction," Saint Mary's University, Halifax, NS, 2016.
S. Gebreyohannes, W. Edmonson, and A. Esterline, "Formalization of the responsive and formal design process using category theory," in 2018 Annual IEEE International Systems Conference (SysCon), 2018, pp. 1–8.
A. L. M. Vilela, C. Wang, K. P. Nelson, and H. E. Stanley, "Majority-vote model for financial markets," Phys. A Stat. Mech. its Appl., vol. 515, pp. 762–770, Feb. 2019.
A. L. M. Vilela and H. E. Stanley, "Effect of Strong Opinions on the Dynamics of the Majority-Vote Model," Scientific Reports, 8, 8709, Jun. 2018.

## Requested funds in USD 49000
