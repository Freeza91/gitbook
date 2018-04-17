





<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8">
  <link rel="dns-prefetch" href="https://assets-cdn.github.com">
  <link rel="dns-prefetch" href="https://avatars0.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars1.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars2.githubusercontent.com">
  <link rel="dns-prefetch" href="https://avatars3.githubusercontent.com">
  <link rel="dns-prefetch" href="https://github-cloud.s3.amazonaws.com">
  <link rel="dns-prefetch" href="https://user-images.githubusercontent.com/">



  <link crossorigin="anonymous" media="all" rel="stylesheet" href="https://assets-cdn.github.com/assets/frameworks-592c4aa40e940d1b0607a3cf272916ff.css" />
  <link crossorigin="anonymous" media="all" rel="stylesheet" href="https://assets-cdn.github.com/assets/github-fdbbae74da4136fd4258a92eb943be60.css" />
  
  
  <link crossorigin="anonymous" media="all" rel="stylesheet" href="https://assets-cdn.github.com/assets/site-348211d27070b0d7bb5d31b1ac3d265b.css" />
  

  <meta name="viewport" content="width=device-width">
  
  <title>openplatform/bot-api.md at master · haobtc/openplatform · GitHub</title>
    <meta name="description" content="GitHub is where people build software. More than 27 million people use GitHub to discover, fork, and contribute to over 80 million projects.">
  <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
  <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
  <meta property="fb:app_id" content="1401488693436528">

    
    <meta property="og:image" content="https://avatars3.githubusercontent.com/u/6447683?s=400&amp;v=4" /><meta property="og:site_name" content="GitHub" /><meta property="og:type" content="object" /><meta property="og:title" content="haobtc/openplatform" /><meta property="og:url" content="https://github.com/haobtc/openplatform" /><meta property="og:description" content="openplatform - Documentation of bixin/haobtc&#39;s open platform" />

  <link rel="assets" href="https://assets-cdn.github.com/">
  
  <meta name="pjax-timeout" content="1000">
  
  <meta name="request-id" content="6AA6:33AB:16CCF9:212994:5AD59932" data-pjax-transient>


  

  <meta name="selected-link" value="repo_source" data-pjax-transient>

    <meta name="google-site-verification" content="KT5gs8h0wvaagLKAVWq8bbeNwnZZK1r1XQysX3xurLU">
  <meta name="google-site-verification" content="ZzhVyEFwb7w3e0-uOTltm8Jsck2F5StVihD0exw2fsA">
  <meta name="google-site-verification" content="GXs5KoUUkNCoaAZn7wPN-t01Pywp9M3sEjnt_3_ZWPc">
    <meta name="google-analytics" content="UA-3769691-2">

<meta name="octolytics-host" content="collector.githubapp.com" /><meta name="octolytics-app-id" content="github" /><meta name="octolytics-event-url" content="https://collector.githubapp.com/github-external/browser_event" /><meta name="octolytics-dimension-request_id" content="6AA6:33AB:16CCF9:212994:5AD59932" /><meta name="octolytics-dimension-region_edge" content="ap-southeast-1" /><meta name="octolytics-dimension-region_render" content="iad" />
<meta name="analytics-location" content="/&lt;user-name&gt;/&lt;repo-name&gt;/blob/show" data-pjax-transient="true" />




  <meta class="js-ga-set" name="dimension1" content="Logged Out">


  

      <meta name="hostname" content="github.com">
    <meta name="user-login" content="">

      <meta name="expected-hostname" content="github.com">
    <meta name="js-proxy-site-detection-payload" content="MWYxNDM0MTdkZjQ2ZjI0NmY3YjA5YjUyOThjZjEyNGZmOWZiZDZjMzMxMzFlMzUwYWI0OWJlYWNiNWE2OTY5ZXx7InJlbW90ZV9hZGRyZXNzIjoiMTE0LjI0MC4yNTMuMjAyIiwicmVxdWVzdF9pZCI6IjZBQTY6MzNBQjoxNkNDRjk6MjEyOTk0OjVBRDU5OTMyIiwidGltZXN0YW1wIjoxNTIzOTQ3ODI3LCJob3N0IjoiZ2l0aHViLmNvbSJ9">

    <meta name="enabled-features" content="UNIVERSE_BANNER,FREE_TRIALS,MARKETPLACE_INSIGHTS,MARKETPLACE_SELF_SERVE,MARKETPLACE_INSIGHTS_CONVERSION_PERCENTAGES">

  <meta name="html-safe-nonce" content="de70c7b13aaebf0052a01b696fa5b9afbc8fb620">

  <meta http-equiv="x-pjax-version" content="b59df07b8cd55bc615e6c910b91c860c">
  

      <link href="https://github.com/haobtc/openplatform/commits/master.atom" rel="alternate" title="Recent Commits to openplatform:master" type="application/atom+xml">

  <meta name="description" content="openplatform - Documentation of bixin/haobtc&#39;s open platform">
  <meta name="go-import" content="github.com/haobtc/openplatform git https://github.com/haobtc/openplatform.git">

  <meta name="octolytics-dimension-user_id" content="6447683" /><meta name="octolytics-dimension-user_login" content="haobtc" /><meta name="octolytics-dimension-repository_id" content="94976424" /><meta name="octolytics-dimension-repository_nwo" content="haobtc/openplatform" /><meta name="octolytics-dimension-repository_public" content="true" /><meta name="octolytics-dimension-repository_is_fork" content="false" /><meta name="octolytics-dimension-repository_network_root_id" content="94976424" /><meta name="octolytics-dimension-repository_network_root_nwo" content="haobtc/openplatform" /><meta name="octolytics-dimension-repository_explore_github_marketplace_ci_cta_shown" content="false" />


    <link rel="canonical" href="https://github.com/haobtc/openplatform/blob/master/doc/bot-api.md" data-pjax-transient>


  <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">

  <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">

  <link rel="mask-icon" href="https://assets-cdn.github.com/pinned-octocat.svg" color="#000000">
  <link rel="icon" type="image/x-icon" class="js-site-favicon" href="https://assets-cdn.github.com/favicon.ico">

<meta name="theme-color" content="#1e2327">



<link rel="manifest" href="/manifest.json" crossOrigin="use-credentials">

  </head>

  <body class="logged-out env-production page-blob">
    

  <div class="position-relative js-header-wrapper ">
    <a href="#start-of-content" tabindex="1" class="px-2 py-4 bg-blue text-white show-on-focus js-skip-to-content">Skip to content</a>
    <div id="js-pjax-loader-bar" class="pjax-loader-bar"><div class="progress"></div></div>

    
    
    



        <header class="Header header-logged-out  position-relative f4 py-3" role="banner">
  <div class="container-lg d-flex px-3">
    <div class="d-flex flex-justify-between flex-items-center">
      <a class="header-logo-invertocat my-0" href="https://github.com/" aria-label="Homepage" data-ga-click="(Logged out) Header, go to homepage, icon:logo-wordmark">
        <svg height="32" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="32" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
      </a>

    </div>

    <div class="HeaderMenu HeaderMenu--bright d-flex flex-justify-between flex-auto">
        <nav class="mt-0">
          <ul class="d-flex list-style-none">
              <li class="ml-2">
                <a class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:features" data-selected-links="/features /features/project-management /features/code-review /features/project-management /features/integrations /features" href="/features">
                  Features
</a>              </li>
              <li class="ml-4">
                <a class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:business" data-selected-links="/business /business/security /business/customers /business" href="/business">
                  Business
</a>              </li>

              <li class="ml-4">
                <a class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:explore" data-selected-links="/explore /trending /trending/developers /integrations /integrations/feature/code /integrations/feature/collaborate /integrations/feature/ship showcases showcases_search showcases_landing /explore" href="/explore">
                  Explore
</a>              </li>

              <li class="ml-4">
                    <a class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:marketplace" data-selected-links=" /marketplace" href="/marketplace">
                      Marketplace
