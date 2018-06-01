{
  "settings": {
    "name": "Portfolio Site",
    "currentPage": "page5.html",
    "theme": {
      "name": "mobirise4",
      "title": "Mobirise 4",
      "styling": {
        "primaryColor": "#2ed2e8",
        "secondaryColor": "#ff3366",
        "successColor": "#F7ED4A",
        "infoColor": "#82786E",
        "warningColor": "#879A9F",
        "dangerColor": "#B1A374",
        "mainFont": "Rubik",
        "display1Font": "Rubik",
        "display1Size": 4.25,
        "display2Font": "Raleway",
        "display2Size": "1.5",
        "display5Font": "Handlee",
        "display5Size": 1.5,
        "display7Font": "Rubik",
        "display7Size": 1,
        "display4Font": "Rubik",
        "display4Size": 1,
        "isRoundedButtons": true,
        "isAnimatedOnScroll": false,
        "isScrollToTopButton": false
      },
      "additionalSetColors": [
        "#0a021e",
        "#1e065e",
        "#12033a",
        "#76719f",
        "#7ff6fb",
        "#893927",
        "#292929"
      ]
    },
    "path": "@PROJECT_PATH@",
    "siteFonts": [
      {
        "css": "'Handlee', handwriting",
        "name": "Handlee",
        "url": "https://fonts.googleapis.com/css?family=Handlee:400"
      },
      {
        "css": "'Roboto Mono', monospace",
        "name": "Roboto Mono",
        "url": "https://fonts.googleapis.com/css?family=Roboto+Mono:100,100i,300,300i,400,400i,500,500i,700,700i"
      },
      {
        "css": "'Cinzel', serif",
        "name": "Cinzel",
        "url": "https://fonts.googleapis.com/css?family=Cinzel:400,700,900"
      },
      {
        "css": "'Permanent Marker', handwriting",
        "name": "Permanent Marker",
        "url": "https://fonts.googleapis.com/css?family=Permanent+Marker:400"
      },
      {
        "css": "'Amatic SC', handwriting",
        "name": "Amatic SC",
        "url": "https://fonts.googleapis.com/css?family=Amatic+SC:400,700"
      },
      {
        "css": "'Raleway', sans-serif",
        "name": "Raleway",
        "url": "https://fonts.googleapis.com/css?family=Raleway:100,100i,200,200i,300,300i,400,400i,500,500i,600,600i,700,700i,800,800i,900,900i"
      }
    ],
    "versionFirst": "4.7.7",
    "uniqCompNum": 35,
    "versionPublish": "4.7.7",
    "screenshot": "screenshot.png"
  },
  "pages": {
    "index.html": {
      "settings": {
        "main": true,
        "title": "Home",
        "meta_descr": "",
        "header_custom": "",
        "footer_custom": "",
        "html_before": ""
      },
      "components": [
        {
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background-color": "@bg-value"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            "h1": {
              "color": "#616161"
            },
            "h2, h3, p": {
              "color": "#767676"
            },
            ".mbr-section-subtitle": {
              "font-style": "italic"
            },
            "P": {
              "color": "#ffffff"
            },
            "H1": {
              "color": "#ffffff"
            },
            "H3": {
              "color": "#cccccc"
            }
          },
          "_name": "header9",
          "_customHTML": "<section class=\"header9\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen,\n                    'mbr-parallax-background': bg.parallax}\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\" checked>\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubTitle\" checked>\n        <input type=\"checkbox\" title=\"Show Text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background1.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#12033a\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#000000\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.2\" condition=\"overlay && bg.type !== 'color'\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n\n    <div class=\"container\">\n        <div class=\"media-container-column mbr-white col-md-8\">\n            <h1 class=\"mbr-section-title align-left mbr-bold pb-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\">\n                Digital Media Portfolio</h1>\n            <h3 class=\"mbr-section-subtitle align-left mbr-light pb-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubTitle\">\n                By Isabella&nbsp;</h3>\n            <p class=\"mbr-text align-left pb-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\">\n                This website is meant to serve as a digital portfolio showcasing some of the things I have made on Photoshop over the last year. Many of these pieces were made as part of school assignments, and some were made on my own, but all were made by me. From having never used Photoshop before to the creation the numerous compositions I can now put my name to, this portfolio chronicles some of the best pieces I have made during my journey of learning to utilize the elements and principles of design in Photoshop.\n            </p>\n            <div class=\"mbr-section-btn align-left\" mbr-if=\"showButtons\" mbr-buttons mbr-theme-style=\"display-4\"><a class=\"btn btn-md btn-primary\" href=\"page2.html\" data-app-placeholder=\"Type Text\">Best Of Gallery</a>\n                <a class=\"btn btn-md btn-primary\" href=\"page1.html\" data-app-placeholder=\"Type Text\">101 Design Gallery</a> <a class=\"btn btn-md btn-primary\" href=\"page3.html\" data-app-placeholder=\"Type Text\">171 Photoshop Gallery</a> <a class=\"btn btn-md btn-primary\" href=\"page5.html\" data-app-placeholder=\"Type Text\">Contact</a></div>\n        </div>\n    </div>\n\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_cid": "qTJOkBzdJT",
          "_anchor": "header9-1",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        }
      ]
    },
    "page2.html": {
      "settings": {
        "meta_descr": "Web Builder Description",
        "title": "Best Of Gallery",
        "order": 2
      },
      "components": [
        {
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "background-color": "@bgColor",
            ".mbr-slider .carousel-control": {
              "background": "#1b1b1b"
            },
            ".mbr-slider .carousel-control-prev": {
              "left": "0",
              "margin-left": "2.5rem"
            },
            ".mbr-slider .carousel-control-next": {
              "right": "0",
              "margin-right": "2.5rem"
            },
            ".mbr-slider .modal-body .close": {
              "background": "#1b1b1b"
            },
            ".mbr-gallery-item > div::before": {
              "content": "''",
              "position": "absolute",
              "left": "0",
              "top": "0",
              "width": "100%",
              "height": "100%",
              "background": "@overlayColor",
              "& when (@gradOverlay)": {
                "background": "linear-gradient(to left, @overlayColor, @overlayColor2) !important"
              },
              "opacity": "0",
              "-webkit-transition": "0.2s opacity ease-in-out",
              "transition": "0.2s opacity ease-in-out"
            },
            ".mbr-gallery-item > div:hover": {
              ".mbr-gallery-title::before": {
                "background": "transparent !important"
              },
              "&:before": {
                "opacity": "@overlayOpacity !important"
              }
            },
            ".mbr-gallery-title": {
              "font-size": ".9em",
              "position": "absolute",
              "display": "block",
              "width": "100%",
              "bottom": "0",
              "padding": "1rem",
              "color": "#fff",
              "z-index": "2",
              "&:before": {
                "content": "\" \"",
                "width": "100%",
                "height": "100%",
                "top": "0",
                "left": "0",
                "z-index": "-1",
                "position": "absolute",
                "background": "@overlayColor !important",
                "& when (@gradOverlay)": {
                  "background": "linear-gradient(to left, @overlayColor, @overlayColor2) !important"
                },
                "opacity": "@overlayOpacity",
                "-webkit-transition": "0.2s background ease-in-out",
                "transition": "0.2s background ease-in-out"
              }
            }
          },
          "_name": "gallery2",
          "_customHTML": "<section class=\"mbr-gallery mbr-slider-carousel\" group=\"Sliders & Gallery\" plugins=\"Masonry,BootstrapCarouselSwipe,Gallery,VimeoPlayer,SliderVideo\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Width\" name=\"fullWidth\">\n        <input type=\"range\" title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"9\" inline>\n        <input type=\"range\" title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"9\" inline>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\">\n        <input type=\"checkbox\" title=\"Gradient Overlay\" name=\"gradOverlay\" checked>\n        <input type=\"color\" title=\"Overlay Color 2\" name=\"overlayColor2\" value=\"#45505b\" condition=\"gradOverlay\">\n        <input type=\"range\" title=\"Overlay Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.6\" inline>\n        <input type=\"color\" title=\"Background Color\" name=\"bgColor\" value=\"#12033a\">\n\n        <input type=\"gallery\" title=\"Gallery\" name=\"gallery\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div mbr-class=\"{'container': !fullWidth}\">\n        <div mbr-gallery=\"gallery\" mbr-gallery-spacing=\"2\" mbr-gallery-show-text></div>\n    </div>\n\n</section>",
          "_cid": "qTJTblWYUR",
          "_anchor": "gallery2-9",
          "_protectedParams": [
            "text_all",
            "gallery__filtersTextStyle",
            "gallery__filtersBtnStyle",
            "gallery"
          ],
          "_global": false,
          "_once": false,
          "_params": {
            "text_all": "All",
            "gallery__filtersTextStyle": "display-2",
            "gallery__filtersBtnStyle": "btn-primary",
            "gallery": [
              {
                "tags": "Animated",
                "videoPreview": "@THEME_PATH@/components/_images/gallery/preview.jpg",
                "playVideo": false,
                "videoUrl": "https://www.youtube.com/watch?v=fwkKc6M60-0",
                "image": "@PROJECT_PATH@/assets/images/remixsquid-500x502.jpg",
                "thumb": "@PROJECT_PATH@/assets/images/remixsquid-500x502-500x502.jpg",
                "alt": "",
                "title": "",
                "customStyle1": "display-5",
                "caption": "Squids",
                "active": false
              },
              {
                "tags": "Animated",
                "videoPreview": "@THEME_PATH@/components/_images/gallery/preview.jpg",
                "playVideo": false,
                "videoUrl": "https://www.youtube.com/watch?v=fwkKc6M60-0",
                "image": "@PROJECT_PATH@/assets/images/birchtrees2-700x500.jpg",
                "thumb": "@PROJECT_PATH@/assets/images/birchtrees2-700x500-700x500.jpg",
                "alt": "",
                "title": "",
                "customStyle1": "display-5",
                "caption": "Birch Trees",
                "active": true
              },
              {
                "tags": "Animated",
                "videoPreview": "@THEME_PATH@/components/_images/gallery/preview.jpg",
                "playVideo": false,
                "videoUrl": "https://www.youtube.com/watch?v=fwkKc6M60-0",
                "image": "@PROJECT_PATH@/assets/images/rhythm-500x498.jpg",
                "thumb": "@PROJECT_PATH@/assets/images/rhythm-500x498-500x498.jpg",
                "alt": "",
                "title": "",
                "customStyle1": "display-5",
                "caption": "Rhythms",
                "active": false
              }
            ]
          }
        },
        {
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background": "linear-gradient(45deg, @bg-value, @color2)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "font-style": "italic",
              "letter-spacing": "1rem"
            }
          },
          "_name": "header11",
          "_customHTML": "<section class=\"header11\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen, 'mbr-parallax-background': bg.parallax}\">\n\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n    <mbr-parameters>\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n        <input type=\"checkbox\" title=\"Show text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#03011b\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"color\" title=\"Color 2\" name=\"color2\" value=\"#1000b3\">\n\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#000000\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.2\" condition=\"overlay && bg.type !== 'color'\">\n    </mbr-parameters>\n    <!-- End block parameters -->\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container align-left\">\n        <div class=\"media-container-column mbr-white col-md-12\">\n            <h3 class=\"mbr-section-subtitle py-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubtitle\">\n                Squids</h3>\n            <h1 class=\"mbr-section-title py-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title, .mbr-section-btn\">\n                Create awesome <b>mobile-friendly</b> websites! No coding and <b>free</b>.\n            </h1>\n            <p class=\"mbr-text py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\">\n                In this piece, I was inspired by the incredible sense of movement that is often exuded by sea creatures. As a result, I took the squids and their interesting shapes, and added a dark, mysterious environment to contrast the vibrance of their forms painted with colorful flair.\n            </p>\n            <div class=\"mbr-section-btn py-4\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\" mbr-buttons mbr-theme-style=\"display-4\">\n                    <a class=\"btn btn-md btn-primary\" href=\"https://mobirise.com\">LEARN MORE</a>\n                    <a class=\"btn btn-md btn-white-outline\" href=\"https://mobirise.com\">LIVE DEMO</a>\n            </div>\n        </div>\n    </div>\n\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_cid": "qTJVS3t0IA",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {},
          "_anchor": "header11-a"
        },
        {
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background": "linear-gradient(45deg, @bg-value, @color2)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "font-style": "italic",
              "letter-spacing": "1rem"
            }
          },
          "_name": "header11",
          "_customHTML": "<section class=\"header11\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen, 'mbr-parallax-background': bg.parallax}\">\n\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n    <mbr-parameters>\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n        <input type=\"checkbox\" title=\"Show text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#1f743e\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"color\" title=\"Color 2\" name=\"color2\" value=\"#2ed2e8\">\n\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#000000\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.2\" condition=\"overlay && bg.type !== 'color'\">\n    </mbr-parameters>\n    <!-- End block parameters -->\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container align-left\">\n        <div class=\"media-container-column mbr-white col-md-12\">\n            <h3 class=\"mbr-section-subtitle py-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubtitle\">\n                Birch Trees</h3>\n            <h1 class=\"mbr-section-title py-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title, .mbr-section-btn\">\n                Create awesome <b>mobile-friendly</b> websites! No coding and <b>free</b>.\n            </h1>\n            <p class=\"mbr-text py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\">\n                This project was originally meant to serve as a simple, minimalist background of birch trees in the summer. However, I saw its potential to become a window into a gorgeous summer day, and brought that potential to fruition through this composition.\n            </p>\n            <div class=\"mbr-section-btn py-4\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\" mbr-buttons mbr-theme-style=\"display-4\">\n                    <a class=\"btn btn-md btn-primary\" href=\"https://mobirise.com\">LEARN MORE</a>\n                    <a class=\"btn btn-md btn-white-outline\" href=\"https://mobirise.com\">LIVE DEMO</a>\n            </div>\n        </div>\n    </div>\n\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_cid": "qTJWpR7O4K",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {},
          "_anchor": "header11-b"
        },
        {
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background": "linear-gradient(45deg, @bg-value, @color2)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "font-style": "italic",
              "letter-spacing": "1rem"
            }
          },
          "_name": "header11",
          "_customHTML": "<section class=\"header11\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen, 'mbr-parallax-background': bg.parallax}\">\n\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n    <mbr-parameters>\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n        <input type=\"checkbox\" title=\"Show text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#9b0026\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"color\" title=\"Color 2\" name=\"color2\" value=\"#002db3\">\n\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#000000\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.2\" condition=\"overlay && bg.type !== 'color'\">\n    </mbr-parameters>\n    <!-- End block parameters -->\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container align-left\">\n        <div class=\"media-container-column mbr-white col-md-12\">\n            <h3 class=\"mbr-section-subtitle py-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubtitle\">\n                Rhythms</h3>\n            <h1 class=\"mbr-section-title py-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title, .mbr-section-btn\">\n                Create awesome <b>mobile-friendly</b> websites! No coding and <b>free</b>.\n            </h1>\n            <p class=\"mbr-text py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\">\n                The goal of this project was to create various impressions of rhythm, and this project achieves that goal beautifully. Combining various textures and colors, I created several squares of raw visual impressions. \n            </p>\n            <div class=\"mbr-section-btn py-4\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\" mbr-buttons mbr-theme-style=\"display-4\">\n                    <a class=\"btn btn-md btn-primary\" href=\"https://mobirise.com\">LEARN MORE</a>\n                    <a class=\"btn btn-md btn-white-outline\" href=\"https://mobirise.com\">LIVE DEMO</a>\n            </div>\n        </div>\n    </div>\n\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_cid": "qTJWYZF1xt",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {},
          "_anchor": "header11-c"
        },
        {
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background": "linear-gradient(45deg, @bg-value, @color2)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "font-style": "italic",
              "letter-spacing": "1rem"
            }
          },
          "_name": "header11",
          "_customHTML": "<section class=\"header11\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen, 'mbr-parallax-background': bg.parallax}\">\n\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n    <mbr-parameters>\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\">\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\">\n        <input type=\"checkbox\" title=\"Show text\" name=\"showText\">\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#12033a\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"color\" title=\"Color 2\" name=\"color2\" value=\"#1e065e\">\n\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#000000\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.2\" condition=\"overlay && bg.type !== 'color'\">\n    </mbr-parameters>\n    <!-- End block parameters -->\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container align-left\">\n        <div class=\"media-container-column mbr-white col-md-12\">\n            <h3 class=\"mbr-section-subtitle py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\">\n                Rhythms</h3>\n            <h1 class=\"mbr-section-title py-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title, .mbr-section-btn\">\n                Create awesome <b>mobile-friendly</b> websites! No coding and <b>free</b>.\n            </h1>\n            <p class=\"mbr-text py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\"></p>\n            <div class=\"mbr-section-btn py-4\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\" mbr-buttons mbr-theme-style=\"display-5\"><a class=\"btn btn-md btn-primary\" href=\"index.html\" data-app-placeholder=\"Type Text\">Return to Home</a></div>\n        </div>\n    </div>\n\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_anchor": "header11-s",
          "_isUserblock": true,
          "_sourceTheme": "mobirise4",
          "_cid": "qTK2XqqXnu",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        }
      ]
    },
    "page3.html": {
      "settings": {
        "meta_descr": "Web Page Generator Description",
        "title": "171 Photoshop Gallery",
        "order": 4
      },
      "components": [
        {
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "background-color": "@bgColor",
            ".mbr-slider .carousel-control": {
              "background": "#1b1b1b"
            },
            ".mbr-slider .carousel-control-prev": {
              "left": "0",
              "margin-left": "2.5rem"
            },
            ".mbr-slider .carousel-control-next": {
              "right": "0",
              "margin-right": "2.5rem"
            },
            ".mbr-slider .modal-body .close": {
              "background": "#1b1b1b"
            },
            ".mbr-gallery-item > div::before": {
              "content": "''",
              "position": "absolute",
              "left": "0",
              "top": "0",
              "width": "100%",
              "height": "100%",
              "background": "@overlayColor",
              "& when (@gradOverlay)": {
                "background": "linear-gradient(to left, @overlayColor, @overlayColor2) !important"
              },
              "opacity": "0",
              "-webkit-transition": "0.2s opacity ease-in-out",
              "transition": "0.2s opacity ease-in-out"
            },
            ".mbr-gallery-item > div:hover": {
              ".mbr-gallery-title::before": {
                "background": "transparent !important"
              },
              "&:before": {
                "opacity": "@overlayOpacity !important"
              }
            },
            ".mbr-gallery-title": {
              "font-size": ".9em",
              "position": "absolute",
              "display": "block",
              "width": "100%",
              "bottom": "0",
              "padding": "1rem",
              "color": "#fff",
              "z-index": "2",
              "&:before": {
                "content": "\" \"",
                "width": "100%",
                "height": "100%",
                "top": "0",
                "left": "0",
                "z-index": "-1",
                "position": "absolute",
                "background": "@overlayColor !important",
                "& when (@gradOverlay)": {
                  "background": "linear-gradient(to left, @overlayColor, @overlayColor2) !important"
                },
                "opacity": "@overlayOpacity",
                "-webkit-transition": "0.2s background ease-in-out",
                "transition": "0.2s background ease-in-out"
              }
            }
          },
          "_name": "gallery2",
          "_customHTML": "<section class=\"mbr-gallery mbr-slider-carousel\" group=\"Sliders & Gallery\" plugins=\"Masonry,BootstrapCarouselSwipe,Gallery,VimeoPlayer,SliderVideo\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Width\" name=\"fullWidth\">\n        <input type=\"range\" title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"9\" inline>\n        <input type=\"range\" title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"9\" inline>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#554346\">\n        <input type=\"checkbox\" title=\"Gradient Overlay\" name=\"gradOverlay\" checked>\n        <input type=\"color\" title=\"Overlay Color 2\" name=\"overlayColor2\" value=\"#45505b\" condition=\"gradOverlay\">\n        <input type=\"range\" title=\"Overlay Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.7\" inline>\n        <input type=\"color\" title=\"Background Color\" name=\"bgColor\" value=\"#12033a\">\n\n        <input type=\"gallery\" title=\"Gallery\" name=\"gallery\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div mbr-class=\"{'container': !fullWidth}\">\n        <div mbr-gallery=\"gallery\" mbr-gallery-spacing=\"2\" mbr-gallery-show-text></div>\n    </div>\n\n</section>",
          "_cid": "qTJRlpFb2o",
          "_anchor": "gallery2-4",
          "_protectedParams": [
            "text_all",
            "gallery__filtersTextStyle",
            "gallery__filtersBtnStyle",
            "gallery"
          ],
          "_global": false,
          "_once": false,
          "_params": {
            "text_all": "All",
            "gallery__filtersTextStyle": "display-7",
            "gallery__filtersBtnStyle": "btn-primary",
            "gallery": [
              {
                "tags": "Animated",
                "videoPreview": "@THEME_PATH@/components/_images/gallery/preview.jpg",
                "playVideo": false,
                "videoUrl": "https://www.youtube.com/watch?v=fwkKc6M60-0",
                "image": "@PROJECT_PATH@/assets/images/venusfinal-1-700x1120.jpg",
                "thumb": "@PROJECT_PATH@/assets/images/venusfinal-1-700x1120-700x1120.jpg",
                "alt": "",
                "title": "",
                "customStyle1": "display-5",
                "caption": "Venus Poster",
                "active": false
              },
              {
                "tags": "Animated",
                "videoPreview": "@THEME_PATH@/components/_images/gallery/preview.jpg",
                "playVideo": false,
                "videoUrl": "https://www.youtube.com/watch?v=fwkKc6M60-0",
                "image": "@PROJECT_PATH@/assets/images/designchallangepuffinkronar-700x467.jpg",
                "thumb": "@PROJECT_PATH@/assets/images/designchallangepuffinkronar-700x467-700x467.jpg",
                "alt": "",
                "title": "",
                "customStyle1": "display-5",
                "caption": "Puffinland Kronar",
                "active": true
              },
              {
                "tags": "Animated",
                "videoPreview": "@THEME_PATH@/components/_images/gallery/preview.jpg",
                "playVideo": false,
                "videoUrl": "https://www.youtube.com/watch?v=fwkKc6M60-0",
                "image": "@PROJECT_PATH@/assets/images/camera-woman-700x438.jpg",
                "thumb": "@PROJECT_PATH@/assets/images/camera-woman-700x438-700x438.jpg",
                "alt": "",
                "title": "",
                "customStyle1": "display-5",
                "caption": "Camera Girl",
                "active": false
              }
            ]
          }
        },
        {
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background": "linear-gradient(45deg, @bg-value, @color2)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "font-style": "italic",
              "letter-spacing": "1rem"
            }
          },
          "_name": "header11",
          "_customHTML": "<section class=\"header11\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen, 'mbr-parallax-background': bg.parallax}\">\n\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n    <mbr-parameters>\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n        <input type=\"checkbox\" title=\"Show text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#000000\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"color\" title=\"Color 2\" name=\"color2\" value=\"#ec923d\">\n\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#000000\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.2\" condition=\"overlay && bg.type !== 'color'\">\n    </mbr-parameters>\n    <!-- End block parameters -->\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container align-left\">\n        <div class=\"media-container-column mbr-white col-md-12\">\n            <h3 class=\"mbr-section-subtitle py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\">\n                Venus Poster</h3>\n            <h1 class=\"mbr-section-title py-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title, .mbr-section-btn\">\n                Create awesome <b>mobile-friendly</b> websites! No coding and <b>free</b>.\n            </h1>\n            <p class=\"mbr-text py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\">\n                This composition, featuring a women’s silhouette colored with the surface of Venus and appearing to hold a planet in one hand, was created with the objective purpose of promoting an event centered around the planet Venus. It was made to emphasis space in the style of a gig poster.  \n            </p>\n            <div class=\"mbr-section-btn py-4\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\" mbr-buttons mbr-theme-style=\"display-4\">\n                    <a class=\"btn btn-md btn-primary\" href=\"https://mobirise.com\">LEARN MORE</a>\n                    <a class=\"btn btn-md btn-white-outline\" href=\"https://mobirise.com\">LIVE DEMO</a>\n            </div>\n        </div>\n    </div>\n\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_anchor": "header11-d",
          "_isUserblock": true,
          "_sourceTheme": "mobirise4",
          "_cid": "qTJZ3CPXO4",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background": "linear-gradient(45deg, @bg-value, @color2)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "font-style": "italic",
              "letter-spacing": "1rem"
            }
          },
          "_name": "header11",
          "_customHTML": "<section class=\"header11\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen, 'mbr-parallax-background': bg.parallax}\">\n\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n    <mbr-parameters>\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n        <input type=\"checkbox\" title=\"Show text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#7ff6fb\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"color\" title=\"Color 2\" name=\"color2\" value=\"#002db3\">\n\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#000000\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.2\" condition=\"overlay && bg.type !== 'color'\">\n    </mbr-parameters>\n    <!-- End block parameters -->\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container align-left\">\n        <div class=\"media-container-column mbr-white col-md-12\">\n            <h3 class=\"mbr-section-subtitle py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\">\n                Puffinland Kronar</h3>\n            <h1 class=\"mbr-section-title py-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title, .mbr-section-btn\">\n                Create awesome <b>mobile-friendly</b> websites! No coding and <b>free</b>.\n            </h1>\n            <p class=\"mbr-text py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\">\n                Created in less than two hours in a Design Challenge, this composition is the fictional currency of a country inhabited entirely by Puffins. The clean, cool look of the bill provides an interesting contrast to the whimsical nature of the design concept. \n            </p>\n            <div class=\"mbr-section-btn py-4\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\" mbr-buttons mbr-theme-style=\"display-4\">\n                    <a class=\"btn btn-md btn-primary\" href=\"https://mobirise.com\">LEARN MORE</a>\n                    <a class=\"btn btn-md btn-white-outline\" href=\"https://mobirise.com\">LIVE DEMO</a>\n            </div>\n        </div>\n    </div>\n\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_anchor": "header11-f",
          "_isUserblock": true,
          "_sourceTheme": "mobirise4",
          "_cid": "qTJZ4vyDwD",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background": "linear-gradient(45deg, @bg-value, @color2)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "font-style": "italic",
              "letter-spacing": "1rem"
            }
          },
          "_name": "header11",
          "_customHTML": "<section class=\"header11\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen, 'mbr-parallax-background': bg.parallax}\">\n\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n    <mbr-parameters>\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n        <input type=\"checkbox\" title=\"Show text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#292929\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"color\" title=\"Color 2\" name=\"color2\" value=\"#893927\">\n\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#000000\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.2\" condition=\"overlay && bg.type !== 'color'\">\n    </mbr-parameters>\n    <!-- End block parameters -->\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container align-left\">\n        <div class=\"media-container-column mbr-white col-md-12\">\n            <h3 class=\"mbr-section-subtitle py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\">\n                Camera Girl</h3>\n            <h1 class=\"mbr-section-title py-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title, .mbr-section-btn\">\n                Create awesome <b>mobile-friendly</b> websites! No coding and <b>free</b>.\n            </h1>\n            <p class=\"mbr-text py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\">\n                In this project the goal was to create something a little different than my usual body of work, but also something that was consistent with my personal style. This woman with a camera for a head, a metaphor for how people live on autopilot, is the result. The lanterns were help provide interest and give the piece a more layered, complex tone. \n            </p>\n            <div class=\"mbr-section-btn py-4\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\" mbr-buttons mbr-theme-style=\"display-4\">\n                    <a class=\"btn btn-md btn-primary\" href=\"https://mobirise.com\">LEARN MORE</a>\n                    <a class=\"btn btn-md btn-white-outline\" href=\"https://mobirise.com\">LIVE DEMO</a>\n            </div>\n        </div>\n    </div>\n\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_anchor": "header11-e",
          "_isUserblock": true,
          "_sourceTheme": "mobirise4",
          "_cid": "qTJZ44I1Cc",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background": "linear-gradient(45deg, @bg-value, @color2)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "font-style": "italic",
              "letter-spacing": "1rem"
            }
          },
          "_name": "header11",
          "_customHTML": "<section class=\"header11\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen, 'mbr-parallax-background': bg.parallax}\">\n\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n    <mbr-parameters>\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\">\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\">\n        <input type=\"checkbox\" title=\"Show text\" name=\"showText\">\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#12033a\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"color\" title=\"Color 2\" name=\"color2\" value=\"#1e065e\">\n\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#000000\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.2\" condition=\"overlay && bg.type !== 'color'\">\n    </mbr-parameters>\n    <!-- End block parameters -->\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container align-left\">\n        <div class=\"media-container-column mbr-white col-md-12\">\n            <h3 class=\"mbr-section-subtitle py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\">\n                Rhythms</h3>\n            <h1 class=\"mbr-section-title py-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title, .mbr-section-btn\">\n                Create awesome <b>mobile-friendly</b> websites! No coding and <b>free</b>.\n            </h1>\n            <p class=\"mbr-text py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\"></p>\n            <div class=\"mbr-section-btn py-4\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\" mbr-buttons mbr-theme-style=\"display-5\"><a class=\"btn btn-md btn-primary\" href=\"index.html\" data-app-placeholder=\"Type Text\">Return to Home</a></div>\n        </div>\n    </div>\n\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_anchor": "header11-u",
          "_isUserblock": true,
          "_sourceTheme": "mobirise4",
          "_cid": "qTK3qyR3gh",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        }
      ]
    },
    "page4.html": {
      "settings": {
        "meta_descr": "Web Builder Description",
        "title": "DESIGN 101 GALLERY",
        "order": 3
      },
      "components": [
        {
          "_styles": {
            "padding-top": "(@paddingTop * 15px)",
            "padding-bottom": "(@paddingBottom * 15px)",
            "background-color": "@bgColor",
            ".mbr-slider .carousel-control": {
              "background": "#1b1b1b"
            },
            ".mbr-slider .carousel-control-prev": {
              "left": "0",
              "margin-left": "2.5rem"
            },
            ".mbr-slider .carousel-control-next": {
              "right": "0",
              "margin-right": "2.5rem"
            },
            ".mbr-slider .modal-body .close": {
              "background": "#1b1b1b"
            },
            ".mbr-gallery-item > div::before": {
              "content": "''",
              "position": "absolute",
              "left": "0",
              "top": "0",
              "width": "100%",
              "height": "100%",
              "background": "@overlayColor",
              "& when (@gradOverlay)": {
                "background": "linear-gradient(to left, @overlayColor, @overlayColor2) !important"
              },
              "opacity": "0",
              "-webkit-transition": "0.2s opacity ease-in-out",
              "transition": "0.2s opacity ease-in-out"
            },
            ".mbr-gallery-item > div:hover": {
              ".mbr-gallery-title::before": {
                "background": "transparent !important"
              },
              "&:before": {
                "opacity": "@overlayOpacity !important"
              }
            },
            ".mbr-gallery-title": {
              "font-size": ".9em",
              "position": "absolute",
              "display": "block",
              "width": "100%",
              "bottom": "0",
              "padding": "1rem",
              "color": "#fff",
              "z-index": "2",
              "&:before": {
                "content": "\" \"",
                "width": "100%",
                "height": "100%",
                "top": "0",
                "left": "0",
                "z-index": "-1",
                "position": "absolute",
                "background": "@overlayColor !important",
                "& when (@gradOverlay)": {
                  "background": "linear-gradient(to left, @overlayColor, @overlayColor2) !important"
                },
                "opacity": "@overlayOpacity",
                "-webkit-transition": "0.2s background ease-in-out",
                "transition": "0.2s background ease-in-out"
              }
            }
          },
          "_name": "gallery2",
          "_customHTML": "<section class=\"mbr-gallery mbr-slider-carousel\" group=\"Sliders & Gallery\" plugins=\"Masonry,BootstrapCarouselSwipe,Gallery,VimeoPlayer,SliderVideo\">\n\n    <mbr-parameters>\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n        <input type=\"checkbox\" title=\"Full Width\" name=\"fullWidth\">\n        <input type=\"range\" title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"9\" step=\"1\" value=\"9\" inline>\n        <input type=\"range\" title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"9\" step=\"1\" value=\"9\" inline>\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#232323\">\n        <input type=\"checkbox\" title=\"Gradient Overlay\" name=\"gradOverlay\" checked>\n        <input type=\"color\" title=\"Overlay Color 2\" name=\"overlayColor2\" value=\"#45505b\" condition=\"gradOverlay\">\n        <input type=\"range\" title=\"Overlay Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.6\" inline>\n        <input type=\"color\" title=\"Background Color\" name=\"bgColor\" value=\"#12033a\">\n\n        <input type=\"gallery\" title=\"Gallery\" name=\"gallery\">\n    <!-- End block parameters -->\n    </mbr-parameters>\n\n    <div mbr-class=\"{'container': !fullWidth}\">\n        <div mbr-gallery=\"gallery\" mbr-gallery-spacing=\"2\" mbr-gallery-show-text></div>\n    </div>\n\n</section>",
          "_cid": "qTK1bz2eFc",
          "_protectedParams": [
            "text_all",
            "gallery__filtersTextStyle",
            "gallery__filtersBtnStyle",
            "gallery"
          ],
          "_global": false,
          "_once": false,
          "_params": {
            "text_all": "All",
            "gallery__filtersTextStyle": "display-2",
            "gallery__filtersBtnStyle": "btn-primary",
            "gallery": [
              {
                "tags": "Animated",
                "videoPreview": "@THEME_PATH@/components/_images/gallery/preview.jpg",
                "playVideo": false,
                "videoUrl": "https://www.youtube.com/watch?v=fwkKc6M60-0",
                "image": "@PROJECT_PATH@/assets/images/nighttrees-500x700.jpg",
                "thumb": "@PROJECT_PATH@/assets/images/nighttrees-500x700-500x700.jpg",
                "alt": "",
                "title": "",
                "customStyle1": "display-5",
                "caption": "Night Trees",
                "active": true
              },
              {
                "tags": "Animated",
                "videoPreview": "@THEME_PATH@/components/_images/gallery/preview.jpg",
                "playVideo": false,
                "videoUrl": "https://www.youtube.com/watch?v=fwkKc6M60-0",
                "image": "@PROJECT_PATH@/assets/images/sharkshape-500x500.jpg",
                "thumb": "@PROJECT_PATH@/assets/images/sharkshape-500x500-500x500.jpg",
                "alt": "",
                "title": "",
                "customStyle1": "display-5",
                "caption": "Sharks",
                "active": false
              },
              {
                "tags": "Animated",
                "videoPreview": "@THEME_PATH@/components/_images/gallery/preview.jpg",
                "playVideo": false,
                "videoUrl": "https://www.youtube.com/watch?v=fwkKc6M60-0",
                "image": "@PROJECT_PATH@/assets/images/valueboi-500x625.jpg",
                "thumb": "@PROJECT_PATH@/assets/images/valueboi-500x625-500x625.jpg",
                "alt": "",
                "title": "",
                "customStyle1": "display-5",
                "caption": "Chess Champ",
                "active": false
              }
            ]
          },
          "_anchor": "gallery2-o"
        },
        {
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background": "linear-gradient(45deg, @bg-value, @color2)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "font-style": "italic",
              "letter-spacing": "1rem"
            }
          },
          "_name": "header11",
          "_customHTML": "<section class=\"header11\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen, 'mbr-parallax-background': bg.parallax}\">\n\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n    <mbr-parameters>\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n        <input type=\"checkbox\" title=\"Show text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#03011b\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"color\" title=\"Color 2\" name=\"color2\" value=\"#76719f\">\n\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#000000\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.2\" condition=\"overlay && bg.type !== 'color'\">\n    </mbr-parameters>\n    <!-- End block parameters -->\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container align-left\">\n        <div class=\"media-container-column mbr-white col-md-12\">\n            <h3 class=\"mbr-section-subtitle py-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubtitle\">\n                Night Trees</h3>\n            <h1 class=\"mbr-section-title py-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title, .mbr-section-btn\">\n                Create awesome <b>mobile-friendly</b> websites! No coding and <b>free</b>.\n            </h1>\n            <p class=\"mbr-text py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\">\n                This piece of trees lining a road at night was meant to demonstrate the element of design of space. However, although its sense of space is quite noticeable, it is drastically outshined by this compositions powerful atmosphere.\n            </p>\n            <div class=\"mbr-section-btn py-4\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\" mbr-buttons mbr-theme-style=\"display-4\">\n                    <a class=\"btn btn-md btn-primary\" href=\"https://mobirise.com\">LEARN MORE</a>\n                    <a class=\"btn btn-md btn-white-outline\" href=\"https://mobirise.com\">LIVE DEMO</a>\n            </div>\n        </div>\n    </div>\n\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_cid": "qTK1bztGrv",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {},
          "_anchor": "header11-p"
        },
        {
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background": "linear-gradient(45deg, @bg-value, @color2)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "font-style": "italic",
              "letter-spacing": "1rem"
            }
          },
          "_name": "header11",
          "_customHTML": "<section class=\"header11\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen, 'mbr-parallax-background': bg.parallax}\">\n\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n    <mbr-parameters>\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n        <input type=\"checkbox\" title=\"Show text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#292929\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"color\" title=\"Color 2\" name=\"color2\" value=\"#000000\">\n\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#000000\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.2\" condition=\"overlay && bg.type !== 'color'\">\n    </mbr-parameters>\n    <!-- End block parameters -->\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container align-left\">\n        <div class=\"media-container-column mbr-white col-md-12\">\n            <h3 class=\"mbr-section-subtitle py-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubtitle\">\n                Sharks</h3>\n            <h1 class=\"mbr-section-title py-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title, .mbr-section-btn\">\n                Create awesome <b>mobile-friendly</b> websites! No coding and <b>free</b>.\n            </h1>\n            <p class=\"mbr-text py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\">\n                This piece is a playful composition featuring some sharks, made to serve as an example of shape. The black and white design helps viewers to focus on the shape of each creature, as well as on shape created in the negative space.\n            </p>\n            <div class=\"mbr-section-btn py-4\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\" mbr-buttons mbr-theme-style=\"display-4\">\n                    <a class=\"btn btn-md btn-primary\" href=\"https://mobirise.com\">LEARN MORE</a>\n                    <a class=\"btn btn-md btn-white-outline\" href=\"https://mobirise.com\">LIVE DEMO</a>\n            </div>\n        </div>\n    </div>\n\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_cid": "qTK1bzSgPI",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {},
          "_anchor": "header11-q"
        },
        {
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background": "linear-gradient(45deg, @bg-value, @color2)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "font-style": "italic",
              "letter-spacing": "1rem"
            }
          },
          "_name": "header11",
          "_customHTML": "<section class=\"header11\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen, 'mbr-parallax-background': bg.parallax}\">\n\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n    <mbr-parameters>\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n        <input type=\"checkbox\" title=\"Show text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\">\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"../_images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#000000\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"color\" title=\"Color 2\" name=\"color2\" value=\"#ffffff\">\n\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#000000\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.2\" condition=\"overlay && bg.type !== 'color'\">\n    </mbr-parameters>\n    <!-- End block parameters -->\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container align-left\">\n        <div class=\"media-container-column mbr-white col-md-12\">\n            <h3 class=\"mbr-section-subtitle py-3 mbr-fonts-style\" mbr-theme-style=\"display-2\" mbr-if=\"showSubtitle\">\n                Chess Camp</h3>\n            <h1 class=\"mbr-section-title py-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title, .mbr-section-btn\">\n                Create awesome <b>mobile-friendly</b> websites! No coding and <b>free</b>.\n            </h1>\n            <p class=\"mbr-text py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\">\n                In this composition, I wanted to focus on value. This composition, featuring a woman playing chess has a sense of value that not only directs the viewer's attention, but also conveys the tone of the piece. \n            </p>\n            <div class=\"mbr-section-btn py-4\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\" mbr-buttons mbr-theme-style=\"display-4\">\n                    <a class=\"btn btn-md btn-primary\" href=\"https://mobirise.com\">LEARN MORE</a>\n                    <a class=\"btn btn-md btn-white-outline\" href=\"https://mobirise.com\">LIVE DEMO</a>\n            </div>\n        </div>\n    </div>\n\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_cid": "qTK1bAlf5m",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {},
          "_anchor": "header11-r"
        },
        {
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background": "linear-gradient(45deg, @bg-value, @color2)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "font-style": "italic",
              "letter-spacing": "1rem"
            }
          },
          "_name": "header11",
          "_customHTML": "<section class=\"header11\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen, 'mbr-parallax-background': bg.parallax}\">\n\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n    <mbr-parameters>\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\">\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\">\n        <input type=\"checkbox\" title=\"Show text\" name=\"showText\">\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#12033a\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"color\" title=\"Color 2\" name=\"color2\" value=\"#1e065e\">\n\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#000000\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.2\" condition=\"overlay && bg.type !== 'color'\">\n    </mbr-parameters>\n    <!-- End block parameters -->\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container align-left\">\n        <div class=\"media-container-column mbr-white col-md-12\">\n            <h3 class=\"mbr-section-subtitle py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\">\n                Rhythms</h3>\n            <h1 class=\"mbr-section-title py-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title, .mbr-section-btn\">\n                Create awesome <b>mobile-friendly</b> websites! No coding and <b>free</b>.\n            </h1>\n            <p class=\"mbr-text py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\"></p>\n            <div class=\"mbr-section-btn py-4\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\" mbr-buttons mbr-theme-style=\"display-5\"><a class=\"btn btn-md btn-primary\" href=\"index.html\" data-app-placeholder=\"Type Text\">Return to Home</a></div>\n        </div>\n    </div>\n\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_anchor": "header11-t",
          "_isUserblock": true,
          "_sourceTheme": "mobirise4",
          "_cid": "qTK3npq0jB",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        }
      ]
    },
    "page5.html": {
      "settings": {
        "meta_descr": "Web Page Generator Description",
        "title": "Contact",
        "order": 1
      },
      "components": [
        {
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background": "linear-gradient(45deg, @bg-value, @color2)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "font-style": "italic",
              "letter-spacing": "1rem"
            }
          },
          "_name": "header11",
          "_customHTML": "<section class=\"header11\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen, 'mbr-parallax-background': bg.parallax}\">\n\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n    <mbr-parameters>\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\" checked>\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\" checked>\n        <input type=\"checkbox\" title=\"Show text\" name=\"showText\" checked>\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#0a021e\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"color\" title=\"Color 2\" name=\"color2\" value=\"#1e065e\">\n\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#000000\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.2\" condition=\"overlay && bg.type !== 'color'\">\n    </mbr-parameters>\n    <!-- End block parameters -->\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container align-left\">\n        <div class=\"media-container-column mbr-white col-md-12\">\n            <h3 class=\"mbr-section-subtitle py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\">Contact Isabella</h3>\n            <h1 class=\"mbr-section-title py-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title, .mbr-section-btn\">\n                Create awesome <b>mobile-friendly</b> websites! No coding and <b>free</b>.\n            </h1>\n            <p class=\"mbr-text py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\">Isabella is a student of Photoshop, Animation, and Promgramming at LCC. To contact her further see the links below.</p>\n            <div class=\"mbr-section-btn py-4\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\" mbr-buttons mbr-theme-style=\"display-4\"><a class=\"btn btn-md btn-primary\" href=\"https://www.linkedin.com/in/isabella-briseno-01565b15b/\" data-app-placeholder=\"Type Text\">Linkedin Account</a> <a class=\"btn btn-md btn-primary\" href=\"mailto:Briseni42@gmail.com\" data-app-placeholder=\"Type Text\">Briseni42@gmal.com</a></div>\n        </div>\n    </div>\n\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_anchor": "header11-x",
          "_isUserblock": true,
          "_sourceTheme": "mobirise4",
          "_cid": "qTK41A3IXW",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        },
        {
          "_styles": {
            "& when not (@fullScreen)": {
              "padding-top": "(@paddingTop * 15px)",
              "padding-bottom": "(@paddingBottom * 15px)"
            },
            "& when (@bg-type = 'color')": {
              "background": "linear-gradient(45deg, @bg-value, @color2)"
            },
            "& when (@bg-type = 'image')": {
              "background-image": "url(@bg-value)"
            },
            ".mbr-section-subtitle": {
              "font-style": "italic",
              "letter-spacing": "1rem"
            }
          },
          "_name": "header11",
          "_customHTML": "<section class=\"header11\" group=\"Headers\" data-bg-video=\"{{bg.type == 'video' && bg.value.url}}\" mbr-class=\"{'mbr-fullscreen': fullScreen, 'mbr-parallax-background': bg.parallax}\">\n\n    <!-- Block parameters controls (Blue \"Gear\" panel) -->\n    <mbr-parameters>\n        <input type=\"checkbox\" title=\"Full Screen\" name=\"fullScreen\">\n        <input type=\"range\" inline title=\"Top\" name=\"paddingTop\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n        <input type=\"range\" inline title=\"Bottom\" name=\"paddingBottom\" min=\"0\" max=\"8\" step=\"1\" value=\"6\" condition=\"fullScreen == false\">\n\n        <input type=\"checkbox\" title=\"Show Arrow\" name=\"showArrow\">\n        <input type=\"checkbox\" title=\"Show Title\" name=\"showTitle\">\n        <input type=\"checkbox\" title=\"Show Subtitle\" name=\"showSubtitle\">\n        <input type=\"checkbox\" title=\"Show text\" name=\"showText\">\n        <input type=\"checkbox\" title=\"Show Buttons\" name=\"showButtons\" checked>\n\n        <fieldset type=\"background\" name=\"bg\" parallax>\n            <input type=\"image\" title=\"Background Image\" value=\"@PROJECT_PATH@/assets/images/background4.jpg\" parallax>\n            <input type=\"color\" title=\"Background Color\" value=\"#0a021e\" selected>\n            <input type=\"video\" title=\"Background Video\" value=\"http://www.youtube.com/watch?v=uNCr7NdOJgw\">\n        </fieldset>\n        <input type=\"color\" title=\"Color 2\" name=\"color2\" value=\"#0a021e\">\n\n        <input type=\"checkbox\" title=\"Overlay\" name=\"overlay\" condition=\"bg.type !== 'color'\">\n        <input type=\"color\" title=\"Overlay Color\" name=\"overlayColor\" value=\"#000000\" condition=\"overlay && bg.type !== 'color'\">\n        <input type=\"range\" inline title=\"Opacity\" name=\"overlayOpacity\" min=\"0\" max=\"1\" step=\"0.1\" value=\"0.2\" condition=\"overlay && bg.type !== 'color'\">\n    </mbr-parameters>\n    <!-- End block parameters -->\n\n    <div class=\"mbr-overlay\" mbr-if=\"overlay && bg.type!== 'color'\" mbr-style=\"{'opacity': overlayOpacity, 'background-color': overlayColor}\">\n    </div>\n    <div class=\"container align-left\">\n        <div class=\"media-container-column mbr-white col-md-12\">\n            <h3 class=\"mbr-section-subtitle py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showSubtitle\">\n                Rhythms</h3>\n            <h1 class=\"mbr-section-title py-3 mbr-fonts-style\" mbr-theme-style=\"display-1\" mbr-if=\"showTitle\" data-app-selector=\".mbr-section-title, .mbr-section-btn\">\n                Create awesome <b>mobile-friendly</b> websites! No coding and <b>free</b>.\n            </h1>\n            <p class=\"mbr-text py-3 mbr-fonts-style\" mbr-theme-style=\"display-5\" mbr-if=\"showText\"></p>\n            <div class=\"mbr-section-btn py-4\" mbr-if=\"showButtons\" data-toolbar=\"-mbrBtnMove\" mbr-buttons mbr-theme-style=\"display-4\"><a class=\"btn btn-md btn-primary\" href=\"index.html\" data-app-placeholder=\"Type Text\">Return to Home</a></div>\n        </div>\n    </div>\n\n    <div mbr-if=\"showArrow\" class=\"mbr-arrow hidden-sm-down\" aria-hidden=\"true\">\n        <a href=\"#next\">\n            <i class=\"mbri-down mbr-iconfont\"></i>\n        </a>\n    </div>\n</section>",
          "_anchor": "header11-y",
          "_isUserblock": true,
          "_sourceTheme": "mobirise4",
          "_cid": "qTK571wqux",
          "_protectedParams": [],
          "_global": false,
          "_once": false,
          "_params": {}
        }
      ]
    }
  }
}
