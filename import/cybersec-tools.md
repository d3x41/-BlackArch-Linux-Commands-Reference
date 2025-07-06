# cybersec tools

\
&#x20; (function() {\
&#x20;   if('serviceWorker' in navigator) {\
&#x20;     window.addEventListener('load', function () {\
&#x20;       navigator.serviceWorker.register('/service-worker.js')\
&#x20;         .catch(function (error) {\
&#x20;           console.error('ServiceWorker failed to register', error)\
&#x20;         });\
&#x20;     })\
&#x20;   }\
&#x20; })();\
&#x20; (function(w,d,s,l,i) {\
&#x20;   w\[l]=w\[l]||\[];\
&#x20;   w\[l].push({'gtm.start':new Date().getTime(),event:'gtm.js'});\
&#x20;   var f=d.getElementsByTagName(s)\[0], j=d.createElement(s),dl=l!='dataLayer'?'\&l='+l:'';\
&#x20;   j.async=true;\
&#x20;   j.src='//www.googletagmanager.com/gtm.js?id='+i+dl;\
&#x20;   f.parentNode.insertBefore(j,f);\
&#x20; })(window,document,'script','dataLayer','GTM-PV67T8');(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.\_\_CF$cv$params={r:'95ab089c8b18c714',t:'MTc1MTc2MjI0Ny4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')\[0].appendChild(a);";b.getElementsByTagName('head')\[0].appendChild(d)\}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())\}}\}})();
