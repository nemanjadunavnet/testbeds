---
layout: default
title: AIOTI Testbeds Portfolio
---

<head>
    <link
      rel="stylesheet"
      href="https://cdn.jsdelivr.net/npm/bulma@0.8.2/css/bulma.min.css"
    />
    <link rel="stylesheet" href="{{ '/assets/css/main.css' | relative_url }}" />
    
    <script
      src="https://code.jquery.com/jquery-3.5.0.min.js"
      integrity="sha256-xNzN2a4ltkB44Mc/Jz3pT4iU1cmeR0FkXs4pru/JxaQ="
      crossorigin="anonymous">
    </script>
    <script
      src="https://cdnjs.cloudflare.com/ajax/libs/datatables/1.10.20/js/jquery.dataTables.min.js"
      integrity="sha256-L4cf7m/cgC51e7BFPxQcKZcXryzSju7VYBKJLOKPHvQ="
      crossorigin="anonymous">
      </script>
  </head>

Browse the solutions provided by AIOTI members in the table below.

If you need to return to the main page, just follow [**this link**](./index.html).


### Catalogue of IoT Solutions focused on Testbeds Goals

<table id="catalogue" class="display" style="width: 100%">
    <thead>
      <tr>
        <th>Name</th>
        <th>Domains</th>
        <th>Use-cases</th>
        <th>Provider</th>
        <th>Access</th>
        <th>Testbed stage</th>
      </tr>
    </thead>

    <tbody>
      <!--For loop that iterates over markdown frontmatter in _skus folder-->
      {% for solution in site.solutions %}
      <tr>
        <td><strong><a href="{{ solution.link }}">{{ solution.short_name }}, {{ solution.name }}</a></strong></td>
        <td>{{ solution.domains}}</td>
        <td>{{ solution.use-cases}}</td>
        <td><a href="{{ solution.testbed_url }}"><img src="{{ solution.provider_logo }}" alt="{{ solution.provider }}"/>{{ solution.provider}},{{ solution.city_country}}</a></td>
        <td>{{ solution.licence}}, {{ solution.partner_access}}</td>
        <td>{{ solution.testbed_stage}}</td>
      </tr>
      {% endfor %}
    </tbody>
  <!-- 
    <tfoot>
      <tr>
        <th>Name</th>
        <th>Position</th>
        <th>Description</th>
      </tr>
    </tfoot> -->
  </table>


## Contribute to our Portfolio!

This page is an [open-source project available on GitHub](https://github.com/AIOTIEU/testbeds). Feel free to contribute!

<script>
$(document).ready(function() {
    $('#catalogue').DataTable();
} );
</script>
