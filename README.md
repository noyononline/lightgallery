# lightgallery

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/lightgallery/2.7.2/css/lightgallery.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/lightgallery/2.7.2/css/lg-thumbnail.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/lightgallery/2.7.2/css/lg-autoplay.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/lightgallery/2.7.2/css/lg-fullscreen.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/lightgallery/2.7.2/css/lg-pager.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/lightgallery/2.7.2/css/lg-zoom.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/lightgallery/2.7.2/css/lg-share.min.css">
    

    <script src="https://cdnjs.cloudflare.com/ajax/libs/lightgallery/2.7.2/lightgallery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/lightgallery/2.7.2/plugins/thumbnail/lg-thumbnail.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/lightgallery/2.7.2/plugins/autoplay/lg-autoplay.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/lightgallery/2.7.2/plugins/fullscreen/lg-fullscreen.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/lightgallery/2.7.2/plugins/pager/lg-pager.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/lightgallery/2.7.2/plugins/zoom/lg-zoom.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/lightgallery/2.7.2/plugins/share/lg-share.min.js"></script>
    

</head>
<body>
    


    <div id="lightgallery">
        
        <a href="https://www.freecodecamp.org/news/content/images/2022/11/What-is.png">
            <img src="https://media.geeksforgeeks.org/wp-content/uploads/20230726113229/Concept-of-nodejs.webp" alt="" />
        </a>
        <a href="https://successive.tech/wp-content/uploads/2022/01/Advantages-of-Using-Node.js-for-Enterprise-Development.jpg">
            <img style="display: none;" src="https://successive.tech/wp-content/uploads/2022/01/Advantages-of-Using-Node.js-for-Enterprise-Development.jpg" alt="" />
        </a>
        <a href="https://images.unsplash.com/photo-1609342122563-a43ac8917a3a?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=1600&q=80" data-pswp-width="1200" data-pswp-height="600">
            <img style="display: none;" src="https://images.unsplash.com/photo-1609342122563-a43ac8917a3a?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=1600&q=80" alt="" />
        </a>
        <a href="https://learn.microsoft.com/en-us/azure/developer/javascript/media/node-howto-e2e/visual-studio-code-debug-console-autocomplete.png" data-pswp-width="1200" data-pswp-height="600">
            <img style="display: none;" src="https://learn.microsoft.com/en-us/azure/developer/javascript/media/node-howto-e2e/visual-studio-code-debug-console-autocomplete.png" alt="" />
        </a>
        <a href="https://www.freecodecamp.org/news/content/images/2022/11/What-is.png" data-pswp-width="1200" data-pswp-height="600">
            <img style="display: none;" src="https://www.freecodecamp.org/news/content/images/2022/11/What-is.png" alt="" />
        </a>
        <a href="https://fusionauth.io/img/blogs/easy-integration-fusionauth-nodejs/node-and-fusionauth-example-tiny.jpg" data-pswp-width="1200" data-pswp-height="600">
            <img style="display: none;" src="https://fusionauth.io/img/blogs/easy-integration-fusionauth-nodejs/node-and-fusionauth-example-tiny.jpg" alt="" />
        </a>
    </div>




    <script type="text/javascript">
        let gallery = document.getElementById("lightgallery")
            lightGallery(gallery,{
                controls: true,
                showCloseIcon: true,
                download: false,
                plugins: [lgThumbnail, lgZoom, lgAutoplay, lgFullscreen, lgPager, lgShare],
                mobileSettings: {
                    controls: false,
                    showCloseIcon: false,
                    download: false,
                    rotate: false
                    
                },
            })
    </script>
</body>
</html>