</a>              </li>
              <li class="ml-4">
                <a class="js-selected-navigation-item HeaderNavlink px-0 py-2 m-0" data-ga-click="Header, click, Nav menu - item:pricing" data-selected-links="/pricing /pricing/developer /pricing/team /pricing/business-hosted /pricing/business-enterprise /pricing" href="/pricing">
                  Pricing
</a>              </li>
          </ul>
        </nav>

      <div class="d-flex">
          <div class="d-lg-flex flex-items-center mr-3">
            <div class="header-search scoped-search site-scoped-search js-site-search" role="search">
  <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-site-search-form" data-scoped-search-url="/haobtc/openplatform/search" data-unscoped-search-url="/search" action="/haobtc/openplatform/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
    <label class="form-control header-search-wrapper  js-chromeless-input-container">
          <a class="header-search-scope no-underline" href="/haobtc/openplatform/blob/master/doc/bot-api.md">This repository</a>
      <input type="text"
        class="form-control header-search-input  js-site-search-focus js-site-search-field is-clearable"
        data-hotkey="s,/"
        name="q"
        value=""
        placeholder="Search"
        aria-label="Search this repository"
        data-unscoped-placeholder="Search GitHub"
        data-scoped-placeholder="Search"
        autocapitalize="off"
        >
        <input type="hidden" class="js-site-search-type-field" name="type" >
    </label>
</form></div>

          </div>

        <span class="d-inline-block">
            <div class="HeaderNavlink px-0 py-2 m-0">
              <a class="text-bold text-white no-underline" href="/login?return_to=%2Fhaobtc%2Fopenplatform%2Fblob%2Fmaster%2Fdoc%2Fbot-api.md" data-ga-click="(Logged out) Header, clicked Sign in, text:sign-in">Sign in</a>
                <span class="text-gray">or</span>
                <a class="text-bold text-white no-underline" href="/join?source=header-repo" data-ga-click="(Logged out) Header, clicked Sign up, text:sign-up">Sign up</a>
            </div>
        </span>
      </div>
    </div>
  </div>
</header>

  </div>

  <div id="start-of-content" class="show-on-focus"></div>

    <div id="js-flash-container">
</div>



  <div role="main" class="application-main ">
        <div itemscope itemtype="http://schema.org/SoftwareSourceCode" class="">
    <div id="js-repo-pjax-container" data-pjax-container >
      





  



  <div class="pagehead repohead instapaper_ignore readability-menu experiment-repo-nav  ">
    <div class="repohead-details-container clearfix container">

      <ul class="pagehead-actions">
  <li>
      <a href="/login?return_to=%2Fhaobtc%2Fopenplatform"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to watch a repository" rel="nofollow">
    <svg class="octicon octicon-eye" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.06 2C3 2 0 8 0 8s3 6 8.06 6C13 14 16 8 16 8s-3-6-7.94-6zM8 12c-2.2 0-4-1.78-4-4 0-2.2 1.8-4 4-4 2.22 0 4 1.8 4 4 0 2.22-1.78 4-4 4zm2-4c0 1.11-.89 2-2 2-1.11 0-2-.89-2-2 0-1.11.89-2 2-2 1.11 0 2 .89 2 2z"/></svg>
    Watch
  </a>
  <a class="social-count" href="/haobtc/openplatform/watchers"
     aria-label="25 users are watching this repository">
    25
  </a>

  </li>

  <li>
      <a href="/login?return_to=%2Fhaobtc%2Fopenplatform"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to star a repository" rel="nofollow">
    <svg class="octicon octicon-star" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M14 6l-4.9-.64L7 1 4.9 5.36 0 6l3.6 3.26L2.67 14 7 11.67 11.33 14l-.93-4.74z"/></svg>
    Star
  </a>

    <a class="social-count js-social-count" href="/haobtc/openplatform/stargazers"
      aria-label="9 users starred this repository">
      9
    </a>

  </li>

  <li>
      <a href="/login?return_to=%2Fhaobtc%2Fopenplatform"
        class="btn btn-sm btn-with-count tooltipped tooltipped-n"
        aria-label="You must be signed in to fork a repository" rel="nofollow">
        <svg class="octicon octicon-repo-forked" viewBox="0 0 10 16" version="1.1" width="10" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8 1a1.993 1.993 0 0 0-1 3.72V6L5 8 3 6V4.72A1.993 1.993 0 0 0 2 1a1.993 1.993 0 0 0-1 3.72V6.5l3 3v1.78A1.993 1.993 0 0 0 5 15a1.993 1.993 0 0 0 1-3.72V9.5l3-3V4.72A1.993 1.993 0 0 0 8 1zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3 10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zm3-10c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
        Fork
      </a>

    <a href="/haobtc/openplatform/network" class="social-count"
       aria-label="1 user forked this repository">
      1
    </a>
  </li>
</ul>

      <h1 class="public ">
  <svg class="octicon octicon-repo" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9H3V8h1v1zm0-3H3v1h1V6zm0-2H3v1h1V4zm0-2H3v1h1V2zm8-1v12c0 .55-.45 1-1 1H6v2l-1.5-1.5L3 16v-2H1c-.55 0-1-.45-1-1V1c0-.55.45-1 1-1h10c.55 0 1 .45 1 1zm-1 10H1v2h2v-1h3v1h5v-2zm0-10H2v9h9V1z"/></svg>
  <span class="author" itemprop="author"><a class="url fn" rel="author" href="/haobtc">haobtc</a></span><!--
--><span class="path-divider">/</span><!--
--><strong itemprop="name"><a data-pjax="#js-repo-pjax-container" href="/haobtc/openplatform">openplatform</a></strong>

</h1>

    </div>
    
<nav class="reponav js-repo-nav js-sidenav-container-pjax container"
     itemscope
     itemtype="http://schema.org/BreadcrumbList"
     role="navigation"
     data-pjax="#js-repo-pjax-container">

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a class="js-selected-navigation-item selected reponav-item" itemprop="url" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages /haobtc/openplatform" href="/haobtc/openplatform">
      <svg class="octicon octicon-code" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M9.5 3L8 4.5 11.5 8 8 11.5 9.5 13 14 8 9.5 3zm-5 0L0 8l4.5 5L6 11.5 2.5 8 6 4.5 4.5 3z"/></svg>
      <span itemprop="name">Code</span>
      <meta itemprop="position" content="1">
</a>  </span>

    <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
      <a itemprop="url" data-hotkey="g i" class="js-selected-navigation-item reponav-item" data-selected-links="repo_issues repo_labels repo_milestones /haobtc/openplatform/issues" href="/haobtc/openplatform/issues">
        <svg class="octicon octicon-issue-opened" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7 2.3c3.14 0 5.7 2.56 5.7 5.7s-2.56 5.7-5.7 5.7A5.71 5.71 0 0 1 1.3 8c0-3.14 2.56-5.7 5.7-5.7zM7 1C3.14 1 0 4.14 0 8s3.14 7 7 7 7-3.14 7-7-3.14-7-7-7zm1 3H6v5h2V4zm0 6H6v2h2v-2z"/></svg>
        <span itemprop="name">Issues</span>
        <span class="Counter">0</span>
        <meta itemprop="position" content="2">
</a>    </span>

  <span itemscope itemtype="http://schema.org/ListItem" itemprop="itemListElement">
    <a data-hotkey="g p" itemprop="url" class="js-selected-navigation-item reponav-item" data-selected-links="repo_pulls checks /haobtc/openplatform/pulls" href="/haobtc/openplatform/pulls">
      <svg class="octicon octicon-git-pull-request" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 11.28V5c-.03-.78-.34-1.47-.94-2.06C9.46 2.35 8.78 2.03 8 2H7V0L4 3l3 3V4h1c.27.02.48.11.69.31.21.2.3.42.31.69v6.28A1.993 1.993 0 0 0 10 15a1.993 1.993 0 0 0 1-3.72zm-1 2.92c-.66 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2zM4 3c0-1.11-.89-2-2-2a1.993 1.993 0 0 0-1 3.72v6.56A1.993 1.993 0 0 0 2 15a1.993 1.993 0 0 0 1-3.72V4.72c.59-.34 1-.98 1-1.72zm-.8 10c0 .66-.55 1.2-1.2 1.2-.65 0-1.2-.55-1.2-1.2 0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2zM2 4.2C1.34 4.2.8 3.65.8 3c0-.65.55-1.2 1.2-1.2.65 0 1.2.55 1.2 1.2 0 .65-.55 1.2-1.2 1.2z"/></svg>
      <span itemprop="name">Pull requests</span>
      <span class="Counter">0</span>
      <meta itemprop="position" content="3">
