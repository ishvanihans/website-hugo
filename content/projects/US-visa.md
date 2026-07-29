---
title: "Analyzing Dark Design Patterns in US visa application"
draft: false
comment: true
area: Information Systems
---

## Introduction

I analysed the process of applying for a tourist visa for the United States of America. This process is different for each country, so I decided to focus on Canada as my location. This process is spread across different websites, such as <a href=https://travel.state.gov/content/travel/en/us-visas.html> The Bureau of Consular Affairs website </a> (for filling an application form), the US Embassy in Canada website (for scheduling a visa appointment in Canada), and the US Embassy website (for locating a US embassy in various locations). As a result, my analysis is that of an information system and not of a singular website. Similarly, the three design aspects that I have focused on are different stages of the application process instead of features in one particular website. 

Canadians do not need a tourist visa to visit the United States of America. Therefore, the user group is likely composed of immigrants, temporary workers, international students, and families of temporary residents. The user group seems to be sufficiently literate with technology, lead a busy lifestyle, and value recreation. 

## Design principle 1: Learnability 
I chose the principle of learnability to analyse the aspect of ‘finding out how to apply for the visa’. This is the initial stage in the process of applying for the visa and the user’s web search typically lands them on The Bureau of Consular Affairs website.

<figure>
    <img src="https://ishvanihans.github.io/website-hugo/images/US-visa-images/fig1.png">
    <figcaption>
        <em>Figure 1. How to Apply</em> 
    </figcaption>
</figure>


At first glance, the design seems good. The webpage makes use of headers, bullet points, and external links to break down information (Figure 1) for the ease of use and paints a comprehensive picture about the entire process. It would’ve been slightly more useful had the ‘How to Apply’ text been differentiated by another colour or a font size since it is the header and separate from the steps. Alternatively, the two steps ‘Complete the Online Visa Application’ and ‘Schedule an Interview’ could’ve been numbered. 

When the user clicks on the first link under ‘How to Apply’ (Figure 1) and lands on to the US Embassy in Canada’s website to consult the instructions, the user has to wade through a series of steps (Figure 2) before finding the relevant link for scheduling an interview.  

<figure>
    <img src="https://ishvanihans.github.io/website-hugo/images/US-visa-images/fig2.png">
    <figcaption>
        <em>Figure 2. US Embassy in Canada page</em> 
    </figcaption>
</figure>

Additionally, the multiple websites in this information system are not stylistically consistent with each other, which might act as a hindrance to the learnability of the process. As a result, the learnability of this information system is moderate. 

## Design principle 2: Efficiency
I chose the principle of efficiency to study the aspect of ‘filling out the application form’. The information system requires personal details across domains from the user and as such, the process is quite time-consuming. While filling the form, the user cannot enter in their details in any order as they please which might slow down the process. For instance, imagine the user is seamlessly filling the application form in a coffee shop and a question requires them to enter in the details about their driver’s licence which they left at home. Now, the user cannot proceed with the application until they answer the question about their driver’s licence. The website also mentions the estimated time taken to finish the form (Figure 3)

<figure>
    <img src="https://ishvanihans.github.io/website-hugo/images/US-visa-images/fig3.png">
    <figcaption>
        <em>Figure 3. Tourist visa application form</em> 
    </figcaption>
</figure>

Every time the user accesses the website to either start a new application or retrieve an existing one, they have to enter their location, a CAPTCHA, application ID, and security questions (Figures 4 and 5). After every 20 minutes, the session times out so the user would have to login again

<figure>
    <img src="https://ishvanihans.github.io/website-hugo/images/US-visa-images/fig4.png">
    <figcaption>
        <em>Figure 4. Login for tourist visa application form</em> 
    </figcaption>
</figure>

<figure>
    <img src="https://ishvanihans.github.io/website-hugo/images/US-visa-images/fig5.png">
    <figcaption>
        <em>Figure 5. Tourist visa application form security questions</em> 
    </figcaption>
</figure>

Moreover, the application ID (Figure 5) is a system-generated alphanumeric string of characters that the user is prompted to note down for later access (Figure 4). This would likely require the user to refer to an additional resource (such as the notes app on their phone or a physical notebook) and add an extra step to the process of signing in to access the form.  

All of these features impede the efficiency of the information system. However, one saving grace about the webpage is that it automatically saves a section once it’s completed so the user wouldn’t have to restart the lengthy process. 

Overall, this aspect of the information system is not designed to foster efficiency although part of it could be because of the nature of the product itself. 

## Design principle 3: Affordance
I chose the principle of affordance to analyse the final stage in the application process – scheduling an interview with the US Embassy in Canada. When the user visits the US Embassy in Canada’s website for scheduling an interview, the viewport suggests that there is nothing more to see on the landing page. (Figure 6) 

<figure>
    <img src="https://ishvanihans.github.io/website-hugo/images/US-visa-images/fig6.png">
    <figcaption>
        <em>Figure 6. Landing page for scheduling the visa interview</em> 
    </figcaption>
</figure>

It’s only after the user scrolls down further that they find a signifier that tells them to scroll down for more information (Figure 7). This is a case of misplaced affordance and the user would have benefited if the signifier (the down arrow) was positioned correctly.

<figure>
    <img src="https://ishvanihans.github.io/website-hugo/images/US-visa-images/fig7.png">
    <figcaption>
        <em>Figure 7. Signifier(down arrow) placed below the viewport height</em> 
    </figcaption>
</figure>

Once the user gets past the landing page, they have to create an account to book a visa interview. The website asks the user a series of questions and makes use of popular screen-based conventions like radio buttons, text areas, and checkboxes (Figures 8 and 9)

<figure>
    <img src="https://ishvanihans.github.io/website-hugo/images/US-visa-images/fig8.png">
    <figcaption>
        <em>Figure 8. Visa interviewing scheduling page with radio buttons</em> 
    </figcaption>
</figure>

<figure>
    <img src="https://ishvanihans.github.io/website-hugo/images/US-visa-images/fig9.png">
    <figcaption>
        <em>Figure 9. Visa interviewing scheduling page with text area and checkboxes</em> 
    </figcaption>
</figure>

Most of these design features are fitting and afford responses from the user. Therefore, the overall design of this aspect of the information system is good when it comes to the principle of affordance. 

## Conclusion 
To summarise, the design of the process of applying for a tourist visa for the US from Canada is complex and time-consuming but leaves no room for knowledge gaps. The designers should aim for streamlining the information system. 





