| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [data viz examples](dataviz-examples) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |


# Outline
This project provides an in-depth analysis of the aviation sector, highlighting the trends that are influencing passenger traffic and shaping airline operations. Over the past several years, passenger traffic data reveals clear shifts in airline market share at the airport. Certain carriers have steadily increased their passenger volumes, while others have lost ground, reflecting changes in route strategies, fleet investments, and customer preferences. Visualizing this evolution highlights not only who the dominant players are today but also which airlines are emerging as challengers. For airport authorities, these changes are not just competitive dynamics between airlines — they directly affect slot allocation, terminal usage, and the airport’s long-term relationships with its most important partners.

The dataset chosen shows a compelling story when comparing domestic versus international passenger traffic. Domestic volumes may be recovering more quickly due to strong regional demand, while international routes show a slower but steadier comeback. In some cases, specific international markets — such as Europe or Asia — may be bouncing back faster than others, depending on travel restrictions, fuel costs, or airline strategies. This segmentation between domestic and international flows is critical for airports because the infrastructure, staffing, and regulatory requirements for each category are different.

For instance, in recent years, United Airlines’ market share has shifted notably, showing both growth opportunities and areas of stronger competition compared to other carriers. Its strategy is further reflected in passenger flows: domestic volumes recover quickly with steady regional demand, while international routes rebound more unevenly, depending on markets and global conditions. For airport authorities, these patterns highlight how United’s capacity choices and hub priorities directly influence connectivity and infrastructure needs, from terminal usage to customs and international gate planning.

Through this project, I am interested in exploring why passengers choose to shift their preferences — whether due to factors like route availability, competitive pricing, or operational issues such as denial of confirmed space. By uncovering these patterns, we can better understand how passenger behavior drives broader shifts in the industry and what this means for airport planning.


## Project Structure
> Data wrangling

> Data analysis

> Design

> Storytelling

## Initial sketches

<div class='tableauPlaceholder' id='viz1758854445744' style='position: relative'><noscript>
 <a href='#'><img alt='Sheet 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;fi&#47;fin_proj_17588544348410&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> 
  <param name='site_root' value='' />
  <param name='name' value='fin_proj_17588544348410&#47;Sheet1' />
  <param name='tabs' value='no' />
  <param name='toolbar' value='yes' />
  <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;fi&#47;fin_proj_17588544348410&#47;Sheet1&#47;1.png' /> 
  <param name='animate_transition' value='yes' />
  <param name='display_static_image' value='yes' />
  <param name='display_spinner' value='yes' />
  <param name='display_overlay' value='yes' />
  <param name='display_count' value='yes' />
  <param name='language' value='en-US' />
  <param name='filter' value='publish=yes' />
 </object>
</div>                
 <script type='text/javascript'>                    
  var divElement = document.getElementById('viz1758854445744');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                    
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
 </script>

 Sketch 2

 <div class='tableauPlaceholder' id='viz1758854945008' style='position: relative'><noscript><a href='#'><img alt='Sheet 2 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;fi&#47;fin_proj_17588544348410&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> 
  <param name='embed_code_version' value='3' /> <param name='site_root' value='' />
  <param name='name' value='fin_proj_17588544348410&#47;Sheet2' />
  <param name='tabs' value='no' /><param name='toolbar' value='yes' />
  <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;fi&#47;fin_proj_17588544348410&#47;Sheet2&#47;1.png' /> 
  <param name='animate_transition' value='yes' />
  <param name='display_static_image' value='yes' />
  <param name='display_spinner' value='yes' />
  <param name='display_overlay' value='yes' />
  <param name='display_count' value='yes' />
  <param name='language' value='en-US' />
  <param name='filter' value='publish=yes' />
 </object></div>                
 <script type='text/javascript'>                    
  var divElement = document.getElementById('viz1758854945008');                    
  var vizElement = divElement.getElementsByTagName('object')[0];                   
  vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    
  var scriptElement = document.createElement('script');                    
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    
  vizElement.parentNode.insertBefore(scriptElement, vizElement);                
 </script>

# The data

The three datasets listed below bring complementary strengths:

* Kaggle “Airline Traffic Passenger Statistics” gives you historical passenger volumes and trends by airline (and possibly route types).

* BTS “Popular Air Carrier Statistics” offers U.S.-focused operational and performance metrics: delays, passengers denied confirmed space, load factors, etc.

* OpenSky Network gives you actual flight trajectories (positions, paths) in real time or historically.

By integrating these datasets, we can link airline market share, passenger volumes, and flight routes to uncover insights that help both airlines and airports optimize operations, enhance the passenger experience, and ultimately drive profitability.
 

| Name | URL | Description |
|------|-----|-------------|
|  Airlines Traffic Passenger Statistics    | https://www.kaggle.com/datasets/thedevastator/airlines-traffic-passenger-statistics? |  The Airlines Traffic Passenger Statistics dataset available on Kaggle compiles historical passenger traffic figures for multiple airlines over time. It includes metrics such as total passenger counts (often broken down by year and possibly by domestic vs. international segments)           |
|     BTS  | https://www.bts.gov/topics/airlines-and-airports/quick-links-popular-air-carrier-statistics     |   The Bureau of Transportation Statistics (BTS) “Quick Links to Popular Air Carrier Statistics” page serves as a hub for U.S. aviation data, aggregating key metrics and direct links to datasets on airline and airport performance.           |
|   Open Sky   |   https://opensky-network.org/datasets  |  The OpenSky Network datasets provide real-time and historical aircraft surveillance data, including flight positions, altitude, speed, and identifiers collected from ADS-B and Mode-S sensors. These datasets are widely used by researchers and analysts to study flight paths, airspace usage, delays, and broader trends in global air traffic.|

# Method and medium
> For this project, I’ll be bringing the story to life with Shorthand, weaving data and visuals into a flowing narrative. The visualizations themselves will be powered by Tableau. To keep things sharp and accessible, I’ll also use Datawrapper for crisp, easy-to-read charts that make the key takeaways clear at a glance.

## References
* Good Charts Chapters 5-8
* [hedonometer.org](https://hedonometer.org/)

* [https://nap.nationalacademies.org/read/29145/chapter/12](https://nap.nationalacademies.org/read/29145/chapter/12)

* [https://www.transportation.gov/sites/dot.gov/files/2025-09/August%202025%20ATCR%20-%20June%20Data.pdf](https://www.transportation.gov/sites/dot.gov/files/2025-09/August%202025%20ATCR%20-%20June%20Data.pdf)

## AI acknowledgements
I used AI to help finding the datasets and rephrasing my roughly drafted outline
