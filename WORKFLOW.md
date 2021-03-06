# Workflow
Things that I constantly remind myself when working on projects.

## General Design Workflow
- Product design research. Involve developers. Identify your app's [core functionality](https://blog.intercom.com/the-dribbblisation-of-design/).
- Scenario and storyboard creation.
- Create user stories.
- Work with clients and developers to produce low fidelity [prototypes](https://www.uxpin.com/studio/blog/paper-prototyping-the-practical-beginners-guide/).
- Wireframes using Sketch and [InVision](https://www.invisionapp.com/) or [Marvel](https://marvelapp.com/) to establish the flow of the app.
- Do not neglect your UI's **microcopy**. Here's a [great article](https://material.io/guidelines/style/writing.html) on microcopy. Trying to decide between a few different terms, and you’re not sure which term is best? Use [Google Trends](https://www.google.com/trends/). Google Trends compares how often people search for these terms on Google.
- Design studies. Most of the time, I present at least 2 studies to clients for the first 3-5 screens/pages.
- Visual design. Set up your project's styleguide using Craft. Using Craft's Style plugin will let you easily change text styles and colors. It is important to setup your library first before it gets too big to manage.
- Use [Symbols and Symbol Overrides](https://medium.com/ux-power-tools/this-is-without-a-doubt-the-coolest-sketch-technique-youll-see-all-day-ddefa65ea959#.fsb60f7k2) to create a [design system](http://atomicdesign.bradfrost.com/).
- High fidelity prototypes using Invision or Marvel.
- Frontend development.

## Redesign Workflow
- Research. Talk to people who use the website/app.  

   **_1. Why should we redesign the site?_**  
   **_2. Why do you think should we redesign the site now?_**  
   **_3. How will we know if the new site is better than the old one?_**
- Determine OKRs
- Visualize. OKR-based designs.
- Element Collage

## Sketch Workflow
- Use [Craft](https://www.invisionapp.com/craft) and [Auto Layout](https://animaapp.github.io/Auto-Layout/). These plugins will make your life easier!
- Organize your designs using **Pages** and **Artboards**. You will find these features useful once you're working on a design file with multiple screens with multiple variants. I always have pages for **Symbols**, **Experiments**, **Pattern Library**, **Moodboard** and the different application pages (e.g. Mobile Screens, Tablet Screens, etc.)
- The **Symbols** Page is auto generated by Sketch but please take time to organize your artboards here.
- The **Experiments** Page contains different versions of all the components in the design that might be used in the future.
- The **Pattern Library** contains the final elements, components and modules used in the design.
- The **Moodboard** contains design inspirations and pegs provided by the client.
- Use proper naming for **Pages** and **Artboards** just as you would for Photoshop layers. I make it a habit to keep a screen together with its variants in a separate **Page**. Here's an example (you don't have to follow this style):  

   A **Page** named **Editing Room** might contain the following **Artboards**:

   **_001 - Editing Room_** - Main design, in this case, for the "Editing Room".  
   **_002 - Editing Room - Comments_** - A variant of the "Editing Room" with the comments section visible.  
   **_003 - Editing Room - Chapters_** - A variant of the "Editing Room" with the chapters section visible.  
   **_004 - Editing Room - Comments (Mobile)_** - The mobile design for the Editing Room with the comments section visible.  
   **_005 - Editing Room - Chapters (Tablet)_** - The tablet design for the Editing Room with the chapters section visible.  
- Keep a folder in your machine with different assets organized into subfolders (e.g. food, avatars, office, etc.). This is especially useful when you're using Craft's Data, a plugin that helps you pull real content from a range of sources and place it directly in your design.
- Be sure there are no rogue text fields in your design. These tend to show up in Zeplin.
- Always setup your project's color palette in Zeplin. It's in the Styleguide tab. This will make your developers' lives easier.
- Avoid using phone templates in Sketch. Stick to Artboards. The output is easier to use in prototyping apps such as Invision and Marvel.
- As much as possible, make all icons(not font icons) and images exportable in Sketch so that it will be easier to export assets in Zeplin.
- Sketch has plugins for Zeplin, InVision and Marvel. Use those!

## Frontend Coding Tips
- Make it a habit to use a different *default* browser everyday. Do not stick to one browser.
- Always check your work using your browser's responsive design mode.
- Firefox also has **Reader View**. Use it for viewing pages with very long articles just to check if your heading hierarchy is okay.
- Always check your work using your mobile phone. When working on Rails Projects, use `rails s -b 0.0.0.0` instead of `rails s` so that you can view your project using your mobile devices.
- Safari is the new IE. Use Safari more often.
