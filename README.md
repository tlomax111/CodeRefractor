# Code Refractor Homework

I was asked by my instructors to update code for acessibility purposes and better SEO visibility. I did this by substituting standard <div> attributes for more specific semantic attributes in each section of the web docs 


# Description
This is a website dedicated to SEO optimization, digital Marketing and social Media services. I was asked to update the semantics of the source code for more visibility on web browsers as well as make it more accessible for prospective clients. 


## Semantic Language Update

I added a **<nav>** element where the navigation and logo are placed:

        `<nav class="header">
            <h1>Hori<span class="seo">seo</span>n</h1>
            <div>
                <ul>
                    <li>
                        <a href="#search-engine-optimization">Search Engine Optimization</a>
                    </li>
                    <li>
                        <a href="#online-reputation-management">Online Reputation Management</a>
                    </li>
                    <li>
                        <a href="#social-media-marketing">Social Media Marketing</a>
                    </li>
                </ul>
            </div>
        </nav> `
        
        
I added a **<main>** element to include the sections of the web page where the most important infromation is placed.


        `<main class="content">
            <section class="search-engine-optimization">
                <img src="/Users/tonilomax/Desktop/code/Homework/Homework1/images/online-reputation-management.jpg" alt="someone's desktop work station"
                    class="float-left" />
                <h2>Search Engine Optimization</h2>
                <p>
                    The dominance of mobile internet use means that users are searching for the right business as they
                    travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase
                    your visibility and find the right customers for your business.
                </p>
            </section>
            <section id="online-reputation-management" class="online-reputation-management">
                <img src="/Users/tonilomax/Desktop/code/Homework/Homework1/images/online-reputation-management.jpg" class="float-right"
                    alt="someone sitting at a desk surfing the web" />
                <h2>Online Reputation Management</h2>
                <p>
                    The web is full of opinions, and some of these can be negative. Social media allows anyone with an
                    internet connection to say whatever they want about your business. Online Reputation Management gives
                    you the control over what potential customers see when they search for your business.
                </p>
            </section>
            <section id="social-media-marketing" class="social-media-marketing">
                <img src="/Users/tonilomax/Desktop/code/Homework/Homework1/images/social-media-marketing.jpg" class="float-left"
                    alt="colorful image of people sitting at a desk surrounded by words attributed to social media" />
                <h2>Social Media Marketing</h2>
                <p>
                    Social media continues to have a sizable influence on buying habits. Social media marketing helps you
                    determine which platforms are suited to your brand, using analytics to find the right markets and
                    increase your lead generation.
                </p>
            </section>
        </main>
    `
For each section of information within the **<main>** element I added a **<section>** element.

        `<main class="content">
          <section class="search-engine-optimization">
              <img src="/Users/tonilomax/Desktop/code/Homework/Homework1/images/online-reputation-management.jpg" alt="someone's desktop work station"
                  class="float-left" />
              <h2>Search Engine Optimization</h2>
              <p>
                  The dominance of mobile internet use means that users are searching for the right business as they
                  travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase
                  your visibility and find the right customers for your business.
              </p>
          </section> `

  
For the information in the side bar I placed each section within the **<aside>** element.

    ` <aside class="benefits">`


Each section of information within the side bar is placed within its on **<section>** element.

    <aside class="benefits">
        <section class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="/Users/tonilomax/Desktop/code/Homework/Homework1/images/lead-generation.png"
                alt=" black and white vector image describing work being done turning into cash flow" />
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly
                to your website.
            </p>
        </section>
        <section class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="/Users/tonilomax/Desktop/code/Homework/Homework1/images/brand-awareness.png"
                alt="black and white vectore image of a person with a lightbulb for a head" />
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility
                for your business.
            </p>
        </section>
        <section class="benefit-cost">
            <h3>Cost Management</h3>
            <img src="/Users/tonilomax/Desktop/code/Homework/Homework1/images/cost-management.png"
                alt=" black and white vector image of a gear and coins"></img>
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer
                need to advertise your page.
            </p>
        </section>
    </aside>


The **<div>** that holds content for the footer is replaced by a <footer> element.
        
        <footer class="footer">
            <h2>Made with ❤️️ by Horiseon</h2>
            <p>
                &copy; 2019 Horiseon Social Solution Services, Inc.
            </p>
        </footer>
        
## Images 
Each image recieved its own "alt" description. 

        `<img src="/Users/tonilomax/Desktop/code/Homework/Homework1/images/online-reputation-management.jpg" alt="someone's desktop work station"`


## Formatting 
I formtted the html document for better readability.


# Media Files 

Header Navigation and Header Image
! [ Header and Nav ] 
(/Users/tonilomax/Desktop/Screen Shot 2020-02-02 at 2.33.46 PM.png)

Main and its Sections
! [Main and its Sections]
(/Users/tonilomax/Desktop/Screen Shot 2020-02-02 at 2.34.16 PM.png)

SIde Bar and its Section 
! [Aside]
(/Users/tonilomax/Desktop/Screen Shot 2020-02-02 at 2.34.24 PM.png)


## Link to Application 

[Toni Lomax Homework1 Link]
(https://tlomax111.github.io/Homework1/)





