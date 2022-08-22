+++
title = "CV"
sort_by = "weight"
template = "section.html"
page_template = "blog-page.html"
weight = 20

[extra]
banner1 = "Curriculum Vitae"
banner2 = "Information about my publications, my education, and my teaching."
+++

# PUBLICATIONS
<div class="card">
    <table>
        <td class="flex-y"><i class="fa-solid fa-file-lines"></i></td>
      <td>
        <div class="card-title">
          Mixing Comics and Literature in Calvino's <em>Castle of Crossed Destinies</em>
        </div>
        <div class="card-date">
          September 2022 • Poetics Today
        </div>
      </td>
    </table>
        <hr>
        <div class="card-desc">I remember reading Calvino's <em>Castle</em> for the first time and thinking that it felt like a cross between a novel and a graphic novel. As it turns out, the novel has a clear precedent in the weird tradition of Italian newspaper comics. It seemed that nobody had explored the connection, so I wrote this essay to fill the gap in scholarship. The whole thing makes for an interesting bit of art-historical literary criticism, whether or not you've read the book.</div>
        <div class="flex-x">
            <div class="card-link-placeholder" href="">Coming soon!</div>
        </div>
        <!-- placeholder for links when the essay is published
        <div class="flex-x">
            <a class="card-link" href="">Read on this site</a>
            <a class="card-link" href="">Read on publisher's site</a>
            <a class="card-link" href=""><i class="fa-solid fa-file-pdf"></i> Download PDF</a>
        </div>
        -->
</div>

<div style="width: auto; height: 10px;"></div>

The essay above is my first academic publication. My work has also appeared in <a href="https://www.hobartpulp.com/web_features/to-never-speak-again"><i>Hobart</i></a>. And here's a <a href="https://killscreen.com/previously/articles/the-dizzying-art-of-the-zoom-invades-videogames/">write-up</a> for a videogame I worked on as an undergrad (with my friends <a href="https://www.thnewlands.com/">Holly</a> and Luke). 

<div style="width: auto; height: 10px;"></div>
<hr>

# EDUCATION
<div class="card">
    <table>
        <td class="flex-y"><i class="fa-solid fa-graduation-cap"></i></td>
      <td>
        <div class="card-title">
          M.A. (Master of Arts Program in the Humanities)
        </div>
        <div class="card-date">
          2020 • University of Chicago
        </div>
      </td>
    </table>
    <hr>
    <ul>
      <li>Thesis: "Mixing Comics and Literature in Calvino's <em>Castle of Crossed Destinies</em>"</li>
      <li>Research interests: modernist literature, structuralist linguistics, and narratology</li>
    </ul>
</div>
{{ 
  card(
    fa_classes="fa-solid fa-graduation-cap", 
    title="B.F.A.", 
    date="2018", 
    publisher="School of the Art Institute of Chicago",
    bullets=["Research interests: alternative comics, indie videogames, and illustration"]
  ) 
}}

<div style="width: auto; height: 15px;"></div>
<hr>

# TEACHING
{{ 
  card(
    fa_classes="fa-solid fa-person-chalkboard", 
    title="Art Teacher", 
    date="2021", 
    publisher="StudioUs (Chicago)",
    bullets=["Gave private art lessons to kids and adults, aimed at developing the skill for classical realism"]
  ) 
}}
{{ 
  card(
    fa_classes="fa-solid fa-person-chalkboard", 
    title="Writing Teacher", 
    date="2016 - 2019", 
    publisher="826CHI (Chicago)",
    bullets=["Led students ages 8 to 16 in creative writing workshops, with a focus on the joys of writing"]
  ) 
}}
