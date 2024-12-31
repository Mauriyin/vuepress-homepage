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

#cv: https://en.wikipedia.org/wiki/Harry_Potter
bio: Research Scientist
email: haoyin (at) meta (dot) com
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me
Dr. Hao Yin is currently a Wireless System Engineer at Meta Reality Lab. He received his Ph.D. degree from the [University of Washington](https://www.washington.edu/) in 2023 under the supervision of Prof. [Sumit Roy](https://people.ece.uw.edu/roy/). Before this, he received his Bachelor's degree (2015-2019) from Huazhong University of Science and Technology.
              
Dr. Yin works on system performance analysis and optimization for wearable hardware and MMAI applications. His research focuses on scheduling and resource allocation algorithms in wireless communication, especially for the next generation of 5G and Wi-Fi systems. He also works on applying machine learning algorithms to complex wireless systems to build more intelligent wireless systems in the future.

## News
- [Sept 2024] I started to teach EE 595 / EEP 569 Introduction to WLAN this fall at the University of Washington.
- [Apr 2024] Our paper "ANN-Assisted Wireless Link Rate Adaptation for Compute-Constrained Embedded Gaming Devices" has been [presented](https://www.usenix.org/conference/nsdi24/presentation/yin) at NSDI 24.
- [Jul 2023] Updated the latest status of multi-bss Wi-Fi simulations at [Wireless Next Generation (WNG) Standing Committee
Meeting](https://mentor.ieee.org/802.11/dcn/23/11-23-1257-00-0wng-wng-meeting-minutes-2023-july-berlin-meeting.docx)
- [Jun 2023] Updated the latest status of multi-bss Wi-Fi simulations at [WNS3 2023](https://www.nsnam.org/research/wns3/wns3-2023/program/)
- [Oct 2022] We offered the tutorial for the ns-3 Wi-Fi simulation at [LANC 2022](https://lanc.top/2022/tutorials-offered/)
- [Jun 2022] Present our work on 6 GHz Wi-Fi in [WNS3 2022](https://www.nsnam.org/research/wns3/wns3-2022/program/)
- [Apr 2022] We offered the tutorial for the ns-3 Wi-Fi simulation at [ACMSE 2022](https://acmse.net/2022/tutorials-offered/#tut-work04)


## Education

- **University of Washington, Seattle, USA** <br/>
PhD, ECE, Sept 2019 - Aug 2023
- **University of Washington, Seattle, USA** <br/>
MS, AMATH, March 2021 - Dec 2022
- **Huazhong University of Science and Technology, Wuhan, China** <br/>
BS, Sept 2015 - Jun 2019

## Working Experience
- **Meta Reality Lab**, Sept 2023 - Present, Redmond, WA
  - Working on the optimization of the Wi-Fi network for XR products.
  - MMAI use cases performance analysis and optimization for AR/Smart Glasses.

- **Meta, TED wireless Team**, Jun 2022 - Sept 2022, Sunnyvale, CA
  - HW Product Engineer Intern
  - Working on the optimization of the Wi-Fi network for XR scenarios.

- **Microsoft Research**, Apr 2021 - Jun 2022, Oct 2022 - Mar 2023, Redmond, WA
  - Research Intern
  - Working on the optimization of Wthe i-Fi network for gaming scenarios.

- **Intel**, Apr 2018 - Jun, 2019, Beijing, China
  - Research Intern
  - Implemented 5G NR and LTE layer 2 (mainly MAC, RLC, PDCP layer) stacks on Intel Architecture with Linux and C/C++ for the benchmarking of LTE/NR prototypes.
  
## Projects


<!-- [→ Full list](/projects/) -->

<ProjectCard image="/projects/wifi.png" hideBorder=true>

  **Next-Generation Wi-Fi Networks**
With the imminent IEEE 802.11be (Wi-Fi 7) amendment, future Wi-Fi 7 aims to offer low latency and ultra-reliability in license-exempt spectrum bands. The new physical (PHY) and medium access control (MAC) layer enhancements, such as multi-link operation (MLO) and multi-AP cooperation, provide more opportunities for Wi-Fi networks to meet often conflicting QoE metrics. Our projects focus on smart scheduling and optimization for the next-generation Wi-Fi networks.    

**Papers**: [6 GHz](https://dl.acm.org/doi/abs/10.1145/3532577.3532580), [Channel Access](https://ieeexplore.ieee.org/abstract/document/9348485), [Wi-Fi 7 Scheduling](https://ieeexplore.ieee.org/abstract/document/9810021)

</ProjectCard>

<ProjectCard image="/projects/5g.png" hideBorder=true>

  **Resource Allocation and Scheduling for 5G Networks**
  Diverse mission-critical applications require Ultra-Reliable and Low-Latency Communications (URLLC) services, such as industrial automation, intelligent transportation, gaming, and Virtual/Augmented Reality (VR/AR). Different types of wireless technology have coexisted and provided URLLC services under various scenarios. Our projects study the requirements of the URLLC traffic in 5G networks and propose optimization algorithms for the scheduling and resource allocation problem.

**Papers**: [Joint Scheduling](https://ieeexplore.ieee.org/abstract/document/9247169), [Multi-hop](https://ieeexplore.ieee.org/abstract/document/9625389), [Channel Prediction](https://ieeexplore.ieee.org/abstract/document/9625323)
</ProjectCard>

<!-- <ProjectCard hideBorder=true>

  **The ns-3 simulation tools**
  
  [[Link](https://www.google.com)]

</ProjectCard> -->

<ProjectCard image="/projects/v2x.png" hideBorder=true>

  **Vehicle to Everything (V2X) Communication**
Vehicle-to-everything, or V2X, is an all-encompassing term for a vehicle’s connected communications. The overall idea is that a vehicle is able, or will be able to, use its on-board communication tools to deliver real-time traffic information, preemptively react to changing road conditions, recognize road signs and warnings, and more. In these projects, we mainly focus on the scheduling and resource allocation in V2X communication based on the latest standards.  

**Papers**:[Vehicle Platooning](https://ieeexplore.ieee.org/abstract/document/9527765), [Blockchain for Vehicular Safety](https://ieeexplore.ieee.org/abstract/document/9625342)
</ProjectCard>


## Awards & Honors
- Qualcomm Innovation Fellowship Finalist, 2022 
- Huazhong University of Science and Technology Outstanding undergraduate graduation thesis, 2019
- National Scholarship in China, 2018
- Merit Student of Huazhong University of Science and Technology, 2017 & 2018
- Huazhong University of Science and Technology undergraduate excellent student, 2017
- Team Winner, College Students' Innovation and Entrepreneurship Campus, 2017

<!-- ### Contests

- First place in **The Hogwarts House Cup** -->


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
