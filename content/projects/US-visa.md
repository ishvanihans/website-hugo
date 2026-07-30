---
title: "Analyzing Dark Design Patterns in US visa application"
draft: false
comment: true
area: Information Systems
---

For years, <em><a href=https://www.goodreads.com/book/show/840.The_Design_of_Everyday_Things>The Design of Everyday Things</a></em> by Don Norman sat on my "I'll get to it eventually" reading list. An assignment for my information design course finally gave me the perfect excuse to dive in (and boy, had I been sleeping on it). In this critique, I evaluate the process of applying for a U.S. tourist visa through the lens of three of Norman's core human-centered design principles.

The process of applying for a tourist visa for the United States of America varies by country, so I chose Canada (where I'm currently writing this from) as the context for my analysis. This process is spread across different websites – <a href=https://travel.state.gov/content/travel/en/us-visas.html> The Bureau of Consular Affairs website </a>  for filling an application form, the <a href=https://ca.usembassy.gov/> US Embassy in Canada website </a> for scheduling a visa appointment, and the <a href=https://www.usembassy.gov/> US Embassy website </a> for locating a US embassy in various locations. Because users must navigate across several interconnected websites, this analysis focuses on the information system as a whole rather than on any individual website. Likewise, the three design principles discussed in this critique correspond to different stages of the visa application journey instead of isolated interface features.

Since Canadian citizens do not require a tourist visa to visit the United States, the primary users of this system are likely immigrants, temporary foreign workers, international students, and family members of temporary residents living in Canada. These users are likely to be reasonably comfortable with digital technologies, manage busy schedules, and value an application process that is clear, efficient, and easy to navigate.

## Design principle 1: Learnability 
> Learnability refers to how easily first-time users can understand a system and accomplish their goals without needing extensive instruction. A learnable design helps users form a clear mental model of how the system works, making it easier to predict what to do next.

I chose the principle of learnability to evaluate the first stage of the visa application process: figuring out how to apply. This is the initial stage in the process of applying for the visa and the user’s web search typically lands them on <a href=https://travel.state.gov/content/travel/en/us-visas.html> The Bureau of Consular Affairs website. </a>

<figure>
    <img src="https://ishvanihans.github.io/website-hugo/images/US-visa-images/fig1.png">
    <figcaption>
        <em>Figure 1. How to Apply</em> 
    </figcaption>
</figure>

At first glance, it looks like the page supports learnability well. The webpage makes use of headers, bullet points, and external links to break down information (Figure 1) for the ease of use and paints a comprehensive picture about the entire process. However, there are opportunities to strengthen the visual hierarchy. For example the 'How to Apply' heading could be made more visually distinct through a larger font size or contrasting colour to better separate it from the subsequent steps. Likewise, numbering the actions, such as 'Complete the Online Visa Application' and 'Schedule an Interview' would reinforce that they form a sequential process rather than a list of unrelated links.

When the user clicks on the first link under ‘How to Apply’ (Figure 1) and lands on to the <a href=https://ca.usembassy.gov/> US Embassy in Canada’s website </a> to consult the instructions, the user has to wade through a series of steps (Figure 2) before finding the relevant link for scheduling an interview.  

<figure>
    <img src="https://ishvanihans.github.io/website-hugo/images/US-visa-images/fig2.png">
    <figcaption>
        <em>Figure 2. US Embassy in Canada page</em> 
    </figcaption>
</figure>

Additionally, the multiple websites in this information system are not stylistically consistent with each other. Differences in layout, navigation, and visual design require users to repeatedly reorient themselves as they move between sites, increasing the cognitive effort needed to learn the overall process. While each individual page is reasonably understandable, the fragmented experience reduces the learnability of the system as a whole.


## Design principle 2: Efficiency
> Efficiency refers to how quickly and effortlessly users can complete their goals once they understand how the system works. An efficient design minimizes unnecessary steps, reduces cognitive effort, and enables users to accomplish tasks with minimal time and effort.

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

Overall, this aspect of the information system is not designed to foster efficiency. While some friction is unavoidable given the security and legal requirements of a visa application, several aspects of the interaction – such as the rigid workflow, repeated authentication, and reliance on an externally stored application ID introduce unnecessary effort beyond what the task itself demands.

## Design principle 3: Affordance
> Affordances are the perceived and actual properties of an object that suggest how it can be used. Effective affordances make available actions obvious, helping users understand what interactions are possible without requiring instructions. In digital interfaces, affordances are often communicated through signifiers which are visual cues that indicate the actions users can take.

I chose the principle of affordance to analyse the final stage in the application process – scheduling an interview with the US Embassy in Canada. When the user visits the <a href=https://ais.usvisa-info.com/en-ca> US Embassy in Canada’s website </a> for scheduling an interview, the viewport suggests that there is nothing more to see on the landing page. (Figure 6) 

<figure>
    <img src="https://ishvanihans.github.io/website-hugo/images/US-visa-images/fig6.png">
    <figcaption>
        <em>Figure 6. Landing page for scheduling the visa interview</em> 
    </figcaption>
</figure>

It’s only after the user scrolls down further that they find a signifier that tells them to scroll down for more information (Figure 7). This is a case of misplaced affordance and the user would have benefited if the signifier (the down arrow) was positioned correctly, within the initial viewport to better communicate that the page continues.

<figure>
    <img src="https://ishvanihans.github.io/website-hugo/images/US-visa-images/fig7.png">
    <figcaption>
        <em>Figure 7. Signifier(down arrow) placed below the viewport height</em> 
    </figcaption>
</figure>

Once the user gets past the landing page, they have to create an account to book a visa interview. The website asks the user a series of questions and makes use of familiar screen-based conventions like radio buttons, text areas, and checkboxes (Figures 8 and 9). These interface elements clearly communicate how they should be used and effectively support user interaction.

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

Although the placement of the scrolling signifier could be improved, the remainder of the interface makes effective use of familiar controls that clearly indicate the actions available to users. Therefore, the overall design of this aspect of the information system is good when it comes to the principle of affordance. 

## Conclusion 
To summarise, the design of the process of applying for a tourist visa for the US from Canada is complex and time-consuming but leaves no room for knowledge gaps. The designers should aim for streamlining navigation across websites, reducing repetitive authentication steps, and improving visual cues to make the information system more intuitive and efficient. 





