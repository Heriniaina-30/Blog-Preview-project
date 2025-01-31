# Blog-Preview-project
Blog preview from Frontend Mentor
# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![**Alt text**](screenshot_1738323006931-2.png)


### Links

- Solution URL: https://github.com/Heriniaina-30/Blog-Preview-project.git


### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox


**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

```html
 <main>
        <img src="images/illustration-article.svg" alt="">
        <button>Learning</button>
        <p>Published 21 Dec 2023</p>
        <h1>HTML & CSS foundations</h1>
        <section>
            <p>These languages are the backbone of every website, defining structure, content, and presentation.</p>
        </section>
        <div class="profile">
            <img src="images/image-avatar.webp" alt="Greg Hooper" class="profile-image">
            <div class="profile-info">
                <p class="profile-name">Greg Hooper</p>
            </div>
        </div>
    </main>
```
```css
.profile {
    display: flex;
    align-items: center;
    gap: 10px;
}

.profile-image {
    width: 30px;
    height: 30px;
    border-radius: 50%;
    object-fit: cover;
}

.profile-info {
    display: flex;
    flex-direction: column;
}

.profile-name {
    font-weight: bold;
    margin: 0;
    font-size: 14px;
}

.profile-title {
    margin: 0;
    font-size: 12px;
    color: #666;
}

