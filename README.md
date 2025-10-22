# Download Wistia videos
Steps to download wistia videos (works as of 2025/10/22)
1. Right-click on the playing video, select Copy link, then paste in a Notepad

2. Find Wistia video ID in the copied link e.g. wvideo=fra6g1m6rl

3. Load http://fast.wistia.net/embed/iframe/ + video ID in your browser
   e.g. http://fast.wistia.net/embed/iframe/fra6g1m6rl

4. If it is password protected, enter the password.

5. Play the video <-- important step

6. Open Developer tools and search for something like  "contentUrl":"https://embed-ssl.wistia.com/deliveries/85c81303920f5e17922be67c2a04e856d641680e.m3u8".
It should be something that ends with .m3u8.

7. Copy the link and paste in the browser, change .m3u8 to .mp4
 e.g. https://embed-ssl.wistia.com/deliveries/85c81303920f5e17922be67c2a04e856d641680e.mp4

8. Right click on the video and save as mp4.

