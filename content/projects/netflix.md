---
title: "Analyzing Dark Design Patterns in Netflix's Subscription Process"
draft: false
area: User Experience Analysis
---
><a href="https://deceptive.design/">Deceptive design</a> patterns or dark patterns are design choices that manipulate or mislead users into taking actions they might not otherwise choose. Instead of prioritizing the user's goals, these patterns often exploit cognitive biases, learned behaviours, and familiar interface conventions to benefit the service provider—such as encouraging a purchase, obtaining consent, or making it difficult to cancel a service. In 2010, User Experience Designer Harry Brignull started [a pattern library]([url](https://deceptive.design/types/)) with the specific goal of naming and shaming deceptive user interfaces. 

For this analysis, I used Harry Brignull's [deceptive design pattern library]([url](https://deceptive.design/types/)) to examine deceptive design patterns in Netflix's subscription process, focusing particularly on how <a href=https://deceptive.design/book/contents/chapter-16/>misdirection</a> influences users' choices as they navigate pricing and sign-up. I also show how these deceptive patterns violate some foundational design principles. 

Netflix is built mainly for entertainment so its intended user group is people who have some spare time in their lives designated for leisure. This could range from students, working individuals, retirees, and anyone seeking on-demand media content. 

<figure>
    <img src="https://ishvanihans.github.io/website-hugo/images/netflix-images/fig1.png">
    <figcaption>
        <em>Figure 1. Pricing for prospective users</em> 
    </figcaption>
</figure>

When prospective users access Netflix for the first time, they cannot view the various pricing plans without entering their email IDs and signing up for Netflix. The only pricing information they can see is the range of the plans in the FAQs section (Figure 1). So, when the user has no option but to sign up to see the pricing plans(a ‘[Forced Option]([url](https://deceptive.design/types/forced-action/))’ dark design strategy), that’s when the misdirection begins (Figure 2). 

<figure>
    <img src="https://ishvanihans.github.io/website-hugo/images/netflix-images/fig2.png">
    <figcaption>
        <em>Figure 2. Sign up form</em> 
    </figcaption>
</figure>

There is an unchecked box at the sign up stage (Figure 2) for email communication. If the user proceeds to click the ‘Next’ button without checking the box, they will start receiving marketing emails from Netflix. This is a [‘trick wording’]([url](https://deceptive.design/types/trick-wording/)) and violates the design principle of ‘mapping’ because the correlation between the control and effect is flawed. The action of checking something usually implies an affirmative, so a checkmark does not correctly map to a “do not” statement. Moreover, the design convention of subscribing to an email list involves checking the box instead of leaving it unchecked. Here, Netflix plays on the user’s memory of the design convention of mailing lists and thereby also breaks the design principle of ‘memorability’. The dark design strategy of aesthetic manipulation is used to achieve this misdirection.

<figure>
    <img src="https://ishvanihans.github.io/website-hugo/images/netflix-images/fig3.png">
    <figcaption>
        <em>Figure 3. Pricing plans</em> 
    </figcaption>
</figure>

After the user provides their email ID and signs up, they can finally view the pricing plan in detail (Figure 3). However, once again there is misdirection because the design intentionally wants the user to focus on specific information. To start with, the most expensive pricing plan is not only the default selection (Figure 3), but the other two pricing plans have a grey overlay, which can be misinterpreted by the user as a ‘gray out’, a well-known design convention that indicates unavailability. But that’s not where the misrepresentation ends. When the user clicks on the button ‘See All Plans’ (Figure 3), a fourth pricing plan emerges that was previously concealed (Figure 4). 

<figure>
    <img src="https://ishvanihans.github.io/website-hugo/images/netflix-images/fig4.png">
    <figcaption>
        <em>Figure 4. All pricing plans</em> 
    </figcaption>
</figure>

If one starts to compare all the features in the four pricing plans (Figure 4), it becomes clear that the concealed option likely yields the most favourable return on investment. This kind of misdirection by concealing information prevents the user from accessing the information they might need, which breaks the design principle of ‘effectiveness’. The dark design strategies that gave rise to the misdirection here are ‘preselection’, 'aesthetic manipulation’, and ‘hidden information’. 

At the end of the day, Netflix is a proprietary streaming service that wants to maximise its profit by deploying the aforementioned dark design strategies. However, this might lead to unintended and unethical consequences for the user. For example, if the user checks the box to receive promotional emails from Netflix (Figure 2), they might risk getting overwhelmed by information which might lead to burn out and affect their performance at work. Similarly, a film studies student who needs Netflix to download movies for their school work might miss out on the ‘Basic’ tier plan (Figure 4), if they do not click on the ‘See All Plans’ button (Figure 3). This may lead to financial stress, which can impact the student’s studies and wellbeing. 

## Redesign 

In order to eliminate deceptive design patterns in the subscription task flow, I first got rid of the forced sign up action to view the pricing plans (Figure 6). This would ensure that the design is effective to use because it is capable of allowing users to access the information they need. Next, I added a ‘Terms & Conditions’ checkbox to the sign up form (Figure 5), which is unchecked by default but is checked by the user in Figure 5 for display purposes. I also changed the language of checkbox statements to get rid of double negatives and confusion. This ensures the design principle of mapping. The addition of the ‘Terms & Conditions’ checkbox creates space for mindfulness and lets the user think twice before clicking on both the checkboxes. 

<figure>
    <img src="https://ishvanihans.github.io/website-hugo/images/netflix-images/fig5.png">
    <figcaption>
        <em>Figure 5. Redesigned sign up</em> 
    </figcaption>
</figure>

<figure>
    <img src="https://ishvanihans.github.io/website-hugo/images/netflix-images/fig6.png">
    <figcaption>
        <em>Figure 6. Redesigned pricing plan</em> 
    </figcaption>
</figure>

Finally, the redesigned pricing plan page shows all pricing plans in one go and has the most favourable pricing plan pre-selected. It also has a ‘Recommended’ tag that shows why a certain option is pre-selected. This restores the design principle of ‘Effectiveness’ because it shows the users the necessary information to do their task.

In conclusion, the redesign eliminates unintended consequences and is ethically correct because it gives users control, the ability to make sound decisions, and takes into consideration the socio-economic status of its users. 

