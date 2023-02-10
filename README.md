# webRTC-video-android
Simple Android app example that streams and receives video/audio using WebRTC

### Setup
1. Create a Web Server using this code https://github.com/buster92/signaling-server. 
In my case I created the server on Render (https://render.com/)

2. After the web server is deployed and ready. Replace the given url on the Android project (`SERVER_ENDPOINT`)

```
public class CompleteActivity extends AppCompatActivity {
    private static final String SERVER_ENDPOINT = "https://signaling-server-kiwg.onrender.com/";
    private stat
    
    ...
```

3. Run the Android app.
