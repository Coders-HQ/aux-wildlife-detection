<p align="center">
 <img width="500" src="https://user-images.githubusercontent.com/92259277/190894050-ba6b293d-c3b0-4679-86aa-61622a4dafde.png">
 <h1 align="center">Wildlife Detection Project</h1>
</p>

<p align="center">
  <img src="https://user-images.githubusercontent.com/92259277/190902650-28f2a7d4-c243-4b69-9992-20fdc2821b32.png"/>
</p>

<h2>:memo: Table Of Contents</h2>
<ol>
  <li>Motivation</li>
  <li>Project Overview</li>
  <li>Relevant Strategies</li>
  <li>Relevant Conventions</li>
  <li>Relevant References</li>
  <li>Relevant Events</li>
  <li>Interesting Facts</li>
  <li>System Architecture</li>
  <ol>
    <li>Image Annotation Process</li>
    <li>ML Model Training And Serving</li>
    <li>Web App Development</li>
  </ol>
</ol>

<h2>:muscle: Motivation</h2>
<p>Tourism is one of the priority sectors in the <a href="https://ai.gov.ae/wp-content/uploads/2021/07/UAE-National-Strategy-for-Artificial-Intelligence-2031.pdf" target="_blank">UAE National AI Strategy 2031</a>, and Natural Reserves are direct contributors to <a href="https://u.ae/en/information-and-services/visiting-and-exploring-the-uae/what-to-do-in-the-uae/other-things-to-do-in-the-uae-/ecotourism" target="_blank">Ecotourism</a>. By 2020 there were 49 <a href="https://u.ae/en/information-and-services/environment-and-energy/environmental-protection/nature-reserves" target="_blank">nature reserves</a> in the UAE.</p>

<h2>:mag_right: Project Overview</h2>
<p>Wildlife Reserves track animals in multiple ways including camera trap images, drone footage, and GPS tracking devices:</p>

<ul>
  <li>Camera traps capture hundreds of thousands of images every year. They are usually analyzed manually to identify the species in each image. It is a labor intensive task that this platform aims to automate by a large degree.</li>
  <li>GPS tracking devices are used to study the movement behavior of a small number of animals. The tracked path is integrated with the camera trap and drone footage to give a comprehensive spatial perspective of the species behavior in the reserve.</li>
  <li>Drone footage is used by reserves to get an idea of all the species present in a specific area at a specific point in time. To get a head count of Oryx for example. This type of image/video analysis will be added to the platform at a later stage.</li>
</ul>

<p>The first phase of the project will focus on developing an AI powered web application to:</p>

<ol>
  <li>Automate species detection from camera trap images.</li>
  <li>Provide statistics on the detected images, and GPS tracking signals.</li>
  <li>Provide an easy interface for a non technical user to use the web app.</li>
</ol>

<p>The entire code of the platform will be made available on AI Code Hub as an Open Source Project.

The trained Models of Each Reserve, and Models trained on open source datasets will be available as well.

Image Datasets from each reserve might not be available as open source depending on the preference of the Reserve. DDRC do not prefer to make their data available at this stage.</p>

<h2>:chart_with_upwards_trend: Relevant Strategies</h2>
<ul>
  <li><a href="https://u.ae/en/about-the-uae/strategies-initiatives-and-awards/local-governments-strategies-and-plans/dubai-2040-urban-master-plan" target="_blank">Dubai 2040 Urban Plan</a>: 60% of Dubai to be turned into natural reserves.</li>
  <li><a href="https://www.ead.gov.ae/-/media/Project/EAD/EAD/Documents/Resources/EAD-Strategy-Report-Digital-EN.pdf" target="_blank">Enivronmental Agency – Abu Dhabi (EAD) Strategy 2021-2025</a>:</li>
  <ul>
    <li>Main Priority #7 (Slide 63):</li>
    <p>Leverage Advanced Data Analytics and Lead Environmental R&D and Outreach Activates.</p>
    <li>Under “Our Environmental Challenge/Our Scope” (slide 48):</li>
    <p><i>“To help us do all this, we will improve our <b>data collection and management capabilities</b>, including expanding our biodiversity research activities and leveraging public participation in scientific research.”</i></p>
  </ul>
