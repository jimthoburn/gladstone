---
title: Support & Wellness Programs at Gladstone High School
layout: default
image: "/images/photos/one-student.png"
image_focus: bottom
has_wide_content: true
---

<style media="(max-width: 59.9em)">
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
  min-height: 80vmax;
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
  width: 50%;
  position: absolute;
  top: 35vh;
  left: auto;
  right: 0;
  transform: translate(10%, 0);
  z-index: 9999;
}

body.image-reverse > .image img {
  right: auto;
  left: 0;
}


body > main::before {
  display: none;
}
body > main > div:first-of-type {
  background: white;
  position: relative;
  z-index: 9999999999;
  padding: 1.5em 1.5em;
  margin: -1.5em -1.5em -3em;
  background: rgb(46, 127, 182); /* --ocean */
  background-color: rgb(237, 237, 239);
  background-color: rgb(245, 245, 245);
  background-color: rgb(244, 209, 81); /* --gold */
  background: transparent;
  background: white;
  background-color: rgb(255, 251, 254); /* --strawberry */
  /*
  background-image: url(/images/aztec-pattern.svg), url(/images/aztec-pattern.svg);
  background-position: top, bottom;
  background-size: auto 1.5em;
  background-repeat: repeat-x;
  background-image: url(/images/aztec-circle.png);
  background-position: top;
  background-size: 100% 100%;
  */
  /*
  box-sizing: border-box;
  display: flex;
  align-content: center;
  align-items: center;
  justify-content: center;
  padding-left: 6em !important;
  padding-right: 6em !important;
  border-radius: 50%;
  height: 100vw;
  -webkit-clip-path: circle(50vw at 50% 50%);
  transform: skew(0, 2deg) translate(0, 5%);
  transform: perspective(600px) rotateY(5deg);
  */

  /*Chrome,Safari*/
  /*
  -webkit-clip-path: polygon(0 0,100% 25%,100% 100%,0 100%);
  margin-top: -3em;
  padding-top: 3em !important;
  padding-bottom: 1.5em !important;
  */
}
/*
@media (min-width: 60em) {
  body > main > div:first-of-type {
    padding-top: 3em !important;
    padding-bottom: 3em !important;
  }
}
*/

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
    margin-top: -3em;
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
body > header h2,
body > header h2 + p {
  color: rgb(40, 41, 43); /* --tungsten */
  text-shadow: none;
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
  left: 0;
  z-index: 3;
  text-align: left;
  /*
  transform: translate(0, -100%);
  margin-top: -1.5rem;
  */
  top: 15rem;
  margin-left: 1.5rem;
  margin-right: 1.5rem;
  width: calc(100% - 3rem);
}
@media (min-width: 30em) {
  main h1 {
    margin-left: 3rem;
    margin-right: 3rem;
    font-size: 6vmax;
    width: calc(100% - 6rem);
  }
}

body.image-reverse main h1 {
  text-align: right;
}

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

