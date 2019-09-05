





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://github.githubassets.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" media="all" integrity="sha512-aVn2DoCuXdXX9G3sp/Luupl/Ui00/iXrUh7Ke3geLlkigQY8GHBky7kKRSuyeKxGApWDdCQUy+6gTF1ZmYHWkw==" rel="stylesheet" href="https://github.githubassets.com/assets/frameworks-6b8b7859c4b8fbe3ab45f8ab0905a9f8.css" />
  
    <link crossorigin="anonymous" media="all" integrity="sha512-sLO1JuwvgYFNw548DR/keEd4Blx2a4qLD++xhOua+7VKNkB16DtOt9LOFNQjahAnCxt76u9Vh2vlD94gzan2/Q==" rel="stylesheet" href="https://github.githubassets.com/assets/github-8574c5af92bd7369457853930ff4eb9d.css" />
    
    
    
    

  <meta name="viewport" content="width=device-width">
  
  <title>node/README.md at master · VisualCurve/node</title>
    <meta name="description" content="Node.js JavaScript runtime :sparkles::turtle::rocket::sparkles: - VisualCurve/node">
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    <meta name="twitter:image:src" content="https://avatars3.githubusercontent.com/u/54949313?s=400&amp;v=4" /><meta name="twitter:site" content="@github" /><meta name="twitter:card" content="summary" /><meta name="twitter:title" content="VisualCurve/node" /><meta name="twitter:description" content="Node.js JavaScript runtime :sparkles::turtle::rocket::sparkles: - VisualCurve/node" />
    <meta property="og:image" content="https://avatars3.githubusercontent.com/u/54949313?s=400&amp;v=4" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="VisualCurve/node" /><meta property="og:url" content="https://github.com/VisualCurve/node" /><meta property="og:description" content="Node.js JavaScript runtime :sparkles::turtle::rocket::sparkles: - VisualCurve/node" />

  <link rel="assets" href="https://github.githubassets.com/">
  <link rel="web-socket" href="wss://live.github.com/_sockets/VjI6NDQyMzg5ODk0OmVjZDliY2Y0MzgxZDhkNGUwMmRkMTU0Yzc2YmQ0Mjc3MzkyYmFmNTg4ZDFiMDA1ZmU1ZTdjNGQ1OTJjYzQ3NzY=--27cea6c87e2a12591b4f5893548439beae78d85c">
  <meta name="pjax-timeout" content="1000">
  <link rel="sudo-modal" href="/sessions/sudo_modal">
  <meta name="request-id" content="6E50:33B6C:A346BC:F5250D:5D71290E" data-pjax-transient>


  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

      <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
    <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
    <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">

  <meta name="octolytics-host" content="collector.githubapp.com" /><meta name="octolytics-app-id" content="github" /><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event" /><meta name="octolytics-dimension-request_id" content="6E50:33B6C:A346BC:F5250D:5D71290E" /><meta name="octolytics-dimension-region_edge" content="ams" /><meta name="octolytics-dimension-region_render" content="iad" /><meta name="octolytics-dimension-ga_id" content="" class="js-octo-ga-id" /><meta name="octolytics-dimension-visitor_id" content="304478135919859121" /><meta name="octolytics-actor-id" content="54949313" /><meta name="octolytics-actor-login" content="VisualCurve" /><meta name="octolytics-actor-hash" content="24ee341faf4ef1bb767ad48a2685b6b7bdbe6f8ab3987988db68be2463ab3305" />
<meta name="analytics-location" content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" />



    <meta name="google-analytics" content="UA-3769691-2">

  <meta class="js-ga-set" name="userId" content="3b7c67ec291f013f50e0ff2074ab65d8">

<meta class="js-ga-set" name="dimension1" content="Logged In">



  

      <meta name="hostname" content="github.com">
    <meta name="user-login" content="VisualCurve">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="ZDNiOWJmYzZmMTVhYjQ4ZjlhZGJjMDMzMGQ1YmFjYzAxMzVmZGFhOWZmYzE2NmNhNzgzNTA3NWVjNzc2MDJkYnx7InJlbW90ZV9hZGRyZXNzIjoiODcuMTE2LjE4MS4yMTEiLCJyZXF1ZXN0X2lkIjoiNkU1MDozM0I2QzpBMzQ2QkM6RjUyNTBEOjVENzEyOTBFIiwidGltZXN0YW1wIjoxNTY3Njk3MTc5LCJob3N0IjoiZ2l0aHViLmNvbSJ9">

    <meta name="enabled-features" content="ACTIONS_V2_ON_MARKETPLACE,MARKETPLACE_FEATURED_BLOG_POSTS,MARKETPLACE_INVOICED_BILLING,MARKETPLACE_SOCIAL_PROOF_CUSTOMERS,MARKETPLACE_TRENDING_SOCIAL_PROOF,MARKETPLACE_RECOMMENDATIONS,MARKETPLACE_PENDING_INSTALLATIONS,NOTIFY_ON_BLOCK,RELATED_ISSUES,GHE_CLOUD_TRIAL">

  <meta name="html-safe-nonce" content="2e005f86e2fc93739f0983ece26e456a09a532ed">

  <meta http-equiv="x-pjax-version" content="fb2b5492172cf14a83c1752d7e2a28d0">
  

      <link href="https://github.com/VisualCurve/node/commits/master.atom" rel="alternate" title="Recent Commits to node:master" type="application/atom+xml">

  <meta name="go-import" content="github.com/VisualCurve/node git https://github.com/VisualCurve/node.git">

  <meta name="octolytics-dimension-user_id" content="54949313" /><meta name="octolytics-dimension-user_login" content="VisualCurve" /><meta name="octolytics-dimension-repository_id" content="206595781" /><meta name="octolytics-dimension-repository_nwo" content="VisualCurve/node" /><meta name="octolytics-dimension-repository_public" content="true" /><meta name="octolytics-dimension-repository_is_fork" content="true" /><meta name="octolytics-dimension-repository_parent_id" content="27193779" /><meta name="octolytics-dimension-repository_parent_nwo" content="nodejs/node" /><meta name="octolytics-dimension-repository_network_root_id" content="27193779" /><meta name="octolytics-dimension-repository_network_root_nwo" content="nodejs/node" /><meta name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" content="false" />


    <link rel="canonical" href="https://github.com/VisualCurve/node/blob/master/README.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://github.githubassets.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://github.githubassets.com/favicon.ico">

<meta name="theme-color" content="#1e2327">



  <meta name="webauthn-auth-enabled" content="true">

  <meta name="webauthn-registration-enabled" content="true">

  <link rel="manifest" href="/manifest.json" crossOrigin="use-credentials">

  </head>

  <body class="logged-in env-production page-responsive page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="p-3 bg-blue text-white show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    


          <header class="Header js-details-container Details flex-wrap flex-lg-nowrap p-responsive" role="banner">

    <div class="Header-item d-none d-lg-flex">
      <a class="Header-link" href="https://github.com/" data-hotkey="g d" aria-label="Homepage" data-ga-click="Header, go to dashboard, icon:logo">
  <svg class="octicon octicon-mark-github v-align-middle" height="32" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>

    </div>

    <div class="Header-item d-lg-none">
      <button class="Header-link btn-link js-details-target" type="button" aria-label="Toggle navigation" aria-expanded="false">
        <svg height="24" class="octicon octicon-three-bars" viewBox="0 0 12 16" version="1.1" width="18" aria-hidden="true"><path fill-rule="evenodd" d="M11.41 9H.59C0 9 0 8.59 0 8c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zm0-4H.59C0 5 0 4.59 0 4c0-.59 0-1 .59-1H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1h.01zM.59 11H11.4c.59 0 .59.41.59 1 0 .59 0 1-.59 1H.59C0 13 0 12.59 0 12c0-.59 0-1 .59-1z"/></svg>
      </button>
    </div>

    <div class="Header-item Header-item--full flex-column flex-lg-row width-full flex-order-2 flex-lg-order-none mr-0 mr-lg-3 mt-3 mt-lg-0 Details-content--hidden">
        <div class="header-search flex-self-stretch flex-lg-self-auto mr-0 mr-lg-3 mb-3 mb-lg-0 scoped-search site-scoped-search js-site-search position-relative js-jump-to"
  role="combobox"
  aria-owns="jump-to-results"
  aria-label="Search or jump to"
  aria-haspopup="listbox"
  aria-expanded="false"
>
  <div class="position-relative">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-site-search-form" role="search" aria-label="Site" data-scope-type="Repository" data-scope-id="206595781" data-scoped-search-url="/VisualCurve/node/search" data-unscoped-search-url="/search" action="/VisualCurve/node/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
      <label class="form-control input-sm header-search-wrapper p-0 header-search-wrapper-jump-to position-relative d-flex flex-justify-between flex-items-center js-chromeless-input-container">
        <input type="text"
          class="form-control input-sm header-search-input jump-to-field js-jump-to-field js-site-search-focus js-site-search-field is-clearable"
          data-hotkey="s,/"
          name="q"
          value=""
          placeholder="Search or jump to…"
          data-unscoped-placeholder="Search or jump to…"
          data-scoped-placeholder="Search or jump to…"
          autocapitalize="off"
          aria-autocomplete="list"
          aria-controls="jump-to-results"
          aria-label="Search or jump to…"
          data-jump-to-suggestions-path="/_graphql/GetSuggestedNavigationDestinations#csrf-token=pZjtfIu0HvufTvjgHTrVzQLAGkEQwtTcMYs4uHl7N3sPTsZssEXumxLFj+OFlbVKPDZEqb0I06O6m4uyr3jRTQ=="
          spellcheck="false"
          autocomplete="off"
          >
          <input type="hidden" class="js-site-search-type-field" name="type" >
            <img src="https://github.githubassets.com/images/search-key-slash.svg" alt="" class="mr-2 header-search-key-slash">

            <div class="Box position-absolute overflow-hidden d-none jump-to-suggestions js-jump-to-suggestions-container">
              
<ul class="d-none js-jump-to-suggestions-template-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-suggestion" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

</ul>

<ul class="d-none js-jump-to-no-results-template-container">
  <li class="d-flex flex-justify-center flex-items-center f5 d-none js-jump-to-suggestion p-2">
    <span class="text-gray">No suggested jump to results</span>
  </li>
</ul>

<ul id="jump-to-results" role="listbox" class="p-0 m-0 js-navigation-container jump-to-suggestions-results-container js-jump-to-suggestions-results-container">
  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-scoped-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>

  

<li class="d-flex flex-justify-start flex-items-center p-0 f5 navigation-item js-navigation-item js-jump-to-global-search d-none" role="option">
  <a tabindex="-1" class="no-underline d-flex flex-auto flex-items-center jump-to-suggestions-path js-jump-to-suggestion-path js-navigation-open p-2" href="">
    <div class="jump-to-octicon js-jump-to-octicon flex-shrink-0 mr-2 text-center d-none">
      <svg height="16" width="16" class="octicon octicon-repo flex-shrink-0 js-jump-to-octicon-repo d-none" title="Repository" aria-label="Repository" viewBox="0 0 12 16" version="1.1" role="img"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-project flex-shrink-0 js-jump-to-octicon-project d-none" title="Project" aria-label="Project" viewBox="0 0 15 16" version="1.1" role="img"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      <svg height="16" width="16" class="octicon octicon-search flex-shrink-0 js-jump-to-octicon-search d-none" title="Search" aria-label="Search" viewBox="0 0 16 16" version="1.1" role="img"><path fill-rule="evenodd" d="M15.7 13.3l-3.81-3.83A5.93 5.93 0 0 0 13 6c0-3.31-2.69-6-6-6S1 2.69 1 6s2.69 6 6 6c1.3 0 2.48-.41 3.47-1.11l3.83 3.81c.19.2.45.3.7.3.25 0 .52-.09.7-.3a.996.996 0 0 0 0-1.41v.01zM7 10.7c-2.59 0-4.7-2.11-4.7-4.7 0-2.59 2.11-4.7 4.7-4.7 2.59 0 4.7 2.11 4.7 4.7 0 2.59-2.11 4.7-4.7 4.7z"/></svg>
    </div>

    <img class="avatar mr-2 flex-shrink-0 js-jump-to-suggestion-avatar d-none" alt="" aria-label="Team" src="" width="28" height="28">

    <div class="jump-to-suggestion-name js-jump-to-suggestion-name flex-auto overflow-hidden text-left no-wrap css-truncate css-truncate-target">
    </div>

    <div class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none js-jump-to-badge-search">
      <span class="js-jump-to-badge-search-text-default d-none" aria-label="in this repository">
        In this repository
      </span>
      <span class="js-jump-to-badge-search-text-global d-none" aria-label="in all of GitHub">
        All GitHub
      </span>
      <span aria-hidden="true" class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>

    <div aria-hidden="true" class="border rounded-1 flex-shrink-0 bg-gray px-1 text-gray-light ml-1 f6 d-none d-on-nav-focus js-jump-to-badge-jump">
      Jump to
      <span class="d-inline-block ml-1 v-align-middle">↵</span>
    </div>
  </a>
</li>


    <li class="d-flex flex-justify-center flex-items-center p-0 f5 js-jump-to-suggestion">
      <img src="https://github.githubassets.com/images/spinners/octocat-spinner-128.gif" alt="Octocat Spinner Icon" class="m-2" width="28">
    </li>
</ul>

            </div>
      </label>
</form>  </div>
</div>


      <nav class="d-flex flex-column flex-lg-row flex-self-stretch flex-lg-self-auto" aria-label="Global">
    <a class="Header-link d-block d-lg-none py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-ga-click="Header, click, Nav menu - item:dashboard:user" aria-label="Dashboard" href="/dashboard">
      Dashboard
