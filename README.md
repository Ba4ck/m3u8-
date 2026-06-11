# m3u8-ts-视频下载合成器

获取m3u8网址完整链接  
如下  
https://xxx.xxx.com/live/2b06fbd1-xxxxxxxx-9972-a2b6f7c11edc_normal.m3u8?auth_key=xxxxx

获取该请求的响应，ts文件列表，如下  
#EXTM3U  
#EXT-X-VERSION:3  
#EXT-X-MEDIA-SEQUENCE:1  
#EXT-X-TARGETDURATION:35  
#EXTINF:30.949,  
2b06fbd1-xxxxxxxx-9972-a2b6f7c11edc/1.ts?auth_key=1782021331-69874cec53b94bb78fb4543ce9c36142-0-660045c92ae2bf0968c6b2d9054ffa4b  
#EXTINF:31.420,  
2b06fbd1-xxxxxxxx-9972-a2b6f7c11edc/2.ts?auth_key=1782021331-69874cec53b94bb78fb4543ce9c36142-0-65312b430cde4da3623856f3d22c599c  
#EXTINF:31.244,  
2b06fbd1-xxxxxxxx-9972-a2b6f7c11edc/3.ts?auth_key=1782021331-69874cec53b94bb78fb4543ce9c36142-0-cea88962b3391adbb7078647a03878dc  
#EXTINF:33.900,  
2b06fbd1-xxxxxxxx-9972-a2b6f7c11edc/4.ts?auth_key=1782021331-69874cec53b94bb78fb4543ce9c36142-0-f50e68ebcd6ac255d71062f31e6ea7bd  
#EXTINF:32.968,  
...  
#EXT-X-ENDLIST  
  
选择要保存ts文件的目录
  
选择要保存合成视频的目录
  
可设置线程数
  
点击解析合成下载即可
