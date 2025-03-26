 
# Analiza Danych z Titanica

 **01.02.2025**

 ![Titanic](../titanic//image%20(2).jpg)
 
Zapraszamy Cię do zapoznania się z moją wspaniałą, gruntownie wykonaną analizą eksploracyjną danych (EDA) z Titanica. Mój projekt zawiera wiele ciekawych wniosków, które mogą być niezwykle przydatne w modelowaniu danych. Odkryjemy zależności pomiędzy różnymi kolumnami oraz zidentyfikujemy najważniejsze cechy w naszym zbiorze danych. Dodatkowo, moja analiza wyróżnia się kreatywnością, na przykład poprzez skonstruowanie unikalnego 'survival score'.
 
 <a href="titanic.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>
 
 <iframe
     id="content"
     src="titanic.html"
     width="100%"
     style="border:1px solid black;overflow:hidden;"
 ></iframe>
 <script>
 function resizeIframeToFitContent(iframe) {
     iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
     iframe.contentDocument.body.style["overflow"] = 'hidden';
 }
 window.addEventListener('load', function() {
     var iframe = document.getElementById('content');
     resizeIframeToFitContent(iframe);
 });
 window.addEventListener('resize', function() {
     var iframe = document.getElementById('content');
     resizeIframeToFitContent(iframe);
 });
 </script>
 