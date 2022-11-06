# Olivia-Rodrigo-freeCodeCamp-
(New) Responsive Web Design (Tribute Page)

index.html
<main id="main">
  <h1 id="title">Olivia Rodrigo</h1>
  <div class="container">
  <figure id="img-div">
    <link rel="stylesheet" href="styles.css">
    <img id="image" src="https://www.biography.com/.image/ar_1:1%2Cc_fill%2Ccs_srgb%2Cg_face%2Cq_auto:good%2Cw_300/MTg0ODYwOTg5MDMwNjcxNDgw/gettyimages-1184956791.jpg" alt="olivia rodrigo" />
    <figcaption id="img-caption"><figcaption>Olivia Rodrigo grew up in California, where she demonstrated an early ability in music that included composing her own songs. A child actress, she landed starring roles on the TV series "Bizaardvark" and "High School Musical: The Musical: The Series." Rodrigo released the heartrending debut single "Drivers License" in January 2021. The song hit No. 1 on the Billboard Hot 100 and was the first song with more than one billion streams in 2021. She followed that up with the acclaimed album "Sour" (2021).</figcaption>
  </figure>
  <section id="tribute-info"><p>"Sour" came out on May 21, 2021, to both critical and commercial success. Rodrigo is proud of its heartfelt content, with multiple songs that address heartbreak. "I'm a songwriter who writes from a place of authenticity and truth," she declared to Billboard. "And truthfully, love and happiness and everything wasn't feelings that I was feeling at the time. And what's the point of putting out a record if it isn't something that you feel is important to say to people?" The tracks' different styles reflect the variety of Rodrigo's musical influences, which include Fiona Apple, Alanis Morissette and Green Day. 
 Rodrigo performed "Drivers License" on "The Tonight Show Starring Jimmy Fallon" in February 2021. Due to the Covid-19 pandemic, her first live performance didn't happen until the Brit Awards in the United Kingdom in May 2021. She was a success there, and as a bonus got to meet Swift. Rodrigo also was a musical performer on an episode of "Saturday Night Live" the same month.</p>
    
    <a href="https://www.youtube.com/watch?v=ZmDBbnmKpqQ" id="tribute-link" 
target="_blank">Olivia's most popular song</a>
    </section>
  </div>
</main>

style.css
body {
  background-color: #CF72CD;
  font-family: 'Merriweather', serif;
}

#main {
  color: #1d1d1d;
}
h1 {
  text-align: center;
  font-size: 64px;
  text-transform: uppercase;
}

.container {
  display: flex;
}

#img-div {
  flex: 1;
}

#tribute-info {
  flex: 1;
  font-size: 20px;
}

#image {
  display: block;
  margin: 0 auto;
  max-width: 100%;
  height: auto;
  margin-bottom: 10px;
}
