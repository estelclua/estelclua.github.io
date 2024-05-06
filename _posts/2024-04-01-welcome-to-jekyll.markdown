---
layout: post
title:  "Our Final Project"
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
         <embed type="text/html" src="/preus.jpeg" width="700" height="600" >
         Slide to view the complete figure! (This way it has higher resolution ;) 
    </div>

    <div class="column-separator"></div>

    <div class="section-title">Superhosts</div>
    <div class="section-content">
        <p>
            Superhosts are individuals recognized for their exceptional hospitality and consistent delivery of outstanding guest experiences. The designation of Superhost carries a certain prestige within the Airbnb community, suggesting a higher level of professionalism and service quality.

            <strong>What are super hosts?</strong> <em>Airbnb Superhost</em> is a program designed by Airbnb to identify, promote and reward the most hospitable hosts in the website. They are hosts with more experience who are well rated by travelers and that can be set as en example for the whole Airbnb community. These hosts stand out for being able to offer memorable experiences to travelers staying with them.

            <strong>What are the criteria for an average host to be able to become a superhost?</strong> Airbnb monitors hosts activities 4 times a year (every trimester) and performs evaluations on profiles. These are some prerequisites that might grant a superhost stamp for a host profile: first, they need to succesfully conclude at least 10 booked trips or 3 trips with a total stay of, at least, 100 nights. Then, keep a comment rate for the trips of, at least, 50% from all the bookings. In addition, keep a guest response rate of, at least, 90% from all contacts done for your lodgings. They also need having 0 cancellations (exceptuating the ones included in Major Disruptive Events Policy), and finally, keeping an overall score of 4,8.

            From these information, it can be considered that superhosts might really be able to offer an outstanding experience at their lodgings and, with this post, we aim to study this specific category of host to confirm or deny such statement. In the dataset at hand, we counted on 2325 profiles of superhost for the evaluation, against 16188 regular hosts. This data imbalance roots from the recent designation of the superhost term.

            Le'ts take a look at the localizations of the hosts and superhosts around the city of Copenhagen. Notice the density of superhosts is much reduced compared to regular hosts, since this highlighted role is, as we mentioned before, of recent creation in the platform.
        </p>
             <div class="section-title">Map for Superhosts locations</div>
            <embed type="text/html" src="/maphosts.html" width="700" height="500" >
            <div class="section-title">Map for non-Superhosts locations</div>
            <embed type="text/html" src="/mapnohosts.html" width="700" height="500" >
        

    </div>

<div class="section-content">
 <div class="column-separator"></div>
        <p>
            Independently from the opinion Airbnb has from their Superhosts, guests' opinions might result more valuable for a lodge-seeker. In this interactive plot, you will be able to explore and tell the difference between the number of reviews regular hosts and superhosts receive. We can notice that superhosts have less review but, since this is an absolute count and there are less superhosts in our data set, it makes sense for the data to appear like so.

        </p>
            <embed type="text/html" src="/number_host_reviews.html" width="500" height="400" >
        

    </div>


    <div class="column-separator"></div>

    <div class="section-title">Response time</div>
    <div class="section-content">
        <p>
            Something that we like when we plan a trip is having everything well organized, including where we will stay during the trip. Being a able to rent a place within minutes is something at our reach with the Airbnb chats with their hosts. In the polar graphs above, we can appreciate that Superhost response time is notably faster than a regular host response. This strengthens the myth surrounding the quality of stay provided this type of hosts. 
        </p>
         <embed type="text/html" src="/pies.jpeg" width="700" height="400">

<p>
         But Superhosts do not only have to reply fast, but they also must reply to almost everybody requesting hosting in their facilities, even if this answer might end up being negative. In the bar plot below, it is shown that the response rate for Superhosts is mostly 100%. For regular hosts, it does not reach 80%, but it still can be considered to be high enough. Something interesting is that a certain amoun of the Superhosts have a response rate smaller than 50%, meaning that in the next evaluation done by Airbnb, they might loose their Superhost credential, since this value is not up to the expectations of the platform.
