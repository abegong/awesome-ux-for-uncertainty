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
Here, an algorithm makes a decision, which the user can audit and change if they choose.  This pattern works best when you can be very confident in algorithm's accuracy and/or the consequences of making a mistake aren't severe.

**Examples:**

* Gmail spam filtering
<img src="https://www.dangerouscommonsense.com/wp-content/uploads/2012/10/gmail-spam-fighting.jpg" width="400">

### Confirmation
With the confirmation pattern, an algorithm makes a decision, which the user can review and confirm. In some cases, confirmation is a required step in a multi-step workflow. In other cases, it can be optional.

**Examples:**

* Facebook person matching
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRRPeBSWmQ6vwJdqUIgb8mzIgBa29ZvguHjNXnsceuer_-dwrXo" width="400">

* Google photos face matching
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR2vUFlsyp3qYW9RZ0oVzY7Ml_i6aZCA6NYwRmQL0Gv-dXxoTse" width="400">

### Autocomplete text suggestions
Autocomplete text suggestions can save time and give the user ideas for what to write next. "Tab to accept" has proven to be a simple and intuitive interface. For this kind of interface, low latency and the length of the recommended text snippet are important considerations.

**Examples:**

* Gmail text completion
<img src="https://2.bp.blogspot.com/-KlBuhzV_oFw/WvxP_OAkJ1I/AAAAAAAACu0/T0F6lFZl-2QpS0O7VBMhf8wkUPvnRaPIACLcBGAs/s1600/image2.gif" width="400"> 
  
* Github copilot
<img src="https://rubenr.dev/_ipx/w_850/img/content/github-copilot-copilot-example.gif" width="400"> 
<img src="https://miro.medium.com/v2/resize:fit:1400/1*unz4NueAtEe6k3IgdDYpsw.gif" width="400">


### Regenerate, with options
Many of the design patterns create new content, or make a standalone decision. This pattern allows the user to collaborate with an algorithm to edit content together. The user selects a portion of the image/text/etc., (optionally) provides instructions to the algorithm, and the algorithm converts it into something new.  From there, the user can accept, edit, or decline the proposed changes, and then repeat the process.

**Examples:**

* Photoshop generative fill
<img src="https://www.geekseller.com/wp-content/uploads/2023/05/ADOBE-REMOVE-BG.gif" width="400">

* tome.app
<img src="https://github.com/abegong/awesome-ux-for-uncertainty/blob/main/img/Tome%20app%20gif.gif?raw=true" width="400">

* notion.ai
<img src="https://images.squarespace-cdn.com/content/v1/5e9f110643dda33450579f3b/7ab655a1-cd33-42bc-a49b-80d8832cf9bf/fix_spelling_notionai.gif" width="400">


### Choose from one of a few
In this pattern, the user is presented with a set of ideas or suggestions.  Typically the user picks at least one option, but may opt for more or none at all.  The pattern can be a good fit if the user needs to make a multiple-choice-type decision, or if you want to present the user with a variety of possibilities.

**Examples:**

* Pinterest: Find some ideas
<img src="https://assets-global.website-files.com/63769718a5796097e763daed/63fc9e80d3a5afa59e348f18_PLANOLY%2520-%2520Story%2520Pins%2520-%2520Blog%2520Post%2520-%2520GIF%25201.gif" width="400">

* Powerpoint: Slide ideas
<img src="https://cdn.slidemodel.com/wp-content/uploads/powerpoint-design-ideas-8-designer-slides.jpg" width="400"> 
  
* Midjourney: Pick one of 4 generated images to enlarge
<img src="https://media.licdn.com/dms/image/D4D12AQF4DGcp2vmgmA/article-inline_image-shrink_1000_1488/0/1683099231582?e=1704931200&v=beta&t=9mcLMs-nbwDScd9By3ej9fAWk5kZMM-ParZ27Zyq3Ao" width="400">

* Apple text swipe interface
  * This one is a mix of confirmation and multiple choice.
<img src="https://wolfewithane.com/_image_cache/f1a040a0-8c47-453f-a5ff-530d8e927da2.gif" width="400">

* Gmail autocomplete responses
<img src="https://betanews.com/wp-content/uploads/2017/05/Side-By-Side-v2.png" width="400">

