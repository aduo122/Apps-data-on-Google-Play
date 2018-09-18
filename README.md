# Apps-data-on-Google-Play 

Word Count
----
Hadoop code sample
add local combiner, range count, outputformat as sequence file

1. Use nutch get metadata from google play store

       metadata {url : meta data}

2. Combine acces log with metadata by the url
          
        Access Log Example
        190.152.211.196 - - [01/Oct/2017:00:00:00 +0000] "GET /axis2/services/WebFilteringService/getCategoryByUrl?app=chrome_antiporn&ver=0.19.7.1&url=http%3A//www.frlp.utn.edu.ar/materias/integracion3/UT_4_Nomenclatura.pdf&cat=unknown HTTP/1.1" 200 133 "-" "Mozilla/5.0 (Windows NT 6.2; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/61.0.3163.100 Safari/537.36”
        
        187.237.231.28 - - [03/Oct/2017:23:37:05 +0000] "GET /axis2/services/WebFilteringService/getCategoryByUrl?app=android_safebrowser&ver=1.2.5&url=https://play.googl e.com/store/apps/details?id=com.google.android.youtube&hl=es&referrer=utm_source%3Dgoogle%26utm_medium %3Dorganic%26utm_term%3Dyoutube&pcampaignid=APPU_1_Bh_UWf63L6bY0gKs2YL4DQ&cat=unknown HTTP/1.1" 200 133 "-" "Dalvik/1.6.0 (Linux; U; Android 4.4.2; lt-A31S Build/KOT49H)"

3. ETL data analysis

        most popular category
        geological distributed
        visit by time


<img src="https://raw.githubusercontent.com/aduo122/data-anlysis-for-Google-Play-Apps/master/visualization.pdf" width="40%">.
