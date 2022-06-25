---
pageClass: home-page
# some data for the components

name: Hao Yin
profile: /profile.jpg

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/Mauriyin
  - title: linkedin
    icon: "/icons/linkedin-mono.svg"
    link: https://www.linkedin.com/in/hao-yin-2367b0173/
  - title: Google Scholar
    icon: "/icons/scholar.svg"
    link: https://scholar.google.com/citations?user=KnEC9NAAAAAJ&hl=en

cv: https://en.wikipedia.org/wiki/Harry_Potter
bio: Phd Candidate at University of Washington
email: haoyin (at) hogwarts (dot) edu
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me
I am a research assistant and Ph.D. candidate in the [department of electrical & computer engineering](https://www.ece.uw.edu/) at the [University of Washington](https://www.washington.edu/), under the supervision of Prof. [Sumit Roy](https://people.ece.uw.edu/roy/) since 2019. Before this, I received my Bachelor's degree (2015-2019) from Huazhong University of Science and Technology.
              
My research mainly focuses on the scheduling and resource allocation algorithms in wireless communication, especially for the next generation 5G and Wi-Fi systems. I am also working on applying machine learning algorithms to complex wireless systems to build more intellegent wireless system in the future.

## News

- [Jun 2022] Present our work on 6 GHz Wi-Fi in [WNS3 2022](https://www.nsnam.org/research/wns3/wns3-2022/program/)
- [Apr 2022] We offered the tutorial for the ns-3 Wi-Fi simulation at [ACMSE](https://acmse.net/2022/tutorials-offered/#tut-work04)
- [Jun 2021] We offered the tutorial for the ns3-ai model at [WNS3 2021](https://www.nsnam.org/research/wns3/wns3-2021/tutorials/)


## Education

- **University of Washington, Seattle, USA** <br/>
PhD, ECE, Sept 2019 - Present
- **University of Washington, Seattle, USA** <br/>
MS, AMATH, March 2021 - Present
- **Huazhong University of Science and Technology, Wuhan, China** <br/>
BS, Sept 2015 - Jun 2019

## Experience

- **Meta, TED wireless Team**, Jun 2022 - Sept, 2022, Sunnyvale, CA
  - HW Product Engineer Intern
  - Working on the optimization of Wi-Fi network for XR scenarios.

- **Microsoft Research**, Apr 2021 - Jun, 2022, Redmond, WA
  - Research Intern
  - Working on the optimization of Wi-Fi network for gaming scenarios.

- **Intel**, Apr 2018 - Jun, 2019, Beijing, China
  - Research Intern
  - Implemented 5G NR and LTE layer 2 (mainly MAC, RLC, PDCP layer) stacks on Intel Architecture with Linux and C/C++ for the benchmarking of LTE/NR prototypes.
  
## Projects


[→ Full list](/projects/)

<ProjectCard image="/projects/1.png" hideBorder=true>

  **The Making of Harry Potter's Wand**

  Harry P., Hermione G., *et al*
  
  Harry's wand was broken in 1997, but was repaired by him after the 1998 Battle of Hogwarts. Usually the repair of a wand is impossible, but with the use of the Elder Wand it was achievable.
  
  [[PDF](https://www.google.com)] [[arXiv](https://arxiv.org)]

</ProjectCard>

<ProjectCard hideBorder=true>

  **Harry Potter and the Deathly Hallows**
  
  In the epilogue of Deathly Hallows, which is set 19 years after Voldemort's death, Harry and Ginny are a couple and have three children: James Sirius Potter, who has already been at Hogwarts for at least one year, Albus Severus Potter, who is starting his first year there, and Lily Luna Potter, who is two years away from her first year at the school.

  [[Link](https://www.google.com)]

</ProjectCard>


## Awards & Honors

### Contests

- First place in **The Hogwarts House Cup**


<!-- Custom style for this page -->

<style lang="stylus">

.theme-container.home-page .page
  font-size 14px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      img
        max-width 120px
        max-height 120px
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img 
          width 100%
          max-width 400px

</style>
