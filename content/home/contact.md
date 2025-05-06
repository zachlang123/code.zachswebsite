---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

align: left
title: Contact Me
subtitle:

content:
  # Automatically link email and phone or display as text?
  autolink: true

  
design:
  columns: '2'
---
<style>
    .google-maps {
        position: relative;
        padding-bottom: 75%; // This is the aspect ratio
        height: 0;
        overflow: hidden;
    }
    .google-maps iframe {
        position: absolute;
        top: 0;
        left: 0;
        width: 100% !important;
        height: 100% !important;
    }
</style>

<div class="google-maps">
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3844.0214096403015!2d-82.64206008815394!3d34.51461187287374!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x88586c2e16cebfc1%3A0xc6467d7192b53cf9!2sAnderson%20University!5e1!3m2!1sen!2sus!4v1746544370707!5m2!1sen!2sus" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade" width="600" height="450" style="border:0"></iframe>
</div>
