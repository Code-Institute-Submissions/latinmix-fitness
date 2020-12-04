# LatinMix Fitness - Testing Protocol

[Demo of Website](https://belaventer.github.io/latinmix-fitness/).

Refer to [Main project file](https://github.com/belaventer/latinmix-fitness/blob/master/README.md) for further detail.

## Code validation
- [W3C CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator/)
- [W3C Markup Validator](https://validator.w3.org/#validate_by_input)

All HTML and CSS files were validated with direct input and returned no errors at the time of this entry.


## User stories testing
1.	As a new visitor to the website, I want to easily navigate throughout all pages of the website.

![Website navigation bar](https://github.com/belaventer/latinmix-fitness/blob/master/screenshots/navigation-screenshot.png "Website navigation bar")

    - As a new visitor, I can easily navigate on the website by the Navigation Bar located at the top of each page.
    - As a new visitor, without the use of the Navigation Bar, I can also complete the following paths from Home page to contacting the business:
        Home > Class > Contact
        Home > Plans > Contact
    - As a new visitor, I can clearly idetified which page I'm on from the Heading on top of the page and the Hero Image for the Home page.

2.	As a new visitor to the website, I want to clearly identify what classes that are being offered.

![Classes cards on Home page](https://github.com/belaventer/latinmix-fitness/blob/master/screenshots/classescards-screenshot.png "Classes cards on Home page")

    - As a new visitor, I can find the four options of classes displayed on the Home page, just below the About Us section.
    - As a new visitor, I can also identify the four options available from the Navigation Bar dropdown menu under "Classes".

3.	As a potential client, I want to learn more about each individual class.

![Classes page layout](https://github.com/belaventer/latinmix-fitness/blob/master/screenshots/classespage-screenshot.png "Classes page layout")

    - As a potential client, I can click the "Learn More" button for each class to be redirected to the Class page.
    - As a potential client, I can also access the Class page from the Navigation Bar.
    - As a potential client, on the Class page, I can play a video showing of the dance style.
    - As a potential client, on the Class page, I can read more about the dance style's origin and step / beat.

4.	As a potential client, I want to easily find the directions to the facility as the business contact information.

![Business details on Contact page](https://github.com/belaventer/latinmix-fitness/blob/master/screenshots/businessdetails-screenshot.png "Business details on Contact page")

    - As a potential client, I can find the Business address as well as a interactive embbeded Google maps on the bottom of the Home page.
    - As a potential client, I can use the Navigation Bar to load the Contact page and find the same address and map.
    - As a potential client, I can scroll down to the bottom of each page and find the Business phone and email address on the footer. 
    - As a potential client, I can also access the Contact page from the individual Class or Plans pages by clicking the button "Contact Us".
    - As a potential client, I can directly contact the business by sending a form with my query.

5.	As a potential client, I want to find clear pricing and payment instructions.

![Plans page layout](https://github.com/belaventer/latinmix-fitness/blob/master/screenshots/plans-screenshot.png "Plans page layout")

    - As a potential client, I can find the price for just one class from the Home page.
    - As a potential client, I learn that are other Plans options from the Home page.
    - As a potential client, I can learn more about each plan option by clicking the button "Find you perfect paln!" on the Home page.
    - Alternatively, I can navigate to the Plans page from the Navigation Bar.
    - As a potential client, on the Plans page, I learn how payments are completed and the payment options.

6.	As an existing client, I want to be on top of all updates on classes and offers.

![Contact forms](https://github.com/belaventer/latinmix-fitness/blob/master/screenshots/contactforms-screeshot.png "Contact forms")

    - As an existing client, I navigate to the Contact page from the Navigation Bar and subscribe to the business Newsletter.

## Manual testing of features
The deployed GitHub Page website was viewed on 2 desktops screens (21 and 13 inches) and also on Motorola G6 Play device.

The website was tested with Google Chrome (v.87), Mozilla Firefox (v.83) and Microsoft Edge (v.87) browsers.

On mobile, it was viewed with Google Chrome application v.86 on Android 9.

The Developer Tools of Google Chrome (v.87) on desktop was used to verify responsiveness on different devices. Also used to Audit the web pages with Lighthouse.
Home page had a decrease Performance Audit due to large content (images). Point for improvement on future versins of website.

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

9. **Contact - Home and Contact page** feature:

   | Test No. | Action & spected results | Pass / Fail |
   | --- | :---:| ---:|
   | 9.1 | Load the Home page and verify the **Contact** section is visible. | Pass |
   | 9.2 | Verify Google Maps is displayed and can be interacted with. | Pass |
   | 9.3 | From the Home page, use the developers tool to decrease the view width. Verify the sections content do not break. | Pass |
   | 9.4 | Repeat steps 1 to 3 on the Contact page. | Pass |

10. **Forms - Contact page** feature:

   | Test No. | Action & spected results | Pass / Fail |
   | --- | :---:| ---:|
   | 10.1 | Load the Contact page and verify the **Contact Us** section is visible. | Pass |
   | 10.2 | Click on the first form button without filling any of the fiels. Verify the form is not sent and default tooltip is shown. | Pass |
   | 10.3 | Enter the name on the first form and click the button. Verify the form is not sent and default tooltip is shown. | Pass |
   | 10.4 | Enter an invalid email on the first form and verify the default tooltip is shown. | Pass |
   | 10.5 | Enter a valid email on the first form and click the button. Verify the form is not sent and default tooltip is shown. | Pass |
   | 10.6 | Click on the Selection field and verify four different options are available. Chose one option and click the button. Verify the form is not sent and default tooltip is shown.| Pass |
   | 10.7 | Enter some text on the last field and click the form button. Verify the form is sent. | Pass |
   | 10.8 | Repeat steps 2 to 4 on the second form and verify the results. | Pass |
   | 10.9 | Enter a valid email on the first form and click the button. Verify the form is sent. | Pass |
   | 10.10 | From the Contact page, use the developers tool to decrease the view width. Verify the sections content do not break. | Pass |

11. **Plans - Plans page** feature:

   | Test No. | Action & spected results | Pass / Fail |
   | --- | :---:| ---:|
   | 11.1 | Load the Plans page and verify the three options appear one after the other. | Pass |
   | 11.2 | Hover over the "Contact us now and book your first class" and verify the button changes colour. Click the button and verify the **Contact** page is loaded. | Pass |
   | 11.3 | Return to the **Plans** page, use the developers tool to decrease the view width. Verify the sections content do not break. | Pass |

12. **Video - Classes page** feature:

   | Test No. | Action & spected results | Pass / Fail |
   | --- | :---:| ---:|
   | 12.1 | Load the Salsa Class page and verify the video player is available and can be interacted with. | Pass |
   | 12.2 | Hover over the "Contact us" and verify the button changes colour. Click the button and verify the **Contact** page is loaded. | Pass |
   | 12.3 | Return to the **Salsa Class** page, use the developers tool to decrease the view width. Verify the sections content do not break. | Pass |
   | 12.4 | Repeat steps 1 to 3 for the other three classes pages and verify the results. | Pass |