</a>  </span>


    <a class="js-selected-navigation-item reponav-item" data-hotkey="g w" data-selected-links="repo_wiki /haobtc/openplatform/wiki" href="/haobtc/openplatform/wiki">
      <svg class="octicon octicon-book" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M3 5h4v1H3V5zm0 3h4V7H3v1zm0 2h4V9H3v1zm11-5h-4v1h4V5zm0 2h-4v1h4V7zm0 2h-4v1h4V9zm2-6v9c0 .55-.45 1-1 1H9.5l-1 1-1-1H2c-.55 0-1-.45-1-1V3c0-.55.45-1 1-1h5.5l1 1 1-1H15c.55 0 1 .45 1 1zm-8 .5L7.5 3H2v9h6V3.5zm7-.5H9.5l-.5.5V12h6V3z"/></svg>
      Wiki
</a>

  <a class="js-selected-navigation-item reponav-item" data-selected-links="repo_graphs repo_contributors dependency_graph pulse /haobtc/openplatform/pulse" href="/haobtc/openplatform/pulse">
    <svg class="octicon octicon-graph" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M16 14v1H0V0h1v14h15zM5 13H3V8h2v5zm4 0H7V3h2v10zm4 0h-2V6h2v7z"/></svg>
    Insights
</a>

</nav>


  </div>

<div class="container new-discussion-timeline experiment-repo-nav  ">
  <div class="repository-content ">

    
  <a class="d-none js-permalink-shortcut" data-hotkey="y" href="/haobtc/openplatform/blob/23662f0970cfdf03ae569d6ba71a10f076201011/doc/bot-api.md">Permalink</a>

  <!-- blob contrib key: blob_contributors:v21:c42faf32194d2712b2cc555b893f682e -->

  <div class="file-navigation">
    
<div class="select-menu branch-select-menu js-menu-container js-select-menu float-left">
  <button class=" btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    
    type="button" aria-label="Switch branches or tags" aria-expanded="false" aria-haspopup="true">
      <i>Branch:</i>
      <span class="js-select-button css-truncate-target">master</span>
  </button>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax>

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <svg class="octicon octicon-x js-menu-close" role="img" aria-label="Close" viewBox="0 0 12 16" version="1.1" width="12" height="16"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
        <span class="select-menu-title">Switch branches/tags</span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="form-control js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab" role="tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab" role="tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches" role="menu">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/haobtc/openplatform/blob/master/doc/bot-api.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <svg class="octicon octicon-check select-menu-item-icon" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M12 5l-8 8-4-4 1.5-1.5L4 10l6.5-6.5z"/></svg>
              <span class="select-menu-item-text css-truncate-target js-select-menu-filter-text">
                master
              </span>
            </a>
        </div>

          <div class="select-menu-no-results">Nothing to show</div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="tags">
        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


        </div>

        <div class="select-menu-no-results">Nothing to show</div>
      </div>

    </div>
  </div>
</div>

    <div class="BtnGroup float-right">
      <a href="/haobtc/openplatform/find/master"
            class="js-pjax-capture-input btn btn-sm BtnGroup-item"
            data-pjax
            data-hotkey="t">
        Find file
      </a>
      <clipboard-copy
            for="blob-path"
            aria-label="Copy file path to clipboard"
            class="btn btn-sm BtnGroup-item tooltipped tooltipped-s"
            copied-label="Copied!">
        Copy path
      </clipboard-copy>
    </div>
    <div id="blob-path" class="breadcrumb">
      <span class="repo-root js-repo-root"><span class="js-path-segment"><a data-pjax="true" href="/haobtc/openplatform"><span>openplatform</span></a></span></span><span class="separator">/</span><span class="js-path-segment"><a data-pjax="true" href="/haobtc/openplatform/tree/master/doc"><span>doc</span></a></span><span class="separator">/</span><strong class="final-path">bot-api.md</strong>
    </div>
  </div>


  <include-fragment src="/haobtc/openplatform/contributors/master/doc/bot-api.md" class="commit-tease">
    <div>
      Fetching contributors&hellip;
    </div>

    <div class="commit-tease-contributors">
      <img alt="" class="loader-loading float-left" src="https://assets-cdn.github.com/images/spinners/octocat-spinner-32-EAF2F5.gif" width="16" height="16" />
      <span class="loader-error">Cannot retrieve contributors at this time</span>
    </div>
</include-fragment>


  <div class="file">
    <div class="file-header">
  <div class="file-actions">

    <div class="BtnGroup">
      <a id="raw-url" class="btn btn-sm BtnGroup-item" href="/haobtc/openplatform/raw/master/doc/bot-api.md">Raw</a>
        <a class="btn btn-sm js-update-url-with-hash BtnGroup-item" data-hotkey="b" href="/haobtc/openplatform/blame/master/doc/bot-api.md">Blame</a>
      <a rel="nofollow" class="btn btn-sm BtnGroup-item" href="/haobtc/openplatform/commits/master/doc/bot-api.md">History</a>
    </div>


        <button type="button" class="btn-octicon disabled tooltipped tooltipped-nw"
          aria-label="You must be signed in to make or propose changes">
          <svg class="octicon octicon-pencil" viewBox="0 0 14 16" version="1.1" width="14" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M0 12v3h3l8-8-3-3-8 8zm3 2H1v-2h1v1h1v1zm10.3-9.3L12 6 9 3l1.3-1.3a.996.996 0 0 1 1.41 0l1.59 1.59c.39.39.39 1.02 0 1.41z"/></svg>
        </button>
        <button type="button" class="btn-octicon btn-octicon-danger disabled tooltipped tooltipped-nw"
          aria-label="You must be signed in to make or propose changes">
          <svg class="octicon octicon-trashcan" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M11 2H9c0-.55-.45-1-1-1H5c-.55 0-1 .45-1 1H2c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1v9c0 .55.45 1 1 1h7c.55 0 1-.45 1-1V5c.55 0 1-.45 1-1V3c0-.55-.45-1-1-1zm-1 12H3V5h1v8h1V5h1v8h1V5h1v8h1V5h1v9zm1-10H2V3h9v1z"/></svg>
        </button>
  </div>

  <div class="file-info">
      653 lines (548 sloc)
      <span class="file-info-divider"></span>
    15.9 KB
  </div>
</div>

    
  <div id="readme" class="readme blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="text"><h2><a id="user-content-bot-api" class="anchor" aria-hidden="true" href="#bot-api"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Bot API</h2>
