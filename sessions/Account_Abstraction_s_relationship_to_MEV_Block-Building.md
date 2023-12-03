<!DOCTYPE html>
<html lang="dev">

<head>
    <meta charset="utf-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black">
<meta name="mobile-web-app-capable" content="yes">
<meta property="og:image" content="https://hackmd.io/images/media/HackMD-og.jpg">

    <meta property="fb:app_id" content="1436904003272070">


<meta name="realtime-register-serverurl" content="https://hackmd.io/realtime-reg">

<meta name="csrf-token" content="W85hNrzr-xhBU3hdocWqeAjcJ17Jn-1rB250">
<title>D1 - HackMD</title>
<link rel="icon" type="image/png" href="https://hackmd.io/favicon.png">
<link rel="apple-touch-icon" href="https://hackmd.io/apple-touch-icon.png">

<script nonce="7e4e2a18-0f6b-48a9-9017-39e491ea067a">
  window.domain = 'hackmd.io'
  window.urlpath = ''
  window.debug = false
  window.version = '1.3.0'
  window.brand = 'HackMD'

  

  window.GOOGLE_API_KEY = 'AIzaSyCjSrqWHhmWJnoI7JlD88XDSaBgiKbaenA'
  window.GOOGLE_CLIENT_ID = '911617723593-drikdibvvn63slfd6kbqigo8ql1no55s.apps.googleusercontent.com'
  window.DROPBOX_APP_KEY = 'rdoizrlnkuha23r'
  
  window.PLANTUML_SERVER = 'https://ptuml.hackmd.io'

  window.ASSET_URL = 'https://assets.hackmd.io'

  window.USER_CAN_CREATE_TEAM = true
  window.USER_CAN_DELETE_ACCOUNT = true
  window.USER_DELETE_ACCOUNT_VIA_EMAIL = true
  window.PAYMENT_ENABLED = true
  window.PAYMENT_PROMOTION_BANNER_ENABLED = false
  window.GITHUB_SYNC_ENABLED = true
  window.GITLAB_SYNC_ENABLED = false
  window.GITLAB_SYNC_BASE_URL = ''
  window.VCS_SYNC_MODE = 'github'
  window.VCS_PROVIDER_NAME = 'GitHub'
  window.FREE_TEAM_NUM = 20
  window.FREE_TEAM_MEMBER_NUM = 3
  window.FREE_PUBLIC_TEAM_NUM = 10
  
  window.EE_SITE_ENABLE = false
  window.EE_SITE_NAME = 'false'
  window.EE_SITE_LINK = 'false'
  window.EESITE_INFO = false
  window.ENTERPRISE_DISCOVERY_ENABLE = false
  window.ENTERPRISE_DISCOVERY_TEAM = true
  window.ENTERPRISE_DISCOVERY_NOTE = true
  window.ENTERPRISE_DISCOVERY_VIEW_PERMISSION = 'guest'
  
  window.ALLOW_ANONYMOUS = true
  window.ALLOW_ANONYMOUS_EDIT = false
  window.PUBLIC_OVERVIEW = false
  window.INTERNAL_PUBLIC_OVERVIEW = false
  window.FULL_TEXT_SEARCH_ENABLE = false
  window.ALGOLIA_SEARCH_ENABLE = true
  window.MARKETING_EMAIL_ENABLE = true
  
  window.ARWEAVE_ENABLE = false
  
  
  window.RECAPTCHA_SCORE_KEY = '6LdtkK4ZAAAAAG1B4iENhmQTce1xNTyHu0GjgnXi'
  
  
  window.API_MANAGEMENT_UI_ENABLE = true
  window.FEEDBACK_UI_ENABLE = true
  window.PUBLISH_ENABLE = true

  

  

  

  
  window.SHOW_OVERVIEW = false
  

  

  

  

  

  

  

  

  

  
  window.canEdit = false
  

  

  window.TRASH_NOTE_DELETE_AFTER_FREE = 3
  window.TRASH_NOTE_DELETE_AFTER_PAID = 30

  

  
    window.IS_OWNER_UPGRADED = false
  

  
    window.IMGUR_FALLBACK_CDN = 'https://imgur-backup.hackmd.io'
  

  
    window.CLOUD_META_UI = true
  
  
    window.CLOUD_META_API = true
  
  
    window.CLOUD_META_MIGRATION = false
  
  
    window.YAML_METADATA_ENABLED = false
  

  
    window.NOTE_CAPACITY_LIMIT = 50
  

  
    window.DOCUMENT_MAX_LENGTH = 100000
  

  
    window.SOCIAL_NETWORK_FEATURES_ENABLED = true
  
</script>