</a>
  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-hotkey="g p" data-ga-click="Header, click, Nav menu - item:pulls context:user" aria-label="Pull requests you created" data-selected-links="/pulls /pulls/assigned /pulls/mentioned /pulls" href="/pulls">
    Pull requests
</a>
  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-hotkey="g i" data-ga-click="Header, click, Nav menu - item:issues context:user" aria-label="Issues you created" data-selected-links="/issues /issues/assigned /issues/mentioned /issues" href="/issues">
    Issues
</a>
    <div class="mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15">
      <a class="js-selected-navigation-item Header-link" data-ga-click="Header, click, Nav menu - item:marketplace context:user" data-octo-click="marketplace_click" data-octo-dimensions="location:nav_bar" data-selected-links=" /marketplace" href="/marketplace">
        Marketplace
</a>      

    </div>

  <a class="js-selected-navigation-item Header-link  mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore" href="/explore">
    Explore
</a>


    <a class="Header-link d-block d-lg-none mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15" href="https://github.com/VisualCurve">
      <img class="avatar" height="20" width="20" alt="@VisualCurve" src="https://avatars2.githubusercontent.com/u/54949313?s=60&amp;v=4" />
      VisualCurve
</a>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="73E4rkV/YnRcZw4lChmCpI2oLrNKTYelrPO7GX85IPzPl1x7P6j2omWcSuOfYahPwcifkuUSr/HRUL8T9Zx8fQ==" />
      <button type="submit" class="Header-link mr-0 mr-lg-3 py-2 py-lg-0 border-top border-lg-top-0 border-white-fade-15 d-lg-none btn-link d-block width-full text-left" data-ga-click="Header, sign out, icon:logout" style="padding-left: 2px;">
        <svg class="octicon octicon-sign-out v-align-middle" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 9V7H8V5h4V3l4 3-4 3zm-2 3H6V3L2 1h8v3h1V1c0-.55-.45-1-1-1H1C.45 0 0 .45 0 1v11.38c0 .39.22.73.55.91L6 16.01V13h4c.55 0 1-.45 1-1V8h-1v4z"/></svg>
        Sign out
      </button>
</form></nav>

    </div>

    <div class="Header-item Header-item--full flex-justify-center d-lg-none position-relative">
      <div class="css-truncate css-truncate-target width-fit position-absolute left-0 right-0 text-center">
              <svg class="octicon octicon-repo-forked" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
    <a class="Header-link" href="/VisualCurve">VisualCurve</a>
    /
    <a class="Header-link" href="/VisualCurve/node">node</a>

</div>
    </div>



    <div class="Header-item mr-0 mr-lg-3 flex-order-1 flex-lg-order-none">
      

    <a aria-label="You have no unread notifications" class="Header-link notification-indicator position-relative tooltipped tooltipped-s js-socket-channel js-notification-indicator" data-hotkey="g n" data-ga-click="Header, go to notifications, icon:read" data-channel="notification-changed:54949313" href="/notifications">
        <span class="mail-status "></span>
        <svg class="octicon octicon-bell" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 12v1H0v-1l.73-.58c.77-.77.81-2.55 1.19-4.42C2.69 3.23 6 2 6 2c0-.55.45-1 1-1s1 .45 1 1c0 0 3.39 1.23 4.16 5 .38 1.88.42 3.66 1.19 4.42l.66.58H14zm-7 4c1.11 0 2-.89 2-2H5c0 1.11.89 2 2 2z"/></svg>
</a>
    </div>


    <div class="Header-item position-relative d-none d-lg-flex">
      <details class="details-overlay details-reset">
  <summary class="Header-link"
      aria-label="Create new…"
      data-ga-click="Header, create new, icon:add">
    <svg class="octicon octicon-plus" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 9H7v5H5V9H0V7h5V2h2v5h5v2z"/></svg> <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw">
    
<a role="menuitem" class="dropdown-item" href="/new" data-ga-click="Header, create new repository">
  New repository
</a>

  <a role="menuitem" class="dropdown-item" href="/new/import" data-ga-click="Header, import a repository">
    Import repository
  </a>

<a role="menuitem" class="dropdown-item" href="https://gist.github.com/" data-ga-click="Header, create new gist">
  New gist
</a>

  <a role="menuitem" class="dropdown-item" href="/organizations/new" data-ga-click="Header, create new organization">
    New organization
  </a>



  <a role="menuitem" class="dropdown-item" href="/new/project" data-ga-click="Header, create new project">
    New project
  </a>

  </details-menu>
</details>

    </div>

    <div class="Header-item position-relative mr-0 d-none d-lg-flex">
      
<details class="details-overlay details-reset">
  <summary class="Header-link"
    aria-label="View profile and more"
    data-ga-click="Header, show menu, icon:avatar">
    <img alt="@VisualCurve" class="avatar" src="https://avatars1.githubusercontent.com/u/54949313?s=40&amp;v=4" height="20" width="20">
    <span class="dropdown-caret"></span>
  </summary>
  <details-menu class="dropdown-menu dropdown-menu-sw mt-2" style="width: 180px">
    <div class="header-nav-current-user css-truncate"><a role="menuitem" class="no-underline user-profile-link px-3 pt-2 pb-2 mb-n2 mt-n1 d-block" href="/VisualCurve" data-ga-click="Header, go to profile, text:Signed in as">Signed in as <strong class="css-truncate-target">VisualCurve</strong></a></div>
    <div role="none" class="dropdown-divider"></div>

      <div class="pl-3 pr-3 f6 user-status-container js-user-status-context pb-1" data-url="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1">
        
<div class="js-user-status-container
    user-status-compact rounded-1 px-2 py-1 mt-2
    border
  " data-team-hovercards-enabled>
  <details class="js-user-status-details details-reset details-overlay details-overlay-dark">
    <summary class="btn-link btn-block link-gray no-underline js-toggle-user-status-edit toggle-user-status-edit "
      role="menuitem" data-hydro-click="{&quot;event_type&quot;:&quot;user_profile.click&quot;,&quot;payload&quot;:{&quot;profile_user_id&quot;:54949313,&quot;target&quot;:&quot;EDIT_USER_STATUS&quot;,&quot;user_id&quot;:54949313,&quot;client_id&quot;:&quot;70891840.1566594481&quot;,&quot;originating_request_id&quot;:&quot;6E50:33B6C:A346BC:F5250D:5D71290E&quot;,&quot;originating_url&quot;:&quot;https://github.com/VisualCurve/node/blob/master/README.md&quot;,&quot;referrer&quot;:&quot;https://github.com/VisualCurve/node&quot;}}" data-hydro-click-hmac="cb361c5750b0f206c3f7c41732b4e7cc90f1d1fba0c6e25eb668ff123c24617f">
      <div class="d-flex">
        <div class="f6 lh-condensed user-status-header
          d-inline-block v-align-middle
            user-status-emoji-only-header circle
            pr-2
"
            style="max-width: 29px"
          >
          <div class="user-status-emoji-container flex-shrink-0 mr-1 mt-1 lh-condensed-ultra v-align-bottom" style="">
            <svg class="octicon octicon-smiley" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8s3.58 8 8 8 8-3.58 8-8-3.58-8-8-8zm4.81 12.81a6.72 6.72 0 0 1-2.17 1.45c-.83.36-1.72.53-2.64.53-.92 0-1.81-.17-2.64-.53-.81-.34-1.55-.83-2.17-1.45a6.773 6.773 0 0 1-1.45-2.17A6.59 6.59 0 0 1 1.21 8c0-.92.17-1.81.53-2.64.34-.81.83-1.55 1.45-2.17.62-.62 1.36-1.11 2.17-1.45A6.59 6.59 0 0 1 8 1.21c.92 0 1.81.17 2.64.53.81.34 1.55.83 2.17 1.45.62.62 1.11 1.36 1.45 2.17.36.83.53 1.72.53 2.64 0 .92-.17 1.81-.53 2.64-.34.81-.83 1.55-1.45 2.17zM4 6.8v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2H5.2C4.53 8 4 7.47 4 6.8zm5 0v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2h-.59C9.53 8 9 7.47 9 6.8zm4 3.2c-.72 1.88-2.91 3-5 3s-4.28-1.13-5-3c-.14-.39.23-1 .66-1h8.59c.41 0 .89.61.75 1z"/></svg>
          </div>
        </div>
        <div class="
          d-inline-block v-align-middle
          
          
           css-truncate css-truncate-target 
           user-status-message-wrapper f6"
           style="line-height: 20px;" >
          <div class="d-inline-block text-gray-dark v-align-text-top text-left">
              <span class="text-gray ml-2">Set status</span>
          </div>
        </div>
      </div>
    </summary>
    <details-dialog class="details-dialog rounded-1 anim-fade-in fast Box Box--overlay" role="dialog" tabindex="-1">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="position-relative flex-auto js-user-status-form" action="/users/status?compact=1&amp;link_mentions=0&amp;truncate=1" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="put" /><input type="hidden" name="authenticity_token" value="wylsNfliH6fgHsxKztNOVpmdd+KanokjZ7IkxiMDYM33efYDRS1WOQb948FVUycuSVuGZBnajUKMDm7lMdAboA==" />
        <div class="Box-header bg-gray border-bottom p-3">
          <button class="Box-btn-octicon js-toggle-user-status-edit btn-octicon float-right" type="reset" aria-label="Close dialog" data-close-dialog>
            <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
          </button>
          <h3 class="Box-title f5 text-bold text-gray-dark">Edit status</h3>
        </div>
        <input type="hidden" name="emoji" class="js-user-status-emoji-field" value="">
        <input type="hidden" name="organization_id" class="js-user-status-org-id-field" value="">
        <div class="px-3 py-2 text-gray-dark">
          <div class="js-characters-remaining-container position-relative mt-2">
            <div class="input-group d-table form-group my-0 js-user-status-form-group">
              <span class="input-group-button d-table-cell v-align-middle" style="width: 1%">
                <button type="button" aria-label="Choose an emoji" class="btn-outline btn js-toggle-user-status-emoji-picker btn-open-emoji-picker p-0">
                  <span class="js-user-status-original-emoji" hidden></span>
                  <span class="js-user-status-custom-emoji"></span>
                  <span class="js-user-status-no-emoji-icon" >
                    <svg class="octicon octicon-smiley" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8s3.58 8 8 8 8-3.58 8-8-3.58-8-8-8zm4.81 12.81a6.72 6.72 0 0 1-2.17 1.45c-.83.36-1.72.53-2.64.53-.92 0-1.81-.17-2.64-.53-.81-.34-1.55-.83-2.17-1.45a6.773 6.773 0 0 1-1.45-2.17A6.59 6.59 0 0 1 1.21 8c0-.92.17-1.81.53-2.64.34-.81.83-1.55 1.45-2.17.62-.62 1.36-1.11 2.17-1.45A6.59 6.59 0 0 1 8 1.21c.92 0 1.81.17 2.64.53.81.34 1.55.83 2.17 1.45.62.62 1.11 1.36 1.45 2.17.36.83.53 1.72.53 2.64 0 .92-.17 1.81-.53 2.64-.34.81-.83 1.55-1.45 2.17zM4 6.8v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2H5.2C4.53 8 4 7.47 4 6.8zm5 0v-.59c0-.66.53-1.19 1.2-1.19h.59c.66 0 1.19.53 1.19 1.19v.59c0 .67-.53 1.2-1.19 1.2h-.59C9.53 8 9 7.47 9 6.8zm4 3.2c-.72 1.88-2.91 3-5 3s-4.28-1.13-5-3c-.14-.39.23-1 .66-1h8.59c.41 0 .89.61.75 1z"/></svg>
                  </span>
                </button>
              </span>
              <text-expander keys=": @" data-mention-url="/autocomplete/user-suggestions" data-emoji-url="/autocomplete/emoji">
                <input
                  type="text"
                  autocomplete="off"
                  data-no-org-url="/autocomplete/user-suggestions"
                  data-org-url="/suggestions?mention_suggester=1"
                  data-maxlength="80"
                  class="d-table-cell width-full form-control js-user-status-message-field js-characters-remaining-field"
                  placeholder="What's happening?"
                  name="message"
                  value=""
                  aria-label="What is your current status?">
              </text-expander>
              <div class="error">Could not update your status, please try again.</div>
            </div>
            <div style="margin-left: 53px" class="my-1 text-small label-characters-remaining js-characters-remaining" data-suffix="remaining" hidden>
              80 remaining
            </div>
          </div>
          <include-fragment class="js-user-status-emoji-picker" data-url="/users/status/emoji"></include-fragment>
          <div class="overflow-auto ml-n3 mr-n3 px-3 border-bottom" style="max-height: 33vh">
            <div class="user-status-suggestions js-user-status-suggestions collapsed overflow-hidden">
              <h4 class="f6 text-normal my-3">Suggestions:</h4>
              <div class="mx-3 mt-2 clearfix">
                  <div class="float-left col-6">
                      <button type="button" value=":palm_tree:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="palm_tree" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f334.png">🌴</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          On vacation
                        </div>
                      </button>
                      <button type="button" value=":face_with_thermometer:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="face_with_thermometer" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f912.png">🤒</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Out sick
                        </div>
                      </button>
                  </div>
                  <div class="float-left col-6">
                      <button type="button" value=":house:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="house" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3e0.png">🏠</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Working from home
                        </div>
                      </button>
                      <button type="button" value=":dart:" class="d-flex flex-items-baseline flex-items-stretch lh-condensed f6 btn-link link-gray no-underline js-predefined-user-status mb-1">
                        <div class="emoji-status-width mr-2 v-align-middle js-predefined-user-status-emoji">
                          <g-emoji alias="dart" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f3af.png">🎯</g-emoji>
                        </div>
                        <div class="d-flex flex-items-center no-underline js-predefined-user-status-message ws-normal text-left" style="border-left: 1px solid transparent">
                          Focusing
                        </div>
                      </button>
                  </div>
              </div>
            </div>
            <div class="user-status-limited-availability-container">
              <div class="form-checkbox my-0">
                <input type="checkbox" name="limited_availability" value="1" class="js-user-status-limited-availability-checkbox" data-default-message="I may be slow to respond." aria-describedby="limited-availability-help-text-truncate-true-compact-true" id="limited-availability-truncate-true-compact-true">
                <label class="d-block f5 text-gray-dark mb-1" for="limited-availability-truncate-true-compact-true">
                  Busy
                </label>
                <p class="note" id="limited-availability-help-text-truncate-true-compact-true">
                  When others mention you, assign you, or request your review,
                  GitHub will let them know that you have limited availability.
                </p>
              </div>
            </div>
          </div>
            

