<!-- -------================-----------------------=====================----------- -->

ALL INNER PAGES SHALL BE USING 70% 30% margin ratio of top and bottom. The pages’ content will occupy 68% of the viewport height.

ALL PAGES HAVE A FIXED BOTTOM MARGIN, LEFT MARGIN, TOP MARGIN RATIO.
THEIR CONTENT CONTAINERS ARE FIXED TO THE LEFT.

The Space Tourism Webpage

<!-- ----------------------------------------------------- -->

I’ve decided to make the multipage website in a single html file.

I will be using a single body container. The body container will be 4 times width of viewport. The overflow will be hidden.

The NAVBAR will be FIXED on top of webpage through ABOSLUTE POSTIONING.
NAVBAR INCLUDES :-

Star SVG
HR Line
Tabs for switching to other Inner Pages.
Background transparent with the filter:blur() property of CSS.

NAVBAR will not be using flexbox or grids. The positioning will be custom.

DESTINATION PAGE 01

<!-- ----------------------------------------------------- -->

This inner page’s content has the following features:

Flexbox property on the content container. The FLEX_FLOW PROPERTY WILL BE SET TO COLUMN.
Content container shall further contain two flex parents.
One shall inhabit the heading and the other will have FLEXBOX property.

FLEXBOX CONTAINER
Left Hand Side Content:
A transparent background
A responsive image aligned in the center with transform:translate.

Right Hand Side Content:
A Navbar which changes content in both sides on tab switching.
An inline-block H1 with 0.2 rem padding.
A description
HR
Flexbox again with two child containers.

CREW PAGE 02

<!-- --------------------------------------------- -->

This inner page’s content has the following elements:

Flexbox property on the content container. The FLEX_FLOW PROPERTY WILL BE SET TO COLUMN.
Content container shall further contain two divisions.
Second Division has the following content:
h2
h3
p with line height
[!important] a dotted slider which Changes CONTENT on Click FUNCTIONALITY.
Avatar

SLIDER IS LOCATED AT THE BOTTOM OF CONTAINER WITH SOME BOTTOM MARGIN.

TECHNOLOGY PAGE 03

<!-- ----------------------------------------------- -->

This inner page’s content has the following elements:

Flexbox property on the content container. The FLEX_FLOW PROPERTY WILL BE SET TO COLUMN.
--Second child container has the following elements:
The container itself will have the FLEXBOX property.
container itself has three child boxes.

1. First child box has three circular buttons in column prop.
2. Second child has H2, H1, and P.
3. Third child has an image.
   The flex% of 3 child elements are 15% + 50% + 35% approx.

<!-- =============================================== -->
<!-- =============================================== -->

COMPONENTS TO CREATE:

1. THE AVATAR CARD COMPONENT
<!-- ========================= -->
2. THE PLANET CARD COMPONENT
<!-- ---====----=-=-=-======== -->
3. THE SPACESHIP LAUNCH CARD COMPONENT

MAIN PAGE WILL BE CREATED SEPERATELY.
NAVBAR WILL BE FIXED FOR ALL PAGES.
