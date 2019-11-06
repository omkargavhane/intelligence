CropAdvApp is app written to acces the cropadvisor service 
it is client server system.where client is android application
and server is written in python

let's  talk about services that server servers.
1]find best crop service::finds best crop for given district and season name.
2]wikisearch::provides wikipedia search service.
3]Top 10 service::returns top10 crop producing states for given crop.

cropadv.zip[cropadv.zip]=>android client 
cropadvappserver.zip[cropadvserver.zip]=>python server

Instruction for setting up system
install cropadv in your mobile phone availbale in [cropadv.zip]
then extarct directory(cropadvserver) present in [cropadvserver.zip]
and just run (cropadvd.py) file present in (cropadvserver directory)
then check for your computers ip addresss and feed it into server's  ip address field
of app
as Top 10 service uses chrome_webdriver_linux_64bit  you must check 
the correct version according to your plateform and make corresponding changes in top10.py file in 
(cropadvserver directory) and also install proper ebdrive rfor your browser.

important note==>server pc and mobile device must be on same network .
