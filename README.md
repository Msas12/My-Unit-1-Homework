# Unit-1-Homework

## Completed Web Page

The following image shows the completed web application's appearance and functionality:


![Completed Homework Image](./assets/images/Picture1.png)



## Tasks to be Completed for Acceptance

```
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Steps to complete homework

### In HTML file

- Added comments to better describe and separate sections
- Added name of webpage to title tag
- Fixed Image tags
    - Links had incorrect endings
    - Added alt tags to all image tags
- Fixed "Search Engine Optimization link"
    - Added id tag to the div
    - Now properly jumps to correct section of page
- Fixed heading tags
    -Footer h tag was too high for a footer
- Attempted to make page mobile friendly to no avail

### In CSS File

- Added comments to better describe and separate sections
- Moved some selectors arround to better fit flow of page.
- Combined selectors that had the same attributes applied to them
    - Example: 
    .benefit-lead img, .benefit-brand img, .benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
    }
    - Instead of: 
    .benefit-lead img, {
        display: block;
        margin: 10px auto;
        max-width: 150px;
    }
    .benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
    }
    .benefit-brand img, {
     display: block;
     margin: 10px auto;
     max-width: 150px;   
     }   

## Link to Webpage 
[My Unit 1 Homework Page](https://msas12.github.io/My-Unit-1-Homework/)