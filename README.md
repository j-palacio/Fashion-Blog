
# Fashion Blog
Welcome to the Fashion Blog project! This is a simple HTML project designed to create the underlying structure for a fashion blog. Your friend Isa, a budding fashion blogger, has requested your help to build her a new website just in time for New York Fashion Week. The project includes incorporating HTML elements like images, links, lists, and more to make the blog visually appealing and engaging.

Project Structure
The main HTML file for the project is index.html. Here's a breakdown of the structure and the elements used:

```html
Copy code
<!DOCTYPE html>
<html>
  <head>
    <title>Everyday with Isa</title>
  </head>
  <body>
    <!-- Profile Image linked to the contact section -->
    <a href="#contact"><img src="https://content.codecademy.com/courses/learn-html/elements-and-structure/profile.jpg"></a>

    <!-- Blog Post Information -->
    <h3>by Isabelle Rodriguez | 1 day ago</h3>
    <h1>An Insider's Guide to NYFM</h1>

    <!-- Main Blog Image -->
    <img src="https://content.codecademy.com/courses/learn-html/elements-and-structure/image-one.jpeg" />

    <!-- Blog Post Content -->
    <p><a href="https://en.wikipedia.org/wiki/New_York_Fashion_Week" target="_blank">NYFW</a> can be both amazingly fun & incredibly overwhelming, especially if you’ve never been. Luckily, I’m here to give you an insider’s guide and make your first show a pleasurable experience. By taking my tips and tricks, and following your gut, you’ll have an unforgettable experience!</p>

    <!-- Subheadings and Images -->
    <h2>Getting Tickets & Picking the Shows</h2>
    <img src="https://content.codecademy.com/courses/learn-html/elements-and-structure/image-two.jpeg" />
    <p>If you’re lucky or connected you can get an invite, sans the price tag. But I wasn’t so lucky or connected my first 2 years so I’m here to help you out. First, plan out which shows are most important to you and make a schedule and this is a biggie: SET A BUDGET. If you’re worrying about blowing your cash the whole time you won’t have fun. Then check out prices, days, and times and prioritize the designers you want to see most. Lastly, purchase your tickets and get excited!</p>

    <h2>Dressing for the Shows</h2>
    <img src="https://content.codecademy.com/courses/learn-html/elements-and-structure/image-three.jpeg" />
    <p>Always be true to your own sense of style, if you don’t you’ll be uncomfortable the whole time and it will show. Remember, NYFW is about expressing yourself and taking in what the designers have chosen to express through their new lines. Also it’s important to wear shoes you’ll be comfortable in all day. Obviously you want to look good, but you’ll be on your feet all day long, so be prepared.</p>

    <!-- Related Content List -->
    <h4>Related Content</h4>
    <ul>
      <li>How To Style Boyfriend Jeans</li>
      <li>When Print is Too Much</li>
      <li>The Overalls Trend</li>
      <li>Fall's It Color: Blush</li>
    </ul>

    <!-- Contact Information -->
    <div id="contact">
      <p><strong>email</strong>: isa@fashionblog.com | <strong>phone</strong>: 917-555-1098 | <strong>address</strong>: 371 284th St, New York, NY, 10001</p>
    </div>
  </body>
</html>
```

## Instructions

Profile Image Link: 
The profile image at the top of the page is linked to the contact section. Clicking on the image will take the user directly to the contact information.

Blog Post Information: The blog post includes details such as the author's name and the posting date.

Main Blog Image: A captivating image related to the blog post content is displayed prominently.

Blog Post Content: The main content of the blog post provides information about NYFW and offers tips and tricks for a pleasurable experience.

Subheadings and Images: Additional sections with subheadings and images provide more detailed information about getting tickets and picking shows.

Related Content List: A list of related content is included at the end, providing links to other blog posts.

Contact Information: The contact section at the end includes Isa's email, phone number, and address.