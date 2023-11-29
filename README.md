# awesome-ux-for-uncertainty
...is a repo of links and resources about UX patterns for applications the involve prediction/uncertainty/"guessing"/etc.

UI patterns for uncertainty have been an important niche topic ever since we started building apps that surface data and predictions from algorithms.

With all the new capabilities of generative AI, this area of UX is due for reimagination.

Putting a talk in Nov 2023, I was surprised that nothing quite like awesome-ux-for-uncertainty existed. I hope it’ll be a useful place for data and UX people to collaborate.



## UX Patterns

### Reversible decision
Here, an algorithm makes a decision, which the user can audit and change if they choose.  The algorithm's job is to interpret what the user may want to see and what they may want to ignore based on pre-existing standards and filter options presented to the user.

<img src="https://www.dangerouscommonsense.com/wp-content/uploads/2012/10/gmail-spam-fighting.jpg" width="400">

* Gmail spam filtering [image](https://www.dangerouscommonsense.com/wp-content/uploads/2012/10/gmail-spam-fighting.jpg)

### Confirmation
With the confirmation pattern, an algorithm makes a decision, which the user must review and confirm. However, the user may opt to not confirm or accept the decision at all.  This decide-and-confirm step is often one step in a multi-step workflow.

<img src="https://betanews.com/wp-content/uploads/2017/05/Side-By-Side-v2.png" width="400">
<img src="https://media3.giphy.com/media/26mkhMYkitO7DoJuU/giphy.gif" width="400">

* Gmail responses [image](https://betanews.com/wp-content/uploads/2017/05/Side-By-Side-v2.png)
* Apple text swipe interface

### Autocomplete text suggestions
Autocomplete text suggestions provide the user with presumed text that the algorithm thinks will best complete the user’s sentence as it is typed.  The user is in full control over the function and may choose to ignore the algorithm’s suggestions or continue to type a particular suggestion in full.

<img src="https://2.bp.blogspot.com/-KlBuhzV_oFw/WvxP_OAkJ1I/AAAAAAAACu0/T0F6lFZl-2QpS0O7VBMhf8wkUPvnRaPIACLcBGAs/s1600/image2.gif" width="400"> <img src="https://rubenr.dev/_ipx/w_850/img/content/github-copilot-copilot-example.gif" width="400">

* Gmail text completion [gif](https://2.bp.blogspot.com/-KlBuhzV_oFw/WvxP_OAkJ1I/AAAAAAAACu0/T0F6lFZl-2QpS0O7VBMhf8wkUPvnRaPIACLcBGAs/s1600/image2.gif)
* Github copilot [gif](https://rubenr.dev/_ipx/w_850/img/content/github-copilot-copilot-example.gif)

### Regenerate, with options
In this pattern, algorithms ask the user to submit some form of media (ie: text or photo).  The job of the algorithm is to take that media and convert it into something different and new, such as turning basic text into a presentation, editing a photo, etc.  The user can accept, edit, or decline the proposed changes and maintains full control throughout the process.  They can also use the algorithm for all of the work or just as a launching point.

<img src="https://media.giphy.com/media/vFKqnCdLPNOKc/giphy.gif" width="400">

* tome.app
* notion.ai (???)
* Photoshop generative fill [gif](https://www.geekseller.com/wp-content/uploads/2023/05/ADOBE-REMOVE-BG.gif)

### Choose from one of a few
In this pattern, the user is presented with ideas or suggestions to help build a more personalized experience.  Typically the user picks at least one option, but may opt for more or none at all.  The algorithm’s job is to provide the user with a variety of possibilities to improve their experience, and the user has the flexibility to make changes to their initial selection throughout the entire process.

<img src="https://assets-global.website-files.com/63769718a5796097e763daed/63fc9e80d3a5afa59e348f18_PLANOLY%2520-%2520Story%2520Pins%2520-%2520Blog%2520Post%2520-%2520GIF%25201.gif" width="400">

* Pinterest: Find some ideas [gif](https://assets-global.website-files.com/63769718a5796097e763daed/63fc9e80d3a5afa59e348f18_PLANOLY%2520-%2520Story%2520Pins%2520-%2520Blog%2520Post%2520-%2520GIF%25201.gif)
* Powerpoint: Slide ideas
  Midjourney

### Select-among-many
In this pattern, the user is presented with many options and asked to select among them. Often, The user is picking a single item, although multiple select UIs also exist. In some cases, the user might not make any choice at all. The algorithm's job is essentially to rank a large set of options, based on how appealing they're likely to be to the user.

<img src="https://assets-global.website-files.com/60f03643ffba6a48a3bda298/6283567dd5e53d12f2bd1575_MeXlYz3B3hDgwKRyxKgt5E81tZrjGAJnRamktIFrBVn6vZt0NyK50a4MyS6WxP0Xy3E8CJPdAISoxxfiepg_nYKJQ9C4jovZhTClir3ljw_uAgqb9yZZv1Ksy7WZsAiUAW48mcFVvJTo8SlJSQ.png"> 

<img src="https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcSY9DW8V_BEMukiGsqAO8UhNFrpuMOWUjACbRwPXnNOoYuckycb" width="400">

* Amazon: Top Picks for You [image](https://assets-global.website-files.com/60f03643ffba6a48a3bda298/6283567dd5e53d12f2bd1575_MeXlYz3B3hDgwKRyxKgt5E81tZrjGAJnRamktIFrBVn6vZt0NyK50a4MyS6WxP0Xy3E8CJPdAISoxxfiepg_nYKJQ9C4jovZhTClir3ljw_uAgqb9yZZv1Ksy7WZsAiUAW48mcFVvJTo8SlJSQ.png)
* Netflix: Recommended movies within rows [image](https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcSY9DW8V_BEMukiGsqAO8UhNFrpuMOWUjACbRwPXnNOoYuckycb)
    * [more info](https://help.netflix.com/en/node/100639)
* Linkedin: People you May Know


### Algorithmic feeds
Algorithmic feeds provide initial generic options for the user.  They then quietly track usage and build a UX based on what the algorithm thinks the user will want to see and the order in which they will want to see it.  Frequency and volume is determined by the user’s actions.

* Facebook newsfeed
* Twitter “For You”
* Pinterest: “More ideas”
* Bluesky

### Free text chat
Natural language chat asks the user to input written or spoken language in the form of a command or question.  The job of the algorithm is to take that prompt and provide an output or reply using the internet and/or other databases.  The algorithm can also personalize responses based on user input.  Users can then opt to ask follow-up questions, not reply at all, or ask entirely new questions and repeat the sequence.

* ChatGPT

### Irreversible decisions
Tangential to the select-among-many pattern, irreversible decisions are where the user is presented with a series of preset categories and asked to make a selection from within those categories. The algorithm's job is essentially to populate preset categories with a large set of ranked options. The user may review the options presented and make any number of choices but lacks the ability to change or influence the overall categories provided by the algorithm.

### Wake words
Similar to natural language chat, wake words asks the user to input written or spoken language in the form of a command or question using a specific trigger word or phrase (ie: wake word) to initiate the sequence.  The job of the algorithm is to engage once the wake word has been typed or spoken and captured into the microphone.   The algorithm cannot customize wake words but can customize responses based on user input.  To initiate the sequence again, the wake words must be spoken each time.


-----

## Blog posts
* https://medium.com/@rachel_d_ai/how-to-successfully-productise-ai-and-realise-its-full-potential-f18e08386370
* [four UI design guidelines for creating machine learning applications](https://www.linkedin.com/pulse/four-ui-design-guidelines-creating-machine-learning-liikkanen/)


## Presentations
* https://www.youtube.com/watch?v=zqUi3p-o8wU&list=PLXDU_eVOJTx61IdqXh3jrvopJN8HGkS5F&index=43
* https://www.youtube.com/watch?v=qw4PrtyvJI0&t=3567s
