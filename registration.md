---
title: Registration
layout: page
feature_image: "normale.jpg"
# image_source:
---
{% assign early_entry = site.data.dates | where: "id", "early-bird" %}
{% assign early_date = early_entry[0].entries[0].date | date: "%a, %d %b %Y"%}
{% assign registration_entry = site.data.dates | where: "id", "registration" %}
{% assign registration_date = registration_entry[0].entries[0].date | date: "%a, %d %b %Y"%}


## Dates

- **Early registration deadline:** {{ early_date }}
- **Late registration deadline:** {{ registration_date }}

## Participant Registration

The Conference registration fee includes:

- Participation in all technical sessions
- Digital Access to conference pre-proceedings
- Meals and coffee breaks during the conference.

The participation in the conference social dinner can be paid directly on-site. You will receive instructions after the registration.

**At least one author per paper must register at full rate.**

## Registration Process

1. Download and complete the registration form in all its parts,
2. Sign it, scan it and send it to <a href="mailto:ricerca@di.unipi.it">ricerca@di.unipi.it</a>, and 
3. Follow the instructions on the second page of the registration form to proceed with the payment.

<div markdown="1" class="text-justify">
<p style="margin:2em;" class="text-center">
    <a href="https://pages.di.unipi.it/forti/microservices23/registrationform.doc" target="_blank">
        <button style="padding:1em;" type="button" class="btn btn-primary btn-lg enabled">Download the registration form</button>
    </a>
</p>
<div class="clearfix"></div>

The Microservices Conference will host the General Assembly of the Microservices Community, where the future directions of the community are discussed. The assembly is open to all community members.

If you are interested in joining the community, follow this link:

<p style="margin:2em;" class="text-center">
    <a href="https://microservices.sdu.dk/join/" target="_blank">
        <button style="padding:1em;" type="button" class="btn btn-primary btn-lg">Join the Microservices Community</button>
    </a>
</p>

## Registration fees

<table class="table">
<thead>
<tr>
<th><strong>Category</strong></th>
<th><strong>Fee (early)</strong></th>
<th><strong>Fee (late)</strong></th>
</tr>
</thead>
<tbody>

<tr>
    <td>Full registration</td>
    <td>250,00€</td>
    <td>300,00€</td>
</tr>

<tr>
    <td>Student registration</td>
    <td>190,00€</td>
    <td>230,00€</td>
</tr>
</tbody>
</table>

<!-- <div markdown="1" class="text-justify">
<p style="margin:2em;" class="text-center">
    <button style="padding:1em;" type="button" class="btn btn-primary btn-lg disabled">The registration is closed</button>
</p>
<div class="clearfix"></div>

</div> -->

{%- comment -%}
<span id="invoicing-info" />

# Ticket Invoicing Party

<div class="text-justify col-xs-8">
<strong>Invoicing Party:</strong><br/>
<strong>Address:</strong><br/>
<strong>VAT No.:</strong>
</div>
{%- endcomment -%}