<!-- Google Tag Manager -->
<script nonce="7e4e2a18-0f6b-48a9-9017-39e491ea067a">(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-KLW9Z3');</script>
<!-- End Google Tag Manager -->


 <link href="https://assets.hackmd.io/build/font-vendor.85aea95458609ff85035.css" rel="stylesheet"><link href="https://assets.hackmd.io/build/common-vendor.8badda337754ab1de336.css" rel="stylesheet"><link href="https://assets.hackmd.io/build/index-vendor.3773b3818032440d1806.css" rel="stylesheet"><link href="https://assets.hackmd.io/build/index.8db9e6caa080d2f3f544.css" rel="stylesheet">
<!-- style-loader will insert style before this div in development -->
<!-- This prevents overwriting reveal.js theme css -->
<meta id="style-tag-insertion">
<!-- HTML5 shim and Respond.js for IE8 support of HTML5 elements and media queries -->
<!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
<!--[if lt IE 9]>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/html5shiv/3.7.3/html5shiv.min.js" integrity="sha256-3Jy/GbSLrg0o9y5Z5n1uw0qxZECH7C6OQpVBgNFYa0g=" crossorigin="anonymous"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/respond.js/1.4.2/respond.min.js" integrity="sha256-g6iAfvZp+nDQ2TdTR/VVKJf3bGro4ub5fvWSWVRi2NE=" crossorigin="anonymous"></script>
	<script src="https://cdnjs.cloudflare.com/ajax/libs/es5-shim/4.5.9/es5-shim.min.js" integrity="sha256-8E4Is26QH0bD52WoQpcB+R/tcWQtpzlCojrybUd7Mxo=" crossorigin="anonymous"></script>
<![endif]-->


<style>
  .grecaptcha-badge {
      visibility: hidden;
  }
</style>
<script nonce="7e4e2a18-0f6b-48a9-9017-39e491ea067a" src="https://www.google.com/recaptcha/enterprise.js?render=6LdtkK4ZAAAAAG1B4iENhmQTce1xNTyHu0GjgnXi&hl=dev"></script>



    <script src="https://tally.so/widgets/embed.js"></script>
</head>

<body>
    


<nav class="navbar navbar-default navbar-fixed-top unselectable hidden-print">
    <!-- Brand and toggle get grouped for better mobile display -->
    <div class="navbar-header hmd-navbar-header">
        
        <a class="navbar-brand pull-left" style="float: left;" href="https://hackmd.io/"><i
                class="fa fa-file-text"></i><span class="hidden-xs"> HackMD</span></a>
        

        <div id="nav-mobile-note-title" class="nav-mobile"></div>

        
        

        <ul class="nav-mobile pull-right mobile-extra-menu" style="margin: 0 8px 0 0;">
            <li>
                
                    <a class="rounded btn-link side-menu-button ui-guest-signin-tooltip"
                    data-toggle="tooltip"
                    title="Sign in to create, share, and comment on a note"
                    data-placement="bottom"
                    data-container=".navbar-default"
                    data-offset="0,5">
                
                    <i class="fa fa-bars"></i>
                </a>
            </li>
        </ul>
        <ul class="nav-mobile pull-right mobile-user-profile">
            <li id="short-online-user-list" class="ui-host-list">
                <button class="ui-short-status btn bg-transparent text-red-light hover:text-red-light focus:text-red-light ml-1.5" data-toggle="dropdown"><i class="fa fa-plug"></i></button>
                <ul class="dropdown-menu list" role="menu" aria-labelledby="menu">
                </ul>
            </li>
            <li>
                <a class="ui-mode btn text-blue-default border-blue-default ml-1.5">
                    <i class="mt-1 fa fa-pencil"></i>
                </a>
            </li>
            <li>
                <a class="ui-share btn ml-1.5 " sidenav-target="sidenav-permission" tabindex="-1" href="#">
                    <i class="mt-1 fa fa-share-alt fa-fw"></i>
                </a>
            </li>
        </ul>
    </div>
    <div class="hmd-navbar navbar-collapse">
        <nav class="nav mode-switch navbar-nav navbar-form navbar-left">
            <div class="btn-group" data-toggle="buttons">
                <label class="btn btn-default ui-edit" style="padding: 6px 9px;" title="Edit (Ctrl+Alt+E)" aria-label="Edit">
                    <input type="radio" name="mode" autocomplete="off"><i class="fa fa-pencil fa-fw"></i>
                </label>
                <label class="btn btn-default ui-both" style="padding: 6px 9px;" title="Both (Ctrl+Alt+B)" aria-label="Both">
                    <input type="radio" name="mode" autocomplete="off"><i class="fa fa-columns fa-fw"></i>
                </label>
                <label class="btn btn-default ui-view" style="padding: 6px 9px;" title="View (Ctrl+Alt+V)" aria-label="View">
                    <input type="radio" name="mode" autocomplete="off"><i class="fa fa-eye fa-fw"></i>
                </label>
            </div>
        </nav>
        <ul class="nav action-group navbar-nav navbar-left">
            
            
                
            
            
            <li title="Help" data-toggle="tooltip" data-placement="bottom" data-container=".navbar-default" data-offset="0,5" class="mr-3.5">
                <a class="rounded ui-help navbar-button-icon" href="#" data-toggle="modal" data-target=".help-modal" aria-label="Help">
                    <i class="fa fa-question fa-20"></i>
                </a>
            </li>

            
        </ul>

        
        

        
            
            <div id="nav-note-setting"
                class="nav navbar-nav h-full w-full selectable pointer-events-none flex justify-around items-center"
                data-workspace="WalletUncon2023"></div>
        

        <ul class="nav extra-menu navbar-nav navbar-right">
            <li class="ui-share-button mr-1.5" data-toggle="tooltip" data-placement="bottom" data-container=".navbar-default" data-offset="0,5">
                <button class="ui-sharing btn " data-toggle="dropdown" tabindex="0">
                    <i class="fa fa-share-alt fa-18"></i>
                    Share
                </button>
                <ul class="dropdown-menu list ui-share-menu permission-dropdown" role="menu" aria-labelledby="menu" style="width: 308px; padding: 15px 0px;">
                    
                    <li class="dropdown-header" style="margin-bottom: 4px;">
                        Sharing
                        <i class="fa fa-question-circle fa-12 tooltip-align-left ui-first-menu-tooltip" style="color: #CDCDCD"
                        title="Share this note with below URL. Make sure your audience has the permission to access this note."
                            data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i>
                        <span class="ui-share-msg" style="display: none;">
                            Link copied
                        </span>
                    </li>
                    <li class="dropdown-header ui-share-domain" style="margin-bottom: 2px; word-break: break-all; overflow: hidden; text-overflow: ellipsis;">
                    </li>
                    <li class="input-group" style="padding: 0px 20px;">
                        <input type="text" class="form-control ui-share-field" maxlength="200" placeholder="https://hackmd.io" style="height: 28px; font-size: 13px;">
                        <div class="ui-share-edit-mode" style="color:#888; position: absolute; z-index: 10; font-size: 13px; top: 5px; right: 100px; display: none;">/edit</div>
                        <span class="input-group-btn">
                            <button class="btn ui-share-copy" type="button">Copy</button>
                        </span>
                        <span class="input-group-btn" style="display: none">
                            <button class="btn ui-share-save" type="button">Save</button>
                        </span>
                    </li>

                    <li class="hmd-flex hmd-justify-end hmd-items-center" style="padding: 0 20px; margin-top: 10px;">
                        <div class="hmd-flex hmd-flex-one hmd-items-center ui-publish-type">
                            <div class="hmd-flex-one">
                                <div class="dropdown menuitem-dropdown">
                                    <div class="menuitem-dropdown-trigger" data-toggle="dropdown" tabindex="0">
                                        <span class="ui-publish-type-label">
                                            <i class="fa fa-eye fa-fw" aria-hidden="true"></i> View mode
                                        </span>
                                        <i class="fa fa-angle-down menuitem-angle" aria-hidden="true" style="margin-left: 10px;"></i>
                                    </div>

                                    <ul class="dropdown-menu" role="menu">
                                        <li role="presentation"><a role="menuitem" class="menuitem-item ui-mode-edit" href="#" tabindex="-1"><i class="fa fa-pencil-square-o fa-fw" aria-hidden="true"></i> Edit mode</a></li>
                                        <li role="presentation"><a role="menuitem" class="menuitem-item ui-mode-view" href="#" tabindex="-1"><i class="fa fa-eye fa-fw" aria-hidden="true"></i> View mode</a></li>
                                        <li role="presentation"><a role="menuitem" class="menuitem-item ui-mode-book" href="#" tabindex="-1"><i class="fa fa-book fa-fw" aria-hidden="true"></i> Book mode</a></li>
                                        <li role="presentation"><a role="menuitem" class="menuitem-item ui-mode-slide" href="#" tabindex="-1"><i class="fa fa-television fa-fw" aria-hidden="true"></i> Slide mode</a></li>
                                    </ul>
                                </div>
                            </div>
                            <i class="fa fa-question-circle fa-12 tooltip-align-left ui-first-menu-tooltip"  style="color: #CDCDCD; margin-left: 5px; margin-right: 15px; font-size: 12px;"
                            title="Note owner decides who can read or write this note." data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i>
                        </div>

                        <div class="permission-item-badge permission-item-readonly ui-publish-type-badge" style="display: none;">
                            <span name="edit"><i class="fa fa-pencil-square-o fa-fw" aria-hidden="true"></i> Edit mode</span>
                            <span name="view"><i class="fa fa-eye fa-fw" aria-hidden="true"></i> View mode</span>
                            <span name="book"><i class="fa fa-book fa-fw" aria-hidden="true"></i> Book mode</span>
                            <span name="slide"><i class="fa fa-television fa-fw" aria-hidden="true"></i> Slide mode</span>
                        </div>
                        <div>
                            <button class="btn btn-default ui-share-preview" type="button">Preview</button>
                        </div>
                    </li>

                    
                    <li role="presentation">
                        <div class="ui-publish-slide-options" style="display: none;">
                            <span>Customize slides</span>
                            <i class="fa fa-angle-right fa-fw"></i>
                        </div>
                        <style>
                            .ui-publish-slide-options {
                                margin: 9px 20px 11px 20px;
                                width: calc(100% - 40px) !important;
                                cursor: pointer;
                        }
                        </style>
                    </li>
                    

                    <li role="presentation" aria-hidden="true" class="divider"></li>
                    <li class="dropdown-header" style="margin-bottom: 7px;">
                        Note Permission
                        <i class="fa fa-question-circle fa-12 tooltip-align-left ui-first-menu-tooltip" style="color: #CDCDCD"
                        title="Note owner decides who can read or write this note."
                            data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i>
                    </li>
                    <li role="presentation" style="margin-bottom: 10px;">
                        <div class="hmd-flex" style="padding: 0 20px; height: 26px;">
                            <span class="hmd-flex-one">
                                <div style="display: table; width: 100%; height: 100%;">
                                    <div style="display: table-cell; vertical-align: middle;">
                                        Read
                                    </div>
                                </div>
                            </span>
                            <div class="hmd-flex-two ui-note-read">
                                <div>
                                    <div class="dropdown menuitem-dropdown">
                                        <button class="menuitem-dropdown-trigger" data-toggle="dropdown" tabindex="0">
                                            <span class="ui-note-read-label">
                                                Owners
                                            </span>
                                            <i class="fa fa-angle-down menuitem-angle" aria-hidden="true" style="margin-left: 10px;"></i>
                                        </button>

                                        <ul class="dropdown-menu" role="menu">
                                            <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-read-owners" href="#" tabindex="-1">Owners</a></li>
                                            <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-read-signed_in_users" href="#" tabindex="-1">Signed-in users</a></li>
                                            <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-read-everyone" href="#" tabindex="-1">Everyone</a></li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                            <div class="permission-item-badge permission-item-readonly" style="display: none;" name="read">
                                <span name="owners">Owners</span>
                                <span name="signed_in_users">Signed-in users</span>
                                <span name="everyone">Everyone</span>
                            </div>
                        </div>
                    </li>
                    <li role="presentation" style="margin-bottom: 10px;">
                        <div style="display: flex; padding: 0 20px; height: 26px;">
                            <span style="flex: 1;">
                                <div style="display: table; width: 100%; height: 100%;">
                                    <div style="display: table-cell; vertical-align: middle;">
                                        Write
                                    </div>
                                </div>
                            </span>
                            <div style="flex: 2" class="ui-note-write">
                                <div>
                                    <div class="dropdown menuitem-dropdown">
                                        <button class="menuitem-dropdown-trigger" data-toggle="dropdown" tabindex="0"
                                        >
                                            <span class="ui-note-write-label">
                                                Owners
                                            </span>
                                            <i class="fa fa-angle-down menuitem-angle" aria-hidden="true" style="margin-left: 10px;"></i>
                                        </button>
                                        <ul class="dropdown-menu" role="menu">
                                            <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-write-owners" href="#" tabindex="-1">Owners</a></li>
                                            <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-write-signed_in_users" href="#" tabindex="-1">Signed-in users</a></li>
                                            <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-write-everyone" href="#" tabindex="-1">Everyone</a></li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                            <div class="permission-item-badge permission-item-readonly" style="display: none;" name="write">
                                <span name="owners">Owners</span>
                                <span name="signed_in_users">Signed-in users</span>
                                <span name="everyone">Everyone</span>
                            </div>
                        </div>
                    </li>

                    <div class="px-5 my-2 font-semibold permission-notice">
                        <small class="text-gray-600"></small>
                    </div>

                    
                        
                        
                        <li role="presentation">
                            <a href="#" class="ui-more-settings overwrite">
                                <div class="note-permission-button" style="margin: 0 20px 11px 20px; width: calc(100% - 40px);">
                                    <span>
                                        
                                        
                                        
                                            Commenting &amp; Invitee
                                        
                                    </span>
                                    <i class="fa fa-angle-right fa-fw"></i>
                                </div>
                            </a>
                            <style>
                                a.ui-more-settings.overwrite {
                                    margin: 0;
                                    padding: 0;
                                }
                                a.ui-more-settings.overwrite:hover {
                                    background-color: transparent;
                                }
                            </style>
                        </li>
                        
                    

                    <div class="public-publish-container" style="display: none;">
                        <li role="presentation" aria-hidden="true" class="divider"></li>

                        <div class="dropdown-header">
    Publishing
</div>

<div class="hmd-flex hmd-justify-center public-published-toggle" data-published="true">
    <button type="button" class="btn btn-default publish hmd-flex-auto">
        <i class="fa fa-globe" aria-hidden="true"></i>
        Published
    </button>

    <button type="button" class="btn btn-default unpublish-action hmd-flex-auto">
        Unpublish
    </button>

    <button type="button" class="btn btn-primary unpublish hmd-flex-auto">
        Publish
    </button>
</div>
<div class="mb-[10px] px-5 community-guideline-container leading-[14px]">
    <label class="font-normal text-3 text-gray-600 mb-[3px] flex">
        <input type="checkbox" style="margin-top: 0; margin-right: 6px;">
        <span>I agree to HackMD’s <a href="https://hackmd.io/@hackmd/community-guidelines" target="_blank">Community Guideline</a>.</span>
    </label>
    <span class="error-message text-red-light text-3 hidden">Please check the box to agree to the Community Guidelines.</span>
</div>
<div style="margin-bottom: 10px;">
    <div class="publish-note-description-for-public-team" style="display: none; color: #888888; padding: 0 20px; white-space: initial; font-size: 13px;">Everyone on the web can find and read all notes of this public team.</div>
    <div class="publish-note-description" style="color: #888888; padding: 0 20px; white-space: initial; font-size: 13px;">After the note is published, everyone on the web can find and read this note.</div>
    <div class="how-to-publish-note-description" style="color: #888888; padding: 0 20px; white-space: initial; font-size: 13px;">See all published notes on <a target="_blank" href="">profile page</a>.</div>
</div>

                    </div>
                </ul>
                <ul class="dropdown-menu list ui-more-settings-menu permission-dropdown" role="menu" aria-labelledby="menu" style="width: 308px; padding-top: 0px; padding-bottom: 0px; display: none">
                    <li role="presentation">
                        <button class="ui-more-settings-menu-back hmd-text-left" style="width: 100%; padding: 15px 20px 15px 20px; font-size: 15px; background-color: white; cursor: pointer; border: none; border-bottom: #888888 1px solid;">
                            <i class="fa fa-angle-left fa-fw" style="width:auto; margin-right: 15px;"></i>
                            <span><span>More (Comment, </span><span class="ui-more-invitee">Invitee</span>)</span>
                        </button>
                    </li>
                    
                    <li class="dropdown-header" style="margin-bottom: 7px; margin-top: 15px;">
                        Commenting
                        <i class="fa fa-question-circle fa-12 tooltip-align-left ui-second-menu-tooltip" style="color: #CDCDCD"
                        title="Note owner decides who can give comments."
                        data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i>
                        <span class="ui-comment-permission-toggle pull-right">
                            <span style="margin-right: 3px;">
                                Enable
                            </span>
                            <span>
                                <label class="switch" style="vertical-align: middle;" aria-label="Enable">
                                    <input type="checkbox">
                                    <span class="slider round"></span>
                                </label>
                            </span>
                        </span>
                        <div class="permission-item-badge permission-item-readonly pull-right" style="display: none;" name="comment">
                            <span name="disabled">Disabled</span>
                            <span name="forbidden">Forbidden</span>
                            <span name="owners">Owners</span>
                            <span name="signed_in_users">Signed-in users</span>
                            <span name="everyone">Everyone</span>
                        </div>
                    </li>
                    <li class="ui-comment-permission-comment" role="presentation" style="margin-bottom: 20px;">
                        <div style="display: flex; padding: 0 20px; height: 26px;">
                            <span style="flex: 1;">
                                <div style="display: table; width: 100%; height: 100%;">
                                    <div style="display: table-cell; vertical-align: middle;">
                                        Permission
                                    </div>
                                </div>
                            </span>
                            <div style="flex: 2">
                                <div>
                                    <div class="dropdown menuitem-dropdown">
                                        <button class="menuitem-dropdown-trigger" data-toggle="dropdown" tabindex="0">
                                            <span class="ui-comment-write-label">Owners</span><i class="fa fa-angle-down menuitem-angle" aria-hidden="true" style="margin-left: 10px;"></i>
                                        </button>
                                        <ul class="dropdown-menu" role="menu">
                                            <li role="presentation"><a role="menuitem" class="menuitem-item ui-comment-write-forbidden" href="#" tabindex="-1">Forbidden</a></li>
                                            <li role="presentation"><a role="menuitem" class="menuitem-item ui-comment-write-owners" href="#" tabindex="-1">Owners</a></li>
                                            <li role="presentation"><a role="menuitem" class="menuitem-item ui-comment-write-signed_in_users" href="#" tabindex="-1">Signed-in users</a></li>
                                            <li role="presentation"><a role="menuitem" class="menuitem-item ui-comment-write-everyone" href="#" tabindex="-1">Everyone</a></li>
                                        </ul>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </li>
                    <li role="presentation" aria-hidden="true" class="divider ui-invitee-divider"></li>
                    
                    
                    <li class="dropdown-header ui-invitee-label" style="padding-bottom: 9px; margin-top: 15px;">
                        Invitee
                        <i class="fa fa-question-circle fa-12 tooltip-align-left ui-second-menu-tooltip" style="color: #CDCDCD"
                        title="Admin can invite users and change note permissions."
                        data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i>
                    </li>
                    <li class="ui-invitee-form" role="presentation" style="padding: 0px 20px 15px 20px;">
                        <div class="input-group" style="display: flex;">
                            <input type="text" class="form-control search-user search-user-large ui-invitee-input" placeholder="Search user by email...">
                            <div class="input-group-append">
                                <button class="btn btn-default ui-invitee-invite" invite-target=".search-user-large">Invite</button>
                            </div>
                        </div>
                    </li>
                    <li role="presentation" class="ui-no-invitee-label" style="padding: 0px 20px 10px 20px; font-size: 12px; color: #888888; display: none">
                        No invitee
                    </li>
                    <li role="presentation" style="padding: 0 20px 15px 20px;" class="ui-invitee ui-invitee-list" data-email-invitation="true">
                        <div style="padding-bottom: 10px; font-size: 12px; color: #888888; display: none" class="ui-invitee-limit-label"></div>
                    </li>
                    
                </ul>

                <ul class="dropdown-menu list ui-customize-slide-menu permission-dropdown" role="menu" aria-labelledby="menu" style="width: 308px; padding-top: 0px; padding-bottom: 0px; display: none">
                    <li role="presentation">
                        <button
                            class="ui-customize-slide-menu-back hmd-text-left"
                            style="width: 100%; padding: 15px 20px 15px 20px; font-size: 15px; background-color: white; cursor: pointer; border: none; border-bottom: #888888 1px solid;">
                            <i class="fa fa-angle-left fa-fw" style="width:auto; margin-right: 15px;"></i>
                            Customize slides options
                        </button>
                    </li>
                    <li role="presentation" class="ui-customize-slide-menu-options"></li>
                </ul>
            </li>

            <!-- Extra Menu -->
            <li title="Menu" data-toggle="tooltip" data-placement="bottom" data-container=".navbar-default" data-offset="0,5" aria-label="Menu" class="mr-3.75">
                <a class="rounded ui-menu navbar-button-icon" data-toggle="dropdown" tabindex="0">
                    <i class="fa fa-ellipsis-h fa-18"></i>
                </a>
                <span class="ui-menu-popover-target" style="left: 50%; position: absolute;"></span>
                <ul class="dropdown-menu list" role="menu" aria-label="Menu">
                    <li class="dropdown-header">
                        Options
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-extra-revision" data-toggle="modal" data-target="#namedRevisionModal" href="#" tabindex="-1">
                            <i class="fa fa-history fa-fw"></i>
                            Versions and GitHub Sync
                        </a>
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-transfer-note" href="#" tabindex="-1">
                            <i class="fa fa-exchange fa-fw"></i>
                            Transfer ownership
                        </a>
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-delete-note" href="#" tabindex="-1">
                            <i class="fa fa-trash fa-fw"></i>
                            Delete this note
                        </a>
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-note-settings" href="#" tabindex="-1">
                            <i class="fa fa-fw fa-info-circle"></i>
                            Note settings
                        </a>
                    </li>
                    
                    <li role="presentation" aria-hidden="true" class="divider"></li>
                    <li class="dropdown-header ui-menu-template-header">
                        Template
                    </li>
                    
                    <li role="presentation">
                        <a role="menuitem" class="ui-template-insert" data-toggle="modal" data-target="#templateModal" href="#" tabindex="-1">
                            <i class="fa fa-plus fa-fw"></i>
                            Insert from template
                        </a>
                    </li>
                    
                    <li role="presentation" aria-hidden="true" class="divider"></li>
                    <li class="dropdown-header">
                        Export
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-save-dropbox" href="#" target="_self" tabindex="-1">
                            <i class="fa fa-dropbox fa-fw"></i>
                            Dropbox
                        </a>
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-save-google-drive" href="#" target="_self" tabindex="-1">
                            <img src="https://hackmd.io/images/logo_google_drive.png" alt="Google Drive" class="fa fa-fw" />
                            Export to Google Drive
                        </a>
                    </li>
                    
                    <li role="presentation">
                        <a role="menuitem" class="ui-save-gist" href="#" target="_blank" tabindex="-1">
                            <i class="fa fa-github fa-fw"></i>
                            Gist</a>
                        </li>
                    </li>
                    
                    
                    
                    <li role="presentation" aria-hidden="true" class="divider"></li>
                    <li class="dropdown-header">
                        Import
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-import-dropbox" target="_self" href="#" tabindex="-1">
                            <i class="fa fa-dropbox fa-fw"></i>
                            Dropbox
                        </a>
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-import-google-drive" target="_self" href="#" tabindex="-1">
                            <img src="https://hackmd.io/images/logo_google_drive.png" alt="Google Drive" class="fa fa-fw" />
                            Import from Google Drive
                        </a>
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-import-gist" data-toggle="modal" data-target="#gistImportModal" href="#" tabindex="-1">
                            <i class="fa fa-github fa-fw"></i>
                            Gist
                        </a>
                    </li>
                    
                    <li role="presentation">
                        <a role="menuitem" class="ui-import-clipboard" data-toggle="modal" data-target="#clipboardModal" href="#" tabindex="-1">
                            <i class="fa fa-clipboard fa-fw"></i>
                            Clipboard
                        </a>
                    </li>
                    
                    <li role="presentation" aria-hidden="true" class="divider"></li>
                    <li class="dropdown-header">
                        Download
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-download-markdown" href="#" target="_blank" tabindex="-1">
                            <i class="fa fa-file-text fa-fw"></i>
                            Markdown
                        </a>
                    </li>
                    <li role="presentation">
                        <a role="menuitem" class="ui-download-html" href="#" target="_blank" tabindex="-1">
                            <i class="fa fa-file-code-o fa-fw"></i>
                            HTML
                        </a>
                    </li>
                    <li role="presentation"><a role="menuitem" class="ui-download-raw-html" href="#" target="_blank" tabindex="-1">
                            <i class="fa fa-file-code-o fa-fw"></i>
                            Raw HTML
                        </a>
                    </li>
                    
                </ul>
            </li>
            <!-- End Extra Menu -->
        </ul>
        <ul class="nav user-profile navbar-nav navbar-right">
            <li id="online-user-list" class="ui-host-list mr-1.5" data-toggle="tooltip" data-placement="bottom" data-container=".navbar-default" data-offset="0,5">
                <button class="bg-transparent ui-status btn text-red-light" data-toggle="dropdown">
                    <i class="fa fa-plug"></i> OFFLINE
                </button>
                <ul class="dropdown-menu list" role="menu" aria-labelledby="menu" style="width: 250px;">
                </ul>
            </li>
            
                <li>
                    <button
                        class="btn btn-success ui-signin ui-signin-note ui-signin-action ui-guest-signin-tooltip"
                        data-toggle="tooltip"
                        title="Sign in to create, share, and comment on a note"
                        data-placement="bottom"
                        data-container=".navbar-default"
                        data-offset="0,14"
                    >Sign in</button>
                </li>
            
        </ul>
    </div>

    <div class="sidenav main-sidenav" style="display: none;">
        
        <button class="sidenav-item ui-signin ui-signin-note" data-toggle="modal" data-target=".signin-modal" style="border-bottom: none; background-color: #5CB85C; color: white;">Sign in</button>
        
        <a class="sidenav-item sidenav-trigger ui-menu" sidenav-target="sidenav-menu" tabindex="-1" href="#"><i class="fa fa-ellipsis-h fa-fw"></i>
            <span>
                Menu
            </span>
            <i class="fa fa-angle-right fa-fw"></i>
        </a>

        
            <a class="sidenav-item sidenav-trigger ui-note-settings-mobile" sidenav-target="sidenav-note-setting" tabindex="-1" href="#">
                <i class="fa fa-info-circle fa-fw"></i>
                <span>
                    Note settings
                </span>
                <i class="fa fa-angle-right fa-fw"></i>
            </a>
        

        <a class="sidenav-item sidenav-trigger ui-share" sidenav-target="sidenav-permission" tabindex="-1" href="#"><i class="fa fa-share-alt fa-fw"></i>
            <span>
                Sharing
            </span>
            <i class="fa fa-angle-right fa-fw"></i>
        </a>
        
            
                
            
        


        

        <a class="sidenav-item ui-help dark-border" href="#" data-toggle="modal" data-target=".help-modal"><i class="fa fa-question fa-fw"></i>
            <span>
                    Help
            </span>
        </a>
    </div>


    
    
        
    
    
    <div class="sidenav sidenav-menu" style="display: none;">
        <a class="sidenav-item sidenav-back ui-menu-back" tabindex="-1" href="#">
            <i class="fa fa-angle-left fa-fw" style="width:auto"></i>
            <i class="fa fa-ellipsis-h fa-fw" style="margin: 2px 6px 0px 15px;"></i>
            Menu
        </a>
        <div class="divider-header">Options</div>
        <a class="sidenav-item ui-extra-revision" tabindex="-1" data-toggle="modal" data-target="#namedRevisionModal"><i class="fa fa-history fa-fw"></i>
            <span>
                Versions and GitHub Sync
            </span>
        </a>
        <a class="sidenav-item ui-transfer-note"><i class="fa fa-exchange fa-fw"></i>
            <span>Transfer ownership</span></a>
        <a class="sidenav-item ui-delete-note"><i class="fa fa-trash fa-fw"></i>
            <span>Delete this note</span></a>
        <div class="divider-header">Export</div>
        <a class="sidenav-item ui-save-dropbox" tabindex="-1" href="#" target="_self"><i class="fa fa-dropbox fa-fw"></i><span>Dropbox</span></a>
        <a class="sidenav-item ui-save-google-drive" tabindex="-1" href="#" target="_self">
            <img src="https://hackmd.io/images/logo_google_drive.png" alt="Google Drive" class="fa fa-fw" />
            <span>Export to Google Drive</span>
        </a>
        
            <a class="sidenav-item ui-save-gist" tabindex="-1" href="#" target="_blank"><i class="fa fa-github fa-fw"></i><span>Gist</span></a>
        
        
        
        <div class="divider-header">Import</div>
        <a class="sidenav-item ui-import-dropbox" tabindex="-1" href="#" target="_self"><i class="fa fa-dropbox fa-fw"></i><span>Dropbox</span></a>
        <a class="sidenav-item ui-import-google-drive" tabindex="-1" href="#" target="_self">
            <img src="https://hackmd.io/images/logo_google_drive.png" alt="Google Drive" class="fa fa-fw" />
            <span>Import from Google Drive</span>
        </a>
        <a class="sidenav-item ui-import-gist" href="#" data-toggle="modal" data-target="#gistImportModal"><i class="fa fa-github fa-fw"></i><span>Gist</span></a>
        
        <a class="sidenav-item ui-import-clipboard" href="#" data-toggle="modal" data-target="#clipboardModal"><i class="fa fa-clipboard fa-fw"></i><span> Clipboard</span></a>
        
        <div class="divider-header">Download</div>
        <a class="sidenav-item ui-download-markdown" tabindex="-1" href="#" target="_blank"><i class="fa fa-file-text fa-fw"></i><span>Markdown</span></a>
        <a class="sidenav-item ui-download-html" tabindex="-1" href="#" target="_blank"><i class="fa fa-file-code-o fa-fw"></i><span>HTML</span></a>
        <a class="sidenav-item ui-download-raw-html" tabindex="-1" href="#" target="_blank"><i class="fa fa-file-code-o fa-fw"></i><span> Raw HTML</span></a>
        
    </div>
    <div class="sidenav sidenav-profile" style="display: none;">
        
            <a class="sidenav-item sidenav-back ui-profile-menu-back">
                <i class="fa fa-angle-left fa-fw" style="width: auto;"></i>
                Back</a>
            </a>
        
    </div>
    <div class="sidenav full sidenav-permission permission-dropdown" style="display: none;">
        <a class="sidenav-item sidenav-back ui-share-back" tabindex="-1" href="#">
            <i class="fa fa-angle-left fa-fw" style="width: auto;"></i>
            <i class="fa fa-share-alt fa-fw" style="margin: 2px 6px 0px 15px;"></i>
            Sharing
        </a>
        
        <div class="dropdown-header">
            Sharing
            <i class="fa fa-question-circle fa-12 tooltip-align-left" style="color: #CDCDCD"
            title="Share this note with below URL. Make sure your audience has the permission to access this note."
                data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i>
            <span class="ui-share-msg" style="display: none;">
                Link copied
            </span>
        </div>
        <div class="ui-share-domain" style="margin-bottom: 5px; padding: 0 15px; font-size: 12px; color: #888888; word-break: break-all; overflow: hidden; text-overflow: ellipsis;">
        </div>
        <div class="input-group" style="padding: 0px 15px;">
            <input type="text" class="form-control ui-share-field" maxlength="200" placeholder="https://hackmd.io" style="height: 28px; font-size: 13px;">
            <div class="ui-share-edit-mode" style="color:#888; position: absolute; z-index: 10; font-size: 13px; top: 5px; right: 100px; display: none;">/edit</div>
            <span class="input-group-btn">
                <button class="btn ui-share-copy" type="button">Copy</button>
            </span>
            <span class="input-group-btn" style="display: none">
                <button class="btn ui-share-save" type="button">Save</button>
            </span>
        </div>
        <div style="display: flex; padding: 0px 15px; margin-top: 10px; align-items: center; justify-content: flex-end;">
            <div class="ui-publish-type" style="flex: 1; display: flex; align-items: center;">
                <div style="flex: 1">
                    <div>
                        <div class="dropdown menuitem-dropdown">
                            <div class="menuitem-dropdown-trigger"><span class="ui-publish-type-label"><i class="fa fa-eye fa-fw" aria-hidden="true"></i> View mode</span><i class="fa fa-angle-down menuitem-angle" aria-hidden="true" style="margin-left: 10px;"></i></div>
                            <ul class="dropdown-menu" role="menu">
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-mode-edit"><i class="fa fa-pencil-square-o fa-fw" aria-hidden="true"></i> Edit mode</a></li>
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-mode-view"><i class="fa fa-eye fa-fw" aria-hidden="true"></i> View mode</a></li>
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-mode-book"><i class="fa fa-book fa-fw" aria-hidden="true"></i> Book mode</a></li>
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-mode-slide"><i class="fa fa-television fa-fw" aria-hidden="true"></i> Slide mode</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
                <i class="fa fa-question-circle fa-12 tooltip-align-left" style="color: #CDCDCD; margin-left: 5px; margin-right: 15px; font-size: 12px;"
                title="Note owner decides who can read or write this note."
                    data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i>
            </div>
            <div class="permission-item-badge permission-item-readonly ui-publish-type-badge" style="display: none;">
                <span name="edit"><i class="fa fa-pencil-square-o" aria-hidden="true"></i> Edit mode</span>
                <span name="view"><i class="fa fa-eye" aria-hidden="true"></i> View mode</span>
                <span name="book"><i class="fa fa-book" aria-hidden="true"></i> Book mode</span>
                <span name="slide"><i class="fa fa-television" aria-hidden="true"></i> Slide mode</span>
            </div>
            <div>
                <button class="btn btn-default ui-share-preview" type="button">Preview</button>
            </div>
        </div>

        
        <div class="ui-publish-slide-options mobile" style="display: none;">
            <span>Customize slides</span>
            <i class="fa fa-angle-right fa-fw"></i>
        </div>
        <style>
            .ui-publish-slide-options.mobile {
                margin: 9px 15px 5px 15px;
                width: calc(100% - 30px) !important;
                cursor: pointer;
            }
        </style>
        

        <div style="border-bottom: #e5e5e5 1px solid; margin-top: 15px;"></div>
        <div class="dropdown-header">
            Note Permission
            <i class="fa fa-question-circle fa-12 tooltip-align-left" style="color: #CDCDCD" title="Note owner decides who can read or write this note." data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i>
        </div>
        <div class="note-permission-item">
            <div style="display: flex; height: 26px;">
                <span style="flex: 1;">
                    <div style="display: table; width: 100%; height: 100%;">
                        <div style="display: table-cell; vertical-align: middle;">
                            Read
                        </div>
                    </div>
                </span>
                <div style="flex: 2" class="ui-note-read">
                    <div>
                        <div class="dropdown menuitem-dropdown">
                            <div class="menuitem-dropdown-trigger"><span class="ui-note-read-label">Owners</span><i class="fa fa-angle-down menuitem-angle" aria-hidden="true" style="margin-left: 10px;"></i></div>
                            <ul class="dropdown-menu" role="menu">
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-read-owners">Owners</a></li>
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-read-signed_in_users">Signed-in users</a></li>
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-read-everyone">Everyone</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="permission-item-badge permission-item-readonly" style="display: none;" name="read">
                    <span name="owners">Owners</span>
                    <span name="signed_in_users">Signed-in users</span>
                    <span name="everyone">Everyone</span>
                </div>
            </div>
        </div>
        <div class="note-permission-item">
            <div style="display: flex; height: 26px;">
                <span style="flex: 1;">
                    <div style="display: table; width: 100%; height: 100%;">
                        <div style="display: table-cell; vertical-align: middle;">
                            Write
                        </div>
                    </div>
                </span>
                <div style="flex: 2" class="ui-note-write">
                    <div>
                        <div class="dropdown menuitem-dropdown">
                            <div class="menuitem-dropdown-trigger"><span class="ui-note-write-label">Owners</span><i class="fa fa-angle-down menuitem-angle" aria-hidden="true" style="margin-left: 10px;"></i></div>
                            <ul class="dropdown-menu" role="menu">
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-write-owners">Owners</a></li>
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-write-signed_in_users">Signed-in users</a></li>
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-note-write-everyone">Everyone</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="permission-item-badge permission-item-readonly" style="display: none;" name="write">
                    <span name="owners">Owners</span>
                    <span name="signed_in_users">Signed-in users</span>
                    <span name="everyone">Everyone</span>
                </div>
            </div>
        </div>

        <div class="my-2 font-semibold hmd-ph-3/2 permission-notice">
            <small class="text-gray-600"></small>
        </div>

        
        <div class="note-permission-item" style="text-align: right;">
            <span class="sidenav-trigger" sidenav-target="sidenav-note-more">
                
                
                <div class="note-permission-button">
                    <span>
                        Comment
                         &amp; 
                        Invitee
                    </span>
                    <i class="fa fa-angle-right fa-fw"></i>
                </div>
                <style>
                    div.note-permission-button,
                    div.ui-publish-slide-options {
                        display: inline-flex;
                        width: 100%;
                        justify-content: space-between;
                        padding: 8px 10px;
                        color: #337AB7;
                        background-color: #E7E7E7;
                        border-radius: 4px;
                        font-size: 14px;
                        line-height: 16px;
                    }
                    div.note-permission-button:hover,
                    div.ui-publish-slide-options:hover {
                        filter: brightness(95%);
                    }
                    div.note-permission-button > span {
                        text-align: left;
                    }
                </style>
                
            </span>
        </div>
        

        <div class="public-publish-container" style="display: none;">
            <div style="border-bottom: #e5e5e5 1px solid; margin-top: 16.5px;"></div>

            <div class="dropdown-header">
    Publishing
</div>

<div class="hmd-flex hmd-justify-center public-published-toggle" data-published="true">
    <button type="button" class="btn btn-default publish hmd-flex-auto">
        <i class="fa fa-globe" aria-hidden="true"></i>
        Published
    </button>

    <button type="button" class="btn btn-default unpublish-action hmd-flex-auto">
        Unpublish
    </button>

    <button type="button" class="btn btn-primary unpublish hmd-flex-auto">
        Publish
    </button>
</div>
<div class="mb-[10px] px-5 community-guideline-container leading-[14px]">
    <label class="font-normal text-3 text-gray-600 mb-[3px] flex">
        <input type="checkbox" style="margin-top: 0; margin-right: 6px;">
        <span>I agree to HackMD’s <a href="https://hackmd.io/@hackmd/community-guidelines" target="_blank">Community Guideline</a>.</span>
    </label>
    <span class="error-message text-red-light text-3 hidden">Please check the box to agree to the Community Guidelines.</span>
</div>
<div style="margin-bottom: 10px;">
    <div class="publish-note-description-for-public-team" style="display: none; color: #888888; padding: 0 20px; white-space: initial; font-size: 13px;">Everyone on the web can find and read all notes of this public team.</div>
    <div class="publish-note-description" style="color: #888888; padding: 0 20px; white-space: initial; font-size: 13px;">After the note is published, everyone on the web can find and read this note.</div>
    <div class="how-to-publish-note-description" style="color: #888888; padding: 0 20px; white-space: initial; font-size: 13px;">See all published notes on <a target="_blank" href="">profile page</a>.</div>
</div>

        </div>
    </div>
    <div class="sidenav full sidenav-note-more permission-dropdown" style="display: none;">
        <a class="sidenav-item sidenav-back ui-note-more-back" tabindex="-1" href="#">
            <i class="fa fa-angle-left fa-fw" style="width: auto; margin-right: 15px;"></i>
            <span><span>More (Comment, </span><span class="ui-more-invitee">Invitee</span>)</span>
        </a>
        
        <div class="dropdown-header">
            Commenting
            <i class="fa fa-question-circle fa-12 tooltip-align-left" style="color: #CDCDCD" title="Note owner decides who can give comments." data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i>
            <span class="ui-comment-permission-toggle pull-right">
                <span style="margin-left: 0; margin-right: 3px;">
                    Enable
                </span>
                <span style="margin-left: 0;">
                    <label class="switch" style="vertical-align: middle; margin-bottom: 1px;">
                        <input type="checkbox">
                        <span class="slider round" style="margin-left: 0;"></span>
                    </label>
                </span>
            </span>
            <div class="permission-item-badge permission-item-readonly pull-right" style="display: none;" name="comment">
                <span name="disabled">Disabled</span>
                <span name="forbidden">Forbidden</span>
                <span name="owners">Owners</span>
                <span name="signed_in_users">Signed-in users</span>
                <span name="everyone">Everyone</span>
            </div>
        </div>
        <div class="comment-permission-item ui-comment-permission-comment-mobile">
            <div style="display: flex; height: 26px;">
                <span style="flex: 1;">
                    <div style="display: table; width: 100%; height: 100%;">
                        <div style="display: table-cell; vertical-align: middle;">
                            Permission
                        </div>
                    </div>
                </span>
                <div style="flex: 2">
                    <div>
                        <div class="dropdown menuitem-dropdown">
                            <div class="menuitem-dropdown-trigger"><span class="ui-comment-write-label">Owners</span><i class="fa fa-angle-down menuitem-angle" aria-hidden="true" style="margin-left: 10px;"></i></div>
                            <ul class="dropdown-menu" role="menu">
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-comment-write-forbidden">Forbidden</a></li>
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-comment-write-owners">Owners</a></li>
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-comment-write-signed_in_users">Signed-in users</a></li>
                                <li role="presentation"><a role="menuitem" class="menuitem-item ui-comment-write-everyone">Everyone</a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="ui-invitee-divider" style="border-bottom: #e5e5e5 1px solid; margin-top: 15px;"></div>
        
        
        <div class="ui-invitee-label dropdown-header">
            Invitee
            <i class="fa fa-question-circle fa-12 tooltip-align-left" style="color: #CDCDCD" title="Admin can invite users and change note permissions." data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i>
        </div>
        <div class="ui-invitee-form" style="padding-bottom: 10px;">
            <div class="input-group" style="display: flex; padding: 0 15px;">
                <input type="text" class="form-control search-user search-user-small ui-invitee-input" placeholder="Search user by email...">
                <div class="input-group-append">
                    <button class="btn btn-default ui-invitee-invite" invite-target=".search-user-small">Invite</button>
                </div>
            </div>
        </div>
        <div style="padding: 0 15px;" class="ui-invitee ui-invitee-list" data-email-invitation="true">
        </div>
        <div class="ui-no-invitee-label" style="padding: 0 15px 10px 15px; font-size: 12px; color: #888888; display: none;">
            No invitee
        </div>
        <div class="ui-invitee-limit-label" style="padding: 0 15px; font-size: 12px; color: #888888; display: none;"></div>
        
    </div>
    <div class="modal-backdrop dim ui-more-menu-back" style="display: none; margin-top: 51px;"></div>
</nav>
<div class="ui-spinner unselectable hidden-print"></div>

    <div class="row ui-content" style="display: none;">
    <div class="ui-edit-area unselectable">
        <textarea id="textit"></textarea>
    </div>
    <div class="relative h-full ui-view-area">
        <div class="ui-infobar container-fluid unselectable hidden-print" style="visibility: hidden;">
            <small class="pull-left hmd-mt-1/2">
                <span class="ui-owner hmd-dn">
                    &thinsp;<a class="ui-user-icon small" target="_blank"></a>
                    &nbsp;<span class="text-uppercase">owned this note</span>
                </span>

                <span class="ui-owner-team hmd-dn">
                    &thinsp;<a class="ui-user-icon small" target="_blank"></a>
                    &nbsp;<span class="text-uppercase">owned this note</span>
                </span>

                <span class="ui-lastchangeuser hmd-dn">
                    &thinsp;<a class="ui-user-icon small" target="_blank"></a>
                    <span class="text-uppercase ui-status-lastchange"></span>
                </span>

                <span class="ui-no-lastchangeuser hmd-dn">
                    &thinsp;<i class="fa fa-clock-o fa-fw" style="width: 18px;"></i>
                    <span class="text-uppercase ui-status-lastchange"></span>
                </span>

                <span class="ui-more-info hmd-dn" data-toggle="popover">
                    &thinsp;<i class="fa fa-info-circle" aria-hidden="true"></i>

                    <div class="more-info-raw hmd-dn">
                        <span class="ui-published-note note-status-row hmd-db">
                            <i class="fa fa-globe" aria-hidden="true"></i>
                            Published
                        </span>

                        <span class="ui-connectedGithub note-status-row hmd-dn">
                            <i class="fa fa-20 ui-connectedGithubIcon fa-github"></i>

                            <span>Linked with GitHub</span>

                            <br>

                            <a class="file-path" target="_blank"></a>
                        </span>
                    </div>
                </span>
            </small>

            <span class="pull-right">
                
                    <span class="ui-signin community-button ui-like" data-toggle="tooltip" data-placement="bottom" title="Like"><i class="fa fa-fw"></i><span class="text hidden-xs">Like</span><span class="count"></span></span>
                    <span class="ui-signin community-button ui-bookmark" data-toggle="tooltip" data-placement="bottom" title="Bookmark"><i class="fa fa-fw"></i><span class="text hidden-xs"><span class="bookmark-label">Bookmark</span><span class="bookmarked-label">Bookmarked</span></span></span>
                
                
                <span class="ui-notification dropdown pull-right" style="display: none;">
                    <span id="notificationLabel" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">
                        <div  class="ui-notification-status community-button" title="Subscribe" data-toggle="tooltip" data-placement="bottom">
                            <i class="fa fa-fw fa-bell"></i><span class="text hidden-xs">Subscribed<i class="fa fa-fw fa-angle-down"></i><i class="fa fa-fw fa-angle-up"></i></span>
                        </div>
                    </span>
                    <ul class="dropdown-menu" aria-labelledby="notificationLabel">
                        <li class="ui-notification-watch notification-menu-item"><i class="fa fa-check fa-fw"></i><i class="fa fa-bell fa-fw"></i><div class="info"><div class="title">Any changes</div><div class="description">Be notified of any changes</div></div></li>
                        <li class="ui-notification-mention notification-menu-item"><i class="fa fa-check fa-fw"></i><i class="fa fa-at fa-fw"></i><div class="info"><div class="title">Mention me</div><div class="description">Be notified of mention me</div></div></li>
                        <li class="divider"></li>
                        <!--
                            <li class="ui-notification-list notification-menu-item"><span><a href="#"><i class="fa fa-list-ul fa-fw"></i>My subscribed list</a></span></li>
                        -->
                        <li class="ui-notification-unsubscribe notification-menu-item"><i class="fa fa-bell-slash-o fa-fw"></i>Unsubscribe</li>
                    </ul>
                    <span class="ui-notification-subscribe community-button"><i class="fa fa-fw fa-bell-o"></i><span class="text hidden-xs">Subscribe</span></span>
                </span>
                
                
                    <div class="visible-xs" style="margin-top: 10px;"></div>
                
            </span>
            <div class="ui-comment-app" id="hackmd-app">
                <div id="comment-app"></div>
            </div>
        </div>

        <div id="comments-panel-portal" class="ui-comment-app"></div>

        <div id="doc" class="markdown-body container-fluid" data-hard-breaks="true"># Notes for session D1 at WalletUncon 2023

Title of talk: **Account Abstraction’s relationship to MEV &amp; Block-Building**
Convener(s) of talk: eshon
Scribe(s) of talk:
Links to any presentation matter: https://hackmd.io/@evangelion808/rkVwA5VNT

Tips:
- if you use github or gitlab handles instead of names, that allows scribes and conveners to be easily findable/taggable in threads when these notes get published to the CASA github org)
- preface remarks with name/handle and org if you WANT to be credited for contributions or ideas. 
- feel free to call multiple people &#34;anon&#34; if you don&#39;t catch their names or they do not give them
- most scribes love an assist!

