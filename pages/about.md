---
layout: page
title: What is Wax?
permalink: /about/
---
For this project, we asked a question of social observation. We wondered- what is the culture of Kirkwood and how does it ebb and flow with our society? The series of 20 photos collected responded to this question in several ways, depicting religion, arts, restaurants, and closed doors. Monday through Thursday, Kirkwood is seemingly monotonous. Restaurants close fairly early, leaving the streets lacking people but ridden with lights and store signs. The photos demonstrate a culture of acceptance as many cultures and values are depicted. Kirkwood is the hub of the University and of Bloomington as a whole, and we were comforted to view the symbols of tolerance and acceptance, silently embracing and encouraging diversity in our community every day. From the surface level, it seems insignificant. However, in our community full of diverse student backgrounds, religions, etc., it is inexplicably important to represent this variety to create a sense of belonging. Kirkwood sits right in front of the Sample Gates, the entrance to Indiana University's remarkable campus. It defines our culture before one even steps foot on the campus, further emphasizing the importance of its strong first impression.          

**Wax helps you create digital exhibits.**   
A digital exhibit is a collection of curated cultural artifacts—manuscripts, paintings, photographs, sculptures, etc—often accompanied by an explicit narrative or argument. Though Wax focuses on images and text, it could be used for sound or video collections with some customization.

**Wax is an extensible workflow based on minimal computing principles.**  
Wax is hyper-aware of differences in resources, control and access around the world and close to home. As a result, it is purposefully lightweight: a few Ruby gems, some customizable UI components, good documentation and (hopefully soon!) recipes for creating, deploying, and maintaining custom digital exhibitions.

**The exhibition sites created by Wax are static.**  
This means they consist of flat HTML, CSS, and JavaScript files that don't need to communicate in a complex way back to a server. This makes them cheaper, safer, and generally easier to maintain.

**The skills needed to create Wax sites are agnostic.**  
This means they are largely transferable for use in other digital projects. 'Learning Wax' does not mean learning how to use a platform. It involves learning the fundamentals of web development, data management, and [plain text editing](https://zapier.com/blog/beginner-ultimate-guide-markdown/) while leveraging a few great open source libraries and frameworks along the way.

**Wax keeps the collection presentation separate from the collection data.**  
The Wax workflow starts with making standardized image files and metadata records and builds around them, handling canonical information, scholarly content, and site styling differently and deliberately. This makes it easier for you or others to share, reuse and reimagine your collection data in other contexts.

## Who is Wax for?

Wax was created for individuals and groups who either don't have or don't want to use a lot of resources to create their scholarly or cultural exhibits. It's best suited for folks who are willing to take on some technical responsibility in exchange for a lot of flexibility.

For beginners, Wax has a relatively high, but general-purpose learning curve. To get the most out of Wax, you should have some familiarity with:

- Using an interactive shell (e.g., Bash/Terminal) to install and interact with programs, files, and directories on your local computer.
- Using Git and GitHub to version control and collaborate on projects.
- Using Jekyll to generate static sites.
- Creating and normalizing data files (e.g., CSV, JSON, YAML)
- Using file-naming conventions and best practices.
- Editing HTML, CSS, and some JavaScript.

**However, Wax is also great for teaching or learning the skills above!** For examples of digital pedagogy via the creation of Wax exhibitions, check out [this workshop](https://studentcouncil.college.columbia.edu/events/introduction-minimal-computing-humanities-building-exhibit-primary-sources-using-wax), [this GitHub repository](https://github.com/stylerevolution/stylerevolution.github.io), and [this custom Wax site](https://stylerevolution.github.io/).

**Wax is also phenomenal for professionals who play a facilitating role**, such as Digital Scholarship Librarians or Coordinators. With some practice, Wax substantially reduces the time to production and post-production maintenance costs for you and your team. In the most common scenario, students, faculty, colleagues or any other collaborators just have to provide you with a properly formatted spreadsheet and the text for the exhibits. The extras are up to you.


## So what does the Wax workflow *look like?*

Below is a diagram to give you a zoomed-out view. In summary, you create a file of metadata records for your collection (in CSV, YAML, or JSON format), organize your collection image files, and put both in the Jekyll site folder. After updating your configuration, you run a few command line tasks to prepare the data and metadata for use by the Jekyll site. Jekyll then uses special layouts and Wax components to build the exhibit and spits them out as static pages ready to publish.

From there, you can run tests on your site to catch errors and decide where and how to put it online or in offline media.

<a href="{{ '/img/wax_workflow.jpg' | absolute_url }}">
  <img src="{{ '/img/wax_workflow.jpg' | absolute_url }}"/>
</a>
