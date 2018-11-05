# BLISS
Food donation web app that searches nearby NGOs  and helps to connect to them for food donation.
<h2>WHAT IS WRONG</h2>
<p>Most of the food we waste is, in fact, fit for human consumption. Indians waste as much food as
the whole of United Kingdom consumes.
Supermarkets, greengrocers, bakers, our homes, farms are dumping out a large amount of food.
These food items are then locked in a truck and dumped in landfills. Surely, we can do more
sensible to food than to waste it.
When we talk about food waste we throw away we don’t talk about rotten stuff, we are talking
about good fresh food that is being wasted on a colossal scale. There always will be a waste. I am
not so unrealistic that I think we can live in a waste-free world.
Weddings, canteens, hotels, social and family functions, households throw out so much food. One
such colossal waste is discarding food which is edible because they are of wrong shape or size. Ex:
Potatoes that are of wrong shape or size or oranges that have a spot on its peel are discarded by the
supermarkets and it goes into bins.
According to the United Nations Development Programme, up to 40% of the food produced in
India is wasted. This includes farm waste, transportation waste, household level, waste from
supermarkets due to the wrong shape, size etc.
You know India is the second largest producer of food crops but it’s highly ironical that the largest
hunger population resides in India. About 7 million children died in 2015 because of
hunger/malnutrition. 20 crore Indians sleep hungry on any given night.
India is home to the largest undernourished population in the world. About 14.5% of our
population is undernourished. 1 in every 4 children is malnourished. 3000 children in India die
every day from diet-related issues. Hunger remains the number one cause of death not only in
India but the entire world. AIDS, cancer etc. follows.
So, we are observing that on one hand there is a large amount of food being wasted but on the
other hand, there are millions who die every year due to hunger.</p>
<h2>WHAT IS BEING DONE</h2>
<p>There are a large number of NGOs working in this field by collecting the excess food from
marriages, functions, public gatherings or individuals who have excess food and are distributing it
to the poor or orphanages and old age homes.
Let me ask you a question how many NGOs do you know in your area who do
such a thing and how can you contact them? Maybe you know a few of them or not a single one.
So, I will give you a list of food charities, NGOs and will also show you what is the problem.<br>
  <ol>
    <li>Feeding India – Delhi + 16 other cities. The organization can be contacted on 098711 78810.</li>
    <li>Annakshetra – Jaipur. To contact the organization, call +91-9001295293, 0141-3221267.</li>
    <li>Robin Hood Army – Delhi/NCR + 8 cities.</li>
    </ol>
There are many more organizations which can be contacted on their telephone numbers. Some of
them have their websites as well but we don’t even know their names so how can we contact
them?</p>
<h2>WHAT WE PROPOSE</h2>
You all must have heard of Trivago. It is not a hotel website but a website that searches for a hotel
in a particular area and compares them and helps you contact them without taking much pain. Our
website is quite similar. If you want to donate you don’t have to search for an NGO in your area
and then contact them. We will do all that for you. You just have to visit our website and pick a
date and time and if you wish you can see the NGOs active in your area and choose your preferred
NGO.
Next question coming to your mind would be why NGOs will get registered to our website? Well,
NGOs are in a fight against hunger and food waste and if they could find a helping hand they
would surely take it.
<h2>WHAT WE DO</h2>
<h3>Summary:</h3>
<p>An organization which wishes to accept donation requests and distributes it registers itself on our
website. In this step, they provide their address and other contact details.
Now we have a network of organizations.
Now anyone ranging from restaurants, supermarkets, and other common people can make
donation requests. They specify their address. We calculate the distance and time required
between user’s location and all the registered organizations in the city and sort them according to
the distance. With this, we also show the location of both user and NGO on a map. Here the user
can select his/her preferred organization. Once the user selects an organization, the NGO gets a
notification to either accept it or reject it. If the NGO excepts it, the work is done and both user
and NGO receive a mail regarding each other's contact details. If the NGO declines it, the request
made by the user is treated as a floating one.
Now through the services portal specifically created by us for the organizations, NGOs can select
the user according to its convenience. This way we are ensuring higher chances for the donation
request to be successful.</p>
<h3Detailed Working :</h3>
<ul>
  <li><b>Registration :</b></li>
<p>New NGOs will provide their e-mail ID on which an OTP will be sent to verify credibility*- of the
e-mail ID and also e-mail will be searched in the database to restrict multiple registrations on our
website through same e-mail ID.
Once the e-mail has been verified the user will be redirected to the registration page on which he
can provide details about his organization. Then the data provided by the user is verified through
PHP (with the help of regex) for mistakes (like the phone number is of 10 digits, the password
should be strong, the address should be valid etc.)
From a security point of view, the registration page can’t be opened directly without going through
the e-mail verification stage. If anyone tries to open the registration page directly then he/she will
  be redirected to the e-mail verification page.</p>
  <li><b>Manage your account :</b></li>
