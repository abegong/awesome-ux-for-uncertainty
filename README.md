# awesome-ux-for-uncertainty
...is a repo of resources about **UX patterns for applications based on data / machine learning / AI**. Apps of this kind are different than traditional software, because they include statistical uncertainty (aka "guessing".) 

Putting together a talk in Nov 2023, I discovered that information on how to design and build the *backends* for these kinds of applications was easy to find, but information about how to design and build good *frontend* experiences was surprisingly hard to find. There was a lot of good raw material (blog posts, conference talks, screen shots, books, etc.), but it's scattered and disorganized.

My goal for `awesome-ux-for-uncertainty` is to provide a one-stop-shop for these kinds of resources, so that anyone who builds these kinds of applications can quickly some up to speed. This area of UI/UX has been an important niche topic ever since applications started surfacing data and predictions from algorithms. With all the new capabilities of generative AI, this area of UX is due for reimagination.

## Contributing

As of Nov 2023, this repo is the single best resource on this subject that I know of, but it's not remotely complete or comprehensive. It includes links I used for a single talk on this subject, plus some ideas contributed by others on twitter and Linkedin. 

* If you'd like to add a link/screen shot/etc, please submit a pull request and I'll review and approve as quickly as possible.
  * The lists of blog posts, presentations, and books are alphabetical by title. Please use this ordering.
  * All links must be related to UX patterns for applications based on data / machine learning / AI, but they don't need to be focused exclusively on that topic. If it's questionable, I'll make a judgement call as part of my review.
  * Within UX Patterns, I add links in the order they're submitted.
  * Please use consistent styling and formatting when adding new links.