<div class="d-inline-block f5 mr-2 pt-3 pb-2" >
  <div class="d-inline-block mr-1">
    Clear status
  </div>

  <details class="js-user-status-expire-drop-down f6 dropdown details-reset details-overlay d-inline-block mr-2">
    <summary class="f5 btn-link link-gray-dark border px-2 py-1 rounded-1" aria-haspopup="true">
      <div class="js-user-status-expiration-interval-selected d-inline-block v-align-baseline">
        Never
      </div>
      <div class="dropdown-caret"></div>
    </summary>

    <ul class="dropdown-menu dropdown-menu-se pl-0 overflow-auto" style="width: 220px; max-height: 15.5em">
      <li>
        <button type="button" class="btn-link dropdown-item js-user-status-expire-button ws-normal" title="Never">
          <span class="d-inline-block text-bold mb-1">Never</span>
          <div class="f6 lh-condensed">Keep this status until you clear your status or edit your status.</div>
        </button>
      </li>
      <li class="dropdown-divider" role="none"></li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 30 minutes" value="2019-09-05T17:56:19+02:00">
            in 30 minutes
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 1 hour" value="2019-09-05T18:26:19+02:00">
            in 1 hour
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="in 4 hours" value="2019-09-05T21:26:19+02:00">
            in 4 hours
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="today" value="2019-09-05T23:59:59+02:00">
            today
          </button>
        </li>
        <li>
          <button type="button" class="btn-link dropdown-item ws-normal js-user-status-expire-button" title="this week" value="2019-09-08T23:59:59+02:00">
            this week
          </button>
        </li>
    </ul>
  </details>
  <input class="js-user-status-expiration-date-input" type="hidden" name="expires_at" value="">
</div>

          <include-fragment class="js-user-status-org-picker" data-url="/users/status/organizations"></include-fragment>
        </div>
        <div class="d-flex flex-items-center flex-justify-between p-3 border-top">
          <button type="submit" disabled class="width-full btn btn-primary mr-2 js-user-status-submit">
            Set status
          </button>
          <button type="button" disabled class="width-full js-clear-user-status-button btn ml-2 ">
            Clear status
          </button>
        </div>
</form>    </details-dialog>
  </details>
</div>

      </div>
      <div role="none" class="dropdown-divider"></div>


    <a role="menuitem" class="dropdown-item" href="/VisualCurve" data-ga-click="Header, go to profile, text:your profile">Your profile</a>


    <a role="menuitem" class="dropdown-item" href="/VisualCurve?tab=repositories" data-ga-click="Header, go to repositories, text:your repositories">Your repositories</a>

    <a role="menuitem" class="dropdown-item" href="/VisualCurve?tab=projects" data-ga-click="Header, go to projects, text:your projects">Your projects</a>

    <a role="menuitem" class="dropdown-item" href="/VisualCurve?tab=stars" data-ga-click="Header, go to starred repos, text:your stars">Your stars</a>
      <a role="menuitem" class="dropdown-item" href="https://gist.github.com/mine" data-ga-click="Header, your gists, text:your gists">Your gists</a>


    <div role="none" class="dropdown-divider"></div>
    <a role="menuitem" class="dropdown-item" href="https://help.github.com" data-ga-click="Header, go to help, text:help">Help</a>
    <a role="menuitem" class="dropdown-item" href="/settings/profile" data-ga-click="Header, go to settings, icon:settings">Settings</a>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="logout-form" action="/logout" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="1Cu4xQyTGB3P31eD/k/6AquaCrTb6+oH/iScD2XRTID0zdwQdkSMy/YkE0VrN9Dp5/q7lXS0wlODh5gF73QQAQ==" />
      
      <button type="submit" class="dropdown-item dropdown-signout" data-ga-click="Header, sign out, icon:logout" role="menuitem">
        Sign out
      </button>
</form>  </details-menu>
</details>

    </div>

  </header>

      

  </div>

  <div id="start-of-content" class="show-on-focus"></div>


    <div id="js-flash-container">

</div>



  <div class="application-main " data-commit-hovercards-enabled>
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <main  >
      


  

      <div class="border-bottom shelf intro-shelf js-notice mb-0 pb-4">
  <div class="width-full container">
    <div class="width-full mx-auto shelf-content">
      <h2 class="shelf-title">Learn Git and GitHub without any code!</h2>
      <p class="shelf-lead">
          Using the Hello World guide, you’ll start a branch, write comments, and open a pull request.
      </p>
      <a class="btn btn-primary shelf-cta" target="_blank" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;READ_GUIDE&quot;,&quot;repository_id&quot;:206595781,&quot;client_id&quot;:&quot;70891840.1566594481&quot;,&quot;originating_request_id&quot;:&quot;6E50:33B6C:A346BC:F5250D:5D71290E&quot;,&quot;originating_url&quot;:&quot;https://github.com/VisualCurve/node/blob/master/README.md&quot;,&quot;referrer&quot;:&quot;https://github.com/VisualCurve/node&quot;,&quot;user_id&quot;:54949313}}" data-hydro-click-hmac="862dc3956e94c9fc8adaa422d22a4aaf456940ef7224c060a55349f73d03575f" href="https://guides.github.com/activities/hello-world/">Read the guide</a>
    </div>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="shelf-dismiss js-notice-dismiss" action="/dashboard/dismiss_bootcamp" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="delete" /><input type="hidden" name="authenticity_token" value="gyO1VLfzqnISPR9v0V5VDk+hbRvZalgAE7MkNpndv2f0WgJOoqXciK8hoh9a8YFBrzrEwfjuH5tLg3Idd6K3sA==" />
      <button name="button" type="submit" class="mr-1 close-button tooltipped tooltipped-w" aria-label="Hide this notice forever" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;DISMISS_BANNER&quot;,&quot;repository_id&quot;:206595781,&quot;client_id&quot;:&quot;70891840.1566594481&quot;,&quot;originating_request_id&quot;:&quot;6E50:33B6C:A346BC:F5250D:5D71290E&quot;,&quot;originating_url&quot;:&quot;https://github.com/VisualCurve/node/blob/master/README.md&quot;,&quot;referrer&quot;:&quot;https://github.com/VisualCurve/node&quot;,&quot;user_id&quot;:54949313}}" data-hydro-click-hmac="c3ff079afbfd47200b6f9b03a2f56d14da109db9d1a66f395571ed7071f762e7">
        <svg aria-label="Hide this notice forever" class="octicon octicon-x v-align-text-top" viewBox="0 0 12 16" version="1.1" width="12" height="16" role="img"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
</button></form>  </div>
</div>










  <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav pt-0 pt-lg-4 ">
    <div class="repohead-details-container clearfix container-lg p-responsive d-none d-lg-block">

      <ul class="pagehead-actions">




  <li>
    
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form data-remote="true" class="clearfix js-social-form js-social-container" action="/notifications/subscribe" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="f4oXmMoafce2bmQuzDYwNVXJ33FaAT5lMxieRxhPIh5XSUluXfJgtlPk8QtwdReEOmW8IVKZsuQg1LaI/i1PSQ==" />      <input type="hidden" name="repository_id" value="206595781">

      <details class="details-reset details-overlay select-menu float-left">
        <summary class="select-menu-button float-left btn btn-sm btn-with-count" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;WATCH_BUTTON&quot;,&quot;repository_id&quot;:206595781,&quot;client_id&quot;:&quot;70891840.1566594481&quot;,&quot;originating_request_id&quot;:&quot;6E50:33B6C:A346BC:F5250D:5D71290E&quot;,&quot;originating_url&quot;:&quot;https://github.com/VisualCurve/node/blob/master/README.md&quot;,&quot;referrer&quot;:&quot;https://github.com/VisualCurve/node&quot;,&quot;user_id&quot;:54949313}}" data-hydro-click-hmac="9d83c75dc5feeb233afe154ba398f5d6f87dcb8022dcae2d8432193968865a40" data-ga-click="Repository, click Watch settings, action:blob#show">          <span data-menu-button>
              <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
              Watch
          </span>
</summary>        <details-menu
          class="select-menu-modal position-absolute mt-5"
          style="z-index: 99;">
          <div class="select-menu-header">
            <span class="select-menu-title">Notifications</span>
          </div>
          <div class="select-menu-list">
            <button type="submit" name="do" value="included" class="select-menu-item width-full" aria-checked="true" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Not watching</span>
                <span class="description">Be notified only when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Watch
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="release_only" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Releases only</span>
                <span class="description">Be notified of new releases, and when participating or @mentioned.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Unwatch releases
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="subscribed" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Watching</span>
                <span class="description">Be notified of all conversations.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-eye v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
                  Unwatch
                </span>
              </div>
            </button>

            <button type="submit" name="do" value="ignore" class="select-menu-item width-full" aria-checked="false" role="menuitemradio">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5L12 5z"/></svg>
              <div class="select-menu-item-text">
                <span class="select-menu-item-heading">Ignoring</span>
                <span class="description">Never be notified.</span>
                <span class="hidden-select-button-text" data-menu-button-contents>
                  <svg class="octicon octicon-mute v-align-text-bottom" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 2.81v10.38c0 .67-.81 1-1.28.53L3 10H1c-.55 0-1-.45-1-1V7c0-.55.45-1 1-1h2l3.72-3.72C7.19 1.81 8 2.14 8 2.81zm7.53 3.22l-1.06-1.06-1.97 1.97-1.97-1.97-1.06 1.06L11.44 8 9.47 9.97l1.06 1.06 1.97-1.97 1.97 1.97 1.06-1.06L13.56 8l1.97-1.97z"/></svg>
                  Stop ignoring
                </span>
              </div>
            </button>
          </div>
        </details-menu>
      </details>
        <a class="social-count js-social-count"
          href="/VisualCurve/node/watchers"
          aria-label="0 users are watching this repository">
          0
        </a>
</form>
  </li>

  <li>
      <div class="js-toggler-container js-social-container starring-container ">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="starred js-social-form" action="/VisualCurve/node/unstar" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="pBtmFC6ZDbTLL8EZNHd/PcBI+zcK7T7Rc64XpTF7BpMo0hvTbRWsxVlAX1jJK5Zg4kVENcMpYUYRoMkAafaYpg==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Unstar VisualCurve/node" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;UNSTAR_BUTTON&quot;,&quot;repository_id&quot;:206595781,&quot;client_id&quot;:&quot;70891840.1566594481&quot;,&quot;originating_request_id&quot;:&quot;6E50:33B6C:A346BC:F5250D:5D71290E&quot;,&quot;originating_url&quot;:&quot;https://github.com/VisualCurve/node/blob/master/README.md&quot;,&quot;referrer&quot;:&quot;https://github.com/VisualCurve/node&quot;,&quot;user_id&quot;:54949313}}" data-hydro-click-hmac="57a0b2c4c947b46991fa667967e0eeb1065bdf24196930ed52e788a5cab6dac7" data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar">        <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
        Unstar
</button>        <a class="social-count js-social-count" href="/VisualCurve/node/stargazers"
           aria-label="0 users starred this repository">
           0
        </a>
</form>
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="unstarred js-social-form" action="/VisualCurve/node/star" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="auo0a+47D/4fuEF7HAM8Mj45EPe0L4wY/Oad7wEedH7BQNsTRHBtS4CrI/ybjV62yVdnSvQC1V09NHvcpBtQiA==" />
      <input type="hidden" name="context" value="repository"></input>
      <button type="submit" class="btn btn-sm btn-with-count js-toggler-target" aria-label="Unstar this repository" title="Star VisualCurve/node" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;STAR_BUTTON&quot;,&quot;repository_id&quot;:206595781,&quot;client_id&quot;:&quot;70891840.1566594481&quot;,&quot;originating_request_id&quot;:&quot;6E50:33B6C:A346BC:F5250D:5D71290E&quot;,&quot;originating_url&quot;:&quot;https://github.com/VisualCurve/node/blob/master/README.md&quot;,&quot;referrer&quot;:&quot;https://github.com/VisualCurve/node&quot;,&quot;user_id&quot;:54949313}}" data-hydro-click-hmac="8c1aa4823bbb1fb122c7df59931436cf04bcdb7b6327f196e43f35ea7e2ff7c5" data-ga-click="Repository, click star button, action:blob#show; text:Star">        <svg class="octicon octicon-star v-align-text-bottom" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74L14 6z"/></svg>
        Star
</button>        <a class="social-count js-social-count" href="/VisualCurve/node/stargazers"
           aria-label="0 users starred this repository">
          0
        </a>
