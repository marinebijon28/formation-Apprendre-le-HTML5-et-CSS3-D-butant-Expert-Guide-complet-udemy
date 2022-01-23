#### formation udemy : Apprendre le HTML5 et CSS3 Debutant Expert Guide Complet 

### Section 3 : Learn HTML

## The HTML element head

# html structure 
Whereas now you have seen how you can write HTML code. We will only be interested in the first element in the fisrt element that we will encounter in an HTML structure, which is the head tag.

Head is simply the header. The first thing we're gonna do. I created a new file called index.html. You can see it from exploring it in an html and css course folder. You will see that I will see that I will work with this folder. You will see that I will work with this folder throughout this course and we will be able to manage the files. What interests me now is what can be placed in the head tag. It's already creating an html structure in this html file.

# doctype
The first thing the DOCTYPE.

# html
Then, we open an html tage, obviously we close it. We will place two other tags there.

# head
La première ça va être le head qu'on place toujours en premier c'est l'en-tête du fichier.

# body
Then, the tag called body. It's thee body, we've seen how it works. We are going to put a space here which will allow us to have here. My tags that are going to be indented fine.

# Data in the head tag
In this head tag. Between these two tags there. We will place elements there. In fact, which will not necessarily have a visual impact on your site, but on the other hand it will allow you to communicate information that will be useful. In particular for search engines or to indicate to the browser which encoding to use for the web page. We will only have to fill this head of the new site.

# official documentation
I encourage you to consult the official documentation, it must be a reflex each time you want to do something that you do not necessarily master. We will go to the documentation, we will go to the technology level and we will choose html on the left we always have the same things and we will go down a little. At the reference level, you have the references here. of html elements, this is what will interest us. We can observe categories. What will interest us. We will click on it, we can observe categories. What will interest us is the metadata. All that you will use inside your head tag. Besides, we can see that the head tag is there. There are things that we will imperatively use and others a little less. I'm going to go through the elements very quickly. Base will define the base url to use for the site when urls are going to be composed, we will use the base element the base url.

Head is what we are seeing that provides general metadata information about the document. 
Then we will have other links tags. The link tags. The link tag will be very interesting as it will allow us to link our html file with another. It is mainly used for example to link a css style sheet to our html page so we will use it in the second part with the css, but it can be used for something else. We'll come back to that when the time comes.
Head is what we are seeing that provides general metadata information about the document.
The meta tag, the most important tag here of the head content because the html meta element will provide a lot of information at the metadata level, it is very important for a site, especially for is other.
The style tag when you want to make css inside our file without using the link we will also come back to it. The title tag simply allows you to define a title for the html document. We are going to come back to Visual Studio Code. We will modify create our title tag. I show you right away how it works and here I will write : 


# title
<title>my awesome website</title>
I save my file for now if I do an alt + b. I had put the extension to be able to run the file. We can see here that at the level of its name it is my great website because I changed the title tag. Imagine that I changed the title tag. Imagine that I do not put this tag I will delete it temporatily. I do a ctrl + s and I re-open my page here and I updates it with the name index.html, why because I haven't defined a type for my site. Here I will defined a type for my site. Here I will defined a type for my site. Here I will define the title. I'm going to put the right indentation back and so I defined the title which makes my site when I update we will able to see that I have my great website and there. It has visual interest, but not all of what you're going to put here. For example the title is very important for search engines. You have to put a relevant name that corresponds to your site without it being too long, etc. It is necessary to put a name which corresponds to your site it is really very important and obviously for the search engines. So much for the title tag, you have understood how it works.

# meta
Then, if we go back to the documentation level, we have the meta part. This part will be of great interest to us. We can see that inside this element like the charset that we have already met. It allows to define the encoding of the web page. What I'm going to do is create a meta tag.

<meta charset="utf-8">
C'est une balise vide et évidemment je vais mettre l'attribut charset qui est égal à l'utf-8 qui est d'ailleurs le système par défaut ici de Visual Studio. It will allow you to do this if you have accent and other display problems. If you use this tag will solve the problem, it will force the browser to use utf-8 encoding. It's not very complicated, we'll go back here. We're going down. We're going down. We will see a multitude of attributes.
Content which is quite interesting which will allow us for example to associate it with another attribute it will work in pairs. I'll show you right away. htt-equiv is no longer used today. It can be seen that it is no longer recommended to use. This allows you to define the content-language. We're not going to use it anymore. We will do it together later, but not with the meta tags.
If I go down, I have the content-type, the name. The name is quite interesting and we will take an interest in it right away.

# name
What's the name ? It allows you to define metadata a description of your document. So look if I go downa little here we will see that the name can take as value : author, description, generator, keywords or generator. The most used this description. It will contain a concise and relevant summary of the web page. So how are we going to code this. We will simply open another meta tag.

<meta name="description" content="Description du site web" />
We will use name and we will say that it is equal to description. Now we will say that it is equal to description. Now we are going to see using the content attribute which works in pairs to simply assign in description what I simply want to assign in description what I simply want to assign there. I'll say it's equal to website description what I simply assign there. I'll say it's equal to website description. this is interesting not only at the referencing to help you, but also you look at a page like Google. I did a movie search query. You can see the description of the site here. It will show up in search engines. We can see that it is not very long and it is quite interesting. If I click to display the source code of the page. We will be able to see in the head that I have meta tags. I have the utf-8 charset. I will look at the level of the name description. We can see that there are others like keywords, author, etc. We have the description tag. We can see : Find all the films in the cinema, the screenings throughout France, the guide to the best films to see, the films to see on TV….
We can see that it is quite interesting, I encourage you to look at the html code of the web pages because it will allow you to understand. You can see here there is quite a bit of meta. We lower down like Twitter here, these are metas for social networks. We are not going to use it for the moment when the time comes you may be interested in it. As we can see it is quite interesting and we have a lot of value as we can see here author who defines the author of the document. This I could do, but it is not used too much, we have the description we have just used. We could use Keywords is no longer widely used because it is no longer too relevant.

<meta name="keywords" content="html, programmation, CSS" />
You can still use the name equals keywords. We will say that content is equal and there we will put keywords. Let's imagine that we make a site on HTML. For example html, programming, css, etc. You can put a lot of it. These are keywords of the tags that allow identification on it. What you need to know also you can see the official documentation for the rest, but we also have a meta for the language.

<html lang="fr">
We don't use that anymore because it's becoming obsolete. It's at the level of the html tag. We are going to declare the language attribute which is lang is for us it is fr therefore France. So that's how we're going to tell you about that again. I told you about the other link tags and all that. We will see them when the time comes.

We got around to things. We can see that it's not very complicated in this head. For the moment we will tackle two three meta. The utf and the description of the site. That's very important and this keywords we don't have to put it. We put it less and less because here the title and the meta name description. We will be able to make a description which will make a description which will make it possible to index the site at the level of search engines and to have a description. So, that's what has to be said for the element of our html file. It's not very complicated I encourage you to go see the documentation when you need to fill it a little more, but in the case of this course, we will not go further. The other metas are very specific. Here we will have a general case. We don't necessarily need meta, but we'll add some throughout this course. Well now I'll give you an appointment in the next session because there. We have seen what the head tag is. We did the trick, it's not very complicated. Now we will focus on what we can put in the body, that is to say the body of the html.