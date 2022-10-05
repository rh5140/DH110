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

Using the search feature takes the user to the Recommendations page. Users can filter their searches with criteria like species, harvest method, country/region, body of water, and recommendation level. 
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

Using the search feature takes the user to the Recommendations page. Users can filter their searches with criteria like species, harvest method, country/region, body of water, and recommendation level. 
![Seafood Watch Recommendations page](https://user-images.githubusercontent.com/40257341/193736371-6e53f995-38d9-41bd-8c6d-c5b4b25f86af.png)

### Heuristic Evaluation

#### 1. Visibility of System Status

**Evalution:** \
**Recommendation:** \
**Severity level:** 1

**Evalution:** \
**Recommendation:** \
**Severity level:** 1

#### 2. Match between system and the real world

**Evaluation:** \
**Recommendation:** \
**Severity level:**

**Evaluation:** 
**Recommendation:** 
**Severity level:** 

#### 3. User control and freedom

**Evaluation:** The main actions users would take is making searches. There aren't really consequences for making an incorrect search -- the user can easily search again. "Undo" doesn't really make sense in this context. The other mistake users could make is misclick and go to a page they weren't intending to, but the browser back 1 page button is sufficient for that.\
**Recommendation:** N/A\
**Severity level:** N/A

#### 4. Consistency and standards
**Evaluation:** \
**Recommendation:**\
**Severity level:** 


**Evaluation:** \
**Recommendation:** \
**Severity level:** 

#### 5. Error prevention
**Evaluation:** \
**Recommendation:**\
**Severity level:** 

#### 6. Recognition rather than recall

**Evaluation:**  \
**Recommendation:** \
**Severity level:** 

#### 7. Flexibility and efficiency of use
**Evaluation:** \
**Recommendation:**  \
**Severity level:**  \

#### 8. Aesthetic and minimalist design
**Evaluation:** \
**Recommendation:** \
**Severity level:** 3


**Evaluation:** \
**Recommendation:** \
**Severity level:** 


#### 9. Help users recognize, diagnose, and recover from errors
**Evaluation:** \
**Recommendation:** \
**Severity level:** 


#### 10. Help and documentation
**Evaluation:** \
**Recommendation:** \
**Severity level:** \


