// Variables
$red: #c00;

// Placeholder selectors
%transition {
  transition: all .25s;
}

/*Typography*/
body {font: 300 16px 'Roboto', 'Lato', sans-serif;}
/*Layout*/
html,
body {
  margin: 0;
  padding: 0;
  width: 100%;
  height: 100%;
}
*,
*:before,
*:after {box-sizing: border-box;}
.wrapper {
  width: 100%;
  height: 100%;
}
section,
footer {
  width: 100%;
}
.row {
  margin: auto;
  width: 100%;
  max-width: 60em;/*960px*/
  &:first-child {padding-top: 3em;}
  &:last-child {padding-bottom: 3em;}
}
.col-3,
.col-2 {
  display: inline-block;
  vertical-align: top;
}
.col-3 {width: 280px;}
.col-2 {width: 49%;}
@media screen and (max-width: 768px) {
  .col-3,
  .col-2 {width: 49%;}
}
@media screen and (max-width: 500px) {
  .col-3,
  .col-2 {
    display: block;
    margin: auto;
    width: 80%;
  }
}
.row h1 {
  margin: 0;
  font-weight: 300;
  text-transform: uppercase;
}
button {
  margin-top: 1em;
  width: 13em;
  line-height: 2em;
  text-transform: uppercase;
  background: #000;
  color: #fff;
  border: 0;
  outline: 0;
  @extend %transition;
  &:focus,
  &:hover {background: lighten(#000, 10%);}
  &:active {background: lighten(#000, 3%);}
}
/*Intro*/
.sec-intro {position: relative;}
/*Navigagtion*/
header {}
header input {display: none;}
header input:checked + label {&:before {content: "\f00d";}}
header input:checked ~ nav > .nav {
  width: 11em;
  opacity: 10;
}
.nav {
  position: absolute;
  top: 0;
  left: 2.9em;
  margin: 0;
  padding: 0;
  width: 0;
  list-style-type: none;
  background: $red;
  opacity: 0;
  overflow: hidden;
  @extend %transition;
}
.nav a {
  display: block;
  padding: .85em 0;
  width: 11em;
  text-align: center;
  text-decoration: none;
  color: #fff;
  @extend %transition;
  &:focus,
  &:hover {background: darken($red, 10%);}
  &:active {background: lighten($red, 1%);}
}
header label {
  display: block;
  padding: .5em;
  width: 47px;
  text-align: center;
  background: $red;
  color: #fff;
  cursor: pointer;
  @extend %transition;
  &:before {
    content: "\f0c9";
    font: 2em fontAwesome;
  }
  &:focus,
  &:hover {background: darken($red, 10%);}
  &:active {background: lighten($red, 1%);}
}
.sec-intro {
  position: relative;
  width: 100%;
  height: 100%;
  background: url(http://www.zeleznakoule.cz/wp-content/uploads/2011/11/kettlebell-graphic.jpg) no-repeat center center fixed;
  background-size: cover;
}
.sec-intro h1 {
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  margin: auto;
  width: 10em;
  height: 3em;
  font-family: 'Black Ops One';
  line-height: 3em;
  text-align: center;
  background: rgba(0,0,0,.5);
  color: #c00;
  cursor: default;
}
/*About*/
.sec-about {text-align: center;}
@media screen and (max-width: 768px) {
  br {display: none;}
}
.row-red {
  background: $red;
  color: #fff;
}
.row-red .row {
  padding-left: 1em;
  padding-right: 1em;
}
.sec-about p {font-size: .90em;}
.row-grey {
  background: #111;
  color: #ddd;
}
.sec-about .row-grey .row {padding: 3em 0;}
.sec-about article {padding: 0 1em;}
/*News*/
.sec-news {text-align: center;}
.sec-news .row > h1 {padding-bottom: .5em;}
.sec-news .col-2 {padding: 1em;}
.post {
  position: relative;
  height: 245px;
  cursor: pointer;
  @extend %transition;
  &:hover {opacity: .8;}
}
.post span,
.post h1,
.post p {position: absolute;}
.post span {
  padding: .25em .5em;
  font-weight: bold;
  background: $red;
  color: #fff;
  opacity: .85;
}
.post h1 {
  bottom: 0;
  padding-left: .5em;
  width: 100%;
  font-size: 1.15em;
  line-height: 2em;
  text-align: left;
  color: #fff;
  background: rgba(0,0,0,.75);
}
.col-2 img {
  width: 100%;
  height: 245px;
}

/*Gallery*/
.sec-gallery {
  text-align: center;
  background: url(http://crossfitdrakkarhondarribia.com/wp-content/uploads/2011/09/crossfit21.jpg) no-repeat center center;
  //background-size: 100% 100%;
  background-size: cover;
  color: #fff;
}
.overlay {background: rgba(0,0,0,.75);}
.sec-gallery h1:first-of-type {
  padding: .5em 0;
  color: #fff;
}
.col-3 img {
  width: 100%;
  cursor: pointer;
  @extend %transition;
  &:hover {/*opacity: .8;*/filter: brightness(50%);}
}
/*Footer*/
footer {background: #111;}
.soc-media {
  display: flex;
  justify-content: center;
  margin: 0;
  padding: 0;
  list-style-type: none;
}
.soc-media li {margin-right: 1em;}
.soc-media a {
  font-size: 1.5em;
  text-decoration: none;
  color: #fff;
  @extend %transition;
  &:focus,
  &:hover {color: $red;}
  &:active {color: #222;}
}
footer p {
  font-size: .85em;
  text-align: center;
  color: #aaa;
}