# Code Refactor - Horiseon Website by Benjamin Wilson ✨
## Description 🤙
I have updated the Horiseon website to the clients needs and wishes, this project was fun and helped me learn more about semantic elements, data redundancy, efficency of coding, and clean code to make development in the future or for other developers easier. 

## Changes 

### Comments 💬

I have added multiple comments to both HTML file and CSS file to explain my changes and what they mean. I have also included comments for different sections of the website for ease of navigation around the code.

### HTML 🖥️

I have updated the HTML to ensure that the website is functioning as needed this includes:
- Updated broken website links in navigation
- Made sure all elements were semantic for accessibility standards
- Added descriptive alt attributes to images for webcrawlers and speech devices
- Created a title which helps describe the use of the page and what its for
- Ensured all elements follow a logical structure with good indentation

> EXAMPLE: this code shows the previous code and what updates have been made
```HTML
FROM - 
<div class="footer">
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
    </div>

TO - 
   <!-- FOOTER -->
    <footer class="footer">
        <h4>Made with ❤️️ by Horiseon</h2>
            <p>
                &copy; 2019 Horiseon Social Solution Services, Inc.
            </p>
    </footer>
```


### CSS 💻

I have updated the CSS file to improve functionallity while keeping the websites style the same this includes:
- Creating or editing existing elements that follow the same style to have the same editor in CSS which helps improve proficiency in coding
- No style values or attributes have been changes but selectors have been updated acorrdingly

> EXAMPLE: this code shows the previous code and what updates have been made

```CSS
FROM -
.benefit-lead {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-brand {
    margin-bottom: 32px;
    color: #ffffff;
}

.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

TO - 

/* making sure all aside elements follow the same style */
section aside {
    margin-bottom: 32px;
    color: #ffffff;
}
```

## Repository 📁

What i have been doing to keep my repo clean and up to date
- I have constantly used git add, commit and push to ensure all changes have been updated to the github repo
- added extensive comments describing changes and what they could possibly mean for the client or developer
- Created a high quality read me file using different methods to convey and display info

## Screenshot 📷
![Screenshot](https://user-images.githubusercontent.com/77607177/109375747-39715400-7913-11eb-8e55-8b25616f8373.png)
> *NOTE:* All changes have impacted the accessibility of the code while keeping the appearance of the website the same

## Links 🔗
[REPOSITARY](https://github.com/MarketingPlus/1-code-refactor)

[WEBSITE](https://marketingplus.github.io/1-code-refactor/)