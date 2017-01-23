---
title: Gladstone High School, Preparing students for success
classname: home
layout: default
has_wide_content: true
image: "/images/photos/four-students-2.png"
image_focus: bottom
---

<style>
/*
body > main::before {
  content: "";
  background-color: white;
  height: 1.5em;
  width: 120%;
  margin-top: -2.25em;
  position: absolute;
  z-index: 3;
  left: -10%;
  transform: rotate(-2deg);
}
  @media (min-width: 60em) {
    body > main::before {
      margin-top: -4.5em;
      height: 3em;
    }
  }

*/
body {
  background-color: rgb(244, 209, 81); /* --gold */
  background-color: rgb(237, 237, 239);
}
body > main::before,
body > main {
  background-color: rgb(244, 209, 81); /* --gold */
  background-color: rgb(237, 237, 239);
}
/*
body > .image {
  background-color: rgb(237, 237, 239);
  background-image: url(/images/athletics.jpg);
  background-position: center;
  background-size: cover;
}
*/
body > .image {
  background-color: rgb(46, 127, 182); /* --ocean */
  background-color: white;
  background-color: rgb(244, 209, 81); /* --gold */
  background-color: rgb(237, 237, 239);
  background-image: none;
  /*
  transform: skew(0, -2deg) translate(0, -5vh);
  */
  height: 10em;
  min-height: 75vmax;
}
/*
body > .image img {
  transform: skew(0, 2deg) translate(0, 5vh);
}
*/
body > .image::before,
body > .image::after {
  display: none;
}
body > .image img {
  height: auto;
  width: 100%;
  position: absolute;
  top: 50vh;
  right: 0;
  z-index: 9999;
}

body.image-reverse > .image img {
  left: 0.75em;
}
@media (min-width: 60em) {
  body.image-reverse > .image img {
    left: 3em;
  }
}

body > main > div:first-of-type {
  background: white;
  position: relative;
  z-index: 9999999999;
  padding: 1.5em;
  margin: 0 -1.5em -3em;
  background: rgb(238, 51, 56); /* --strawberry */
  background-color: rgb(215, 1, 0);
  background-image: url(/images/texture-shape.png);
  background-position: center;
  background-size: 160% auto;
  color: white;
  /*
  transform: skew(0, 2deg) translate(0, 5%);
  transform: perspective(600px) rotateY(5deg);
  */

  /*Chrome,Safari*/
  -webkit-clip-path: polygon(0 0,6.25% 5%,25% 0,62.5% 5%,75% 0,87.5% 5%,100% 0,100% 100%,92.5% 95%,75% 100%,50% 95%,25% 100%,12.5% 95%,0 100%);
  padding-top: 2.25em !important;
  padding-bottom: 2.25em !important;
  transform: translate(0, 5%);
}
@media (min-width: 60em) {
  body > main > div:first-of-type {
    margin-top: -3em;
    padding-top: 6em !important;
    padding-bottom: 6em !important;
  }
}
body > main > div:first-of-type > * {
}
body > main > div:first-of-type p a {
  color: inherit;
}
body > main > div:first-of-type p {
    text-align: center;
    margin-left: auto;
    margin-right: auto;
}
@media (min-width: 60em) {
  body > main > div:first-of-type {
    padding: 3em;
    margin-left: -3em;
    margin-right: -3em;
    margin-bottom: -3em;
  }
  body > main > div:first-of-type p {
    font-size: 2vmax;
  }
}
body > main > div:first-of-type h2:first-child {
  margin-top: 0.75rem;
}
body.image-reverse main h1 {
  left: auto;
  right: 1.5rem;
  max-width: none;
  text-align: right;
}
/*
@media (min-aspect-ratio: 1/1) {
  body > .image {
    height: 65vh;
    min-height: 65vh;
  }
  body > .image img {
    top: 30vh;
  }
  body > .image img {
    width: 40vw;
    height: auto;
    right: -3em;
  }
  body > main > div:first-of-type {
    background: transparent;
    position: static;
    padding: 0;
    margin: 0;
    margin-right: 35%;
  }
  body.image-reverse main h1 {
    margin-left: 0;
    left: 50vw;
    right: auto;
    margin-right: 3rem;
    text-align: left;
  }
  body.image-reverse > main > div:first-of-type {
    margin-right: 0;
    margin-left: 50vw;
    margin-left: calc(50vw - 1.5em);
  }
  @media (min-width: 60em) {
    body.image-reverse > main > div:first-of-type {
      margin-left: calc(50vw - 3em);
    }
  }
}
*/
/*
@media (min-width: 35em) {
  body.image-reverse main h1 {
    margin-left: 0;
    left: 50vw;
    right: auto;
    margin-right: 3rem;
    text-align: left;
  }
  body.image-reverse main > div:first-of-type p,
  body.image-reverse main > div:first-of-type ul {
    max-width: none;
    margin-left: 50vw;
    margin-left: calc(50vw - 3em);
    margin-right: 0;
  }
}
*/

