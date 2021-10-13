
# SSD ASSIGNMENT-2 PART B


#### 1) Tools Used
`Bootstrap` `Jquery`

#### 2)Features of Website
`Home` : Home tab include an interactive carousel and live twitter feed alongwith some static data. Home tab can serve as starting point of the website.<br />
`People` : People tab has various subsections like faculty, PHD students , MS students etc. Each subsections shows some dummy profiles. Clicking on the profile redirects to profile.html which laods data dynamically from remote json file. Currently for demonstration purpose profile.html uses [Json](https://data-host.github.io/data/profile.json).
`Publications` : Publication tab dynamically loads data of different faculty members from [DBLP](https://dblp.org/). These entries can be further categorized based on year of publication. Publication tab also has admin mode, whoose feture is discussed below.
`Focus Areas` : Focus Area shows various areas with auto ZOOM IN feature.
`Events` : Events tabs show a fun and interactive calendar. This calendar can bifurcate events based on hours, days, weeks, months. Data for events can also be laoded dynamically from xml or json(not implemented).
`Resources` : Resources show subsection project, which loads different type of projects from remote json file. Further admin privileges in project section allows user to add new project. Other sections of resources tab loads static data as in [SERC](https://serc.iiit.ac.in)
`Contacts` : A static contact page.

#### 3)Admin Mode
Admin mode can be used on `./publication/index.html` & `./resources/project.html`. Upon entering admin mode a new form appears below side navbar, which can be used to add new publication & project respectively. Refreshing the page exits admin mode and all the changes made during that period.

#### 4)Directory Structure
All the static Javascript\CSS libraries and images are inside `assets` folder. Further rendering resources various sections of website are stored inside corresponding folder name. `index.html` can be considered starting point or root of website.
