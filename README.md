# old-website
Dump of my old website.
# Reflections
  * **Landing page**: It seemed like a good idea at the time but in retrospect, a landing page that simply serves as a redirect page is wasteful / lacks purpose.
  * **About me page**: I liked the contrast of the "About Me" against the black leathery backgroun.d
  * **Work page**: The thing I liked (and wanted to retain) the most was the chatbox at the bottom right corner you often see in computer game interfaces; it was very fresh and unique in websites.

## Other Reflections (mostly on optimizations)

* **Use CDNs**: I never used any CDNs (https://gtmetrix.com/why-use-a-cdn.html and https://cdnjs.com/) in this project; based on PageSpeed Insights' advice to merge js and css files, I had merged files together to reduce overhead etc. Not a bad choice either, but quite troublesome when you have cdnjs to do it for you. Awesome!
* **Typography matters**: Typography makes or breaks a website.
* **Grey background**: While they say a greyish background is easier on the eyes, I feel that a white background ellicits more professionalism / modernism as compared to a greyish one.
* **Use CSS for animations**: Now that CSS3 has actually become more widely supported and there are more polyfills/shims in place, I think it's safe to say that CSS3 can be widely used for animation purposes; if it is not supported, the animation can be forgone for the sake of efficiency (the likelihood of the machine being old is also much higher if it is using an old browser, after all; good looking websites are probably the least of the user's worries).
* **Use frameworks... carefully**: Frameworks are good; they are used so often that their css/js/fonts are probably already cached in the user's machine. JQuery is so convenient that it is almost a sin nowadays not to use it on most websites. However, frameworks often come as one big package and some frameworks (MaterializeCSS, for example) are still very green and not optimized, which can (and will) weigh down your website unnecessarily.
  * That doesn't mean don't use frameworks, because they are very convenient; but don't use them if you're only going to use 10 or 20% of its features.