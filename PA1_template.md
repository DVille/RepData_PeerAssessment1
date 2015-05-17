


<!DOCTYPE html>
<html lang="en" class="">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# object: http://ogp.me/ns/object# article: http://ogp.me/ns/article# profile: http://ogp.me/ns/profile#">
    <meta charset='utf-8'>
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta http-equiv="Content-Language" content="en">
    
    
    <title>coursera-repdata/PA1_template.md at master · sefakilic/coursera-repdata · GitHub</title>
    <link rel="search" type="application/opensearchdescription+xml" href="/opensearch.xml" title="GitHub">
    <link rel="fluid-icon" href="https://github.com/fluidicon.png" title="GitHub">
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-touch-icon-114.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-touch-icon-144.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-touch-icon-144.png">
    <meta property="fb:app_id" content="1401488693436528">

      <meta content="@github" name="twitter:site" /><meta content="summary" name="twitter:card" /><meta content="sefakilic/coursera-repdata" name="twitter:title" /><meta content="coursera-repdata - Peer Assessment 1 for Reproducible Research" name="twitter:description" /><meta content="https://avatars1.githubusercontent.com/u/1227083?v=3&amp;s=400" name="twitter:image:src" />
      <meta content="GitHub" property="og:site_name" /><meta content="object" property="og:type" /><meta content="https://avatars1.githubusercontent.com/u/1227083?v=3&amp;s=400" property="og:image" /><meta content="sefakilic/coursera-repdata" property="og:title" /><meta content="https://github.com/sefakilic/coursera-repdata" property="og:url" /><meta content="coursera-repdata - Peer Assessment 1 for Reproducible Research" property="og:description" />
      <meta name="browser-stats-url" content="https://api.github.com/_private/browser/stats">
    <meta name="browser-errors-url" content="https://api.github.com/_private/browser/errors">
    <link rel="assets" href="https://assets-cdn.github.com/">
    
    <meta name="pjax-timeout" content="1000">
    

    <meta name="msapplication-TileImage" content="/windows-tile.png">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="selected-link" value="repo_source" data-pjax-transient>
      <meta name="google-analytics" content="UA-3769691-2">

    <meta content="collector.githubapp.com" name="octolytics-host" /><meta content="collector-cdn.github.com" name="octolytics-script-host" /><meta content="github" name="octolytics-app-id" /><meta content="4A652C15:07E9:890B39B:55580918" name="octolytics-dimension-request_id" />
    
    <meta content="Rails, view, blob#show" name="analytics-event" />
    <meta class="js-ga-set" name="dimension1" content="Logged Out">
    <meta class="js-ga-set" name="dimension2" content="Header v3">
    <meta name="is-dotcom" content="true">
    <meta name="hostname" content="github.com">
    <meta name="user-login" content="">

    
    <link rel="icon" type="image/x-icon" href="https://assets-cdn.github.com/favicon.ico">


    <meta content="authenticity_token" name="csrf-param" />
