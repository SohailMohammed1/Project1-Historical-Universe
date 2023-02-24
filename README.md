![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

# **Historical Universe**

The Historical Universe webpage is a educational site for both adults and children, alike. It offers a brief insight into the timeline of the universe and aims to educate users about its birth up until its eventual death. 

Users of this website will be able to read about the Universe and look through various photos, showing different celestial bodies. On its final page, users may input any comment and offer suggestions to the developer on different things they would like to be added. 

![responsive element](/assets/css/images/responsive.jpg)

The image above demonstrates how the website will look on different devices and attests to its responsiveness. 

## **Features**
 ### **Header**
- The header contains the name of the website and this can be used as a button to navigate back to the homepage. 
- Background picture provides subtlety. 

![header](/assets/css/images/header1.jpg)

 ### **Navigation bar**
 - Placed on the top left of the page to provide easy access to other parts of the website. 
 - Navigation bar inherits similar font as header for contrast purposes. 
 - Background colour of navigation bar follows the same colour scheme as the rest of the page. 

![navigation bar](/assets/css/images/navigation_bar.jpg)

### **Main Body**
- Provides brief timeline of the Universe. 
- Follows uniform layout and colour scheme, black borders and font color as well as white background, for contrast purposes. 
- Selected sections are given pictures in order to emphasise timeline or provide real-time imagery of celestial bodies mentioned in the text it belongs to. 

![Sample of main body](/assets/css/images/body.jpg)

### **Gallery**
- Gallery provides different views of different celestial bodies, sourced from google images. 
- Gallery layout is straight forward in order to easily navigate between them. 
- Each image will automatically take users to a new tab where the image is enlarged. This is useful for users who have issues regarding vision. 
- Brief description is given under each image to provide context. 

![Gallery](/assets/css/images/gallery.jpg)

### **Contact Us**
- Final webpage allows users to input any comment, directly to the developers via form. 
- Form asks for user input if submit button is pressed prematurely and displays message urging users to not leave sections unattended.
Users can input comments or suggestions.  
- Once submit buttion is pressed, the users are told that the form went through successfully. 

![form](/assets/css/images/form.jpg)

![form submission](/assets/css/images/form_submission.jpg)

### **Footer**
- Footer provides links to different social media accounts. 
- Each icon is sourced from Font Awesome and opens a new page when pressed. 

![footer](/assets/css/images/socials.jpg)

## **Testing**
- Website has been tested on different browsers and works, accordingly. 

- I have provided evidence that the website can retain its responsive elements on multiple devices. 

- I can confirm that the features of this website are all readable and easy to understand. 

- I can confirm that the form will only allow submission on the condition that each field is filled in correctly. This includes the email field that will only accept email values. 

## **Bugs**
- The images were not loading within the gallery and the homepage. To fix this, I altered the pathway for the webpage to follow, for example:

- Previous code: 
```
 /images/Big-Bang.jpg  
```
- Improved Code: 
```
./assets/css/images/Big-Bang.jpg
```
This helped to load all the images correctly. 

## **Validator Testing**
- HTML
    - Html was put through the W3C Validator. Each page came out with no errors. 
- CSS
    - CSS was put through official (jigsaw) validator. No errors were found. 
- Accessibility
    - I can confirm that the colors and fonts are accessible and easy to read and this can be proven by running it through the lighthouse in devtools: 

![Lighthouse](/assets/css/images/lighthouse_devtools.jpg)

## **Deployment**
- The site was deployed via GitHub Pages. The method of which this took place are as follows:
    - Within the GitHub repository, navigate to Settings tab
    - Click on the pages tab, located on the left-hand side
    - Select 'Main' for Branch selection and ensure that 'root' is also selected.
    - Ensure that 'Deploy from branch' is selected, underneath the Source heading. 

The live link generated: https://sohailmohammed1.github.io/Project1-Historical-Universe/
## **Credits**

- Footer - Code sourced from the 'Love-Running' project

- Icons in footer - Sourced from font awesome

- Fonts - url('https://fonts.googleapis.com/css2?family=Merriweather&family=Nunito+Sans:wght@200&display=swap')

- Navigation bar - https://www.w3schools.com/howto/howto_css_fixed_menu.asp

- Images - All images were sourced from Google, I claim no rights to any of them

- Star gazing location format - 'Love Running' project

### **Gallery**

- Images - All images belong to NASA and the JWST organisation

- Gallery - https://www.w3schools.com/css/css_image_gallery.asp

## **Contact page**

Form - https://www.w3schools.com/howto/howto_css_contact_form.asp