</form>  </div>

  </li>

  <li>
        <span class="btn btn-sm btn-with-count disabled tooltipped tooltipped-sw" aria-label="Cannot fork because you own this repository and are not a member of any organizations.">
          <svg class="octicon octicon-repo-forked v-align-text-bottom" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
          Fork
</span>
    <a href="/VisualCurve/node/network/members" class="social-count"
       aria-label="14742 users forked this repository">
      14,742
    </a>
  </li>
</ul>

      <h1 class="public ">
    <svg class="octicon octicon-repo-forked" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
  <span class="author" itemprop="author"><a class="url fn" rel="author" data-hovercard-type="user" data-hovercard-url="/hovercards?user_id=54949313" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/VisualCurve">VisualCurve</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a data-pjax="#js-repo-pjax-container" href="/VisualCurve/node">node</a></strong>
  

    <span class="fork-flag" data-repository-hovercards-enabled>
      <span class="text">forked from <a data-hovercard-type="repository" data-hovercard-url="/nodejs/node/hovercard" href="/nodejs/node">nodejs/node</a></span>
    </span>
</h1>

    </div>
    
<nav class="hx_reponav reponav js-repo-nav js-sidenav-container-pjax container-lg p-responsive d-none d-lg-block"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
    aria-label="Repository"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a class="js-selected-navigation-item selected reponav-item" itemprop="url" data-hotkey="g c" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /VisualCurve/node" href="/VisualCurve/node">
      <svg class="octicon octicon-code" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>


  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a data-hotkey="g p" itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /VisualCurve/node/pulls" href="/VisualCurve/node/pulls">
      <svg class="octicon octicon-git-pull-request" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>


    <a data-hotkey="g b" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /VisualCurve/node/projects" href="/VisualCurve/node/projects">
      <svg class="octicon octicon-project" viewBox="0 0 15 16" version="1.1" width="15" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M10 12h3V2h-3v10zm-4-2h3V2H6v8zm-4 4h3V2H2v12zm-1 1h13V1H1v14zM14 0H1a1 1 0 0 0-1 1v14a1 1 0 0 0 1 1h13a1 1 0 0 0 1-1V1a1 1 0 0 0-1-1z"/></svg>
      Projects
      <span class="Counter" >0</span>
</a>


    <a data-skip-pjax="true" class="js-selected-navigation-item reponav-item" data-selected-links="security alerts policy code_scanning /VisualCurve/node/network/alerts" href="/VisualCurve/node/network/alerts">
      <svg class="octicon octicon-shield" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 2l7-2 7 2v6.02C14 12.69 8.69 16 7 16c-1.69 0-7-3.31-7-7.98V2zm1 .75L7 1l6 1.75v5.268C13 12.104 8.449 15 7 15c-1.449 0-6-2.896-6-6.982V2.75zm1 .75L7 2v12c-1.207 0-5-2.482-5-5.985V3.5z"/></svg>
      Security
</a>
    <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse people /VisualCurve/node/pulse" href="/VisualCurve/node/pulse">
      <svg class="octicon octicon-graph" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
      Insights
</a>
    <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_settings repo_branch_settings hooks integration_installations repo_keys_settings issue_template_editor secrets_settings /VisualCurve/node/settings" href="/VisualCurve/node/settings">
      <svg class="octicon octicon-gear" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 8.77v-1.6l-1.94-.64-.45-1.09.88-1.84-1.13-1.13-1.81.91-1.09-.45-.69-1.92h-1.6l-.63 1.94-1.11.45-1.84-.88-1.13 1.13.91 1.81-.45 1.09L0 7.23v1.59l1.94.64.45 1.09-.88 1.84 1.13 1.13 1.81-.91 1.09.45.69 1.92h1.59l.63-1.94 1.11-.45 1.84.88 1.13-1.13-.92-1.81.47-1.09L14 8.75v.02zM7 11c-1.66 0-3-1.34-3-3s1.34-3 3-3 3 1.34 3 3-1.34 3-3 3z"/></svg>
      Settings
</a>
</nav>

  <div class="reponav-wrapper reponav-small d-lg-none">
  <nav class="reponav js-reponav text-center no-wrap"
       itemscope
       itemtype="http://schema.org/BreadcrumbList">

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a class="js-selected-navigation-item selected reponav-item" itemprop="url" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /VisualCurve/node" href="/VisualCurve/node">
        <span itemprop="name">Code</span>
        <meta itemprop="position" content="1">
</a>    </span>


    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /VisualCurve/node/pulls" href="/VisualCurve/node/pulls">
        <span itemprop="name">Pull requests</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="3">
</a>    </span>

      <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
        <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_projects new_repo_project repo_project /VisualCurve/node/projects" href="/VisualCurve/node/projects">
          <span itemprop="name">Projects</span>
          <span class="Counter">0</span>
          <meta itemprop="position" content="4">
</a>      </span>


      <a itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="security alerts policy code_scanning /VisualCurve/node/network/alerts" href="/VisualCurve/node/network/alerts">
        <span itemprop="name">Security</span>
        <meta itemprop="position" content="6">
</a>
      <a class="js-selected-navigation-item reponav-item" data-selected-links="pulse /VisualCurve/node/pulse" href="/VisualCurve/node/pulse">
        Pulse
</a>

  </nav>
</div>


  </div>
<div class="container-lg clearfix new-discussion-timeline experiment-repo-nav  p-responsive">
  <div class="repository-content ">

    
    


  


    <a class="d-none js-permalink-shortcut" data-hotkey="y" href="/VisualCurve/node/blob/af161f0efb1eb6690c64144cff2988d25186a46f/README.md">Permalink</a>

    <!-- blob contrib key: blob_contributors:v21:e912dc81476088cd463aa9c67bc70a5f -->
      

    <div class="d-flex flex-items-start flex-shrink-0 pb-3 flex-column flex-md-row">
      <span class="d-flex flex-justify-between width-full width-md-auto">
        
<details class="details-reset details-overlay select-menu branch-select-menu  hx_rsm" id="branch-select-menu">
  <summary class="btn btn-sm select-menu-button css-truncate"
           data-hotkey="w"
           title="Switch branches or tags">
    <i>Branch:</i>
    <span class="css-truncate-target" data-menu-button>master</span>
  </summary>

  <details-menu class="select-menu-modal hx_rsm-modal position-absolute" style="z-index: 99;" src="/VisualCurve/node/ref-list/master/README.md?source_action=show&amp;source_controller=blob" preload>
    <include-fragment class="select-menu-loading-overlay anim-pulse">
      <svg height="32" class="octicon octicon-octoface" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M14.7 5.34c.13-.32.55-1.59-.13-3.31 0 0-1.05-.33-3.44 1.3-1-.28-2.07-.32-3.13-.32s-2.13.04-3.13.32c-2.39-1.64-3.44-1.3-3.44-1.3-.68 1.72-.26 2.99-.13 3.31C.49 6.21 0 7.33 0 8.69 0 13.84 3.33 15 7.98 15S16 13.84 16 8.69c0-1.36-.49-2.48-1.3-3.35zM8 14.02c-3.3 0-5.98-.15-5.98-3.35 0-.76.38-1.48 1.02-2.07 1.07-.98 2.9-.46 4.96-.46 2.07 0 3.88-.52 4.96.46.65.59 1.02 1.3 1.02 2.07 0 3.19-2.68 3.35-5.98 3.35zM5.49 9.01c-.66 0-1.2.8-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.54-1.78-1.2-1.78zm5.02 0c-.66 0-1.2.79-1.2 1.78s.54 1.79 1.2 1.79c.66 0 1.2-.8 1.2-1.79s-.53-1.78-1.2-1.78z"/></svg>
    </include-fragment>
  </details-menu>
</details>

        <div class="BtnGroup flex-shrink-0 d-md-none">
          <a href="/VisualCurve/node/find/master"
                class="js-pjax-capture-input btn btn-sm BtnGroup-item"
                data-pjax
                data-hotkey="t">
            Find file
          </a>
          <clipboard-copy value="README.md" class="btn btn-sm BtnGroup-item">
            Copy path
          </clipboard-copy>
        </div>
      </span>
      <h2 id="blob-path" class="breadcrumb flex-auto min-width-0 text-normal flex-md-self-center ml-md-2 mr-md-3 my-2 my-md-0">
        <span class="js-repo-root text-bold"><span class="js-path-segment"><a data-pjax="true" href="/VisualCurve/node"><span>node</span></a></span></span><span class="separator">/</span><strong class="final-path">README.md</strong>
      </h2>

      <div class="BtnGroup flex-shrink-0 d-none d-md-inline-block">
        <a href="/VisualCurve/node/find/master"
              class="js-pjax-capture-input btn btn-sm BtnGroup-item"
              data-pjax
              data-hotkey="t">
          Find file
        </a>
        <clipboard-copy value="README.md" class="btn btn-sm BtnGroup-item">
          Copy path
        </clipboard-copy>
      </div>
    </div>



    <include-fragment src="/VisualCurve/node/contributors/master/README.md" class="Box Box--condensed commit-loader">
      <div class="Box-body bg-blue-light f6">
        Fetching contributors&hellip;
      </div>

      <div class="Box-body d-flex flex-items-center" >
          <img alt="" class="loader-loading mr-2" src="https://github.githubassets.com/images/spinners/octocat-spinner-32-EAF2F5.gif" width="16" height="16" />
        <span class="text-red h6 loader-error">Cannot retrieve contributors at this time</span>
      </div>
</include-fragment>




    <div class="Box mt-3 position-relative">
      
<div class="Box-header py-2 d-flex flex-column flex-shrink-0 flex-md-row flex-md-items-center">

  <div class="text-mono f6 flex-auto pr-3 flex-order-2 flex-md-order-1 mt-2 mt-md-0">
      589 lines (532 sloc)
      <span class="file-info-divider"></span>
    25.4 KB
  </div>

  <div class="d-flex py-1 py-md-0 flex-auto flex-order-1 flex-md-order-2 flex-sm-grow-0 flex-justify-between">

    <div class="BtnGroup">
      <a id="raw-url" class="btn btn-sm BtnGroup-item" href="/VisualCurve/node/raw/master/README.md">Raw</a>
        <a class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b" href="/VisualCurve/node/blame/master/README.md">Blame</a>
      <a rel="nofollow" class="btn btn-sm BtnGroup-item" href="/VisualCurve/node/commits/master/README.md">History</a>
    </div>


    <div>
            <a class="btn-octicon tooltipped tooltipped-nw hide-sm"
               href="https://desktop.github.com"
               aria-label="Open this file in GitHub Desktop"
               data-ga-click="Repository, open with desktop, type:windows">
                <svg class="octicon octicon-device-desktop" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M15 2H1c-.55 0-1 .45-1 1v9c0 .55.45 1 1 1h5.34c-.25.61-.86 1.39-2.34 2h8c-1.48-.61-2.09-1.39-2.34-2H15c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm0 9H1V3h14v8z"/></svg>
            </a>

            <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form js-update-url-with-hash" action="/VisualCurve/node/edit/master/README.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="PFG1Jnf8V8PcuFlv28teo9chrAKZMMxjcDMvQgu5pnBKdQnMtm0D7BAU5SjYWzGzRsI5jOidJ+ujc+7cwn0fhg==" />
              <button class="btn-octicon tooltipped tooltipped-nw" type="submit"
                aria-label="Edit this file" data-hotkey="e" data-disable-with>
                <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
              </button>
</form>
          <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="inline-form" action="/VisualCurve/node/delete/master/README.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="J2sygtCmJEoRTXMyXC/wtUl2gLEAJUXh+D5EJF2+CDoyKHnfB49hcZhm48PgLER1SMEwMdnuyiouFYVpknHnVA==" />
            <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit"
              aria-label="Delete this file" data-disable-with>
              <svg class="octicon octicon-trashcan" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
            </button>
</form>    </div>
  </div>
</div>




      
  <div id="readme" class="Box-body readme blob instapaper_body js-code-block-container">
    <article class="markdown-body entry-content p-3 p-md-6" itemprop="text"><p align="center">
  <a href="https://nodejs.org/" rel="nofollow">
    <img alt="Node.js" src="https://camo.githubusercontent.com/9c24355bb3afbff914503b663ade7beb341079fa/68747470733a2f2f6e6f64656a732e6f72672f7374617469632f696d616765732f6c6f676f2d6c696768742e737667" width="400" data-canonical-src="https://nodejs.org/static/images/logo-light.svg" style="max-width:100%;">
  </a>