<p>Bot API可以让服务号和用户互动。用户在服务号内发生动作时，币信服务器会向指定的Bot Callback地址发送用户的动作信息。第三方服务通过解析用户的动作行为，通过Bot API来和用户进行交互：回复文本、图片、选择事件、填写表单、广播图文等等。</p>
<h2><a id="user-content-bot初始化" class="anchor" aria-hidden="true" href="#bot初始化"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>Bot初始化</h2>
<p>在Vendor页面中可以查看到详细的Bot信息：</p>
<p><a target="_blank" href="https://raw.githubusercontent.com/haobtc/openplatform/master/images/bot_info_key.png"><img src="https://raw.githubusercontent.com/haobtc/openplatform/master/images/bot_info_key.png" alt="image" style="max-width:100%;"></a></p>
<p>Bot Access Token是和币信交互的凭证。
Bot AES Key和币信交互的数据加密Key。</p>
<p>创建一个Bot:</p>
<div class="highlight highlight-source-python"><pre><span class="pl-k">class</span> <span class="pl-en">Bot</span>(<span class="pl-c1">object</span>):
    <span class="pl-k">def</span> <span class="pl-c1">__init__</span>(<span class="pl-smi"><span class="pl-smi">self</span></span>, <span class="pl-smi">name</span><span class="pl-k">=</span>settings.<span class="pl-c1">APP_NAME</span>,
                 <span class="pl-smi">bot_access_token</span><span class="pl-k">=</span>settings.<span class="pl-c1">BOT_ACCESS_TOKEN</span>,
                 <span class="pl-smi">bot_aes_key</span><span class="pl-k">=</span>settings.<span class="pl-c1">BOT_AES_KEY</span>):

        <span class="pl-c1">self</span>.name <span class="pl-k">=</span> name
        <span class="pl-c1">self</span>.bot_access_token <span class="pl-k">=</span> bot_access_token
        <span class="pl-c1">self</span>.bot_aes_key <span class="pl-k">=</span> bot_aes_key

        <span class="pl-c1">self</span>.pc <span class="pl-k">=</span> Prpcrypt(<span class="pl-c1">self</span>.bot_aes_key)
        <span class="pl-c1">self</span>.evt <span class="pl-k">=</span> <span class="pl-c1">None</span>

