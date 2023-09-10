---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Fala Mais Alto
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Lorem ipsum dolor sit amet. Quo autem dolor sed iure delectus ut blanditiis error. Et perspiciatis inventore et velit illo ut quos similique vel dolor dolore et fuga nihil et nesciunt nihil qui deserunt sequi. A nisi consequuntur est voluptatem laudantium id perferendis quas et quos possimus est autem nesciunt et nobis nobis. </p><p>Eos soluta atque ut esse laborum et deserunt officiis. Sed harum corrupti et distinctio dolorem aut suscipit provident? </p><p>Est doloremque officia At tempora quod aut asperiores neque id inventore saepe vel impedit nemo et obcaecati ipsa non sequi pariatur! Sit sint fuga ut corrupti iure id molestiae expedita qui amet accusantium ut quis asperiores est facere asperiores sit assumenda nobis. Eum ipsa fuga in odio dolores id nostrum provident eos nihil omnis qui eaque mollitia ut architecto nobis aut itaque nobis.

  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---