<style media="(min-width: 60em)">
body > .image {
  background: transparent;
}
.image {
  /*
  background-image: url(/images/background.png);
  background-position: center;
  background-size: cover;
  */
  padding-top: 35vh;
  box-sizing: border-box;
}
@media (min-width: 60em) {
  .image {
    padding-top: 25vh;
  }
}
.image::before,
.image::after {
  display: none;
}
body > main::before {
  display: none;
}
body.has-image > header {
  height: 50vh;
  min-height: 50vh;
}
.image img {
  height: 100vmax;
  width: auto;
  margin-left: auto;
  margin-right: auto;
  position: absolute;
  left: 35%;
}
body > nav,
body > footer {
  position: relative;
  z-index: 3;
}
@media (min-width: 45em) {
  .image img {
    left: 50%;
  }
}
body.image-reverse .image img {
  left: -10%;
}
@media (min-width: 60em) {
  body.image-reverse .image img {
    left: 10%;
  }
}
/*
.image:after {
  content: "";
  background-image: linear-gradient(to top, rgba(255, 255, 255, 1), rgba(255, 255, 255, 1) 5%, rgba(255, 255, 255, 0) 55%, rgba(255, 255, 255, 0));
  height: 100vmax;
  width: 50vw;
  margin-left: auto;
  margin-right: auto;
  position: absolute;
  left: 50%;
  top: 5vh;
  z-index: 99999;
}
*/
/*
body > header h2,
body > header h2 + p {
  color: black;
  text-shadow: none;
}
*/
body > header > a {
  margin-top: 1em;
}
body.has-image > header {
  color: inherit;
}
body > header h2,
body > header h2 + p {
  color: inherit;
  text-shadow: none;
}
/*
body > header h2 + p {
  text-indent: -9999px;
  overflow: hidden;
}
body > header h2 img {
  transform: translateY(-65%);
}
*/
/*
body > main > p {
  margin-right: 50vw;
}
*/
/*
main h1 {
  position: absolute;
  transform: translateY(-150%);
  width: 75%;
  width: calc(75% - 1.5rem);
  font-size: 2em;
}
body.image-reverse main h1 {
  right: 1.5rem;
}
@media (min-width: 60em) {
  main h1 {
    width: 50%;
    width: calc(50% - 3rem);
  }
  body.image-reverse main h1 {
    right: 3rem;
  }
}
*/
main h1 {
  font-size: 2em;
  font-size: 5vmax;
  margin-bottom: 3rem;
}
@media (min-width: 55em) {
  main h1 {
    font-size: 3em;
    font-size: 5vmax;
  }
}
body.image-reverse main h1,
body.image-reverse main > p,
body.image-reverse main > ul {
  text-align: right;
}
@media (min-width: 30em) {
  body.image-reverse main h1,
  body.image-reverse main > p,
  body.image-reverse main > ul {
    text-align: left;
  }
}
/*
@media (min-width: 35em) {
  main h1 {
    transform: translateY(-175%);
  }
}
@media (min-width: 55em) {
  main h1 {
    font-size: 3em;
    transform: translateY(-200%);
  }
}
*/
main h1 + h2 {
  margin-top: 0;
}

main > h1,
main > p,
main > ul {
  max-width: 75%;
}
body.image-reverse main > h1,
body.image-reverse main > p,
body.image-reverse main > ul {
  margin-left: 20%;
}
@media (min-width: 60em) {
  main > h1,
  main > p,
  main > ul {
    max-width: 50%;
  }
  body.image-reverse main > h1,
  body.image-reverse main > p,
  body.image-reverse main > ul {
    margin-left: 45%;
  }
}
body {
  background-color: rgb(237, 237, 239);
}
.staff-list {
  margin-top: 3em;
  padding: 1px 3em 3em 3em;
  margin-left: -3em;
  margin-right: -3em;
  background-color: white;
}
.summaries {
  margin-top: 0;
  background-color: white;
}
</style>

# Support <span class="lowercase">&amp;</span> Wellness Programs

<div markdown="1">

![](/images/icons/wellness/heart-hands.svg) Intervention Programs
: [Advisory](http://info.gladstonehighschool.jimthoburn.com/ghsgeneralinformation)
: Azusa Calculates

![](/images/icons/wellness/school.svg) Afterschool Programs
: APEX
: Adult School

[![](/images/icons/wellness/teach.svg) Special Education](http://info.gladstonehighschool.jimthoburn.com/cms/page_view-d=x&piid=&vpid=1351934773435/)
: VI Program
: Certificate Of Completion

![](/images/icons/wellness/international.svg) Bilingual Education
: ELD Classes
: PASS

![](/images/icons/wellness/heart-beat.svg) Student Wellness Center
: APU Interns
: Pacific Clinics

[![](/images/icons/wellness/graduate.svg) College and Career Center](http://info.gladstonehighschool.jimthoburn.com/guidancewelcome/)
: Naviance ASVAB
: Four Year Plan

</div>