bot <span class="pl-k">=</span> Bot()
</pre></div>
<p><a href="/haobtc/openplatform/blob/master/lib/bixin/bot.py">详细参考代码</a></p>
<h2><a id="user-content-api" class="anchor" aria-hidden="true" href="#api"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>API</h2>
<h3><a id="user-content-文本消息" class="anchor" aria-hidden="true" href="#文本消息"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>文本消息</h3>
<p>Content-Type: application/x-www-form-urlencoded</p>
<pre><code>POST https://openapi.bixin.im/api/v2/bot.postText
</code></pre>
<p>参数：</p>
<table>
<thead>
<tr>
<th>名称(name)</th>
<th>描述(description)</th>
</tr>
</thead>
<tbody>
<tr>
<td>target_id</td>
<td>发送对象的id</td>
</tr>
<tr>
<td>text</td>
<td>发送文本</td>
</tr>
<tr>
<td>request_id</td>
<td>请求消息id 用uuid生成</td>
</tr></tbody></table>
<p>返回：</p>
<div class="highlight highlight-source-json"><pre>{
	<span class="pl-s"><span class="pl-pds">"</span>ok<span class="pl-pds">"</span></span>: <span class="pl-c1">true</span>,
	<span class="pl-s"><span class="pl-pds">"</span>data<span class="pl-pds">"</span></span>: {
		<span class="pl-s"><span class="pl-pds">"</span>created_at<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>2017-07-07T03:08:59.871191<span class="pl-pds">"</span></span>,
		<span class="pl-s"><span class="pl-pds">"</span>content_type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>text<span class="pl-pds">"</span></span>,
		<span class="pl-s"><span class="pl-pds">"</span>content<span class="pl-pds">"</span></span>: {
			<span class="pl-s"><span class="pl-pds">"</span>text<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>text<span class="pl-pds">"</span></span>
		},
		<span class="pl-s"><span class="pl-pds">"</span>sender<span class="pl-pds">"</span></span>: {
			<span class="pl-s"><span class="pl-pds">"</span>name<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>bot_test<span class="pl-pds">"</span></span>,
			<span class="pl-s"><span class="pl-pds">"</span>nickname<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>Ghost bot<span class="pl-pds">"</span></span>,
			<span class="pl-s"><span class="pl-pds">"</span>avatar_url<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>https://openapi.bixin.im/res/vendor_fin_dollar2.png<span class="pl-pds">"</span></span>,
			<span class="pl-s"><span class="pl-pds">"</span>gender<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>,
			<span class="pl-s"><span class="pl-pds">"</span>menu<span class="pl-pds">"</span></span>: [{
				<span class="pl-s"><span class="pl-pds">"</span>icon_url<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>https://openapi.bixin.im/res/faq.png<span class="pl-pds">"</span></span>,
				<span class="pl-s"><span class="pl-pds">"</span>desc<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>Test<span class="pl-pds">"</span></span>,
				<span class="pl-s"><span class="pl-pds">"</span>action<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>bixin://postevent?event=index_view&amp;text=Test&amp;target_id=f2c5609ae91c4a2ab20c4b196aac9b4a&amp;conv_type=bot<span class="pl-pds">"</span></span>
			}],
			<span class="pl-s"><span class="pl-pds">"</span>btc_address<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>1Har9AL8QyRuQ5DiLfm6kFndscbVR6ctHG<span class="pl-pds">"</span></span>,
			<span class="pl-s"><span class="pl-pds">"</span>desc<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>Bixin Official Service<span class="pl-pds">"</span></span>,
			<span class="pl-s"><span class="pl-pds">"</span>id<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>f2c5609ae91c4a2ab20c4b196aac9b4a<span class="pl-pds">"</span></span>,
			<span class="pl-s"><span class="pl-pds">"</span>conv_type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>bot<span class="pl-pds">"</span></span>
		},
		<span class="pl-s"><span class="pl-pds">"</span>brief<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>text<span class="pl-pds">"</span></span>,
		<span class="pl-s"><span class="pl-pds">"</span>request_id<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>a573e676casa44259dc0ee29087adea23<span class="pl-pds">"</span></span>,
		<span class="pl-s"><span class="pl-pds">"</span>prev_id<span class="pl-pds">"</span></span>: <span class="pl-c1">9363</span>,
		<span class="pl-s"><span class="pl-pds">"</span>receiver<span class="pl-pds">"</span></span>: {
			<span class="pl-s"><span class="pl-pds">"</span>name<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>echo<span class="pl-pds">"</span></span>,
			<span class="pl-s"><span class="pl-pds">"</span>nickname<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>12555<span class="pl-pds">"</span></span>,
			<span class="pl-s"><span class="pl-pds">"</span>avatar_url<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>https://openapi.bixin.im/upload/2017/05/11/6146c20c214745f3b29b73216fe47fd1.png<span class="pl-pds">"</span></span>,
			<span class="pl-s"><span class="pl-pds">"</span>gender<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>male<span class="pl-pds">"</span></span>,
			<span class="pl-s"><span class="pl-pds">"</span>menu<span class="pl-pds">"</span></span>: [],
			<span class="pl-s"><span class="pl-pds">"</span>btc_address<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>1vkJV6bnJdbjocerXjLJkc3tEsjmEjh94<span class="pl-pds">"</span></span>,
			<span class="pl-s"><span class="pl-pds">"</span>desc<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>,
			<span class="pl-s"><span class="pl-pds">"</span>id<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>a573e67b760a44259dc0ee29087ade72<span class="pl-pds">"</span></span>,
			<span class="pl-s"><span class="pl-pds">"</span>conv_type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>private<span class="pl-pds">"</span></span>
		},
		<span class="pl-s"><span class="pl-pds">"</span>id<span class="pl-pds">"</span></span>: <span class="pl-c1">9364</span>,
		<span class="pl-s"><span class="pl-pds">"</span>is_mute<span class="pl-pds">"</span></span>: <span class="pl-c1">false</span>,
		<span class="pl-s"><span class="pl-pds">"</span>conv_type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>bot<span class="pl-pds">"</span></span>
	}
}</pre></div>
<h3><a id="user-content-图片消息" class="anchor" aria-hidden="true" href="#图片消息"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>图片消息</h3>
<p>Content-Type: multipart/form-data</p>
<pre><code>POST https://openapi.bixin.im/api/v2/bot.postImage
</code></pre>
<p>参数：</p>
<table>
<thead>
<tr>
<th>名称(name)</th>
<th>描述(description)</th>
</tr>
</thead>
<tbody>
<tr>
<td>target_id</td>
<td>发送对象的id</td>
</tr>
<tr>
<td>request_id</td>
<td>请求消息id 用uuid生成</td>
</tr>
<tr>
<td>conv_type</td>
<td>会话类型, 可选[private,group]</td>
</tr>
<tr>
<td>file</td>
<td>image文件</td>
</tr></tbody></table>
<p>返回：</p>
<pre><code>{
	"ok": true,
	"data": {
		"content_type": "image",
		"conv_type": "bot",
		"sender": {
			"nickname": "Ghost bot",
			"avatar_url": "https://openapi.bixin.im/res/vendor_fin_dollar2.png",
			"conv_type": "bot",
			"name": "bot_test",
			"id": "f2c5609ae91c4a2ab20c4b196aac9b4a",
			"btc_address": "1Har9AL8QyRuQ5DiLfm6kFndscbVR6ctHG",
			"gender": "",
			"menu": [{
				"icon_url": "https://openapi.bixin.im/res/faq.png",
				"desc": "Test",
				"action": "bixin://postevent?event=index_view&amp;text=Test&amp;target_id=f2c5609ae91c4a2ab20c4b196aac9b4a&amp;conv_type=bot"
			}],
			"desc": "Bixin Official Service"
		},
		"id": 10560,
		"request_id": "a1273e67b760a44259dc0ee29087ade722",
		"content": {
			"image_url": "https://openapi.bixin.im/upload/2017/07/07/a75955a4165e4b5990ea9559ce794f94.png",
			"image_height": 768,
			"thumb_height": 112,
			"thumb_url": "https://openapi.bixin.im/upload/2017/07/07/a75955a4165e4b5990ea9559ce794f94.png",
			"thumb_width": 200,
			"image_width": 1366
		},
		"prev_id": 10558,
		"receiver": {
			"nickname": "Echo",
			"avatar_url": "https://openapi.bixin.im/upload/2017/07/07/1adf8b1675e84435aa5e3c6a2202a825.png",
			"conv_type": "private",
			"name": "echo",
			"id": "a573e67b760a44259dc0ee29087ade72",
			"btc_address": "1vkJV6bnJdbjocerXjLJkc3tEsjmEjh94",
			"gender": "male",
			"menu": [],
			"desc": ""
		},
		"brief": "Image",
		"created_at": "2017-07-07T08:18:45.487664",
		"is_mute": false
	}
}
</code></pre>
<h3><a id="user-content-select-消息" class="anchor" aria-hidden="true" href="#select-消息"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>select 消息</h3>
<p>Content-Type: application/json</p>
<pre><code>POST https://openapi.bixin.im/api/v2/bot.postSelect
</code></pre>
<p>参数：</p>
<table>
<thead>
<tr>
<th>名称(name)</th>
<th>描述(description)</th>
</tr>
</thead>
<tbody>
<tr>
<td>target_id</td>
<td>发送对象的id</td>
</tr>
<tr>
<td>request_id</td>
<td>请求消息id 用uuid生成</td>
</tr>
<tr>
<td>conv_type</td>
<td>会话类型, 可选[private,group]</td>
</tr>
<tr>
<td>text</td>
<td>发送文本</td>
</tr>
<tr>
<td>select</td>
<td>消息内容为数组[{'desc': '', 'image_url': '', 'image_width': '', 'image_height': '', 'action': ''}]</td>
</tr></tbody></table>
<p>返回：</p>
<pre><code>{
	"ok": true,
	"data": {
		"created_at": "2017-07-07T03:51:23.330868",
		"content_type": "select",
		"content": {
			"text": "text",
			"select": [{
					"desc": "desc",
					"image_url": "image_url",
					"image_width": "image_width",
					"image_height": "image_height",
					"action": "bixin://postevent/?target_id=f2c5609ae91c4a2ab20c4b196aac9b4a&amp;conv_type=bot&amp;text=desc&amp;event=action"
				},
				{
					"desc": "desc2",
					"image_url": "imgae_url2",
					"image_width": "image_width2",
					"image_height": "image_height2",
					"action": "bixin://postevent/?target_id=f2c5609ae91c4a2ab20c4b196aac9b4a&amp;conv_type=bot&amp;text=desc2&amp;event=action2"
				}
			]
		},
		"sender": {
			"name": "bot_test",
			"nickname": "Ghost bot",
			"avatar_url": "https://openapi.bixin.im/res/vendor_fin_dollar2.png",
			"gender": "",
			"menu": [{
				"icon_url": "https://openapi.bixin.im/res/faq.png",
				"desc": "Test",
				"action": "bixin://postevent?event=index_view&amp;text=Test&amp;target_id=f2c5609ae91c4a2ab20c4b196aac9b4a&amp;conv_type=bot"
			}],
			"btc_address": "1Har9AL8QyRuQ5DiLfm6kFndscbVR6ctHG",
			"desc": "Bixin Official Service",
			"id": "f2c5609ae91c4a2ab20c4b196aac9b4a",
			"conv_type": "bot"
		},
		"brief": "text",
		"request_id": "a573a17a0asess251dc0ee29087adea23",
		"prev_id": 9369,
		"receiver": {
			"name": "echo",
			"nickname": "12555",
			"avatar_url": "https://openapi.bixin.im/upload/2017/05/11/6146c20c214745f3b29b73216fe47fd1.png",
			"gender": "male",
			"menu": [],
			"btc_address": "1vkJV6bnJdbjocerXjLJkc3tEsjmEjh94",
			"desc": "",
			"id": "a573e67b760a44259dc0ee29087ade72",
			"conv_type": "private"
		},
		"id": 9370,
		"is_mute": false,
		"conv_type": "bot"
	}
}
</code></pre>
<h3><a id="user-content-文章消息" class="anchor" aria-hidden="true" href="#文章消息"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>文章消息</h3>
<p>Content-Type: application/x-www-form-urlencoded</p>
<pre><code>POST https://openapi.bixin.im/api/v2/bot.postArticle
</code></pre>
<p>参数：</p>
<table>
<thead>
<tr>
<th>名称(name)</th>
<th>描述(description)</th>
</tr>
</thead>
<tbody>
<tr>
<td>target_id</td>
<td>发送对象的id</td>
</tr>
<tr>
<td>request_id</td>
<td>请求消息id 用uuid生成</td>
</tr>
<tr>
<td>conv_type</td>
<td>会话类型, 可选[private,group]</td>
</tr>
<tr>
<td>title</td>
<td>artilce 消息标题</td>
</tr>
<tr>
<td>desc</td>
<td>artilce 消息标描述</td>
</tr>
<tr>
<td>image_url</td>
<td>背景图片url</td>
</tr>
<tr>
<td>action</td>
<td>跳转连接或者 event</td>
</tr></tbody></table>
<p>返回：</p>
<pre><code>{
	"ok": true,
	"data": {
		"created_at": "2017-07-07T03:35:44.246799",
		"content_type": "article",
		"content": {
			"desc": "desc描述",
			"image_url": "https://bixin.im/static/images/logo_scroll@2x.21af7c9605c2.png",
			"background": "https://bixin.im/static/images/logo_scroll@2x.21af7c9605c2.png",
			"title": "title标题",
			"action": "bixin://webview_auth/?url=https://bixin.im&amp;bot_id=f2c5609ae91c4a2ab20c4b196aac9b4a"
		},
		"sender": {
			"name": "bot_test",
			"nickname": "Ghost bot",
			"avatar_url": "https://openapi.bixin.im/res/vendor_fin_dollar2.png",
			"gender": "",
			"menu": [{
				"icon_url": "https://openapi.bixin.im/res/faq.png",
				"desc": "Test",
				"action": "bixin://postevent?event=index_view&amp;text=Test&amp;target_id=f2c5609ae91c4a2ab20c4b196aac9b4a&amp;conv_type=bot"
			}],
			"btc_address": "1Har9AL8QyRuQ5DiLfm6kFndscbVR6ctHG",
			"desc": "Bixin Official Service",
			"id": "f2c5609ae91c4a2ab20c4b196aac9b4a",
			"conv_type": "bot"
		},
		"brief": "Article",
		"request_id": "a573e4760as144259dc0ee29087adea23",
		"prev_id": 9366,
		"receiver": {
			"name": "echo",
			"nickname": "12555",
			"avatar_url": "https://openapi.bixin.im/upload/2017/05/11/6146c20c214745f3b29b73216fe47fd1.png",
			"gender": "male",
			"menu": [],
			"btc_address": "1vkJV6bnJdbjocerXjLJkc3tEsjmEjh94",
			"desc": "",
			"id": "a573e67b760a44259dc0ee29087ade72",
			"conv_type": "private"
		},
		"id": 9369,
		"is_mute": false,
		"conv_type": "bot"
	}
}
</code></pre>
<h3><a id="user-content-广播文本" class="anchor" aria-hidden="true" href="#广播文本"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>广播文本</h3>
<p>Content-Type: application/x-www-form-urlencoded</p>
<pre><code>POST https://openapi.bixin.im/api/v2/bot.broadcastText
</code></pre>
<p>参数：</p>
<table>
<thead>
<tr>
<th>名称(name)</th>
<th>描述(description)</th>
</tr>
</thead>
<tbody>
<tr>
<td>text</td>
<td>发送文本</td>
</tr></tbody></table>
<p>返回：</p>
<pre><code>{"ok": true}

