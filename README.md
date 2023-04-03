<!-- Complete this worksheet in html and css. Instructions are as comments; you may use reference_sheet.html and the internet to jog your memory on html tags and css. -->

<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>Basic HTML</title>
        <link href='https://fonts.googleapis.com/css?family=Open+Sans:300italic,400italic,600italic,400,300,600,700&subset=latin,latin-ext' rel='stylesheet' type='text/css'>
        
        <style>
        
        p {
            color: red;
            font-size: 16px;
            font-family: 'Open Sans', serif;
            width: 50%;
        }
            h1 { color:cornflowerblue; }
        #quote {
            color: magenta;
            font-style: italic;
            border: solid lightskyblue 2px;
        }

        #bargraph {
            border: 1px solid gray;
            padding-left: 10px;
            padding-bottom: 10px;
            width: 25%;
        }
        .bar_label {
            color: red;
        }
        #longest {
            width: 300px;
            height: 10px;
            background: gray;
            border: 1px solid red;
        }
        #longer {
            height: 10px;
            background: gray;
            border: 1px solid red;
        }
        #long {
            height: 10px;
            background: gray;
            border: 1px solid red;
        }
        .alert {
            border: 1px burlywood;
            width: 300px;
        }   
        #byline {
            color: indigo;
        }
        </style>
    </head>
    
    <body>
    
     <div class="alert">
       <div style="border: 10px solid red; width: 100%;">
        <h3>Breaking news: Chelsea have won the Champions League</h3>
        <p id="byline"> Reporting by JNL 221</p> 
       </div>
    
    <h1>  <div style="border: 10px solid red; width: 100%;"> 
        A little about me!</h1>
    
    <strong>It surprises many when I tell them I wasn't actually born in American or the UK. I was born in Prague, Czech Republic. My family too are all immigrants to the United States and my family is the first in my bloodline to live in the states. I attend Syracuse University and study Broadcast and Digital Journalism. I play soccer for fun and hope to become a commentator in the future<strong>
    <!-- Include: a brief intro to yourself -- where you're from, what you like to do for fun, what you're studying, and who your community or family is. -->
    <!-- Tags to use: <p>, <strong>, <i> -->
    

    <h2>My handles:</h2> </p>Twitter: Nicholas_Waley 
        Instagram: nickwaley</p>
    <!-- Include: at least two handles for your social media accounts -->
    <!-- Tags to use: <p>, <a> -->

    
    <h2> ~ Challenge: Why is my text maroon? ~</h2>
    <!-- Challenge! The text in your p tags is currently maroon. Figure out why and make it dark gray, using a hex code. (Hint: use google to find a hex code for a dark gray) When you're done, change the text in the <p> tag below to "My text is gray." -->
    <p>My text is gray.</p>


    <h2>My favorite meme</h2>
    <img src="large_wink.png">
    <!-- Include: "large_wink.png" as an image -->
    <!-- Tags to use: <img> -->
    <!-- Hint! Use 'reference_sheet.html', which you downloaded with this file, to remember how to include an image. -->

    
    <h2>Why I'm a great student</h2>
    <ul>Public speaking, Determination, Driven</ul>
    <!-- Include: Use 'reference_sheet.html' to figure out how to add an unordered list here -->
    <!-- Tags to use: <ul>, <li>, <strong> -->

    
    <h2>Top 3 most famous people from my hometown</h2>
    <li>Pavel Nedved Peter Cech Nicola Tesla</li>
    <!-- Include: an ordered list -->
    <!-- Tags to use: <ol>, <li>, <a> -->


    <h2> ~ Challenge: Read my poetry ~</h2>
    <!-- Challenge! Use the internet to figure out what a <br> tag is. Write a short poem about your college experience so far. -->
    <p>Oh, college days, how swift they flew,
From classes, friends, to books anew,
Endless nights of studying hard,
And days of fun, in the campus yard.<br>

<br>We laughed, we learned, we grew so much,
Through triumphs, failures, and every touch,
Of knowledge, life, and love so true,
Oh, college days, we'll cherish you.<br>

<br>For in those halls of ivory white,
We found our passions, our guiding light,
And met the people, who'd shape our fate,
And showed us how, to conquer hate.<br>

<br>Oh, college days, you've come to pass,
But memories of you, will forever last,
And we'll look back, with grateful heart,
For all the lessons, that we impart.<p>
    <!-- Tags to use: <p> tags for your lines of poetry, and at least two <br> tags -->
        

    
    <h2>This is one of my favorite quotes</h2>
    <!-- Include: a quote from a book -- quote should be in italics and gray, title of source should be in an <h3> tag --> <h3>“The only one who can tell you 'you can't win' is you and you don't have to listen.”—Jessica Ennis-Hill.<h3>
    <!-- Tags to use: <h3>, <p> with an id named 'quote' that is styled in the <style> section -->


    <h2>These are more of my favorite books</h2>
    <!-- Include: an unordered list of at least three books, list items should have a border --><ul>Hungar Games, Harry Potter, The Shinning</ul>
    <!-- Tags to use: <ul>, <li> with classes named 'book' that is styled in the <style> section -->
        
    <h2>Here's how I normally spend my weekend</h2>
    <!-- Include: a complete Datawrapper chart (you can make up data) showing what you normally spend time on over the weekend; must include all requirements of a complete chart (hed, subhed, intentional colors, byline, etc.) --> <iframe src=""></iframe>
    <!-- Tags to use: <iframe> --> <iframe src="l7kwN-time-wasted-during-weekend.png"></iframe>


    <h3>~ Challenge: A very simple bar graph ~</h3>
    <!-- Challenge! Add CSS styles to '#longer' and '#long' to make the bar graph look like it's ordered from longest to shortest. You may also change the h4 text and the p text to make this simple bar chart reflect real (or fake) data. -->

    <h4>Longest Popsicles</h4>

    <div id="bargraph">
        <h4>Length of Popsicles</h4>
        <p class="bar_label">Longest</p>
        <div id="longest"></div>
        <p class="bar_label">Longer</p>
        <div id="longer"></div>
        <p class="bar_label">Long</p>
        <div id="long"></div>
    </div>
     
    </body>
</html>
