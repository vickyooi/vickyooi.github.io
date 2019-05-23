+++
    #this is the "front matter" of the template of a project. It's the variables associated with the file
    #this portion is written in TOML (Tom's Obvious Minimal Language)
    
    title = "Demo Reel"
    #replace takes the filename and replaces all hyphens with spaces so that when it appears on your page, it's using spaces. The filename is used in the URL and URLs can't have spaces so use hyphen in the filename.
    #title converts to title-case (using capital letters for principal words only)
    
    date = 2019-05-21T10:47:11-07:00 #the date the file was created

    
    shortDescription = "Video compilation of my works"
    projectVideo = "292454077"
    #Project video is just the unique part of the URL  
    # For example, if the link is https://vimeo.com/285189099 then the unique part is  285189099
    projectVideoType = "vimeo"
    #Enter "youtube" or "vimeo". You can add other video types as well by editing single.html 
    projectImage = "metaballs.png"
    #Enter the filename only. For example, "metropolis_album.jpg" 
    #This image should be saved in the project folder with the name of your project 
    projectImageAltText = ""
    #Alt text is the text that gets read by screenreaders for accessibility (typically for the visually impaired) 

+++

Demo Reel


<div class="embed-responsive embed-responsive-16by9">
     <iframe class="content-video embed-responsive-item" src="https://player.vimeo.com/video/292428816?title=0&byline=0&portrait=0"  frameborder="0" allow="encrypted-media; picture-in-picture; fullscreen" allowfullscreen></iframe>
</div>
<div class="video">
        <iframe src="https://player.vimeo.com/video/292428816" 
        width="640" height="360" frameborder="0" allow="autoplay; fullscreen" 
        allowfullscreen></iframe>
        <p class="page-description"><b>SPRING IN EUROPE</b> During the Spring of 2018, I had the opportunity to study abroad in London for 
            three months. While I was there, I decided to film some of the places around London, as well as the 
            countries I visited in Europe. I wanted my film to convey a strong and nostalgic feeling, therefore I’ve 
            set the color tone to appear washed out and chose the song, “Mystery of Love” by Sufjan Stevens as I 
            felt it reflected these feelings the most.</p>
             <iframe src="https://player.vimeo.com/video/282626079" 
        width="640" height="360" frameborder="0" allow="autoplay; fullscreen" 
        allowfullscreen></iframe>
        <p class="page-description"><b>ASCEND UC DAVIS</b> A video I created to promote Ascend UC Davis, a chapter of a national business 
          organization in North America. The video showcases events that Ascend UC Davis have hosted and 
          attended, including events with guest speakers from E. & J. Gallo, Edelman Digital, and FDIC. I created 
          the title transitions using Adobe After Effect and edited using Adobe Premiere. </p>
        <iframe src="https://player.vimeo.com/video/293658691" 
        width="640" height="426" frameborder="0" allow="autoplay; fullscreen" 
        allowfullscreen></iframe>
        <p class="page-description"><b>BUTTON</b> This animation was the first rotoscoping animation I made using Adobe Animate. It was 
          inspired by my nine-year-old bunny name Button. My inspiration for this video came when I was 
          watching a video of Button hopping and realized how agile and detailed a rabbit’s action is.  </p>
          <iframe src="https://player.vimeo.com/video/336651977" 
          width="640" height="360" frameborder="0" allow="autoplay; fullscreen" 
          allowfullscreen></iframe>
        <p class="page-description"><b>METABALLS</b> For this animation, I was inspired by the way cells pull apart from each other. The goal 
          of this project was to match an action to a song and after deciding upon mimicking a cell division, I 
          conveniently chose a song called “Gooey” because the balls resembled goo. Through camera works 
          and color choices, I was able to pair the music and animation together to create a simple, but 
          appealing piece.  </p>
          <iframe src="https://player.vimeo.com/video/282953322" 
          width="640" height="640" frameborder="0" allow="autoplay; fullscreen" 
          allowfullscreen></iframe>
          <p class="page-description"><b>ORANGES AS STOCKING STUFFERS</b> The first video I created for Spoon University, a nationwide 
            online food blog. “Oranges as Stocking Stuffers” explains the reasoning behind the tradition of putting 
            oranges in Christmas Stockings. It was published on the official Spoon University social medias, gaining 
            almost 100,000 views and over 100 comments on Facebook and Instagram combined. This video style
            is created in a way to emphasize the information through big, bold text and gif/pictures that matches 
            the current text on-screen. I edited this video using Adobe Premiere. </p>
</div>
a new line in markdown will not be displayed in the browser.
\
\
\ 
the lines above this line showed up because they started with backslash (NOT A NORMAL SLASH) \
  
*here's some "emphasized" text, which defaults to italics but you can make it anythign you want in css*
**here's some "strong" text, which defaults to bold but you can make it anything you want in css**

Below is a list
* asterisks make bullets
- hyphens make bullets
+ plusses make bullets
* you can choose!
