# Release notes

## Release V5.1 - July 07, 2019

- Brand compliance - Updated font stack and typography docs to use 'font-family: Arial,Helvetica,sans-serif;'
- Fix - Updated jquery CDN link to inlcude HTTPS//: to work locally
- Fix - fixed favicons not showing on doc pages
- Enhancement - Added favicon page detaling usage and examples how to include
- Brand compliance - updated logo on homepage to be compliant colour and aligment in corner
- Enhancement - New side navigation to allow for easy navigation around pages inc active states for current page
- Redundant - Removed graphic.html
- Redundant -  Removed headers-and-footers.html 
- Updated index.html to use small single colum for compliant line-lengh and added more useful about content.
- Grouped doc html files into catgeory specifc folders for easier navigation
- Updated navigation items to remove duplicates or incorrect categorisation i.e removed articles from layout
- Added new accessability.css file with sr-only clss for screen reader only text
- New global folder to create seperation between global styles and info/set-up pages
- Added new accessbility page detailing standards, resources and utility classes
- Removed content-media,content-form and content-video as these where not linked to and duplicates
- Added 'text-rendering: optimizeLegibility; and -webkit-font-smoothing: antialiased; on body to enhance text legibility
- Updated body copy grey colour from #222 to #4d4d4d to be compliant
- Updated small element colour from #666 to #737373 to be accessable and brand compliant
- Removed del and s tags from typography page due to know accessability issues.
- Updated info on using the em tag to reflect proper semantic meaning
- Added info on using i tag to Italicize text with no semantic meaning
- Added a tag to inline section on typography page
- Updated link colour #039 to #0e56a7 to be brand compliant
- Updated link:visited colour from #9F2563 to #e21481 to be brand compliant
- Updated mark tag off-brand yellow #FFD400 to use turquoise (lead) #068293 and white text to be brand compliant
- Added new release notes page to keep track of changes 
- Updated OU ice code snipped colours off-brand/unaccessble orange #D13E34 to use a dark grey background #262626 and white text to be brand compliant
- Added code styling in for native styling without JS
- Added reference to pre/code element within the typography page
- Updated code icon buttons to be on brand pink / consistent with interactive buttons
- Updated red #B5002E to #cd2041 to be brand compliant - categorised as UI
- Updated pink #E80074 to #e21481 to be brand compliant
- Updated dark blue #003366 to #072b54 to be brand compliant
- Updated dark grey #333333 to #262626 to be brand compliant
- Updated blue (lead) #0b55a8 to #0e56a7 to be brand compliant
- Updated grey #A7A9AC to #4d4d4d  to be brand compliant
- Updated light grey #e7eff7 to #737373  to be brand compliant
- Updated turqoise #00B0AC to #068293  to be brand compliant
- Updated orange #C5540A to #d34616  to be brand compliant
- Updated purple #4E247B to #716fb3  to be brand compliant - categorised as reserved
- Updated yellow #F4C400 to #ffd400  to be brand compliant - categorised as reserved
- Updated green #539d3c to #008A00 to be brand compliant - categorised as UI
- Updated beige #D1D1A5 to #f8f6ed to be brand compliant - categorised as UI
- Added depreciated message on non brand compliant text and background colours
- Updated light red (used on warnings and validations) #fedbdb to #fdf0f2 to be brand compliant - categorised as UI 

### Noticable design changes

- Updated mark tag off-brand yellow #FFD400 to use turquoise (lead) #068293 and white text to be brand compliant


### Developer update notes

- 'Del' element depcriated - recomend removing del element where used and replacing with alternative solution - see typography page for details
- Several colours have been made redundant as they no longer brand compliant, appropirate action should be taken to remove or remplace from sites which use these colours. See colours page for details
- Several colours have been categorised as reserved, appropirate action should be taken to ensure colours are not used unless allowed under the guidance for reserved colours. See colours page for details
- Several colours have been categorised as UI colurs, appropirate action should be taken to ensure colours are not used in ways not recomended as per the new guidance. See colours page for details


## Release V5.2 - July 10, 2019

- Article.html moved from layout to content folder
- Updated article date element colour #777 to #737373 to be brand compliant and accessable
- Updated artle border-bottom colour #ddd to #e9eaea to be brand compliant
- Deleted colour and background CSS for ou-articles--smaller class variaiton as redundant/non-brand compliant
- Information noticed added to articles.html instructing on correct use of alt text
- Added border, padding and margin to compnent previews to add clearer seperation between docs and component previews
- Removed all 'see all' buttons from artlce examples
- Added new component example 'Pattern - Articles with see all button'
- Updated example heading 'Filter: A-Z' to 'Pattern - Article with filter: A-Z'
- Updated example heading 'Filter: another example' to 'Pattern - Articles with see all button' 
- Added alt text to images which describes the links in all linked artcle examples
- Removed 'text-decoration: none' from links within article headings to meet accessablity best practises.
- Removed CSS on objects.various.css that removed underline from all heading elements.
- Removed additional elements in article examples to more clearly demonstrate component in question i.e For 'Standard, no image' the articles with images have been removed.
- Added info box regarding adding meaningful descriptive text to links on article page
- Updated light blue background #e7eff7 on stripped articles to #eef3f9 to be brand compliant
- Updated light blue background #e7eff7 references within theme--ou-blue class to #eef3f9 to be brand compliant
- Updated arrow colour on 'ou-list--arrows' #999 to #737373 to be brand compliant
- Removed colour off-brand #222 on .ou-creative
- Removed colour off-brand #666; on .ou-creative__wording
- Removed #000 color on ou-creative__title as headings are #000 by default
- Added '.ou-ice-full-preview' class to allow ful width component previews within the OI ice docs
- Clear examples with code for each variaition of the creative component on creative.html - standard, with wording, wording top and wording bottom. Added TOC component for easier navigation on page.
- Updated ou-creative background colour #f5f5f5 to #E9EAEA to be brand compliant
- Added new speerate full page examples for the 3 layouts, removing uneccassaryry components and providing clear labels for the regions
- Restrctured layout pages so they work like other pages, complete with individual code examples and image previews

### Noticable design changes

- Headings which act as links now have an underline to meet accessablility best practises. This has been done to ensure colour blind users can identify links easiliy. 

### Developer update notes

- Article alt text - Ensure meaningful alt text that describes the link NOT the image is used whenever an image is wrapped within an a tag. 