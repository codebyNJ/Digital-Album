# Digital-Album
This digital album focuses on storing your memorable images in a scrollable website that is accessible anywhere anytime and easily shareable.

## Features:

1. The whole website is hosted in your drive.
2. Highly secured until the link is shared between the people you wish is inaccessible.
3. The images are accessed from Google Drive not hosted into any public forum/platform.
4. A beautiful song of your choice can be added and will play in the background if you see your images on the website.
5. There is a greeting card at the end of each album.
6. Accessible anytime and anywhere.
7. Easily shareable.
8. Two different themes are provided:
     - Butterfly Skies (Dark Theme)
     - Pastel Ink (Light Theme)

## Replacing Images:

1. Clone the repository in your desired directory.

   ***Note: The CSS and the HTML are combined in a single html file.***

2. To add your desired photos from the default ones. It differs in both themes.
      - Butterfly Skies Theme:
        ```html
        <ul class="img-list">
        <li><span class="img-placeholder">- placeholder -</span></li>
        <li><img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/451895/009.jpg"></li>
        
        <li><img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/451895/010.jpg"></li>
        <li><img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/451895/012.jpg"></li>
        <li><span class="img-placeholder">- placeholder -</span></li>
        <li><img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/451895/015.jpg"></li>
        <li><span class="img-placeholder">- placeholder -</span></li>
        <li><img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/451895/038.jpg"></li>
        <li><img src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/451895/044.jpg"></li>
        <li></li>
        <li></li>
        <li></li>
        ```

        In the source attribute of the image tag, you can change the link. To add more images just copy and paste more li tags.
        
      - Pastel Ink Theme:
        ```html
        <div class="column">
            <img src="https://drive.google.com/thumbnail?id=1TlUByA_2dgKBwn8LetReRo_2hreHxC-E" style="width:100%;border-radius:5px;box-shadow: 2px 4px 5px #4E4E50">
               <div class="nj"> 
                    <p>Some Caption</p>
               </div>
            <img src="https://drive.google.com/thumbnail?id=1Kf0EdKdSEBQBaneaEj8uTwDFGb0ag1BV" style="width:100%;border-radius:5px;box-shadow: 2px 4px 5px #4E4E50">
               <div class="nj"> 
                    <p>Some Caption</p>
               </div>
            <img src="https://drive.google.com/thumbnail?id=1ZhH1jZYhTA7muDv9epn7Yxxyqehf-VQN" style="width:100%;border-radius:5px;box-shadow: 2px 4px 5px #4E4E50">
               <div class="nj"> 
                    <p>Some Caption</p>
               </div>
        </div>
        ```

        In the source attribute of the image tag, you can change the link. To add more columns duplicate the class column as you many times desire and the same is applicable for the image in each column just duplicate the image tag as much as you want. To change captions you can find them in the nj class.

3. To add an image as a Google Drive link, the steps are:
     - Upload the image into your drive, make it public, and then copy the link.
     - 
       ```bash
            https://drive.google.com/file/d/1wDeGWnRbBv7tAsrrCbJDJlveXgNxZu3u/view?usp=sharing
       ```
       
     - The link will look like the above one here you will FILE_ID. In this case, the FILE_ID is ***1wDeGWnRbBv7tAsrrCbJDJlveXgNxZu3u***.
     - Using the FILE_ID paste in the below URL given.
   
       ```bash
            Syntax:
            https://drive.google.com/thumbnail?id=FILE_ID-VQN
            or
            https://drive.google.com/thumbnail?export=view&id=FILE_ID

            Example:
            https://drive.google.com/thumbnail?id=1wDeGWnRbBv7tAsrrCbJDJlveXgNxZu3u-VQN
       ```
       
     - To display original-quality images via the Google Drive link, then use the below syntax.
       
       ```bash
            Syntax:
            https://drive.google.com/uc?id=FILE_ID-VQN
            or
            https://drive.google.com/uc?export=view&id=FILE_ID

            Example:
            https://drive.google.com/uc?id=1wDeGWnRbBv7tAsrrCbJDJlveXgNxZu3u-VQN
       ```

4. To add your desired song to the album you can change the link in the below code.
   ```html
   <audio controls>
      <source src="https://files.ceenaija.com/uploads/music/2024/01/Benson-Boone-Beautiful-Things-(CeeNaija.com).mp3" />
   </audio>
   ```
   - The link must end in ***.mp3*** not anything else.

5. The ***Click Your Surprise*** button can be customized according to your desired links/gifts.

## Language and Technologies:

![Static Badge](https://img.shields.io/badge/HTML-blue)   ![Static Badge](https://img.shields.io/badge/CSS-green)
![Static Badge](https://img.shields.io/badge/JavaScript-yellow)
--
![Static Badge](https://img.shields.io/badge/FullStackDev-purple)     ![Static Badge](https://img.shields.io/badge/UI%2FUX-purple)
![Static Badge](https://img.shields.io/badge/URL%20Study-purple)

#### Both the themes Link:
1. Buttefly Skies Theme:
   ![Static Badge](https://img.shields.io/badge/DNS%20Study-purple)
2. Pastel Ink Theme:
   ![Static Badge](https://img.shields.io/badge/DNS%20Study-purple)