<meta content="+jwySP6+f5DM+fli/SKuZP8Q9Z/l9eM661pa/YrwlwMlZSx36v9N8xiGRKqNlvJuM8FqktKLq6ZSA4Hkgd+ENw==" name="csrf-token" />

    <link href="https://assets-cdn.github.com/assets/github/index-d80e093fe7c48ff920ce83dfd2ad7c02806722220d164b49101ed783098ea618.css" media="all" rel="stylesheet" />
    <link href="https://assets-cdn.github.com/assets/github2/index-99a58ea750b0547d1266460cd4ade0c2c81ed8c524cbba4ea5e3b37e18daec79.css" media="all" rel="stylesheet" />
    
    


    <meta http-equiv="x-pjax-version" content="282d80bd51fc0e03270191711c02f726">

      
  <meta name="description" content="coursera-repdata - Peer Assessment 1 for Reproducible Research">
  <meta name="go-import" content="github.com/sefakilic/coursera-repdata git https://github.com/sefakilic/coursera-repdata.git">

  <meta content="1227083" name="octolytics-dimension-user_id" /><meta content="sefakilic" name="octolytics-dimension-user_login" /><meta content="19899531" name="octolytics-dimension-repository_id" /><meta content="sefakilic/coursera-repdata" name="octolytics-dimension-repository_nwo" /><meta content="true" name="octolytics-dimension-repository_public" /><meta content="true" name="octolytics-dimension-repository_is_fork" /><meta content="16709733" name="octolytics-dimension-repository_parent_id" /><meta content="rdpeng/RepData_PeerAssessment1" name="octolytics-dimension-repository_parent_nwo" /><meta content="16709733" name="octolytics-dimension-repository_network_root_id" /><meta content="rdpeng/RepData_PeerAssessment1" name="octolytics-dimension-repository_network_root_nwo" />
  <link href="https://github.com/sefakilic/coursera-repdata/commits/master.atom" rel="alternate" title="Recent Commits to coursera-repdata:master" type="application/atom+xml">

  </head>


  <body class="logged_out  env-production windows vis-public fork page-blob">
    <a href="#start-of-content" tabindex="1" class="accessibility-aid js-skip-to-content">Skip to content</a>
    <div class="wrapper">
      
      
      


        
        <div class="header header-logged-out" role="banner">
  <div class="container clearfix">

    <a class="header-logo-wordmark" href="https://github.com/" data-ga-click="(Logged out) Header, go to homepage, icon:logo-wordmark">
      <span class="mega-octicon octicon-logo-github"></span>
    </a>

    <div class="header-actions" role="navigation">
        <a class="btn btn-primary" href="/join" data-ga-click="(Logged out) Header, clicked Sign up, text:sign-up">Sign up</a>
      <a class="btn" href="/login?return_to=%2Fsefakilic%2Fcoursera-repdata%2Fblob%2Fmaster%2Fproject1%2FPA1_template.md" data-ga-click="(Logged out) Header, clicked Sign in, text:sign-in">Sign in</a>
    </div>

    <div class="site-search repo-scope js-site-search" role="search">
      <form accept-charset="UTF-8" action="/sefakilic/coursera-repdata/search" class="js-site-search-form" data-global-search-url="/search" data-repo-search-url="/sefakilic/coursera-repdata/search" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
  <label class="js-chromeless-input-container form-control">
    <div class="scope-badge">This repository</div>
    <input type="text"
      class="js-site-search-focus js-site-search-field is-clearable chromeless-input"
      data-hotkey="s"
      name="q"
      placeholder="Search"
      data-global-scope-placeholder="Search GitHub"
      data-repo-scope-placeholder="Search"
      tabindex="1"
      autocapitalize="off">
  </label>
</form>
    </div>

      <ul class="header-nav left" role="navigation">
          <li class="header-nav-item">
            <a class="header-nav-link" href="/explore" data-ga-click="(Logged out) Header, go to explore, text:explore">Explore</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="/features" data-ga-click="(Logged out) Header, go to features, text:features">Features</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="https://enterprise.github.com/" data-ga-click="(Logged out) Header, go to enterprise, text:enterprise">Enterprise</a>
          </li>
          <li class="header-nav-item">
            <a class="header-nav-link" href="/blog" data-ga-click="(Logged out) Header, go to blog, text:blog">Blog</a>
          </li>
      </ul>

  </div>
</div>



      <div id="start-of-content" class="accessibility-aid"></div>
          <div class="site" itemscope itemtype="http://schema.org/WebPage">
    <div id="js-flash-container">
      
    </div>
    <div class="pagehead repohead instapaper_ignore readability-menu">
      <div class="container">
        
<ul class="pagehead-actions">

  <li>
      <a href="/login?return_to=%2Fsefakilic%2Fcoursera-repdata"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to watch a repository" rel="nofollow">
    <span class="octicon octicon-eye"></span>
    Watch
  </a>
  <a class="social-count" href="/sefakilic/coursera-repdata/watchers">
    3
  </a>

  </li>

  <li>
      <a href="/login?return_to=%2Fsefakilic%2Fcoursera-repdata"
    class="btn btn-sm btn-with-count tooltipped tooltipped-n"
    aria-label="You must be signed in to star a repository" rel="nofollow">
    <span class="octicon octicon-star"></span>
    Star
  </a>

    <a class="social-count js-social-count" href="/sefakilic/coursera-repdata/stargazers">
      1
    </a>

  </li>

    <li>
      <a href="/login?return_to=%2Fsefakilic%2Fcoursera-repdata"
        class="btn btn-sm btn-with-count tooltipped tooltipped-n"
        aria-label="You must be signed in to fork a repository" rel="nofollow">
        <span class="octicon octicon-repo-forked"></span>
        Fork
      </a>
      <a href="/sefakilic/coursera-repdata/network" class="social-count">
        14,172
      </a>
    </li>
