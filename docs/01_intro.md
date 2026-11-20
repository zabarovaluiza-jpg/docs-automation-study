# Введение
Это моя первая автоматизированная документация.
## Цель
- Изучить инструменты автоматизации.
- Навести порядок в файлах.

![scheme](https://github.com/user-attachments/assets/9d884ddb-0611-450e-8f22-0f227c24b158)

<!-- saved from url=(0024)https://plantuml.com/ru/ -->
<html lang="ru"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><script src="https://secure.quantserve.com/quant.js" async="true"></script><script type="text/javascript" async="" src="./scheme_files/client" data-ez-gsi="1"></script><script src="./scheme_files/SDK.js.Без названия" defer=""></script><script>var __ezHttpConsent={setByCat:function(src,tagType,attributes,category,force,customSetScriptFn=null){var setScript=function(){if(force||window.ezTcfConsent[category]){if(typeof customSetScriptFn==='function'){customSetScriptFn();}else{var scriptElement=document.createElement(tagType);scriptElement.src=src;attributes.forEach(function(attr){for(var key in attr){if(attr.hasOwnProperty(key)){scriptElement.setAttribute(key,attr[key]);}}});var firstScript=document.getElementsByTagName(tagType)[0];firstScript.parentNode.insertBefore(scriptElement,firstScript);}}};if(force||(window.ezTcfConsent&&window.ezTcfConsent.loaded)){setScript();}else if(typeof getEzConsentData==="function"){getEzConsentData().then(function(ezTcfConsent){if(ezTcfConsent&&ezTcfConsent.loaded){setScript();}else{console.error("cannot get ez consent data");force=true;setScript();}});}else{force=true;setScript();console.error("getEzConsentData is not a function");}},};</script>
<script>var ezTcfConsent=window.ezTcfConsent?window.ezTcfConsent:{loaded:false,store_info:false,develop_and_improve_services:false,measure_ad_performance:false,measure_content_performance:false,select_basic_ads:false,create_ad_profile:false,select_personalized_ads:false,create_content_profile:false,select_personalized_content:false,understand_audiences:false,use_limited_data_to_select_content:false,};function getEzConsentData(){return new Promise(function(resolve){document.addEventListener("ezConsentEvent",function(event){var ezTcfConsent=event.detail.ezTcfConsent;resolve(ezTcfConsent);});});}</script>
<script>if(typeof _setEzCookies!=='function'){function _setEzCookies(ezConsentData){var cookies=window.ezCookieQueue;for(var i=0;i<cookies.length;i++){var cookie=cookies[i];if(ezConsentData&&ezConsentData.loaded&&ezConsentData[cookie.tcfCategory]){document.cookie=cookie.name+"="+cookie.value;}}}}
window.ezCookieQueue=window.ezCookieQueue||[];if(typeof addEzCookies!=='function'){function addEzCookies(arr){window.ezCookieQueue=[...window.ezCookieQueue,...arr];}}
addEzCookies([{name:"ezfs_173770",value:"2165909046; Path=/; Domain=plantuml.com; Expires=Fri, 20 Nov 2026 16:14:09 UTC",tcfCategory:"store_info",isEzoic:"true",},{name:"ezoab_173770",value:"mod30; Path=/; Domain=plantuml.com; Expires=Fri, 20 Nov 2026 16:14:09 UTC",tcfCategory:"store_info",isEzoic:"true",},{name:"ezopvc_173770",value:"1; Path=/; Domain=plantuml.com; Expires=Fri, 20 Nov 2026 14:44:09 UTC",tcfCategory:"understand_audiences",isEzoic:"true",},{name:"ezoab_173770",value:"mod30; Path=/; Domain=plantuml.com; Max-Age=7200",tcfCategory:"store_info",isEzoic:"true",},{name:"active_template::173770",value:"pub_site.1795184049; Path=/; Domain=plantuml.com; Expires=Sun, 22 Nov 2026 14:14:09 UTC",tcfCategory:"store_info",isEzoic:"true",},{name:"ezoadgid_173770",value:"-1; Path=/; Domain=plantuml.com; Max-Age=1800",tcfCategory:"understand_audiences",isEzoic:"true",},{name:"ezoid",value:"a1d77620-8a07-4287-8f61-d55ca1e851a6; Path=/; Domain=ezoic.net; Max-Age=31536000; SameSite=None; Secure; HttpOnly",tcfCategory:"store_info",isEzoic:"true",},{name:"ezoid",value:"a1d77620-8a07-4287-8f61-d55ca1e851a6; Path=/; Max-Age=31536000; SameSite=None; Secure; HttpOnly",tcfCategory:"store_info",isEzoic:"true",}]);if(window.ezTcfConsent&&window.ezTcfConsent.loaded){_setEzCookies(window.ezTcfConsent);}else if(typeof getEzConsentData==="function"){getEzConsentData().then(function(ezTcfConsent){if(ezTcfConsent&&ezTcfConsent.loaded){_setEzCookies(window.ezTcfConsent);}else{console.error("cannot get ez consent data");_setEzCookies(window.ezTcfConsent);}});}else{console.error("getEzConsentData is not a function");_setEzCookies(window.ezTcfConsent);}</script><script type="text/javascript" data-ezscrex="false" data-cfasync="false">window._ezaq = Object.assign({"edge_cache_status":1,"edge_response_time":26,"url":"https://plantuml.com/ru/"}, typeof window._ezaq !== "undefined" ? window._ezaq : {});</script><script type="text/javascript" data-ezscrex="false" data-cfasync="false">window._ezaq = Object.assign({"ab_test_id":"mod30"}, typeof window._ezaq !== "undefined" ? window._ezaq : {});window.__ez=window.__ez||{};window.__ez.tf={"PrebidScopedClone":"true","lcpm":"false","vosfq":"true","vs2sfe":"true"};window.__ez=window.__ez||{};window.__ez.fs={"ACFloorPlanSplit":"false","ACFloorTSV3PriorsSplit":"true","ACLowRungFloorSplit":"false","ADXHardFloorsSplit":"true","AdaptiveExclusion":"false","AdaptiveExclusionAggressivePage":"false","AdaptiveExclusionRefreshReset":"true","AdaptiveExclusionTimeoutAware":"true","AdaptiveExclusionValueStrip":"false","AdxPageLoad":"sync_delay_10s","AffiliateWidgets":"false","AllowMultipleBigAdsAboveFold":"false","Anchor728AltSizesSplit":"false","AnchorAltSizesSplit":"false","AnchorExpansionBanditSplit":"true","AnchorTallMobileSplit":"false","ArticleNavRewardedBar":"false","AtfAltSizesSplit":"false","AuctionSpacingOff":"true","BsRetryAtBid":"default","CenteredAds":"false","CpmHierarchyExtraLevel":"false","CpmHierarchyPageLevel":"true","DealOnlyExclusivitySplit":"true","DirectRenderBanditSplit":"true","DirectRenderDoseSplit":"off","DirectRenderFloormultGridSplit":"grid8","DirectRenderFloormultHoldoutSplit":"off","DirectRenderLowGridSplit":"off","DirectRenderPt4ThresholdSplit":"off","DirectRenderRefreshOff":"false","DirectRenderThresholdGreedySplit":"false","DirectRenderTierAHighSplit":"a080","DirectRenderTierASplit":"default","DurationBanditV2RewardSplit":"noleak","EidSourcesV1":"default","EidStrip":"default","EscalationAllCountries":"true","EscalationDownround":"false","EscalationEarlyGam":"true","EscalationHighFloorDownround":"false","EscalationLowFloorGate":"true","EscalationMidFloorDownround":"true","EscalationNoWalk":"false","EscalationS2sBannerFloormin":"false","EscalationS2sLowFloor":"true","EscalationS2sMidFloor":"true","EscalationS2sNoLadderFloor":"true","EscalationTridentAdapters":"true","EscalationUpwalkMap2":"true","FloatingBanditChallenger":"true","FloatingBanditWindow":"true","FloatingInterstitialBanditSplit":"true","FloatingLadderBottomOff":"true","FloorBanditChallengerSplit":"challenger","FloorBanditGreedySplit":"true","FloorBanditGroupLevelSplit":"false","FloorBanditSplit":"true","FloorEscalation":"false","FloorPlanSplit":"false","FlyingCarpet":"false","GamAltSizesSplit":"false","HbFloorBanditDeliver":"true","HbFloorBanditGreedySplit":"false","HbFloorBanditKeepAllSplit":"true","HbFloorBanditSplit":"false","HbFloorBanditTrainSplit":"true","HbFloorSignalOnlySplit":"false","HbFloorSignalScale":"0.5","HbFloorZeroSplit":"false","InterstitialLatePrebidRecovery":"recover","LazyloadArm27vs19":"rest","LazyloadBanditSplit":"true","LazyloadCashReward":"false","LazyloadRetryViewport":"base","LazyloadSendDistance":"base","MonopolyReserveFloorSplit":"false","OfferwallTriggerBanditSplit":"true","OutstreamAspectBanditV3Split":"control","OutstreamBidderInclusionCurve":"aggressive","OutstreamBidderInclusionSplit":"true","OutstreamErrorRetryV1":"false","OutstreamPoolScopeFixV1":"false","OutstreamPub1MaxSize":"false","OutstreamReserveBanditSplit":"true","OutstreamReserveCAPinSplit":"true","OutstreamReserveFRDesktopPinSplit":"true","OutstreamReserveGridExtV1":"true","OutstreamReserveUSDesktopPinSplit":"false","OutstreamTSV3Split":"false","OutstreamWideEligibilityV1":"false","PoolAuctionLockDomain":"false","PrebidScopedCloneSplit":"true","RefreshDisplayLadderBottomOff":"false","RefreshFloorAllCycleMult":"2","RefreshFloorBanditSplit":"true","RefreshFloorFirstCycleDefault":"true","RefreshFloorTimerCap30":"false","RefreshFloorTimerMult":"1","RewardedDisplaySize":"320x560","RewardedLazyVideoStackSplit":"true","RewardedMultiplierGateSplit":"legacy","S2SFloorEnforceSplit":"true","S2SSingleFloorSplit":"true","SaStorageConsentGate":"false","SizeBanditGreedySplit":"false","SizeBanditMergeRestore":"true","SizeBanditRestoreFitOnly":"true","SizeBanditSplit":"true","SlotMachineAuctions":"false","SyncFrequencyCap":"false","SyncSpacing":"false","TSFloorCapSplit":"none","TimeoutBanditRecentMeanSplit":"false","TimeoutBanditSplit":"true","TimeoutBelowFoldHoldSplit":"false","TimeoutCapExtend":"true","TimeoutRefreshLeadSplit":"false","TimeoutS2SFollowSplit":"false","TimeoutS2SLaneKeepSplit":"false","TimeoutShortArmsSplit":"false","VideoACLifecycleTelemetrySplit":"off","VideoStackLazy":"false","WpBridge":"true"};window.__ez.fss='2165909046';</script><script type="text/javascript" data-ezscrex="false" data-cfasync="false">window.ezDisableAds = true;</script>
<script data-ezscrex="false" data-cfasync="false" data-pagespeed-no-defer="">var __ez=__ez||{};__ez.stms=Date.now();__ez.evt={};__ez.script={};__ez.ck=__ez.ck||{};__ez.template={};__ez.template.isOrig=false;window.__ezScriptHost="//www.ezojs.com";__ez.queue=__ez.queue||function(){var e=0,i=0,t=[],n=!1,o=[],r=[],s=!0,a=function(e,i,n,o,r,s,a){var l=arguments.length>7&&void 0!==arguments[7]?arguments[7]:window,d=this;this.name=e,this.funcName=i,this.parameters=null===n?null:w(n)?n:[n],this.isBlock=o,this.blockedBy=r,this.deleteWhenComplete=s,this.isError=!1,this.isComplete=!1,this.isInitialized=!1,this.proceedIfError=a,this.fWindow=l,this.isTimeDelay=!1,this.process=function(){f("... func = "+e),d.isInitialized=!0,d.isComplete=!0,f("... func.apply: "+e);var i=d.funcName.split("."),n=null,o=this.fWindow||window;i.length>3||(n=3===i.length?o[i[0]][i[1]][i[2]]:2===i.length?o[i[0]][i[1]]:o[d.funcName]),null!=n&&n.apply(null,this.parameters),!0===d.deleteWhenComplete&&delete t[e],!0===d.isBlock&&(f("----- F'D: "+d.name),p())}},l=function(e,i,t,n,o,r,s){var a=arguments.length>7&&void 0!==arguments[7]?arguments[7]:window,l=this;this.name=e,this.path=i,this.async=o,this.defer=r,this.isBlock=t,this.blockedBy=n,this.isInitialized=!1,this.isError=!1,this.isComplete=!1,this.proceedIfError=s,this.fWindow=a,this.isTimeDelay=!1,this.isPath=function(e){return"/"===e[0]&&"/"!==e[1]},this.getSrc=function(e){return void 0!==window.__ezScriptHost&&this.isPath(e)?window.__ezScriptHost+e:e},this.process=function(){l.isInitialized=!0,f("... file = "+e);var i=this.fWindow?this.fWindow.document:document,t=i.createElement("script");t.src=this.getSrc(this.path),!0===o?t.async=!0:!0===r&&(t.defer=!0),t.onerror=function(){var e={url:window.location.href,name:l.name,path:l.path,user_agent:window.navigator.userAgent};"undefined"!=typeof _ezaq&&(e.pageview_id=_ezaq.page_view_id);var i=encodeURIComponent(JSON.stringify(e)),t=new XMLHttpRequest;t.open("GET","//g.ezoic.net/ezqlog?d="+i,!0),t.send(),f("----- ERR'D: "+l.name),l.isError=!0,!0===l.isBlock&&p()},t.onreadystatechange=t.onload=function(){var e=t.readyState;f("----- F'D: "+l.name),e&&!/loaded|complete/.test(e)||(l.isComplete=!0,!0===l.isBlock&&p())},i.getElementsByTagName("head")[0].appendChild(t)}},d=function(e,i){this.name=e,this.path="",this.async=!1,this.defer=!1,this.isBlock=!1,this.blockedBy=[],this.isInitialized=!0,this.isError=!1,this.isComplete=i,this.proceedIfError=!1,this.isTimeDelay=!1,this.process=function(){}};function c(e,i,n,s,a,d,c,u,f){var p=new l(e,i,n,s,a,d,c,f);!0===u?o[e]=p:r[e]=p,t[e]=p,h(p)}function h(e){!0!==u(e)&&0!=s&&e.process()}function u(e){if(!0===e.isTimeDelay&&!1===n)return f(e.name+" blocked = TIME DELAY!"),!0;if(w(e.blockedBy))for(var i=0;i<e.blockedBy.length;i++){var o=e.blockedBy[i];if(!1===t.hasOwnProperty(o))return f(e.name+" blocked = "+o),!0;if(!0===e.proceedIfError&&!0===t[o].isError)return!1;if(!1===t[o].isComplete)return f(e.name+" blocked = "+o),!0}return!1}function f(e){var i=window.location.href,t=new RegExp("[?&]ezq=([^&#]*)","i").exec(i);"1"===(t?t[1]:null)&&console.debug(e)}function p(){++e>200||(f("let's go"),m(o),m(r))}function m(e){for(var i in e)if(!1!==e.hasOwnProperty(i)){var t=e[i];!0===t.isComplete||u(t)||!0===t.isInitialized||!0===t.isError?!0===t.isError?f(t.name+": error"):!0===t.isComplete?f(t.name+": complete already"):!0===t.isInitialized&&f(t.name+": initialized already"):t.process()}}function w(e){return"[object Array]"==Object.prototype.toString.call(e)}return window.addEventListener("load",(function(){setTimeout((function(){n=!0,f("TDELAY -----"),p()}),5e3)}),!1),{addFile:c,addFileOnce:function(e,i,n,o,r,s,a,l,d){t[e]||c(e,i,n,o,r,s,a,l,d)},addDelayFile:function(e,i){var n=new l(e,i,!1,[],!1,!1,!0);n.isTimeDelay=!0,f(e+" ...  FILE! TDELAY"),r[e]=n,t[e]=n,h(n)},addFunc:function(e,n,s,l,d,c,u,f,p,m){!0===c&&(e=e+"_"+i++);var w=new a(e,n,s,l,d,u,f,m);!0===p?o[e]=w:r[e]=w,t[e]=w,h(w)},addDelayFunc:function(e,i,n){var o=new a(e,i,n,!1,[],!0,!0);o.isTimeDelay=!0,f(e+" ...  FUNCTION! TDELAY"),r[e]=o,t[e]=o,h(o)},items:t,processAll:p,setallowLoad:function(e){s=e},isLoadAllowed:function(){return!1!==s},markLoaded:function(e){if(e&&0!==e.length){if(e in t){var i=t[e];!0===i.isComplete?f(i.name+" "+e+": error loaded duplicate"):(i.isComplete=!0,i.isInitialized=!0)}else t[e]=new d(e,!0);f("markLoaded dummyfile: "+t[e].name)}},logWhatsBlocked:function(){for(var e in t)!1!==t.hasOwnProperty(e)&&u(t[e])}}}();__ez.evt.add=function(e,t,n){e.addEventListener?e.addEventListener(t,n,!1):e.attachEvent?e.attachEvent("on"+t,n):e["on"+t]=n()},__ez.evt.remove=function(e,t,n){e.removeEventListener?e.removeEventListener(t,n,!1):e.detachEvent?e.detachEvent("on"+t,n):delete e["on"+t]};__ez.script.add=function(e){var t=document.createElement("script");t.src=e,t.async=!0,t.type="text/javascript",document.getElementsByTagName("head")[0].appendChild(t)};__ez.dot=__ez.dot||{};__ez.queue.addFileOnce('/detroitchicago/boise.js', '/detroitchicago/boise.js?gcb=195-5&cb=5', true, [], true, false, true, false);__ez.queue.addFileOnce('/parsonsmaize/abilene.js', '/parsonsmaize/abilene.js?gcb=195-5&cb=50624fad95', true, [], true, false, true, false);__ez.queue.addFileOnce('/parsonsmaize/mulvane.js', '/parsonsmaize/mulvane.js?gcb=195-5&cb=e75e48eec0', true, ['/parsonsmaize/abilene.js'], true, false, true, false);__ez.queue.addFileOnce('/detroitchicago/birmingham.js', '/detroitchicago/birmingham.js?gcb=195-5&cb=c4ed651ab8', true, ['/parsonsmaize/abilene.js'], true, false, true, false);</script><script src="./scheme_files/boise.js.Без названия" async=""></script><script src="./scheme_files/abilene.js.Без названия" async=""></script>
<script data-ezscrex="false" type="text/javascript" data-cfasync="false">window._ezaq = Object.assign({"ad_cache_level":1,"adpicker_placement_cnt":0,"ai_placeholder_cache_level":1,"ai_placeholder_placement_cnt":-1,"domain":"plantuml.com","domain_id":173770,"ezcache_level":2,"ezcache_skip_code":0,"has_bad_image":0,"has_bad_words":0,"is_sitespeed":0,"lt_cache_level":0,"response_size":64922,"response_size_orig":51716,"response_time_orig":3,"template_id":134,"url":"https://plantuml.com/ru/","word_count":781,"worst_bad_word_level":0}, typeof window._ezaq !== "undefined" ? window._ezaq : {});__ez.queue.markLoaded('ezaqBaseReady');if(window._ezaq&&window._ezaq.page_view_id==="01a1f94e-bbc5-7c47-bfd4-6c9ed400afc0"){window.__ezPvSig=window.__ezPvSig||"tot0vl.e1e6ca8e28450dd230070af7b807783a";}</script>
<script type="text/javascript">(function(){function storageAvailable(type){var storage;try{storage=window[type];var x='__storage_test__';storage.setItem(x,x);storage.removeItem(x);return true;}
catch(e){return e instanceof DOMException&&(e.code===22||e.code===1014||e.name==='QuotaExceededError'||e.name==='NS_ERROR_DOM_QUOTA_REACHED')&&(storage&&storage.length!==0);}}
function remove_ama_config(){if(storageAvailable('localStorage')){localStorage.removeItem("google_ama_config");}}
remove_ama_config()})()</script>
<script type="text/javascript">var ezoicTestActive = true</script>
<script type="text/javascript" data-ezscrex="false" data-cfasync="false">
window.ezAnalyticsStatic = true;

function analyticsAddScript(script) {
	var ezDynamic = document.createElement('script');
	ezDynamic.type = 'text/javascript';
	ezDynamic.innerHTML = script;
	document.head.appendChild(ezDynamic);
}
function getCookiesWithPrefix() {
    var allCookies = document.cookie.split(';');
    var cookiesWithPrefix = {};

    for (var i = 0; i < allCookies.length; i++) {
        var cookie = allCookies[i].trim();

        for (var j = 0; j < arguments.length; j++) {
            var prefix = arguments[j];
            if (cookie.indexOf(prefix) === 0) {
                var cookieParts = cookie.split('=');
                var cookieName = cookieParts[0];
                var cookieValue = cookieParts.slice(1).join('=');
                cookiesWithPrefix[cookieName] = decodeURIComponent(cookieValue);
                break; // Once matched, no need to check other prefixes
            }
        }
    }

    return cookiesWithPrefix;
}
function getOrMintFss() {
	var UINT32_MAX = 4294967295;
	var UINT32_DECIMAL = /^\d{1,10}$/;
	function ensureEz() {
		if (!window.__ez || typeof window.__ez !== 'object') {
			window.__ez = {};
		}
		return window.__ez;
	}
	function isValidUint32String(value) {
		if (typeof value !== 'string' || !value) {
			return false;
		}
		if (!UINT32_DECIMAL.test(value)) {
			return false;
		}
		return Number(value) <= UINT32_MAX;
	}
	if (window.__ez && isValidUint32String(window.__ez.fss)) {
		return window.__ez.fss;
	}
	var cookieStr = '';
	try {
		cookieStr = document.cookie;
	} catch (err) {
		cookieStr = '';
	}
	if (cookieStr && typeof cookieStr === 'string') {
		var parts = cookieStr.split(';');
		for (var i = 0; i < parts.length; i++) {
			var part = parts[i];
			var eq = part.indexOf('=');
			if (eq === -1) {
				continue;
			}
			var name = part.slice(0, eq).trim();
			if (name.indexOf('ezfs_') !== 0) {
				continue;
			}
			var raw = part.slice(eq + 1).trim();
			var value;
			try {
				value = decodeURIComponent(raw);
			} catch (err) {
				continue;
			}
			if (!isValidUint32String(value)) {
				continue;
			}
			ensureEz().fss = value;
			return value;
		}
	}
	var seed;
	if (
		typeof crypto !== 'undefined' &&
		typeof crypto.getRandomValues === 'function' &&
		typeof Uint32Array === 'function'
	) {
		seed = crypto.getRandomValues(new Uint32Array(1))[0];
	} else {
		seed = Math.floor(Math.random() * 4294967296);
	}
	var minted = String(seed >>> 0);
	ensureEz().fss = minted;
	return minted;
}
function productAnalytics() {
	var d = {"pr":[6,3,1],"aop":{"14":0,"26":0,"4":134,"7":0},"omd5":"3eba40a737e82f36e25856adfff21ba6","fs_seed":"2165909046"};
	d.u = _ezaq.url;
	d.p = _ezaq.page_view_id;
	d.v = _ezaq.visit_uuid;
	d.ab = _ezaq.ab_test_id;
	d.e = JSON.stringify(_ezaq);
	d.ref = document.referrer;
	d.dw = document.documentElement.clientWidth || window.innerWidth || 0;
	d.dh = window.screen.height || 0;
	d.vpw = window.innerWidth || document.documentElement.clientWidth || 0;
	d.vph = window.innerHeight || document.documentElement.clientHeight || 0;
	d.doch = Math.max((document.body && document.body.scrollHeight) || 0, (document.documentElement && document.documentElement.scrollHeight) || 0, (document.body && document.body.offsetHeight) || 0, (document.documentElement && document.documentElement.offsetHeight) || 0, (document.body && document.body.clientHeight) || 0, (document.documentElement && document.documentElement.clientHeight) || 0);
	d.c = getCookiesWithPrefix('active_template', 'ez', 'lp_');
	if(typeof ez_utmParams !== 'undefined') {
		d.utm = ez_utmParams;
	}
	d.qs = window.location.search;
	if (typeof d.fs_seed === 'string' && d.fs_seed && (!window.__ez || !window.__ez.fss)) {
		if (!window.__ez || typeof window.__ez !== 'object') {
			window.__ez = {};
		}
		window.__ez.fss = d.fs_seed;
	}
	d.fs_seed = getOrMintFss();

	var dataText = JSON.stringify(d);
	var xhr = new XMLHttpRequest();
	xhr.open('POST','/ezais/analytics?cb=1', true);
	xhr.onload = function () {
		if (xhr.status!=200) {
            return;
		}

        if(document.readyState !== 'loading') {
            analyticsAddScript(xhr.response);
            return;
        }

        var eventFunc = function() {
            if(document.readyState === 'loading') {
                return;
            }
            document.removeEventListener('readystatechange', eventFunc, false);
            analyticsAddScript(xhr.response);
        };

        document.addEventListener('readystatechange', eventFunc, false);
	};
	xhr.setRequestHeader('Content-Type','text/plain');
	xhr.send(dataText);
}
__ez.queue.addFunc("productAnalytics", "productAnalytics", null, true, ['ezaqBaseReady'], false, false, false, true);
</script><!--<base href="https://plantuml.com/ru/">--><base href=".">
<meta name="flattr:id" content="1ew3x0">







<script type="application/ld+json">
{
  "@context": "http://schema.org",
  "@type": "Organization",
  "url": "https://plantuml.com",
  "name": "PlantUML",
  "sameAs" : ["https://twitter.com/plantuml","https://en.wikipedia.org/wiki/PlantUML","https://www.wikidata.org/wiki/Q18346546"],
  "logo": "https://cdn-0.plantuml.com/logo3.png",
  "contactPoint": [{
    "@type": "ContactPoint",
    "email": "plantuml@gmail.com",
    "url": "https://plantuml.com",
    "contactType": "customer service"
  }]
}
</script>
<script type="application/ld+json">
{
  "@context": "http://schema.org",
  "@type": "BreadcrumbList",
  "itemListElement": [{
    "@type": "ListItem",
    "position": 1,
    "item": {
      "@id": "https://plantuml.com",
      "name": "Home"
    }
  },{
    "@type": "ListItem",
    "position": 2,
    "item": {
      "@id": "https://plantuml.com/sitemap-news-and-information",
      "name": "News and information"
    }
  },{
    "@type": "ListItem",
    "position": 3,
    "item": {
      "@id": "https://plantuml.com/index",
      "name": "PlantUML in a nutshell"
  }
  }]
}
</script>
<link rel="canonical" href="https://plantuml.com/ru/">
<link rel="alternate" hreflang="x-default" href="https://plantuml.com/">
<link rel="alternate" hreflang="de" href="https://plantuml.com/de/">
<link rel="alternate" hreflang="en" href="https://plantuml.com/">
<link rel="alternate" hreflang="es" href="https://plantuml.com/es/">
<link rel="alternate" hreflang="fr" href="https://plantuml.com/fr/">
<link rel="alternate" hreflang="ja" href="https://plantuml.com/ja/">
<link rel="alternate" hreflang="ko" href="https://plantuml.com/ko/">
<link rel="alternate" hreflang="zh" href="https://plantuml.com/zh/">

<link rel="shortcut icon" href="https://plantuml.com/favicon.ico">

<link rel="preload" as="image" href="./scheme_files/svgrepo-house.svg">
<link rel="preload" as="image" href="./scheme_files/svgrepo-text-news.svg">
<link rel="preload" as="image" href="./scheme_files/svgrepo-rocket-3-start.svg">
<link rel="preload" as="image" href="./scheme_files/svgrepo-server.svg">
<link rel="preload" as="image" href="./scheme_files/svgrepo-play.svg">
<link rel="preload" as="image" href="./scheme_files/svgrepo-forum.svg">
<link rel="preload" as="image" href="./scheme_files/svgrepo-add-to-online-cart.svg">
<link rel="preload" as="image" href="./scheme_files/svgrepo-forum-message.svg">
<link rel="preload" as="image" href="./scheme_files/svgrepo-palette-fill.svg">
<link rel="preload" as="image" href="./scheme_files/svgrepo-cpu.svg">
<link rel="preload" as="image" href="./scheme_files/svgrepo-books-library.svg">
<link rel="preload" as="image" href="./scheme_files/svgrepo-signpost-fill.svg">
<link rel="preload" as="image" href="./scheme_files/svgrepo-library.svg">

<link rel="preload" as="image" href="https://plantuml.com/flags22.png">

<link rel="preload" as="image" href="./scheme_files/svgrepo-uxwing-light-mode-toggle.svg">


<!-- link rel="preload" as="image" href="https://img.shields.io/liberapay/patrons/plantuml.svg?logo=liberapay" -->


<title>Инструмент с открытым исходным кодом, использующий простые текстовые описания для рисования UML-диаграмм.</title>
<meta name="description" content="Лёгкое создание UML-диаграмм из простого текстового описания. Многочисленные виды доступных диаграмм. Экспорт изображений в формате PNG, EPS, SVG и латексные...">

<meta property="og:type" content="article">
<!-- volt:dokuwiki titleog: -->
<!-- volt:dokuwiki descriptionog: -->

<meta property="og:url" content="https://plantuml.com/ru/">
<meta property="og:site_name" content="PlantUML.com">

<!-- meta property="og:image" content="https://plantuml.com/og-index" -->
<meta name="twitter:image" content="https://plantuml.com/og-index">
<meta property="og:locale" content="ru">

<meta name="twitter:card" content="summary">
<!-- volt:dokuwiki titletwitter: -->
<!-- volt:dokuwiki descriptiontwitter: -->
<meta name="twitter:site" content="@PlantUML">
<meta name="twitter:creator" content="@PlantUML">







<!-- https://www.w3schools.com/colors/colors_picker.asp -->
<!-- filter css https://codepen.io/sosuke/pen/Pjoqqp -->













<style>
.scale {
}

li {
	margin: 2px;
}
#external li {
	margin: 13px;
}


