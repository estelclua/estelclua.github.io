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
    <div class="title"> Airbnb superhosts in Copenhagen - are they the real deal?</div>
    <div class="authors">Estel Clua i Sánchez (s232507), Andrea Matamoros Alonso (s233514), Víctor Sobrino Cusidó (s232773)</div>

    <div class="section-title">Introduction</div>
    <div class="section-content">
        <p>

        Airbnb is a well-known platform where hosts offer lodging to tourists and travelers. In the city of <strong>Copenhagen</strong>, there is a great number of listings available for those seeking a place to stay during their visit to this vibrant city. During this post, we want to offer you the possibility of exploring something that is often misregarded: the hosts.
       
        In Copenhagen, there is a large number of listings, more 18000. In the map below, you can see their distribution along the city.

        </p>
         <embed type="text/html" src="/map.html" width="700" height="500" >

        <p>
        The most expensive neighbourhood is Indre By, which corresponds to Copenhagen city center, inside of Copenhagen metropolitan area. This price difference is obvious, since it is much more convenient for toursits to be hosted right in the city center, to be as close as possible to all the touristy attractions and to avoid using public transport, which can become one of the main expenses when travelling around Copenhagen. Despite of this, some other neighbourhoods, such as Frederiksberg and Norrebro, could also be good choices for your stay in the city.

        Norrebro is a bustling part of Copenhagen, a multicultural neighbourhood full of places with quite the charm and very interesting cafés, whose popularity has grown over the years among university students and alternative crowds. On the other hand, Frederiskberg is a much more quiet part of the city, due to its residential nature. Here, you can find some interesting place,s such as the Zoo, Frederiskberg Palace and Gardens and even an underground museum, Cisternerne.

        Taking into account all of the neighbourhoods, the mean price per night stay is of $1314.37. It seems quite high right? Well, there might be a certain type of host, called Superhost, that might be deserving of such high rates for their lodgings around the city. Let us explain why:

          
        </p>
         <embed type="text/html" src="/preus.jpeg" width="700" height="500" >
    </div>

    <div class="column-separator"></div>

    <div class="section-title">Superhosts</div>
    <div class="section-content">
        <p>
            Superhosts are individuals recognized for their exceptional hospitality and consistent delivery of outstanding guest experiences. The designation of Superhost carries a certain prestige within the Airbnb community, suggesting a higher level of professionalism and service quality.

            <strong>What are super hosts?</strong> <em>Airbnb Superhost</em> is a program designed by Airbnb to identify, promote and reward the most hospitable hosts in the website. They are hosts with more experience who are well rated by travelers and that can be set as en example for the whole Airbnb community. These hosts stand out for being able to offer memorable experiences to travelers staying with them.

            <strong>What are the criteria for an average host to be able to become a superhost?</strong> Airbnb monitors hosts activities 4 times a year (every trimester) and performs evaluations on profiles. These are some prerequisites that might grant a superhost stamp for a host profile:

            - Succesfully conclude at least 10 booked trips or 3 trips with a total stay of, at least, 100 nights.
            - Keep a comment rate for the trips of, at least, 50% from all the bookings.
            - Keep a guest response rate of, at least, 90% from all contacts done for your lodgings.
            - Having 0 cancellations (exceptuating the ones included in Major Disruptive Events Policy).
            - Keeping an overall score of 4,8.

            From these information, it can be considered that superhosts might really be able to offer an outstanding experience at their lodgings and, with this post, we aim to study this specific category of host to confirm or deny such statement. In the dataset at hand, we counted on 2325 profiles of superhost for the evaluation, against 16188 regular hosts. This data imbalance roots from the recent designation of the superhost term.
        </p>

    </div>

    <div class="column-separator"></div>

    <div class="section-title">Response time</div>
    <div class="section-content">
        <p>
            Something that we like when we plan a trip is having everything well organized, including where we will stay during the trip. Being a able to rent a place within minutes is something at our reach with the Airbnb chats with their hosts. In the polar graphs above, we can appreciate that Superhost response time is notably faster than a regular host response. This strengthens the myth surrounding the quality of stay provided this type of hosts. But Superhosts do not only have to reply fast, but they also must reply to almost everybody requesting hosting in their facilities, even if this answer might end up being negative. In the bar plot below, it is shown that the response rate for Superhosts is mostly 100%. For regular hosts, it does not reach 80%, but it still can be considered to be high enough. Something interesting is that a certain amoun of the Superhosts have a response rate smaller than 50%, meaning that in the next evaluation done by Airbnb, they might loose their Superhost credential, since this value is not up to the expectations of the platform.
        </p>
         <embed type="text/html" src="/pies.jpeg" width="700" height="400">
         <embed type="text/html" src="/barras.jpeg" width="700" height="400">
    </div>

    <div class="column-separator"></div>

    <div class="section-title">Context for the third plot</div>
    <div class="section-content">
        <p>
            Independently from the opinion Airbnb has from their Superhosts, guests' opinions might result more valuable for a lodge-seeker. In this interactive plot, you will be able to explore and tell the difference between the number of reviews regular hosts and superhosts receive. We can notice that superhosts have less review but, since this is an absolute count and there are less superhosts in our data set, it makes sense for the data to appear like so.

        </p>
        <embed type="text/html" src="/reviews.html" width="700" height="700">
Slide to view the complete figure! (This way it has higher resolution ;) )
    </div>

    <div class="column-separator"></div>

    <div class="section-title">Conclusions of our short story</div>
    <div class="section-content">
        <p>
            After this deeper analysis of the SF crime reports, and specifically the prostitution crimes, a better understanding of the city has been achieved. While one could think that prositution is all over the city, it has been seen how it is concentrated in a specific zone of the city, and even more in a specific street called Capp Street. It has also been seen how the city is subject to political and social events, such as a final game or the state proposition of the general elections, acting in different directions depending on the event. Finally, it is relieving to see this kind of crimes decrease over time.
        </p>
    </div>

    <div class="column-separator"></div>

    <div class="references">
        <div class="section-title">References</div>
        <ul>
            <li><a href="https://data.sfgov.org/Public-Safety/Police-Department-Incident-Reports-Historical-2003/tmnf-yvry/about_data">SF Crime Data. Police Department Incident Reports: Historical 2003 to May 2018</a></li>
            <li><a href="https://uspros.net/">US PROS COllective</a></li>
	<li><a href="https://sfelections.org/results/20121106/index.php">Results of state propositions</a></li>
	<li><a href="https://lao.ca.gov/ballot/2012/35_11_2012.aspx">Explanation of proposition</a></li>
            <li><a href="https://abc7news.com/san-francisco-sex-workers-prostitution-neighbors-speak-out-capp-street-sf/12764865/">EXCLUSIVE: SF residents say this street has turned into 'Las Vegas Strip' with alleged sex workers</a></li>
            <li><a href="https://www.sfchronicle.com/sf/article/sex-workers-capp-street-17774301.php">This is the brutal reality for sex workers on S.F.'s Capp Street</a></li>
        </ul>
    </div>
</div>

</body>
</html>