</code></pre>
<h3><a id="user-content-广播图片" class="anchor" aria-hidden="true" href="#广播图片"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>广播图片</h3>
<p>Content-Type: multipart/form-data</p>
<pre><code>POST https://openapi.bixin.im/api/v2/bot.broadcastImage
</code></pre>
<p>参数：</p>
<table>
<thead>
<tr>
<th>名称(name)</th>
<th>描述(description)</th>
</tr>
</thead>
<tbody>
<tr>
<td>file</td>
<td>image文件</td>
</tr></tbody></table>
<p>返回：</p>
<pre><code>{"ok": true}

</code></pre>
<h3><a id="user-content-广播文章" class="anchor" aria-hidden="true" href="#广播文章"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>广播文章</h3>
<p>Content-Type: application/x-www-form-urlencoded</p>
<pre><code>POST https://openapi.bixin.im/api/v2/bot.broadcastArticle
</code></pre>
<p>参数：</p>
<table>
<thead>
<tr>
<th>名称(name)</th>
<th>描述(description)</th>
</tr>
</thead>
<tbody>
<tr>
<td>target_id</td>
<td>发送对象的id</td>
</tr>
<tr>
<td>request_id</td>
<td>请求消息id 用uuid生成</td>
</tr>
<tr>
<td>conv_type</td>
<td>会话类型, 可选[private,group]</td>
</tr>
<tr>
<td>title</td>
<td>artilce 消息标题</td>
</tr>
<tr>
<td>desc</td>
<td>artilce 消息标描述</td>
</tr>
<tr>
<td>image_url</td>
<td>背景图片url</td>
</tr>
<tr>
<td>action</td>
<td>跳转连接或者 event</td>
</tr></tbody></table>
<p>返回：</p>
<pre><code>{"ok": true}
</code></pre>
<h3><a id="user-content-广播置顶消息" class="anchor" aria-hidden="true" href="#广播置顶消息"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>广播置顶消息</h3>
<p>Content-Type: application/x-www-form-urlencoded</p>
<pre><code>POST https://openapi.bixin.im/api/v2/bot.broadcastSticky
</code></pre>
<p>参数：</p>
<table>
<thead>
<tr>
<th>名称(name)</th>
<th>描述(description)</th>
</tr>
</thead>
<tbody>
<tr>
<td>text</td>
<td>文本</td>
</tr>
<tr>
<td>action_text</td>
<td>action文本</td>
</tr>
<tr>
<td>action</td>
<td>跳转连接或者 event</td>
</tr>
<tr>
<td>closable</td>
<td>是否关闭 取值为0(False),1(True)</td>
</tr></tbody></table>
<p>返回：</p>
<pre><code>{"ok": true}
</code></pre>
<h3><a id="user-content-广播select消息" class="anchor" aria-hidden="true" href="#广播select消息"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>广播select消息</h3>
<p>Content-Type: application/json</p>
<pre><code>POST https://openapi.bixin.im/api/v2/bot.broadcastSelect
</code></pre>
<p>参数：</p>
<table>
<thead>
<tr>
<th>名称(name)</th>
<th>描述(description)</th>
</tr>
</thead>
<tbody>
<tr>
<td>target_id</td>
<td>发送对象的id</td>
</tr>
<tr>
<td>request_id</td>
<td>请求消息id 用uuid生成</td>
</tr>
<tr>
<td>conv_type</td>
<td>会话类型, 可选[private,group]</td>
</tr>
<tr>
<td>select</td>
<td>消息内容为数组: ['desc': '', 'image_url': '', 'action': '跳转连接或者event']</td>
</tr></tbody></table>
<p>返回：</p>
<pre><code>{"ok": true}
</code></pre>
<h3><a id="user-content-获取粉丝用户信息" class="anchor" aria-hidden="true" href="#获取粉丝用户信息"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>获取粉丝用户信息</h3>
<pre><code>GET https://openapi.bixin.im/api/v2/bot.getFollowers
</code></pre>
<p>返回：</p>
<div class="highlight highlight-source-json"><pre>{
    <span class="pl-s"><span class="pl-pds">"</span>ok<span class="pl-pds">"</span></span>: <span class="pl-c1">true</span>,
    <span class="pl-s"><span class="pl-pds">"</span>data<span class="pl-pds">"</span></span>: {
        <span class="pl-s"><span class="pl-pds">"</span>followers<span class="pl-pds">"</span></span>: [
            {
                <span class="pl-s"><span class="pl-pds">"</span>username<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>echo<span class="pl-pds">"</span></span>,
                <span class="pl-s"><span class="pl-pds">"</span>id<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>a573e67b760a44259dc0ee29087ade72<span class="pl-pds">"</span></span>,
                <span class="pl-s"><span class="pl-pds">"</span>nickname<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>heid<span class="pl-pds">"</span></span>
            },
            {
                <span class="pl-s"><span class="pl-pds">"</span>username<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>ttttt<span class="pl-pds">"</span></span>,
                <span class="pl-s"><span class="pl-pds">"</span>id<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>c94aa4caa38444f6bd7b4c86e10e5c3e<span class="pl-pds">"</span></span>,
                <span class="pl-s"><span class="pl-pds">"</span>nickname<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>wqfas<span class="pl-pds">"</span></span>
            }
        ]
    }
}</pre></div>
<h3><a id="user-content-收款消息" class="anchor" aria-hidden="true" href="#收款消息"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>收款消息</h3>
<p>Content-Type: application/x-www-form-urlencoded</p>
<pre><code>POST https://openapi.bixin.im/api/v2/bot.postPaymentRequest
</code></pre>
<p>参数：</p>
<table>
<thead>
<tr>
<th>名称(name)</th>
<th>描述(description)</th>
</tr>
</thead>
<tbody>
<tr>
<td>target_id</td>
<td>发送对象的id</td>
</tr>
<tr>
<td>request_id</td>
<td>请求消息id 用uuid生成</td>
</tr>
<tr>
<td>conv_type</td>
<td>会话类型, 可选[private,group]</td>
</tr>
<tr>
<td>file</td>
<td>image文件</td>
</tr>
<tr>
<td>btc_address</td>
<td>vendor的比特币地址</td>
</tr>
<tr>
<td>message</td>
<td>备注内容</td>
</tr>
<tr>
<td>amount_btc</td>
<td>收款BTC数量</td>
</tr>
<tr>
<td>arg0</td>
<td>arg[0-9]自定义参数</td>
</tr></tbody></table>
<p>返回：</p>
<div class="highlight highlight-source-json"><pre>{
    <span class="pl-s"><span class="pl-pds">"</span>ok<span class="pl-pds">"</span></span>: <span class="pl-c1">true</span>,
    <span class="pl-s"><span class="pl-pds">"</span>data<span class="pl-pds">"</span></span>: {
        <span class="pl-s"><span class="pl-pds">"</span>is_mute<span class="pl-pds">"</span></span>: <span class="pl-c1">false</span>,
        <span class="pl-s"><span class="pl-pds">"</span>brief<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>Payment Request<span class="pl-pds">"</span></span>,
        <span class="pl-s"><span class="pl-pds">"</span>content<span class="pl-pds">"</span></span>: {
            <span class="pl-s"><span class="pl-pds">"</span>content_type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>payment_request<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>target_id<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>a573e67b760a44259dc0ee29087ade72<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>action<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>bitcoin:1248bTMWvsKyetnw9LZ9bH6XSnjCTA3YUD?amount=0.1&amp;message=hello%26msg&amp;arg1=12342342&amp;arg9=13112999<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>conv_type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>private<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>desc<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>100,000 Bits<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>comment<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>Bixin Payment Request<span class="pl-pds">"</span></span>
        },
        <span class="pl-s"><span class="pl-pds">"</span>created_at<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>2017-08-14T08:40:47.984493<span class="pl-pds">"</span></span>,
        <span class="pl-s"><span class="pl-pds">"</span>content_type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>payment_request<span class="pl-pds">"</span></span>,
        <span class="pl-s"><span class="pl-pds">"</span>request_id<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>acs32cs23casa44259dc0sas29081ccs232<span class="pl-pds">"</span></span>,
        <span class="pl-s"><span class="pl-pds">"</span>id<span class="pl-pds">"</span></span>: <span class="pl-c1">83093</span>,
        <span class="pl-s"><span class="pl-pds">"</span>sender<span class="pl-pds">"</span></span>: {
            <span class="pl-s"><span class="pl-pds">"</span>gender<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>nickname<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>bot nickname<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>desc<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>id<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>53b0e04dfaf749c3939c3c6614fa41de<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>menu<span class="pl-pds">"</span></span>: [],
            <span class="pl-s"><span class="pl-pds">"</span>conv_type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>bot<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>name<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>bot12345678<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>avatar_url<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>https://bixin.im/media/openplatform/2017/07/17/pECXyQZz7u8SuvFr.png<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>btc_address<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>1PgwDda8KuhyZJDeypm94WbDhoz4b7GJqi<span class="pl-pds">"</span></span>
        },
        <span class="pl-s"><span class="pl-pds">"</span>conv_type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>bot<span class="pl-pds">"</span></span>,
        <span class="pl-s"><span class="pl-pds">"</span>prev_id<span class="pl-pds">"</span></span>: <span class="pl-c1">83089</span>,
        <span class="pl-s"><span class="pl-pds">"</span>receiver<span class="pl-pds">"</span></span>: {
            <span class="pl-s"><span class="pl-pds">"</span>gender<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>male<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>nickname<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>heid<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>desc<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>id<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>a573e67b760a44259dc0ee29087ade72<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>menu<span class="pl-pds">"</span></span>: [],
            <span class="pl-s"><span class="pl-pds">"</span>conv_type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>private<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>name<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>echo<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>avatar_url<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>https://bixin.im/upload/2017/07/14/348c0df261ff487698f797d416b4a847.png<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>btc_address<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>1vkJV6bnJdbjocerXjLJkc3tEsjmEjh94<span class="pl-pds">"</span></span>
        }
    }
}</pre></div>
<h3><a id="user-content-form消息" class="anchor" aria-hidden="true" href="#form消息"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>form消息</h3>
<p>Content-Type: application/json</p>
<pre><code>POST https://openapi.bixin.im/api/v2/bot.postForm
</code></pre>
<p>参数：</p>
<table>
<thead>
<tr>
<th>名称(name)</th>
<th>描述(description)</th>
</tr>
</thead>
<tbody>
<tr>
<td>target_id</td>
<td>发送对象的id</td>
</tr>
<tr>
<td>request_id</td>
<td>请求消息id 用uuid生成</td>
</tr>
<tr>
<td>form</td>
<td>详见form wiki</td>
</tr>
<tr>
<td>title</td>
<td>文章Title</td>
</tr>
<tr>
<td>category</td>
<td>类型（用于显示账单, 可选)</td>
</tr></tbody></table>
<p>返回：</p>
<div class="highlight highlight-source-json"><pre>{
    <span class="pl-s"><span class="pl-pds">"</span>data<span class="pl-pds">"</span></span>: {
        <span class="pl-s"><span class="pl-pds">"</span>request_id<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>1473e3b718asaasdfa123e290872322<span class="pl-pds">"</span></span>,
        <span class="pl-s"><span class="pl-pds">"</span>id<span class="pl-pds">"</span></span>: <span class="pl-c1">83100</span>,
        <span class="pl-s"><span class="pl-pds">"</span>sender<span class="pl-pds">"</span></span>: {
            <span class="pl-s"><span class="pl-pds">"</span>id<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>f2c5609ae91c4a2ab20c4b196aac9b4a<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>avatar_url<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>https://openapi.bixin.im/res/vendor_fin_dollar2.png<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>nickname<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>Ghost bot<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>btc_address<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>1Har9AL8QyRuQ5DiLfm6kFndscbVR6ctHG<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>gender<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>desc<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>conv_type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>bot<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>name<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>bx_bot_ghost<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>menu<span class="pl-pds">"</span></span>: []
        },
        <span class="pl-s"><span class="pl-pds">"</span>created_at<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>2017-08-15T03:46:34.895666<span class="pl-pds">"</span></span>,
        <span class="pl-s"><span class="pl-pds">"</span>receiver<span class="pl-pds">"</span></span>: {
            <span class="pl-s"><span class="pl-pds">"</span>id<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>a573e67b760a44259dc0ee29087ade72<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>avatar_url<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>https://openapi.bixin.im/upload/2017/07/14/348c0df261ff487698f797d416b4a847.png<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>nickname<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>heid<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>btc_address<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>1vkJV6bnJdbjocerXjLJkc3tEsjmEjh94<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>gender<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>male<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>desc<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span><span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>conv_type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>private<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>name<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>echo<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>menu<span class="pl-pds">"</span></span>: []
        },
        <span class="pl-s"><span class="pl-pds">"</span>prev_id<span class="pl-pds">"</span></span>: <span class="pl-c1">83097</span>,
        <span class="pl-s"><span class="pl-pds">"</span>content<span class="pl-pds">"</span></span>: {
            <span class="pl-s"><span class="pl-pds">"</span>id<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>put-any-id-in-it<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>title<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>A title as you see<span class="pl-pds">"</span></span>,
            <span class="pl-s"><span class="pl-pds">"</span>form<span class="pl-pds">"</span></span>: [
                {
                    <span class="pl-s"><span class="pl-pds">"</span>placeholder<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>Im placeholder<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>num<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>name<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>field-1<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>prefix<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>desc1<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>label<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>Im Label<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>suffix<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>Bits<span class="pl-pds">"</span></span>
                },
                {
                    <span class="pl-s"><span class="pl-pds">"</span>type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>text<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>value<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>Im Default<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>name<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>field-2<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>prefix<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>desc2<span class="pl-pds">"</span></span>
                },
                {
                    <span class="pl-s"><span class="pl-pds">"</span>type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>bool<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>value<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>true<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>name<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>field-3<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>prefix<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>Im toggle<span class="pl-pds">"</span></span>
                },
                {
                    <span class="pl-s"><span class="pl-pds">"</span>type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>date<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>value<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>2011-03-98<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>name<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>field-4<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>prefix<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>Im toggle<span class="pl-pds">"</span></span>
                },
                {
                    <span class="pl-s"><span class="pl-pds">"</span>options<span class="pl-pds">"</span></span>: {
                        <span class="pl-s"><span class="pl-pds">"</span>opt2<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>Bob<span class="pl-pds">"</span></span>,
                        <span class="pl-s"><span class="pl-pds">"</span>opt1<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>Alice<span class="pl-pds">"</span></span>
                    },
                    <span class="pl-s"><span class="pl-pds">"</span>type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>select<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>required<span class="pl-pds">"</span></span>: <span class="pl-c1">true</span>,
                    <span class="pl-s"><span class="pl-pds">"</span>label<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>field3<span class="pl-pds">"</span></span>,
                    <span class="pl-s"><span class="pl-pds">"</span>name<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>field-6<span class="pl-pds">"</span></span>
                }
            ]
        },
        <span class="pl-s"><span class="pl-pds">"</span>brief<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>form<span class="pl-pds">"</span></span>,
        <span class="pl-s"><span class="pl-pds">"</span>conv_type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>bot<span class="pl-pds">"</span></span>,
        <span class="pl-s"><span class="pl-pds">"</span>is_mute<span class="pl-pds">"</span></span>: <span class="pl-c1">false</span>,
        <span class="pl-s"><span class="pl-pds">"</span>content_type<span class="pl-pds">"</span></span>: <span class="pl-s"><span class="pl-pds">"</span>form<span class="pl-pds">"</span></span>
    },
    <span class="pl-s"><span class="pl-pds">"</span>ok<span class="pl-pds">"</span></span>: <span class="pl-c1">true</span>
}</pre></div>
<h3><a id="user-content-设置menu" class="anchor" aria-hidden="true" href="#设置menu"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M4 9h1v1H4c-1.5 0-3-1.69-3-3.5S2.55 3 4 3h4c1.45 0 3 1.69 3 3.5 0 1.41-.91 2.72-2 3.25V8.59c.58-.45 1-1.27 1-2.09C10 5.22 8.98 4 8 4H4c-.98 0-2 1.22-2 2.5S3 9 4 9zm9-3h-1v1h1c1 0 2 1.22 2 2.5S13.98 12 13 12H9c-.98 0-2-1.22-2-2.5 0-.83.42-1.64 1-2.09V6.25c-1.09.53-2 1.84-2 3.25C6 11.31 7.55 13 9 13h4c1.45 0 3-1.69 3-3.5S14.5 6 13 6z"></path></svg></a>设置Menu</h3>
<p>Content-Type: application/json</p>
<pre><code>POST https://openapi.bixin.im/api/v2/bot.setMenu
</code></pre>
<p>参数：</p>
<table>
<thead>
<tr>
<th>名称(name)</th>
<th>描述(description)</th>
</tr>
</thead>
<tbody>
<tr>
<td>desc</td>
<td>描述字典（支持多语言: en_US, zh_Hans)</td>
</tr>
<tr>
<td>action</td>
<td>跳转连接或者 event 如: <a href="https://bixin.im" rel="nofollow">https://bixin.im</a></td>
</tr>
<tr>
<td>icon_url</td>
<td>图标url</td>
</tr></tbody></table>
<p>返回：</p>
<pre><code>{ 'ok': True }
</code></pre>
</article>
  </div>

  </div>

  <button type="button" data-facebox="#jump-to-line" data-facebox-class="linejump" data-hotkey="l" class="d-none">Jump to Line</button>
  <div id="jump-to-line" style="display:none">
    <!-- '"` --><!-- </textarea></xmp> --></option></form><form class="js-jump-to-line-form" action="" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" />
      <input class="form-control linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" aria-label="Jump to line" autofocus>
      <button type="submit" class="btn">Go</button>
