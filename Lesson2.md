# Lesson 2

## Learning Target
- I am learning how to use the CSS Box Model to control the size of elements

## Success Criteria
- I can use ```width``` and ```height``` properties to control the size of an element
- I can use ```margin``` to control the space *outside* and element and ```padding``` to control the space *inside*
- I can use ```border``` and ```border-radius``` properties to control the border of an element

### Header Section
- In your ```.header``` CSS selector, set ```height``` to ```60px``` and add ```padding-left: 20px``` and ```padding-right: 20px```
- Set a background color for the header that will look nice with the background color for the rest of the page
- Style the ```a``` tags in your header using the selector ```.header nav a```
    - Use ```text-decoration: none;``` to remove the underline from the links
    - Use ```margin-left``` and ```margin-right``` to add ```4px``` between the links

### Remove Default Margin
Some tags, such as headings and paragraphs, come with default margin. In order to be in full control over how things fit together, we want to remove this and add our own margins.  Add the following selector to the top of your CSS file:
```css
* {
    margin: 0;
    padding: 0;
}
```
The ```*``` is the *universal selector*. It applies the style rules to all HTML elements on the page. So this sets the margin and padding to zero for everything to start. We will add some margin and padding back in as we continue to style the page.

### Hero Section
- In your ```.hero``` CSS selector, set the Hero section to fill the entire screen using ```height: 100vh;```
- Adjust the ```margin``` for the heading and paragraph tags in the hero section

### Products Section
- Again, set the height of the Products section to fill the entire screen like you did with the Hero
- Set a background color that is a slight variation (darker or lighter) of your main background color

### Shop Section
- Set the height of the Shop section to be 1/2 of the screen using ```50vh```

### Footer Section
- Set the height of the Footer section to be 1/5 of the screen using ```20vh```

### Product Cards
- Create a ```.card``` selector, if you don't have one
    - Set the width to be ```280px```
    - Set a background color that is a slight variation (darker or lighter) of your Products section background color
    - Set ```border-radius``` to ```4px``` to round over the corners
- Set the width of ```<img>``` tags inside the ```card``` class to be ```280px```
- Adjust the margin of the paragraph and image to make space between the elements

### Button Class
- Add ```class="button"``` to the links in the product cards and the link in the hero section
- Style the button class to have ```20px``` padding on the left and right and ```10px``` padding on the top and bottom
- Set the background color and text color

 