/*
body > header h2,
body > header h2 + p {
  color: black;
  text-shadow: none;
}
body > header > a {
  margin-top: 1em;
}
*/
body > header > a {
  margin-top: -3em;
  display: table;
  margin-left: auto;
  margin-right: auto;
  padding-left: 0;
  padding-right: 0;
}
body > header h2 img {
  display: block;
  position: static;
  margin-left: auto;
  margin-right: auto;
  transform: none;
}
body > header h2,
body > header h2 + p {
  color: rgb(244, 209, 81); /* --gold */
  color: white;
  color: rgb(46, 127, 182); /* --ocean */
  text-shadow: none;
  color: rgb(57, 164, 208); /* --light-blue */
  color: rgb(238, 51, 56); /* --strawberry */
  color: rgb(40, 41, 43); /* --tungsten */
  text-shadow: none;
  text-align: center;
}
/*
body > header h2 img {
  transform: translateY(-65%);
}
body > main > p {
  margin-right: 50vw;
}
*/
main h1 {
  position: absolute;
  z-index: 3;
  text-align: center;
  /*
  transform: translate(0, -100%);
  margin-top: -1.5rem;
  */
  font-size: 2.25em;
  top: 10.5rem;
  margin-right: 1.5rem;
  color: rgb(244, 209, 81); /* --gold */
  color: white;
  color: rgb(46, 127, 182); /* --ocean */
  color: rgb(57, 164, 208); /* --light-blue */
  color: rgb(238, 51, 56); /* --strawberry */
}
@media (min-width: 30em) {
  main h1 {
    margin-right: 3rem;
    font-size: 6vmax;
    padding-left: 10vw;
    padding-right: 10vw;
  }
}
/*
@media (min-width: 50em) {
  main h1 {
    font-size: 3em;
  }
}
@media (min-width: 75em) {
  main h1 {
    font-size: 4em;
  }
}
*/
main h1 + h2,
main h1 + p {
  margin-top: 0;
}
figure {
  margin-top: 1.5em;
  margin-left: -4.5em;
  margin-right: -4.5em;
  margin-bottom: -4.5em;
  max-width: none;
  position: relative;
  z-index: 99999;
  transform: rotate(-2deg);
  overflow: hidden;
  background: rgb(51, 51, 51);
}
@media (min-width: 60em) {
  figure {
    margin-bottom: -7.5em;
  }
}
figure img {
  width: 100%;
  height: auto;
  max-width: none;
  transform: rotate(2deg) scale(1.125);
}
/*
figure {
  transform: rotate(-5deg) scale(0.85) translate(-6em, 0);
  margin-top: 1.5em;
  margin-bottom: 3em;
}
figure img {
  transform: rotate(5deg) scale(1.15);
}
*/
.staff-list {
  margin-top: 3em;
  padding: 1px 1.5em 3em 1.5em;
  margin-left: -1.5em;
  margin-right: -1.5em;
  background-color: white;
  position: relative;
  z-index: 99999;
}
@media (min-width: 60em) {
  .staff-list {
    padding-left: 3em;
    padding-right: 3em;
    margin-left: -3em;
    margin-right: -3em;
  }
}
.summaries {
  margin-top: 0;
  background-color: white;
  position: relative;
  z-index: 99999;
}
</style>

<style media="false">
body.has-image > header {
  color: inherit;
  text-shadow: none;
}
.nav-link {
  z-index: 99999999999999 !important;
}
body > .image {
  background: transparent;
  background-color: rgb(237, 237, 239);
  padding-top: 30em;
}
body > .image img {
  width: 100%;
  height: auto;
}
main > div:first-of-type {
  position: absolute;
  z-index: 9999;
  top: 12em;
  margin-right: 1.5em;
}

