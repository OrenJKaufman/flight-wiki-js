---
title: Boeing 737
description: 
published: true
date: 2026-10-07T23:14:30.631Z
tags: 
editor: markdown
dateCreated: 2026-10-07T21:03:37.888Z
---

## OnAir Loading
Subtract 4,000 lbs from OnAir when entering into SimBrief.
## References
<a href="/assets/qrh/1_737-800-qrh.pdf" target="_blank">QRH</a>
[Download QRH](/assets/qrh/1_737-800-qrh.pdf)
[Open QRH](pdfefile://truenas.local:4500/assets/qrh/1_737-800-qrh.pdf)
<script>
document.addEventListener("DOMContentLoaded", function() {
  document.body.addEventListener("click", function(e) {
    let link = e.target.closest("a");
    
    // Check if the clicked link is a PDF
    if (link && link.href.toLowerCase().endsWith(".pdf")) {
      
      // Check if we are running inside the standalone iPad PWA container
      const isPWA = window.navigator.standalone === true || window.matchMedia('(display-mode: standalone)').matches;
      
      // If we are in the PWA and the browser supports the native Share API
      if (isPWA && navigator.share) {
        e.preventDefault(); // Stop the PWA container from breaking or opening inline
        
        // Pass the absolute file URL straight into the native iPadOS Share Menu
        navigator.share({
          title: link.innerText || "Aircraft Handbook",
          url: link.href
        })
        .catch(function(err) {
          console.log("Share menu dismissed or failed: ", err);
        });
      }
    }
  });
});
</script>