</ul>

<h2>:busts_in_silhouette: Relevant Conventions (<a href="https://u.ae/en/information-and-services/environment-and-energy/environment-budget-policy-and-laws/conventions-on-environment" target="_blank">signed by the UAE Government</a>):</h2>
<ul>
  <li><a href="https://www.cbd.int/doc/legal/cbd-en.pdf" target="_blank">Convention on Biological Diversity – UN 1992</a></li>
  <li><a href="http://bch.cbd.int/protocol/background/" target="_blank">The Cartagena Protocol on Biosafety to the Convention on Biological Diversity</a></li>
  <li><a href="https://www.cms.int/#:~:text=The%20Convention%20on%20Migratory%20Species,migratory%20animals%20and%20their%20habitats.#:~:text=The%20Convention%20on%20Migratory%20Species,migratory%20animals%20and%20their%20habitats." target="_blank">Convention on the Conservation of Migratory Species of Wild Animals</a></li>
  <li><a href="https://www.cms.int/iosea-turtles/en/page/mou-text-cmp" target="_blank">Memorandum of Understanding on the Conservation and Management of Marine Turtles and their Habitats of the Indian Ocean and South-East Asia</a></li>
  <li><a href="https://www.unenvironment.org/news-and-stories/story/saving-sea-cows-helps-ensure-human-food-security" target="_blank">Memorandum of Understanding on the management and protection of Dugongs and their habitats</a></li>
  <li><a href="https://www.cms.int/raptors/en/page/agreement-text" target="_blank">Memorandum of Understanding on the Conservation of Migratory Birds of Prey in Africa and Eurasia (Raptors- MoU)</a></li>
  <li><a href="https://www.cms.int/sharks/en" target="_blank">Memorandum of Understanding on the Conservation of Migratory Sharks (Sharks MOU)</a></li>
  <li><a href="http://www.gcc-sg.org/en-us/CognitiveSources/DigitalLibrary/Lists/DigitalLibrary/Forests%20pastures%20and%20wildlife/1274593978.pdf" target="_blank">Convention on the Conservation of Wildlife and their Natural habitats in the Countries of the Gulf Cooperation Council.</a></li>
</ul>

<h2>:books: Relevant References</h2>
<ul>
  <li>https://www.ead.gov.ae/en/Knowledge-Hub/Resouces-Materials</li>
</ul>

<h2>:calendar: Relevant Events</h2>
<ul>
  <li><a href="https://www.un.org/en/observances/world-wildlife-day" target="_blank">World Wildlife Day</a>: 3<sup>rd</sup> Of March</li>
  <li><a href="https://www.un.org/en/observances/biological-diversity-day" target="_blank">International Day for Biological Diversity</a>: 22<sup>nd</sup> Of May</li>
  <li><a href="http://wam.ae/en/details/1395302657376" target="_blank">Gulf Wildlife Day / GCC Wildlife Day</a>: 30<sup>th</sup> December</li>
</ul>

<h2>:question: Interesting Facts</h2>
<ul>
  <li>The UAE has more than 5,036.24 square kilometers of protected areas. This is equivalent to 6.02 per cent of the total area of the country. <a href="https://u.ae/en/information-and-services/visiting-and-exploring-the-uae/what-to-do-in-the-uae/other-things-to-do-in-the-uae-/ecotourism" target="_blank">(Updated on 25 Nov 2021)</a></li>
  <li>In total, around 18,000 km2 of Abu Dhabi Emirate’s 67,340 km2 are already managed as protected areas. Over the next few years, we plan to expand this network, to bring even greater protection to our natural heritage. <a href="https://www.ead.gov.ae/-/media/Project/EAD/EAD/Documents/Resources/EAD-Strategy-Report-Digital-EN.pdf" target="_blank">(EAD Strategy 2021-2025)</a></li>
</ul>