* If you'd like to add a whole new section, please create an issue and we can discuss it there.
* If you have other questions, comments, ideas, or just want to compare notes on this subject, you can reach me in the smoking remains of twitter at [@abegong](https://twitter.com/abegong). DMs open.

Huge thanks for @drmann86 for his help pulling resources from the talk over into this repo.

## Table of contents

* <a href="https://github.com/abegong/awesome-ux-for-uncertainty#blog-posts">Blog posts</a>
* <a href="https://github.com/abegong/awesome-ux-for-uncertainty#presentations">Presentations</a>
* <a href="https://github.com/abegong/awesome-ux-for-uncertainty#books">Books</a>
* <a href="https://github.com/abegong/awesome-ux-for-uncertainty#ux-patterns">UX Patterns</a>



## Blog posts
* [Four UI design guidelines for creating machine learning applications](https://www.linkedin.com/pulse/four-ui-design-guidelines-creating-machine-learning-liikkanen/), Lassi A. Liikkanen
* [How to successfully productise ai and realise its full potential](https://medium.com/@rachel_d_ai/how-to-successfully-productise-ai-and-realise-its-full-potential-f18e08386370), Rachel Dulberg


## Presentations
* [Climbing the ladder of abstraction](https://www.youtube.com/watch?v=qw4PrtyvJI0&t=3355s), Amelia Wattenberger, AI Engineer Summit 2023
* [Designing with AI: building the flagship GPT-4 language product at Duolingo](https://www.youtube.com/watch?v=zqUi3p-o8wU&list=PLXDU_eVOJTx61IdqXh3jrvopJN8HGkS5F&index=43), Edwin Bodge and Megan Bednarczyk, Config 2023
* [UX Patterns for Uncertainty](https://docs.google.com/presentation/d/e/2PACX-1vS8sxzTOOzqoNEfyh3sHsjSUNs3Pa0SnvD9RezK4yNu9zG_lWZz0dhQRbJXegD7bOTp9ijsu-7q2DL1/pub?start=false&loop=false&slide=id.p), Abe Gong, November 2023

## Books

* [Designing for behavior change](https://www.amazon.com/Designing-Behavior-Change-Psychology-Behavioral/dp/1492056030), Stephen Wendel
* [Don’t make me think](https://www.amazon.com/Dont-Make-Think-Revisited-Usability/dp/0321965515/), Steve Krug
* [Hooked: How to Build Habit-Forming Products](https://www.amazon.com/Hooked-How-Build-Habit-Forming-Products/dp/0241184835), Nir Eyal
* [Microinteractions](https://www.amazon.com/Microinteractions-Full-Color-Designing-Details/dp/1491945923/), Dan Saffer and Don Norman


## UX Patterns

### Reversible decision
Here, an algorithm makes a decision, which the user can audit and change if they choose.  The algorithm's job is to interpret what the user may want to see and what they may want to ignore based on pre-existing standards and filter options presented to the user.

**Examples:**

* Gmail spam filtering [image](https://www.dangerouscommonsense.com/wp-content/uploads/2012/10/gmail-spam-fighting.jpg)
<img src="https://www.dangerouscommonsense.com/wp-content/uploads/2012/10/gmail-spam-fighting.jpg" width="400">

### Confirmation
With the confirmation pattern, an algorithm makes a decision, which the user must review and confirm. However, the user may opt to not confirm or accept the decision at all.  This decide-and-confirm step is often one step in a multi-step workflow.

**Examples:**

* Gmail responses [image](https://betanews.com/wp-content/uploads/2017/05/Side-By-Side-v2.png)
<img src="https://betanews.com/wp-content/uploads/2017/05/Side-By-Side-v2.png" width="400">

* Verification questions [image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRRPeBSWmQ6vwJdqUIgb8mzIgBa29ZvguHjNXnsceuer_-dwrXo)
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRRPeBSWmQ6vwJdqUIgb8mzIgBa29ZvguHjNXnsceuer_-dwrXo" width="400">

* Tinder [gif](media3.giphy.com/media/26mkhMYkitO7DoJuU/giphy.gif)
<img src="https://camo.githubusercontent.com/276fc38a1fb7ef779fc0b173bbc3a50c540365f975f07f391ec8bb0c72ff2f95/68747470733a2f2f6d65646961332e67697068792e636f6d2f6d656469612f32366d6b684d596b69744f37446f4a75552f67697068792e676966" width="400">


* Tinder [image](https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcTVZYfbTg8wfy6y_foFM-FlBpQeH1SEHlLl9zvEkrPDF1y3M3sr)
<img src="https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcTVZYfbTg8wfy6y_foFM-FlBpQeH1SEHlLl9zvEkrPDF1y3M3sr" width="400">


* Photo ID [image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR2vUFlsyp3qYW9RZ0oVzY7Ml_i6aZCA6NYwRmQL0Gv-dXxoTse)
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR2vUFlsyp3qYW9RZ0oVzY7Ml_i6aZCA6NYwRmQL0Gv-dXxoTse" width="400">

* Apple text swipe interface [gif](https://wolfewithane.com/_image_cache/f1a040a0-8c47-453f-a5ff-530d8e927da2.gif)
<img src="https://wolfewithane.com/_image_cache/f1a040a0-8c47-453f-a5ff-530d8e927da2.gif" width="400">


### Autocomplete text suggestions
Autocomplete text suggestions provide the user with presumed text that the algorithm thinks will best complete the user’s sentence as it is typed.  The user is in full control over the function and may choose to ignore the algorithm’s suggestions or continue to type a particular suggestion in full.

**Examples:**

* Gmail text completion [gif](https://2.bp.blogspot.com/-KlBuhzV_oFw/WvxP_OAkJ1I/AAAAAAAACu0/T0F6lFZl-2QpS0O7VBMhf8wkUPvnRaPIACLcBGAs/s1600/image2.gif)
<img src="https://2.bp.blogspot.com/-KlBuhzV_oFw/WvxP_OAkJ1I/AAAAAAAACu0/T0F6lFZl-2QpS0O7VBMhf8wkUPvnRaPIACLcBGAs/s1600/image2.gif" width="400"> 
  
* Github copilot [gif](https://rubenr.dev/_ipx/w_850/img/content/github-copilot-copilot-example.gif)
<img src="https://rubenr.dev/_ipx/w_850/img/content/github-copilot-copilot-example.gif" width="400"> 
  
* Github copilot [gif](https://miro.medium.com/v2/resize:fit:1400/1*unz4NueAtEe6k3IgdDYpsw.gif)
<img src="https://miro.medium.com/v2/resize:fit:1400/1*unz4NueAtEe6k3IgdDYpsw.gif" width="400">


### Regenerate, with options
In this pattern, algorithms ask the user to submit some form of media (ie: text or photo).  The job of the algorithm is to take that media and convert it into something different and new, such as turning basic text into a presentation, editing a photo, etc.  The user can accept, edit, or decline the proposed changes and maintains full control throughout the process.  They can also use the algorithm for all of the work or just as a launching point.

**Examples:**

* Photoshop generative fill [gif](https://www.geekseller.com/wp-content/uploads/2023/05/ADOBE-REMOVE-BG.gif)
<img src="https://www.geekseller.com/wp-content/uploads/2023/05/ADOBE-REMOVE-BG.gif" width="400">

* tome.app [gif](https://github.com/abegong/awesome-ux-for-uncertainty/blob/main/img/Tome%20app%20gif.gif?raw=true)
<img src="https://github.com/abegong/awesome-ux-for-uncertainty/blob/main/img/Tome%20app%20gif.gif?raw=true" width="400">

* notion.ai [gif](https://images.squarespace-cdn.com/content/v1/5e9f110643dda33450579f3b/7ab655a1-cd33-42bc-a49b-80d8832cf9bf/fix_spelling_notionai.gif)
<img src="https://images.squarespace-cdn.com/content/v1/5e9f110643dda33450579f3b/7ab655a1-cd33-42bc-a49b-80d8832cf9bf/fix_spelling_notionai.gif" width="400">


### Choose from one of a few
In this pattern, the user is presented with ideas or suggestions to help build a more personalized experience.  Typically the user picks at least one option, but may opt for more or none at all.  The algorithm’s job is to provide the user with a variety of possibilities to improve their experience, and the user has the flexibility to make changes to their initial selection throughout the entire process.

**Examples:**

* Pinterest: Find some ideas [gif](https://assets-global.website-files.com/63769718a5796097e763daed/63fc9e80d3a5afa59e348f18_PLANOLY%2520-%2520Story%2520Pins%2520-%2520Blog%2520Post%2520-%2520GIF%25201.gif)
<img src="https://assets-global.website-files.com/63769718a5796097e763daed/63fc9e80d3a5afa59e348f18_PLANOLY%2520-%2520Story%2520Pins%2520-%2520Blog%2520Post%2520-%2520GIF%25201.gif" width="400">

* Powerpoint: Slide ideas [image](https://cdn.slidemodel.com/wp-content/uploads/powerpoint-design-ideas-8-designer-slides.jpg)
<img src="https://cdn.slidemodel.com/wp-content/uploads/powerpoint-design-ideas-8-designer-slides.jpg" width="400"> 
  
* Midjourney [gif](https://media.licdn.com/dms/image/D4D12AQF4DGcp2vmgmA/article-inline_image-shrink_1000_1488/0/1683099231582?e=1704931200&v=beta&t=9mcLMs-nbwDScd9By3ej9fAWk5kZMM-ParZ27Zyq3Ao)
<img src="https://media.licdn.com/dms/image/D4D12AQF4DGcp2vmgmA/article-inline_image-shrink_1000_1488/0/1683099231582?e=1704931200&v=beta&t=9mcLMs-nbwDScd9By3ej9fAWk5kZMM-ParZ27Zyq3Ao" width="400">


### Select-among-many
In this pattern, the user is presented with many options and asked to select among them. Often, The user is picking a single item, although multiple select UIs also exist. In some cases, the user might not make any choice at all. The algorithm's job is essentially to rank a large set of options, based on how appealing they're likely to be to the user.

**Examples:**

* Amazon: Top Picks for You [image](https://assets-global.website-files.com/60f03643ffba6a48a3bda298/6283567dd5e53d12f2bd1575_MeXlYz3B3hDgwKRyxKgt5E81tZrjGAJnRamktIFrBVn6vZt0NyK50a4MyS6WxP0Xy3E8CJPdAISoxxfiepg_nYKJQ9C4jovZhTClir3ljw_uAgqb9yZZv1Ksy7WZsAiUAW48mcFVvJTo8SlJSQ.png)
<img src="https://assets-global.website-files.com/60f03643ffba6a48a3bda298/6283567dd5e53d12f2bd1575_MeXlYz3B3hDgwKRyxKgt5E81tZrjGAJnRamktIFrBVn6vZt0NyK50a4MyS6WxP0Xy3E8CJPdAISoxxfiepg_nYKJQ9C4jovZhTClir3ljw_uAgqb9yZZv1Ksy7WZsAiUAW48mcFVvJTo8SlJSQ.png"> 

* Netflix: Recommended movies within rows [image](https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcSY9DW8V_BEMukiGsqAO8UhNFrpuMOWUjACbRwPXnNOoYuckycb)
    * [more info](https://help.netflix.com/en/node/100639)
<img src="https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcSY9DW8V_BEMukiGsqAO8UhNFrpuMOWUjACbRwPXnNOoYuckycb" width="400">

* Linkedin: People you May Know [image](https://content.linkedin.com/content/dam/engineering/site-assets/images/blog/posts/2021/08/pymkupdate3.png)
<img src="https://content.linkedin.com/content/dam/engineering/site-assets/images/blog/posts/2021/08/pymkupdate3.png" width="400">


### Algorithmic feeds
Algorithmic feeds provide initial generic options for the user.  They then quietly track usage and build a UX based on what the algorithm thinks the user will want to see and the order in which they will want to see it.  Frequency and volume is determined by the user’s actions.

* Facebook newsfeed [image](https://raw.githubusercontent.com/abegong/awesome-ux-for-uncertainty/80df3b25c169ecd57d1d14b27a1829b1b64eb96d/img/Facebook%20img.jpeg)
<img src="https://raw.githubusercontent.com/abegong/awesome-ux-for-uncertainty/80df3b25c169ecd57d1d14b27a1829b1b64eb96d/img/Facebook%20img.jpeg" width="400">

* Twitter “For You” [image](https://pbs.twimg.com/media/FeUJLLQXoAI8Fid.jpg:large)
<img src="https://pbs.twimg.com/media/FeUJLLQXoAI8Fid.jpg:large" width="400">
  
* Pinterest “More ideas” [gif](https://github.com/abegong/awesome-ux-for-uncertainty/blob/main/img/Pinterest%20gif.gif?raw=true)
<img src="https://github.com/abegong/awesome-ux-for-uncertainty/blob/main/img/Pinterest%20gif.gif?raw=true" width="400">

* Bluesky [image](https://blueskyweb.xyz/images/blogposts/skyfeed.png)
<img src="https://blueskyweb.xyz/images/blogposts/skyfeed.png" width="400">

### Free text chat
Natural language chat asks the user to input written or spoken language in the form of a command or question.  The job of the algorithm is to take that prompt and provide an output or reply using the internet and/or other databases.  The algorithm can also personalize responses based on user input.  Users can then opt to ask follow-up questions, not reply at all, or ask entirely new questions and repeat the sequence.

* ChatGPT [gif](https://cdn.fstoppers.com/styles/full/s3/media/2022/12/08/chatgpt_screen_rec_cropped.gif)
<img src="https://cdn.fstoppers.com/styles/full/s3/media/2022/12/08/chatgpt_screen_rec_cropped.gif" width="400">

### Irreversible decisions
Tangential to the select-among-many pattern, irreversible decisions are where the user is presented with a series of preset categories and asked to make a selection from within those categories. The algorithm's job is essentially to populate preset categories with a large set of ranked options. The user may review the options presented and make any number of choices but lacks the ability to change or influence the overall categories provided by the algorithm.

* Netflix movie recommendation rows [link](https://help.netflix.com/en/node/100639)
<img src="https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcSY9DW8V_BEMukiGsqAO8UhNFrpuMOWUjACbRwPXnNOoYuckycb" width="400">

### Wake words
Similar to natural language chat, wake words asks the user to input written or spoken language in the form of a command or question using a specific trigger word or phrase (ie: wake word) to initiate the sequence.  The job of the algorithm is to engage once the wake word has been typed or spoken and captured into the microphone.   The algorithm cannot customize wake words but can customize responses based on user input.  To initiate the sequence again, the wake words must be spoken each time.

* Siri [gif](https://media.tenor.com/oqH_E3R9gD4AAAAC/siri-apple.gif)
<img src="https://media.tenor.com/oqH_E3R9gD4AAAAC/siri-apple.gif" width="400">
  
* Alexa [gif](https://rapidapi.com/blog/wp-content/uploads/2016/10/alexa-gif.gif)
<img src="https://rapidapi.com/blog/wp-content/uploads/2016/10/alexa-gif.gif" width="400">
