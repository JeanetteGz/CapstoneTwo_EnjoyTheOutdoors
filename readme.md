# Capstone 2: Enjoy The Outdoors

Description:
- HTML, CSS and JS project
- Involves findind national parks using dropdowns
- There are three pages, a home page, search by location/type and mountains search page

## Pages

### Home
This is the landing page for our website and it includes navigation and highlights things people can do to enjoy the great outdoors.

<p align="center" width="100%">
    <img width="70%" src="/images/ReadmeImages/home.jpeg">
</p>

## National parks
On this page, you can search for parks by selecting one of the two dropdowns. There is a State dropdown that will give you all the parks in that state and a Type Of Park dropdown that will give you the parks based on the type you choose.

<p align="center" width="100%">
    <img width="70%" src="/images/ReadmeImages/parks.jpeg">
</p>

## Mountains
In this page you can scroll throught the list of mountains by selecting the dropdown. When you see a mountain that interst you, once selected, you will get important information pertaining to that mountain.

<p align="center" width="100%">
    <img width="70%" src="/images/ReadmeImages/mountains.jpeg">
</p>
## Interesting Code Snippet

What makes this code interesting is:
- I learned how to layer my background images by using z-index.

```
    .top-image,
.bottom-image {
    width: 100%;
    background-size: cover;
    background-position: center;
    z-index: -1;
    height: 40vh;
}

.top-image {
    background-image: url('/images/NationalParks/trees-each-other-forest-covered-by-creeping-mist.jpg');
}

.bottom-image {
    background-image: url('/images/NationalParks/04_copia.jpg');
    position: fixed;
    top: 10vh;
    left: 0;
    width: 100%;
    height: 90vh;
    z-index: -2;
}
```