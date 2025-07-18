---
title: Future Work
nav: Future Work
gallery: true
---

<br>

**Using this as a test case**, I believe there are substantial opportunities to expand on this approach in more programmatic, non-proprietary ways. 

{% include gallery-figure.html img="geo_viz_oh_05.jpg" alt="Current Oral History as Data user interface" caption="Current Oral History as Data User Interface" %}

The Oral History as Data template that was used to host and visualize the Taylor recordings is powered by enriched data, in the form of CSV transcripts with start and end timestamps as well as tag fields along the rows where those subjects occur in the dialogue. 

{% include gallery-figure.html img="geo_viz_oh_02.jpg" alt="Oral History as Data user interface with timestamped geographic element, front and back end." caption="Oral History as Data user interface with timestamped geographic element, front and back end." %}

It seems plausible to simply add a geographical coordinate field in the CSV on the line of dialogue where the location is mentioned, triggering a placemarker on a map displayed next to the transcript in the interface. These maps implement Leaflet, “an open-source JavaScript library for mobile-friendly interactive maps” that we currently use in all of our digital collections at U of I.19

<div class="symbol-container">
    <p class="symbol">&#10042;</p>
</div>

<br>

That said, Leaflet is a two dimensional, overhead map and one could argue that something is lost by not having the three dimensional context of the physical terrain. Potential solutions include using topographical Leaflet “skins” that visualize the elevation along the path of place markers alongside a traditional overhead map, such as Height Graph21 and the slightly more chaotic Leaflet-Elevation.js.22 For true 3D rendering, CesiumJS23 and Deck.gl24 are possible, non-proprietary alternatives to Google Earth Studio that can be embedded programmatically in JavaScript, just as we are with Leaflet. 

<br>

Embedding the maps programmatically and tying the geographic data to the timestamps where they are mentioned means users can go backwards, forwards and repeat as needed in the transcript rather than the linear momentum of a standard media player. Allowing researchers to essentially scratch the record back and forth on these recordings, in concert with the geographical data or drop directly into visualized subject tags, moving beyond passive narrative engagement to interactive experimentation. William G. Thomas describes this ideal digital scholarship learning environment as one where “the reader can immerse him/herself in the past, surrounded with the evidence, and … build connections versus the narrative anticipation of what comes next.”

<div class="symbol-container">
    <p class="symbol">&#10042;</p>
</div>

<br>

If we can integrate this geographic element into our OHD template, there are incredible opportunities to enhance audio and video archival resources. In the same way that these videos helped viewer comprehension of a remote area in the Taylor collection, many oral history collections would benefit from a clearer understanding of how distance shapes historical context. A project I’ve previously worked on documented the life of an “Alaskero,” a Filipino-American who worked in the Alaskan salmon canneries.26 Oral history recordings from similar migratory workers could be enhanced by visualizing the incredible distance that make up migratory circuits along Puyallup hop farms, lumber mills in Grays Harbor, and the canneries of Alaska. 

<div class="symbol-container">
    <p class="symbol">&#10042;</p>
</div>

<br>

There’s also an opportunity to combine oral history and mapping to make new insights around environmental history. Another digital initiative I contributed to, highlighted and geolocated the expeditions of the Tacoma Mountaineers, a women’s back-to-the-land hiking organization that formed in 1906 and used their monumental summits to promote suffrage.27 Mapping these expeditions as their being recounted in oral history recordings and contrasting the environment as it was in photos taken by the Mountaineers to how they are now in 3D renderings could help make evident stark contrasts in urban development, environmental policy change, access to public lands and, in direct effect, the public’s inability to organize for political empowerment. 

<div class="symbol-container">
    <p class="symbol">&#10042;</p>
</div>

<br>

Regarding corporate history and urban development, there may also be new insights gleaned by comparing different geographic “skins” within the same map to add context to oral history recordings. These could be aerial photos arranged chronologically to understand change over time. These could also incorporate “marketing maps” created by boosters and real estate agents to attract potential investors. One example is a map titled Spokane Falls and Her Natural Resources, commissioned by investors for the 1890 Northwestern Industrial Exposition. Not only does the map not account for the Great Fire, which destroyed all of downtown Spokane less than a year earlier, it also depicts a tobacco plantation alongside the timber and hops resources, a crop that could never actually be maintained in the Palouse environment.

<br>

A more recent example of a map projecting real estate imagination rather than reflecting reality is discussed in Manissa M. Maharawal and Erin McElroy’s The Anti-Eviction Mapping Project: Counter Mapping and Oral History toward Bay Area Housing Justice, describing a map created by the “luxury apartment complex NEMA—located in the "Twitter Tax Break Zone," ….  which erased Chinatown and the largely working-class southern neighborhoods of the city, and renamed the Castro, a historically gay neighborhood, as Eureka Valley/Dolores Heights. The list of such real estate-driven neoliberal fantasy maps goes on…” (381) 28 Incorporating maps into oral history projects that incorporate both early aerial maps, these “fantasy maps” and present day geographies can help us understand the ways that these imaginings of the very few have become the reality for so many. 

<div class="symbol-container">
    <p class="symbol">&#10042;</p>
</div>

<br>

More abstractly, I believe there are fresh insights that could be understood by combining oral history recordings and mapping regarding memory studies. The methodology “argues that the so-called unreliability of memory is also its strength, and that the subjectivity of memory provides clues not only about the meanings of historical experience, but also about the relationships between past and present, between memory and personal identity and between individual and collective memory.”29 Mapping oral history allows historians to create a literal mind map, understanding the interviewees’ association of one place to another, with positive or negative sentiments or whether their feelings toward that place were shaped by societal narratives or personal experiences. 

<div class="symbol-container">
    <p class="symbol">&#10042;</p>
</div>

<br>

## Conclusion

Expanding on these two experiments with these improvements, I believe there is an opportunity to reevaluate and recontextualize a wealth of oral history material. 