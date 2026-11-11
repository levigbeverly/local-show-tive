---
title: Overview
layout: home
nav_order: 1
---

# 🚂 Local-Show-Tive REST API

**Local-Show-Tive** is a lightweight REST API service for discovering, organizing, and managing local concerts and venues across the United States.

<div class="card-grid">
  <div class="card-box">
    <h3>🎫 Concert-Goers</h3>
    <p>Discover upcoming local shows, search by venue, and filter by artist.</p>
  </div>
  <div class="card-box">
    <h3>🏟️ Venue Owners</h3>
    <p>Publish and manage accurate venue details, location data, and schedules.</p>
  </div>
  <div class="card-box">
    <h3>🎸 Artists & Managers</h3>
    <p>Post show listings, update tour dates, and keep your audience informed.</p>
  </div>
</div>

Built for simplicity, Local-Show-Tive provides an intuitive cloud-based database query layer with zero complex setup required.

*All aboard!*

<p>
  <img src="img/local-show-tive.jpg" alt="Local-Show-Tive Train Logo" style="width: 300px; height: auto; border-radius: 10px; box-shadow: 5px 5px 10px rgba(0,0,0,0.5); object-fit: fill;">
</p>

---

## Getting Started

New to Local-Show-Tive? Follow our step-by-step guides to set up prerequisites and test requests locally:

- **[Getting Started Guide](getting-started.html):** Verify requirements and run your first test request.
- **[Quickstart](quickstart.html):** Set up sample venues and concerts in under 5 minutes.

---

## Tutorials

Learn how to complete common tasks step by step:

- [Add a new venue](tutorials/add-a-venue.html)
- [Add a new concert](tutorials/add-a-concert.html)
- [Search concerts by venue](tutorials/search-for-concerts-by-venue.html)
- [Search concerts by artist](tutorials/search-for-concerts-by-artist.html)

<details>
  <summary><strong>View All Tutorials</strong></summary>
  
  <ul>
    <li><strong>Venues</strong>
      <ul>
        <li><a href="tutorials/add-a-venue.html">Add a venue</a></li>
        <li><a href="tutorials/update-a-venue.html">Update a venue</a></li>
        <li><a href="tutorials/delete-a-venue.html">Delete a venue</a></li>
      </ul>
    </li>
    <li><strong>Concerts</strong>
      <ul>
        <li><a href="tutorials/add-a-concert.html">Add a concert</a></li>
        <li><a href="tutorials/update-a-concert.html">Update a concert</a></li>
        <li><a href="tutorials/search-for-concerts-by-venue.html">Search concerts by venue</a></li>
        <li><a href="tutorials/search-for-concerts-by-artist.html">Search concerts by artist</a></li>
        <li><a href="tutorials/delete-a-concert.html">Delete a concert</a></li>
      </ul>
    </li>
  </ul>
</details>

---

## API Reference

Explore available endpoints under the [`venues`](references/venues.html) and [`concerts`](references/concerts.html) resources:

<details>
  <summary><strong>View Endpoint Reference List</strong></summary>
  
  <ul>
    <li><a href="references/venues.html"><strong>Venues Endpoint (`/venues`)</strong></a>
      <ul>
        <li><span class="badge-http badge-post">POST</span> <a href="references/post-add-venue.html">Add venue</a></li>
        <li><span class="badge-http badge-put">PUT</span> <a href="references/put-update-venue.html">Update venue details</a></li>
        <li><span class="badge-http badge-get">GET</span> <a href="references/get-venues.html">List all venues</a></li>
        <li><span class="badge-http badge-get">GET</span> <a href="references/get-venue-details.html">Get venue by ID</a></li>
        <li><span class="badge-http badge-get">GET</span> <a href="references/get-venue-by-name.html">Find venue by name</a></li>
        <li><span class="badge-http badge-get">GET</span> <a href="references/get-venues-by-city.html">Filter venues by city</a></li>
        <li><span class="badge-http badge-delete">DELETE</span> <a href="references/delete-venue.html">Delete venue</a></li>
      </ul>
    </li>
    
    <li><a href="references/concerts.html"><strong>Concerts Endpoint (`/concerts`)</strong></a>
      <ul>
        <li><span class="badge-http badge-post">POST</span> <a href="references/post-add-concert.html">Create concert listing</a></li>
        <li><span class="badge-http badge-put">PUT</span> <a href="references/put-update-concert.html">Update concert listing</a></li>
        <li><span class="badge-http badge-get">GET</span> <a href="references/get-concerts.html">List all concerts</a></li>
        <li><span class="badge-http badge-get">GET</span> <a href="references/get-concert-details.html">Get concert by ID</a></li>
        <li><span class="badge-http badge-get">GET</span> <a href="references/get-concerts-by-venue-id.html">Find concerts by venue ID</a></li>
        <li><span class="badge-http badge-get">GET</span> <a href="references/get-concerts-by-artist.html">Find concerts by artist</a></li>
        <li><span class="badge-http badge-get">GET</span> <a href="references/get-concerts-by-date.html">Filter concerts by date</a></li>
        <li><span class="badge-http badge-delete">DELETE</span> <a href="references/delete-concert.html">Delete concert listing</a></li>
      </ul>
    </li>
  </ul>
</details>

---

## Support & Contact

Have questions or feedback about **Local-Show-Tive**? Reach out via email at [`levigbeverly@gmail.com`](mailto:levigbeverly@gmail.com).
