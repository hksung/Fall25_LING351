---
type: assignment
date: 2025-11-14T23:59:00+3:30
title: '3. Assignment guidelines'

due_event: 
    type: due
    date: 2025-12-05T23:59:00+3:30
    description: '3. Assignment guidelines'
---
After each presentation round (Nov 14 & Dec 5), students will submit their presentation slides (PDF with quiz questions) and a short written reflection. This is a graded assignment: 10 points total * 2 (20% of final grade).

{% assign pdf = '/Files/Assignment_Guidelines.pdf' %}

<!-- Inline preview (with fallback) -->
<object
  data="{{ pdf | relative_url }}"
  type="application/pdf"
  width="100%"
  height="800">
  <p>
    PDF preview isn’t available in this browser.
    <a href="{{ pdf | relative_url }}" target="_blank" rel="noopener">Open the PDF</a>.
  </p>
</object>

<!-- Download + open in new tab -->
<p>
  <a href="{{ pdf | relative_url }}" download>Download PDF</a>
  &nbsp;|&nbsp;
  <a href="{{ pdf | relative_url }}" target="_blank" rel="noopener">Open in new tab</a>
</p>