</ul>

        <h1 itemscope itemtype="http://data-vocabulary.org/Breadcrumb" class="entry-title public">
          <span class="mega-octicon octicon-repo-forked"></span>
          <span class="author"><a href="/sefakilic" class="url fn" itemprop="url" rel="author"><span itemprop="title">sefakilic</span></a></span><!--
       --><span class="path-divider">/</span><!--
       --><strong><a href="/sefakilic/coursera-repdata" class="js-current-repository" data-pjax="#js-repo-pjax-container">coursera-repdata</a></strong>

          <span class="page-context-loader">
            <img alt="" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
          </span>

            <span class="fork-flag">
              <span class="text">forked from <a href="/rdpeng/RepData_PeerAssessment1">rdpeng/RepData_PeerAssessment1</a></span>
            </span>
        </h1>
      </div><!-- /.container -->
    </div><!-- /.repohead -->

    <div class="container">
      <div class="repository-with-sidebar repo-container new-discussion-timeline  ">
        <div class="repository-sidebar clearfix">
            
<nav class="sunken-menu repo-nav js-repo-nav js-sidenav-container-pjax js-octicon-loaders"
     role="navigation"
     data-pjax="#js-repo-pjax-container"
     data-issue-count-url="/sefakilic/coursera-repdata/issues/counts">
  <ul class="sunken-menu-group">
    <li class="tooltipped tooltipped-w" aria-label="Code">
      <a href="/sefakilic/coursera-repdata" aria-label="Code" class="selected js-selected-navigation-item sunken-menu-item" data-hotkey="g c" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches /sefakilic/coursera-repdata">
        <span class="octicon octicon-code"></span> <span class="full-word">Code</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>


    <li class="tooltipped tooltipped-w" aria-label="Pull requests">
      <a href="/sefakilic/coursera-repdata/pulls" aria-label="Pull requests" class="js-selected-navigation-item sunken-menu-item" data-hotkey="g p" data-selected-links="repo_pulls /sefakilic/coursera-repdata/pulls">
          <span class="octicon octicon-git-pull-request"></span> <span class="full-word">Pull requests</span>
          <span class="js-pull-replace-counter"></span>
          <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

  </ul>
  <div class="sunken-menu-separator"></div>
  <ul class="sunken-menu-group">

    <li class="tooltipped tooltipped-w" aria-label="Pulse">
      <a href="/sefakilic/coursera-repdata/pulse" aria-label="Pulse" class="js-selected-navigation-item sunken-menu-item" data-selected-links="pulse /sefakilic/coursera-repdata/pulse">
        <span class="octicon octicon-pulse"></span> <span class="full-word">Pulse</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>

    <li class="tooltipped tooltipped-w" aria-label="Graphs">
      <a href="/sefakilic/coursera-repdata/graphs" aria-label="Graphs" class="js-selected-navigation-item sunken-menu-item" data-selected-links="repo_graphs repo_contributors /sefakilic/coursera-repdata/graphs">
        <span class="octicon octicon-graph"></span> <span class="full-word">Graphs</span>
        <img alt="" class="mini-loader" height="16" src="https://assets-cdn.github.com/assets/spinners/octocat-spinner-32-e513294efa576953719e4e2de888dd9cf929b7d62ed8d05f25e731d02452ab6c.gif" width="16" />
</a>    </li>
  </ul>


</nav>

              <div class="only-with-full-nav">
                  
<div class="clone-url open"
  data-protocol-type="http"
  data-url="/users/set_protocol?protocol_selector=http&amp;protocol_type=clone">
  <h3><span class="text-emphasized">HTTPS</span> clone URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/sefakilic/coursera-repdata.git" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>

  
<div class="clone-url "
  data-protocol-type="subversion"
  data-url="/users/set_protocol?protocol_selector=subversion&amp;protocol_type=clone">
  <h3><span class="text-emphasized">Subversion</span> checkout URL</h3>
  <div class="input-group js-zeroclipboard-container">
    <input type="text" class="input-mini input-monospace js-url-field js-zeroclipboard-target"
           value="https://github.com/sefakilic/coursera-repdata" readonly="readonly">
    <span class="input-group-button">
      <button aria-label="Copy to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
    </span>
  </div>
</div>



<p class="clone-options">You can clone with
  <a href="#" class="js-clone-selector" data-protocol="http">HTTPS</a> or <a href="#" class="js-clone-selector" data-protocol="subversion">Subversion</a>.
  <a href="https://help.github.com/articles/which-remote-url-should-i-use" class="help tooltipped tooltipped-n" aria-label="Get help on which URL is right for you.">
    <span class="octicon octicon-question"></span>
  </a>
</p>


  <a href="https://windows.github.com" class="btn btn-sm sidebar-button" title="Save sefakilic/coursera-repdata to your computer and use it in GitHub Desktop." aria-label="Save sefakilic/coursera-repdata to your computer and use it in GitHub Desktop.">
    <span class="octicon octicon-device-desktop"></span>
    Clone in Desktop
  </a>


                <a href="/sefakilic/coursera-repdata/archive/master.zip"
                   class="btn btn-sm sidebar-button"
                   aria-label="Download the contents of sefakilic/coursera-repdata as a zip file"
                   title="Download the contents of sefakilic/coursera-repdata as a zip file"
                   rel="nofollow">
                  <span class="octicon octicon-cloud-download"></span>
                  Download ZIP
                </a>
              </div>
        </div><!-- /.repository-sidebar -->

        <div id="js-repo-pjax-container" class="repository-content context-loader-container" data-pjax-container>

          

