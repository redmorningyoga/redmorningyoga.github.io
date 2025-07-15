---
layout: projects
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_projects

##### Begin Insert of the _data/content/classes/en.yml content #####
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
    - title: "Church"
      type: id_church
      color: "#62b462"
      address: "Paddington Uniting Church"
    - title: "Surry Hills"
      type: id_surry_hills
      color: "#62b462"
      address: "Eddie Ward Park"
    
  list:
    - type: id_paddington_classes
      project_name: "Community Yoga in Paddington"
      project_excerpt: "read more for booking"
      img: ":paddington.jpg"
      img_title: "img title1"
      date: "Mondays, Fridays 8:30-9:30 am"
      post: |
        These classes are designed to start Your week right and feel good in your own skin.
        
        
        🧘‍♀️ Only 10 spots available – **please book [here](https://calendly.com/redmorningyoga/community-yoga-at-paddington-1).**

        📍 **EJ Ward Paddington Community Centre**
        
        🗓️ Mondays and Fridays 8:30am
        
        💸 $18 per class, BYO mat or rent for $2. **First class is free!**

        🌿 What to expect:
        
        * Small, relaxed group setting (max 10 people)

        * Easy-to-follow guidance, perfect for beginners

        * Focus on flexibility, balance, and breath

        * Leave feeling calm, clear, and refreshed



    - type: id_church
      project_name: "Yoga at the Church"
      project_excerpt: "no booking required"
      img: ":church.jfif"
      img_title: "img title1"
      date: "Wednesdays 6pm, Saturdays 9am"
      post: |
        Join me for balanced, all-levels yoga at Paddington Uniting Church — no need to book, just come along.

        📍 **Paddington Uniting Church**, 395 Oxford St

        🗓️ Wednesdays 6:00 pm and Saturdays 9:00 am

        💸 $15 per class. Mats available but limited; bring your own if possible.

        ✨ I’ll be subbing these classes from **July 19 to August 9**, and would love to see you there.

        Expect a gentle, beginner-friendly flow to help you build strength, reduce stress, and move mindfully.

    - type: id_surry_hills
      project_name: "Yoga in the Park → Matcha with new Friend"
      project_excerpt: "no booking required"
      img: ":surry_hills.JPG"
      img_title: "img title1"
      date: "Mondays 9am, starting from 8th of September"
      post: |
        Start Your Monday with Movement, Sunlight & Real Connection. Balanced yoga class in the park, followed by coffee + chats right next door.
        
        📅 Starting from September 8, every **Monday 9:00AM**
        
        📍 **Eddie Ward Park**
        
        💸 $10 yoga class, BYO mat!
        
        🧘‍♀️ Gentle beginner-friendly yoga class to start your week right, build strength, reduce stress, and move mindfully
        
        ☕ Malika Bakehouse offers **10% off** the bill for yoga friends, just show your mat!

        
##### Finish Insert of the _data/content/classes/en.yml content #####

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