.pezoic {
margin:0;
padding:0;
max-width: calc(100vw - 420px);
overflow-x: hidden;
}
@media screen and (max-width: 1190px) {
.pezoic {
max-width: calc(100vw - 250px);
}
}


.coptable {
	max-width: 90%;
}

.mytab {
	display:inline-block;
	border-radius: 3px;
	border: 1px solid #e1e4e8;
}

.mytab:hover {
	border: 1px dashed #0366d6;
	cursor: pointer;
	color: #0366d6;
	background: #f6f8fa;
}

.cop {
	margin: 25px 10px 0 10px;
}
.cop:hover {
	cursor: pointer; 
	filter: invert(30%) sepia(75%) saturate(4001%) hue-rotate(201deg) brightness(88%) contrast(98%);
}
.cop2 {
	margin: 25px 10px 0 10px;
}
.cop2:hover {
	cursor: pointer; 
}
.msg {
	position: absolute;
	color:#339966;
	background-color: #FFF;
	margin-top: 55px;
	display:none;
	border-radius: 3px;
	border: 1px solid #4dff00;
}

.mycell0 {
	float: left;
	vertical-align : top;
	padding:10px;
}
.mycell0 code:hover {
	cursor: default; 
	color: #000;
}

.mycell {
	float: right;
	vertical-align : top;
	padding:10px;
	max-width: 55vw;
	overflow-x: auto;
}

.mycell0 pre {
	max-width: 55vw;
	overflow-x: auto;
}

.cod {
	background: #edeff3;
	padding: 2px 5px;
	border-radius: 3px;
}
.colo {
	display: inline-block;
	background: #edeff3;
	padding: 7px 12px;
	border-radius: 3px;
}
.tag,.tagg,.tago,.tagr {
	text-rendering: optimizeLegibility;
	display: inline-block;
	padding: 3px 5px 2px 4px;
	text-decoration: none;
	white-space: nowrap;
	border: 1px solid #999;
	text-transform: uppercase;
	text-align: center;
	border-radius: 3px;
	font-size: 11px;
	font-weight: bold;
	line-height: 90%;
}
.tag {
	background-color: #EEEEEE;
}
.tagg {
	background-color: #98FB98;
}
.tago {
	background-color: #fafa00;
}
.tagr {
	background-color: #FF4500;
}


a {
    text-decoration:none;
    color:#0366d6;
}
a:hover {
    text-decoration:underline;
}

.menu1 {
    display: flex;
    flex-direction: row;
    border: 0;
    font-size: 14px;
    padding: 0;
    margin: 0;
	white-space: nowrap;
}
.menu1 a {
	white-space: nowrap;
    padding: 0 8px;
    text-decoration: none;
    color:#5e6d7d;
    line-height: 30px;
    height: 30px;
}
.menu1 a:hover{
    background: #fefefe;
    color:#0366d6;
}

.menuside2 {
    display: flex;
    flex-direction: column;
    border: 0;
    font-size: 14px;
    padding: 0;
    margin: 0;
    overflow: hidden;
	justify-content: center;
}

.menuside2 img {
vertical-align: top;
padding: 0 8px;
filter: brightness(0) saturate(100%) invert(42%) sepia(22%) saturate(385%) hue-rotate(170deg) brightness(92%) contrast(84%);
}

.menuside2 a {
    padding: 6px 0;
    text-decoration: none;
    color:#5e6d7d;
}

.menuside2 a:hover {
	color:#0366d6;
	background: #fefefe;
}

.menuside2 a:hover img {
filter: brightness(0) saturate(100%) invert(23%) sepia(44%) saturate(7029%) hue-rotate(203deg) brightness(94%) contrast(98%);
}

.breadcrumb {
    z-index:1;
	font-size:14px;
	text-align: center;
	display: inline-block;
	overflow: hidden;
	border-radius: 5px;
}