### Sequential questions
Sometimes the user needs to make a series of several decisions one after another. In that case, a lightweight UI that presents relevant information and allows a quick decision can be a good fit.

**Examples:**

* Tinder swipe UI
<img src="https://camo.githubusercontent.com/276fc38a1fb7ef779fc0b173bbc3a50c540365f975f07f391ec8bb0c72ff2f95/68747470733a2f2f6d65646961332e67697068792e636f6d2f6d656469612f32366d6b684d596b69744f37446f4a75552f67697068792e676966" width="400">

### Select-among-many
This pattern (often paired with a recommender system on the backend) is a good way to present the user with many options to see which (if any) are interesting. It's a good fit when there are a very large number of options to select among, and you have an algorithm that is accurate enough can help users filter out many options, but not accurate enough to identify exactly what will be appealing to the user.

**Examples:**

* Amazon: Top Picks for You
<img src="https://assets-global.website-files.com/60f03643ffba6a48a3bda298/6283567dd5e53d12f2bd1575_MeXlYz3B3hDgwKRyxKgt5E81tZrjGAJnRamktIFrBVn6vZt0NyK50a4MyS6WxP0Xy3E8CJPdAISoxxfiepg_nYKJQ9C4jovZhTClir3ljw_uAgqb9yZZv1Ksy7WZsAiUAW48mcFVvJTo8SlJSQ.png"> 

* Netflix: Recommended movies within rows
    * [more info](https://help.netflix.com/en/node/100639)
<img src="https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcSY9DW8V_BEMukiGsqAO8UhNFrpuMOWUjACbRwPXnNOoYuckycb" width="400">

* Linkedin: People you May Know
<img src="https://content.linkedin.com/content/dam/engineering/site-assets/images/blog/posts/2021/08/pymkupdate3.png" width="400">


### Algorithmic feeds
Algorithmic feeds provide initial generic options for the user.  They then quietly track usage and build a UX based on what the algorithm thinks the user will want to see and the order in which they will want to see it.  Frequency and volume is determined by the user’s actions.

* Facebook newsfeed
<img src="https://raw.githubusercontent.com/abegong/awesome-ux-for-uncertainty/80df3b25c169ecd57d1d14b27a1829b1b64eb96d/img/Facebook%20img.jpeg" width="400">

* Twitter “For You”
<img src="https://pbs.twimg.com/media/FeUJLLQXoAI8Fid.jpg:large" width="400">
  
* Pinterest “More ideas”
<img src="https://github.com/abegong/awesome-ux-for-uncertainty/blob/main/img/Pinterest%20gif.gif?raw=true" width="400">

* Bluesky
<img src="https://blueskyweb.xyz/images/blogposts/skyfeed.png" width="400">

### Natural language chat
Natural language chat is modeled on conversation. Typically, user writes/speaks commands or questions, which the algorithm responds to. There are many variations: the algorithm can initiate and structure the conversation, questions can go both ways, etc. Depending on the application, the algorithm may be able to personalize responses, bring in additional context, call out to other services, etc.

* ChatGPT
<img src="https://cdn.fstoppers.com/styles/full/s3/media/2022/12/08/chatgpt_screen_rec_cropped.gif" width="400">

* Intercom
* <img src="https://blog.intercomassets.com/blog/wp-content/uploads/2023/03/AI-Bot-1-Multiple-Questions-Crop.jpg.optimal.jpg" width="400">

### Irreversible decisions
In this UX pattern, an algorithm makes a decision silently, with no direct interaction from the user.

* Netflix movie recommendation rows
<img src="https://encrypted-tbn3.gstatic.com/images?q=tbn:ANd9GcSY9DW8V_BEMukiGsqAO8UhNFrpuMOWUjACbRwPXnNOoYuckycb" width="400">

### Wake words
Wake words are a way of distinguishing between background noise and communication with a device. The job of the wake word algorithm is to passively "listen" until the user says the wake word, then switch into a more active state for other input.

* Siri
<img src="https://media.tenor.com/oqH_E3R9gD4AAAAC/siri-apple.gif" width="400">
  
* Alexa
<img src="https://rapidapi.com/blog/wp-content/uploads/2016/10/alexa-gif.gif" width="400">
