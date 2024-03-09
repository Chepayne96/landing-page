Cheyenne Payne
3/8/24
TOP- Landing Page project

The goal of this project is to make a webpage that looks like, atleast has the same layout, as the example given. This project will teach and help practice the concept of Flexbox in CSS. As well as the practice from styling all the fonts and background colors.

There are four main sections to the example webpage, plus the inclusion of a footer. To start this project I am going to contain all the main elements in the body to one container called "wholeContainer". This way I will be able to quickly stack all five sections (includeing the footer) of this page verticaly. After that each section will get its own container, in order "headContainer", "bodyContainer1", "bodyContainer2", "bodyContainer3", lastly will be "footerContainer". This will allow me more control over the items inside so I can make them stack which ever way I need.

headerContainer- This container houses the title, nav, image, and paragragh. --> flex-col
    div.header --> header and the nav --> flex-row
    div.headbody --> h3, p, button, img --> flex-row

bodyContainer1- This container houses the four image cards that have txt below. --> flex-col
    div.title --> Some random information
    div.cards --> all four card div's --> flex-row
        div.card(1-4) --> img, p --> flex-col

bodyContainer2- This container houses a quote and the person who said the quote. -->flex-col
    div.quote --> p 
    div.source --> p

bodyContainer3- This container houses a banner at the bottom with a button that says "sign up". flex-col
    div.banner --> h6, p, button --> flex-row
        div.action --> h6, p --> flex-col
        div.button --> button 

footerContainer- This container houses copyright for  the images and all other things uses.
    https://pixabay.com/images/search/relaxing/ --> Images 
    https://www.goodreads.com/quotes/tag/bruce-lee#:~:text=Empty%20your%20mind%2C%20be%20formless,and%20it%20becomes%20the%20bottle.              --> Bruce Lee quote