- **Project Summary:** This project is part of The Odin Project. This project involved using HTML and CSS to replicate a particular layout design, making a non-interactive landing page for desktop. The project required application of various styling and layout rules, primarily Flexbox, covered in the HTML and CSS foundations.

- **Key Features:** The web-page uses Flexbox to layout and align all its elements, to achieve as much flexibility in design as possible but using only the concepts learnt leading up to this project. While the page does not use Media Queries for mobile-specific layouts, it utilizes fluid containers and wrapping to adapt to different screen sizes.

- **Technologies And Tools Used:** As outlined above, this webpage has been made using HTML and CSS, and the tools used to make, maintain, and publish this website are Command Line (WSL), VS Code (code editor), Git (Version Control), GitHub (Remote Repository), and GitHub's feature that allows publishing web projects from public repositories.

**What I learned:**
- This project introduced me to thinking about layout from a dominantly Flexbox perspective. 

- Before working on this project, I thought that Flexbox is used to arrange only elements such as cards, Divs wrapping other elements within it etc., but while working on this project, I discovered that Flexbox is also a powerful tool for typography. I realized I could turn a text container into a flex parent to align the text vertically without relying on or rigid padding.

- The landing page layout had, for me, a somewhat difficult to implement arrangement. The main content is laid out with significant margins on the sides. This made me think of the arrangement modularly and in layers. While thinking about elements **modularly** was introduced in exercises in the preceding lesson, Alignment, thinking about layering the containers to achieve the layout was something different. I learnt that I can organize the working parts of the layout - the texts, images, etc. - along with their specific styles - font-size, font-color, font-weight, etc. - normally as I would, by modularizing them and making them flex-items of a container. However, in order to ensure that I arrange them as shown in the design image, with the huge margins on the side, I used wrappers that would wrap the flex-containers containing the working parts of the page. These wrappers were made flex-containers for the flex-containers of the working parts and used to arrange them by implementing alignment properties of Flexbox. In order to ensure that flex containers being wrapped had space to move, they were given a `max-width` property to restrict them from stretching beyond a certain size. This realization made the work of achieving the layout significantly convenient. 

**What I would like to improve**: 
- While I managed to complete this project, the process was not smooth. I was not able to plan out or visualize the layout effectively before I began coding, as in I had a sense of what I would do but not the clarity with which I can begin coding and complete it smoothly without having to think about what I was doing and what I should do next. As a result, on several instances, after being within a layer of a section, I felt lost about what I should do next or at what layer I am. I would like to be able to organize my thoughts about the project better before I delve into coding.
	    
- **Image Credits**
	- Photo by [Kristaps Ungurs](https://unsplash.com/@kristapsungurs?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/photos/aerial-view-of-a-forest-clearing-with-a-swampy-area-MEjgD0XqZ2I?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
	
    - Photo by [Ivan Stepanov](https://unsplash.com/@evil_bumblebee?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/photos/a-river-with-trees-and-grass-LN99GsoBrPQ?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
	
    - Photo by [Heather Shevlin](https://unsplash.com/@thehmstravels?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/photos/aerial-view-of-forest-ssZQiAfcw10?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
	
    - Photo by [Aamir](https://unsplash.com/@aamirbilalm?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/photos/here-is-a-caption-for-the-image-an-aerial-view-of-a-colorful-forest-kHRbUZqJV00?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)
	
    - Photo by [Jeremy Hynes](https://unsplash.com/@hynesight?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/photos/grayscale-photo-of-a-eagle-zXDw1TqWLKs?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)

