# Assignment 01: Heuristic Evaluation
Rachel “Ray” Hsiao | DH 110: User Experience and Design | Fall 2022

## Tentative title: seagood seafood
I’ve always liked learning more about the natural world, and I developed an interest in marine conservation through participating in the National Ocean Sciences Bowl academic competition in high school. I don’t have many opportunities to explore this through my major, so when I saw “Life Under Water” was one of the UN Sustainable Development Goals, I was excited to choose it. 

I thought of focusing on seafood because overfishing is by far the greatest danger to marine organism populations. I want to help people make sustainable choices when they are out shopping for seafood to cook. I remember that the Monterey Bay Aquarium had an activity in which you guess which seafood option is the best for the environment, so I knew that tools with similar goals to mine already existed. 

I will conduct a heuristic evaluation of two such websites in this assignment using usability heuristics and severity ratings.

### [10 Usability Heuristics for User Interface Design](https://www.nngroup.com/articles/ten-usability-heuristics/)
| # | Heuristic | Description |
| - | - | - |
| 1 | Visibility of system status | Inform user what is happening and provide feedback for actions |
| 2 | Match between system and the real world | Use language familiar to the user and design analagously to the real world |
| 3 | User control and freedom | Allow users to make mistakes and undo and redo actions easily |
| 4 | Consistency and standards | Design based on well-known standards and to have internal consistency |
| 5 | Error prevention | Reduce likelihood user makes mistakes |
| 6 | Recognition rather than recall | Provide references for user to reduce cognitive load |
| 7 | Flexibility and efficiency of use | Provide several avenues to complete the same task |
| 8 | Aesthetic and minimalist design | Focus design around what is relevant to the user |
| 9 | Help users recognize, diagnose, and recover from errors | Identify problems and tell users how to solve them |
| 10 | Help and documentation | Provide information to help user complete task (ideally not needed) |

### [Severity Ratings for Usability Problems](https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/)
| Rating | Description |
| - | - |
| 1 | Cosmetic problem, fix only if time allows for it |
| 2 | Minor usability problem, low priority |
| 3 | Major usability problem, high priority |


