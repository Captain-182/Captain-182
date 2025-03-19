<!DOCTYPE html>
<html>
  <head>
        <title>Testing site</title>
  </head>
    <!--Body here-->
    
  <body>
     <!--Header-->
 <header>
     
    <h1>Testing site</h1>
    
    <h2>Table of content</h2>
    
       <nav>
       <ul>
           <li><a href=#Motto>Motto</a></li>
           <li><a href=#Vid&Img>Video & Images</a></li>
           <li><a href=#Audio>Audio</a></li>
       </ul>
       </nav>
       
 </header>
     <!--Main-->
 <main>
    
 <section>
    <h3 id="Motto">Motto</h3>
     <p> To test different codes and add different elements in the code. </p>
 </section>
        
        <!--Video and img-->
 <section>
        <h2 id="Vid&img">Video & Images</h2>
        
        <h3>Image</h3>
        
        <!--Image-->
   <img src="https://i.imgur.com/JJ4U0g0.png">
    <p>Is this not an error?<p>
    
   <form>
    <label for="yesimg">Yes</label>
    <input type="checkbox" id="yesimg" name="Yes">
    
    <label for="noimg">No</label>
    <input id="noimg" type="checkbox" name="No">
   </form>
    
    <br>
    
    <input type="submit" value="submit">
    
       <!--Video-->
       
       <h3>Video</h3>
       
       <p>What a title drop :o</p>
       
   <iframe width="340" height="250" 
        src="https://www.youtube.com/embed/cUpkA5peclA" 
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
        allowfullscreen>
</iframe>

    <p>How was it?</p>
    
  <form>
   <label for="Good">Good</label>
   <input id="Good" type="radio">
   
   <label fpr="Average">Average</label>
   <input id="Average" type="radio">
   
   <label for="Bad">Bad</label>
   <input id="Bad" type="radio">
   
   <br>
   
   <input type="submit" value="submit">
  </form>
  </section>
  
  <section>
  <h3 id="Audio">Audio</h3>
  
    <audio controls>
       <source src="https://www.dropbox.com/scl/fi/l5eer16wpy9naq7yiukjx/Screen_Recording_20250316_180131_Instagram_17032025.mp3?rlkey=lgygtjazrz6p4ra6aowyjcxwh&st=sxs6u91b&raw=1" type="audio/mp3">
  Your browser does not support the audio element.
    </audio>
    <br>
    <audio controls>
        <source src="https://www.dropbox.com/scl/fi/kiu35asodsw6t0fz7635y/Screen_Recording_20250318_191906_Instagram_19032025.mp3?rlkey=92saitmqn84aq6jsurabywk3e&st=0n858bgp&raw=1"
        type="audio/mp3">
  Your browser does not support the audio element
    </audio>
    <br>
    <p><b>"Haider said no"</b></p>
    <audio>
        <source src=""
        type="">
    </audio>
    
    <p>Which one did you like better?</p>
    <br>
    <form>
      <label for="audioselect">I liked</label>
     <select id="audioselect">
         <option value="Audio 1">Abdullah</option>
         <option value="Audio 2">Abubaker</option> 
         <option value="Audio 3">Haider</option>
     </select>
     <input type="submit" name="submit">
    </form>
  </section>
 </main>

    </body>
</html>
