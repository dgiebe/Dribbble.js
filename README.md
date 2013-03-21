#Dribbble.js with 800x600 support
Dribbble.js is a single file, library agnositc script for adding your recent Dribbble shots to your website. 

This repository is forked by the original Dribbble.js repository. I added support for the 400 url from pictures on dribbble. Usually the script loads the 800x600 version if you upload it to dribbble. But I wanted to have all images as 400x300 at my website, without scaling down the 2x pictures. So this script checks, if an image 400 url exists and will load this one, instead of the 800 version.

```javascript
<script src="scripts/dribbble.js" type="text/javascript"></script>
<script type="text/javascript">
    getShotsForID('tim', 'shots');
</script>
```

The paramets for getShotsForID are as follows

```javascript
getShotsForID (dribble user id or username, element ID to add the shots to, number of shots)
```

For a more detailed example, check out the demo page source and the script file itself.
