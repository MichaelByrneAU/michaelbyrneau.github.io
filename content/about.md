+++
title = "About"
description = """\
  I work with Rust and web technologies. Currently analysing and simulating \
  city-scale travel behaviour at Arup.\
  """ 
+++

I'm a Melbourne-based software engineer with an interest in high performance analysis, behaviour simulation, and storytelling through data.
I primarily work with Rust and web technologies on a day-to-day basis. 
However, I have a broader passion for computer science and am always learning new skills.

Right now I look after [Arup](https://www.arup.com/) Australasia's _City Modelling Lab_, focused on complex travel behaviour analysis and simulating how our cities will grow over the coming decades. 
Use the email at the bottom of the page to get in touch.

# Experience

{{ position(
  org="Arup", 
  date="2017 &mdash; Ongoing", 
  title="Australasian City Modelling Lab Lead (Associate)"
) }}

I currently oversee both the strategic transport modelling team in Mel&shy;bourne as well as the Austra&shy;lasian City Modelling Lab team.
Both focus on the analysis and simulation of people's travel behaviour to support future infrastructure and policy assessment. 
A big part of this work is translating complex and probabilistic forecasts into narratives that can be used to inform better government planning. 

I act as an operational lead, overseeing 10-15 people within these teams. 
I'm also a senior technical contributor &mdash; I help architect and develop the tools that facilitate all of the simulation and data analysis work. 
I use Rust for things that need to be fast and lean, Python where that doesn't matter as much, and web stuff{% sidenote() %}
JavaScript/TypeScript, and more specifically technologies and libraries like [WebGL](https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API), [D3](https://d3js.org/), [Observable Plot](https://observablehq.com/plot/), [MapLibre](https://maplibre.org/) and [deck.gl](https://deck.gl/) depending on what a project needs.
{% end %} for inter&shy;active data visual&shy;isation.
Some interesting projects I've led:

<details closed>
<summary>Project Monty for the New Zealand Ministry of Transport</summary>

The development of a new, country-wide strategic transport model for New Zealand. 
A synthetic version of the population is created within this system where everyone is assigned activities to undertake. 
These modelled people then interact with each other across a simulated day, allowing the forecasting of travel conditions into the future.

I led this project for several years, overseeing many aspects of its development including creation of the transport network and demand generation models, calibration of the system using available observed data, as well as data visualisation tools to enable the debugging and evaluation of executed scenarios. 

</details>    

<details closed>
<summary>Infrastructure Victoria 30-Year Strategy</summary>

[Infrastructure Victoria](https://www.infrastructurevictoria.com.au/) is tasked with generating an independent 30-year infrastructure strategy for the Victorian state government in Australia every three to five years.
A large component of this concerns transport network infrastructure, and my team has provided the primary transport simulation evidence for the last two iterations of the strategy.

These have been complex and impactful projects, involving the forecasting of potential travel behaviour three decades into the future for an area the size of the United Kingdom.
For the most recent release, I oversaw the development a new land use and transport interaction (LUTI) model, capable of predicting how the decisions people make about where they live or go to work can be affected by transport network conditions. 

</details>

<details closed>
<summary>Major Road Projects Victoria Strategic Modelling</summary>

For several years I oversaw all strategic transport modelling undertaken by [Major Road Projects Victoria](https://bigbuild.vic.gov.au/about/mtia/major-road-projects-victoria).
My team tackled over twenty different projects during this time, helping the Victorian state government prioritise and assess the business cases for large road projects like bypasses and widenings prior to construction.

Apart from the travel behaviour aspects of this work, I also led the development of new data visualisation tools aimed at facilitating rapid exploration of complex modelling outputs. 
Some of these tools were further adapted to help with historical crash safety analysis and economic appraisal. 

</details>

{{ position(
  org="Australian Road Research Board (ARRB)", 
  date="2013 &mdash; 2017", 
  title="Technical Officer"
) }}

Whilst studying at university I worked at ARRB across the asset management, network operations, and heavy vehicles teams. 
I helped develop pavement degradation models that were used to predict when roads would require maintenance. 
I also led a fun piece of research that led to the abolishment of slower speed limits for trucks on state freeways{% sidenote() %}
[Some people were happy about it](https://twu.asn.au/monash-freeway-truck-speed-limit-trial-ends-sunday/).
{% end %}. 
ARRB was where I got really good at VBA (fortunately or unfortunately).

{{ position(
  org="Monash University Accident Research Centre (MUARC)", 
  date="2016 &mdash; 2017", 
  title="Researcher"
) }}

I helped MUARC investigate the different ways in which freight and other trucking companies approached road safety for their drivers.

# Publications

<small>

* _Infrastructure Victoria_ 2023, Choosing Victoria's future: Strategic transport modelling - urban development scenarios \[[report](https://assets.infrastructurevictoria.com.au/assets/Resources/Arup-Urban-development-scenarios_-strategic-transport-modelling-1.pdf)\].
* _Infrastructure Victoria_ 2021, Victoria's infrastructure strategy 2021-2051:
  * Problem definition modelling \[[report](https://assets.infrastructurevictoria.com.au/assets/Resources/ARUP-Problem-Definition-Modelling-26-October-2020.pdf)\].
  * Strategic modelling outcomes report \[[report](https://assets.infrastructurevictoria.com.au/assets/Resources/ARUP-Strategic-Modelling-rastructure-strategy-2021-2051.pdf)\].
* _Infrastructure Victoria_ 2021, Victorian land use and transport integration model: Architecture overview \[[report](https://www.infrastructurevictoria.com.au/resources/victorian-land-use-and-transport-integration-model-architecture-report)\].
* _Austroads_ 2017, Reassessment of the benefits and impacts of the use of high productivity vehicles on australian highway pavements \[[report](https://austroads.com.au/publications/freight/ap-r541-17)\].
* _Road and Transport Research_ 2017, The impact of minimum licensing age on youth employment \[[paper](https://australasiantransportresearchforum.org.au/wp-content/uploads/2022/03/ATRF2016_Full_papers_resubmission_109.pdf)\].
* _ITS World Congress_ 2016, Measuring excessive congestion delay and travel time reliability cost for multi-modal travels \[[paper](https://nacoe.com.au/wp-content/uploads/2016/10/ITS16_Excessive-delay-and-travel-time-reliability-cost.pdf)\].
* _Austroads_ 2016, National steer axle mass limits \[[report](https://austroads.com.au/publications/freight/ap-r505-16)\].
* _Austroads_ 2016, ITS performance and benchmarking \[[report](https://austroads.com.au/publications/traffic-management/ap-r506-16)\].

</small>

# Education

I hold a _Bachelor of Civil Engineering (Honours)_ and a _Bachelor of Commerce (Finance)_ from Monash University. 
I didn't do computer science or software engineering because the high school version of me thought that I would be able to self-learn that on the side. 
I think things turned out alright.

# This Website
This website is generated with [Zola](https://www.getzola.org/) using a theme I designed.
The typefaces used are PT Serif, <span style="font-family: PT Sans;">PT Sans</span>, and `PT Mono`{% sidenote() %}
All are available on [Google Fonts](https://fonts.google.com/).
{% end %}.
The website icon is a homage to _Harold_, a fat [spotted dove](https://en.wikipedia.org/wiki/Spotted_dove) that visits our window every day for food.
I can't draw so the stylised illustration was generated courtesy of [DALL-E](https://openai.com/dall-e-3), along with all of the artist work that was scraped to get that model working.
