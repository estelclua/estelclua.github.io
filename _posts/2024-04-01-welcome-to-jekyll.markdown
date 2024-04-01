---
layout: post
title:  "Our short data story"
date:   2024-04-01 13:19:53 +0200
categories: jekyll update
---

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: 'Palatino', serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }

        .container {
            max-width: 1000px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .title {
            text-align: center;
            font-size: 32px;
            font-weight: bold;
            margin-bottom: 20px;
        }

        .authors {
            text-align: center;
            font-size: 18px;
            margin-bottom: 20px;
        }

        .section-title {
            font-size: 24px;
            font-weight: bold;
            margin-top: 30px;
            margin-bottom: 10px;
        }

        .section-content {
            font-size: 16px;
            line-height: 1.6;
        }

        .column-separator {
            margin-top: 30px;
            border-top: 1px solid #ccc;
            padding-top: 20px;
        }

        .references {
            margin-top: 30px;
        }

        .references ul {
            list-style-type: none;
            padding: 0;
        }

        .references ul li {
            margin-bottom: 10px;
        }

        .references ul li a {
            text-decoration: none;
            color: #007bff;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="title"> Prostitution in San Francisco</div>
    <div class="authors">Estel Clua i Sánchez (s232507), Andrea Matamoros Alonso (s233514), Víctor Sobrino Cusidó (s232773)</div>

    <div class="section-title">Introduction of our case</div>
    <div class="section-content">
        <p>
            San Francisco is a city located in the state of California, surrounded by the Pacific Ocean and the San Francisco Bay, with its very iconic Golden Gate Bridge. Despite being an iconic city in the USA, the crime rate can be quite high. The dataset at disposal for the next series of events is the San Francisco Police Department Incident Reports: Historical 2003 to May 2018 (<a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry/about_data">See the dataset here</a>). In this dataset, the descriptions of several types of crimes are present throughout the years 2003 to May 2018. This data will allow us to develop a <strong>thorough exploration of the crimes related to prostitution</strong> occurring in this period of time. Something interesting to point out from this data is that the term <em>prostitution crimes</em> makes reference to both soliciting and loitering reports. This means that in this police records both incidences for people offering prostitution services and people soliciting them are reflected. In the year 2023, which falls outside the scope for this dataset, loitering was depenalized. This means that sex workers could no longer be arrested for offering their services. This law targeted a vulnerable group of people and worked specially in the detriment of trans-women in the area, whose arrests for this crime were recurrent, as stated by Rachel West, working for the <a href="https://uspros.net/">US Prostitutes Collective</a>.
        </p>
    </div>

    <div class="column-separator"></div>

    <div class="section-title">Context for the first plot in the webpage</div>
    <div class="section-content">
        <p>
            From this representation, we can infer that the number of crimes by prostitution has significantly decreased since the year 2003 to the year 2018. A first decrease can be appreciated from the year 2003 to the year 2006, when it starts to increase once again. Then, the highest crime count for prostitution was reached in July 2008, with a value of 223 cases. After a thorough inspection of events related to this summer in the city, a relevant multitudinary event was found to have taken place in this date. During July 2008, San Francisco hosted the Major League Baseball All-Start Game, an event that brought together the top players from the American Baseball League and the national League for a showcase game. This event took place in the AT&T Park in the city, a baseball stadium home to the San Francisco Giants baseball team and which counts with a capacity for more that 40000 spectators. Such event would have had a positive impact in local economy, enhancing tourism, hotel bookings and spending in local businesses. The other side of this congestion time for the city shows up in the above representation, showcasing the significant increment in prostitution-related police reports in the city at this time. Of course, this event might not be directly related to the increase in prostitution-related crimes for this specific moment in the city, but it certainly is a reason that could have contributed to this increment in cases.
        </p>

         <embed type="text/html" src="/assets/1.jpeg" width="500" height="400">
    </div>

    <div class="column-separator"></div>

    <div class="section-title">Context for the second plot</div>
    <div class="section-content">
        <p>
            In this plot, we can see a heat map with the incidence of prostitution crimes from the year 2003 to May 2018. This representation of the data reflects very well what it is known about sex trafficking and sex workers locations in the city. It is clearly seen that the San Francisco district where prostitution crime reports have been more frequent in the time period that concerns us is in the Mission district, specially known for its Capp Street, were the prostitution activities are mainly located in the city. Hovering over the map, it is reflected that the total number of reports associated to prostitution in this area is 7307, which is very high compared to the rest of the areas. The next bigger value after this is 3945 in the Northern district. This region is adjacent to the Mission district, which could be a reason for why its number of reports due to prostitution are also high compared to the rest of the districts. Despite of this, other districts which share a longer border with the mission district do not have such a high incidence in this crime. This might be because, even though the Capp Street is in the Mission district, it goes up to the north, having the beginning of the street sitting fairly close to the border of the Northern district, something that does not happen with the rest of the areas around it.
        </p>
         <embed type="text/html" src="/2.html" width="500" height="400">
    </div>

    <div class="column-separator"></div>

    <div class="section-title">Context for the third plot</div>
    <div class="section-content">
        <p>
            This plot is an interactive way of seeing when sexual crimes took place. It starts with an overview, where it does not differentiate between hours, so the reader has a holistic view. The plot allows to better visualize if there is a tendency in month or year. Then, it groups the crimes by the different hours, to have a more detailed understanding.
        </p>
        <embed type="text/html" src="/3.html" width="500" height="400">
    </div>

    <div class="column-separator"></div>

    <div class="section-title">Conclusions of our short story</div>
    <div class="section-content">
        <p>
            alg de conclusioo updated btches
        </p>
    </div>

    <div class="column-separator"></div>

    <div class="references">
        <div class="section-title">References</div>
        <ul>
            <li><a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry/about_data">SF Crime Data 2003-2018</a></li>
            <li><a href="https://docs.bokeh.org/en/latest/docs/user_guide/topics/pie.html">Bokeh Pie Charts</a></li>
            <li><a href="https://raw.githubusercontent.com/suneman/socialdata2022/main/files/sfpd.geojson">Map coordinates for Police Districts in San Francisco - geojson</a></li>
            <li><a href="https://localnewsmatters.org/2023/08/17/sex-work-and-the-city-policing-prostitution-in-san-francisco-reflects-evolving-attitudes/">New stories about prostitution in San Francisco</a></li>
        </ul>
    </div>
</div>

</body>
</html>
