:root {
    --main-text-colour: #434343;
    --white: #ffffff;
    --second-text-colour: #056088;
    --acent: #09A7CA;
}

html,
body,
div,
span,
applet,
object,
iframe,
h1,
h2,
h3,
h4,
h5,
h6,
p,
blockquote,
pre,
a,
abbr,
acronym,
address,
big,
cite,
code,
del,
dfn,
em,
img,
ins,
kbd,
q,
s,
samp,
small,
strike,
strong,
sub,
sup,
tt,
var,
b,
u,
i,
center,
dl,
dt,
dd,
ol,
ul,
li,
fieldset,
form,
label,
legend,
table,
caption,
tbody,
tfoot,
thead,
tr,
th,
td,
article,
aside,
canvas,
details,
embed,
figure,
figcaption,
footer,
header,
hgroup,
menu,
nav,
output,
ruby,
section,
summary,
time,
mark,
audio,
video {
    margin: 0;
    padding: 0;
    border: 0;
}

body {
    background-color: var(--white);
    /* background-color: gray; */
    color: var(--main-text-colour);
    font-family: Montserrat, sans-serif;
    font-style: normal;
    
}

ul {
    list-style: none;
}

a {
    text-decoration: none;
    color: inherit;
}

.text-first {
    font-size: 16px;
    line-height: 1.8;
}

.text-second {
    font-size: 16px;
    line-height: 1.7;
}

.text-third {
    font-weight: 700;
    font-size: 20px;
    line-height: 1.7;
}

.text-fourth {
    font-weight: 700;
    font-size: 24px;
    line-height: 1.7;
}

.container {
    width: 1310px;
    margin-left: auto;
    margin-right: auto;
    padding: 0 10px;
}

