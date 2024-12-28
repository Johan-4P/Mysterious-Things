# Mysterious Things - Testing
![mockup of Mysterious Things](assets/images/mockup.png)

Visit the deployed site [Mysterious Things](https://johan-4p.github.io/Mysterious-Things/index.html)
## CONTENTS

* [AUTOMATED TESTING](#automated-testing)
  * [W3C Validator](#w3c-validator)
  * [Lighthouse](#lighthouse)
* [MANUAL TESTING](#manual-testing)
  * [Testing User Stories](#testing-user-stories)
  * [Full Testing](#full-testing)

Testing was ongoing throughout the entire build. I utilized Chrome developer tools whilst building to pinpoint and troubleshoot any issues as I went along.

During development I made use of google developer tools to ensure everything was working correctly and to assist with troubleshooting when things were not working as expected.

I have gone through each page using google chrome developer tools to ensure that each page is responsive on a variety of different screen sizes and devices.

## AUTOMATED TESTING

### W3C Validator

[W3C](https://validator.w3.org/) was used to validate the HTML on all pages of the website. It was also used to validate the CSS.

* [index.html](assets/testing/w3/W3Cindex.png) - Passed
* [tarot.html](assets/testing/w3/W3Ctarot.png) - Passed
* [rune.html](assets/testing/w3/W3Crune.png) - Passed
* [oracle.html](assets/testing/w3/W3Coracle.png) - Passed
* [question.html](assets/testing/w3/W3Cquestion.png) - Passed
* [success.html](assets/testing/w3/W3Csuccess.png) - Passed

* [style.css](assets/testing/w3/W3Ccss.png) - Passed

---

### Lighthouse

I used Lighthouse within the Chrome Developer Tools to test the performance, accessibility, best practices and SEO of the website.

### Desktop Results

varying results most because all the images i used.

### Desktop Results

* [index.html](assets/testing/w3/lighthouse/main-page.png) 
* [tarot.html](assets/testing/w3/lighthouse/tarot-page.png) 
* [rune.html](assets/testing/w3/lighthouse/rune-page.png) 
* [oracle.html](assets/testing/w3/lighthouse/oracle-page.png) 
* [question.html](assets/testing/w3/lighthouse/q-page.png) 
* [success.html](assets/testing/w3/lighthouse/succsess-page.png) 

# Mobile Results

* [index.html](assets/testing/w3/lighthouse/mobile.png) 
* [tarot.html](assets/testing/w3/lighthouse/mobile1.png) 
* [rune.html](assets/testing/w3/lighthouse/mobile2.png) 
* [oracle.html](assets/testing/w3/lighthouse/mobile3.png) 
* [question.html](assets/testing/w3/lighthouse/mobile4.png) 
* [success.html](assets/testing/w3/lighthouse/mobile5.png)


---

### Full Testing

Full Testing was performed on the following devices:

* Laptop:
    * Asus Tuf Gaming F15 15.6 inch screen.
* Mobile Devices:
    * Samsung galaxy 22 ultra.

I was using:

* Google Chrome.

Additional testing was taken by friends and family on a variety of devices and screen sizes. They reported no issues when using the website.

`Home Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Sites Logo | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| The tree card's buttons | Links to specifics page| Button clicked | The desired page opens | Pass |
| The Sites Footer-Button | Get you back to the top of the page | Button clicked | The page refreshes | Pass |
| The Sites Footer Links | Open up a new page to the desired page | Link clicked | A new page opens to correct page | Pass |

`Tarot Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Sites Logo | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| The page's carousel's arrow-left| The carousel should go left when clicked on | Arrow clicked | Carousel goes left | Pass |
| The page's carousel's arrow-right | The carousel should go right when clicked on | Arrow clicked | Carousel goes right | Pass |
| Arrows should be bigger when hoover over | Arrows become bigger | Hoover over with mouse | Arrows got bigger | Pass |
| The Sites Footer-Button | Get you back to the top of the page | Button clicked | The page refreshes | Pass |
| The Sites Footer Links | Open up a new page to the desired page | Link clicked | A new page opens to correct page | Pass |

`Rune Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Sites Logo | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| The page's carousel's arrow-left| The carousel should go left when clicked on | Arrow clicked | Carousel goes left | Pass |
| The page's carousel's arrow-right | The carousel should go right when clicked on | Arrow clicked | Carousel goes right | Pass |
| Arrows should be bigger when hoover over | Arrows become bigger | Hoover over with mouse | Arrows got bigger | Pass |
| The Sites Footer-Button | Get you back to the top of the page | Button clicked | The page refreshes | Pass |
| The Sites Footer Links | Open up a new page to the desired page | Link clicked | A new page opens to correct page | Pass |

`Oracle Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Sites Logo | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| The page's carousel's arrow-left| The carousel should go left when clicked on | Arrow clicked | Carousel goes left | Pass |
| The page's carousel's arrow-right | The carousel should go right when clicked on | Arrow clicked | Carousel goes right | Pass |
| Arrows should be bigger when hoover over | Arrows become bigger | Hoover over with mouse | Arrows got bigger | Pass |
| The Sites Footer-Button | Get you back to the top of the page | Button clicked | The page refreshes | Pass |
| The Sites Footer Links | Open up a new page to the desired page | Link clicked | A new page opens to correct page | Pass |

`Question Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Sites Logo | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| If you forgot to insert letters in the form you can't proceed | A message comes up and tell you to: fill in this field| Missed a field | A message comes up and tell you to: fill in this field | Pass |
| If all fields correct you can submit | You goes to Success Page | Fill all fields and pushed submit | You comes to Success Page | Pass |
| The Sites Footer-Button | Get you back to the top of the page | Button clicked | The page refreshes | Pass |
| The Sites Footer Links | Open up a new page to the desired page | Link clicked | A new page opens to correct page | Pass |

`Success Page`

| Feature | Expected Outcome | Testing Performed | Result | Pass/Fail |
| --- | --- | --- | --- | --- |
| The Sites Logo | Link directs the user back to the home page | Clicked title | Home page reloads | Pass |
| Thank you message comes up with button "Return to the home page" | Push button and you go to the home page | Pushed button | You comes to home page | Pass |
| The Sites Footer-Button | Get you back to the top of the page | Button clicked | The page refreshes | Pass |
| The Sites Footer Links | Open up a new page to the desired page | Link clicked | A new page opens to correct page | Pass | 