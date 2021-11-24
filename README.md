this html page shows incidents of traffic for a choden city.
<button type="button" onclick="getChosenItem()">Submit</button>


<!-- <script>
      function getChosenItem(){
        const xhttp = new XMLHttpRequest();
        xhttp.onreadystatechange = function(){
        let chosenCity = document.getElementById("city").value;
        document.getElementById("mycity").innerHTML = chosenCity;
        let lat;
        let lon;
        let city = document.getElementById("city").value;
        if(city == "New York"){
           lat = 40.71;
           lon = -74.00;
        }
        else if(city ==  "Los Angeles"){
             lat = 34.03;
             lon = -118.15;
        }
        else if(city == "Chicago"){
             lat = 41.53;
             lon = -87.38;
        }
        else if(city == "Seattle"){
             lat = 47.37;
             lon = -122.20;
        }
        else if(city == "Louisville"){
             lat = 38.15;
             lon = -85.46;
        }

      L.mapquest.key = 'AGBTa4KWOct6qBEcQDQUmj1c2RlgfTH4';
      var map = L.mapquest.map('map', {
      center: [lat, lon],
      layers: L.mapquest.tileLayer('map'),
      zoom: 13
});
      map.addControl(L.mapquest.control());
        }
        xhttp.open('POST', 'http://localhost:5502');
        xhttp.send();
    };
     </script> -->