.button-link {
    color: var(--white);
    font-weight: 500;
    font-size: 16px;
    line-height: 1.7;
    text-align: center;
    padding-top: 22px;
    padding-bottom: 22px;
    background: linear-gradient(104.58deg, #056088 10.57%, #09A7CA 96.62%);
    display: inline-block;
    min-width: 200px;
}

.see-more {
    min-width: 200px;
    padding-left: 26px;
    padding-right: 26px;
}

input {
    width: 500px;
    padding: 22px 25px;
    border: none;
}

.button {
    color: var(--white);
    font-weight: 500;
    font-size: 16px;
    line-height: 1.7;
    text-align: center;
    padding-top: 18px;
    padding-bottom: 18px;
    background: linear-gradient(104.58deg, #056088 10.57%, #09A7CA 96.62%);
    display: inline-block;
    border: none;
    min-width: 150px;
    padding-left: 25px;
    padding-right: 25px;
    cursor: pointer;
}

.link {
    transition: color 100ms linear;
}

.link:hover,
.link:focus {
    color: #023957;
}

header {
    color: var(--white);
}

.header {
    position: absolute;
    z-index: 2;
    width: 100%;
}

.logo {
    font-weight: 700;
    font-size: 66px;
    line-height: 1.17;
}

.header-nav .header-nav-list {
    display: flex;
}

.header-nav-list > li:not(:last-child) {
    margin-right: 40px;
}

.header-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.header-nav a {
    font-size: 16px;
    line-height: 1.5;
    padding-top: 57px;
    padding-bottom: 57px;
    display: block;
}



.hero {
    color: var(--white);
    background: linear-gradient(26.47deg, #023957 22.58%, #056088 94.16%);
    height: 690px;
    /* position: relative; */
}

/* .hero > .container {
    padding: 0;
    margin: 0;
} */

.hero-title {
    font-weight: 700;
    font-size: 52px;
    line-height: 1.5;
    margin-bottom: 16px;
}

.hero-text {
    margin-bottom: 32px;
}

.hero-text,
.hero-button-link {
    font-weight: 500;
    font-size: 16px;
    line-height: 1.7;
}

.hero-text-container {
    position: absolute;
    z-index: 2;
    top: 180px;
}

.hero-img-container {
    position: absolute;
    z-index: 1;
    width: 930px;
    height: 703px;
    /* right: 50%; 
    top: 0;
    transform: translateX(-50%); */
    /* bottom: 0; */
    margin-left: auto;
    right: 0;
}

.hero-container {
    position: relative;
    width: 1400px;
    margin: 0 auto;
}

.our-company {
    padding-top: 100px;
    padding-bottom: 100px;
    text-align: center;
}

.our-company-list p {
    color: var(--second-text-colour);
    margin-bottom: 32px;
}

.our-company-list {
    display: flex;
    justify-content: center;
}

.our-company-list > li:not(:last-child) {
    margin-right: 62px;
}

.our-company-title {
    font-weight: 700;
    font-size: 24px;
    line-height: 1.7;
    color: var(--second-text-colour);
    margin-bottom: 16px;
}

.company-text-first {
    margin-bottom: 16px;
}

.company-text-second {
    font-weight: 500;
    font-size: 16px;
    line-height: 1.8;
    margin-bottom: 16px;
}

.services {
    padding-bottom: 400px;
}

.services h2 {
    color: var(--second-text-colour);
    font-weight: 700;
    font-size: 24px;
    line-height: 1.7;
    text-align: center;
    margin-bottom: 16px;
}

.services p.text-first {
    text-align: center;
    margin-bottom: 32px;
}

.services-list h3 {
    margin-bottom: 16px;
    margin-top: 16px;

}

.services-list {
    display: flex;
    justify-content: space-between;
}

.services-list li {
    width: 310px;
    padding-left: 30px;
    padding-right: 30px;
    padding-bottom: 20px;
    padding-top: 20px;
}

.services-list li:hover {
    background-image: linear-gradient(180deg, rgba(5, 96, 136, 0.8) 0%, rgba(2, 57, 87, 0.8) 100%),
     url(../images/Rectangle-15.jpg);
    color: #fff;
    box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
    background-size: cover;
}

.services-list li:hover .icon {
    fill: #fff;
}

.services-list .icon {
    fill: #434343;
}

.benefits h2.benefits-title {
    color: var(--second-text-colour);
    margin-bottom: 16px;
}

.benefits p.benefits-p {
    margin-bottom: 32px;
}

.benefits {
    text-align: center;
    position: absolute;
    left: 50%;
    transform: translateX(-50%) translateY(-80%);
}

.benefits-list h3, .benefits-list p {
    color: var(--white);

}

.benefits-list li {
    width: 420px;
    padding-right: 95px;
    padding-left: 95px;
    padding-bottom: 42px;
    padding-top: 52px;
    background: linear-gradient(180deg, rgba(5, 96, 136, 0.8) 0%, rgba(2, 57, 87, 0.8) 100%), url(../images/Rectangle-13.jpg);
    background-repeat: no-repeat;

}

.benefits-list li:nth-child(3) {
    margin: 0;
}

.benefits-list {
    display: flex;
    justify-content: space-between;
}

.works {
    color: var(--white);
    background: linear-gradient(180deg, rgba(5, 96, 136, 0.9) 0%, rgba(2, 57, 87, 0.9) 100%), url(../images/Rectangle-38.jpg);
    padding-top: 173px;
    padding-bottom: 501px;
    background-size: cover;
    height: 1414px;
}

.works h2,
.works p {
    text-align: center;
}

.works h2 {
    margin-bottom: 16px;
}

.works p {
    margin-bottom: 32px;
}

.works-list {
    display: grid;
    grid-template-columns: 200px 200px 420px 200px 200px;
    grid-template-rows: 153px 153px 153px;
    grid-gap: 20px;
}

.works-list-item1 {
    grid-row-start: 1;
    grid-column-start: 1;
    grid-row-end: 2.471;
    grid-column-end: 2;
}

.works-list-item2 {
    grid-row-start: 1;
    grid-column-start: 2;
    grid-row-end: 3;
    grid-column-end: 3;
}

.works-list-item3 {
    grid-row-start: 1;
    grid-column-start: 3;
    grid-row-end: 2;
    grid-column-end: 3;
}

.works-list-item7 {
    grid-row-start: 1;
    grid-column-start: 2;
    grid-row-end: 3;
    grid-column-end: 3;
}

/* .works-button-link {
} */

.underundertitle {
    display: flex;
    align-items: center;
}

.underundertitle::before {
    content: "";
    width: 714.5px;
    height: 2px;
    display: block;
    background-color: #fff;
    background: linear-gradient(180deg, #056088 0%, #09A7CA 100%);
    margin-right: 40px;
}

.undertitle {
    margin-top: 32px;
    display: block;
    text-align: right;
    display: flex;
    justify-content: end;
}

.reviews {
    position: absolute;
    text-align: center;
    left: 50%;
    transform: translateX(-50%) translateY(-100%);
}

.reviews-wrapper {
    display: flex;

}

.rewiews-block {
    padding-top: 51px;
    padding-bottom: 71px;
    padding-left: 32px;
    padding-right: 32px;
    background-color: #fff;
}

.reviews h2 {
    color: var(--second-text-colour);
    margin-bottom: 16px;
}

.reviews p.text-first {
    margin-bottom: 32px;
}

/* .rewiews-block {
    background-color: #fff;
} */

.review-img {
    position: absolute;
    top: -35px;
    left: -35px;
}

.review-container {
    position: absolute;
    right: 10px;
    top: 50%;
}

.reviews-container {
    position: relative;
}

.review {
    color: var(--white);
    background: linear-gradient(1.17deg, #023957 -19.65%, #056088 93.67%);
    width: 416px;
    padding-left: 50px;
    padding-right: 24px;
    padding-top: 59px;
    padding-bottom: 29px;
    position: relative;
    text-align: left;
}

.review-text {
    font-style: italic;
    font-size: 16px;
    line-height: 1.7;
}

.review-end {
    font-weight: 600;
    font-size: 16px;
    line-height: 1.7;
}

.video {
    text-align: right;
    /* background-color: grey; */
    padding-top: 120px;
    padding-bottom: 50px;
}

.video img {
    width: 1080px;
    height: 512px;
    position: relative;
    left: -8%;
}

.video-container {
    position: relative;
}

.video p {
    color: var(--white);
    background: linear-gradient(1.17deg, #023957 -19.65%, #056088 93.67%);
    padding: 40px;
    text-align: left;
    position: absolute;
    right: 113px;
    bottom: -5%;
}

.subscribe {
    color: var(--white);
    text-align: center;
    padding-top: 50px;
    padding-bottom: 50px;
}

.subscribe .container-sub {
    background: linear-gradient(360deg, rgba(2, 57, 87, 0.8) 0%, rgba(5, 96, 136, 0.8) 112.47%), url(../images/BG.jpg);
    padding-left: 280px;
    padding-right: 280px;
    padding-top: 55px;
    padding-bottom: 55px;
    background-size: cover;
}

.subscribe h2 {
    font-weight: 700;
    font-size: 52px;
    line-height: 1.5;
    text-align: center;
    margin-bottom: 16px;
}

.subscribe p {
    font-weight: 500;
    font-size: 16px;
    line-height: 1.7;
    text-align: center;
    margin-bottom: 32px;
}

footer {
    color: var(--white);
    background-color: #023957;
    padding-top: 40px;
    padding-bottom: 40px;
}

.contacts-list a {
    font-size: 16px;
    line-height: 1.5;
}

.footer-nav-container {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-grow: 1;
}

.footer-menu {
    font-weight: 700;
    font-size: 24px;
    line-height: 1.7;
    /* margin-bottom: 32px; */
    margin-right: 50px;

}

.footer-nav {
    display: flex;
    align-items: center;
}

.footer-nav a {
    font-size: 16px;
    line-height: 1.5;
}

.footer-nav .link:hover, .footer-nav .link:focus {
    color: #09A7CA;
}

.footer-nav .link {
    padding-top: 20px;
    padding-bottom: 20px;
}

.footer-nav li:not(:last-child) {
    margin-right: 40px; 
}

.footer-cont {
    display: flex;
}

.footer-logo {
    margin-bottom: 32px;
    display: block;
}

.logo-container{
    margin-right: 149px;
}