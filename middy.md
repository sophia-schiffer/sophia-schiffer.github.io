---
title: Cat News - Sophia Schiffer
image1: /assets/images/MiddyTime/middy1.png
image2: /assets/images/MiddyTime/middy2.png
---

# This Week's Newsletter

<img src="{{ page.image1 | relative_url }}" alt="page1.png">
<br>
<img src="{{ page.image2 | relative_url }}" alt="page2.png">

<div class="button-container">
    <a href="#" onclick="openPopup('subscribe.html'); return false;">
        <button type="button" class="button" style="text-decoration: none;">
            Subscribe!
        </button>
    </a>
    <a href="#" onclick="openPopup('unsubscribe.html'); return false;">
        <button type="button" class="button" style="text-decoration: none;">
            Unsubscribe :(
        </button>
    </a>
</div>

<script>
    function openPopup(url) {
        var width = 600;
        var height = 300;
        var left = (window.innerWidth / 2) - (width / 2);  // Calculate horizontal center
        var top = (window.innerHeight / 2) - (height / 2); // Calculate vertical center

        var MyWindow = window.open(url, 'PopupWindow', 
            'width=' + width + ',height=' + height + 
            ',left=' + left + ',top=' + top + 
            ',scrollbars=yes,resizable=yes');

        if (MyWindow) {
            MyWindow.focus(); // Bring the popup to the front
        }
    }
</script>