</form>  </div>


  </div>
  <div class="modal-backdrop js-touch-events"></div>
</div>

    </div>
  </div>

  </div>

      
<div class="footer container-lg px-3" role="contentinfo">
  <div class="position-relative d-flex flex-justify-between pt-6 pb-2 mt-6 f6 text-gray border-top border-gray-light ">
    <ul class="list-style-none d-flex flex-wrap ">
      <li class="mr-3">&copy; 2018 <span title="0.30190s from unicorn-2755095919-3fxh7">GitHub</span>, Inc.</li>
        <li class="mr-3"><a data-ga-click="Footer, go to terms, text:terms" href="https://github.com/site/terms">Terms</a></li>
        <li class="mr-3"><a data-ga-click="Footer, go to privacy, text:privacy" href="https://github.com/site/privacy">Privacy</a></li>
        <li class="mr-3"><a href="https://help.github.com/articles/github-security/" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li class="mr-3"><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
        <li><a data-ga-click="Footer, go to help, text:help" href="https://help.github.com">Help</a></li>
    </ul>

    <a aria-label="Homepage" title="GitHub" class="footer-octicon" href="https://github.com">
      <svg height="24" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1" width="24" aria-hidden="true"><path fill-rule="evenodd" d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"/></svg>
</a>
   <ul class="list-style-none d-flex flex-wrap ">
        <li class="mr-3"><a data-ga-click="Footer, go to contact, text:contact" href="https://github.com/contact">Contact GitHub</a></li>
      <li class="mr-3"><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li class="mr-3"><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li class="mr-3"><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li class="mr-3"><a href="https://blog.github.com" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a data-ga-click="Footer, go to about, text:about" href="https://github.com/about">About</a></li>

    </ul>
  </div>
  <div class="d-flex flex-justify-center pb-6">
    <span class="f6 text-gray-light"></span>
  </div>
