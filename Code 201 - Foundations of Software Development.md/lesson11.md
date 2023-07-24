# Video, Audio, CSS, and Responsive Images.

## Video and Audio Content

1. Explain how the ability to use video and audio on the web has evolved since the early 2000's. 
    * Well for one, streaming content, whether it is audio or video, has become the most popular form of content consumption. In the early 2000's, audio and video files were mostly still attached to hardware such as CD's, with the electronic popularity of ripped mp3 files not yet taking over the mainstream.

2. Describe the use of *src* and *controls* attributes in the video element.
    * *src* works the same way as an *img* tag, while *controls* allow for the user to control the video and audio playback.

3. Why is it important to have *fallback content* inside the <video> element?
    * Because a contingency needs to be in place in the event that the browser accessing the page does not support the <video> element. In some cases, the fallback can be a direct link to the video file so at least the user can access it in some way regardless of the browser they are using.

4. Write a very short story where <audio> and <video> are characters.
    * Once upon a time, there were two lovers, audio, and video. They were disgusting, inseperable! If video was playing, audio was right there with her or right around the corner. When video wasn't able to play, she would leave fallbacks for audio to remember what he was supposed to do in her absence. 

## GRID

1. How does Grid layout differ from Flex?
    * Grid is essentially much more precise and versatile in it's useage than Flexbox. Flexbox is a one-dimensional layout whereas Grid is two-dimensional, allowing for complexity in layouts where items need to be moved around in multiple dimensions. Flex is much better for arranging things in a single dimension like a row or a column.

2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
    *  Grid container - This is the parent element that holds the grid items.
    * Grid item - These are the children elements inside of the grid container, and each item occupies one or more cells in the grid, defined by rows and columns.
    * Grid line - These are the horizontal and vertical lines that make up the structure of the grid. They also create the columns and rows.

## Responsive Images

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
    * There are a multitude of reasons, some include: Faster load times for the user, a generally much smoother user experience, accessiblity (including being mobile friendly), and even SEO (Search Engine Optimization). If your page can load faster, sometimes search engines will then prioritize it over something with full-size images that are unscalable.

2. Define the following <img> attributes *srcset* and *sizes*. Write an example of how they are used. 
    * *srcset* defines the set of images we will allow the browser to choose between, and what size each image is. Each set of image information is separated from the previous one by a comma.
    * *sizes* defines a set of media conditions and indicates what image size would be best to choose, when certain media conditions are true. 
    * Some examples for use-case would be a scenario in which you require different image resolutions for different screen sizes. Art direction is also another good example. Maybe you want to maintain focus on a particular image.

3. How is <srcset> more helpful for responsive images than CSS or JavaScript?
    * With how pages are loaded, CSS and JS are loaded first, which means any images that exist would be loaded prior to seeing what type of viewport the image will be loaded into. If the image is not responsive and dynamic, it could cause a page-breaking error, or disrupt the visual flow of the UX.