## Notes

- 4 main block builders
    - https://mevboost.pics/

## Links

- [description](https://example.com)

## Presentation Notes



#### Context 
- More and more chains are adding support for AA (Ethereum, BSC, Solana, Avax, Polygon, Algorand, Fantom, Gnosis, Tezos, Iotex, Harmony, Fuse, Optimism, Arbitrum, Celo, Near, Cosmos, Aurora, Polkadot, Flow), as well as many [RPC Providers](https://github.com/arddluma/awesome-list-rpc-nodes-providers#account-abstraction-rpc-providers).
- Filecoin launched an EVM this past March 2023 and the community is interested in adding support for AA.
  - However Filecoin&#39;s blockchain has a different structure from Ethereum&#39;s and does not have an MEV economy or tools like MEV-boost.
  - We are also worried about the possible attack vectors of AA because there are lots of trust assumptions between bundlers and block builders

#### What about Malicious Miners?

- There are places in the AA spec where submitting Txns to a malicious miner can cause trouble.
- These issues also exist on Eth where Txns are supposed to be submitted to &#34;block builders you trust&#34;...
- *What if there are malicious miners who attack bundlers?*
   - 4337 addresses this by saying that bundlers can only submit bundles to block producers they trust:
   
![Screen Shot 2023-11-17 at 11.45.42 AM](https://hackmd.io/_uploads/rkGAdjVE6.png)

 - `eth_sendRawTransactionConditional` - Polygon and Arbitum have implemented this API method
 - But from Polygon&#39;s https://github.com/maticnetwork/Polygon-Improvement-Proposals/blob/main/PIPs/PIP-15.md:
 
 ![Screen Shot 2023-11-17 at 11.54.15 AM](https://hackmd.io/_uploads/SJPU9iENT.png)

- From the PIP excerpt above: &#34;The validator trusts that the bundler is not going to spam him, and the bundler trusts that the validator will not front-run the transaction.&#34;

#### Centralized AA Infra &amp; Private Mempools

- Trust is straightforward when your AA infra provider is private but this is centralized
    - Users must select a specific private bundler to trust
    - AA infra provider must also be a block builder or work with block builders they trust.
- A public p2p mempool is coming to Ethereum

#### A Public Mempool is coming to Eth

The article [Why Must ERC-4337 Bundlers Work with Block Builders](https://medium.com/@blockpi/aa-useroperation-failure-incident-why-is-public-mempool-necessary-to-erc-4337-bundlers-d939d6dc8812) talks about nonce collision attacks in bundlers:

![Screen Shot 2023-11-17 at 12.04.42 PM](https://hackmd.io/_uploads/rJbCpjVN6.png)

- *To summarize the article:*

    - After the public mempool is introduced, most UserOps are from this pool.
    - There must be a mechanism to prevent multiple Bundlers from bundling the same UserOperation in the mempool.
    - EtherSpot is developing this p2p network where once bundled and processed on-chain, UserOps will be marked and delisted. They say: &#34;it is meaningless to send duplicate UserOps to the mempool because it can be easily detected by the p2p network.&#34;
    - At this point, multiple Bundlers will access the same set of unprocessed UserOps.
    - They recommend that **&#34;One cannot and should not run a bundler in the p2p mempool without a service like mevboost on a public mempool on Ethereum.&#34;**
    - This will ensure the elimination of duplicate submissions and reduce online rejections.

There seem to be additional hidden assumptions in how the mevboost block builder market work with bundlers.


- Filecoin doesn’t have an mevboost block builder market 
    - Do all of these chains have this?...
        - More and more chains (Eth, BSC, Solana, Avax, Polygon, Algorand, Fantom, Gnosis, Tezos, Iotex, Harmony, Fuse, Optimism, Arbitrum, Celo, Near, Cosmos, Aurora, Polkadot, Flow) are adding support for AA
</div>

        <section class="absolute top-0 bottom-0 left-0 right-0 z-50 overflow-hidden slide-preview-container" style="display: none;">
            <link rel="stylesheet" href="https://assets.hackmd.io/build/reveal.js/dist/theme/defaultTheme.css" id="theme">
            <div class="h-full reveal">
                <div class="slides" style="display: none;"></div>
            </div>
        </section>

        <div class="ui-toc dropup unselectable hidden-print" style="display:none;">
            <div class="pull-left dropdown">
                <a id="tocLabel" class="ui-toc-label btn btn-default" data-toggle="dropdown" href="#" role="button" aria-haspopup="true" aria-expanded="false" title="Table of content">
                    <i class="fa fa-bars"></i>
                </a>
                <ul id="ui-toc" class="ui-toc-dropdown dropdown-menu" aria-labelledby="tocLabel">
                </ul>
            </div>
        </div>
        <div class="toc-placeholder hidden"></div>
        <div id="ui-toc-affix" class="ui-affix-toc ui-toc-dropdown unselectable hidden-print" data-spy="affix" style="top:51px;display:none;"></div>
    </div>
</div>
<!-- clipboard modal -->
<div class="modal fade" id="clipboardModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">Import from clipboard</h4>
            </div>
            <div class="modal-body">
                <div contenteditable data-ph="Paste your markdown or webpage here..." id="clipboardModalContent" style="overflow:auto;max-height:50vh"></div>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
                <button type="button" class="btn btn-danger" id="clipboardModalClear">Clear</button>
                <button type="button" class="btn btn-primary" id="clipboardModalConfirm">Import</button>
            </div>
        </div>
    </div>
</div>
<!-- basic use modal -->
<div class="modal fade basic-use-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                <h4 class="modal-title" id="myModalLabel"><i class="fa fa-lock"></i> Advanced permission required</h4>
            </div>
            <div class="modal-body" style="color:black;">
                <h5>Your current role can only read. Ask the system administrator to acquire write and comment permission.</h5>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-primary ui-request-permission">Request permission</button>
                <button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
            </div>
        </div>
    </div>
</div>
<!-- team locked modal -->
<div class="modal fade team-locked-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                <h4 class="modal-title" id="myModalLabel"><i class="fa fa-lock"></i> This team is disabled</h4>
            </div>
            <div class="modal-body" style="color:black;">
                <h5>Sorry, this team is disabled. You can&#39;t edit this note.</h5>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-danger" data-dismiss="modal">OK</button>
            </div>
        </div>
    </div>
</div>
<!-- locked modal -->
<div class="modal fade locked-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                <h4 class="modal-title" id="myModalLabel"><i class="fa fa-lock"></i> This note is locked</h4>
            </div>
            <div class="modal-body" style="color:black;">
                <h5>Sorry, only owner can edit this note.</h5>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-danger" data-dismiss="modal">OK</button>
            </div>
        </div>
    </div>
</div>
<!-- limit modal -->
<div class="modal fade limit-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                <h4 class="modal-title" id="myModalLabel"><i class="fa fa-exclamation-triangle"></i> Reach the limit</h4>
            </div>
            <div class="modal-body" style="color:black;">
                <h5>Sorry, you&#39;ve reached the max length this note can be.</h5>
                <strong>Please reduce the content or divide it to more notes, thank you!</strong>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-warning" data-dismiss="modal">OK</button>
            </div>
        </div>
    </div>
</div>
<!-- gist import modal -->
<div class="modal fade" id="gistImportModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">Import from Gist</h4>
            </div>
            <div class="modal-body">
                <input type="url" class="form-control" placeholder="Paste your gist url here... (like: https://gist.github.com/username/gistid)" id="gistImportModalContent">
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
                <button type="button" class="btn btn-danger" id="gistImportModalClear">Clear</button>
                <button type="button" class="btn btn-primary" id="gistImportModalConfirm">Import</button>
            </div>
        </div>
    </div>
</div>
<!-- snippet import modal -->
<div class="modal fade" id="snippetImportModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">Import from Snippet</h4>
            </div>
            <div class="modal-body">
                <input type="hidden" id="snippetImportModalAccessToken" />
                <input type="hidden" id="snippetImportModalBaseURL" />
                <div class="ui-field-contain" style="display:table;margin-bottom:10px;width:100%;">
                    <div style="display:table-row;margin-bottom:5px;">
                        <label style="display:table-cell;">Project:</label>
                        <select class="form-control" id="snippetImportModalProjects" style="display:table-cell;" disabled="disabled">
                            <option value="init" selected="selected" disabled="disabled">Select From Available Projects</option>
                        </select>
                    </div>
                    <div style="display:table-row;">
                        <label style="display:table-cell;">Snippet:</label>
                        <select class="form-control" id="snippetImportModalSnippets" style="display:table-cell;" disabled="disabled">
                            <option value="init" selected="selected" disabled="disabled">Select From Available Snippets</option>
                        </select>
                    </div>
                </div>
                <p class="snippet-import-or">or</p>
                <input type="url" class="form-control" placeholder="/projects/:id/snippets/:snippet_id" id="snippetImportModalContent" disabled="disabled">
            </div>
            <div class="modal-footer">
                <span id="snippetImportModalLoading"><i class="fa fa-refresh fa-spin fa-fw"></i></span>
                <button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
                <button type="button" class="btn btn-danger" id="snippetImportModalClear">Clear</button>
                <button type="button" class="btn btn-primary" id="snippetImportModalConfirm" disabled="disabled">Import</button>
            </div>
        </div>
    </div>
</div>
<!-- snippet export modal -->
<div class="modal fade" id="snippetExportModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
    <div class="modal-dialog">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">Export to Snippet</h4>
            </div>
            <div class="modal-body">
                <input type="hidden" id="snippetExportModalAccessToken" />
                <input type="hidden" id="snippetExportModalBaseURL" />
                <div class="ui-field-contain" style="display:table;margin-bottom:10px;width:100%;">
                    <div style="display:table-row;margin-bottom:5px;">
                        <label style="display:table-cell;">Title:</label>
                        <input class="form-control" placeholder="new snippet" type="text" id="snippetExportModalTitle" />
                    </div>
                    <div style="display:table-row;margin-bottom:5px;">
                        <label style="display:table-cell;">File Name:</label>
                        <input class="form-control" placeholder="new_snippet.md" type="text" id="snippetExportModalFileName" />
                    </div>
                    <div style="display:table-row;margin-bottom:5px;">
                        <label style="display:table-cell;">Project:</label>
                        <select class="form-control" id="snippetExportModalProjects" style="display:table-cell;">
                            <option value="init" selected="selected" disabled="disabled">Select From Available Projects</option>
                        </select>
                    </div>
                    <div style="display:table-row;margin-bottom:5px;">
                        <label style="display:table-cell;">Visibility:</label>
                        <select class="form-control" id="snippetExportModalVisibility" style="display:table-cell;">
                            <option value="" selected="selected" disabled="disabled">Select Visibility Level</option>
                            <option value="0">Private</option>
                            <option value="10">Internal</option>
                        </select>
                    </div>
                </div>
            </div>
            <div class="modal-footer">
                <span id="snippetExportModalLoading"><i class="fa fa-refresh fa-spin fa-fw"></i></span>
                <button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
                <button type="button" class="btn btn-primary" id="snippetExportModalConfirm">Export</button>
            </div>
        </div>
    </div>
</div>
<!-- delete modal -->
<div class="modal fade delete-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">Are you sure?</h4>
            </div>
            <div class="modal-body" style="color:black;">
                <h5 class="ui-delete-modal-msg">Do you really want to delete this note?</h5>
                <strong class="ui-delete-modal-item">All users will lost their connection.</strong>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
                <button type="button" class="btn btn-danger ui-delete-modal-confirm">Yes, do it!</button>
            </div>
        </div>
    </div>
</div>

<!-- template notes modal -->
<div class="modal fade template-modal" id="templateModal" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel" aria-hidden="true"  data-team="walletuncon2023"  >
    <div class="modal-dialog modal-lg" style="width: calc(100vw - 20px); max-width: 1000px;">
        <div class="modal-content template-content">
            <div class="modal-header">
                <button type="button" class="close ui-template-cancel visible-xs hidden-xs" style="margin-top: 2px !important; font-size: 15px !important; display: none;"><span aria-hidden="true">Cancel</span></button>
                <button type="button" class="close ui-template-close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true"><i class="fa fa-times fa-18"></i></span></button>
                <h4 class="modal-title ui-template-title" id="mySmallModalLabel"><i class="fa fa-file-image-o"></i> <span>Create a note from template</span></h4>
                <h4 class="modal-title visible-xs hidden-xs ui-template-title-xs"><i class="fa fa-file-image-o"></i> <span>Create a note from template</span></h4>
            </div>
            <div class="modal-body" style="padding: 0px; overflow-x: hidden;">
                <div class="row">
                    <div class="col-sm-8 template-preview-container hidden-xs">
                        <div>
                            <div class="ui-template-spinner unselectable hidden-print"></div>
                            <iframe class="template-viewer" style="width: 100%; height: 100%; border: none;"></iframe>
                            <div class="template-empty ui-template-viewer-empty" style="display: none; margin: 0px;">
                                <img src="https://hackmd.io/not-available.svg">
                                <div>
                                    <div>Oops...</div>
                                    <div>This template has been removed or transferred.</div>
                                </div>
                            </div>
                        </div>
                        <button type="button" class="visible-xs btn btn-primary ui-use-template-btn-mobile">Use this template</button>
                    </div>
                    <div class="col-sm-4 template-list-container">
                        <div class="ui-templates-container">
                            <div class="border-0 border-b border-gray-200 border-solid template-button-container hmd-pa-2">
                                
                                    
                                        <button type="button" class="btn btn-success w-100" style="height: 40px; font-size: 16px;" data-toggle="modal" data-target=".signin-modal">
                                            Sign in
                                        </button>
                                    
                                

                                <p style="margin-top: 15px; display: none;" class="template-quota-alert">
                                    <span class="template-quota-description" style="color: #777777;"></span>
                                    <br>
                                    <a target="_blank" href="/?nav=billing" class="template-quota-upgrade-now">
                                        Upgrade
                                        <i class="fa fa-fw fa-angle-right" aria-hidden="true"></i>
                                    </a>
                                </p>
                            </div>

                            <div class="dropdown ui-template-list-filter" style="margin: 20px;">
                                <a class="ui-template-list-filter-label" id="template-list-filter" data-filter-type="all" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false"><span>All</span><i class="fa fa-angle-down" aria-hidden="true" style="margin-left: 10px;"></i></a>
                                <ul class="dropdown-menu" role="menu" aria-labelledby="template-list-filter" style="right: 0px; left: auto;">
                                    <li role="presentation"><a role="menuitem" class="ui-template-filter-all" tabindex="-1" href="#">All</a></li>
                                    
                                    <li role="presentation"><a role="menuitem" class="ui-template-filter-team" tabindex="-1" href="#">Team</a></li>
                                    
                                </ul>
                            </div>
                            <div class="template-empty ui-template-list-empty">
                                <i class="fa fa-file-image-o" aria-hidden="true"></i>
                                <div>No template.</div>
                            </div>
                            <div class="list-group ui-template-list" style="flex:1;">
                            </div>
                            <button type="button" class="btn btn-primary ui-use-template-btn hidden-xs">Use this template</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- create template modal -->
<div class="modal fade create-template-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true"  data-team="walletuncon2023"  >
    <div class="modal-dialog modal-lg" style="width: calc(100vw - 20px); max-width: 860px;">
        <form>
            <div class="modal-content template-content">
                <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal" aria-label="Close" style="margin-top: 2px; height: 17px;"><span aria-hidden="true"><i class="fa fa-times fa-18"></i></span>
                    </button>
                    <h4 class="modal-title" id="myModalLabel">Create a template</h4>
                </div>

                <div class="modal-body hmd-text-center" style="color:black; padding: 20px; padding-bottom: 10px; text-align: left;">
                    <div class="mb-5 template-quota-excceed-block">
                        <span class="template-quota-description" style="color: #777777;"></span>
                        <br>
                        <a target="_blank" href="/?nav=billing" class="template-quota-upgrade-now">
                            Upgrade
                            <i class="fa fa-fw fa-angle-right" aria-hidden="true"></i>
                        </a>
                    </div>


                    <div class="grid items-center grid-cols-12 form-group mb-7" >
                        <label class="col-span-4 font-normal text-black-brand" for="templateName">Template name</label>

                        <input type="text" id="templateName" class="col-span-8 form-control" placeholder="Template name" aria-label="TemplateName" aria-describedby="template-name" maxlength="250" required>
                    </div>

                    <div class="grid items-start grid-cols-12 form-group creation-method-option">
                        <label class="col-span-4 font-normal text-black-brand" for="templateName">Save as option</label>

                        <div class="col-span-8">
                            <label class="w-full font-normal ui-save-template-directly" for="save-template-directly">
                                <input type="radio" name="save-template" value="save-directly" checked id="save-template-directly">
                                <span class="ml-2">Save this note as a template</span>
                            </label>

                            <label class="w-full font-normal ui-save-template-as-another-template" for="save-template-as-another-template">
                                <input type="radio" name="save-template" value="save-as-another-template" id="save-template-as-another-template">
                                <span class="ml-2">Save to another note as a template</span>
                            </label>
                        </div>
                    </div>

                </div>

                <div class="modal-footer" style="border: none; padding: 20px;">
                    <button type="button" class="btn btn-default" data-dismiss="modal" style="flex:1;">Cancel</button>
                    <button type="submit" class="btn btn-primary ui-create-template-modal-confirm" style="flex:1;">Yes</button>
                </div>
            </div>
        </form>
    </div>
</div>

<!-- delete template modal -->
<div class="modal fade delete-template-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-sm">
        <div class="modal-content template-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close" style="margin-top: 2px; height: 17px;"><span aria-hidden="true"><i class="fa fa-times fa-18"></i></span>
                </button>
                <h4 class="modal-title" id="myModalLabel">Delete template</h4>
            </div>
            <div class="modal-body hmd-text-center" style="color:black; padding: 14.5px 15px; padding-bottom: 0px; text-align: left;">
                <p class="ui-delete-modal-msg" style="font-size: 15px;">Do you really want to delete this template?</p>
                <div class="form-check" style="display: flex;">
                    <input type="checkbox" class="form-check-input ui-delete-note-check" style="margin-top: 7px;" id="deleteNoteCheck">
                    <label class="form-check-label" style="margin-top: 3px; margin-left: 5px; font-weight: 400;" for="deleteNoteCheck">
                        Keep the content
                        <div style="font-size: 13px; margin-top: 5px; color: #818181; line-height: 18px;">Turn this template into a regular note and keep its content, versions, and comments.</div>
                    </label>
                </div>
            </div>
            <div class="modal-footer" style="border: none; padding: 20px 15px; display: flex;">
                <button type="button" class="btn btn-default" data-dismiss="modal" style="flex:1;">Cancel</button>
                <button type="button" class="btn btn-danger ui-delete-template-modal-confirm" style="flex:1;">Delete</button>
            </div>
        </div>
    </div>
</div>

<!-- refresh modal -->
<div class="modal fade" id="refreshModal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">This page need refresh</h4>
            </div>
            <div class="modal-body">
                <div class="incompatible-version">
                    <h5>You have an incompatible client version.</h5>
                    <strong>Refresh to update.</strong>
                </div>
                <div class="new-version" style="display:none;">
                    <h5>New version available!</h5>
                    <a href="https://hackmd.io/s/release-notes" target="_blank">See releases notes here</a>
                    <br>
                    <strong>Refresh to enjoy new features.</strong>
                </div>
                <div class="user-state-changed" style="display:none;">
                    <h5>Your user state has changed.</h5>
                    <strong>Refresh to load new user state.</strong>
                </div>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-primary" id="refreshModalRefresh">Refresh</button>
            </div>
        </div>
    </div>
</div>

<!-- signin modal -->

<div class="modal fade signin-modal" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel" aria-hidden="true">
    <div class="modal-dialog">
        <div class="modal-content">
            <button type="button" class="close" data-dismiss="modal" aria-label="Close" style="margin-top: 10px; right: 20px; position: absolute;"><span aria-hidden="true">&times;</span></button>
            






    







<h3>Sign in</h3>

<form data-toggle="validator" role="form" class="form-horizontal" method="post" enctype="application/x-www-form-urlencoded" id="signin-form">
    <div class="hmd-dn"><input type="hidden" name="_csrf" value="W85hNrzr-xhBU3hdocWqeAjcJ17Jn-1rB250"></div>
    <div class="hmd-dn"><input type="hidden" name="create_team" value="false"></div>
    <div class="hmd-dn"><input type="hidden" name="create_paid_team" value="false"></div>
    <div class="form-group  ">
        <label for="email" class="control-label">Email</label>
        <label for="inputEmail" class="control-label pull-right errors">
            
        </label>
        <span class="help-block control-label with-errors pull-right" style="display: inline;"></span>
        <div class="input-block">
            
                <input type="email" class="form-control" name="email" placeholder="Your email" required autocomplete="email">
            
            <span class="error-sign"></span>
        </div>
    </div>
    <div class="form-group ">
        <label for="password" class="control-label">Password</label>
        <label for="inputPassword" class="control-label pull-right errors">
            
        </label>
        <span class="help-block control-label with-errors pull-right" style="display: inline;"></span>
        <div class="input-block">
            <input type="password" class="form-control" name="password" placeholder="Your password" required autocomplete="current-password">
            <span class="error-sign"></span>
            
                <span class="control-label pull-right" style="font-size: 13px; margin-top: 5px;"><a href="https://hackmd.io/settings/forgotPassword" style="text-decoration: underline;">Forgot password</a></span>
            
        </div>
    </div>

    <div style="text-align: center; padding-top: 15px; margin-bottom: 0px;">
        
            <input type="hidden" id="recaptcha-token" name="g-recaptcha-response">
        

        
            <input type="submit" class="btn btn-success btn-large" formaction="https://hackmd.io/login" value="Sign in">
        

        
    </div>
</form>








    
        <p class="separator">or</p>
    

    
        <p>By clicking below, you agree to our <a href="https://hackmd.io/s/terms" target="_blank">terms of service</a>.</p>
    

    








 



<script id="gsi-client" src="https://accounts.google.com/gsi/client" async defer nonce="7e4e2a18-0f6b-48a9-9017-39e491ea067a"></script>
<script nonce="7e4e2a18-0f6b-48a9-9017-39e491ea067a">
    function handleCredentialResponse(response) {
        const form = document.getElementById('sign-in-with-google-form')
        form.children.credential.value = response.credential
        form.children.method.value = location.href.toLowerCase() === 'https://hackmd.io/settings#general' ? 'merge' : 'login'
        form.submit()
    }
    var GSI_READY = new Promise(function (resolve) {
        function initialize () {
            google.accounts.id.initialize({
                client_id: '911617723593-drikdibvvn63slfd6kbqigo8ql1no55s.apps.googleusercontent.com',
                callback: handleCredentialResponse
            })
            const loginPath = 'https://hackmd.io/login'
            const joinPath = 'https://hackmd.io/join'
            const renderButton = function () {
                google.accounts.id.renderButton(
                    document.getElementById('sign-in-with-google-button'),
                    { type: 'standard', width: 250 }
                )
            }
            if (location.href.toLowerCase() === loginPath || location.href.toLowerCase() === joinPath) {
                renderButton()
            } else {
                $('.signin-modal').one('shown.bs.modal', function () {
                    renderButton()
                })
            }
            resolve()
        }

        window.addEventListener('load', function () { initialize() })
    })
</script>
<form class="hidden" id="sign-in-with-google-form" action="/auth/google" method="post">
    <input type="hidden" name="credential">
    <input type="hidden" name="method">
</form>
 

<div class="social-buttons-container">
    
    <div id="sign-in-with-google-button"></div>
    
    
    <a href="https://hackmd.io/auth/facebook" class="btn btn-lg btn-block btn-social btn-facebook">
        <i class="fa fa-facebook"></i> Sign in via Facebook
    </a>
    
    
    <a href="https://hackmd.io/auth/twitter" class="btn btn-lg btn-block btn-social btn-twitter">
        <i class="fa fa-twitter"></i> Sign in via Twitter
    </a>
    
    
    <a href="https://hackmd.io/auth/github" class="btn btn-lg btn-block btn-social btn-github">
        <i class="fa fa-github"></i> Sign in via GitHub
    </a>
    
    
    <a href="https://hackmd.io/auth/dropbox" class="btn btn-lg btn-block btn-social btn-dropbox">
        <i class="fa fa-dropbox"></i> Sign in via Dropbox
    </a>
    
    
    
</div>





    <div >
        <p>New to HackMD? <a href="https://hackmd.io/join">Sign up</a></p>
    </div>


            
<script nonce="7e4e2a18-0f6b-48a9-9017-39e491ea067a">
  (function () {
    function onSubmit (e) {
      const submitButton = e.target
      const tokenInput = document.getElementById('recaptcha-token')
      if (tokenInput.value) return

      e.preventDefault()
      grecaptcha.enterprise.ready(async () => {
        const token = await grecaptcha.enterprise.execute('6LdtkK4ZAAAAAG1B4iENhmQTce1xNTyHu0GjgnXi', {action: 'login'})
        tokenInput.value = token
        submitButton.click()
      })
    }
    document.querySelectorAll('#signin-form input[type="submit"]').forEach((el) => {
      el.addEventListener('click', onSubmit)
    })
  })()
</script>


        </div>
    </div>
</div>

<!-- help modal -->
<div class="modal fade help-modal" id="help-modal" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                <h4 class="modal-title" id="mySmallModalLabel"><i class="fa fa-question"></i> Help</h4>
            </div>
            <div class="modal-body">
                <div class="row">
                    <div class="col-lg-3">
                        <div class="dropdown" style="margin-bottom: 30px;">
                            <button id="helpLangDropdown" type="button" class="btn btn-default modal-lang-btn" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                                Switch language
                                <span class="caret"></span>
                            </button>
                            <ul class="dropdown-menu" id="modal-lang-menu" aria-labelledby="helpLangDropdown">
                                <li><a href="#" class="modal-lang-menu-item" data-lang="en">
                                    <i class="fa fa-check"></i> English
                                </a></li>
                                <li><a href="#" class="modal-lang-menu-item" data-lang="zh">
                                    <i class="fa fa-check"></i> 中文
                                </a></li>
                                <li><a href="#" class="modal-lang-menu-item" data-lang="fr">
                                    <i class="fa fa-check"></i> Français
                                </a></li>
                                <li><a href="#" class="modal-lang-menu-item" data-lang="de">
                                    <i class="fa fa-check"></i> Deutsch
                                </a></li>
                                <li><a href="#" class="modal-lang-menu-item" data-lang="ja">
                                    <i class="fa fa-check"></i> 日本語
                                </a></li>
                                <li><a href="#" class="modal-lang-menu-item" data-lang="es">
                                    <i class="fa fa-check"></i> Español
                                </a></li>
                                <li><a href="#" class="modal-lang-menu-item" data-lang="ca">
                                    <i class="fa fa-check"></i> Català
                                </a></li>
                                <li><a href="#" class="modal-lang-menu-item" data-lang="el">
                                    <i class="fa fa-check"></i> Ελληνικά
                                </a></li>
                                <li><a href="#" class="modal-lang-menu-item" data-lang="pt">
                                    <i class="fa fa-check"></i> Português
                                </a></li>
                                <li><a href="#" class="modal-lang-menu-item" data-lang="it">
                                    <i class="fa fa-check"></i> italiano
                                </a></li>
                                <li><a href="#" class="modal-lang-menu-item" data-lang="tr">
                                    <i class="fa fa-check"></i> Türkçe
                                </a></li>
                                <li><a href="#" class="modal-lang-menu-item" data-lang="ru">
                                    <i class="fa fa-check"></i> Русский
                                </a></li>
                                <li><a href="#" class="modal-lang-menu-item" data-lang="nl">
                                    <i class="fa fa-check"></i> Nederlands
                                </a></li>
                                <li><a href="#" class="modal-lang-menu-item" data-lang="hr">
                                    <i class="fa fa-check"></i> hrvatski jezik
                                </a></li>
                                <li><a href="#" class="modal-lang-menu-item" data-lang="pl">
                                    <i class="fa fa-check"></i> język polski
                                </a></li>
                                <li><a href="#" class="modal-lang-menu-item" data-lang="uk">
                                    <i class="fa fa-check"></i> Українська
                                </a></li>
                                <li><a href="#" class="modal-lang-menu-item" data-lang="hi">
                                    <i class="fa fa-check"></i> हिन्दी
                                </a></li>
                                <li><a href="#" class="modal-lang-menu-item" data-lang="sv">
                                    <i class="fa fa-check"></i> svenska
                                </a></li>
                                <li><a href="#" class="modal-lang-menu-item" data-lang="eo">
                                    <i class="fa fa-check"></i> Esperanto
                                </a></li>
                                <li><a href="#" class="modal-lang-menu-item" data-lang="da">
                                    <i class="fa fa-check"></i> dansk
                                </a></li>
                            </ul>
                        </div>
                        <div class="modal-side-menu-block">
                            <h4>Documents</h4>
                            <p>
                                <a href="https://hackmd.io/c/tutorials" title="Tutorials" target="_blank">Tutorials <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                            <p>
                                <a href="https://hackmd.io/c/tutorials/%2Fs%2Fhow-to-create-book" title="Book Mode Tutorial" target="_blank">Book Mode Tutorial <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                            <p>
                                <a href="https://hackmd.io/c/tutorials/%2Fs%2Fhow-to-create-slide-deck" title="Slide Mode Tutorial" target="_blank">Slide Example <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                            <p>
                                <a href="./yaml-metadata" title="YAML Metadata" target="_blank">YAML Metadata <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                        </div>

                        
                        <div class="modal-side-menu-block">
                            <h4>Contacts</h4>
                            <p>
                                <a href="https://facebook.com/hackmdio" target="_blank">Facebook <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                            <p>
                                <a href="https://twitter.com/hackmdio" target="_blank">Twitter <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                            <p>
                                <a href="https://discord.gg/yDw3AJbmwx" target="_blank">Discord <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                            
                                <p>
                                    <a href="#" data-toggle="modal" data-target=".feedback-modal">Feedback <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                                </p>
                            
                            <p>
                                <a href="mailto:support@hackmd.io">Send us email <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                        </div>
                        

                        <div class="modal-side-menu-block">
                            <h4>Resources</h4>
                            <p>
                                <a href="/s/release-notes" title="Tutorials" target="_blank">Releases <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                            
                            <p>
                                <a href="/pricing" title="YAML Metadata" target="_blank">Pricing <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                            
                            <p>
                                <a href="https://blog.hackmd.io" title="Blog" target="_blank">Blog <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                        </div>

                        <div class="modal-side-menu-block">
                            <h4>Policy</h4>
                            <p>
                                <a href="/s/terms" title="Tutorials" target="_blank">Terms <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                            <p>
                                <a href="/s/privacy" title="YAML Metadata" target="_blank">Privacy <span style="margin-left: 0.5em;"><i class="fa fa-angle-right"></i></span> </a>
                            </p>
                        </div>
                    </div>
                    <div class="col-lg-9">
                        <div class="modal-vertical-divider"></div>
                        <div class="tabs">
                            <h4 class="tab-item active" data-tabidx="1">Cheatsheet</h4>
                            <!-- <h4 class="tab-item" data-tabidx="2">FAQ</h4> -->
                            <div class="tab-slider-rail">
                                <div class="tab-slider"></div>
                            </div>
                        </div>
                        <table class="table table-condensed table-cheatsheet">
                            <thead class="markdown-example-table-head">
                                <tr>
                                    <th>Syntax</th>
                                    <th>Example</th>
                                    <th class="hidden-xs">Reference</th>
                                </tr>
                            </thead>
                            <tbody class="markdown-body markdown-example-table-body" style="font-family: inherit; font-size: 14px; padding: 0; max-width: inherit;">
                                <tr>
                                    <td class="example-syntax"># Header</td>
                                    <td class="example-present">Header</td>
                                    <td rowspan="14" class="show-on-zh hidden-xs"><a href="https://hackmd.io/c/tutorials-tw/%2Fs%2Fbasic-markdown-formatting-tw">基本排版</a></td>
                                    <td class="show-on-not-zh hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">- Unordered List</td>
                                    <td class="example-present"><ul style="margin: 0;"><li>Unordered List</li></ul></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">1. Ordered List</td>
                                    <td class="example-present"><ol style="margin: 0;"><li>Ordered List</li></ol></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">- [ ] Todo List</td>
                                    <td class="example-present"><ul style="margin: 0;"><li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled><label></label>Todo List</li></ul></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">> Blockquote</td>
                                    <td class="example-present"><blockquote style="margin: 0;"> Blockquote</blockquote></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">**Bold font**</td>
                                    <td class="example-present"><strong>Bold font</strong></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">*Italics font*</td>
                                    <td class="example-present"><i>Italics font</i></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">~~Strikethrough~~</td>
                                    <td class="example-present"><s>Strikethrough</s></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">19^th^</td>
                                    <td class="example-present">19<sup>th</sup></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">H~2~O</td>
                                    <td class="example-present">H<sub>2</sub>O</td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">++Inserted text++</td>
                                    <td class="example-present"><ins>Inserted text</ins></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">==Marked text==</td>
                                    <td class="example-present"><mark>Marked text</mark></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">[link text](https:// "title")</td>
                                    <td class="example-present"><a>Link</a></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">![image alt](https:// "title")</td>
                                    <td class="example-present">Image</td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">`Code`</td>
                                    <td class="example-present"><code>Code</code></td>
                                    <td rowspan="2" class="show-on-zh hidden-xs"><a href="https://hackmd.io/c/tutorials-tw/%2Fs%2Fhow-to-use-code-blocks-tw">在筆記中貼入程式碼</a></td>
                                    <td class="show-on-not-zh hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">```javascript<br>var i = 0;<br>```</td>
                                    <td class="example-present"><pre style="border:none !important; margin: 0;"><code class="javascript hljs"><div class="wrapper"><div class="gutter linenumber"><span data-linenumber="1"></span></div><div class="code"><span class="hljs-keyword">var</span> i = <span class="hljs-number">0</span>;</div></div></code></pre></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">:smile:</td>
                                    <td class="example-present"><img align="absmiddle" alt=":smile:" class="emoji" src="./build/emojify.js/dist/images/basic/smile.png" title=":smile:"></img></td>
                                    <td class="hidden-xs"><a href="https://github.com/ikatyang/emoji-cheat-sheet">Emoji list</a></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">{%youtube youtube_id %}</td>
                                    <td class="example-present">Externals</td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">$L^aT_eX$</td>
                                    <td class="example-present">L<sup>a</sup>T<sub>e</sub>X</td>
                                    <td class="hidden-xs"></td>
                                </tr>
                                <tr>
                                    <td class="example-syntax">:::info<br>This is a alert area.<br>:::</td>
                                    <td class="example-present"><div class="alert alert-info" style="margin: 0;"><p>This is a alert area.</p></div></td>
                                    <td class="hidden-xs"></td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- revision modal -->
<div class="modal fade" id="revisionModal" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-lg" style="width: calc(100vw - 20px); max-width: 1000px;">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                <h4 class="modal-title" id="mySmallModalLabel"><i class="fa fa-history"></i> Versions</h4>
            </div>
            <div class="modal-body">
                <div class="row">
                    <div class="col-sm-4" style="max-height: calc(100vh - 215px); overflow: auto;">
                        <div class="list-group ui-revision-list"></div>
                    </div>
                    <div class="col-sm-8" style="height: calc(100vh - 215px); overflow: hidden;">
                        <textarea id="revisionViewer" style="display:none;"></textarea>
                    </div>
                </div>
            </div>
            <div class="modal-footer">
                <button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
                <button type="button" class="btn btn-primary" id="revisionModalDownload">Download</button>
                <button type="button" class="btn btn-danger" id="revisionModalRevert">Revert</button>
            </div>
        </div>
    </div>
</div>

<!-- revision modal -->
<div class="modal fade" id="namedRevisionModal" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-lg" style="width: calc(100vw - 20px); max-width: 1200px; height: calc(100vh - 100px);">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                <button type="button" class="close back" aria-label="Back"><span aria-hidden="true"><i class="fa fa-arrow-left" aria-hidden="true"></i></span>
                </button>
                <h4 class="modal-title" id="mySmallModalLabel"><i class="fa fa-history"></i> Versions and GitHub Sync</h4>
            </div>
            <div class="container-fluid modal-body hmd-pa-0 github-sync-enabled" style="max-height: calc(100vh - 100px); height: calc(100vh - 100px); overflow: hidden;">
                
                <div class="hidden-xs ui-github-sync" style="height: 51px; border-bottom: solid 1px #e7e7e7;">
                    <div style="display: none;" class="signin-to-connect">
                        Sign in to link this note to GitHub
                        <button class="btn btn-success" style="margin-left: 30px" data-toggle="modal" data-target=".signin-modal">Sign in to HackMD</button>
                        <a href="https://hackmd.io/c/tutorials/%2Fs%2Flink-with-github" target="_blank" style="margin-left: 30px;"><span>Learn more</span><i class="fa fa-angle-right fa-fw"></i></a></a>
                    </div>
                    <div style="display: none;" class="no-connect-github">
                        This note is not linked with GitHub
                        <button class="btn btn-primary btn-outline ui-github-pull" style="margin-left: 30px">Pull from GitHub</button>
                        <button class="btn btn-primary btn-outline ui-github-push" style="margin-left: 10px">Push to GitHub</button>
                        <a href="https://hackmd.io/c/tutorials/%2Fs%2Flink-with-github" target="_blank" style="margin-left: 30px;"><span>Learn more</span><i class="fa fa-angle-right fa-fw"></i></a></a>
                    </div>
                    <div style="display: none;" class="github-status">
                        <i class="fa fa-github"></i>&nbsp;<div class="github-path-container"><a target="_blank" class="github-path" title="" data-toggle="tooltip" data-placement="bottom" data-offset="30px,5" data-container=".github-status" data-original-title=""></a></div></span>

                        <a class="ui-github-badge github-control site-ui-font" style="margin-left: 30px;">
                            <i class="fa fa-link fa-18"></i>
                            Add badge
                        </a>
                        <a class="ui-github-pull github-control" style="margin-left: 30px;">
                            <i class="fa fa-arrow-down fa-18"></i>
                            Pull
                        </a>
                        <a class="ui-github-push github-control"  style="margin-left: 30px;">
                            <i class="fa fa-arrow-up fa-18"></i>
                            Push
                        </a>
                        <a class="ui-show-github-synced-settings-modal github-control" style="margin-left: 30px;">
                            <i class="fa fa-cog fa-18"></i>
                            GitHub Link Settings
                        </a>
                    </div>
                </div>
                
                <div class="col-xs-12 col-sm-4 hmd-pl-0 hmd-pr-0 sidebar revision-list-container">
                    <div class="list-group ui-named-revision-list"></div>
                    <div class="list-group ui-upgrade-tips" style="display: none;">
                        <div class="upgrade-tips"></div>
                        <a class="ui-upgrade-button" target="_blank" href="/?nav=billing">Upgrade now<i class="fa fa-angle-right" style="margin-left: 5px"></i></a>
                    </div>
                    <div class="list-group ui-version-preview-list" style="display: none;"></div>
                </div>
                <div id="revision-editor-container" class="col-xs-12 col-sm-8 hmd-pl-0 hmd-pr-0 hmd-flex hmd-flex-column">
                    <div id="revisionSummary" style="display: none;" class="hmd-flex">
                        <h4 style="margin-right: 5px;">
                            <i class="fa fa-history"></i>
                        </h4>

                        <div class="hmd-flex hmd-flex-column hmd-flex-auto">
                            <h4 class="summary-title"></h4>
                            <p class="summary-author-info hmd-flex hmd-flex-wrap-xs">
                                <span class="summary-timestamp" style="margin-right: 15px;"></span>
                                <span>Version named by &nbsp;</span>
                                <span class="summary-authorship">
                                    <a href="#"></a> &nbsp;
                                </span>
                                <span></span>
                            </p>
                            <div class="hmd-flex hmd-items-end hmd-justify-between">
                                <p class="summary-description" style="margin-bottom: 22px;"></p>
                                <div class="summary-collapse-toggle">
                                    <span class="expand">
                                        More
                                        <i class="fa fa-angle-down" aria-hidden="true"></i>
                                    </span>
                                    <span class="collapse">
                                        Less
                                        <i class="fa fa-angle-up" aria-hidden="true"></i>
                                    </span>
                                </div>
                            </div>
                        </div>

                        <div class="dropdown-container hmd-dni-xs" id="revisionSummaryDropdown">
                            <ul class="dropdown-menu" role="menu" aria-labelledby="menu">
                                <li role="presentation">
                                    <a role="menuitem" class="ui-rename-revision" id="rename-named-revision-button" tabindex="-1" href="#">
                                        <i class="fa fa-pencil fa-fw"></i> Edit
                                    </a>
                                </li>

                                <li role="presentation">
                                    <a role="menuitem" class="ui-delete-revision" tabindex="-1" href="#" id="remove-named-revision-button">
                                    <i class="fa fa-trash fa-fw"></i> Delete</a>
                                </li>
                            </ul>
                            <a class="ui-revision-action-menu" data-toggle="dropdown" style="color: #777;" aria-expanded="false"><i class="fa fa-ellipsis-h fa-fw" style="vertical-align: middle; width:100%;"></i>
                            </a>
                        </div>

                        <div class="create-revision-button-container hmd-flex hmd-items-center hmd-dni-xs">
                            <i class="fa fa-question-circle fa-fw tooltip-align-left" style="color: #CDCDCD; margin-right: 10px;" title="" data-toggle="tooltip" data-placement="bottom" data-offset="0,5" data-original-title="Save current content into a named version."></i>
                            <button class="btn btn-outline btn-primary ui-create-revision-button" title="Note content is identical to the latest version." data-toggle="tooltip" data-placement="bottom" data-offset="0,5">
                                Name version
                            </button>
                        </div>
                    </div>

                    <form data-toggle="validator" id="namedRevisionForm" style="display: none;" class="hmd-flex hmd-flex-column hmd-dni-xs" role="form">
                        <h4 style="display: none;" class="revision-timestamp">
                            <i style="margin-right: 1px;" class="fa fa-history"></i>
                            <span></span>
                        </h4>
                        <div class="hmd-flex" style="margin-top: 10px;">
                            <div class="hmd-flex hmd-flex-column hmd-flex-auto">
                                <div class="hmd-flex hmd-items-center form-group">
                                    <label class="control-label" for="name">
                                        Name
                                    </label>
                                    <input class="form-control" name="name" type="text" placeholder="Please name the version" required maxlength="80">
                                </div>

                                <div class="hmd-flex hmd-items-start form-group">
                                    <label class="control-label" for="description">
                                        Description
                                    </label>
                                    <textarea rows="3" class="form-control" name="description" placeholder="Please describe the version (optional)" maxlength="500" style="max-height: 74px; resize: none;"></textarea>
                                    <div class="help-block with-errors"></div>
                                </div>
                            </div>
                            <div class="hmd-flex hmd-items-end form-group" style="margin-left: 40px;">
                                <strong class="ui-state-message" style="position: absolute; top: 20px; color:green; padding-right: 15px;">
                                    Note content is identical to the latest version.
                                </strong>
                                <button type="button" id="cancel-named-revision-button" class="btn btn-default" style="margin-right: 10px;">Cancel</button>
                                <button type="submit" id="submit-named-revision-button" class="btn btn-primary">
                                    Name this version
                                </button>
                            </div>
                        </div>
                    </form>

                    <div style="height: calc(100vh - 140px); overflow: hidden;">
                        <textarea id="namedrevisionViewer" style="display:none;"></textarea>
                    </div>

                    <div class="hmd-flex hmd-justify-between hmd-items-center hmd-dni-xs" id="revision-operation-panel">
                        <!-- #region Compare revision dropdown menu -->
                        <div class="diff-revision-menu hmd-flex hmd-items-center">
                            <span>
                                <input type="checkbox" name="compareWithLastVersion" checked>
                            </span>
                            <span>
                                Compare with
                            </span>
                            <div class="btn-group dropup" id="diff-revision-dropdown-menu">
                                <button class="btn btn-default dropdown-toggle ui-diff-revision-menu hmd-flex hmd-items-center hmd-justify-between" type="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="true">
                                    <span>
                                        Previous version
                                    </span>
                                    <i class="fa fa-angle-down fa-12" aria-hidden="true" style="margin-left: 5px;"></i>
                                </button>
                                <ul class="dropdown-menu pull-left" aria-labelledby="diff-revision-dropdown-menu">
                                    <div class="dropdown-section">
                                        <div class="section-header">
                                            Choose a version
                                        </div>

                                        <div class="section-filter">
                                            <span>
                                                <input id="showOnlyNamedRevision" type="checkbox" name="showOnlyNamedRevision">
                                                <label for="showOnlyNamedRevision">
                                                    Only named versions
                                                </label>
                                            </span>
                                        </div>
                                    </div>
                                    <div class="revision-list-container d-flex hmd-justify-center">
                                        <div class="revision-list-inner">
                                        </div>
                                        <div class="empty-revision-list">
                                            <div class="search-icon">
                                                <img src="https://hackmd.io/empty-search-result.svg" alt="No search result">
                                            </div>
                                            Version not found
                                        </div>
                                    </div>
                                </ul>
                            </div>
                            <span>
                                
                            </span>
                        </div>
                        <!-- #endregion -->

                        <div>
                            <button type="button" class="btn btn-danger btn-outline ui-revisionModalRevert" style="margin-right: 10px; display: none;">Revert</button>
                            <button type="button" class="btn btn-primary btn-outline ui-revisionModalDownload">Download</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- message modal -->
<div class="modal fade message-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-sm">
      <div class="modal-content">
          <div class="modal-header">
              <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
              </button>
              <h4 class="modal-title" id="myModalLabel"></h4>
          </div>
          <div class="modal-body" style="color:black;">
              <h5 style="font-weight: 500; font-size: 14px; text-align: left;"></h5>
              <a target="_blank" style="word-break: break-all;" rel="noopener"></a>
          </div>
          <div class="modal-footer">
              <button type="button" class="btn btn-default" data-dismiss="modal">OK</button>
          </div>
      </div>
  </div>
</div>
<!-- feedback modal -->
<div class="modal fade feedback-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
  <div class='modal-dialog modal-lg' role='document'>
    <div class='modal-content'>
      <div class='modal-header' style="padding: 8px 15px; font-weight: 700">
        <button type='button' class='close' aria-label='Close' style="font-size: 26px; margin-top: -1px;" data-dismiss="modal">
          <span aria-hidden='true'>&times;</span>
        </button>
        <h4 class='modal-title'>Feedback</h4>
      </div>
      <div class='modal-body' style="text-align: left;">
        <div class='alert alert-danger' style="display: none;">
          <i class='fa fa-exclamation-triangle' aria-hidden='true' style="margin-right: 5px"></i>
          Submission failed, please try again
        </div>
        <h3 style="margin-top:5px">Thanks for your support.</h3>
        <p>On a scale of 0-10, how likely is it that you would recommend HackMD to your friends, family or business associates?</p>
        <div class="rating-group" style="margin-top: 15px; margin-bottom: 30px;"></div>
        <p style="font-size:16px">Please give us some advice and help us improve HackMD.</p>
        <form role='form' data-toggle='validator'>
          <div class='form-group' style="margin-bottom: 10px;">
            <textarea name='feedback' class='form-control' placeholder="Enter your feedback" rows="3" style="resize: none;" required></textarea>
          </div>
          <div class='checkbox' style="font-size:16px">
            <label>
              <input name='engage' type='checkbox' checked />
              I’m willing to participate in user experience research or beta testing so HackMD could build things I want.
            </label>
          </div>
          <div class='form-group hmd-flex hmd-items-center' style="font-size: 16px; padding-left: 20px;">
            <label style="font-weight: normal;">My Email:</label>
            &nbsp;
            <div class='hmd-flex-auto hmd-pr-0'>
              <input type='email' name='email' class='form-control col-sm-9' aria-describedby='helpId' placeholder="Email address" required />
            </div>
          </div>
          <div class='modal-footer' style="padding: 15px 0; border: none;">
            <button type='button' class='btn btn-default' data-dismiss="modal">Cancel</button>
            <button type='submit' class='btn btn-primary ui-feedback-submit'>Submit</button>
          </div>
        </form>
      </div>
    </div>
  </div>
</div>

<!-- feedback success modal -->
<div class="modal fade feedback-success-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
  <div class='modal-dialog modal-sm' role='document'>
    <div class='modal-content'>
      <div class='modal-body' style="padding: 50px 20px; text-align: center;">
        <img src="/images/feedback.svg" width="85" height="95" />
        <h4>Thanks for your feedback</h4>
      </div>
    </div>
  </div>
</div>

<!-- action modal -->
<div class="modal fade action-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                <h4 class="modal-title" id="myModalLabel"></h4>
            </div>
            <div class="modal-body" style="color:black;">
                <p></p>
            </div>
            <div class="hmd-flex modal-footer">
                <button type="button" class="btn btn-default cancel hmd-flex-one" data-dismiss="modal">Cancel</button>
                <button type="button" class="btn btn-primary yes hmd-flex-one" data-dismiss="modal">OK</button>
            </div>
        </div>
    </div>
</div>

<!-- action modal -->
<div class="modal fade remove-revision-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">Remove version name</h4>
            </div>
            <div class="modal-body" style="color:black;">
                <h5>Do you want to remove this version name and description?</h5>
            </div>
            <div class="hmd-flex modal-footer">
                <button type="button" class="btn btn-default hmd-flex-one" data-dismiss="modal">Cancel</button>
                <button type="button" class="btn btn-danger hmd-flex-one" data-dismiss="modal">OK</button>
            </div>
        </div>
    </div>
</div>

<!-- transfer modal -->
<div class="modal fade transfer-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">Transfer ownership</h4>
            </div>
            <div class="modal-body" style="color:black; overflow: inherit; padding-bottom: 0;">
                Transfer to

                <div class="form-group" style="margin-bottom: 0;">
                    <div class="radio">
                        <label>
                            <input type="radio" name="transfer-type" value="team" required checked="checked">
                            <span>
                                Transfer to team you&#39;ve joined
                            </span>
                        </label>
                    </div>

                    <div class="dropdown btn-group ui-transfer-modal-team-dropdown" style="width: 100%; margin-bottom: 10px;">
                        <button class="btn btn-default hmd-text-left dropdown-toggle" type="button" style="width: 100%; height: 40px;" id="dropdownMenuTransferToTeam" data-toggle="dropdown" aria-haspopup="true" aria-expanded="true">
                            <span class="ui-transfer-modal-team-label" style="line-height: 18px;">
                                No teams available
                            </span>

                            <span class="caret" style="position: absolute; top: 17px; right: 10px;"></span>
                        </button>

                        <ul class="dropdown-menu" aria-labelledby="dropdownMenuTransferToTeam" style="width: 100%;"></ul>
                    </div>
                    <div class="public-team-notice" style="font-size: 12px; color: #C9302C; display: none;">
                        Warning: <span class="team-name"></span> is a <b>public team</b>. If you transfer note to this team, <b>everyone on the web can find and read this note.</b>
                    </div>

                    <div class="radio transfer-team-radio">
                        <label>
                            <input type="radio" name="transfer-type" value="member" required>
                            <span>
                                Transfer to current team member
                            </span>
                        </label>
                    </div>

                    <div class="dropdown btn-group ui-transfer-modal-team-member-dropdown" style="width: 100%; margin-bottom: 10px;">
                        <button class="btn btn-default hmd-text-left dropdown-toggle" type="button" style="width: 100%; height: 40px;" id="dropdownMenuTransferToTeamMember" data-toggle="dropdown" aria-haspopup="true" aria-expanded="true">
                            <span class="ui-transfer-modal-team-member-label" style="line-height: 18px;">
                                No team members available
                            </span>

                            <span class="caret" style="position: absolute; top: 17px; right: 10px;"></span>
                        </button>

                        <ul class="dropdown-menu" aria-labelledby="dropdownMenuTransferToTeamMember" style="width: 100%;"></ul>
                    </div>
                </div>

                <div class="error text-danger" style="display: none; margin-top: 10px; color: red;"></div>
            </div>

            <div class="modal-footer">
                <button type="button" class="btn btn-default" data-dismiss="modal">
                    Cancel
                </button>

                <button type="button" class="btn btn-danger ui-transfer-modal-confirm" disabled>
                    Transfer
                </button>
            </div>
        </div>
    </div>
</div>


<!-- github signin modal -->
<div class="modal fade github-signin-modal hmd-text-left" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">Link with GitHub</h4>
            </div>
            <div class="modal-body" style="color:black;">
                <h4 style="border-bottom: 2px solid #cccccc; padding-bottom: 15px; margin: 5px 0px 30px 0px">Please authorize HackMD on GitHub</h4>
                <p style="margin-bottom: 15px;">
                    
                        Please sign in to GitHub and install the HackMD app on your GitHub repo.
                    
                    <a href="https://hackmd.io/c/tutorials/%2Fs%2Flink-with-github" target="_blank">Learn more</a>
                </p>


                
                    <a href=https://github.com/login/oauth/authorize?client_id=Iv1.dce7f04830297ce5&amp;redirect_uri=https%3A%2F%2Fhackmd.io%2Fapi%2Fgithub%2Fsync%2Fcallback data-href="https://github.com/apps/hackmd-hub/installations/new" type="button" class="btn btn-primary ui-github-signin-button" style="margin-bottom: 30px"><i class="fa fa-github fa-fw"></i>&nbsp;Sign in to GitHub</a>
                

                
                    <p><small style="color: #888888">HackMD links with GitHub through a GitHub App. You can choose which repo to install our App.</small></p>
                
            </div>
        </div>
    </div>
</div>

<!-- github sync modal -->
<div class="modal fade github-sync-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>

                <h4 class="modal-title" id="myModalLabel">
                    <span class="ui-push-title">Push the note to GitHub</span>
                    <span class="ui-push-only-title">Push to GitHub</span>
                    <span class="ui-pull-title">Pull a file from GitHub</span>
                </h4>
            </div>
            <div class="modal-body">
                <div class="alert alert-danger" style="display: none;">
                    <i class="fa fa-times ui-close-alert" aria-hidden="true" style="float: right;"></i>
                    <span class="ui-github-sync-alert-msg"></span>
                    &nbsp;
                    
                        <a href=https://github.com/login/oauth/authorize?client_id=Iv1.dce7f04830297ce5&amp;redirect_uri=https%3A%2F%2Fhackmd.io%2Fapi%2Fgithub%2Fsync%2Fcallback target="_blank" class="ui-github-sync-authorize-again" style="display: none;">Authorize again</a>
                    
                </div>

                <div class="github-path-container hmd-flex hmd-items-center form-group">
                    <i class="fa fa-github"></i>&nbsp;
                    <span class="github-path" title="" data-toggle="tooltip" data-placement="bottom" data-offset="0,5" data-original-title=""></span>
                </div>

                <div class="choose-repo-file-section">
                    <h4 class="github-section-title">Choose which file to push to</h4>
                    <div style="display: flex; margin-bottom: 0px; align-items: center;">
                        <div style="flex: 1">Select repo
                            
                                <i class="fa fa-question-circle fa-12 tooltip-align-left ui-second-menu-tooltip" style="color: #CDCDCD"
                                title="Select from repos that had HackMD’s GitHub App installed"
                                data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i>
                            
                        </div>
                        <div style="flex: 2; max-width: calc(100% * 2 / 3);">
                            <select id="github-repos" placeholder="Select a repo"></select>
                        </div>
                    </div>

                    <div style="margin: 5px 0px 30px 0px; text-align: right;">
                        <a href="#" class="ui-refresh-github-sync-repos" style="margin-right: 10px;">Refresh<i class="fa fa-rotate-left fa-12" style="margin-left: 3px;"></i></a>
                        
                            <a href="https://github.com/apps/hackmd-hub/installations/new" target="_blank">Authorize more repos<i class="fa fa-angle-right fa-12" style="margin-left: 3px;"></i></a>
                        
                    </div>

                    <div style="display: flex; margin-bottom: 30px; align-items: center;">
                        <div style="flex: 1">Select branch
                            <i class="fa fa-question-circle fa-12 tooltip-align-left ui-second-menu-tooltip" style="color: #CDCDCD"
                            title="You can select the target branch every time you push or pull"
                            data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i>
                        </div>
                        <div style="flex: 2; max-width: calc(100% * 2 / 3);">
                            <select id="github-branches"></select>
                        </div>
                    </div>

                    <div style="display: flex; margin-bottom: 30px; align-items: center;">
                        <div style="flex: 1">Select file</div>
                        <div style="flex: 2; max-width: calc(100% * 2 / 3);">
                            <select id="github-files"></select>
                        </div>
                    </div>
                </div>

                <div class="choose-branch-section">
                    <div style="display: flex; margin-bottom: 30px; align-items: center;">
                        <div style="flex: 1">Select branch
                            <i class="fa fa-question-circle fa-12 tooltip-align-left ui-second-menu-tooltip" style="color: #CDCDCD"
                            title="You can select the target branch every time you push or pull"
                            data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i>
                        </div>
                        <div style="flex: 2; max-width: calc(100% * 2 / 3);">
                            <select id="github-push-branches" placeholder="Select or create a branch"></select>
                        </div>
                    </div>
                </div>

                <div class="relative flex flex-col ui-push-mode" style="display: none">
                    <div class="flex">
                        <div style="flex: 1;" class="pt-2.5">Choose version(s) to push
                            <i class="fa fa-question-circle fa-12 tooltip-align-left ui-second-menu-tooltip" style="color: #CDCDCD"
                                title="HackMD will concatenate the version name and description as its commit message"
                                data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i>
                        </div>
                        <div style="flex: 2; max-width: calc(100% * 2 / 3); margin-bottom: 35px;" id="version-select-tabs">
                            <ul class="nav nav-tabs" role="tablist" style="margin-bottom: 20px;">
                                <li role="presentation" class="ui-create-new-version active">
                                    <a href="#create-new-version" aria-controls="create-new-version" role="tab" data-toggle="tab" style="height: 100%;">
                                        <i class="fa fa-check visibility-on-active" aria-hidden="true" style="margin-right:  3px;"></i>Save a new version and push</a>
                                </li>
                                <li role="presentation" class="ui-select-from-existing-version">
                                    <a href="#select-from-existing-version" aria-controls="select-from-existing-version" role="tab" data-toggle="tab" style="height: 100%;">
                                        <i class="fa fa-check visibility-on-active" aria-hidden="true" style="margin-right:  3px;"></i>Choose from existing versions</a>
                                </li>
                            </ul>
                            <!-- Tab panes -->
                            <div class="tab-content">
                                <div role="tabpanel" class="tab-pane active" id="create-new-version">
                                    <form role="form" class="form create-version-form">
    <div class="form-group">
        <div class="ui-revision-timestamp">
            <i class="fa fa-clock-o fa-fw"></i>
            <span></span>
        </div>
    </div>

    <div class="form-group">
        <label for="">Name</label>
        <input type="text" class="form-control" maxlength="80">
    </div>

    <div class="form-group">
        <label for="">Description</label>
        <textarea class="form-control" style="width: 100%; height: 76px; resize: vertical;" placeholder="Please describe the version (optional)" maxlength="500"></textarea>
    </div>

    <input type="text" required name="canPushHiddenField" class="hidden">

    <div class="github-sync-button-container">
        <button type="button" class="btn btn-default" data-dismiss="modal" style="margin-right: 5px;">Cancel</button>
        <button type="submit" class="btn btn-primary ui-github-sync-button">Push</button>
    </div>
</form>

                                </div>

                                <div role="tabpanel" class="tab-pane" id="select-from-existing-version">
                                    <div class="version-list hmd-flex hmd-flex-column">
                                    </div>

                                    <div class="github-sync-button-container">
                                        <button type="button" class="btn btn-default" data-dismiss="modal" style="margin-right: 5px;">Cancel</button>
                                        <button type="button" class="btn btn-primary ui-github-sync-button" disabled>Push</button>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="flex items-start mb-11 github-available-quota-section" style="display: none;">
                        <div style="flex: 1">
                            Available push count
                        </div>

                        <div style="flex: 2; word-break: break-all">
                            <div class="ui-github-synced-push-count mb-2.5"></div>
                            <div class="text-gray-600" style="font-size: 12px;">
                                <span class="github-synced-push-info"></span>
                                <br>
                                <a target="_blank" href="/?nav=billing" class="github-push-quota-upgrade-now">
                                    Upgrade
                                    <i class="fa fa-fw fa-angle-right" aria-hidden="true"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="ui-pull-mode" style="text-align: right">
                    <button type="button" class="btn btn-default" data-dismiss="modal" style="margin-right: 5px;">Cancel</button>
                    <button type="button" class="btn btn-primary ui-github-sync-button" disabled>Pull</button>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- github sync pull modal -->
<div class="modal fade" id="githubSyncPullModal" tabindex="-1" role="dialog" aria-labelledby="mySmallModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-lg" style="width: calc(100vw - 20px); max-width: 1200px; height: calc(100vh - 100px);">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                </button>
                <h4 class="modal-title" id="mySmallModalLabel">Pull from GitHub</h4>
            </div>
            <div class="container-fluid modal-body hmd-pa-0 hmd-flex hmd-flex-column" style="max-height: calc(100vh - 100px); height: calc(100vh - 100px); overflow: hidden;">
                <div class="github-sync-pull-error hmd-flex hmd-flex-column hmd-items-center hmd-justify-center" style="display: none;">
                    <h3></h3>
                </div>

                <div class="github-path-container hmd-flex hmd-items-center">
                    <i class="fa fa-github"></i>&nbsp;
                    <span class="github-path" title="" data-toggle="tooltip" data-placement="bottom" data-offset="0,5" data-original-title=""></span>
                </div>

                <div class="github-pull-form">
                    <form class="form" id="github-sync-pull-form">
                        <div class="form-group hmd-flex hmd-justify-between hmd-items-center">
                            <label class="hmd-flex-shrink-0 hmd-mr-1">Pull from branch</label>

                            <select id="github-pull-branches" placeholder="Select a branch"></select>

                            <div class="pull-actions hmd-flex-shrink-0 hmd-ml-1">
                                <button type="button" data-dismiss="modal" class="btn btn-default" style="margin-right: 10px;">Cancel</button>

                                <button type="submit" class="btn btn-primary">
                                    Apply all changes
                                </button>
                            </div>
                        </div>

                        <div class="pull-view-indicator hmd-flex">
                            <div class="hmd-flex-one github">
                                <small>File from GitHub</small>
                            </div>
                            <div class="hmd-flex-one source">
                                <small>File from HackMD</small>
                            </div>
                        </div>
                    </form>

                </div>
                <div class="pull-editor-container hmd-flex hmd-flex-column">
                    <div id="github-sync-pull-editor" class="hmd-flex-one"></div>
                    <div class="ui-spinner unselectable hidden-print"></div>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- github synced settings modal -->
<div class="modal fade github-synced-settings-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
    <div class="modal-dialog modal-lg">
        <div class="modal-content">
            <div class="modal-header">
                <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
                </button>
                <h4 class="modal-title" id="myModalLabel">GitHub Link Settings</h4>
            </div>

            <div class="modal-body" style="color:black;">
                <h4 style="border-bottom: 2px solid #cccccc; padding-bottom: 15px; margin: 5px 0px 30px 0px">File linked</h4>

                <div style="display: flex; margin-bottom: 30px; align-items: center;">
                    <div style="flex: 1">Linked by</div>
                    <div style="flex: 2; text-overflow: ellipsis; overflow: hidden; white-space: nowrap;" class="ui-github-synced-user">
                        <a target="_blank" class="ui-github-synced-user-photo"><img class="ui-avatar" width="30" height="30" style="border-radius: 100%; margin-right: 10px;"  src=""></a>
                        <a target="_blank" class="ui-github-synced-user-name"></a>
                    </div>
                </div>

                <div style="display: flex; margin-bottom: 30px; align-items: center;">
                    <div style="flex: 1">File path</div>
                    <div style="flex: 2; word-break: break-all" class="ui-github-synced-filepath" style="word-break: break-all;"></div>
                </div>

                <div style="display: flex; margin-bottom: 30px; align-items: center;">
                    <div style="flex: 1">Last synced branch
                        <i class="fa fa-question-circle fa-12 tooltip-align-left ui-second-menu-tooltip" style="color: #CDCDCD"
                        title="You can select the target branch every time you push or pull"
                        data-toggle="tooltip" data-placement="bottom" data-offset="0,5"></i>
                    </div>
                    <div style="flex: 2; word-break: break-all" class="ui-github-synced-recent-branch"></div>
                </div>

                <div class="flex mb-7.5 items-start github-available-quota-section" style="display: none;">
                    <div style="flex: 1">
                        Available push count
                    </div>

                    <div style="flex: 2; word-break: break-all">
                        <div class="ui-github-synced-push-count mb-2.5"></div>
                        <div class="text-gray-600" style="font-size: 12px;">
                            <span class="github-synced-push-info"></span>
                            <br>
                            <a target="_blank" href="/?nav=billing" class="github-setting-quota-upgrade-now">
                                Upgrade
                                <i class="fa fa-fw fa-angle-right" aria-hidden="true"></i>
                            </a>
                        </div>
                    </div>
                </div>


                <h4 style="border-bottom: 2px solid #cccccc; padding-bottom: 15px; margin: 5px 0px 30px 0px">Danger Zone</h4>

                <div style="display: flex; margin-bottom: 5px;">
                    <div style="flex: 1; margin-top: 7px;">Unlink</div>
                    <div style="flex: 2">
                        <button type="button" class="btn btn-danger btn-outline ui-github-cancel-sync-button">Unlink</button>
                        <div style="margin-top: 15px; font-size: 12px; color: #888;">You will no longer receive notification when GitHub file changes after unlink.</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- loading modal -->
<div class="modal fade loading-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true" data-backdrop="static" data-keyboard="false">
    <div class="modal-dialog modal-sm">
        <div class="modal-content">
            <div class="modal-body">
                <div>
                    <div class="ui-loading" style="height: 139px; width: 139px; position: relative; margin: 0 auto; top: 10px;"></div>
                    <p class="ui-loading-msg" style="text-align: center; margin-bottom: 35px; position: relative; top: 15px;">Syncing</p>
                </div>
            </div>
        </div>
    </div>
</div>

<!-- push failed modal -->
<div class="modal fade push-failed-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-lg" style="max-width: 400px; margin: auto;">
      <div class="modal-content">
          <div class="modal-header">
              <button type="button" class="close" data-dismiss="modal" aria-label="Close"><span aria-hidden="true">&times;</span>
              </button>
              <h4 class="modal-title" id="myModalLabel">Push failed</h4>
          </div>
          <div class="modal-body" style="text-align: center;">
              <img src="https://hackmd.io/push-xx.svg" width="85px" height="96px" style="margin-top: 5px;">
              <div style="font-size: 16px; text-align: left; margin-top: 20px; word-break: break-all;"></div>
          </div>
          <div class="modal-footer" style="border: none; padding-top: 5px;">
              <button type="button" class="btn btn-default" data-dismiss="modal">Cancel</button>
              <button type="button" class="btn btn-primary" data-dismiss="modal">Try again</button>
          </div>
      </div>
  </div>
</div>
<!-- push success modal -->
<div class="modal fade push-success-modal" tabindex="-1" role="dialog" aria-labelledby="myModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-lg" style="max-width: 400px; margin: auto;">
      <div class="modal-content">
          <div class="modal-body" style="text-align: center; margin: 35px 0px;">
                <img src="https://hackmd.io/push-done.svg" width="85px" height="94.7px">
                <div style="font-size: 18px; margin-top: 20px;">
                    Push successfully
                </div>
          </div>
      </div>
  </div>
</div>

<div class="publish-limiter"></div>

    
    
    <script src="https://www.googletagmanager.com/gtag/js?id=UA-60728495-1"></script>
    <script nonce="7e4e2a18-0f6b-48a9-9017-39e491ea067a">
        window.dataLayer = window.dataLayer || [];
        function gtag(){dataLayer.push(arguments);}
        gtag('js', new Date());
        let userid = (document.cookie.match('(^|; )userid=([^;]*)')||0)[2];
        gtag('config', 'UA-60728495-1', {'user_id': userid});
        
    </script>



<script src="https://browser.sentry-cdn.com/5.15.5/bundle.min.js" crossorigin="anonymous"></script>
<script nonce="7e4e2a18-0f6b-48a9-9017-39e491ea067a">Sentry.init({ dsn: 'https://73410f1915d84abc8b2dd1f1aabd1c82@sentry.hackmd.dev/4', environment: 'production', integrations: function (intrus) { return intrus.filter(function (itr) { return itr.name !== 'TryCatch' }) } });</script>



<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-KLW9Z3"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<!-- End Google Tag Manager (noscript) -->


<script src="https://hackmd.io/api/i18n.js"></script>
 <script src="https://assets.hackmd.io/build/font-vendor.1b4c8aac415c85d7f33b.js" defer="defer"></script><script src="https://assets.hackmd.io/build/common-vendor.9ad4eb1bd27d1eb68036.js" defer="defer"></script><script src="https://assets.hackmd.io/build/index-vendor.a885ce2abbc6c2eb626e.js" defer="defer"></script><script src="https://assets.hackmd.io/build/index-common.d52cf049ff9ac905d29e.js" defer="defer"></script><script src="https://assets.hackmd.io/build/index.c283d7e9929162d986c8.js" defer="defer"></script>



</body>

</html>
