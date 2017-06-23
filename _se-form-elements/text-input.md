---
layout: default
title: Text input
usage: Group form fields together into smaller chunks, this makes the form feel easier to complete and less intimidating. Labels should always be used as screen-readers will have problems if they are omitted. The wrapping label pattern is preferred over the use of the for attribute, as this requires a corresponding id on the target form input, which may change according to how it needs to be integrated with a backend system. All inputs have autocorrect="off" added for usability on mobiles and tablets.
---


<div class="form-group relative">
    <label for="name">Name</label>
    <input aria-required="true" required="" id="name" class="grey form-control input--large dirty" type="text">
    <ul class="current-errors"></ul>
</div>