Photo Gallery with Objects
==========================

Build an array called 'myPhotos'. The array should contain at least 7 objects where each object corresponds to a photo in your gallery. You should have the following properties:

```
{
	source: "image1.gif",
	caption: "caption about image 1 here",
	tags: "beach, ocean, outdoors"
}
```

1. Write a loop that goes through the myPhotos array and displays each image on the page.
2. Create a search box at the top of the page. 
3. When a user types into the search box, run a function that searches through myPhotos (the array of objects) and checks if the searched value is contained within the caption OR the tags for each photo object. This should be _case insensitive_. If a photo's caption or tags contain the search term, add a green border with rounded corners (border-radius) using jQuery's .css() method using objects. If the search box is empty, none of the images should have the green border or rounded corners.

### Optional (not for EC)

Somewhere on the page, display all unique tags under a section called "Tags". There are many ways to do this but I'll let you decide how to go about implementing this.