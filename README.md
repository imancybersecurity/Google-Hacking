# Google-Hacking
![image](https://user-images.githubusercontent.com/106005322/197342340-a8d266bc-aa6c-4b2b-bf82-ed8c792b2cae.png)

#
## What is Crawlers?
#### A web crawler, spider, or search engine bot downloads and indexes content from all over the Internet. The goal of such a bot is to learn what (almost) every webpage on the web is about, so that the information can be retrieved when it's needed. They're called "web crawlers" because crawling is the technical term for automatically accessing a website and obtaining data via a software program.
#### These bots are almost always operated by search engines. By applying a search algorithm to the data collected by web crawlers, search engines can provide relevant links in response to user search queries, generating the list of webpages that show up after a user types a search into Google or Bing (or another search engine).

#
## What is Index?
#### Search engines process and store information they find in an index, a huge database of all the content they’ve discovered and deem good enough to serve up to searchers.

#
## What is Robots.txt
#### Robots.txt is a text file with instructions for search engine crawlers. It defines which areas of a website crawlers are allowed to search. However, these are not explicitly named by the robots.txt file. Rather, certain areas are not allowed to be searched. Using this simple text file, you can easily exclude entire domains, complete directories, one or more subdirectories or individual files from search engine crawling. However, this file does not protect against unauthorized access.
#### Robots.txt is stored in the root directory of a domain. Thus it is the first document that crawlers open when visiting your site. However, the file does not only control crawling. You can also integrate a link to your sitemap, which gives search engine crawlers an overview of all existing URLs of your domain.

#
## What is Google Dorking?
#### Dork is an act of entering keywords in the Google search engine to find security holes on a website with the aim of hacking. This technique is usually called Dorking or looking for detailed information.
#### Dork is often used by hackers to find websites that are vulnerable to security (Vulnerability) which will later become targets for hacking.
#### The function of Google Dork itself is to find specific information on the website you are looking for according to the keywords entered in the Google search engine.
#### Next, how to use google dork? Google dork has many types that can be used as needed. Here's the explanation

#
# Types of Dorks

#
## Inurl & Allinurl
#### Inurl & Allinurl. Inurl is used to display the URL of the website that contains the specified keyword. For example, when looking for information about Learning Html, you can use inurl:/learn-html or allinurl:/learn-html. Then what appears is only a URL containing the keyword learn html.
![Screenshot (189)](https://user-images.githubusercontent.com/106005322/197344095-ff63e568-7ea8-4894-8b32-5829f6c661a4.png)

#
## Intitle
#### Intitle is used to display keywords that are in the title of a website. For example intitle:Hacking Tutorial. Then what appears is only websites that contain the word Hacking tutorial in the post title.

#
## Site
#### Site is used to display websites that use a certain domain. For example site:.my, only websites that use the .my domain will appear. Or it could be site:eliteghost.com.my, then all the URLs on the website will appear.

#
## Intext
#### Intext is used to display websites that contain the keywords you are looking for. For example intext:hacking, then what appears is only a website that contains the word hacking in it, whether in the url, title, or something else.

#
## Filetype
#### File type is used to search for files based on their extension, whether it's pdf, txt, or something else. For example filetype:pdf then what appears is only sites that provide pdf-type files that are ready to be downloaded.

#
# Developing Dork to Get More Accurate Information
#### You can combine several types of dorks above into one to get more accurate information.

#
## How to?
#### For example, you are looking for free ethical hacking learning books. You can use intitle:ethical hacking filetype:pdf. Then what appears are all sites that provide ethical hacking books in pdf format.
![Screenshot (190)](https://user-images.githubusercontent.com/106005322/197344954-bdd1f68a-465d-4821-a1e7-057df96bea72.png)

#
## You can develop again according to the needs you are looking for.

#### Why is Google Dork often used by hackers? As I mentioned at the opening of this article, Google Dork is commonly referred to as Google Hacking.

#### With Google Dork, a hacker can easily find out which parts of the website are vulnerable to hacking.

#### For example, they want to deface the website by using the bypass admin login method. A hacker can find where the admin login is on the website with google dork inurl:/wp-login.php.

#### After getting several websites that point to the admin login page, they can search one by one for websites whose admin logins can be bypassed.

#### If it is developed, there will be more websites that appear more specifically according to what they are looking for.






