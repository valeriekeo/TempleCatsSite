# TempleCatsSite

Valerie Lam
CIS 3296							

### Project Proposal

![Image of UML Diagram](https://github.com/valeriekeolam/TempleCatsSite/blob/main/ProposalUML.drawio.png)

#### Description
For the project, I am proposing the creation of a website for Temple Cats. Temple Cats is a small TNR rescue around Temple’s main campus, with approximately 16 colony locations for feral cats. The website should be an introduction to students of the colonies. The homepage will contain squares of active slideshows of the colony cats at each location. The active squares however, are also embedded hyperlinks, and when clicked, will take the user to a dedicated page for the colony, showing images of all the cats at the location (current, previous, and rehomed). Current cats will appear first, previous cats that have been rehomed or passed will be at the bottom. Alternatively, there could be a “kitty graveyard” type area of the website that contains all cats who have passed or been adopted. The location of noncurrent colony cats has yet to be decided. The dedicated colony pages will also have links to a wishlist/active donation links, so viewers can make donations, or alternatively, buy cat supplies straight out. However, the site needs a way to be updated weekly. Each colony page will have dedicated weekly updates, with status of the cats, as well as new images. 
The website is also meant to be a resource for Temple students who want to get cats, and there needs to be a way to allow large amounts of information. Although an FAQ makes sense, there may simply be too many questions and therefore potentially improbable. Some miscellaneous information (structure hasn’t been decided yet) that needs to be included is:
* Resources on what to do if you find a cat and how to care for depending on various attributes such as: immediate health, pregnancy, injury, neonatal orphans, etc.
* Resources on best vet care in the area, and how to get your pet fixed for free in Philadelphia
* Cat diseases, etc.

#### Educational Goals
The proposed project will cover the following educational goals: 
* Design Patterns: AGILE methods, will need to frequently converse with rescue coordinator for Temple Cats
* On-the-fly coding
* Access to Database: There is potential for the images of the website to live on Amazon S3 buckets, therefore placed in the cloud. Additionally, depending on how robust the website needs to be, there is also potential for the website to be hosted in the cloud with Amazon.

#### Proposed Contribution
This project was originally started by a previous student; however, I have no expectation to maintain their code, only use the reserved domain templecats.org. The website is currently hosted by Squarespace. I am not sure how the website will be hosted, but since the expectation is small traffic, there is not a demand for high availability and scalability. Therefore, it will most likely be a static website. I expect to incorporate S3 buckets to hold all of the colony images, which will ideally be private, and will be delivered via Amazon CloudFront. Alternatively, it might be a good idea to look into Zapier, which is a product that allows users to automate workflow and control the transfer of data between S3 and Squarespace. The frontend of the website will need to be completely redone, and therefore requires HTML, CSS, JavaScript
