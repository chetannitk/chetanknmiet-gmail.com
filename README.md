# chetanknmiet-gmail.com
COVID-19
<!DOCTYPE html>
<html>
<head>    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.5.1/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-1.12.4.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.5.1/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://rawcdn.githack.com/python-visualization/folium/master/folium/templates/leaflet.awesome.rotate.css"/>
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_e6ae7888d25a4796b3074d998b100d7d {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
            </style>
        
</head>
<body>    
    
            <div class="folium-map" id="map_e6ae7888d25a4796b3074d998b100d7d" ></div>
        
</body>
<script>    
    
            var map_e6ae7888d25a4796b3074d998b100d7d = L.map(
                "map_e6ae7888d25a4796b3074d998b100d7d",
                {
                    center: [23.26, 77.39],
                    crs: L.CRS.EPSG3857,
                    zoom: 4.5,
                    zoomControl: true,
                    preferCanvas: false,
                }
            );

            

        
    
            var tile_layer_b422fcd9db0f425bafd33704e8c31a31 = L.tileLayer(
                "https://stamen-tiles-{s}.a.ssl.fastly.net/toner/{z}/{x}/{y}.png",
                {"attribution": "Map tiles by \u003ca href=\"http://stamen.com\"\u003eStamen Design\u003c/a\u003e, under \u003ca href=\"http://creativecommons.org/licenses/by/3.0\"\u003eCC BY 3.0\u003c/a\u003e. Data by \u0026copy; \u003ca href=\"http://openstreetmap.org\"\u003eOpenStreetMap\u003c/a\u003e, under \u003ca href=\"http://www.openstreetmap.org/copyright\"\u003eODbL\u003c/a\u003e.", "detectRetina": false, "maxNativeZoom": 18, "maxZoom": 18, "minZoom": 0, "noWrap": false, "opacity": 1, "subdomains": "abc", "tms": false}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
            var circle_marker_36300dc82b6a4e938f243c8e71431d22 = L.circleMarker(
                [16.94374, 82.23506],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_ec5f67efb8884c81a2c8cef7c37ad44a = L.popup({"maxWidth": "100%"});

        
            var html_713dd16590c14672bff4b9285ec98d16 = $(`<div id="html_713dd16590c14672bff4b9285ec98d16" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: East godavari<br><strong>State</strong>: Andhra Pradesh<br><strong>Confirmed Cases</strong>: 2<br></div>`)[0];
            popup_ec5f67efb8884c81a2c8cef7c37ad44a.setContent(html_713dd16590c14672bff4b9285ec98d16);
        

        circle_marker_36300dc82b6a4e938f243c8e71431d22.bindPopup(popup_ec5f67efb8884c81a2c8cef7c37ad44a)
        ;

        
    
    
            var circle_marker_c58ef0c742474bc3b273dec523404943 = L.circleMarker(
                [16.31043, 81.16987],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_4df1424c14414d00b01128ccb1a5594a = L.popup({"maxWidth": "100%"});

        
            var html_ee0e203f3e984231b032be6fecdff106 = $(`<div id="html_ee0e203f3e984231b032be6fecdff106" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Krishna<br><strong>State</strong>: Andhra Pradesh<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_4df1424c14414d00b01128ccb1a5594a.setContent(html_ee0e203f3e984231b032be6fecdff106);
        

        circle_marker_c58ef0c742474bc3b273dec523404943.bindPopup(popup_4df1424c14414d00b01128ccb1a5594a)
        ;

        
    
    
            var circle_marker_1cb04b4be1d14959811ae3570ff451e7 = L.circleMarker(
                [14.44606, 79.98622],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_695487ed5d2f4f209ab82062882e274f = L.popup({"maxWidth": "100%"});

        
            var html_25d331edd53e4251949b1c6863e976e6 = $(`<div id="html_25d331edd53e4251949b1c6863e976e6" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Nellore<br><strong>State</strong>: Andhra Pradesh<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_695487ed5d2f4f209ab82062882e274f.setContent(html_25d331edd53e4251949b1c6863e976e6);
        

        circle_marker_1cb04b4be1d14959811ae3570ff451e7.bindPopup(popup_695487ed5d2f4f209ab82062882e274f)
        ;

        
    
    
            var circle_marker_8145abf03e9346469739176a7f03adff = L.circleMarker(
                [15.63227, 79.64718],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_41d50db6b0ae472a9f451ce58208149a = L.popup({"maxWidth": "100%"});

        
            var html_99f7c3a597b840fe9f54e0fa26f8d9a7 = $(`<div id="html_99f7c3a597b840fe9f54e0fa26f8d9a7" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Prakasam<br><strong>State</strong>: Andhra Pradesh<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_41d50db6b0ae472a9f451ce58208149a.setContent(html_99f7c3a597b840fe9f54e0fa26f8d9a7);
        

        circle_marker_8145abf03e9346469739176a7f03adff.bindPopup(popup_41d50db6b0ae472a9f451ce58208149a)
        ;

        
    
    
            var circle_marker_1a651cca0a874b3aa0b445fe7bb020ae = L.circleMarker(
                [15.57429, 80.12893],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_a0436053ac88443eaa0228c5f28e6895 = L.popup({"maxWidth": "100%"});

        
            var html_6b9a9e8a7a544514936b7f0add28c867 = $(`<div id="html_6b9a9e8a7a544514936b7f0add28c867" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Vizag<br><strong>State</strong>: Andhra Pradesh<br><strong>Confirmed Cases</strong>: 2<br></div>`)[0];
            popup_a0436053ac88443eaa0228c5f28e6895.setContent(html_6b9a9e8a7a544514936b7f0add28c867);
        

        circle_marker_1a651cca0a874b3aa0b445fe7bb020ae.bindPopup(popup_a0436053ac88443eaa0228c5f28e6895)
        ;

        
    
    
            var circle_marker_661a84a65b0643f09e32671d377bd54e = L.circleMarker(
                [25.21616, 86.52812],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_162ba229d86741579e1c67d8463b6b9d = L.popup({"maxWidth": "100%"});

        
            var html_0f0f6f6ac2a8429a8aa0436940506264 = $(`<div id="html_0f0f6f6ac2a8429a8aa0436940506264" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Munger<br><strong>State</strong>: BIHAR<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_162ba229d86741579e1c67d8463b6b9d.setContent(html_0f0f6f6ac2a8429a8aa0436940506264);
        

        circle_marker_661a84a65b0643f09e32671d377bd54e.bindPopup(popup_162ba229d86741579e1c67d8463b6b9d)
        ;

        
    
    
            var circle_marker_535678d0a32c4bb8bf898a8973ce6690 = L.circleMarker(
                [25.60524, 85.14085],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_1de8a05e476b46f5abee696982fc4510 = L.popup({"maxWidth": "100%"});

        
            var html_c268bc76e91a4ca783004847ef1246cc = $(`<div id="html_c268bc76e91a4ca783004847ef1246cc" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Patna<br><strong>State</strong>: BIHAR<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_1de8a05e476b46f5abee696982fc4510.setContent(html_c268bc76e91a4ca783004847ef1246cc);
        

        circle_marker_535678d0a32c4bb8bf898a8973ce6690.bindPopup(popup_1de8a05e476b46f5abee696982fc4510)
        ;

        
    
    
            var circle_marker_2ac28d9930364133b9d117ade6f0db6d = L.circleMarker(
                [30.72604, 76.77768],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_1f88a80c58ff4fc2a5ec5ac922107a9e = L.popup({"maxWidth": "100%"});

        
            var html_3628f64dca5043bcb2de82eb689abc59 = $(`<div id="html_3628f64dca5043bcb2de82eb689abc59" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Chandigarh<br><strong>State</strong>: Chandigarh<br><strong>Confirmed Cases</strong>: 6<br></div>`)[0];
            popup_1f88a80c58ff4fc2a5ec5ac922107a9e.setContent(html_3628f64dca5043bcb2de82eb689abc59);
        

        circle_marker_2ac28d9930364133b9d117ade6f0db6d.bindPopup(popup_1f88a80c58ff4fc2a5ec5ac922107a9e)
        ;

        
    
    
            var circle_marker_454a5c592ebe4de7833599a85cc41b3b = L.circleMarker(
                [21.20789, 81.62618],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_212ced61ac384089911b0a35e7c3557e = L.popup({"maxWidth": "100%"});

        
            var html_f8295473117b4f33a382bab21a9d01f0 = $(`<div id="html_f8295473117b4f33a382bab21a9d01f0" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Raipur<br><strong>State</strong>: Chhattisgarh<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_212ced61ac384089911b0a35e7c3557e.setContent(html_f8295473117b4f33a382bab21a9d01f0);
        

        circle_marker_454a5c592ebe4de7833599a85cc41b3b.bindPopup(popup_212ced61ac384089911b0a35e7c3557e)
        ;

        
    
    
            var circle_marker_3760a23257e84e78b12ded554521f679 = L.circleMarker(
                [28.64231, 77.21332],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_ac1ffc306b3c4681899ebcf1d669a75d = L.popup({"maxWidth": "100%"});

        
            var html_bc9b2f927a63438f83042e95386f11d9 = $(`<div id="html_bc9b2f927a63438f83042e95386f11d9" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Central<br><strong>State</strong>: Delhi<br><strong>Confirmed Cases</strong>: 3<br></div>`)[0];
            popup_ac1ffc306b3c4681899ebcf1d669a75d.setContent(html_bc9b2f927a63438f83042e95386f11d9);
        

        circle_marker_3760a23257e84e78b12ded554521f679.bindPopup(popup_ac1ffc306b3c4681899ebcf1d669a75d)
        ;

        
    
    
            var circle_marker_1a1dd484c87e4bc69e81555ed1552fcd = L.circleMarker(
                [28.65137, 77.29074],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_56525e2234f14d08982a2cc988ff33e8 = L.popup({"maxWidth": "100%"});

        
            var html_f77791abc5494446baf7e13dd0e32398 = $(`<div id="html_f77791abc5494446baf7e13dd0e32398" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: East delhi<br><strong>State</strong>: Delhi<br><strong>Confirmed Cases</strong>: 3<br></div>`)[0];
            popup_56525e2234f14d08982a2cc988ff33e8.setContent(html_f77791abc5494446baf7e13dd0e32398);
        

        circle_marker_1a1dd484c87e4bc69e81555ed1552fcd.bindPopup(popup_56525e2234f14d08982a2cc988ff33e8)
        ;

        
    
    
            var circle_marker_d8cf2fc21f9946a5b7461c57214d87a1 = L.circleMarker(
                [28.6951, 77.21427],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_223badb1ff9a4eaf94d048fdff219e47 = L.popup({"maxWidth": "100%"});

        
            var html_661bc4cc8e1c4fb9be2d3de12f9d0557 = $(`<div id="html_661bc4cc8e1c4fb9be2d3de12f9d0557" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: North delhi<br><strong>State</strong>: Delhi<br><strong>Confirmed Cases</strong>: 3<br></div>`)[0];
            popup_223badb1ff9a4eaf94d048fdff219e47.setContent(html_661bc4cc8e1c4fb9be2d3de12f9d0557);
        

        circle_marker_d8cf2fc21f9946a5b7461c57214d87a1.bindPopup(popup_223badb1ff9a4eaf94d048fdff219e47)
        ;

        
    
    
            var circle_marker_8a5fc207ac6942868b1112d8707f7e4c = L.circleMarker(
                [28.67108, 77.31587],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_a627f885be614a9dba22e5b1abc9da31 = L.popup({"maxWidth": "100%"});

        
            var html_ad944a74bff94976ba20ffb5c1a0e486 = $(`<div id="html_ad944a74bff94976ba20ffb5c1a0e486" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: North east<br><strong>State</strong>: Delhi<br><strong>Confirmed Cases</strong>: 5<br></div>`)[0];
            popup_a627f885be614a9dba22e5b1abc9da31.setContent(html_ad944a74bff94976ba20ffb5c1a0e486);
        

        circle_marker_8a5fc207ac6942868b1112d8707f7e4c.bindPopup(popup_a627f885be614a9dba22e5b1abc9da31)
        ;

        
    
    
            var circle_marker_9e620fcdf6734d9c9e01cc5e38b7f84f = L.circleMarker(
                [28.71188, 77.11934],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_d17f4785dbb249d49673113e7536a09e = L.popup({"maxWidth": "100%"});

        
            var html_0450990cd5bb4a7e950b2caa3229a4f0 = $(`<div id="html_0450990cd5bb4a7e950b2caa3229a4f0" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: North west<br><strong>State</strong>: Delhi<br><strong>Confirmed Cases</strong>: 5<br></div>`)[0];
            popup_d17f4785dbb249d49673113e7536a09e.setContent(html_0450990cd5bb4a7e950b2caa3229a4f0);
        

        circle_marker_9e620fcdf6734d9c9e01cc5e38b7f84f.bindPopup(popup_d17f4785dbb249d49673113e7536a09e)
        ;

        
    
    
            var circle_marker_81cd560de9ac4f6cbb14cbd07301dc44 = L.circleMarker(
                [28.5479, 77.23791],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_97d9a077a67d41cab98bd8380c08bed3 = L.popup({"maxWidth": "100%"});

        
            var html_d60260303883449da46c805588027373 = $(`<div id="html_d60260303883449da46c805588027373" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: South delhi<br><strong>State</strong>: Delhi<br><strong>Confirmed Cases</strong>: 3<br></div>`)[0];
            popup_97d9a077a67d41cab98bd8380c08bed3.setContent(html_d60260303883449da46c805588027373);
        

        circle_marker_81cd560de9ac4f6cbb14cbd07301dc44.bindPopup(popup_97d9a077a67d41cab98bd8380c08bed3)
        ;

        
    
    
            var circle_marker_b2902126c73e4babb810e14d8bcbc061 = L.circleMarker(
                [28.54351, 77.11657],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_88bbe9aeb22d46eaade7889732e58047 = L.popup({"maxWidth": "100%"});

        
            var html_fc55644656494f83ad719ff2e4d6a4ef = $(`<div id="html_fc55644656494f83ad719ff2e4d6a4ef" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: South west<br><strong>State</strong>: Delhi<br><strong>Confirmed Cases</strong>: 3<br></div>`)[0];
            popup_88bbe9aeb22d46eaade7889732e58047.setContent(html_fc55644656494f83ad719ff2e4d6a4ef);
        

        circle_marker_b2902126c73e4babb810e14d8bcbc061.bindPopup(popup_88bbe9aeb22d46eaade7889732e58047)
        ;

        
    
    
            var circle_marker_fc454c85eab24b609a6d7c3710a90287 = L.circleMarker(
                [28.64212, 77.11103],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_d15ab64ae9b4443a8a805744838979f1 = L.popup({"maxWidth": "100%"});

        
            var html_a063045e11734854b120b9187ef9bb5a = $(`<div id="html_a063045e11734854b120b9187ef9bb5a" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: West delhi<br><strong>State</strong>: Delhi<br><strong>Confirmed Cases</strong>: 5<br></div>`)[0];
            popup_d15ab64ae9b4443a8a805744838979f1.setContent(html_a063045e11734854b120b9187ef9bb5a);
        

        circle_marker_fc454c85eab24b609a6d7c3710a90287.bindPopup(popup_d15ab64ae9b4443a8a805744838979f1)
        ;

        
    
    
            var circle_marker_32095eaf2c7b413a8eed6eb7e686d59a = L.circleMarker(
                [22.75039, 72.30294],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_cd0f65f588ee43a8954cc90c5158fb38 = L.popup({"maxWidth": "100%"});

        
            var html_3825577208c74adcaadd56350d2cbdcb = $(`<div id="html_3825577208c74adcaadd56350d2cbdcb" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Ahmedabad<br><strong>State</strong>: Gujarat<br><strong>Confirmed Cases</strong>: 13<br></div>`)[0];
            popup_cd0f65f588ee43a8954cc90c5158fb38.setContent(html_3825577208c74adcaadd56350d2cbdcb);
        

        circle_marker_32095eaf2c7b413a8eed6eb7e686d59a.bindPopup(popup_cd0f65f588ee43a8954cc90c5158fb38)
        ;

        
    
    
            var circle_marker_4006da2bfbed436898f71274f66fcd81 = L.circleMarker(
                [23.22259, 72.6645],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_48bbc645749e430f9711dc21db090d76 = L.popup({"maxWidth": "100%"});

        
            var html_cd367852a1db49c9abdcb29f89698a17 = $(`<div id="html_cd367852a1db49c9abdcb29f89698a17" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Gandhinagar<br><strong>State</strong>: Gujarat<br><strong>Confirmed Cases</strong>: 4<br></div>`)[0];
            popup_48bbc645749e430f9711dc21db090d76.setContent(html_cd367852a1db49c9abdcb29f89698a17);
        

        circle_marker_4006da2bfbed436898f71274f66fcd81.bindPopup(popup_48bbc645749e430f9711dc21db090d76)
        ;

        
    
    
            var circle_marker_8ead44b1a7384a7f8a94f73ce738aefd = L.circleMarker(
                [21.48642, 69.93125],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_a4d692c37c6149f7b0288771be160e50 = L.popup({"maxWidth": "100%"});

        
            var html_ae026726e5064aaf86905abbcfa448a7 = $(`<div id="html_ae026726e5064aaf86905abbcfa448a7" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Kutch<br><strong>State</strong>: Gujarat<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_a4d692c37c6149f7b0288771be160e50.setContent(html_ae026726e5064aaf86905abbcfa448a7);
        

        circle_marker_8ead44b1a7384a7f8a94f73ce738aefd.bindPopup(popup_a4d692c37c6149f7b0288771be160e50)
        ;

        
    
    
            var circle_marker_84687d7906b94570909928739fdf4c6f = L.circleMarker(
                [22.34095, 70.78601],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_f1e9913e772a4aa4a0ffa26a26015a50 = L.popup({"maxWidth": "100%"});

        
            var html_553df2b1f30a4ee085c59b45bb287530 = $(`<div id="html_553df2b1f30a4ee085c59b45bb287530" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Rajkot<br><strong>State</strong>: Gujarat<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_f1e9913e772a4aa4a0ffa26a26015a50.setContent(html_553df2b1f30a4ee085c59b45bb287530);
        

        circle_marker_84687d7906b94570909928739fdf4c6f.bindPopup(popup_f1e9913e772a4aa4a0ffa26a26015a50)
        ;

        
    
    
            var circle_marker_d1154510c3024177ab0bbca4fb7e6fb3 = L.circleMarker(
                [21.41034, 73.29927],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_1ff4f047a59f46dda02bbf17045ba939 = L.popup({"maxWidth": "100%"});

        
            var html_919b7eb14a154f3ca1ddee3687bcdeab = $(`<div id="html_919b7eb14a154f3ca1ddee3687bcdeab" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Surat<br><strong>State</strong>: Gujarat<br><strong>Confirmed Cases</strong>: 4<br></div>`)[0];
            popup_1ff4f047a59f46dda02bbf17045ba939.setContent(html_919b7eb14a154f3ca1ddee3687bcdeab);
        

        circle_marker_d1154510c3024177ab0bbca4fb7e6fb3.bindPopup(popup_1ff4f047a59f46dda02bbf17045ba939)
        ;

        
    
    
            var circle_marker_37568fd024dc4e21910ceb47006d47bc = L.circleMarker(
                [22.31775, 73.36254],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_4ae25fa4e98241d9bf8696e7cd6c2eb9 = L.popup({"maxWidth": "100%"});

        
            var html_831f181050c64543be116f608a10ceaf = $(`<div id="html_831f181050c64543be116f608a10ceaf" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Vadodara<br><strong>State</strong>: Gujarat<br><strong>Confirmed Cases</strong>: 6<br></div>`)[0];
            popup_4ae25fa4e98241d9bf8696e7cd6c2eb9.setContent(html_831f181050c64543be116f608a10ceaf);
        

        circle_marker_37568fd024dc4e21910ceb47006d47bc.bindPopup(popup_4ae25fa4e98241d9bf8696e7cd6c2eb9)
        ;

        
    
    
            var circle_marker_dbafaf2257d64ca887c6a90e3cd3a8e1 = L.circleMarker(
                [28.18325, 77.34851],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_1e37b41b99934694895e63a3e4cf5d65 = L.popup({"maxWidth": "100%"});

        
            var html_18597f6ba95140509906a377c5185fec = $(`<div id="html_18597f6ba95140509906a377c5185fec" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Faridabad<br><strong>State</strong>: Haryana<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_1e37b41b99934694895e63a3e4cf5d65.setContent(html_18597f6ba95140509906a377c5185fec);
        

        circle_marker_dbafaf2257d64ca887c6a90e3cd3a8e1.bindPopup(popup_1e37b41b99934694895e63a3e4cf5d65)
        ;

        
    
    
            var circle_marker_c6f372922f314b938d4d12db7ca70658 = L.circleMarker(
                [28.45219, 77.04632],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 22, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_c922f0839914467c91904e1ad52c69d9 = L.popup({"maxWidth": "100%"});

        
            var html_141bb4be8ae0445480b4d408ae0be12f = $(`<div id="html_141bb4be8ae0445480b4d408ae0be12f" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Gurugram<br><strong>State</strong>: Haryana<br><strong>Confirmed Cases</strong>: 22<br></div>`)[0];
            popup_c922f0839914467c91904e1ad52c69d9.setContent(html_141bb4be8ae0445480b4d408ae0be12f);
        

        circle_marker_c6f372922f314b938d4d12db7ca70658.bindPopup(popup_c922f0839914467c91904e1ad52c69d9)
        ;

        
    
    
            var circle_marker_238d310549614add88c466847ec83177 = L.circleMarker(
                [30.72663, 76.96176],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_5cbaff1ec85f4989ab692363918825aa = L.popup({"maxWidth": "100%"});

        
            var html_b30618108f244a9085aed377da9685a8 = $(`<div id="html_b30618108f244a9085aed377da9685a8" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Panchkula<br><strong>State</strong>: Haryana<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_5cbaff1ec85f4989ab692363918825aa.setContent(html_b30618108f244a9085aed377da9685a8);
        

        circle_marker_238d310549614add88c466847ec83177.bindPopup(popup_5cbaff1ec85f4989ab692363918825aa)
        ;

        
    
    
            var circle_marker_969fbf2bfa3d43abba549d20d8f6e7b7 = L.circleMarker(
                [29.05587, 76.89537],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_3f6eeec6bb394009be0f051787748f11 = L.popup({"maxWidth": "100%"});

        
            var html_8f4c2673ef354b43a8100c53df2236a7 = $(`<div id="html_8f4c2673ef354b43a8100c53df2236a7" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Sonipat<br><strong>State</strong>: Haryana<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_3f6eeec6bb394009be0f051787748f11.setContent(html_8f4c2673ef354b43a8100c53df2236a7);
        

        circle_marker_969fbf2bfa3d43abba549d20d8f6e7b7.bindPopup(popup_3f6eeec6bb394009be0f051787748f11)
        ;

        
    
    
            var circle_marker_27d6404af09f4a02a4c5384b6ac247a7 = L.circleMarker(
                [32.07961, 76.25384],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_e387db1756904031bdd37330df01957d = L.popup({"maxWidth": "100%"});

        
            var html_52842cff69364424bde4a983f5479a4d = $(`<div id="html_52842cff69364424bde4a983f5479a4d" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Kangra<br><strong>State</strong>: Himachal Pradesh<br><strong>Confirmed Cases</strong>: 3<br></div>`)[0];
            popup_e387db1756904031bdd37330df01957d.setContent(html_52842cff69364424bde4a983f5479a4d);
        

        circle_marker_27d6404af09f4a02a4c5384b6ac247a7.bindPopup(popup_e387db1756904031bdd37330df01957d)
        ;

        
    
    
            var circle_marker_c51dcc6b2ee84d4ca7371991d3aeca6c = L.circleMarker(
                [32.74713, 74.87663],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_4de5d93762654311aa3df2cda57ca58c = L.popup({"maxWidth": "100%"});

        
            var html_9184809394de40a9bad2bae59a46442e = $(`<div id="html_9184809394de40a9bad2bae59a46442e" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Jammu<br><strong>State</strong>: J&K<br><strong>Confirmed Cases</strong>: 3<br></div>`)[0];
            popup_4de5d93762654311aa3df2cda57ca58c.setContent(html_9184809394de40a9bad2bae59a46442e);
        

        circle_marker_c51dcc6b2ee84d4ca7371991d3aeca6c.bindPopup(popup_4de5d93762654311aa3df2cda57ca58c)
        ;

        
    
    
            var circle_marker_92a248db24864e289eb5c581f58330fb = L.circleMarker(
                [34.10259, 74.83777],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_ffda5a08a9054d0f8a05d4e69187f5f7 = L.popup({"maxWidth": "100%"});

        
            var html_0dfce5ba954d449696279ea60e1835cf = $(`<div id="html_0dfce5ba954d449696279ea60e1835cf" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Srinagar<br><strong>State</strong>: J&K<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_ffda5a08a9054d0f8a05d4e69187f5f7.setContent(html_0dfce5ba954d449696279ea60e1835cf);
        

        circle_marker_92a248db24864e289eb5c581f58330fb.bindPopup(popup_ffda5a08a9054d0f8a05d4e69187f5f7)
        ;

        
    
    
            var circle_marker_addcb92b775249258893e6d0887e155a = L.circleMarker(
                [12.8228, 77.51061],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 18, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_95f5c483d4714c268c93b1a83d5af28e = L.popup({"maxWidth": "100%"});

        
            var html_1d727646a8484afd9e7c2f8f0a2f02a9 = $(`<div id="html_1d727646a8484afd9e7c2f8f0a2f02a9" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Bengaluru urban<br><strong>State</strong>: Karnataka<br><strong>Confirmed Cases</strong>: 18<br></div>`)[0];
            popup_95f5c483d4714c268c93b1a83d5af28e.setContent(html_1d727646a8484afd9e7c2f8f0a2f02a9);
        

        circle_marker_addcb92b775249258893e6d0887e155a.bindPopup(popup_95f5c483d4714c268c93b1a83d5af28e)
        ;

        
    
    
            var circle_marker_acd40397913c4593b977e3038124c5c9 = L.circleMarker(
                [13.5894, 77.77999],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_ba66a33fc21d483f80a8a2ceaee53ea5 = L.popup({"maxWidth": "100%"});

        
            var html_82fd3aceb92a48dc9b17cbdb0847449b = $(`<div id="html_82fd3aceb92a48dc9b17cbdb0847449b" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Chikkaballapura<br><strong>State</strong>: Karnataka<br><strong>Confirmed Cases</strong>: 3<br></div>`)[0];
            popup_ba66a33fc21d483f80a8a2ceaee53ea5.setContent(html_82fd3aceb92a48dc9b17cbdb0847449b);
        

        circle_marker_acd40397913c4593b977e3038124c5c9.bindPopup(popup_ba66a33fc21d483f80a8a2ceaee53ea5)
        ;

        
    
    
            var circle_marker_d52aa24395664bef84c03587b506c9e0 = L.circleMarker(
                [12.81141, 75.1008],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_41fe88a55aef4273b56e7ec67620d31d = L.popup({"maxWidth": "100%"});

        
            var html_ee308962cb02469fb976615dfdd65efd = $(`<div id="html_ee308962cb02469fb976615dfdd65efd" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Dakshin kannada<br><strong>State</strong>: Karnataka<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_41fe88a55aef4273b56e7ec67620d31d.setContent(html_ee308962cb02469fb976615dfdd65efd);
        

        circle_marker_d52aa24395664bef84c03587b506c9e0.bindPopup(popup_41fe88a55aef4273b56e7ec67620d31d)
        ;

        
    
    
            var circle_marker_20166aead78e4941b61f552428e116ca = L.circleMarker(
                [15.37259, 75.13728],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_88317defaa8d49d9bb1c630b1cfb3a8f = L.popup({"maxWidth": "100%"});

        
            var html_b184a82816544d81892796d559b7fc26 = $(`<div id="html_b184a82816544d81892796d559b7fc26" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Dharwad<br><strong>State</strong>: Karnataka<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_88317defaa8d49d9bb1c630b1cfb3a8f.setContent(html_b184a82816544d81892796d559b7fc26);
        

        circle_marker_20166aead78e4941b61f552428e116ca.bindPopup(popup_88317defaa8d49d9bb1c630b1cfb3a8f)
        ;

        
    
    
            var circle_marker_4db0f61e5fe14bfb8805627aa769adbc = L.circleMarker(
                [14.54387, 76.23089],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_18096ef5ae17477da1343309720daf1d = L.popup({"maxWidth": "100%"});

        
            var html_918f9e7f9b9f46d3b24ac9596d0ea391 = $(`<div id="html_918f9e7f9b9f46d3b24ac9596d0ea391" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Kalaburgi<br><strong>State</strong>: Karnataka<br><strong>Confirmed Cases</strong>: 3<br></div>`)[0];
            popup_18096ef5ae17477da1343309720daf1d.setContent(html_918f9e7f9b9f46d3b24ac9596d0ea391);
        

        circle_marker_4db0f61e5fe14bfb8805627aa769adbc.bindPopup(popup_18096ef5ae17477da1343309720daf1d)
        ;

        
    
    
            var circle_marker_0dd7e6f08c0e4a0bb0b5dee5f28a0b37 = L.circleMarker(
                [12.38117, 75.66772],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_35eb6910794e407db04167284aaa5346 = L.popup({"maxWidth": "100%"});

        
            var html_f2e234ff30fc4176839f06d110250a1d = $(`<div id="html_f2e234ff30fc4176839f06d110250a1d" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Kodagu<br><strong>State</strong>: Karnataka<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_35eb6910794e407db04167284aaa5346.setContent(html_f2e234ff30fc4176839f06d110250a1d);
        

        circle_marker_0dd7e6f08c0e4a0bb0b5dee5f28a0b37.bindPopup(popup_35eb6910794e407db04167284aaa5346)
        ;

        
    
    
            var circle_marker_ccb896a7ba744bcd88c64ff8c1dfcc96 = L.circleMarker(
                [12.31301, 76.64119],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_f0d2385e31a94c8fabb260d49b30d80c = L.popup({"maxWidth": "100%"});

        
            var html_5692527b80464d94bde928c034552a1b = $(`<div id="html_5692527b80464d94bde928c034552a1b" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Mysore<br><strong>State</strong>: Karnataka<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_f0d2385e31a94c8fabb260d49b30d80c.setContent(html_5692527b80464d94bde928c034552a1b);
        

        circle_marker_ccb896a7ba744bcd88c64ff8c1dfcc96.bindPopup(popup_f0d2385e31a94c8fabb260d49b30d80c)
        ;

        
    
    
            var circle_marker_8b21a490ca144694a4ff1757707e2531 = L.circleMarker(
                [14.67264, 74.47292],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_53402088dc3342d6b01bfd0cd7f2a4e1 = L.popup({"maxWidth": "100%"});

        
            var html_4347353f52004cdf80a1fbb73a16b39b = $(`<div id="html_4347353f52004cdf80a1fbb73a16b39b" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Uttar kannada<br><strong>State</strong>: Karnataka<br><strong>Confirmed Cases</strong>: 2<br></div>`)[0];
            popup_53402088dc3342d6b01bfd0cd7f2a4e1.setContent(html_4347353f52004cdf80a1fbb73a16b39b);
        

        circle_marker_8b21a490ca144694a4ff1757707e2531.bindPopup(popup_53402088dc3342d6b01bfd0cd7f2a4e1)
        ;

        
    
    
            var circle_marker_6f2405c317174d7394e5f507788a5513 = L.circleMarker(
                [9.46214, 76.28424],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_ab765e01e89f47e598b4e4d2f8d42761 = L.popup({"maxWidth": "100%"});

        
            var html_d936c7dd4b2a457f9e9a00038acfa748 = $(`<div id="html_d936c7dd4b2a457f9e9a00038acfa748" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Alappuzha<br><strong>State</strong>: Kerala<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_ab765e01e89f47e598b4e4d2f8d42761.setContent(html_d936c7dd4b2a457f9e9a00038acfa748);
        

        circle_marker_6f2405c317174d7394e5f507788a5513.bindPopup(popup_ab765e01e89f47e598b4e4d2f8d42761)
        ;

        
    
    
            var circle_marker_263bda77c25140bca4dd7a4a09734183 = L.circleMarker(
                [9.9871, 76.3431],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 16, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_30a4b3db16dc43c5b80adf81e3079f09 = L.popup({"maxWidth": "100%"});

        
            var html_17d8d72d726440558121b5d52336bcff = $(`<div id="html_17d8d72d726440558121b5d52336bcff" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Ernakulam<br><strong>State</strong>: Kerala<br><strong>Confirmed Cases</strong>: 16<br></div>`)[0];
            popup_30a4b3db16dc43c5b80adf81e3079f09.setContent(html_17d8d72d726440558121b5d52336bcff);
        

        circle_marker_263bda77c25140bca4dd7a4a09734183.bindPopup(popup_30a4b3db16dc43c5b80adf81e3079f09)
        ;

        
    
    
            var circle_marker_ec158152ebed44ef8e288404e3c53cdf = L.circleMarker(
                [9.8139, 77.00703],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_85d84ba9ba36471a877c7d8a1681ef64 = L.popup({"maxWidth": "100%"});

        
            var html_bc964ef147fd48178970fc97676d45eb = $(`<div id="html_bc964ef147fd48178970fc97676d45eb" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Idukki<br><strong>State</strong>: Kerala<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_85d84ba9ba36471a877c7d8a1681ef64.setContent(html_bc964ef147fd48178970fc97676d45eb);
        

        circle_marker_ec158152ebed44ef8e288404e3c53cdf.bindPopup(popup_85d84ba9ba36471a877c7d8a1681ef64)
        ;

        
    
    
            var circle_marker_0298ee06b6b146ab87174c722c1b1866 = L.circleMarker(
                [11.9093, 75.46016],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_b71b46aefd36408285d32c136982f309 = L.popup({"maxWidth": "100%"});

        
            var html_6b4a834ea457447abc52d93c0c8b749f = $(`<div id="html_6b4a834ea457447abc52d93c0c8b749f" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Kannur<br><strong>State</strong>: Kerala<br><strong>Confirmed Cases</strong>: 13<br></div>`)[0];
            popup_b71b46aefd36408285d32c136982f309.setContent(html_6b4a834ea457447abc52d93c0c8b749f);
        

        circle_marker_0298ee06b6b146ab87174c722c1b1866.bindPopup(popup_b71b46aefd36408285d32c136982f309)
        ;

        
    
    
            var circle_marker_886587fa1d4f4099adb55961a5636521 = L.circleMarker(
                [65.38071, 26.9073],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 39, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_7734db601785490b8b741c9d6465f551 = L.popup({"maxWidth": "100%"});

        
            var html_0057029bf2ed4605aeaf253f748c82dd = $(`<div id="html_0057029bf2ed4605aeaf253f748c82dd" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Kasargod<br><strong>State</strong>: Kerala<br><strong>Confirmed Cases</strong>: 39<br></div>`)[0];
            popup_7734db601785490b8b741c9d6465f551.setContent(html_0057029bf2ed4605aeaf253f748c82dd);
        

        circle_marker_886587fa1d4f4099adb55961a5636521.bindPopup(popup_7734db601785490b8b741c9d6465f551)
        ;

        
    
    
            var circle_marker_34895c8cf7894bc5a8d9ccee5513f776 = L.circleMarker(
                [9.63726, 76.60583],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_541a4dd5cf3d4a3aa203ce7c5baa40c6 = L.popup({"maxWidth": "100%"});

        
            var html_17ade83bdd654488bd42741b22a78cee = $(`<div id="html_17ade83bdd654488bd42741b22a78cee" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Kottayam<br><strong>State</strong>: Kerala<br><strong>Confirmed Cases</strong>: 2<br></div>`)[0];
            popup_541a4dd5cf3d4a3aa203ce7c5baa40c6.setContent(html_17ade83bdd654488bd42741b22a78cee);
        

        circle_marker_34895c8cf7894bc5a8d9ccee5513f776.bindPopup(popup_541a4dd5cf3d4a3aa203ce7c5baa40c6)
        ;

        
    
    
            var circle_marker_6ada365645e540b389f4615cd830bed8 = L.circleMarker(
                [11.43062, 75.72201],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_4a50513cacaf477993791a0dcca99014 = L.popup({"maxWidth": "100%"});

        
            var html_f375d07a2e3c4886bbf6690c656d7f82 = $(`<div id="html_f375d07a2e3c4886bbf6690c656d7f82" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Kozhikode<br><strong>State</strong>: Kerala<br><strong>Confirmed Cases</strong>: 2<br></div>`)[0];
            popup_4a50513cacaf477993791a0dcca99014.setContent(html_f375d07a2e3c4886bbf6690c656d7f82);
        

        circle_marker_6ada365645e540b389f4615cd830bed8.bindPopup(popup_4a50513cacaf477993791a0dcca99014)
        ;

        
    
    
            var circle_marker_812fbab146f64628a878262afd97914e = L.circleMarker(
                [11.95, 78.21931],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_185a8ca5253845039aa7ab5d104d091f = L.popup({"maxWidth": "100%"});

        
            var html_688f35679ad843f88765973dc2f995fc = $(`<div id="html_688f35679ad843f88765973dc2f995fc" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Mallapuram<br><strong>State</strong>: Kerala<br><strong>Confirmed Cases</strong>: 4<br></div>`)[0];
            popup_185a8ca5253845039aa7ab5d104d091f.setContent(html_688f35679ad843f88765973dc2f995fc);
        

        circle_marker_812fbab146f64628a878262afd97914e.bindPopup(popup_185a8ca5253845039aa7ab5d104d091f)
        ;

        
    
    
            var circle_marker_32c84b3067eb49cda4bdb612359fbb90 = L.circleMarker(
                [9.26553, 76.78715],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 10, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_18b6f57d7d6f4593947a0aa26bf1a4f8 = L.popup({"maxWidth": "100%"});

        
            var html_f9d49ee2f668482fbeaf6f3179a06387 = $(`<div id="html_f9d49ee2f668482fbeaf6f3179a06387" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Pathanamthitta<br><strong>State</strong>: Kerala<br><strong>Confirmed Cases</strong>: 10<br></div>`)[0];
            popup_18b6f57d7d6f4593947a0aa26bf1a4f8.setContent(html_f9d49ee2f668482fbeaf6f3179a06387);
        

        circle_marker_32c84b3067eb49cda4bdb612359fbb90.bindPopup(popup_18b6f57d7d6f4593947a0aa26bf1a4f8)
        ;

        
    
    
            var circle_marker_a3acc58858a24abba71ab68b6943214c = L.circleMarker(
                [65.38071, 26.9073],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_2de62dc68e5d44e5a1602fd7007fbe92 = L.popup({"maxWidth": "100%"});

        
            var html_78b28925374c45e0827e771b8a2e1f51 = $(`<div id="html_78b28925374c45e0827e771b8a2e1f51" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Thiruvanthpuram<br><strong>State</strong>: Kerala<br><strong>Confirmed Cases</strong>: 4<br></div>`)[0];
            popup_2de62dc68e5d44e5a1602fd7007fbe92.setContent(html_78b28925374c45e0827e771b8a2e1f51);
        

        circle_marker_a3acc58858a24abba71ab68b6943214c.bindPopup(popup_2de62dc68e5d44e5a1602fd7007fbe92)
        ;

        
    
    
            var circle_marker_b20f80f3cf704b7181c31ea2242c9c46 = L.circleMarker(
                [10.401, 76.1742],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_b96439a1b8124258847eb10d26ebc586 = L.popup({"maxWidth": "100%"});

        
            var html_da7528d049264e68869908c2b4143627 = $(`<div id="html_da7528d049264e68869908c2b4143627" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Thrissur<br><strong>State</strong>: Kerala<br><strong>Confirmed Cases</strong>: 3<br></div>`)[0];
            popup_b96439a1b8124258847eb10d26ebc586.setContent(html_da7528d049264e68869908c2b4143627);
        

        circle_marker_b20f80f3cf704b7181c31ea2242c9c46.bindPopup(popup_b96439a1b8124258847eb10d26ebc586)
        ;

        
    
    
            var circle_marker_ed591ce33d574b548da1fe114f29ff32 = L.circleMarker(
                [34.55682, 76.16182],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_4d5829cddc044d6d8e7640432acf2bcb = L.popup({"maxWidth": "100%"});

        
            var html_6aaff0138cdf40c08ae2b3297969f785 = $(`<div id="html_6aaff0138cdf40c08ae2b3297969f785" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Kargil<br><strong>State</strong>: Ladakh<br><strong>Confirmed Cases</strong>: 2<br></div>`)[0];
            popup_4d5829cddc044d6d8e7640432acf2bcb.setContent(html_6aaff0138cdf40c08ae2b3297969f785);
        

        circle_marker_ed591ce33d574b548da1fe114f29ff32.bindPopup(popup_4d5829cddc044d6d8e7640432acf2bcb)
        ;

        
    
    
            var circle_marker_83ef47bcce474365a43bae0122af06ae = L.circleMarker(
                [34.165, 77.584],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 11, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_d567fda904614d9d9fc1e85d05885ac7 = L.popup({"maxWidth": "100%"});

        
            var html_1fed0846a4d248e1b49772150b663d70 = $(`<div id="html_1fed0846a4d248e1b49772150b663d70" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Leh<br><strong>State</strong>: Ladakh<br><strong>Confirmed Cases</strong>: 11<br></div>`)[0];
            popup_d567fda904614d9d9fc1e85d05885ac7.setContent(html_1fed0846a4d248e1b49772150b663d70);
        

        circle_marker_83ef47bcce474365a43bae0122af06ae.bindPopup(popup_d567fda904614d9d9fc1e85d05885ac7)
        ;

        
    
    
            var circle_marker_66c6563e5e6e40a881bd2afe18f33ae4 = L.circleMarker(
                [23.4979, 77.39304],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_ddd92eda2de1438b800caacf3d1e66ba = L.popup({"maxWidth": "100%"});

        
            var html_8d12481d552544b59d2a1b62caa3b98a = $(`<div id="html_8d12481d552544b59d2a1b62caa3b98a" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Bhopal<br><strong>State</strong>: Madhya Pradesh<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_ddd92eda2de1438b800caacf3d1e66ba.setContent(html_8d12481d552544b59d2a1b62caa3b98a);
        

        circle_marker_66c6563e5e6e40a881bd2afe18f33ae4.bindPopup(popup_ddd92eda2de1438b800caacf3d1e66ba)
        ;

        
    
    
            var circle_marker_13acde9b45a347c3b17a793b90de090c = L.circleMarker(
                [23.32886, 80.10729],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_8dadef674be24c01919eda8d8cc7f0e9 = L.popup({"maxWidth": "100%"});

        
            var html_bdb093e477494f06b8a919b0dd49eb1e = $(`<div id="html_bdb093e477494f06b8a919b0dd49eb1e" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Jabalpur<br><strong>State</strong>: Madhya Pradesh<br><strong>Confirmed Cases</strong>: 6<br></div>`)[0];
            popup_8dadef674be24c01919eda8d8cc7f0e9.setContent(html_bdb093e477494f06b8a919b0dd49eb1e);
        

        circle_marker_13acde9b45a347c3b17a793b90de090c.bindPopup(popup_8dadef674be24c01919eda8d8cc7f0e9)
        ;

        
    
    
            var circle_marker_c67ce20226ee45038003ca2f70d1b809 = L.circleMarker(
                [19.15733, 74.86029],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_b130dce2ce2345008ba19f564eb76c13 = L.popup({"maxWidth": "100%"});

        
            var html_7d219ef4dd32410f80afa84688c86277 = $(`<div id="html_7d219ef4dd32410f80afa84688c86277" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Ahmednagar<br><strong>State</strong>: Maharashtra<br><strong>Confirmed Cases</strong>: 2<br></div>`)[0];
            popup_b130dce2ce2345008ba19f564eb76c13.setContent(html_7d219ef4dd32410f80afa84688c86277);
        

        circle_marker_c67ce20226ee45038003ca2f70d1b809.bindPopup(popup_b130dce2ce2345008ba19f564eb76c13)
        ;

        
    
    
            var circle_marker_6fa7e769eb37451696f3c306625fda5e = L.circleMarker(
                [20.03284, 75.15895],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_a3872e15ad8346d5a764b020caf6857e = L.popup({"maxWidth": "100%"});

        
            var html_88a07872bd054337adb2950663f27454 = $(`<div id="html_88a07872bd054337adb2950663f27454" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Aurangabad<br><strong>State</strong>: Maharashtra<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_a3872e15ad8346d5a764b020caf6857e.setContent(html_88a07872bd054337adb2950663f27454);
        

        circle_marker_6fa7e769eb37451696f3c306625fda5e.bindPopup(popup_a3872e15ad8346d5a764b020caf6857e)
        ;

        
    
    
            var circle_marker_00ab4326839544ddb24c22becdb4845c = L.circleMarker(
                [18.95238, 72.83271],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 25, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_c93b48561f3746e7a22ec491567cb18d = L.popup({"maxWidth": "100%"});

        
            var html_718d39d981d54c3db19877a84eb91892 = $(`<div id="html_718d39d981d54c3db19877a84eb91892" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Mumbai<br><strong>State</strong>: Maharashtra<br><strong>Confirmed Cases</strong>: 25<br></div>`)[0];
            popup_c93b48561f3746e7a22ec491567cb18d.setContent(html_718d39d981d54c3db19877a84eb91892);
        

        circle_marker_00ab4326839544ddb24c22becdb4845c.bindPopup(popup_c93b48561f3746e7a22ec491567cb18d)
        ;

        
    
    
            var circle_marker_327677f240704be984e84324667ca7aa = L.circleMarker(
                [18.95238, 72.83271],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_e7d7ebb9cd6f45ffae6fada4ada51733 = L.popup({"maxWidth": "100%"});

        
            var html_383b3205a1794288b1778f868ac08302 = $(`<div id="html_383b3205a1794288b1778f868ac08302" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Mumbai suburb<br><strong>State</strong>: Maharashtra<br><strong>Confirmed Cases</strong>: 5<br></div>`)[0];
            popup_e7d7ebb9cd6f45ffae6fada4ada51733.setContent(html_383b3205a1794288b1778f868ac08302);
        

        circle_marker_327677f240704be984e84324667ca7aa.bindPopup(popup_e7d7ebb9cd6f45ffae6fada4ada51733)
        ;

        
    
    
            var circle_marker_38b316b4f84c49068332e10161228dc1 = L.circleMarker(
                [21.1501, 79.0127],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_ab35bf1ac3914f50af6e2e6016d4ed73 = L.popup({"maxWidth": "100%"});

        
            var html_ed98711b1a2a4b06a81d405df8b8642a = $(`<div id="html_ed98711b1a2a4b06a81d405df8b8642a" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Nagpur<br><strong>State</strong>: Maharashtra<br><strong>Confirmed Cases</strong>: 4<br></div>`)[0];
            popup_ab35bf1ac3914f50af6e2e6016d4ed73.setContent(html_ed98711b1a2a4b06a81d405df8b8642a);
        

        circle_marker_38b316b4f84c49068332e10161228dc1.bindPopup(popup_ab35bf1ac3914f50af6e2e6016d4ed73)
        ;

        
    
    
            var circle_marker_234947547ce94f389e931e138d768223 = L.circleMarker(
                [18.64396, 73.93257],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 27, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_16cff1a928ba4c3f926f52abaef13614 = L.popup({"maxWidth": "100%"});

        
            var html_e1d6877f2efc47d4a2e1c9a62f3371c1 = $(`<div id="html_e1d6877f2efc47d4a2e1c9a62f3371c1" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Pune<br><strong>State</strong>: Maharashtra<br><strong>Confirmed Cases</strong>: 27<br></div>`)[0];
            popup_16cff1a928ba4c3f926f52abaef13614.setContent(html_e1d6877f2efc47d4a2e1c9a62f3371c1);
        

        circle_marker_234947547ce94f389e931e138d768223.bindPopup(popup_16cff1a928ba4c3f926f52abaef13614)
        ;

        
    
    
            var circle_marker_5a0a03f648234df58a38d2738dba7755 = L.circleMarker(
                [18.98503, 73.46749],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_1ff0478495e540be98634f20c2356280 = L.popup({"maxWidth": "100%"});

        
            var html_12c1112558a042ebb5fdbc8c37223718 = $(`<div id="html_12c1112558a042ebb5fdbc8c37223718" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Raigad<br><strong>State</strong>: Maharashtra<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_1ff0478495e540be98634f20c2356280.setContent(html_12c1112558a042ebb5fdbc8c37223718);
        

        circle_marker_5a0a03f648234df58a38d2738dba7755.bindPopup(popup_1ff0478495e540be98634f20c2356280)
        ;

        
    
    
            var circle_marker_06a0601949e24e0e9c5d7e929b9f740a = L.circleMarker(
                [17.27448, 73.27618],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_b48aac109dfd447599323ea1f70c6552 = L.popup({"maxWidth": "100%"});

        
            var html_5dfd7a6498c344c9baf4d3ec742c1e18 = $(`<div id="html_5dfd7a6498c344c9baf4d3ec742c1e18" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Ratnagiri<br><strong>State</strong>: Maharashtra<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_b48aac109dfd447599323ea1f70c6552.setContent(html_5dfd7a6498c344c9baf4d3ec742c1e18);
        

        circle_marker_06a0601949e24e0e9c5d7e929b9f740a.bindPopup(popup_b48aac109dfd447599323ea1f70c6552)
        ;

        
    
    
            var circle_marker_5126539098bd488386ec884d2a841246 = L.circleMarker(
                [19.23137, 72.98281],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_1ec0906ef09240058077f746c81cae1d = L.popup({"maxWidth": "100%"});

        
            var html_a2e262efe35a4655a6f6bed9556618ed = $(`<div id="html_a2e262efe35a4655a6f6bed9556618ed" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Thane<br><strong>State</strong>: Maharashtra<br><strong>Confirmed Cases</strong>: 4<br></div>`)[0];
            popup_1ec0906ef09240058077f746c81cae1d.setContent(html_a2e262efe35a4655a6f6bed9556618ed);
        

        circle_marker_5126539098bd488386ec884d2a841246.bindPopup(popup_1ec0906ef09240058077f746c81cae1d)
        ;

        
    
    
            var circle_marker_5f236da448ff4649878a106d66453006 = L.circleMarker(
                [20.06361, 78.35058],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_2a89c6b6d2784194baa0c9d128cbd859 = L.popup({"maxWidth": "100%"});

        
            var html_b9aeb13c081b4579a87533c7552f4bc1 = $(`<div id="html_b9aeb13c081b4579a87533c7552f4bc1" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Yavatmal<br><strong>State</strong>: Maharashtra<br><strong>Confirmed Cases</strong>: 4<br></div>`)[0];
            popup_2a89c6b6d2784194baa0c9d128cbd859.setContent(html_b9aeb13c081b4579a87533c7552f4bc1);
        

        circle_marker_5f236da448ff4649878a106d66453006.bindPopup(popup_2a89c6b6d2784194baa0c9d128cbd859)
        ;

        
    
    
            var circle_marker_92171397349842c3bffee6570883f924 = L.circleMarker(
                [20.04287, 85.49866],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_1d8a9c0844694ecca146530ad34e9728 = L.popup({"maxWidth": "100%"});

        
            var html_bb90f8f2208f487eb0b05b76a733c8c0 = $(`<div id="html_bb90f8f2208f487eb0b05b76a733c8c0" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Khurda<br><strong>State</strong>: Odisha<br><strong>Confirmed Cases</strong>: 2<br></div>`)[0];
            popup_1d8a9c0844694ecca146530ad34e9728.setContent(html_bb90f8f2208f487eb0b05b76a733c8c0);
        

        circle_marker_92171397349842c3bffee6570883f924.bindPopup(popup_1d8a9c0844694ecca146530ad34e9728)
        ;

        
    
    
            var circle_marker_ed85a27d39224ddd8ccc808b81fa1390 = L.circleMarker(
                [11.69556, 75.53827],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_3afb266ab4184387a3f7adc413e61397 = L.popup({"maxWidth": "100%"});

        
            var html_8e286020fb194bb98e7e68a0d316a923 = $(`<div id="html_8e286020fb194bb98e7e68a0d316a923" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Mahe<br><strong>State</strong>: Puducherry<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_3afb266ab4184387a3f7adc413e61397.setContent(html_8e286020fb194bb98e7e68a0d316a923);
        

        circle_marker_ed85a27d39224ddd8ccc808b81fa1390.bindPopup(popup_3afb266ab4184387a3f7adc413e61397)
        ;

        
    
    
            var circle_marker_2d9005da6c4941fd8623260c2cacf5d9 = L.circleMarker(
                [31.56818, 74.98127],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_3cdfc6ae1c16489e82245a02cda22796 = L.popup({"maxWidth": "100%"});

        
            var html_716dec6dfa02452e87bac596f42f14d9 = $(`<div id="html_716dec6dfa02452e87bac596f42f14d9" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Amritsar<br><strong>State</strong>: Punjab<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_3cdfc6ae1c16489e82245a02cda22796.setContent(html_716dec6dfa02452e87bac596f42f14d9);
        

        circle_marker_2d9005da6c4941fd8623260c2cacf5d9.bindPopup(popup_3cdfc6ae1c16489e82245a02cda22796)
        ;

        
    
    
            var circle_marker_0aedb0d2502946f385b1f31bb8c4193a = L.circleMarker(
                [31.6062, 75.84975],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_2038337949d94791b8ce21722ec1155e = L.popup({"maxWidth": "100%"});

        
            var html_ecff604a46304414b303eb446813fee4 = $(`<div id="html_ecff604a46304414b303eb446813fee4" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Hoshiarpur<br><strong>State</strong>: Punjab<br><strong>Confirmed Cases</strong>: 2<br></div>`)[0];
            popup_2038337949d94791b8ce21722ec1155e.setContent(html_ecff604a46304414b303eb446813fee4);
        

        circle_marker_0aedb0d2502946f385b1f31bb8c4193a.bindPopup(popup_2038337949d94791b8ce21722ec1155e)
        ;

        
    
    
            var circle_marker_ca478e81f3af4283b5761b336f6a261d = L.circleMarker(
                [32.3265, 73.78252],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_7b41f09db9df41bab8968f27a17d0eaa = L.popup({"maxWidth": "100%"});

        
            var html_ab55da86751e4623a8e627a72c4dc7d0 = $(`<div id="html_ab55da86751e4623a8e627a72c4dc7d0" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Sas nagar<br><strong>State</strong>: Punjab<br><strong>Confirmed Cases</strong>: 4<br></div>`)[0];
            popup_7b41f09db9df41bab8968f27a17d0eaa.setContent(html_ab55da86751e4623a8e627a72c4dc7d0);
        

        circle_marker_ca478e81f3af4283b5761b336f6a261d.bindPopup(popup_7b41f09db9df41bab8968f27a17d0eaa)
        ;

        
    
    
            var circle_marker_931f452df84d482e8e6207a34006e446 = L.circleMarker(
                [30.60981, 76.6823],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 14, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_0c8ed57549e84d51b8386142fbf82171 = L.popup({"maxWidth": "100%"});

        
            var html_c22ba94ab0ec4df2a1080951b6559dfc = $(`<div id="html_c22ba94ab0ec4df2a1080951b6559dfc" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Sbs nagar<br><strong>State</strong>: Punjab<br><strong>Confirmed Cases</strong>: 14<br></div>`)[0];
            popup_0c8ed57549e84d51b8386142fbf82171.setContent(html_c22ba94ab0ec4df2a1080951b6559dfc);
        

        circle_marker_931f452df84d482e8e6207a34006e446.bindPopup(popup_0c8ed57549e84d51b8386142fbf82171)
        ;

        
    
    
            var circle_marker_b05d117dfaa4427dad7003c0791398eb = L.circleMarker(
                [25.49157, 74.7134],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 13, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_981e4a7ac6e84353be21b6562a49f683 = L.popup({"maxWidth": "100%"});

        
            var html_4172f408f94a4a329cf97444de728dcc = $(`<div id="html_4172f408f94a4a329cf97444de728dcc" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Bhilwara<br><strong>State</strong>: Rajasthan<br><strong>Confirmed Cases</strong>: 13<br></div>`)[0];
            popup_981e4a7ac6e84353be21b6562a49f683.setContent(html_4172f408f94a4a329cf97444de728dcc);
        

        circle_marker_b05d117dfaa4427dad7003c0791398eb.bindPopup(popup_981e4a7ac6e84353be21b6562a49f683)
        ;

        
    
    
            var circle_marker_3eee3c9c8e0642a18c0f4c67a7d40a26 = L.circleMarker(
                [27.15609, 75.74761],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_9d45d204a9d34141860126fd4e9a2805 = L.popup({"maxWidth": "100%"});

        
            var html_ccd302c35cd84414a567bba24d65c570 = $(`<div id="html_ccd302c35cd84414a567bba24d65c570" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Jaipur<br><strong>State</strong>: Rajasthan<br><strong>Confirmed Cases</strong>: 8<br></div>`)[0];
            popup_9d45d204a9d34141860126fd4e9a2805.setContent(html_ccd302c35cd84414a567bba24d65c570);
        

        circle_marker_3eee3c9c8e0642a18c0f4c67a7d40a26.bindPopup(popup_9d45d204a9d34141860126fd4e9a2805)
        ;

        
    
    
            var circle_marker_959ec990db5c4eecba2815c2652491a5 = L.circleMarker(
                [28.1256, 75.398],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_b4281ba24d3b4dca92b63552edd817be = L.popup({"maxWidth": "100%"});

        
            var html_dd4977412a004ed099b00764056dcd8f = $(`<div id="html_dd4977412a004ed099b00764056dcd8f" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Jhunjhunu<br><strong>State</strong>: Rajasthan<br><strong>Confirmed Cases</strong>: 4<br></div>`)[0];
            popup_b4281ba24d3b4dca92b63552edd817be.setContent(html_dd4977412a004ed099b00764056dcd8f);
        

        circle_marker_959ec990db5c4eecba2815c2652491a5.bindPopup(popup_b4281ba24d3b4dca92b63552edd817be)
        ;

        
    
    
            var circle_marker_661ff2c1eb7d4c238bc829947baadec3 = L.circleMarker(
                [26.22928, 72.99845],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_7175eafe85d04790941d781c2532988b = L.popup({"maxWidth": "100%"});

        
            var html_b23193e016aa4c348a0180f05008b6d3 = $(`<div id="html_b23193e016aa4c348a0180f05008b6d3" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Jodhpur<br><strong>State</strong>: Rajasthan<br><strong>Confirmed Cases</strong>: 3<br></div>`)[0];
            popup_7175eafe85d04790941d781c2532988b.setContent(html_b23193e016aa4c348a0180f05008b6d3);
        

        circle_marker_661ff2c1eb7d4c238bc829947baadec3.bindPopup(popup_7175eafe85d04790941d781c2532988b)
        ;

        
    
    
            var circle_marker_a67dbf5080b14c379f5515d8f24e4b03 = L.circleMarker(
                [25.61489, 73.41513],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_02b06b5e2f4146bfab8d19d0443bc3f0 = L.popup({"maxWidth": "100%"});

        
            var html_de19a92c168143d990e44582d941a6d2 = $(`<div id="html_de19a92c168143d990e44582d941a6d2" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Pali<br><strong>State</strong>: Rajasthan<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_02b06b5e2f4146bfab8d19d0443bc3f0.setContent(html_de19a92c168143d990e44582d941a6d2);
        

        circle_marker_a67dbf5080b14c379f5515d8f24e4b03.bindPopup(popup_02b06b5e2f4146bfab8d19d0443bc3f0)
        ;

        
    
    
            var circle_marker_a527a90696cc4b448e31cd894cf9ae8e = L.circleMarker(
                [25.8951, 81.9424],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_8d7fd7be8a1e4cb599abfdbbb812784c = L.popup({"maxWidth": "100%"});

        
            var html_d4c83be69bb1458faf1ca9ba8eec358d = $(`<div id="html_d4c83be69bb1458faf1ca9ba8eec358d" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Pratapgarh<br><strong>State</strong>: Rajasthan<br><strong>Confirmed Cases</strong>: 2<br></div>`)[0];
            popup_8d7fd7be8a1e4cb599abfdbbb812784c.setContent(html_d4c83be69bb1458faf1ca9ba8eec358d);
        

        circle_marker_a527a90696cc4b448e31cd894cf9ae8e.bindPopup(popup_8d7fd7be8a1e4cb599abfdbbb812784c)
        ;

        
    
    
            var circle_marker_5afb5a584d0748feb206cc6695aa183a = L.circleMarker(
                [27.66409, 75.02408],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_478f77fca6d741229b9ffe75ad3981a4 = L.popup({"maxWidth": "100%"});

        
            var html_dd1f21af3e6a4f2db0184dd7a22177e5 = $(`<div id="html_dd1f21af3e6a4f2db0184dd7a22177e5" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Sikar<br><strong>State</strong>: Rajasthan<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_478f77fca6d741229b9ffe75ad3981a4.setContent(html_dd1f21af3e6a4f2db0184dd7a22177e5);
        

        circle_marker_5afb5a584d0748feb206cc6695aa183a.bindPopup(popup_478f77fca6d741229b9ffe75ad3981a4)
        ;

        
    
    
            var circle_marker_2c595b396ab444dcbd75b5e15c816d9a = L.circleMarker(
                [12.97611, 80.22678],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_f1bd3866d6764f449ef09cdfa2f6d7ac = L.popup({"maxWidth": "100%"});

        
            var html_d928fb0e757149478fc34c9e758fb2a1 = $(`<div id="html_d928fb0e757149478fc34c9e758fb2a1" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Chennai<br><strong>State</strong>: Tamil Nadu<br><strong>Confirmed Cases</strong>: 5<br></div>`)[0];
            popup_f1bd3866d6764f449ef09cdfa2f6d7ac.setContent(html_d928fb0e757149478fc34c9e758fb2a1);
        

        circle_marker_2c595b396ab444dcbd75b5e15c816d9a.bindPopup(popup_f1bd3866d6764f449ef09cdfa2f6d7ac)
        ;

        
    
    
            var circle_marker_be6091909abf41dba2743dacda81fb8d = L.circleMarker(
                [10.88184, 78.65384],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_6ca678b241f14296be4c591dc8ef54a0 = L.popup({"maxWidth": "100%"});

        
            var html_d255206fc6f642cd92a1025366de22a9 = $(`<div id="html_d255206fc6f642cd92a1025366de22a9" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Coimbatoor<br><strong>State</strong>: Tamil Nadu<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_6ca678b241f14296be4c591dc8ef54a0.setContent(html_d255206fc6f642cd92a1025366de22a9);
        

        circle_marker_be6091909abf41dba2743dacda81fb8d.bindPopup(popup_6ca678b241f14296be4c591dc8ef54a0)
        ;

        
    
    
            var circle_marker_931a009d8ad74e099b43f7095fb5fbfe = L.circleMarker(
                [11.33035, 77.71777],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_eada54c1df5d4669a3535c5391e6c72c = L.popup({"maxWidth": "100%"});

        
            var html_7b96aff60a6c4648aaa880a0d16504c3 = $(`<div id="html_7b96aff60a6c4648aaa880a0d16504c3" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Erode<br><strong>State</strong>: Tamil Nadu<br><strong>Confirmed Cases</strong>: 2<br></div>`)[0];
            popup_eada54c1df5d4669a3535c5391e6c72c.setContent(html_7b96aff60a6c4648aaa880a0d16504c3);
        

        circle_marker_931a009d8ad74e099b43f7095fb5fbfe.bindPopup(popup_eada54c1df5d4669a3535c5391e6c72c)
        ;

        
    
    
            var circle_marker_4ffe738685b6446583cf30c2e1dcb1b2 = L.circleMarker(
                [10.88184, 78.65384],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_14b0395fe41c42199bb03144a2eee98e = L.popup({"maxWidth": "100%"});

        
            var html_ff8bbb3c951c44139cb07bc9593fd310 = $(`<div id="html_ff8bbb3c951c44139cb07bc9593fd310" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Kanchipurum<br><strong>State</strong>: Tamil Nadu<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_14b0395fe41c42199bb03144a2eee98e.setContent(html_ff8bbb3c951c44139cb07bc9593fd310);
        

        circle_marker_4ffe738685b6446583cf30c2e1dcb1b2.bindPopup(popup_14b0395fe41c42199bb03144a2eee98e)
        ;

        
    
    
            var circle_marker_ca9470452e434f2c91c0664642bea7a5 = L.circleMarker(
                [9.93743, 78.09082],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_17573058501e4e8098b10bf22dcf73b3 = L.popup({"maxWidth": "100%"});

        
            var html_1c424fb866cd44f1a13616a16f0f1e8f = $(`<div id="html_1c424fb866cd44f1a13616a16f0f1e8f" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Madurai<br><strong>State</strong>: Tamil Nadu<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_17573058501e4e8098b10bf22dcf73b3.setContent(html_1c424fb866cd44f1a13616a16f0f1e8f);
        

        circle_marker_ca9470452e434f2c91c0664642bea7a5.bindPopup(popup_17573058501e4e8098b10bf22dcf73b3)
        ;

        
    
    
            var circle_marker_850d816721dc49f7bdb1dcd7c7f388fb = L.circleMarker(
                [10.88184, 78.65384],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_b8d836394160477ba15eab9b9641736e = L.popup({"maxWidth": "100%"});

        
            var html_771ff25c999a4aaead1f309fabb069e6 = $(`<div id="html_771ff25c999a4aaead1f309fabb069e6" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Tiruneveli<br><strong>State</strong>: Tamil Nadu<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_b8d836394160477ba15eab9b9641736e.setContent(html_771ff25c999a4aaead1f309fabb069e6);
        

        circle_marker_850d816721dc49f7bdb1dcd7c7f388fb.bindPopup(popup_b8d836394160477ba15eab9b9641736e)
        ;

        
    
    
            var circle_marker_5ba3d92ff0144c549593d92095ebee23 = L.circleMarker(
                [10.9643, 77.595],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_d812488c6de943bc809a1b541f4eaa1f = L.popup({"maxWidth": "100%"});

        
            var html_eef153fbbadd4c8ea4dee484be3b8cd4 = $(`<div id="html_eef153fbbadd4c8ea4dee484be3b8cd4" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Tirupur<br><strong>State</strong>: Tamil Nadu<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_d812488c6de943bc809a1b541f4eaa1f.setContent(html_eef153fbbadd4c8ea4dee484be3b8cd4);
        

        circle_marker_5ba3d92ff0144c549593d92095ebee23.bindPopup(popup_d812488c6de943bc809a1b541f4eaa1f)
        ;

        
    
    
            var circle_marker_5e08a1c1b6974f39834e5b0f2f2118bf = L.circleMarker(
                [17.42677, 78.45051],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_d8741a24e18b40098617fe154d3a5991 = L.popup({"maxWidth": "100%"});

        
            var html_6d0b24d720014272b91528f5bd611382 = $(`<div id="html_6d0b24d720014272b91528f5bd611382" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Bhadradri kothagudam<br><strong>State</strong>: Telangana<br><strong>Confirmed Cases</strong>: 2<br></div>`)[0];
            popup_d8741a24e18b40098617fe154d3a5991.setContent(html_6d0b24d720014272b91528f5bd611382);
        

        circle_marker_5e08a1c1b6974f39834e5b0f2f2118bf.bindPopup(popup_d8741a24e18b40098617fe154d3a5991)
        ;

        
    
    
            var circle_marker_856f6b39a11543aeac50fbb3674e64df = L.circleMarker(
                [17.45859, 78.37372],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 21, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_2534e8cf40ee4ce3860c88fa751a201d = L.popup({"maxWidth": "100%"});

        
            var html_c180fd6c194944f9a29f775ed94b82aa = $(`<div id="html_c180fd6c194944f9a29f775ed94b82aa" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Hyderabad<br><strong>State</strong>: Telangana<br><strong>Confirmed Cases</strong>: 21<br></div>`)[0];
            popup_2534e8cf40ee4ce3860c88fa751a201d.setContent(html_c180fd6c194944f9a29f775ed94b82aa);
        

        circle_marker_856f6b39a11543aeac50fbb3674e64df.bindPopup(popup_2534e8cf40ee4ce3860c88fa751a201d)
        ;

        
    
    
            var circle_marker_668d067ada3040a382c6195c358de086 = L.circleMarker(
                [17.42677, 78.45051],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_074ecddaa3764792a4e9caabb17e3d83 = L.popup({"maxWidth": "100%"});

        
            var html_1cdb3bed5ecc455387915d294d18349f = $(`<div id="html_1cdb3bed5ecc455387915d294d18349f" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Medchal<br><strong>State</strong>: Telangana<br><strong>Confirmed Cases</strong>: 3<br></div>`)[0];
            popup_074ecddaa3764792a4e9caabb17e3d83.setContent(html_1cdb3bed5ecc455387915d294d18349f);
        

        circle_marker_668d067ada3040a382c6195c358de086.bindPopup(popup_074ecddaa3764792a4e9caabb17e3d83)
        ;

        
    
    
            var circle_marker_b874592491524c48bcde40d49f84c97c = L.circleMarker(
                [17.27578, 78.10196],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 4, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_b03e9ae33f4d409b8892ba280ca41acd = L.popup({"maxWidth": "100%"});

        
            var html_db6dffe9c5c540739c77dec826aa1b0e = $(`<div id="html_db6dffe9c5c540739c77dec826aa1b0e" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Ranga reddy<br><strong>State</strong>: Telangana<br><strong>Confirmed Cases</strong>: 4<br></div>`)[0];
            popup_b03e9ae33f4d409b8892ba280ca41acd.setContent(html_db6dffe9c5c540739c77dec826aa1b0e);
        

        circle_marker_b874592491524c48bcde40d49f84c97c.bindPopup(popup_b03e9ae33f4d409b8892ba280ca41acd)
        ;

        
    
    
            var circle_marker_f5f0fac0c3d945bca9ab9d05d6467840 = L.circleMarker(
                [17.96156, 79.58744],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_4d279f247849499ca46eb0e64e6a8639 = L.popup({"maxWidth": "100%"});

        
            var html_30bb3a760a75426999ab0db978536d34 = $(`<div id="html_30bb3a760a75426999ab0db978536d34" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Warangal (u)<br><strong>State</strong>: Telangana<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_4d279f247849499ca46eb0e64e6a8639.setContent(html_30bb3a760a75426999ab0db978536d34);
        

        circle_marker_f5f0fac0c3d945bca9ab9d05d6467840.bindPopup(popup_4d279f247849499ca46eb0e64e6a8639)
        ;

        
    
    
            var circle_marker_f3f4723a28b64c278fd82b010c33d97e = L.circleMarker(
                [27.02317, 78.09255],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_1c42ccc36cf6410d8c2194a90d2fe63a = L.popup({"maxWidth": "100%"});

        
            var html_f65877a5e31d4dfd91f813e3c6e19271 = $(`<div id="html_f65877a5e31d4dfd91f813e3c6e19271" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Agra<br><strong>State</strong>: Uttar Pradesh<br><strong>Confirmed Cases</strong>: 8<br></div>`)[0];
            popup_1c42ccc36cf6410d8c2194a90d2fe63a.setContent(html_f65877a5e31d4dfd91f813e3c6e19271);
        

        circle_marker_f3f4723a28b64c278fd82b010c33d97e.bindPopup(popup_1c42ccc36cf6410d8c2194a90d2fe63a)
        ;

        
    
    
            var circle_marker_77b0a26f4a1c4d93900c4e7651c85fa0 = L.circleMarker(
                [32.1507, 77.14841],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_4521e879a0fa414d905038c71f103a56 = L.popup({"maxWidth": "100%"});

        
            var html_9eaebbd0b67441058382fd27dff28e27 = $(`<div id="html_9eaebbd0b67441058382fd27dff28e27" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Gb nagar<br><strong>State</strong>: Uttar Pradesh<br><strong>Confirmed Cases</strong>: 8<br></div>`)[0];
            popup_4521e879a0fa414d905038c71f103a56.setContent(html_9eaebbd0b67441058382fd27dff28e27);
        

        circle_marker_77b0a26f4a1c4d93900c4e7651c85fa0.bindPopup(popup_4521e879a0fa414d905038c71f103a56)
        ;

        
    
    
            var circle_marker_6c41d33aec0c4074a93ebca4fa9b0c48 = L.circleMarker(
                [28.68564, 77.62016],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_02ed84fe3d844a62a257d7483910a378 = L.popup({"maxWidth": "100%"});

        
            var html_5b8d3e243d0d4558b34c3e3c6d1681c1 = $(`<div id="html_5b8d3e243d0d4558b34c3e3c6d1681c1" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Ghaziabad<br><strong>State</strong>: Uttar Pradesh<br><strong>Confirmed Cases</strong>: 3<br></div>`)[0];
            popup_02ed84fe3d844a62a257d7483910a378.setContent(html_5b8d3e243d0d4558b34c3e3c6d1681c1);
        

        circle_marker_6c41d33aec0c4074a93ebca4fa9b0c48.bindPopup(popup_02ed84fe3d844a62a257d7483910a378)
        ;

        
    
    
            var circle_marker_395c879c3cfd41ce87ffb9731b246dca = L.circleMarker(
                [26.45555, 80.32727],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_99b9900a5a8e45d5b9fe2ab5b8609708 = L.popup({"maxWidth": "100%"});

        
            var html_0301bba386a2493db99b56b621e3927e = $(`<div id="html_0301bba386a2493db99b56b621e3927e" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Kanpur<br><strong>State</strong>: Uttar Pradesh<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_99b9900a5a8e45d5b9fe2ab5b8609708.setContent(html_0301bba386a2493db99b56b621e3927e);
        

        circle_marker_395c879c3cfd41ce87ffb9731b246dca.bindPopup(popup_99b9900a5a8e45d5b9fe2ab5b8609708)
        ;

        
    
    
            var circle_marker_7da30f192bc8425096946a1d737655d7 = L.circleMarker(
                [28.17768, 80.7067],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_a3abb8e1ee1e4f0f9cdff9b90ea5ea7f = L.popup({"maxWidth": "100%"});

        
            var html_19d068b6f74740febbfe1c15e777155c = $(`<div id="html_19d068b6f74740febbfe1c15e777155c" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Lakhimpur kheri<br><strong>State</strong>: Uttar Pradesh<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_a3abb8e1ee1e4f0f9cdff9b90ea5ea7f.setContent(html_19d068b6f74740febbfe1c15e777155c);
        

        circle_marker_7da30f192bc8425096946a1d737655d7.bindPopup(popup_a3abb8e1ee1e4f0f9cdff9b90ea5ea7f)
        ;

        
    
    
            var circle_marker_968020c8ce9b4ba69cf121ef2b61e9df = L.circleMarker(
                [26.83451, 80.90802],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 8, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_b0086ae5ebaf407585850a65b39c9fd9 = L.popup({"maxWidth": "100%"});

        
            var html_e25edcc04b3f4c25b0ee3c0d794c6ab8 = $(`<div id="html_e25edcc04b3f4c25b0ee3c0d794c6ab8" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Lucknow<br><strong>State</strong>: Uttar Pradesh<br><strong>Confirmed Cases</strong>: 8<br></div>`)[0];
            popup_b0086ae5ebaf407585850a65b39c9fd9.setContent(html_e25edcc04b3f4c25b0ee3c0d794c6ab8);
        

        circle_marker_968020c8ce9b4ba69cf121ef2b61e9df.bindPopup(popup_b0086ae5ebaf407585850a65b39c9fd9)
        ;

        
    
    
            var circle_marker_294d1a71e1a040f1aace980032a2f76c = L.circleMarker(
                [26.96937, 80.56707],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_1a6e111a1b324454918f6c3e3ba87b9b = L.popup({"maxWidth": "100%"});

        
            var html_4119c7dbc7ad493a99ea806c9dbfd585 = $(`<div id="html_4119c7dbc7ad493a99ea806c9dbfd585" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Philibhit<br><strong>State</strong>: Uttar Pradesh<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_1a6e111a1b324454918f6c3e3ba87b9b.setContent(html_4119c7dbc7ad493a99ea806c9dbfd585);
        

        circle_marker_294d1a71e1a040f1aace980032a2f76c.bindPopup(popup_1a6e111a1b324454918f6c3e3ba87b9b)
        ;

        
    
    
            var circle_marker_b67fc4092d92463b9e6f61d388f1004a = L.circleMarker(
                [26.96937, 80.56707],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_14a9b5bd89b541c5892feac60c51d277 = L.popup({"maxWidth": "100%"});

        
            var html_8ead74f992b0497aa69c5ebc98905d09 = $(`<div id="html_8ead74f992b0497aa69c5ebc98905d09" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Shamli<br><strong>State</strong>: Uttar Pradesh<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_14a9b5bd89b541c5892feac60c51d277.setContent(html_8ead74f992b0497aa69c5ebc98905d09);
        

        circle_marker_b67fc4092d92463b9e6f61d388f1004a.bindPopup(popup_14a9b5bd89b541c5892feac60c51d277)
        ;

        
    
    
            var circle_marker_0714754aecc74e88b05c1af65d1cca67 = L.circleMarker(
                [25.38029, 82.93882],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 1, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_61b5f1f314e1493ca86230906bf7ac5c = L.popup({"maxWidth": "100%"});

        
            var html_b8a29991705c47bc9e53ec63d98f9c2c = $(`<div id="html_b8a29991705c47bc9e53ec63d98f9c2c" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Varanasi<br><strong>State</strong>: Uttar Pradesh<br><strong>Confirmed Cases</strong>: 1<br></div>`)[0];
            popup_61b5f1f314e1493ca86230906bf7ac5c.setContent(html_b8a29991705c47bc9e53ec63d98f9c2c);
        

        circle_marker_0714754aecc74e88b05c1af65d1cca67.bindPopup(popup_61b5f1f314e1493ca86230906bf7ac5c)
        ;

        
    
    
            var circle_marker_93ad3d9cac6e4adf896ec375c3aa16d2 = L.circleMarker(
                [30.46371, 77.91558],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 3, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_0adea29852ec4773a3820333b62ce15c = L.popup({"maxWidth": "100%"});

        
            var html_9e1183748d6649d7ac14a29d7d7930db = $(`<div id="html_9e1183748d6649d7ac14a29d7d7930db" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Dehradun<br><strong>State</strong>: Uttarakhand<br><strong>Confirmed Cases</strong>: 3<br></div>`)[0];
            popup_0adea29852ec4773a3820333b62ce15c.setContent(html_9e1183748d6649d7ac14a29d7d7930db);
        

        circle_marker_93ad3d9cac6e4adf896ec375c3aa16d2.bindPopup(popup_0adea29852ec4773a3820333b62ce15c)
        ;

        
    
    
            var circle_marker_15179fd5471c4509b885a274d9f543ca = L.circleMarker(
                [22.56775, 88.3476],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 5, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_67af2a69d64a42fcb8b54a49af4bb811 = L.popup({"maxWidth": "100%"});

        
            var html_111160435eed44e895f4e71efca6edb5 = $(`<div id="html_111160435eed44e895f4e71efca6edb5" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: Kolkata<br><strong>State</strong>: West Bengal<br><strong>Confirmed Cases</strong>: 5<br></div>`)[0];
            popup_67af2a69d64a42fcb8b54a49af4bb811.setContent(html_111160435eed44e895f4e71efca6edb5);
        

        circle_marker_15179fd5471c4509b885a274d9f543ca.bindPopup(popup_67af2a69d64a42fcb8b54a49af4bb811)
        ;

        
    
    
            var circle_marker_9b65e8c8d6b04bfdb5786ce582c08bb0 = L.circleMarker(
                [22.9353, 88.61297],
                {"bubblingMouseEvents": true, "color": "red", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "red", "fillOpacity": 0.7, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 2, "stroke": true, "weight": 3}
            ).addTo(map_e6ae7888d25a4796b3074d998b100d7d);
        
    
        var popup_509a476e53224de58c61d1893cc8310c = L.popup({"maxWidth": "100%"});

        
            var html_025355649bd74c15901eb0399e394117 = $(`<div id="html_025355649bd74c15901eb0399e394117" style="width: 100.0%; height: 100.0%;"><strong>District_name</strong>: North 24 pargana<br><strong>State</strong>: West Bengal<br><strong>Confirmed Cases</strong>: 2<br></div>`)[0];
            popup_509a476e53224de58c61d1893cc8310c.setContent(html_025355649bd74c15901eb0399e394117);
        

        circle_marker_9b65e8c8d6b04bfdb5786ce582c08bb0.bindPopup(popup_509a476e53224de58c61d1893cc8310c)
        ;

        
    
</script>
</html>
