---
permalink: browse/
layout: default
title: Browse
---

<ol class="breadcrumb">
    <li><a href="#">Home</a></li>
    <li class="active"><a href="{{ site.baseurl}}/browse/">Public Safety</a></li>
</ol>

<div class="row">
  <div class="col-md-3 col-sm-4 left-nav hidden-xs">
      <nav role="navigation">
          <div class="list-group">
            {% assign my_array = "Government|Jobs|Public Safety|Licensing & Permits|Utilities & Streets|Transportation|Parks & Recreation" | split: "|" %}
            {% for item in my_array %}
              <a href="#" class="list-group-item {% if item == 'Public Safety' %}active{% endif %}">
                  <h4 class="list-group-item-heading">{{ item }}</h4>
              </a>
            {% endfor %}
          </div>
      </nav>
  </div>
  <div class="col-md-3 col-sm-4 left-nav hidden-xs">
      <nav role="navigation">
          <div class="list-group">
              <a href="#" class="list-group-item ">
                  <h4 class="list-group-item-heading">Crime Statistics and Maps</h4>
                  <p class="list-group-item-text">Crime statistics and reports by district and map</p>
              </a>
              <a href="#" class="list-group-item active ">
                  <h4 class="list-group-item-heading">Incident Reports</h4>
                  <p class="list-group-item-text">Including crime, EMS, and traffic collision (accident) reports</p>
              </a>
              <a href="#" class="list-group-item ">
                  <h4 class="list-group-item-heading">Education, Training, and Tips</h4>
                  <p class="list-group-item-text">Smoke alarm installs, car seat education, CPR trainings, and fire truck visits</p>
              </a>
              <a href="#" class="list-group-item ">
                  <h4 class="list-group-item-heading">Fire Stations and Police Departments</h4>
              </a>
              <a href="#" class="list-group-item ">
                  <h4 class="list-group-item-heading">Emergency Services</h4>
                  <p class="list-group-item-text">How to prepare, mitigate and recover from emergencies</p>
              </a>
              <a href="#" class="list-group-item ">
                  <h4 class="list-group-item-heading">Jail and Inmate Support</h4>
                  <p class="list-group-item-text">Includes jail locations, visiting hours, and inmate support services</p>
              </a>
              <a href="#" class="list-group-item ">
                  <h4 class="list-group-item-heading">Report an Issue or Crime</h4>
                  <p class="list-group-item-text">Report a public safety issue or tip - If you are reporting a crime in progress, or require emergency service, please dial 9-1-1 to submit information regarding suspicious, nuisance and criminal activity to the Lexington Police Department</p>
              </a>
          </div>
      </nav>
  </div>
  <div class="col-md-3 col-sm-4 left-nav hidden-xs">
      <nav role="navigation">
          <div class="list-group">
              <a href="#" class="list-group-item ">
                  <h4 class="list-group-item-heading">Incident Report</h4>
              </a>
              <div style="margin-top: 0.5em;font-weight:bold">
                {% assign my_array = "Crime Report|Fire Report|Traffic Collision (Accident) Report" | split: "|" %}
                {% for item in my_array %}
                  <a href="#" class="list-group-item ">
                      <p style="font-size:16px; text-decoration:underline" class="list-group-item-text">{{ item }}</p>
                  </a>
                {% endfor %}
              </div>
          </div>
      </nav>
  </div>
</div>