</p>
<p>Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine. For
more information on using Node.js, see the <a href="https://nodejs.org/" rel="nofollow">Node.js Website</a>.</p>
<p>The Node.js project uses an <a href="/VisualCurve/node/blob/master/GOVERNANCE.md">open governance model</a>. The
<a href="http://openjs.foundation/" rel="nofollow">OpenJS Foundation</a> provides support for the project.</p>
<p><strong>This project is bound by a <a href="https://github.com/nodejs/admin/blob/master/CODE_OF_CONDUCT.md">Code of Conduct</a>.</strong></p>
<h1><a id="user-content-table-of-contents" class="anchor" aria-hidden="true" href="#table-of-contents"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Table of Contents</h1>
<ul>
<li><a href="#support">Support</a></li>
<li><a href="#release-types">Release Types</a>
<ul>
<li><a href="#download">Download</a>
<ul>
<li><a href="#current-and-lts-releases">Current and LTS Releases</a></li>
<li><a href="#nightly-releases">Nightly Releases</a></li>
<li><a href="#api-documentation">API Documentation</a></li>
</ul>
</li>
<li><a href="#verifying-binaries">Verifying Binaries</a></li>
</ul>
</li>
<li><a href="#building-nodejs">Building Node.js</a></li>
<li><a href="#security">Security</a></li>
<li><a href="#contributing-to-nodejs">Contributing to Node.js</a></li>
<li><a href="#current-project-team-members">Current Project Team Members</a>
<ul>
<li><a href="#tsc-technical-steering-committee">TSC (Technical Steering Committee)</a></li>
<li><a href="#collaborators">Collaborators</a></li>
<li><a href="#release-keys">Release Keys</a></li>
</ul>
</li>
</ul>
<h2><a id="user-content-support" class="anchor" aria-hidden="true" href="#support"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Support</h2>
<p>Looking for help? Check out the
<a href="/VisualCurve/node/blob/master/.github/SUPPORT.md">instructions for getting support</a>.</p>
<h2><a id="user-content-release-types" class="anchor" aria-hidden="true" href="#release-types"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Release Types</h2>
<ul>
<li><strong>Current</strong>: Under active development. Code for the Current release is in the
branch for its major version number (for example,
<a href="https://github.com/nodejs/node/tree/v10.x">v10.x</a>). Node.js releases a new
major version every 6 months, allowing for breaking changes. This happens in
April and October every year. Releases appearing each October have a support
life of 8 months. Releases appearing each April convert to LTS (see below)
each October.</li>
<li><strong>LTS</strong>: Releases that receive Long-term Support, with a focus on stability
and security. Every even-numbered major version will become an LTS release.
LTS releases receive 18 months of <em>Active LTS</em> support and a further 12 months
of <em>Maintenance</em>. LTS release lines have alphabetically-ordered codenames,
beginning with v4 Argon. There are no breaking changes or feature additions,
except in some special circumstances.</li>
<li><strong>Nightly</strong>: Code from the Current branch built every 24-hours when there are
changes. Use with caution.</li>
</ul>
<p>Current and LTS releases follow <a href="https://semver.org" rel="nofollow">Semantic Versioning</a>. A
member of the Release Team <a href="#release-keys">signs</a> each Current and LTS release.
For more information, see the
<a href="https://github.com/nodejs/Release#readme">Release README</a>.</p>
<h3><a id="user-content-download" class="anchor" aria-hidden="true" href="#download"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Download</h3>
<p>Binaries, installers, and source tarballs are available at
<a href="https://nodejs.org/en/download/" rel="nofollow">https://nodejs.org/en/download/</a>.</p>
<h4><a id="user-content-current-and-lts-releases" class="anchor" aria-hidden="true" href="#current-and-lts-releases"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Current and LTS Releases</h4>
<p><a href="https://nodejs.org/download/release/" rel="nofollow">https://nodejs.org/download/release/</a></p>
<p>The <a href="https://nodejs.org/download/release/latest/" rel="nofollow">latest</a> directory is an
alias for the latest Current release. The latest-<em>codename</em> directory is an
alias for the latest release from an LTS line. For example, the
<a href="https://nodejs.org/download/release/latest-carbon/" rel="nofollow">latest-carbon</a> directory
contains the latest Carbon (Node.js 8) release.</p>
<h4><a id="user-content-nightly-releases" class="anchor" aria-hidden="true" href="#nightly-releases"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Nightly Releases</h4>
<p><a href="https://nodejs.org/download/nightly/" rel="nofollow">https://nodejs.org/download/nightly/</a></p>
<p>Each directory name and filename contains a date (in UTC time) and the commit
SHA at the HEAD of the release.</p>
<h4><a id="user-content-api-documentation" class="anchor" aria-hidden="true" href="#api-documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>API Documentation</h4>
<p>Documentation for the latest Current release is at <a href="https://nodejs.org/api/" rel="nofollow">https://nodejs.org/api/</a>.
Version-specific documentation is available in each release directory in the
<em>docs</em> subdirectory. Version-specific documentation is also at
<a href="https://nodejs.org/download/docs/" rel="nofollow">https://nodejs.org/download/docs/</a>.</p>
<h3><a id="user-content-verifying-binaries" class="anchor" aria-hidden="true" href="#verifying-binaries"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Verifying Binaries</h3>
<p>Download directories contain a <code>SHASUMS256.txt</code> file with SHA checksums for the
files.</p>
<p>To download <code>SHASUMS256.txt</code> using <code>curl</code>:</p>
<div class="highlight highlight-text-shell-session"><pre>$ <span class="pl-s1">curl -O https://nodejs.org/dist/vx.y.z/SHASUMS256.txt</span></pre></div>
<p>To check that a downloaded file matches the checksum, run
it through <code>sha256sum</code> with a command such as:</p>
<div class="highlight highlight-text-shell-session"><pre>$ <span class="pl-s1">grep node-vx.y.z.tar.gz SHASUMS256.txt <span class="pl-k">|</span> sha256sum -c -</span></pre></div>
<p>For Current and LTS, the GPG detached signature of <code>SHASUMS256.txt</code> is in
<code>SHASUMS256.txt.sig</code>. You can use it with <code>gpg</code> to verify the integrity of
<code>SHASUM256.txt</code>. You will first need to import
<a href="#release-keys">the GPG keys of individuals authorized to create releases</a>. To
import the keys:</p>
<div class="highlight highlight-text-shell-session"><pre>$ <span class="pl-s1">gpg --keyserver pool.sks-keyservers.net --recv-keys DD8F2338BAE7501E3DD5AC78C273792F7D83545D</span></pre></div>
<p>See the bottom of this README for a full script to import active release keys.</p>
<p>Next, download the <code>SHASUMS256.txt.sig</code> for the release:</p>
<div class="highlight highlight-text-shell-session"><pre>$ <span class="pl-s1">curl -O https://nodejs.org/dist/vx.y.z/SHASUMS256.txt.sig</span></pre></div>
<p>Then use <code>gpg --verify SHASUMS256.txt.sig SHASUMS256.txt</code> to verify
the file's signature.</p>
<h2><a id="user-content-building-nodejs" class="anchor" aria-hidden="true" href="#building-nodejs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Building Node.js</h2>
<p>See <a href="/VisualCurve/node/blob/master/BUILDING.md">BUILDING.md</a> for instructions on how to build Node.js from
source and a list of supported platforms.</p>
<h2><a id="user-content-security" class="anchor" aria-hidden="true" href="#security"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Security</h2>
<p>For information on reporting security vulnerabilities in Node.js, see
<a href="/VisualCurve/node/blob/master/SECURITY.md">SECURITY.md</a>.</p>
<h2><a id="user-content-contributing-to-nodejs" class="anchor" aria-hidden="true" href="#contributing-to-nodejs"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Contributing to Node.js</h2>
<ul>
<li><a href="/VisualCurve/node/blob/master/CONTRIBUTING.md">Contributing to the project</a></li>
<li><a href="https://github.com/nodejs/TSC/blob/master/WORKING_GROUPS.md">Working Groups</a></li>
<li><a href="https://github.com/nodejs/TSC/blob/master/Strategic-Initiatives.md">Strategic Initiatives</a></li>
</ul>
<h2><a id="user-content-current-project-team-members" class="anchor" aria-hidden="true" href="#current-project-team-members"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Current Project Team Members</h2>
<p>For information about the governance of the Node.js project, see
<a href="/VisualCurve/node/blob/master/GOVERNANCE.md">GOVERNANCE.md</a>.</p>
<h3><a id="user-content-tsc-technical-steering-committee" class="anchor" aria-hidden="true" href="#tsc-technical-steering-committee"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>TSC (Technical Steering Committee)</h3>
<ul>
<li><a href="https://github.com/addaleax">addaleax</a> -
<strong>Anna Henningsen</strong> &lt;<a href="mailto:anna@addaleax.net">anna@addaleax.net</a>&gt; (she/her)</li>
<li><a href="https://github.com/apapirovski">apapirovski</a> -
<strong>Anatoli Papirovski</strong> &lt;<a href="mailto:apapirovski@mac.com">apapirovski@mac.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/ChALkeR">ChALkeR</a> -
<strong>Сковорода Никита Андреевич</strong> &lt;<a href="mailto:chalkerx@gmail.com">chalkerx@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/cjihrig">cjihrig</a> -
<strong>Colin Ihrig</strong> &lt;<a href="mailto:cjihrig@gmail.com">cjihrig@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/danbev">danbev</a> -
<strong>Daniel Bevenius</strong> &lt;<a href="mailto:daniel.bevenius@gmail.com">daniel.bevenius@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/fhinkel">fhinkel</a> -
<strong>Franziska Hinkelmann</strong> &lt;<a href="mailto:franziska.hinkelmann@gmail.com">franziska.hinkelmann@gmail.com</a>&gt; (she/her)</li>
<li><a href="https://github.com/Fishrock123">Fishrock123</a> -
<strong>Jeremiah Senkpiel</strong> &lt;<a href="mailto:fishrock123@rocketmail.com">fishrock123@rocketmail.com</a>&gt;</li>
<li><a href="https://github.com/gabrielschulhof">gabrielschulhof</a> -
<strong>Gabriel Schulhof</strong> &lt;<a href="mailto:gabriel.schulhof@intel.com">gabriel.schulhof@intel.com</a>&gt;</li>
<li><a href="https://github.com/gireeshpunathil">gireeshpunathil</a> -
<strong>Gireesh Punathil</strong> &lt;<a href="mailto:gpunathi@in.ibm.com">gpunathi@in.ibm.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/jasnell">jasnell</a> -
<strong>James M Snell</strong> &lt;<a href="mailto:jasnell@gmail.com">jasnell@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/joyeecheung">joyeecheung</a> -
<strong>Joyee Cheung</strong> &lt;<a href="mailto:joyeec9h3@gmail.com">joyeec9h3@gmail.com</a>&gt; (she/her)</li>
<li><a href="https://github.com/mcollina">mcollina</a> -
<strong>Matteo Collina</strong> &lt;<a href="mailto:matteo.collina@gmail.com">matteo.collina@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/mhdawson">mhdawson</a> -
<strong>Michael Dawson</strong> &lt;<a href="mailto:michael_dawson@ca.ibm.com">michael_dawson@ca.ibm.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/MylesBorins">MylesBorins</a> -
<strong>Myles Borins</strong> &lt;<a href="mailto:myles.borins@gmail.com">myles.borins@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/sam-github">sam-github</a> -
<strong>Sam Roberts</strong> &lt;<a href="mailto:vieuxtech@gmail.com">vieuxtech@gmail.com</a>&gt;</li>
<li><a href="https://github.com/targos">targos</a> -
<strong>Michaël Zasso</strong> &lt;<a href="mailto:targos@protonmail.com">targos@protonmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/thefourtheye">thefourtheye</a> -
<strong>Sakthipriyan Vairamani</strong> &lt;<a href="mailto:thechargingvolcano@gmail.com">thechargingvolcano@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/Trott">Trott</a> -
<strong>Rich Trott</strong> &lt;<a href="mailto:rtrott@gmail.com">rtrott@gmail.com</a>&gt; (he/him)</li>
</ul>
<h3><a id="user-content-tsc-emeriti" class="anchor" aria-hidden="true" href="#tsc-emeriti"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>TSC Emeriti</h3>
<ul>
<li><a href="https://github.com/bnoordhuis">bnoordhuis</a> -
<strong>Ben Noordhuis</strong> &lt;<a href="mailto:info@bnoordhuis.nl">info@bnoordhuis.nl</a>&gt;</li>
<li><a href="https://github.com/chrisdickinson">chrisdickinson</a> -
<strong>Chris Dickinson</strong> &lt;<a href="mailto:christopher.s.dickinson@gmail.com">christopher.s.dickinson@gmail.com</a>&gt;</li>
<li><a href="https://github.com/evanlucas">evanlucas</a> -
<strong>Evan Lucas</strong> &lt;<a href="mailto:evanlucas@me.com">evanlucas@me.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/gibfahn">gibfahn</a> -
<strong>Gibson Fahnestock</strong> &lt;<a href="mailto:gibfahn@gmail.com">gibfahn@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/indutny">indutny</a> -
<strong>Fedor Indutny</strong> &lt;<a href="mailto:fedor.indutny@gmail.com">fedor.indutny@gmail.com</a>&gt;</li>
<li><a href="https://github.com/isaacs">isaacs</a> -
<strong>Isaac Z. Schlueter</strong> &lt;<a href="mailto:i@izs.me">i@izs.me</a>&gt;</li>
<li><a href="https://github.com/joshgav">joshgav</a> -
<strong>Josh Gavant</strong> &lt;<a href="mailto:josh.gavant@outlook.com">josh.gavant@outlook.com</a>&gt;</li>
<li><a href="https://github.com/mscdex">mscdex</a> -
<strong>Brian White</strong> &lt;<a href="mailto:mscdex@mscdex.net">mscdex@mscdex.net</a>&gt;</li>
<li><a href="https://github.com/nebrius">nebrius</a> -
<strong>Bryan Hughes</strong> &lt;<a href="mailto:bryan@nebri.us">bryan@nebri.us</a>&gt;</li>
<li><a href="https://github.com/ofrobots">ofrobots</a> -
<strong>Ali Ijaz Sheikh</strong> &lt;<a href="mailto:ofrobots@google.com">ofrobots@google.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/orangemocha">orangemocha</a> -
<strong>Alexis Campailla</strong> &lt;<a href="mailto:orangemocha@nodejs.org">orangemocha@nodejs.org</a>&gt;</li>
<li><a href="https://github.com/piscisaureus">piscisaureus</a> -
<strong>Bert Belder</strong> &lt;<a href="mailto:bertbelder@gmail.com">bertbelder@gmail.com</a>&gt;</li>
<li><a href="https://github.com/rvagg">rvagg</a> -
<strong>Rod Vagg</strong> &lt;<a href="mailto:r@va.gg">r@va.gg</a>&gt;</li>
<li><a href="https://github.com/shigeki">shigeki</a> -
<strong>Shigeki Ohtsu</strong> &lt;<a href="mailto:ohtsu@ohtsu.org">ohtsu@ohtsu.org</a>&gt; (he/him)</li>
<li><a href="https://github.com/TimothyGu">TimothyGu</a> -
<strong>Tiancheng "Timothy" Gu</strong> &lt;<a href="mailto:timothygu99@gmail.com">timothygu99@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/trevnorris">trevnorris</a> -
<strong>Trevor Norris</strong> &lt;<a href="mailto:trev.norris@gmail.com">trev.norris@gmail.com</a>&gt;</li>
</ul>
<h3><a id="user-content-collaborators" class="anchor" aria-hidden="true" href="#collaborators"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Collaborators</h3>
<ul>
<li><a href="https://github.com/addaleax">addaleax</a> -
<strong>Anna Henningsen</strong> &lt;<a href="mailto:anna@addaleax.net">anna@addaleax.net</a>&gt; (she/her)</li>
<li><a href="https://github.com/ak239">ak239</a> -
<strong>Aleksei Koziatinskii</strong> &lt;<a href="mailto:ak239spb@gmail.com">ak239spb@gmail.com</a>&gt;</li>
<li><a href="https://github.com/AndreasMadsen">AndreasMadsen</a> -
<strong>Andreas Madsen</strong> &lt;<a href="mailto:amwebdk@gmail.com">amwebdk@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/antsmartian">antsmartian</a> -
<strong>Anto Aravinth</strong> &lt;<a href="mailto:anto.aravinth.cse@gmail.com">anto.aravinth.cse@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/apapirovski">apapirovski</a> -
<strong>Anatoli Papirovski</strong> &lt;<a href="mailto:apapirovski@mac.com">apapirovski@mac.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/aqrln">aqrln</a> -
<strong>Alexey Orlenko</strong> &lt;<a href="mailto:eaglexrlnk@gmail.com">eaglexrlnk@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/bcoe">bcoe</a> -
<strong>Ben Coe</strong> &lt;<a href="mailto:bencoe@gmail.com">bencoe@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/bengl">bengl</a> -
<strong>Bryan English</strong> &lt;<a href="mailto:bryan@bryanenglish.com">bryan@bryanenglish.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/benjamingr">benjamingr</a> -
<strong>Benjamin Gruenbaum</strong> &lt;<a href="mailto:benjamingr@gmail.com">benjamingr@gmail.com</a>&gt;</li>
<li><a href="https://github.com/BethGriggs">BethGriggs</a> -
<strong>Beth Griggs</strong> &lt;<a href="mailto:Bethany.Griggs@uk.ibm.com">Bethany.Griggs@uk.ibm.com</a>&gt; (she/her)</li>
<li><a href="https://github.com/bmeck">bmeck</a> -
<strong>Bradley Farias</strong> &lt;<a href="mailto:bradley.meck@gmail.com">bradley.meck@gmail.com</a>&gt;</li>
<li><a href="https://github.com/bmeurer">bmeurer</a> -
<strong>Benedikt Meurer</strong> &lt;<a href="mailto:benedikt.meurer@gmail.com">benedikt.meurer@gmail.com</a>&gt;</li>
<li><a href="https://github.com/bnoordhuis">bnoordhuis</a> -
<strong>Ben Noordhuis</strong> &lt;<a href="mailto:info@bnoordhuis.nl">info@bnoordhuis.nl</a>&gt;</li>
<li><a href="https://github.com/boneskull">boneskull</a> -
<strong>Christopher Hiller</strong> &lt;<a href="mailto:boneskull@boneskull.com">boneskull@boneskull.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/brendanashworth">brendanashworth</a> -
<strong>Brendan Ashworth</strong> &lt;<a href="mailto:brendan.ashworth@me.com">brendan.ashworth@me.com</a>&gt;</li>
<li><a href="https://github.com/BridgeAR">BridgeAR</a> -
<strong>Ruben Bridgewater</strong> &lt;<a href="mailto:ruben@bridgewater.de">ruben@bridgewater.de</a>&gt; (he/him)</li>
<li><a href="https://github.com/bzoz">bzoz</a> -
<strong>Bartosz Sosnowski</strong> &lt;<a href="mailto:bartosz@janeasystems.com">bartosz@janeasystems.com</a>&gt;</li>
<li><a href="https://github.com/calvinmetcalf">calvinmetcalf</a> -
<strong>Calvin Metcalf</strong> &lt;<a href="mailto:calvin.metcalf@gmail.com">calvin.metcalf@gmail.com</a>&gt;</li>
<li><a href="https://github.com/cclauss">cclauss</a> -
<strong>Christian Clauss</strong> &lt;<a href="mailto:cclauss@me.com">cclauss@me.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/ChALkeR">ChALkeR</a> -
<strong>Сковорода Никита Андреевич</strong> &lt;<a href="mailto:chalkerx@gmail.com">chalkerx@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/cjihrig">cjihrig</a> -
<strong>Colin Ihrig</strong> &lt;<a href="mailto:cjihrig@gmail.com">cjihrig@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/claudiorodriguez">claudiorodriguez</a> -
<strong>Claudio Rodriguez</strong> &lt;<a href="mailto:cjrodr@yahoo.com">cjrodr@yahoo.com</a>&gt;</li>
<li><a href="https://github.com/codebytere">codebytere</a> -
<strong>Shelley Vohr</strong> &lt;<a href="mailto:codebytere@gmail.com">codebytere@gmail.com</a>&gt; (she/her)</li>
<li><a href="https://github.com/danbev">danbev</a> -
<strong>Daniel Bevenius</strong> &lt;<a href="mailto:daniel.bevenius@gmail.com">daniel.bevenius@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/DavidCai1993">DavidCai1993</a> -
<strong>David Cai</strong> &lt;<a href="mailto:davidcai1993@yahoo.com">davidcai1993@yahoo.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/davisjam">davisjam</a> -
<strong>Jamie Davis</strong> &lt;<a href="mailto:davisjam@vt.edu">davisjam@vt.edu</a>&gt; (he/him)</li>
<li><a href="https://github.com/devnexen">devnexen</a> -
<strong>David Carlier</strong> &lt;<a href="mailto:devnexen@gmail.com">devnexen@gmail.com</a>&gt;</li>
<li><a href="https://github.com/devsnek">devsnek</a> -
<strong>Gus Caplan</strong> &lt;<a href="mailto:me@gus.host">me@gus.host</a>&gt; (he/him)</li>
<li><a href="https://github.com/digitalinfinity">digitalinfinity</a> -
<strong>Hitesh Kanwathirtha</strong> &lt;<a href="mailto:digitalinfinity@gmail.com">digitalinfinity@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/edsadr">edsadr</a> -
<strong>Adrian Estrada</strong> &lt;<a href="mailto:edsadr@gmail.com">edsadr@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/eljefedelrodeodeljefe">eljefedelrodeodeljefe</a> -
<strong>Robert Jefe Lindstaedt</strong> &lt;<a href="mailto:robert.lindstaedt@gmail.com">robert.lindstaedt@gmail.com</a>&gt;</li>
<li><a href="https://github.com/eugeneo">eugeneo</a> -
<strong>Eugene Ostroukhov</strong> &lt;<a href="mailto:eostroukhov@google.com">eostroukhov@google.com</a>&gt;</li>
<li><a href="https://github.com/evanlucas">evanlucas</a> -
<strong>Evan Lucas</strong> &lt;<a href="mailto:evanlucas@me.com">evanlucas@me.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/fhinkel">fhinkel</a> -
<strong>Franziska Hinkelmann</strong> &lt;<a href="mailto:franziska.hinkelmann@gmail.com">franziska.hinkelmann@gmail.com</a>&gt; (she/her)</li>
<li><a href="https://github.com/Fishrock123">Fishrock123</a> -
<strong>Jeremiah Senkpiel</strong> &lt;<a href="mailto:fishrock123@rocketmail.com">fishrock123@rocketmail.com</a>&gt;</li>
<li><a href="https://github.com/gabrielschulhof">gabrielschulhof</a> -
<strong>Gabriel Schulhof</strong> &lt;<a href="mailto:gabriel.schulhof@intel.com">gabriel.schulhof@intel.com</a>&gt;</li>
<li><a href="https://github.com/gdams">gdams</a> -
<strong>George Adams</strong> &lt;<a href="mailto:george.adams@uk.ibm.com">george.adams@uk.ibm.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/geek">geek</a> -
<strong>Wyatt Preul</strong> &lt;<a href="mailto:wpreul@gmail.com">wpreul@gmail.com</a>&gt;</li>
<li><a href="https://github.com/gengjiawen">gengjiawen</a> -
<strong>Jiawen Geng</strong> &lt;<a href="mailto:technicalcute@gmail.com">technicalcute@gmail.com</a>&gt;</li>
<li><a href="https://github.com/gibfahn">gibfahn</a> -
<strong>Gibson Fahnestock</strong> &lt;<a href="mailto:gibfahn@gmail.com">gibfahn@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/gireeshpunathil">gireeshpunathil</a> -
<strong>Gireesh Punathil</strong> &lt;<a href="mailto:gpunathi@in.ibm.com">gpunathi@in.ibm.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/guybedford">guybedford</a> -
<strong>Guy Bedford</strong> &lt;<a href="mailto:guybedford@gmail.com">guybedford@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/hashseed">hashseed</a> -
<strong>Yang Guo</strong> &lt;<a href="mailto:yangguo@chromium.org">yangguo@chromium.org</a>&gt; (he/him)</li>
<li><a href="https://github.com/hiroppy">hiroppy</a> -
<strong>Yuta Hiroto</strong> &lt;<a href="mailto:hello@hiroppy.me">hello@hiroppy.me</a>&gt; (he/him)</li>
<li><a href="https://github.com/iarna">iarna</a> -
<strong>Rebecca Turner</strong> &lt;<a href="mailto:me@re-becca.org">me@re-becca.org</a>&gt;</li>
<li><a href="https://github.com/imyller">imyller</a> -
<strong>Ilkka Myller</strong> &lt;<a href="mailto:ilkka.myller@nodefield.com">ilkka.myller@nodefield.com</a>&gt;</li>
<li><a href="https://github.com/indutny">indutny</a> -
<strong>Fedor Indutny</strong> &lt;<a href="mailto:fedor.indutny@gmail.com">fedor.indutny@gmail.com</a>&gt;</li>
<li><a href="https://github.com/italoacasas">italoacasas</a> -
<strong>Italo A. Casas</strong> &lt;<a href="mailto:me@italoacasas.com">me@italoacasas.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/JacksonTian">JacksonTian</a> -
<strong>Jackson Tian</strong> &lt;<a href="mailto:shyvo1987@gmail.com">shyvo1987@gmail.com</a>&gt;</li>
<li><a href="https://github.com/jasnell">jasnell</a> -
<strong>James M Snell</strong> &lt;<a href="mailto:jasnell@gmail.com">jasnell@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/jasongin">jasongin</a> -
<strong>Jason Ginchereau</strong> &lt;<a href="mailto:jasongin@microsoft.com">jasongin@microsoft.com</a>&gt;</li>
<li><a href="https://github.com/jbergstroem">jbergstroem</a> -
<strong>Johan Bergström</strong> &lt;<a href="mailto:bugs@bergstroem.nu">bugs@bergstroem.nu</a>&gt;</li>
<li><a href="https://github.com/jdalton">jdalton</a> -
<strong>John-David Dalton</strong> &lt;<a href="mailto:john.david.dalton@gmail.com">john.david.dalton@gmail.com</a>&gt;</li>
<li><a href="https://github.com/jkrems">jkrems</a> -
<strong>Jan Krems</strong> &lt;<a href="mailto:jan.krems@gmail.com">jan.krems@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/joaocgreis">joaocgreis</a> -
<strong>João Reis</strong> &lt;<a href="mailto:reis@janeasystems.com">reis@janeasystems.com</a>&gt;</li>
<li><a href="https://github.com/joshgav">joshgav</a> -
<strong>Josh Gavant</strong> &lt;<a href="mailto:josh.gavant@outlook.com">josh.gavant@outlook.com</a>&gt;</li>
<li><a href="https://github.com/joyeecheung">joyeecheung</a> -
<strong>Joyee Cheung</strong> &lt;<a href="mailto:joyeec9h3@gmail.com">joyeec9h3@gmail.com</a>&gt; (she/her)</li>
<li><a href="https://github.com/julianduque">julianduque</a> -
<strong>Julian Duque</strong> &lt;<a href="mailto:julianduquej@gmail.com">julianduquej@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/JungMinu">JungMinu</a> -
<strong>Minwoo Jung</strong> &lt;<a href="mailto:minwoo@nodesource.com">minwoo@nodesource.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/kfarnung">kfarnung</a> -
<strong>Kyle Farnung</strong> &lt;<a href="mailto:kfarnung@microsoft.com">kfarnung@microsoft.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/kunalspathak">kunalspathak</a> -
<strong>Kunal Pathak</strong> &lt;<a href="mailto:kunal.pathak@microsoft.com">kunal.pathak@microsoft.com</a>&gt;</li>
<li><a href="https://github.com/lance">lance</a> -
<strong>Lance Ball</strong> &lt;<a href="mailto:lball@redhat.com">lball@redhat.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/Leko">Leko</a> -
<strong>Shingo Inoue</strong> &lt;<a href="mailto:leko.noor@gmail.com">leko.noor@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/lpinca">lpinca</a> -
<strong>Luigi Pinca</strong> &lt;<a href="mailto:luigipinca@gmail.com">luigipinca@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/lucamaraschi">lucamaraschi</a> -
<strong>Luca Maraschi</strong> &lt;<a href="mailto:luca.maraschi@gmail.com">luca.maraschi@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/lundibundi">lundibundi</a> -
<strong>Denys Otrishko</strong> &lt;<a href="mailto:shishugi@gmail.com">shishugi@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/maclover7">maclover7</a> -
<strong>Jon Moss</strong> &lt;<a href="mailto:me@jonathanmoss.me">me@jonathanmoss.me</a>&gt; (he/him)</li>
<li><a href="https://github.com/mafintosh">mafintosh</a>
<strong>Mathias Buus</strong> &lt;<a href="mailto:mathiasbuus@gmail.com">mathiasbuus@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/mcollina">mcollina</a> -
<strong>Matteo Collina</strong> &lt;<a href="mailto:matteo.collina@gmail.com">matteo.collina@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/mhdawson">mhdawson</a> -
<strong>Michael Dawson</strong> &lt;<a href="mailto:michael_dawson@ca.ibm.com">michael_dawson@ca.ibm.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/misterdjules">misterdjules</a> -
<strong>Julien Gilli</strong> &lt;<a href="mailto:jgilli@nodejs.org">jgilli@nodejs.org</a>&gt;</li>
<li><a href="https://github.com/mmarchini">mmarchini</a> -
<strong>Matheus Marchini</strong> &lt;<a href="mailto:mat@mmarchini.me">mat@mmarchini.me</a>&gt;</li>
<li><a href="https://github.com/MoonBall">MoonBall</a> -
<strong>Chen Gang</strong> &lt;<a href="mailto:gangc.cxy@foxmail.com">gangc.cxy@foxmail.com</a>&gt;</li>
<li><a href="https://github.com/mscdex">mscdex</a> -
<strong>Brian White</strong> &lt;<a href="mailto:mscdex@mscdex.net">mscdex@mscdex.net</a>&gt;</li>
<li><a href="https://github.com/MylesBorins">MylesBorins</a> -
<strong>Myles Borins</strong> &lt;<a href="mailto:myles.borins@gmail.com">myles.borins@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/not-an-aardvark">not-an-aardvark</a> -
<strong>Teddy Katz</strong> &lt;<a href="mailto:teddy.katz@gmail.com">teddy.katz@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/ofrobots">ofrobots</a> -
<strong>Ali Ijaz Sheikh</strong> &lt;<a href="mailto:ofrobots@google.com">ofrobots@google.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/oyyd">oyyd</a> -
<strong>Ouyang Yadong</strong> &lt;<a href="mailto:oyydoibh@gmail.com">oyydoibh@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/princejwesley">princejwesley</a> -
<strong>Prince John Wesley</strong> &lt;<a href="mailto:princejohnwesley@gmail.com">princejohnwesley@gmail.com</a>&gt;</li>
<li><a href="https://github.com/psmarshall">psmarshall</a> -
<strong>Peter Marshall</strong> &lt;<a href="mailto:petermarshall@chromium.org">petermarshall@chromium.org</a>&gt; (he/him)</li>
<li><a href="https://github.com/Qard">Qard</a> -
<strong>Stephen Belanger</strong> &lt;<a href="mailto:admin@stephenbelanger.com">admin@stephenbelanger.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/refack">refack</a> -
<strong>Refael Ackermann (רפאל פלחי)</strong> &lt;<a href="mailto:refack@gmail.com">refack@gmail.com</a>&gt; (he/him/הוא/אתה)</li>
<li><a href="https://github.com/richardlau">richardlau</a> -
<strong>Richard Lau</strong> &lt;<a href="mailto:riclau@uk.ibm.com">riclau@uk.ibm.com</a>&gt;</li>
<li><a href="https://github.com/ronkorving">ronkorving</a> -
<strong>Ron Korving</strong> &lt;<a href="mailto:ron@ronkorving.nl">ron@ronkorving.nl</a>&gt;</li>
<li><a href="https://github.com/RReverser">RReverser</a> -
<strong>Ingvar Stepanyan</strong> &lt;<a href="mailto:me@rreverser.com">me@rreverser.com</a>&gt;</li>
<li><a href="https://github.com/rubys">rubys</a> -
<strong>Sam Ruby</strong> &lt;<a href="mailto:rubys@intertwingly.net">rubys@intertwingly.net</a>&gt;</li>
<li><a href="https://github.com/rvagg">rvagg</a> -
<strong>Rod Vagg</strong> &lt;<a href="mailto:rod@vagg.org">rod@vagg.org</a>&gt;</li>
<li><a href="https://github.com/ryzokuken">ryzokuken</a> -
<strong>Ujjwal Sharma</strong> &lt;<a href="mailto:usharma1998@gmail.com">usharma1998@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/saghul">saghul</a> -
<strong>Saúl Ibarra Corretgé</strong> &lt;<a href="mailto:saghul@gmail.com">saghul@gmail.com</a>&gt;</li>
<li><a href="https://github.com/sam-github">sam-github</a> -
<strong>Sam Roberts</strong> &lt;<a href="mailto:vieuxtech@gmail.com">vieuxtech@gmail.com</a>&gt;</li>
<li><a href="https://github.com/santigimeno">santigimeno</a> -
<strong>Santiago Gimeno</strong> &lt;<a href="mailto:santiago.gimeno@gmail.com">santiago.gimeno@gmail.com</a>&gt;</li>
<li><a href="https://github.com/sebdeckers">sebdeckers</a> -
<strong>Sebastiaan Deckers</strong> &lt;<a href="mailto:sebdeckers83@gmail.com">sebdeckers83@gmail.com</a>&gt;</li>
<li><a href="https://github.com/seishun">seishun</a> -
<strong>Nikolai Vavilov</strong> &lt;<a href="mailto:vvnicholas@gmail.com">vvnicholas@gmail.com</a>&gt;</li>
<li><a href="https://github.com/shigeki">shigeki</a> -
<strong>Shigeki Ohtsu</strong> &lt;<a href="mailto:ohtsu@ohtsu.org">ohtsu@ohtsu.org</a>&gt; (he/him)</li>
<li><a href="https://github.com/shisama">shisama</a> -
<strong>Masashi Hirano</strong> &lt;<a href="mailto:shisama07@gmail.com">shisama07@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/silverwind">silverwind</a> -
<strong>Roman Reiss</strong> &lt;<a href="mailto:me@silverwind.io">me@silverwind.io</a>&gt;</li>
<li><a href="https://github.com/srl295">srl295</a> -
<strong>Steven R Loomis</strong> &lt;<a href="mailto:srloomis@us.ibm.com">srloomis@us.ibm.com</a>&gt;</li>
<li><a href="https://github.com/starkwang">starkwang</a> -
<strong>Weijia Wang</strong> &lt;<a href="mailto:starkwang@126.com">starkwang@126.com</a>&gt;</li>
<li><a href="https://github.com/targos">targos</a> -
<strong>Michaël Zasso</strong> &lt;<a href="mailto:targos@protonmail.com">targos@protonmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/thefourtheye">thefourtheye</a> -
<strong>Sakthipriyan Vairamani</strong> &lt;<a href="mailto:thechargingvolcano@gmail.com">thechargingvolcano@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/thekemkid">thekemkid</a> -
<strong>Glen Keane</strong> &lt;<a href="mailto:glenkeane.94@gmail.com">glenkeane.94@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/thlorenz">thlorenz</a> -
<strong>Thorsten Lorenz</strong> &lt;<a href="mailto:thlorenz@gmx.de">thlorenz@gmx.de</a>&gt;</li>
<li><a href="https://github.com/TimothyGu">TimothyGu</a> -
<strong>Tiancheng "Timothy" Gu</strong> &lt;<a href="mailto:timothygu99@gmail.com">timothygu99@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/tniessen">tniessen</a> -
<strong>Tobias Nießen</strong> &lt;<a href="mailto:tniessen@tnie.de">tniessen@tnie.de</a>&gt;</li>
<li><a href="https://github.com/trevnorris">trevnorris</a> -
<strong>Trevor Norris</strong> &lt;<a href="mailto:trev.norris@gmail.com">trev.norris@gmail.com</a>&gt;</li>
<li><a href="https://github.com/trivikr">trivikr</a> -
<strong>Trivikram Kamat</strong> &lt;<a href="mailto:trivikr.dev@gmail.com">trivikr.dev@gmail.com</a>&gt;</li>
<li><a href="https://github.com/Trott">Trott</a> -
<strong>Rich Trott</strong> &lt;<a href="mailto:rtrott@gmail.com">rtrott@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/vdeturckheim">vdeturckheim</a> -
<strong>Vladimir de Turckheim</strong> &lt;<a href="mailto:vlad2t@hotmail.com">vlad2t@hotmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/vkurchatkin">vkurchatkin</a> -
<strong>Vladimir Kurchatkin</strong> &lt;<a href="mailto:vladimir.kurchatkin@gmail.com">vladimir.kurchatkin@gmail.com</a>&gt;</li>
<li><a href="https://github.com/watilde">watilde</a> -
<strong>Daijiro Wachi</strong> &lt;<a href="mailto:daijiro.wachi@gmail.com">daijiro.wachi@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/watson">watson</a> -
<strong>Thomas Watson</strong> &lt;<a href="mailto:w@tson.dk">w@tson.dk</a>&gt;</li>
<li><a href="https://github.com/XadillaX">XadillaX</a> -
<strong>Khaidi Chu</strong> &lt;<a href="mailto:i@2333.moe">i@2333.moe</a>&gt; (he/him)</li>
<li><a href="https://github.com/yhwang">yhwang</a> -
<strong>Yihong Wang</strong> &lt;<a href="mailto:yh.wang@ibm.com">yh.wang@ibm.com</a>&gt;</li>
<li><a href="https://github.com/yorkie">yorkie</a> -
<strong>Yorkie Liu</strong> &lt;<a href="mailto:yorkiefixer@gmail.com">yorkiefixer@gmail.com</a>&gt;</li>
<li><a href="https://github.com/yosuke-furukawa">yosuke-furukawa</a> -
<strong>Yosuke Furukawa</strong> &lt;<a href="mailto:yosuke.furukawa@gmail.com">yosuke.furukawa@gmail.com</a>&gt;</li>
<li><a href="https://github.com/ZYSzys">ZYSzys</a> -
<strong>Yongsheng Zhang</strong> &lt;<a href="mailto:zyszys98@gmail.com">zyszys98@gmail.com</a>&gt; (he/him)</li>
</ul>
<h3><a id="user-content-collaborator-emeriti" class="anchor" aria-hidden="true" href="#collaborator-emeriti"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Collaborator Emeriti</h3>
<ul>
<li><a href="https://github.com/andrasq">andrasq</a> -
<strong>Andras</strong> &lt;<a href="mailto:andras@kinvey.com">andras@kinvey.com</a>&gt;</li>
<li><a href="https://github.com/AnnaMag">AnnaMag</a> -
<strong>Anna M. Kedzierska</strong> &lt;<a href="mailto:anna.m.kedzierska@gmail.com">anna.m.kedzierska@gmail.com</a>&gt;</li>
<li><a href="https://github.com/estliberitas">estliberitas</a> -
<strong>Alexander Makarenko</strong> &lt;<a href="mailto:estliberitas@gmail.com">estliberitas@gmail.com</a>&gt;</li>
<li><a href="https://github.com/chrisdickinson">chrisdickinson</a> -
<strong>Chris Dickinson</strong> &lt;<a href="mailto:christopher.s.dickinson@gmail.com">christopher.s.dickinson@gmail.com</a>&gt;</li>
<li><a href="https://github.com/firedfox">firedfox</a> -
<strong>Daniel Wang</strong> &lt;<a href="mailto:wangyang0123@gmail.com">wangyang0123@gmail.com</a>&gt;</li>
<li><a href="https://github.com/imran-iq">imran-iq</a> -
<strong>Imran Iqbal</strong> &lt;<a href="mailto:imran@imraniqbal.org">imran@imraniqbal.org</a>&gt;</li>
<li><a href="https://github.com/isaacs">isaacs</a> -
<strong>Isaac Z. Schlueter</strong> &lt;<a href="mailto:i@izs.me">i@izs.me</a>&gt;</li>
<li><a href="https://github.com/jhamhader">jhamhader</a> -
<strong>Yuval Brik</strong> &lt;<a href="mailto:yuval@brik.org.il">yuval@brik.org.il</a>&gt;</li>
<li><a href="https://github.com/lxe">lxe</a> -
<strong>Aleksey Smolenchuk</strong> &lt;<a href="mailto:lxe@lxe.co">lxe@lxe.co</a>&gt;</li>
<li><a href="https://github.com/matthewloring">matthewloring</a> -
<strong>Matthew Loring</strong> &lt;<a href="mailto:mattloring@google.com">mattloring@google.com</a>&gt;</li>
<li><a href="https://github.com/micnic">micnic</a> -
<strong>Nicu Micleușanu</strong> &lt;<a href="mailto:micnic90@gmail.com">micnic90@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/mikeal">mikeal</a> -
<strong>Mikeal Rogers</strong> &lt;<a href="mailto:mikeal.rogers@gmail.com">mikeal.rogers@gmail.com</a>&gt;</li>
<li><a href="https://github.com/monsanto">monsanto</a> -
<strong>Christopher Monsanto</strong> &lt;<a href="mailto:chris@monsan.to">chris@monsan.to</a>&gt;</li>
<li><a href="https://github.com/Olegas">Olegas</a> -
<strong>Oleg Elifantiev</strong> &lt;<a href="mailto:oleg@elifantiev.ru">oleg@elifantiev.ru</a>&gt;</li>
<li><a href="https://github.com/orangemocha">orangemocha</a> -
<strong>Alexis Campailla</strong> &lt;<a href="mailto:orangemocha@nodejs.org">orangemocha@nodejs.org</a>&gt;</li>
<li><a href="https://github.com/othiym23">othiym23</a> -
<strong>Forrest L Norvell</strong> &lt;<a href="mailto:ogd@aoaioxxysz.net">ogd@aoaioxxysz.net</a>&gt; (he/him)</li>
<li><a href="https://github.com/petkaantonov">petkaantonov</a> -
<strong>Petka Antonov</strong> &lt;<a href="mailto:petka_antonov@hotmail.com">petka_antonov@hotmail.com</a>&gt;</li>
<li><a href="https://github.com/phillipj">phillipj</a> -
<strong>Phillip Johnsen</strong> &lt;<a href="mailto:johphi@gmail.com">johphi@gmail.com</a>&gt;</li>
<li><a href="https://github.com/piscisaureus">piscisaureus</a> -
<strong>Bert Belder</strong> &lt;<a href="mailto:bertbelder@gmail.com">bertbelder@gmail.com</a>&gt;</li>
<li><a href="https://github.com/pmq20">pmq20</a> -
<strong>Minqi Pan</strong> &lt;<a href="mailto:pmq2001@gmail.com">pmq2001@gmail.com</a>&gt;</li>
<li><a href="https://github.com/rlidwka">rlidwka</a> -
<strong>Alex Kocharin</strong> &lt;<a href="mailto:alex@kocharin.ru">alex@kocharin.ru</a>&gt;</li>
<li><a href="https://github.com/rmg">rmg</a> -
<strong>Ryan Graham</strong> &lt;<a href="mailto:r.m.graham@gmail.com">r.m.graham@gmail.com</a>&gt;</li>
<li><a href="https://github.com/robertkowalski">robertkowalski</a> -
<strong>Robert Kowalski</strong> &lt;<a href="mailto:rok@kowalski.gd">rok@kowalski.gd</a>&gt;</li>
<li><a href="https://github.com/romankl">romankl</a> -
<strong>Roman Klauke</strong> &lt;<a href="mailto:romaaan.git@gmail.com">romaaan.git@gmail.com</a>&gt;</li>
<li><a href="https://github.com/stefanmb">stefanmb</a> -
<strong>Stefan Budeanu</strong> &lt;<a href="mailto:stefan@budeanu.com">stefan@budeanu.com</a>&gt;</li>
<li><a href="https://github.com/tellnes">tellnes</a> -
<strong>Christian Tellnes</strong> &lt;<a href="mailto:christian@tellnes.no">christian@tellnes.no</a>&gt;</li>
<li><a href="https://github.com/tunniclm">tunniclm</a> -
<strong>Mike Tunnicliffe</strong> &lt;<a href="mailto:m.j.tunnicliffe@gmail.com">m.j.tunnicliffe@gmail.com</a>&gt;</li>
<li><a href="https://github.com/vsemozhetbyt">vsemozhetbyt</a> -
<strong>Vse Mozhet Byt</strong> &lt;<a href="mailto:vsemozhetbyt@gmail.com">vsemozhetbyt@gmail.com</a>&gt; (he/him)</li>
<li><a href="https://github.com/whitlockjc">whitlockjc</a> -
<strong>Jeremy Whitlock</strong> &lt;<a href="mailto:jwhitlock@apache.org">jwhitlock@apache.org</a>&gt;</li>
</ul>
<p>Collaborators follow the <a href="/VisualCurve/node/blob/master/COLLABORATOR_GUIDE.md">COLLABORATOR_GUIDE.md</a> in
maintaining the Node.js project.</p>
<h3><a id="user-content-release-keys" class="anchor" aria-hidden="true" href="#release-keys"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Release Keys</h3>
<p>GPG keys used to sign Node.js releases:</p>
<ul>
<li><strong>Beth Griggs</strong> &lt;<a href="mailto:bethany.griggs@uk.ibm.com">bethany.griggs@uk.ibm.com</a>&gt;
<code>4ED778F539E3634C779C87C6D7062848A1AB005C</code></li>
<li><strong>Colin Ihrig</strong> &lt;<a href="mailto:cjihrig@gmail.com">cjihrig@gmail.com</a>&gt;
<code>94AE36675C464D64BAFA68DD7434390BDBE9B9C5</code></li>
<li><strong>Evan Lucas</strong> &lt;<a href="mailto:evanlucas@me.com">evanlucas@me.com</a>&gt;
<code>B9AE9905FFD7803F25714661B63B535A4C206CA9</code></li>
<li><strong>Gibson Fahnestock</strong> &lt;<a href="mailto:gibfahn@gmail.com">gibfahn@gmail.com</a>&gt;
<code>77984A986EBC2AA786BC0F66B01FBB92821C587A</code></li>
<li><strong>James M Snell</strong> &lt;<a href="mailto:jasnell@keybase.io">jasnell@keybase.io</a>&gt;
<code>71DCFD284A79C3B38668286BC97EC7A07EDE3FC1</code></li>
<li><strong>Jeremiah Senkpiel</strong> &lt;<a href="mailto:fishrock@keybase.io">fishrock@keybase.io</a>&gt;
<code>FD3A5288F042B6850C66B31F09FE44734EB7990E</code></li>
<li><strong>Michaël Zasso</strong> &lt;<a href="mailto:targos@protonmail.com">targos@protonmail.com</a>&gt;
<code>8FCCA13FEF1D0C2E91008E09770F7A9A5AE15600</code></li>
<li><strong>Myles Borins</strong> &lt;<a href="mailto:myles.borins@gmail.com">myles.borins@gmail.com</a>&gt;
<code>C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8</code></li>
<li><strong>Rod Vagg</strong> &lt;<a href="mailto:rod@vagg.org">rod@vagg.org</a>&gt;
<code>DD8F2338BAE7501E3DD5AC78C273792F7D83545D</code></li>
<li><strong>Ruben Bridgewater</strong> &lt;<a href="mailto:ruben@bridgewater.de">ruben@bridgewater.de</a>&gt;
<code>A48C2BEE680E841632CD4E44F07496B3EB3C1762</code></li>
<li><strong>Shelley Vohr</strong> &lt;<a href="mailto:shelley.vohr@gmail.com">shelley.vohr@gmail.com</a>&gt;
<code>B9E2F5981AA6E0CD28160D9FF13993A75599653C</code></li>
</ul>
<p>To import the full set of trusted release keys:</p>
<div class="highlight highlight-source-shell"><pre>gpg --keyserver pool.sks-keyservers.net --recv-keys 4ED778F539E3634C779C87C6D7062848A1AB005C
gpg --keyserver pool.sks-keyservers.net --recv-keys B9E2F5981AA6E0CD28160D9FF13993A75599653C
gpg --keyserver pool.sks-keyservers.net --recv-keys 94AE36675C464D64BAFA68DD7434390BDBE9B9C5
gpg --keyserver pool.sks-keyservers.net --recv-keys B9AE9905FFD7803F25714661B63B535A4C206CA9
gpg --keyserver pool.sks-keyservers.net --recv-keys 77984A986EBC2AA786BC0F66B01FBB92821C587A
gpg --keyserver pool.sks-keyservers.net --recv-keys 71DCFD284A79C3B38668286BC97EC7A07EDE3FC1
gpg --keyserver pool.sks-keyservers.net --recv-keys FD3A5288F042B6850C66B31F09FE44734EB7990E
gpg --keyserver pool.sks-keyservers.net --recv-keys 8FCCA13FEF1D0C2E91008E09770F7A9A5AE15600
gpg --keyserver pool.sks-keyservers.net --recv-keys C4F0DFFF4E8C1A8236409D08E73BC641CC11F4C8
gpg --keyserver pool.sks-keyservers.net --recv-keys DD8F2338BAE7501E3DD5AC78C273792F7D83545D
gpg --keyserver pool.sks-keyservers.net --recv-keys A48C2BEE680E841632CD4E44F07496B3EB3C1762</pre></div>
<p>See the section above on <a href="#verifying-binaries">Verifying Binaries</a> for how to
use these keys to verify a downloaded file.</p>
<p>Other keys used to sign some previous releases:</p>
<ul>
<li><strong>Chris Dickinson</strong> &lt;<a href="mailto:christopher.s.dickinson@gmail.com">christopher.s.dickinson@gmail.com</a>&gt;
<code>9554F04D7259F04124DE6B476D5A82AC7E37093B</code></li>
<li><strong>Isaac Z. Schlueter</strong> &lt;<a href="mailto:i@izs.me">i@izs.me</a>&gt;
<code>93C7E9E91B49E432C2F75674B0A78B0A6C481CF6</code></li>
<li><strong>Italo A. Casas</strong> &lt;<a href="mailto:me@italoacasas.com">me@italoacasas.com</a>&gt;
<code>56730D5401028683275BD23C23EFEFE93C4CFFFE</code></li>
<li><strong>Julien Gilli</strong> &lt;<a href="mailto:jgilli@fastmail.fm">jgilli@fastmail.fm</a>&gt;
<code>114F43EE0176B71C7BC219DD50A3051F888C628D</code></li>
<li><strong>Timothy J Fontaine</strong> &lt;<a href="mailto:tjfontaine@gmail.com">tjfontaine@gmail.com</a>&gt;
<code>7937DFD2AB06298B2293C3187D33FF9D0246406D</code></li>
</ul>
</article>
  </div>

    </div>

  

  <details class="details-reset details-overlay details-overlay-dark">
    <summary data-hotkey="l" aria-label="Jump to line"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast linejump" aria-label="Jump to line">
      <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-jump-to-line-form Box-body d-flex" action="" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
        <input class="form-control flex-auto mr-3 linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
        <button type="submit" class="btn" data-close-dialog>Go</button>
