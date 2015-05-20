# CommonComponents(web开发组件)


[![npm version](https://badge.fury.io/js/engine.io.svg)](http://badge.fury.io/js/engine.io)
[![Build Status](https://travis-ci.org/chinakids/CommonComponents.svg?branch=master)](https://travis-ci.org/chinakids/CommonComponents)
[![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)

开发用公共组件库

###1.安装

Install: `bower install https://github.com/chinakids/CommonComponents.git --save`


###2.Environment（浏览器环境检测）

src:`src/environment/environment.js`

dest:`src/environment/environment.min.js`


使用：

	window.environment

结果：

	{
		base: {
			Objectbrowserlanguage: undefined,
			codename: "Mozilla",
			cookieenabled: true,
			cpuclass: undefined,
			minorversion: undefined,
			name: "Netscape",
			online: true,
			platform: "MacIntel",
			systemlanguage: undefined,
			uaheader: "Mozilla/5.0 (Macintosh; Intel Mac OS X 10_10_4) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2272.76 Safari/537.36",
			userlanguage: undefined,
			version: "5.0 (Macintosh; Intel Mac OS X 10_10_4) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/41.0.2272.76 Safari/537.36"
			}
		info:{
			Objectbrowser: "Chrome",
			browserversion: "41.0.2272.76",
			device: "pc",
			engine: "AppleWebKit",
			engineversion: "537.36",
			platform: "MacIntel",
			project: "web",
			system: "iOS",
			systemversion: ""
			}
	}