<a href="/sefakilic/coursera-repdata/blob/887120ed7a37211dd2d2bdc05dbe0e81e0e1ae7d/project1/PA1_template.md" class="hidden js-permalink-shortcut" data-hotkey="y">Permalink</a>

<!-- blob contrib key: blob_contributors:v21:8ebe111b683764384a2ebb13df2206cf -->

<div class="file-navigation js-zeroclipboard-container">
  
<div class="select-menu js-menu-container js-select-menu left">
  <span class="btn btn-sm select-menu-button js-menu-target css-truncate" data-hotkey="w"
    data-master-branch="master"
    data-ref="master"
    title="master"
    role="button" aria-label="Switch branches or tags" tabindex="0" aria-haspopup="true">
    <span class="octicon octicon-git-branch"></span>
    <i>branch:</i>
    <span class="js-select-button css-truncate-target">master</span>
  </span>

  <div class="select-menu-modal-holder js-menu-content js-navigation-container" data-pjax aria-hidden="true">

    <div class="select-menu-modal">
      <div class="select-menu-header">
        <span class="select-menu-title">Switch branches/tags</span>
        <span class="octicon octicon-x js-menu-close" role="button" aria-label="Close"></span>
      </div>

      <div class="select-menu-filters">
        <div class="select-menu-text-filter">
          <input type="text" aria-label="Filter branches/tags" id="context-commitish-filter-field" class="js-filterable-field js-navigation-enable" placeholder="Filter branches/tags">
        </div>
        <div class="select-menu-tabs">
          <ul>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="branches" data-filter-placeholder="Filter branches/tags" class="js-select-menu-tab">Branches</a>
            </li>
            <li class="select-menu-tab">
              <a href="#" data-tab-filter="tags" data-filter-placeholder="Find a tag…" class="js-select-menu-tab">Tags</a>
            </li>
          </ul>
        </div>
      </div>

      <div class="select-menu-list select-menu-tab-bucket js-select-menu-tab-bucket" data-tab-filter="branches">

        <div data-filterable-for="context-commitish-filter-field" data-filterable-type="substring">


            <a class="select-menu-item js-navigation-item js-navigation-open selected"
               href="/sefakilic/coursera-repdata/blob/master/project1/PA1_template.md"
               data-name="master"
               data-skip-pjax="true"
               rel="nofollow">
              <span class="select-menu-item-icon octicon octicon-check"></span>
              <span class="select-menu-item-text css-truncate-target" title="master">
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

  <div class="btn-group right">
    <a href="/sefakilic/coursera-repdata/find/master"
          class="js-show-file-finder btn btn-sm empty-icon tooltipped tooltipped-s"
          data-pjax
          data-hotkey="t"
          aria-label="Quickly jump between files">
      <span class="octicon octicon-list-unordered"></span>
    </a>
    <button aria-label="Copy file path to clipboard" class="js-zeroclipboard btn btn-sm zeroclipboard-button tooltipped tooltipped-s" data-copied-hint="Copied!" type="button"><span class="octicon octicon-clippy"></span></button>
  </div>

  <div class="breadcrumb js-zeroclipboard-target">
    <span class='repo-root js-repo-root'><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/sefakilic/coursera-repdata" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">coursera-repdata</span></a></span></span><span class="separator">/</span><span itemscope="" itemtype="http://data-vocabulary.org/Breadcrumb"><a href="/sefakilic/coursera-repdata/tree/master/project1" class="" data-branch="master" data-direction="back" data-pjax="true" itemscope="url"><span itemprop="title">project1</span></a></span><span class="separator">/</span><strong class="final-path">PA1_template.md</strong>
  </div>
