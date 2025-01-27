+++
top_logo_custom="/assets/local/eindhoven2023/img/juliacon_local_eindhoven_logo.png"
top_logo_link="/local/eindhoven2023"

top_navbar_custom_flag="/assets/local/eindhoven2023/img/vibes.png"
footer_hide_signup_form = true
footer_hide_social_media = true
+++

# JuliaCon Local Eindhoven 2023 Program

We are thrilled to announce the official program for JuliaCon Local Eindhoven 2023! Our team has carefully curated a diverse and captivating lineup of talks, workshops, panels, and networking sessions designed to cater to a wide range of interests and levels of Julia expertise. Do not miss an opportunity to signup for the [Pluto workshop](/local/eindhoven2023/pluto) one day before JuliaCon Local Eindhoven 2023.

## Detailed schedule

To view the detailed schedule, simply scroll down or visit [this website](https://eindhoven2023.pydata.org/juliacon/schedule/).

~~~
<script type="text/javascript" src="https://eindhoven2023.pydata.org/juliacon/schedule/widget/v2.en.js"></script>
<pretalx-schedule event-url="https://eindhoven2023.pydata.org/juliacon/" locale="en" format="grid" style="--pretalx-clr-primary: #4C9CB4"></pretalx-schedule>

<script type="text/javascript">
// Hack the pretalx viewer, since they don't provide an easy way to set the width
document.addEventListener("DOMContentLoaded", function() {
  // Add a small delay (e.g., 100 milliseconds) to ensure the element is available
  setTimeout(function() {
    // Find the element "pretalx-schedule"
    var scheduleRoot = document.querySelector("pretalx-schedule");

    // Query its shadow root
    var scheduleElement = scheduleRoot.shadowRoot.querySelector(".pretalx-schedule")

    // Calculate 80% of the current browser view width
    var maxWidth = Math.min(window.innerWidth * 0.8, 1378);

    // Change the style setting "--schedule-max-width"
    scheduleElement.style.setProperty("--schedule-max-width", maxWidth + "px");
  }, 250);
});
</script>

<noscript>
   <div class="pretalx-widget">
        <div class="pretalx-widget-info-message">
            JavaScript is disabled in your browser. To access our schedule without JavaScript,
            please <a target="_blank" href="https://eindhoven2023.pydata.org/juliacon/schedule/">click here</a>.
        </div>
    </div>
</noscript>
~~~