.breadcrumb a {
	text-decoration: none;
	outline: none;
	display: block;
	float: left;
	font-size: 12px;
	line-height: 24px;
	color: #373f49;
	padding: 0 10px 0 35px;
	background: #f0f1f1;
	background: linear-gradient(#f0f1f1, #c6d2d2);
	position: relative;
}
.breadcrumb a:first-child {
	padding-left: 21px;
	border-radius: 5px 0 0 5px; /*to match with the parent's radius*/
}
.breadcrumb a:first-child:before {
	left: 14px;
}
.breadcrumb a:last-child {
	visibility: hidden;
}

.breadcrumb a.active, .breadcrumb a:hover{
	color: #0366d6;
	background: #c6d2d2;
	background: linear-gradient(#e3e4e4, #b8c7c7);
}
.breadcrumb a.active:after, .breadcrumb a:hover:after {
	background: #c6d2d2;
	background: linear-gradient(135deg, #e3e4e4, #b8c7c7);
}

.breadcrumb a:after {
	content: '';
	position: absolute;
	top: 0; 
	right: -12px; /*half of square's length*/
	/*same dimension as the line-height of .breadcrumb a */
	width: 24px; 
	height: 24px;
	transform: scale(0.707) rotate(45deg);
	/*we need to prevent the arrows from getting buried under the next link*/
	z-index: 1;
	/*background same as links but the gradient will be rotated to compensate with the transform applied*/
	background: #f0f1f1;
	background: linear-gradient(135deg, #f0f1f1, #c6d2d2);
	/*stylish arrow design using box shadow*/
	box-shadow: 
		2px -2px 0 2px rgba(0,0,0,0.1), 
		3px -3px 0 2px rgba(255,255,255,0.1);
	/*
		5px - for rounded arrows and 
		50px - to prevent hover glitches on the border created using shadows*/
	border-radius: 0 5px 0 50px;
}

/*we dont need an arrow after the last link*/
.breadcrumb a:last-child:after {
	content: none;
	visibility: hidden;
}


.lga,.lga a,.lgi,.lgi a {
	font-size:13px;
	text-align: center;
    color: #fff;
    padding: 0 5px;
    margin: 0;
}
.lga,.lga a {
    background-color: #008;
}
.lgi,.lgi a {
    background-color: #888;
}
.lga:hover,.lga:hover a {
    text-decoration: none;
    color: #BBB;
}
.lgi:hover,.lgi:hover a {
    text-decoration: none;
    color: #CCC;
}

</style>

<style>
.backtop {
	margin:0px 10px;
}
.backtop:hover {
	cursor: pointer;
	filter: invert(30%) sepia(75%) saturate(4001%) hue-rotate(201deg) brightness(88%) contrast(98%);
}
</style>




<style>
/* Dropdown Button */
.dropbtn {
  padding: 0px;
  border: none;
  background: none;
}

/* The container <div> - needed to position the dropdown content */
.dropdown {
  position: relative;
  display: inline-block;
  margin: 0 10px;
}

/* Dropdown Content (Hidden by Default) */
.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content img {
vertical-align:middle;
margin: 0 8px 0 1px;
}

/* Links inside the dropdown */
.dropdown-content a {
  font-size: small;
  font-weight: normal;
  color: black;
  padding: 5px 10px;
  text-decoration: none;
  display: block;
}

/* Change color of dropdown links on hover */
.dropdown-content a:hover {
  background-color: #ddd;
  color: #0366d6;
}

/* Show the dropdown menu on hover */
.dropdown:hover .dropdown-content {display: block;}

/* Change the background color of the dropdown button when the dropdown content is shown */
.dropdown:hover .dropbtn {background-color: #3e8e41;}
</style>
<style>


body {
	font-family: system-ui, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
	font-size: 14px;
	line-height: 1.5;
	margin: auto;
	overflow-x: hidden;
    background: #fefefe;
}

h1.chap { font-size: 1.8em; }
h2.chap { font-size: 1.35em; }
h3, h3.chap { font-size: 1.15em; }
h4 { font-size: 1.05em; }
table { font-size: inherit; }

</style>


  <style>
    .dyn {
      display: flex;
      flex-direction: row;
      gap: 3em;
      align-items: stretch;
      flex-wrap: wrap;
      margin: 10px 0;
    }
    .dyn textarea {
      font-family: monospace;
      font-size: 13px;
      line-height: 1.4;
      min-width: 30ch;
      max-width: 90ch;
      box-sizing: border-box;
      resize: both;
      white-space: pre;
      overflow: auto;
      field-sizing: content;
      align-self: stretch;
      border: 1px solid #888;
      border-radius: 3px;
      margin: 0;
      padding: 4px 8px;
      background: #fefefe;
    }
    .dyn > div {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      display: flex;
    }
    .dyn > div > div {
      margin: 0;
      padding: 0;
    }
    .dyn img {
      margin: 0;
      padding: 0;
    }
    .scale {
      max-width: 100%;
      height: auto;
      border: 1px solid #dde;
      border-radius: 4px;
    }
  </style>




<script>window.pushMST_config={"vapidPK":"BBodn2vLFoDO5AdCfmOOzNmcUsn52kTA6JNZNYVFymzEdWHonz_bkUcsaTkPXHvNGRkRUSAxMbup-H0l2sb1h_Q","enableOverlay":true,"swPath":"/sw.js","i18n":{}};
  var pushmasterTag = document.createElement('script');
  pushmasterTag.src = "https://cdn.pushmaster-cdn.xyz/scripts/publishers/629f5e297baecc00098a271b/SDK.js";
  pushmasterTag.setAttribute('defer','');

  var firstScriptTag = document.getElementsByTagName('script')[0];
  firstScriptTag.parentNode.insertBefore(pushmasterTag, firstScriptTag);
</script>

<!-- Global site tag (gtag.js) - Google Analytics -->
<script async="" src="./scheme_files/js"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-TKZNNQT9CZ');
</script>



<script>
var llg = "ru";
var az=0;
var amdark=0;
function ljs(n) {
	if (az) return false;
    var sc = document.createElement("script");
    sc.type = "text/javascript";
    sc.src = "/btn-"+n+".js";
	document.body.innerHTML = "<i style='position:absolute;top:30%;width:100%;'><center>Loading in progress...";
    document.body.appendChild(sc);
}
function ctc(id) {
document.getElementById('img'+id).classList.remove('cop'); document.getElementById('img'+id).classList.add('cop2');
document.getElementById('pre'+id).style.backgroundColor = '#4dff00';
document.getElementById('msg'+id).style.display = 'inline';

setTimeout(function() { document.getElementById('img'+id).classList.remove('cop2'); document.getElementById('img'+id).classList.add('cop'); document.getElementById('pre'+id).style.backgroundColor = ''; document.getElementById('msg'+id).style.display = 'none';}, 800);      


	text = document.getElementById('pre'+id).innerText;
    if (window.clipboardData && window.clipboardData.setData)
        return window.clipboardData.setData("Text", text);
    else if (document.queryCommandSupported && document.queryCommandSupported("copy")) {
        var ta = document.createElement("textarea");
        ta.textContent = text;
        ta.style.position = "fixed";
        document.body.appendChild(ta);
        ta.select();
        try {
            return document.execCommand("copy");
        }
        catch (ex) {
            return false;
        }
        finally {
            document.body.removeChild(ta);
        }
    }
}
</script>



<script async="" src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>

<script src="./scheme_files/min.js.Без названия" data-cfasync="false"></script>
<script src="./scheme_files/cmp.min.js.Без названия" data-cfasync="false"></script>
<script type="text/javascript">
var ezoTemplate = 'pub_site';
var ezouid = '1';
var ezoFormfactor = '1';
</script><script data-ezscrex="false" type="text/javascript">
var soc_app_id = '0';
var did = 173770;
var ezdomain = 'plantuml.com';
var ezoicSearchable = 1;
</script>
<script type="text/javascript" style="display:none;" async="">window.__ezOptableApproved=true;if (typeof window.__ez !== 'undefined' && window.__ez?.queue?.addFileOnce) {window.__ez.queue.addFileOnce('identity', ('noModule' in document.createElement('script'))?'https://go.ezodn.com/detroitchicago/indy.es6.js?cb=42&gcb=0':'https://go.ezodn.com/detroitchicago/indy.js?cb=200&gcb=0', true, [], true, false, false, true);} </script><script src="./scheme_files/indy.es6.js.Без названия" async=""></script>
<script>window.__ezSocialLoginConfig = {"providers":{"google":{"enabled":true,"clientId":"626901221629-15ss1s412okbv1qg834f6e3h8chm6ubk.apps.googleusercontent.com"},"facebook":{"enabled":false},"apple":{"enabled":false},"microsoft":{"enabled":false}},"routes":{"facebookStart":"https://identity.ezoic.com/social-login/facebook/start","facebookCallback":"https://identity.ezoic.com/social-login/facebook/callback","facebookResult":"https://identity.ezoic.com/social-login/facebook/result","appleStart":"https://identity.ezoic.com/social-login/apple/start","appleCallback":"https://identity.ezoic.com/social-login/apple/callback","appleResult":"https://identity.ezoic.com/social-login/apple/result","microsoftStart":"https://identity.ezoic.com/social-login/microsoft/start","microsoftCallback":"https://identity.ezoic.com/social-login/microsoft/callback","microsoftResult":"https://identity.ezoic.com/social-login/microsoft/result"},"domainId":173770,"copy":{"titleText":"","bodyHtml":""},"newsletter":{"enabled":false,"label":""}};window.__ezOneTapClientId = "626901221629-15ss1s412okbv1qg834f6e3h8chm6ubk.apps.googleusercontent.com";</script><script src="./scheme_files/mulvane.js.Без названия" async=""></script><script src="./scheme_files/birmingham.js.Без названия" async=""></script><style id="ez-grippy-dim">.grippy-host{opacity:.5;}body{padding-bottom:0 !important;padding-top:0 !important;}</style><script type="text/javascript">if(typeof _setEzCookies!=='function'){function _setEzCookies(ezConsentData){var cookies=window.ezCookieQueue;for(var i=0;i<cookies.length;i++){var cookie=cookies[i];if(ezConsentData&&ezConsentData.loaded&&ezConsentData[cookie.tcfCategory]){document.cookie=cookie.name+"="+cookie.value;}}}}
window.ezCookieQueue=window.ezCookieQueue||[];if(typeof addEzCookies!=='function'){function addEzCookies(arr){window.ezCookieQueue=[...window.ezCookieQueue,...arr];}}
addEzCookies([{name:"ezfs_173770",value:"2165909046; Path=/; Domain=plantuml.com; Expires=Fri, 20 Nov 2026 16:14:09 UTC",tcfCategory:"store_info",isEzoic:"true",},{name:"ezovuuidtime_173770",value:"1795184049; Path=/; Domain=plantuml.com; Expires=Sun, 22 Nov 2026 14:14:09 UTC",tcfCategory:"understand_audiences",isEzoic:"true",},{name:"lp_173770",value:"https://plantuml.com/ru/; Path=/; Domain=plantuml.com; Expires=Fri, 20 Nov 2026 14:44:09 UTC",tcfCategory:"store_info",isEzoic:"true",},{name:"ezovuuid_173770",value:"01a1f94e-bcda-7f00-b58b-8535ea3ebc82; Path=/; Domain=plantuml.com; Expires=Fri, 20 Nov 2026 14:44:09 UTC",tcfCategory:"understand_audiences",isEzoic:"true",},{name:"ezoref_173770",value:"plantuml.com; Path=/; Domain=plantuml.com; Expires=Fri, 20 Nov 2026 14:44:09 UTC",tcfCategory:"understand_audiences",isEzoic:"true",}]);if(window.ezTcfConsent&&window.ezTcfConsent.loaded){_setEzCookies(window.ezTcfConsent);}else if(typeof getEzConsentData==="function"){getEzConsentData().then(function(ezTcfConsent){if(ezTcfConsent&&ezTcfConsent.loaded){_setEzCookies(window.ezTcfConsent);}else{console.error("cannot get ez consent data");_setEzCookies(window.ezTcfConsent);}});}else{console.error("getEzConsentData is not a function");_setEzCookies(window.ezTcfConsent);}window._ezaq = Object.assign({"ab_test_id":"mod30","ad_cache_level":1,"ad_count_adjustment":0,"ad_lazyload_version":0,"ad_load_version":1,"ad_location_ids":"","adpicker_placement_cnt":0,"adx_ad_count":0,"ai_placeholder_cache_level":1,"ai_placeholder_placement_cnt":-1,"bidder_method":0,"bidder_version":3,"city":"Achinsk","country":"RU","days_since_last_visit":-1,"device_make":"Microsoft","device_model":"Windows PC","device_os_name":"Windows","device_os_version":"10.0.0","display_ad_count":0,"domain":"plantuml.com","domain_id":173770,"domain_test_group":20230802,"edge_cache_status":1,"edge_response_time":26,"engaged_time_visit":0,"ezcache_level":2,"ezcache_skip_code":0,"first_party_signals_content_keywords":"plantuml,uml,diagrams,software,coding,programming,developer tools,open source,sequence diagram,class diagram,use case diagram,gantt diagram,json to diagram,yaml to diagram,svg export,png export,latex,graphviz,text description,mindmap,er diagram,download plantuml,plantuml open source,plantuml guide,direct sales,plantuml sponsors,uml tool download,buy plantuml support,uml diagram software,unified modeling language,software engineering,open source software,diagramming tool,text to diagram","first_party_signals_domain_categories":"IAB19","first_party_signals_domain_categories_v2":"596,602,631","first_party_signals_keywords":"plantuml,uml diagrams,software modeling,coding,diagramming tool,software development,programming,technical drawing,software design,open source,download plantuml,plantuml server,uml diagram tool,software design software,open source uml tool,gantt chart generator,enterprise architecture tool,wireframe software,mindmap tool,professional diagram software,uml,diagrams,software,developer tools,plantuml open source,plantuml guide,direct sales,plantuml sponsors,uml tool download,buy plantuml support,uml diagram software,unified modeling language,diagram as code,software architecture,technical documentation,open source software,systems engineering,markup languages,visual modeling,software engineering,text to diagram","first_party_signals_page_categories":"IAB19","first_party_signals_page_categories_v2":"596,602,631","first_party_signals_publisher_vertical":"Tech","first_party_signals_site_keywords":"plantuml,uml diagrams,software modeling,coding,diagramming tool,software development,programming,technical drawing,software design,open source,download plantuml,plantuml server,uml diagram tool,software design software,open source uml tool,gantt chart generator,enterprise architecture tool,wireframe software,mindmap tool,professional diagram software,uml,diagrams,software,developer tools,plantuml open source,plantuml guide,direct sales,plantuml sponsors,uml tool download,buy plantuml support,uml diagram software,unified modeling language,diagram as code,software architecture,technical documentation,open source software,systems engineering,markup languages,visual modeling,software engineering,text to diagram","form_factor_id":1,"framework_id":1,"full_url":"https://plantuml.com/ru/","has_bad_image":0,"has_bad_words":0,"iab_blocked_categories":"","iab_category":"","ipv4":"46.166.80.62","is_embed":false,"is_from_recommended_pages":false,"is_return_visitor":false,"is_sitespeed":0,"last_page_load":"","last_pageview_id":"","lt_cache_level":0,"max_ads":0,"metro_code":0,"optable_approved":true,"optable_iab_categories":[596,602,631],"optimization_version":0,"ortb_signals_language":"en","page_ad_positions":"","page_view_count":0,"page_view_id":"01a1f94e-bcdb-7118-a27d-d72ca3eac1ef","position_selection_id":0,"postal_code":"662150","product_1":true,"product_3":true,"product_5":true,"product_6":true,"pv_event_count":0,"referring_domain":"plantuml.com","response_size":64922,"response_size_orig":51716,"response_time_orig":3,"serverid":"i-026dfabfdaf207f75","site_iab_categories":[632,1019,132],"state":"KYA","sub_page_ad_positions":"","t_epoch":1795184049,"template_id":134,"time_on_site_visit":0,"url":"https://plantuml.com/ru/","url_prebid_signals_id":1450829,"visit_uuid":"01a1f94e-bcda-7f00-b58b-8535ea3ebc82","word_count":781,"worst_bad_word_level":0}, typeof window._ezaq !== "undefined" ? window._ezaq : {});__ez.queue.markLoaded('ezaqReady');if(window._ezaq&&window._ezaq.page_view_id==="01a1f94e-bcdb-7118-a27d-d72ca3eac1ef"){window.__ezPvSig=window.__ezPvSig||"tot0vl.1bfb92a38257fc34fb6d09a6b5119865";}
__ez.queue.addFileOnce('/parsonsmaize/mulvane.js', '/parsonsmaize/mulvane.js?gcb=195-5&cb=e75e48eec0', true, ['/parsonsmaize/abilene.js'], true, false, true, false);__ez.queue.addFileOnce('/parsonsmaize/olathe.js', '/parsonsmaize/olathe.js?gcb=195-5&cb=30', true, ['/parsonsmaize/abilene.js','/parsonsmaize/mulvane.js'], true, false, true, false);__ez.queue.addFileOnce('/porpoiseant/et.js', '/porpoiseant/et.js?gcb=195-5&cb=4', true, [], true, false, true, false);__ez.queue.addFileOnce('/detroitchicago/reno.js', '/detroitchicago/reno.js?gcb=195-5&cb=3ee98ed026', true, ['/parsonsmaize/abilene.js'], true, false, true, false);__ez.queue.addFileOnce('/detroitchicago/overlandpark.js', '/detroitchicago/overlandpark.js?gcb=195-5&cb=301bbdaf04', true, ['/parsonsmaize/abilene.js'], true, false, true, false);__ez.queue.addFileOnce('/detroitchicago/omaha.js', '/detroitchicago/omaha.js?gcb=195-5&cb=8506900a4e', true, ['/detroitchicago/reno.js'], true, false, true, false);__ez.queue.addFileOnce('/detroitchicago/birmingham.js', '/detroitchicago/birmingham.js?gcb=195-5&cb=c4ed651ab8', true, ['/parsonsmaize/abilene.js'], true, false, true, false);
__ez.queue.addFileOnce('/detroitchicago/wichita.js', '/detroitchicago/wichita.js?gcb=195-5&cb=07d674ad9b', true, ['/parsonsmaize/abilene.js'], true, false, true, false);
function create_ezolpl() {
	var cname = "ezux_lpl_173770";
	var d = new Date();
	d.setTime(d.getTime() + 365 * 24 * 60 * 60 * 1000);
	var expires = "expires=" + d.toUTCString();
	__ez.ck.setByCat(cname, "; expires=Thu, 01 Jan 1970 00:00:01 GMT", "understand_audiences", true);
	__ez.ck.setByCat(
	  cname,
	  new Date().getTime() +
		"|" +
		_ezaq.page_view_id +
		"|" +
		_ezaq.is_return_visitor +
		"; path=/; " +
		expires,
	  "understand_audiences",
	  false
	);
  }
  function attach_ezolpl() {
	if (document.readyState === "complete") {
	  create_ezolpl();
	  return;
	}
	window.addEventListener("load", create_ezolpl);
  }  

__ez.queue.addFunc("attach_ezolpl", "attach_ezolpl", null, false, ['/detroitchicago/boise.js'], true, false, false, false);

__ez.queue.addFile('/tardisrocinante/vitals.js', '/tardisrocinante/vitals.js?gcb=5&cb=6', false, ['/parsonsmaize/mulvane.js'], true, false, true, false);
var _audins_dom="plantuml_com",_audins_did=173770;__ez.queue.addDelayFunc("audins.js","__ez.script.add", "//go.ezodn.com/detroitchicago/audins.js?cb=4");
var __ez_dims = (function() {
		var setCookie = function( name, content, expiry ) {
			return document.cookie = name+'='+content+((expiry)?';expires='+(new Date(Math.floor(new Date().getTime()+expiry*1000)).toUTCString()):'')+';path=/';
		};
		var ffid = 1;
		var oh = window.screen.height;
		var ow = window.screen.width;
		var h = ffid === 1 ? oh : (oh > ow) ? oh : ow;
		var w = ffid === 1 ? ow : (oh > ow) ? ow : oh;
		var uh = window.innerHeight || document.documentElement.clientHeight || document.getElementsByTagName('body')[0].clientHeight;
		var uw = window.innerWidth || document.documentElement.clientWidth || document.getElementsByTagName('body')[0].clientWidth;
	
		var setAllCookies = function() {
			setCookie('ezds', encodeURIComponent('ffid='+ffid+',w='+w+',h='+h+',tp='+(navigator.maxTouchPoints||0)), (31536e3*7));
			setCookie('ezohw', encodeURIComponent('w='+uw+',h='+uh+',tp='+(navigator.maxTouchPoints||0)), (31536e3*7));
		};
	
		if (window.ezTcfConsent && window.ezTcfConsent.loaded) {
			if (window.ezTcfConsent.understand_audiences) { 
				setAllCookies();
			}
		} else if (typeof getEzConsentData === "function") {
			getEzConsentData().then(function (ezTcfConsent) {
				if (ezTcfConsent && ezTcfConsent.loaded) {
					if (ezTcfConsent.understand_audiences) { 
						setAllCookies();
					}
				} else {
					console.error("cannot get ez consent data");
					setAllCookies();
				}
			});
		} else {
			console.error("getEzConsentData is not a function");
			setAllCookies();
		}
	
	})();
__ez.queue.addFile('/parsonsmaize/chanute.js', '/parsonsmaize/chanute.js?a=a&cb=6b78d167f7&dcb=195-5&shcb=34', true, ['/parsonsmaize/mulvane.js'], true, false, false, false);
__ez.queue.addFile('/porpoiseant/jellyfish.js', '/porpoiseant/jellyfish.js?a=a&cb=31&dcb=195-5&shcb=34', false, [], true, false, false, false);
</script><script src="./scheme_files/olathe.js.Без названия" async=""></script><script src="./scheme_files/et.js.Без названия" async=""></script><script src="./scheme_files/reno.js.Без названия" async=""></script><script src="./scheme_files/overlandpark.js.Без названия" async=""></script><script src="./scheme_files/wichita.js.Без названия" async=""></script><script src="./scheme_files/vitals.js.Без названия" async=""></script><script src="./scheme_files/jellyfish.js.Без названия" async=""></script><script src="./scheme_files/omaha.js.Без названия" async=""></script><style id="googleidentityservice_button_styles">.qJTHM{-moz-user-select:none;-webkit-user-select:none;-ms-user-select:none;color:#202124;direction:ltr;-webkit-touch-callout:none;font-family:Roboto-Regular,arial,sans-serif;-webkit-font-smoothing:antialiased;font-weight:400;margin:0;overflow:hidden;-webkit-text-size-adjust:100%}.ynRLnc{left:-9999px;position:absolute;top:-9999px}.L6cTce{display:none}.bltWBb{overflow-wrap:break-word;word-break:break-word}.hSRGPd{color:#1a73e8;cursor:pointer;font-weight:500;text-decoration:none}.Bz112c-W3lGp{height:16px;width:16px}.Bz112c-E3DyYd{height:20px;width:20px}.Bz112c-r9oPif{height:24px;width:24px}.Bz112c-u2z5K{height:36px;width:36px}.Bz112c-uaxL4e{border-radius:10px}.LgbsSe-Bz112c{display:block}.S9gUrf-YoZ4jf{border:none;margin:0;padding:0}.S9gUrf-YoZ4jf *{border:none;margin:0;padding:0}.fFW7wc-ibnC6b>.aZ2wEe>div{border-color:#4285f4}.P1ekSe-ZMv3u{transition:height .2s linear}.P1ekSe-ZMv3u>div:first-child{background-color:#1a73e8!important;transition:width .3s linear}.P1ekSe-ZMv3u>div:nth-child(2){background-image:linear-gradient(90deg,rgba(255,255,255,.7),rgba(255,255,255,.7)),linear-gradient(90deg,#1a73e8,#1a73e8)!important}.P1ekSe-ZMv3u>div:nth-child(3){background-image:linear-gradient(90deg,rgba(255,255,255,.7),rgba(255,255,255,.7)),linear-gradient(90deg,#1a73e8,#1a73e8)!important}.haAclf{display:inline-block}.nsm7Bb-HzV7m-LgbsSe{border-radius:4px;box-sizing:border-box;transition:background-color .218s,border-color .218s;-moz-user-select:none;-webkit-user-select:none;-ms-user-select:none;-webkit-appearance:none;background-color:#fff;background-image:none;border:1px solid #dadce0;color:#3c4043;cursor:pointer;font-family:Google Sans,arial,sans-serif;font-size:.875rem;height:40px;letter-spacing:.25px;outline:none;overflow:hidden;padding:0 12px;position:relative;text-align:center;vertical-align:middle;white-space:nowrap;width:auto}.nsm7Bb-HzV7m-LgbsSe.TzA9Ye-LgbsSe{font-size:14px}@media screen and (-ms-high-contrast:active){.nsm7Bb-HzV7m-LgbsSe{border:2px solid windowText;color:windowText}}@media screen and (preferes-contrast:more){.nsm7Bb-HzV7m-LgbsSe{color:#000}}.nsm7Bb-HzV7m-LgbsSe.pSzOP-SxQuSe{font-size:.875rem;height:32px;letter-spacing:.25px;padding:0 10px}.nsm7Bb-HzV7m-LgbsSe.pSzOP-SxQuSe.TzA9Ye-LgbsSe{font-size:14px}.nsm7Bb-HzV7m-LgbsSe.purZT-SxQuSe{font-size:.6875rem;height:20px;letter-spacing:.3px;padding:0 8px}.nsm7Bb-HzV7m-LgbsSe.purZT-SxQuSe.TzA9Ye-LgbsSe{font-size:11px}.nsm7Bb-HzV7m-LgbsSe.Bz112c-LgbsSe{padding:0;width:40px}.nsm7Bb-HzV7m-LgbsSe.Bz112c-LgbsSe.pSzOP-SxQuSe{width:32px}.nsm7Bb-HzV7m-LgbsSe.Bz112c-LgbsSe.purZT-SxQuSe{width:20px}.nsm7Bb-HzV7m-LgbsSe.JGcpL-RbRzK{border-radius:20px}.nsm7Bb-HzV7m-LgbsSe.JGcpL-RbRzK.pSzOP-SxQuSe{border-radius:16px}.nsm7Bb-HzV7m-LgbsSe.JGcpL-RbRzK.purZT-SxQuSe{border-radius:10px}.nsm7Bb-HzV7m-LgbsSe.i5vt6e-to915-Ia7Qfc{border:1px solid #8e918f;background-color:#131314;color:#e3e3e3}.nsm7Bb-HzV7m-LgbsSe.MFS4be-Ia7Qfc{border:none;color:#fff}.nsm7Bb-HzV7m-LgbsSe.MFS4be-v3pZbf-Ia7Qfc{background-color:#1a73e8}.nsm7Bb-HzV7m-LgbsSe.MFS4be-JaPV2b-Ia7Qfc{background-color:#202124;color:#e8eaed}@media screen and (prefers-contrast:more){.nsm7Bb-HzV7m-LgbsSe.MFS4be-JaPV2b-Ia7Qfc{color:#fff}}.nsm7Bb-HzV7m-LgbsSe .nsm7Bb-HzV7m-LgbsSe-Bz112c{height:18px;margin-right:8px;min-width:18px;width:18px}.nsm7Bb-HzV7m-LgbsSe.pSzOP-SxQuSe .nsm7Bb-HzV7m-LgbsSe-Bz112c{height:14px;min-width:14px;width:14px}.nsm7Bb-HzV7m-LgbsSe.purZT-SxQuSe .nsm7Bb-HzV7m-LgbsSe-Bz112c{height:10px;min-width:10px;width:10px}.nsm7Bb-HzV7m-LgbsSe.jVeSEe .nsm7Bb-HzV7m-LgbsSe-Bz112c{margin-left:8px;margin-right:-4px}.nsm7Bb-HzV7m-LgbsSe.Bz112c-LgbsSe .nsm7Bb-HzV7m-LgbsSe-Bz112c{margin:0;padding:10px}.nsm7Bb-HzV7m-LgbsSe.Bz112c-LgbsSe.pSzOP-SxQuSe .nsm7Bb-HzV7m-LgbsSe-Bz112c{padding:8px}.nsm7Bb-HzV7m-LgbsSe.Bz112c-LgbsSe.purZT-SxQuSe .nsm7Bb-HzV7m-LgbsSe-Bz112c{padding:4px}.nsm7Bb-HzV7m-LgbsSe .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf{border-top-left-radius:3px;border-bottom-left-radius:3px;display:flex;justify-content:center;align-items:center;background-color:#fff;height:36px;margin-left:-10px;margin-right:12px;min-width:36px;width:36px}.nsm7Bb-HzV7m-LgbsSe .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf .nsm7Bb-HzV7m-LgbsSe-Bz112c,.nsm7Bb-HzV7m-LgbsSe.Bz112c-LgbsSe .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf .nsm7Bb-HzV7m-LgbsSe-Bz112c{margin:0;padding:0}.nsm7Bb-HzV7m-LgbsSe.pSzOP-SxQuSe .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf{height:28px;margin-left:-8px;margin-right:10px;min-width:28px;width:28px}.nsm7Bb-HzV7m-LgbsSe.purZT-SxQuSe .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf{height:16px;margin-left:-6px;margin-right:8px;min-width:16px;width:16px}.nsm7Bb-HzV7m-LgbsSe.Bz112c-LgbsSe .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf{border-radius:3px;margin-left:2px;margin-right:0;padding:0}.nsm7Bb-HzV7m-LgbsSe.JGcpL-RbRzK .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf{border-radius:18px}.nsm7Bb-HzV7m-LgbsSe.pSzOP-SxQuSe.JGcpL-RbRzK .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf{border-radius:14px}.nsm7Bb-HzV7m-LgbsSe.purZT-SxQuSe.JGcpL-RbRzK .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf{border-radius:8px}.nsm7Bb-HzV7m-LgbsSe .nsm7Bb-HzV7m-LgbsSe-bN97Pc-sM5MNb{display:flex;align-items:center;flex-direction:row;justify-content:space-between;flex-wrap:nowrap;height:100%;position:relative;width:100%}.nsm7Bb-HzV7m-LgbsSe .oXtfBe-l4eHX{justify-content:center}.nsm7Bb-HzV7m-LgbsSe .nsm7Bb-HzV7m-LgbsSe-BPrWId{flex-grow:1;font-family:Google Sans,arial,sans-serif;font-weight:500;overflow:hidden;text-overflow:ellipsis;vertical-align:top}.nsm7Bb-HzV7m-LgbsSe.purZT-SxQuSe .nsm7Bb-HzV7m-LgbsSe-BPrWId{font-weight:300}.nsm7Bb-HzV7m-LgbsSe .oXtfBe-l4eHX .nsm7Bb-HzV7m-LgbsSe-BPrWId{flex-grow:0}.nsm7Bb-HzV7m-LgbsSe .nsm7Bb-HzV7m-LgbsSe-MJoBVe{transition:background-color .218s;bottom:0;left:0;position:absolute;right:0;top:0}.nsm7Bb-HzV7m-LgbsSe:focus,.nsm7Bb-HzV7m-LgbsSe:hover{box-shadow:none;border-color:rgb(210,227,252);outline:none}.nsm7Bb-HzV7m-LgbsSe:focus-within{outline:2px solid #00639b;border-color:transparent}.nsm7Bb-HzV7m-LgbsSe:hover .nsm7Bb-HzV7m-LgbsSe-MJoBVe{background:rgba(66,133,244,.08)}.nsm7Bb-HzV7m-LgbsSe:active .nsm7Bb-HzV7m-LgbsSe-MJoBVe,.nsm7Bb-HzV7m-LgbsSe:focus .nsm7Bb-HzV7m-LgbsSe-MJoBVe{background:rgba(66,133,244,.1)}.nsm7Bb-HzV7m-LgbsSe.i5vt6e-to915-Ia7Qfc:hover .nsm7Bb-HzV7m-LgbsSe-MJoBVe{background:rgba(255,255,255,.08)}.nsm7Bb-HzV7m-LgbsSe.i5vt6e-to915-Ia7Qfc:active .nsm7Bb-HzV7m-LgbsSe-MJoBVe,.nsm7Bb-HzV7m-LgbsSe.i5vt6e-to915-Ia7Qfc:focus .nsm7Bb-HzV7m-LgbsSe-MJoBVe{background:rgba(255,255,255,.12)}.nsm7Bb-HzV7m-LgbsSe.MFS4be-Ia7Qfc:hover .nsm7Bb-HzV7m-LgbsSe-MJoBVe{background:rgba(255,255,255,.24)}.nsm7Bb-HzV7m-LgbsSe.MFS4be-Ia7Qfc:active .nsm7Bb-HzV7m-LgbsSe-MJoBVe,.nsm7Bb-HzV7m-LgbsSe.MFS4be-Ia7Qfc:focus .nsm7Bb-HzV7m-LgbsSe-MJoBVe{background:rgba(255,255,255,.32)}.nsm7Bb-HzV7m-LgbsSe .n1UuX-DkfjY{border-radius:50%;display:flex;height:20px;margin-left:-4px;margin-right:8px;min-width:20px;width:20px}.nsm7Bb-HzV7m-LgbsSe.jVeSEe .nsm7Bb-HzV7m-LgbsSe-BPrWId{font-family:Roboto;font-size:12px;text-align:left}.nsm7Bb-HzV7m-LgbsSe.jVeSEe .nsm7Bb-HzV7m-LgbsSe-BPrWId .K4efff .fmcmS,.nsm7Bb-HzV7m-LgbsSe.jVeSEe .nsm7Bb-HzV7m-LgbsSe-BPrWId .ssJRIf{overflow:hidden;text-overflow:ellipsis}.nsm7Bb-HzV7m-LgbsSe.jVeSEe .nsm7Bb-HzV7m-LgbsSe-BPrWId .K4efff{display:flex;align-items:center;color:#5f6368;fill:#5f6368;font-size:11px;font-weight:400}.nsm7Bb-HzV7m-LgbsSe.jVeSEe.i5vt6e-to915-Ia7Qfc .nsm7Bb-HzV7m-LgbsSe-BPrWId .K4efff{color:#c4c7c5;fill:#c4c7c5}.nsm7Bb-HzV7m-LgbsSe.jVeSEe.MFS4be-Ia7Qfc .nsm7Bb-HzV7m-LgbsSe-BPrWId .K4efff{color:#e8eaed;fill:#e8eaed}@media screen and (prefers-contrast:more){.nsm7Bb-HzV7m-LgbsSe.jVeSEe .nsm7Bb-HzV7m-LgbsSe-BPrWId .K4efff,.nsm7Bb-HzV7m-LgbsSe.jVeSEe.MFS4be-Ia7Qfc .nsm7Bb-HzV7m-LgbsSe-BPrWId .K4efff{color:#000;fill:#000}}.nsm7Bb-HzV7m-LgbsSe.jVeSEe .nsm7Bb-HzV7m-LgbsSe-BPrWId .K4efff .Bz112c{height:18px;margin:-3px -3px -3px 2px;min-width:18px;width:18px}.nsm7Bb-HzV7m-LgbsSe.jVeSEe .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf{border-top-left-radius:0;border-bottom-left-radius:0;border-top-right-radius:3px;border-bottom-right-radius:3px;margin-left:12px;margin-right:-10px}.nsm7Bb-HzV7m-LgbsSe.jVeSEe.JGcpL-RbRzK .nsm7Bb-HzV7m-LgbsSe-Bz112c-haAclf{border-radius:18px}.L5Fo6c-sM5MNb{border:0;display:block;left:0;position:relative;top:0}.L5Fo6c-bF1uUb{border-radius:4px;bottom:0;cursor:pointer;left:0;position:absolute;right:0;top:0}.L5Fo6c-bF1uUb:focus{border:none;outline:none}sentinel{}</style><link id="googleidentityservice" type="text/css" media="all" href="./scheme_files/style" rel="stylesheet"><link id="ez-ssm-roboto-font" rel="stylesheet" href="./scheme_files/css2"><script src="./scheme_files/audins.js.Без названия" async="" type="text/javascript"></script></head>

<body>
    <style>
body, .container, #A1, #B3, #C5, #C6, #C7, #D7, #D8 {
    margin: 0;
    padding: 0;
}
        body {
            overflow-y: scroll;
        }

        .container {
            display: grid;
            grid-template-columns: auto 1fr auto auto auto;
            grid-template-rows: auto 1fr auto;
            min-height: 100vh;
        }

        #A1 {
            grid-column: 1;
            grid-row: 1 / -1;
            position: sticky;
            top: 0;
            height: 100vh;
            padding: 0 10px;
            overflow: hidden;
            background: #edeff3;
            color: white;
        }

        #A1::after {
            content: "";
            position: absolute;
            top: 30px;
            right: 0;
            width: 1px;
            height: calc(100vh - 30px);
            background: #d4d8de;
        }

        #B3 {
            grid-column: 2 / 6;
            grid-row: 1;
            position: sticky;
            top: 0;
            height: 30px;
            padding: 0;
            z-index: 10;
            overflow: hidden;
            background: #edeff3;
            border-bottom: 1px solid #d4d8de;
        }

        #D7 {
            grid-column: 2;
            grid-row: 2;
            margin: 0;
            padding: 0;
            padding-left: 30px;
            line-height: 1.6;
        }

        #D8 {
            grid-column: 2;
            grid-row: 3;
            position: sticky;
            bottom: 0;
            z-index: 5;
            background: #fefefe;
        }

        #C5 {
            grid-column: 3;
            grid-row: 1 / -1;
            position: sticky;
            top: 40px;
            align-self: start;
            height: calc(98vh - 60px);
            overflow: hidden;
    display: flex;
    flex-direction: column;
    justify-content: center;
        }
        
        #C6 {
            grid-column: 4;
            grid-row: 1 / -1;
            position: sticky;
            top: 40px;
            align-self: start;
            height: calc(98vh - 60px);
            max-width: 200px;
            overflow: hidden;
            margin: 0 10px;
            padding: 8px 5px;
    display: flex;
    flex-direction: column;
    justify-content: center;
        }
        
        #C7 {
            grid-column: 5;
            grid-row: 1 / -1;
            position: sticky;
            top: 40px;
            align-self: start;
            height: calc(98vh - 60px);
            margin: 0 20px 0 0;
            overflow: hidden;
    display: flex;
    flex-direction: column;
    justify-content: center;
        }
        
 #toc {
 z-index:15;
 overflow-x: hidden;
 overflow-y: auto;
 background: #f6f8fa;
 border-width: 2px;
 border-style: groove;
 border-radius: 3px;
 border-color: #e1e4e8;
 margin: 0 5px;
 padding: 0;
 max-height: 100%;
}

