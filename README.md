#Dribbble.js
Dribbble.js is a single file, library agnositc script for adding your recent Dribbble shots to your website. Dribbble.js is written in "old fashioned" JavaScript and doesn't need jQuery or other such libraries to operate, and can therefore be dropped into any site and just work. Below is an example of to implement Dribbble.js on your website

```javascript
<script src="scripts/dribbble.js" type="text/javascript"></script>
<scripttype="text/javascript">
    getShotsForID(2151, 'shots');
</script>
```

The paramets for getShotsForID are as follows

```javascript
getShotsForID (dribble user id, element ID to add the shots to, number of shots)
```

For a more detailed example, check out the demo page source and the script file itself.