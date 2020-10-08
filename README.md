# HoriseonSEO

## Refactor (Client) Horiseon webpage HTML and CSS files for optimized design

[ PATCH 1.1 ]
DATE: 10/08/20

Summary of Changes: 
Noted that .header functioned same as Heder HTML tag
Removed class and placed formatting in Header Tag

Noted that .footer class functioned same as Footer HTML tag
Removed class and placed formatting in Footer Tag

All text in website is white except for two specific areas
Removed all color formatting and added text color format into body tag

Class .SEO is only unique individual format in the page
Changed SEO from a Class to an ID

Class .Hero is only unique individual format in the page
Changed Hero from a class to an ID

Class .footer h2 not necessary to be specifically formatted
Consolidated formatting & added black text color into footer tag

Multiple H2 (in Article) tag formatting was repititious
Consolidated formatting into H2 tag

3x classes(in Article) had reptitious formatting
Consolidated formatting into single class "Block"

Noted that .benefit class functioned same as Aside HTML tag
Removed class and placed all formatting in Aside Tag

Multiple IMG (in Aside) formatting was repititious
Consolidated formatting into Article Img tag


Multiple H3 (in Aside) tag formatting was repititious
Consolidated formatting into Aside Img tag

Multiple H3 tag (in Aside) was reptitious
Consolidated formatting into H3 tag

Header 2 (H2) tag utilized in Section & Footer
Changed Footer Header to H4


[ PATCH 1.0 ]
DATE: 10/07/20

Summary of Changes:
File: index.html updates...
-Reviewed all HTML and CSS
-Title update to represent webpage content
-Multiple Div section changed to HTML semantic labels (header, nav, figure, section, article, aside, footer)
-Renamed 3x IDs of Navbar (header) items to differentiate from class with same text
-Fixed issue with Navbar SEO HREF not jumping to below content section

File: style.css updates...
-Replaced div with semantic HTML headings to properly link functions in HTML file