#toc ul {
margin: 0;
list-style-type: none;
padding: 0;
}

#toc li {
    padding:0 10px;
    margin: 0;
}

#toc li a {
    padding:5px 0;
display: inline-block;
text-decoration:none;
width:100%;
color: #5e6d7d;
}

#toc li a:hover {
color: #0366d6;
}

#toc li:hover {
background: #fefefe;
}

        #magic {
            position: absolute;
            top: 0;
            right: 50px;
            width: 30px;
            height: 30px;
            overflow: hidden;
            background: #edeff3;
            z-index: 14;
        }

        #magic:hover {
            width: calc(100% - 50px);
        }

        #magic .menu1 {
            position: absolute;
            top: 0;
            right: 30px;
            height: 30px;
            padding-left: 10px;
            background: #edeff3;
            border-left: 1px solid #d4d8de;
            border-bottom: 1px solid #d4d8de;
        }

        #magic > img {
            position: absolute;
            top: 0;
            right: 0;
            width: 30px;
            height: 30px;
            filter: brightness(0) saturate(100%) invert(42%) sepia(22%) saturate(385%) hue-rotate(170deg) brightness(92%) contrast(84%);
        }

        #magic:hover > img {
            filter: brightness(0) saturate(100%) invert(23%) sepia(44%) saturate(7029%) hue-rotate(203deg) brightness(94%) contrast(98%);
        }

        #magic2 {
            position: absolute;
            top: 0;
            right: 0;
            width: 50px;
            height: 30px;
            overflow: hidden;
            background: #edeff3;
            z-index: 16;
        }

        #magic2 img {
            margin: 5px 0 0 5px;
