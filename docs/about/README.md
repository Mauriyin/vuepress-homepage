---
pageClass: about-page
description: 'The biography and information about me.'
avatar: /profile.jpg
head: 'Hao Yin'
info: 'Wireless System Engineer at Meta'
socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/Mauriyin
  - title: linkedin
    icon: "/icons/linkedin-mono.svg"
    link: https://www.linkedin.com/in/hao-yin-2367b0173/
  - title: Scholar
    icon: "/icons/Google_Scholar_logo.svg"
    link: https://scholar.google.com/citations?user=KnEC9NAAAAAJ&hl=en
# actions:
# - text: Projects
#   link: /projects/
# - text: Blog
#   link: https://github.com/mtobeiyf
# - text: CV
#   link: /article/
---

<AboutCard :frontmatter="$page.frontmatter" >

I am currently a Wireless System Engineer at Meta Reality Labs. I received my Ph.D. from the [Department of Electrical & Computer Engineering](https://www.ece.uw.edu/) at the [University of Washington](https://www.washington.edu/), under the supervision of Prof. [Sumit Roy](https://people.ece.uw.edu/roy/) in 2023. Prior to this, I earned my Bachelor's degree (2015-2019) from Huazhong University of Science and Technology.

My work focuses on system performance analysis and optimization for wearable hardware and mixed-mode AI applications. My research areas include scheduling and resource allocation algorithms in wireless communications, particularly in advancing next-generation 5G and Wi-Fi systems. Additionally, I am engaged in integrating machine learning algorithms into complex wireless networks to develop more sophisticated and intelligent systems for the future.

</AboutCard>

<style lang="stylus">

.theme-container.about-page .page
  background-color #e6ecf0
  min-height calc(100vh)
  
  .last-updated
    display none

</style>