</form>    </details-dialog>
  </details>



  </div>
</div>

    </main>
  </div>
  

  </div>

        
<div class="footer container-lg width-full p-responsive" role="contentinfo">
  <div class="position-relative d-flex flex-row-reverse flex-lg-row flex-wrap flex-lg-nowrap flex-justify-center flex-lg-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
      <li class="mr-3 mr-lg-0">&copy; 2019 <span title="0.43215s from unicorn-687bb95c97-tppnk">GitHub</span>, Inc.</li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy</a></li>
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to security, text:security" href="https://github.com/security">Security</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://githubstatus.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a data-ga-click="Footer, go to help, text:help" href="https://help.github.com">Help</a></li>
    </ul>

    <a aria-label="Homepage" title="GitHub" class="footer-octicon d-none d-lg-block mx-lg-4" href="https://github.com">
      <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
   <ul class="list-style-none d-flex flex-wrap col-12 col-lg-5 flex-justify-center flex-lg-justify-between mb-2 mb-lg-0">
        <li class="mr-3 mr-lg-0"><a data-ga-click="Footer, go to contact, text:contact" href="https://github.com/contact">Contact GitHub</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.com/pricing" data-ga-click="Footer, go to Pricing, text:Pricing">Pricing</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3 mr-lg-0"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
        <li class="mr-3 mr-lg-0"><a href="https://github.blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>

    </ul>
  </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 text-gray-light"></span>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
    </button>
    You can’t perform that action at this time.
  </div>


    
    <script crossorigin="anonymous" integrity="sha512-66yPJ4JAblq1zDn/+3IKWzUuzR0Oin7dKMBwDVuflRlcQHmegTtqoyANZqWlTompijP0bSNSRyk09xnPzusbjw==" type="application/javascript" src="https://github.githubassets.com/assets/frameworks-7cd2951d.js"></script>
    
    <script crossorigin="anonymous" async="async" integrity="sha512-M54FZTZ1ar6gKiYdZzpgGInN7W4YUGVASMZeEDmLgnyv8mWl0efMbw0fkUkUg6wc5dECgHnA22M0HBfhF9znAQ==" type="application/javascript" src="https://github.githubassets.com/assets/github-bootstrap-e5aebd6a.js"></script>
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner" hidden
    >
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.893 1.5c-.183-.31-.52-.5-.887-.5s-.703.19-.886.5L.138 13.499a.98.98 0 0 0 0 1.001c.193.31.53.501.886.501h13.964c.367 0 .704-.19.877-.5a1.03 1.03 0 0 0 .01-1.002L8.893 1.5zm.133 11.497H6.987v-2.003h2.039v2.003zm0-3.004H6.987V5.987h2.039v4.006z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <template id="site-details-dialog">
  <details class="details-reset details-overlay details-overlay-dark lh-default text-gray-dark hx_rsm" open>
    <summary role="button" aria-label="Close dialog"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast hx_rsm-dialog hx_rsm-modal">
      <button class="Box-btn-octicon m-0 btn-octicon position-absolute right-0 top-0" type="button" aria-label="Close dialog" data-close-dialog>
        <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48L7.48 8z"/></svg>
      </button>
      <div class="octocat-spinner my-6 js-details-dialog-spinner"></div>
    </details-dialog>
  </details>
</template>

  <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;" tabindex="0">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box box-shadow-large" style="width:360px;">
  </div>
</div>

  <div aria-live="polite" class="js-global-screen-reader-notice sr-only"></div>

  </body>
</html>

