---

title: Title of the post
post_status: publish
post_excerpt: This is a post excerpt
---

## My post content

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec a lacinia orci.
Nunc sodales massa enim, nec consectetur orci tempus ac.

### Section with image

![alt text for the image](/_images/pic4.jpg "Caption for the image")

Nam rutrum ultricies sapien id rhoncus. In pellentesque efficitur suscipit.
Aliquam vel est consectetur lectus malesuada mollis sit amet non neque. 

### Section with link

This is a [relative link](../sub-dir1/post3.md) which links to another markdown post w.r.t the current file.
This is an [absolute link](/folder1/sub-dir1/post3.md) which links to another post w.r.t the root directory.

### Section with HTML


`fetch()` is a modern way to make HTTP requests in JavaScript.

## Example

```javascript
fetch('https://api.example.com/data')
  .then(res => res.json())
  .then(data => console.log(data))
  .catch(err => console.error(err));
