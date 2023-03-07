---
title: Registration
layout: page
feature_image: "normale.jpg"
# image_source:
---

{% assign registration_dates = site.data.dates | where: "id", "registration" %}
{% assign registration_end = registration_dates[0].entries[0].to | date: "%a %d %b %Y" %}

## Dates

- **Early registration deadline:** TODO
- **Late registration deadline:** TODO

## Participant Registration

The Conference registration fee includes:

- Participation in all technical sessions
- Digital Access to conference pre-proceedings
- A meal and coffee breaks during the conference.

The participation in the conference social dinner can be bought separately
during the registration process (one ticket per person).

**At least one author per paper must register.**

## Registration Process

<div markdown="1" class="text-justify">
<p style="margin:2em;" class="text-center">
        <button style="padding:1em;" type="button" class="btn btn-primary btn-lg disabled">The registration is closed</button>
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
    <td>TODO</td>
    <td>TODO</td>
    <td>TODO</td>
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
