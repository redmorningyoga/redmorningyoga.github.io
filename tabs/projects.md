---
layout: projects
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_projects

##### Begin Insert of the _data/content/projects/en.yml content #####
page_data:
  main:
    header: "Classes"
    info: "Yoga classes in Sydney"
    text_color: "white"
    # if you don't want to use background image, comment it. back_color will be activated.
    img: ":projects-heading.jpg"
    back_color: "light-blue"

#buttons
  category:
    - title: "Paddington"
      type: id_paddington_classes
      color: "#62b462"
      address: "EJ Ward Paddington Community Centre"
    - title: "Moore Park"
      type: id_moore_park_classes
      color: "#62b462"
      address: "Bat and Ball Oval"

  list:
    - type: id_paddington_classes
      project_name: "Paddington community Yoga"
      project_excerpt: "read more for booking"
      img: ":project1_thumb.png"
      img_title: "img title1"
      date: "Mondays 8:30-9:30 am"
      post: |
        These classes are designed to start Your week right and feel good in your own skin.
        
        
        🧘‍♀️ Only 10 spots available – **please book [here](https://calendly.com/redmorningyoga/community-yoga-at-paddington-1).**

        📍 **Location**: EJ Ward Paddington Community Centre
        
        🗓️ **When**: Every Monday from 8:30 am to 9:30 am
        
        💸 Cost: $18 per class, bring your own mat or rent for $2 per class. **First class is free!**

        🌿 What to expect:
        
        * Small, relaxed group setting (max 10 people)

        * Easy-to-follow guidance, perfect for beginners

        * Focus on flexibility, balance, and breath

        * Leave feeling calm, clear, and refreshed

    - type: id_moore_park_classes
      project_name: "Free Yoga in Sydney"
      project_excerpt: "no booking required"
      img: ":project2_thumb.png"
      img_title: "img title3"
      date: "Fridays 4:00-5:00 pm"
      post: |
        These classes are about sharing space, movement, and good energy with your body and pup!
        

        📍 **Location**: Bat and Ball Oval at Moore Park 
        
        🗓️ **When**: Every Friday from 4 pm to 5 pm
        
        💸 **Cost**: Free! Just bring a mat and a smile 

        
        🐾 What to expect:
        
        * A gentle, beginner-friendly yoga flow

        * Calm, outdoor setting with dogs running around


        Whether you're a seasoned yogi or just yoga-curious, this is a light-hearted, community-focused way to unwind with your dog and meet other locals who love         movement and furry companions. All dogs welcome — big, small, sleepy, or silly. 

        *No dog? No problem!* You're absolutely welcome to join with or without a furry friend — it's all about connection and community.

        
        🙏Donations appreciated. PayID: redmorningyoga@gmail.com



##### Finish Insert of the _data/content/projects/en.yml content #####

# publish date (used for seo)
# if not specified, site.time will be used.
#date: 2022-03-03 12:32:00 +0000

# for override items in _data/lang/[language].yml
#title: My title
#button_name: "My button"
# for override side_and_top_nav_buttons in _data/conf/main.yml
#icon: "fa fa-bath"

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-03-03 12:32:00 +0000
# check the meta_common_description in _data/owner/[language].yml
#meta_description: ""

# optional
# please use the "image_viewer_on" below to enable image viewer for individual pages or posts (_posts/ or [language]/_posts folders).
# image viewer can be enabled or disabled for all posts using the "image_viewer_posts: true" setting in _data/conf/main.yml.
image_viewer_on: true
# please use the "image_lazy_loader_on" below to enable image lazy loader for individual pages or posts (_posts/ or [language]/_posts folders).
# image lazy loader can be enabled or disabled for all posts using the "image_lazy_loader_posts: true" setting in _data/conf/main.yml.
image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false
---
