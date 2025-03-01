---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        3D Surround View
      image:
        filename: town_10_4_0_1.png
      text: |
        <br>
        
        As an ADAS, the 3D Surround View System can provide drivers with panoramic environmental information around the vehicle. We propose a 3D Surround View System based on depth information surface reconstruction.
  
  #- block: collection
  #  content:
  #    title: Latest News
  #    subtitle:
  #    text:
  #    count: 5
  #    filters:
  #      author: ''
  #      category: ''
  #      exclude_featured: false
  #      publication_type: ''
  #      tag: ''
  #    offset: 0
  #    order: desc
  #    page_type: post
  #  design:
  #    view: card
  #    columns: '1'
  
  #- block: markdown
  #  content:
  #    title: Abstract
  #    subtitle: ''
  #    text: Accurate 3D perception is essential for autonomous driving. Traditional methods often struggle with geometric ambiguity and slow convergence due to a lack of geometric prior. To address this challenge, we use omnidirectional depth estimation, which is generated by our lab's XXXNET, to introduce geometric prior. Based on the depth information, We propose a cylindrical voxel-based Sketch-Coloring framework. Additionally, our approach introduces a cylindrical voxel representation based on polar coordinate, better aligning with the radial nature of panoramic camera views. This representation adjusts voxel density according to distance, boosting the performance of close proximity. We also build a virtual scene dataset with six fisheye cameras, addressing the lack of fisheye camera dataset in autonomous driving tasks. Experimental results demonstrate that our Sketch-Coloring network significantly enhances 3D perception performance, especially in nearby regions, which makes our method a promising solution for autonomous driving perception.
  - block: markdown
    content:
      title: Novelties
      subtitle: ''
      text: <center><big><b>A novel dual-layer surface of foreground and background to restore structural information of close-range obstacles.</b></big></center> <br><p> <img  src="DUAL.png" align="center" /> </p> <br><center><big><b>An innovative texture acquisition method to address the ghosting problem in stitching</b></big></center> <br><p> <img  src="ERP(a).png" align="center" /> </p> 
  #- block: markdown
  #  content:
  #    title: Innovation Points
  #    subtitle: ''
  #    text: <p> <img  src="occ_coord.png" align="left" /> </p>    
  #- block: markdown
  #  content:
  #    title: Innovation Points
  #    subtitle: ''
  #    text: <p> <img  src="occ_dataset.png" align="left" /> </p>    
  - block: markdown
    content:
      title: Experimental Result
      subtitle: ''
      text: <center><big><b>Qualitative rusult of our proposed method</b></big></center><br><big><center> Qualitative result of simulated scenarios </center> </big><br><p> <img  src="overview.png" align="center" /> </p><br> <big><center> Close-region detail of simulated scenarios </center></big> <br> <p> <img  src="detail.png" align="center" /> </p><br><big><center> Qualitative result of real scenarios </center> </big><br><p> <img  src="real sence.png" align="center" /> </p><br> <big><center> There is a comparison video.</center> </big><br> <video src="comparison_around_car.mp4" autoplay="autoplay" loop="loop" controls="controls"></video>



  #add some unique images
    #design:
    #  columns: '1'
    #  background:
    #    image: 
    #      filename: coders.jpg
    #      filters:
    #        brightness: 1
    #      parallax: false
    #      position: center
    #      size: cover
    #      text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  #- block: collection
  #  content:
  #    title: Latest Preprints
  #    text: ""
  #    count: 5
  #    filters:
  #      folders:
  #        - publication
  #      publication_type: 'article'
  #  design:
  #    view: citation
  #    columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
