## What I Learned

Here are the main code snippets I used in this project:

```html
<!-- HTML structure for the photo gallery -->
<div class="gallery">
    <img src="image1.jpg" alt="Photo 1">
    <img src="image2.jpg" alt="Photo 2">
    <!-- More images -->
</div>
```

```css
/* Flexbox layout for the gallery */
.gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    align-items: flex-start;
    gap: 16px;
}

.gallery img {
    width: 200px;
    height: auto;
    border-radius: 8px;
    object-fit: cover;
}
```