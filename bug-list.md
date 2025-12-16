# Bug List
body showing around the edges of my divs: fixed this by setting margin and padding for the body to 0.
iframe not working: i simply didnt do it properly. in my project the iframes are done by inserting the code that is given when you press share and embed on youtube.
youtube embed not showing video error 153: it needs to be hosted in order for the youtube videos to be viewed on the website. when coding i was using the live server extension which just hosts your website locally. i highly recommend this extension because it actually refreshes the page for you when you make a save in either the html or css code.
the description (p tag) not making a new line when being too long and not being centered: fixed it by setting the max-width to the size of the iframe.
star not being centered : added display flex and align-items center to my h3 tag, which is where the star is located. this made it centered in the y axis which is what i wanted.
header not staying on screen when scrolling on mobile: changed from sticky position in the header to fixed and added margin-top to my container with the size of the header.
header not working for mobile: added flex-wrap and put the 4 genres on each side into their own div.
the text for each genre on the homepage not being centered in the y axis: added position:absolute to my h1 tag.
grid not working for mobile: added grid-template-columns: 1fr in my @media.
photo in the a tag in the grid expanding in height on mobile. added object-position.
