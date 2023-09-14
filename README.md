# Thinkfulbnb

Thinkfulbnb is a vacation rental website that allows people to rent out their homes to people who are seeking short-term accommodations in that locale. Thinkfulbnb hosts rent out different kinds of properties, including single rooms, apartments, and unique living spaces such as yachts, houseboats, yurts, tiny houses, and even renovated medieval castles.

For this assignment, I implemented Thinkfulbnb's landing page in HTML & CSS. This website was created with a mobile-first development approach. Flexbox was used to achieve the desired layouts.

## Links
- [Live Demo](https://angelalouh.github.io/project-thinkfulbnb/)

## Thinkfulbnb Views

The UX designer provided the following user interface mockups:

### Mobile view:

![mobile view](images/Thinkfulbnb-mobile.png)

### Desktop view:

![desktop view](images/Thinkfulbnb-desktop.png)

### Features:
#### Navigation

- The logo stacks on top of the menu links, which are aligned horizontally, as follows:

![Navigation mobile](./images/navigation-mobile.png)

- **Single-page navigation**: The navigation links were modified so that clicking on each link would take the user to the corresponding sections on the page, as follows:

| Link clicked | Take the user to the section with `id` of |
| ------------ | ----------------------------------------- |
| `Stay`       | `id="stay"`                               |
| `About`      | `id="about"`                              |
| `Ideas`      | `id="ideas"`                              |
| `Host`       | `id="host"`                               |

#### HTML form

- In the "Find your perfect vacation rental" section, a form was created with the following input fields and specified types:

  - `Location`: `text` input type, with a placeholder value of "Search destination"
  - `Arrive`: `date` input type
  - `Depart`: `date` input type
  - `Type`: a dropdown list with the following options:
    - Apartment
    - Barn
    - Castle
    - Houseboat
    - Tiny House
    - Yacht
    - Yurt
  - a `"Search"` button

- CSS was added to the form so that the labels (i.e., "Location", "Arrive", "Depart", "Type") and their corresponding form fields are aligned towards the opposite ends of each row

The final form design appears like this:

![Search form mobile](./images/search-form-mobile.png)

#### Vertical content alignment

- The content in the remainder of the sections (i.e., "About", "Ideas", "Want to become a Thinkfulbnb Host?"), including any text and images, stack on top of each other.

#### Responsive images

- CSS was written for all images so that the images would match whatever container width they are placed within, and changing the container sizes would update the image sizes appropriately.

#### Media query: Desktop view

The design was also adapted for a desktop view.

- Created a media query for screens that are wider than `480px`.

Within the media query, CSS was written to create the following designs for desktop:

- The logo and the navigation menu links are spaced apart from each other, like this:

![Navigation desktop](./images/navigation-desktop.png)

- The search form input fields and the button are horizontally aligned, like this:

![Search form desktop](./images/search-form-desktop.png)

- The items in the "About" section are horizontally aligned. The paragraph content is vertically centered and is always about twice as wide as each image item, like this:

![About desktop](./images/about-desktop.png)

- The "Ideas" images are displayed in a 2 by 2 grid (see the desktop design shared above).

- The items in the "Want to Become a Thinkful Host?" section are horizontally aligned. The paragraph content is vertically centered and is as wide as each image item, like this:

![Host desktop](./images/host-desktop.png)

## Technology
### Built With:
- HTML & CSS