filter: brightness(0) saturate(100%) invert(42%) sepia(22%) saturate(385%) hue-rotate(170deg) brightness(92%) contrast(84%);
        }

        #magic2:hover img {
filter: brightness(0) saturate(100%) invert(23%) sepia(44%) saturate(7029%) hue-rotate(203deg) brightness(94%) contrast(98%);
        }

        .menu1-tail {
            flex-grow: 1;
            flex-shrink: 0;
            height: 30px;
            position: relative;
            z-index: 15;
            background: #edeff3;
        }

        .grid {
            display: grid;
            grid-template-columns: auto auto auto;
            grid-auto-rows: auto;
            gap: 5px;
            margin: 0;
            padding: 0;
        }

        .merged {
            grid-column: 1 / -1;
        }
        
        .ezoic-wrap {
            display: block;
            overflow: hidden;
        }

#C6 {
    display: none;
}

@media (min-width: 1401px) {
    #C6:has(#toc li) {
        display: flex;
    }
}

@media (max-width: 1100px) {
	.ezoic-wrap, #C5, #C7 {
		display: none;
	}
}

@media (max-width: 1200px) {
	.merged {
		display: none;
	}
}

        
    </style>

<div class="container">


<aside id="C5">
<!-- Ezoic - side3 - top_of_page -->
<span id="ezoic-pub-ad-placeholder-681"></span><!-- ezoic_pub_ad_placeholder-681-top_of_page-120x600-681-nonexxxnonexxxxxxezmaxscaleval100 --><!-- ezoic_pub_ad_placeholder-681-top_of_page-160x600-681-nonexxxnonexxxxxxezmaxscaleval100 -->
<!-- End Ezoic - side3 - top_of_page -->
</aside>

<aside id="C7">
<!-- Ezoic - side4 - top_of_page -->
<span id="ezoic-pub-ad-placeholder-682"></span><!-- ezoic_pub_ad_placeholder-682-top_of_page-120x600-682-nonexxxnonexxxxxxezmaxscaleval100 --><!-- ezoic_pub_ad_placeholder-682-top_of_page-160x600-682-nonexxxnonexxxxxxezmaxscaleval100 -->
<!-- End Ezoic - side4 - top_of_page -->
</aside>

<footer id="D8">

<div style="display: flex; justify-content: center; min-height: 100px;">
<p>
</p></div>

</footer>

    <aside id="A1">
        <div class="grid">
            <div class="merged">
<!-- Ezoic - alpha-bloc - top_of_page -->
<span id="ezoic-pub-ad-placeholder-678"></span><!-- ezoic_pub_ad_placeholder-678-top_of_page-250x250-678-nonexxxnonexxxxxxezmaxscaleval100 --><!-- ezoic_pub_ad_placeholder-678-top_of_page-300x250-678-nonexxxnonexxxxxxezmaxscaleval100 -->
<!-- End Ezoic - alpha-bloc - top_of_page -->
            </div>
            
            <div>
<!-- Ezoic - side1 - top_of_page -->
<div class="ezoic-wrap">
  <span id="ezoic-pub-ad-placeholder-679"></span><!-- ezoic_pub_ad_placeholder-679-top_of_page-120x600-679-nonexxxnonexxxxxxezmaxscaleval100 --><!-- ezoic_pub_ad_placeholder-679-top_of_page-160x600-679-nonexxxnonexxxxxxezmaxscaleval100 -->
</div>
<!-- End Ezoic - side1 - top_of_page -->
            </div>
            
            <div>

<!--menu 10-->

<!-- https://stackoverflow.com/questions/22252472/how-to-change-the-color-of-an-svg-element -->
<!-- https://codepen.io/sosuke/pen/Pjoqqp -->


<div class="menuside2">
<a id="mitem10" href="https://plantuml.com/ru/index"><img src="./scheme_files/svgrepo-house.svg" width="16" height="16">В начало</a>
<a id="mitem20" href="https://plantuml.com/ru/news"><img src="./scheme_files/svgrepo-text-news.svg" width="16" height="16">Что нового ?</a>
<a id="mitem30" href="https://plantuml.com/ru/starting"><img src="./scheme_files/svgrepo-rocket-3-start.svg" width="16" height="16">Быстрый старт</a>
<a href="https://www.plantuml.com/plantuml/uml/SyfFKj2rKt3CoKnELR1Io4ZDoSa70000"><img src="./scheme_files/svgrepo-server.svg" width="16" height="16">Online Server</a>
<a id="mitem40" href="https://plantuml.com/ru/running"><img src="./scheme_files/svgrepo-play.svg" width="16" height="16">Запуск</a>
<a id="mitem50" href="https://plantuml.com/ru/faq"><img src="./scheme_files/svgrepo-forum.svg" width="16" height="16">F.A.Q.</a>
<a id="mitem60" href="https://plantuml.com/ru/download"><img src="./scheme_files/svgrepo-add-to-online-cart.svg" width="16" height="16">Скачать</a>
<a id="mitem70" href="https://forum.plantuml.net/"><img src="./scheme_files/svgrepo-forum-message.svg" width="16" height="16">Форум</a>
<a id="mitem80" href="https://the-lum.github.io/puml-themes-gallery/themes/index.html"><img src="./scheme_files/svgrepo-palette-fill.svg" width="16" height="16">Theme</a>
<a id="mitem90" href="https://plantuml.com/ru/preprocessing"><img src="./scheme_files/svgrepo-cpu.svg" width="16" height="16">Препроцессинг</a>
<a id="mitem100" href="https://plantuml.com/ru/stdlib"><img src="./scheme_files/svgrepo-books-library.svg" width="16" height="16">Стандартная библиотека</a>
<a href="https://plantuml.com/ru/guide"><img src="./scheme_files/svgrepo-library.svg" width="16" height="16">PDF Guide</a>
<a href="https://crashedmind.github.io/PlantUMLHitchhikersGuide"><img src="./scheme_files/svgrepo-signpost-fill.svg" width="16" height="16">Hitchhiker's Guide</a>
</div>

            </div>
            
            <div>
<!-- Ezoic - side2 - top_of_page -->
<div class="ezoic-wrap">
<span id="ezoic-pub-ad-placeholder-680"></span><!-- ezoic_pub_ad_placeholder-680-top_of_page-120x600-680-nonexxxnonexxxxxxezmaxscaleval100 --><!-- ezoic_pub_ad_placeholder-680-top_of_page-160x600-680-nonexxxnonexxxxxxezmaxscaleval100 -->
</div>
<!-- End Ezoic - side2 - top_of_page -->
            </div>


            <div class="merged">
<!-- Ezoic - alpha-bloc2 - top_of_page -->
<span id="ezoic-pub-ad-placeholder-683"></span><!-- ezoic_pub_ad_placeholder-683-top_of_page-250x250-683-nonexxxnonexxxxxxezmaxscaleval100 --><!-- ezoic_pub_ad_placeholder-683-top_of_page-300x250-683-nonexxxnonexxxxxxezmaxscaleval100 -->
<!-- End Ezoic - alpha-bloc2 - top_of_page -->
            </div>

            
        </div><!-- grid -->
    </aside>

    <header id="B3">
<div class="menu1">
<a id="titem10" href="https://plantuml.com/ru/sequence-diagram">последовательност</a>
<a id="titem20" href="https://plantuml.com/ru/use-case-diagram">прецедентов</a>
<a id="titem30" href="https://plantuml.com/ru/class-diagram">классов</a>
<a id="titem40" href="https://plantuml.com/ru/activity-diagram-beta">активности</a>
<a id="titem50" href="https://plantuml.com/ru/component-diagram">компонент</a>
<a id="titem60" href="https://plantuml.com/ru/state-diagram">состояний</a>
<a id="titem70" href="https://plantuml.com/ru/object-diagram">объект</a>
<a id="titem80" href="https://plantuml.com/ru/deployment-diagram">развёртывания</a>
<a id="titem90" href="https://plantuml.com/ru/timing-diagram">синхронизации</a>

<a id="titem99" href="https://plantuml.com/ru/regex">Regex</a>
<a id="titem100" href="https://plantuml.com/ru/nwdiag">Network</a>
<a id="titem110" href="https://plantuml.com/ru/salt">Wireframe</a>
<a id="titem120" href="https://plantuml.com/ru/archimate-diagram">Archimate</a>
<a id="titem130" href="https://plantuml.com/ru/gantt-diagram">Gantt</a>
<a id="titem140" href="https://plantuml.com/ru/mindmap-diagram">MindMap</a>
<a id="titem150" href="https://plantuml.com/ru/wbs-diagram">WBS</a>
<a id="titem151" href="https://plantuml.com/ru/ebnf">EBNF</a>
<a id="titem160" href="https://plantuml.com/ru/json">JSON</a>
<a id="titem170" href="https://plantuml.com/ru/yaml">YAML</a>

<div class="menu1-tail"></div>
</div>
        <div id="magic">
<div class="menu1">
<a id="titem10" href="https://plantuml.com/ru/sequence-diagram">последовательност</a>
<a id="titem20" href="https://plantuml.com/ru/use-case-diagram">прецедентов</a>
<a id="titem30" href="https://plantuml.com/ru/class-diagram">классов</a>
<a id="titem40" href="https://plantuml.com/ru/activity-diagram-beta">активности</a>
<a id="titem50" href="https://plantuml.com/ru/component-diagram">компонент</a>
<a id="titem60" href="https://plantuml.com/ru/state-diagram">состояний</a>
<a id="titem70" href="https://plantuml.com/ru/object-diagram">объект</a>
<a id="titem80" href="https://plantuml.com/ru/deployment-diagram">развёртывания</a>
<a id="titem90" href="https://plantuml.com/ru/timing-diagram">синхронизации</a>

<a id="titem99" href="https://plantuml.com/ru/regex">Regex</a>
<a id="titem100" href="https://plantuml.com/ru/nwdiag">Network</a>
<a id="titem110" href="https://plantuml.com/ru/salt">Wireframe</a>
<a id="titem120" href="https://plantuml.com/ru/archimate-diagram">Archimate</a>
<a id="titem130" href="https://plantuml.com/ru/gantt-diagram">Gantt</a>
<a id="titem140" href="https://plantuml.com/ru/mindmap-diagram">MindMap</a>
<a id="titem150" href="https://plantuml.com/ru/wbs-diagram">WBS</a>
<a id="titem151" href="https://plantuml.com/ru/ebnf">EBNF</a>
<a id="titem160" href="https://plantuml.com/ru/json">JSON</a>
<a id="titem170" href="https://plantuml.com/ru/yaml">YAML</a>

