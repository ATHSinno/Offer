**Thought process 
step1: Analysing data returned from JSON API that presents a bunch of Hotel deals, and identifying needed information to be viewed on user interface. 

step2: Start by building solution which consists of three separated projects and each project considered as "Layer", Solution as mentioned consists of three projects (layers) described below: 

1- Interface Layer (HotelOffers in Solution)
This layer contains user interfaces, events, scripts, and css files and this layer will communicate with bussiness logic layer and will receive user interaction and react to it.
2- Bussiness Logic Layer (HotelOffersBL in Solution)
This layer Contains Entities(classes describe each object type and it's members), also contains bussiness logic classes which are responsible for calling service layer to get JSON and deserialize JSON string into object of entities type in my solution it will be HotelOffer which  is under HotelOffersBL-->Entities in solution
3- Service Layer (HotelOffers in Solution)
This layer is responsible for creating request to JSON API and return JSON string. 

step3: Test project by sending parameters values via user interfaace, and solving problems that appeared and add new features to the solution such as reponsive design by using bootstrap css classes, also add bility to order by choosed column dynamically

----

By building this application i am intended to show my knowledge and ability in my field of expertise including ability to analyse requirements, coding skills using ASP.net/C#, applicaton layers, JSON API consumption and deserializtion,.. 

During this work i had to research and gained knowledge and skills for the following: 
1- Dealing with JSON.
2- Reflection implemetation for dynamic sorting.
3- Dealing with BootStrap and responsive design.