</div>


  <div class="commit file-history-tease">
    <div class="file-history-tease-header">
        <img alt="@sefakilic" class="avatar" data-user="1227083" height="24" src="https://avatars2.githubusercontent.com/u/1227083?v=3&amp;s=48" width="24" />
        <span class="author"><a href="/sefakilic" rel="author">sefakilic</a></span>
        <time datetime="2014-05-18T15:05:57Z" is="relative-time">May 18, 2014</time>
        <div class="commit-title">
            <a href="/sefakilic/coursera-repdata/commit/a294c1c2856357eb6f345902dd359b0814b386b0" class="message" data-pjax="true" title="peer assessment 1">peer assessment 1</a>
        </div>
    </div>

    <div class="participation">
      <p class="quickstat">
        <a href="#blob_contributors_box" rel="facebox">
          <strong>1</strong>
           contributor
        </a>
      </p>
      
    </div>
    <div id="blob_contributors_box" style="display:none">
      <h2 class="facebox-header">Users who have contributed to this file</h2>
      <ul class="facebox-user-list">
          <li class="facebox-user-list-item">
            <img alt="@sefakilic" data-user="1227083" height="24" src="https://avatars2.githubusercontent.com/u/1227083?v=3&amp;s=48" width="24" />
            <a href="/sefakilic">sefakilic</a>
          </li>
      </ul>
    </div>
  </div>

<div class="file">
  <div class="file-header">
    <div class="file-actions">

      <div class="btn-group">
        <a href="/sefakilic/coursera-repdata/raw/master/project1/PA1_template.md" class="btn btn-sm " id="raw-url">Raw</a>
          <a href="/sefakilic/coursera-repdata/blame/master/project1/PA1_template.md" class="btn btn-sm js-update-url-with-hash">Blame</a>
        <a href="/sefakilic/coursera-repdata/commits/master/project1/PA1_template.md" class="btn btn-sm " rel="nofollow">History</a>
      </div>

        <a class="octicon-btn tooltipped tooltipped-nw"
           href="https://windows.github.com"
           aria-label="Open this file in GitHub for Windows"
           data-ga-click="Repository, open with desktop, type:windows">
            <span class="octicon octicon-device-desktop"></span>
        </a>

          <button type="button" class="octicon-btn disabled tooltipped tooltipped-n" aria-label="You must be signed in to make or propose changes">
            <span class="octicon octicon-pencil"></span>
          </button>

        <button type="button" class="octicon-btn octicon-btn-danger disabled tooltipped tooltipped-n" aria-label="You must be signed in to make or propose changes">
          <span class="octicon octicon-trashcan"></span>
        </button>
    </div>

    <div class="file-info">
        160 lines (113 sloc)
        <span class="file-info-divider"></span>
      3.904 kb
    </div>
  </div>
    <div id="readme" class="blob instapaper_body">
    <article class="markdown-body entry-content" itemprop="mainContentOfPage"><h1>
<a id="user-content-reproducible-research-peer-assessment-1" class="anchor" href="#reproducible-research-peer-assessment-1" aria-hidden="true"><span class="octicon octicon-link"></span></a>Reproducible Research: Peer Assessment 1</h1>

<h2>
<a id="user-content-loading-and-preprocessing-the-data" class="anchor" href="#loading-and-preprocessing-the-data" aria-hidden="true"><span class="octicon octicon-link"></span></a>Loading and preprocessing the data</h2>