<p>The user will be redirected to a login page where he can log in by providing his registered e-mail
and password. For increased security captcha is also included. If the password matches the user is
redirected to a management portal. Again, the portal can’t be opened directly without going
through the login page.
  <li><b>Forgot password:</b></li><p> On the login, page user can find a link to forget password page. On clicking it
a new page opens which demands registered e-mail ID of the user. If the e-mail ID is registered in
  our database then a temporary password is sent to the user e-mail ID.</p>
  <h3>NGO Portal provides three services :</h3>
  <ol>
  <li><b>Pending/ Confirmed Requests-</b> Here the registered NGOs can see the pending requests of the
donors who choose that NGO as their preferred NGO and can confirm or reject the request.
Also, all the accepted requests by the NGO is displayed in another section of the page along with
  the details of the user.</li>
  <li><b>Floating Requests- </b>In this section, all the requests which are rejected by the preferred NGO of
the user is displayed and are open to all NGO to get confirmed thus increasing the chances of the
  food to be utilized.</li>
  <li><b>Update Information-</b> For organizations that wish to update their information in our database.</li>
  </ol>
  </ul>
  <ul>
  <li><b>List of connected NGOs :</b></li>
<p>Here the donors can find all the NGOs connected to our platform sorted according to the city in
which they are active along with their ratings by the previous donors which help the donor to
  choose his/her preferred NGO to donate.</p>
  <li><b>Donate :</b></li>
<p>If you want to donate to any NGO which are connected to our platform then you have to click on
“donate” option. After clicking you will be redirected to a page which will ask you for the address
details with address autocomplete feature. After clicking submit button, the entered details will be
checked for credibility and then you will be redirected to a page which will show you NGO near
you sorted according to the distance from you. You can click on “click to see location” to see the
map and the route between you and the NGO. After choosing the preferred NGO you can click on
the option “pick date and time” and confirm donation time along with your contact details.
After, that the preferred NGO of the user is sent an e-mail having details of the donation and
asking for the confirmation. Also, the same request will be displayed on the NGO portal’s
“Pending Requests” option. If the NGO choose “Yes” then a mail is sent to both donor and the
NGO having details of each other contact details and date of donation and the information is also
displayed in “Confirmed Requests” option. If the NGO chooses “No” then the donation is
displayed in the “Floating Requests” page and visible to all NGOs in the city so that any NGO in
the city can confirm it. If any NGO confirms then a mail is sent to both of them having details of
  each other contact details and date of donation.</p>
  <li><b>Feedback :</b></li>
Basically, there are two types of feedback forms :
  <ol>
<li>After the successful donation by the user, a mail will be sent to the user having a link to the
feedback form where they will rate the NGO which will help future donors to choose their
  preferred NGO. We have used delayed mail implemented using a cronjob to schedule it.</li>
<li>Another feedback form is directly accessible from the front page of our website. It is where all
the users and NGOs will rate our services. It shows the average rating of our website along with
comments by the recent users. We have implemented infinite scrolling feature so all the comments
  are loaded as the user scrolls down the comment section.</li>
  </ol>
    <h3>APIs, software, and tools used</h3>
  <ol>
<li>Distance Matrix API- Finding distance and time required to travel between an origin and
  multiple destinations to help NGOs to choose donors and vice-versa.</li>
    <li>Sendgrid API- E-mail verification through OTP and sending important e-mails.</li>
<li>Geolocation- Locating NGO and users on a map and then sorting the results to find nearest
  donor or nearest NGO.</li>
<li>Cronjob- We have used cronjob to schedule delayed mails for feedback by the donors once the
donation is complete in which users give ratings to the NGO donated which helps future users to
  decide their preferred NGO.<br>
  Also, it is used to delete records from the table when it is out of date.</li>
<li>Address autocomplete API- To verify that a correct address is a feed to the address of both the
  user and NGO</li>
    <li>Microsoft Azure to deploy the website</li>
    <li>The user interface to pick date and time.</li>
  </ol>
</ul>
<h3>Web Stack</h3>
<h4>Frontend</h4>
<ol>
  <li>HTML</li>
  <li>CSS</li>
  <li>Javascript (Jquery)</li>
  </ol>
  <p><h4>Backend</h4> PHP</p>
  <p><span><h4>Database</h4></span> SQL Server</p>
