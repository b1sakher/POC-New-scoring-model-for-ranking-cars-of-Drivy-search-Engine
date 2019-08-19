# POC-New-scoring-model-for-ranking-cars-of-Drivy-search-Engine
The goal is to make a proof of concept of a new ranking algorithm for Drivy's  search engine.

The goal of this test is to make a proof of concept of a new ranking algorithm for Drivy's search engine.

How does the search engine work?
<li> ● Users input an address of search and desired dates and time for their trip. (screenshot) </li>
<li>● Optionally, users can filter the results on various criteria such as the type of car (city,
sedan, commercial vans..), price, options (AC, snow tires..) etc..</li>
<li>● The search engine renders a list of cars. It follows 2 main steps to do so:
<li>○ Filtering: Generate the list of cars that matches the search request: ie. Cars
nearby the address, that are available for the dates of search, and that match the
selected filters. This is not in the scope of this project.</li>
<li>○ Ranking: Order the list based on a score. Current score is computed with a
simple heuristic. The scope of this project is precisely this ranking part.</li></li>
<li>● Anytime the user changes a parameter, filter or page number, a new request is sent to
the search engine and the results refresh.</li>
<li>● Users can then visit different car listings, select cars and eventually book one of them.</li>
