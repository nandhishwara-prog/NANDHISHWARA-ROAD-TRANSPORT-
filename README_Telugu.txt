SST ACTIONS UPDATE — జాగ్రత్తగా పరీక్షించండి

1) Reports Actions లో View, Print మాత్రమే కనిపించేలా మార్చబడింది.
2) View LR పేజీలో Print/PDF, Edit, Share, Cancel LR, Delete బటన్లు కనిపిస్తాయి.
3) Cancel status ను Supabase lrs table లో status='Cancelled' గా update చేస్తుంది; మీ Supabase policy అనుమతించాలి.
4) Delete శాశ్వతం. టెస్ట్ LR మాత్రమే వాడండి.
5) Print CSS / renderPrint ఫంక్షన్‌ను మార్చలేదు. అయినా browser print పరీక్షించకుండా live data మీద నమ్మకంగా ఉపయోగించవద్దు.
6) Upload చేయాల్సినవి shiva-bilty.html మరియు shiva-reports.html మాత్రమే. index.html, bilty.html, reports.html, supabase-config.js, background image మార్చవద్దు.
7) JavaScript syntax check మాత్రమే చేయబడింది; Live Supabase end-to-end పరీక్షించబడలేదు. ముందుగా backup తీసుకోండి.