</p>
         <embed type="text/html" src="/barras.jpeg" width="700" height="400">
    </div>

 <div class="column-separator"></div>

    <div class="section-title">Since when are hosts and super hosts, hosts?</div>
    <div class="section-content">
        <p>
            With the violin plot below, it can be seen what time did a host become a host for the first time. The plot has the most recent dates at the bottom and the most ancient ones on the top. At first sight, it is clear how around 2015, lots of new hosts came to the airbnb platform. The graph peaks again in 2022. Even though both sides of the figure look very simiilar, with deep inspection it can be seen how the green tendency is always ahead of the red one, meaning that superhosts became host before to their relative comparison. Is is important to mention that both sides are equally large, but that does not mean the number of super hosts is equal to the number of regular hosts. The amount of super hosts is smaller.

            Relevant insights that can be obtained from the plot are that the inscription of new hosts follow a specific curve (the reason behind that curve is unknown with the information avaiolable, except for 2020 and 2021 sicne the reasons are clearly the pandemic), and that super hosts seem to be the precursors when new hosts sign up to airbnb.
        </p>
        <embed type="text/html" src="/violin.pdf" width="700" height="500">
    </div>
   
    <div class="section-title">How many listings do hosts have?</div>
    <div class="section-content">
        <p>
            With this plot it is evidenced that the vaste majority of hosts only have one listing, and that having 2 or 3 listings is quite popular. From there on the count drops to lower values, since the economic resources required to have many listings are much bigger. The histogram above reveals an insight that may seem contradictory. It can be seen that hosts with 7 or more listings are mostly regular hosts, while it would make sense that these people where super hosts. 

        </p>
        <embed type="text/html" src="/listings.html" width="850" height="700">

    </div>

    <div class="section-title">Can people instantly book listings?</div>
    <div class="section-content">
        <p>
            Here it can be seen how there is no apparent difference between hosts and super hosts for what the instat booking does. There are more rgular hosts that accept instant bookings, but that is because there are more regular hosts. If the percentage is taken into account, it is very similar. Also, it would make sense that super hosts allowed less instant bookings, since they are more wanted by tenants and therfore more booked thoroughout the year.

        </p>
        <embed type="text/html" src="/instant.pdf" width="710" height="540">

    </div>

   <div class="column-separator"></div>

    <div class="section-content">
        <p>
            Something to comtemplate, if not the most important aspect, is the pricing difference between regular hosts and superhosts. Superhosts have a mean pricing per night of 1258.28 kr and regular hosts have a mean pricing per night of 1239.61 kr. As we can see, this difference is not significant at all and, in the next jitter plot, we are able to appreaciate the difference in ratings per category, where Superhosts do not have very bad or bad ratings, only one avergae rating, and the rest of them have good and very good ratings, meaning that the scoring of superhosts is much higher than for regular hosts.
        <embed type="text/html" src="/last.jpeg" width="700" height="550">
        Slide to view the complete figure! (This way it has higher resolution ;)
        </p>
    
    </div>

    

   <div class="column-separator"></div>
    <div class="section-title">Conclusions</div>
    <div class="section-content">
        <p>
            All in all, our exploration of the categorizations between hosts and superhosts within the realm of Airbnb accommodations in Copenhagen sheds light on the differences that can significantly impact one's lodging experience. Through our analysis, it becomes evident that superhosts offer a heightened level of reliability and hospitality, thus rendering them a favorable choice for discerning travelers. This, of course, without a significant price raise, for which giving a try to this type of host should be quite recommendable. Therefore, while both categories present unique offerings, the commitment to excellence demonstrated by superhosts suggests that opting for their accommodations may yield a more enriching stay in the Danish capital. Therefore, when choosing from different lodging options for your next visit to Copenhagen, considering a superhost may indeed prove to be a prudent decision, potentially elevating your experience to new heights of satisfaction and enjoyment.

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