<div class="highlight highlight-r"><pre>unzip(<span class="pl-v">zipfile</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>activity.zip<span class="pl-pds">"</span></span>)
<span class="pl-smi">data</span> <span class="pl-k">&lt;-</span> read.csv(<span class="pl-s"><span class="pl-pds">"</span>activity.csv<span class="pl-pds">"</span></span>)</pre></div>

<h2>
<a id="user-content-what-is-mean-total-number-of-steps-taken-per-day" class="anchor" href="#what-is-mean-total-number-of-steps-taken-per-day" aria-hidden="true"><span class="octicon octicon-link"></span></a>What is mean total number of steps taken per day?</h2>

<div class="highlight highlight-r"><pre>library(<span class="pl-smi">ggplot2</span>)
<span class="pl-smi">total.steps</span> <span class="pl-k">&lt;-</span> tapply(<span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">date</span>, <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-smi">sum</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)
qplot(<span class="pl-smi">total.steps</span>, <span class="pl-v">binwidth</span> <span class="pl-k">=</span> <span class="pl-c1">1000</span>, <span class="pl-v">xlab</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>total number of steps taken each day<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/sefakilic/coursera-repdata/blob/master/project1/figure/unnamed-chunk-1.png" target="_blank"><img src="/sefakilic/coursera-repdata/raw/master/project1/figure/unnamed-chunk-1.png" alt="plot of chunk unnamed-chunk-1" style="max-width:100%;"></a> </p>

<div class="highlight highlight-r"><pre>mean(<span class="pl-smi">total.steps</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)</pre></div>

<pre><code>## [1] 9354
</code></pre>

<div class="highlight highlight-r"><pre>median(<span class="pl-smi">total.steps</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)</pre></div>

<pre><code>## [1] 10395
</code></pre>

<h2>
<a id="user-content-what-is-the-average-daily-activity-pattern" class="anchor" href="#what-is-the-average-daily-activity-pattern" aria-hidden="true"><span class="octicon octicon-link"></span></a>What is the average daily activity pattern?</h2>

<div class="highlight highlight-r"><pre>library(<span class="pl-smi">ggplot2</span>)
<span class="pl-smi">averages</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-v">x</span> <span class="pl-k">=</span> <span class="pl-k">list</span>(<span class="pl-v">steps</span> <span class="pl-k">=</span> <span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">steps</span>), <span class="pl-v">by</span> <span class="pl-k">=</span> <span class="pl-k">list</span>(<span class="pl-v">interval</span> <span class="pl-k">=</span> <span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">interval</span>), 
    <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-smi">mean</span>, <span class="pl-v">na.rm</span> <span class="pl-k">=</span> <span class="pl-c1">TRUE</span>)
ggplot(<span class="pl-v">data</span> <span class="pl-k">=</span> <span class="pl-smi">averages</span>, aes(<span class="pl-v">x</span> <span class="pl-k">=</span> <span class="pl-smi">interval</span>, <span class="pl-v">y</span> <span class="pl-k">=</span> <span class="pl-smi">steps</span>)) <span class="pl-k">+</span> geom_line() <span class="pl-k">+</span> xlab(<span class="pl-s"><span class="pl-pds">"</span>5-minute interval<span class="pl-pds">"</span></span>) <span class="pl-k">+</span> 
    ylab(<span class="pl-s"><span class="pl-pds">"</span>average number of steps taken<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/sefakilic/coursera-repdata/blob/master/project1/figure/unnamed-chunk-2.png" target="_blank"><img src="/sefakilic/coursera-repdata/raw/master/project1/figure/unnamed-chunk-2.png" alt="plot of chunk unnamed-chunk-2" style="max-width:100%;"></a> </p>

<p>On average across all the days in the dataset, the 5-minute interval contains
the maximum number of steps?</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">averages</span>[which.max(<span class="pl-smi">averages</span><span class="pl-k">$</span><span class="pl-smi">steps</span>), ]</pre></div>

<pre><code>##     interval steps
## 104      835 206.2
</code></pre>

<h2>
<a id="user-content-imputing-missing-values" class="anchor" href="#imputing-missing-values" aria-hidden="true"><span class="octicon octicon-link"></span></a>Imputing missing values</h2>

<p>There are many days/intervals where there are missing values (coded as <code>NA</code>). The presence of missing days may introduce bias into some calculations or summaries of the data.</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">missing</span> <span class="pl-k">&lt;-</span> is.na(<span class="pl-smi">data</span><span class="pl-k">$</span><span class="pl-smi">steps</span>)
<span class="pl-c"># How many missing</span>
table(<span class="pl-smi">missing</span>)</pre></div>

<pre><code>## missing
## FALSE  TRUE 
## 15264  2304
</code></pre>

<p>All of the missing values are filled in with mean value for that 5-minute
interval.</p>

<div class="highlight highlight-r"><pre><span class="pl-c"># Replace each missing value with the mean value of its 5-minute interval</span>
<span class="pl-en">fill.value</span> <span class="pl-k">&lt;-</span> <span class="pl-k">function</span>(<span class="pl-smi">steps</span>, <span class="pl-smi">interval</span>) {
    <span class="pl-smi">filled</span> <span class="pl-k">&lt;-</span> <span class="pl-c1">NA</span>
    <span class="pl-k">if</span> (<span class="pl-k">!</span>is.na(<span class="pl-smi">steps</span>)) 
        <span class="pl-smi">filled</span> <span class="pl-k">&lt;-</span> c(<span class="pl-smi">steps</span>) <span class="pl-k">else</span> <span class="pl-smi">filled</span> <span class="pl-k">&lt;-</span> (<span class="pl-smi">averages</span>[<span class="pl-smi">averages</span><span class="pl-k">$</span><span class="pl-smi">interval</span> <span class="pl-k">==</span> <span class="pl-smi">interval</span>, <span class="pl-s"><span class="pl-pds">"</span>steps<span class="pl-pds">"</span></span>])
    <span class="pl-k">return</span>(<span class="pl-smi">filled</span>)
}
<span class="pl-smi">filled.data</span> <span class="pl-k">&lt;-</span> <span class="pl-smi">data</span>
<span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">steps</span> <span class="pl-k">&lt;-</span> mapply(<span class="pl-smi">fill.value</span>, <span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">interval</span>)</pre></div>

<p>Now, using the filled data set, let's make a histogram of the total number of steps taken each day and calculate the mean and median total number of steps.</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">total.steps</span> <span class="pl-k">&lt;-</span> tapply(<span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">steps</span>, <span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">date</span>, <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-smi">sum</span>)
qplot(<span class="pl-smi">total.steps</span>, <span class="pl-v">binwidth</span> <span class="pl-k">=</span> <span class="pl-c1">1000</span>, <span class="pl-v">xlab</span> <span class="pl-k">=</span> <span class="pl-s"><span class="pl-pds">"</span>total number of steps taken each day<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/sefakilic/coursera-repdata/blob/master/project1/figure/unnamed-chunk-5.png" target="_blank"><img src="/sefakilic/coursera-repdata/raw/master/project1/figure/unnamed-chunk-5.png" alt="plot of chunk unnamed-chunk-5" style="max-width:100%;"></a> </p>

<div class="highlight highlight-r"><pre>mean(<span class="pl-smi">total.steps</span>)</pre></div>

<pre><code>## [1] 10766
</code></pre>

<div class="highlight highlight-r"><pre>median(<span class="pl-smi">total.steps</span>)</pre></div>

<pre><code>## [1] 10766
</code></pre>

<p>Mean and median values are higher after imputing missing data. The reason is
that in the original data, there are some days with <code>steps</code> values <code>NA</code> for 
any <code>interval</code>. The total number of steps taken in such days are set to 0s by
default. However, after replacing missing <code>steps</code> values with the mean <code>steps</code>
of associated <code>interval</code> value, these 0 values are removed from the histogram
of total number of steps taken each day.</p>

<h2>
<a id="user-content-are-there-differences-in-activity-patterns-between-weekdays-and-weekends" class="anchor" href="#are-there-differences-in-activity-patterns-between-weekdays-and-weekends" aria-hidden="true"><span class="octicon octicon-link"></span></a>Are there differences in activity patterns between weekdays and weekends?</h2>

<p>First, let's find the day of the week for each measurement in the dataset. In
this part, we use the dataset with the filled-in values.</p>

<div class="highlight highlight-r"><pre><span class="pl-en">weekday.or.weekend</span> <span class="pl-k">&lt;-</span> <span class="pl-k">function</span>(<span class="pl-smi">date</span>) {
    <span class="pl-smi">day</span> <span class="pl-k">&lt;-</span> weekdays(<span class="pl-smi">date</span>)
    <span class="pl-k">if</span> (<span class="pl-smi">day</span> <span class="pl-k">%in%</span> c(<span class="pl-s"><span class="pl-pds">"</span>Monday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Tuesday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Wednesday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Thursday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Friday<span class="pl-pds">"</span></span>)) 
        <span class="pl-k">return</span>(<span class="pl-s"><span class="pl-pds">"</span>weekday<span class="pl-pds">"</span></span>) <span class="pl-k">else</span> <span class="pl-k">if</span> (<span class="pl-smi">day</span> <span class="pl-k">%in%</span> c(<span class="pl-s"><span class="pl-pds">"</span>Saturday<span class="pl-pds">"</span></span>, <span class="pl-s"><span class="pl-pds">"</span>Sunday<span class="pl-pds">"</span></span>)) 
        <span class="pl-k">return</span>(<span class="pl-s"><span class="pl-pds">"</span>weekend<span class="pl-pds">"</span></span>) <span class="pl-k">else</span> stop(<span class="pl-s"><span class="pl-pds">"</span>invalid date<span class="pl-pds">"</span></span>)
}
<span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">date</span> <span class="pl-k">&lt;-</span> as.Date(<span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">date</span>)
<span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">day</span> <span class="pl-k">&lt;-</span> sapply(<span class="pl-smi">filled.data</span><span class="pl-k">$</span><span class="pl-smi">date</span>, <span class="pl-v">FUN</span> <span class="pl-k">=</span> <span class="pl-smi">weekday.or.weekend</span>)</pre></div>

<p>Now, let's make a panel plot containing plots of average number of steps taken
on weekdays and weekends.</p>

<div class="highlight highlight-r"><pre><span class="pl-smi">averages</span> <span class="pl-k">&lt;-</span> aggregate(<span class="pl-smi">steps</span> <span class="pl-k">~</span> <span class="pl-smi">interval</span> <span class="pl-k">+</span> <span class="pl-smi">day</span>, <span class="pl-v">data</span> <span class="pl-k">=</span> <span class="pl-smi">filled.data</span>, <span class="pl-smi">mean</span>)
ggplot(<span class="pl-smi">averages</span>, aes(<span class="pl-smi">interval</span>, <span class="pl-smi">steps</span>)) <span class="pl-k">+</span> geom_line() <span class="pl-k">+</span> facet_grid(<span class="pl-smi">day</span> <span class="pl-k">~</span> .) <span class="pl-k">+</span> 
    xlab(<span class="pl-s"><span class="pl-pds">"</span>5-minute interval<span class="pl-pds">"</span></span>) <span class="pl-k">+</span> ylab(<span class="pl-s"><span class="pl-pds">"</span>Number of steps<span class="pl-pds">"</span></span>)</pre></div>

<p><a href="/sefakilic/coursera-repdata/blob/master/project1/figure/unnamed-chunk-7.png" target="_blank"><img src="/sefakilic/coursera-repdata/raw/master/project1/figure/unnamed-chunk-7.png" alt="plot of chunk unnamed-chunk-7" style="max-width:100%;"></a> </p>
</article>
  </div>

</div>

<a href="#jump-to-line" rel="facebox[.linejump]" data-hotkey="l" style="display:none">Jump to Line</a>
<div id="jump-to-line" style="display:none">
  <form accept-charset="UTF-8" action="" class="js-jump-to-line-form" method="get"><div style="margin:0;padding:0;display:inline"><input name="utf8" type="hidden" value="&#x2713;" /></div>
    <input class="linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line&hellip;" autofocus>
    <button type="submit" class="btn">Go</button>
</form></div>

        </div>

      </div><!-- /.repo-container -->
      <div class="modal-backdrop"></div>
    </div><!-- /.container -->
  </div><!-- /.site -->


    </div><!-- /.wrapper -->

      <div class="container">
  <div class="site-footer" role="contentinfo">
    <ul class="site-footer-links right">
        <li><a href="https://status.github.com/" data-ga-click="Footer, go to status, text:status">Status</a></li>
      <li><a href="https://developer.github.com" data-ga-click="Footer, go to api, text:api">API</a></li>
      <li><a href="https://training.github.com" data-ga-click="Footer, go to training, text:training">Training</a></li>
      <li><a href="https://shop.github.com" data-ga-click="Footer, go to shop, text:shop">Shop</a></li>
        <li><a href="https://github.com/blog" data-ga-click="Footer, go to blog, text:blog">Blog</a></li>
        <li><a href="https://github.com/about" data-ga-click="Footer, go to about, text:about">About</a></li>

    </ul>

    <a href="https://github.com" aria-label="Homepage">
      <span class="mega-octicon octicon-mark-github" title="GitHub"></span>
</a>
    <ul class="site-footer-links">
      <li>&copy; 2015 <span title="0.03675s from github-fe122-cp1-prd.iad.github.net">GitHub</span>, Inc.</li>
        <li><a href="https://github.com/site/terms" data-ga-click="Footer, go to terms, text:terms">Terms</a></li>
        <li><a href="https://github.com/site/privacy" data-ga-click="Footer, go to privacy, text:privacy">Privacy</a></li>
        <li><a href="https://github.com/security" data-ga-click="Footer, go to security, text:security">Security</a></li>
        <li><a href="https://github.com/contact" data-ga-click="Footer, go to contact, text:contact">Contact</a></li>
    </ul>
  </div>
</div>


    <div class="fullscreen-overlay js-fullscreen-overlay" id="fullscreen_overlay">
  <div class="fullscreen-container js-suggester-container">
    <div class="textarea-wrap">
      <textarea name="fullscreen-contents" id="fullscreen-contents" class="fullscreen-contents js-fullscreen-contents" placeholder=""></textarea>
      <div class="suggester-container">
        <div class="suggester fullscreen-suggester js-suggester js-navigation-container"></div>
      </div>
    </div>
  </div>
  <div class="fullscreen-sidebar">
    <a href="#" class="exit-fullscreen js-exit-fullscreen tooltipped tooltipped-w" aria-label="Exit Zen Mode">
      <span class="mega-octicon octicon-screen-normal"></span>
    </a>
    <a href="#" class="theme-switcher js-theme-switcher tooltipped tooltipped-w"
      aria-label="Switch themes">
      <span class="octicon octicon-color-mode"></span>
    </a>
  </div>
</div>



    

    <div id="ajax-error-message" class="flash flash-error">
      <span class="octicon octicon-alert"></span>
      <a href="#" class="octicon octicon-x flash-close js-ajax-error-dismiss" aria-label="Dismiss error"></a>
      Something went wrong with that request. Please try again.
    </div>


      <script crossorigin="anonymous" src="https://assets-cdn.github.com/assets/frameworks-5c08de317e4054ec200d36d3b1361ddd3cb30c05c9070a9d72862ee28ab1d7f9.js"></script>
      <script async="async" crossorigin="anonymous" src="https://assets-cdn.github.com/assets/github/index-b79817a43c4618022b9ecd18dadd96010ccecbb12b56fcc232664db1f897e3a8.js"></script>
      
      

  </body>
</html>