<div class="menu1-tail"></div>
</div>
            <img src="./scheme_files/svgrepo-left.svg" alt="" style="width:30px;height:30px">
        </div><!-- magic -->
        <div id="magic2">
<a href="https://plantuml.com/ru-dark/">
<img src="./scheme_files/svgrepo-uxwing-light-mode-toggle.svg" width="40" height="20">
</a>
        </div><!-- magic2 -->
    </header>

    <main id="D7">

<style>
    #haut1 {
        margin: 15px 0 10px;
        padding: 0;
        min-height: 50px;
    }

    #donate {
        padding-top: 10px;
        min-height: 30px;
    }
</style>

<div id="haut1">

<!-- c --><div style="float:left;">
<!-- a simple div with some links -->
<div class="breadcrumb">
<a href="https://plantuml.com/ru/sitemap">PlantUML</a>
<a href="https://plantuml.com/ru/sitemap-news-and-information">News and information</a>
<a href="https://plantuml.com/ru/index">PlantUML in a nutshell</a>
<a href="https://plantuml.com/ru/#"></a>
</div>


    <div id="donate">

&nbsp;

<a href="https://github.com/sponsors/plantuml/" style="text-decoration: none;">
<img src="./scheme_files/plantuml">
</a>

&nbsp;

<a href="https://www.patreon.com/bePatron?patAmt=1&amp;u=527450&amp;rid=152970" style="text-decoration: none;">
<img src="./scheme_files/patreon-122-chocolate">
</a>

&nbsp;

<a href="https://liberapay.com/plantuml/donate" style="text-decoration: none;">
<img src="./scheme_files/plantuml(1)">
</a>

&nbsp;

<a href="https://plantuml.com/en/paypal" style="text-decoration: none;">
<img src="./scheme_files/paypal-297-skyblue">
</a>

<!--
 

<a href="https://github.com/sponsors/plantuml" style="text-decoration: none;">
<img src="https://img.shields.io/github/sponsors/plantuml?label=github">
</a>

-->
    </div><!-- donate -->
</div><!-- c -->

<!-- e --><div style="float:right; margin:3px 0;">

<!-- https://github.com/joielechong/iso-country-flags-svg-collection -->

<!-- https://www.flaticon.com/packs/international-flags -->
<!-- https://flagicons.lipis.dev/?continent=Europe -->
<!-- https://flagpedia.net/download/icons -->

<!-- https://www.countryflags.io/ -->

<style>
#langlist {
display: flex;
justify-content: space-between;
width: 317px;
height: 16px;
margin: 3px 10px 3px 0;
}

.sel2 {
  border: 2px solid #fefefe;
}
.nosel2 {
  border: 2px solid #fefefe;
  filter: grayscale(100%) opacity(75%);
}
.sel2:hover, .nosel2:hover {
  cursor: pointer;
  border: 2px solid #0366d6;
  border-spacing: 0;
  filter: grayscale(0%);
  filter: contrast(200%);
  filter: brightness(150%);
}
#flag1,#flag2,#flag3,#flag4,#flag5,#flag6,#flag7,#flag8 {
background: url(/flags22.png);
background-repeat: no-repeat;
background-clip: content-box;
width: 22px;
height: 16px;
}
#flag2 {
background-position: -22px 0px;
}
#flag3 {
background-position: -44px 0px;
}
#flag4 {
background-position: -66px 0px;
}
#flag5 {
background-position: -88px 0px;
}
#flag6 {
background-position: -110px 0px;
}
#flag8 {
background-position: -132px 0px;
}
</style>

<div id="langlist">



<div id="flag1" onclick="location.href='/en/'" class="nosel2"></div>

<div id="flag2" onclick="location.href='/de/'" class="nosel2"></div>


<div id="flag3" onclick="location.href='/es/'" class="nosel2"></div>


<div id="flag4" onclick="location.href='/fr/'" class="nosel2"></div>


<div id="flag5" onclick="location.href='/ja/'" class="nosel2"></div>


<div id="flag6" onclick="location.href='/ko/'" class="nosel2"></div>


<div id="flag8" onclick="location.href='/zh/'" class="nosel2"></div>





</div><!-- langlist -->
</div><!-- e -->

</div><!-- haut1 -->

<!-- =================== Browser extension promo banner =================== -->
<style>
#ext-promo {
    clear: both;
    margin: 12px 0 18px;
    padding: 12px 18px;
    border-radius: 5px;
    font-size: 14px;
    line-height: 1.5;
    display: flex;
    align-items: center;
    gap: 14px;
    flex-wrap: wrap;
}
#ext-promo .ext-promo-icon {
    font-size: 22px;
    line-height: 1;
    flex-shrink: 0;
}
#ext-promo .ext-promo-text {
    flex: 1;
    min-width: 240px;
}
#ext-promo .ext-promo-links {
    display: flex;
    gap: 8px;
    flex-wrap: wrap;
    flex-shrink: 0;
}
#ext-promo .ext-promo-links a {
    display: inline-block;
    padding: 5px 12px;
    border-radius: 4px;
    color: #fff;
    text-decoration: none;
    font-weight: 500;
    font-size: 13px;
    white-space: nowrap;
    transition: background 0.15s;
}
#ext-promo .ext-promo-links a.firefox:hover {
    background: #a64200;
}
#ext-promo .ext-promo-links a.chrome:hover {
    background: #0250a8;
}
</style>
<style>
#ext-promo {
    border: 1px solid #c9e0f7;
    border-left: 4px solid #0366d6;
    background: linear-gradient(90deg, #f0f7ff 0%, #f8fbff 100%);
    color: #24292e;
}
#ext-promo .ext-promo-text strong { color: #0366d6; }
#ext-promo .ext-promo-links a.chrome { background: #0366d6; }
#ext-promo .ext-promo-links a.firefox { background: #d75500; }
</style>

<div id="ext-promo">
    <span class="ext-promo-icon">🧩</span>
    <div class="ext-promo-text">
        <strong>New!</strong> Render PlantUML diagrams directly inside GitHub
        with <a href="https://github.com/plantuml/plantuml-for-github">our official browser extension</a> —
        No server. No tokens. No tracking. Zero permissions but clipboard. —
        Try it out and let us know what you think!
    </div>
    <div class="ext-promo-links">
        <a class="chrome" href="https://chromewebstore.google.com/detail/plantuml-for-github/lbokhidfopkdehkmlmpaabacljoediic" target="_blank" rel="noopener">Add to Chrome</a>
        <a class="firefox" href="https://addons.mozilla.org/en-US/firefox/addon/plantuml-for-github/" target="_blank" rel="noopener">Add to Firefox</a>
    </div>
</div>
<!-- =================== End extension promo banner =================== -->

<p style="clear:both;">


<style>
#mitem10 {
 color:#0366d6;
 background-color: #fefefe;
}
#mitem10 img {
filter: brightness(0) saturate(100%) invert(23%) sepia(44%) saturate(7029%) hue-rotate(203deg) brightness(94%) contrast(98%);
}
.menuside2:hover #mitem10 {
	color:#5e6d7d;
}
.menuside2:hover #mitem10:hover {
	color:#0366d6;
}
.menuside2:hover #mitem10 img {
filter: brightness(0) saturate(100%) invert(42%) sepia(22%) saturate(385%) hue-rotate(170deg) brightness(92%) contrast(84%);
}
.menuside2:hover #mitem10:hover img {
filter: brightness(0) saturate(100%) invert(23%) sepia(44%) saturate(7029%) hue-rotate(203deg) brightness(94%) contrast(98%);
}
</style>


<style>
.code3-container {
	display: flex;
	gap: 20px;
	margin: 20px 0;
	width: 100%;
}
.code3-container textarea {
	flex: 1 1 0;
	min-width: 0;
	min-height: 200px;
	resize: vertical;
	padding: 15px;
	border-radius: 10px;
	border: 1px solid #ddd;
	box-shadow: 0 2px 4px rgba(0,0,0,0.1);
	font-family: monospace;
	font-size: 14px;
	background: #fefefe;
	color: #24292e;
}
.code3-container #out {
	flex: 1 1 0;
	min-width: 0;
	overflow: hidden;
	padding: 15px;
	border-radius: 10px;
	background: #fefefe;
}
.code3-container #out img,
.code3-container #out svg {
	max-width: 100%;
	height: auto;
	display: block;
}
</style>

</p><p style="font-size:14px;color:#666;font-style:italic;">
This editor runs entirely in your browser thanks to our
<a href="https://plantuml.github.io/plantuml/js-plantuml/index-collection.html">JavaScript rendering engine</a>.
Edit the code on the left and see the diagram update instantly!
</p>

<div class="code3-container">
<textarea id="src" rows="10" spellcheck="false" autocorrect="off" autocapitalize="off" autocomplete="off">@startuml
Alice-&gt;Bob : Hello
return ok
@enduml</textarea>
<div id="out"><svg xmlns="http://www.w3.org/2000/svg" version="1.1" viewBox="0 0 362 309" width="362" height="309"><defs></defs><g><g class="message" data-entity-1="part1" data-entity-2="part2" id="msg1" data-source-line="3"></g><g class="message" data-entity-1="part1" data-entity-2="part2" id="msg2" data-source-line="4"></g><g class="message" data-entity-1="part2" data-entity-2="part2" id="msg3" data-source-line="5"></g><g class="message" data-entity-1="part2" data-entity-2="part1" id="msg4" data-source-line="6"></g><g class="participant-lifeline" data-qualified-name="......." data-entity-uid="part1" id="part1-lifeline" data-source-line="1"><g><title>.......</title><rect x="31.16" y="81" width="8" height="147" fill="#00000000" stroke="#00000000" stroke-width="0"></rect><line x1="34.66" y1="81" x2="34.66" y2="228" stroke="#181818" stroke-width="0.5" stroke-dasharray="5,5"></line></g></g><g class="participant-lifeline" data-qualified-name="Git" data-entity-uid="part2" id="part2-lifeline" data-source-line="2"><g><title>GitHub Pages</title><rect x="195.19" y="81" width="8" height="147" fill="#00000000" stroke="#00000000" stroke-width="0"></rect><line x1="198.69" y1="81" x2="198.69" y2="228" stroke="#181818" stroke-width="0.5" stroke-dasharray="5,5"></line></g></g><g class="participant participant-head" data-qualified-name="......." data-entity-uid="part1" id="part1-head" data-source-line="1"><text x="5" y="78" font-size="14" fill="#000000" xml:space="preserve" style="white-space: pre" font-family="sans-serif">Студент</text><circle cx="34.66" cy="13.5" r="8" fill="#E2E2F0" stroke="#181818" stroke-width="0.5"></circle><path d="M34.66,21.5 L34.66,48.5 M21.66,29.5 L47.66,29.5 M34.66,48.5 L21.66,63.5 M34.66,48.5 L47.66,63.5" fill="#00000000" stroke="#181818" stroke-width="0.5"></path></g><g class="participant participant-head" data-qualified-name="Git" data-entity-uid="part2" id="part2-head" data-source-line="2"><rect x="148.11" y="50" width="101.16" height="30" rx="2.5" ry="2.5" fill="#E2E2F0" stroke="#181818" stroke-width="0.5"></rect><text x="155.11" y="70" font-size="14" fill="#000000" xml:space="preserve" style="white-space: pre" font-family="sans-serif">GitHub Pages</text></g><g class="participant participant-tail" data-qualified-name="......." data-entity-uid="part1" id="part1-tail" data-source-line="1"><text x="5" y="241" font-size="14" fill="#000000" xml:space="preserve" style="white-space: pre" font-family="sans-serif">Студент</text><circle cx="34.66" cy="252.5" r="8" fill="#E2E2F0" stroke="#181818" stroke-width="0.5"></circle><path d="M34.66,260.5 L34.66,287.5 M21.66,268.5 L47.66,268.5 M34.66,287.5 L21.66,302.5 M34.66,287.5 L47.66,302.5" fill="#00000000" stroke="#181818" stroke-width="0.5"></path></g><g class="participant participant-tail" data-qualified-name="Git" data-entity-uid="part2" id="part2-tail" data-source-line="2"><rect x="148.11" y="228" width="101.16" height="30" rx="2.5" ry="2.5" fill="#E2E2F0" stroke="#181818" stroke-width="0.5"></rect><text x="155.11" y="248" font-size="14" fill="#000000" xml:space="preserve" style="white-space: pre" font-family="sans-serif">GitHub Pages</text></g><g class="message" data-entity-1="part1" data-entity-2="part2" id="msg1" data-source-line="3"><polygon points="186.69,106 196.69,110 186.69,114 190.69,110" fill="#181818" stroke="#181818" stroke-width="1"></polygon><line x1="34.66" y1="110" x2="192.69" y2="110" stroke="#181818" stroke-width="1"></line><text x="41.66" y="105" font-size="13" fill="#000000" xml:space="preserve" style="white-space: pre" font-family="sans-serif">Редактирует .md файл</text></g><g class="message" data-entity-1="part1" data-entity-2="part2" id="msg2" data-source-line="4"><polygon points="186.69,135 196.69,139 186.69,143 190.69,139" fill="#181818" stroke="#181818" stroke-width="1"></polygon><line x1="34.66" y1="139" x2="192.69" y2="139" stroke="#181818" stroke-width="1"></line><text x="41.66" y="134" font-size="13" fill="#000000" xml:space="preserve" style="white-space: pre" font-family="sans-serif">Нажимает Commit</text></g><g class="message" data-entity-1="part2" data-entity-2="part2" id="msg3" data-source-line="5"><line x1="198.69" y1="168" x2="240.69" y2="168" stroke="#181818" stroke-width="1"></line><line x1="240.69" y1="168" x2="240.69" y2="181" stroke="#181818" stroke-width="1"></line><line x1="199.69" y1="181" x2="240.69" y2="181" stroke="#181818" stroke-width="1"></line><polygon points="209.69,177 199.69,181 209.69,185 205.69,181" fill="#181818" stroke="#181818" stroke-width="1"></polygon><text x="205.69" y="163" font-size="13" fill="#000000" xml:space="preserve" style="white-space: pre" font-family="sans-serif">Автоматическая сборка</text></g><g class="message" data-entity-1="part2" data-entity-2="part1" id="msg4" data-source-line="6"><polygon points="45.66,206 35.66,210 45.66,214 41.66,210" fill="#181818" stroke="#181818" stroke-width="1"></polygon><line x1="39.66" y1="210" x2="197.69" y2="210" stroke="#181818" stroke-width="1"></line><text x="51.66" y="205" font-size="13" fill="#000000" xml:space="preserve" style="white-space: pre" font-family="sans-serif">Выдает ссылку на сайт</text></g><?plantuml-src TKux2i904EqznP1U3s1XOw6bLrW_I8feI6AlYM2HGh4Nz0PHZCJ4U8OtD_Aj868XMypEc_SpesWU24uQQu8hSjGQDtmJHEx8zSqi4gVdHlt5K0PcEWaTCQ4GQFmAfDcnQ5jm9715Xb9Z5Bea9UUvvOr5ruJlgFvA3xpVKE31QKNTkUSnYSSlPuSBZP-MymxOaBb2oMqh_9pnrALTFwhVB1hiDNttim6wuajHiMmYg95P2tRK-0K0?></g></svg></div>
</div>

<script src="./scheme_files/viz-global.js.Без названия"></script>
<script type="module">
	import { render } from "https://plantuml.github.io/plantuml/js-plantuml/plantuml.js";
	const renderOptions = {};
	const textarea = document.getElementById("src");
	function renderNow() {
		render(textarea.value.split(/\r\n|\r|\n/), "out", renderOptions);
	}
	textarea.addEventListener("input", renderNow);
	renderNow();
</script>


