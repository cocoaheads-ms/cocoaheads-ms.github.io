---
layout: default
title: Welcome!
---

Wir sind der Ableger der [CocoaHeads](http://www.cocoaheads.org) Community in Münster. Wir treffen uns **normalerweise jeden letzten Montag im Monat** (leider aber aktuell nicht sehr regelmäßig) und sprechen über iOS, macOS, watchOS oder tvOS Entwicklung, Swift, Objective-C, etc...

Anfänger sind genau so herzlich willkommen wie Profis! Wenn du Cocoa, Swift oder Objective-C magst und in oder um Münster bist, komm einfach vorbei.

Mehr Infos finden sich auf der <a href="http://cocoaheads.org:8106/de/Muenster/index.html">offiziellen CocoaHeads Seite</a>.

<!--  id="social-buttons" -->
<div class="container-fluid">
	<a class="twitter" href="https://twitter.com/cocoaheads_ms"><span class="title">Twitter</span></a>
	 - 
	<a class="facebook" href="https://www.facebook.com/groups/cocoaheads.ms/"><span clasS="title">Facebook</span></a> 
	 - 
	<a class="meetup" href="https://www.meetup.com/de-DE/CocoaHeads-Munster/"><span clasS="title">MeetUp</span></a> 
	<div class="clear"></div>
</div>

# Nächstes Treffen

<h2 class="meeting upcoming" id="nextMeeting"><small>Wird geladen…</small></h2>
<!-- Bitte auf <a href="http://cocoaheads.org:8106/de/Muenster/index.html">der CocoaHeads Seite</a> schauen. -->

<script language="JavaScript">
var evnt;
function _ical_callback(event) {
  evnt = event;

  var nextMeeting = document.getElementById("nextMeeting");
  
  if (event.startDate === null) {
    nextMeeting.innerHTML = "<i>Kein Event</i>";
    return;
  }
  
  var options = { year: "numeric", month: "long", day: "numeric", hour: "numeric", minute: "2-digit" };
  nextMeeting.innerHTML = "" + event.startDate.toJSDate().toLocaleDateString("de-DE", options) 
	+ "<br>" + event.location;
}
loadICal(_ical_callback);
</script>

Weitere Infos findest du auf <a href="http://cocoaheads.org:8106/de/Muenster/index.html">der offiziellen CocoaHeads Seite</a>.

<!--<address><a href="https://www.warpzone.ms/wiki/newbiebereich:besuch">WarpZone.ms</a><br/>
Am Hawerkamp<br/>
Münster<br/>
</address>
(<a href="https://www.google.de/maps/place/warpzone+e.V./@51.944511,7.63893">map</a>)
-->
<!-- <address><a href="https://www.facebook.com/stullenschmiede/info?tab=page_info">Café Dreiklang</a><br/>
Wolbecker Straße 38<br/>
48155 Münster<br/>
</address>
(<a href="https://www.google.com/maps/place/Wolbecker+Str.+38,+48155+Münster,+Germany/@51.9574967,7.6398686,17z/data=!3m1!4b1!4m2!3m1!1s0x47b9bad8f0000673:0xf2987a2491b207cd">map</a>)
-->

<!--<address><a href="https://www.google.com/maps/place/Früh+Bis+Spät/@51.961794,7.633094,17z/data=!3m1!4b1!4m2!3m1!1s0x47b9bae7be7a8a05:0xef38ea6ffd59a6f2">Früh bis Spät</a><br/>
Alter Steinweg 31<br/>
48143 Münster<br/>
</address>
(<a href="https://www.google.com/maps/place/Früh+Bis+Spät/@51.961794,7.633094,17z/data=!3m1!4b1!4m2!3m1!1s0x47b9bae7be7a8a05:0xef38ea6ffd59a6f2">map</a>)-->

## Vorträge

<div id="talk-survey" class="drop-shadow lifted">
    Hast du Interesse einen Vortrag zu halten, schreib' eine Mail an <a href="mailto:cocoaheads-ms@chbeer.de">Christian</a>!
</div>


### 2018 - Mai

* [Introduction Charles Proxy - Carsten Wenderdel](talks/201805_Carsten_Wenderdel_Charles-Proxy.pdf)

Im [Archiv](talks-archive.html) kann man ältere Vorträge finden.

<!--
# Vergangene Treffen

* Apple Event (live) "Spring Forward." - [RSVP](https://www.facebook.com/events/1571788669765074/)


 -->

# Über

Organisiert durch: [Christian Beer](http://chbeer.de)

Eine Liste der Teilnehmer findest du auf unserer [Facebook Seite](https://www.facebook.com/groups/cocoaheads.ms/).
