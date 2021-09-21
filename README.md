# homework-week1-refactoring
Acceptance criteria
Webpage meets accessibility standards
Semantic HTML elements are applied
Elements follow a logical structure independent of styling and positioning
Acessible alt attributes
Heading attributes fall in sequential order
Includes concise, descriptive title

These findings and modifications to the HTML file

Structure and descriptive comments were added

<!--- Header --->
<!--- Main content --->
<!--- Additional indirect content--->
<!--- Page footer--->

Changed title to
Changed <div> for <header> tag
Changed <div> for <nav> tag in HTML, and .header nav CSS rules
Changed meetingMainImage and included into the header section.
Added empty lines to make the HTML look cleaner

Changed the content class name for mainContent both in the HTML and CSS files
Added <main> tag to group the main content
Added <footer> tag at the bottom of the page
The Benefits <div> tag was changed to <aside> tag

Added alt properties with description
Changed class search-engine-optimization to id search-engine-optimization
changed the classes benefit-lead, benefit-brand and benefit-cost to id instead
Removed the online-reputation-managment class and rules in CSS updated to id
Removed social-media-marketing class and rules in CSS updated to id
</img> was removed


Findings and modifications to the CSS file
Descriptive comments were added to the CSS file, and the css rules were clasified
/* ---------- The Header ---------- */

/* ---------- Main content ---------- */

/* ------- Additional content ------- */

/* --------- The Page Footer --------- */

Rules that were simplified into one rule:

#search-engine-optimization,
#online-reputation-management,
#social-media-marketing {
    margin-top: 20px;
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;

#search-engine-optimization img,
#online-reputation-management img,
#social-media-marketing img {
    max-height: 200px;
}

#search-engine-optimization h2,
#online-reputation-management h2,
#social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;
}

#benefit-lead,
#benefit-brand,
#benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}

#benefit-lead h3,
#benefit-brand h3,
#benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}

#benefit-lead img,
#benefit-brand img,
#benefit-cost img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

Screenshot

![HoriseonScreenShot](https://user-images.githubusercontent.com/89947774/134260921-98ba4cc2-4bed-4717-af74-3974e120902d.png)