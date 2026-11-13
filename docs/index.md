---
title: Overview
layout: home
nav_order: 1
---

# Local-Show-Tive REST API

**Local-Show-Tive** is a lightweight REST API service for discovering, organizing, and managing local concerts and venues across the United States.

<div class="card-grid" style="grid-template-columns: repeat(auto-fit, minmax(240px, 1fr)) !important; margin-bottom: 2rem !important;">
  <div class="card-box">
    <h3>Concert-Goers</h3>
    <p>Find a detailed list of upcoming shows in your area.</p>
  </div>
  <div class="card-box">
    <h3>Venue Owners</h3>
    <p>Share consistent information about your venue.</p>
  </div>
  <div class="card-box">
    <h3>Artists & Promoters</h3>
    <p>Post and update information about upcoming shows.</p>
  </div>
</div>

**Local-Show-Tive** allows users to update and query an ongoing database of concerts and venues. The service is cloud-based, available on any internet-connected device, and designed for minimal to no prior REST API experience.

*All aboard!*

<p style="margin: 2rem 0;">
  <img src="img/local-show-tive.jpg" alt="Local-Show-Tive Train Logo" style="width: 100%; max-width: 600px; height: auto; border-radius: 12px; border: 1px solid #1f2430; box-shadow: 0 8px 24px rgba(0,0,0,0.6); display: block; margin-left: auto; margin-right: auto;">
</p>

---

## First-time Users

<div class="card-box" style="margin-top: 1rem; margin-bottom: 1.5rem; background: rgba(245, 158, 11, 0.04) !important; border-color: rgba(245, 158, 11, 0.2) !important;">
  <p style="margin-bottom: 0.5rem;">If this is your first time setting up and using <strong>Local-Show-Tive</strong>, see <a href="getting-started.md">Getting Started</a> to walk through service prerequisites and local testing.</p>
  <p style="margin-bottom: 0;">Once completed, check out the <a href="quickstart.md">Quickstart</a> guide to rapidly set up your first concerts and venues.</p>
</div>

---

## Tutorials

Learn how to complete the most common **Local-Show-Tive** tasks:
- [Add a venue](tutorials/add-a-venue.html)
- [Add a concert](tutorials/add-a-concert.html)
- [Search for concerts by venue](tutorials/search-for-concerts-by-venue.html)
- [Search for concerts by artist](tutorials/search-for-concerts-by-artist.html)

To view the full list of available tutorials, expand the menu below:

<details>
  <summary><strong>View All Tutorials</strong></summary>
  
<ul>
  <li><strong>venues</strong>
    <ul>
      <li><a href="tutorials/add-a-venue.html">Add a venue</a></li>
      <li><a href="tutorials/update-a-venue.html">Update a venue</a></li>
      <li><a href="tutorials/delete-a-venue.html">Delete a venue</a></li>
    </ul>
  </li>
  
  <li><strong>concerts</strong>
    <ul>
      <li><a href="tutorials/add-a-concert.html">Add a concert</a></li>
      <li><a href="tutorials/update-a-concert.html">Update a concert</a></li>
      <li><a href="tutorials/search-for-concerts-by-venue.html">Search for concerts by venue</a></li>
      <li><a href="tutorials/search-for-concerts-by-artist.html">Search for concerts by artist</a></li>
      <li><a href="tutorials/delete-a-concert.html">Delete a concert</a></li>
    </ul>
  </li>
</ul>

</details>

---

## References

All venue-related actions are performed under the [`venues`](references/venues.md) resource, and all concert-related actions are performed with the [`concerts`](references/concerts.md) resource.

To view detailed descriptions of the service's resources and individual API calls, expand the menu below:

<details>
  <summary><strong>View Endpoint Reference List</strong></summary>
  
<ul>
  <li><a href="references/venues.html"><strong>venues</strong></a> resource
    <ul>
      <li><span class="badge-http badge-post">POST</span> <a href="references/post-add-venue.html">Add venue</a></li>
      <li><span class="badge-http badge-put">PUT</span> <a href="references/put-update-venue.html">Update venue</a></li>
      <li><span class="badge-http badge-get">GET</span> <a href="references/get-venues.html">Get venues</a></li>
      <li><span class="badge-http badge-get">GET</span> <a href="references/get-venue-details.html">Get venue details</a></li>
      <li><span class="badge-http badge-get">GET</span> <a href="references/get-venue-by-name.html">Get venue by name</a></li>
      <li><span class="badge-http badge-get">GET</span> <a href="references/get-venues-by-city.html">Get venues by city</a></li>
      <li><span class="badge-http badge-delete">DELETE</span> <a href="references/delete-venue.html">Delete venue</a></li>
    </ul>
  </li>
  
  <li><a href="references/concerts.html"><strong>concerts</strong></a> resource
    <ul>
      <li><span class="badge-http badge-post">POST</span> <a href="references/post-add-concert.html">Add concert</a></li>
      <li><span class="badge-http badge-put">PUT</span> <a href="references/put-update-concert.html">Update concert</a></li>
      <li><span class="badge-http badge-get">GET</span> <a href="references/get-concerts.html">Get concerts</a></li>
      <li><span class="badge-http badge-get">GET</span> <a href="references/get-concert-details.html">Get concert details</a></li>
      <li><span class="badge-http badge-get">GET</span> <a href="references/get-concerts-by-venue-id.html">Get concerts by venue id</a></li>
      <li><span class="badge-http badge-get">GET</span> <a href="references/get-concerts-by-artist.html">Get concerts by artist</a></li>
      <li><span class="badge-http badge-get">GET</span> <a href="references/get-concerts-by-date.html">Get concerts by date</a></li>
      <li><span class="badge-http badge-delete">DELETE</span> <a href="references/delete-concert.html">Delete concert</a></li>
    </ul>
  </li>
</ul>

</details>

---

## Support & Contact

If you have questions or inquiries related to **Local-Show-Tive** or its documentation, please email `levigbeverly@gmail.com`.
