# Helping Hand - Your Mental Health Hub

Helping Hand is a comprehensive mental health resource hub designed to provide guidance, support, and access to vital resources for individuals seeking help. The website offers practical self-help strategies and valuable signposting to external services, including therapy, support groups, and counselors. Targeted primarily at adults, Helping Hand aims to foster mental well-being and resilience, while also offering resources that can be helpful for younger individuals. Whether you're seeking advice, looking for professional support, or simply need a starting point for your mental health journey, Helping Hand is here to assist and empower you.

![image](https://github.com/user-attachments/assets/bbb2395f-e28c-41c3-86e4-8b01c397f9d9)

## Features 

### Existing Features

- __Navigation Bar__

  - Featured on all three pages, the full responsive navigation bar includes links to the Logo, Home page, Self Help, and Find Support page and is identical in each page to allow for easy navigation. Included in the design is also an emergency help button linking externally to the NHS Mental Health emergency resources.
  - It is to be noted also regarding upper page structure, that all pages have appropriate titles for browsers, and a generated favicon with multiple sized favicons for appropriat resizing.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![HHnavbar](https://github.com/user-attachments/assets/376284b3-77b6-4775-90d2-b2eccd59b585)


- __Home Page Hero Image__

  - The home page includes a photograph of the mental health awareness symbol so the user can clearly understand the type of website they're interacting with.
  - This section introduces the user to Love Running with an eye catching animation to grab their attention

![image](https://github.com/user-attachments/assets/4690ba48-e9f0-43ba-89da-b534ccb3e355)


- __Home Hero Encouragement Text__

  - The section of text here on the home page is designed to be direct, yet sincere in the reality of mental health, encouraging the user to take the leap to living healthier. 
  - This user will be face with the honest truth about mental health in the world in a tone with no malice, with an age old quote in the text to break up the page, and inspire bravery from them to go on.

![image](https://github.com/user-attachments/assets/b1e6fcf5-0a60-4e7e-bcba-da15d1bc8182)


- __Direction Buttons__

  - This section will allow the user to take the leap on engaging with the site, offering them clear links to the page more suited to them without returning their view to the top of the page, where they may drop engagement.
  - In future these buttons will undergo further styling to improve their appeal and soften them visually. 

![image](https://github.com/user-attachments/assets/3ee2b1e7-17d4-4170-9f27-3e4808e387ac)


- __The Footer__ 

  - The footer section includes links to the relevant social media sites for Helping Hand. The links will open to a new tab to allow easy navigation for the user. 
  - The footer is valuable to the user as it encourages them to keep connected via social media, potentially keeping their interest in how we can help them by reminding them of our presence and support. It is kept simple with clear, clean content that is built in a manner that can easily allow for additional content should the website expand in the future.

![image](https://github.com/user-attachments/assets/8accc667-97c2-4d48-806d-cb65639e77dd)


- __Self Help Page__

  - Each support page is formatted in cards, with this self targeted methods page being clearly and minimally split into a physically targeted set of ideas, and a set focused more on working with feelings, managing them, and expressing them. 
  - This section is valuable as the information is kept in light, illustrated cards with brief factual statements, followed by recommendations with how to try them distinctly shown in italics for the user to absorb in small portions at their own pace. The 'Meditation' card can be seen with clear linking in the text to help signpoint to what is a more appropriate length publication on the topic to avoid overloading the card content. (The 'here' links to this NHS mental health page regarding the same topic in approachable sections: https://www.nhs.uk/every-mind-matters/mental-wellbeing-tips/what-is-mindfulness/ )

![image](https://github.com/user-attachments/assets/75fc0685-faf4-44a9-8cb5-869435350224) ![image](https://github.com/user-attachments/assets/d535ed61-56f9-4375-b097-3bf4417652d9)

- __The Find Support Page__

  - This page will allow the user to get signposted to resources and services from established, UK based/appropriate organisations that offer the most popular and successful support depending on need, context, or personal comfort. The user will be able to read the card text in digestable amounts and decide if/what method they may find most suited to their needs and carry on directly to find out more in the right places. Each card has a relevant icon to try and lighten the appearance and tone of the content, which for a user in a mentally compromised condition, may help remove any sense of intimidation. These icons are colour coded for their card, with the button links matching accordingly.

![image](https://github.com/user-attachments/assets/0b5abf86-633b-48a6-8c9e-8d66d97c4fb4) ![image](https://github.com/user-attachments/assets/e478f48e-1f5d-40d9-86ae-cec82797d835)

### Features Left to Implement

- About Page describing the connection between the Helping Hand team and the user via anecdotal understanding of how mental health can be.
- Feedback Form modal / footer link placed on new small descriptive section at bottom of support pages, anonymous for privacy, required checkbox to confirm consent for feedback to be used (positive testimonials shown on site in section on lower half of About Page, negative feedback used internally to review content quality and reliability, may help streamline bug feedback also.
- Motivational Moodboard, a page akin to a gallery stylised similar to the site Pinterest and their board system, stocked with collaged motivational images, quotes, scenery, etc. to provide the user motivational visual aid they may need at the time, or keep for themselves in the long term. Could include wide carousel to keep the page cycling and interactive (all images royalty free and no crediting requirements)
- Moodbooster Email Newsletter signup form option in footer (Uncertain on genuine value to user compared to biased hopes for interaction as the developer, feels forced.)


## Wireframes

![HH - Homepage](https://github.com/user-attachments/assets/d83a1937-b826-48c0-984c-351ba1e91248) ![HH - Self Help](https://github.com/user-attachments/assets/23ef3418-022e-48ac-8b25-e004e6fc9ab6) ![HH - Find Support](https://github.com/user-attachments/assets/12bcd845-7459-41be-9598-4cb6a84d74b9)




## Testing 

__Navbar, header, Linked Logo, Emergency Help Button__

- Navbar functions across all devices, with correct collapsing for smaller devices, all buttons link to correct site pages, internal links stay within the same tab, external emergency link opens in new tab to keep user on website without hitting back.
- Brand Name/logo links to home page. All internal links need no adjustment for deployment as html pages exist in root of file structure.
- Header formats correctly in size and nav collapse on smaller devices, with emergency button still prominent and clear due to its important nature.
- Bar is identical on all pages. The active page highlight in the navbar list is correct for each page including aria tag.

__Home Page Hero Section & Direction Buttons__

- Text is clear and readable across all device sizes, quote is distinctly set out from regular text using blockquote.
- Image resizes on different device sizes however CSS and bootstrap interactions may need refining for more appropriate use of page space in future.
- h1 element displays clear dominant text to introduce the page, site and content in correct font and color formatting across the site works as intended with correct var() use on this element.
- Direction Buttons function as intended, correct filepaths and stays within same tab, may need formatting update at certain larger screen sizes. Functionally stable. They sometimes jolt to left align at very specific thresholds. Will be bugfixed in future.

__The Footer__
- The footer displays correctly with matching theme to header across all devices.
- Social Media icons are all visible clearly, sized and spaced correctly. Each links to the correct social media homepage in a new browser tab.
- Present on all pages identically.

__Self Help Page__
- Hero displays correctly with text set to color deemed readable, resizes on other devices.
- Section titles display at correct size and spacing per device.
- Cards all contain typo free content, clear images with correct relative filepaths.
- Cards have even spacing, stack correctly without overlap on smaller screens, distinct rows on medium and larger screens. Heights all match across all screens.

__Find Support Page__
- Hero displays correctly with text set to color deemed readable, resizes on other devices.
- Section Titular text at correct size and spacing per device
- Cards all contain typo free content, correct icons and color theme matching the button.
- Cards all stack and row align correct on different screen sizes.
- All card links go to correct external webpages, and all open in new tabs.

### Validator Testing 

- HTML
  - No errors were returned when passing through the official W3C Validator. Due to deployment issues, this has been tested via direct input resulting in no providable link. You are welcome to use the files in this updated repository to repeat these tests.

- CSS
  - No errors were found when passing through the official W3c CSS Validator (Jigsaw). Due to deployment issues, this has been tested via direct input resulting in no providable link. You are welcome to use the files in this updated repository to repeat these tests.

### Unfixed Bugs
- Direction buttons snap to left-aligned when at certain sizes (Struggling to locate media query issues)
- Direction buttons increased to use more free space displaces hero image and causes it to shrink (Lack of understanding for a fix in time)
- Occasionally burger icon displaces itself slightly too close to logo (Can't pinpoint cause in query)
- Hero image doesn't fill as much space as intended/planned on homepage (may be resolution related, CSS fixes attempted but little impact)
- Some CSS, both general and media query related my overlap or write each other obsolete, vast majority is fully functional and has minimal impact. May have spaghetti code leftover or in need of refining. Most has been checked over. (Time constraints and partial limit of understanding)

## Deployment

- The site WILL be deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the main Branch
  - Once the main branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - (NOT AVAILABLE DUE TO GITHUB RESTRICTIONS. AWAITING GITHUB SUPPORT RESOLUTION)

## Credits 

### Content 

- The text for the Home page was written by myself, yet the statistic and quote were sourced from OpenAI's ChatGPT 4.0 
- The text for the support page cards was created by myself, with the Meditation card on Self Help linking further info directly from an external source.
- The code used to create my bootstrap cards on both support pages was taken from the Code Institute - Boardwalk Games Project. My repository from this walkthrough project: https://github.com/JGroves2k24/boardwalk-games
- The icons seen anywhere on the website except the favicon were taken from [Font Awesome](https://fontawesome.com/)
- The resources that my advisory cards link to were compiled for me by OpenAI's ChatGPT 4.0 searching for UK based services and sites.
- Any bootstrap structured items (buttons, cards, navbar, etc.) were sourced from Bootstrap's documentation library for v5.3.3 (https://getbootstrap.com/docs/5.3/getting-started/introduction/)

### Media

- The Home Page Hero Image was sourced from the Free library on Adobe Stock
- The favicon, and the images for the support cards on Self Help are a combination of Adobe Stock, freepik.com, and the Meditation card image was generated via OpenAI's Dall-E .
- The Support Pages hero image is sourced from freepik.com
