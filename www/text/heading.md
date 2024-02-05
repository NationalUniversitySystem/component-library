---
parent: Text
grand_parent: www
---

# Heading

We use the WordPress Core "heading" block wherever possible. There are some legacy headings across the site from before the Block Editor days, particularly in Posts.

<a href="#standard">Standard headings</a><br/>
<a href="#underlined">Underlined variation</a>

<style>
    h1.wp-block-heading, h2.wp-block-heading, h3.wp-block-heading, h4.wp-block-heading, h5.wp-block-heading, h6.wp-block-heading {
        font-family: Besley, serif;
        font-weight: 600;
        line-height: 1.15;
        color: #003a92;
        margin-top: 0;
        margin-bottom: 0;
    }
    h1.wp-block-heading { font-size: clamp(2rem, 5vw, 3.33rem) !important; }
    h2.wp-block-heading { font-size: clamp( 1.6rem, 4vw, 2.66rem ) !important; }
    h3.wp-block-heading { font-size: clamp( 1.4rem, 3vw, 2rem ) !important; }
    h4.wp-block-heading { font-size: clamp( 1.3rem, 2.5vw, 1.66rem ) !important; text-transform: none; letter-spacing: 0; }
    h5.wp-block-heading { font-size: clamp( 1.2rem, 2vw, 1.4rem ) !important; }
    h5.wp-block-heading { font-size: clamp( 1.2rem, 2vw, 1.4rem ) !important; }
    h6.wp-block-heading { font-size: clamp( 1.1rem, 1vw, 1.33rem ) !important; }
    .heading--underlined:after { display: block; content: ""; background-color: #23bdc1; height: 2px; margin-top: 21px; width: 70px; }
    @media (min-width: 992px) {
        .heading--underlined:after { width: 80px; }
    }
</style>

<h1 class="wp-block-heading" id="standard">Heading one</h1><br/>

HTML:

    <h1 class="wp-block-heading">Heading one</h1>

CSS:

    font-size: clamp( 2rem, 5vw, 3.33rem );

    font-family: Besley, serif;
    font-weight: 600;
    line-height: 1.15;
    color: #003a92;

<br/>
<h2 class="wp-block-heading">Heading two</h2><br/>

HTML:

    <h2 class="wp-block-heading">Heading two</h2>

CSS:

    font-size: clamp( 1.6rem, 4vw, 2.66rem );

    font-family: Besley, serif;
    font-weight: 600;
    line-height: 1.15;
    color: #003a92;

<br/>
<h3 class="wp-block-heading">Heading three</h3><br/>

HTML:

    <h3 class="wp-block-heading">Heading three</h3>

CSS:

    font-size: clamp( 1.4rem, 3vw, 2rem );

    font-family: Besley, serif;
    font-weight: 600;
    line-height: 1.15;
    color: #003a92;

<br/>
<h4 class="wp-block-heading">Heading four</h4><br/>

HTML:

    <h4 class="wp-block-heading">Heading four</h4>

CSS:

    font-size: clamp( 1.3rem, 2.5vw, 1.66rem );

    font-family: Besley, serif;
    font-weight: 600;
    line-height: 1.15;
    color: #003a92;

<br/>
<h5 class="wp-block-heading">Heading five</h5><br/>

HTML:

    <h5 class="wp-block-heading">Heading five</h5>

CSS:

    font-size: clamp( 1.2rem, 2vw, 1.4rem );

    font-family: Besley, serif;
    font-weight: 600;
    line-height: 1.15;
    color: #003a92;

<br/>
<h6 class="wp-block-heading">Heading six</h6><br/>

HTML:

    <h6 class="wp-block-heading">Heading six</h6>

CSS:

    font-size: clamp( 1.1rem, 1vw, 1.33rem );

    font-family: Besley, serif;
    font-weight: 600;
    line-height: 1.15;
    color: #003a92;

<hr />

<h1 class="wp-block-heading heading--underlined" id="underlined">Heading one</h1><br/>

HTML:

    <h1 class="wp-block-heading heading--underlined">Heading one</h1>

CSS:

    .heading--underlined:after {
        display: block;
        content: "";
        background-color: #23bdc1;
        height: 2px;
        margin-top: 21px;
        width: 70px;
    }

    @media (min-width: 992px) {
        .heading--underlined:after {
            width: 80px;
        }
    }

<br/>
<h2 class="wp-block-heading heading--underlined">Heading two</h2><br/>

HTML:

    <h2 class="wp-block-heading heading--underlined">Heading two</h2>

CSS:

    .heading--underlined:after {
        display: block;
        content: "";
        background-color: #23bdc1;
        height: 2px;
        margin-top: 21px;
        width: 70px;
    }

    @media (min-width: 992px) {
        .heading--underlined:after {
            width: 80px;
        }
    }

<br/>
<h3 class="wp-block-heading heading--underlined">Heading three</h3><br/>

HTML:

    <h3 class="wp-block-heading heading--underlined">Heading three</h3>

CSS:

    .heading--underlined:after {
        display: block;
        content: "";
        background-color: #23bdc1;
        height: 2px;
        margin-top: 21px;
        width: 70px;
    }

    @media (min-width: 992px) {
        .heading--underlined:after {
            width: 80px;
        }
    }

<br/>
<h4 class="wp-block-heading heading--underlined">Heading four</h4><br/>

HTML:

    <h4 class="wp-block-heading heading--underlined">Heading four</h4>

CSS:

    .heading--underlined:after {
        display: block;
        content: "";
        background-color: #23bdc1;
        height: 2px;
        margin-top: 21px;
        width: 70px;
    }

    @media (min-width: 992px) {
        .heading--underlined:after {
            width: 80px;
        }
    }

<br/>
<h5 class="wp-block-heading heading--underlined">Heading five</h5><br/>

HTML:

    <h5 class="wp-block-heading heading--underlined">Heading five</h5>

CSS:

    .heading--underlined:after {
        display: block;
        content: "";
        background-color: #23bdc1;
        height: 2px;
        margin-top: 21px;
        width: 70px;
    }

    @media (min-width: 992px) {
        .heading--underlined:after {
            width: 80px;
        }
    }

<br/>
<h6 class="wp-block-heading heading--underlined">Heading six</h6><br/>

HTML:

    <h6 class="wp-block-heading heading--underlined">Heading six</h6>

CSS:

    .heading--underlined:after {
        display: block;
        content: "";
        background-color: #23bdc1;
        height: 2px;
        margin-top: 21px;
        width: 70px;
    }

    @media (min-width: 992px) {
        .heading--underlined:after {
            width: 80px;
        }
    }