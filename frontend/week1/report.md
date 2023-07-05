# Frontend Analysis of Moodle
## Layout
We can see that page forms a tree structure. The root node can be assumed to be the HTML document itself, which is initially divided into two parts- the head and the body.
![image](https://github.com/sabhyakhurana/summer-of-code-2023/assets/137145463/3bb1ade4-b3bc-4858-9d05-366d717746b9)

Once we further expand the head and the body, we can see several smaller elements emnating from the head and the body nodes.

- The head describes the properties of the page, but doesn't appear on the page itself. It defines the title of the webpage, the URL, and it contains most of the requests made to the server, such as CSS files for the design and JavaScript scripts. It also has the keywords and terms, which upon searching on a browser would lead to the website. It goes on to describe the general properties of the page.
![image](https://github.com/sabhyakhurana/summer-of-code-2023/assets/137145463/a0df771e-c35f-44da-bba0-2d4808192598)

- The body, on the other hand, after making a few requests for interactive elements through JS, splits the body into a header and other divisions.
![image](https://github.com/sabhyakhurana/summer-of-code-2023/assets/137145463/fbae292d-0e6e-4eaf-88bd-f3b44a0c318c)

## Layout of the Body
- The body splits into the header, the main content and the footer.
Header:
![image](https://github.com/sabhyakhurana/summer-of-code-2023/assets/137145463/bfff9441-4ac8-4831-ac6a-ae627903db2d)

Main Content:
![image](https://github.com/sabhyakhurana/summer-of-code-2023/assets/137145463/0db990f6-490e-44ec-a18b-ebfd31827203)

The body also splits into the login panel, signup panel and so on.
