# HTML-CSS-refractor
Code Refractor
Steps taken in index.html :
1. Changed the heading tag to just <heading>
2. Changed the title tag from website to Horiseon for search engine optimization.
3. Changed the div tag to nav tag in line 13 and closed it by /nav in line 25
4. Changed     <div class="content"> to <main>
5. Changed div tags into section  in line 32-58
6. Changed the search-engine-optimizaition and gave it an id with a class= "service"
7. Gave message a alt section in case image fails
8. changed the benefits from div to aside to make it like a sidebar
9. Changed the div class footer tag to just footer
10. Chagned the benefit cost, benefit lead and benefit brand to just benefit and added an alt
11. Images are not self closing so deleted img on line 79


Steps taken in style.css:
1. changed the class tag of all .header to header tags
2. changed header div to header nav to accommodate for step 3 in html code
3. Image was breaking so changed the .content in line 72 to main
4. also deleted the seo,smm,orm and replace with 1 .service command for efficiency displayed below
.service {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;

   
 5. changed line 146 to .service img in order for all of them to use the same rule
6. Repeated this same step for h2
7. Step 9 in html makes for the change of .footer into a footer
8. Adjusted for some repitiion for the benefit