<a style="position:relative;top:-38px;" name="3928870aae1e447d"></a>
<!--heading--><h1 class="chap"><div class="dropdown"><button class="dropbtn"><img width="16" height="16" src="./scheme_files/edit1.svg"></button><div class="dropdown-content"><a href="http://alphadoc.plantuml.com/cmp/dokuwiki/ru/index#0"><img width="20" height="20" src="./scheme_files/dokuwiki.png">Edit in Dokuwiki</a><a href="http://alphadoc.plantuml.com/cmp/asciidoc/ru/index#0"><img width="20" height="20" src="./scheme_files/asciidoc32.png">Edit in Asciidoc</a><a href="http://alphadoc.plantuml.com/cmp/markdown/ru/index#0"><img width="20" height="20" src="./scheme_files/markdown.png">Edit in Markdown</a></div></div>🌱 PlantUML с первого взгляда</h1>
<style>
#sticky-647-wrap {
    position: -webkit-sticky;
    position: sticky;
    top: 30px;
    z-index: 9;
    background: #fefefe;
}
</style>
<!-- Ezoic - under_first_paragraph - under_first_paragraph -->
<div id="sticky-647-wrap">
<span id="ezoic-pub-ad-placeholder-647"></span><!-- ezoic_pub_ad_placeholder-647-under_page_title-728x90-647-nonexxxnonexxxxxxezmaxscaleval100 --><!-- ezoic_pub_ad_placeholder-647-under_page_title-468x60-647-nonexxxnonexxxxxxezmaxscaleval100 --><!-- ezoic_pub_ad_placeholder-647-under_page_title-320x50-647-nonexxxnonexxxxxxezmaxscaleval100 --><!-- ezoic_pub_ad_placeholder-647-under_page_title-320x100-647-nonexxxnonexxxxxxezmaxscaleval100 --><!-- ezoic_pub_ad_placeholder-647-under_page_title-300x50v2-647-nonexxxnonexxxxxxezmaxscaleval100 -->
</div>
<!-- End Ezoic - under_first_paragraph - under_first_paragraph -->
<a style="position:relative;top:-38px;" name="544eb4250eacd956"></a>
<!--heading--><h2 class="chap"><img onclick="window.scrollTo(0,0);" title="Back to top" src="./scheme_files/backtop1.svg" width="20" height="20" class="backtop"><div class="dropdown"><button class="dropbtn"><img width="16" height="16" src="./scheme_files/edit1.svg"></button><div class="dropdown-content"><a href="http://alphadoc.plantuml.com/cmp/dokuwiki/ru/index#1"><img width="20" height="20" src="./scheme_files/dokuwiki.png">Edit in Dokuwiki</a><a href="http://alphadoc.plantuml.com/cmp/asciidoc/ru/index#1"><img width="20" height="20" src="./scheme_files/asciidoc32.png">Edit in Asciidoc</a><a href="http://alphadoc.plantuml.com/cmp/markdown/ru/index#1"><img width="20" height="20" src="./scheme_files/markdown.png">Edit in Markdown</a></div></div>🚀 Начало работы</h2>
<p></p>
<strong>PlantUML</strong> - это универсальный инструмент, позволяющий быстро и просто создавать широкий спектр диаграмм.
<p></p>
Используя простой и интуитивно понятный язык, пользователи могут без труда создавать различные типы диаграмм.
Для подробного изучения возможностей и синтаксиса языка обратитесь к <a href="https://plantuml.com/ru/guide">Справочному руководству по языку PlantUML</a>.
<p></p>
Если вы новичок в PlantUML, мы рекомендуем начать со <a href="https://plantuml.com/ru/starting">страницы быстрого запуска</a>, чтобы быстро освоиться
и начать работать. Если у вас возникнут вопросы, наша <a href="https://plantuml.com/ru/faq">страница F.A.Q.</a> является ценным ресурсом.
Кроме того, PlantUML может быть легко интегрирован с <a href="https://plantuml.com/ru/running">множеством других инструментов</a> для улучшения вашего рабочего процесса.
<a style="position:relative;top:-38px;" name="2a2b6e53c5a4c591"></a>
<!--heading--><h2 class="chap"><img onclick="window.scrollTo(0,0);" title="Back to top" src="./scheme_files/backtop1.svg" width="20" height="20" class="backtop"><div class="dropdown"><button class="dropbtn"><img width="16" height="16" src="./scheme_files/edit1.svg"></button><div class="dropdown-content"><a href="http://alphadoc.plantuml.com/cmp/dokuwiki/ru/index#2"><img width="20" height="20" src="./scheme_files/dokuwiki.png">Edit in Dokuwiki</a><a href="http://alphadoc.plantuml.com/cmp/asciidoc/ru/index#2"><img width="20" height="20" src="./scheme_files/asciidoc32.png">Edit in Asciidoc</a><a href="http://alphadoc.plantuml.com/cmp/markdown/ru/index#2"><img width="20" height="20" src="./scheme_files/markdown.png">Edit in Markdown</a></div></div>🧩 Поддерживаемые UML-диаграммы</h2>
<p></p>
С помощью PlantUML вы можете создавать хорошо структурированные UML-диаграммы, включая, но не ограничиваясь ими:
<p></p>
<ul>
<li><a href="https://plantuml.com/ru/sequence-diagram">Диаграмма последовательности</a></li>
<li><a href="https://plantuml.com/ru/use-case-diagram">Диаграмма случая использования</a></li>
<li><a href="https://plantuml.com/ru/class-diagram">Диаграмма классов</a></li>
<li><a href="https://plantuml.com/ru/object-diagram">Диаграмма объектов</a></li>
<li><a href="https://plantuml.com/ru/activity-diagram-beta">Диаграмма деятельности</a> (Найти <a href="https://plantuml.com/ru/activity-diagram-legacy">синтаксис устаревшей версии можно здесь</a>)</li>
<li><a href="https://plantuml.com/ru/component-diagram">Диаграмма компонентов</a></li>
<li><a href="https://plantuml.com/ru/deployment-diagram">Диаграмма развертывания</a></li>
<li><a href="https://plantuml.com/ru/state-diagram">Диаграмма состояний</a></li>
<li><a href="https://plantuml.com/ru/timing-diagram">Временная диаграмма</a></li>
</ul>
<a style="position:relative;top:-38px;" name="6255d7ba3ee1e2ec"></a>
<!--heading--><h2 class="chap"><img onclick="window.scrollTo(0,0);" title="Back to top" src="./scheme_files/backtop1.svg" width="20" height="20" class="backtop"><div class="dropdown"><button class="dropbtn"><img width="16" height="16" src="./scheme_files/edit1.svg"></button><div class="dropdown-content"><a href="http://alphadoc.plantuml.com/cmp/dokuwiki/ru/index#3"><img width="20" height="20" src="./scheme_files/dokuwiki.png">Edit in Dokuwiki</a><a href="http://alphadoc.plantuml.com/cmp/asciidoc/ru/index#3"><img width="20" height="20" src="./scheme_files/asciidoc32.png">Edit in Asciidoc</a><a href="http://alphadoc.plantuml.com/cmp/markdown/ru/index#3"><img width="20" height="20" src="./scheme_files/markdown.png">Edit in Markdown</a></div></div>📈 Поддерживаемые диаграммы, не относящиеся к UML</h2>
<p></p>
Помимо традиционных диаграмм UML, PlantUML также поддерживает создание различных других типов диаграмм, таких как:
<p></p>
<ul>
<li><a href="https://plantuml.com/ru/json">JSON-данные</a></li>
<li><a href="https://plantuml.com/ru/yaml">Данные YAML</a></li>
<li><a href="https://plantuml.com/ru/ebnf">EBNF-диаграмма</a></li>
<li><a href="https://plantuml.com/ru/regex">Диаграмма Regex</a></li>
<li><a href="https://plantuml.com/ru/nwdiag">Сетевая диаграмма (nwdiag)</a></li>
<li><a href="https://plantuml.com/ru/salt">Макеты пользовательского интерфейса (соль)</a></li>
<li><a href="https://plantuml.com/ru/archimate-diagram">Диаграмма архитекторов</a></li>
<li>[Язык спецификаций и описания (SDL)](activity-diagram-beta#sdl)</li>
<li><a href="https://plantuml.com/ru/ditaa">Диаграмма Дитаа</a></li>
<li><a href="https://plantuml.com/ru/gantt-diagram">Диаграмма Ганта</a></li>
<li><a href="https://plantuml.com/ru/chronology-diagram">Диаграмма хронологии</a></li>
<li><a href="https://plantuml.com/ru/mindmap-diagram">Диаграмма MindMap</a></li>
<li><a href="https://plantuml.com/ru/wbs-diagram">WBS-диаграмма</a></li>
<li><a href="https://plantuml.com/ru/ascii-math">Математика с нотацией AsciiMath или JLaTeXMath</a></li>
<li><a href="https://plantuml.com/ru/ie-diagram">Диаграмма информационной инженерии (IE)</a></li>
<li><a href="https://plantuml.com/ru/er-diagram">Диаграмма отношений между сущностями (ER)</a></li>
<li><a href="https://plantuml.com/ru/chart-diagram">Chart diagram</a></li>
<li><a href="https://plantuml.com/ru/files-diagram">Files diagram</a></li>
</ul>
<p></p>
<p></p>
<ul>
<li><a href="https://plantuml.com/ru/files-diagram">Files (files tree) diagram</a></li>
</ul>
<center><div class="tago">WARNING</div>&nbsp;<b>This translation need to be updated.</b>&nbsp;<div class="tago">WARNING</div></center>
<a style="position:relative;top:-38px;" name="1fc1d85af1b3cf73"></a>
<!--heading--><h2 class="chap"><img onclick="window.scrollTo(0,0);" title="Back to top" src="./scheme_files/backtop1.svg" width="20" height="20" class="backtop"><div class="dropdown"><button class="dropbtn"><img width="16" height="16" src="./scheme_files/edit1.svg"></button><div class="dropdown-content"><a href="http://alphadoc.plantuml.com/cmp/dokuwiki/ru/index#4"><img width="20" height="20" src="./scheme_files/dokuwiki.png">Edit in Dokuwiki</a><a href="http://alphadoc.plantuml.com/cmp/asciidoc/ru/index#4"><img width="20" height="20" src="./scheme_files/asciidoc32.png">Edit in Asciidoc</a><a href="http://alphadoc.plantuml.com/cmp/markdown/ru/index#4"><img width="20" height="20" src="./scheme_files/markdown.png">Edit in Markdown</a></div></div>📣 Дополнительные возможности</h2>
<p></p>
Повысьте динамичность и информативность ваших диаграмм с помощью этих дополнительных возможностей:
<p></p>
<ul>
<li><a href="https://plantuml.com/ru/link">Гиперссылки и всплывающие подсказки</a> для обеспечения дополнительного контекста и интерактивности</li>
<li><a href="https://plantuml.com/ru/creole">Богатое форматирование текста, смайлики, Unicode и иконки с Creole</a> для визуально привлекательного представления</li>
<li><a href="https://plantuml.com/ru/openiconic">Иконки OpenIconic</a> для улучшенного визуального представления</li>
<li><a href="https://plantuml.com/ru/sprite">Иконки Sprite</a> для добавления пользовательских символов</li>
<li><a href="https://plantuml.com/ru/ascii-math">Математические выражения AsciiMath</a> для точного математического представления</li>
</ul>
<a style="position:relative;top:-38px;" name="114d02427b7dc147"></a>
<!--heading--><h2 class="chap"><img onclick="window.scrollTo(0,0);" title="Back to top" src="./scheme_files/backtop1.svg" width="20" height="20" class="backtop"><div class="dropdown"><button class="dropbtn"><img width="16" height="16" src="./scheme_files/edit1.svg"></button><div class="dropdown-content"><a href="http://alphadoc.plantuml.com/cmp/dokuwiki/ru/index#5"><img width="20" height="20" src="./scheme_files/dokuwiki.png">Edit in Dokuwiki</a><a href="http://alphadoc.plantuml.com/cmp/asciidoc/ru/index#5"><img width="20" height="20" src="./scheme_files/asciidoc32.png">Edit in Asciidoc</a><a href="http://alphadoc.plantuml.com/cmp/markdown/ru/index#5"><img width="20" height="20" src="./scheme_files/markdown.png">Edit in Markdown</a></div></div>📥 Форматы ввода</h2>
<p></p>
PlantUML позволяет генерировать диаграммы из различных форматов исходных данных:
<ul>
<li><a href="https://plantuml.com/ru/sources">Исходные данные: <em>Как и где могут быть написаны диаграммы</em></a></li>
</ul>
<p></p>
Вы можете выбрать одну из различных внутренних кодировок:
<ul>
<li><a href="https://plantuml.com/ru/text-encoding">Текстовая кодировка PlantUML</a></li>
</ul>
<a style="position:relative;top:-38px;" name="6e560fe71abef84f"></a>
<!--heading--><h2 class="chap"><img onclick="window.scrollTo(0,0);" title="Back to top" src="./scheme_files/backtop1.svg" width="20" height="20" class="backtop"><div class="dropdown"><button class="dropbtn"><img width="16" height="16" src="./scheme_files/edit1.svg"></button><div class="dropdown-content"><a href="http://alphadoc.plantuml.com/cmp/dokuwiki/ru/index#6"><img width="20" height="20" src="./scheme_files/dokuwiki.png">Edit in Dokuwiki</a><a href="http://alphadoc.plantuml.com/cmp/asciidoc/ru/index#6"><img width="20" height="20" src="./scheme_files/asciidoc32.png">Edit in Asciidoc</a><a href="http://alphadoc.plantuml.com/cmp/markdown/ru/index#6"><img width="20" height="20" src="./scheme_files/markdown.png">Edit in Markdown</a></div></div>⚙ Движки компоновки и опции</h2>
<p></p>
PlantUML позволяет использовать несколько различных <a href="https://plantuml.com/ru/layout-engines">движков компоновки</a>:
<p></p>
<ul>
<li><a href="https://plantuml.com/ru/graphviz-dot">Graphviz</a> — движок по умолчанию. Использует внешнюю программу;</li>
<li><a href="https://plantuml.com/ru/smetana02">Smetana</a>. <em>(Используйте <code class="cod">!pragma layout smetana</code> в файле или <code class="cod">-Playout=smetana</code> в командной строке.)</em> Порт Graphviz на Java. Отличается немного более прямыми стрелками;</li>
<li><a href="https://plantuml.com/ru/vizjs">VizJs</a> использует JavaScript. <em>(Используйте <code class="cod">-graphvizdot vizjs</code> в командной строке.)</em> Имеет свойство увеличивать расстояние между узлами, что приводит к увеличению диаграммы;</li>
<li><a href="https://plantuml.com/ru/elk">ELK (Eclipse Layout Kernel)</a>. <em>(Используйте <code class="cod">!pragma layout elk</code>  в файле или <code class="cod">-Playout=elk</code> в командной строке.)</em> Поддерживает только ортогональную компоновку и не охватывает всех возможностей.</li>
</ul>
<p></p>
<a href="https://plantuml.com/ru/sequence-diagram">Диаграммы последовательностей</a> имеют 2 движка:
<ul>
<li><em>Puma</em> — старый и все еще используемый по умолчанию;</li>
<li><a href="https://plantuml.com/ru/teoz">Teoz</a> <em>(Используйте <code class="cod">!pragma teoz true</code>  в файле или <code class="cod">-Pteoz=true</code> в командной строке)</em> — новый движок, обладающий некоторыми уникальными возможностями: <em>привязки(именованные стрелки/сообщения), длительность, вложенные блоки...</em>.</li>
</ul>
<p></p>
<blockquote>
Добиться хорошей компоновки с помощью PlantUML иногда бывает непросто. 
<em>Смотрите <a href="https://isgb.otago.ac.nz/infosci/mark.george/Wiki/wiki/PlantUML%20GraphViz%20Layout">PlantUML GraphViz Layout</a> от Марка Джорджа из Университета Отаго для получения дополнительных советов.</em>
</blockquote>
<p></p>
<center><div class="tago">WARNING</div>&nbsp;<b>This translation need to be updated.</b>&nbsp;<div class="tago">WARNING</div></center>
<a style="position:relative;top:-38px;" name="ffc0ab0a7e38b981"></a>
<!--heading--><h2 class="chap"><img onclick="window.scrollTo(0,0);" title="Back to top" src="./scheme_files/backtop1.svg" width="20" height="20" class="backtop"><div class="dropdown"><button class="dropbtn"><img width="16" height="16" src="./scheme_files/edit1.svg"></button><div class="dropdown-content"><a href="http://alphadoc.plantuml.com/cmp/dokuwiki/ru/index#7"><img width="20" height="20" src="./scheme_files/dokuwiki.png">Edit in Dokuwiki</a><a href="http://alphadoc.plantuml.com/cmp/asciidoc/ru/index#7"><img width="20" height="20" src="./scheme_files/asciidoc32.png">Edit in Asciidoc</a><a href="http://alphadoc.plantuml.com/cmp/markdown/ru/index#7"><img width="20" height="20" src="./scheme_files/markdown.png">Edit in Markdown</a></div></div>📤 Выходные форматы</h2>
<p></p>
Экспорт диаграмм в различные форматы, соответствующие вашим потребностям, включая:
<p></p>
<ul>
<li>PNG для удобного обмена изображениями</li>
<li><a href="https://plantuml.com/ru/svg">SVG</a> для масштабируемой векторной графики</li>
<li><a href="https://plantuml.com/ru/latex">LaTeX</a> для высококачественного набора текста</li>
<li>ASCII <a href="https://plantuml.com/ru/ascii-art">art</a> <em>(доступно только для диаграмм последовательности)</em> для текстового представления</li>
</ul>
<a style="position:relative;top:-38px;" name="2c4ec809d7f75591"></a>
<!--heading--><h2 class="chap"><img onclick="window.scrollTo(0,0);" title="Back to top" src="./scheme_files/backtop1.svg" width="20" height="20" class="backtop"><div class="dropdown"><button class="dropbtn"><img width="16" height="16" src="./scheme_files/edit1.svg"></button><div class="dropdown-content"><a href="http://alphadoc.plantuml.com/cmp/dokuwiki/ru/index#8"><img width="20" height="20" src="./scheme_files/dokuwiki.png">Edit in Dokuwiki</a><a href="http://alphadoc.plantuml.com/cmp/asciidoc/ru/index#8"><img width="20" height="20" src="./scheme_files/asciidoc32.png">Edit in Asciidoc</a><a href="http://alphadoc.plantuml.com/cmp/markdown/ru/index#8"><img width="20" height="20" src="./scheme_files/markdown.png">Edit in Markdown</a></div></div>🎉 Наслаждайтесь</h2>
<p></p>
Начните работу сегодня и расширьте свои возможности создания диаграмм с помощью <strong>PlantUML</strong>. Превращайте свои идеи в четкие и профессиональные диаграммы без особых усилий 🎉!


</main>

    
<aside id="C6">
<!--toc-->
<div id="toc">
<ul>
<li><a href="https://plantuml.com/ru/#544eb4250eacd956">🚀 Начало работы</a>
</li><li><a href="https://plantuml.com/ru/#2a2b6e53c5a4c591">🧩 Поддерживаемые UML-диаграммы</a>
</li><li><a href="https://plantuml.com/ru/#6255d7ba3ee1e2ec">📈 Поддерживаемые диаграммы, не относящиеся к UML</a>
</li><li><a href="https://plantuml.com/ru/#1fc1d85af1b3cf73">📣 Дополнительные возможности</a>
</li><li><a href="https://plantuml.com/ru/#114d02427b7dc147">📥 Форматы ввода</a>
</li><li><a href="https://plantuml.com/ru/#6e560fe71abef84f">⚙ Движки компоновки и опции</a>
</li><li><a href="https://plantuml.com/ru/#ffc0ab0a7e38b981">📤 Выходные форматы</a>
</li><li><a href="https://plantuml.com/ru/#2c4ec809d7f75591">🎉 Наслаждайтесь</a>
</li></ul>
</div>
</aside>

</div>




<!-- Start of StatCounter Code --><script type="text/javascript">
var sc_project=11129479; var sc_invisible=1; var sc_security="66ff16f1";
</script>
<script async="" type="text/javascript" src="./scheme_files/counter.js.Без названия"></script> <!-- End of StatCounter Code -->

  <script src="./scheme_files/viz-global.js.Без названия"></script>
  <script type="module">
    import { render } from "https://plantuml.github.io/plantuml/js-plantuml/plantuml.js";
    const renderOptions = {};
    document.querySelectorAll('.dyn').forEach(dynDiv => {
      const textarea = dynDiv.querySelector('textarea');
      const outDiv = dynDiv.querySelector('div');
      textarea.addEventListener('input', () => {
        render(textarea.value.split(/\r\n|\r|\n/), outDiv.id, renderOptions);
      });
    });
  </script>




<!--[selectrongo:done]--><span id="ezoic-pub-ad-placeholder-100"></span><!-- ezoic_pub_ad_placeholder-100-bottom_floating-728x90-100-nonexxxnonexxxxxxezmaxscaleval100 --><!-- ezoic_pub_ad_placeholder-100-bottom_floating-970x90-100-nonexxxnonexxxxxxezmaxscaleval100 --><script>!function(){function t(t,r){var n="undefined"!=typeof Symbol&&t[Symbol.iterator]||t["@@iterator"];if(!n){if(Array.isArray(t)||(n=function(t,r){if(t){if("string"==typeof t)return e(t,r);var n=Object.prototype.toString.call(t).slice(8,-1);return"Object"===n&&t.constructor&&(n=t.constructor.name),"Map"===n||"Set"===n?Array.from(t):"Arguments"===n||/^(?:Ui|I)nt(?:8|16|32)(?:Clamped)?Array$/.test(n)?e(t,r):void 0}}(t))||r&&t&&"number"==typeof t.length){n&&(t=n);var a=0,o=function(){};return{s:o,n:function(){return a>=t.length?{done:!0}:{done:!1,value:t[a++]}},e:function(t){throw t},f:o}}throw new TypeError("Invalid attempt to iterate non-iterable instance.\nIn order to be iterable, non-array objects must have a [Symbol.iterator]() method.")}var i,u=!0,s=!1;return{s:function(){n=n.call(t)},n:function(){var t=n.next();return u=t.done,t},e:function(t){s=!0,i=t},f:function(){try{u||null==n.return||n.return()}finally{if(s)throw i}}}}function e(t,e){(null==e||e>t.length)&&(e=t.length);for(var r=0,n=new Array(e);r<e;r++)n[r]=t[r];return n}!function(){var e=function(t){var e=getComputedStyle(t);if(-1===parseInt(e.bottom,10)){var r=t.offsetHeight||300;t.style.bottom=-r+"px"}};function r(){return document.querySelector('ins[data-anchor-shown="true"][data-anchor-status="displayed"]')}function n(t){var e=t.querySelector("iframe");e&&requestAnimationFrame((function(){var r=parseFloat(getComputedStyle(e).height);isNaN(r)||t.style.setProperty("height","".concat(r+5,"px"),"important")}))}function a(t){t.style.setProperty("width","100%","important"),t.style.maxWidth="none"}function o(t){var e=t.querySelector("iframe");e&&(e.style.setProperty("display","block","important"),e.style.setProperty("margin","0 auto","important"));var r=t.querySelector("[id$='__container__']");r&&r.style.setProperty("display","contents","important")}new MutationObserver((function(r){var n,a=t(r);try{for(a.s();!(n=a.n()).done;){var o=n.value;if("attributes"===o.type){var i=o.target;i.matches("[data-anchor-status]")&&("data-anchor-status"===o.attributeName&&"dismissed"===i.getAttribute("data-anchor-status")&&e(i),"style"===o.attributeName&&"dismissed"===i.getAttribute("data-anchor-status")&&e(i))}}}catch(t){a.e(t)}finally{a.f()}})).observe(document.documentElement,{subtree:!0,attributes:!0,attributeFilter:["style","data-anchor-status"]});var i=new WeakSet;function u(e){e&&(i.has(e)||(i.add(e),new MutationObserver((function(r){var i,u=t(r);try{for(u.s();!(i=u.n()).done;){var s=i.value;"style"===s.attributeName?(n(e),a(e),o(e)):"attributes"===s.type&&"data-google-query-id"===s.attributeName&&o(e)}}catch(t){u.e(t)}finally{u.f()}})).observe(e,{attributes:!0,attributeFilter:["style","data-google-query-id"]})))}!function(){var t=r();if(t)return n(t),a(t),o(t),void u(t);var e=new MutationObserver((function(){var t=r();t&&(n(t),a(t),o(t),u(t),e.disconnect())}));e.observe(document.body,{attributes:!0,subtree:!0,childList:!0})}()}()}();</script>
<script>window.ezAnchorBodyMargin=true;!function(){if(!document.getElementById("ez-grippy-dim")){var t=document.createElement("style");t.id="ez-grippy-dim",t.textContent=".grippy-host{opacity:.5;}body{padding-bottom:0 !important;padding-top:0 !important;}",(document.head||document.documentElement).appendChild(t)}window.__ezGabmEpoch=1+(0|window.__ezGabmEpoch);var e=window.__ezGabmEpoch,o=null,r=null,n=!1,a=0;function i(t){return"margin-top"===t?"padding-top":"padding-bottom"}function d(t){return"margin-top"===t?"padding-top":"padding-bottom"}function l(t){return!!(t&&t.closest&&t.closest(".ezmob-footer, .ezmob-footer-top, #ezmobfooter, #ezmobfooter-top, #ez-anchor-competitor"))}function u(t){return(t.getAttribute("data-ez-anchor-shell-pad")||"").split(/\s+/).filter(Boolean)}function p(t,e){e.length?t.setAttribute("data-ez-anchor-shell-pad",e.join(" ")):t.removeAttribute("data-ez-anchor-shell-pad")}function c(t,e){for(var o=d(t),r=function(){var t=window.innerWidth||0,e=window.innerHeight||0;if(t<2||e<2)return[];var o=[];return function r(n,a){if(n&&!(a>6)){var i=n.children;if(i)for(var d=0;d<i.length;d++){var u=i[d],p=u.tagName;if("SCRIPT"!==p&&"STYLE"!==p&&"LINK"!==p&&"NOSCRIPT"!==p){if(!l(u)&&"fixed"===window.getComputedStyle(u).position){var c=u.getBoundingClientRect();c.top>=-1&&c.top<=1&&c.left>=-1&&c.left<=1&&c.width>=t-2&&Math.abs(c.height-e)<=2&&o.push(u)}r(u,a+1)}}}}(document.body,0),o}(),n=document.querySelectorAll("[data-ez-anchor-shell-pad]"),a=0;a<n.length;a++){for(var i=n[a],c=!1,m=0;m<r.length;m++)if(r[m]===i){c=!0;break}if(!c){for(var s=u(i),y=[],g=0;g<s.length;g++)s[g]===o?i.style.removeProperty(o):y.push(s[g]);p(i,y)}}for(var h=0;h<r.length;h++){var f=r[h];f.style.getPropertyValue(o)===e&&"important"===f.style.getPropertyPriority(o)||f.style.setProperty(o,e,"important");var b=u(f);-1===b.indexOf(o)&&b.push(o),p(f,b)}}function m(t,e){document.body.style.getPropertyValue(t)===e&&"important"===document.body.style.getPropertyPriority(t)||document.body.style.setProperty(t,e,"important")}function s(t,e){var o=t.slice(7),r="--ez-anchor-"+o+"-h",n="data-ez-anchor-"+o+"-h-owner",a=document.documentElement;a.style.getPropertyValue(r)!==e&&a.style.setProperty(r,e),"google"!==a.getAttribute(n)&&a.setAttribute(n,"google")}function y(t){var e=t.slice(7),o="--ez-anchor-"+e+"-h",r="data-ez-anchor-"+e+"-h-owner",n=document.documentElement;"google"===n.getAttribute(r)&&(""!==n.style.getPropertyValue(o)&&n.style.removeProperty(o),n.removeAttribute(r))}function g(t,e,i){a=i,m(t,i+"px"),s(t,i+"px"),m(e,"0px"),c(t,i+"px"),o=t,r=null,n=!1}function h(){if(document&&e===window.__ezGabmEpoch){var t=function(){for(var t=document.querySelectorAll('ins[data-anchor-shown="true"][data-anchor-status="displayed"]:not(#ez-anchor-comp-trigger)'),e=t.length-1;e>=0;e--)if(t[e].offsetHeight>0)return t[e];return null}();if(!t)return document.querySelector('ins[data-anchor-status="displayed"]:not(#ez-anchor-comp-trigger)')?void function(){for(var t=["padding-bottom","padding-top"],e=0;e<t.length;e++){var o=t[e];parseFloat(document.body.style.getPropertyValue(o))>0&&(m(o,"0px"),n=!0)}}():(function(){if(null!==o){var t=i(o);""!==document.body.style.getPropertyValue(o)&&document.body.style.removeProperty(o),m(t,"0px"),function(t){for(var e=d(t),o=document.querySelectorAll("[data-ez-anchor-shell-pad]"),r=0;r<o.length;r++){for(var n=o[r],a=u(n),i=[],l=0;l<a.length;l++)a[l]===e?n.style.removeProperty(e):i.push(a[l]);p(n,i)}}(o),y(o),o=null,a=0}}(),r=null,void(n=!1));var l,h="0px"===getComputedStyle(t).top?"margin-top":"margin-bottom",f=i(h),b=t.offsetHeight+(l=parseInt(window.ezAnchorExtraSpacing,10),!isFinite(l)||l<0?0:l>300?300:l);if(null!==o&&o!==h&&(""!==document.body.style.getPropertyValue(o)&&document.body.style.removeProperty(o),y(o),o=null,a=0),o===h)return m(h,(a=Math.max(a,b))+"px"),s(h,a+"px"),m(f,"0px"),void c(h,a+"px");var v=function(t){var e,o=document.body.style.getPropertyValue(t);if(""===o){var r=getComputedStyle(document.body);e=parseFloat("padding-top"===t?r.paddingTop:r.paddingBottom)}else e=parseFloat(o);return isNaN(e)||e<=0?0:e}(f);v>0||n?g(h,f,b):(null===r&&(r=Date.now()),Date.now()-r>=1500&&g(h,f,b))}}new MutationObserver(h).observe(document.documentElement,{subtree:!0,attributes:!0,attributeFilter:["style","data-anchor-status","data-anchor-shown"]}),new MutationObserver(h).observe(document.documentElement,{childList:!0,subtree:!0}),h(),setInterval(h,500)}();</script>
<script src="./scheme_files/leavenworth.js.Без названия"></script>
<script src="./scheme_files/socialproviders.js.Без названия"></script>
<script src="./scheme_files/ezonetap.js.Без названия"></script><script data-cfasync="false">function _emitEzConsentEvent(){var customEvent=new CustomEvent("ezConsentEvent",{detail:{ezTcfConsent:window.ezTcfConsent},bubbles:true,cancelable:true,});document.dispatchEvent(customEvent);}
(function(window,document){function _setAllEzConsentTrue(){window.ezTcfConsent.loaded=true;window.ezTcfConsent.store_info=true;window.ezTcfConsent.develop_and_improve_services=true;window.ezTcfConsent.measure_ad_performance=true;window.ezTcfConsent.measure_content_performance=true;window.ezTcfConsent.select_basic_ads=true;window.ezTcfConsent.create_ad_profile=true;window.ezTcfConsent.select_personalized_ads=true;window.ezTcfConsent.create_content_profile=true;window.ezTcfConsent.select_personalized_content=true;window.ezTcfConsent.understand_audiences=true;window.ezTcfConsent.use_limited_data_to_select_content=true;window.ezTcfConsent.select_personalized_content=true;}
function _clearEzConsentCookie(){document.cookie="ezCMPCookieConsent=tcf2;Domain=.plantuml.com;Path=/;expires=Thu, 01 Jan 1970 00:00:00 GMT";}
_clearEzConsentCookie();if(typeof window.__tcfapi!=="undefined"){window.ezgconsent=false;var amazonHasRun=false;function _ezAllowed(tcdata,purpose){return(tcdata.purpose.consents[purpose]||tcdata.purpose.legitimateInterests[purpose]);}
function _handleConsentDecision(tcdata){window.ezTcfConsent.loaded=true;if(!tcdata.vendor.consents["347"]&&!tcdata.vendor.legitimateInterests["347"]){window._emitEzConsentEvent();return;}
window.ezTcfConsent.store_info=_ezAllowed(tcdata,"1");window.ezTcfConsent.develop_and_improve_services=_ezAllowed(tcdata,"10");window.ezTcfConsent.measure_content_performance=_ezAllowed(tcdata,"8");window.ezTcfConsent.select_basic_ads=_ezAllowed(tcdata,"2");window.ezTcfConsent.create_ad_profile=_ezAllowed(tcdata,"3");window.ezTcfConsent.select_personalized_ads=_ezAllowed(tcdata,"4");window.ezTcfConsent.create_content_profile=_ezAllowed(tcdata,"5");window.ezTcfConsent.measure_ad_performance=_ezAllowed(tcdata,"7");window.ezTcfConsent.use_limited_data_to_select_content=_ezAllowed(tcdata,"11");window.ezTcfConsent.select_personalized_content=_ezAllowed(tcdata,"6");window.ezTcfConsent.understand_audiences=_ezAllowed(tcdata,"9");window._emitEzConsentEvent();}
function _handleGoogleConsentV2(tcdata){if(!tcdata||!tcdata.purpose||!tcdata.purpose.consents){return;}
var consents=tcdata.purpose.consents;var googConsentV2={ad_storage:consents[1]?'granted':'denied',analytics_storage:consents[1]?'granted':'denied',ad_personalization:(consents[3]&&consents[4])?'granted':'denied',ad_user_data:(consents[1]&&consents[7])?'granted':'denied'};if(googConsentV2.analytics_storage==='denied'){gtag('set','url_passthrough',true);}
gtag('consent','update',googConsentV2);}
__tcfapi("addEventListener",2,function(tcdata,success){if(!success||!tcdata){window._emitEzConsentEvent();return;}
if(!tcdata.gdprApplies){_setAllEzConsentTrue();window._emitEzConsentEvent();return;}
if(tcdata.eventStatus==="useractioncomplete"||tcdata.eventStatus==="tcloaded"){if(typeof gtag!='undefined'){_handleGoogleConsentV2(tcdata);}
_handleConsentDecision(tcdata);if(tcdata.purpose.consents["1"]===true&&tcdata.vendor.consents["755"]!==false){window.ezgconsent=true;(adsbygoogle=window.adsbygoogle||[]).pauseAdRequests=0;}
if(window.__ezconsent){__ezconsent.setEzoicConsentSettings(ezConsentCategories);}
__tcfapi("removeEventListener",2,function(success){return null;},tcdata.listenerId);if(!(tcdata.purpose.consents["1"]===true&&_ezAllowed(tcdata,"2")&&_ezAllowed(tcdata,"3")&&_ezAllowed(tcdata,"4"))){if(typeof __ez=="object"&&typeof __ez.bit=="object"&&typeof window["_ezaq"]=="object"&&typeof window["_ezaq"]["page_view_id"]=="string"){__ez.bit.Add(window["_ezaq"]["page_view_id"],[new __ezDotData("non_personalized_ads",true),]);}}}});}else{_setAllEzConsentTrue();window._emitEzConsentEvent();}})(window,document);</script></body></html>
