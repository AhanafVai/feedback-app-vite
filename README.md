![Desktop](/design/desktop-preview.jpg)

## Table of contents

- [Overview](#overview)

  - [The challenge](#the-challenge)
  - [Links](#links)

  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Author](#author)

## Overview

This is a feedback app. the user can provide their feedback here

### Links

- Solution URL: [Add solution URL here](https://github.com/AhanafVai/Mastercraft-Bamboo-Monitor)
- Live Site URL: [Add live site URL here](https://tubular-sfogliatella-6e2351.netlify.app)

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Vite
- React
- Mobile-first workflow

### What I learned

This was a big challange for me both the desing and functionallity gave me some hard time.

To see how you can add code snippets, see below:

```html
<div>
  <button>Back this project</button>
  <figure>
    <img src="/images/icon-bookmark.svg" alt="bookmark" />
  </figure>
</div>
```

```css
.shadow-md {
  --tw-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
  --tw-shadow-colored: 0 4px 6px -1px var(--tw-shadow-color), 0 2px 4px -2px var(--tw-shadow-color);
  box-shadow: var(--tw-ring-offset-shadow, 0 0 #0000), var(
      --tw-ring-shadow,
      0 0 #0000
    ), var(--tw-shadow);
}
```

```js (react)
// loader
const loader = (
  <div>
    <img alt="loader" />
  </div>
);

// Default Props
Example.defaultProps = {
  name: "Example",
  eyeColor: "example color",
  age: "00",
};

// Params
<Route path="/Post/:id" element={<Post />} />;
import {useParams} from "react-router-dom"
const params = useParams()

<h1>Post {params.id} </h1>

// Navigate
import {Navigate,useNavigate} from "react-router-dom"
const navigate = useNavigate()
if(x){
  navigate("/post")
}
<Navigate to="/not found">


```

### Continued development

I am willing to add a dynamic functionality to the counter.

- More focus on js.

## Author

- Github - [Ahanaf](https://github.com/AhanafVai)