@media (min-aspect-ratio: 1/1) {
  body > .image {
    padding-top: 15em;
  }
  main > div:first-of-type {
    top: 10.5em;
  }
}

/*
body > .image img {
  position: relative;
  z-index: 2;
}
*/
.staff-list {
  background-color: white;
}
main > div:first-of-type + p,
.staff-list h2 {
  margin-top: 0;
}

    .image::before,
    .image::after {
      display: none;
    }
@supports (object-fit: cover) {
  .image {
    padding-top: 20vh;
    position: static;
  }
  .image img {
    width: 100%;
    height: 85vh;
    position: relative;
    z-index: 9999;
  }
  @media (min-aspect-ratio: 1/1) {
    .image {
      padding-top: 0;
    }
    .image img {
      height: 100vh;
      object-position: top !important;
    }
  }
}

/*
.summaries .parents-summary {
  transform: rotate(2deg);
  padding-bottom: 3em;
  margin-bottom: -3em;
}
.summaries .parents-summary > * {
  transform: rotate(-2deg);
}
.summaries .calendar-summary {
  transform: rotate(-2deg);
}
.summaries .calendar-summary > * {
  transform: rotate(2deg);
}
*/
</style>

# Preparing Students <span class="lowercase">for</span> Success

<div markdown="1">

<!--
Our mission is to educate every student for academic achievement and life-long learning, and planner for the future–ready to be responsible for their own success.
-->

Our mission is to prepare students to be *academic achievers*, *life-long learners*, and *planners for the future*–ready to be responsible for <span class="avoid-break">their own success</span>. <span class="avoid-break">Learn more [about our school](/about).</span>

</div>

<div class="staff-list">
  <h2>Our Teachers</h2>
  <ul>
    <li>
      <img src="/images/teachers/img_2804.jpg" width="200" alt="TODO: Add Teacher’s Name" />
      <h3>Ms. Teri Perdomo</h3>
      <p class="title">Fine Arts Department Chair</p>
    </li>
    <li>
      <img src="/images/teachers/img_3560.jpg" width="200" alt="TODO: Add Teacher’s Name" />
      <h3>Ms. Amie Brady</h3>
      <p class="title">Choir</p>
    </li>
    <li>
      <img src="/images/teachers/img_2966.jpg" width="200" alt="TODO: Add Teacher’s Name" />
      <h3>Mr. Brodie O'Brien</h3>
      <p class="title">English</p>
    </li>
    <li>
      <img src="/images/teachers/img_2991.jpg" width="200" alt="TODO: Add Teacher’s Name" />
      <h3>Mr. Joseph Calderon</h3>
      <p class="title">Music</p>
    </li>
  </ul>
  <p>See more <a href="/staff">staff members</a></p>
</div>

<div class="summaries">
  <div class="facilities-summary text" markdown="1">

## Facilities

*   Gym (with newly added air conditioning)
*   Theater
*   4 Computer Labs
*   Chrome Book Carts
*   Auto Shop
*   Science Labs

  </div>

  <div class="calendar-summary text" markdown="1">

## Calendar

January 11
: Students Return from Break

January 17
: Coffee with the Principal

February 21
: Parent Forum