<h2>:gear: System Architecture</h2>
<p>At the moment, we do not have the capacity to develop the project in house at the AI Office but we can guide the development. This project can be co-developed with:</p>
<ul>
  <li>Interns</li>
  <li>(hq) challenges</li>
  <li>www.volunteers.ae</li>
  <li>Environment Agency – Abu Dhabi – <a href="https://www.ead.gov.ae/en/Join-the-Movement/Citizens-and-Residents" target="_blank">Volunteering page</a></li>
</ul>

<p>(Block Diagram / process flow for each section)</p>

<h3>:writing_hand: Image Annotation Process</h3>
<p>
(Selection of labeling tool)<br/>
(Dataset analysis)
</p>

<p>Data Preparation:</p>
<ul>
  <li>Resizing images to fit the requirements of the selected image detection model</li>
  <li>Sorting images per species to make labeling easier</li>
</ul>

<h3>:robot: ML Model Training And Serving</h3>

<p><b>Technologies:</b></p>
<ul>
  <li>Tensorflow</li>
  <li>Keras</li>
  <li>etc</li>
</ul>

<p>Tutorial: <br/>
https://www.tensorflow.org/tfx/tutorials/serving/rest_simple <br/>
Getting Started Guide: <br/>
https://www.tensorflow.org/tfx/guide/serving</p>

<p><b>Object Detection Model:</b></p>
<p>We will use a pretrained model and modify it through transfer learning using our dataset. Existing pretrained models with tensorflow implementation: https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md</p>

<h3>:technologist: Web App Development</h3>
<p>Benchmark: <a href="http://www.wildlifeinsights.org/">Wildlife Insights</a> by Google</p>

<p>Possible Technologies:</p>
<ul>
  <li>Backend Framework: Django</li>
  <li>Database: PostgreSQL</li>
  <li>Webserver: Traefik</li>
  <li>Frontend: React</li>
  <li>Maps: Ceisum map / mapbox</li>
</ul>

<p>List Of Features:</p>
<ul>
  <li>The user can select the trained model that best suits their application. Multiple Versions of the trained models can be made available. For example: a model that only clears empty images, a model that only detects common species with very high accuracy, a model that tries to detect all species.</li>
  <li>List of Datasets available + Map displaying the locations of these datasets.</li>
  <li>Etc</li>
</ul>

<p>Dashboard GUI:</p>

<p><b>Page 1 GUI: Camera Trap Image detection:</b><br/>
  <b>Component 1:</b> The image detection model <br/>
  Browse Detection Model: ex DDRC v1.0, Snapshot Serengeti etc. <br/>
Browse Input Data folder: Unclassified images with location tag. <br/>
Browse Output Data folder: Classified images in folder + location tag added to metadata EXIF <br/>
  <b>Component 2:</b> Radio buttons that appear after the classification has been done (or after the Reserve has been selected) <br/>
  Each radio button corresponds to a species. A Radio button can be selected or deselected based by clicking on it. <br/>
  <b>Component 3:</b> Map <br/>
  Display of input data: locations of camera traps. + # of images captured by each <br/>
  Display of output data: locations of camera traps + # of each specific species captured (of the selected ones from the radio buttons) <br/>
  Layer filers: <br/>
  <ol>
    <li>Display geo fence of the natural reserve</li>
    <li>Heat map</li>
  </ol>
  <b>Component 4:</b> Statistical figures and graphs. (check Miro)
</p>

<p><b>Page 2 GUI: GPS Tracking:</b>
  <b>Component 1:</b> File upload. <br/>
  <b>Component 2:</b> Interactive map (2d or 3d) <br/>
  Display a live trace of the tracked data points. The trace should be color coded to indicate the speed. <br/>
  Option to choose: playback speed / reset from start. <br/>
  <b>Component 3:</b> Option to add the locations of the camera traps and identify potential camera traps that captured the animal being tracked. Display these potential images.
</p>

<p><b>Page 3 GUI: Drone detection:</b></p>

<p><b>Page 5 GUI: Tools</b>
<ul>
  <li>EXIF Tools to explore the metadata of a selected image</li>
</ul>
</p>