</div>



  <div id="ajax-error-message" class="ajax-error-message flash flash-error">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <button type="button" class="flash-close js-ajax-error-dismiss" aria-label="Dismiss error">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
    You can't perform that action at this time.
  </div>


    <script crossorigin="anonymous" type="application/javascript" src="https://assets-cdn.github.com/assets/compat-413dd2a0695c3dfaf7de158468a91646.js"></script>
    <script crossorigin="anonymous" type="application/javascript" src="https://assets-cdn.github.com/assets/frameworks-eca8e7e9ccc2078d10d49cad268f6a4f.js"></script>
    
    <script crossorigin="anonymous" async="async" type="application/javascript" src="https://assets-cdn.github.com/assets/github-fb4e1757f58f124affd2813ccc02f86b.js"></script>
    
    
    
    
  <div class="js-stale-session-flash stale-session-flash flash flash-warn flash-banner d-none">
    <svg class="octicon octicon-alert" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M8.865 1.52c-.18-.31-.51-.5-.87-.5s-.69.19-.87.5L.275 13.5c-.18.31-.18.69 0 1 .19.31.52.5.87.5h13.7c.36 0 .69-.19.86-.5.17-.31.18-.69.01-1L8.865 1.52zM8.995 13h-2v-2h2v2zm0-3h-2V6h2v4z"/></svg>
    <span class="signed-in-tab-flash">You signed in with another tab or window. <a href="">Reload</a> to refresh your session.</span>
    <span class="signed-out-tab-flash">You signed out in another tab or window. <a href="">Reload</a> to refresh your session.</span>
  </div>
  <div class="facebox" id="facebox" style="display:none;">
  <div class="facebox-popup">
    <div class="facebox-content" role="dialog" aria-labelledby="facebox-header" aria-describedby="facebox-description">
    </div>
    <button type="button" class="facebox-close js-facebox-close" aria-label="Close modal">
      <svg class="octicon octicon-x" viewBox="0 0 12 16" version="1.1" width="12" height="16" aria-hidden="true"><path fill-rule="evenodd" d="M7.48 8l3.75 3.75-1.48 1.48L6 9.48l-3.75 3.75-1.48-1.48L4.52 8 .77 4.25l1.48-1.48L6 6.52l3.75-3.75 1.48 1.48z"/></svg>
    </button>
  </div>
</div>

  <div class="Popover js-hovercard-content position-absolute" style="display: none; outline: none;" tabindex="0">
  <div class="Popover-message Popover-message--bottom-left Popover-message--large Box box-shadow-large" style="width:360px;">
  </div>
</div>

<div id="hovercard-aria-description" class="sr-only">
  Press h to open a hovercard with more details.
</div>


  </body>
</html>