[See full calendar](http://info.gladstonehighschool.jimthoburn.com/cms/month-d=x&group_id=1301752510365&month_id=0)

  </div>

  <div class="parents-summary text" markdown="1">

## Parents & Students

Learn about attendance, handbooks, dress code and more on the <span class="avoid-break" markdown="1">[handbook](http://info.gladstonehighschool.jimthoburn.com/handbook) page</span>.

  </div>
</div>

<section class="announcements">

<header>
<h2>News &amp; Announcements</h2>
</header>

<ul>
<li markdown="1">

### Winter break is from December 23, 2016 - January 10, 2017.

Students return to school on January 11th.

</li>
<li markdown="1">

### The Local Scholarship Application is now open.

[View the application](http://links.schoolloop.com/link/rd?href=736c5f6c696e6b6666303163633065623266687474703a2f2f6768732d617573642d63612e7363686f6f6c6c6f6f702e636f6d2f66696c652f313330313735323531303336352f313333383034303830363232312f353939383139363434393231353536303333312e646f6378)

The application must be typed. Please submit your application to Ms. Madden in the Career Center by Friday, February 3, 2017, by 3 PM.

</li>
<li markdown="1">

### Math Tutoring

*2:50 PM - 3:50 PM in Room B22*

#### Mondays & Wednesdays

Integrated Math II and Integrated Math III

#### Tuesdays & Thursdays

Pre-Calculus, Calculus, and Stats

</li>
</ul>

</section>

<div class="feature">
  <h2>
    <svg class="icon" viewBox="0 0 24 24" width="48" height="48">
      <switch>
        <path fill="white" d="M22,19.4c0,1.4-1.2,2.6-2.6,2.6H4.6C3.2,22,2,20.8,2,19.4V4.6C2,3.2,3.2,2,4.6,2h14.9C20.8,2,22,3.2,22,4.6 V19.4z M19.7,10.5H18c0.2,0.5,0.3,1.1,0.3,1.7c0,3.3-2.8,6-6.2,6c-3.4,0-6.2-2.7-6.2-6c0-0.6,0.1-1.2,0.3-1.7H4.2v8.4 c0,0.4,0.4,0.8,0.8,0.8h13.9c0.4,0,0.8-0.4,0.8-0.8V10.5z M12,8.1c-2.2,0-4,1.7-4,3.9c0,2.1,1.8,3.9,4,3.9c2.2,0,4-1.7,4-3.9 C16,9.8,14.2,8.1,12,8.1z M19.7,5.1c0-0.5-0.4-0.9-0.9-0.9h-2.3c-0.5,0-0.9,0.4-0.9,0.9v2.1c0,0.5,0.4,0.9,0.9,0.9h2.3 c0.5,0,0.9-0.4,0.9-0.9L19.7,5.1L19.7,5.1z"></path>
        <foreignObject>Instagram</foreignObject>
      </switch>
    </svg>
    @gladstonehighschool
  </h2>
  <!--
  <p class="more">See more <a href="/news">news &amp; announcements</a></p>
  -->

  <a href="https://www.instagram.com">
      <img src="/images/photos/aHR0cDovL2docy1hdXNkLWNhLnNjaG9vbGxvb3AuY29tL3VpbWcvaW1hZ2UvMTMwMTc1MjUxMTE3MS8xMzQ1Mjc5MTU3MDQxLzE0NDEyNjI2MjM4NzYuanBnP2Nyb3BUb3A9MzcmY3JvcFJpZ2h0PTk1MCZjcm9wQm90dG9tPTcxMiZjcm9wTGVmdD00OSZiYXNpc1dpZHRoPTEwMDA=.jpeg" />
    <p>Medical Pathway Students 2015-16</p>
  </a>

  <a href="https://www.instagram.com" class="icon">
    <svg class="comment icon" viewBox="0 0 24 24" width="24" height="24">
      <path fill="white" d="M2.2,8.9c0,1,0.3,1.9,1,2.8c0.7,0.9,1.6,1.5,2.8,2c1.2,0.5,2.5,0.7,3.9,0.7c0.4,0,0.8,0,1.3-0.1c1.1,1,2.5,1.7,4,2.1
        c0.3,0.1,0.6,0.1,1,0.2c0.1,0,0.2,0,0.3-0.1c0.1-0.1,0.1-0.1,0.2-0.3v0c0,0,0-0.1,0-0.1c0,0,0-0.1,0-0.1c0,0,0,0,0-0.1L16.5,16
        c0,0,0,0-0.1-0.1c0,0-0.1-0.1-0.1-0.1c0,0-0.1-0.1-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.3s-0.2-0.2-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.4
        c-0.1-0.1-0.1-0.3-0.2-0.5s-0.2-0.4-0.2-0.7c0.9-0.5,1.6-1.2,2.1-1.9s0.8-1.6,0.8-2.4c0-0.8-0.2-1.5-0.6-2.2s-1-1.3-1.7-1.8
        S14,4.1,13,3.8s-2-0.4-3-0.4c-1.4,0-2.7,0.2-3.9,0.7S4,5.2,3.3,6.1S2.2,7.9,2.2,8.9z"></path>
    </svg>
    2
  </a>

  <a href="https://www.instagram.com" class="icon">
    <svg class="heart icon" viewBox="0 0 24 24" width="24" height="24">
      <path fill="white" d="M17.631 5.93c-0.394-0.913-1.185-1.682-2.281-2.158-0.968-0.422-2.012-0.471-2.96-0.214s-1.801 0.956-2.388 1.767c-0.588-0.811-1.44-1.511-2.389-1.767-0.949-0.258-1.991-0.207-2.96 0.214-1.096 0.476-1.885 1.243-2.281 2.158-0.394 0.912-0.397 1.974 0.103 3.027 1.062 2.257 7.494 7.55 7.529 7.64 0.033-0.090 6.466-5.383 7.53-7.64 0.498-1.053 0.496-2.115 0.101-3.027z"></path>
    </svg>
    115
  </a>
</div>

<ul class="news-summary">
  <li>
    <a href="https://www.instagram.com">
      <img src="/images/photos/aHR0cDovL2docy1hdXNkLWNhLnNjaG9vbGxvb3AuY29tL3VpbWcvaW1hZ2UvMTM1NjYxMjg2NjM4Ni8xMzQ1Mjc5MTU3MDQxLzE0NzEzMzMyNzY4NDguanBnP2Nyb3BUb3A9MzMmY3JvcFJpZ2h0PTkwMCZjcm9wQm90dG9tPTYzMyZjcm9wTGVmdD0xMDAmYmFzaXNXaWR0aD0xMDAw.jpeg" />
      <span>2016 Homecoming</span>
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="comment icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M2.2,8.9c0,1,0.3,1.9,1,2.8c0.7,0.9,1.6,1.5,2.8,2c1.2,0.5,2.5,0.7,3.9,0.7c0.4,0,0.8,0,1.3-0.1c1.1,1,2.5,1.7,4,2.1
          c0.3,0.1,0.6,0.1,1,0.2c0.1,0,0.2,0,0.3-0.1c0.1-0.1,0.1-0.1,0.2-0.3v0c0,0,0-0.1,0-0.1c0,0,0-0.1,0-0.1c0,0,0,0,0-0.1L16.5,16
          c0,0,0,0-0.1-0.1c0,0-0.1-0.1-0.1-0.1c0,0-0.1-0.1-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.3s-0.2-0.2-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.4
          c-0.1-0.1-0.1-0.3-0.2-0.5s-0.2-0.4-0.2-0.7c0.9-0.5,1.6-1.2,2.1-1.9s0.8-1.6,0.8-2.4c0-0.8-0.2-1.5-0.6-2.2s-1-1.3-1.7-1.8
          S14,4.1,13,3.8s-2-0.4-3-0.4c-1.4,0-2.7,0.2-3.9,0.7S4,5.2,3.3,6.1S2.2,7.9,2.2,8.9z"></path>
      </svg>
      2
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="heart icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M17.631 5.93c-0.394-0.913-1.185-1.682-2.281-2.158-0.968-0.422-2.012-0.471-2.96-0.214s-1.801 0.956-2.388 1.767c-0.588-0.811-1.44-1.511-2.389-1.767-0.949-0.258-1.991-0.207-2.96 0.214-1.096 0.476-1.885 1.243-2.281 2.158-0.394 0.912-0.397 1.974 0.103 3.027 1.062 2.257 7.494 7.55 7.529 7.64 0.033-0.090 6.466-5.383 7.53-7.64 0.498-1.053 0.496-2.115 0.101-3.027z"></path>
      </svg>
      115
    </a>
  </li>
  <li>
    <a href="https://www.instagram.com">
      <img src="/images/photos/aHR0cDovL2docy1hdXNkLWNhLnNjaG9vbGxvb3AuY29tL3VpbWcvaW1hZ2UvMTMwMTc1MjUxMTE3MS8xMzQ1Mjc5MTU3MDQxLzE0Nzc4MTI3OTI4NjguanBnP2Nyb3BUb3A9MzUmY3JvcFJpZ2h0PTkyOCZjcm9wQm90dG9tPTY3OCZjcm9wTGVmdD03MSZiYXNpc1dpZHRoPTEwMDA=.jpeg" />
      <span>2016 Homecoming</span>
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="comment icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M2.2,8.9c0,1,0.3,1.9,1,2.8c0.7,0.9,1.6,1.5,2.8,2c1.2,0.5,2.5,0.7,3.9,0.7c0.4,0,0.8,0,1.3-0.1c1.1,1,2.5,1.7,4,2.1
          c0.3,0.1,0.6,0.1,1,0.2c0.1,0,0.2,0,0.3-0.1c0.1-0.1,0.1-0.1,0.2-0.3v0c0,0,0-0.1,0-0.1c0,0,0-0.1,0-0.1c0,0,0,0,0-0.1L16.5,16
          c0,0,0,0-0.1-0.1c0,0-0.1-0.1-0.1-0.1c0,0-0.1-0.1-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.3s-0.2-0.2-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.4
          c-0.1-0.1-0.1-0.3-0.2-0.5s-0.2-0.4-0.2-0.7c0.9-0.5,1.6-1.2,2.1-1.9s0.8-1.6,0.8-2.4c0-0.8-0.2-1.5-0.6-2.2s-1-1.3-1.7-1.8
          S14,4.1,13,3.8s-2-0.4-3-0.4c-1.4,0-2.7,0.2-3.9,0.7S4,5.2,3.3,6.1S2.2,7.9,2.2,8.9z"></path>
      </svg>
      2
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="heart icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M17.631 5.93c-0.394-0.913-1.185-1.682-2.281-2.158-0.968-0.422-2.012-0.471-2.96-0.214s-1.801 0.956-2.388 1.767c-0.588-0.811-1.44-1.511-2.389-1.767-0.949-0.258-1.991-0.207-2.96 0.214-1.096 0.476-1.885 1.243-2.281 2.158-0.394 0.912-0.397 1.974 0.103 3.027 1.062 2.257 7.494 7.55 7.529 7.64 0.033-0.090 6.466-5.383 7.53-7.64 0.498-1.053 0.496-2.115 0.101-3.027z"></path>
      </svg>
      115
    </a>
  </li>
  <li>
    <a href="https://www.instagram.com">
      <img src="/images/photos/aHR0cDovL2docy1hdXNkLWNhLnNjaG9vbGxvb3AuY29tL3VpbWcvaW1hZ2UvMTM1NjYxMjg2NjM4Ni8xMzQ1Mjc5MTU3MDQxLzE0NzEzMzMyNzY4NDYuanBnP2Nyb3BUb3A9MzMmY3JvcFJpZ2h0PTkwMCZjcm9wQm90dG9tPTYzMyZjcm9wTGVmdD0xMDAmYmFzaXNXaWR0aD0xMDAw.jpeg" alt="" />
      <span>2016 Homecoming</span>
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="comment icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M2.2,8.9c0,1,0.3,1.9,1,2.8c0.7,0.9,1.6,1.5,2.8,2c1.2,0.5,2.5,0.7,3.9,0.7c0.4,0,0.8,0,1.3-0.1c1.1,1,2.5,1.7,4,2.1
          c0.3,0.1,0.6,0.1,1,0.2c0.1,0,0.2,0,0.3-0.1c0.1-0.1,0.1-0.1,0.2-0.3v0c0,0,0-0.1,0-0.1c0,0,0-0.1,0-0.1c0,0,0,0,0-0.1L16.5,16
          c0,0,0,0-0.1-0.1c0,0-0.1-0.1-0.1-0.1c0,0-0.1-0.1-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.3s-0.2-0.2-0.3-0.3c-0.1-0.2-0.2-0.3-0.3-0.4
          c-0.1-0.1-0.1-0.3-0.2-0.5s-0.2-0.4-0.2-0.7c0.9-0.5,1.6-1.2,2.1-1.9s0.8-1.6,0.8-2.4c0-0.8-0.2-1.5-0.6-2.2s-1-1.3-1.7-1.8
          S14,4.1,13,3.8s-2-0.4-3-0.4c-1.4,0-2.7,0.2-3.9,0.7S4,5.2,3.3,6.1S2.2,7.9,2.2,8.9z"></path>
      </svg>
      2
    </a>

    <a href="https://www.instagram.com" class="icon">
      <svg class="heart icon" viewBox="0 0 24 24" width="24" height="24">
        <path fill="white" d="M17.631 5.93c-0.394-0.913-1.185-1.682-2.281-2.158-0.968-0.422-2.012-0.471-2.96-0.214s-1.801 0.956-2.388 1.767c-0.588-0.811-1.44-1.511-2.389-1.767-0.949-0.258-1.991-0.207-2.96 0.214-1.096 0.476-1.885 1.243-2.281 2.158-0.394 0.912-0.397 1.974 0.103 3.027 1.062 2.257 7.494 7.55 7.529 7.64 0.033-0.090 6.466-5.383 7.53-7.64 0.498-1.053 0.496-2.115 0.101-3.027z"></path>
      </svg>
      115
    </a>
  </li>
</ul>
