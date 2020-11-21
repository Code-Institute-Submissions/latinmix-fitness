# LatinMix Fitness - Testing Protocol

[Demo of Website](https://belaventer.github.io/latinmix-fitness/).
Refer to [Main project file](https://github.com/belaventer/latinmix-fitness/blob/master/README.md) for further detail.

## Automated testing

## User stories testing

## Manual testing of features
1. **Navigation Bar** feature **Header Logo**:

   | Test No. | Action & spected results | Pass / Fail |
   | --- | :---:| ---:|
   | 1.1 | From the Home page, verify the **Header Logo** is visible on the top left corner of the page. | Pass |
   | 1.2 | From the Home page, click on the **Header Logo** and verify the Home Page is loaded. | Pass |
   | 1.3 | Reapet steps 1 and 2 for all other pages and verify the same results are achieved. | Pass |

2. **Navigation Bar** feature **Navigation Links**:

   | Test No. | Action & spected results | Pass / Fail |
   | --- | :---:| ---:|
   | 2.1 | From the Home page, verify the **Navigation Links** are visible on the top right corner of the page. | Pass |
   | 2.2 | From the Home page, click on the **Home Link** and verify the Home Page is loaded. | Pass |
   | 2.3 | From the Home page, click on the **Classes Link** and verify the dropdown is shown with Links "Salsa", "Samba", "Zumba", "Forró". | Pass |
   | 2.4 | From the Home page, click on the **Classes Link** then on **Salsa** and verify the Salsa Page is loaded. | Pass |
   | 2.5 | From the Home page, click on the **Classes Link** then on **Samba** and verify the Samba Page is loaded. | Pass |
   | 2.6 | From the Home page, click on the **Classes Link** then on **Zumba** and verify the Zumba Page is loaded. | Pass |
   | 2.7 | From the Home page, click on the **Classes Link** then on **Forró** and verify the Forró Page is loaded. | Pass |
   | 2.8 | From the Home page, click on the **Plans Link** and verify the Plans Page is loaded. | Pass |
   | 2.9 | From the Home page, click on the **Contact Link** and verify the Contact Page is loaded. | Pass |
   | 2.10 | From the Home page, use the developers tool to decrease the view widht. Verify links collapse to a **Burger button** on the top right corner of the page. | Pass |
   | 2.11 | From the previous step, click on the burger button and verify the links are shown. | Pass |
   | 2.12 | Reapet steps 1 to 11 for all other pages and verify the same results are achieved. | Fail - Navbar on other pages did not have the same style as Home page as link to style.css was not initally included on other html files - **Issue fixed** |

3. **Footer** feature **Responsiveness**:

   | Test No. | Action & spected results | Pass / Fail |
   | --- | :---:| ---:|
   | 3.1 | From the Home page, verify the business **Phone and Email** information is visible on the left bottom side of the page. | Pass |
   | 3.2 | From the Home page, verify the **Social Media icons** are visible on the right bottom side of the page. | Pass |
   | 3.3 | From the Home page, use the developers tool to decrease the view widht. Verify the footer content does not break and it stacks as the screen gets narrower. | Fail - the use of bootsrap alone was not enough to fit the content, as the font size also need to be reduced. Media queries added for this purpose - **Issue fixed** |
   | 3.4 | Reapet steps 1 to 3 for all other pages and verify the same results are achieved. | Pass |

4. **Footer** feature **Social Media**:

   | Test No. | Action & spected results | Pass / Fail |
   | --- | :---:| ---:|
   | 4.1 | From the Home page, hover over the **Social Media icons** and verify each icon gets darker. | Pass |
   | 4.2 | From the Home page, click every icon and verify **Social Media home page** opens in a new tab. | Pass |
   | 4.3 | Reapet steps 1 and 2 for all other pages and verify the same results are achieved. | Pass |

5. **Hero-image** feature:

   | Test No. | Action & spected results | Pass / Fail |
   | --- | :---:| ---:|
   | 5.1 | Load the Home page and verify the **hero-image** is visible. | Pass |
   | 5.2 | Load the Home page and verify the text and horizontal rule on top of the hero images moves slightly to the right together. | Pass |

6. **Classes - Home page** feature:

   | Test No. | Action & spected results | Pass / Fail |
   | --- | :---:| ---:|
   | 6.1 | Load the Home page and verify the **Our Classes** is visible. | Pass |
   | 6.2 | From the Home page, hover over each image and verify the text about class and learn more button becomes visible. | Pass |
   | 6.3 | From the Home page, click every image and verify relevant **Class page** opens. | Pass |
   | 6.4 | From the Home page, use the developers tool to decrease the view width. Verify the images decrease to 2 by side and then stack 1 on top of each other. | Fail - the use of max/min-widht was overwritten Bootstraps column responsiveness. Div to force break added for small to large sizes - **Issue fixed**  |
   | 6.5 | From the Home page, use the developers tool to decrease the view width below 1200px. Verify the image text is alwys visible. | Fail - as border were always visible on smaller screens, for small displays with hover function a second border appeared on hover. Hover border style removed with media query. - **Issue fixed**  |

7. **Plans - Home page** feature:

   | Test No. | Action & spected results | Pass / Fail |
   | --- | :---:| ---:|
   | 7.1 | Load the Home page and verify the **Plans** section is visible. | Pass |
   | 7.2 | From the Home page, verify the price background and color is blinkig on the section heading. | Pass |
   | 7.3 | From the Home page, click the **Find your plan** button and verify the **Plans** page opens. | Pass |
   | 7.4 | From the Home page, use the developers tool to decrease the view width. Verify the sections content do not break. | Pass |

8. **Gallery - Home page** feature:

   | Test No. | Action & spected results | Pass / Fail |
   | --- | :---:| ---:|
   | 8.1 | Load the Home page and verify the **Gallery** section is visible. | Pass |
   | 8.2 | From the Home page, click the first image thumbnail and verify the full-size picture appears on the modal. Close the modal and repeat for the other four images. | Fail - the modal would show the carrousel on the last seen image. Used data-slide-to on the img element to link to correct slide - **Issue fixed** |
   | 8.3 | From the Home page, click any image, use the slide buttons at left and right and verify the previous or next image are shown. | Pass |
   | 8.4 | From the Home page, use the developers tool to decrease the view width. Verify the images stack in 2, then 3 and 5 rows. | Pass |