## Competitor 1: [Monterey Bay Aquarium Seafood Watch](https://www.seafoodwatch.org/)
My first competitor site is [Seafood Watch](https://www.seafoodwatch.org/), a sustainable seafood advisory list with a search feature. It is a program run by the Monterey Bay Aquarium that reviews the impact of fisheries and aquaculture on marine and freshwater ecosystems todevelop a scoring called the Seafood Watch Recommendation.

Using the search feature takes the user to the Recommendations page. Users can filter their searches with criteria like species, harvest method, country/region, body of water, and recommendation level. The website is extremely informative and stylish, but it is difficult to use to find the desired information.
![Seafood Watch Recommendations page](https://user-images.githubusercontent.com/40257341/193736371-6e53f995-38d9-41bd-8c6d-c5b4b25f86af.png)

### Heuristic Evaluation

#### 1. Visibility of System Status

**Evalution:** What tab you're on is indicated by a blue line at the bottom of the associated button in the menu bar. However, this is not very apparent since the line is not very thick and blends in with the webpage below.\
**Recommendation:** Change the entire button to blue so it obviously contrasts with the other buttons in the menu bar.\
**Severity level:** 1
![image](https://user-images.githubusercontent.com/40257341/193740906-1e6fa5d6-975c-4161-8f89-abe589773a05.png)

**Evalution:** The website displays a loading circle icon after the user clicks something.\
**Recommendation:** The color of the loading icon doesn't match the prominent colors on the site, so I would change it to one of those colors instead.\
**Severity level:** 1
![image](https://user-images.githubusercontent.com/40257341/193742430-9a3e3be4-f35a-449a-bcfe-7344fa3712c6.png)

#### 2. Match between system and the real world

**Evaluation:** The menu bar is categorized into "Recommendations," "Seafood Basics," "For Business," "Our Projects," and "Collaborations." These terms are easy to understand on their own. However, the subcategories for "Recommendations" don't seem like they all belong there. For example, "Join the movement" is out of place.\
**Recommendation:** Add a separate tab for getting involved instead of nesting it under "Recommendations."\
**Severity level:** 1
![image](https://user-images.githubusercontent.com/40257341/193950530-83dbb127-2357-4773-950a-0f264fae1aa9.png)

**Evaluation:** For species without members in the "avoid" category, the text under "AVOID" is "We hope you enjoy the [species name]!" which is very confusing. I found that there weren't any species in the "avoid" category by trying to filter for "avoid" and getting no results.\
**Recommendation:** State cleary that there aren't examples to avoid.\
**Severity level:** 3
![image](https://user-images.githubusercontent.com/40257341/193986366-11cc5f37-efe5-4cd3-83ad-18c5960ba07f.png)
![image](https://user-images.githubusercontent.com/40257341/193986405-0397c964-3fcf-46b1-9425-bf63d038ef1b.png)

#### 3. User control and freedom

**Evaluation:** The main actions users would take is making searches. There aren't really consequences for making an incorrect search -- the user can easily search again. "Undo" doesn't really make sense in this context. The other mistake users could make is misclick and go to a page they weren't intending to, but the browser back 1 page button is sufficient for that.\
**Recommendation:** N/A\
**Severity level:** N/A

#### 4. Consistency and standards
**Evaluation:** The home page displays the recommendations search feature prominently. On the actual recommendations page, the recommendations search works a little differently from the one on the home page -- it has a drop-down menu with both the option to input your own search or choosing from "popular" selections.\
**Recommendation:** Rather than have a different format for recommendations search on the home page, make it a text box with a button that takes the user to the recommendations page instead since that is how it is done for the other features on the home page. \
**Severity level:** 2
![Seafood Watch home page](https://user-images.githubusercontent.com/40257341/193717234-681ca2fa-2feb-4eb2-b10f-e3693e089c59.png)
![image](https://user-images.githubusercontent.com/40257341/193953336-ae91b730-5f52-45ab-a692-65894b963d43.png)

![image](https://user-images.githubusercontent.com/40257341/193950225-41604888-5bdb-42a7-9480-4fbcc345ded5.png)
![image](https://user-images.githubusercontent.com/40257341/193950311-90c70f86-2ea6-4832-949b-32e601ddea73.png)


**Evaluation:** The general search bar for the entire website is formatted differently on the search page compared to how it looks in the menu bar.\
**Recommendation:** Match the search bar in the menu bar to the one on the search page since that one is more informative with "Name or keyword" included.\
**Severity level:** 1
![image](https://user-images.githubusercontent.com/40257341/193953630-839c5a15-926e-4818-b17e-224dfd8bcd0b.png)

#### 5. Error prevention
**Evaluation:** The text input box does not have spell check or search recommendations. \
**Recommendation:** Add spell check and search recommendations. \
**Severity level:** 2

#### 6. Recognition rather than recall

**Evaluation:** Only a couple entries can be displayed at once, and it is hard for users to distinguish them from one another. It gets worse with users having to scroll up/down to reference other entries. \
**Recommendation:** More entries should be visible at once for the users to be able to reference them.\
**Severity level:** 3
![Search result displaying abalone](https://user-images.githubusercontent.com/40257341/193736449-d06f054f-1fd0-4b62-a390-3cebda805f49.png)
![Search result displaying abalone](https://user-images.githubusercontent.com/40257341/193736487-4169a97f-dc7a-4b74-a1ca-d11da64f2308.png)

#### 7. Flexibility and efficiency of use
**Evaluation:** There are several places to search for recommendations: on the home page, on the recommendations page, and using the search bar in the menu bar. The recommendations search has ample options for filtering. The general search doesn't have any and displays recommendations at the top (without recommendation filters) and other pages that match the search query below. \
**Recommendation:** Add a filter system for the general search page. \
**Severity level:** 2

#### 8. Aesthetic and minimalist design
**Evaluation:** The design is aesthetic but not minimalist -- it overloads the user with information. Due to the design of the entries, it is difficult to distinguish how entries are different. There is a lot of redundant information -- for example, the list of what abalone is also known is the exact same for every one of the abalone entries. Additionally, only a couple entries can be displayed at once, making it even more difficult to cross reference them. What’s worse, Seafood Watch’s app support got discontinued so mobile users must use the browser website on their phones, which shows even less information per viewport.\
**Recommendation:** Reduce the amount of information displayed per entry so more entries can be seen at once. Group the results for the same recommendation level and emphasize how they are different from each other instead of displaying information that is the same across entries. \
**Severity level:** 3


**Evaluation:** Clicking on an entry takes the user to a page with additional details, including the Seafood Watch Recommendation score. However, there is too much information to be displayed in one screen.\
**Recommendation:** Condense the formatting so more information can be seen at once.\
**Severity level:** 2
![image](https://user-images.githubusercontent.com/40257341/193737401-ecb686a6-9f24-4bca-9217-891148f78fd7.png)
![image](https://user-images.githubusercontent.com/40257341/193737504-c25cca1a-3b91-4934-8608-dadb74165713.png)


#### 9. Help users recognize, diagnose, and recover from errors
**Evaluation:** This is similar to my evaluation for error prevention. There is no spell check or search suggestion, so users might be confused if they see no results when they misspell something.\
**Recommendation:** Add in spellcheck and suggestions for what the user might have meant to have typed.\
**Severity level:** 2
![image](https://user-images.githubusercontent.com/40257341/193987167-b88d6df9-6cb8-43c0-bf9d-fbbd97ad81fe.png)


#### 10. Help and documentation
**Evaluation:** The recommendations search page has instructions for how to use search. It also has details explaining what the recommendation levels mean.\
**Recommendation:** It would be helpful to have an easy-to-find page with details about each harvesting method. This information can be found viewing details for a particular species, but it would be good to have a consolidated reference sheet.\
**Severity level:** 2\
![image](https://user-images.githubusercontent.com/40257341/193977873-7cc76f9f-1d7a-414a-9595-86ebb8647c2e.png)


## Competitor 2: [Marine Conservation Society Good Fish Guide](https://www.mcsuk.org/goodfishguide/)
My second competitor site is [Marine Conservation Society Good Fish Guide](https://www.mcsuk.org/goodfishguide/), a sustainable seafood advisory list with a search feature run by the Marine Conservation Society, a UK charity focused on marine conservation.

It has two main features: the first is "Explore all seafood", which by default displays seafood in alphabetical order and has a search feature with filters.
![image](https://user-images.githubusercontent.com/40257341/194002422-1397d3ff-718e-4eee-be28-f91535c958f2.png)
![image](https://user-images.githubusercontent.com/40257341/194002498-d3b1e08d-a6f7-4b84-8b15-a77acea428e7.png)

The second feature is a beta tool called "Seafood checker." It lets users find specific information about seafood through asking a series of questions.
![image](https://user-images.githubusercontent.com/40257341/194002729-87a4b4af-7451-4f5a-8b39-dd293ab4ddae.png)
![image](https://user-images.githubusercontent.com/40257341/194002775-c17273a4-1423-4294-80d9-a21611f1aaad.png)
![image](https://user-images.githubusercontent.com/40257341/194002839-3d41c4e8-a6bc-4978-ac23-fc37ba12ae77.png)

The website has a clean design and is easy to use to find desired information, especially with the "Seafood checker" tool. I particularly appreciate that it provides alternative seafood options.

### Heuristic Evaluation

#### 1. Visibility of System Status

**Evalution:** There is a fish icon that fills with green while the page is loading.\
**Recommendation:** I don't always see the green fill up the fish, so maybe that animation needs to be adjusted.\
**Severity level:** 1
![image](https://user-images.githubusercontent.com/40257341/194003029-b374a991-8a3c-44d0-9179-24b7a4638a6f.png)


**Evalution:** There is no visual indication in the menu bar or with header text whether you're on the "Explore all seafood" or "Seafood checker" page. The only cue that the buttons are interactable are because the cursor changes into a pointer when hovering over.\
**Recommendation:** Highlight the buttons when hovered over, and highlight the button to match with the currently displayed page.\
**Severity level:** 1

#### 2. Match between system and the real world

**Evaluation:** The two menu options are "Explore all seafood" and "Seafood checker," the meaning of which is not obvious without context.\
**Recommendation:** One idea is to rename "Explore all seafood" to "Seafood search". I don't see how I could rename "Seafood checker", but maybe have a home page with context about the site so people can understand what each page does. The below image is on the sidebar of a seafood entry, and I think it would be good for it to be more prominent on the site, not only displayed after finding a specific seafood.\
**Severity level: 2**
![image](https://user-images.githubusercontent.com/40257341/194006296-6db76a40-e838-48f0-9a4a-5837dc13d392.png)


#### 3. User control and freedom

**Evaluation:** In the "Explore all seafood" page, this isn't really relevant because it is for searching.\
**Recommendation:** N/A\
**Severity level:** N/A

**Evaluation:* When using the "Seafood checker," there are options for the user to go back or to start again.\
**Recommendation:** I think the site does a good job already, but the options could be more prominent on the screen by being larger.\
**Severity level:** 1
![image](https://user-images.githubusercontent.com/40257341/194004001-77e5f314-3f65-4b7b-a4b4-42804b454691.png)

#### 4. Consistency and standards
**Evaluation:** The size and boldness of text is not consistent across the site.\
**Recommendation:** Reduce the variation of text styles. Make sure text that serves the same purpose is formatted the same (for example, "Good Fish Guide" on the "Explore all seafood page" and "How good is your fish or seafood?" on the "Seafood checker" page should be changed to be the same size).\
**Severity level: 1** 


**Evaluation:** There exists simultaneously a menu bar and a dropdown menu.\
**Recommendation:** Choose one of the two to commit to. It is confusing to have both and to have different options on the two.\
**Severity level: 2** 
![image](https://user-images.githubusercontent.com/40257341/194004591-585c5bb5-edd8-4514-bd0c-f5192790c3aa.png)


#### 5. Error prevention
**Evaluation:** The text input box does not have spell check or search recommendations.\
**Recommendation:** Add spell check and search recommendations.\
**Severity level: 1** 

#### 6. Recognition rather than recall

**Evaluation:** After clicking on a seafood option, all the different ratings are displayed. There are options to filter amongst these ratings, and since many ratings can be seen at once, the user can easily compare them and see how they're different from one another.\
**Recommendation:** Make the boxes consistent sizes. The ones without certification don't have the certification field at all, but that makes it so the boxes are smaller, which looks strange.\
**Severity level: 1** 
![image](https://user-images.githubusercontent.com/40257341/194005279-e0ab3c01-3648-4373-baa4-93e2f4e59554.png)


#### 7. Flexibility and efficiency of use
**Evaluation:** There are two ways to find information on seafood: through the search feature and through the seafood checker feature.\
**Recommendation:** I like that there are two ways of finding information! Again, I think it would be good to give more context about how each tool works. The below image is at the very bottom of the "Explore seafood ratings" page, so it is not easy to notice that the "Seafood checker" tool could be helpful to the user.\
**Severity level:**  1\
![image](https://user-images.githubusercontent.com/40257341/194006930-2ef28b66-e0d5-4baf-9387-c66b33adc536.png)


#### 8. Aesthetic and minimalist design
**Evaluation:** The website has a very strong visual identity, with vector drawings for each type of seafood. It gives a brief overview of the species and only after clicking the species is more informaton provided, which makes it much easier for useres to look through and compare multiple entries. \
**Recommendation:** There is information that is not unique to the species in the sidebar ("How our ratings work" and "Seafood checker"), which takes the focus away from the information about the seafood, which is the purpose of visiting the page. There should be more of a focus on information relevant to the seafood.\
**Severity level:** 1
![image](https://user-images.githubusercontent.com/40257341/194007388-c115166a-0d3f-43e2-bf55-6d19d92635a0.png)


#### 9. Help users recognize, diagnose, and recover from errors
**Evaluation:** If a user misspells a seafood, there are still search results that are somewhat similar to the misspelling. Additionally, if no results are found, there is a graphic that points users to try the "Seafood checker" instead.\
**Recommendation:** It is not clear how the site decides to recommend results based on the misspellings. I would like there to be some indication of why a result shows up despite the misspelling. For example, `abaloneyyyy` is recognizable as `abalone`, but adding an extra `y` at the end makes it unrecognizable by the site.\
**Severity level:** 2\
![image](https://user-images.githubusercontent.com/40257341/194008180-34861320-3839-4a9f-9c54-06bcdd343b5b.png)
![image](https://user-images.githubusercontent.com/40257341/194008510-f58cac16-c539-4896-b0f4-1ca57af46aba.png)


#### 10. Help and documentation
**Evaluation:** In the "Seafood checker", there is a little tooltip users can open to help them with finding information about seafood. The site also recommends either the "Explore all seafood" or "Seafood checker" tools when away from those pages.\
**Recommendation:** I think there should be a dedicated place for information instead of scattered around the site.\
**Severity level:** 1\
![image](https://user-images.githubusercontent.com/40257341/194007795-88cdac6f-0ba7-494e-8a23-fac33980e141.png)



