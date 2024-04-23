webpackJsonp([2, 20], {
    "0": function(e, n, t) {
        var i = t(99039043)
          , o = t(1)
          , s = t(12)
          , a = t(4)
          , r = t(19)
          , c = t(112745811)
          , l = t(72876602);
        r.set("type", c.GAME),
        l.setType(c.GAME);
        var u = function() {
            i.call(this),
            this.orderHeight = 164
        };
        a.inherits(u, i),
        u.prototype.loadVMConfig = function() {
            var e = u._super.prototype.loadVMConfig.call(this);
            return o.mix({}, e, {
                "$id": "root"
            })
        }
        ;
        var d = new u;
        d.render();
        var p = {
            "order": t(67505057)(d),
            "subChannel": t(50736890)(d),
            "result": t(122487386)(d)
        }
          , h = function(e, n) {
            return "result" == e && (n.ResultClass = t(75846869)),
            n
        };
        for (var f in p)
            !function(e) {
                s.add(e, function(e, n, t) {
                    l.setPage(e),
                    d.currentPage = e,
                    i.loadVM(p[e], n, h(e, t)),
                    d.changePage(e)
                })
            }(f);
        o.ready(function() {
            d.run()
        }),
        window.gameTimeEnd = +new Date
    },
    "1": function(e, n, t) {
        e.exports = t(2)(80667616)
    },
    "2": function(e, n) {
        e.exports = vendor_lib
    },
    "3": function(e, n, t) {
        e.exports = t(2)(78057199)
    },
    "4": function(e, n, t) {
        e.exports = t(2)(88981800)
    },
    "5": function(e, n, t) {
        e.exports = t(2)(115781265)
    },
    "7": function(e, n, t) {
        e.exports = t(8)(78082052)
    },
    "8": function(e, n) {
        e.exports = cgiVendor_lib
    },
    "9": function(e, n, t) {
        e.exports = t(2)(113677689)
    },
    "10": function(e, n, t) {
        e.exports = t(2)(99817079)
    },
    "11": function(e, n, t) {
        e.exports = t(2)(56034868)
    },
    "12": function(e, n, t) {
        e.exports = t(2)(91187074)
    },
    "13": function(e, n, t) {
        e.exports = t(2)(70901372)
    },
    "14": function(e, n, t) {
        e.exports = t(2)(43759118)
    },
    "15": function(e, n, t) {
        e.exports = t(2)(99505187)
    },
    "16": function(e, n, t) {
        e.exports = t(2)(89045516)
    },
    "17": function(e, n, t) {
        e.exports = t(2)(74520267)
    },
    "18": function(e, n, t) {
        e.exports = t(2)(85151090)
    },
    "19": function(e, n, t) {
        e.exports = t(2)(52137608)
    },
    "20": function(e, n, t) {
        e.exports = t(2)(100152084)
    },
    "21": function(e, n, t) {
        e.exports = t(2)(98480501)
    },
    "22": function(e, n, t) {
        e.exports = t(2)(43866881)
    },
    "23": function(e, n, t) {
        function i(e) {
            return t(o(e))
        }
        function o(e) {
            return s[e] || function() {
                throw new Error("Cannot find module '" + e + "'.")
            }()
        }
        var s = {
            "./abstractChannel.js": 100835382,
            "./bank.js": 108535814,
            "./cft_b2b.js": 48800002,
            "./friendpay.js": 104708884,
            "./hfpay.js": 50980797,
            "./kj.js": 123135374,
            "./mcard.js": 111578709,
            "./qb.js": 79091806,
            "./qcard.js": 43820868,
            "./qqwallet.js": 89561790,
            "./remitpay.js": 54142212,
            "./wechat.js": 79488087
        };
        i.keys = function() {
            return Object.keys(s)
        }
        ,
        i.resolve = o,
        e.exports = i,
        i.id = 23
    },
    "24": function(e, n, t) {
        e.exports = t(2)(98911480)
    },
    "25": function(e, n, t) {
        e.exports = t(2)(55191419)
    },
    "43511251": function(e, n) {
        e.exports = function(e) {
            var n = !0
              , t = "";
            return "undefined" == typeof e.appid && (n = !1,
            t = "appid should not empty"),
            {
                "isPass": n,
                "errMsg": t
            }
        }
    },
    "43820868": function(e, n, t) {
        var i = t(4)
          , o = t(1);
        t(66520979),
        t(89500152);
        var s = t(117821206)
          , a = t(112745811)
          , r = (t(10),
        t(70508452))
          , c = t(43847285)
          , l = t(100835382)
          , u = t(66520979)
          , d = t(84811753)
          , p = t(75748174)
          , h = function(e, n, t) {
            l.apply(this, arguments),
            this.verifyCode = null,
            this.numVm = null,
            this.passVm = null,
            this.initVm(),
            this.qcardVm.amount = this.store.getAmount()
        };
        i.inherits(h, l),
        h.prototype.onChange = function() {
            if (this.qcardVm) {
                this.qcardVm.hideBalanceNotEnough();
                var e = this.store.getPrice().price;
                e != this.qcardVm.price,
                this.qcardVm.amount = this.store.getAmount(),
                this.qcardVm.price = e
            }
        }
        ,
        i.fn.extend(h.prototype, {
            "lock": function() {
                l.prototype.lock.call(this),
                this.qcardVm.disableSubmit = !0,
                this.numVm.disable(),
                this.passVm.disable()
            },
            "unlock": function() {
                l.prototype.unlock.call(this),
                this.qcardVm.disableSubmit = !1,
                this.numVm.enable(),
                this.passVm.enable()
            },
            "onDestroy": function() {
                l.prototype.removeListener.call(this),
                this.verifyCode && !this.verifyCode.isClose() && this.verifyCode.close(),
                l.prototype.destroy.call(this)
            },
            "initVmConfig": function() {
                var e = this;
                return this.vmConfig = i.fn.extend({
                    "$id": "qcard-controller-" + function() {
                        return e.mode == l.MODE.COMPLETE ? "complete" : e.mode == l.MODE.SIMPLE ? "simple" : void 0
                    }(),
                    "$skipArray": [],
                    "showVerify": !1,
                    "verifyUrl": "",
                    "amount": this.store.getAmount(),
                    "cardNum": "",
                    "passNum": "",
                    "cardNumMsg": "",
                    "cardPassMsg": "",
                    "cardNumValidatePass": !1,
                    "cardPassValidatePass": !1,
                    "price": this.store.getPrice().price,
                    "qcardBalanceNotEnough": !1,
                    "showBalance": !1,
                    "balance": null,
                    "disableSubmit": !1,
                    "$computed": {
                        "isSimpleMode": {
                            "set": o.noop,
                            "get": function() {
                                return e.mode == l.MODE.SIMPLE
                            }
                        },
                        "isCompleteMode": {
                            "set": o.noop,
                            "get": function() {
                                return e.mode == l.MODE.COMPLETE
                            }
                        }
                    },
                    "getNumVm": function(n) {
                        e.numVm = n
                    },
                    "getPassVm": function(n) {
                        e.passVm = n
                    },
                    "cardNumberConfig": {
                        "filters": ["number|*"],
                        "validations": [{
                            "name": "maxlen",
                            "params": [10],
                            "msg": "卡号为9位或10位"
                        }, {
                            "name": "minlen",
                            "params": [9],
                            "msg": "卡号为9位或10位"
                        }],
                        "maskcfg": u.masks.space
                    },
                    "cardPassConfig": {
                        "filters": ["number|*"],
                        "validations": [{
                            "name": "len",
                            "params": [12],
                            "msg": "QQ卡密码为12位"
                        }],
                        "maskcfg": u.masks.space
                    },
                    "pay": function(n) {
                        if (n.stopPropagation(),
                        n.preventDefault(),
                        !e.isLocked() && 0 != e.store.getAmount()) {
                            if (e.store.isInterfaceDisabled())
                                return void e.store.emit("channelDataChange", new d(p));
                            if (e.qcardVm.isCompleteMode) {
                                if (e.qcardVm.cardNum = e.numVm.getValue(),
                                e.qcardVm.passNum = e.passVm.getValue(),
                                !e.qcardVm.cardNumValidatePass || !e.qcardVm.cardPassValidatePass)
                                    return;
                                if (e.verifyCode && !e.verifyCode.isClose())
                                    return void e.verifyCode.verifyDone();
                                e.buy()
                            } else
                                e.qcardVm.isSimpleMode && e.store.changePage("subPage", {
                                    "channelObj": e.channelObj,
                                    "mode": l.MODE.COMPLETE
                                })
                        }
                    },
                    "onCardNumValidate": function(n) {
                        e.qcardVm.cardNumMsg = n.validation.msg,
                        e.qcardVm.cardNumValidatePass = n.passed
                    },
                    "onCardPassValidate": function(n) {
                        e.qcardVm.cardPassMsg = n.validation.msg,
                        e.qcardVm.cardPassValidatePass = n.passed
                    },
                    "onQcardNumChange": function(n) {
                        e.qcardVm.cardNumMsg = "",
                        e.qcardVm.cardNumValidatePass = !0
                    },
                    "onQcardPassChange": function(n) {
                        e.qcardVm.cardPassMsg = "",
                        e.qcardVm.cardPassValidatePass = !0
                    },
                    "showBalanceNotEnough": function() {
                        e.qcardVm.qcardBalanceNotEnough = !0
                    },
                    "hideBalanceNotEnough": function() {
                        e.qcardVm.qcardBalanceNotEnough = !1,
                        e.qcardVm.balance = null
                    },
                    "queryBalance": function() {
                        e.qcardVm.cardNum = e.numVm.getValue(),
                        e.qcardVm.passNum = e.passVm.getValue(),
                        e.qcardVm.cardNumValidatePass && e.qcardVm.cardPassValidatePass && (e.reportUser("surplus.click"),
                        e.store.cgi.mobileGetBalance({
                            "cmd": "1"
                        }, function(n) {
                            ~~n.ret || (e.qcardVm.showBalance = !0,
                            e.qcardVm.balance = i.math.div(~~n.balance, 100))
                        }))
                    }
                }, this.getTermsVmConfig()),
                this.vmConfig
            },
            "buy": function(e) {
                if (e = e || {},
                !this.isLocked()) {
                    this.lock(),
                    this.qcardVm.hideBalanceNotEnough(),
                    this.showMask(),
                    this.reportUser("pay.click");
                    var n = {
                        "pay_id": this.qcardVm.cardNum,
                        "auth_key": this.qcardVm.passNum,
                        "pay_method": this.channelObj.channel
                    };
                    i.fn.extend(n, e),
                    this.store.buy(n, function(e) {
                        return this.hideMask(),
                        this.handlerBuy(e, n)
                    }
                    .bind(this))
                }
            },
            "handlerBuy": function(e, n) {
                var t, o = this, a = ~~e.ret;
                return this.verifyCode && !this.verifyCode.isClose() && (this.verifyCode.close(),
                this.verifyCode = null),
                a ? (t = new s({
                    "errCode": a,
                    "errMsg": e.msg,
                    "oriParams": n,
                    "10006": function() {
                        this.opt["10002"].apply(this, arguments),
                        o.verifyCode && o.verifyCode.setFailMsg(r.TEXT.REINPUTVERIFY)
                    },
                    "10002": function() {
                        o.verifyCode = new r({
                            "el": document.getElementById("qcardVerifyContainer"),
                            "isNested": !0,
                            "limitLen": 4,
                            "session": e.info.verifysession,
                            "verifyCodePic": e.info.verifycode ? e.info.verifycode.replace(/http\:/g, "") : "",
                            "onFullfill": function() {
                                o.unlock()
                            },
                            "onReject": function() {
                                o.unlock()
                            },
                            "onConfirm": function(e, n) {
                                var t = {};
                                i.fn.extend(t, {
                                    "verify_code": e,
                                    "verify_session": n
                                }),
                                o.buy(t)
                            },
                            "onChangeVerifyCode": function(e) {
                                o.store.getCgi().mobileGetImage({
                                    "type": "url",
                                    "pay_method": "qqcard"
                                }, function(n) {
                                    e(~~n.ret ? !1 : {
                                        "url": n.url ? n.url.replace(/http\:/g, "") : "",
                                        "verifySession": n.verify_session
                                    })
                                })
                            },
                            "onDestroy": function() {
                                o.unlock()
                            }
                        })
                    },
                    "1014": function() {
                        o.qcardVm.showBalanceNotEnough(),
                        o.unlock()
                    },
                    "2022": function() {
                        var n = o.store.getCgi().sessionObj.getSessionParam()
                          , t = e.info;
                        new c({
                            "url": t.verify_url,
                            "fk_info": t.fk_info,
                            "fk_amt": t.fk_amt,
                            "jiazhang_url": t.jiazhang_url,
                            "veri_url": t.veri_url,
                            "qrcode_url": t.qrcode_url,
                            "cgi": o.store.getCgi(),
                            "accountType": "wc_actoken" === n.session_type ? "wx" : "qq",
                            "onLoad": function() {
                                o.unlock()
                            },
                            "onRcRestrict": function(e, n) {
                                e = e || {},
                                o.store.rcRestrict(e, n)
                            },
                            "onVerifyDone": function(e) {
                                e = e || {},
                                o.buy(e)
                            }
                        })
                    }
                }),
                t.canHandle() ? (t.exec(),
                !0) : (o.unlock(),
                !1)) : (this.unlock(!1),
                this.store.onSuccess({
                    "portalNo": e.info.portal_serial_no
                }),
                !0)
            }
        }),
        h.prototype.initVm = function() {
            this.qcardVm = o.define(this.initVmConfig())
        }
        ,
        h.create = function(e, n, t) {
            return new h(e,n,t)
        }
        ,
        h.getTemplate = function(e) {
            return e = e || {
                "mode": l.MODE.COMPLETE
            },
            t(110138172)({
                "mode": function() {
                    return e.mode == l.MODE.COMPLETE ? "complete" : e.mode == l.MODE.SIMPLE ? "simple" : void 0
                }(),
                "type": e.type === a.QB ? t(118085477)() : void 0
            })
        }
        ,
        e.exports = h
    },
    "43847285": function(e, n, t) {
        function i() {
            var e = /Chrome\/([0-9a-z]+)/.exec(b);
            return e ? 1 * e[1] : null
        }
        var o = t(4)
          , s = t(1)
          , a = t(112211847)
          , r = t(51748615)
          , c = t(119561448)
          , l = (t(101127449),
        t(53578085))
          , u = t(83058212)
          , d = (t(66520979),
        t(11))
          , p = t(87998867)
          , h = t(100216969)
          , f = t(10)
          , m = {
            "pic": "2",
            "face": "3",
            "sms": "4",
            "identity": "9"
        }
          , g = {
            "pic": 1,
            "sms": 3,
            "url": 4,
            "token": 5,
            "face": 6,
            "identity": 7
        }
          , v = 0
          , b = navigator.userAgent
          , y = i()
          , _ = b.indexOf("MSIE") > -1 || !window.Proxy || !window.fetch || !Object.entries || y && y < 55
          , k = function(e) {
            e = e || {},
            this.opts = e,
            this.cgi = e.cgi,
            this.el = e.el || document.body,
            this.container = document.createElement("div"),
            this.controller = "riskVcode_" + v++,
            this.el.appendChild(this.container),
            this.vms = {},
            this.renderType = null,
            this.params = {},
            this.checkVerType(),
            null != this.renderType && this.init()
        };
        o.fn.extend(k.prototype, {
            "checkVerType": function() {
                if (this.opts.fk_info && o.lang.isString(this.opts.fk_info)) {
                    var e = this.opts.fk_info.replace(/,/g, "&")
                      , e = o.fn.getParams(e)
                      , n = e.veri_type
                      , t = e.auth_type;
                    n == m.pic ? this.renderType = g.pic : n == m.sms ? "1" == t || "4" == t ? this.renderType = g.sms : "2" != t && "3" != t || (this.renderType = g.url) : n == m.face ? this.renderType = g.face : n == m.identity && (this.renderType = g.identity),
                    o.fn.extend(this.params, e)
                }
                f("riskvcode.checktype", {
                    "resultinfo": {
                        "type": this.renderType
                    }
                })
            },
            "init": function() {
                switch (this.renderType) {
                case g.url:
                    this.initUrlVerify();
                    break;
                case g.pic:
                    this.initPicVerify();
                    break;
                case g.sms:
                    this.initSmsVerify();
                    break;
                case g.face:
                    this.initFaceVerify();
                    break;
                case g.identity:
                    this.initIdentityVerify()
                }
            },
            "initSmsVerify": function() {
                var e, n = this, t = "riskVcode_sms_" + v++;
                this.refVm = {},
                f("riskvcode.smsverify.begin");
                var i = this.params.verify_reasonid;
                try {
                    var c = "";
                    __midasStaticConfig_rc.sms_reason_desc.forEach(function(e) {
                        e.reasonid === i && (c = e.desc)
                    })
                } catch (l) {}
                n.params.sub_auth_type = 2;
                var u = !1;
                this.vms["smsVm"] = s.define({
                    "$id": t,
                    "$skipArray": ["phoneNoPass", "veriCodePass", "token"],
                    "token": "",
                    "mobileNo": this.params.mobile_no,
                    "url": this.params.url,
                    "toastContent": "",
                    "toastOffset": "",
                    "reasonMsg": c,
                    "phoneNoPass": !1,
                    "veriCodePass": !1,
                    "verifyCodeCountDown": "",
                    "phoneNoMsg": "",
                    "veriCodeMsg": "",
                    "isLoading": !1,
                    "phoneNoConfig": {
                        "filters": ["number|*"],
                        "maxlength": 11,
                        "validations": [{
                            "name": "minlen",
                            "params": [11],
                            "msg": "请输入正确的手机号"
                        }, {
                            "func": function(e) {
                                return e = e || "",
                                /^1.+/.test(e)
                            },
                            "params": [],
                            "msg": "手机号码非法"
                        }],
                        "value": n.opts.phoneNum || "",
                        "onInit": function(e) {
                            n.refVm["phoneNo"] = e
                        },
                        "onChange": function(e) {
                            var t = n.vms["smsVm"];
                            t.phoneNoMsg = "",
                            t.phoneNoPass = !0
                        },
                        "onValidate": function(e) {
                            e = e || {};
                            var t = n.vms["smsVm"];
                            t.phoneNoPass = e.passed,
                            t.phoneNoMsg = e.validation.msg
                        }
                    },
                    "veriCodeConfig": {
                        "filters": ["number|*"],
                        "maxlength": 8,
                        "validations": [{
                            "func": function(e) {
                                return e = e || "",
                                "" != e
                            },
                            "params": [],
                            "msg": "请输入验证码"
                        }],
                        "_disable": !0,
                        "onInit": function(e) {
                            n.refVm["veriCode"] = e
                        },
                        "onChange": function(e) {
                            var t = n.vms["smsVm"];
                            t.veriCodeMsg = "",
                            t.veriCodePass = !0
                        },
                        "onValidate": function(e) {
                            e = e || {};
                            var t = n.vms["smsVm"];
                            t.veriCodePass = e.passed,
                            t.veriCodeMsg = e.validation.msg
                        }
                    },
                    "close": function() {
                        e ? e.close() : n.close()
                    },
                    "getVerifyCode": function() {
                        var e = n.vms["smsVm"];
                        if (!e.verifyCodeCountDown) {
                            var t;
                            if (n.params.mobile_no)
                                t = n.params.mobile_no;
                            else
                                try {
                                    t = n.refVm["phoneNo"].getValue()
                                } catch (i) {}
                            if (t) {
                                n.refVm["veriCode"].enable();
                                var o = {
                                    "action": "send",
                                    "mobile": t,
                                    "flex_extend": n.params.flex_extend || "",
                                    "query_sig": n.params.query_sig || ""
                                };
                                e.isLoading = !0,
                                f("riskvcode.smsverify.sendsms"),
                                n.sendSms(o, function(t) {
                                    if (f("riskvcode.smsverify.getsms", {
                                        "resultcode": t.ret,
                                        "resultinfo": {
                                            "err_code": t.err_code || "",
                                            "msg": t.msg || ""
                                        }
                                    }),
                                    e.isLoading = !1,
                                    ~~t.ret)
                                        if (1018 == ~~t.ret)
                                            e.showToast("登录过期，请重新登录");
                                        else {
                                            var i = "系统繁忙，请稍后再试";
                                            t.msg ? i = t.msg : t.err_code && (i = i + "（" + t.err_code + "）"),
                                            e.showToast(i)
                                        }
                                    else
                                        n.verifyCodeTimer = new d.CountDown({
                                            "time": 60,
                                            "beforeCount": function() {},
                                            "counting": function(n) {
                                                e.verifyCodeCountDown = String.format("{time} S", {
                                                    "time": n
                                                })
                                            },
                                            "countEnd": function() {
                                                e.verifyCodeCountDown = ""
                                            }
                                        })
                                })
                            }
                        }
                    },
                    "showToast": function(e) {
                        if (e) {
                            var t = n.vms["smsVm"];
                            t.toastContent = e,
                            t.toastOffset = "-" + (24 + 12 * e.length) / 2 + "px",
                            setTimeout(function() {
                                t.toastContent = ""
                            }, 2e3)
                        }
                    },
                    "onConfirm": function(t) {
                        t && t.preventDefault();
                        var i;
                        i = n.params.mobile_no ? n.params.mobile_no : n.refVm["phoneNo"].getValue();
                        var o = n.refVm["veriCode"].getValue();
                        if (i && o) {
                            var s = {
                                "mobile": i,
                                "verify_code": o,
                                "flex_extend": n.params.flex_extend || "",
                                "query_sig": n.params.query_sig || ""
                            }
                              , a = n.vms["smsVm"];
                            a.isLoading = !0,
                            f("riskvcode.smsverify.confirm.begin"),
                            n.checkVerify(s, function(t) {
                                if (f("riskvcode.smsverify.checkresp", {
                                    "resultcode": t.ret,
                                    "resultinfo": {
                                        "err_code": t.err_code || "",
                                        "msg": t.msg || ""
                                    }
                                }),
                                a.isLoading = !1,
                                ~~t.ret)
                                    if (1018 == ~~t.ret)
                                        a.showToast("登录过期，请重新登录");
                                    else {
                                        var o = "系统繁忙，请稍后再试";
                                        t.msg ? o = t.msg : t.err_code && (o = o + "（" + t.err_code + "）"),
                                        a.showToast(o)
                                    }
                                else
                                    n.triggerVerifyDone({
                                        "rc_token": t["rc_token"],
                                        "mobile_no": i
                                    }, !0),
                                    e ? e.close() : n.close()
                            })
                        }
                    },
                    "onCancel": function(t) {
                        o.lang.isFunction(n.opts.onCancel) && n.opts.onCancel(),
                        f("riskvcode.smsverify.cancel"),
                        e ? e.close() : n.close()
                    },
                    "onSwitch": function(t) {
                        t && t.preventDefault(),
                        u = !0,
                        e && e.close(),
                        n.params.sub_auth_type = 1,
                        n.params.auth_type = 2,
                        n.renderType = g.url,
                        n.initUrlVerify()
                    }
                }),
                r.create({
                    "size": {
                        "w": 348,
                        "h": 292
                    },
                    "title": "短信验证",
                    "hideHeader": !0,
                    "onReady": function(t) {
                        o.lang.isFunction(n.opts.onLoad) && n.opts.onLoad(),
                        e = t,
                        s.scan(document.getElementById(t.getDisplayHtmlId()), n.vms["smsVm"]),
                        f("riskvcode.smsverify.dialog.show")
                    },
                    "maskConfig": {
                        "onMaskClick": o.fn.emptyFunc
                    },
                    "onClose": function() {
                        u || n.close()
                    },
                    "displayHtml": a({
                        "id": t
                    })
                })
            },
            "initPicVerify": function() {
                var e = this
                  , n = "3" == this.params.auth_type ? "2083754301" : "2000000034";
                f("riskvcode.picverify.begin"),
                new Promise(function(e) {
                    "function" == typeof window.TencentCaptcha ? e(!0) : s.getScript("https://ssl.captcha.qq.com/TCaptcha.js", function() {
                        return o.lang.isFunction(window.TencentCaptcha) ? e(!0) : void e(!1)
                    })
                }
                ).then(function(t) {
                    return o.lang.isFunction(e.opts.onLoad) && e.opts.onLoad(),
                    t ? new Promise(function(t) {
                        c.show(),
                        new TencentCaptcha(e.container,n,function(e) {
                            c.hide(),
                            t(e)
                        }
                        ,{
                            "showHeader": !1,
                            "sid": e.params.risk_sessionid || ""
                        }).show()
                    }
                    ) : (f("riskvcode.picverify.capapi.loadfail"),
                    e.close())
                }).then(function(t) {
                    f("riskvcode.picverify.cap.callback", {
                        "resultcode": t.ret
                    }),
                    0 != t.ret ? e.close() : e.triggerVerifyDone({
                        "rc_token": t.ticket,
                        "cap_type": "7",
                        "disturb_level": "1",
                        "veri_appid": n,
                        "veri_code": t.randstr
                    })
                })
            },
            "initUrlVerify": function() {
                var e, n = this, t = decodeURIComponent(this.params.url || "");
                return f("riskvcode.urlverify.begin"),
                t ? (t = t.replace(/(.+)(\/\/)/, "$2"),
                r.create({
                    "url": t,
                    "size": {
                        "w": 400,
                        "h": 292
                    },
                    "hideHeader": !0,
                    "onReady": function(t) {
                        o.lang.isFunction(n.opts.onLoad) && n.opts.onLoad(),
                        e = t
                    },
                    "onClose": function() {
                        e = null,
                        n.close()
                    }
                }),
                void (window._MBQ_CALLBACK = function(t) {
                    if (f("riskvcode.urlverify.callback.begin"),
                    window._MBQ_CALLBACK = o.fn.emptyFunc,
                    !t)
                        return void f("riskvcode.urlverify.callback.url.empty");
                    var i = o.fn.getParam("dna_result_key", t);
                    i ? (f("riskvcode.urlverify.verifydone"),
                    n.triggerVerifyDone({
                        "rc_token": i
                    }, !0)) : f("riskvcode.urlverify.verifynotoken"),
                    e.close()
                }
                )) : (f("riskvcode.urlverify.url.empty"),
                this.close())
            },
            "initFaceVerify": function() {
                var e, n, t = this;
                if (_) {
                    var i = decodeURIComponent(this.opts.jiazhang_url || "");
                    if (f("riskvcode.faceVerify.begin", {
                        "resultinfo": {
                            "downgrade": 1,
                            "jiazhang_url": i
                        }
                    }),
                    !i)
                        return f("riskvcode.faceVerify.url.empty"),
                        this.close();
                    i = i.replace(/(.+)(\/\/)/, "$2"),
                    this.openScanDialog(g.face, i)
                } else {
                    var a = !1
                      , c = !1
                      , i = decodeURIComponent(this.opts.qrcode_url || "").replace("guide.html", "guide_pc.html");
                    if (f("riskvcode.faceVerify.begin", {
                        "resultinfo": {
                            "downgrade": 0,
                            "qrcode_url": i
                        }
                    }),
                    !i)
                        return f("riskvcode.faceVerify.url.empty"),
                        this.close();
                    i = i.replace(/(.+)(\/\/)/, "$2"),
                    i += "&isMidas=1";
                    var l = function(t) {
                        if (n && t.source === n.contentWindow) {
                            var i = JSON.parse(t.data);
                            "success" == i.action && (a = !0),
                            "close" == i.action && (c = !0,
                            e.close())
                        }
                    };
                    r.create({
                        "title": "腾讯游戏人脸识别验证",
                        "url": i,
                        "size": {
                            "w": 640,
                            "h": 350
                        },
                        "clickClose": !1,
                        "maskConfig": {
                            "bgColor": "#000000",
                            "opacity": "0.8"
                        },
                        "onReady": function(i) {
                            o.lang.isFunction(t.opts.onLoad) && t.opts.onLoad(),
                            e = i,
                            n = document.getElementById(e.getIframeId()),
                            s.bind(window, "message", l)
                        },
                        "onClose": function() {
                            a ? t.checkFaceRes().then(function() {
                                t.close()
                            }) : t.close(),
                            e = null,
                            n = null,
                            s.unbind(window, "message", l),
                            f("riskvcode.faceVerify.close", {
                                "resultinfo": {
                                    "verifySuccess": a ? 1 : 0,
                                    "calledClose": c ? 1 : 0
                                }
                            })
                        }
                    })
                }
            },
            "checkFaceRes": function() {
                var e = this;
                return new Promise(function(n) {
                    l.show(),
                    e.checkVerify({
                        "action": "check"
                    }, function(t) {
                        l.remove(),
                        f("riskvcode.faceVerify.checkresp", {
                            "resultcode": t.ret,
                            "resultinfo": {
                                "err_code": t.err_code || "",
                                "msg": t.msg || ""
                            }
                        }),
                        ~~t.ret ? 3216 === t.ret ? u.create({
                            "msg": "人脸身份验证失败",
                            "confirmBtnTxt": "返回",
                            "hideCancel": !0,
                            "onConfirm": n
                        }) : u.create({
                            "msg": "未查询到认证结果，请重试（" + t.ret + "）",
                            "confirmBtnTxt": "重试",
                            "cancelBtnTxt": "返回",
                            "onConfirm": function() {
                                e.checkFaceRes().then(n)
                            },
                            "onCancel": n
                        }) : (e.triggerVerifyDone({
                            "rc_token": t.rc_token
                        }, !0),
                        n())
                    })
                }
                )
            },
            "initIdentityVerify": function() {
                var e, n = this, t = !1, i = !1, a = decodeURIComponent(this.opts.veri_url || "");
                if (f("riskvcode.identityVerify.begin", {
                    "resultinfo": {
                        "downgrade": _ ? 1 : 0,
                        "veri_url": a
                    }
                }),
                !a)
                    return f("riskvcode.identityVerify.url.empty"),
                    this.close();
                if (a = a.replace(/(.+)(\/\/)/, "$2"),
                a += "&isMidas=1",
                _)
                    this.openScanDialog(g.identity, a);
                else {
                    var c = function(o) {
                        /^(https?:\/\/)?(test\.)?jiazhang\.qq\.com($|\/|\\)/i.test(o.origin) && ("200" == o.data && (t = !0),
                        "100" == o.data && (i = !0,
                        s.unbind(window, "message", c),
                        t ? (n.triggerVerifyDone({}),
                        e && e.close()) : (n.close(),
                        e && e.close())))
                    };
                    r.create({
                        "title": "腾讯游戏实名认证",
                        "url": a,
                        "size": {
                            "w": 640,
                            "h": 350
                        },
                        "clickClose": !1,
                        "hideHeader": !1,
                        "maskConfig": {
                            "bgColor": "#000000",
                            "opacity": "0.8"
                        },
                        "onReady": function(t) {
                            o.lang.isFunction(n.opts.onLoad) && n.opts.onLoad(),
                            e = t,
                            t.dialogLoading = !0
                        },
                        "onClose": function() {
                            e = null,
                            s.unbind(window, "message", c),
                            t ? n.triggerVerifyDone({}) : n.close(),
                            f("riskvcode.identityVerify.close", {
                                "resultinfo": {
                                    "verifySuccess": t ? 1 : 0,
                                    "calledClose": i ? 1 : 0
                                }
                            })
                        },
                        "iframeOnLoad": function(e) {
                            e.dialogLoading = !1
                        }
                    }),
                    s.bind(window, "message", c)
                }
            },
            "_getPublicParams": function() {
                return {
                    "verify_type": this.params.veri_type,
                    "auth_type": this.params.auth_type,
                    "amt": this.opts.fk_amt
                }
            },
            "checkVerify": function(e, n) {
                e = e || {};
                var t = {
                    "action": "check"
                };
                o.fn.extend(t, this._getPublicParams(), e),
                o.lang.isFunction(this.opts.onRcRestrict) && this.opts.onRcRestrict(t, n)
            },
            "sendSms": function(e, n) {
                e = e || {};
                var t = {};
                o.fn.extend(t, this._getPublicParams(), e),
                o.lang.isFunction(this.opts.onRcRestrict) && this.opts.onRcRestrict(t, n)
            },
            "triggerVerifyDone": function(e, n) {
                e = e || {},
                e = o.fn.extend({
                    "veri_type": this.params.veri_type,
                    "auth_type": this.params.auth_type,
                    "sub_auth_type": this.params.sub_auth_type || "",
                    "mobile_no": this.params.mobile_no,
                    "flex_extend": this.params.flex_extend || ""
                }, e);
                try {
                    o.lang.isFunction(this.opts.onVerifyDone) && this.opts.onVerifyDone(e)
                } catch (t) {}
                n || this.close()
            },
            "close": function() {
                try {
                    o.lang.isFunction(this.opts.onDestroy) && this.opts.onDestroy()
                } catch (e) {}
                for (var n in this.vms) {
                    try {
                        delete s.vmodels[this.vms[n].$id]
                    } catch (e) {
                        this.vms[n] && this.vms[n].$id && (s.vmodels[this.vms[n].$id] = null)
                    }
                    this.vms[n] = null
                }
                this.vms = null,
                this.refVm = null,
                this.container && (this.container.innerHTML = "",
                this.el.removeChild(this.container),
                this.container = null),
                this.opts = null,
                this.verifyCodeTimer && (this.verifyCodeTimer.stop(1),
                this.verifyCodeTimer = null)
            },
            "openScanDialog": function(e, n) {
                var t = this
                  , i = null
                  , s = function(e) {
                    i.url = e
                }
                  , a = !1;
                r.create({
                    "forceMaskCss": !0,
                    "opacity": .8,
                    "bgColor": "#000000",
                    "clickClose": !1,
                    "title": e === g.face ? "腾讯游戏人脸识别验证" : "腾讯游戏实名认证",
                    "url": "",
                    "displayHtml": e === g.face ? p() : h(),
                    "size": {
                        "w": 600,
                        "h": e === g.face ? 375 : 400
                    },
                    "accountType": t.opts.accountType,
                    "onConfirm": function() {
                        a = !0,
                        e === g.face ? (t.checkFaceRes().then(function() {
                            t.close()
                        }),
                        f("riskvcode.faceVerify.confirm")) : (t.triggerVerifyDone({}, !0),
                        t.close(),
                        f("riskvcode.identityVerify.confirm")),
                        i && i.close()
                    },
                    "onClose": function() {
                        a || t.close(),
                        f(e === g.face ? "riskvcode.faceVerify.close" : "riskvcode.identityVerify.close")
                    },
                    "onReady": function(e) {
                        i = e,
                        t.getFKScanUrl(n, s),
                        o.lang.isFunction(t.opts.onLoad) && t.opts.onLoad()
                    }
                })
            },
            "getFKScanUrl": function(e, n) {
                var t = "";
                this.cgi.getQrcode({
                    "a": "get_qrcode",
                    "url": encodeURIComponent(location.protocol + e),
                    "size": 200,
                    "http_type": "https"
                }, function(e) {
                    ~~e.ret ? n("error") : (t = e.qrcode,
                    n("data:image/png;base64," + t))
                }
                .bind(this))
            }
        }),
        k.TEXT = {
            "REINPUTVERIFY": "验证码错误，请重新输入"
        },
        e.exports = k
    },
    "44017488": function(e, n) {
        e.exports = "bind-card"
    },
    "47721167": function(e, n) {
        e.exports = {
            "CardType": {
                "credit": "credit",
                "debit": "debit"
            },
            "CardTypeDesc": {
                "credit": "信用卡",
                "debit": "储蓄卡"
            },
            "BankType": {
                "B2B": "B2B",
                "B2C": "B2C"
            },
            "BankTypeDesc": {
                "B2B": "企业银行",
                "B2C": "个人银行"
            },
            "PayTypeDesc": {
                "kj": "快捷支付",
                "bank": "网银支付"
            }
        }
    },
    "48016802": function(e, n, t) {
        var i = t(19)
          , o = t(74109955);
        "undefined" == typeof __Service && (window.__Service = {}),
        "undefined" == typeof __UIConfig && (window.__UIConfig = {
            "base": {}
        });
        var s = function(e, n) {
            if (n)
                return __Service[n] && __Service[n][e];
            var t = i.get("type")
              , o = __UIConfig[t]
              , s = __UIConfig["base"];
            return o && o[e] ? o[e] : s[e]
        };
        e.exports = {
            "get": function(e) {
                return s(e)
            },
            "getTitle": function(e) {
                return s("title", e)
            },
            "getOrderServiceName": function(e) {
                return s("orderServiceName", e)
            },
            "getPriceItemName": function(e, n) {
                return s(n == o.day ? "priceItemNameByDay" : n == o.year ? "priceItemNameByYear" : "priceItemName", e)
            }
        }
    },
    "48111119": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div class="goods-items"\n     ms-on-mouseenter="mouseenter"\n     ms-on-mouseleave="mouseleave"\n     ms-class-1="checked:checked"\n     ms-class-2="error:isWarn"\n     ms-on-click="handleClickGoods" ms-attr-title="title"\n     data-track="product">\n    <div class="total service" style="border-bottom: none; padding-top: 25px;">\n        <div ms-if="!editable">\n            <p class="service__quantity"><img class="service__logo" ms-attr-src="logo" alt="" title=""><span class="service__num">{{count}}</span>\n                <span\n                    class="service__sub-num" ms-if="discountAmount>0">+{{discountAmount}}</span>\n            </p>\n            <div class="service__gift">\n                <p class="service__txt" ms-if="discountTips">{{discountTips}}</p>\n                <div class="tooltip gift" ms-if="discountDetailTips.length>0">\n                    <ul class="gift__list">\n                        <li ms-repeat="discountDetailTips" class="gift__item">{{el.name}}</li>\n                    </ul>\n                </div>\n            </div>\n        </div>\n        <div ms-if="editable">\n            <p class="service__quantity" style="position:relative">\n                <img class="service__logo" ms-attr-src="logo" alt="" title=""><input  ms-attr-id="inputId" class="form-input form-input--s form-input--no-border service__input service__input-cn"\n                                                                                      ms-on-click="handleInputClick"\n                                                                                      ms-on-focus="handleFocus"\n                                                                                      ms-on-keydown="handleKeyDown"\n                                                                                      ms-on-keyup="handleKeyUp"\n                                                                                      ms-on-blur="handleBlur"\n                                                                                      data-track="customAmountInput"><label ms-attr-for="inputId" ms-if="enablePlaceHolder && count==\'\' && !ie7focused" style="position:absolute;font-size:16px;left: 0;top:0;width:80px;*width:70px;height:18px;*height:24px;height:24px\\0;left:30px;line-height:30px;vertical-align:middle;" class="input-placeholder">\n                其他数量\n            </label></p>\n        </div>\n    </div>\n    <div class="relative-to-total" style="visibility: hidden">\n      <em class="money">{{price}}</em>\n      <span class="unit">{{priceUnitName}}</span>\n    </div>\n    <i class="icon-corner-checked" ms-if="!editable"></i>\n    <i class="icon-corner-checked hide" ms-if="editable" ms-attr-id="cornerId" ></i>\n    <div class="goods-marketing" ms-if="restrictionRule">\n        <i class="icon-marketing-l"></i>\n        <span>{{restrictionRule}}</span>\n        <i class="icon-marketing-r"></i>\n    </div>\n    <p class="tips icon-tips warn custom-tips" ms-if="isWarn">\n        <i class="icon-warn"></i>\n        {{errorTips}}\n    </p>\n</div>';
            return __p
        }
    },
    "48666621": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div class="goods-items"\n     ms-on-mouseenter="mouseenter"\n     ms-on-mouseleave="mouseleave"\n     ms-class-1="checked:checked"\n     ms-class-2="error:isWarn"\n     ms-on-click="handleClickGoods" ms-attr-title="title"\n     data-track="product">\n    <div class="total service">\n        <div ms-if="!editable">\n            <p class="service__quantity"><img class="service__logo" ms-attr-src="logo" alt="" title=""><span class="service__num">{{count}}</span>\n                <span\n                    class="service__sub-num" ms-if="discountAmount>0">+{{discountAmount}}</span>\n            </p>\n            <div class="service__gift">\n                <p class="service__txt" ms-if="discountTips">{{discountTips}}</p>\n                <div class="tooltip gift" ms-if="discountDetailTips.length>0">\n                    <ul class="gift__list">\n                        <li ms-repeat="discountDetailTips" class="gift__item">{{el.name}}</li>\n                    </ul>\n                </div>\n            </div>\n        </div>\n        <div ms-if="editable">\n            <p class="service__quantity" style="position:relative">\n                <img class="service__logo" ms-attr-src="logo" alt="" title=""><input  ms-attr-id="inputId" class="form-input form-input--s form-input--no-border service__input service__input-cn"\n                                                                                      ms-on-click="handleInputClick"\n                                                                                      ms-on-focus="handleFocus"\n                                                                                      ms-on-keydown="handleKeyDown"\n                                                                                      ms-on-keyup="handleKeyUp"\n                                                                                      ms-on-blur="handleBlur"\n                                                                                      data-track="customAmountInput"><label ms-attr-for="inputId" ms-if="enablePlaceHolder && count==\'\' && !ie7focused" style="position:absolute;font-size:16px;left: 0;top:0;width:80px;*width:70px;height:18px;*height:24px;height:24px\\0;left:30px;line-height:30px;vertical-align:middle;" class="input-placeholder">\n                其他数量\n            </label></p>\n        </div>\n    </div>\n    <div class="relative-to-total">\n      <em class="money">{{price}}</em>\n      <span class="unit">{{priceUnitName}}</span>\n    </div>\n    <i class="icon-corner-checked" ms-if="!editable"></i>\n    <i class="icon-corner-checked hide" ms-if="editable" ms-attr-id="cornerId" ></i>\n    <div class="goods-marketing" ms-if="restrictionRule">\n        <i class="icon-marketing-l"></i>\n        <span>{{restrictionRule}}</span>\n        <i class="icon-marketing-r"></i>\n    </div>\n    <p class="tips icon-tips warn custom-tips" ms-if="isWarn">\n        <i class="icon-warn"></i>\n        {{errorTips}}\n    </p>\n</div>';
            return __p
        }
    },
    "48695175": function(module, exports) {
        module.exports = function(obj) {
            function print() {
                __p += __j.call(arguments, "")
            }
            obj || (obj = {});
            var __t, __p = "", __j = Array.prototype.join;
            with (obj)
                __p += '<div ms-controller="result-detail" class="result-body" ms-class-1="result-{{status}}" style="padding-bottom:0; position: relative;">\n    <div ms-if="!isQuery&&!isCustom">\n        <div class="icons-area">\n            <i ms-class="icon-{{status}}-l"></i>\n        </div>\n        <div class="info-area">\n            <!--这里可以放info通过ejs-->\n            ',
                "undefined" != typeof info && (__p += "\n                " + (null == (__t = info) ? "" : __t) + "\n            "),
                __p += '\n            <!--<p>565220833(QQ)成功开通好莱坞会员1个月</p>-->\n            <p class="sub-info" ms-if="subInfo" ms-html="subInfo"></p>\n            <div class="tips-wrapper" ms-html="tips" ms-if="tips">\n\n            </div>\n        </div>\n        <div class="marketing-area">\n            <!--这里可以放marketing 营销活动信息-->\n            ',
                "undefined" != typeof market && (__p += "\n                " + (null == (__t = market) ? "" : __t) + "\n                    "),
                __p += '\n        </div>\n        <div class="oper-area">\n            <!--这里加额外的操作按钮-->\n            ',
                "undefined" != typeof oper && (__p += "\n                " + (null == (__t = oper) ? "" : __t) + "\n                    "),
                __p += '\n                        <a ms-if="showFinish" href="#" ms-on-click="finish($event,status)" class="btn btn-default">{{buttonTxt}}</a>\n        </div>\n    </div>\n    <div ms-if="isQuery" ms-html="queryContainer">\n\n    </div>\n    <div ms-if="isCustom" ms-html="customContainer">\n\n    </div>\n    <div ms-if="bottomText" ms-html="bottomText"></div>\n</div>';
            return __p
        }
    },
    "48800002": function(e, n, t) {
        var i = t(55660113)
          , o = t(4)
          , s = t(1)
          , a = o.fn.getParam("sandbox")
          , r = t(100835382)
          , c = t(17)
          , l = t(11)
          , u = t(119561448)
          , d = t(104491903)
          , p = t(84811753)
          , h = t(75748174)
          , f = o.fn.getParam("inApp")
          , m = "//midas.gtimg.cn/mtob/web/channel-web-sdk/jssdk/mtob-channel-api.umd.js"
          , g = !1
          , v = function(e, n, t) {
            r.apply(this, arguments),
            this.portal_serial_no = null,
            this.payProxy = window.location.protocol + "//" + window.location.host + "/midas/minipay_v2/views/public/pay-bank.php",
            this.cacheBankData = {},
            this.bankObj = {},
            this.amount = 0,
            this.saveTimout = null,
            this.payBankUrl = null,
            this.payBankUrlTimeout = null,
            this.init()
        }
          , b = {
            "init": function() {
                this.initVm(),
                this.calculatePrice(),
                this.fetchTargetUin(),
                this.fetchAmount(),
                this.initChannel()
            },
            "calculatePrice": function() {
                var e = this.store.getPrice().price;
                this.price = this.store.getPrice(o.discount.checkHasDiscount(e, this.channelObj.channel) ? this.channelObj.discount : void 0, this.coupon).price,
                this.vm.price = this.price
            },
            "fetchAmount": function() {
                this.vm.amount = this.store.getAmount(),
                this.amount = this.store.getAmount()
            },
            "fetchTargetUin": function() {
                this.targetUin = this.store.getTargetInfo().uin
            },
            "initChannel": function() {
                var e = this;
                return this.refreshUuid(),
                this.store.isInterfaceDisabled() ? (this.vm.isDisable = !0,
                void (this.vm.disableText = this.store.getChannelDisableText())) : 0 == this.amount ? (this.vm.isDisable = !0,
                void (this.vm.disableText = "请完善充值信息")) : (this.vm.isDisable = !1,
                void setTimeout(function() {
                    return g ? void e.initedChannel() : void s.getScript(m, function() {
                        g = !0,
                        e.initedChannel()
                    })
                }, 0))
            },
            "initedChannel": function() {
                this.mTobChannelApi && (this.mTobChannelApi.destroy(),
                this.mTobChannelApi = null);
                var e = this
                  , n = window.MtobChannelApi.init({
                    "params": {
                        "appID": this.store.info.offer_id,
                        "userID": this.store.session.openid,
                        "channel": this.store.channel,
                        "tenantID": "deploy_env",
                        "deploy_env": this.getDeployEnv(),
                        "channelParams": {
                            "payerType": this.channelObj.allowed_payer_types || [],
                            "disableEnterpriseBank": "true" === o.fn.getParam("disableEnterpriseBank"),
                            "disableIndividualBank": "true" === o.fn.getParam("disableIndividualBank"),
                            "individualBankFirst": "true" === o.fn.getParam("individualBankFirst")
                        },
                        "sessionID": this.uuid,
                        "reqID": this.uuid
                    },
                    "envOptions": {
                        "env": 2 == a ? "dev" : 1 == a ? "sandbox" : "release",
                        "pageUriConfigs": {
                            "release": {
                                "baseUri": "https://pay.qq.com/mtob/web/channel-web-sdk/p/channel-client"
                            },
                            "sandbox": {
                                "baseUri": "https://sandbox.pay.qq.com/mtob/web/channel-web-sdk/p/channel-client"
                            },
                            "dev": {
                                "baseUri": "https://dev.tke.midas.qq.com/mtob/web/channel-web-sdk/p/channel-client"
                            }
                        }
                    },
                    "timeout": 5e3,
                    "theme": "compact"
                });
                this.mTobChannelApi = n,
                n.on("ready", function() {
                    e.vm.loading = !1
                }),
                n.on("resize", function(e) {
                    var n = document.querySelector("#b2bChannelWebIframe");
                    n.style.height = e.height + "px";
                }),
                n.on("status", function(e) {}),
                n.on("timeout", function() {
                    e.store.onFail({
                        "ret": 9901,
                        "msg": "系统繁忙，请稍后再试"
                    })
                }),
                n.on("channelEvent", function(n) {
                    if (n) {
                        if ("cft_b2b" !== n.channel)
                            return;
                        "setBank" === n.action && n.data ? e.onSelectedBank(n.data) : "unsetBank" === n.action && e.onSelectedBank(null)
                    }
                }),
                n.attach({
                    "target": document.querySelector("#b2bChannelWebIframe")
                })
            },
            "getDeployEnv": function() {
                if (this.store.params && this.store.params.goodstokenurl) {
                    var e = o.fn.getParam("deploy_env", this.store.params.goodstokenurl);
                    return e ? e : "tboss"
                }
                return "tboss"
            },
            "onChange": function() {
                this.fetchTargetUin(),
                this.fetchAmount(),
                this.refreshCoupon(),
                this.calculatePrice(),
                this.debounceOrder()
            },
            "debounceOrder": function() {
                if (this.payBankUrl = null,
                this.payBankUrlTimeout && (clearTimeout(this.payBankUrlTimeout),
                this.payBankUrlTimeout = null),
                this.saveTimout && (this.saveTimout.stop(0),
                this.saveTimout = null,
                this.vm.paying = !1,
                this.unlock()),
                !this.store.isInterfaceDisabled() && 0 != this.amount) {
                    var e = this;
                    this.vm.paying = !0,
                    this.lock(),
                    this.saveTimout = new l.Timeout({
                        "time": .7,
                        "timeUp": function() {
                            e.vm.paying = !1,
                            e.unlock(),
                            e.saveTimout = null,
                            e.order({}, function(n, t) {
                                e.payBankUrl = n,
                                e.payBankUrlTimeout = setTimeout(function() {
                                    e.debounceOrder()
                                }, 1e3 * t)
                            })
                        }
                    })
                }
            },
            "order": function(e, n) {
                e = e || {};
                var t = this
                  , i = {
                    "uuid": this.uuid,
                    "pushtype": "NodeJS",
                    "pay_method": "cft_b2b:5",
                    "bank_type": encodeURIComponent(this.bankObj.bankType)
                };
                o.fn.extend(i, e);
                var s = function() {
                    var e = {
                        "proxy": !0
                    };
                    t.lock(),
                    t.vm.paying = !0,
                    u.show({
                        "opacity": "0"
                    }),
                    t.store.buy(i, function(e) {
                        if (t.unlock(),
                        t.vm.paying = !1,
                        u.hide(),
                        !~~e.ret) {
                            var i = t.store.getSession().getSessionParam()
                              , s = e.jump;
                            return t.lock(),
                            t.vm.paying = !0,
                            u.show({
                                "opacity": "0"
                            }),
                            t.getShortUrl(s, function(e) {
                                if (t.unlock(),
                                t.vm.paying = !1,
                                u.hide(),
                                e.status) {
                                    var a = o.fn.addParam({
                                        "short_url": encodeURIComponent(e.shortUrl),
                                        "openid": encodeURIComponent(i.openid),
                                        "openkey": encodeURIComponent(i.openkey),
                                        "rc_params": encodeURIComponent(o.req.serializeParam(t.store.getRcRestrictParams()))
                                    }, t.payProxy);
                                    n(a, 1 * e.validTime || 600),
                                    t.report("bank.qrcodeSuccess", {
                                        "resultinfo": {
                                            "webSaveLength": s.length
                                        }
                                    })
                                } else
                                    t.store.onFail(e.res),
                                    t.report("bank.qrcodeFail", {
                                        "resultinfo": {
                                            "webSaveLength": s.length,
                                            "ret": e.res && e.res.ret || "",
                                            "err_code": e.res && e.res.err_code || ""
                                        }
                                    })
                            }, !0),
                            !0
                        }
                    }, e)
                };
                s()
            },
            "getVmConfig": function() {
                var e = this;
                return o.fn.extend({
                    "$id": "bank-controller",
                    "price": this.price,
                    "amount": this.amount,
                    "$computed": {
                        "bankClass": {
                            "get": function() {
                                if (this.bank)
                                    return "icon-" + this.bank
                            }
                        }
                    },
                    "disableSubmit": !0,
                    "paying": !1,
                    "tips": "",
                    "isDisable": !1,
                    "loading": !0,
                    "disableText": "请完善充值信息",
                    "pay": function(n) {
                        if (n.preventDefault(),
                        !e.isLocked())
                            return e.reportUser("pay.click"),
                            e.store.isInterfaceDisabled() ? void e.store.emit("channelDataChange", new p(h)) : void (0 != e.amount && e.payBankUrl && ("1" != f ? o.openWindow(e.payBankUrl) : c.openWindow(e.payBankUrl),
                            e.store.changePage("subChannel", s.mix({
                                "channelObj": e.channelObj,
                                "portal_serial_no": e.portal_serial_no,
                                "mode": r.MODE.COMPLETE,
                                "price": e.price,
                                "coupon": e.coupon,
                                "store": e.store
                            }, {
                                "uuid": e.uuid
                            }, e.bankObj)),
                            e.store.emit(d, new p(d,{
                                "show": !1
                            }))))
                    }
                }, this.getCouponVmConfig(), this.getTermsVmConfig(), this.getPubVmConfig())
            },
            "onSelectedBank": function(e) {
                this.vm && (e ? (this.vm.tips = "",
                this.vm.disableSubmit = !1,
                this.bankObj = e,
                this.debounceOrder()) : (this.vm.tips = "",
                this.vm.disableSubmit = !0,
                this.bankObj = {}))
            },
            "initVm": function() {
                this.vm = s.define(this.getVmConfig())
            },
            "onDestroy": function() {
                this.mTobChannelApi && this.mTobChannelApi.destroy(),
                this.mTobChannelApi = null,
                this.portal_serial_no = null,
                this.removeListener(),
                this.payBankUrlTimeout && (clearTimeout(this.payBankUrlTimeout),
                this.payBankUrlTimeout = null),
                this.saveTimout && this.saveTimout.stop(0),
                this.destroy(),
                u.hide()
            }
        };
        o.inherits(v, r),
        o.fn.extend(v.prototype, b),
        v.create = function(e, n, t) {
            return new v(e,n,t)
        }
        ,
        v.getTemplate = function(e) {
            return i()
        }
        ,
        e.exports = v
    },
    "49140953": function(e, n, t) {
        var i = t(72074753)
          , o = t(112745811)
          , s = t(4)
          , a = s.fn.getParam("skin")
          , r = "dnf" === a || "minimonth" === a
          , c = {
            "KFURL": "//kf.qq.com/",
            "chargeQbAppid": "1450000186",
            "cpayContainerid": "pannel",
            "wxAppid": "wx951bdcac522929b6",
            "goodVipConfig": window.__GOODS_VIP_CONFIGS || {},
            "TEXT": {
                "COMMONERRORTXT": "系统繁忙，请稍后再试",
                "INVALIDLOGIN": "登录态已经失效，请重新登录",
                "GETORDERFAIL": "订单拉取失败",
                "RETRYPAY": "更换渠道购买",
                "CHANNELPAYFAIL": "支付失败"
            }
        }
          , l = {}
          , u = [o.GOODS, o.GAME, o.MONTH];
        l[i.QBQD] = {
            "name": "Q币支付",
            "payMethod": "qbqd",
            "discount": 1,
            "moneyname": "Q币",
            "status": 1,
            "height": r ? 112 : 170,
            "visibleCoupon": u
        },
        l[i.QDQB] = {
            "name": "Q币支付",
            "payMethod": "qdqb",
            "discount": 1,
            "moneyname": "Q点",
            "status": 1,
            "height": r ? 112 : 170,
            "visibleCoupon": u
        },
        l[i.QQACCT] = {
            "name": "Q币支付",
            "payMethod": "qqacct",
            "discount": 1,
            "moneyname": "Q币",
            "status": 1,
            "height": r ? 112 : 170,
            "visibleCoupon": u
        },
        l[i.QQPOINT] = {
            "name": "Q币支付",
            "payMethod": "qqpoint",
            "discount": 1,
            "moneyname": "Q点",
            "status": 1,
            "height": r ? 112 : 170,
            "visibleCoupon": u
        },
        l[i.KJ] = {
            "name": "快捷支付",
            "payMethod": "pccft",
            "desc": '<small class="tx-thin">（快捷支付）</small>',
            "logoVer": 2,
            "status": 1,
            "height": r ? 155 : 214
        },
        l[i.BANK] = {
            "name": "网银支付",
            "payMethod": "pcbank",
            "desc": '<small class="tx-thin">（银行卡）</small>',
            "logoVer": 2,
            "status": 1,
            "height": r ? 235 : 290
        },
        l[i.MCARD] = {
            "name": "手机充值卡",
            "payMethod": "mcard",
            "status": 1,
            "height": r ? 200 : 288
        },
        l[i.HFPAY] = {
            "value": "hfpay",
            "discounts": {
                "service": 1,
                "upgrade": 1,
                "recharge": 1,
                "game": 1
            },
            "name": "手机话费",
            "invisible": {
                "send": [o.MONTH, o.QB, o.GAME, o.GOODS]
            },
            "payMethod": "hfpay",
            "status": 1,
            "height": 160
        },
        l[i.WECHAT] = {
            "name": "微信支付",
            "payMethod": "wechat",
            "status": 1,
            "height": r ? 160 : 235,
            "visibleCoupon": u
        },
        l[i.QQWALLET] = {
            "name": "QQ钱包",
            "payMethod": "qqwallet",
            "desc": '<small class="tx-thin">（银行卡快捷、余额）</small>',
            "logoVer": 2,
            "status": 1,
            "height": r ? 180 : 235,
            "visibleCoupon": u
        },
        l[i.QQCARD] = {
            "name": "QQ卡",
            "payMethod": "qqcard",
            "status": 1,
            "height": r ? 145 : 236
        },
        l[i.FRIENDPAY] = {
            "name": "好友代付",
            "payMethod": "friendpay",
            "status": 1,
            "height": r ? 150 : 220
        },
        l[i.REMITPAY] = {
            "name": "转账/汇款",
            "payMethod": "remitpay",
            "status": 1,
            "height": 400
        },
        l[i.CFTB2B] = {
            "name": "网银支付",
            "payMethod": "cft_b2b",
            "desc": '<small class="tx-thin">（银行卡）</small>',
            "logoVer": 2,
            "status": 1,
            "height": r ? 250 : 380
        },
        "minimonth" === a && (l[i.QQWALLET].height = 80,
        l[i.WECHAT].height = 80,
        l[i.HFPAY].height = 80,
        l[i.QQCARD].height = 80,
        l[i.QBQD].height = 80,
        l[i.QDQB].height = 80,
        l[i.QQACCT].height = 80,
        l[i.QQPOINT].height = 80,
        l[i.FRIENDPAY].height = 80,
        l[i.BANK].height = 235,
        l[i.CFTB2B].height = 250),
        c.channels = l,
        e.exports = c
    },
    "49898765": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div>\n    <div class="icons-area">\n        <i ms-class="icon-{{status}}-l" ms-attr-title="countDown">{{countDown}}</i>\n    </div>\n    <div class="info-area">\n        <p ms-html="info"></p>\n        <p class="sub-info" ms-html="subInfo">\n            \n            <!--由于网络异常，你的支付正在查询中。如支付成功，您将会在24小时内收到成功短信；如未收到短信将不会发生扣款。给您带来的不便，我们深感抱歉。-->\n        </p>\n    </div>\n    <div class="oper-area" ms-visible="showQueryButton">\n        <button class="btn btn-default" ms-class-1="btn-dis:!enableQuery" type="button">查询</button>\n    </div>\n    <!--<div class="oper-area">-->\n        <!--<button type="button" ms-on-click="confirm" ms-class-1="btn-dis:!enableConfirm" class="btn btn-default" ms-attr-disabled="!enableConfirm">我知道了</button>-->\n    <!--</div>-->\n</div>\n\n';
            return __p
        }
    },
    "50087682": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div class="marketing-title" id="marketing-title" ms-if="market">\n    <p>赠送物品</p>\n</div>\n<div class="privileges" ms-if="market">\n    <ul>\n        <li ms-repeat="market" style="text-align: center">{{el.name}}</li>\n    </ul>\n</div>';
            return __p
        }
    },
    "50736890": function(e, n, t) {
        var i = t(1)
          , o = t(69854898)
          , s = t(66138017)
          , a = t(19)
          , r = t(119122155)
          , c = t(12)
          , l = t(76531812)
          , u = t(10)
          , d = t(4)
          , p = t(104491903)
          , h = t(109895087)
          , f = t(72700182);
        e.exports = function(e) {
            function n(e) {
                t && t.onBack && t.onBack(e)
            }
            var t = i.define({
                "$id": "subChannel",
                "subChannel": o(),
                "orderInfo": "",
                "showHeader": !1,
                "subChannelHtml": "",
                "subHeaderHtml": "",
                "price": "",
                "buyinfo": "",
                "buycount": "",
                "user": "",
                "unit": "",
                "onBack": function(e) {
                    "subChannel" == e && (c.off("back", n),
                    l.emit("destroy-channel"),
                    t.subChannelHtml = "")
                },
                "back": function() {
                    e.back()
                },
                "onInit": function(i) {
                    e.on("InnerHeader", function(e) {
                        "subChannel" == e.page && (t.showHeader = e.isShow)
                    }),
                    l.on(p, function(n) {
                        e.showBackBtn(n.getData().show)
                    }),
                    e.showInnerHeader && f.create(e, {
                        "currentPage": e.currentPage,
                        "controllerId": "subheader",
                        "showBackText": "lol" == e.skin
                    }).on("ready", function() {
                        t.subHeaderHtml = h({
                            "controllerId": "subheader",
                            "templateType": "default"
                        })
                    }),
                    e.showBackBtn(!0),
                    c.on("back", n),
                    t.orderInfo = s(),
                    t.price = i.price ? i.price : r.getPrice(i.channelObj.discount).price,
                    t.buycount = r.getAmount(),
                    t.user = a.get("wechatNickName") || a.get("qqNumber") || a.get("qqNickName") || "";
                    var o = r.getUnitName();
                    o && o != r.getName() ? (t.buyinfo = "购买" + r.getName(),
                    t.unit = r.getUnitName()) : (t.buyinfo = "购买",
                    t.unit = r.getName());
                    var m = function(e) {
                        t.subChannelHtml = e
                    };
                    u.user.action("page", "subChannel", {
                        "channel": i.channelObj.channel
                    }),
                    u("subChannel.pv", {
                        "action": i.channelObj.channel
                    }),
                    l.isInit() && l.renderChannel(m, d.fn.extend({}, i))
                }
            });
            return t
        }
    },
    "50980797": function(e, n, t) {
        var i = t(4)
          , o = t(1)
          , s = t(66520979)
          , a = t(100835382)
          , r = t(109181847)
          , c = (t(11),
        t(117821206))
          , l = t(43847285)
          , u = i.fn.emptyFunc
          , d = function(e, n, t) {
            a.apply(this, arguments),
            this.phoneNumVm = null,
            this.vm = null,
            this.phoneNum = null,
            this.hfMode = null,
            this.hfprice = null,
            this.allowAmt = e.getHfAllowAmt(),
            this.mobileWirelessCgiData = {},
            this.miguProxy = window.location.protocol + "//" + window.location.host + "/midas/minipay_v2/views/public/migu_proxy.shtml?",
            this.cgi = e.getCgi(),
            this.initVm()
        };
        i.inherits(d, a),
        i.fn.extend(d.prototype, {
            "onDestroy": function() {
                a.prototype.removeListener.call(this),
                "month" !== i.fn.safeGet(this, "store.opts.type") && a.prototype.destroy.call(this)
            },
            "onChange": function() {},
            "lock": function() {
                a.prototype.lock.call(this),
                this.vm.disableSubmit = !0,
                this.showMask()
            },
            "unlock": function() {
                a.prototype.unlock.call(this),
                this.vm.disableSubmit = !1,
                this.hideMask()
            },
            "getVmConfig": function() {
                var e = this;
                return this.vmConfig = {
                    "$id": "hfpay-controller-simple",
                    "loading": !1,
                    "getPhoneNumVm": function(n) {
                        e.phoneNumVm = n
                    },
                    "disableSubmit": !1,
                    "phoneNum": this.opts.phoneNum || "",
                    "phoneNumConfig": {
                        "validations": [{
                            "name": "len",
                            "params": [11],
                            "msg": "请输入正确的手机号"
                        }, {
                            "func": function(e) {
                                return /^1/.test("" + e)
                            },
                            "msg": "手机号码必须以1开头"
                        }],
                        "filters": ["number|*"],
                        "maskcfg": s.masks.space
                    },
                    "hfTips": "",
                    "warnMsg": "",
                    "phoneValidatePass": !1,
                    "phoneValidateMsg": "",
                    "onValidatePhoneNum": function(n) {
                        e.vm.phoneValidatePass = n.passed,
                        e.vm.phoneValidateMsg = n.validation.msg
                    },
                    "onPhoneNumChange": function(n) {
                        e.vm.phoneValidateMsg = "",
                        e.vm.phoneValidatePass = !0,
                        e.vm.phoneNum = n
                    },
                    "handleCheck": function(n) {
                        n.preventDefault(),
                        e.vm.phoneNum = e.phoneNumVm.getValue(),
                        e.vm.phoneValidatePass && (e.reportUser("next.click"),
                        e.phoneNum = e.vm.phoneNum,
                        e.handleCheck(e.vm.phoneNum))
                    }
                }
            },
            "initVm": function() {
                this.vm = o.define(this.getVmConfig()),
                this.vm.hfTips = this.getTips()
            },
            "onSupportDD": function() {
                return !1
            },
            "onBeforeCheck": function() {
                return !0
            },
            "handleCheck": function(e) {
                if (!this.isLocked())
                    return this.lock(),
                    this.onBeforeCheck && !this.onBeforeCheck() ? void this.phoneNotSupport() : void this.cgi.mobileWirelessProc(i.fn.extend({
                        "action": "hfpay_check_type",
                        "type": this.getType(),
                        "mobile": e
                    }, this.getCheckParams()), function(e) {
                        this.unlock(),
                        ~~e.ret ? this.phoneNotSupport() : (this.mobileWirelessCgiData = e,
                        this.hfMode = 1 == e.hfpay_pay_flow ? d.MODE.SMSVERIFY : d.MODE.SMSSEND,
                        this.buy(),
                        this.hfPayTips = e.hfpay_pay_tips,
                        this.onAfterCheckHfpay(e))
                    }
                    .bind(this))
            },
            "phoneNotSupport": function() {
                this.vm.phoneValidateMsg = "该号码不支持"
            },
            "buy": function(e) {
                e = e || {};
                var n = {
                    "mobile": this.phoneNum,
                    "pay_method": this.channelObj.channel
                };
                i.fn.extend(n, e),
                this.vm.loading = !0,
                this.hfMode == d.MODE.SMSSEND ? (i.fn.extend(n, {
                    "mobile": this.phoneNum,
                    "pay_method": this.channelObj.channel,
                    "pay_scene": "pay",
                    "success_return_url": encodeURIComponent(this.miguProxy + "action=1"),
                    "fail_return_url": encodeURIComponent(this.miguProxy + "action=0")
                }),
                this.reportUser("smssend.pv"),
                this.onSupportDD() ? this.ddBuy(n) : this.phoneNotSupport()) : (this.dyBuy(n),
                this.reportUser("smsverify.pv"))
            },
            "ddBuy": function(e) {
                e = e || {};
                var n = i.fn.extend({}, e);
                this.isLocked() || (this.lock(),
                this.reportUser("smssend.order.click"),
                this.store.buy(n, function(e) {
                    return this.unlock(),
                    this.handlerDDbuy(e, n)
                }
                .bind(this)))
            },
            "dyBuy": function(e) {
                e = e || {};
                var n = i.fn.extend({
                    "hfpay_pay_flow": "1"
                }, e);
                this.isLocked() || (this.lock(),
                this.reportUser("smsverify.order.click"),
                this.store.buy(n, function(e) {
                    return this.unlock(),
                    this.handlerDYbuy(e, n)
                }
                .bind(this)))
            },
            "handlerDDbuy": function(e, n) {
                this.vm.loading = !1;
                var t = this;
                if (~~e.ret)
                    this.phoneNotSupport();
                else if (e.info && e.info.channel_info && e.info.channel_info.hfpay_url) {
                    this.hfMode = d.MODE.MIGU;
                    var o = e.info.channel_info.hfpay_url.replace(/^https?:/, location.protocol)
                      , s = i.fn.addParam({
                        "redirectURL": encodeURIComponent(this.miguProxy + "action=1"),
                        "failRedirectURL": encodeURIComponent(this.miguProxy + "action=0")
                    }, o)
                      , r = o.indexOf("unipayphone.wostore.cn") > 0
                      , c = r ? o : s
                      , u = {
                        "mode": a.MODE.COMPLETE,
                        "channelObj": this.channelObj,
                        "phoneNum": this.phoneNum,
                        "hfCheckRes": this.mobileWirelessCgiData,
                        "hfMode": this.hfMode,
                        "miguURL": c,
                        "hideSubOrder": !0
                    };
                    i.fn.extend(u, this.onBeforeChangePage()),
                    this.store.changePage("subChannel", u)
                } else if ("2022" == e.ret) {
                    var p = t.store.getCgi().sessionObj.getSessionParam()
                      , h = e.info;
                    new l({
                        "phoneNum": t.phoneNum,
                        "url": h.verify_url,
                        "fk_info": h.fk_info,
                        "fk_amt": h.fk_amt,
                        "jiazhang_url": h.jiazhang_url,
                        "veri_url": h.veri_url,
                        "qrcode_url": h.qrcode_url,
                        "cgi": t.store.getCgi(),
                        "accountType": "wc_actoken" === p.session_type ? "wx" : "qq",
                        "onLoad": function() {},
                        "onRcRestrict": function(e, n) {
                            e = e || {},
                            t.store.rcRestrict(e, n)
                        },
                        "onVerifyDone": function(e) {
                            e = e || {},
                            t.buy(e)
                        }
                    })
                } else
                    this.phoneNotSupport();
                return !0
            },
            "handlerDYbuy": function(e, n) {
                this.vm.loading = !1;
                var t = this;
                if (!~~e.ret) {
                    this.hfBillno = e.info.channel_orderid,
                    this.portalNo = e.info.portal_serial_no,
                    this.hfSaveRes = e.info.channel_info;
                    var o = {
                        "mode": a.MODE.COMPLETE,
                        "channelObj": this.channelObj,
                        "phoneNum": this.phoneNum,
                        "price": this.hfprice || this.getPrice(),
                        "hfMode": this.hfMode,
                        "hfBillno": this.hfBillno,
                        "portalNo": this.portalNo,
                        "hfCheckRes": this.mobileWirelessCgiData,
                        "res": this.hfSaveRes
                    };
                    if (i.fn.extend(o, this.onBeforeChangePage()),
                    this.hfMode == d.MODE.SMSSEND) {
                        var s = this.hfSaveRes;
                        i.fn.extend(o, {
                            "sendSmsFlowAccessMsg": s.msg,
                            "sendSmsFlowAccessNum": s.access_num
                        })
                    }
                    return this.store.changePage("subChannel", o),
                    !0
                }
                var r = new c({
                    "errCode": e.ret,
                    "errMsg": e.msg,
                    "oriParams": n,
                    "2022": function() {
                        var n = t.store.getCgi().sessionObj.getSessionParam()
                          , i = e.info;
                        new l({
                            "phoneNum": t.phoneNum,
                            "url": i.verify_url,
                            "fk_info": i.fk_info,
                            "fk_amt": i.fk_amt,
                            "jiazhang_url": i.jiazhang_url,
                            "veri_url": i.veri_url,
                            "qrcode_url": i.qrcode_url,
                            "cgi": t.store.getCgi(),
                            "accountType": "wc_actoken" === n.session_type ? "wx" : "qq",
                            "onLoad": function() {},
                            "onRcRestrict": function(e, n) {
                                e = e || {},
                                t.store.rcRestrict(e, n)
                            },
                            "onVerifyDone": function(e) {
                                e = e || {},
                                t.buy(e)
                            }
                        })
                    }
                });
                return !!r.canHandle() && (r.exec(),
                !0)
            },
            "checkAllowAmt": function() {
                var e, n = this.allowAmt, t = !1;
                return i.lang.isArray(n) || (t = !1),
                n.length && n.indexOf(i.fn.formatFloat(100 * this.getPrice(), 0, "round")) === -1 ? (e = n.map(function(e) {
                    return i.fn.formatFloat(e / 100, 2, "round")
                }).join("，"),
                e = "话费支付仅支持以下金额(元)：" + e,
                t = !1) : t = !0,
                t ? this.vm.warnMsg = "" : this.vm.warnMsg = e || "",
                t
            },
            "onAfterCheckHfpay": u,
            "getTips": u,
            "getPrice": u,
            "getCheckParams": u,
            "getType": u,
            "onBeforeChangePage": function() {
                return {}
            }
        }),
        d.MODE = {
            "SMSVERIFY": 1,
            "MIGU": 3,
            "SMSSEND": 2
        },
        d.getTemplate = function(e) {
            return e = e || {},
            r(e)
        }
        ,
        d.create = function(e, n, t) {
            return t = t || {},
            new d(e,n,t)
        }
        ,
        e.exports = d
    },
    "51748615": function(e, n, t) {
        var i = t(1)
          , o = t(117538369)
          , s = t(4)
          , a = t(119561448);
        i.component("ms:dialog", {
            "$template": o(),
            "domId": "",
            "$replace": !0,
            "url": "",
            "displayHtml": "",
            "title": "",
            "width": 300,
            "height": 200,
            "hideHeader": !1,
            "$skipArray": ["maskConfig"],
            "maskConfig": {},
            "clickClose": !0,
            "forceMaskCss": !1,
            "opacity": .1,
            "bgColor": "#fffff",
            "bodyTopOffset": null,
            "dialogLoading": !1,
            "$computed": {
                "margin": {
                    "get": function() {
                        return this.displayHtml ? -this.height / 2 + "px 0 0 " + -this.width / 2 + "px" : -this.height / 2 - (this.hideHeader ? 0 : 20) + "px 0 0 " + -this.width / 2 + "px"
                    }
                }
            },
            "onClose": function() {},
            "onReady": function() {},
            "close": function() {
                var e = document.getElementById(this.domId);
                try {
                    e.innerHTML = ""
                } catch (n) {}
                e && e.parentNode && (e.parentNode.removeChild(e),
                e = null,
                a.remove(),
                this.onClose.call(this))
            },
            "$init": function(e) {
                var n = {
                    "forceCss": e.forceMaskCss,
                    "opacity": e.opacity,
                    "bgColor": e.bgColor,
                    "onMaskClick": function() {
                        e.clickClose && e.close()
                    }
                };
                n = s.fn.extend(n, e.maskConfig),
                a.show(n)
            },
            "$ready": function(e) {
                this.onReady(e),
                null != this.bodyTopOffset && (document.getElementById("dialog_body_" + this.domId).style.top = this.bodyTopOffset + "px")
            },
            "getBodyId": function() {
                return "dialog_body_" + this.domId
            },
            "getIframeId": function() {
                return "dialog_iframe_" + this.domId
            },
            "getDisplayHtmlId": function() {
                return "dialog_custom_" + this.domId
            },
            "$dispose": function() {}
        }),
        e.exports = {
            "create": function(e) {
                var n = "dialog-" + (2 * Math.random() + 10).toString().replace(".", "");
                "object" != typeof e.size ? e.size = {
                    "w": 300,
                    "h": 200
                } : ("number" != typeof e.size.w && (e.size.w = 300),
                "number" != typeof e.size.h && (e.size.w = 200));
                var t = (i.define({
                    "$id": n,
                    "config": {
                        "hideHeader": e.hideHeader,
                        "title": e.title || "",
                        "onReady": function(n) {
                            "function" == typeof e.onReady && e.onReady(n)
                        },
                        "onClose": function() {
                            i.vmodels[n] = null,
                            "function" == typeof e.onClose && e.onClose()
                        },
                        "iframeOnLoad": function() {
                            "function" == typeof e.iframeOnLoad && e.iframeOnLoad(this)
                        },
                        "domId": n,
                        "bodyTopOffset": e.bodyTopOffset,
                        "width": e.size.w,
                        "clickClose": e.clickClose,
                        "forceMaskCss": e.forceMaskCss,
                        "height": e.size.h,
                        "displayHtml": e.displayHtml,
                        "maskConfig": e.maskConfig || {},
                        "opacity": e.hasOwnProperty("opacity") ? e.opacity : .1,
                        "bgColor": e.bgColor || "#fffff",
                        "url": e.url,
                        "accountType": e.accountType,
                        "dialogLoading": !1,
                        "onConfirm": function() {
                            "function" == typeof e.onConfirm && e.onConfirm()
                        }
                    }
                }),
                document.createElement("div"));
                t.setAttribute("ms-controller", n),
                t.setAttribute("id", n),
                t.innerHTML = '<ms:dialog config="config"></ms:dialog>',
                document.body.appendChild(t),
                i.scan(t)
            }
        }
    },
    "51768702": function(e, n, t) {
        function i() {
            if (r.call(this),
            this.buyInfo = a.fn.extend({}, a.fn.getParams()),
            p.getLoginStatus().ptlogin) {
                var e = p.getLoginStatusFromCookie();
                e && a.fn.extend(this.buyInfo, {
                    "openid": String(this.buyInfo.openid || e.uin),
                    "openkey": this.buyInfo.openkey || e.skey
                })
            }
            this.initCgi(),
            m.prefetchFpBehv(this.cgi, !0)
        }
        var o = t(7)
          , s = t(9)
          , a = t(4)
          , r = t(21)
          , c = t(22)
          , l = t(101670216)
          , u = t(49140953)
          , d = t(43511251)
          , p = t(109735088)
          , h = t(78805100)
          , f = t(10)
          , m = t(66158855)
          , g = t(17);
        a.inherits(i, r),
        a.fn.extend(i.prototype, {
            "constructor": i,
            "checkParams": function() {
                return d(this.buyInfo)
            },
            "initCgi": function() {
                var e = this.buyInfo;
                e.appids = e.appid.split(","),
                e.appid = e.appids[0],
                this.session = new s({
                    "openid": e.openid,
                    "openkey": e.openkey || "nokey",
                    "sessionid": e.session_id || "hy_gameid",
                    "sessiontype": e.session_type || "st_dummy"
                }),
                this.cgi = new o({
                    "appid": e.appid,
                    "report": f,
                    "sandbox": ~~e.sandbox,
                    "sessionObj": this.session,
                    "webversion": "minipayv2",
                    "aid": e.aid,
                    "pf": e.pf,
                    "pfkey": e.pfkey
                })
            },
            "getCgi": function() {
                return this.cgi
            },
            "getSession": function() {
                return this.session
            },
            "getPublicParams": function() {
                var e = {
                    "isusempaymode": "1",
                    "zoneid": this.buyInfo.zoneid || "0"
                };
                return this.buyInfo.coupon_id && this.buyInfo.coupon_id.length > 10 && (e.sp_info = this.buyInfo.coupon_id),
                p.getLoginStatus().wechat && this.buyInfo.wxappid && (e.wx_appid = this.buyInfo.wxappid || ""),
                e
            },
            "getWechatNick": function(e) {
                var n = this.getSession()
                  , t = {
                    "appid": u.wxAppid,
                    "get_detail": 2,
                    "openid": encodeURIComponent(n.openid),
                    "access_token": encodeURIComponent(n.openkey)
                };
                a.fn.getParam("canGetNick") ? (g.register("getNickname", function(n) {
                    a.lang.isFunction(e) && e({
                        "nickname": n
                    })
                }),
                g.notify("messageCallback", {
                    "key": "getNickname"
                })) : o.get(String.format("//{domain}pay.qq.com/cgi-bin/account/get_wechat_userinfo.cgi?" + a.req.serializeParam(t), {
                    "domain": c.isSandbox || c.isDev ? "sandbox." : ""
                }), function(n, t, i) {
                    var o = i && i.responseText ? JSON.parse(i.responseText) : {};
                    o = !~~o.resultcode && o.resultinfo.obj,
                    a.lang.isFunction(e) && e(o)
                }
                .bind(this))
            },
            "getQQNick": function() {
                var e = null;
                return function(n, t) {
                    t = t || {};
                    var i = this.getCgi();
                    return e ? n(t.getAll ? e : e.nick) : void i.wechatQuery({
                        "cmd": "1"
                    }, function(o) {
                        if (~~o.ret)
                            o = !1;
                        else {
                            var s = decodeURIComponent(o.nick).replace(/□/g, "");
                            o.nick = a.fn.getStringWidth(s) > 16 ? a.fn.trimToWidth(s, 14) + "..." : s,
                            e = o,
                            h.setDisplayInfoByOpenid(i.sessionObj.openid, {
                                "uin": a.fn.desensitize(o.provide_uin),
                                "nick": o.nick
                            }),
                            h.setDisplayInfoByOpenid(o.provide_uin, {
                                "uin": a.fn.desensitize(o.provide_uin),
                                "nick": o.nick
                            })
                        }
                        a.lang.isFunction(n) && n(t.getAll ? o : o.nick)
                    })
                }
            }(),
            "isAllowSend": function() {
                var e = "true" === this.buyInfo.disableSend;
                return !e && (p.getLoginStatus().accesstoken ? !!l.getQQAppid() : p.getLoginStatus().ptlogin || p.getLoginStatus().pskey)
            }
        }),
        e.exports = i
    },
    "52088519": function(e, n, t) {
        function i(e) {
            if (e = e || {},
            this.opt = e,
            this.mount = e.mount,
            this.unmount = e.unmount,
            this.cgi = e.cgi,
            this.provide_uin = e.provide_uin,
            this.isNewMcard = e.isNewMcard,
            this.configName = e.configName,
            this.setConfig = e.setConfig,
            this.onSuccess = e.onSuccess || s,
            this.onPending = e.onPending || s,
            this.onFail = e.onFail || s,
            this.onNoResult = e.onNoResult || s,
            this.onError = e.onError || s,
            this.onContinue = e.onContinue || s,
            this.billNo = e.billNo || "",
            this.portalNo = e.portalNo || "",
            this.resultQueryVm = null,
            !this.billNo)
                throw Error("billNo must be provide");
            this.init()
        }
        var o = t(4)
          , s = (t(1),
        o.fn.emptyFunc)
          , a = t(80576922)
          , r = t(79775620)
          , c = t(10);
        o.fn.extend(i.prototype, {
            "init": function() {
                this.initConfig(),
                this.mount(a.create(this.configName)),
                c("mcard.query.pv")
            },
            "initConfig": function() {
                var e = this
                  , n = this.cgi;
                this.setConfig({
                    "onInit": function(n) {
                        e.resultQueryVm = n
                    },
                    "onQuery": function(t) {
                        n.mobileGetCardBillInfo({
                            "provide_uin": e.provide_uin,
                            "billno": e.billNo,
                            "mcard_pay_mode": e.isNewMcard ? "1" : "0"
                        }, function(n) {
                            if (~~n.ret)
                                t.queryDone(a.ENUM_STATUS.PENDING),
                                t.setSubInfo("");
                            else
                                switch (n.state) {
                                case 1003:
                                case 1005:
                                case 1008:
                                case 1009:
                                case 1012:
                                case 4:
                                case 9:
                                    t.setInfo("对不起，支付失败"),
                                    t.setSubInfo(""),
                                    t.queryDone(a.ENUM_STATUS.FAIL);
                                    break;
                                case 1006:
                                case 1102:
                                case 2:
                                    t.setInfo("");
                                    var i = "";
                                    i = e.getMcardInfo(n),
                                    n.provide_count && t.setExtraInfo("realAmount", n.provide_count),
                                    t.setSubInfo(i),
                                    t.queryDone(a.ENUM_STATUS.SUCCESS);
                                    break;
                                case 1103:
                                    o.math.sub(e.opt.price, o.math.div(n.mpay_total_amount, 100));
                                    t.setInfo(">.<充值卡金额不足支付订单，请重新购买"),
                                    t.setSubInfo("此次交易不扣费，充值卡的金额已存入您的充值卡账户余额"),
                                    t.setExtraInfo("mcardDetail", e.getMcardInfo(n)),
                                    t.queryDone(a.ENUM_STATUS.ERROR),
                                    e.onContinue();
                                    break;
                                case 1007:
                                case 1011:
                                case 3:
                                default:
                                    t.queryDone(a.ENUM_STATUS.PENDING),
                                    t.setSubInfo("")
                                }
                        })
                    },
                    "onPending": function(e) {},
                    "onSuccess": function(n) {
                        e.onSuccess(n.getInfo(), n.getSubInfo(), n.getExtraInfo())
                    },
                    "onNoResult": function(n) {
                        n.setStatus(a.ENUM_STATUS.ERROR),
                        n.setInfo("未查询到充值卡支付结果"),
                        e.onNoResult(n.getInfo(), n.getSubInfo())
                    },
                    "onError": function(n) {
                        e.onError(n.getInfo(), n.getSubInfo(), n.getExtraInfo())
                    },
                    "onFail": function(n) {
                        e.onFail(n.getInfo(), n.getSubInfo())
                    }
                })
            },
            "getMcardInfo": function(e) {
                var n = this
                  , t = "";
                return n.isNewMcard && e.mpay_total_amount > 0 && (t += r({
                    "name": "充值卡账户余额:",
                    "content": o.math.div(e.mpay_total_amount, 100)
                })),
                e.mpay_card_amount > 0 && (t += r({
                    "noEm": !0,
                    "name": "当前充值卡面额:",
                    "content": o.math.div(e.mpay_card_amount, 100)
                })),
                t
            },
            "onDestroy": function() {
                o.fn.stop(),
                this.resultQueryVm.destroy(),
                this.resultQueryVm = null,
                this.unmount()
            },
            "destroy": function() {
                this.onDestroy()
            }
        }),
        e.exports = i
    },
    "53578085": function(e, n, t) {
        var i = t(1)
          , o = t(111121174)
          , s = null
          , a = "_cp__load__"
          , r = 0;
        e.exports = {
            "show": function() {
                if (s = document.getElementById(a))
                    i(s).css({
                        "display": "block"
                    });
                else {
                    var e = document.createElement("div");
                    e.id = a,
                    document.body.appendChild(e),
                    e.appendChild(i.parseHTML(o()))
                }
                r++
            },
            "hide": function(e) {
                r--,
                e && (r = 0),
                r > 0 || i(document.getElementById(a)).css({
                    "display": "none"
                })
            },
            "remove": function() {
                r = 0,
                document.body.removeChild(document.getElementById(a))
            }
        }
    },
    "54142212": function(e, n, t) {
        var i = t(82760872)
          , o = t(4)
          , s = t(1)
          , a = t(100835382)
          , r = t(119561448)
          , c = t(43847285)
          , l = t(117821206)
          , u = o.fn.getParam("sandbox")
          , d = "//midas.gtimg.cn/mtob/web/channel-web-sdk/jssdk/mtob-channel-api.umd.js"
          , p = !1
          , h = t(84811753)
          , f = t(103146681)
          , m = t(87145282);
        t(68682076);
        var g = function(e, n, t) {
            a.apply(this, arguments),
            this.init()
        }
          , v = {
            "init": function() {
                this.initVm(),
                this.initChannel()
            },
            "initChannel": function() {
                var e = this;
                return this.fetchAmount(),
                this.calculatePrice(),
                this.refreshUuid(),
                this.store.isInterfaceDisabled() ? (this.vm.isDisable = !0,
                void (this.vm.disableText = this.store.getChannelDisableText())) : 0 == this.amount ? (this.vm.isDisable = !0,
                void (this.vm.disableText = "请完善充值信息")) : (this.vm.isDisable = !1,
                void setTimeout(function() {
                    return p ? void e.initedChannel() : void s.getScript(d, function() {
                        p = !0,
                        e.initedChannel()
                    })
                }, 0))
            },
            "initedChannel": function() {
                this.remitpayApi && (this.remitpayApi.destroy(),
                this.remitpayApi = null);
                var e = this
                  , n = window.MtobChannelApi.init({
                    "params": {
                        "appID": this.store.info.offer_id,
                        "userID": this.store.session.openid,
                        "channel": this.store.channel,
                        "channelParams": {},
                        "sessionID": this.uuid,
                        "reqID": this.uuid
                    },
                    "envOptions": {
                        "env": 2 == u ? "dev" : 1 == u ? "sandbox" : "release"
                    },
                    "timeout": 5e3
                });
                this.remitpayApi = n,
                n.on("ready", function() {
                    e.vm.loading = !1
                }),
                n.on("resize", function(e) {}),
                n.on("status", function(e) {}),
                n.on("timeout", function() {
                    e.store.onFail({
                        "ret": 9901,
                        "msg": "系统繁忙，请稍后再试"
                    })
                }),
                n.registerMethod("createChannelOrder", function(n, t) {
                    "remitpay" === n.channel && e.buy({
                        "user_openname": n.data.userOpenname
                    }, t)
                }),
                n.attach({
                    "target": document.querySelector("#channelWebIframe")
                })
            },
            "calculatePrice": function() {
                var e = this.store.getPrice().price;
                this.price = this.store.getPrice(o.discount.checkHasDiscount(e, "remitpay") ? this.channelObj.discount : void 0, this.coupon).price
            },
            "fetchAmount": function() {
                this.amount = this.store.getAmount()
            },
            "onChange": function() {
                this.initChannel()
            },
            "getVmConfig": function() {
                return o.fn.extend({
                    "$id": "remitpay-controller",
                    "loading": !0,
                    "isDisable": !1,
                    "disableText": "请完善充值信息"
                }, this.getPubVmConfig())
            },
            "initVm": function() {
                this.vm = s.define(this.getVmConfig())
            },
            "buy": function(e, n) {
                if (e = e || {},
                0 != this.store.getAmount() && e.user_openname) {
                    var t = {
                        "uuid": this.uuid,
                        "pay_method": this.channelObj.channel
                    };
                    o.fn.extend(t, e),
                    r.show({
                        "opacity": "0"
                    }),
                    this.store.buy(t, function(e) {
                        r.hide();
                        try {
                            return this.handlerBuy(e, t, n)
                        } catch (i) {
                            return !0
                        }
                    }
                    .bind(this))
                }
            },
            "handlerBuy": function(e, n, t) {
                var i, s = this;
                return ~~e.ret ? (i = new l({
                    "errCode": e.ret,
                    "errMsg": e.msg,
                    "oriParams": n,
                    "2022": function() {
                        var i = e.info
                          , a = s.store.getCgi().sessionObj.getSessionParam();
                        new c({
                            "url": i.verify_url,
                            "fk_info": i.fk_info,
                            "fk_amt": i.fk_amt,
                            "jiazhang_url": i.jiazhang_url,
                            "veri_url": i.veri_url,
                            "qrcode_url": i.qrcode_url,
                            "cgi": s.store.getCgi(),
                            "accountType": "wc_actoken" === a.session_type ? "wx" : "qq",
                            "onLoad": function() {},
                            "onRcRestrict": function(e) {
                                e = e || {},
                                s.store.rcRestrict(e)
                            },
                            "onVerifyDone": function(e) {
                                e = e || {},
                                s.vm.qrcodeLoading = !0,
                                s.vm.qrcodeReload = !1,
                                o.fn.extend(n, e),
                                s.buy(n, t)
                            },
                            "onDestroy": function() {
                                t && t({
                                    "name": e.ret,
                                    "message": e.msg
                                }, null)
                            }
                        })
                    }
                }),
                !(!i || !i.canHandle()) && (i.exec(),
                !0)) : (t && t(null, {
                    "channel": "remitpay",
                    "data": {
                        "bankAccount": e.info.channel_info.bank_account,
                        "bankFullName": e.info.channel_info.bank_fullname,
                        "bankOpenName": e.info.channel_info.bank_openname,
                        "orderId": e.info.channel_info.order_id,
                        "referenceId": e.info.channel_info.referece_id,
                        "price": "" + s.price
                    }
                }),
                !0)
            },
            "onDestroy": function() {
                this.remitpayApi && this.remitpayApi.destroy(),
                this.remitpayApi = null,
                a.prototype.removeListener.call(this),
                this.comet && this.comet.abort(),
                a.prototype.destroy.call(this),
                this.vm = null,
                r.hide()
            },
            "handlePriceLoading": function(e) {
                if (!(e instanceof h))
                    throw Error("action must be instance of Action");
                var n = this;
                switch (e.getType()) {
                case f:
                    this.vm && (this.vm.priceLoading = !0),
                    this.lock();
                    break;
                case m:
                    this.vm && setTimeout(function() {
                        n.vm.priceLoading = !1
                    }),
                    this.unlock()
                }
            }
        };
        o.inherits(g, a),
        o.fn.extend(g.prototype, v),
        g.create = function(e, n, t) {
            return new g(e,n,t)
        }
        ,
        g.getTemplate = function(e) {
            return i(e)
        }
        ,
        e.exports = g
    },
    "54152206": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div ms-controller="qqwallet-controller">\n    <div class="coupon" ms-if="coupon" ms-html="couponHTML"></div>\n    <div class="qr-code-txt">\n        <i class="icon-qq"></i>\n        手Q扫码，支付\n        <em ms-if="!priceLoading">{{price}}</em>\n        <span ms-if="priceLoading" ms-html="priceLoadingTplHtml"></span>\n        元\n        <span ms-if="isQB&&savePrice"> (已省 <em>{{savePrice}}</em>元)</span>\n    </div>\n    <div class="qr-code-area" ms-visible="showQrcode">\n        <div class="qr-code-container qq" ms-visible="!disableQrcode">\n            <div id="qr-code-qqwallet" style="display: none"></div>\n            <img ms-if="url" ms-attr-src="url" ms-on-load="qrcodeLoaded" ms-on-error="qrcodeLoadFail">\n            <div class="qr-code-mask" ms-if="qrcodeLoading||qrcodeReload||priceLoading"></div>\n            <div class="qr-code-loading" ms-if="qrcodeLoading||priceLoading">\n                <i></i>\n                <p>加载中，请稍后</p>\n            </div>\n            <div class="qr-code-reload" ms-if="qrcodeReload" ms-on-click="refreshQrcode">\n                <i></i>\n                <p>重新获取二维码</p>\n            </div>\n        </div>\n        <div class="qr-code-container qq" ms-visible="disableQrcode&&!disableText"></div>\n    </div>\n    <div class="qr-code-area" ms-visible="showScaned">\n        <i class="icon-phone"></i>\n        <p>请在手机上进行支付</p>\n        <a href="javascript:void(0);" ms-on-click="backQrcode">返回二维码</a>\n    </div>\n    <div class="qr-code-area" ms-visible="disableQrcode && disableText">\n        <i class="icon-phone"></i>\n        <p>{{disableText}}</p>\n        <a href="javascript:void(0);" ms-on-click="backQrcode">刷新二维码</a>\n    </div>\n    <div class="qr-code-wrapper" ms-if="isQB&&tips">\n        <p class="tips icon-tips qr-code-tips"><i class="icon-txt"></i>\n            {{tips}}\n        </p>\n    </div>\n    <div class="qr-code-txt" ms-if="terms.length > 0" style="padding-top: 8px;">\n        <p class="tips sub-tips">支付前阅读并同意\n            <span ms-repeat="terms">\n                <a href="#" ms-click="openTerm(el,$event)">{{el.termName}}</a>\n            </span>\n        </p>\n    </div>\n</div>';
            return __p
        }
    },
    "54520283": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div class="cp-body result-body result-waiting bank-waiting" style="padding: 80px 206px 60px 206px;">\n    <div class="info-area">\n        <h2>腾讯充值入口</h2>\n        <div style="margin: 10px 0 15px; width: 130; height: 130;">\n            <img width="130" height="130" src="//midas.gtimg.cn/h5pay/images/webpay/game/dqscan/scan-dnfdq.png" alt="">\n        </div>\n        <h2>微信/手Q 扫一扫</h2>\n        <h3>安全快捷充值点券</h3>\n    </div>\n    <div class="info-area" style="text-align: left;">\n        <p style="font-size: 14px;"><i class="icon-txt"></i>温馨提示</p>\n        <p class="sub-info">· 充值金额为100的倍数，最小充值金额为100点券。<br>· 兑换比例：1元=1Q币=100点券</p>\n    </div>\n    <!-- <div class="warm-prompt open">\n        <h4><i class="icon-info"></i>温馨提示 <i class="icon-arrow"></i></h4>\n        <ul class="warm-prompt-detail">\n            <li>充值金额为100的倍数，最小充值金额为100点券。</li>\n            <li>兑换比例：1元=1Q币=100点券</li>\n        </ul>\n    </div> -->\n</div>';
            return __p
        }
    },
    "54698897": function(e, n, t) {
        var i = t(4)
          , o = t(112745811)
          , s = {
            "ParamsService": function(e, n, t) {
                var i = t.appids || (t.appid || "").split(",")
                  , s = t.wxappid || "";
                n = n || i[0];
                var a, r = (t.groupid || "").split(","), c = (t.inner_productid || "").split(","), l = {};
                return s && (l["wx_appid"] = s),
                e == o.MONTH && (l.query_scope = "include_continuous"),
                avalon.each(i, function(i, s) {
                    if (n == s)
                        return c.length > i && c[i] && (l["inner_productid"] = c[i]),
                        t.drm_info ? l["drm_info"] = t["drm_info"] : r.length > i && r[i] && (a = e == o.MONTH ? "month_group" : e == o.QB ? "qbqd_group" : e == o.GOODS ? "goods_group" : "currency_group",
                        l["drm_info"] = encodeURIComponent(String.format("{groupkey}={groupid}", {
                            "groupkey": a,
                            "groupid": r[i]
                        })),
                        "month_group" === a && (l["drm_info"] = l["drm_info"] + encodeURIComponent("&version=3.0"))),
                        !1
                }),
                l
            },
            "RecoveryAddress": function() {
                var e = i.fn.getParam("sandbox");
                return ("1" == e || "2" == e ? "//sandbox.midas.gtimg.cn/" : "//midas.gtimg.cn/") + "midas/minipay_v2/js/app/recovery/{appid}.js"
            },
            "GetBankSubChannel": function(e) {
                var n = e.appid
                  , t = e.sessionObj.openid
                  , o = i.fn.safeGet(window.__midasStaticConfig_midas_webpay, "itemMap.webpay.bank82_offerid", [])
                  , s = i.fn.safeGet(window.__midasStaticConfig_midas_webpay, "itemMap.webpay.bank82_openid", [])
                  , a = !1
                  , r = s.some(function(e) {
                    return e === t
                })
                  , c = o.some(function(e) {
                    return e === n
                });
                return (r || "*" === s[0]) && (a = !0),
                (c || "*" === o[0]) && (a = !0),
                a ? "82" : "80"
            },
            "UpdateBankList": function(e) {
                e.getBankList({}, function(e) {
                    if (!~~e.ret) {
                        var n = window.__BANK_CONFIG;
                        avalon.each(n, function(e, n) {
                            n.credit && delete n.credit,
                            n.debit && delete n.debit,
                            n.cardTypes && delete n.cardTypes
                        }),
                        e.bank_list.filter(function(e) {
                            return "2" === e.bank_trans_flag
                        }).forEach(function(e) {
                            var t = e.card_type
                              , i = e.bank_sname.toLowerCase();
                            n[i].cardTypes = n[i].cardTypes || [],
                            "1" === t && (n[i].cardTypes.push("debit"),
                            n[i].debit = {
                                "payTypes": ["bank"],
                                "bank": i + "_" + e.card_type + "_" + e.bank_trans_flag
                            }),
                            "2" === t && (n[i].cardTypes.push("credit"),
                            n[i].credit = {
                                "payTypes": ["bank"],
                                "bank": i + "_" + e.card_type + "_" + e.bank_trans_flag
                            })
                        });
                        var t = window.__B2B_BANK_CONFIG;
                        avalon.each(t, function(e, n) {
                            n.credit && delete n.credit,
                            n.debit && delete n.debit,
                            n.cardTypes && delete n.cardTypes
                        }),
                        e.bank_list.filter(function(e) {
                            return "1" === e.bank_trans_flag
                        }).forEach(function(e) {
                            var n = e.card_type
                              , i = e.bank_sname.toLowerCase();
                            t[i].cardTypes = t[i].cardTypes || [],
                            "1" === n && (t[i].cardTypes.push("debit"),
                            t[i].debit = {
                                "payTypes": ["bank"],
                                "bank": i + "_" + e.card_type + "_" + e.bank_trans_flag
                            }),
                            "2" === n && (t[i].cardTypes.push("credit"),
                            t[i].credit = {
                                "payTypes": ["bank"],
                                "bank": i + "_" + e.card_type + "_" + e.bank_trans_flag
                            })
                        })
                    }
                })
            }
        };
        e.exports = s
    },
    "55004913": function(e, n, t) {
        var i = t(1)
          , o = t(18)
          , s = function(e) {
            this.controllerId = e.controllerId,
            this.opts = {},
            this.parentVM = e.parentVM,
            this.loadConfig = e.loadVMConfig.bind(this),
            this.callbacks = e.callbacks,
            this._handlers = {},
            this.vm = null
        };
        i.mix(s.prototype, o),
        i.mix(s.prototype, {
            "setOpts": function(e) {
                this.opts = i.mix(this.opts, e)
            },
            "createVm": function(e) {
                if (this.vm) {
                    var n = this;
                    i.each(e, function(e, t) {
                        n.vm[e] = t
                    })
                } else
                    this.vm = i.define(i.mix({
                        "$id": this.controllerId,
                        "$skipArray": []
                    }, e, this.callbacks));
                return this.vm
            },
            "loadVMConfig": function() {
                var e = this;
                this.loadConfig(function(n) {
                    i.nextTick(function() {
                        e.emit("vmReady", n)
                    })
                })
            }
        }),
        e.exports = s
    },
    "55660113": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div ms-controller="bank-controller">\n    <!-- 抵扣券 -->\n    <div class="coupon" ms-if="coupon" ms-html="couponHTML"></div>\n    <!-- loading -->\n    <div ms-if="loading" id="_webpay__dialog__load__">\n        <div class="mdsweb-loading-wrapper abs">\n            <div class="mdsweb-loading">\n                <div class="dot"></div>\n                <div class="dot"></div>\n                <div class="dot"></div>\n            </div>\n        </div>\n    </div>\n    <div>\n        <!-- 状态提示 -->\n        <p class="choose-type tips icon-tips error" ms-if="tips!=\'\'"><i class="icon-warn"></i>{{tips}}</p>\n        <div class="left-money-warn" ms-if="isDisable">\n            <p class="tips sub-tips"><i class="icon-error"></i> 温馨提示：{{disableText}}</p>\n        </div>\n\n        <!-- 银行列表 -->\n        <iframe ms-if="!isDisable" frameborder="0" name="channelWebIframe" id="b2bChannelWebIframe" scrolling="no"\n            style="width: 100%;"></iframe>\n\n        <!-- 支付按钮 -->\n        <div class="oper-to-pay" style="margin-top: 0px;">\n            <!-- 没有服务条款 -->\n            <a ms-on-click="pay" ms-class="btn btn-default" ms-class-1="btn-dis:(disableSubmit||amount==0)"\n                ms-class-2="loading:(paying||priceLoading)" href="#" ms-if="terms.length==0">\n                <span ms-if="!paying&&!priceLoading">去支付 <span>{{price}}</span>元</span>\n                <span><i class="icon-btn-loading"></i></span>\n            </a>\n            <!-- 有服务条款 -->\n            <a ms-on-click="pay" ms-class="btn btn-default" ms-class-1="btn-dis:(disableSubmit||amount==0)"\n                ms-class-2="loading:(paying||priceLoading)" href="#" style="min-width: 180px;" ms-if="terms.length>0">\n                <span ms-if="!paying&&!priceLoading">同意协议并支付 <span>{{price}}</span>元</span>\n                <span><i class="icon-btn-loading"></i></span>\n            </a>\n        </div>\n        <!-- 服务条款 -->\n        <div class="left-money-warn" ms-if="terms.length > 0">\n            <p class="tips sub-tips">支付前阅读并同意\n                <span ms-repeat="terms">\n                    <a href="#" ms-click="openTerm(el,$event)">{{el.termName}}</a>\n                </span>\n            </p>\n        </div>\n    </div>\n</div>';
            return __p
        }
    },
    "56711316": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div ms-controller="bank-controller">\n    <div class="coupon" ms-if="coupon" ms-html="couponHTML"></div>\n    <div>\n        <ms:bankselector config="bankData" on-selected-bank="onSelectedBank"></ms:bankselector>\n    </div>\n    <p class="choose-type tips icon-tips error" ms-if="tips!=\'\'"><i class="icon-warn"></i>{{tips}}</p>\n    <div class="oper-to-pay">\n        <!-- 没有服务条款 -->\n        <a ms-on-click="pay" ms-class="btn btn-default" ms-class-1="btn-dis:(disableSubmit||amount==0)"\n            ms-class-2="loading:(paying||priceLoading)" href="#" ms-if="terms.length==0">\n            <span ms-if="!paying&&!priceLoading">去支付 <span>{{price}}</span>元</span>\n            <span><i class="icon-btn-loading"></i></span>\n        </a>\n        <!-- 有服务条款 -->\n        <a ms-on-click="pay" ms-class="btn btn-default" ms-class-1="btn-dis:(disableSubmit||amount==0)"\n            ms-class-2="loading:(paying||priceLoading)" href="#" style="min-width: 180px;" ms-if="terms.length>0">\n            <span ms-if="!paying&&!priceLoading">同意协议并支付 <span>{{price}}</span>元</span>\n            <span><i class="icon-btn-loading"></i></span>\n        </a>\n    </div>\n    <div class="left-money-warn" ms-if="terms.length > 0">\n        <p class="tips sub-tips">支付前阅读并同意\n            <span ms-repeat="terms">\n                <a href="#" ms-click="openTerm(el,$event)">{{el.termName}}</a>\n            </span>\n        </p>\n    </div>\n</div>';
            return __p
        }
    },
    "56851482": function(e, n, t) {
        var i = t(1)
          , o = t(121508273)
          , s = t(4)
          , a = (3 * Math.random() + 1).toString().replace(".", "")
          , r = t(10)
          , c = document.all && !window.XMLHttpRequest
          , l = {
            "$skipArray": ["step", "_defaultValue", "_pv"],
            "value": 0,
            "disabled": !1,
            "min": NaN,
            "max": NaN,
            "step": 1,
            "_defaultValue": 0,
            "_pv": "",
            "onChange": i.noop,
            "click": i.noop,
            "width": 150,
            "unit": "",
            "id1": a,
            "btn1": s.fn.uuid(),
            "btn2": s.fn.uuid(),
            "onInit": i.noop
        }
          , u = i.mix(l, {
            "_setValue": function(e) {
                if (document.getElementById(this.id1).value = e,
                this.value = e,
                !c) {
                    var n = document.getElementById(this.btn1)
                      , t = document.getElementById(this.btn2);
                    i(n).removeClass("disabled"),
                    n.removeAttribute("disabled"),
                    i(t).removeClass("disabled"),
                    t.removeAttribute("disabled")
                }
            },
            "keydown": function(e) {
                var n = [46, 37, 38, 40, 39, 8];
                if (n.indexOf(e.which) == -1) {
                    if (!isNaN(this.max)) {
                        var t = this.max + "";
                        if (e.target.value.length >= t.length && !this.isSelect())
                            return void e.preventDefault()
                    }
                    e.which >= 96 && e.which <= 105 || e.which >= 48 && e.which <= 57 || e.preventDefault()
                }
            },
            "isSelect": function() {
                try {
                    if (window.getSelection) {
                        var e = window.getSelection();
                        return "" != e.toString()
                    }
                    if (document.selection) {
                        var n = document.selection.createRange();
                        return str = n.text,
                        "" != str
                    }
                } catch (t) {}
            },
            "focus": function(e) {
                this._pv = e.target.value
            },
            "blur": function(e) {
                var n = document.getElementById(this.id1).value;
                (isNaN(n) || "" == n) && (n = this._defaultValue),
                this._setValue(n),
                r("spiner.input.blur", {
                    "action": n
                }),
                this._pv != this.value && this.change(e)
            },
            "change": function(e) {
                var n = Number(this.value);
                isNaN(this.max) || (n = n > this.max ? this.max : this.value),
                isNaN(this.min) || (n = n < this.min ? this.min : n),
                n -= n % this.step,
                this._setValue(n),
                this.onChange.call(null, this.value)
            },
            "decrease": function(e) {
                var n = Number(this.value) - this.step
                  , t = "i" === e.target.nodeName.toLowerCase() ? e.target.parentNode : e.target;
                return !isNaN(this.min) && n < this.min ? void (c || (i(t).addClass("disabled"),
                t.setAttribute("disabled", "true"))) : (r("spiner.decrease.click"),
                this._setValue(n),
                void this.onChange.call(null, this.value, "decrease"))
            },
            "setAmount": function(e) {
                var n = Number(e);
                isNaN(this.max) || (n = n > this.max ? this.max : n),
                isNaN(this.min) || (n = n < this.min ? this.min : n),
                n -= n % this.step,
                this._setValue(n),
                this.onChange.call(null, this.value, "setAmount")
            },
            "increase": function(e) {
                var n = "i" === e.target.nodeName.toLowerCase() ? e.target.parentNode : e.target
                  , t = Number(this.value) + this.step;
                return !isNaN(this.max) && t > this.max ? void (c || (i(n).addClass("disabled"),
                n.setAttribute("disabled", "true"))) : (r("spiner.increase.click"),
                this._setValue(t),
                void this.onChange.call(null, this.value, "increase"))
            },
            "$template": o(),
            "$init": function(e, n) {
                this._defaultValue = e.value,
                "function" == typeof e.onInit && e.onInit(e)
            }
        });
        i.component("ms:spiner", u),
        e.exports = {
            "create": function(e) {
                return '<ms:spiner config="' + e + '" on-init="onSpinerInit"></ms:spiner>'
            }
        }
    },
    "57188951": function(module, exports) {
        !function() {
            function _fixedLengthWithPrefix(e, n, t) {
                n = n || 2,
                t = t || "0";
                var i = [];
                return i[n] = e,
                i.join(t).slice(-n)
            }
            function _firstLetterUpper(e) {
                return e += "",
                e.substr(0, 1).toUpperCase() + e.substr(1).toLowerCase()
            }
            function _jsonFilter(e) {
                var n = Object.prototype.toString.call(e);
                if (null === e || e instanceof String || e instanceof Number || e instanceof Boolean || e instanceof Date || {
                    "[object String]": 1,
                    "[object Number]": 1,
                    "[object Boolean]": 1,
                    "[object Date]": 1
                }[n])
                    return e;
                if (void 0 !== e) {
                    if (e === window)
                        return "[object DOMWindow]";
                    if (e === document)
                        return "[object HTMLDocument]";
                    if ("function" != typeof e.constructor)
                        return e && "string" == typeof e.tagName ? "[object HTML" + _firstLetterUpper(e.tagName) + "Element]" : void 0;
                    if (!{
                        "[object Object]": 1,
                        "[object Array]": 1
                    }[n])
                        return n;
                    if (_jsonHash[e.__CASHIER_JSON_HASH] !== e) {
                        for (var t = LIB.getIntRandom(); _jsonHash[t]; )
                            t = LIB.getIntRandom();
                        return _jsonHash[e.__CASHIER_JSON_HASH = t] = e,
                        e
                    }
                }
            }
            function _jsonQuote(e) {
                return _jsonEscapable.lastIndex = 0,
                '"' + (_jsonEscapable.test(e) ? e.replace(_jsonEscapable, function(e) {
                    var n = _jsonMetaChar[e];
                    return "string" == typeof n ? n : "\\u" + _fixedLengthWithPrefix(e.charCodeAt(0).toString(16), 4)
                }) : e) + '"'
            }
            function _jsonGetString(e) {
                e = _jsonFilter(e);
                var n, t, i, o = Object.prototype.toString.call(e);
                if (void 0 !== e) {
                    if (null === e || e instanceof Boolean || "[object Boolean]" === o)
                        return String(e);
                    if (e instanceof String || "[object String]" === o)
                        return _jsonQuote(e);
                    if (e instanceof Number || "[object Number]" === o)
                        return isFinite(e) ? String(e) : "null";
                    if (e instanceof Date || "[object Date]" === o)
                        return isFinite(e.valueOf()) ? _jsonQuote(e.getUTCFullYear() + "-" + _fixedLengthWithPrefix(e.getUTCMonth() + 1) + "-" + _fixedLengthWithPrefix(e.getUTCDate()) + "T" + _fixedLengthWithPrefix(e.getUTCHours()) + ":" + _fixedLengthWithPrefix(e.getUTCMinutes()) + ":" + _fixedLengthWithPrefix(e.getUTCSeconds()) + "." + _fixedLengthWithPrefix(e.getUTCMilliseconds(), 3) + "Z") : "null";
                    if (e instanceof Array || "[object Array]" === o) {
                        n = [];
                        for (var s = 0, a = e.length; s < a; s++)
                            n[s] = _jsonGetString(e[s]) || "null";
                        return delete _jsonHash[e.__CASHIER_JSON_HASH],
                        delete e.__CASHIER_JSON_HASH,
                        "[" + n.join(",") + "]"
                    }
                    if (e) {
                        n = [],
                        i = Object.hasOwnProperty;
                        for (var r in e)
                            "__CASHIER_JSON_HASH" != r && i.call(e, r) && (t = _jsonGetString(e[r])) && n.push(_jsonQuote(r) + ":" + t);
                        return delete _jsonHash[e.__CASHIER_JSON_HASH],
                        delete e.__CASHIER_JSON_HASH,
                        "{" + n.join(",") + "}"
                    }
                    return "null"
                }
            }
            function _fireUnloadEvent() {
                LIB.unload.notify()
            }
            function _xsDispatch(e, n) {
                if ("string" == typeof e && 0 == e.indexOf(_XS_TAG)) {
                    e = e.substring(_XS_TAG.length);
                    var t, i = JSON.parse(e), o = i.port;
                    (t = _xsInstance[o]) && t._handle(i, n, e)
                }
            }
            function _mergeDuration(e, n) {
                return e._total = e._total || e.duration * (e.rate - 1) || 0,
                e._total += n.duration || 0,
                e.duration = Math.max(Math.round(e._total / e.rate), 1),
                e
            }
            function _xsend(e, n) {
                _dialogXStream.closed || DLG._call(_dialogXStream, e, n)
            }
            function _handleLocal(e, n) {
                _dialogXStream.closed || (_methodObservers[e].notify(n),
                DLG._call(_dialogXStream, e, n))
            }
            function _callClosure(e) {
                _methodObservers[e] = new Observer;
                var n = function(n) {
                    _handleLocal(e, n)
                };
                return n.on = function(n) {
                    _methodObservers[e].subscribe(n)
                }
                ,
                n
            }
            var thisAPI = window.cashier = {}
              , LIB = thisAPI.LIB = {}
              , VER = thisAPI.VER = {
                "dialog": 1,
                "api": 1
            };
            LIB.err = function() {
                window.debug && (window.console && console.error && Function.prototype.apply.call(console.error, console, Array.prototype.slice.call(arguments, 0)),
                "string" == typeof arguments[0] && alert(arguments[0]))
            }
            ,
            LIB.warn = function() {
                window.debug && window.console && console.warn && Function.prototype.apply.call(console.warn, console, Array.prototype.slice.call(arguments, 0))
            }
            ,
            LIB.log = function() {
                window.debug
            }
            ,
            LIB.getIntRandom = function() {
                return Math.round(Math.random() * (new Date).getTime()) % 9e9 + 1e9
            }
            ,
            LIB.emptyFn = function() {}
            ,
            LIB.getParam = function(e, n) {
                var t = new RegExp("(?:^|\\?|#|&)" + e + "=([^&#]*)(?:$|&|#)","i")
                  , i = t.exec(n || location.href);
                return i ? i[1] : ""
            }
            ;
            var JSON = thisAPI.JSON = {}
              , _jsonHash = {}
              , _jsonEscapable = /[\\\"\x00-\x1f\x7f-\x9f\u00ad\u0600-\u0604\u070f\u17b4\u17b5\u200c-\u200f\u2028-\u202f\u2060-\u206f\ufeff\ufff0-\uffff]/g
              , _jsonMetaChar = {
                "\b": "\\b",
                "\t": "\\t",
                "\n": "\\n",
                "\f": "\\f",
                "\r": "\\r",
                '"': '\\"',
                "\\": "\\\\"
            }
              , _jsonInvisibleChar = /[\u0000\u00ad\u0600-\u0604\u070f\u17b4\u17b5\u200c-\u200f\u2028-\u202f\u2060-\u206f\ufeff\ufff0-\uffff]/g;
            JSON.stringify = function(e) {
                var n = _jsonGetString(e);
                return n
            }
            ,
            JSON.parse = function(text) {
                if (text = String(text),
                text && (_jsonInvisibleChar.lastIndex = 0,
                _jsonInvisibleChar.test(text) && (text = text.replace(_jsonInvisibleChar, function(e) {
                    return "\\u" + _fixedLengthWithPrefix(e.charCodeAt(0).toString(16), 4)
                })),
                /^[\],:{}\s]*$/.test(text.replace(/\\(?:["\\\/bfnrt]|u[0-9a-fA-F]{4})/g, "@").replace(/"[^"\\\n\r]*"|true|false|null|-?\d+(?:\.\d*)?(?:[eE][+\-]?\d+)?/g, "]").replace(/(?:^|:|,)(?:\s*\[)+/g, ""))))
                    try {
                        return new Function("return " + text)()
                    } catch (_) {
                        return eval("(" + text + ")")
                    }
                throw new SyntaxError("JSON.parse")
            }
            ,
            LIB.setTimeout = function(e, n, t, i) {
                return setTimeout(function() {
                    e.apply(t, i || [])
                }, n)
            }
            ,
            LIB.ua = function() {
                var e, n = {}, t = navigator.userAgent;
                return window.ActiveXObject ? (n.ie = 6,
                (window.XMLHttpRequest || t.indexOf("MSIE 7.0") >= 0) && (n.ie = 7),
                (window.XDomainRequest || t.indexOf("Trident/4.0") >= 0) && (n.ie = 8),
                t.indexOf("Trident/5.0") >= 0 && (n.ie = 9),
                t.indexOf("Trident/6.0") >= 0 && (n.ie = 10)) : document.getBoxObjectFor || "undefined" != typeof window.mozInnerScreenX ? (e = /(?:Firefox|GranParadiso|Iceweasel|Minefield).(\d+\.\d+)/i.exec(t),
                n.firefox = e ? parseFloat(e[1], 10) : 3.3) : navigator.taintEnabled ? window.opera && (n.opera = parseFloat(window.opera.version(), 10)) : (e = /AppleWebKit.(\d+\.\d+)/i.exec(t),
                n.webkit = e ? parseFloat(e[1], 10) : document.evaluate ? document.querySelector ? 525 : 420 : 419,
                (e = /Chrome.(\d+\.\d+)/i.exec(t)) || window.chrome ? n.chrome = e ? parseFloat(e[1], 10) : 2 : ((e = /Version.(\d+\.\d+)/i.exec(t)) || window.safariHandler) && (n.safari = e ? parseFloat(e[1], 10) : 3.3)),
                e = /CPU.+?OS (\d+(?:_\d+)?).+?like Mac OS X/i.exec(t),
                t.indexOf("iPod") >= 0 ? n.iPod = e ? parseFloat(e[1].replace(/_/g, "."), 10) : 1 : t.indexOf("iPhone") >= 0 ? n.iPhone = e ? parseFloat(e[1].replace(/_/g, "."), 10) : 1 : t.indexOf("iPad") >= 0 ? n.iPad = e ? parseFloat(e[1].replace(/_/g, "."), 10) : 1 : t.indexOf("Macintosh") >= 0 || t.indexOf("OS X") >= 0 ? (e = /(?:Mac )?OS X (\d+(?:_\d+)?)/i.exec(t),
                n.mac = e ? parseFloat(e[1].replace(/_/g, "."), 10) : 1) : t.indexOf("Window") >= 0 ? (e = /Windows NT (\d+(?:\.\d+)?)/i.exec(t),
                n.windows = e ? parseFloat(e[1], 10) : 1) : t.indexOf("Android") >= 0 ? (e = /Android (\d+(?:\.\d+)?)/i.exec(t),
                n.android = e ? parseFloat(e[1], 10) : 1) : t.indexOf("Linux") >= 0 && (n.linux = 1),
                n
            }();
            var Observer = LIB.Observer = function(e, n) {
                this._sender = e,
                this._timeout = +n || 0,
                this._subscriber = [],
                this._timer = 0
            }
            ;
            Observer.prototype.subscribe = function(e, n, t) {
                return "function" == typeof e && (this._subscriber.push({
                    "fn": e,
                    "self": n,
                    "context": t
                }),
                !0)
            }
            ,
            Observer.prototype.unsubscribe = function(e) {
                if ("function" != typeof e)
                    return !1;
                for (var n, t = this._subscriber, i = !1, o = 0; n = t[o]; o++)
                    if (n.fn == e) {
                        i = !0,
                        t = t.slice(0, o).concat(t.slice(o + 1));
                        break
                    }
                return !!i && (this._subscriber = t,
                !0)
            }
            ,
            Observer.prototype.notify = function(e) {
                var n = function() {
                    this._timer = 0;
                    for (var n, t = this._subscriber, i = 0; n = t[i]; i++)
                        n.fn.call(n.self, e, this._sender, n.context)
                };
                this._timeout ? (this._timer && clearTimeout(this._timer),
                this._timer = LIB.setTimeout(n, this._timeout, this)) : n.call(this)
            }
            ;
            var ReadyCall = LIB.ReadyCall = function() {
                this.isReady = !1,
                this._onReady = new Observer(this),
                this._first = !0,
                this._onFirst = new Observer(this)
            }
            ;
            ReadyCall.prototype.onReady = function(e) {
                this.isReady ? e() : this._onReady.subscribe(e),
                this._first && (this._onFirst.notify(),
                this._first = !1)
            }
            ,
            ReadyCall.prototype.ready = function() {
                this.isReady || (this.isReady = !0,
                this._onReady.notify())
            }
            ,
            ReadyCall.prototype.onFirst = function(e) {
                this._onFirst.subscribe(e)
            }
            ;
            var _eventList = [];
            LIB.attachEvent = function(e, n, t, i) {
                if (e && n && "function" == typeof t) {
                    i = i || {},
                    i.win = i.win || window;
                    var o = function(e) {
                        t.apply(i.self, [e || i.win.event].concat(i.args || []))
                    };
                    _eventList.push({
                        "el": e,
                        "type": n,
                        "cfn": o,
                        "fn": t
                    }),
                    e.attachEvent ? e.attachEvent("on" + n, o) : e.addEventListener && e.addEventListener(n, o, !1)
                }
            }
            ;
            var _crossEventList = {};
            LIB.fireCrossEvent = function(e, n) {
                var t;
                return !!_crossEventList[n] && ((t = _crossEventList[n]).fn.apply(t.opt.self, [e].concat(t.opt.args || [])),
                !0)
            }
            ,
            LIB.attachCrossEvent = function(e, n, t, i, o) {
                if (e && n && "function" == typeof t && i) {
                    if (i == window)
                        return LIB.attachEvent(e, n, t, o);
                    o = o || {};
                    for (var s = LIB.getIntRandom(); _crossEventList[s]; )
                        s = LIB.getIntRandom();
                    _crossEventList[s] = {
                        "fn": t,
                        "opt": o
                    },
                    i["_CASHIER_CROSS_EVENT_HANDLER_" + s] = window,
                    i["_CASHIER_CROSS_EVENT_TARGET_" + s] = e;
                    var a = new i.Function("evt","var win=window._CASHIER_CROSS_EVENT_HANDLER_" + s + ",ret=false,el=window._CASHIER_CROSS_EVENT_TARGET_" + s + ";if(win&&win.parent&&win.parent!=win&&win.cashier){try{ret=win.cashier.LIB.fireCrossEvent(evt||window.event," + s + ");}catch(_){}}if(!ret){el&&(el.removeEventListener?el.removeEventListener('" + n + "',arguments.callee,false):el.detachEvent&&el.detachEvent('on" + n + "',arguments.callee));try{delete window._CASHIER_CROSS_EVENT_HANDLER_" + s + ";delete window._CASHIER_CROSS_EVENT_TARGET_" + s + ";}catch(_){window._CASHIER_CROSS_EVENT_HANDLER_" + s + "=void 0;window._CASHIER_CROSS_EVENT_TARGET_" + s + "=void 0;}}");
                    _eventList.push({
                        "el": e,
                        "type": n,
                        "cfn": a,
                        "fn": t,
                        "win": i,
                        "id": s
                    }),
                    e.attachEvent ? e.attachEvent("on" + n, a) : e.addEventListener && e.addEventListener(n, a, !1)
                }
            }
            ,
            LIB.detachEvent = function(e, n, t) {
                for (var i, o = [], s = 0; i = _eventList[s]; s++)
                    if (e && i.el != e || n && i.type != n || "function" == typeof t && i.fn != t)
                        o.push(i);
                    else if (i.el.detachEvent ? i.el.detachEvent("on" + i.type, i.cfn) : i.el.removeEventListener && i.el.removeEventListener(i.type, i.cfn, !1),
                    i.win && i.id)
                        try {
                            delete i.win["_CASHIER_CROSS_EVENT_HANDLER_" + i.id],
                            delete i.win["_CASHIER_CROSS_EVENT_TARGET_" + i.id]
                        } catch (a) {
                            i.win["_CASHIER_CROSS_EVENT_HANDLER_" + i.id] = void 0,
                            i.win["_CASHIER_CROSS_EVENT_TARGET_" + i.id] = void 0
                        }
                _eventList = o
            }
            ,
            LIB.getEvent = function() {
                var e, n = window.event, t = 0;
                if (!n)
                    try {
                        for (e = arguments.callee; e && t < 10 && !((n = e.arguments) && (n = n[0]) && "object" == typeof n && "type"in n && "button"in n && "ctrlKey"in n && "altKey"in n && "shiftKey"in n); )
                            n = null,
                            e = e.caller,
                            t++
                    } catch (i) {
                        return null
                    }
                return n
            }
            ,
            LIB.unload = new Observer,
            LIB.unload.subscribe(function() {
                LIB.detachEvent()
            });
            var _unloadEventName = LIB.ua.chrome || LIB.ua.opera ? "beforeunload" : "unload";
            window.attachEvent ? window.attachEvent("on" + _unloadEventName, _fireUnloadEvent) : window.addEventListener && window.addEventListener(_unloadEventName, _fireUnloadEvent, !1),
            LIB.unload.subscribe(function() {
                window.cashier && (window.cashier = void 0),
                window.detachEvent ? window.detachEvent("on" + _unloadEventName, _fireUnloadEvent) : window.removeEventListener && window.removeEventListener(_unloadEventName, _fireUnloadEvent, !1)
            }),
            LIB.encodeURI = function(e) {
                return e ? (e + "").replace(/\%/g, "%25").replace(/\+/g, "%2B").replace(/ /g, "%20").replace(/\?/g, "%3F").replace(/#/g, "%23").replace(/&/g, "%26").replace(/=/g, "%3D").replace(/"/g, "%22") : ""
            }
            ;
            var _supportPostMessage = function() {
                if (window.postMessage)
                    try {
                        if (window.postMessage.toString().indexOf("[native code]") >= 0)
                            return !0;
                        LIB.err('The native "postMessage" function of browsers seems to have been overridden, DO NOT override it, or Cashier API will not work properly!')
                    } catch (e) {
                        return !0
                    }
                return !1
            }()
              , _xsInstance = {}
              , _XS_TAG = "__CashXStream_";
            _supportPostMessage && LIB.attachEvent(window, "message", function(e) {
                _xsDispatch(e.data, e.source)
            });
            var XStream = LIB.XStream = function(e, n, t) {
                var i;
                return (i = _xsInstance[n]) ? i : (_xsInstance[n] = this,
                this.handler = e,
                this.targetPort = n,
                this.target = t,
                this.closed = !1,
                this.onInit = new Observer(this),
                this._pool = [],
                void (!_supportPostMessage && !navigator[_XS_TAG + XStream.channel + XStream.localPort] && (navigator[_XS_TAG + XStream.channel + XStream.localPort] = _xsDispatch)))
            }
            ;
            XStream.channel = 0,
            XStream.localPort = "",
            XStream.prototype._sendRaw = function(e) {
                var n;
                try {
                    _supportPostMessage ? this.target.postMessage(e, "*") : "function" == typeof (n = navigator[_XS_TAG + XStream.channel + this.targetPort]) && n(e, window)
                } catch (t) {
                    LIB.warn("XStream sending error: ", t)
                }
            }
            ,
            XStream.prototype._handle = function(e, n, t) {
                if (e.init)
                    for (this.target = n,
                    this.closed = !1,
                    this.onInit.notify(); this._pool.length; )
                        this._sendRaw(this._pool.shift());
                else
                    !this.closed && "function" == typeof this.handler && this.handler.call(this, e.data, this.targetPort)
            }
            ,
            XStream.prototype.init = function() {
                if (this.target) {
                    var e = {
                        "port": XStream.localPort,
                        "init": 1
                    }
                      , n = JSON.stringify(e);
                    n = _XS_TAG + n,
                    this._sendRaw(n),
                    this.onInit.notify()
                }
            }
            ,
            XStream.prototype.send = function(e) {
                if (!this.closed && e) {
                    var n = {
                        "port": XStream.localPort,
                        "data": e
                    }
                      , t = JSON.stringify(n);
                    t = _XS_TAG + t,
                    this.target ? this._sendRaw(t) : this._pool.push(t)
                }
            }
            ,
            XStream.prototype.close = function() {
                this.closed = !0,
                delete _xsInstance[this.targetPort]
            }
            ;
            var OnceCall = LIB.OnceCall = function(e, n, t) {
                this._timeout = e,
                this._timer = 0,
                n = n || {},
                this.onConsume = n.onConsume,
                this.onReject = n.onReject,
                this.onTimeout = n.onTimeout,
                this.hasCalled = !1,
                t && this.start()
            }
            ;
            OnceCall.prototype._call = function(e) {
                this.hasCalled || (this.hasCalled = !0,
                this._timer && clearTimeout(this._timer),
                this._timer = 0,
                "function" == typeof e && e.call(this))
            }
            ,
            OnceCall.prototype.start = function() {
                this._timeout >= 0 && (this._timer = LIB.setTimeout(this.timeout, this._timeout, this))
            }
            ,
            OnceCall.prototype.consume = function() {
                this._call(this.onConsume)
            }
            ,
            OnceCall.prototype.reject = function() {
                this._call(this.onReject)
            }
            ,
            OnceCall.prototype.timeout = function() {
                this._timer = 0,
                this._call(this.onTimeout)
            }
            ;
            var _psIdx = 0
              , _psPool = LIB._psPool = {};
            LIB.pingSender = function(e, n) {
                return
            }
            ;
            var BatchReporter = function(e, n, t, i) {
                this.key = e,
                this.query = n,
                this.merge = t,
                this.url = i,
                this.count = 0,
                this.store = {},
                this.timer = 0,
                this._url = ""
            };
            BatchReporter.MAX_LEN = 1e3,
            BatchReporter.tmpl = function(e, n) {
                return (e + "").replace(/\{(\w+)\}/g, function(e, t) {
                    return n[t]
                })
            }
            ,
            BatchReporter.prototype.add = function(e) {
                var n, t;
                if (this.key ? (t = BatchReporter.tmpl(this.key, e),
                (n = this.store[t]) && (n.rate++,
                n = this.merge(n, e))) : t = this.count,
                !n) {
                    this.count++,
                    n = this.store[t] = {},
                    n.rate = 1;
                    for (var i in e)
                        n[i] = e[i]
                }
                this.report()
            }
            ,
            BatchReporter.prototype.report = function(e) {
                var n, t = [], i = 1;
                if ("function" == typeof this.query)
                    for (var o in this.store)
                        n = this.store[o],
                        t.push(this.query(i++, n));
                else {
                    for (var s = 0, a = this.query.length; s < a; s++)
                        t.push([]);
                    for (var o in this.store) {
                        n = this.store[o];
                        for (var s = 0, a = this.query.length; s < a; s++)
                            t[s].push(this.query[s](i, n));
                        i++
                    }
                    for (var s = 0, a = t.length; s < a; s++)
                        t[s] = t[s].join("")
                }
                this._url = BatchReporter.tmpl(this.url, {
                    "random": LIB.getIntRandom(),
                    "count": this.count,
                    "query": t.join("")
                }),
                this._url.length >= BatchReporter.MAX_LEN || e ? this._doReport() : !this.timer && (this.timer = LIB.setTimeout(this._doReport, 3e5, this))
            }
            ,
            BatchReporter.prototype.reportImmediate = function() {
                this.count > 0 && (this.report(!0),
                setTimeout(LIB.emptyFn, 1e3))
            }
            ,
            BatchReporter.prototype._doReport = function() {
                clearTimeout(this.timer),
                this.timer = 0,
                0 != this.count && (this.count = 0,
                this.store = {},
                LIB.pingSender(this._url, -1))
            }
            ,
            LIB.pv = function(e, n) {}
            ,
            LIB.timeStat = function(e, n, t, i) {}
            ,
            LIB.valueStat = function(e, n, t, i, o) {}
            ,
            LIB.valueStat2 = function(e, n, t, i, o) {}
            ,
            LIB.performanceTimeStat = function(e, n) {
                LIB.setTimeout(function() {
                    var t = window.performance || window.webkitPerformance || window.msPerformance;
                    if (t) {
                        if (0 == t.timing.loadEventEnd)
                            return void LIB.setTimeout(arguments.callee, 5e3);
                        var i = [t.timing.navigationStart, t.timing.unloadEventStart, t.timing.unloadEventEnd, t.timing.redirectStart, t.timing.redirectEnd, t.timing.fetchStart, t.timing.domainLookupStart, t.timing.domainLookupEnd, t.timing.connectStart, t.timing.connectEnd, t.timing.requestStart, t.timing.responseStart, t.timing.responseEnd, t.timing.domLoading, t.timing.domInteractive, t.timing.domContentLoadedEventStart, t.timing.domContentLoadedEventEnd, t.timing.domComplete, t.timing.loadEventStart, t.timing.loadEventEnd];
                        LIB.timeStat(e, i, n, !0)
                    }
                }, 5e3)
            }
            ,
            LIB.resourceTimeStat = function(e, n, t, i) {
                LIB.setTimeout(function() {
                    var o = window.performance || window.webkitPerformance || window.msPerformance;
                    if (o && (o.getEntriesByName || o.webkitGetEntriesByName)) {
                        if (0 == o.timing.loadEventEnd)
                            return void LIB.setTimeout(arguments.callee, 5e3);
                        var s;
                        try {
                            s = (o.getEntriesByName || o.webkitGetEntriesByName).call(o, n)[0]
                        } catch (a) {
                            return
                        }
                        if (!s)
                            return void LIB.valueStat(i, 1, 11);
                        if (0 == s.responseEnd)
                            return void LIB.setTimeout(arguments.callee, 5e3);
                        var r = [s.startTime, 0, s.startTime + s.startTime, s.redirectStart, s.redirectEnd, s.fetchStart, s.domainLookupStart, s.domainLookupEnd, s.connectStart, s.connectEnd, s.requestStart, s.responseStart, s.responseEnd, 0, 0, 0, 0, s.startTime + s.duration];
                        LIB.timeStat(e, r, t, !0),
                        LIB.valueStat(i, 1, 12)
                    }
                }, 5e3)
            }
            ,
            LIB.report = function() {
                var e = [];
                return function(n) {
                    var t = new Image;
                    e.push(t),
                    t.onload = t.onerror = t.onabort = function() {
                        t = t.onload = t.onerror = t.onabort = null;
                        for (var n = 0, i = e.length; n < i; ++n)
                            e[n] === t && e.splice(n, 1)
                    }
                    ,
                    t.src = n
                }
            }();
            var DLG = LIB.DLG = {}
              , _dlgInstance = {}
              , _dlgIndex = 1;
            DLG._handle = function(e, n) {
                var t, i = n.idx;
                n.key;
                return !n.key && (t = _dlgInstance[i]) ? (t.platform.consume(),
                delete _dlgInstance[i],
                !1) : (e.send({
                    "idx": i
                }),
                !0)
            }
            ,
            DLG._call = function(e, n, t) {
                t = t || {};
                var i = t.timestamp = t.timestamp || (new Date).getTime()
                  , o = _dlgIndex++;
                _dlgInstance[o] = {
                    "timestamp": i,
                    "platform": new OnceCall(1e4,{
                        "onConsume": function() {
                            LIB.valueStat(350303, 1, 20, (new Date).getTime() - i)
                        },
                        "onTimeout": function() {
                            !e.closed && LIB.valueStat(350303, 2, 19, (new Date).getTime() - i)
                        }
                    },(!0))
                };
                e.send({
                    "key": n,
                    "args": t,
                    "idx": o
                })
            }
            ;
            var customParam = decodeURIComponent(LIB.getParam(window._cashierDialogParam || "cash_param")) || window._cashierDialogValue;
            cashier.quiet = "1" == LIB.getParam("quiet", customParam);
            var dialogId = LIB.getParam("_fd_id", customParam)
              , dialogMethods = LIB.getParam("_fd_ms", customParam).split("|")
              , _methodObservers = {};
            XStream.channel = +LIB.getParam("_fd_c", customParam),
            XStream.localPort = dialogId;
            for (var _dialogXStream = new XStream(function(e) {
                var n;
                DLG._handle(_dialogXStream, e) && ((n = _methodObservers[e.key]) ? n.notify(e.args) : LIB.warn("Invalid method from Remote: " + e.key))
            }
            ,"lib",parent), i = 0, one; one = dialogMethods[i]; i++)
                cashier[one] = _callClosure(one);
            _methodObservers.submit = new Observer,
            _methodObservers.close = new Observer;
            var MSGBOX_TYPE = cashier.MSGBOX_TYPE = {};
            MSGBOX_TYPE.INFO = 1,
            MSGBOX_TYPE.OK = 2,
            MSGBOX_TYPE.WARN = 3,
            MSGBOX_TYPE.LOADING = 4,
            cashier.showMsgbox = function(e, n, t) {
                _xsend("showMsgbox", {
                    "type": e,
                    "msg": n,
                    "timeout": t
                })
            }
            ,
            cashier.hideMsgbox = function() {
                _xsend("hideMsgbox")
            }
            ;
            var _lastWidth = -1
              , _lastHeight = -1;
            cashier.resize = function(e, n) {
                (+e && e > 0 && e != _lastWidth || +n && n > 0 && n != _lastHeight) && (_xsend("resize", {
                    "w": e,
                    "h": n
                }),
                _lastWidth = +e,
                _lastHeight = +n)
            }
            ,
            cashier.submit = function(e) {
                _methodObservers.submit.notify(e)
            }
            ,
            cashier.submit.on = function(e) {
                _methodObservers.submit.subscribe(e)
            }
            ,
            cashier.succeed = function(e) {
                _xsend("succeed", e),
                cashier.quiet && _dialogXStream.close()
            }
            ,
            cashier.notify = function(e) {
                _xsend("notify", e)
            }
            ,
            cashier.show = function(e) {
                cashier.quiet && (cashier.quiet = !1,
                _xsend("show", e))
            }
            ,
            cashier.error = function(e) {
                _xsend("error", e),
                cashier.quiet && _dialogXStream.close()
            }
            ,
            cashier.close = function(e) {
                _methodObservers.close.notify(e),
                _xsend("close", e),
                _dialogXStream.close()
            }
            ,
            cashier.close.on = function(e) {
                _methodObservers.close.subscribe(e)
            }
            ,
            cashier.on = function(e, n, t) {
                _methodObservers[e] || (_methodObservers[e] = new Observer),
                _methodObservers[e].subscribe(n, t)
            }
            ,
            cashier.off = function(e, n) {
                _methodObservers[e] && _methodObservers[e].unsubscribe(n)
            }
            ,
            cashier.showBackBtn = function() {
                _xsend("showBackBtn")
            }
            ,
            cashier.resetTitle = function() {
                _xsend("resetTitle")
            }
            ,
            cashier.hideBackBtn = function() {
                _xsend("hideBackBtn")
            }
            ,
            cashier.newdialog = function(e) {
                _xsend("newdialog", e)
            }
            ,
            cashier.openwindow = function(e) {
                _xsend("openwindow", e)
            }
            ,
            cashier.messageCallback = function(e) {
                e = e || {},
                _xsend("messageCallback", e)
            }
            ,
            _dialogXStream.init(),
            _xsend("load", {
                "quiet": cashier.quiet
            });
            var dialogBodySize = LIB.getParam("_fd_size", customParam).split("|"), dialogBodyHeight = dialogBodySize[1], dialogBodyWrapper = LIB.getParam("_fd_w", customParam), targetHeight = dialogBodyHeight ? dialogBodyHeight + "px" : "", dialogBodyWrapperNode
        }()
    },
    "66138017": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div class="prop prop-brief">\n    <div class="prop-brief-info">\n        <span>为 </span><span class="account-id">{{user}}</span> <span class="business">{{buyinfo}}</span> <span class="duration"> {{buycount}} {{unit}}</span>\n    </div>\n    <em class="total-price-in-brief">{{price}}</em>\n    <div class="prop-price">元</div>\n</div>';
            return __p
        }
    },
    "66158855": function(e, n, t) {
        function i(e, n) {
            return f && (((new Date).getTime() - h) / 1e3 > l || p >= u) && (p = 0,
            h = 0,
            f = null),
            f || (p = 0,
            h = (new Date).getTime(),
            f = new c.Promise(function(n) {
                a.getFpBehvReporter(e)(n)
            }
            )),
            n ? null : (p++,
            f)
        }
        function o(e) {
            return c.Promise.race([new c.Promise(function(e) {
                setTimeout(function() {
                    e({
                        "ret": -9997
                    })
                }, d)
            }
            ), i(e)]).then(function(e) {
                return e.ret === -9997 && r("fpBehv.timeout"),
                e
            })
        }
        var s = t(4)
          , a = t(107544357)
          , r = t(10);
        t(5);
        var c = t(1)
          , l = s.fn.safeGet(window.__midasStaticConfig_midas_webpay, "itemMap.webpay.kepler_ticket_max_age", 600)
          , u = s.fn.safeGet(window.__midasStaticConfig_midas_webpay, "itemMap.webpay.kepler_ticket_reuse_limit", 10)
          , d = s.fn.safeGet(window.__midasStaticConfig_midas_webpay, "itemMap.webpay.get_kepler_timeout", 5e3)
          , p = 0
          , h = 0
          , f = null;
        e.exports = {
            "prefetchFpBehv": i,
            "waitFpBehv": o
        }
    },
    "66520979": function(e, n, t) {
        var i = t(1)
          , o = t(4)
          , s = t(104500419)
          , a = t(74720348)
          , r = navigator.userAgent.indexOf("MSIE 7.0") > 0 || "1" == o.fn.getParam("noKeyEvent")
          , c = 0
          , l = {
            "NORMAL": 0,
            "VALIDATEFAIL": 1
        };
        i.component("ms:input", {
            "$template": s(),
            "$$template": function(e) {
                return "simpleinput" == e ? s() : a()
            },
            "$replace": !0,
            "$skipArray": ["enablePlaceHolder", "filters", "validations", "maxlength", "_placeHolder", "maskcfg"],
            "$el": null,
            "onInput": i.noop,
            "onValidate": function(e, n) {},
            "onChange": i.noop,
            "onFocus": i.noop,
            "onBlur": i.noop,
            "onInit": i.noop,
            "filters": [],
            "validations": [],
            "placeholder": "",
            "ie7focused": !1,
            "defaultClass": "form-input",
            "extraClass": "",
            "extraContainerClass": "",
            "enablePlaceHolder": !1,
            "hideFocus": !0,
            "isFocused": !1,
            "_disable": !1,
            "id": "",
            "value": "",
            "oldValue": "",
            "displayValue": "",
            "oldDisplayValue": "",
            "width": "100%",
            "oldPos": 0,
            "maxlength": null,
            "state": l.NORMAL,
            "usemask": !1,
            "maskcfg": {},
            "$init": function(e, n) {
                e.id = "input_" + c++,
                e.enablePlaceHolder = !!e.placeholder && !e.supportPlaceHolder(),
                o.fn.each(e.maskcfg, function(e, n) {
                    o.lang.isFunction(e) && (this.maskcfg[n] = function() {
                        return e.apply(this, arguments)
                    }
                    .bind(this))
                }
                .bind(e))
            },
            "supportPlaceHolder": function() {
                var e = document.createElement("input");
                return "placeholder"in e && !document.all
            },
            "$ready": function(e) {
                e.value = e.useFilter.call(e, "*"),
                e.$el = document.getElementById(e.id),
                e.onInit(e),
                e.value += "",
                e.$el.value = e.oldValue = e.value,
                e.enablePlaceHolder || e.$el.setAttribute("placeholder", e.placeholder),
                e.handleInput.call(e, "init")
            },
            "$dispose": function(e) {
                e.$unwatch(),
                e.maskcfg = {}
            },
            "getPos": function(e) {
                var n;
                try {
                    if (e.setSelectionRange)
                        return n = e.selectionStart;
                    if (e.createTextRange) {
                        var t = document.selection.createRange()
                          , i = 0 - t.moveStart("character", -e.value.length);
                        return i
                    }
                } catch (o) {}
            },
            "setPos": function(e, n) {
                try {
                    if (e.setSelectionRange)
                        e.setSelectionRange(n, n);
                    else if (e.createTextRange) {
                        var t = e.createTextRange();
                        t.collapse(!0),
                        t.moveStart("character", n),
                        t.select()
                    }
                    this.oldPos = n
                } catch (i) {}
            },
            "fixPos": function(e) {
                return e
            },
            "handleKeyDown": function(e) {
                var n = [46, 37, 38, 40, 39, 8]
                  , t = !0
                  , i = this.$el.value;
                32 == e.keyCode && (t = !1),
                null == this.maxlength || this.isSelect() || this.useFilter("*", i).length >= ~~this.maxlength && (t = !1),
                n.indexOf(e.keyCode) > -1 && (t = !0),
                t || (e.preventDefault ? e.preventDefault() : e.returnValue = !1)
            },
            "isSelect": function() {
                if (window.getSelection) {
                    var e = window.getSelection();
                    return "" != e.toString()
                }
                if (document.selection) {
                    var n = document.selection.createRange();
                    return str = n.text,
                    "" != str
                }
            },
            "handleInput": function(e) {
                this.oldValue;
                this.value = this.$el.value;
                var n = this.useFilter("input", this.value);
                this.value = n,
                this.onValidate({
                    "passed": !0,
                    "validation": {}
                }),
                this.state = l.NORMAL,
                null != this.maxlength ? (this.maxlength = ~~this.maxlength,
                this.value.length > this.maxlength && (this.value = n = this.value.substr(0, this.maxlength)),
                this.onInput(this.value)) : this.onInput(this.value);
                var t = this.getPos(this.$el);
                this.$el.value = n,
                "init" != e ? (this.displayValue = this.$el.value,
                this.setPos(this.$el, t)) : this.displayValue = this.oldDisplayValue = this.$el.value
            },
            "handleChange": function() {
                var e = this.$el.value;
                this.value = e,
                "" != this.value && (this.value = this.useFilter("change", this.value));
                var n = {
                    "passed": !0
                };
                "" == this.value || (n = this.validate()),
                n.passed ? (this.state = l.NORMAL,
                this.onChange(this.value)) : (this.state = l.VALIDATEFAIL,
                this.onValidate(n))
            },
            "handleBlur": function(e) {
                this.isFocused = !1,
                r && (this.ie7focused = !1),
                this.onBlur();
                var n = this.$el.value;
                this.value = this.$el.value = this.useFilter("*", n),
                this.value != this.oldValue && this.handleChange()
            },
            "handleFocus": function() {
                this.isFocused = !0,
                this.oldValue = this.value = this.$el.value,
                this.onFocus(),
                r && (this.ie7focused = !0)
            },
            "useFilter": function(e, n) {
                var t = "undefined" == typeof n ? this.value : n;
                return this.filters.forEach(function(n, i) {
                    if (n = /([^\|]*)\|([^\|]*)\|?(\S]*)?/.exec(n),
                    n && !(n.length < 2)) {
                        var s = n[1]
                          , a = [t];
                        "undefined" != typeof n[3] && (a = a.concat(n[3].split(",")));
                        var r = n[2];
                        "*" == e || "*" == r ? o.filter && o.filter[s] && (t = o.filter[s].apply(null, a)) : r == e && o.filter && o.filter[s] && (t = o.filter[s].apply(null, a))
                    }
                }
                .bind(this)),
                t
            },
            "validate": function(e) {
                e = "undefined" != typeof e ? e : this.value;
                var n = this.validations
                  , t = {
                    "passed": !0
                };
                return o.fn.each(n, function(n) {
                    n.params = n.params || {};
                    var i = u[n.name]
                      , o = [this.value].concat(n.params);
                    if (i) {
                        if (!i.apply(null, o))
                            return t = {
                                "passed": !1,
                                "validation": n,
                                "value": e
                            },
                            !1
                    } else if (n.func && !n.func.apply(null, o))
                        return t = {
                            "passed": !1,
                            "validation": n,
                            "value": e
                        },
                        !1
                }
                .bind(this)),
                t
            },
            "clearValue": function() {
                this.value = this.$el.value = "",
                this.state = l.NORMAL,
                this.handleChange(),
                setTimeout(function() {
                    this.$el.focus()
                }
                .bind(this), 10)
            },
            "getValue": function() {
                this.value = this.useFilter("*", this.value);
                var e = this.validate();
                return e.passed ? (this.state = l.NORMAL,
                this.value) : (this.state = l.VALIDATEFAIL,
                this.onValidate(e),
                !1)
            },
            "enable": function() {
                this._disable = !1
            },
            "disable": function() {
                this._disable = !0
            }
        });
        var u = {
            "len": function(e, n) {
                return e.length == n
            },
            "minlen": function(e, n) {
                return !(e.length < n)
            },
            "maxlen": function(e, n) {
                return !(e.length > n)
            }
        };
        e.exports = {
            "create": function(e, n) {
                n = n || {};
                var t = String.format('<ms:input $template="{tplType}" $id="{id}" on-input="{onInput}"on-change="{onChange}"on-focus="{onFocus}"on-blur="{onBlur}"config="{config}"></ms:input>', {
                    "id": n.id || "",
                    "tplType": n.tplType,
                    "componentName": n.componentName,
                    "onInput": n.onInput || "onInput",
                    "onChange": n.onChange || "onChange",
                    "onBlur": n.onBlur || "onBlur",
                    "onFocus": n.onFocus || "onFocus",
                    "config": e || "inputConfig"
                });
                return t
            },
            "addValidator": function(e, n) {
                u[e] = n
            },
            "masks": {
                "space": {
                    "stripMask": function(e) {
                        if (e = "undefined" == typeof e ? this.value : e,
                        !this.usemask)
                            return e;
                        try {
                            return e.replace(/\s/g, "")
                        } catch (n) {}
                        return e
                    },
                    "runMask": function(e) {
                        if (!this.usemask)
                            return e;
                        var n = ""
                          , t = e.split("");
                        try {
                            for (var i = 0, o = t.length; i < o; ++i)
                                n += t[i],
                                (i + 1) % 4 || (n += " ")
                        } catch (s) {}
                        return /\s+$/.test(n) && (n = n.replace(/\s+$/, "")),
                        n
                    },
                    "fixPos": function(e, n) {
                        if (this.displayValue.length >= this.oldDisplayValue.length)
                            this.maskcfg.testSpace(e) && (e += 1),
                            e == this.$el.value.length - 1 && this.value.length != this.maxlength && (e += 1);
                        else if (this.displayValue.length < this.oldDisplayValue.length && this.maskcfg.testSpace(e))
                            return e - 1;
                        return e
                    },
                    "testSpace": function(e) {
                        return /\s/g.test(this.$el.value.substr(e - 1, 1))
                    },
                    "checkPos": function(e, n) {
                        this.usemask && (n >= e && this.maskcfg.testSpace(e) ? this.setPos(this.$el, e - 1) : this.oldDisplayValue != this.$el.value ? (this.$el.value = this.$el.value.substr(0, e - 1) + this.$el.value.substr(e, this.$el.value.length),
                        this.handleInput("force"),
                        this.setPos(this.$el, e - 1)) : this.setPos(this.$el, e))
                    }
                }
            }
        }
    },
    "66850917": function(module, exports, __webpack_require__) {
        var util = __webpack_require__(4)
          , mpinfo = {
            "setInfo": function(e, n, t) {
                this.info = e,
                this.cuStep = n,
                this.disableCusInput = t
            },
            "getRecommendList": function() {
                var mpinfo = this.info.mp_info, re = [], i;
                if (mpinfo && mpinfo.utp_mpinfo_detail) {
                    var rank_info = mpinfo.utp_mpinfo_detail.rank_info;
                    for (i = 0; i < rank_info.length; i++) {
                        var m0 = rank_info[i];
                        rank_info[i].__send_num = "2" == m0.send_type ? m0.send_num : parseInt(m0.send_rate) * parseInt(m0.num) / 100,
                        re.push(rank_info[i])
                    }
                } else if (mpinfo && mpinfo.utp_mpinfo)
                    for (i = 0; i < mpinfo.utp_mpinfo.length; i++) {
                        var m = mpinfo.utp_mpinfo[i], m1, m0;
                        m.single_ex && m.single_ex instanceof Array && (m1 = m.single_ex[0],
                        m1.send_ext ? m1._weight = 4 : m1._weight = 2),
                        m.send_ext ? m._weight = 3 : m._weight = 1,
                        m0 = m1 && m1._weight > m._weight ? m1 : m,
                        m0.__send_num = m0.send_type + "" == "2" ? m0.send_num : parseInt(m0.send_rate) * parseInt(m0.num) / 100,
                        re.push(m0)
                    }
                else {
                    if ("string" == typeof this.info.recommend_list)
                        try {
                            this.info.recommend_list = eval(this.info.recommend_list)
                        } catch (e) {}
                    if (this.info.recommend_list instanceof Array)
                        for (i = 0; i < this.info.recommend_list.length; i++)
                            re.push({
                                "num": this.info.recommend_list[i]
                            })
                }
                return this.gameListAdapter(re, {
                    "logo": this.info.logo,
                    "rate": ~~this.info.rate
                })
            },
            "gameListAdapter": function(e, n) {
                for (var t = 0; t < e.length; t++)
                    if (e[t].count = parseInt(e[t].num),
                    e[t].logo = n.logo,
                    e[t].rate = n.rate,
                    parseInt(e[t].__send_num) && (e[t].discountAmount = e[t].__send_num,
                    e[t].restrictionRule = e[t].send_ext),
                    e[t].type = "drm",
                    e[t].ex_send instanceof Array && e[t].ex_send.length && e[t].ex_send.length > 0) {
                        for (var i = [], o = 0; o < e[t].ex_send.length; o++)
                            i.push({
                                "name": e[t].ex_send[o].name,
                                "num": e[t].ex_send[o].num
                            });
                        i.length > 1 && (e[t].discountDetailTips = i),
                        e[t].discountTips = {
                            "name": i[0].name,
                            "num": i[0].num
                        }
                    }
                if (e.length < 8 && !this.disableCusInput) {
                    var s, a = ~~this.info.rate, r = 100 % a === 0;
                    s = r ? this.cuStep ? this.cuStep : 1 : this.cuStep && this.cuStep % a === 0 ? this.cuStep : a;
                    var c = parseFloat(util.fn.getParam("maxCount")) || 5e3;
                    e.push({
                        "count": 0,
                        "logo": n.logo,
                        "type": "drm",
                        "step": s,
                        "min": s,
                        "max": c * a,
                        "editable": !0,
                        "rate": n.rate,
                        "onBlurCallBack": function(e) {
                            var n = e.count
                              , t = mpinfo.getSendCount(n, !0)
                              , i = [];
                            t.total && i.push({
                                "name": mpinfo.info.product_name,
                                "num": t.total
                            }),
                            t.firstInfo && t.firstInfo.ex_send instanceof Array && util.fn.each(t.firstInfo.ex_send, function(e) {
                                i.push({
                                    "name": e.name,
                                    "num": e.num
                                })
                            }),
                            t.mpInfo && t.mpInfo.ex_send instanceof Array && util.fn.each(t.mpInfo.ex_send, function(e) {
                                i.push({
                                    "name": e.name,
                                    "num": e.num
                                })
                            }),
                            e.discountTips = i[0],
                            i.length > 1 ? e.discountDetailTips = i : e.discountDetailTips = []
                        }
                    })
                }
                return e
            },
            "_firstInfo": function(e) {
                var n = this.info
                  , t = null;
                if (n.mp_info && n.mp_info.first_mpinfo) {
                    var i, o = n.mp_info.first_mpinfo;
                    o._weight = o.send_ext ? 3 : 1,
                    o.single_ex && o.single_ex instanceof Array && (i = o.single_ex[0],
                    i._weight = i.send_ext ? 4 : 2);
                    var s = i && i._weight > o._weight ? i : o;
                    s.__sendNum = s.send_type + "" == "2" ? s.send_num : parseInt(s.send_rate) * parseInt(s.num) / 100,
                    1 == s._weight || 3 == s._weight ? e >= parseInt(s.num) && (t = s) : e + "" == s.num && (t = s)
                }
                return t
            },
            "findNum": function(e, n) {
                for (var t = null, i = 0; i < n.length; i++)
                    if (n[i].num == e + "") {
                        t = n[i];
                        break
                    }
                return t
            },
            "findRange": function(e, n) {
                var t = null
                  , i = 0
                  , o = n.length;
                if (e > parseInt(n[o - 1].num))
                    return n[o - 1];
                if (e <= parseInt(n[i].num))
                    return t;
                for (i = 0; i < o; i++)
                    if (parseInt(n[i].num) < e && i + 1 < o && parseInt(n[i + 1].num) > e) {
                        t = n[i];
                        break
                    }
                return t
            },
            "_findRangeInMpInfo": function(e, n) {
                var t = null
                  , i = 0
                  , o = n.length;
                if (e >= parseInt(n[o - 1].num))
                    return n[o - 1];
                if (e < parseInt(n[i].num))
                    return t;
                for (i = 0; i < o; i++)
                    if (parseInt(n[i].num) <= e && i + 1 < o && parseInt(n[i + 1].num) > e) {
                        t = n[i];
                        break
                    }
                return t
            },
            "_mpInfo": function(e) {
                var n, t = this.info.mp_info;
                if (t && t.utp_mpinfo_detail) {
                    var i = this.findNum(e, t.utp_mpinfo_detail.rank_info || []);
                    if (i)
                        return i.__sendNum = "2" == i.send_type ? i.send_num : parseInt(i.send_rate) * parseInt(i.num) / 100,
                        i;
                    var o = this.findRange(e, t.utp_mpinfo_detail.range_info || []);
                    if (o) {
                        var s = 0;
                        for (n = 0; n < o.coin.length; n++)
                            s += "2" == o.coin[n].send_type ? parseInt(o.coin[n].send_num) : Math.ceil(parseInt(o.coin[n].send_num) * e / 100);
                        return o.__sendNum = s,
                        o
                    }
                } else if (t && t.utp_mpinfo) {
                    var a, r;
                    for (n = 0; n < t.utp_mpinfo.length; n++)
                        if (r = t.utp_mpinfo[n],
                        r.num == e + "") {
                            a = r;
                            break
                        }
                    if (a) {
                        r = a;
                        var c, l;
                        return r.single_ex && r.single_ex instanceof Array && (c = r.single_ex[0],
                        c.send_ext ? c._weight = 4 : c._weight = 2),
                        r.send_ext ? r._weight = 3 : r._weight = 1,
                        l = c && c._weight > r._weight ? c : r,
                        l.__sendNum = "2" == l.send_type ? l.send_num : parseInt(l.send_rate) * parseInt(l.num) / 100,
                        l
                    }
                    var u = this._findRangeInMpInfo(e, t.utp_mpinfo);
                    return u && (u.__sendNum = "2" == u.send_type ? parseInt(u.send_num) : Math.ceil(parseInt(u.send_rate) * e / 100)),
                    u
                }
            },
            "getSendCount": function(e, n) {
                var t, i = 0;
                n || (t = this._firstInfo(e)),
                t && (i += parseInt(t.__sendNum));
                var o = this._mpInfo(e);
                return o && (i += parseInt(o.__sendNum)),
                {
                    "total": i,
                    "firstInfo": t,
                    "mpInfo": o
                }
            },
            "getMarketingTips": function() {
                var e = this.info.mp_info
                  , n = "";
                return e.mpinfo_ex && e.mpinfo_ex.title ? n = e.mpinfo_ex.title : e.first_mpinfo_ex && e.first_mpinfo_ex.title ? n = e.first_mpinfo_ex.title : e.acc_mpinfo_ex && e.acc_mpinfo_ex.title ? n = e.acc_mpinfo_ex.title : e.utp_mpinfo_ex && e.utp_mpinfo_ex.title && (n = e.utp_mpinfo_ex.title),
                n
            }
        };
        module.exports = mpinfo
    },
    "67505057": function(e, n, t) {
        var i = t(119122155)
          , o = t(106745080)
          , s = i.buyInfo.game_type || "default"
          , a = t(110085254)
          , r = t(117520354)
          , c = t(75677352);
        e.exports = function(e) {
            var n = null
              , t = navigator.userAgent.indexOf("MSIE 6.0") > 0;
            if (t && i.buyInfo && "1450000238" == i.buyInfo.appid)
                n = new c(e,{},{});
            else
                switch (s) {
                case o.Type.HOSTING:
                    n = new a(e,{},{});
                    break;
                case o.Type.NOHOSTING:
                    n = new r(e,{},{});
                    break;
                default:
                    n = new a(e,{},{})
                }
            return n.init(),
            n
        }
    },
    "68682076": function(e, n, t) {
        var i = t(1)
          , o = t(103220717)
          , s = t(4);
        i.component("ms:dropdown", {
            "value": {
                "name": ""
            },
            "isShow": !1,
            "data": [],
            "$skipArray": [],
            "$replace": !0,
            "onInit": i.noop,
            "onChange": function(e) {},
            "showList": function(e) {
                this.isShow = "true" === e
            },
            "select": function(e) {
                var n = s.fn.extend({}, e ? e.$model || e : {});
                this.value = n,
                this.isShow = !1,
                this.onChange(n)
            },
            "label": "",
            "width": "140px",
            "$template": o(),
            "$init": function(e, n) {
                if (e.value.name) {
                    var t = 0;
                    e.data.some(function(n, i) {
                        if (n.name === e.value.name)
                            return t = i,
                            !0
                    });
                    e.select.call(e, e.data[t])
                } else
                    e.select.call(e, e.data[0])
            },
            "$ready": function(e) {
                e.onInit(e)
            },
            "reset": function(e, n) {
                this.data = e,
                n && this.select(n)
            }
        }),
        e.exports = {
            "create": function(e) {
                return '<ms:dropdown config="' + e + '" on-change="onChange"></ms:dropdown>'
            }
        }
    },
    "68718905": function(e, n, t) {
        var i = t(1)
          , o = t(49140953)
          , s = t(72074753)
          , a = t(76531812)
          , r = t(119122155)
          , c = t(12)
          , l = t(78901017)
          , u = t(70127470)
          , d = t(78805100)
          , p = t(112745811)
          , h = t(87796589)
          , f = (t(102521382),
        t(44017488))
          , m = t(4)
          , g = t(17)
          , v = t(19)
          , b = null
          , y = t(10)
          , _ = t(109735088)
          , k = _.getLoginStatus()
          , w = t(84811753)
          , C = ("true" === r.buyInfo.disableSend,
        function(e, n, t) {
            this.root = e,
            this.handlers = t || {};
            var o = this;
            this.vmConfig = {
                "$id": "order",
                "showOrder": !0,
                "showSimpleOrder": !1,
                "canchangeCount": "undefined" == typeof r.buyInfo.canChangeCount || "true" === r.buyInfo.canChangeCount,
                "SimpleOrderHtml": "",
                "orderHtml": "",
                "channelList": "",
                "curChannel": null,
                "title": "",
                "img_title": "",
                "logo": "",
                "account": "",
                "area": "",
                "active": !0,
                "showAccountInfo": k.qq1 || k.pskey || k.wechat || k.ctlogin || k.accesstoken,
                "discount": 1,
                "fvm": null,
                "$skipArray": [],
                "friendListConfig": {
                    "container": "friendSelector",
                    "initCallBack": !0,
                    "initExpand": !0,
                    "data": [],
                    "value": {},
                    "onBlur": function() {
                        o.vm.active = !0
                    },
                    "onInit": function(e) {
                        o.vm.fvm = e
                    },
                    "onFriendSelected": function(e, n) {
                        o.friendSelected(e, n)
                    }
                },
                "friendSelector": "",
                "price": 0,
                "tips": "",
                "enableChangeAccount": r.isAllowSend(),
                "buycount": "",
                "buyinfo": "",
                "unit": "",
                "changeAccount": function() {
                    o.onClickSwitch()
                },
                "fixAccountToSelf": function(e) {
                    if (this.enableChangeAccount = r.isAllowSend() && !e,
                    e && r.isAllowSend()) {
                        var n = r.getSession().openid
                          , t = d.getDisplayInfoByOpenid(n);
                        this.account = t.nick ? String.format("{uin}（{nickname}）", {
                            "uin": t.uin,
                            "nickname": t.nick
                        }) : "自己",
                        r.provide_uin = n
                    }
                }
            },
            i.mix(!0, this.vmConfig, n)
        }
        );
        C.prototype = {
            "onChannelEvent": function(e) {
                var n = e.getData().showBindCard
                  , t = this.vm;
                t.showSimpleOrder = n,
                n ? (t.buycount = r.getAmount(),
                t.buyinfo = "购买" + r.getInfo().offer_name,
                t.unit = r.getInfo().product_name,
                g.trigger("headerDataReady", {
                    "title": a.getStore().getChannelObj().channelText
                }),
                this.root.fakeSubChannel = !0) : (g.notify("resetTitle"),
                this.root.fakeSubChannel = !0)
            },
            "onDataReady": i.noop,
            "onOrderInit": function(e) {
                var n = this.vm;
                e = e || {},
                r.isWechatLogin ? r.getWechatNick(function(e) {
                    n.account = e ? e.nickname + "(微信)" : "微信用户",
                    v.set("wechatNickName", n.account)
                }) : r.loginStatus.qq && (r.loginStatus.qq1 ? v.set("qqNumber", r.getSession().openid) : i.nextTick(function() {
                    r.getQQNick(function(e) {
                        r.isAllowSend() || (n.account = e ? e + "(QQ昵称)" : "QQ用户"),
                        e && v.set("qqNickName", e)
                    })
                })),
                y("resource.time", {
                    "resultinfo": {
                        "vendorjs": window.vendorTimeEnd - window.vendorTimeStart,
                        "gamejs": window.gameTimeEnd - window.vendorTimeEnd
                    }
                })
            },
            "onInitFriendComponent": i.noop,
            "onSelectFriend": i.noop,
            "friendSelected": function(e) {
                if (!e.invalid && e.qq) {
                    this.vm.active = !0;
                    var n = d.getDisplayInfoByOpenid(e.qq);
                    this.vm.account = n.uin + String.format("（{nickname}）", {
                        "nickname": n.nick
                    }),
                    r.provide_uin = e.qq,
                    v.set("qqNickName", (d.getDisplayInfoByOpenid(e.qq) || {}).nick),
                    a.emit("dataChange", "count", {
                        "provide_uin": e.qq
                    }),
                    this.onSelectFriend(e)
                }
            },
            "onClickSwitch": function() {
                this.vm.active = !1,
                this.initFriendsComponent(!0)
            },
            "onChannelAPIReady": i.noop,
            "initFriendsComponent": function(e) {
                var n = this.vm || this.vmConfig
                  , t = function(t) {
                    n.friendListConfig.data = t,
                    n.friendListConfig.value = r.provide_uin ? {
                        "qq": r.provide_uin
                    } : t[0],
                    n.friendListConfig.initExpand = !!e,
                    i.nextTick(function() {
                        l.create(n.friendListConfig)
                    })
                };
                n.enableChangeAccount ? n.fvm ? e && i.nextTick(function() {
                    n.fvm.focusInput(),
                    n.fvm.show()
                }) : u(r, t, {}) : "uin" === r.buyInfo.session_id && r.getPayFor() === h.SELF ? n.account = r.getSession().openid + "（自己）" : r.provide_uin && r.provide_uin != r.getSession().openid && (n.account = r.provide_uin),
                this.onInitFriendComponent()
            },
            "onInit": function(e) {
                var n = this.vm;
                e = e || {},
                n.orderHtml = this.handlers.onTemplate();
                var t = this;
                r.getOrderInfo(function(e, s) {
                    return i(m.Id("cp_loading_")).css({
                        "display": "none"
                    }),
                    e ? (e.logo && (n.logo = e.logo.replace(/https?:/g, "")),
                    t.onDataReady(function() {
                        t._resizeHeight()
                    }),
                    t.initChannelSelector(),
                    t.updatePrice(),
                    void y.Performance.userTrace("timer.js.exec")) : void (1018 == s.ret && _.canUsePTLoginCookie && (k.qq1 || k.pskey) ? (n.showOrder = !1,
                    r.showLoginBox("qq", {
                        "force": !0,
                        "onSuccess": function(e) {
                            var n = e.getSessionParam();
                            n.openid = decodeURIComponent(n.openid),
                            n.openkey = decodeURIComponent(n.openkey),
                            location.href = m.fn.addParam(n, location.href)
                        },
                        "onClose": function() {
                            t.goLoginResult()
                        }
                    })) : s.ret == -9999 ? t.goLoginResult() : c.go("result", {
                        "status": "error",
                        "res": s,
                        "modifyTitle": !1,
                        "actionType": t.root.actionType,
                        "displayInfo": s.msg || o.TEXT.GETORDERFAIL
                    }))
                }),
                this.onOrderInit(e)
            },
            "goLoginResult": function() {
                var e = {
                    "displayInfo": o.TEXT.INVALIDLOGIN,
                    "status": "error",
                    "cgi": r.getCgi(),
                    "session": r.getSession(),
                    "modifyTitle": !1,
                    "buttonTxt": "登录",
                    "onAction": function() {
                        r.showLoginBox("qq", {
                            "force": !0,
                            "onSuccess": function(e) {
                                var n = e.getSessionParam();
                                n.openid = decodeURIComponent(n.openid),
                                n.openkey = decodeURIComponent(n.openkey),
                                location.href = m.fn.addParam(n, location.href)
                            },
                            "onClose": function() {}
                        })
                    }
                };
                c.go("result", e)
            },
            "onResult": function(e) {
                g.notify("resetTitle"),
                m.delayRun("again.event", function() {
                    a.emit("onShow")
                }, 500),
                e && e.refresh && a.emit("dataChange", e.refresh.key, e.refresh.data)
            },
            "_resizeHeight": function() {
                if ("true" !== r.buyInfo.noresize) {
                    var e = document.getElementById("order");
                    if (e) {
                        var n = i(e).outerHeight(!0);
                        g.resize({
                            "h": n
                        })
                    }
                }
            },
            "initChannelSelector": function() {
                var e = this.vm
                  , n = this
                  , t = r.getInfo()
                  , o = function(n) {
                    e.channelList = n
                };
                a.init({
                    "info": t,
                    "session": r.session,
                    "cgi": r.cgi,
                    "params": r.buyInfo,
                    "type": p.GAME
                }, function() {
                    a.render(o),
                    a.on("channelChange", function(e) {
                        var n = e && e.channel === s.FRIENDPAY;
                        i.vmodels.order.fixAccountToSelf(n),
                        n && (this.provide_uin = ""),
                        "true" !== r.buyInfo.noresize && "auto" != e.height && b !== e.height && m.delayRun("channel.resize.event", function() {
                            b = e.height;
                            var n = i(document.getElementById("channelSelectWrap")).outerHeight(!0)
                              , t = e.height + i(document.getElementById("order_info")).outerHeight(!0) + n + (n > 0 ? 25 : 0);
                            g.resize({
                                "h": t
                            })
                        }, 300)
                    }),
                    a.on(f, function(e) {
                        n.onChannelEvent(e)
                    }),
                    a.on("channelDataChange", function(e) {
                        e instanceof w && "function" == typeof n.onChannelDataChange && n.onChannelDataChange(e)
                    }),
                    n.onChannelAPIReady(),
                    n.initFriendsComponent(!1)
                })
            },
            "updatePrice": function() {
                this.vm.price = r.getPrice(this.vm.discount).price
            },
            "channelCallback": function(e, n) {},
            "setConfig": function(e) {
                i.mix(this.vmConfig, e)
            },
            "init": function() {
                this.vm = i.define(this.vmConfig)
            },
            "getVm": function() {
                return this.vm
            }
        },
        e.exports = C
    },
    "69061514": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div class="type-item">{{$selectName}}：\n    <form class="form-inline">\n        <div ms-repeat="radioList" class="form-group radio-box" ms-class-1="checked:$index==index" ms-on-click="handleClick($index,$event)">\n            <label ms-attr-for="radioId">\n                <input type="radio" ms-attr-checked="$index==index">\n                <i class="icon-radio"></i>\n                <span ms-html="el.name"></span>\n            </label>\n        </div>\n    </form>\n</div>';
            return __p
        }
    },
    "69854898": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div ms-visible="showHeader" ms-html="subHeaderHtml"></div>\n<div ms-html="orderInfo"></div>\n<div  class="pay-area pay-area-active">\n    <div class="pay-area-body">\n        <div class="channel-detail" ms-html="subChannelHtml">\n\n        </div>\n    </div>\n</div>';
            return __p
        }
    },
    "70058909": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div>\n    <div class="index-marketing-area" ms-html="marketingTips" ms-if="marketingTips">\n    </div>\n    <div id="order_info">\n        <div class="prop" ms-if="!showSimpleOrder">\n            <div class="account" ms-if="showAccountInfo">\n\n                <div class="account-area">\n                    <!-- 账号 & 游戏大厅 -->\n                    <!--  <p class="account-title">购入账号：565220833(QQ) | 游戏大区1</p>-->\n\n                    <!-- 账号 & 赠送功能 -->\n                    <span class="account-title">充值账号：</span>\n                    <div class="account-id  active" ms-class="account-default-id:active"\n                        ms-class-1="account-change-id:!active">\n                        <div ms-visible="active">\n                            <span class="loged-id" ms-if="!account">...</span>\n                            <span class="loged-id">{{account | html}} {{ area}}</span>\n                            <span class="change-id" ms-if="enableChangeAccount && account"\n                                ms-on-click="changeAccount"><i class="icon-change"></i>更换</span>\n                        </div>\n\n                        <div ms-if="enableChangeAccount" ms-visible="!active" id="friendSelector">\n                        </div>\n\n                    </div>\n                </div>\n\n\n            </div>\n\n            <div ms-if="showRecommend" ms-html="recommendList"></div>\n            <div class="prop-detail dq" ms-if="!showRecommend">\n                <div class="prop-img">\n                    <img ms-attr-src="logo" width="80" height="60" ms-attr-title="img_title" />\n                </div>\n                <div class="prop-info" ms-if="canchangeCount">\n                    <div ms-html="amountSpinerHtml"></div>\n                    <p class="tips">{{tips}}</p>\n                </div>\n                <div ms-if="!canchangeCount" class="prop-info">\n\n                    <p class="prop-title" style="margin-top:25px">{{title}}</p>\n\n                </div>\n\n                <div class="prop-price">\n                    <em>{{price}}</em>元\n                </div>\n            </div>\n        </div>\n        <div ms-if="showSimpleOrder">\n\n            <div class="prop prop-brief">\n                <div class="prop-brief-info">\n                    <span>为 </span><span class="account-id">{{account|html}}</span> <span\n                        class="business">{{buyinfo}}</span> <span class="duration">x {{buycount}} {{unit}}</span>\n                </div>\n                <em class="total-price-in-brief">{{price}}</em>\n                <div class="prop-price">元</div>\n            </div>\n\n\n        </div>\n    </div>\n    <div ms-html="channelList"></div>\n</div>';
            return __p
        }
    },
    "70127470": function(e, n, t) {
        var i = t(4)
          , o = t(109735088)
          , s = t(78805100);
        e.exports = function(e, n, t) {
            if (!e)
                throw Error("context must be an object");
            if (!e.cgi)
                throw Error("context must contain cgi");
            var a = e
              , r = o.getLoginStatus() || {};
            if (a.flist)
                return void (i.lang.isFunction(n) && n(a.flist));
            var c = {};
            t = t || {},
            i.fn.extend(c, t),
            r.accesstoken && (c.version = "2",
            c.offerid_for_qq_appid = i.fn.getParam("qqAppid"));
            var l = function(e) {
                if (!e)
                    throw Error("callback must be function");
                if (r.ptlogin || r.pskey) {
                    var n = a.getPayUin && a.getPayUin();
                    return s.setDisplayInfoByOpenid(n, {
                        "uin": n,
                        "nick": "自己"
                    }),
                    e({
                        "qq": n,
                        "nick": "自己"
                    })
                }
                a.getQQNick(function(n) {
                    if (n) {
                        var t = n.nick;
                        return e({
                            "qq": n.provide_uin,
                            "nick": t
                        })
                    }
                    return e({
                        "qq": "",
                        "nick": "QQ用户"
                    })
                }, {
                    "getAll": !0
                })
            };
            a.cgi.getFriendlist(c, function(e) {
                l(function(t) {
                    var o = a.cgi.sessionObj.openid;
                    ~~e.ret ? r.accesstoken ? i.lang.isFunction(n) && n([{
                        "name": "自己",
                        "qq": o
                    }]) : i.lang.isFunction(n) && n([{
                        "name": "自己",
                        "qq": t.qq,
                        "openid": o
                    }]) : (a.flist = "object" == typeof e.friend_list ? s.friendListV2(t, o, e.friend_list) : s.friendList(t.qq, e.friend_list),
                    i.lang.isFunction(n) && n(a.flist))
                })
            })
        }
    },
    "70508452": function(e, n, t) {
        var i = t(4)
          , o = t(1)
          , s = t(109718908)
          , a = (t(66520979),
        function(e) {
            e = e || {},
            this.opts = e,
            this.el = e.el || document.body,
            this.container = document.createElement("div"),
            this.controller = "verifycode",
            this.isNested = e.isNested || !1,
            this.container.innerHTML = s({
                "controller": this.controller,
                "isNested": this.isNested
            }),
            this.el.appendChild(this.container),
            this.vm = null,
            this.verifySession = e.session,
            this.verifyCodePic = e.verifyCodePic,
            this.verifyCode = "",
            this.limitLen = e.limitLen || 4,
            this.initVm(),
            this.verifySession && this.verifyCodePic || this.vm.changeVerifyCode()
        }
        );
        i.fn.extend(a.prototype, {
            "initVm": function() {
                var e = this;
                this.vm = o.define({
                    "$id": this.controller,
                    "config": {
                        "filters": [],
                        "validations": [{
                            "name": "len",
                            "params": [this.limitLen],
                            "msg": ""
                        }, {
                            "func": function(e) {
                                return !!/[a-z|A-Z|0-9]/g.test(e)
                            },
                            "msg": ""
                        }]
                    },
                    "isNested": this.isNested,
                    "verifyCodePic": this.verifyCodePic,
                    "$skipArray": ["verifyInputVm"],
                    "setVerifyInfo": function(n, t) {
                        e.vm.verifyCodePic = n + "?t=" + i.fn.uuid(),
                        e.verifySession = t
                    },
                    "validateFailMsg": "",
                    "isValidateFail": !0,
                    "verifyInputVm": null,
                    "getVerifyInputVm": function(n) {
                        e.vm.verifyInputVm = n
                    },
                    "changeVerifyCode": function() {
                        this.validateFailMsg = "";
                        var n = function(e) {
                            return n = null,
                            e ? void this.setVerifyInfo(e.url, e.verifySession) : (this.verifyCodePic = "",
                            void (this.validateFailMsg = "验证码加载失败，请重试。"))
                        }
                        .bind(e.vm);
                        i.lang.isFunction(e.opts.onChangeVerifyCode) && e.opts.onChangeVerifyCode(n)
                    },
                    "onValidate": function(n) {
                        e.vm.isValidateFail = !n.passed,
                        n.passed || (e.vm.validateFailMsg = n.validation.msg)
                    },
                    "onInput": function(n) {
                        e.vm.isNested && (n.length == e.limitLen ? i.lang.isFunction(e.opts.onFullfill) && e.opts.onFullfill() : i.lang.isFunction(e.opts.onReject) && e.opts.onReject(),
                        e.vm.isValidateFail = !1,
                        e.vm.validateFailMsg = "")
                    },
                    "onChange": function(n) {
                        e.vm.isValidateFail = !1,
                        e.vm.validateFailMsg = "",
                        e.verifyCode = n
                    },
                    "onConfirm": function(n) {
                        n && n.preventDefault(),
                        e.verifyCode = e.vm.verifyInputVm.getValue(),
                        e.vm.isValidateFail || 0 != e.verifyCode && (!e.isNested && e.close(),
                        i.lang.isFunction(e.opts.onConfirm) && e.opts.onConfirm(e.verifyCode, e.verifySession))
                    },
                    "onCancel": function(n) {
                        n && n.preventDefault(),
                        i.lang.isFunction(e.opts.onCancel) && e.opts.onCancel(),
                        e.close()
                    }
                }),
                o.scan(this.container)
            },
            "getValue": function() {
                return {
                    "verifyCode": this.verifyCode,
                    "verifySession": this.verifySession
                }
            },
            "isClose": function() {
                return !this.vm
            },
            "verifyDone": function() {
                this.vm.onConfirm()
            },
            "setFailMsg": function(e) {
                this.vm && (this.vm.validateFailMsg = e)
            },
            "close": function() {
                i.lang.isFunction(this.opts.onDestroy) && this.opts.onDestroy(),
                this.vm = null,
                this.container.innerHTML = "",
                this.el.removeChild(this.container),
                this.container = null
            }
        }),
        a.TEXT = {
            "REINPUTVERIFY": "验证码错误，请重新输入"
        },
        e.exports = a
    },
    "72074753": function(e, n) {
        e.exports = {
            "QDQB": "qdqb",
            "QBQD": "qbqd",
            "QQACCT": "qqacct",
            "QQPOINT": "qqpoint",
            "KJ": "pccft",
            "BANK": "pcbank",
            "QQWALLET": "qqwallet",
            "QQCARD": "qqcard",
            "MCARD": "mcard",
            "WECHAT": "wechat",
            "HFPAY": "hfpay",
            "FRIENDPAY": "friendpay",
            "MOBILE": "mobile",
            "REMITPAY": "remitpay",
            "CFTB2B": "cft_b2b"
        }
    },
    "72658078": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div id="_cp__load__"  class="mdsweb-loading-wrapper loading_small" style="background-color:transparent; z-index:9995">\n    <div class="mdsweb-loading">\n        <div class="dot"></div>\n        <div class="dot"></div>\n        <div class="dot"></div>\n    </div>\n</div>';
            return __p
        }
    },
    "72700182": function(e, n, t) {
        var i = t(1)
          , o = t(4);
        t(90737419);
        var s = (t(48016802),
        t(112832022))
          , a = t(83497919)
          , r = t(55004913)
          , c = function(e, n) {
            var t = this;
            this.app = n,
            r.call(this, {
                "controllerId": e,
                "callbacks": {
                    "onAgreeRule": function(e) {
                        i.log(e)
                    },
                    "onClickService": function(e) {
                        i.log(e)
                    },
                    "onBack": function() {
                        t.app.back()
                    }
                },
                "loadVMConfig": function(e) {
                    e({
                        "headerData": this.getHeaderData()
                    })
                }
            })
        };
        o.inherits(c, r),
        i.mix(c.prototype, {
            "getHeaderData": function() {
                var e = {
                    "showBackText": !1
                };
                switch (e.name = this.opts.headerName || "",
                e.showBackText = this.opts.showBackText,
                this.opts.currentPage) {
                case "qb":
                    i.mix(e, {
                        "showClose": !0,
                        "showBack": !1
                    });
                    break;
                case "month":
                    e = a.getMonthTabsData([s.getInfo()])[0],
                    i.mix(e, {
                        "showBack": !1,
                        "showRule": !0,
                        "showHeaderBody": !s.showTab
                    });
                    break;
                case "subChannel":
                    e.name = this.opts.channelText,
                    i.mix(e, {
                        "showBack": !0,
                        "showRule": !1,
                        "showHeaderBody": !1
                    });
                    break;
                case "result":
                    e.name = "支付成功",
                    i.mix(e, {
                        "showBack": !0,
                        "showRule": !1,
                        "showHeaderBody": !0
                    })
                }
                return e
            },
            "setOpts": function(e) {
                r.prototype.setOpts.apply(this, arguments),
                this.controllerId = e.controllerId
            }
        });
        var l = {};
        e.exports = {
            "create": function(e, n) {
                if (!n.controllerId)
                    throw "header viewmode need the controllerId";
                var t;
                return t = l[n.controllerId] ? l[n.controllerId] : l[n.controllerId] = new c(n.controllerId,e),
                t.setOpts(n),
                t.off("ready"),
                t.once("vmReady", function(e) {
                    t.createVm(e),
                    t.emit("ready")
                }),
                t.loadVMConfig(),
                t
            }
        }
    },
    "72876602": function(e, n) {
        var t = function() {
            this.type = location.href.match(/(\w+)(?=\.(shtml|html))/)[0],
            this.channel = "",
            this.page = "",
            this.status = ""
        };
        t.prototype = {
            "setType": function(e) {
                this.type = e
            },
            "setChannel": function(e) {
                this.channel = e
            },
            "setPage": function(e) {
                this.page = e
            },
            "setStatus": function(e) {
                this.status = e
            },
            "getChannel": function() {
                return this.channel
            },
            "toJSON": function() {
                return {
                    "type": this.type,
                    "page": this.page,
                    "channel": this.channel,
                    "status": this.status
                }
            },
            "toString": function() {
                return String.format("{type}|{page}|{channel}|{status}", {
                    "type": this.type,
                    "page": this.page,
                    "channel": this.channel,
                    "status": this.status
                })
            }
        },
        e.exports = new t
    },
    "73982165": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<button ms-on-click="handleClick"\n        ms-on-mousedown="handleMouseDown"\n        ms-on-mouseup="handleMouseUp"\n        ms-on-mouseenter="handleMouseEnter"\n        ms-on-mouseleave="handleMouseLeave"\n        ms-class="btn btn-default" ms-class-1="btn-dis:disabled">\n    {{text}}\n    <span>{{subText}}</span>\n</button>';
            return __p
        }
    },
    "74061101": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<p ms-if="status===\'success\'" ms-html="info"></p>\n<p ms-if="status===\'fail\'" ms-html="info"></p>\n<p ms-if="status===\'error\'" ms-html="info"></p>\n';
            return __p
        }
    },
    "74109955": function(e, n) {
        e.exports = {
            "day": "day",
            "open": "open",
            "upgrade": "upgrade",
            "year": "year",
            "packet": "packet",
            "continousMonth": "continousMonth"
        }
    },
    "74720348": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div class="form-group" ms-class-1="has-feedback:value!=\'\'" ms-class-2="{{extraContainerClass}}" style="margin-bottom: 0;position: relative;z-index: 1" ms-css-width="width">\n    <label ms-attr-for="id" ms-if="enablePlaceHolder && value==\'\' && !ie7focused" style="position:absolute;z-index:1;font-size: 14px;width: 100%;left: 0;top: 0;" class="input-placeholder">\n        {{placeholder}}\n    </label>\n\n    <label style="background: none;" ms-css-width="width">\n\n        <input ms-class-1="{{defaultClass}}" ms-class-2="warn:state==1" ms-class-3="{{extraClass}}"\n            ms-class-4="focus:isFocused" type="text" ms-attr-id="id"\n               ms-attr-disabled="_disable"\n               ms-on-blur="handleBlur"\n               ms-on-focus="handleFocus"\n               ms-on-keydown="handleKeyDown"\n               ms-on-keyup="handleInput"\n         />\n\n        <i class="icon-clear" ms-on-mousedown="clearValue"></i>\n    </label>\n\n\n\n</div>';
            return __p
        }
    },
    "75217507": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div>\n    <div ms-if="showBack" class="header-icon-first" ms-on-click="back($event)">\n        <i class="icon-back"></i>&nbsp;\n    </div>\n    <div ms-if="showHeaderBody" class="prop-custom-title">\n        <img ms-attr-src="{{logo}}" ms-attr-alt="{{alt}}">\n        <span>{{name}}</span>\n        <div ms-if="showRule" ms-class-1="form-group checkbox-box service" ms-class-2="checked:checked">\n            <label for="vip1">\n                <input id="vip1" type="checkbox" name="vip">\n                <i class="icon-checkbox" ms-on-click="handleClickRuler($event)"></i> 同意<a href="#" ms-on-click="handleClickService($event)">服务条款</a>\n            </label>\n        </div>\n    </div>\n</div>';
            return __p
        }
    },
    "75677352": function(e, n, t) {
        var i = t(1)
          , o = (t(68718905),
        t(4))
          , s = t(54520283)
          , a = function(e, n, t) {
            this.handlers = t || {},
            this.vmConfig = {
                "$id": "order",
                "showOrder": !0,
                "orderHtml": ""
            },
            i.mix(this.handlers, {
                "onTemplate": function() {
                    return s()
                }
            })
        };
        a.prototype = {
            "init": function() {
                this.vm = i.define(this.vmConfig)
            },
            "onInit": function(e) {
                var n = this.vm;
                n.orderHtml = this.handlers.onTemplate(),
                i(o.Id("cp_loading_")).css({
                    "display": "none"
                })
            }
        },
        e.exports = a
    },
    "75685166": function(e, n, t) {
        var i = t(4)
          , o = t(1)
          , s = {
            "SJSJCH": 1,
            "LTMCLUB": 2,
            "LZFSSH": 3
        }
          , a = {}
          , r = null
          , c = {
            "fetchFeature": function(e, n) {
                switch (e) {
                case s.SJSJCH:
                    t.e(7, function(e) {
                        var i = t(79110808);
                        n(i)
                    });
                    break;
                case s.LTMCLUB:
                    t.e(8, function(e) {
                        var i = t(115887268);
                        n(i)
                    });
                    break;
                case s.LZFSSH:
                    t.e(9, function(e) {
                        var i = t(91188367);
                        n(i)
                    })
                }
            },
            "TYPE": s,
            "include": function(e) {
                var n = !1;
                return e > 0 && i.fn.each(s, function(t, i) {
                    if (t == e)
                        return n = !0,
                        !1
                }),
                n
            }
        };
        e.exports = {
            "feature": function() {
                return r
            },
            "switchFeature": function(e) {
                r = a[e]
            },
            "fetchFeature": function(e, n) {
                var t = new o.Promise(function(e, n) {
                    e()
                }
                );
                return c.include(n) ? t = new o.Promise(function(t, i) {
                    c.fetchFeature(n, function(n) {
                        a[e] = n,
                        r = n,
                        t()
                    })
                }
                ) : t
            }
        }
    },
    "75736919": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div>\n    <div ms-class="goods {{styleClass}}" ms-class-1="goods--large:cols==\'3c\'" ms-html="gamesHtml" style="margin-bottom:0" ms-on-mouseenter="mouseenter"\n         ms-on-mouseleave="mouseleave">\n\n    </div>\n</div>\n\n\n';
            return __p
        }
    },
    "75748174": function(e, n) {
        e.exports = "channel-disable"
    },
    "75846869": function(e, n, t) {
        var i = t(106745080)
          , o = t(108898004)
          , s = t(74061101)
          , a = t(50087682)
          , r = t(112168480)
          , c = t(84801805)
          , l = {
            "getTemplate": function() {
                return o.getTemplate({
                    "info": s(),
                    "market": a()
                })
            },
            "create": function(e) {
                var n = r;
                if (e.params)
                    switch (e.params.game_type) {
                    case i.Type.HOSTING:
                        n = r;
                        break;
                    case i.Type.NOHOSTING:
                        n = c;
                        break;
                    default:
                        n = r
                    }
                return new n(e)
            }
        };
        e.exports = l
    },
    "76511707": function(e, n, t) {
        var i = t(1)
          , o = document.all && !document.addEventListener
          , s = {
            "_cache": {},
            "getEl": function(e) {
                return this._cache[e] || (this._cache[e] = document.getElementById(e)),
                this._cache[e]
            },
            "_getStyle": function(e, n) {
                return document.defaultView.getComputedStyle(e, null).getPropertyValue(n)
            },
            "_doAnimation": function(e, n, t, i) {
                var o = this
                  , s = {}
                  , a = 16;
                for (var r in n)
                    s[r] = {
                        "s": (parseFloat(n[r]) - parseFloat(o._getStyle(e, r))) / t * a
                    };
                !function() {
                    setTimeout(function() {
                        for (var t in n) {
                            var r = parseFloat(o._getStyle(e, t))
                              , c = r + s[t].s
                              , l = s[t].s > 0 ? c > n[t] : c < n[t];
                            c = l ? n[t] : c,
                            c = "opacity" === t ? c : c + "px",
                            e.style[t] = c
                        }
                        l ? "function" == typeof i && i() : setTimeout(arguments.callee, a)
                    }, a)
                }()
            },
            "init": function(e) {
                i(this.getEl("animation_masktop")).css({
                    "display": "block",
                    "opacity": .1,
                    "top": 0,
                    "height": e.h0
                }),
                i(this.getEl("animation_mask")).css({
                    "display": "block",
                    "opacity": .1,
                    "top": e.h0,
                    "height": i(window).height() - e.h0 - 1
                })
            },
            "start": function(e, n, t, o, s) {
                this.init(t);
                var a = this;
                a._doAnimation(this.getEl("animation_mask"), {
                    "opacity": 1,
                    "top": t.h1
                }, 500),
                a._doAnimation(this.getEl("animation_masktop"), {
                    "opacity": 1,
                    "height": t.h1
                }, 500, function() {
                    i(a.getEl(e)).css({
                        "display": "none"
                    }),
                    o.currentComponent = n,
                    i(a.getEl(n)).css({
                        "display": "block"
                    }),
                    a.end(s)
                })
            },
            "end": function(e) {
                var n = this;
                this._doAnimation(this.getEl("animation_mask"), {
                    "opacity": 0
                }, 100),
                this._doAnimation(this.getEl("animation_masktop"), {
                    "opacity": 0
                }, 100, function() {
                    i(n.getEl("animation_mask")).css({
                        "display": "none"
                    }),
                    i(n.getEl("animation_masktop")).css({
                        "display": "none"
                    }),
                    e && e()
                })
            }
        };
        e.exports = function(e, n, t, a, r) {
            if (a = a || {},
            "order" !== e || "subChannel" !== n || o)
                "subChannel" !== e || "order" !== n || o ? (i(document.getElementById(t.currentComponent)).css({
                    "display": "none"
                }),
                t.currentComponent = n,
                i(document.getElementById(t.currentComponent)).css({
                    "display": "block"
                }),
                r && r()) : s.start(e, n, {
                    "h0": a.h1 || 90,
                    "h1": a.h0 || 164
                }, t, r);
            else {
                var c = {
                    "h0": a.h0 || 164,
                    "h1": a.h1 || 90
                };
                s.start(e, n, c, t, r)
            }
        }
    },
    "76531812": function(e, n, t) {
        var i = (t(4),
        t(23),
        t(112745811))
          , o = !1
          , s = {
            "_store": null,
            "init": function(e, n) {
                if (o)
                    return void ("function" == typeof n && n());
                if (o = !0,
                "undefined" != typeof Raven) {
                    var a = e.session ? e.session.getSessionParam() : {};
                    Raven.setUserContext({
                        "id": a.openid || "UNKNOWN"
                    })
                }
                switch (e.type) {
                case i.GAME:
                    !function() {
                        var i = 2
                          , o = function() {
                            --i < 1 && function(i) {
                                var o = t(87561709);
                                s._store = new o(e),
                                "function" == typeof n && n()
                            }(t)
                        };
                        t.e(16, o),
                        t.e(3, o)
                    }();
                    break;
                case i.MONTH:
                    !function() {
                        var i = 2
                          , o = function() {
                            --i < 1 && function(i) {
                                var o = t(86797109);
                                s._store = o.create(e),
                                "function" == typeof n && n()
                            }(t)
                        };
                        t.e(18, o),
                        t.e(4, o)
                    }();
                    break;
                case i.QB:
                    !function() {
                        var i = 2
                          , o = function() {
                            --i < 1 && function(i) {
                                var o = t(118796619);
                                s._store = o.create(e),
                                "function" == typeof n && n()
                            }(t)
                        };
                        t.e(19, o),
                        t.e(5, o)
                    }();
                    break;
                case i.GOODS:
                    !function() {
                        var i = 2
                          , o = function() {
                            --i < 1 && function(i) {
                                var o = t(69068857);
                                s._store = new o(e),
                                "function" == typeof n && n()
                            }(t)
                        };
                        t.e(17, o),
                        t.e(6, o)
                    }();
                    break;
                default:
                    s._store = e.store
                }
            },
            "isInit": function() {
                return o
            },
            "render": function(e) {
                this._store.render(e)
            },
            "rebindChannel": function(e) {
                this._store.rebindChannel && this._store.rebindChannel(e)
            },
            "renderChannel": function(e, n) {
                this._store.renderChannel(e, n)
            },
            "on": function() {
                return this._store.on.apply(this._store, arguments)
            },
            "off": function() {
                return this._store.off.apply(this._store, arguments)
            },
            "emit": function() {
                return this._store.emit.apply(this._store, arguments)
            },
            "getStore": function() {
                return s._store
            }
        };
        e.exports = s
    },
    "76686721": function(e, n) {
        var t = {};
        e.exports = function(e) {
            t[e] || (t[e] = {
                "q": [],
                "s": 1
            });
            var n = t[e];
            return {
                "add": function(e) {
                    n.q.push(e),
                    3 === n.s && this.run()
                },
                "run": function() {
                    if (1 === n.s || 3 === n.s) {
                        n.s = !0,
                        n.s = 2;
                        var e = function() {
                            return 0 == n.q.length ? void (n.s = 3) : void n.q.shift()(function() {
                                e()
                            })
                        };
                        e()
                    }
                }
            }
        }
    },
    "77769056": function(e, n, t) {
        var i = t(4)
          , o = t(1)
          , s = t(47721167);
        t(97501907);
        var a = t(120707620)
          , r = i.fn.getParams();
        o.component("ms:banktypechoose", {
            "$template": t(69061514)(),
            "$parent": null,
            "$replace": !0,
            "$selectName": "银行类型",
            "radioId": "",
            "radioList": [],
            "index": null,
            "onInit": i.fn.emptyFunc,
            "$init": function(e, n) {
                e.$parent = o.components["ms:radiogroup"]
            },
            "$ready": function(e, n) {
                e.$parent.$init(e, n),
                e.$parent.fireOninit.call(e),
                e.onInit(e)
            },
            "$dispose": function(e) {
                e.$parent.$dispose(e)
            },
            "handleClick": function() {
                this.$parent.handleClick.apply(this, arguments)
            }
        }),
        o.component("ms:bankchoose", {
            "$template": t(81040968)(),
            "$extend": "radiogroup",
            "$replace": !0,
            "$parent": null,
            "radioId": "",
            "radioList": [],
            "index": "",
            "showMoreBank": !1,
            "onInit": i.fn.emptyFunc,
            "onChange": i.fn.emptyFunc,
            "$init": function(e, n) {
                e.$parent = o.components["ms:radiogroup"],
                e.$parent.$init(e, n),
                e.$parent.fireOninit.call(e)
            },
            "$ready": function(e, n) {
                e.$parent.$init(e, n),
                e.$parent.fireOninit.call(e),
                e.onInit(e)
            },
            "$dispose": function(e) {
                e.$parent.$dispose(e)
            },
            "handleClick": function() {
                this.$parent.handleClick.apply(this, arguments)
            },
            "getChecked": function() {
                return this.$parent.getChecked()
            },
            "moreBank": function() {
                this.showMoreBank = !0
            },
            "lessBank": function() {
                this.showMoreBank = !1
            },
            "setList": function(e, n) {
                this.radioList = [],
                this.index = null;
                var t = {};
                e == s.BankType["B2C"] ? t = window.__BANK_CONFIG : e == s.BankType["B2B"] && (t = window.__B2B_BANK_CONFIG);
                var i = this
                  , a = 0
                  , r = null;
                o.each(t, function(e, t) {
                    (t[s.CardType.credit] && t[s.CardType.credit]["bank"] || t[s.CardType.debit] && t[s.CardType.debit]["bank"]) && (i.radioList.push({
                        "name": t.name,
                        "value": e,
                        "logo": t.logo || e
                    }),
                    n && n == e && (r = a),
                    ++a)
                });
                var c = i.radioList;
                null != r && (c[0] = [c[r], c[r] = c[0]][0]),
                this.index = 0
            }
        }),
        o.component("ms:typechoose", {
            "$template": t(69061514)(),
            "$parent": null,
            "$replace": !0,
            "$selectName": "选择卡种",
            "radioId": "",
            "radioList": [],
            "index": null,
            "onInit": i.fn.emptyFunc,
            "onChange": i.fn.emptyFunc,
            "$init": function(e, n) {
                e.$parent = o.components["ms:radiogroup"]
            },
            "$ready": function(e, n) {
                e.$parent.$init(e, n),
                e.$parent.fireOninit.call(e),
                e.onInit(e)
            },
            "$dispose": function(e) {
                e.$parent.$dispose(e)
            },
            "handleClick": function() {
                this.$parent.handleClick.apply(this, arguments)
            },
            "getChecked": function() {
                return this.$parent.getChecked()
            },
            "setList": function(e, n) {
                this.index = null,
                this.radioList = e,
                "undefined" != typeof n ? this.index = n : this.index = 0
            }
        });
        var c = [{
            "name": s.BankTypeDesc["B2C"],
            "value": s.BankType["B2C"]
        }];
        r.appid && window.__SHOW_B2B_BANK_WHITELIST && window.__SHOW_B2B_BANK_WHITELIST.indexOf(r.appid) > -1 ? c = [{
            "name": s.BankTypeDesc["B2B"],
            "value": s.BankType["B2B"]
        }] : r.appid && window.__SHOW_ALL_BANK_WHITELIST && window.__SHOW_ALL_BANK_WHITELIST.indexOf(r.appid) > -1 && (c = [{
            "name": s.BankTypeDesc["B2C"],
            "value": s.BankType["B2C"]
        }, {
            "name": s.BankTypeDesc["B2B"],
            "value": s.BankType["B2B"]
        }]);
        var l = [];
        o.each(c, function(e, n) {
            l.push(n.value)
        }),
        o.component("ms:bankselector", {
            "$template": a(),
            "$replace": !0,
            "onInit": i.fn.emptyFunc,
            "haspaytype": !1,
            "$skipArray": ["bankList", "filterType"],
            "bankList": {},
            "kjdiscount": 1,
            "showMoreBank": !1,
            "bank": null,
            "curBankType": null,
            "curCardType": null,
            "bankName": null,
            "cardTypeName": null,
            "bankTypeName": null,
            "bankTypeListConfig": {
                "radioList": c,
                "index": null
            },
            "filterType": null,
            "$computed": {
                "bankClass": {
                    "get": function() {
                        if (this.bank)
                            return "icon-" + this.bank
                    }
                }
            },
            "onSelectedBank": o.noop,
            "$init": function(e, n) {
                e.curBankType && l.indexOf(e.curBankType) > -1 ? e.bankTypeListConfig.index = l.indexOf(e.curBankType) : e.bankTypeListConfig.index = 0
            },
            "$ready": function(e) {},
            "handleChooseBankType": function(e, n) {
                if (e) {
                    this.curBankType = e.value;
                    var t = this;
                    o.each(o.vmodels, function(n, i) {
                        i && i.$id && i.$id.indexOf("bankchoose") > -1 && i && i.setList(e.value, t.bank ? t.bank : "")
                    })
                }
            },
            "handleChooseBank": function(e, n) {
                e && (this.bank = e.value,
                this.showCardType())
            },
            "handleChooseCardType": function(e, n) {
                e && (this.curCardType = e.value,
                this.onSelectedBank(this.getSelectInfo()))
            },
            "showCardType": function() {
                var e = this.curBankType == s.BankType["B2B"] ? window.__B2B_BANK_CONFIG : window.__BANK_CONFIG
                  , n = e[this.bank];
                if (n) {
                    var t = []
                      , i = 0
                      , a = this;
                    n.cardTypes.forEach(function(e, o) {
                        a.filterType && !n[e][a.filterType] || (e == a.curCardType && (i = o),
                        !!s.CardTypeDesc[e] && t.push({
                            "name": s.CardTypeDesc[e],
                            "value": e
                        }))
                    }
                    .bind(this)),
                    o.each(o.vmodels, function(e, n) {
                        n && n.$id && 0 == n.$id.indexOf("typechoose") && n && n.setList(t, i)
                    })
                }
            },
            "getSelectInfo": function() {
                return {
                    "curBankType": this.curBankType,
                    "bank": this.bank,
                    "curCardType": this.curCardType
                }
            }
        }),
        e.exports = {
            "create": function(e, n) {
                return n = n || {},
                String.format('<ms:bankselector config="{config}" on-selected-bank="{onSelectedBank}"></ms:bankselector>', {
                    "config": e || "bankConfig",
                    "onSelectedBank": n.onSelectedBank
                })
            }
        }
    },
    "78805100": function(e, n, t) {
        var i = t(4)
          , o = (t(1),
        {});
        e.exports = {
            "roleList": function(e) {
                var n = [];
                return e.forEach(function(e, t) {
                    n.push({
                        "txt": e.role_name,
                        "val": e.role_id
                    })
                }),
                {
                    "data": n
                }
            },
            "serverList": function(e, n) {
                var t = e[0]
                  , i = "opt_data_array"
                  , o = "t"
                  , s = "v"
                  , a = "t"
                  , r = "v";
                t && t.hasOwnProperty("sList") && (i = "sList",
                o = "name",
                s = "id",
                a = 0,
                r = 1);
                var c = [];
                return e.forEach(function(e) {
                    if (e[s] == n) {
                        var t = [];
                        e[i].forEach(function(e) {
                            t.push({
                                "val": e[r],
                                "txt": e[a],
                                "status": e.status
                            })
                        }),
                        c.push(t)
                    }
                }),
                {
                    "data": c
                }
            },
            "zoneList": function(e) {
                var n = e[0]
                  , t = "opt_data_array"
                  , i = "t"
                  , o = "v"
                  , s = "t"
                  , a = "v";
                n && n.hasOwnProperty("sList") && (t = "sList",
                i = "name",
                o = "id",
                s = 0,
                a = 1);
                var r = n && n[t] && n[t].length > 0
                  , c = [];
                return e.forEach(function(e) {
                    c.push({
                        "val": e[o],
                        "txt": e[i],
                        "status": e.status
                    })
                }),
                {
                    "data": c,
                    "hasServer": r
                }
            },
            "friendList": function(e, n) {
                var t = [];
                if (n) {
                    var s = n.split(",");
                    s.forEach(function(e, n) {
                        var s = e.split("|")
                          , a = i.escHTML(decodeURIComponent(s[0].replace(/\n|\r/g, "")), !0) || "";
                        try {
                            for (var r = s[1].split("+"), c = [], l = 0; l < r.length; l += 2) {
                                var u = i.escHTML(decodeURIComponent(r[l + 1]).replace(/\n|\r/g, ""), !0) || ""
                                  , d = r[l];
                                d && (o[d] = {
                                    "uin": d,
                                    "nick": u
                                },
                                c.push({
                                    "name": u,
                                    "qq": d,
                                    "mac": l / 2 % 4 + 1
                                }))
                            }
                        } catch (p) {}
                        t.push({
                            "name": a,
                            "expand": !1,
                            "children": c
                        })
                    })
                }
                return o[e] = {
                    "uin": e,
                    "nick": "自己"
                },
                o.self = o[e],
                e && t.unshift({
                    "name": "自己",
                    "qq": e
                }),
                t
            },
            "friendListV2": function(e, n, t) {
                o[n] = {
                    "uin": i.fn.desensitize(e.qq),
                    "nick": e.nick
                },
                o.self = o[n];
                var s = Object.keys(t).reduce(function(e, n) {
                    if ("group_info" !== n) {
                        var s = i.fn.splitFirst(decodeURIComponent(n), "|")
                          , a = parseInt(s[0], 10)
                          , r = s[1]
                          , c = t[n].map(function(e) {
                            var n = e.split("|")
                              , t = n[0];
                            return o[t] ? null : (o[t] = {
                                "uin": n[1],
                                "nick": decodeURIComponent(n[2])
                            },
                            {
                                "qq": t
                            })
                        }).filter(Boolean);
                        e[a] = {
                            "name": r,
                            "expand": !1,
                            "children": c
                        }
                    }
                    return e
                }, []).filter(Boolean);
                return s.unshift({
                    "qq": n
                }),
                s
            },
            "setDisplayInfoByOpenid": function(e, n) {
                o[e] = n
            },
            "getDisplayInfoByOpenid": function(e) {
                return i.fn.isOpenid(e) ? o[e] || o.self || {} : o[e] || {
                    "uin": e,
                    "nick": "陌生人"
                }
            },
            "targetInfo": function(e) {
                return {
                    "targetUin": e.uin || e.qq,
                    "targetName": e.name,
                    "targetOpenid": e.openid
                }
            }
        }
    },
    "78877987": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div>\n  <div id="order_info">\n    <div class="prop" ms-if="!showSimpleOrder">\n      <div class="account" style="position:relative;z-index:100">\n        <div class="account-area" ms-if="!accountEditable">\n          <span class="account-title">充值账号：</span>\n          <div ms-class="account-id account-default-id active">\n            <span class="loged-id" ms-class-1="loged-id-max:showAreaInfo.length>0" ms-attr-title="account">{{account |\n              html}}</span>\n            <div class="game-area" ms-if="showAreaInfo"><span ms-attr-title="areaName+serverName+roleName"\n                class="game-area__txt">{{areaName}}{{serverName}}{{roleName}}</span>\n            </div>\n            <span class="change-id" ms-on-click="changeAccount" ms-if="enableChangeAccount||areaEditable"\n              data-track="changeId"><i class="icon-change"></i>更换</span>\n          </div>\n          <span class="switch_account" ms-if="supportMutilLogin.length>0">\n            切换账号：\n            <span ms-each-item="supportMutilLogin">\n              <i ms-class-1="icon-qq-login:item[0]==\'qq\'" ms-class-2="icon-wx-login:item[0]==\'wechat\'"\n                ms-on-click="onChangeLoginType(item)"></i>\n            </span>\n          </span>\n        </div>\n        <div class="account-area" ms-if="accountEditable">\n          <span class="account-title">充值账号：</span>\n          <div class="account-id account-change-id active">\n            <div class="friend friend--s" ms-if="enableChangeAccount">\n              <div id="friendSelector"></div>\n            </div>\n            <div ms-if="!enableChangeAccount">\n              <span class="loged-id" ms-if="!account">...</span>\n              <span class="loged-id loged-id-max" ms-attr-title="account">{{account | html}}</span>\n            </div>\n          </div>\n          <div class="game-area game-area--region mod-input-selection mod-input-selection--inline"\n            ms-html="areaListHtml" ms-if="areaListHtml" data-track="chooseArea"></div>\n          <div class="game-area game-area--serve mod-input-selection mod-input-selection--inline"\n            ms-html="serverListHtml" ms-if="serverListHtml" data-track="chooseServer"></div>\n          <div class="game-area game-area--role mod-input-selection mod-input-selection--inline" ms-html="roleListHtml"\n            ms-if="roleListHtml" data-track="chooseRole"></div>\n          <span class="switch_account" ms-if="supportMutilLogin.length>0">\n            切换账号：\n            <span ms-each-item="supportMutilLogin">\n              <i ms-class-1="icon-qq-login:item[0]==\'qq\'" ms-class-2="icon-wx-login:item[0]==\'wechat\'"\n                ms-on-click="onChangeLoginType(item)"></i>\n            </span>\n          </span>\n        </div>\n        <p ms-visible="showAccountTips" class="tips icon-tips warn account-tips"\n          style="position:absolute;margin-left:0;margin-bottom:0;left:0">\n          <i class="icon-warn"></i> <span>{{accountSubmitTips}}</span>\n        </p>\n        <p ms-visible="showAreaTips" class="tips icon-tips warn account-tips"\n          style="position:absolute;left:150px;margin-bottom:0;">\n          <i class="icon-warn"></i> <span>{{areaSubmitTips}}</span>\n        </p>\n        <div style="clear:both;width:100%;height:0"></div>\n      </div>\n      <div ms-html="gamePriceListHtml"></div>\n    </div>\n    <div ms-if="showSimpleOrder">\n      <div class="prop prop-brief">\n        <div class="prop-brief-info">\n          <span>为 </span><span class="account-id">{{account|html}}{{areaName}}{{serverName}}{{roleName}}</span> <span\n            class="business">{{buyinfo}}</span>\n          <span class="duration">x {{buycount}}</span>\n        </div>\n        <em class="total-price-in-brief">{{price}}</em>\n        <div class="prop-price">元</div>\n      </div>\n    </div>\n  </div>\n  <div ms-html="channelList"></div>\n  <!--<div class="cp-body__mask" ms-visible="!canOrder"></div>-->\n</div>';
            return __p
        }
    },
    "78901017": function(e, n, t) {
        var i = t(4)
          , o = t(78805100)
          , s = t(1)
          , a = s.bind
          , r = document.all && window.XMLHttpRequest && !document.querySelector
          , c = {
            "mode": 1,
            "data": [],
            "initCallBack": !0,
            "initExpand": !1,
            "value": {},
            "maxlength": 15,
            "placeholder": "好友QQ号/昵称",
            "container": "",
            "onFriendSelected": function() {},
            "onBlur": function() {},
            "onInit": function() {}
        }
          , l = function(e) {
            this.opt = i.fn.extend(c, e || {}),
            this.hideAble = !0,
            this.preValue = "",
            this.isQQConnect = i.fn.isOpenid(this.opt.data[0].qq),
            this.opt.maxlength = this.isQQConnect ? 1 / 0 : this.opt.maxlength,
            this.init()
        };
        l.prototype = {
            "_supportPlaceHolder": function() {
                if ("undefined" == typeof this.isSupportPlaceHolder) {
                    var e = document.createElement("input");
                    this.isSupportPlaceHolder = "placeholder"in e && !document.all
                }
                return this.isSupportPlaceHolder
            },
            "guid": function() {
                return (1e3 * Math.random() + 200).toString().replace(".", "")
            },
            "_mainHtml": function() {
                var e = this.opt
                  , n = this._supportPlaceHolder()
                  , t = (e.value.qq ? e.value.qq : "",
                ['<div class="friend"><div class="form-inline" ><div class="form-group form-combined" id="' + this.containerId + '">']);
                return t.push(' <label><input id="' + this.inputId + '" class="form-input" type="text"  maxlength="' + e.maxlength + '" data-track="friendInput"'),
                n && t.push('placeholder="' + e.placeholder + '"'),
                t.push("/>"),
                n || t.push('<span class="input-placeholder" id="' + this.simPlaceHolderId + '" style="height: 100%;line-height:30px;z-index: 10;visibility: hidden;">' + e.placeholder + "</span>"),
                t.push("</label>"),
                t.push('<button class="form-btn form-btn-icon" id="' + this.btnId + '" title="选择好友"><i class="icon-friend"></i></button>'),
                t.push("</div></div></div>"),
                t.join("")
            },
            "_escHTML": function(e) {
                e = e || "";
                for (var n = ["<", "&lt;", ">", "&gt;", " ", "&nbsp;", '"', "&quot;", "'", "&#39;"], t = 0, i = e; t < n.length; t += 2)
                    i = i.replace(new RegExp(n[t],"g"), n[1 + t]);
                return i
            },
            "_getDisplayInfo": function(e) {
                if (!e.length) {
                    var n, t, s = e.qq, a = e.name;
                    if (i.fn.isOpenid(s)) {
                        var r = o.getDisplayInfoByOpenid(s);
                        n = this._escHTML(r.nick),
                        t = r.uin
                    } else
                        n = this._escHTML(a),
                        t = s;
                    return {
                        "displayName": n,
                        "displayQQ": t
                    }
                }
            },
            "_buildDropdown": function(e) {
                var n = this.opt
                  , t = e instanceof Array ? e : n.data
                  , i = "f_list"
                  , o = "";
                this._dropDownData = t;
                var s = [];
                0 == t.length && (i += " f_list_empty",
                o = "<span >暂无数据！</span>"),
                s.push('<div class="' + i + '" >'),
                s.push(o);
                for (var a = 0, r = t.length; a < r; a++) {
                    0 == a && s.push('<ul class="f_groups">');
                    var c = t[a].children
                      , l = this._getDisplayInfo(t[a])
                      , u = this._escHTML(l.displayName) + "(" + l.displayQQ + ")"
                      , d = c ? "f_group" : ""
                      , p = c ? "icon-more-friend" : "icon-friend-s"
                      , h = c ? this._escHTML(t[a].name) : u
                      , f = c ? "" : u;
                    t[a].expand && (d += " open");
                    var m = t[a].children;
                    if (s.push(' <li class="' + d + '" >'),
                    s.push('<a data-index="' + a + '" data-child="' + (m ? "1" : "0") + '" href="#" ' + (f ? 'title:"' + f + '"' : "") + '> <i class="' + p + '"></i>  ' + h + " </a>"),
                    m)
                        for (var g = t[a].children, v = t[a].expand ? "" : "none", b = 0; b < g.length; b++) {
                            var y = g[b];
                            0 == b && s.push('<ul class="group-list" style="display:' + v + '">');
                            var l = this._getDisplayInfo(y)
                              , _ = l.displayName
                              , k = l.displayQQ
                              , w = _ + "(" + k + ")"
                              , C = a + "-" + b;
                            s.push(" <li >"),
                            s.push('<a href="#" data-index="' + C + '" title="' + w + '"> <i class="icon-friend-s"></i>' + w + "</a>"),
                            s.push(" </li>"),
                            b == g.length - 1 && s.push("</ul>")
                        }
                    s.push("</li>"),
                    a == r - 1 && s.push("</ul>")
                }
                return s.join("")
            },
            "init": function() {
                var e = this.opt;
                if (this.inputId = this.guid(),
                this.btnId = "btn_" + this.inputId,
                this.containerId = "ctn_" + this.inputId,
                this.dropDownId = "drop_" + this.inputId,
                this.simPlaceHolderId = "sim_" + this.inputId,
                e.container) {
                    "string" == typeof e.container ? this.container = document.getElementById(e.container) : this.container = e.container,
                    this.container.innerHTML = this._mainHtml();
                    var n = document.createDocumentFragment()
                      , t = document.createElement("div");
                    t.innerHTML = '<div  class="dropdown" style="z-index: 10000"  id="' + this.dropDownId + '">' + this._buildDropdown() + "</div>",
                    n.appendChild(t.firstChild),
                    document.body.appendChild(n),
                    this.markUp(),
                    this.setValue(this.opt.value),
                    this.bindEvents(),
                    this.opt.initExpand && this.showList(),
                    this.opt.initCallBack && this.opt.onFriendSelected(this.matchOneItem(this.opt.value.qq), !0),
                    this.opt.onInit(this)
                }
            },
            "markUp": function() {
                this.input = document.getElementById(this.inputId),
                this.button = document.getElementById(this.btnId),
                this.innerContainer = document.getElementById(this.containerId),
                this.dropDownContainer = document.getElementById(this.dropDownId),
                this.simPlaceHolder = document.getElementById(this.simPlaceHolderId)
            },
            "showList": function(e) {
                var n = {};
                if (!this.positioned) {
                    var t = this.innerContainer.getBoundingClientRect()
                      , i = s(this.innerContainer).height()
                      , o = s(window).height()
                      , a = s(this.dropDownContainer).height()
                      , r = o - t.bottom;
                    r > t.top ? n.top = s(window).scrollTop() + t.top + i : n.top = s(window).scrollTop() + t.top - a,
                    n.left = t.left,
                    n.width = t.right - t.left,
                    s(this.dropDownContainer).css(n),
                    this.positioned = !0
                }
                "" === this.input.value && this.keyup(!0),
                2 === this.opt.mode ? e ? "" === this.input.value && this.showDropDown(!0) : (this.input.value = "",
                this.keyup(),
                this.showDropDown(!0),
                this.focusInput()) : (this.showDropDown(!0),
                this.focusInput())
            },
            "setHideAble": function(e) {
                this.hideAble = !!e
            },
            "setPlaceHolder": function() {
                if (!this._supportPlaceHolder() && !r) {
                    var e = "" === this.input.value ? "visible" : "hidden";
                    this.simPlaceHolder.style.visibility = e
                }
            },
            "setValue": function(e) {
                this.opt.value = e,
                e.qq ? this.input.value = i.fn.isOpenid(e.qq) ? String.format("{uin}({nick})", o.getDisplayInfoByOpenid(e.qq)) : e.qq : this.input.value = "",
                this.preValue = e,
                this.setPlaceHolder()
            },
            "blur": function(e) {
                if (!this.hideAble)
                    return e.preventDefault && e.preventDefault(),
                    void this.focusInput();
                this.showDropDown(!1);
                var n = this.matchOneItem(this.input.value);
                this.setValue(n),
                this.opt.onBlur(n)
            },
            "matchOneItem": function(e) {
                if (!e)
                    return this.preValue;
                if (/\d{,4}/.test(e))
                    return {
                        "name": "无效QQ号",
                        "qq": e,
                        "invalid": 1
                    };
                var n = this._searchData(e, !0)
                  , t = n.length ? n[0] : /\d{5,}/.test(e) && !this.isQQConnect ? {
                    "name": "陌生人",
                    "qq": e,
                    "stranger": 1
                } : this.preValue;
                return t.qq === this.opt.data[0].qq && (t.name = "自己"),
                t
            },
            "keydown": function(e) {
                8 != e.keyCode && 46 != e.keyCode && this.input.value.length >= this.opt.maxlength && e.preventDefault()
            },
            "select": function(e) {
                var n = e.target || e.srcElement;
                if ("i" === n.nodeName.toLocaleLowerCase() && (n = n.parentNode),
                "a" === n.nodeName.toLocaleLowerCase()) {
                    var t = "1" === n.getAttribute("data-child");
                    if (t) {
                        var i = n.parentNode.className
                          , o = i.indexOf("open") === -1;
                        n.nextSibling && (n.nextSibling.style.display = o ? "block" : "none"),
                        n.parentNode.className = o ? i + " open" : i.replace("open", "")
                    } else {
                        var s = n.getAttribute("data-index").split("-")
                          , a = this._dropDownData[s[0]];
                        s.length > 1 && (a = a.children[s[1]]),
                        this.setValue(a),
                        this.setHideAble(1),
                        this.showDropDown(!1),
                        this.opt.onFriendSelected(a),
                        2 === this.opt.mode && this.input.blur()
                    }
                }
            },
            "_searchData": function(e, n) {
                e += "",
                e = this._escHTML(e);
                var t = []
                  , o = this
                  , s = this.opt.data
                  , a = function(n, t, s) {
                    if (n === t.qq)
                        return !0;
                    var a = i.fn.isOpenid(String(t.qq))
                      , r = o._getDisplayInfo(t)
                      , c = a ? r.displayQQ : String(t.qq)
                      , l = a ? r.displayName : t.name
                      , u = e
                      , d = "";
                    if (/\d+\*+\d+\(.+\)/.test(e) && (u = e.match(/^\d+\*+\d+/)[0]),
                    /\(.*\)/.test(e) && (d = e.match(/\(.*\)/)[0]),
                    s)
                        return d ? "(" + l + ")" === d && u === c : u === c;
                    var p = i.fn.matchDesensitized(u, c);
                    return l.indexOf(e) !== -1 || p
                };
                return s.forEach(function(i) {
                    i.children ? i.children.forEach(function(i) {
                        a(e, i, n) && t.push(i)
                    }) : a(e, i, n) && t.push(i)
                }),
                t
            },
            "keyup": function(e) {
                this.setPlaceHolder();
                var n = this;
                this.timer && clearTimeout(this.timer);
                var t = function() {
                    var e = n.input.value;
                    if ("" === e)
                        return void (n.dropDownContainer.innerHTML = n._buildDropdown());
                    var t = n._searchData(e);
                    2 === n.opt.mode && (0 == t.length ? n.dropDownContainer.style.display = "none" : (n.showDropDown(!0),
                    n.dropDownContainer.style.display = "block")),
                    n.dropDownContainer.innerHTML = n._buildDropdown(t)
                };
                e ? t() : this.timer = setTimeout(t, 100)
            },
            "showDropDown": function(e) {
                this.dropDownContainer.style.display = e ? "block" : "none"
            },
            "bindEvents": function() {
                var e = this;
                a(this.innerContainer, "click", function(n) {
                    var t = "INPUT" === n.target.nodeName;
                    t || (e.dropDownContainer.innerHTML = e._buildDropdown()),
                    e.showList(t)
                }),
                a(this.input, "blur", function(n) {
                    e.blur(n)
                }),
                a(this.input, "keyup", function(n) {
                    e.keyup(n)
                }),
                a(this.input, "keydown", function(n) {
                    e.keydown(n)
                }),
                s.bind(this.dropDownContainer, "mouseleave", function(n) {
                    e.setHideAble(1)
                }),
                s.bind(this.dropDownContainer, "mouseenter", function(n) {
                    e.setHideAble(0)
                }),
                a(this.dropDownContainer, "click", function(n) {
                    n.preventDefault && n.preventDefault(),
                    e.select(n)
                })
            },
            "destroy": function() {},
            "show": function() {
                return this.showList()
            },
            "focusInput": function() {
                var e = this.input
                  , n = i.fn.isOpenid(this.opt.data[0].qq);
                n && (e.value = "");
                try {
                    e.focus()
                } catch (t) {}
            }
        },
        e.exports = {
            "create": function(e) {
                return new l(e)
            }
        }
    },
    "79091806": function(e, n, t) {
        var i = t(4)
          , o = t(1);
        t(89500152);
        var s = t(17)
          , a = t(109735088)
          , r = t(7)
          , c = t(9)
          , l = t(102521382)
          , u = t(87796589)
          , d = t(105875273)
          , p = t(84811753)
          , h = t(119561448)
          , f = t(70508452)
          , m = t(100835382)
          , g = t(51748615)
          , v = t(72074753)
          , b = t(75748174)
          , y = t(112745811)
          , _ = t(49140953)
          , k = t(43847285)
          , w = function(e, n) {
            m.apply(this, arguments),
            this._subSession = null,
            this._subCGI = null,
            this.info = e.info,
            this._relogin = !1,
            this._balance = i.math.div(this.info.qqacct_balance, 100),
            this.cgi = this.store.getCgi(),
            this._price = 0,
            this.initVm(),
            this.calPrice(),
            0 == this.store.getAmount() ? this.vm.disableSubmit = !0 : this.vm.disableSubmit = !1,
            this.refreshUIBalance()
        };
        i.inherits(w, m),
        w.prototype.calPrice = function() {
            var e = this.store.getPrice().price;
            this._price = this.store.getPrice(i.discount.checkHasDiscount(e, this.channelObj.channel) ? this.channelObj.discount : void 0, this.coupon).price,
            this.vm && (this.vm.price = this._price)
        }
        ,
        w.prototype.refreshUIBalance = function() {
            var e = this.store.getBalanceInfo();
            e.QQofBalance && (e.balanceOfQQ || 0 == e.balanceOfQQ) ? (this._balance = e.balanceOfQQ,
            this.showSurplusRes({
                "balance": this._balance,
                "uin": e.QQofBalance
            })) : (this._balance = i.math.div(this.info.qqacct_balance, 100),
            this.showSurplusRes({
                "balance": this._balance
            }))
        }
        ,
        w.prototype.setAutoPaySelectUI = function() {
            this.vm.showAutoTips = !!this.store.supportAutoPay(this.channelObj) && this.vm.balance >= this.vm.price
        }
        ,
        w.prototype.onChange = function() {
            this.refreshCoupon(),
            this.calPrice(),
            this.refreshUIBalance(),
            this.setAutoPaySelectUI(),
            this.vm.balance != -1 && (this.vm.balance >= this.vm.price ? (this.vm.showBalance = !0,
            this.vm.balanceNotEnough = !1) : (this.vm.diff = Math.ceil(this.vm.price - this.vm.balance),
            this.vm.showBalance = !1,
            this.vm.balanceNotEnough = !0,
            this.setAutoPay(!1))),
            0 == this.store.getAmount() ? this.vm.disableSubmit = !0 : this.vm.disableSubmit = !1
        }
        ,
        w.prototype._getLoginStatusFromCookie = function(e) {
            var n = a.getLoginStatusFromCookie();
            if (!n)
                return null;
            var t = i.fn.getParams();
            return this._subSession = new c({
                "openid": n.uin,
                "openkey": n.skey,
                "sessionid": "uin",
                "sessiontype": "skey"
            }),
            this._subCGI = new r({
                "appid": t.appid,
                "sandbox": ~~t.sandbox,
                "sessionObj": this._subSession,
                "pf": t.pf,
                "diableAutoCookie": !e,
                "pfkey": t.pfkey
            }),
            n
        }
        ,
        w.prototype.isQQLogin = function() {
            var e = a.getLoginStatus();
            return !e.qq && this._relogin && (e = this._getLoginStatusFromCookie()),
            e && e.qq
        }
        ,
        w.prototype.supportFetchLoginFromCookie = function() {
            if ((window._QB_Channel_UseCookie || []).indexOf(this.store.getAppid()) > -1) {
                var e = a.getLoginStatus()
                  , n = a.getLoginStatusFromCookie() || {};
                if (!e.qq && n.qq) {
                    var t = this._getLoginStatusFromCookie();
                    if (t && t.qq)
                        return !0
                }
            }
            return !1
        }
        ,
        w.prototype.jumpToNewPage = function() {
            var e = this.store.getGlobalCoupon();
            e && e.getId() && this.store.doCouponRollback({
                "couponId": e.getId(),
                "rollbackFrom": "newPagePay"
            });
            var n = window.location.protocol + "//" + window.location.host + "/midas/minipay_v2/views/cpay/webpay-proxy.shtml" + window.location.search;
            n = i.fn.delParam(["cash_param", "disable_channel"], n),
            n = i.fn.addParam({
                "channel": this.channelObj.channel,
                "disable_channel": "wechat,qqwallet,pcbank,qqcard,mcard,hfpay,friendpay,mobile",
                "proxyBuyType": this.store.type,
                "canChangeCount": !1,
                "buy_quantity": this.info.count,
                "showRecommend": !1
            }, n),
            (y.GOODS === this.store.type && 1 == this.info.appmode || y.GAME === this.store.type) && (this.store.changePage("subChannel", o.mix({
                "channelObj": this.channelObj,
                "portal_serial_no": null,
                "mode": m.MODE.NEW_PAGE_PAY,
                "price": this.price,
                "coupon": this.coupon,
                "store": this.store
            }, {
                "uuid": this.uuid
            })),
            n = i.fn.addParam({
                "forceUUID": this.uuid
            }, n)),
            "1" != i.fn.getParam("inApp") ? i.openWindow(n) : (i.fn.delParam("inApp", n),
            s.openWindow(n))
        }
        ,
        w.prototype.init = function() {
            if (!(this.vm.disableSubmit || this.vm && this.vm.priceLoading)) {
                if (this.store.isInterfaceDisabled())
                    return void this.store.emit("channelDataChange", new p(b));
                var e = a.getLoginStatus();
                if (e.qq)
                    this.pay();
                else {
                    if (this.supportFetchLoginFromCookie())
                        return this._relogin = !0,
                        void this.pay();
                    a.canUsePTLoginCookie ? this.showLoginBox(this.pay.bind(this)) : this.jumpToNewPage()
                }
            }
        }
        ,
        w.prototype.showLoginBox = function(e) {
            var n = this;
            l.init(function() {
                l.setCallBack({
                    "onSuccess": function() {
                        n._relogin = !0,
                        n._getLoginStatusFromCookie(),
                        e.call(n)
                    }
                }),
                l.show()
            }
            .bind(this))
        }
        ,
        w.prototype.showPskeyLoginBox = function(e) {
            var n = this;
            l.init(function() {
                l.setCallBack({
                    "daid": 307,
                    "onSuccess": function() {
                        e.call(n)
                    }
                }),
                l.show()
            }
            .bind(this))
        }
        ,
        w.prototype.getCGI = function() {
            return this._subCGI ? this._subCGI : this.store.cgi
        }
        ,
        w.prototype.checkSurplus = function(e) {
            var n = this;
            n._relogin ? this.getQb({}, e) : (this.showSurplusRes({
                "balance": n._balance
            }),
            e && e())
        }
        ,
        w.prototype.getQb = function(e, n) {
            this.reportUser("surplus.click");
            var t = this.getCGI()
              , i = this
              , o = e || {};
            t.getQqacctYue(o, function(e) {
                n && n(),
                ~~e.ret ? (i.vm.balanceNotEnough = !0,
                i.vm.hideBalance = !0) : (i.vm.hideBalance = !1,
                i.handleSurplusRes(e))
            })
        }
        ,
        w.prototype.handleSurplusRes = function(e) {
            0 == e.ret && this.showSurplusRes({
                "uin": this._subSession ? this._subSession.openid : null,
                "show": !0,
                "balance": i.math.div(e.qb_balance + e.qd_balance, 100)
            })
        }
        ,
        w.prototype.showVerifyCode = function(e, n) {
            var t = this;
            new f({
                "el": document.getElementById("qb_left_money_container"),
                "verifyCodePic": e,
                "session": n,
                "onChangeVerifyCode": function(e) {
                    t.getCGI().getVerifyCode(function(n) {
                        0 == n.ret && e({
                            "verifySession": n.info.session,
                            "url": n.info.url
                        })
                    })
                },
                "onConfirm": function(e, n) {
                    t.getQb({
                        "code": e,
                        "session": n
                    })
                }
            })
        }
        ,
        w.prototype.showSurplusRes = function(e) {
            var n = a.getLoginStatus();
            (e.show || n.qq || 1 === this.info.wc_bind_qq && n.wechat) && (e.uin && (this.vm.uin = e.uin),
            e.balance >= parseFloat(this.vm.price) ? (this.vm.showBalance = !0,
            this.vm.balanceNotEnough = !1) : (this.vm.showBalance = !1,
            this.vm.balanceNotEnough = !0,
            this.vm.diff = Math.ceil(this.vm.price - e.balance),
            this.setAutoPay(!1)),
            this.vm.balance = e.balance,
            this.setAutoPaySelectUI())
        }
        ,
        w.prototype.pay = function(e) {
            if (!this.isLocked()) {
                this.lock(),
                e = e || {},
                this.reportUser("pay.click");
                var n = window.location.protocol + "//" + window.location.host + "/midas/minipay_v2/views/public/mb.shtml"
                  , t = this
                  , o = {
                    "mb_callback_url": encodeURIComponent(n),
                    "pay_method": this.channelObj.channel
                };
                i.fn.getParam("forceUUID") && (o.uuid = i.fn.getParam("forceUUID"),
                o.pushtype = "NodeJS"),
                i.fn.extend(o, e),
                h.show({
                    "opacity": .1
                }),
                this.vm.paying = !0,
                this.store.buy(o, function(e) {
                    return h.hide(),
                    t.vm.paying = !1,
                    t.handleRes(e, o)
                })
            }
        }
        ,
        w.prototype.handleRes = function(e, n) {
            var t, s = ~~e.ret, r = this, c = a.getLoginStatus();
            if (this.unlock(),
            0 !== s) {
                switch (s) {
                case 100004:
                    "subChannel" == r.store.currentPage() ? r.emit("pay:100004") : r.store.changePage("subChannel", o.mix({
                        "channelObj": r.channelObj,
                        "mode": m.MODE.COMPLETE,
                        "price": r._price,
                        "coupon": r.coupon,
                        "store": r.store
                    }, {})),
                    t = !0;
                    break;
                case 1004:
                    r.refreshDataBalance(),
                    t = !0;
                    break;
                case 1034:
                    r.refreshDataBalance(),
                    t = !0;
                    break;
                case 1018:
                    (c.qq1 || c.pskey) && (r.showPskeyLoginBox(function() {
                        window.location.href = i.fn.addParam({
                            "openid": +i.cookie.get("p_uin").replace(/[^\d]/g, ""),
                            "openkey": i.cookie.get("p_skey"),
                            "session_id": "uin",
                            "session_type": "pskey_307"
                        }, window.location.href)
                    }),
                    t = !0);
                    break;
                case 146:
                case 1905:
                    r.store.clearSubSession(),
                    r.showLoginBox(r.pay),
                    t = !0;
                    break;
                case 10001:
                    var c = a.getLoginStatus()
                      , l = a.getLoginStatusFromCookie() || {};
                    c.qq1 || l.qq ? r.securityQ(e, n) : r.showLoginBox(function() {
                        r.securityQ(e, n)
                    }),
                    t = !0;
                    break;
                case 2022:
                    t = !0;
                    var u = r.store.getCgi().sessionObj.getSessionParam()
                      , d = e.info;
                    new k({
                        "url": d.verify_url,
                        "fk_info": d.fk_info,
                        "fk_amt": d.fk_amt,
                        "jiazhang_url": d.jiazhang_url,
                        "veri_url": d.veri_url,
                        "qrcode_url": d.qrcode_url,
                        "cgi": r.store.getCgi(),
                        "accountType": "wc_actoken" === u.session_type ? "wx" : "qq",
                        "onLoad": function() {},
                        "onRcRestrict": function(e, n) {
                            e = e || {};
                            var t = a.getLoginStatusFromCookie();
                            r._relogin && t && i.fn.extend(e, {
                                "have_changed_uin": "1",
                                "pay_session_id": "uin",
                                "pay_session_type": "skey",
                                "pay_id": t.uin,
                                "auth_key": t.skey
                            }),
                            r.store.rcRestrict(e, n)
                        },
                        "onVerifyDone": function(e) {
                            e = e || {},
                            r.pay(e)
                        }
                    })
                }
                switch (String(e.err_code)) {
                case "1003--1-101":
                case "1003-1-101":
                    this.vm.paying = !0,
                    this.checkSurplus(function() {
                        r.vm.paying = !1
                    }),
                    t = !0
                }
            }
            return t
        }
        ,
        w.prototype.securityQ = function(e, n) {
            n = n || {};
            var t = e.info.mb_url;
            t += "",
            t = t.replace(/(.+)(\/\/)/, "$2");
            var o, s = this;
            g.create({
                "url": t,
                "size": {
                    "w": 400,
                    "h": 292
                },
                "hideHeader": !0,
                "onReady": function(e) {
                    o = e
                }
            }),
            window._MBQ_CALLBACK = function(e) {
                o.close();
                var t = i.fn.getParam("dna_result_key", e);
                t && (s.pay(i.fn.extend({}, n, {
                    "mb_pwd": t
                })),
                window._MBQ_CALLBACK = null)
            }
        }
        ,
        w.prototype.setAutoPay = function(e) {
            this.vm.autoPay = e,
            this.report("auto.click", {
                "action": this.vm.autoPay ? 1 : 0
            }),
            this.store.setAutoPay && this.store.setAutoPay(this.vm.autoPay)
        }
        ,
        w.prototype.initVmConfig = function() {
            var e = this
              , n = this.store.supportAutoPay(this.channelObj)
              , t = this.store.getAutoPay();
            this.vmConfig = i.fn.extend({
                "$id": "qb-controller",
                "needJumpToNewPage": !1,
                "price": this._price,
                "balanceNotEnough": !1,
                "hideBalance": !1,
                "showBalance": !1,
                "showAutoTips": n,
                "unitPrice": n ? this.store.getAutoUnit(this.channelObj) : 0,
                "unitName": _.channels[v.QBQD]["moneyname"] || "元",
                "autoPay": t,
                "balance": -1,
                "uin": null,
                "diff": "",
                "disableSubmit": !1,
                "paying": !1,
                "autoHandle": function() {
                    e.setAutoPay(!e.vm.autoPay)
                },
                "queryBalance": function() {
                    e.isQQLogin() ? e.checkSurplus() : e.showLoginBox(e.checkSurplus)
                },
                "handleClick": function(n) {
                    n.preventDefault(),
                    e.init()
                },
                "goCharge": function(n) {
                    n.preventDefault(),
                    e.goCharge()
                }
            }, this.getCouponVmConfig(), this.getTermsVmConfig(), this.getPubVmConfig());
            var o = a.getLoginStatus();
            return o.qq || a.canUsePTLoginCookie || (this.vmConfig.needJumpToNewPage = !0),
            this.vmConfig
        }
        ,
        w.prototype.goCharge = function(e) {
            this.reportUser("recharge.click");
            var n = {
                "balance": this._balance,
                "price": this._price
            }
              , t = Math.ceil(n.price - n.balance);
            this.vm.diff && (t = this.vm.diff);
            var o = {
                "appid": _.chargeQbAppid,
                "pf": this.store.params.pf,
                "pfkey": this.store.params.pfkey,
                "session_id": "uin",
                "session_type": "skey",
                "buy_quantity": t,
                "zoneid": this.store.params.zoneid,
                "sandbox": this.store.params.sandbox,
                "source_message": encodeURIComponent(this.store.getChargeMsg(t)),
                "source_from": this.store.type
            };
            this.store.getPayFor() != u.SELF && (o.recharge_other = 1,
            o.buy_quantity = Math.ceil(n.price)),
            this.store.params.skin && (o.skin = this.store.params.skin),
            this.store.params.cft_skin && (o.cft_skin = this.store.params.cft_skin),
            this.store.params.noKeyEvent && (o.noKeyEvent = this.store.params.noKeyEvent),
            this._subSession ? (o.openid = this._subSession.openid,
            o.openkey = this._subSession.openkey,
            o.session_id = this._subSession.sessionid,
            o.session_type = this._subSession.sessiontype) : (o.openid = this.store.session.openid,
            o.openkey = this.store.session.openkey,
            o.session_id = this.store.session.sessionid,
            o.session_type = this.store.session.sessiontype),
            o.buyType = "qb",
            i.fn.extend(o, e || {}),
            window.cashier && (window.cashier.newdialog(o),
            this._cashierEvent || (window.cashier.on("qbchargesuccess", this._qbChargeCallBack, this),
            window.cashier.on("qbchargeclose", this._qbChargeCallBack, this),
            window.cashier.on("qbchargeresize", this._qbChargeResize, this),
            this._cashierEvent = !0))
        }
        ,
        w.prototype._qbCookieRevert = function() {
            this.store.cgi.setLoginToCookie()
        }
        ,
        w.prototype.refreshDataBalance = function() {
            var e = a.getLoginStatus();
            e.qq ? this.store.queryBalance(function(e) {
                e ? (this._balance = e.balance,
                this.info.qqacct_balance = 100 * e.balance,
                this.store.emit("dataUpdate", "qqbalance", this.info.qqacct_balance),
                this.showSurplusRes({
                    "show": !0,
                    "balance": this._balance
                })) : window.location.reload()
            }
            .bind(this)) : this.checkSurplus(function() {})
        }
        ,
        w.prototype._qbChargeCallBack = function() {
            this._qbCookieRevert(),
            this.vm.showBalance = !1,
            this.vm.balanceNotEnough = !1,
            this.refreshDataBalance()
        }
        ,
        w.prototype._qbChargeResize = function(e) {
            s.resize(e)
        }
        ,
        w.prototype.initVm = function() {
            this.vm = o.define(this.initVmConfig())
        }
        ,
        w.prototype.onDestroy = function() {
            m.prototype.removeListener.call(this),
            window.cashier && (window.cashier.off("qbchargesuccess", this._qbChargeCallBack),
            window.cashier.off("qbchargeclose", this._qbChargeCallBack)),
            m.prototype.destroy.call(this)
        }
        ,
        w.create = function(e, n) {
            return new w(e,n)
        }
        ,
        w.getTemplate = function() {
            return d()
        }
        ,
        e.exports = w
    },
    "79488087": function(e, n, t) {
        var i = t(84912183)
          , o = t(4)
          , s = t(1)
          , a = t(100835382)
          , r = t(25)
          , c = t(11)
          , l = t(119561448)
          , u = t(83058212)
          , d = o.fn.getParam("sandbox")
          , p = (t(49140953),
        t(84811753))
          , h = t(75748174)
          , f = t(43847285)
          , m = t(117821206);
        t(68682076);
        var g = function(e, n, t) {
            a.apply(this, arguments),
            this.isBuying = !1,
            this.firstBuy = !0,
            this.saveTimout = null,
            this.validTimeout = null,
            this.init()
        }
          , v = {
            "init": function() {
                this.initVm(),
                this.calculatePrice(),
                this.fetchTargetUin(),
                this.fetchAmount();
                var e = this.store.getParams();
                if (this.isNativeWxpay = window._disableWechatNativePay.indexOf(e.appid) === -1,
                this.isDisable = this.store.isInterfaceDisabled(),
                this.hasLoaded = !1,
                !this.isDisable)
                    return 0 == this.amount ? (this.disableQrcode(),
                    this.vm.disableText = "请完善充值信息",
                    void (this.vm.showScaned = !1)) : void (this.saveTimout = new c.Timeout({
                        "time": .7,
                        "timeUp": function() {
                            this.saveTimout = null,
                            "function" == typeof this.buy && this.buy()
                        }
                        .bind(this)
                    }))
            },
            "calculatePrice": function() {
                var e = this.store.getPrice().price;
                this.price = this.store.getPrice(o.discount.checkHasDiscount(e, "wechat") ? this.channelObj.discount : void 0, this.coupon).price,
                this.vm.price = this.price
            },
            "fetchAmount": function() {
                this.amount = this.store.getAmount()
            },
            "fetchTargetUin": function() {
                this.targetUin = this.store.getTargetInfo().uin
            },
            "onChange": function() {
                return this.fetchTargetUin(),
                this.fetchAmount(),
                this.refreshCoupon(),
                this.calculatePrice(),
                this.saveTimout && this.saveTimout.stop(0),
                this.store.isInterfaceDisabled() ? (this.isDisable = !0,
                this.disableQrcode(),
                void (this.vm.disableText = this.store.getChannelDisableText())) : (this.enableQrcode(),
                this.isDisable && (this.isDisable = !1),
                0 == this.amount ? (this.disableQrcode(),
                this.vm.showScaned = !1,
                void (this.vm.disableText = "请完善充值信息")) : (this.vm.qrcodeLoading = !0,
                this.vm.qrcodeReload = !1,
                this.vm.showQrcode = !0,
                this.vm.showScaned = !1,
                void (this.saveTimout = new c.Timeout({
                    "time": .7,
                    "timeUp": function() {
                        this.saveTimout = null,
                        "function" == typeof this.buy && this.buy()
                    }
                    .bind(this)
                }))))
            },
            "disableQrcode": function() {
                this.vm && (this.vm.disableQrcode = !0)
            },
            "enableQrcode": function() {
                this.vm && (this.vm.disableQrcode = !1)
            },
            "getVmConfig": function() {
                var e = this;
                return o.fn.extend({
                    "$id": "wechat-controller",
                    "price": this.price,
                    "url": null,
                    "showScaned": !1,
                    "showQrcode": !0,
                    "isDialogCreated": !1,
                    "disableQrcode": this.store.isInterfaceDisabled(),
                    "disableText": this.store.getChannelDisableText() || "",
                    "gotonext": function() {},
                    "backQrcode": function() {
                        return e.vm.disableQrcode ? void e.store.emit("channelDataChange", new p(h)) : (e.vm.showQrcode = !0,
                        void (e.vm.showScaned = !1))
                    },
                    "qrcodeLoaded": function() {
                        l.hide(),
                        e.vm && (e.vm.qrcodeLoading = !1,
                        e.vm.qrcodeReload = !1)
                    },
                    "qrcodeLoadFail": function() {
                        if (l.hide(),
                        e.vm) {
                            e.vm.qrcodeLoading = !1,
                            e.vm.qrcodeReload = !0,
                            e.vm.url = "";
                            try {
                                var n = document.getElementById("qr-code-wx");
                                n && (n.innerHTML = "")
                            } catch (t) {}
                        }
                    },
                    "refreshQrcode": function() {
                        e.vm && (e.vm.qrcodeReload = !1,
                        e.vm.qrcodeLoading = !0,
                        e.buy())
                    },
                    "fail": function() {
                        e.vm.qrcodeLoaded(),
                        e.vm.url = ""
                    },
                    "qrcodeLoading": !0,
                    "qrcodeReload": !1
                }, this.getCouponVmConfig(), this.getTermsVmConfig(), this.getPubVmConfig())
            },
            "initVm": function() {
                this.vm = s.define(this.getVmConfig())
            },
            "getQrcode": function(e) {
                this.vm.qrcodeLoading = !0;
                var n = ""
                  , t = this.isNativeWxpay && e.sign
                  , i = this.store.isContinuousMonth() && e.wx_sign_url;
                if (this.store.continuousMonthNotSign(i),
                n = t ? e.sign : o.fn.addParam({
                    "t": e.time,
                    "n": e.nonce,
                    "a": e.appid,
                    "pf": this.store.getPf(),
                    "p": encodeURIComponent(e["package"]),
                    "s": e.sign_type || "SHA1",
                    "si": e.sign,
                    "su": e.wx_sign_url,
                    "showwxpaytitle": 1,
                    "uuid": this.uuid,
                    "scan": 1,
                    "env": 2 == d ? "dev" : 1 == d ? "sandbox" : "live"
                }, "https://pay.qq.com/h5/wechatPay.shtml?"),
                t) {
                    var s = this.genQrcode(n, {
                        "selector": "qr-code-wx",
                        "useBackend": !0,
                        "useOrig": !0
                    });
                    null !== s ? this.vm.url = s : this.vm.qrcodeLoaded()
                } else
                    this.getShortUrl(n, function(e) {
                        if (e && e.status) {
                            var n = this.genQrcode(e.shortUrl, {
                                "selector": "qr-code-wx",
                                "useBackend": !this.getFrontEndAppid()
                            });
                            this.validTimeout = setTimeout(function() {
                                try {
                                    this.vm.qrcodeLoadFail()
                                } catch (e) {}
                            }
                            .bind(this), 1e3 * e.validTime),
                            null !== n ? this.vm.url = n : this.vm.qrcodeLoaded()
                        } else
                            this.vm.qrcodeLoadFail()
                    }
                    .bind(this))
            },
            "buy": function(e, n) {
                if (e = e || {},
                clearTimeout(this.validTimeout),
                this.firstBuy = !1,
                0 != this.store.getAmount()) {
                    var t = {
                        "biz_appid": this.store.getWxAppid(),
                        "wx_direct_pay": this.isNativeWxpay ? 1 : 0,
                        "wx_publice_pay": 1,
                        "uuid": this.uuid,
                        "pay_method": this.channelObj.channel,
                        "pushtype": "NodeJS"
                    };
                    this.isNativeWxpay && (t.wx_order_interface = "1"),
                    this.store.isContinuousMonth() && (t.continuous_month = 1),
                    o.fn.extend(t, e),
                    l.show({
                        "opacity": "0"
                    }),
                    this.store.buy(t, function(e) {
                        this.hasLoaded = !0,
                        l.hide();
                        try {
                            return this.handlerBuy(e, t)
                        } catch (n) {
                            return !0
                        }
                    }
                    .bind(this))
                }
            },
            "handlerBuy": function(e, n) {
                var t, i = this;
                if (!~~e.ret)
                    return this.getQrcode(e.info.wechat_info || e.info.channel_info),
                    setTimeout(function() {
                        try {
                            this.setupPooling(e)
                        } catch (n) {}
                    }
                    .bind(this), 100),
                    !0;
                t = new m({
                    "errCode": e.ret,
                    "errMsg": e.msg,
                    "oriParams": n,
                    "2022": function() {
                        var n = e.info
                          , t = i.store.getCgi().sessionObj.getSessionParam();
                        new f({
                            "url": n.verify_url,
                            "fk_info": n.fk_info,
                            "fk_amt": n.fk_amt,
                            "jiazhang_url": n.jiazhang_url,
                            "veri_url": n.veri_url,
                            "qrcode_url": n.qrcode_url,
                            "cgi": i.store.getCgi(),
                            "accountType": "wc_actoken" === t.session_type ? "wx" : "qq",
                            "onLoad": function() {},
                            "onRcRestrict": function(e, n) {
                                e = e || {},
                                i.store.rcRestrict(e, n)
                            },
                            "onVerifyDone": function(e) {
                                e = e || {},
                                i.vm.qrcodeLoading = !0,
                                i.vm.qrcodeReload = !1,
                                i.buy(e)
                            },
                            "onDestroy": function() {}
                        })
                    }
                });
                try {
                    this.vm.qrcodeLoadFail()
                } catch (o) {}
                return !(!t || !t.canHandle()) && (t.exec(),
                !0)
            },
            "setupPooling": function(e) {
                var n, t = this;
                this.comet || (this.comet = new r({
                    "uuid": this.uuid,
                    "sandbox": ~~this.store.getSandbox(),
                    "sessionObj": this.store.getSession(),
                    "onSuccess": function() {
                        n && (n.destroy(),
                        n = null),
                        t.reportUser("push.success"),
                        t.store.onSuccess()
                    },
                    "onScan": function() {
                        t.reportUser("scan.pv"),
                        t.vm.showScaned = !0,
                        t.vm.showQrcode = !1,
                        t.store.isContinuousMonth() && e.info.channel_info.wx_sign_url && (t.vm.isDialogCreated || (t.vm.isDialogCreated = !0,
                        n = u.create({
                            "msg": "请在微信上完成开通",
                            "confirmBtnTxt": "已完成",
                            "cancelBtnTxt": "重新开通",
                            "onConfirm": function() {
                                t.reportUser("scan.confirm"),
                                t.store.onPending({
                                    "isQuery": !0,
                                    "titleTxt": "结果查询中",
                                    "billNo": e.info.channel_info && e.info.channel_info.serialno,
                                    "portalNo": e.info.portal_serial_no,
                                    "channel": t.store.channel
                                }),
                                n = null
                            },
                            "onCancel": function() {
                                t.reportUser("scan.cancel"),
                                t.vm.backQrcode(),
                                t.vm.isDialogCreated = !1,
                                n = null
                            }
                        })))
                    },
                    "onPaying": function() {}
                }),
                this.comet.start())
            },
            "onDestroy": function() {
                clearTimeout(this.validTimeout),
                a.prototype.removeListener.call(this),
                this.comet && this.comet.abort(),
                this.saveTimout && this.saveTimout.stop(0),
                a.prototype.destroy.call(this),
                this.vm = null,
                l.hide()
            }
        };
        o.inherits(g, a),
        o.fn.extend(g.prototype, v),
        g.create = function(e, n, t) {
            return new g(e,n,t)
        }
        ,
        g.getTemplate = function(e) {
            return i(e)
        }
        ,
        e.exports = g
    },
    "79775620": function(module, exports) {
        module.exports = function(obj) {
            function print() {
                __p += __j.call(arguments, "")
            }
            obj || (obj = {});
            var __t, __p = "", __j = Array.prototype.join;
            with (obj)
                __p += '<p class="tips">\n    ' + (null == (__t = name) ? "" : __t) + "\n        ",
                "undefined" != typeof noEm && noEm && (__p += "\n            " + (null == (__t = content) ? "" : __t) + "\n        "),
                __p += "\n            <span>\n        ",
                "undefined" != typeof noEm && noEm || (__p += '    \n                <em class="left-money-em">\n                    ' + (null == (__t = content) ? "" : __t) + "\n                </em>\n        "),
                __p += "\n        元\n    </span>\n</p>";
            return __p
        }
    },
    "80576922": function(e, n, t) {
        var i = t(4)
          , o = t(1)
          , s = t(49898765)
          , a = t(11)
          , r = {
            "PENDING": "waiting",
            "SUCCESS": "success",
            "FAIL": "fail",
            "ERROR": "error"
        };
        o.component("ms:resultquery", {
            "$template": s(),
            "$replace": !0,
            "status": r.PENDING,
            "info": "支付查询中，请稍后...",
            "subInfo": "",
            "extraInfo": {},
            "countDown": null,
            "timeUp": !1,
            "uuid": null,
            "times": 60,
            "queryTimeout": 10,
            "enableQuery": !1,
            "autoQuery": !0,
            "onInit": i.fn.emptyFunc,
            "onDestroy": i.fn.emptyFunc,
            "$init": function(e, n) {
                e.uuid = i.fn.uuid()
            },
            "$ready": function(e, n) {
                e.onInit(e),
                e.countDown = e.times,
                e.autoQuery && e.startAutoQuery()
            },
            "$skipArray": ["interval", "queryInterval", "extraInfo"],
            "onQuery": function(e, n) {},
            "querying": !1,
            "onSuccess": function(e) {},
            "onPending": function(e) {},
            "onFail": function(e) {},
            "onNoResult": function(e) {},
            "onError": function(e) {},
            "interval": null,
            "queryInterval": null,
            "enableConfirm": !1,
            "$dispose": function() {
                this.stopAutoQuery()
            },
            "stopAutoQuery": function() {
                this.interval && (this.interval.stop(1),
                this.interval = null)
            },
            "showNoResult": function() {
                this.enableConfirm = !0,
                this.confirm()
            },
            "startAutoQuery": function() {
                var e = this;
                this.interval = new a.CountDown({
                    "time": this.times,
                    "beforeCount": function() {
                        e.query()
                    },
                    "counting": function(n) {
                        e.countDown = n,
                        n <= 0 || n % e.queryTimeout == 0 && e.query()
                    },
                    "countEnd": function() {
                        e.timeUp = !0,
                        e.countDown = null,
                        e.stopAutoQuery(),
                        e.status == r.PENDING && e.showNoResult()
                    }
                })
            },
            "destroy": function() {
                this.$dispose()
            },
            "query": function() {
                this.querying || (this.querying = !0,
                this.onQuery(this))
            },
            "queryDone": function(e, n) {
                this.querying = !1,
                this.timeUp && !n || (this.status = e,
                e != r.PENDING && this.stopAutoQuery(),
                e == r.SUCCESS ? this.onSuccess(this) : e == r.PENDING ? this.onPending(this) : e == r.ERROR ? this.onError(this) : this.onFail(this))
            },
            "confirm": function() {
                this.onNoResult(this)
            },
            "setSubInfo": function(e) {
                this.subInfo = e
            },
            "setInfo": function(e) {
                this.info = e
            },
            "setExtraInfo": function(e, n) {
                this.extraInfo[e] = n
            },
            "getExtraInfo": function() {
                return this.extraInfo
            },
            "setStatus": function(e) {
                this.status = e
            },
            "getInfo": function() {
                return this.info
            },
            "getSubInfo": function() {
                return this.subInfo
            }
        }),
        e.exports = {
            "create": function(e, n) {
                return n = n || {},
                String.format('<ms:resultquery config="{config}" on-init="{onInit}" on-success="{onSuccess}" on-error="{onError}" on-fail="{onFail}" on-pending="{onPending}"></ms:resultquery>', {
                    "config": e || "resultQueryConfig",
                    "onInit": n.onInitMethodName,
                    "onSuccess": n.onSuccessMethodName,
                    "onError": n.onErrorMethodName,
                    "onFail": n.onFailMethodName,
                    "onPending": n.onPendingMethodName
                })
            },
            "ENUM_STATUS": r
        }
    },
    "80661677": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div ms-html="resultContent"></div>';
            return __p
        }
    },
    "81040968": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div class="bank-list">\n    <label class="bank-box" style="margin-right: 0" ms-class-1="checked:$index==index" ms-repeat="radioList" ms-if-loop="$index<9||showMoreBank" ms-attr-for="radioId"\n           ms-on-click="handleClick($index,$event)">\n        <input type="radio" class="o-radio" ms-attr-checked="$index==index">\n        <i class="icon-radio"></i>\n        <i ms-class="icon-bank icon-{{el.logo}}"></i>\n        {{el.name}}\n    </label>\n    <a class="more-bank" style="cursor: pointer" ms-if="!showMoreBank" ms-on-click="moreBank">更多银行</a>\n    <!--<a class="more-bank" style="cursor: pointer" ms-if="showMoreBank" ms-on-click="lessBank">收起</a>-->\n</div>';
            return __p
        }
    },
    "81089886": function(e, n, t) {
        var i = t(1)
          , o = function() {
            this._messageHandlers = []
        };
        o.prototype = {
            "postMessage": function(e, n) {
                if (window.debug && i.log("tenpay.xcross.send", e),
                window.postMessage)
                    try {
                        n.postMessage(e, "https://www.tenpay.com")
                    } catch (t) {
                        return !1
                    }
                else {
                    var o = navigator._tenpayCrossCall;
                    o && o(e)
                }
                return !0
            },
            "receiveMessage": function(e) {
                var n = new RegExp("^(http|https)://www.tenpay.com","i");
                if (window.postMessage) {
                    var t = function(t) {
                        n.test(t.origin) && (t = t || window.event,
                        window.debug && i.log("tenpay.xcross.receive", t.data),
                        e(t.data))
                    };
                    i.bind(window, "message", t),
                    this._messageHandlers.push(t)
                } else
                    navigator._payCrossCall = e
            },
            "deReceiveMessage": function() {
                window.postMessage ? (i.each(this._messageHandlers, function(e, n) {
                    i.unbind(window, "message", n)
                }),
                this._messageHandlers = []) : navigator._payCrossCall = i.noop
            }
        },
        e.exports = o
    },
    "82007299": function(e, n, t) {
        var i = t(102521382)
          , o = t(109735088)
          , s = t(4);
        t(51748615),
        t(49140953);
        e.exports = {
            "getPayUin": function() {
                return (this.subSession || this.session)["getSessionParam"]().openid
            },
            "getCache": function(e, n) {
                n = n || this.info;
                var t = n.__cacheData;
                return t ? t[e] : null
            },
            "setCache": function(e, n, t) {
                t = t || this.info;
                var i = t.__cacheData;
                i && (i[e] = n)
            },
            "getCode": function(e) {
                return e = e || this.info,
                e.offer_id
            },
            "getPriceType": function(e) {
                return e = e || this.info,
                e.priceType
            },
            "getName": function(e) {
                return e = e || this.info,
                e.product_name || e.name || e.offer_name || "包月"
            },
            "getUnitName": function(e) {
                return e = e || this.info,
                e.unitName
            },
            "getAmount": function(e) {
                return e = e || this.info,
                e.count
            },
            "getWXNick": function(e) {
                return this.wxNick
            },
            "showLoginBox": function(e) {
                var n = this;
                e = s.fn.extend({
                    "onClose": avalon.noop
                }, e || {}),
                e.isWechat && !this.currentLoginStatus().isQQUser || !o.canUsePTLoginCookie ? e.onClose.bind(n)(!0) : i.init(function() {
                    i.setCallBack({
                        "daid": 307,
                        "onSuccess": function() {
                            location.href = s.fn.addParam({
                                "openid": +s.cookie.get("p_uin").substr(1),
                                "openkey": s.cookie.get("p_skey"),
                                "session_id": "uin",
                                "session_type": "pskey_307"
                            }, location.href)
                        },
                        "onClose": function() {
                            e.onClose.call(n)
                        }
                    }),
                    i.show()
                })
            },
            "unLogin": function(e) {
                return ["2", "1018"].indexOf(String(e)) > -1
            },
            "currentLoginStatus": function() {
                var e = o.getLoginStatus();
                return {
                    "isWechatUser": e.wechat,
                    "isQQUser": e.qq,
                    "isPT": e.ptlogin,
                    "isPskey": e.pskey,
                    "isQQConnect": e.accesstoken,
                    "supportSend": e.accesstoken || e.qq1 || e.pskey
                }
            }
        }
    },
    "82760872": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div ms-controller="remitpay-controller">\n    <div ms-if="loading||priceLoading" id="_webpay__dialog__load__">\n        <div class="mdsweb-loading-wrapper abs">\n            <div class="mdsweb-loading">\n                <div class="dot"></div>\n                <div class="dot"></div>\n                <div class="dot"></div>\n            </div>\n        </div>\n    </div>\n    <div class="left-money-warn" ms-if="isDisable">\n        <p class="tips sub-tips"><i class="icon-error"></i> 温馨提示：{{disableText}}</p>\n    </div>\n    <iframe ms-if="!isDisable" frameborder="0" name="channelWebIframe" id="channelWebIframe" scrolling="no"\n        style="width: 100%; height: 380px;"></iframe>\n</div>';
            return __p
        }
    },
    "83058212": function(e, n, t) {
        var i = t(1)
          , o = t(99186575)
          , s = {};
        i.component("ms:confirm", {
            "$template": o(),
            "domId": "",
            "opacity": 0,
            "$replace": !0,
            "msg": "",
            "hideCancel": !1,
            "confirmBtnTxt": "确认",
            "cancelBtnTxt": "取消",
            "onConfirm": i.noop,
            "onCancel": i.noop,
            "handleConfirm": function() {
                this.remove(),
                this.onConfirm()
            },
            "remove": function() {
                s.hide();
                var e = document.getElementById(this.domId);
                document.body.removeChild(e)
            },
            "handleCancel": function() {
                this.remove(),
                this.onCancel()
            },
            "$init": function(e) {},
            "$ready": function(e) {
                s = function() {
                    var e = i(document.getElementById("_cp_confirm__mask__"));
                    return {
                        "show": function(n) {
                            e.css({
                                "opacity": n,
                                "display": "block"
                            })
                        },
                        "hide": function() {
                            e.css({
                                "display": "none"
                            })
                        }
                    }
                }(),
                s.show(e.opacity)
            },
            "$dispose": function() {}
        });
        var a = !1
          , r = []
          , c = function(e) {
            if (e = e || {},
            a)
                r.push(e);
            else {
                var n = function() {
                    a = !1,
                    r.length > 0 && c(r.shift())
                }
                  , t = "confirm-" + (2 * Math.random() + 10).toString().replace(".", "")
                  , o = function() {
                    try {
                        s.hide();
                        var e = document.getElementById(t);
                        delete i.vmodels[t],
                        e && e.parentNode && e.parentNode.removeChild(e)
                    } catch (n) {}
                };
                "function" == typeof e.onInit && e.onInit(o);
                var l = function() {
                    o(),
                    o = null,
                    n()
                }
                  , u = function() {
                    e.onConfirm && e.onConfirm(),
                    l()
                }
                  , d = function() {
                    e.onCancel && e.onCancel(),
                    l()
                }
                  , p = i.define({
                    "$id": t,
                    "config": {
                        "onConfirm": u,
                        "onCancel": d,
                        "domId": t,
                        "msg": e.msg,
                        "opacity": e.opacity || 0,
                        "hideCancel": e.hideCancel,
                        "confirmBtnTxt": e.confirmBtnTxt || "确认",
                        "cancelBtnTxt": e.cancelBtnTxt || "取消"
                    },
                    "destroy": l
                })
                  , h = document.createElement("div");
                h.setAttribute("ms-controller", t),
                h.setAttribute("id", t),
                h.innerHTML = '<ms:confirm config="config"></ms:confirm>',
                document.body.appendChild(h),
                i.scan(h),
                a = !0
            }
            return p
        };
        e.exports = {
            "create": c
        }
    },
    "83497919": function(e, n, t) {
        var i = t(4)
          , o = t(1)
          , s = t(74109955)
          , a = t(12)
          , r = t(104911180)
          , c = t(48016802)
          , l = t(99560243)
          , u = t(82007299)
          , d = 100
          , p = i.fn.getParams()
          , h = t(75685166)
          , f = t(102987497)
          , m = o.mix({}, u, {
            "getMonthAmount": function(e, n) {
                return Math.floor(e / (n == s.day ? 1 : n == s.year ? 372 : 31))
            },
            "getDaysAmount": function(e, n) {
                return Math.floor(e * (n == s.day ? 1 : n == s.year ? 372 : 31))
            },
            "convertToYuan": function(e, n) {
                return i.math.mul(parseInt(e, 10) / d, n || 1)
            },
            "getPrice": function(e, n) {
                return this.convertToYuan(n ? f.drmDiscount(n, e).price : e.currency_amt)
            },
            "getServiceInfo": function(e) {
                return e ? __Service[e.toLowerCase()] || {} : {}
            },
            "getAutoRenewPrice": function(e) {
                var n = null
                  , t = e["product_list"]
                  , i = this;
                return t.length > 0 && t.some(function(e) {
                    if (1 == i.getMonthAmount(e["auto_open_days"]) && (n = i.convertToYuan(e["auto_currency_amt"]),
                    n > 0))
                        return !0
                }),
                n
            },
            "getMonthDataInfo": function(e, n, t, r, c) {
                t = e.count || 1,
                n = n || s["open"];
                var l, u = this.getMonthPriceItemData(e, r, c);
                if (!u.length)
                    return a.go("result", {
                        "status": "error",
                        "modifyTitle": !1,
                        "displayInfo": "暂无可开通的月卡档位"
                    }),
                    {};
                var d = -1
                  , p = -1
                  , h = !1
                  , f = null;
                return o.each(u, function(e, i) {
                    i.type == s.upgrade && (h = !0),
                    i.type == n && (i.count == t ? p = e : i.editable ? d = e : p < 0 && (p = e,
                    f = i.count))
                }),
                p < 0 && d < 0 ? (l = u[0],
                l.type === s.continousMonth && (l = u[1]),
                t = l.count) : p > -1 && !f ? (l = u[p],
                t = l.count) : d > -1 ? (l = u[d],
                t = Math.min(Math.max(t, l.min), l.max)) : (l = u[p],
                t = l.count),
                {
                    "includeUpgrade": h,
                    "monthList": u,
                    "price": l.editable ? i.calcTotalPrice(t, l.unitPrice) : l.price,
                    "unitPrice": l.editable ? l.unitPrice : null,
                    "type": l.type,
                    "unitName": l.unitName,
                    "count": t,
                    "value": l.value,
                    "innerProductId": l.innerProductId,
                    "serviceCode": l.serviceCode,
                    "productName": l.productName,
                    "editable": l.editable
                }
            },
            "getMonthCardInfo": function(e) {
                var n = (e.product_list || []).filter(function(e) {
                    return "price_list" === e.price_flag && (e.product_id || "").indexOf("continuous_month_pid") === -1
                }).map(function(e) {
                    return {
                        "count": i.math.div(e.open_days, 31),
                        "price": i.math.div(e.currency_amt, 100)
                    }
                });
                return n
            },
            "getCustomMap": function(e) {
                var n = this.getCache("serviceCodeMap", e)
                  , t = this;
                if (!n) {
                    n = {
                        "services": {},
                        "customizable": !0
                    },
                    n.getBaseCode = function() {
                        if (this.customizable)
                            return null;
                        var e = null;
                        return o.each(this.services, function(n, t) {
                            if ("0" == t.level)
                                return e = n,
                                !1
                        }),
                        e
                    }
                    .bind(n),
                    n.getUpgradeCode = function() {
                        if (this.customizable)
                            return null;
                        var e = null;
                        return o.each(this.services, function(n, t) {
                            if ("1" == t.level)
                                return e = n,
                                !1
                        }),
                        e
                    }
                    .bind(n),
                    h.feature() && h.feature().setPackList && h.feature().setPackList(e);
                    var i = e["month_info"]["packet_list"];
                    if (i) {
                        var s = i.split(";");
                        o.each(s, function(e, i) {
                            i = i.split(","),
                            n["services"][i[0]] = {
                                "level": i[1],
                                "unitPrice": t.convertToYuan(i[2])
                            }
                        });
                        var a = null;
                        o.each(n["services"], function(e, t) {
                            if (a) {
                                if (a.level != t.level)
                                    return n["customizable"] = !1,
                                    !1
                            } else
                                a = t
                        })
                    }
                    this.setCache("serviceCodeMap", n, e)
                }
                return n
            },
            "getMaxUpdateCount": function(e) {
                return e["month_info"] ? e["month_info"]["upgrade_months"] : 0
            },
            "getMonthCardTipsDiscountTips": function(e, n, t, o, s) {
                var a = i.fn.safeGet(e, "mp_info.buymonth.monthutp")
                  , r = f.drmDiscount(a, t).extend.tag;
                if (r)
                    return r;
                if (n) {
                    var l = "1" == p["card_tips"]
                      , u = this.convertToYuan(n["currency_amt"], s) - this.convertToYuan(t["currency_amt"]);
                    return l && u > 0 ? String.format(c.get("monthCardTips"), {
                        "discountPrice": u,
                        "name": this.getName(e),
                        "count": s,
                        "opType": c.get("openTxt"),
                        "unitName": this.getUnitName(o)
                    }) : null
                }
                return null
            },
            "getOpendMonthList": function(e) {
                return e["month_list"] || []
            },
            "getOneMonthPrice": function(e) {
                for (var n = [], t = 0; t < e.length; t++) {
                    var i = e[t];
                    i.product_id.indexOf("_continuous_month_pid") == -1 && (i.price_flag == r.FIX && "31" == i.open_days ? n.push(parseInt(i.currency_amt)) : i.price_flag == r.UNFIX && "31" == i.open_days && n.push(parseInt(i.currency_amt)))
                }
                return n.sort(function(e, n) {
                    return e - n
                }),
                n[0]
            },
            "getMonthPriceItemData": function(e, n, t) {
                var a = i.fn.getParam("ignoreProductId").split(/\s*,\s*/).filter(Boolean);
                a.length > 0 && (e.product_list = e.product_list.filter(function(e) {
                    return !(e.price_flag === r.UNFIX && a.indexOf(e.product_id) > -1)
                })),
                e.product_list = e.product_list || [];
                var l = parseInt(i.fn.getParam("removeFixedRate"))
                  , u = 1 === e.product_list.length && e.product_list[0].price_type === r.FIX;
                l && !u && (e.product_list = e.product_list.filter(function(e) {
                    return e.price_flag !== r.FIX || (e.product_id || "").indexOf("continuous_month_pid") > -1
                }));
                var d = parseInt(i.fn.getParam("disableAutoAddList"))
                  , f = n
                  , m = this.getCache(f ? "sendPriceItems" : "priceItems", e);
                if (!m) {
                    h.feature() && h.feature().setMonthCards && h.feature().setMonthCards(e, n);
                    for (var g = this, v = p["price_style"], b = e["max_num"] || e.maxAmount || 9999, y = e.minAmount || 1, _ = [], k = {}, w = !0, C = String.format(c.get("yearTips"), {
                        "name": this.getName(e)
                    }), x = String.format(c.get("openYearTips"), {
                        "name": this.getName(e)
                    }), S = e["month_info"] && e["month_info"]["year_months"], T = !n && S && S > 0, I = e["product_list"], P = 1, L = 1, N = s.open, q = this.getName(e), E = "", B = e["recommend_list"].length > 0 ? e["recommend_list"].split(",") : [1, 3, 6, 12], D = !1, A = null, M = null, R = I.length - 1; R >= 0; --R) {
                        var O = I[R];
                        if (O.product_id.indexOf("_continuous_month_pid") > -1) {
                            var j = this.convertToYuan(O["currency_amt"]);
                            I[R].__type = s.continousMonth;
                            var U = {
                                "wechat": "微信支付",
                                "qqwallet": "QQ钱包"
                            }
                              , V = (e.continous_recommend_channel || []).map(function(e) {
                                return U[e]
                            }).join("、");
                            M = {
                                "style": v,
                                "type": s.continousMonth,
                                "name": "连续包月",
                                "productName": O["product_name"],
                                "innerProductId": O.inner_productid,
                                "count": 1,
                                "originName": "",
                                "originDays": "31",
                                "price": j,
                                "unitPrice": i.math.toDecimal(i.math.div(O["currency_amt"], 100), 2, !0),
                                "value": O["product_id"],
                                "editable": !1,
                                "tipsContent": String.format("连续包月仅支持{channel}，其他套餐支持更多渠道", {
                                    "channel": V
                                })
                            }
                        }
                    }
                    var Q = this.getCustomMap(e)
                      , F = this.getMaxUpdateCount(e)
                      , H = null;
                    if (1 != p["disable_upgrade"] && !Q.customizable && F > 0 && !f) {
                        var $, z = c.get("upgradeTxt") + this.getName(e), G = !1;
                        i.fn.each(I, function(e, n) {
                            if (e.__type != s.continousMonth)
                                return G = e["price_flag"] == r.FIX,
                                N = s.open,
                                P = g.getMonthAmount(e["open_days"], N),
                                0 != P && P == Math.floor(P) || (N = s.day),
                                N == s.open && 1 == P && G && ($ = e),
                                !G
                        });
                        var W = !1;
                        if (h.feature() && h.feature().canUpdate && (W = h.feature().canUpdate(e, n)),
                        G || W) {
                            var X, K;
                            o.each(Q["services"], function(n, t) {
                                1 == t.level && t.unitPrice > 0 && (N = s.upgrade,
                                P = 1,
                                X = g.getName(e),
                                K = g.getBaseName(e),
                                H = {
                                    "style": v,
                                    "type": N,
                                    "name": z,
                                    "productName": z,
                                    "count": P,
                                    "originName": z,
                                    "originDays": 31,
                                    "price": t.unitPrice,
                                    "serviceCode": $.inner_productid,
                                    "unitPrice": t.unitPrice,
                                    "unitName": g.getUnitName(s.open),
                                    "value": $["product_id"],
                                    "max": F,
                                    "min": e.minAmount || y,
                                    "tips": z,
                                    "tipsContent": F > 0 ? String.format("根据您的{baseServiceName}剩余有效期，最多可以升级<em> {upgradeMax} </em>个月的{serviceName}", {
                                        "baseServiceName": K,
                                        "serviceName": X,
                                        "upgradeMax": F
                                    }) : null,
                                    "editable": !0
                                })
                            })
                        }
                    }
                    var J = null
                      , Y = 0
                      , Z = 0
                      , ee = t - (H ? 1 : 0)
                      , ne = 0
                      , te = i.fn.safeGet(e, "mp_info.buymonth.monthutp");
                    I.sort(function(e, n) {
                        return e["price_flag"] != n["price_flag"] ? n["price_flag"] == r.FIX ? 1 : -1 : g.getMonthAmount(e["open_days"]) >= g.getMonthAmount(n["open_days"]) ? 1 : -1
                    });
                    var ie = []
                      , oe = 0;
                    o.each(I, function(n, t) {
                        if (t.__type != s.continousMonth) {
                            if (N = s.open,
                            w = t["price_flag"] == r.FIX,
                            P = oe = g.getMonthAmount(t["open_days"], N),
                            g.getDaysAmount(P, s.open) != t["open_days"] && (N = s.day,
                            P = g.getMonthAmount(t["open_days"], N)),
                            Z && g.getMonthAmount(Z["open_days"], N) == P) {
                                if (!w)
                                    return E = g.getUnitName(N),
                                    originalPrice = g.convertToYuan(t.currency_amt),
                                    Y = g.getPrice(t, te),
                                    void (k[P] = {
                                        "style": v,
                                        "type": N,
                                        "name": c.getPriceItemName(null, N),
                                        "productName": String.format("{0}{1}{2}", P, E, q),
                                        "count": P,
                                        "originName": "",
                                        "originDays": g.getMonthAmount(t["open_days"], s.day),
                                        "price": Y,
                                        "serviceCode": t.inner_productid,
                                        "unitPrice": i.math.toDecimal(i.math.div(Y, N == s.open ? P : P / 31), 2, !0),
                                        "unitName": E,
                                        "value": t["product_id"],
                                        "max": b,
                                        "min": y,
                                        "tips": T && P == S && t["price_flag"] != r.FIX ? 12 == S ? x : C : g.getMonthCardTipsDiscountTips(e, J, t, N, P),
                                        "editable": t["price_flag"] == r.FIX
                                    });
                                k[P] = _.pop()
                            }
                            return !(_.length >= ee) && void (N == s.open && 12 == P && w ? A = t : (N == s.open && 1 == P && w && (J = t,
                            ne = _.length),
                            originalPrice = g.convertToYuan(t.currency_amt),
                            Y = g.getPrice(t, te),
                            ie.push(oe),
                            E = g.getUnitName(N),
                            _.push({
                                "style": v,
                                "type": N,
                                "name": c.getPriceItemName(null, N),
                                "productName": String.format("{0}{1}{2}", P, E, q),
                                "count": P,
                                "originName": "",
                                "originDays": g.getMonthAmount(t["open_days"], s.day),
                                "price": Y,
                                "serviceCode": t.inner_productid,
                                "unitPrice": i.math.toDecimal(i.math.div(Y, N == s.open ? P : P / 31), 2, !0),
                                "unitName": E,
                                "value": t["product_id"],
                                "max": b,
                                "min": y,
                                "tips": T && P == S && t["price_flag"] != r.FIX ? 12 == S ? x : C : g.getMonthCardTipsDiscountTips(e, J, t, N, P),
                                "editable": t["price_flag"] == r.FIX
                            }),
                            D || (D = T && P == S),
                            Z = t))
                        }
                    }),
                    N = s.open;
                    var se = null;
                    T && J && !D && (B.some(function(e) {
                        if (P = parseInt(e, 10),
                        J && P == S)
                            return T = !1,
                            !1
                    }),
                    Y = g.convertToYuan(J["currency_amt"], S),
                    E = g.getUnitName(N),
                    se = {
                        "style": v,
                        "type": N,
                        "name": c.getPriceItemName(null, N),
                        "productName": String.format("{0}{1}{2}", S, E, q),
                        "count": S,
                        "originName": "",
                        "price": Y,
                        "serviceCode": J.inner_productid,
                        "unitPrice": g.convertToYuan(J["currency_amt"]),
                        "unitName": E,
                        "value": J["product_id"],
                        "max": S,
                        "min": y,
                        "tips": 12 == S ? x : C,
                        "editable": !1
                    });
                    var ae = t - (se ? 1 : 0) - (H ? 1 : 0) - (A ? 1 : 0) - (M ? 1 : 0) - _.length;
                    if (J && 1 == p["disable_open"] && ae++,
                    d && (ae = 0),
                    ae > 0 && J) {
                        var re = null
                          , ce = 1
                          , le = g.convertToYuan(J["currency_amt"]);
                        o.each(B, function(e, n) {
                            return 0 != ae && (ce = parseInt(n, 10),
                            void (ie.indexOf(ce) == -1 && (ae--,
                            re = String.format("{id}_{count}", {
                                "id": J["product_id"],
                                "count": ce
                            }),
                            E = g.getUnitName(N),
                            _.push({
                                "style": v,
                                "type": N,
                                "name": c.getPriceItemName(null, N),
                                "productName": String.format("{0}{1}{2}", ce, E, q),
                                "count": ce,
                                "originDays": g.getDaysAmount(ce, s.open),
                                "originName": "",
                                "price": g.convertToYuan(J["currency_amt"], ce),
                                "serviceCode": J.inner_productid,
                                "unitPrice": le,
                                "unitName": E,
                                "value": J["product_id"],
                                "max": b,
                                "min": y,
                                "tips": T && ce == S ? C : null,
                                "editable": !1
                            }))))
                        })
                    }
                    m = _.slice(0, t - (se ? 1 : 0) - (H ? 1 : 0) - (A ? 1 : 0) - (M ? 1 : 0)),
                    m.sort(function(e, n) {
                        return e.editable !== n.editable ? n.editable ? 1 : -1 : e.originDays >= n.originDays ? 1 : -1
                    }),
                    J && 1 == p["disable_open"] ? k[1] ? m.splice(ne, 1, k[1]) : m.splice(ne, 1) : J && m.push(m.splice(ne, 1)[0]),
                    se && m.unshift(se),
                    H && m.unshift(H),
                    M && m.unshift(M),
                    A && (N = s.year,
                    L = this.getMonthAmount(A["open_days"], N),
                    Y = this.convertToYuan(A["currency_amt"]),
                    E = this.getUnitName(N),
                    m.push({
                        "style": v,
                        "type": N,
                        "name": c.getPriceItemName(null, N),
                        "count": L,
                        "productName": String.format("{0}{1}{2}", L, E, q),
                        "originCount": this.getMonthAmount(A["open_days"]),
                        "originName": "",
                        "price": Y,
                        "serviceCode": A.inner_productid,
                        "unitPrice": i.math.toDecimal(i.math.div(Y, 12), 2, !0),
                        "unitName": E,
                        "value": A["product_id"],
                        "max": Math.floor(b / 12),
                        "min": y,
                        "tips": x || "",
                        "editable": A["price_flag"] == r.FIX
                    })),
                    this.setCache(f ? "sendPriceItems" : "priceItems", m, e)
                }
                var ue = parseInt(i.fn.getParam("ignoreFixedRate"))
                  , de = m.length
                  , pe = de && m[de - 1];
                return ue && pe.editable && pe.type === s.open && m.splice(m.length - 1, 1),
                m = m.filter(function(e) {
                    return e.price > 0
                })
            },
            "getUnitName": function(e) {
                return String.format(c.getPriceItemName(null, e), {
                    "count": ""
                })
            },
            "getServiceCode": function(e) {
                return e.month_info.service_code.toLowerCase()
            },
            "getBaseName": function(e) {
                var n = ""
                  , t = e.month_list;
                return baseCode = this.getCustomMap(e).getBaseCode(),
                baseCode && o.each(t, function(e, t) {
                    if (t.code.toLowerCase() == baseCode.toLowerCase())
                        return n = t.name,
                        !1
                }),
                n
            },
            "getDRMInfo": function(e) {
                var n, t = p.appid.split(","), e = e || t[0], i = p.groupid ? p.groupid.split(",") : [];
                return o.each(t, function(t, o) {
                    if (e == o)
                        return i.length > t && i[t] && (n = i[t]),
                        !1
                }),
                n
            },
            "getMpTxt": function(e) {
                return e.mp_info.info || ""
            },
            "isTYClub": function(e) {
                return ["txtypcby", "tyviptpwx"].indexOf(this.getServiceCode(e)) > -1
            },
            "isTYVIPClub": function(e) {
                return ["tyupvipqq", "tyupvipwx"].indexOf(this.getServiceCode(e)) > -1
            },
            "getMonthTabsData": function(e, n) {
                var t = []
                  , s = this
                  , a = null;
                return o.each(n, function(n, o) {
                    a = e[o],
                    a && t.push({
                        "name": s.getName(a),
                        "appid": o,
                        "serviceCode": s.getServiceCode(a),
                        "value": o,
                        "checked": !0,
                        "logo": i.universeProtocol(a.logo),
                        "ruleUrl": a.month_info.service_provision || l.ruleURL
                    })
                }),
                t
            }
        });
        e.exports = m
    },
    "84801805": function(e, n, t) {
        function i(e) {
            a.apply(this, arguments),
            this.initVm(),
            this.getInfo = function() {
                var e = r.getLoginStatus()
                  , n = {
                    "gameCurrencyName": this.orderInfo.product_name,
                    "count": this.orderInfo.count,
                    "account": e.wechat ? s.get("wechatNickName") : this.opt.provide_uin || ""
                };
                if (n.account) {
                    var t = c.getDisplayInfoByOpenid(n.account)
                      , i = t.nick;
                    n.account = "为" + t.uin + '(<span class="f_toe" title="' + i + '">' + i + "</span>)"
                }
                return " 成功" + n.account + "购买 " + ("false" === this.params.showCount ? "" : n.count) + n.gameCurrencyName
            }
            ,
            this.initialize()
        }
        var o = t(4)
          , s = t(19)
          , a = t(108898004)
          , r = t(109735088)
          , c = t(78805100);
        o.inherits(i, a),
        o.fn.extend(i.prototype, {
            "initialize": function() {
                this.vm.status === a.ENUM_STATUS.SUCCESS ? (this.vm.info = this.opt.displayInfo || this.getInfo(),
                this.vm.bottomText = '<div class="rational-tips" id="" style="bottom:20px"><p>适度娱乐 理性消费</p></div>') : this.vm.status !== a.ENUM_STATUS.FAIL && this.vm.status != a.ENUM_STATUS.ERROR || (this.vm.info = this.opt.displayInfo)
            },
            "onQueryNoResult": function(e) {
                this.setInfo(e)
            },
            "onQuerySuccess": function() {
                this.setSuccessInfo()
            },
            "onQueryFail": function(e, n) {
                this.setInfo(e),
                this.setSubInfo(n)
            },
            "onQueryError": function(e) {
                this.setInfo(e)
            },
            "setSuccessInfo": function() {
                this.setInfo(this.opt.displayInfo || this.getInfo())
            }
        }),
        e.exports = i
    },
    "84811753": function(e, n, t) {
        var i = t(4)
          , o = e.exports = function(e, n) {
            if (!e)
                throw Error("action must provide type");
            this.type = e,
            this.opts = n || {}
        }
        ;
        i.fn.extend(o.prototype, {
            "getType": function() {
                return this.type
            },
            "getData": function() {
                return this.opts
            }
        })
    },
    "84912183": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div ms-controller="wechat-controller">\n    <div class="coupon" ms-if="coupon" ms-html="couponHTML"></div>\n    <div class="qr-code-txt">\n        <i class="icon-wx"></i>微信扫码，支付\n        <em ms-if="!priceLoading">{{price}}</em>\n        <span ms-if="priceLoading" ms-html="priceLoadingTplHtml"></span>\n        元\n    </div>\n    <div class="qr-code-area" ms-visible="showQrcode">\n        <div class="qr-code-container wx" ms-visible="!disableQrcode">\n            <div id="qr-code-wx" style="display: none"></div>\n            <img ms-if="url" ms-attr-src="url" ms-on-load="qrcodeLoaded" ms-on-error="qrcodeLoadFail">\n            <div class="qr-code-mask" ms-if="qrcodeLoading||qrcodeReload||priceLoading"></div>\n            <div class="qr-code-loading" ms-if="qrcodeLoading||priceLoading">\n                <i></i>\n                <p>加载中，请稍后</p>\n            </div>\n            <div class="qr-code-reload" ms-if="qrcodeReload" ms-on-click="refreshQrcode">\n                <i></i>\n                <p>重新获取二维码</p>\n            </div>\n        </div>\n        <div class="qr-code-container wx" ms-visible="disableQrcode && !disableText"></div>\n    </div>\n    <div class="qr-code-area" ms-visible="showScaned">\n        <i class="icon-phone"></i>\n        <p>请在手机上进行支付</p>\n        <a href="javascript:void(0);" ms-on-click="backQrcode">返回二维码</a>\n    </div>\n    <div class="qr-code-area" ms-visible="disableQrcode && disableText">\n        <i class="icon-phone"></i>\n        <p>{{disableText}}</p>\n        <a href="javascript:void(0);" ms-on-click="backQrcode">刷新二维码</a>\n    </div>\n    <div class="qr-code-txt" ms-if="terms.length > 0" style="padding-top: 8px;">\n        <p class="tips sub-tips">支付前阅读并同意\n            <span ms-repeat="terms">\n                <a href="#" ms-click="openTerm(el,$event)">{{el.termName}}</a>\n            </span>\n        </p>\n    </div>\n</div>';
            return __p
        }
    },
    "86478814": function(e, n, t) {
        var i = t(4)
          , o = t(1)
          , s = {
            "getRoleListData": function(e) {
                var n = [];
                return e.forEach(function(e) {
                    n.push({
                        "name": decodeURIComponent(e.role_name),
                        "value": e.role_id
                    })
                }),
                n
            },
            "getZoneData": function(e) {
                var n = e[0]
                  , t = "opt_data_array"
                  , i = "t"
                  , o = "v"
                  , s = "t"
                  , a = "v";
                n && n.hasOwnProperty("sList") && (t = "sList",
                i = "name",
                o = "id",
                s = 0,
                a = 1);
                var r = n && n[t] && n[t].length > 0
                  , c = [];
                return e.forEach(function(e) {
                    c.push({
                        "value": e[o],
                        "name": e[i],
                        "status": e.status
                    })
                }),
                {
                    "data": c,
                    "hasServer": r
                }
            },
            "getServerData": function(e, n) {
                var t = e[0]
                  , i = "opt_data_array"
                  , o = "t"
                  , s = "v"
                  , a = "t"
                  , r = "v";
                t && t.hasOwnProperty("sList") && (i = "sList",
                o = "name",
                s = "id",
                a = 0,
                r = 1);
                var c = (t && t[i] && t[i].length > 0,
                []);
                return e.forEach(function(e) {
                    e[s] == n && e[i].forEach(function(e) {
                        c.push({
                            "value": e[r],
                            "name": e[a],
                            "status": e.status
                        })
                    })
                }),
                {
                    "data": c
                }
            },
            "getDefaultStep": function(e) {
                var n = ~~e.rate;
                return n
            },
            "getGamePriceListData": function(e, n, t) {
                var s = e.game_info || {}
                  , a = {
                    "0.01": [3e3, 5e3, 1e4],
                    "0.1": [100, 300, 1e3],
                    "1": [10, 100, 200],
                    "10": [1, 5, 20]
                }
                  , r = e.recommend_list.length > 0 ? JSON.parse(e.recommend_list) : a[l || "0.01"];
                r.sort(function(e, n) {
                    return e <= n ? -1 : 1
                });
                var c = Math.max(this.getDefaultStep(e), Math.min(r[0], n || 1))
                  , l = 1 / parseFloat(e.rate)
                  , u = {
                    "min": ~~s.min_num,
                    "max": ~~s.max_num,
                    "type": "default",
                    "rate": parseFloat(e.rate),
                    "logo": i.universeProtocol(e.logo || "//midas.gtimg.cn/h5pay/images/diamond.png"),
                    "unitName": s.unit_name || e.product_name,
                    "step": c
                }
                  , d = [];
                return o.each(r, function(e, n) {
                    d.push(o.mix({
                        "count": n
                    }, u))
                }),
                d.slice(0, t - 1),
                d.push(o.mix({
                    "count": e.count,
                    "editable": !0
                }, u)),
                {
                    "data": d,
                    "step": c,
                    "minCount": r[0]
                }
            },
            "getDefaultSelected": function(e, n) {
                if (!n)
                    return null;
                var t = {
                    "zone": {},
                    "server": {}
                }
                  , i = e[0]
                  , o = "opt_data_array"
                  , s = "t"
                  , a = "v"
                  , r = "t"
                  , c = "v";
                i && i.hasOwnProperty("sList") && (o = "sList",
                s = "name",
                a = "id",
                r = 0,
                c = 1);
                for (var l, u = i && i[o] && i[o].length > 0, d = !1, p = 0, h = e.length; !d && p < h; p++)
                    if (u) {
                        l = e[p][o];
                        for (var f = 0, m = l.length; f < m; f++)
                            if (l[f][a] == n) {
                                t.zone = {
                                    "value": e[p][a],
                                    "name": e[p][s],
                                    "index": p,
                                    "status": e[p]["status"]
                                },
                                t.server = {
                                    "value": l[f][a],
                                    "name": l[f][s],
                                    "index": f,
                                    "status": l[f]["status"]
                                },
                                d = !0;
                                break
                            }
                    } else
                        e[p][a] == n && (t.zone = {
                            "value": e[p][a],
                            "index": p,
                            "name": e[p][s],
                            "status": e[p]["status"]
                        },
                        d = !0);
                return t
            }
        };
        e.exports = s
    },
    "86576783": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div class="coupon vouchers">\n    <div ms-class-1="vouchers-choose-wrap" ms-class-2="voucher-span-center:center" ms-on-click="showCouponList(true)">\n        <span><i class="icon-coupon"></i></span>\n        <div id="coupon-selected" ms-class-1="vouchers-choosed:editableCoupon" style="display: inline-block;*display:inline;zoom: 1;">{{currentDesc}}<i class="icon-arrow"></i></div>\n    </div>\n</div>';
            return __p
        }
    },
    "87145282": function(e, n) {
        e.exports = "price-loading-end"
    },
    "87709802": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '    <div class="cp-header back-page" ms-on-click="back($event)">\n        <div class="header-icon-first" ms-if="showBack"><i class="icon-back"></i> <span ms-if="showBackText">返回上一步</span></div>\n    <h2 class="cp-header-title" ms-if="showHeaderBody">{{name}}</h2>\n</div>';
            return __p
        }
    },
    "87796589": function(e, n) {
        e.exports = {
            "SEND": "send",
            "SELF": "self"
        }
    },
    "87998867": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div style="padding:10px 0 30px 0;line-height: 1.6;position: relative;width: 100%;z-index: 1;text-align: center;"\n  class="bank-card-paying">\n  <div class="info-area" style="width: 550px; margin: 0 auto;">\n    <h2>\n      系统判断您当前账号可能是未成年人在使用，请配合完成人脸识别。\n      <span style=\'color: #fb8c3c;\'>未通过或拒绝验证</span>\n      ，该账号将被\n      <span style=\'color: #fb8c3c;\'>系统判定为未成年人使用，游戏将受到限制。\n      </span>\n    </h2>\n    <div ms-if="accountType == \'qq\'">\n      <div class="qr-code-txt">\n        <i class="icon-qq"></i>请使用手机QQ扫描二维码进行验证\n      </div>\n      <div\n        style="position: relative;margin: 5px auto 10px auto; width: 170px; height: 170px;border: 1px solid #e5e5e5; border-bottom-color: #3387ef;">\n        <img ms-if="url" width="150" height="150" style="margin: 9px;" ms-attr-src="url" alt="扫码进行人脸识别验证">\n        <div ms-if="!url">\n          <div class="qr-code-mask" style="height: 170px;"></div>\n          <div class="qr-code-loading" style="padding-top: 60px;">\n            <i></i>\n            <p>加载中，请稍后</p>\n          </div>\n        </div>\n      </div>\n    </div>\n    <div ms-if="accountType == \'wx\'">\n      <div class="qr-code-txt">\n        <i class="icon-wx"></i>请使用微信扫描二维码进行验证\n        <div\n          style="position: relative;margin: 5px auto 10px auto; width: 170px; height: 170px;border: 1px solid #e5e5e5; border-bottom-color: #00c800;">\n          <img ms-if="url" width="150" height="150" style="margin: 9px;" ms-attr-src="url" alt="扫码进行人脸识别验证">\n          <div ms-if="!url">\n            <div class="qr-code-mask" style="height: 170px;"></div>\n            <div class="qr-code-loading" style="padding-top: 60px;">\n              <i></i>\n              <p>加载中，请稍后</p>\n            </div>\n          </div>\n        </div>\n      </div>\n    </div>\n    <div class="btn-wrap">\n      <a type="button" class="btn btn-default" href="javascript:void(0)" ms-on-click="onConfirm">\n        <span>已完成验证</span>\n      </a>\n    </div>\n  </div>\n</div>';
            return __p
        }
    },
    "88037617": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div ms-css-width="width" ms-attr-id="autocompleteId">\n    <div class="form-group has-feedback" ms-click="focusEl(this,$event)">\n        <label for="inputgame">\n            <input ms-attr-id="inputId" class="form-input form-input--s" type="text" ms-on-keyup="keyup"  ms-on-blur="blur" ms-attr-value="inputName" />\n            <span ms-visible="showSpan" class="form-input__span" ms-attr-title="name">{{name}}</span>\n            <div><i class="icon-more-arrow"></i></div>\n        </label>\n    </div>\n    <div class="dropdown" ms-class-1="dropdown--multi-column:hasMutil" ms-visible="isShow"  ms-attr-id="dropdownId" ms-css-left="leftPosition" ms-on-mousedown="setHideAble(\'false\')"\n         ms-on-mouseleave="setHideAble(\'true\')">\n        <ul class="dropdown__list">\n            <li ms-if="showall?data.length==0:searchData.length==0">{{noDataMsg}}</li>\n            <li ms-repeat="showall?data:searchData" ms-on-click="select(el,$event)" ms-attr-title="el.name" ms-class="dropdown__item--active:el.name==value.name">{{el.name}}</li>\n        </ul>\n    </div>\n</div>\n\n';
            return __p
        }
    },
    "89481821": function(e, n, t) {
        var i = t(1)
          , o = t(86576783)
          , s = t(121800003)
          , a = t(10);
        document.body.appendChild(i.parseHTML(s()));
        var r = i.define({
            "$id": "couponlist",
            "defaultCoupon": -1,
            "active": !1,
            "bottom": "168px",
            "setPosition": function(e) {
                var n = document.getElementById("coupon-selected")
                  , t = i(n)
                  , o = document.documentElement.clientHeight - t.offset().top - t.height();
                r.bottom = e || o
            },
            "show": function(e) {
                a("couponlist.display", {
                    "action": e
                }),
                r.active = e
            },
            "handleClick": i.noop,
            "showCouponList": i.noop,
            "handleActive": i.noop,
            "handleNextPage": i.noop,
            "handlePrevPage": i.noop,
            "currentPage": 1,
            "totalPages": 1,
            "isLoading": !1,
            "couponList": [],
            "couponListInView": []
        });
        i.scan(null, r),
        i.component("ms:coupon", {
            "$skipArray": ["couponInfo", "oneCoupon", "selectCoupon", "couponList"],
            "$replace": !0,
            "listVm": null,
            "couponList": [],
            "currentDesc": "请选择抵扣券",
            "defaultCoupon": -1,
            "selectCoupon": {},
            "center": !1,
            "onInit": i.noop,
            "onSelect": i.noop,
            "onReady": i.noop,
            "onActiveCoupon": i.noop,
            "onFetchCoupon": i.noop,
            "onShowList": i.noop,
            "editableCoupon": !0,
            "currentPage": 1,
            "totalPages": 1,
            "oneCoupon": {},
            "$template": o(),
            "$init": function(e, n) {
                e._parseCouponList.call(e, e.couponList),
                e.onInit.call(e, e)
            },
            "_initCouponList": function() {
                r.handleActive = this._handleActive.bind(this),
                r.handleClick = this._handleClick.bind(this),
                r.showCouponList = this.showCouponList.bind(this),
                r.handleNextPage = this._handleNextPage.bind(this),
                r.handlePrevPage = this._handlePrevPage.bind(this)
            },
            "showCouponList": function(e, n) {
                if (n && n.stopPropagation(),
                !e && "mouseleave" === n.type) {
                    var t = i(document.getElementById("coupon-list-container")).innerHeight()
                      , o = i(document.getElementById("coupon-list-container")).innerWidth();
                    if (n.offsetX <= o && n.offsetY <= t)
                        return
                }
                this.editableCoupon && (r.show(e),
                e && r.setPosition(),
                this.onShowList(e))
            },
            "_handleClick": function(e, n) {
                n && n.stopPropagation();
                var t = !1;
                (e.without || e.isValid) && e.id != this.defaultCoupon && (this._setDesc(e),
                this._setDefaultCoupon(e.id),
                this.selectCoupon = e,
                this.onSelect(e),
                this.showCouponList(!1, n),
                t = !0),
                a("couponlist.click", {
                    "action": e.id,
                    "resultinfo": {
                        "succeed": t
                    }
                })
            },
            "_setDefaultCoupon": function(e) {
                this.defaultCoupon = e,
                r.defaultCoupon = e
            },
            "rebind": function(e) {
                this._setDefaultCoupon(-1),
                this._parseCouponList(e),
                this._setDesc()
            },
            "_setDesc": function() {
                var e = this.selectCoupon;
                this.currentDesc = e && e.id != -1 ? String.format("优惠券减{price}元", {
                    "price": e.amt
                }) : this.editableCoupon || !this.oneCoupon ? "请选择抵扣券" : String.format("满{leastPrice}元可抵扣{amt}元", this.oneCoupon)
            },
            "_parseCouponList": function(e) {
                var n = e.some(function(e, n) {
                    if (e.selected)
                        return this._setDefaultCoupon(e.id),
                        this.selectCoupon = e,
                        !0
                }
                .bind(this))
                  , t = {
                    "id": -1,
                    "without": !0,
                    "selected": !n
                };
                n || (this.selectCoupon = t),
                e.unshift(t),
                r.couponList = e;
                var i = 9
                  , o = (r.currentPage - 1) * i;
                r.couponListInView = e.slice(o, o + 9)
            },
            "_handleActive": function(e, n) {
                n && n.stopPropagation(),
                e.isLoading = !0,
                this.onActiveCoupon(e, function(n) {
                    e.isLoading = !1,
                    e.isFrozen = !n,
                    e.isValid = !e.expired && !e.isFrozen && !e.disable
                })
            },
            "_handleNextPage": function(e) {
                if (e && e.stopPropagation(),
                !r.isLoading && r.currentPage < r.totalPages) {
                    r.currentPage++;
                    var n = this.onNextPage.call(this, r.currentPage);
                    n && "function" == typeof n.then && (r.isLoading = !0,
                    n.then(function() {
                        r.isLoading = !1
                    })["catch"](function() {
                        r.isLoading = !1,
                        r.currentPage--
                    }))
                }
            },
            "_handlePrevPage": function(e) {
                if (e && e.stopPropagation(),
                !r.isLoading) {
                    r.currentPage > 1 && (r.currentPage--,
                    this.onPrevPage.call(this))
                }
            },
            "onReady": function(e, n) {
                r.totalPages = e.totalPages
            },
            "$ready": function(e, n) {
                this.onReady(e, n),
                this._initCouponList(),
                this._setDesc(this.selectCoupon)
            }
        }),
        e.exports = {
            "create": function(e) {
                return '<ms:coupon config="' + e + '" on-select="onSelect" on-init="onInit" on-ready="onReady"></ms:coupon>'
            }
        }
    },
    "89500152": function(e, n, t) {
        var i = (t(4),
        t(1))
          , o = t(73982165);
        i.component("ms:button", {
            "$template": o(),
            "$replace": !0,
            "text": "",
            "subText": "",
            "disabled": !1,
            "onClick": i.noop,
            "onMouseDown": i.noop,
            "onMouseUp": i.noop,
            "onMouseEnter": i.noop,
            "onMouseLeave": i.noop,
            "$init": function(e, n) {},
            "$ready": function(e) {
                e.onInit(e)
            },
            "$dispose": function(e) {},
            "onInit": i.noop,
            "handleClick": function() {
                this.disabled || this.onClick(this)
            },
            "handleMouseDown": function() {
                this.disabled || this.onMouseDown(this)
            },
            "handleMouseUp": function() {
                this.disabled || this.onMouseUp(this)
            },
            "handleMouseEnter": function() {
                this.disabled || this.onMouseEnter(this)
            },
            "handleMouseLeave": function() {
                this.disabled || this.onMouseLeave(this)
            },
            "disable": function() {
                this.disabled = !0
            },
            "enable": function() {
                this.disabled = !1
            }
        }),
        e.exports = {
            "create": function(e, n) {
                n = n || {};
                var t = String.format('<ms:button on-click="{onClickMethod}"on-mouse-down="{onMouseDownMethod}"on-mouse-up="{onMouseUpMethod}"on-mouse-enter="{onMouseEnterMethod}"on-mouse-leave="{onMouseLeaveMethod}"config="{config}"></ms:button>', {
                    "onClickMethod": n.onClickMethod || "onClick",
                    "onMouseUpMethod": n.onMouseUpMethod || "onMouseUp",
                    "onMouseDownMethod": n.onMouseDownMethod || "onMouseDown",
                    "onMouseEnterMethod": n.onMouseEnterMethod || "onMouseEnter",
                    "onMouseLeaveMethod": n.onMouseLeaveMethod || "onMouseLeave",
                    "config": e || "btnConfig"
                });
                return t
            }
        }
    },
    "89561790": function(e, n, t) {
        var i = t(54152206)
          , o = t(4)
          , s = t(1)
          , a = t(25)
          , r = t(100835382)
          , c = t(11)
          , l = t(119561448)
          , u = t(83058212)
          , d = o.fn.getParam("sandbox")
          , p = (t(49140953),
        t(112745811))
          , h = t(84811753)
          , f = t(75748174)
          , m = t(43847285)
          , g = t(117821206);
        t(68682076);
        var v = function(e, n, t) {
            r.apply(this, arguments),
            this.isQB = p.QB == this.store.type,
            this.saveTimout = null,
            this.validTimeout = null,
            this.init()
        }
          , b = {
            "init": function() {
                if (this.initVm(),
                this.calculatePrice(),
                this.fetchTargetUin(),
                this.fetchAmount(),
                this.isDisable = this.store.isInterfaceDisabled(),
                this.hasLoaded = !1,
                !this.isDisable)
                    return 0 == this.amount ? (this.disableQrcode(),
                    this.vm.disableText = "请完善充值信息",
                    void (this.vm.showScaned = !1)) : void (this.saveTimout = new c.Timeout({
                        "time": .7,
                        "timeUp": function() {
                            this.saveTimout = null,
                            "function" == typeof this.buy && this.buy()
                        }
                        .bind(this)
                    }))
            },
            "calculatePrice": function() {
                var e = this.store.getPrice().price;
                this.price = this.store.getPrice(o.discount.checkHasDiscount(e, "qqwallet") ? this.channelObj.discount : void 0, this.coupon).price,
                this.vm.price = this.price,
                this.isQB && (this.vm.savePrice = +o.math.sub(e, this.price))
            },
            "isAmountChange": function() {
                return this.lastAmount != this.amount
            },
            "fetchAmount": function() {
                this.amount = this.vm.amount = this.store.getAmount()
            },
            "fetchTargetUin": function() {
                this.targetUin = this.store.getTargetInfo().uin
            },
            "disableQrcode": function() {
                this.vm && (this.vm.disableQrcode = !0)
            },
            "enableQrcode": function() {
                this.vm && (this.vm.disableQrcode = !1)
            },
            "getVmConfig": function() {
                var e = this;
                return o.fn.extend({
                    "$id": "qqwallet-controller",
                    "price": this.price,
                    "url": null,
                    "amount": this.amount,
                    "tips": "",
                    "showScaned": !1,
                    "showQrcode": !0,
                    "isDialogCreated": !1,
                    "savePrice": 0,
                    "isQB": this.isQB,
                    "disableQrcode": this.store.isInterfaceDisabled(),
                    "disableText": this.store.getChannelDisableText() || "",
                    "qrcodeLoaded": function() {
                        l.hide(),
                        e.vm && (e.vm.qrcodeLoading = !1,
                        e.vm.qrcodeReload = !1)
                    },
                    "backQrcode": function() {
                        return e.vm.disableQrcode ? void e.store.emit("channelDataChange", new h(f)) : (e.vm.showScaned = !1,
                        void (e.vm.showQrcode = !0))
                    },
                    "qrcodeLoadFail": function() {
                        if (l.hide(),
                        e.vm) {
                            e.vm.qrcodeLoading = !1,
                            e.vm.qrcodeReload = !0,
                            e.vm.url = "";
                            try {
                                var n = document.getElementById("qr-code-qqwallet");
                                n && (n.innerHTML = "")
                            } catch (t) {}
                        }
                    },
                    "refreshQrcode": function() {
                        e.vm && (e.vm.qrcodeReload = !1,
                        e.vm.qrcodeLoading = !0,
                        e.buy())
                    },
                    "qrcodeLoading": !0,
                    "qrcodeReload": !1
                }, this.getCouponVmConfig(), this.getTermsVmConfig(), this.getPubVmConfig())
            },
            "initVm": function() {
                this.vm = s.define(this.getVmConfig())
            },
            "onChange": function() {
                return this.refreshCoupon(),
                this.fetchTargetUin(),
                this.fetchAmount(),
                this.calculatePrice(),
                this.saveTimout && this.saveTimout.stop(0),
                this.store.isInterfaceDisabled() ? (this.isDisable = !0,
                this.disableQrcode(),
                void (this.vm.disableText = this.store.getChannelDisableText())) : (this.enableQrcode(),
                this.isDisable && (this.isDisable = !1),
                0 == this.amount ? (this.disableQrcode(),
                this.vm.showScaned = !1,
                void (this.vm.disableText = "请完善充值信息")) : (this.enableQrcode(),
                this.vm.qrcodeLoading = !0,
                this.vm.qrcodeReload = !1,
                this.vm.showQrcode = !0,
                this.vm.showScaned = !1,
                void (this.saveTimout = new c.Timeout({
                    "time": .7,
                    "timeUp": function() {
                        this.saveTimout = null,
                        "function" == typeof this.buy && this.buy()
                    }
                    .bind(this)
                }))))
            },
            "getQrcode": function(e) {
                this.vm.qrcodeLoading = !0;
                var n = this.store.isContinuousMonth() && e.qq_sign_url;
                this.store.continuousMonthNotSign(n);
                var t = n ? o.fn.addParam({
                    "_wv": 1027,
                    "pf": this.store.getPf(),
                    "usr": this.store.getCgi().sessionObj.openid,
                    "env": 2 == d ? "dev" : 1 == d ? "sandbox" : "live",
                    "uuid": this.uuid,
                    "id": this.store.getAppid(),
                    "scan": 1,
                    "su": e.qq_sign_url
                }, "https://pay.qq.com/h5/mqqPay.shtml?") : o.fn.addParam({
                    "_wv": 1027,
                    "app_jump": 1,
                    "t": e["token"]
                }, "https://myun.tenpay.com/mqq/pay/index.shtml");
                this.getShortUrl(t, function(e) {
                    if (e && e.status) {
                        var n = this.genQrcode(e.shortUrl, {
                            "selector": "qr-code-qqwallet",
                            "useBackend": !this.getFrontEndAppid()
                        });
                        this.validTimeout = setTimeout(function() {
                            try {
                                this.vm.qrcodeLoadFail()
                            } catch (e) {}
                        }
                        .bind(this), 1e3 * e.validTime),
                        null !== n ? this.vm.url = n : this.vm.qrcodeLoaded()
                    } else
                        this.vm.qrcodeLoadFail()
                }
                .bind(this))
            },
            "buy": function(e) {
                if (e = e || {},
                clearTimeout(this.validTimeout),
                0 != this.store.getAmount()) {
                    var n = {
                        "cft_type": "tokenid",
                        "uuid": this.uuid,
                        "pushtype": "NodeJS",
                        "pay_method": "qqwallet:2"
                    };
                    this.store.params.recharge_other && (n.qbqd_not_discount = 1),
                    this.store.isContinuousMonth() && (n.continuous_month = 1),
                    o.fn.extend(n, e),
                    l.show({
                        "opacity": "0"
                    }),
                    this.store.buy(n, function(e) {
                        this.hasLoaded = !0,
                        l.hide();
                        try {
                            return this.handlerBuy(e, n)
                        } catch (t) {
                            return !0
                        }
                    }
                    .bind(this))
                }
            },
            "handlerBuy": function(e, n) {
                var t, i = this;
                if (!~~e.ret)
                    return this.getQrcode(e.info.qqwallet_info || e.info.channel_info),
                    setTimeout(function() {
                        try {
                            this.setupPooling(e)
                        } catch (n) {}
                    }
                    .bind(this), 100),
                    !0;
                t = new g({
                    "errCode": e.ret,
                    "errMsg": e.msg,
                    "oriParams": n,
                    "2022": function() {
                        var n = i.store.getCgi().sessionObj.getSessionParam()
                          , t = e.info;
                        new m({
                            "url": t.verify_url,
                            "fk_info": t.fk_info,
                            "fk_amt": t.fk_amt,
                            "jiazhang_url": t.jiazhang_url,
                            "veri_url": t.veri_url,
                            "qrcode_url": t.qrcode_url,
                            "cgi": i.store.getCgi(),
                            "accountType": "wc_actoken" === n.session_type ? "wx" : "qq",
                            "onLoad": function() {},
                            "onRcRestrict": function(e, n) {
                                e = e || {},
                                i.store.rcRestrict(e, n)
                            },
                            "onVerifyDone": function(e) {
                                e = e || {},
                                i.vm.qrcodeLoading = !0,
                                i.vm.qrcodeReload = !1,
                                i.buy(e)
                            }
                        })
                    }
                });
                try {
                    this.vm.qrcodeLoadFail()
                } catch (o) {}
                return !(!t || !t.canHandle()) && (t.exec(),
                !0)
            },
            "setupPooling": function(e) {
                var n, t = this;
                this.comet || (this.comet = new a({
                    "uuid": this.uuid,
                    "sandbox": ~~this.store.getSandbox(),
                    "sessionObj": this.store.getSession(),
                    "onSuccess": function() {
                        n && (n.destroy(),
                        n = null),
                        t.reportUser("push.success"),
                        t.store.onSuccess()
                    },
                    "onScan": function() {
                        t.reportUser("scan.pv"),
                        t.vm.showScaned = !0,
                        t.vm.showQrcode = !1,
                        t.store.isContinuousMonth() && e.info.channel_info.qq_sign_url && (t.vm.isDialogCreated || (t.vm.isDialogCreated = !0,
                        n = u.create({
                            "msg": "请在手机QQ上完成开通",
                            "confirmBtnTxt": "已完成",
                            "cancelBtnTxt": "重新开通",
                            "onConfirm": function() {
                                t.reportUser("scan.confirm"),
                                t.store.onPending({
                                    "isQuery": !0,
                                    "titleTxt": "结果查询中",
                                    "billNo": e.info.channel_info && e.info.channel_info.serialno,
                                    "portalNo": e.info.portal_serial_no,
                                    "channel": t.store.channel
                                }),
                                n = null
                            },
                            "onCancel": function() {
                                t.reportUser("scan.cancel"),
                                t.vm.backQrcode(),
                                t.vm.isDialogCreated = !1,
                                n = null
                            }
                        })))
                    },
                    "onPaying": function() {}
                }),
                this.comet.start())
            },
            "onDestroy": function() {
                clearTimeout(this.validTimeout),
                r.prototype.removeListener.call(this),
                this.comet && this.comet.abort(),
                this.saveTimout && this.saveTimout.stop(0),
                clearTimeout(this.timeOut),
                r.prototype.destroy.call(this),
                l.hide()
            }
        };
        o.inherits(v, r),
        o.fn.extend(v.prototype, b),
        v.create = function(e, n, t) {
            return new v(e,n,t)
        }
        ,
        v.getTemplate = function(e) {
            return i(e)
        }
        ,
        e.exports = v
    },
    "90737419": function(e, n, t) {
        var i = (t(4),
        t(1))
          , o = t(75217507)
          , s = t(87709802);
        i.component("ms:header", {
            "$template": o(),
            "$$template": function(e) {
                return "month" == e ? o() : s()
            },
            "$skipArray": ["logo", "alt", "name", "showHeaderBody", "showBack", "showClose"],
            "$replace": !0,
            "logo": null,
            "alt": null,
            "name": null,
            "checked": !0,
            "showHeaderBody": !0,
            "showBack": !0,
            "showClose": !0,
            "onAgreeRule": i.noop,
            "onClose": i.noop,
            "onBack": i.noop,
            "onClickService": i.noop,
            "$ready": function(e) {
                i.log("ready")
            },
            "handleClickRuler": function(e) {
                e.stopPropagation(),
                this.checked = !this.checked,
                this.onAgreeRule(this.checked)
            },
            "handleClickService": function(e, n) {
                e.stopPropagation(),
                this.onClickService()
            },
            "agreeRule": function() {
                this.onAgreeRule(this.checked)
            },
            "close": function() {
                this.onClose()
            },
            "back": function() {
                this.onBack()
            }
        }),
        e.exports = {
            "create": function(e, n) {
                return n = n,
                String.format('<ms:header config="{dataName}" on-close="{onClose}" on-back="{onBack}" on-agree-rule="{onAgreeRule}" on-click-service="{onClickService}"></ms:header>', {
                    "dataName": e,
                    "onAgreeRule": n.onAgreeRule,
                    "onClickService": n.onClickService,
                    "onClose": n.onClose,
                    "onBack": n.onBack
                })
            }
        }
    },
    "97501907": function(e, n, t) {
        var i = t(4)
          , o = t(1)
          , s = t(115878448);
        o.component("ms:radiogroup", {
            "$template": s(),
            "radioList": [],
            "$replace": !0,
            "radioId": "",
            "index": null,
            "onChange": o.noop,
            "$init": function(e, n) {
                e.radioId = i.fn.uuid(),
                e.$watch("index", function(n) {
                    e.onChange(e.radioList[e.index], e.index)
                })
            },
            "fireOninit": function() {
                var e = this;
                null !== e.index && "undefined" != typeof e.index && "" !== e.index && e.onChange(e.radioList[e.index], e.index)
            },
            "handleClick": function(e, n) {
                n.stopPropagation(),
                this.index == e && this.onChange(this.radioList[this.index], this.index),
                this.index = e
            },
            "$dispose": function(e) {
                e.$unwatch()
            },
            "getChecked": function() {
                return this.radioList[this.index]
            }
        }),
        e.exports = {
            "create": function(e, n) {
                return n = n || {},
                String.format('<ms:radiogroup config="{config}" on-change="{onChange}"></ms:radiogroup>', {
                    "config": e || "radioGroupConfig",
                    "onChange": n.onChangeMethod || "onChange"
                })
            }
        }
    },
    "98010485": function(e, n, t) {
        var i = t(47721167)
          , o = function(e, n, t, o) {
            var s = {};
            return o && "credit" != o || !t["credit"] || !t["credit"]["bank"] || t["credit"]["bank"] != e ? o && "debit" != o || !t["debit"] || !t["debit"]["bank"] || t["debit"]["bank"] != e || (s.bankName = t.name,
            s.cardTypeName = i.CardTypeDesc["debit"],
            s.bank = n,
            s.curCardType = "debit",
            s.curPayType = "bank") : (s.bankName = t.name,
            s.cardTypeName = i.CardTypeDesc["credit"],
            s.bank = n,
            s.curCardType = "credit",
            s.curPayType = "bank"),
            s
        };
        e.exports = function(e, n) {
            var t = {};
            t = e && 1 == e.split("_")[2] ? window.__B2B_BANK_CONFIG : window.__BANK_CONFIG;
            var s = {};
            return t && e ? (avalon.each(t, function(t, i) {
                return s = o(e, t, i, n),
                !s.bank
            }),
            e && 1 == e.split("_")[2] ? (s.bankTypeName = i.BankTypeDesc["B2B"],
            s.curBankType = i.BankType["B2B"]) : (s.bankTypeName = i.BankTypeDesc["B2C"],
            s.curBankType = i.BankType["B2C"]),
            s) : s
        }
    },
    "99039043": function(e, n, t) {
        t(57188951);
        var i = t(1)
          , o = t(4)
          , s = t(12)
          , a = t(107544357)
          , r = t(10)
          , c = t(109735088)
          , l = r.Performance
          , u = t(17)
          , d = t(76686721)("animation")
          , p = t(72876602)
          , h = t(76511707)
          , f = t(18)
          , m = o.fn.getParam("source_from")
          , g = t(19)
          , v = t(112745811)
          , b = t(109807897)
          , y = t(49140953);
        r("pv", m ? {
            "resultinfo": {
                "source": m
            }
        } : {}),
        r.user.action("page", "order", m ? {
            "source": m
        } : {}),
        l.userTrace("timer.js.exec", {
            "startTime": __startTime
        }),
        t(20),
        t(3);
        var _ = function() {
            this._handlers = {},
            this.vm = null,
            this.currentPage = "order",
            this.orderHeight = 173,
            this.skin = o.fn.getParam("skin"),
            this.fakeSubChannel = !1,
            this.from = m;
            var e = o.fn.getParam("resultAction");
            this.showInnerHeader = "1" === o.fn.getParam("show_header"),
            this.actionType = !this.showInnerHeader || "back" != e && "refresh" != e ? "" : "refresh"
        };
        o.fn.each(f, function(e, n) {
            "function" == typeof e && (_.prototype[n] = e)
        }),
        o.fn.extend(_.prototype, {
            "constructor": _,
            "back": function() {
                this.vm && "order" == this.vm.currentComponent && !this.fakeSubChannel ? u.notify("close") : s.back()
            },
            "go": function(e, n) {
                s.go(e, n)
            },
            "render": function() {
                this.vm = i.define(this.loadVMConfig())
            },
            "run": function(e, n) {
                var t = this.vm
                  , i = this;
                u.register("close", function() {
                    r.user.action("close", "close.click", p.toJSON())
                }, this),
                u.register("goback", function() {
                    "order" != t.currentComponent || i.fakeSubChannel ? i.back() : u.notify("close")
                }),
                c.checkLoginInUrl(function(t) {
                    if (t && t.errorLoginParams) {
                        var o = {
                            "displayInfo": y.TEXT.INVALIDLOGIN,
                            "status": "error",
                            "cgi": {},
                            "session": {},
                            "modifyTitle": !1,
                            "actionType": this.actionType,
                            "buttonTxt": "确定",
                            "res": {
                                "ret": 1018,
                                "msg": "登录校验失败",
                                "err_code": ""
                            }
                        };
                        i.go("result", o)
                    } else
                        i.go(e || "order", n)
                }),
                l.reportPerformance(),
                document.body.setAttribute("inited", "1"),
                this.reportAdBlock(),
                this.loadXMidas(),
                [v.GAME, v.GOODS, v.MONTH].indexOf(g.get("type")) !== -1 && b.keplerPredict(!0),
                "string" == typeof window._checkCompatibleRes && window._checkCompatibleRes && r("checkCompatibleRes", {
                    "resultinfo": {
                        "info": window._checkCompatibleRes
                    }
                })
            },
            "reportAdBlock": function() {
                var e = "";
                "adguardButton"in window && (e = "adguardAPP"),
                e && r("req.block.risk", {
                    "resultinfo": {
                        "name": e
                    }
                })
            },
            "loadXMidas": function() {
                var e = document.getElementById("xMidasToken").value;
                if (!e)
                    return r("xmidas.no.token");
                try {
                    a.initXMidas()
                } catch (n) {
                    console.error(n)
                }
            },
            "showBackBtn": function(e) {
                u.notify(e ? "showBackBtn" : "hideBackBtn"),
                this.showInnerHeader && this.trigger("InnerHeader", {
                    "page": this.currentPage,
                    "isShow": e
                })
            },
            "changePage": function(e, n) {
                var t = this.vm
                  , i = this
                  , o = t.currentComponent;
                d.add(function(s) {
                    var a = function() {
                        n && n(),
                        s && s()
                    };
                    h(o, e, t, {
                        "h0": i.orderHeight,
                        "h1": 90
                    }, a)
                }),
                d.run()
            },
            "loadVMConfig": function() {
                return {
                    "$id": "app",
                    "$skipArray": ["currentComponent", "fakeSubChannel"],
                    "currentComponent": null
                }
            }
        }),
        _.loadVM = function(e, n, t) {
            try {
                n ? e.onResult && e.onResult(t) : e.onInit && e.onInit(t)
            } catch (i) {}
        }
        ,
        e.exports = _
    },
    "99186575": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div>\n    <div style="position:absolute;top:50%;left:50%;z-index:9999;margin-left:-240px;margin-top:-80px;width:480px;" class="bank-card-paying">\n        <p ms-html="msg"></p>\n        <div class="btn-wrap">\n            <button type="button" ms-visible="!hideCancel" class="btn btn-primary" ms-on-click="handleCancel">{{cancelBtnTxt}}</button>\n            <button type="button" class="btn btn-default" ms-on-click="handleConfirm">{{confirmBtnTxt}}</button>\n        </div>\n    </div>\n    <div id="_cp_confirm__mask__" style="width: 100%; height: 100%; position: absolute; top: 0px; left: 0px; z-index: 5; opacity: 0; display: none;zoom: 1; *zoom:1;filter: alpha(opacity=0)"></div>\n</div>\n';
            return __p
        }
    },
    "99560243": function(e, n, t) {
        var i = t(72074753);
        e.exports = {
            "qbCount": 60,
            "monthCount": 1,
            "MaxViewSerivce": 2,
            "canAutoPayChannels": [i.QBQD, i.QDQB, i.KJ],
            "qbDiscountChannels": [i.KJ, i.QQWALLET],
            "qbLogo": "//midas.gtimg.cn/midas/images/logo/qb/90.png",
            "monthLogo": "//midas.gtimg.cn/h5pay/images/ico-month.png",
            "ruleURL": "//www.qq.com/contract.shtml"
        }
    },
    "100216969": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div style="padding:10px 0 30px 0;line-height: 1.6;position: relative;width: 100%;z-index: 1;text-align: center;" class="bank-card-paying">\n  <div class="info-area" style="width: 550px; margin: 0 auto;">\n    <h2 style="text-align: left;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;检测到你的<span style="padding: 0 .05rem;color: #47d998;">认证信息不全</span>，为满足法律法规和主管部门要求，保护您的合法权益，我们需要获取您的姓名和身份信息进行实名认证。在您认证通过前，将可能影响应用充值，请尽快完善信息。</h2>\n    <div ms-if="accountType == \'qq\'">\n      <div class="qr-code-txt">\n        <i class="icon-qq"></i>请使用手机QQ扫描二维码进行验证\n      </div>\n      <div style="position: relative;margin: 5px auto 10px auto; width: 170px; height: 170px;border: 1px solid #e5e5e5; border-bottom-color: #3387ef;">\n        <img ms-if="url" width="150" height="150" style="margin: 9px;" ms-attr-src="url" alt="扫码进行实名认证">\n        <div ms-if="!url">\n          <div class="qr-code-mask" style="height: 170px;"></div>\n          <div class="qr-code-loading" style="padding-top: 60px;">\n              <i></i>\n              <p>加载中，请稍后</p>\n          </div>\n        </div>\n      </div>\n    </div>\n    <div ms-if="accountType == \'wx\'">\n      <div class="qr-code-txt">\n        <i class="icon-wx"></i>请使用微信扫描二维码进行验证\n        <div style="position: relative;margin: 5px auto 10px auto; width: 170px; height: 170px;border: 1px solid #e5e5e5; border-bottom-color: #00c800;">\n          <img ms-if="url" width="150" height="150" style="margin: 9px;" ms-attr-src="url" alt="扫码进行实名认证">\n          <div ms-if="!url">\n            <div class="qr-code-mask" style="height: 170px;"></div>\n            <div class="qr-code-loading" style="padding-top: 60px;">\n                <i></i>\n                <p>加载中，请稍后</p>\n            </div>\n          </div>\n        </div>\n      </div>\n    </div>\n    <div class="btn-wrap">\n      <a type="button" class="btn btn-default" href="javascript:void(0)" ms-on-click="onConfirm">\n        <span>已完成认证</span>\n      </a>\n    </div>\n  </div>\n</div>';
            return __p
        }
    },
    "100835382": function(e, n, t) {
        function i(e, n, t) {
            t = t || {},
            this.opts = t,
            this.store = e,
            this.channelObj = n,
            this._lock = !1,
            this._handlers = {},
            this.refreshUuid(),
            this.coupon = null,
            this.couponVm = null,
            this.mode = t.mode || i.MODE.COMPLETE,
            this.addListener(),
            this.addCouponRefreshListener(),
            this.addPriceLoadingListener()
        }
        var o = t(4)
          , s = t(18)
          , a = t(119561448)
          , r = t(10)
          , c = t(102521382)
          , l = t(49140953)
          , u = t(87796589)
          , d = t(72074753)
          , p = t(22)
          , h = t(101127449)
          , f = t(89481821)
          , m = t(24)
          , g = t(112745811)
          , v = t(84811753)
          , b = t(72658078)
          , y = t(103146681)
          , _ = t(87145282)
          , k = {
            "1450008610": 1,
            "1450007773": 1,
            "1450007826": 1
        }
          , w = o.fn.getParam("inApp")
          , C = t(17);
        o.fn.extend(i.prototype, s),
        o.fn.extend(i.prototype, {
            "addCouponRefreshListener": function() {
                var e = this
                  , n = function() {
                    e.refreshCoupon()
                };
                this.store.on("refreshCoupon", n),
                this.removeCouponRefreshListener = function() {
                    e.store.off("refreshCoupon", n),
                    e.vm && e.vm.couponHTML && (e.vm.couponHTML = "")
                }
            },
            "addPriceLoadingListener": function() {
                var e = this
                  , n = function(n) {
                    e.handlePriceLoading(n)
                };
                this.store.on("priceLoading", n),
                this.removePriceLoadingListener = function() {
                    e.store.off("priceLoading", n),
                    e.vm && e.vm.priceLoadingTplHtml && (e.vm.priceLoading = !1,
                    e.vm.priceLoadingTplHtml = "")
                }
            },
            "calculatePrice": function() {
                var e = this.getOriginPrice();
                this.price = this.store.getPrice(o.discount.checkHasDiscount(e, this.channelObj.channel) ? this.channelObj.discount : void 0, this.coupon).price,
                this.vm && (this.vm.price = this.price)
            },
            "getFrontEndAppid": function() {
                return k[this.store.getAppid()]
            },
            "getDiscount": function() {
                return 1
            },
            "lock": function() {
                this._lock = !0
            },
            "unlock": function() {
                this._lock = !1
            },
            "isLocked": function() {
                return this._lock
            },
            "onChange": o.fn.emptyFunc,
            "removeListener": function() {
                this.removeListener()
            },
            "removeCouponRefreshListener": function() {
                this.removeCouponRefreshListener()
            },
            "removePriceLoadingListener": function() {
                this.removePriceLoadingListener()
            },
            "report": function(e, n) {
                r(String.format("{channel}.{iformat}", {
                    "channel": this.channelObj.channel,
                    "iformat": e
                }), n)
            },
            "reportUser": function(e, n) {
                r.user.action("channel.click", String.format("{channel}.{action}", {
                    "channel": this.channelObj.channel,
                    "action": e
                }), n)
            },
            "destroy": function() {
                this.removeCouponRefreshListener(),
                this.removePriceLoadingListener();
                for (var e in this)
                    "destroy" != e && (this[e] = null)
            },
            "getOriginPrice": function() {
                var e = o.math.toDecimal(this.store.getPrice().price, 2);
                return parseFloat(e)
            },
            "getProductId": function() {
                return g.MONTH == this.store.type ? this.store.getProductId() : ""
            },
            "refreshCoupon": function() {
                var e = this.getChannelCoupons();
                this.vm && (this.vm.coupon = e.length > 0),
                this.couponVm ? this.couponVm.rebind(e) : this.vm && (this.vm.couponConfig.couponList = e)
            },
            "isSupportCoupon": function() {
                var e = this.channelObj.channel
                  , n = l.channels[e].visibleCoupon
                  , t = this.store.getPayFor() == u.SELF;
                return t && this.store.supportCoupon() && n && n.length > 0 && n.indexOf(this.store.type) > -1
            },
            "getChannelCoupons": function() {
                var e = this.channelObj.channel
                  , n = [];
                if (this.isSupportCoupon()) {
                    var t = this.store.getCouponList();
                    if (t.setPayOptions({
                        "channel": e,
                        "price": this.getOriginPrice(),
                        "productId": this.getProductId()
                    }),
                    t.hasValidCoupon()) {
                        var i, o = t.getAllCoupons(), s = null, a = null, r = this.store.editableCoupon();
                        if (r) {
                            var c = this.store.getGlobalCoupon();
                            if (this.useSelect)
                                s = i = c ? c.getId() : null,
                                this.useSelect = !1;
                            else {
                                i = c ? c.getId() : null;
                                var l = this.store.getDefaultCouponId();
                                !i && l && ("1" == l ? (a = t.recommend(),
                                i = a ? a.getId() : null) : i = l),
                                s = i
                            }
                        } else
                            i = this.store.getDefaultCouponId(),
                            "1" == i && (a = t.recommend(),
                            i = a ? a.getId() : null),
                            s = i;
                        t.cancelAll(),
                        s && t.select(s);
                        var u = t.getSelectedCoupons();
                        u.length > 0 && u[0].isValid() ? (this.coupon = u[0],
                        this.store.setGlobalCoupon(u[0])) : (this.coupon = null,
                        this.store.setGlobalCoupon(null)),
                        o.forEach(function(e, t) {
                            !e.isChannelMismatch() && (r || e.getId() == s && e.isValid()) && n.push(this.convertCouponToJSON(e))
                        }
                        .bind(this))
                    }
                }
                return n
            },
            "convertCouponToJSON": function(e) {
                var n = e.getTips();
                return n || !e.isChannelSpecial() && !e.isProductMismatch() || (n = "专属"),
                {
                    "disable": e.isDisable(),
                    "id": e.getId(),
                    "isValid": e.isValid(),
                    "tips": n,
                    "expired": e.isExpired(),
                    "isLoading": !1,
                    "selected": e.isValid() && e.getSelected(),
                    "amt": e.getAmt(),
                    "name": e.getName(),
                    "desc": e.getDescription(),
                    "endDate": e.getEndDate(),
                    "leastPrice": e.getLeastPrice(),
                    "isFrozen": e.isFrozen()
                }
            },
            "fetchCoupon": function() {
                if (this.store.type == g.GOODS && this.store.info.sp_info)
                    return Promise.resolve();
                var e = this
                  , n = this.store.getCouponList();
                return n.fetch().then(function() {
                    "function" == typeof e.refreshCoupon && e.refreshCoupon()
                })
            },
            "handlePriceLoading": function(e) {
                if (!(e instanceof v))
                    throw Error("action must be instance of Action");
                switch (e.getType()) {
                case y:
                    this.vm && (this.vm.priceLoading = !0),
                    this.lock();
                    break;
                case _:
                    this.vm && (this.vm.priceLoading = !1),
                    this.unlock()
                }
            },
            "getCouponVmConfig": function() {
                this.coupon = null;
                var e = this
                  , n = this.getChannelCoupons();
                return {
                    "couponHTML": '<ms:coupon config="couponConfig" on-select="onCouponSelect" on-init="onCouponInit" on-active-coupon="onActiveCoupon" on-prev-page="onPrevPage" on-next-page="onNextPage" on-show-list="onShowList"></ms:coupon>',
                    "coupon": n.length > 0,
                    "onCouponInit": function(n) {
                        e.couponVm = n,
                        e.couponVm.totalPages = e.store.getTotalPages(),
                        e.fetchCoupon(),
                        f.create({
                            "totalPages": e.store.getTotalPages()
                        })
                    },
                    "onShowList": function(e) {},
                    "onActiveCoupon": function(n, t) {
                        var i = e.store.getCouponList();
                        e.report("coupon.active", {
                            "action": n.id
                        }),
                        i.activate(i.getCouponFromId(n.id)).then(function(i) {
                            var o = i.success;
                            e.report("coupon.active." + (o ? "success" : "failed"), {
                                "action": n.id
                            }),
                            t(o),
                            o || h({
                                "content": "激活失败，稍后再试"
                            })
                        })
                    },
                    "onCouponSelect": function(n) {
                        var t = null;
                        n && n.isValid && (t = e.store.getCouponList().getCouponFromId(n.id)),
                        (!!t ^ !!e.coupon || t && e.coupon && t.getId() != e.coupon.getId()) && (e.coupon = t,
                        e.store.setGlobalCoupon(t),
                        e.useSelect = !0,
                        e.store.emitChange())
                    },
                    "onNextPage": function(n) {
                        e.report("coupon.nextpage");
                        var t = e.store.getCouponList()
                          , i = 9
                          , o = Math.min((n + 1) * i - 1, e.store.getTotalCouponCount())
                          , s = o > t.coupons.length;
                        return s ? e.fetchCoupon() : e.refreshCoupon()
                    },
                    "onPrevPage": function() {
                        e.report("coupon.prevpage"),
                        e.refreshCoupon()
                    },
                    "couponConfig": {
                        "oneCoupon": n.length > 0 ? n[0] : null,
                        "editableCoupon": this.store.editableCoupon(),
                        "center": [d.QQWALLET, d.WECHAT].indexOf(this.channelObj.channel) > -1,
                        "couponList": n
                    }
                }
            },
            "getTermsList": function() {
                var e = this.store.info.offer_id
                  , n = {
                    "1450000186": [{
                        "term": "https://www.qq.com/contract.shtml",
                        "termName": "Q币充值用户条例"
                    }]
                };
                if (window.__midasStaticConfig_ipay_pcgame_sidebar && window.__midasStaticConfig_ipay_pcgame_sidebar.itemMap) {
                    var t = window.__midasStaticConfig_ipay_pcgame_sidebar.itemMap;
                    for (_key in t) {
                        var i = t[_key];
                        i.term && (n[i.appid] = [{
                            "term": i.term,
                            "termName": i.homeName + "用户条例"
                        }])
                    }
                }
                if (window.__midasStaticConfig_ipay_month_sidebar && window.__midasStaticConfig_ipay_month_sidebar.itemMap) {
                    var t = window.__midasStaticConfig_ipay_month_sidebar.itemMap;
                    for (_key in t) {
                        var i = t[_key] || {}
                          , o = i.terms || [];
                        n[i.appid] = o.filter(function(e) {
                            return e.termName && e.term
                        })
                    }
                }
                return n[e] && n[e].length ? n[e] : this.store.info && this.store.info.month_info && this.store.info.month_info.service_provision ? [{
                    "term": this.store.info.month_info.service_provision,
                    "termName": "用户条例"
                }] : []
            },
            "getTermsVmConfig": function() {
                var e = this.getTermsList();
                return {
                    "terms": e,
                    "openTerm": function(e, n) {
                        n.stopPropagation(),
                        n.preventDefault(),
                        "1" != w ? o.openWindow(e["term"]) : C.openWindow(e["term"])
                    }
                }
            },
            "getPubVmConfig": function() {
                return {
                    "priceLoading": !1,
                    "priceLoadingTplHtml": b()
                }
            },
            "addListener": function() {
                var e = this;
                this.removeListener = this.store.addListener(function() {
                    e.onChange()
                })
            },
            "isSupportCanvas": function() {
                return "undefined" != typeof CanvasRenderingContext2D
            },
            "getShortUrl": function(e, n, t) {
                var i = 600;
                return p.isProduction || t ? void this.store.getCgi().getQrcode({
                    "a": "get_short_url",
                    "url": encodeURIComponent(e)
                }, function(e) {
                    n(~~e.ret ? {
                        "status": !1,
                        "res": e
                    } : {
                        "status": !0,
                        "validTime": i,
                        "shortUrl": this.store.getCgi().getQrcode({
                            "a": "l",
                            "t": o.fn.getParam("t", e.result_url)
                        }),
                        "res": e
                    })
                }
                .bind(this)) : n({
                    "status": !0,
                    "validTime": i,
                    "shortUrl": e
                })
            },
            "genQrcode": function(e, n) {
                n = n || {};
                this.store.getParams();
                if (p.isProduction || (n.useBackend = !0),
                this.isSupportCanvas() && !n.useBackend && n.selector) {
                    var t = document.getElementById(n.selector);
                    if (t)
                        try {
                            t.style.display = "",
                            t.innerHTML = "";
                            var i = new m(t,{
                                "width": 120,
                                "height": 120,
                                "correctLevel": m.CorrectLevel.M
                            });
                            return i.clear(),
                            i.makeCode(e),
                            this.report("jsqrcode", {
                                "resultinfo": {
                                    "status": "succ"
                                }
                            }),
                            null
                        } catch (s) {
                            this.report("jsqrcode", {
                                "resultinfo": {
                                    "status": "fail",
                                    "err": s.message
                                }
                            })
                        }
                }
                var a = {
                    "size": "120",
                    "url": encodeURIComponent(e),
                    "t": (new Date).getTime()
                };
                return (p.isProduction || n.useOrig) && (a.orig = "1"),
                o.fn.addParam(a, String.format("//pay.qq.com/cgi-bin/account/get_qr_image.cgi", {
                    "domain": p.isProduction ? "" : "sandbox."
                }))
            },
            "secondLoginIsInvalid": function(e) {
                return ["146", "1905"].indexOf(String(e)) > -1
            },
            "showQQLoginBox": function(e) {
                var n = this;
                e = o.fn.extend({
                    "onClose": avalon.noop,
                    "onSuccess": avalon.noop
                }, e || {}),
                c.init(function() {
                    c.setCallBack({
                        "onSuccess": function() {
                            e.onSuccess.call(n)
                        },
                        "onClose": function() {
                            e.onClose.call(n)
                        }
                    }),
                    c.show()
                })
            },
            "refreshUuid": function() {
                this.uuid = o.fn.uuid()
            },
            "showMask": function() {
                a.show({
                    "opacity": "0"
                })
            },
            "hideMask": function() {
                a.hide()
            }
        }),
        i.MODE = {
            "SIMPLE": "simple",
            "COMPLETE": "complete",
            "NEW_PAGE_PAY": "new_page_pay"
        },
        e.exports = i
    },
    "101127449": function(e, n, t) {
        var i = t(1)
          , o = t(4)
          , s = null
          , a = "_cp__toast__";
        Toast = {
            "show": function(e) {
                var e = e || {};
                if (s = document.getElementById(a),
                !s) {
                    var n = i.parseHTML('<div class="pop-tips" id="' + a + '"></div>');
                    e.container ? e.container.appendChild(n) : document.body.appendChild(n),
                    s = document.getElementById(a)
                }
                i(s).css({
                    "display": "block",
                    "z-index": e.zIndex || 5001
                }),
                s.innerHTML = e.content || "无内容"
            },
            "hide": function() {
                s && i(s).css({
                    "display": "none"
                })
            },
            "remove": function() {
                document.body.removeChild(document.getElementById(a))
            }
        },
        e.exports = function(e) {
            Toast.show(e),
            o.delayRun("toast", function() {
                Toast.hide()
            }, 3e3)
        }
    },
    "101670216": function(e, n, t) {
        var i = t(4)
          , o = i.fn.getParams();
        e.exports = {
            "urlParams": o,
            "getQQAppid": function() {
                return o.qqAppid
            }
        }
    },
    "102521382": function(e, n, t) {
        var i = t(1)
          , o = t(10);
        window.__loginCallBack = function() {
            a._onSuccess(),
            a.hide()
        }
        ;
        var s = !1
          , a = {
            "_onSuccess": function() {},
            "setCallBack": function(e) {
                var n = window.pt
                  , t = window.location.protocol + "//" + window.location.host + "/midas/minipay_v2/views/public/pt_proxy.shtml"
                  , i = {
                    "appid": 11000101,
                    "s_url": t,
                    "style": 21,
                    "hide_close_icon": e.hideClose ? 1 : 0,
                    "protocol": location.protocol,
                    "border_radius": 1,
                    "target": "self",
                    "maskOpacity": 40
                };
                e.daid && (i.daid = e.daid),
                n.setParams(i),
                n.setCallback("close", "function" == typeof e.onClose ? e.onClose : function() {}
                ),
                this._onSuccess = e.onSuccess,
                o("ptlogin.pv", {
                    "resultinfo": {
                        "daid": e.daid || 0
                    }
                })
            },
            "_setSize": function() {
                var e = 400
                  , n = 382
                  , t = document.getElementById("ui_ptlogin")
                  , o = t.parentNode;
                t && o && (i(o).css({
                    "width": e,
                    "height": n,
                    "top": "50%",
                    "left": "50%",
                    "position": "absolute",
                    "margin-top": -n / 2,
                    "margin-left": -e / 2,
                    "display": "block"
                }),
                setTimeout(function() {
                    o.style.top = "50%"
                }, 100))
            },
            "show": function() {
                pt.showPtui(),
                this._setSize()
            },
            "hide": function() {
                pt.hidePtui(),
                this._onSuccess = function() {}
            },
            "logout": function(e) {
                pt.logout(e)
            },
            "init": function(e) {
                return s ? void e() : void i.getScript(location.protocol + "//xui.ptlogin2.qq.com/js/ptlogin_v1.js", function() {
                    s = !0,
                    e()
                })
            }
        };
        e.exports = a
    },
    "102987497": function(e, n, t) {
        function i(e, n) {
            var t, i = n.inner_productid, s = n.product_id, a = n.open_days, r = n.currency_amt;
            if (r = 1 * r,
            a = 1 * a,
            e && e.rule_item) {
                var c = e.rule_item
                  , l = e.rank_type
                  , u = c.filter(function(e) {
                    return e.service_code && e.service_code.split(",").indexOf(i) !== -1
                });
                if (u.length) {
                    var d = u.filter(function(e) {
                        return e.product_id && e.product_id.split(",").indexOf(s) !== -1
                    });
                    if (d.length ? t = d[0] : (d = u.filter(function(e) {
                        return "*" === e.product_id
                    }),
                    d.length && (t = d[0])),
                    t) {
                        var p = !1;
                        if ("1" === t.pricingwithrank && o.lang.isArray(t.present_item)) {
                            var h = t.present_item;
                            if ("single" === l)
                                h.forEach(function(e) {
                                    1 * e.num === a && (p = !0)
                                });
                            else if ("range" === l) {
                                h.sort(function(e, n) {
                                    return e < n
                                });
                                for (var f = h.length - 1; f >= 0; f--) {
                                    var m = h[f];
                                    if (a >= 1 * m.num) {
                                        p = !0;
                                        break
                                    }
                                }
                            }
                            p || (t = null)
                        }
                        t && "1" === e.has_qualify_filter && "1" !== e.MatchMonthStatus && (p && "1" === t.monthstatusblock,
                        t = null)
                    }
                    if (t && "fixed" === t.discount_type && /\d+\/\d+/.test(String(t.discount)) && (t.discount_type = "fraction"),
                    t && "fixed" === t.discount_type && t.discount > 0 && t.discount < 100)
                        r *= t.discount / 100;
                    else if (t && "fraction" === t.discount_type) {
                        var g = t.discount.split("/").map(function(e) {
                            return parseFloat(e)
                        });
                        r = r * g[0] / g[1]
                    } else if (t && "unfixed" === t.discount_type)
                        for (var v = t.discount.split(";").map(function(e) {
                            return e.split(":")
                        }), f = 0; f < v.length; f++) {
                            var m = v[f]
                              , b = m[0];
                            if (1 * b === a) {
                                var y = m[1];
                                if ("*" === y || y.split("|").indexOf(String(r)) !== -1) {
                                    r = 1 * m[2];
                                    break
                                }
                            }
                        }
                }
            }
            return {
                "price": r,
                "extend": t && t.extend_info ? o.fn.getParams(decodeURIComponent(t.extend_info || "")) : {}
            }
        }
        var o = t(4);
        e.exports = {
            "drmDiscount": i
        }
    },
    "103146681": function(e, n) {
        e.exports = "price-loading-begin"
    },
    "103218213": function(e, n, t) {
        var i = t(1)
          , o = t(88037617)
          , s = t(4)
          , a = t(10);
        i.component("ms:autocomplate", {
            "value": {
                "name": ""
            },
            "isShow": !1,
            "data": [],
            "searchData": [],
            "_copyData": [],
            "$skipArray": [],
            "$replace": !0,
            "name": "",
            "inputName": "",
            "showSpan": !0,
            "hasClickFocus": !1,
            "onInit": i.noop,
            "onChange": i.noop,
            "noDataMsg": "暂无数据",
            "defaultValue": {
                "name": "请选择"
            },
            "showall": !0,
            "hasMutil": !1,
            "hideAble": !0,
            "leftPosition": "0px",
            "container": null,
            "inputId": "",
            "dropdownId": "",
            "autocompleteId": "",
            "timer": null,
            "getValue": function() {
                return this.value
            },
            "showList": function(e) {
                this.isShow = "true" === e,
                this.isShow && this.adjustPosition()
            },
            "adjustPosition": function() {
                if (this.container && this.hasMutil) {
                    var e = document.getElementById(this.container)
                      , n = i(e).outerWidth(!0)
                      , t = i(e).offset().left
                      , o = i(document.getElementById(this.inputId)).offset().left
                      , s = (e.getBoundingClientRect(),
                    420)
                      , a = o - t;
                    this.leftPosition = a + s > n ? n - a - s - 10 : "0px"
                } else
                    this.leftPosition = "0px"
            },
            "setHideAble": function(e) {
                this.hideAble = "true" === e
            },
            "select": function(e, n, t) {
                n && n.preventDefault();
                var o = i.mix(!0, {}, e.$model || e);
                this.name = e.name,
                this.value = o,
                this.showSpanDom(this.showSpan),
                this.hideAble = !0,
                this.isShow = !1,
                t || this.onChange(o)
            },
            "showSpanDom": function(e) {
                e ? (this.inputName = "",
                this.showSpan = !0) : (this.inputName = this.name,
                this.showSpan = !1)
            },
            "setMutil": function(e) {
                this.hasMutil = e > 6
            },
            "keyup": function(e) {
                var n = this;
                this.timer && clearTimeout(this.timer),
                this.timer = setTimeout(function() {
                    var t = e.target.value;
                    "" === t ? (n.searchData = [],
                    n.showall = !0,
                    n.setMutil(n._copyData.length)) : (n.searchData = n._searchData(t),
                    n.showall = !1,
                    n.setMutil(n.searchData.length)),
                    n.adjustPosition()
                }, 100)
            },
            "_searchData": function(e) {
                a("autocomplete.input", {
                    "action": "autocomplete"
                });
                for (var n = [], t = this._copyData, i = 0, o = t.length; i < o; i++)
                    t[i].name.indexOf(e) == -1 && (t[i].search + "").indexOf(e) == -1 || n.push(t[i]);
                return n
            },
            "focusInput": function() {
                var e = document.getElementById(this.inputId);
                e.focus(),
                this.showSpanDom(!1),
                this.isShow = !0,
                this.showall = !0,
                this.setMutil(this._copyData.length)
            },
            "focusEl": function(e, n) {
                n.preventDefault(),
                this.hasClickFocus = !0,
                this.focusInput(),
                this.adjustPosition(),
                s.delayRun("click.foucs", function() {
                    this.hasClickFocus = !1
                }
                .bind(this), 500)
            },
            "blur": function(e) {
                return this.hideAble ? void s.delayRun("click.blur", function() {
                    this.hasClickFocus || (this.isShow = !1,
                    this.showSpanDom(!0))
                }
                .bind(this), 200) : (e.preventDefault(),
                e.target.focus(),
                void this.showSpanDom(!1))
            },
            "width": "140px",
            "$template": o(),
            "$init": function(e, n) {
                e.autocompleteId = s.fn.uuid(),
                e.inputId = e.autocompleteId + "-input",
                e.dropdownId = e.autocompleteId + "-ddl",
                e._copyData = i.mix(!0, [], e.$model.data),
                e.bindData.call(e, e.value)
            },
            "$ready": function(e) {
                e.onInit(e)
            },
            "bindData": function(e, n) {
                var t = this;
                if (t.setMutil.call(t, t._copyData.length),
                e && (t.value = e),
                t.value.name || t.value.value) {
                    var i = -1;
                    t.data.some(function(e, n) {
                        if (e.name === t.value.name || e.value == t.value.value)
                            return i = n,
                            !0
                    });
                    t.select.call(t, i >= 0 ? t.data[i] : t.defaultValue, null, n)
                } else
                    t.select.call(t, t.defaultValue, null, n)
            },
            "reset": function(e, n, t) {
                this.data = e,
                this._copyData = i.mix(!0, [], e),
                this.bindData(n, t)
            }
        }),
        e.exports = {
            "create": function(e) {
                return '<ms:autocomplate config="' + e + '" on-change="onChange"></ms:autocomplate>'
            }
        }
    },
    "103220717": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div class="coupon" >\n    <span ms-visiable="label"><i class="icon-coupon"></i> {{label}}：</span>\n    <div class="coupon-select" style="z-index: 1000" ms-css-width="width" ms-on-mouseenter="showList(\'true\')" ms-on-mouseleave="showList(\'false\')" ms-class="open:isShow">\n        <div class="coupon-selected">{{value.name}}  <i class="icon-more-arrow"></i></div>\n\n        <div class="coupon-options" ms-css-width="width" style="z-index: 1000">\n\n            <!--<div class="option" ms-repeat="data" ms-on-click="select(el)" ms-class="option-dont:$index==data.length-1">-->\n                <!--<p>{{el.name}}</p>-->\n                <!--<span>{{el.desc}}</span>-->\n            <!--</div>-->\n            <div class="option" ms-repeat="data" ms-on-click="select(el)" ms-class-1="option-dont:el.dont">\n                <p ms-if="!el.dont">{{el.name}}</p>\n                <span ms-if="!el.dont">{{el.desc}}</span>\n                {{el.dont? el.name:\'\'}}\n            </div>\n        </div>\n    </div>\n</div>\n\n';
            return __p
        }
    },
    "104491903": function(e, n) {
        e.exports = "back-button"
    },
    "104500419": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<label>\n<input ms-class-1="{{defaultClass}}" ms-class-2="warn:state==1" ms-class-3="{{extraClass}}" ms-class-4="focus:isFocused" type="text" ms-attr-id="id"\n       ms-duplex="value"\n       ms-attr-placeholder="placeholder"\n       ms-on-blur="handleBlur"\n       ms-on-focus="handleFocus"\n/>\n</label>';
            return __p
        }
    },
    "104708884": function(e, n, t) {
        var i = t(116820311)
          , o = t(4)
          , s = t(1)
          , a = t(100835382)
          , r = t(25)
          , c = t(11)
          , l = t(119561448)
          , u = (o.fn.getParam("sandbox"),
        t(49140953),
        t(112745811))
          , d = t(84811753)
          , p = t(75748174)
          , h = t(43847285)
          , f = t(117821206);
        t(68682076);
        var m = function(e, n, t) {
            a.apply(this, arguments),
            this.isBuying = !1,
            this.firstBuy = !0,
            this.saveTimout = null,
            this.validTimeout = null,
            this.init()
        }
          , g = {
            "init": function() {
                if (this.initVm(),
                this.calculatePrice(),
                this.fetchTargetUin(),
                this.fetchAmount(),
                this.isDisable = this.store.isInterfaceDisabled(),
                this.hasLoaded = !1,
                !this.isDisable)
                    return 0 == this.amount ? (this.disableQrcode(),
                    this.vm.disableText = "请完善充值信息",
                    void (this.vm.showScaned = !1)) : void (this.saveTimout = new c.Timeout({
                        "time": .7,
                        "timeUp": function() {
                            this.saveTimout = null,
                            "function" == typeof this.buy && this.buy()
                        }
                        .bind(this)
                    }))
            },
            "calculatePrice": function() {
                var e = this.store.getPrice().price;
                this.price = this.store.getPrice(o.discount.checkHasDiscount(e, "friendpay") ? this.channelObj.discount : void 0).price,
                this.vm.price = this.price
            },
            "fetchAmount": function() {
                this.amount = this.store.getAmount()
            },
            "fetchTargetUin": function() {
                this.targetUin = this.store.getTargetInfo().uin
            },
            "onChange": function() {
                return this.fetchTargetUin(),
                this.fetchAmount(),
                this.calculatePrice(),
                this.saveTimout && this.saveTimout.stop(0),
                this.store.isInterfaceDisabled() ? (this.isDisable = !0,
                this.disableQrcode(),
                void (this.vm.disableText = this.store.getChannelDisableText())) : (this.enableQrcode(),
                this.isDisable && (this.isDisable = !1),
                0 == this.amount ? (this.disableQrcode(),
                this.vm.showScaned = !1,
                void (this.vm.disableText = "请完善充值信息")) : (this.vm.qrcodeLoading = !0,
                this.vm.qrcodeReload = !1,
                this.vm.showQrcode = !0,
                this.vm.showScaned = !1,
                void (this.saveTimout = new c.Timeout({
                    "time": .7,
                    "timeUp": function() {
                        this.saveTimout = null,
                        "function" == typeof this.buy && this.buy()
                    }
                    .bind(this)
                }))))
            },
            "disableQrcode": function() {
                this.vm && (this.vm.disableQrcode = !0)
            },
            "enableQrcode": function() {
                this.vm && (this.vm.disableQrcode = !1)
            },
            "getVmConfig": function() {
                var e = this;
                return o.fn.extend({
                    "$id": "friendpay-controller",
                    "price": this.price,
                    "url": null,
                    "showScaned": !1,
                    "showQrcode": !0,
                    "disableQrcode": this.store.isInterfaceDisabled(),
                    "disableText": this.store.getChannelDisableText() || "",
                    "gotonext": function() {},
                    "backQrcode": function() {
                        return e.vm.disableQrcode ? void e.store.emit("channelDataChange", new d(p)) : (e.vm.showQrcode = !0,
                        void (e.vm.showScaned = !1))
                    },
                    "qrcodeLoaded": function() {
                        l.hide(),
                        e.vm && (e.vm.qrcodeLoading = !1,
                        e.vm.qrcodeReload = !1)
                    },
                    "qrcodeLoadFail": function() {
                        if (l.hide(),
                        e.vm) {
                            e.vm.qrcodeLoading = !1,
                            e.vm.qrcodeReload = !0,
                            e.vm.url = "";
                            try {
                                var n = document.getElementById("qr-code-friendpay");
                                n && (n.innerHTML = "")
                            } catch (t) {}
                        }
                    },
                    "refreshQrcode": function() {
                        e.vm && (e.vm.qrcodeReload = !1,
                        e.vm.qrcodeLoading = !0,
                        e.buy())
                    },
                    "fail": function() {
                        e.vm.qrcodeLoaded(),
                        e.vm.url = ""
                    },
                    "qrcodeLoading": !0,
                    "qrcodeReload": !1
                }, this.getPubVmConfig())
            },
            "initVm": function() {
                this.vm = s.define(this.getVmConfig())
            },
            "getQrcode": function(e) {
                var n = this.store.cgi.sessionObj
                  , t = {
                    "tk": e.token,
                    "type": this.store.opts.type === u.GAME ? "game" : this.store.opts.type,
                    "pf": this.store.params.pf,
                    "env": this.store.params.sandbox,
                    "ofi": this.store.params.appid,
                    "or_oi": n.openid,
                    "or_si": n.sessionid,
                    "or_st": n.sessiontype,
                    "uuid": this.uuid,
                    "sv_ex": encodeURIComponent(o.req.serializeParam({
                        "biz_appid": this.store.getWxAppid(),
                        "change_wx_openid": this.store.params.change_wx_openid,
                        "token_store_type": e.token_store_type
                    }))
                };
                o.fn.extend(t, o.fn.getParams(decodeURIComponent(this.store.params.friendPayExtend)));
                var i = o.fn.addParam(t, "https://pay.qq.com/webpay-h5/views/friend.html");
                this.getShortUrl(i, function(e) {
                    if (e && e.status) {
                        var n = this.genQrcode(e.shortUrl, {
                            "selector": "qr-code-friendpay",
                            "useBackend": !this.getFrontEndAppid()
                        });
                        this.validTimeout = setTimeout(function() {
                            try {
                                this.vm.qrcodeLoadFail()
                            } catch (e) {}
                        }
                        .bind(this), 1e3 * e.validTime),
                        null !== n ? this.vm.url = n : this.vm.qrcodeLoaded()
                    } else
                        this.vm.qrcodeLoadFail()
                }
                .bind(this))
            },
            "buy": function(e, n) {
                if (e = e || {},
                clearTimeout(this.validTimeout),
                this.firstBuy = !1,
                0 != this.store.getAmount()) {
                    var t = {
                        "biz_appid": this.store.getWxAppid(),
                        "uuid": this.uuid,
                        "pay_method": this.channelObj.channel,
                        "pushtype": "NodeJS"
                    };
                    o.fn.extend(t, e),
                    l.show({
                        "opacity": "0"
                    }),
                    this.vm.qrcodeReload = !1,
                    this.vm.qrcodeLoading = !0,
                    this.store.buy(t, function(e) {
                        this.hasLoaded = !0,
                        l.hide();
                        try {
                            return this.handlerBuy(e, t)
                        } catch (n) {
                            return !0
                        }
                    }
                    .bind(this))
                }
            },
            "handlerBuy": function(e, n) {
                var t, i = this;
                if (!~~e.ret)
                    return this.getQrcode(e.info || {}),
                    setTimeout(function() {
                        try {
                            this.setupPooling()
                        } catch (e) {}
                    }
                    .bind(this), 100),
                    !0;
                t = new f({
                    "errCode": e.ret,
                    "errMsg": e.msg,
                    "oriParams": n,
                    "2022": function() {
                        var n = e.info;
                        new h({
                            "url": n.verify_url,
                            "fk_info": n.fk_info,
                            "fk_amt": n.fk_amt,
                            "onLoad": function() {},
                            "onRcRestrict": function(e, n) {
                                e = e || {},
                                i.store.rcRestrict(e, n)
                            },
                            "onVerifyDone": function(e) {
                                e = e || {},
                                i.vm.qrcodeLoading = !0,
                                i.vm.qrcodeReload = !1,
                                i.buy(e)
                            }
                        })
                    }
                });
                try {
                    this.vm.qrcodeLoadFail()
                } catch (o) {}
                return !(!t || !t.canHandle()) && (t.exec(),
                !0)
            },
            "setupPooling": function() {
                var e = this;
                this.comet || (this.comet = new r({
                    "uuid": this.uuid,
                    "sandbox": ~~this.store.getSandbox(),
                    "sessionObj": this.store.getSession(),
                    "onSuccess": function() {
                        e.reportUser("push.success"),
                        e.store.onSuccess()
                    },
                    "onScan": function() {
                        e.reportUser("scan.pv"),
                        e.vm.showScaned = !0,
                        e.vm.showQrcode = !1
                    },
                    "onPaying": function() {}
                }),
                this.comet.start())
            },
            "onDestroy": function() {
                clearTimeout(this.validTimeout),
                a.prototype.removeListener.call(this),
                this.comet && this.comet.abort(),
                this.saveTimout && this.saveTimout.stop(0),
                a.prototype.destroy.call(this),
                this.vm = null,
                l.hide()
            }
        };
        o.inherits(m, a),
        o.fn.extend(m.prototype, g),
        m.create = function(e, n, t) {
            return new m(e,n,t)
        }
        ,
        m.getTemplate = function(e) {
            return i(e)
        }
        ,
        e.exports = m
    },
    "104911180": function(e, n) {
        e.exports = {
            "FIX": "unit_price",
            "UNFIX": "price_list",
            "CUSTOM": "custom"
        }
    },
    "105155243": function(e, n, t) {
        var i = t(4)
          , o = t(1);
        t(5);
        var s = t(51748615)
          , a = t(9)
          , r = function() {
            var e = !1;
            try {
                var n = window.top.location;
                n.host.toLowerCase();
                e = "https:" == n.protocol
            } catch (t) {}
            return e
        }
          , c = function(e) {
            e = e || {},
            this.wxLoginScript = location.protocol + "//res.wx.qq.com/connect/zh_CN/htmledition/js/wxLogin.js",
            this.appid = e.appid || "wx951bdcac522929b6",
            this.openid = e.openid || null,
            this.self_redirect = e.self_redirect,
            this.authContainer = e.container || c.defaultContainer,
            this.targetUrl = e.targetUrl || i.fn.delParam(["code", "state"], location.href),
            this.saveCookie = e.saveCookie,
            this.accessToken = e.accessToken || null,
            this.scope = e.scope || "snsapi_login",
            this.refreshTokenKey = this.appid + "rt",
            i.cookie.get(this.refreshTokenKey) ? this.type = c.TYPE.REFRESH_TOKEN : i.fn.getParam("code") ? this.type = c.TYPE.CODE : ~~e.forceAuth ? this.type = c.TYPE.NEEDAUTH : this.type = c.TYPE.NEEDAUTH
        };
        c.TYPE = {
            "REFRESH_TOKEN": 1,
            "NEEDAUTH": 2,
            "CODE": 3
        },
        c.defaultContainer = "wx_auth_container",
        i.fn.extend(c.prototype, {
            "needAuth": function() {
                return this.type != c.TYPE.REFRESH_TOKEN
            },
            "setContainer": function(e) {
                this.authContainer = e
            },
            "getOpenid": function(e, n) {
                function t() {
                    o.ajax({
                        "method": "get",
                        "contentType": "application/json; charset=utf-8",
                        "url": "//pay.qq.com/cgi-bin/account/get_wechat_userinfo.cgi?" + i.req.serializeParam(e),
                        "success": function(e, t, o) {
                            if (e = JSON.parse(o.responseText),
                            !~~e.resultcode && e.resultinfo) {
                                var r = e.resultinfo;
                                s.openid = r.obj.openid,
                                s.accessToken = r.obj.access_token,
                                s.info = r.obj,
                                s.saveCookie && i.cookie.set(s.refreshTokenKey, r.obj.refresh_token || ""),
                                n.onSuccess && n.onSuccess(new a({
                                    "openid": s.openid,
                                    "openkey": s.accessToken,
                                    "sessionid": "hy_gameid",
                                    "sessiontype": "wc_actoken"
                                }))
                            } else
                                i.cookie.del(s.refreshTokenKey),
                                s.auth()
                        }
                    })
                }
                if (e = e || {},
                n = n || {},
                this.type == c.TYPE.REFRESH_TOKEN)
                    i.fn.extend(e, {
                        "refresh_token": i.cookie.get(this.refreshTokenKey)
                    });
                else if (this.type == c.TYPE.CODE)
                    i.fn.extend(e, {
                        "code": i.fn.getParam("code")
                    });
                else if (this.type == c.TYPE.NEEDAUTH)
                    return void this.auth();
                i.fn.extend(e, {
                    "appid": this.appid,
                    "r": Math.random()
                }),
                t.call(this);
                var s = this
            },
            "auth": function() {
                this.type = c.TYPE.NEEDAUTH,
                o.getScript(this.wxLoginScript, function() {
                    new WxLogin({
                        "id": this.authContainer,
                        "appid": this.appid,
                        "self_redirect": this.self_redirect,
                        "state": 111,
                        "scope": this.scope,
                        "redirect_uri": encodeURIComponent(i.fn.delParam(["code", "state"], this.targetUrl))
                    })
                }
                .bind(this))
            }
        });
        var l = {};
        l = {
            "_d": null,
            "_wechat": null,
            "_onClose": function() {
                l._closeDialog()
            },
            "_onSuccess": function() {
                l._closeDialog()
            },
            "_closeDialog": function() {
                var e = l._d;
                e && (e.close(),
                e = null)
            }
        },
        window.__wxLoginCallBack = function(e) {
            e && e.refreshToken && l._wechat.saveCookie && i.cookie.set(l._wechat.refreshTokenKey, e.refreshToken),
            l._onSuccess(new a({
                "openid": e.openid,
                "openkey": e.accessToken,
                "sessionid": "hy_gameid",
                "sessiontype": "wc_actoken"
            }))
        }
        ,
        e.exports = {
            "isValidUser": r,
            "init": function(e) {
                function n() {
                    t.getOpenid({}, {
                        "onSuccess": function(e) {
                            i(e)
                        }
                    })
                }
                var t = l._wechat = new c(e)
                  , i = e.onSuccess || l._onSuccess;
                e.onSuccess && (i = l._onSuccess = function(n) {
                    e.onSuccess(n),
                    l._closeDialog()
                }
                );
                var o = e.onClose || l._onClose;
                e.onClose && (l._onClose = function() {
                    e.onClose(),
                    l._closeDialog()
                }
                ),
                t.needAuth() ? s.create({
                    "hideHeader": e.hideHeader,
                    "opacity": e.opacity,
                    "bgColor": e.bgColor,
                    "clickClose": e.clickClose,
                    "forceMaskCss": e.forceMaskCss,
                    "size": {
                        "w": e.width || 500,
                        "h": e.height || 405
                    },
                    "onClose": function() {
                        o()
                    },
                    "onReady": function(e) {
                        l._d = e,
                        t.setContainer(e.getBodyId()),
                        n()
                    }
                }) : n()
            }
        }
    },
    "105875273": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div ms-controller="qb-controller">\n  <!--<div class="left-money" id="qb_left_money_container">-->\n  <!--<a class="query-left-money" href="javascript:;" ms-click="queryBalance">查询余额</a>-->\n  <!--</div>-->\n\n  <div class="coupon" ms-if="goldCouponConfig">\n    <ms:dropdown config="goldCouponConfig"></ms:dropdown>\n  </div>\n  <div class="coupon" ms-if="coupon&&typeof goldCouponConfig==\'undefined\'" ms-html="couponHTML"></div>\n  <div ms-if="showBalance" class="left-money" style="position: static">\n    <p class="tips sub-tips query-after">账户余额： <em>{{balance}}</em> Q币<span ms-if="uin">({{uin}})</span></p>\n  </div>\n\n  <div class="left-money-warn" ms-if="balanceNotEnough">\n    <p>\n      <i class="icon-error"></i>Q币余额不足\n      <span ms-if="!hideBalance">余额：<em class="left-money-em">{{balance}}</em>Q币</span>\n    </p>\n    <p class="tips sub-tips" ms-if="!hideBalance">还需<em>{{diff}}</em>Q币，请先去充值，或选择其他支付方式</p>\n  </div>\n  <div ms-if="showAutoTips" style="margin-bottom: 10px">\n    <div class="form-group checkbox-box" ms-class="checked:autoPay">\n      <label for="checkbox1"><input id="checkbox1" type="checkbox" />\n        <div ms-on-click="autoHandle()">\n          <i class="icon-checkbox"></i> Q币余额足够时，到期后自动续费,专享{{unitPrice}}{{unitName}}/月\n        </div>\n      </label>\n    </div>\n  </div>\n\n  <!-- 无法在跨域iframe里完成Q币支付的场景，引导跳出 -->\n  <div class="left-money-warn" ms-if="needJumpToNewPage">\n    <p class="tips sub-tips"><i class="icon-error"></i> 温馨提示：使用Q币支付需要打开新的页面，请在新页面支付。</p>\n  </div>\n\n  <div>\n    <a ms-if="balanceNotEnough" hidefocus="true" class="btn btn-default" ms-click="goCharge" href="#">去充值</a>\n    <div class="oper-to-pay" data-track="payBtn" ms-if="!balanceNotEnough&&needJumpToNewPage">\n      <a class="btn btn-default" ms-click="handleClick" hidefocus="true" href="#">\n        <span>\n          去支付 \n          <em class="total-price-in-button" ms-if="!priceLoading">{{price}}</em>\n          <span ms-if="priceLoading" ms-html="priceLoadingTplHtml"></span>\n          Q币\n        </span>\n      </a>\n    </div>\n    <div class="oper-to-pay" data-track="payBtn" ms-if="!balanceNotEnough&&!needJumpToNewPage">\n      <!-- 没有服务条款 -->\n      <a class="btn btn-default" ms-class-1="loading:paying" ms-class-2="btn-dis:disableSubmit" ms-click="handleClick"\n        hidefocus="true" href="#" ms-if="terms.length==0">\n        <span ms-if="!paying">\n          <span>\n            确认支付 \n            <em class="total-price-in-button" ms-if="!priceLoading">{{price}}</em>\n            <span ms-if="priceLoading" ms-html="priceLoadingTplHtml"></span>\n            Q币\n          </span>\n        </span>\n        <span>\n          <i class="icon-btn-loading"></i>\n        </span>\n      </a>\n      <!-- 有服务条款 -->\n      <a class="btn btn-default" ms-class-1="loading:paying" ms-class-2="btn-dis:disableSubmit" ms-click="handleClick"\n        hidefocus="true" href="#" style="min-width: 180px;" ms-if="terms.length>0">\n        <span ms-if="!paying">\n          <span>\n            同意协议并支付 \n            <em class="total-price-in-button" ms-if="!priceLoading">{{price}}</em>\n            <span ms-if="priceLoading" ms-html="priceLoadingTplHtml"></span>\n            Q币\n          </span>\n        </span>\n        <span>\n          <i class="icon-btn-loading"></i>\n        </span>\n      </a>\n    </div>\n    <div class="left-money-warn" ms-if="terms.length > 0">\n      <p class="tips sub-tips">支付前阅读并同意\n        <span ms-repeat="terms">\n          <a href="#" ms-click="openTerm(el,$event)">{{el.termName}}</a>\n        </span>\n      </p>\n    </div>\n  </div>\n</div>';
            return __p
        }
    },
    "106121617": function(e, n, t) {
        function i(e) {
            if (this.mount = e.mount,
            this.unmount = e.unmount,
            this.cgi = e.cgi,
            this.configName = e.configName,
            this.setConfig = e.setConfig,
            this.onSuccess = e.onSuccess || s,
            this.onPending = e.onPending || s,
            this.onFail = e.onFail || s,
            this.onNoResult = e.onNoResult || s,
            this.onError = e.onError || s,
            this.billNo = e.billNo || "",
            this.portalNo = e.portalNo || "",
            this.resultQueryVm = null,
            this.buyType = e.buyType,
            this.hfMode = e.hfMode,
            this.realServiceCode = e.realServiceCode,
            this.feeType = e.feeType,
            this.provideUin = e.provideUin,
            !this.billNo)
                throw Error("billNo must be provide");
            this.init()
        }
        var o = t(4)
          , s = (t(1),
        o.fn.emptyFunc)
          , a = t(80576922);
        o.fn.extend(i.prototype, {
            "init": function() {
                this.initConfig(),
                this.mount(a.create(this.configName))
            },
            "initConfig": function() {
                var e = this
                  , n = this.cgi;
                this.setConfig({
                    "times": 60,
                    "queryTimeout": 10,
                    "onInit": function(n) {
                        e.resultQueryVm = n
                    },
                    "onQuery": function(t) {
                        n.mobileGetCardBillInfo({
                            "real_servicecode": e.realServiceCode,
                            "fee_type": e.feeType,
                            "provide_uin": e.provideUin,
                            "billno": e.billNo,
                            "type": "1",
                            "hfpay_pay_flow": e.hfMode
                        }, function(e) {
                            if (~~e.ret)
                                t.queryDone(a.ENUM_STATUS.PENDING);
                            else
                                switch (e.state) {
                                case 3:
                                case 5:
                                    t.setInfo("对不起，支付失败"),
                                    t.setSubInfo(""),
                                    t.queryDone(a.ENUM_STATUS.FAIL);
                                    break;
                                case 4:
                                    t.setInfo("支付成功"),
                                    t.setSubInfo(""),
                                    t.queryDone(a.ENUM_STATUS.SUCCESS);
                                    break;
                                case 1:
                                case 2:
                                case 6:
                                default:
                                    t.setSubInfo(""),
                                    t.queryDone(a.ENUM_STATUS.PENDING)
                                }
                        }
                        .bind(this))
                    },
                    "onSuccess": function(n) {
                        e.onSuccess()
                    },
                    "onPending": function(n) {
                        e.onPending()
                    },
                    "onNoResult": function(n) {
                        n.setStatus(a.ENUM_STATUS.ERROR),
                        n.setInfo("未查询到话费支付结果"),
                        e.onNoResult(n.getInfo(), n.getSubInfo())
                    },
                    "onFail": function(n) {
                        e.onFail(n.getInfo(), n.getSubInfo())
                    }
                })
            },
            "onDestroy": function() {
                o.fn.stop(),
                this.resultQueryVm.destroy(),
                this.resultQueryVm = null,
                this.unmount()
            },
            "destroy": function() {
                this.onDestroy()
            }
        }),
        e.exports = i
    },
    "106745080": function(e, n) {
        e.exports = {
            "Type": {
                "HOSTING": "default",
                "NOHOSTING": "duanyou",
                "MOBILE": "shouyou"
            },
            "CheckType": {
                "NOCheck": 0,
                "CHECK": 1,
                "CHECKRole": 2,
                "SELECTRole": 3
            }
        }
    },
    "108535814": function(e, n, t) {
        var i = t(56711316)
          , o = t(4)
          , s = t(54698897)
          , a = t(1);
        t(77769056);
        var r = t(100835382)
          , c = t(17)
          , l = t(11)
          , u = t(119561448)
          , d = t(98010485)
          , p = t(104491903)
          , h = (t(109735088),
        t(84811753))
          , f = t(75748174)
          , m = o.fn.getParam("inApp");
        t(68682076);
        var g = function(e, n, t) {
            r.apply(this, arguments),
            this.filterBankType = "bank",
            this.cacheBankKey = "selected.bank",
            this.cacheBankData = this.getCookie(),
            this.portal_serial_no = null,
            this.payProxy = window.location.protocol + "//" + window.location.host + "/midas/minipay_v2/views/public/pay-bank.php",
            this.amount = 0,
            this.saveTimout = null,
            this.payBankUrl = null,
            this.payBankUrlTimeout = null,
            this.init()
        }
          , v = {
            "init": function() {
                this.initVm(),
                this.calculatePrice(),
                this.fetchTargetUin(),
                this.fetchAmount()
            },
            "getDiscount": function() {
                return .95
            },
            "calculatePrice": function() {
                var e = this.store.getPrice().price;
                this.price = this.store.getPrice(o.discount.checkHasDiscount(e, this.channelObj.channel) ? this.channelObj.discount : void 0, this.coupon).price,
                this.vm.price = this.price
            },
            "fetchAmount": function() {
                this.vm.amount = this.store.getAmount(),
                this.amount = this.store.getAmount()
            },
            "fetchTargetUin": function() {
                this.targetUin = this.store.getTargetInfo().uin
            },
            "onChange": function() {
                this.fetchTargetUin(),
                this.fetchAmount(),
                this.refreshCoupon(),
                this.calculatePrice(),
                this.debounceOrder()
            },
            "debounceOrder": function() {
                if (this.payBankUrl = null,
                this.payBankUrlTimeout && (clearTimeout(this.payBankUrlTimeout),
                this.payBankUrlTimeout = null),
                this.saveTimout && (this.saveTimout.stop(0),
                this.saveTimout = null,
                this.vm.paying = !1,
                this.unlock()),
                !this.store.isInterfaceDisabled() && 0 != this.amount) {
                    var e = this;
                    this.vm.paying = !0,
                    this.lock(),
                    this.saveTimout = new l.Timeout({
                        "time": .7,
                        "timeUp": function() {
                            e.vm.paying = !1,
                            e.unlock(),
                            e.saveTimout = null,
                            e.order({}, function(n, t) {
                                e.payBankUrl = n,
                                e.payBankUrlTimeout = setTimeout(function() {
                                    e.debounceOrder()
                                }, 1e3 * t)
                            })
                        }
                    })
                }
            },
            "order": function(e, n) {
                e = e || {};
                var t = this
                  , i = this.bankObj && this.bankObj.bank
                  , a = this.bankObj && this.bankObj.curCardType
                  , r = this.bankObj && this.bankObj.curBankType
                  , c = s.GetBankSubChannel(this.store.cgi);
                "82" === c && (i = i.toUpperCase());
                var l = i.toLowerCase() + "_" + ("credit" === a ? "2" : "1") + ("B2B" === r ? "_1" : "_2")
                  , d = {
                    "uuid": this.uuid,
                    "pushtype": "NodeJS",
                    "pay_method": "pcbank:" + c,
                    "bank_type": i + "_" + ("credit" == a ? "2" : "1") + ("B2B" === r ? "_1" : "_2")
                };
                o.fn.extend(d, e),
                this.setCookie(l);
                var p = function() {
                    var e = {
                        "proxy": !0
                    };
                    t.lock(),
                    t.vm.paying = !0,
                    u.show({
                        "opacity": "0"
                    }),
                    t.store.buy(d, function(e) {
                        if (t.unlock(),
                        t.vm.paying = !1,
                        u.hide(),
                        !~~e.ret) {
                            var i = t.store.getSession().getSessionParam()
                              , s = e.jump;
                            return t.lock(),
                            t.vm.paying = !0,
                            u.show({
                                "opacity": "0"
                            }),
                            t.getShortUrl(s, function(e) {
                                if (t.unlock(),
                                t.vm.paying = !1,
                                u.hide(),
                                e.status) {
                                    var a = o.fn.addParam({
                                        "short_url": encodeURIComponent(e.shortUrl),
                                        "openid": encodeURIComponent(i.openid),
                                        "openkey": encodeURIComponent(i.openkey),
                                        "rc_params": encodeURIComponent(o.req.serializeParam(t.store.getRcRestrictParams()))
                                    }, t.payProxy);
                                    n(a, 1 * e.validTime || 600),
                                    t.report("bank.qrcodeSuccess", {
                                        "resultinfo": {
                                            "webSaveLength": s.length
                                        }
                                    })
                                } else
                                    t.store.onFail(e.res),
                                    t.report("bank.qrcodeFail", {
                                        "resultinfo": {
                                            "webSaveLength": s.length,
                                            "ret": e.res && e.res.ret || "",
                                            "err_code": e.res && e.res.err_code || ""
                                        }
                                    })
                            }, !0),
                            !0
                        }
                    }, e)
                };
                p()
            },
            "setCookie": function(e) {
                var n = this.convertStrToObj(o.cookie.get(this.cacheBankKey));
                n[this.store.getSession().getSessionParam().openid] = e,
                o.cookie.set(this.cacheBankKey, this.convertObjToStr(n))
            },
            "getCookie": function() {
                var e = this.convertStrToObj(o.cookie.get(this.cacheBankKey))
                  , n = e[this.store.getSession().getSessionParam().openid]
                  , t = d(n);
                return t.bank && (t.bankType = n),
                t
            },
            "getVmConfig": function() {
                var e = this;
                return o.fn.extend({
                    "$id": "bank-controller",
                    "price": this.price,
                    "amount": this.amount,
                    "$skipArray": ["bankData"],
                    "$computed": {
                        "bankClass": {
                            "get": function() {
                                if (this.bank)
                                    return "icon-" + this.bank
                            }
                        }
                    },
                    "disableSubmit": !0,
                    "paying": !1,
                    "bankData": a.mix({
                        "filterType": this.filterBankType,
                        "haspaytype": !1
                    }, this.cacheBankData),
                    "tips": "",
                    "pay": function(n) {
                        if (n.preventDefault(),
                        !e.isLocked())
                            return e.reportUser("pay.click"),
                            e.store.isInterfaceDisabled() ? void e.store.emit("channelDataChange", new h(f)) : void (0 != e.amount && e.payBankUrl && ("1" != m ? o.openWindow(e.payBankUrl) : c.openWindow(e.payBankUrl),
                            e.store.changePage("subChannel", a.mix({
                                "channelObj": e.channelObj,
                                "portal_serial_no": e.portal_serial_no,
                                "mode": r.MODE.COMPLETE,
                                "price": e.price,
                                "coupon": e.coupon,
                                "store": e.store
                            }, {
                                "uuid": e.uuid
                            }, e.bankObj)),
                            e.store.emit(p, new h(p,{
                                "show": !1
                            }))))
                    },
                    "onSelectedBank": this.onSelectedBank.bind(this)
                }, this.getCouponVmConfig(), this.getTermsVmConfig(), this.getPubVmConfig())
            },
            "convertObjToStr": function(e) {
                var n = []
                  , t = null;
                return a.each(e, function(e, t) {
                    e && t && n.push(String.format("{key}={value}", {
                        "key": e,
                        "value": encodeURIComponent(t)
                    }))
                }),
                n.length > 0 && (t = n.join("&")),
                t
            },
            "convertStrToObj": function(e) {
                var n, t = {}, i = [];
                return e && e.length > 0 && (i = e.split("&"),
                a.each(i, function(e, i) {
                    n = i.split("="),
                    t[n[0]] = decodeURIComponent(n[1])
                })),
                t
            },
            "onSelectedBank": function(e) {
                this.vm && (this.vm.tips = "",
                this.vm.disableSubmit = !1,
                this.bankObj = e,
                this.bankObj.curPayType = this.filterBankType,
                "B2B" == this.bankObj.curBankType ? this.bankObj.bankType = window.__B2B_BANK_CONFIG[this.bankObj.bank][this.bankObj.curCardType][this.bankObj.curPayType] : this.bankObj.bankType = window.__BANK_CONFIG[this.bankObj.bank][this.bankObj.curCardType][this.bankObj.curPayType],
                this.debounceOrder())
            },
            "initVm": function() {
                this.vm = a.define(this.getVmConfig())
            },
            "onDestroy": function() {
                this.portal_serial_no = null,
                this.removeListener(),
                this.payBankUrlTimeout && (clearTimeout(this.payBankUrlTimeout),
                this.payBankUrlTimeout = null),
                this.saveTimout && this.saveTimout.stop(0),
                this.destroy()
            }
        };
        o.inherits(g, r),
        o.fn.extend(g.prototype, v),
        g.create = function(e, n, t) {
            return new g(e,n,t)
        }
        ,
        g.getTemplate = function(e) {
            return i()
        }
        ,
        e.exports = g
    },
    "108898004": function(e, n, t) {
        function i(e) {
            if (this.constructor == i)
                throw Error("you can not direct initialize AbstractResult");
            this.opt = e,
            this.modifyTitle = "undefined" == typeof e.modifyTitle || e.modifyTitle,
            this.orderInfo = e.orderInfo,
            this.priceInfo = e.priceInfo,
            this.params = e.params,
            this.cgi = e.cgi,
            this.session = e.session,
            this.subSession = e.subSession,
            this.type = e.type || "payres",
            this.provide_uin = e.provide_uin,
            this.channel = e.channel,
            "string" == typeof this.channel && (this.channeName = a.channels[this.channel]),
            this.status = e.status || i.ENUM_STATUS.PENDING,
            this.portalNo = e.portalNo,
            "false" == o.fn.getParam("showFinishButton") ? this._showFinish = !1 : this._showFinish = "undefined" == typeof e.showFinish || e.showFinish,
            this.onAction = e.onAction,
            this.finishActionType = this.onAction ? "custom" : e.actionType || "close",
            this.titleTxt = e.titleTxt || "支付结果",
            this.errorCode = e.errorCode || null,
            this.vm = null,
            this.fireEvents = !1,
            this.checkStatus(this.status),
            f.setStatus(this.status),
            this.disableContext = function(e) {
                return e.preventDefault && e.preventDefault(),
                e.stopPropagation && e.stopPropagation(),
                !1
            }
            ,
            s(window).bind("contextmenu", this.disableContext)
        }
        var o = t(4)
          , s = t(1)
          , a = t(49140953)
          , r = t(48695175)
          , c = t(52088519)
          , l = t(106121617)
          , u = t(113871490)
          , d = t(12)
          , p = t(10)
          , h = t(112745811)
          , f = t(72876602)
          , m = t(17);
        i.ENUM_STATUS = {
            "SUCCESS": "success",
            "FAIL": "fail",
            "ERROR": "error",
            "PENDING": "waiting"
        },
        o.fn.extend(i.prototype, {
            "onDestroy": function() {
                s.nextTick(function() {
                    try {
                        this.queryInstance && this.queryInstance.onDestroy(),
                        this.customInstance && this.customInstance.onDestory()
                    } catch (e) {}
                    this.vmConfig = null,
                    this.vm = null,
                    this.customInstance = null,
                    this.queryInstance = null,
                    s(window).unbind("contextmenu", this.disableContext),
                    this.disableContext = null
                }
                .bind(this))
            },
            "showFinish": function() {
                this._showFinish = this.vm.showFinish = !0
            },
            "hideFinish": function() {
                this._showFinish = this.vm.showFinish = !1
            },
            "getAmount": function() {
                return this.orderInfo.count
            },
            "reportUser": function(e, n) {
                p.user.action("result", e, n)
            },
            "report": function(e, n) {
                p(String.format("result.{iformat}", {
                    "iformat": e
                }), n)
            },
            "getVmConfig": function() {
                var e = this
                  , n = this.status == i.ENUM_STATUS.FAIL || this.status == i.ENUM_STATUS.ERROR
                  , t = this.opt.displayInfo || a.TEXT.COMMONERRORTXT;
                return this.vmConfig = {
                    "$id": "result-detail",
                    "status": this.status,
                    "isQuery": this.opt.isQuery || !1,
                    "isCustom": s.isFunction(this.opt.customFactory),
                    "queryContainer": "",
                    "customContainer": "",
                    "bottomText": "",
                    "info": n ? t : this.opt.displayInfo,
                    "subInfo": this.opt.subInfo,
                    "tips": "",
                    "market": this.opt.info,
                    "mcardQueryConfig": {},
                    "hfpayQueryConfig": {},
                    "signQueryConfig": {},
                    "buttonTxt": this.opt.buttonTxt || "确定",
                    "showFinish": this._showFinish,
                    "back": function() {
                        d.back()
                    },
                    "finish": function(n, t) {
                        n.stopPropagation(),
                        n.preventDefault(),
                        !e.checkStatus(t) && m.trigger("noresult");
                        var i = {
                            "status": e.status,
                            "channel": f.getChannel()
                        };
                        switch (e.finishActionType) {
                        case "back":
                            e.reportUser("back.click", i),
                            e.notifyHeader("reset"),
                            d.go("order");
                            break;
                        case "custom":
                            e.reportUser("custom.click", i),
                            e.onAction();
                            break;
                        case "refresh":
                            e.reportUser("refresh.click", i),
                            location.reload();
                            break;
                        default:
                            e.reportUser("finish.click", i),
                            m.notify("close")
                        }
                    }
                }
            },
            "checkStatus": function(e) {
                if (e === i.ENUM_STATUS.SUCCESS)
                    return this.fireEvents || (m.trigger("success"),
                    this.fireEvents = !0),
                    !0;
                if (e === i.ENUM_STATUS.FAIL)
                    return this.fireEvents || (m.trigger("error", this.errorCode),
                    this.fireEvents = !0),
                    !0;
                if (e === i.ENUM_STATUS.ERROR) {
                    if (!this.fireEvents) {
                        var n = this.opt.res || {};
                        m.trigger("error", String(n.err_code || n.ret)),
                        this.fireEvents = !0
                    }
                    return !0
                }
                return !1
            },
            "setFinishActionType": function(e) {
                this.finishActionType = e
            },
            "getFinishActionType": function() {
                return this.finishActionType
            },
            "setAmount": function(e) {
                this.vm.count = e
            },
            "setInfo": function(e) {
                this.vm.info = e
            },
            "setTips": function(e) {
                this.vm.tips = e
            },
            "setSubInfo": function(e) {
                this.vm.subInfo = e
            },
            "setMarket": function(e) {
                this.vm.market = e
            },
            "setStatus": function(e) {
                f.setStatus(e),
                this.vm && (this.vm.status = this.status = e,
                this.notifyHeader())
            },
            "notifyHeader": function(e) {
                this.modifyTitle && m.trigger("headerDataReady", {
                    "title": this.titleTxt
                })
            },
            "initVm": function() {
                this.vm = s.define(this.getVmConfig()),
                this.opt.isQuery ? this.channel == a.channels.mcard.payMethod ? this.mcardQuery() : this.channel == a.channels.hfpay.payMethod ? this.hfpayQuery() : this.store.type === h.MONTH && this.store.isContinuousMonth() && this.signQuery() : s.isFunction(this.opt.customFactory) && this.customResult(),
                this.notifyHeader(),
                this.onVmInit(),
                this.report("pv", {
                    "resultinfo": {
                        "status": this.status,
                        "channel": f.getChannel()
                    }
                }),
                f.setPage("result"),
                s(o.Id("cp_loading_")).css({
                    "display": "none"
                }),
                p.user.action("page", "result", {
                    "status": this.status
                })
            },
            "onVmInit": s.noop,
            "onQuerySuccess": s.noop,
            "onQueryPending": s.noop,
            "onQueryError": s.noop,
            "onQueryFail": s.noop,
            "onQueryNoResult": s.noop,
            "onCustomSuccess": s.noop,
            "onCustomNoResult": s.noop,
            "onCustomError": s.noop,
            "onCustomFail": s.noop,
            "mcardQuery": function() {
                var e = this;
                e.report("mcard.pv"),
                this.queryInstance = new c({
                    "mount": function(n) {
                        e.vm.queryContainer = n
                    },
                    "unmount": function() {
                        e.vm.queryContainer = null,
                        e.vm.mcardQueryConfig = {},
                        e.titleTxt = "支付结果",
                        e.notifyHeader()
                    },
                    "provide_uin": this.provide_uin,
                    "cgi": this.cgi,
                    "billNo": this.opt.billNo,
                    "portalNo": this.portalNo,
                    "buyType": this.opt.buyType,
                    "price": this.opt.priceInfo.price,
                    "isNewMcard": "1" == this.orderInfo.mcard_mode,
                    "configName": "mcardQueryConfig",
                    "setConfig": function(n) {
                        e.vm.mcardQueryConfig = n
                    },
                    "onSuccess": function(n, t, o) {
                        e.report("mcard.success.pv"),
                        e.setStatus(i.ENUM_STATUS.SUCCESS),
                        e.vm.isQuery = !1,
                        this.destroy(),
                        e.setTips(t),
                        e.onQuerySuccess(n, t),
                        o && o.realAmount && e.setAmount(o.realAmount),
                        n && e.setInfo(n)
                    },
                    "onPending": function() {
                        e.report("mcard.pending.pv"),
                        e.onQueryPending()
                    },
                    "onNoResult": function(n, t) {
                        e.report("mcard.noresult.pv"),
                        e.setStatus(i.ENUM_STATUS.ERROR),
                        e.vm.isQuery = !1,
                        t && e.setSubInfo(t),
                        n && e.setInfo(n),
                        this.destroy(),
                        e.onQueryNoResult(n, t)
                    },
                    "onFail": function(n, t) {
                        e.report("mcard.fail.pv"),
                        e.setStatus(i.ENUM_STATUS.FAIL),
                        e.vm.isQuery = !1,
                        t && e.setSubInfo(t),
                        n && e.setInfo(n),
                        this.destroy(),
                        e.onQueryFail(n, t)
                    },
                    "onError": function(n, t, o) {
                        e.vm.isQuery = !1,
                        e.report("mcard.error.pv"),
                        e.setStatus(i.ENUM_STATUS.ERROR),
                        this.destroy(),
                        e.onQueryError(n, t),
                        t && e.setSubInfo(t),
                        o && o.mcardDetail && e.setTips(o.mcardDetail)
                    },
                    "onContinue": function() {
                        e.report("mcard.continue.pv"),
                        o.lang.isFunction(e.shouldMcardContinue) && !e.shouldMcardContinue() || e.vm && (e.vm.buttonTxt = "继续充值",
                        e.setFinishActionType("refresh"))
                    }
                })
            },
            "customResult": function() {
                this.report("custom.pv");
                var e = this;
                this.customInstance = this.opt.customFactory({
                    "cgi": this.cgi,
                    "mount": function(n) {
                        e.vm.customContainer = n
                    },
                    "unmount": function() {
                        e.vm.customContainer = null,
                        e.vm.mcardQueryConfig = {},
                        e.titleTxt = "支付结果",
                        e.notifyHeader()
                    },
                    "onSuccess": function(n, t) {
                        e.report("custom.success.pv"),
                        e.setStatus(i.ENUM_STATUS.SUCCESS),
                        e.vm.isCustom = !1,
                        this.destroy(),
                        t && e.setTips(t),
                        n && e.setInfo(n),
                        e.initialize && e.initialize(),
                        e.onCustomSuccess(n, t)
                    },
                    "onNoResult": function(n, t) {
                        e.report("custom.noresult.pv"),
                        e.setStatus(i.ENUM_STATUS.ERROR),
                        e.vm.isCustom = !1,
                        this.destroy(),
                        t && e.setTips(t),
                        n && e.setInfo(n),
                        e.onCustomNoResult(n, t)
                    },
                    "onFail": function(n, t) {
                        e.report("custom.fail.pv"),
                        e.setStatus(i.ENUM_STATUS.FAIL),
                        e.vm.isCustom = !1,
                        this.destroy(),
                        t && e.setTips(t),
                        n && e.setInfo(n),
                        e.onCustomFail(n, t)
                    },
                    "onError": function(n, t) {
                        e.vm.isQuery = !1,
                        e.report("custom.error.pv"),
                        e.setStatus(i.ENUM_STATUS.ERROR),
                        e.vm.isCustom = !1,
                        this.destroy(),
                        t && e.setTips(t),
                        n && e.setInfo(n),
                        e.onCustomError(n, t)
                    }
                })
            },
            "hfpayQuery": function() {
                var e = this;
                e.report("hfpay.pv"),
                this.queryInstance = new l({
                    "mount": function(n) {
                        e.vm.queryContainer = n
                    },
                    "unmount": function() {
                        e.vm.queryContainer = null,
                        e.vm.hfpayQueryConfig = {},
                        e.titleTxt = "支付结果",
                        e.notifyHeader()
                    },
                    "provide_uin": this.provide_uin,
                    "cgi": this.cgi,
                    "billNo": this.opt.billNo,
                    "portalNo": this.portalNo,
                    "hfMode": this.opt.hfMode,
                    "buyType": this.opt.buyType,
                    "provideUin": this.provide_uin,
                    "configName": "hfpayQueryConfig",
                    "setConfig": function(n) {
                        e.vm.hfpayQueryConfig = n
                    },
                    "onSuccess": function() {
                        e.report("hfpay.success.pv"),
                        e.setStatus(i.ENUM_STATUS.SUCCESS),
                        e.vm.isQuery = !1,
                        this.destroy(),
                        e.onQuerySuccess()
                    },
                    "onPending": function() {
                        e.report("hfpay.pending.pv"),
                        e.onQueryPending()
                    },
                    "onNoResult": function(n, t) {
                        e.report("hfpay.noresult.pv"),
                        e.setStatus(i.ENUM_STATUS.ERROR),
                        e.vm.isQuery = !1,
                        t && e.setSubInfo(t),
                        n && e.setInfo(n),
                        this.destroy(),
                        e.onQueryNoResult(n, t)
                    },
                    "onFail": function(n, t) {
                        e.report("hfpay.fail.pv"),
                        e.setStatus(i.ENUM_STATUS.FAIL),
                        e.vm.isQuery = !1,
                        t && e.setSubInfo(t),
                        n && e.setInfo(n),
                        this.destroy(),
                        e.onQueryFail(n, t)
                    },
                    "onError": function(n) {
                        e.report("hfpay.error.pv"),
                        e.setStatus(i.ENUM_STATUS.ERROR),
                        e.vm.isQuery = !1,
                        subInfo && e.setSubInfo(subInfo),
                        n && e.setInfo(n),
                        this.destroy(),
                        e.onQueryError(n)
                    }
                })
            },
            "signQuery": function() {
                var e = this;
                e.report("sign.pv"),
                this.queryInstance = new u({
                    "mount": function(n) {
                        e.vm.queryContainer = n
                    },
                    "unmount": function() {
                        e.vm.queryContainer = null,
                        e.vm.signQueryConfig = {},
                        e.notifyHeader()
                    },
                    "provide_uin": this.provide_uin,
                    "cgi": this.cgi,
                    "billNo": this.opt.billNo,
                    "portalNo": this.portalNo,
                    "buyType": this.opt.buyType,
                    "provideUin": this.provide_uin,
                    "configName": "signQueryConfig",
                    "channel": this.channel,
                    "setConfig": function(n) {
                        e.vm.signQueryConfig = n
                    },
                    "onSuccess": function() {
                        e.report("sign.success.pv"),
                        e.titleTxt = "支付结果",
                        e.setStatus(i.ENUM_STATUS.SUCCESS),
                        e.vm.isQuery = !1,
                        this.destroy(),
                        e.onQuerySuccess()
                    },
                    "onPending": function() {
                        e.report("sign.pending.pv"),
                        e.onQueryPending()
                    },
                    "onNoResult": function(n, t) {
                        e.titleTxt = "支付结果",
                        e.report("sign.noresult.pv"),
                        e.setStatus(i.ENUM_STATUS.FAIL),
                        e.vm && (e.vm.info = n,
                        e.vm.subInfo = t,
                        e.vm.isQuery = !1,
                        e.vm.buttonTxt = "重新购买",
                        e.setFinishActionType("refresh")),
                        this.destroy(),
                        e.onQueryNoResult(n, t)
                    },
                    "onFail": function(n, t) {
                        e.titleTxt = "支付结果",
                        e.report("sign.fail.pv"),
                        e.setStatus(i.ENUM_STATUS.FAIL),
                        e.vm.isQuery = !1,
                        this.destroy(),
                        e.onQueryFail(n, t)
                    },
                    "onError": function(n) {
                        e.titleTxt = "支付结果",
                        e.report("sign.error.pv"),
                        e.vm && (e.vm.info = "连续包月签约成功，但支付失败，请重新支付",
                        e.vm.subInfo = ""),
                        e.setStatus(i.ENUM_STATUS.ERROR),
                        e.vm.isQuery = !1,
                        this.destroy(),
                        e.onQueryError(n)
                    },
                    "onRetry": function() {
                        e.titleTxt = "支付结果",
                        e.vm && (e.vm.buttonTxt = "重新支付",
                        e.setFinishActionType("refresh"))
                    }
                })
            }
        }),
        i.getTemplate = function(e) {
            return e = e || {},
            r(e)
        }
        ,
        i.create = function(e) {
            return new i(e)
        }
        ,
        e.exports = i
    },
    "109181847": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div ms-controller="hfpay-controller-simple" class="telephone-fee-pay-area">\n    <p ms-if="warnMsg" class="tips icon-tips warn" style="position: relative">\n        <i class="icon-warn"></i> {{warnMsg}}\n    </p>\n    <div ms-if="!warnMsg">\n        <div class="channel-detail-oper-area">\n            <div class="input-areas">\n                <div class="input-row">\n                    <div class="form-group" style="display: block;width: 240px">\n                        <ms:input on-init="getPhoneNumVm" maxlength="11" on-validate="onValidatePhoneNum" config="phoneNumConfig" on-change="onPhoneNumChange"\n                            placeholder="请输入手机号码"></ms:input>\n                    </div>\n                    <p class="tips icon-tips warn" style="position:absolute" ms-if="phoneValidateMsg">\n                        <i class="icon-warn"></i> {{phoneValidateMsg}}\n                    </p>\n                </div>\n            </div>\n            <div class="oper-area">\n                <div class="oper-to-pay">\n                    <a ms-on-click="handleCheck" ms-class="btn btn-default"  ms-class-1="loading:disableSubmit" href="#">\n                        <span ms-visible="!disableSubmit">下一步</span>\n                        <span><i class="icon-btn-loading"></i></span>\n                    </a>\n                </div>\n                <p class="tips icon-tips info" ms-if="hfTips"><i class="icon-txt"></i>{{hfTips}}</p>\n            </div>\n        </div>\n    </div>\n</div>';
            return __p
        }
    },
    "109718908": function(module, exports) {
        module.exports = function(obj) {
            function print() {
                __p += __j.call(arguments, "")
            }
            obj || (obj = {});
            var __t, __p = "", __j = Array.prototype.join;
            with (obj)
                __p += '<div ms-controller="' + (null == (__t = controller) ? "" : __t) + '" ms-class="input-areas:isNested" style="position: relative">\n\n    ',
                isNested || (__p += '\n  <!--  <div class="left-money"> </div>-->\n        <div class="verify-left-money">\n            <div class="form-inline">\n                '),
                __p += '\n                <div class="form-group verify-code-form-group">\n                    <label style="width: 130px">\n                        <ms:input width="110px" on-init="getVerifyInputVm" placeholder="请输入验证码"\n                                  config="config"\n                                  on-validate="onValidate"\n                                  on-change="onChange"\n                                  on-input="onInput"\n                                  ms-attr-extra-class="{{isNested? \'qrcode-input\':\'\'}}"\n                    ></ms:input>\n                    </label>\n                    <a class="verify-code-img" href="javascript:void(0);" ms-on-click="changeVerifyCode">\n                        <img ms-if="verifyCodePic" ms-attr-src="verifyCodePic" ms-attr-alt="verifyCodePic" ma-attr-title="verifyCodePic">\n                    </a>\n                    <a ms-class="{{isNested? \'form-input-append-txt\':\'change-qrcode\'}}"\n                       ms-on-click="changeVerifyCode" href="javascript:void(0);">换一换</a>\n                </div>\n                <!--<p class="tips icon-tips warn" ms-if="validateFailMsg" ms-attr-style="{{isNested? \'position:absolute;top:0;left:310px\':\'\'}}">-->\n                    <!--<i class="icon-warn"></i>-->\n                    <!--{{validateFailMsg}}</p>-->\n                <div class="btn-wrap" ms-if="!isNested">\n                    <a href="#" ms-on-click="onConfirm" class="btn btn-default btn-s">确认</a>\n                    <a href="#" ms-on-click="onCancel" class="btn btn-primary btn-s">取消</a>\n                </div>\n                ',
                isNested || (__p += "\n            </div>\n        </div>\n\n    "),
                __p += "\n\n</div>";
            return __p
        }
    },
    "109735088": function(e, n, t) {
        var i = t(4)
          , o = t(1)
          , s = t(102521382)
          , a = t(10)
          , r = i.fn.getParams();
        "itopid" === r["session_id"] && i.fn.safeGet(window._SERVER_DATA, "realSession.real_session_id") && i.fn.safeGet(window._SERVER_DATA, "realSession.real_session_type") && (r["session_id"] = i.fn.safeGet(window._SERVER_DATA, "realSession.real_session_id"),
        r["session_type"] = i.fn.safeGet(window._SERVER_DATA, "realSession.real_session_type"));
        var c = function(e) {
            for (var n = 0, t = e.length; n < t; n++)
                if (!r[e[n]])
                    return {
                        "res": !1,
                        "filed": e[n],
                        "value": r[e[n]]
                    };
            return {
                "res": !0
            }
        }
          , l = function(e) {
            var n = ["openid", "openkey", "session_id", "session_type"];
            return e && e.checkFiled && e.checkFiled instanceof Array && (n = n.concat(e.checkFiled)),
            c(n)
        }
          , u = "uin" === r["session_id"] && "skey" === r["session_type"]
          , d = "openid" === r["session_id"] && "kp_actoken" === r["session_type"]
          , p = "openid" === r["session_id"] && "openkey" === r["session_type"]
          , h = "uin" === r["session_id"] && /pskey/.test(r["session_type"])
          , f = "openid" === r["session_id"] && "kp_accesstoken" === r["session_type"]
          , m = "uin" === r["session_id"] && /vask/.test(r["session_type"])
          , g = "uin" === r["session_id"] && "vask_27" === r["session_type"]
          , v = "hy_gameid" === r["session_id"] && "wc_actoken" === r["session_type"]
          , b = "hy_gameid" === r["session_id"] && "st_dummy" === r["session_type"]
          , y = "hy_gameid" === r["session_id"] && "st_sogou" === r["session_type"];
        n.getLoginStatus = function() {
            return {
                "qq1": u,
                "qq2": d,
                "qq3": p,
                "pskey": h,
                "qq": u || d || p || h || m || f || g,
                "accesstoken": f,
                "ctlogin": m,
                "ptlogin": u,
                "qqconnect": d,
                "openid": p,
                "pretty": g,
                "wechat": v,
                "none": b,
                "sogou": y
            }
        }
        ,
        n.getLoginStatusFromCookie = function() {
            var e = +i.cookie.get("uin").replace(/[^\d]/g, "")
              , n = i.cookie.get("skey");
            return e && e > 1e3 && n && n.length > 5 ? {
                "qq": !0,
                "uin": e,
                "skey": n
            } : null
        }
        ,
        n.getPskeyLoginStatusFromCookie = function() {
            var e = +i.cookie.get("uin").replace(/[^\d]/g, "")
              , n = i.cookie.get("p_skey");
            return e && e > 1e3 && n && n.length > 5 ? {
                "qq": !0,
                "openid": e,
                "openkey": n,
                "session_id": "uin",
                "session_type": "pskey_307"
            } : null
        }
        ,
        n.checkLoginInUrl = function(e) {
            function n() {
                location.replace(i.fn.addParam({
                    "openid": r.openid,
                    "openkey": r.openkey,
                    "session_id": r.session_id,
                    "session_type": r.session_type
                }, location.href))
            }
            if (!(r.openid && r.openkey && r.session_id && r.session_type)) {
                var t = __midasStaticConfig_midas_webpay.itemMap.webpay._PSKEY_WHITELIST;
                if (t && t.indexOf(r["appid"]) > -1)
                    return r.session_id = "uin",
                    r.session_type = "pskey_307",
                    i.cookie.get("p_uin") && i.cookie.get("p_skey") ? (r.openid = +i.cookie.get("p_uin").replace(/[^\d]/g, ""),
                    r.openkey = i.cookie.get("p_skey"),
                    void n()) : (o.getScript(location.protocol + "//xui.ptlogin2.qq.com/js/ptlogin_v1.js", function() {
                        s.setCallBack({
                            "hideClose": !0,
                            "daid": 307,
                            "onSuccess": function() {
                                r.openid = +i.cookie.get("p_uin").replace(/[^\d]/g, ""),
                                r.openkey = i.cookie.get("p_skey"),
                                n()
                            }
                        }),
                        s.show()
                    }),
                    void a("pskey.login.pv"));
                if (r.session_id = "uin",
                r.session_type = "skey",
                !i.cookie.get("uin") || !i.cookie.get("skey"))
                    return void o.getScript(location.protocol + "//xui.ptlogin2.qq.com/js/ptlogin_v1.js", function() {
                        s.setCallBack({
                            "hideClose": !0,
                            "onSuccess": function() {
                                n()
                            }
                        }),
                        s.show()
                    })
            }
            e && e()
        }
        ,
        n.isWxBindQQ = function(e) {
            var n = e.info;
            return 1 == n.wc_bind_qq
        }
        ,
        n.validateBaseInfo = l;
        var _ = !1;
        i.cookie.set("midas_cookie_samesite_flag", "1"),
        "1" == i.cookie.get("midas_cookie_samesite_flag") && (_ = !0),
        n.canUsePTLoginCookie = _
    },
    "109807897": function(e, n, t) {
        function i() {
            return c || (c = new l.Promise(function(e) {
                var n = (new Date).getTime();
                a.req.loadScript("https://kepler-cn.captcha.qq.com/tencent-kepler.js", function() {
                    var t = (new Date).getTime() - n
                      , i = !!window.TencentKepler;
                    e({
                        "loadTime": t,
                        "loaded": i
                    }),
                    i ? r("kepler.load", {
                        "resultinfo": {
                            "times": t
                        }
                    }) : r("kepler.loadFail", {
                        "resultinfo": {
                            "times": t
                        }
                    })
                })
            }
            )),
            c
        }
        function o(e) {
            return m && (((new Date).getTime() - f) / 1e3 > u || h >= d) && (h = 0,
            f = 0,
            m = null),
            m || (h = 0,
            f = (new Date).getTime(),
            m = i().then(function(e) {
                return new l.Promise(function(n) {
                    if (!e.loaded)
                        return void n(e);
                    var t = (new Date).getTime();
                    TencentKepler.predict({
                        "appid": "9768763",
                        "callback": function(i) {
                            var o = (new Date).getTime() - t;
                            n({
                                "loadTime": e.loadTime,
                                "loaded": e.loaded,
                                "predictTime": o,
                                "ticket": i || ""
                            }),
                            i ? r("kepler.init.result", {
                                "resultinfo": {
                                    "times": o
                                }
                            }) : r("kepler.init.resultFail", {
                                "resultinfo": {
                                    "times": o
                                }
                            })
                        }
                    })
                }
                )
            })),
            e ? null : (h++,
            m)
        }
        function s(e) {
            var n = null
              , t = function() {
                n && (clearTimeout(n),
                n = null),
                e = null
            };
            o().then(function(n) {
                e && e(n.ticket || "default"),
                t()
            }),
            n = setTimeout(function() {
                e && e("default"),
                t(),
                r("kepler.timeout")
            }, p)
        }
        var a = t(4)
          , r = t(10);
        t(5);
        var c, l = t(1), u = a.fn.safeGet(window.__midasStaticConfig_midas_webpay, "itemMap.webpay.kepler_ticket_max_age", 600), d = a.fn.safeGet(window.__midasStaticConfig_midas_webpay, "itemMap.webpay.kepler_ticket_reuse_limit", 10), p = a.fn.safeGet(window.__midasStaticConfig_midas_webpay, "itemMap.webpay.get_kepler_timeout", 5e3), h = 0, f = 0, m = null;
        e.exports = {
            "getTicket": s,
            "keplerPredict": o
        }
    },
    "109895087": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div ms-controller="' + (null == (__t = controllerId) ? "" : __t) + '">\n    <ms:header $template="' + (null == (__t = templateType) ? "" : __t) + '" config="headerData" on-agree-rule="onAgreeRule" on-back="onBack" on-close="onClose"  on-click-service="onClickService"></ms:header>\n</div>';
            return __p
        }
    },
    "110085254": function(e, n, t) {
        function i(e) {
            e = e || "",
            p.lang.isString(e) || (e = e.toString());
            var n, t = 0, i = 31;
            for (n = 0; n < e.length; n++)
                charCode = e.charCodeAt(n),
                t = t * i + charCode,
                t |= 0;
            return t
        }
        function o(e) {
            var n = l.getSendCount(e)
              , t = {
                "sendProps": [],
                "count": e
            };
            return n.total && t.sendProps.push({
                "name": c.getInfo().product_name + " × " + n.total
            }),
            n.firstInfo && n.firstInfo.ex_send instanceof Array && p.fn.each(n.firstInfo.ex_send, function(e) {
                t.sendProps.push({
                    "name": e.name + " × " + e.num
                })
            }),
            n.mpInfo && n.mpInfo.ex_send instanceof Array && p.fn.each(n.mpInfo.ex_send, function(e) {
                t.sendProps.push({
                    "name": e.name + " × " + e.num
                })
            }),
            f.set("drm_data", t),
            t
        }
        var s, a = t(1), r = t(68718905), c = t(119122155), l = t(66850917), u = t(76531812), d = t(56851482), p = t(4), h = t(70058909), f = t(19), m = c.buyInfo.step ? parseInt(c.buyInfo.step) : 0, g = "false" === c.buyInfo.cusInput, v = !!c.buyInfo.showRecommend && "true" === c.buyInfo.showRecommend, b = t(10), y = c.buyInfo.openid;
        if (y) {
            var _ = c.buyInfo.appid
              , k = "1450006018";
            if (v && _ === k) {
                var w = i(y)
                  , C = "";
                w % 2 === 0 ? (s = "no-price",
                C = "noPrice") : (s = "drm",
                C = "showPrice"),
                b("webpay." + C)
            }
        }
        var x = (t(121882200),
        function(e, n, t) {
            var i = this;
            a.mix(!0, n, {
                "$skipArray": ["curChannel", "friendListConfig", "fvm", "friendSelector", "spinerConfig", "recommendListConfig"],
                "amountSpinerHtml": "",
                "marketingTips": "",
                "showRecommend": v,
                "recommendList": "",
                "recommendListConfig": {
                    "type": s || "drm",
                    "cols": c.buyInfo.price_columns,
                    "count": "",
                    "onReady": function() {},
                    "onGameSelected": function(e) {
                        var n = ~~e.count;
                        o(n);
                        var t = c.getAmount();
                        t != n && (c.setAmount(n),
                        u.emit("dataChange", "count", {
                            "count": n
                        }))
                    },
                    "gameList": []
                },
                "spinerConfig": {
                    "min": 1,
                    "step": 1,
                    "max": 999,
                    "value": 0,
                    "onChange": function(e) {
                        o(e),
                        c.setAmount(e),
                        i.updatePrice(),
                        u.emit("dataChange", "count", {
                            "count": e
                        })
                    }
                }
            });
            var i = this;
            a.mix(t, {
                "onTemplate": function() {
                    return h()
                }
            }),
            r.call(this, e, n, t)
        }
        );
        p.inherits(x, r),
        p.fn.extend(x.prototype, {
            "onDataReady": function(e) {
                var n = c.getInfo()
                  , t = this.vm;
                l.setInfo(n, m, g),
                t.marketingTips = l.getMarketingTips(),
                t.showRecommend ? this.initRecommendList(e) : this.initAmountSpiner(e),
                o(c.getAmount())
            },
            "initRecommendList": function(e) {
                var n, t = this.vm, i = c.getInfo(), o = ~~i.count, a = l.getRecommendList();
                "no-price" === s && p.fn.each(a, function(e, n) {
                    e.type = "no-price"
                }),
                o && p.fn.each(a, function(e, t) {
                    if (e.count === o)
                        return n = !0,
                        !1
                }),
                t.recommendListConfig.count = n ? o : a[0].count,
                t.recommendListConfig.onReady = e,
                t.recommendListConfig.gameList = a,
                t.recommendList = '<ms:games config="recommendListConfig"></ms:games>'
            },
            "initAmountSpiner": function() {
                var e = this.vm
                  , n = c.getInfo();
                if (e.img_title = n.product_name,
                !e.canchangeCount)
                    return void (e.title = n.offer_name + " " + ("false" === c.buyInfo.showCount ? "" : n.count) + " " + n.product_name);
                var t, i = ~~n.rate, o = 100 % i === 0;
                t = o ? m ? m : 1 : m && m % i === 0 ? m : i,
                e.spinerConfig.value = ~~n.count || 100 * t,
                e.spinerConfig.min = ~~n.min_num || t,
                e.spinerConfig.max = ~~n.max_num || 5e4 * ~~n.rate,
                e.spinerConfig.step = t,
                e.tips = 1 === t ? "充值数量必须是整数" : "充值数量必须是" + t + "的倍数",
                e.amountSpinerHtml = d.create("spinerConfig")
            }
        }),
        e.exports = x
    },
    "110138172": function(module, exports) {
        module.exports = function(obj) {
            function print() {
                __p += __j.call(arguments, "")
            }
            obj || (obj = {});
            var __t, __p = "", __j = Array.prototype.join;
            with (obj)
                __p += '<div ms-controller="qcard-controller-' + (null == (__t = mode) ? "" : __t) + '">\n    <div class="input-areas" style="margin-bottom: 0;position: relative" ms-if="isCompleteMode">\n        <div class="input-row" style="display: block;margin-bottom: 10px">\n            <ms:input on-init="getNumVm" placeholder="请输入QQ卡号" maxlength="10" on-validate="onCardNumValidate"\n                config="cardNumberConfig" $id="qcardNum" on-change="onQcardNumChange" width="240px"></ms:input>\n            <p style="display: block;" class="tips icon-tips warn" ms-if="cardNumMsg">\n                <i class="icon-warn"></i> {{cardNumMsg}}\n            </p>\n        </div>\n\n        <div class="input-row" style="margin-bottom: 10px">\n            <ms:input on-init="getPassVm" placeholder="请输入QQ卡密码" maxlength="12" config="cardPassConfig"\n                on-validate="onCardPassValidate" on-change="onQcardPassChange" width="240px"></ms:input>\n            <p class="tips icon-tips warn" ms-if="cardPassMsg">\n                <i class="icon-warn"></i> {{cardPassMsg}}\n            </p>\n            <!--<a class="form-input-append-txt" style="position: absolute;top: 0;left: 245px;" href="javascript:void(0)" ms-on-click="queryBalance"-->\n            <!--ms-if="cardPassValidatePass&&cardNumValidatePass">查询余额</a>-->\n        </div>\n\n\n\n        <div id="qcardVerifyContainer"></div>\n    </div>\n    <div class="left-money-warn" ms-if="isCompleteMode && qcardBalanceNotEnough">\n        <p>\n            <i class="icon-error"></i> Q卡余额不足\n        </p>\n        <p class="tips sub-tips">\n            Q卡余额不足请更换Q卡或支付渠道\n        </p>\n    </div>\n    <div ms-if="isCompleteMode && showBalance && balance!=null" class="left-money-warn">\n        <p>Q卡<span>余额：<em class="left-money-em">{{balance}}</em>元</span></p>\n    </div>\n    ',
                __p += "undefined" == typeof type ? '\n        <div class="oper-to-pay">\n            <!-- 没有服务条款 -->\n            <a ms-on-click="pay" ms-class="btn btn-default" ms-class-1="loading:disableSubmit"\n                ms-class-2="btn-dis:amount==0" href="#" ms-if="terms.length==0">\n                <span ms-if="!disableSubmit">确认支付</span>\n                <span><i class="icon-btn-loading"></i></span>\n            </a>\n            <!-- 有服务条款 -->\n            <a ms-on-click="pay" ms-class="btn btn-default" ms-class-1="loading:disableSubmit"\n                ms-class-2="btn-dis:amount==0" href="#" style="min-width: 130px;" ms-if="terms.length>0">\n                <span ms-if="!disableSubmit">同意协议并支付</span>\n                <span><i class="icon-btn-loading"></i></span>\n            </a>\n        </div>\n        <p class="tips icon-tips"><i class="icon-txt"></i>QQ卡可分多次使用</p>\n        ' : "\n            " + (null == (__t = type) ? "" : __t) + "\n                ",
                __p += '\n                    <div class="left-money-warn" ms-if="terms.length > 0">\n                        <p class="tips sub-tips">支付前阅读并同意\n                            <span ms-repeat="terms">\n                                <a href="#" ms-click="openTerm(el,$event)">{{el.termName}}</a>\n                            </span>\n                        </p>\n                    </div>\n</div>';
            return __p
        }
    },
    "111121174": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div id="_cp__load__"  class="mdsweb-loading-wrapper abs" style="background-color:transparent; z-index:9995">\n    <div class="mdsweb-loading">\n        <div class="dot"></div>\n        <div class="dot"></div>\n        <div class="dot"></div>\n    </div>\n</div>';
            return __p
        }
    },
    "111578709": function(e, n, t) {
        var i = t(4)
          , o = t(1)
          , s = t(100835382)
          , a = (t(117821206),
        t(116097651))
          , r = t(84811753)
          , c = t(75748174)
          , l = function(e, n, t) {
            s.apply(this, arguments),
            this.vm = null,
            this.mode = s.MODE.SIMPLE,
            this.bindEvent(),
            this.initVm(),
            this.vm.amount = this.store.getAmount()
        };
        i.inherits(l, s),
        i.fn.extend(l.prototype, {
            "constructor": l,
            "bindEvent": function() {
                this.onShow = function() {}
                .bind(this),
                this.store.on("onShow", this.onShow)
            },
            "destroyEvent": function() {
                this.onShow && this.store.off("onShow", this.onShow)
            },
            "onDestroy": function() {
                this.destroyEvent(),
                s.prototype.removeListener.call(this),
                s.prototype.destroy.call(this)
            },
            "lock": function() {
                s.prototype.lock.call(this),
                this.vm.disableSubmit = !0,
                this.showMask()
            },
            "unlock": function() {
                s.prototype.unlock.call(this),
                this.vm.disableSubmit = !1,
                this.hideMask()
            },
            "getVmConfig": function() {
                var e = this;
                return this.vmConfig = {
                    "$id": "mcard-controller-" + this.mode,
                    "$skipArray": [],
                    "showTooltip": !1,
                    "balance": null,
                    "showNext": !1,
                    "amount": this.store.getAmount(),
                    "directpay": !1,
                    "disableSubmit": !1,
                    "price": this.store.getPrice(this.channelObj.discount).price,
                    "toggleTooltip": function() {
                        e.vm.showTooltip = !e.vm.showTooltip
                    },
                    "onHoverToolTip": function(e) {
                        return e.stopPropagation ? (e.stopPropagation(),
                        e.preventDefault()) : (e.cancelBubble = !0,
                        e.returnValue = !1),
                        !1
                    },
                    "pay": function(n) {
                        if (n.stopPropagation(),
                        n.preventDefault(),
                        0 != e.store.getAmount())
                            return e.store.isInterfaceDisabled() ? void e.store.emit("channelDataChange", new r(c)) : e.vm.directpay ? void e.buy({
                                "mcard_pay_mode": "1",
                                "isusempaymode": "1",
                                "pay_method": "mcard_balance"
                            }) : (e.vm.nextStep(),
                            !1)
                    },
                    "nextStep": function(n) {
                        n.preventDefault(),
                        e.store.changePage("subChannel", {
                            "channelObj": e.channelObj,
                            "mode": s.MODE.COMPLETE
                        })
                    }
                }
            },
            "initVm": function() {
                this.vm = o.define(this.getVmConfig()),
                this.store.isNewMcard() && (this.vm.balance = this.store.getMcardBalance(),
                this.vm.directpay = parseFloat(this.vm.balance) >= this.vm.price),
                this.vm.directpay && this.resize(),
                this.reportMcardBalance(),
                this.reportMcardMode()
            },
            "resize": function() {
                o.nextTick(function() {
                    this.store.emit("channelResize", l.HEIGHT)
                }
                .bind(this))
            },
            "onChange": function() {
                this.vm && (this.vm.price = this.store.getPrice(this.channelObj.discount).price,
                this.store.isNewMcard() && (this.vm.directpay = parseFloat(this.vm.balance) >= this.vm.price),
                this.vm.directpay && this.resize(),
                this.vm.amount = this.store.getAmount(),
                this.reportMcardBalance())
            },
            "reportMcardMode": function() {
                this.reportUser(String.format("mode.{type}.pv", {
                    "type": this.store.isNewMcard() ? "new" : "old"
                }))
            },
            "reportMcardBalance": function() {
                this.store.isNewMcard() && (this.vm.directpay ? this.report("info.plentybalance") : this.report("info.lackbalance"))
            },
            "buy": function(e) {
                this.isLocked() || (this.lock(),
                this.showMask(),
                this.reportUser("pay.click"),
                this.store.buy(e, function(n) {
                    return this.hideMask(),
                    this.handlerBuy(n, e)
                }
                .bind(this)))
            },
            "handlerBuy": function(e, n) {
                var t = this;
                if (t.unlock(),
                !~~e.ret) {
                    this.billNo = e.info.billno || "test",
                    this.portalNo = e.info.portal_serial_no;
                    ({
                        "billNo": e.info.billno,
                        "portalNo": e.info.portal_serial_no
                    });
                    return this.store.onSuccess({
                        "portalNo": e.info.portal_serial_no
                    }),
                    !0
                }
                return !1
            }
        }),
        l.getTemplate = function(e) {
            return e = e || {},
            e.mode = e.mode || s.MODE.SIMPLE,
            a({
                "mode": e.mode
            })
        }
        ,
        l.create = function(e, n, t) {
            return new l(e,n,t)
        }
        ,
        l.HEIGHT = 120,
        e.exports = l
    },
    "112168480": function(e, n, t) {
        function i(e) {
            a.apply(this, arguments),
            this.initVm(),
            this.getInfo = function() {
                var e = {
                    "gameCurrencyName": this.orderInfo.offer_name,
                    "count": this.orderInfo.count,
                    "unit": this.orderInfo.product_name,
                    "account": this.opt.provide_uin || ""
                };
                if (e.account) {
                    var n = r.getDisplayInfoByOpenid(e.account)
                      , t = n.nick;
                    e.account = "为" + n.uin + '(<span class="f_toe" title="' + t + '">' + t + "</span>)"
                }
                return " 成功" + e.account + "购买 " + e.gameCurrencyName + " " + ("false" === this.params.showCount ? "" : e.count) + e.unit
            }
            ,
            this.getMarketingTips = function() {
                var e = s.get("drm_data");
                return e && e.sendProps && e.sendProps.length ? e.sendProps : ""
            }
            ,
            this.initialize()
        }
        var o = t(4)
          , s = t(19)
          , a = t(108898004)
          , r = t(78805100);
        o.inherits(i, a),
        o.fn.extend(i.prototype, {
            "initialize": function() {
                this.vm.status === a.ENUM_STATUS.SUCCESS ? (this.vm.info = this.opt.displayInfo || this.getInfo(),
                this.vm.market = this.getMarketingTips(),
                this.vm.bottomText = '<div class="rational-tips" id="" style="bottom:20px"><p>适度娱乐 理性消费</p></div>') : this.vm.status !== a.ENUM_STATUS.FAIL && this.vm.status != a.ENUM_STATUS.ERROR || (this.vm.info = this.opt.displayInfo)
            },
            "onQueryNoResult": function(e) {
                this.setInfo(e)
            },
            "onQuerySuccess": function() {
                this.setSuccessInfo()
            },
            "onQueryFail": function(e, n) {
                this.setInfo(e),
                this.setSubInfo(n)
            },
            "onQueryError": function(e) {
                this.setInfo(e)
            },
            "setSuccessInfo": function() {
                this.setInfo(this.opt.displayInfo || this.getInfo())
            }
        }),
        e.exports = i
    },
    "112211847": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div ms-important="' + (null == (__t = id) ? "" : __t) + '" style="box-shadow: rgba(176, 176, 176, 0.5) 0px 10px 18px 2px;\n    background: rgb(255, 255, 255);\n    border-width: 1px;\n    border-style: solid;\n    border-color: rgb(229, 229, 229);\n    border-image: initial;\n    border-radius: 2px;\n    padding-bottom:20px;\n    position:relative\n    ">\n    <h3 style="text-align: center;\n    line-height: 40px;\n    border-top: 1px solid #e5e5e5;\n    border-bottom: 1px solid #e5e5e5;\n    font-size: 16px;">短信验证</h3>\n    <a href="javascript:;" class="btn-close" style="color: #bdbdbd;\n    font-size: 22px;\n    position: absolute;\n    right: 0;\n    top: 0;\n    width: 40px;\n    text-align: center;\n    line-height: 40px;" ms-on-click="close">×</a>\n    <div class="pop-content" style="margin-top:25px;">\n        <div class="send-secur-code" style="width:210px;margin:0 auto">\n            <p class="tips" ms-if="reasonMsg">\n                {{reasonMsg}}\n            </p>\n            <div ms-if="!mobileNo" style="padding:5px 0" style="width:100%">\n                <ms:input placeholder="请输入您的手机号" maxlength="11" config="phoneNoConfig"></ms:input>\n                <p class="tips icon-tips warn" ms-if="phoneNoMsg">\n                    <i class="icon-warn"></i> {{phoneNoMsg}}\n                </p>\n            </div>\n            <div ms-if="mobileNo" style="margin-top: 15px;margin-bottom: 5px;" class="telephone-fee-pay-area">\n                <p class="tips">\n                    您的密保手机号码是<em>{{mobileNo}}</em>,请点击获取验证码：\n                </p>\n            </div>\n            <div style="padding:5px 0;display:block;font-size:0;width:250px;">\n                <div style="display:inline-block;*display:inline;*zoom:1;width:130px;*width: 125px">\n                    <ms:input placeholder="请输入验证码" maxlength="8" config="veriCodeConfig"></ms:input>\n                    <p class="tips icon-tips warn" ms-if="veriCodeMsg">\n                        <i class="icon-warn"></i> {{veriCodeMsg}}\n                    </p>\n                </div>\n                <a style="display:inline-block;*display:inline;*zoom:1;text-align: center;width:60px;*margin-left: 16px;*margin-top:1px;" class="form-btn" ms-on-click="getVerifyCode"\n                    ms-attr-disabled="!!verifyCodeCountDown">{{verifyCodeCountDown||\'获取验证码\'}}\n                </a>\n            </div>\n            <div class="btn-wrap" style="padding-top:10px">\n                <button type="button" class="btn btn-default btn-s" style="margin-right:10px;" ms-on-click="onConfirm">提交</button>\n                <button type="button" class="btn btn-primary btn-s" style="margin-right:10px;" ms-on-click="onCancel">取消</button>\n            </div>\n            <div ms-if="mobileNo && url" style="margin-top:10px">\n                <a href="javascript:void;" ms-on-click="onSwitch">切换验证方式</a>\n            </div>\n        </div>\n    </div>\n    <div ms-visible="isLoading" class="mdsweb-loading-wrapper abs" style="z-index:1000;background:none">\n        <div class="mdsweb-loading">\n            <div class="dot"></div>\n            <div class="dot"></div>\n            <div class="dot"></div>\n        </div>\n    </div>\n    <div class="pop-tips" ms-if="toastContent" style="left:50%;" ms-css-margin-left="{{toastOffset}}">{{toastContent}}</div>\n</div>';
            return __p
        }
    },
    "112738610": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div class="goods-items"\n     ms-on-mouseenter="mouseenter"\n     ms-on-mouseleave="mouseleave"\n     ms-class-1="checked:checked"\n     ms-class-2="error:isWarn"\n     ms-on-click="handleClickGoods"\n     data-track="product">\n    <div class="total service" ms-if="!editable">\n            <p class="service__quantity"><img class="service__logo" ms-attr-src="logo" alt="" title=""><span class="service__num" >{{count}}</span>\n                <span\n                        class="service__sub-num" ms-if="discountAmount>0">+{{discountAmount}}</span>\n            </p>\n            <div class="service__gift" >\n\n                <p class="service__txt" ms-if="discountTips">\n                    <span>赠：{{discountTips.name}}</span> × {{discountTips.num}}\n                </p>\n                <p class="more"  ms-if="discountDetailTips.length>0">\n                    <i class="icon-omit"></i>\n                </p>\n                <div class="tooltip gift" ms-if="discountDetailTips.length>0" ms-attr-id="giftId">\n                    <p class="gift__title">赠：</p>\n                    <ul class="gift__list">\n                        <li ms-repeat="discountDetailTips" class="gift__item">\n                            <span>{{el.name}}</span> × {{el.num}}\n                        </li>\n                    </ul>\n                </div>\n\n            </div>\n        </div>\n     <div class="total service" ms-if="editable">\n            <p class="service__quantity" style="position:relative">\n                <img class="service__logo" ms-attr-src="logo" alt="" title=""><input  ms-attr-id="inputId" class="form-input form-input--s form-input--no-border service__input service__input-cn"\n                       ms-on-click="handleInputClick"\n                       ms-on-focus="handleFocus"\n                       ms-on-keydown="handleKeyDown"\n                       ms-on-keyup="handleKeyUp"\n                       ms-on-blur="handleBlur"\n                       data-track="customAmountInput"><label ms-attr-for="inputId" ms-if="enablePlaceHolder && count==\'\' && !ie7focused" style="position:absolute;font-size:16px;left: 0;top:0;width:80px;*width:70px;height:18px;*height:24px;height:24px\\0;left:30px;line-height:30px;vertical-align:middle;" class="input-placeholder">\n                其他数量\n            </label></p>\n\n\n            <div class="service__gift" >\n\n                <p class="service__txt" ms-if="discountTips">\n                    <span>赠：{{discountTips.name}}</span> × {{discountTips.num}}\n                </p>\n                <p class="more"  ms-if="discountDetailTips.length>0">\n                    <i class="icon-omit"></i>\n                </p>\n                <div class="tooltip gift" ms-if="discountDetailTips.length>0" ms-attr-id="giftId">\n                    <p class="gift__title">赠：</p>\n                    <ul class="gift__list">\n                        <li ms-repeat="discountDetailTips" class="gift__item">\n                            <span>{{el.name}}</span> × {{el.num}}\n                        </li>\n                    </ul>\n                </div>\n\n            </div>\n\n        </div>\n    <div class="relative-to-total">\n      <em class="money">{{price}}</em>\n      <span class="unit">{{priceUnitName}}</span>\n    </div>\n    <i class="icon-corner-checked" ms-if="!editable"></i>\n    <i class="icon-corner-checked hide" ms-if="editable" ms-attr-id="cornerId" ></i>\n    <div class="goods-marketing" ms-if="restrictionRule">\n        <i class="icon-marketing-l"></i>\n        <span>{{restrictionRule}}</span>\n        <i class="icon-marketing-r"></i>\n    </div>\n    <p class="tips icon-tips warn custom-tips" ms-if="isWarn">\n        <i class="icon-warn"></i>\n        {{errorTips}}\n    </p>\n</div>';
            return __p
        }
    },
    "112745811": function(e, n) {
        e.exports = {
            "QB": "qb",
            "MONTH": "month",
            "GAME": "save",
            "GOODS": "goods"
        }
    },
    "112832022": function(e, n, t) {
        function i() {
            a.apply(this, arguments),
            this.infoList = {},
            this.defaultPriceType = u[this.buyInfo.price_type] || u["open"],
            this.payFor = "self",
            this.targetInfo = {
                "targetUin": this.buyInfo.provide_uin || this.buyInfo.openid,
                "targetName": ""
            },
            this.wxNick = null
        }
        var o = t(4)
          , s = t(1)
          , a = t(51768702)
          , r = t(83497919)
          , c = t(99560243)
          , l = t(54698897);
        t(5);
        var u = t(74109955)
          , d = t(82007299)
          , p = t(49140953)
          , h = t(48016802)
          , f = (t(83058212),
        t(112745811))
          , m = t(87796589)
          , g = (t(109735088),
        t(10))
          , v = t(75685166)
          , b = {
            "ret": -9999,
            "msg": p.TEXT.INVALIDLOGIN
        }
          , y = function(e) {
            e.offer_name = e.offer_name.split("_")[0]
        };
        o.inherits(i, a),
        s.mix(i.prototype, d, {
            "includeTheNode": function(e) {
                return e["product_list"] && e["product_list"].length > 0
            },
            "_removeUserData": function(e) {
                if (e.info) {
                    var n = s.mix(!0, {}, e, {
                        "info": {
                            "month_list": [],
                            "qqacct_balance": -1,
                            "month_info": {
                                "year_months": -1,
                                "upgrade_months": -1
                            }
                        }
                    });
                    return delete n.info.month_list,
                    n
                }
                return e
            },
            "loadInfo": function(e, n) {
                var t = this
                  , i = this.currentLoginStatus()
                  , a = []
                  , u = {};
                e = e.slice(0, c.MaxViewSerivce),
                this.service = e[0];
                var d = function(e, n) {
                    var i = e.info.month_info && e.info.month_info["service_code"];
                    e.info = o.fn.extend({
                        "__cacheData": {}
                    }, r.getServiceInfo("base"), r.getServiceInfo(i), e.info),
                    y(e.info),
                    e.info.count <= 0 && (e.info.count = c.monthCount),
                    t.setPayFor(),
                    v.fetchFeature(e.info.offer_id, e.info.month_info["upgrade_type"]).then(function(t) {
                        n(e.info)
                    })["catch"](function(t) {
                        n(e.info)
                    })
                };
                s.each(e, function(e, n) {
                    u[n] || (u[n] = !0,
                    a.push(new s.Promise(function(e, i) {
                        var s = l.ParamsService(f.MONTH, n, t.buyInfo);
                        t.cgi.webMonthInfo(o.fn.extend({
                            "buy_quantity": t.buyInfo.buy_quantity
                        }, s), function(s) {
                            if (!~~s.ret && t.includeTheNode(s.info))
                                o.handleDisableChannel(s.info),
                                o.discount.initNoDiscountInterval(s.info),
                                o.localStorage.set(n, JSON.stringify(t._removeUserData(s))),
                                t.infoList[n] = s.info,
                                d(s, e);
                            else if (g("cgi.info", {
                                "resultcode": s.ret
                            }),
                            t.unLogin(s.ret))
                                i(s);
                            else {
                                var a = o.localStorage.get(n, !0);
                                a ? d(a, e) : (g("recovery.info", {
                                    "action": n
                                }),
                                t.cgi.jsonp(String.format(l.RecoveryAddress(), {
                                    "appid": n
                                }), function(n) {
                                    ~~n.ret ? i(n) : d(t._removeUserData(n), e)
                                }, {
                                    "callback": String.format("minipay{appid}", {
                                        "appid": n
                                    })
                                }))
                            }
                        }, {
                            "appid": n
                        }),
                        l.UpdateBankList(t.cgi)
                    }
                    )))
                }),
                s.Promise.all(a).then(function() {
                    arguments[0].length > 1 && (t.showTab = !0),
                    s.each(arguments[0], function(n, i) {
                        t.infoList[e[n]] = i
                    }),
                    g("page.data"),
                    v.switchFeature(t.service),
                    n(t.getInfo())
                }, function(e) {
                    t.unLogin(e.ret) && (i.isPT || i.isPskey) ? t.showLoginBox({
                        "onClose": function(e) {
                            n(!1, b)
                        }
                    }) : n(!1, arguments[0])
                })["catch"](function(e) {})
            },
            "getInfo": function() {
                var e = this.service;
                return this.infoList[e]
            },
            "updateQQbalance": function(e) {
                s.each(this.infoList, function(n, t) {
                    t.qqacct_balance = e
                })
            },
            "getUnitName": function() {
                var e = this.service;
                return r.getUnitName(this.infoList[e].priceType)
            },
            "getHFPriceInfo": function() {
                var e = this.service;
                return r.getMonthDataInfo(this.infoList[e], u["open"], 1)
            },
            "setPrice": function(e) {
                var n = this.service
                  , t = this.infoList[n];
                t && (t.totalPrice = e.price,
                t.unitPrice = e.unitPrice,
                t.unitName = e.unitName,
                t.priceType = e.type,
                t.productId = e.value,
                t.productName = e.productName,
                t.count = e.count,
                t.editable = e.editable,
                t.innerProductId = e.innerProductId,
                t.serviceCode = e.serviceCode),
                t.editable && (t.priceType == u.open || t.priceType == u.year ? t.productName = String.format("{0}{1}{2}", t.count, t.unitName, r.getName(t)) : t.priceType == u.upgrade && (t.productName = String.format("{0}{1}{2}{3}", h.get("upgradeTxt"), t.count, t.unitName, r.getName(t))))
            },
            "setWXNick": function(e) {
                this.wxNick = e
            },
            "getMonthSelected": function() {
                var e = this.service
                  , n = this.infoList[e];
                return n ? {
                    "type": n.priceType,
                    "count": n.count
                } : null
            },
            "monthItemIsSame": function(e) {
                var n = this.service
                  , t = this.infoList[n]
                  , i = e.type == t.priceType && e.value == t.productId && e.count == t.count;
                return i
            },
            "setTargetInfo": function(e) {
                e && (s.mix(this.targetInfo, e),
                this.setPayFor())
            },
            "setNBATeam": function(e) {
                var n = this.getInfo();
                n.nbaTeam = e
            },
            "setPayFor": function() {
                this.payFor = this.targetInfo.targetUin == this.buyInfo.openid ? m.SELF : m.SEND
            },
            "getTargetInfo": function() {
                return this.targetInfo
            },
            "getPayFor": function() {
                return this.payFor
            },
            "getOpenedServices": function() {
                var e = this.service;
                return this.infoList[e].service_list
            }
        });
        var _ = new i;
        e.exports = _
    },
    "113871490": function(e, n, t) {
        function i(e) {
            if (this.mount = e.mount,
            this.unmount = e.unmount,
            this.cgi = e.cgi,
            this.configName = e.configName,
            this.setConfig = e.setConfig,
            this.onSuccess = e.onSuccess || s,
            this.onPending = e.onPending || s,
            this.onFail = e.onFail || s,
            this.onNoResult = e.onNoResult || s,
            this.onError = e.onError || s,
            this.onRetry = e.onRetry || s,
            this.channel = e.channel,
            this.billNo = e.billNo || "",
            this.portalNo = e.portalNo || "",
            this.resultQueryVm = null,
            this.buyType = e.buyType,
            this.realServiceCode = e.realServiceCode,
            this.feeType = e.feeType,
            this.provideUin = e.provideUin,
            !this.billNo)
                throw Error("billNo must be provide");
            this.init()
        }
        var o = t(4)
          , s = (t(1),
        o.fn.emptyFunc)
          , a = t(80576922);
        o.fn.extend(i.prototype, {
            "init": function() {
                this.initConfig(),
                this.mount(a.create(this.configName))
            },
            "initConfig": function() {
                var e = this
                  , n = this.cgi;
                this.setConfig({
                    "info": "支付结果确认中",
                    "subInfo": "请稍后留意微信支付扣款信息",
                    "times": 60,
                    "queryTimeout": 10,
                    "onInit": function(n) {
                        e.resultQueryVm = n
                    },
                    "onQuery": function(t) {
                        n.querySignStatus({
                            "type": e.channel,
                            "billNo": e.billNo
                        }, function(n) {
                            if (~~n.ret)
                                t.queryDone(a.ENUM_STATUS.PENDING);
                            else {
                                var i = "wechat" === e.channel ? n.wx_order_status : n.qq_order_status;
                                switch (i) {
                                case 4:
                                    t.setInfo("支付成功"),
                                    t.setSubInfo(""),
                                    t.queryDone(a.ENUM_STATUS.SUCCESS);
                                    break;
                                case 5:
                                    t.queryDone(a.ENUM_STATUS.ERROR),
                                    e.onRetry();
                                    break;
                                default:
                                    t.queryDone(a.ENUM_STATUS.PENDING)
                                }
                            }
                        }
                        .bind(this))
                    },
                    "onSuccess": function(n) {
                        e.onSuccess()
                    },
                    "onPending": function(n) {
                        e.onPending()
                    },
                    "onNoResult": function(n) {
                        n.setInfo("开通失败"),
                        n.setSubInfo(""),
                        e.onNoResult(n.getInfo(), n.getSubInfo())
                    },
                    "onError": function(n) {
                        e.onError(n.getInfo(), n.getSubInfo())
                    },
                    "onFail": function(n) {
                        e.onFail(n.getInfo(), n.getSubInfo())
                    }
                })
            },
            "onDestroy": function() {
                o.fn.stop(),
                this.resultQueryVm.destroy(),
                this.resultQueryVm = null,
                this.unmount()
            },
            "destroy": function() {
                this.onDestroy()
            }
        }),
        e.exports = i
    },
    "115878448": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<form class="form-inline">\n    <div ms-repeat="radioList" class="form-group radio-box" ms-class-1="checked:$index==index" ms-on-click="handleClick($index,$event)">\n        <label ms-attr-for="radioId">\n            <input type="radio" ms-attr-checked="$index==index">\n            <i class="icon-radio"></i>\n            <span ms-html="el.name"></span>\n        </label>\n    </div>\n</form>';
            return __p
        }
    },
    "116097651": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div ms-controller="mcard-controller-' + (null == (__t = mode) ? "" : __t) + '" class="pay-area-active">\n\n    <div class="left-money-warn" ms-if="directpay">\n        <div class="cellphone-info">\n            <p>手机充值卡账户余额：<span><em class="left-money-em">{{balance}}</em>元</span>\n                <a class="cellphone-tooltip-trigger" style="vertical-align: middle" ms-class-1="open:showTooltip" ms-on-mouseenter="toggleTooltip" ms-on-mouseleave="toggleTooltip">\n                    <i class="icon-info"></i>\n                    <span ms-visible="showTooltip" ms-on-mouseenter="onHoverToolTip" ms-on-mouseleave="onHoverToolTip" class="tooltip">手机充值卡将一次性销卡，请选择与卡面额对应的面值，若有金额剩余，将以手机充值卡账户余额的形式保留，供下次使用该渠道支付时使用。例如余额:5元，订单金额：10元，使用20元充值卡支付完成后会有15元存入手机充值卡账户余额。</span>\n                </a>\n            </p>\n        </div>\n    </div>\n    <div ms-if="!showNext" class="oper-to-pay">\n        <a ms-on-click="pay" ms-class-1="btn btn-default" ms-class-2="btn-dis:disableSubmit||amount==0" ms-class-3="loading:disableSubmit" href="#">\n            <span ms-if="!disableSubmit">\n                确认支付 <span>{{price}}</span>元\n            </span>\n            <span>\n                <i class="icon-btn-loading"></i>    \n            </span>        \n        </a>\n    </div>\n    <a ms-on-click="nextStep" ms-class="btn btn-default" ms-if="showNext" href="#">\n        下一步\n    </a>\n</div>';
            return __p
        }
    },
    "116820311": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div ms-controller="friendpay-controller">\n    <div class="qr-code-txt">\n        <i class="icon-wx"></i><i class="icon-qq"></i>\n        微信或手Q扫码，邀请朋友支付\n        <em ms-if="!priceLoading">{{price}}</em>\n        <span ms-if="priceLoading" ms-html="priceLoadingTplHtml"></span>\n        元\n    </div>\n    <div class="qr-code-area" ms-visible="showQrcode">\n        <div class="qr-code-container friendpay" ms-visible="!disableQrcode">\n            <div id="qr-code-friendpay" style="display: none"></div>\n            <img ms-if="url" ms-attr-src="url" ms-on-load="qrcodeLoaded" ms-on-error="qrcodeLoadFail">\n            <div class="qr-code-mask" ms-if="qrcodeLoading||qrcodeReload||priceLoading"></div>\n            <div class="qr-code-loading" ms-if="qrcodeLoading||priceLoading">\n                <i></i>\n                <p>加载中，请稍后</p>\n            </div>\n            <div class="qr-code-reload" ms-if="qrcodeReload" ms-on-click="refreshQrcode">\n                <i></i>\n                <p>重新获取二维码</p>\n            </div>\n        </div>\n        <div class="qr-code-container friendpay" ms-visible="disableQrcode && !disableText"></div>\n    </div>\n    <div class="qr-code-area" ms-visible="showScaned">\n        <i class="icon-phone"></i>\n        <p>请在手机上分享给好友进行支付</p>\n        <a href="javascript:void(0);" ms-on-click="backQrcode">返回二维码</a>\n    </div>\n    <div class="qr-code-area" ms-visible="disableQrcode && disableText">\n        <i class="icon-phone"></i>\n        <p>{{disableText}}</p>\n        <a href="javascript:void(0);" ms-on-click="backQrcode">刷新二维码</a>\n    </div>\n</div>';
            return __p
        }
    },
    "117520354": function(e, n, t) {
        var i = t(1)
          , o = t(68718905)
          , s = t(119122155)
          , a = t(4)
          , r = t(78805100)
          , c = t(78877987)
          , l = s.buyInfo.step ? parseInt(s.buyInfo.step) : 1
          , u = t(17)
          , d = t(19)
          , p = t(106745080)
          , h = t(10)
          , f = t(66850917);
        t(103218213),
        t(121882200);
        var m = t(84811753)
          , g = t(75748174)
          , v = t(76531812)
          , b = t(86478814)
          , y = t(12)
          , _ = {
            "accountPromptTips": "请完善充值游戏账号信息",
            "noRole": "用户在该大区没有创建角色",
            "noAccount": "用户在该游戏下没有创建角色",
            "serverMaintain": "您选择的大区/服务器正在停机维护，暂时无法充值"
        }
          , k = {
            "serverDropdownlist": {
                "name": "请选择服务器",
                "value": ""
            },
            "areaDropdownlist": {
                "name": "请选择大区",
                "value": ""
            },
            "roleDropdownlist": {
                "name": "请选择角色",
                "value": ""
            }
        }
          , w = decodeURIComponent(s.buyInfo.zoneid ? s.buyInfo.zoneid : "").split("|")
          , C = function(e, n, t) {
            this.hasServer = !1,
            this.withoutArea = !1;
            var r = this;
            this.hasRole = !1,
            this.validation = {
                "account": !0,
                "area": !1
            };
            var l = s.getSwitchLoginTypeMsg();
            i.mix(!0, n, {
                "showTips": !1,
                "showAccountTips": !1,
                "accountSubmitTips": "",
                "showAreaTips": !1,
                "areaSubmitTips": "",
                "canOrder": !0,
                "accountEditable": !0,
                "amountSpinerHtml": "",
                "areaEditable": !1,
                "showAreaInfo": !0,
                "enableChangeAccount": s.isAllowSend(),
                "step": 1,
                "areaListHtml": "",
                "serverListHtml": "",
                "roleListHtml": "",
                "areaName": "",
                "serverName": "",
                "roleName": "",
                "positionLeft": "230px",
                "submitTips": "",
                "supportMutilLogin": l,
                "$skipArray": ["curChannel", "friendListConfig", "fvm", "friendSelector", "areaInfoConfig", "serverInfoConfig", "roleInfoConfig", "gamePriceListConfig"],
                "areaInfoConfig": {
                    "data": [],
                    "value": {
                        "name": w.length > 0 ? decodeURIComponent(w[0]) : k.areaDropdownlist.name,
                        "value": w.length > 0 ? w[0] : k.areaDropdownlist.value
                    },
                    "container": "order_info",
                    "defaultValue": k.areaDropdownlist,
                    "width": "100px",
                    "onChange": function(e) {
                        var n = s.getInfo();
                        if (n.zone_id = null,
                        n.role_id = null,
                        "0" == e.status) {
                            if (r.vm.areaSubmitTips = _.serverMaintain,
                            r.vm.showAreaTips = !0,
                            r.hasServer) {
                                var t = i.vmodels["serverDropdownlist"];
                                t && t.reset([], null, !0)
                            } else
                                r.resetRole(!0);
                            r.setAutoOrder(r.vm.areaSubmitTips)
                        } else
                            r.vm.showAreaTips = !1,
                            r.vm.areaSubmitTips = "",
                            r.hasServer ? s.loadGameJS(n.game_info, function(t) {
                                if (e.value) {
                                    n.zone_id = [e.value],
                                    r.vm.areaName = e.value ? e.name + "；" : "";
                                    var t = b.getServerData(t, e.value).data;
                                    r.vm.serverListHtml ? i.vmodels["serverDropdownlist"].reset(t) : (r.vm.serverInfoConfig.data = t,
                                    a.lang.isArray(t) && 1 == t.length && (r.vm.serverInfoConfig.value = a.fn.extend({}, t[0])),
                                    r.vm.serverListHtml = '<ms:autocomplate $id="serverDropdownlist" config="serverInfoConfig" on-change="onChange"></ms:autocomplate>')
                                } else {
                                    var o = i.vmodels["serverDropdownlist"];
                                    o && o.reset([])
                                }
                            }) : (n.zone_id = [],
                            r.initRole(e))
                    }
                },
                "serverInfoConfig": {
                    "data": [],
                    "width": "110px",
                    "container": "order_info",
                    "value": {
                        "name": w.length > 1 ? decodeURIComponent(w[1]) : k.serverDropdownlist.name,
                        "value": w.length > 1 ? w[1] : k.serverDropdownlist.value
                    },
                    "defaultValue": k.serverDropdownlist,
                    "onChange": function(e) {
                        "0" == e.status ? (r.vm.areaSubmitTips = _.serverMaintain,
                        r.vm.showAreaTips = !0,
                        r.resetRole(!0),
                        r.setAutoOrder(r.vm.areaSubmitTips)) : (r.vm.showAreaTips = !1,
                        r.vm.areaSubmitTips = "",
                        r.initRole(e),
                        e.value || (r.validation.area = !1,
                        r.setAutoOrder()))
                    }
                },
                "roleInfoConfig": {
                    "data": [],
                    "width": "100px",
                    "container": "order_info",
                    "value": {
                        "name": w.length > 2 ? decodeURIComponent(w[2]) : k.roleDropdownlist.name,
                        "value": w.length > 2 ? w[2] : k.roleDropdownlist.value
                    },
                    "defaultValue": k.roleDropdownlist,
                    "onChange": function(e) {
                        var n = s.getInfo();
                        r.vm.showAreaTips = !1,
                        r.vm.areaSubmitTips = "",
                        e.value ? (r.validation.area = !0,
                        n.role_id = e.value,
                        r.vm.roleName = e.value ? e.name + "；" : "",
                        r.setAutoOrder()) : (r.validation.area = !1,
                        r.setAutoOrder())
                    }
                },
                "friendListConfig": {
                    "initExpand": !1,
                    "initCallBack": !0,
                    "mode": 2,
                    "placeholder": "请输入QQ号",
                    "onFriendSelected": function(e, n) {
                        r.friendSelected(e, n)
                    },
                    "onBlur": function(e) {
                        r.friendSelected(e)
                    }
                },
                "gamePriceListHtml": "",
                "gamePriceListConfig": {},
                "onGameSelected": function(e) {
                    h.user.action("order", "gamelist.click", {
                        "cardtype": e.type,
                        "amount": e.count,
                        "editable": e.editable ? 1 : 0
                    }),
                    e.count != s.getAmount() && (s.setAmount(e.count),
                    r.updatePrice(),
                    r.emitOrder("count", {
                        "count": ~~e.count
                    }))
                },
                "onChangeLoginType": function(e) {
                    e && s.showLoginBox(e[0], {
                        "onSuccess": function(e) {
                            var n = e.getSessionParam();
                            n.openid = decodeURIComponent(n.openid),
                            n.openkey = decodeURIComponent(n.openkey),
                            location.href = a.fn.addParam(n, location.href)
                        },
                        "onClose": function() {}
                    })
                }
                .bind(this)
            }),
            i.mix(t, {
                "onTemplate": function() {
                    return c()
                }
            }),
            o.call(this, e, n, t)
        };
        a.inherits(C, o),
        a.fn.extend(C.prototype, {
            "onChannelAPIReady": function() {
                this.channelReady = !0,
                this.setAutoOrder(this.vm.canOrder)
            },
            "onChannelEvent": function(e) {
                var n = e.getData().showBindCard
                  , t = this.vm;
                t.showSimpleOrder = n,
                n ? (t.buycount = s.getAmount(),
                t.buyinfo = "购买" + s.getInfo().product_name,
                u.trigger("headerDataReady", {
                    "title": v.getStore().getChannelObj().channelText
                }),
                this.root.fakeSubChannel = !0) : (u.notify("resetTitle"),
                this.root.fakeSubChannel = !0)
            },
            "friendSelected": function(e, n) {
                if (!e.invalid) {
                    var t = this.vm || this.vmConfig;
                    t.accountSubmitTips = "",
                    t.showAccountTips = !1,
                    this.validation.account = !0,
                    e.invalid ? (t.accountSubmitTips = "请选择正确的QQ号",
                    t.showAccountTips = !0,
                    this.validation.account = !1) : e.stranger && (t.accountSubmitTips = String.format("正在为陌生人{qq}充值", {
                        "qq": e.qq
                    }),
                    t.showAccountTips = !0);
                    var i = r.getDisplayInfoByOpenid(e.qq);
                    t.account = i.uin + String.format("（{nickname}）", {
                        "nickname": i.nick
                    }),
                    s.setProvideUin(e.qq),
                    d.set("qqNickName", (r.getDisplayInfoByOpenid(e.qq) || {}).nick),
                    this.onSelectFriend(),
                    s.getInfo().game_info.check_type == p.CheckType.CHECK ? this.checkGameRole(function(n) {
                        this.emitOrder("count", {
                            "provide_uin": e.qq
                        }),
                        n && (t.accountEditable = !1)
                    }
                    .bind(this)) : (this.emitOrder("count", {
                        "provide_uin": e.qq
                    }),
                    this.withoutArea && (t.accountEditable = !1),
                    this.setAutoOrder())
                }
            },
            "checkDropdown": function() {
                this.onChannelDataChange(new m(g))
            },
            "checkGameRole": function(e) {
                var n = this;
                s.getRoleList(0, function(t, i) {
                    n.validation.area = t;
                    var o;
                    o = 1290 === i.ret ? _.noAccount : i.err_code ? String.format("系统繁忙，请稍后再试（{errCode}）", {
                        "errCode": i.err_code
                    }) : i.msg,
                    n.setAutoOrder(o),
                    t ? (n.vm.showAccountTips = !1,
                    n.vm.accountSubmitTips = "") : (n.vm.accountSubmitTips = o,
                    n.vm.showAccountTips = !0),
                    e && e(t)
                })
            },
            "onChannelDataChange": function(e) {
                var n = s.getInfo().game_info;
                switch (e.getType()) {
                case g:
                    var t = !1;
                    if (!this.validation.account)
                        return;
                    a.fn.each(["areaDropdownlist", "serverDropdownlist", "roleDropdownlist"], function(e) {
                        var n;
                        if (i.vmodels && (n = i.vmodels[e],
                        n && n.getValue)) {
                            var o = n.getValue();
                            if (!o || !o.value)
                                return t = !1,
                                this.vm.areaSubmitTips = _.accountPromptTips,
                                this.vm.showAreaTips = !0,
                                !1;
                            if (("areaDropdownlist" === e || "serverDropdownlist" === e) && "0" == o.status)
                                return t = !1,
                                this.vm.areaSubmitTips = _.serverMaintain,
                                this.vm.showAreaTips = !0,
                                !1;
                            t = !0,
                            this.vm.areaSubmitTips = "",
                            this.vm.showAreaTips = !1
                        }
                    }
                    .bind(this));
                    var o = n.check_type == p.CheckType.SELECTRole || n.check_type == p.CheckType.CHECKRole;
                    o && t && (this.hasRole ? (this.vm.showAreaTips = !1,
                    this.vm.areaSubmitTips = "") : (this.vm.areaSubmitTips = _.noRole,
                    this.vm.showAreaTips = !0))
                }
            },
            "setAutoOrder": function(e) {
                var n = this.validation.account && this.validation.area;
                this.vm.canOrder = n;
                var t = "";
                n || (t = e || _.accountPromptTips || ""),
                this.emitOrder("canOrder", {
                    "canOrder": n,
                    "text": t
                }),
                this.vm.accountEditable = !n
            },
            "onClickSwitch": function() {
                this.vm.accountEditable = !0,
                this.vm.friendListConfig.initExpand = this.withoutArea,
                this.initFriendsComponent(this.withoutArea)
            },
            "onResult": function() {
                u.trigger("headerDataReady", {
                    "title": s.getInfo().product_name
                }),
                a.delayRun("again.event", function() {
                    v.emit("onShow")
                }, 500)
            },
            "onDataReady": function(e) {
                this.initAreaInfo(),
                this.initGamePriceList(e),
                u.trigger("headerDataReady", {
                    "title": s.getInfo().product_name
                })
            },
            "onSelectFriend": function() {
                var e = i.vmodels["areaDropdownlist"];
                if (this.vm.showAreaTips = !1,
                this.vm.areaSubmitTips = "",
                e) {
                    var n = this.vm.areaInfoConfig.data
                      , t = a.lang.isArray(n) && 1 === n.length ? n[0] : k.areaDropdownlist;
                    e.select(t),
                    this.setAutoOrder(!1)
                }
            },
            "emitOrder": function(e, n) {
                this.channelReady && v.emit("dataChange", e, n)
            },
            "resetRole": function(e) {
                this.hasRole = !1;
                var n = i.vmodels["roleDropdownlist"];
                n && n.reset([], null, e)
            },
            "initRole": function(e) {
                var n = s.getInfo()
                  , t = this
                  , o = n.game_info
                  , a = o.check_type == p.CheckType.SELECTRole || o.check_type == p.CheckType.CHECKRole;
                n.role_id = null,
                this.vm.serverName = e.value ? e.name + "；" : "",
                a ? e.value && this.validation.account ? s.getRoleList(e.value, function(s, a) {
                    if (s)
                        if (t.hasRole = !0,
                        t.vm.showAreaTips = !1,
                        o.check_type == p.CheckType.SELECTRole) {
                            n.zone_id.push(e.value);
                            var r = b.getRoleListData(a.role_list);
                            t.vm.submitTips = k.roleDropdownlist.name,
                            t.vm.roleListHtml ? i.vmodels["roleDropdownlist"].reset(r, 1 == r.length ? r[0] : null) : (t.vm.roleInfoConfig.data = r,
                            1 == r.length && (t.vm.roleInfoConfig.value = r[0]),
                            t.vm.roleListHtml = '<ms:autocomplate $id="roleDropdownlist" config="roleInfoConfig" on-change="onChange"></ms:autocomplate>')
                        } else
                            t.validation.area = !0,
                            n.zone_id = e.value,
                            t.setAutoOrder();
                    else {
                        switch (t.resetRole(),
                        t.validation.area = !1,
                        a.ret) {
                        case "1220":
                            t.hasRole = !1
                        }
                        t.vm.showAreaTips = !0,
                        t.vm.areaSubmitTips = a.msg,
                        t.setAutoOrder(a.msg)
                    }
                }) : (t.validation.area = !1,
                t.resetRole()) : (t.validation.area = !0,
                this.setAutoOrder())
            },
            "initAreaInfo": function() {
                var e = this.vm
                  , n = s.getInfo()
                  , t = n.game_info
                  , o = this;
                if (t && t.hasOwnProperty("check_type")) {
                    var r = t.check_type;
                    switch (r) {
                    case p.CheckType.NOCheck:
                        n.zone_id = 0,
                        o.vm.accountEditable = !1,
                        o.vm.canOrder = !0,
                        o.withoutArea = !0,
                        o.vm.areaEditable = !1,
                        o.validation.area = !0;
                        break;
                    case p.CheckType.CHECK:
                        n.zone_id = 0,
                        o.vm.accountEditable = !1,
                        o.withoutArea = !0,
                        o.vm.areaEditable = !1,
                        o.vm.canOrder = !1;
                        break;
                    case p.CheckType.CHECKRole:
                    case p.CheckType.SELECTRole:
                        o.vm.accountEditable = !0,
                        o.vm.areaEditable = !0,
                        o.vm.canOrder = !1,
                        s.loadGameJS(t, function(n) {
                            var t = b.getZoneData(n);
                            e.areaInfoConfig.data = t.data,
                            o.hasServer = t.hasServer,
                            a.lang.isArray(t.data) && 1 == t.data.length && (o.vm.areaInfoConfig.value = a.fn.extend({}, t.data[0])),
                            e.areaListHtml = '<ms:autocomplate $id="areaDropdownlist" config="areaInfoConfig" on-change="onChange"></ms:autocomplate>',
                            i.nextTick(function() {
                                e.showAreaTips = !1
                            })
                        })
                    }
                } else
                    y.go("result", {
                        "status": "error",
                        "modifyTitle": !1,
                        "displayInfo": "请确认游戏配置是否正确~"
                    })
            },
            "initGamePriceList": function(e) {
                var n = this.vm
                  , t = s.getInfo()
                  , o = Math.max(~~t.count, 1)
                  , r = "false" === s.buyInfo.cusInput
                  , c = !!s.buyInfo.showRecommend && "true" === s.buyInfo.showRecommend
                  , u = b.getGamePriceListData(t, l, "3c" == s.buyInfo.price_columns ? 6 : 8);
                n.step = u.step,
                n.gamePriceListConfig.type = "default",
                n.gamePriceListConfig.count = o % u.step == 0 ? o : u.minCount,
                c ? (f.setInfo(t, l, r),
                n.gamePriceListConfig.gameList = f.getRecommendList()) : n.gamePriceListConfig.gameList = u.data,
                n.gamePriceListConfig.cols = s.buyInfo.price_columns,
                e && (n.gamePriceListConfig.onReady = e);
                var d = !1;
                i.each(u.data, function(e, t) {
                    t.editable || t.count != n.gamePriceListConfig.count || (d = !0)
                }),
                d && (u.data[u.data.length - 1].count = "");
                var p = "games-price" + a.fn.uuid();
                n.gamePriceListHtml = '<ms:games $id="' + p + '" config="gamePriceListConfig" on-game-selected="onGameSelected"></ms:games>'
            }
        }),
        e.exports = C
    },
    "117538369": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div style="position:absolute;top:50%;left:50%;z-index:10000;" ms-css-width="{{width}}" ms-css-height="{{height}}" ms-css-margin="{{margin}}">\n\n    <div class="cp-header" ms-if="!hideHeader">\n        <!-- 标题 -->\n        <h2 class="cp-header-title">{{title}}</h2>\n        <!-- 关闭按钮 -->\n        <div class="header-icon-last" ms-on-click="close">\n            <!-- 这里可以更改icon -->\n            <i class="icon-clear" style="margin-top: 5px;"></i>\n        </div>\n    </div>\n\n\n    <div ms-if="!displayHtml"  ms-attr-id="\'dialog_body_\'+domId" style="background-color: #fff;width:100%;height:100%;position:absolute;z-index: -1;text-align:center;">\n\n        <iframe ms-if="url"  ms-attr-id="\'dialog_iframe_\'+domId" class="cp-body-iframe" ms-attr-src="url" ms-on-load="iframeOnLoad" frameborder="0" style="width: 100%;height:100%">\n        </iframe>\n\n    </div>\n\n    <div ms-html="displayHtml" ms-if="displayHtml" ms-attr-id="\'dialog_custom_\'+domId">\n    </div>\n\n    <div ms-if="dialogLoading" id="_webpay__dialog__load__"  style="position: relative;height: 100%;">\n        <div class="mdsweb-loading-wrapper abs">\n            <div class="mdsweb-loading">\n                <div class="dot"></div>\n                <div class="dot"></div>\n                <div class="dot"></div>\n            </div>\n        </div>\n    </div>\n</div>\n';
            return __p
        }
    },
    "117821206": function(e, n, t) {
        function i(e) {
            e = e || {},
            this.opt = e,
            this.errCode = e.errCode,
            this.errMsg = e.errMsg,
            this.oriParams = e.oriParams
        }
        var o = t(4);
        o.fn.extend(i.prototype, {
            "canHandle": function() {
                return "function" == typeof this.opt[this.errCode]
            },
            "_handle": function() {
                var e = this.errCode;
                "function" == typeof this.opt[e] && this.opt[e].apply(this, arguments)
            },
            "exec": function() {
                if (!this.canHandle())
                    throw Error("can not handle this kind of error code");
                this._handle.apply(this, arguments)
            }
        }),
        e.exports = i
    },
    "118085477": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<p class="tips icon-tips" style="margin-top: 0">\n    <span>当前充值<span style="color: #ff6d33"><span>{{amount}}</span>Q币</span>，QQ卡可分多次使用</span>\n</p>\n<div class="oper-to-pay" style="margin-top: 10px">\n    <a ms-on-click="pay" ms-class="btn btn-default" ms-class-1="loading:disableSubmit" ms-class-2="btn-dis:amount==0"\n        href="#">\n        <!--<span ms-if="!disableSubmit">确认支付 {{price}}元</span>-->\n        <span ms-if="!disableSubmit">确认支付</span>\n        <span><i class="icon-btn-loading"></i></span>\n    </a>\n</div>';
            return __p
        }
    },
    "118485612": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div ms-controller="kj-controller">\n    <div id="kj-bank" ms-if="showBank">\n        <ms:bankselector config="bankData" on-selected-bank="onSelectedBank"></ms:bankselector>\n        <p class="choose-type tips icon-tips error" ms-if="tips!=\'\'"><i class="icon-warn"></i>{{tips}}</p>\n        <div class="oper-to-pay">\n            <a ms-on-click="pay" ms-class="btn btn-default" ms-class-1="btn-dis:disableSubmit" ms-class-2="loading:disableSubmit" href="#">\n              <span ms-if="!disableSubmit">去支付 <span>{{price}}</span>元</span>\n                <span><i class="icon-btn-loading"></i></span>\n            </a>\n        </div>\n    </div>\n    <div id="kj-loading" class="mdsweb-loading-wrapper abs" style="display: none;height: 900px;">\n        <div class="mdsweb-loading" style="top:100px;">\n            <div class="dot"></div>\n            <div class="dot"></div>\n            <div class="dot"></div>\n        </div>\n    </div>\n    <iframe id="tenpay-iframe" frameborder="0" scrolling="no" width="100%" height="100%" ms-visible="!showBank"></iframe>\n</div>';
            return __p
        }
    },
    "118899109": function(e, n, t) {
        var i = t(4);
        e.exports = function(e, n, t, o) {
            var s = !!e.hf_rate
              , a = s ? i.math.div(1, ~~e.hf_rate) : 0
              , r = i.math.div(n, parseFloat(e.rate));
            r = i.math.sub(r, o && !o.isDisable() ? o.getAmt() : 0);
            var c = i.math.mul(a, n);
            "undefined" != typeof t && t < 1 && (r = i.math.mul(r, t),
            c = i.math.mul(c, t)),
            r <= .01 && (r = .01),
            s && c < .01 && (c = .01),
            0 == n && (r = c = 0);
            var l = {
                "showDiscount": !0,
                "price": r
            };
            return s && i.fn.extend(l, {
                "hfPrice": c,
                "hfUnitPrice": a
            }),
            l
        }
    },
    "119122155": function(e, n, t) {
        function i() {
            a.apply(this, arguments),
            this.orderInfo = null,
            this.amount = null;
            var e = String(this.buyInfo.provide_uin || this.buyInfo.openid);
            this.loginStatus = d.getLoginStatus(),
            this.isQQLogin = this.loginStatus.qq,
            this.isQQConnect = this.loginStatus.accesstoken,
            this.isWechatLogin = this.loginStatus.wechat,
            this.gameType = this.buyInfo.game_type || "default",
            this.gameAreaList = null,
            e.length >= 5 && !this.isQQConnect && (this.provide_uin = e)
        }
        var o = t(4)
          , s = t(1)
          , a = t(51768702)
          , r = t(102521382)
          , c = (t(82007299),
        t(105155243))
          , l = t(9)
          , u = t(118899109)
          , d = t(109735088)
          , p = t(49140953)
          , h = t(87796589)
          , f = t(112745811)
          , m = t(54698897);
        t(5);
        var g = t(106745080)
          , v = t(10)
          , b = {
            "ret": -9999,
            "msg": p.TEXT.INVALIDLOGIN
        };
        o.inherits(i, a),
        i.prototype.showLoginBox = function(e, n) {
            var t = this;
            switch (e) {
            case "qq":
                if (!d.canUsePTLoginCookie) {
                    n.onClose.call(t);
                    break
                }
                var i = d.getPskeyLoginStatusFromCookie();
                i && i.qq && !n.force ? n.onSuccess.call(t, new l({
                    "openid": i.openid,
                    "openkey": i.openkey,
                    "sessionid": i.session_id,
                    "sessiontype": i.session_type
                })) : r.init(function() {
                    r.setCallBack({
                        "daid": 307,
                        "onSuccess": function() {
                            var e = new l({
                                "openid": +o.cookie.get("p_uin").substr(1),
                                "openkey": o.cookie.get("p_skey"),
                                "sessionid": "uin",
                                "sessiontype": "pskey_307"
                            });
                            n.onSuccess.call(t, e)
                        },
                        "onClose": function() {
                            n.onClose.call(t)
                        }
                    }),
                    r.show()
                });
                break;
            case "wechat":
                v("switchlogin.wechat");
                var s = null;
                document.domain = "qq.com";
                try {
                    s = o.fn.delParam(["code", "state"], window.top.location.href)
                } catch (a) {}
                "https:" == location.protocol && (s = o.fn.addParam({
                    "wxAppid": this.buyInfo.wxappid
                }, location.protocol + "//" + window.location.host + "/midas/minipay_v2/views/public/wx_proxy.shtml")),
                c.init({
                    "forceMaskCss": !0,
                    "opacity": .4,
                    "bgColor": "#000000",
                    "clickClose": !1,
                    "width": 400,
                    "height": 400,
                    "appid": this.buyInfo.wxappid,
                    "targetUrl": s,
                    "onSuccess": function(e) {
                        n.onSuccess.call(t, e)
                    },
                    "onClose": function() {
                        n.onClose.call(t)
                    }
                })
            }
        }
        ,
        i.prototype.resetDelayOrder = function() {
            this.orderInfo.__delay__order = 0
        }
        ,
        i.prototype.getSwitchLoginTypeMsg = function() {
            var e = this.buyInfo.enable_change_login
              , n = [];
            return window._allowMutilLoginGame.indexOf(this.buyInfo.appid) > -1 && e && (this.isQQLogin ? n.push(["wechat", "切换微信账号"]) : this.isWechatLogin && (n.push(["qq", "切换QQ账号"]),
            "qq" == e && n.push(["wechat", "切换微信账号"]))),
            n
        }
        ,
        i.prototype.getOrderInfo = function(e) {
            var n = this;
            if (n.orderInfo)
                return void (o.lang.isFunction(e) && e(n.orderInfo));
            var t = function() {
                var e = n;
                return new s.Promise(function(t, i) {
                    n.cgi.webBuyPage(o.fn.extend({
                        "buy_quantity": n.buyInfo.buy_quantity
                    }, n.getPublicParams(), m.ParamsService(f.GAME, n.buyInfo.appid, n.buyInfo) || {}), function(s) {
                        if (~~s.ret)
                            v("webpageinfo.fail", {
                                "resultinfo": {
                                    "code": s.ret
                                }
                            }),
                            i(s);
                        else {
                            o.handleDisableChannel(s.info),
                            o.discount.initNoDiscountInterval(s.info);
                            var a = e.buyInfo.recommendList;
                            a && /[\d.,]/.test(a) && (s.info.recommend_list = "[" + a + "]"),
                            "true" === e.buyInfo.canChangeCount || "true" === e.buyInfo.showRecommend ? n.cgi.getCouponList({
                                "action": "query_valid_sp_coupons",
                                "sp_status": "COUPON_MULTCOND%3B1%2CEFFECT%3B9%2CEFFECT",
                                "curpage": 1,
                                "pagesize": 9
                            }, function(e) {
                                if (!~~e.ret && s.info.mp_info) {
                                    var n = o.fn.safeGet(s, "info.mp_info.unicoupon_mpinfo.recommend");
                                    s.info.mp_info.unicoupon_mpinfo = e.mp_info.unicoupon_mpinfo,
                                    s.info.mp_info.unicoupon_mpinfo_ex = e.mp_info.unicoupon_mpinfo_ex,
                                    n && (s.info.mp_info.unicoupon_mpinfo.recommend = n)
                                }
                                t(s.info)
                            }) : t(s.info)
                        }
                    }),
                    m.UpdateBankList(n.cgi)
                }
                )
            };
            if (this.gameType == g.Type.NOHOSTING)
                if (this.isQQLogin || this.isWechatLogin) {
                    var i = [];
                    i.push(t()),
                    s.Promise.all(i).then(function() {
                        var t = arguments[0];
                        n.orderInfo = t[0],
                        "true" === n.buyInfo.showRecommend && (n.orderInfo.__delay__order = 1),
                        n.orderInfo.offer_id && window.__gameRate && window.__gameRate[n.orderInfo.offer_id] && (n.orderInfo.rate = window.__gameRate[n.orderInfo.offer_id]),
                        n.orderInfo.main_bind_info = t[1] || {},
                        v("page.data"),
                        o.lang.isFunction(e) && e(n.orderInfo)
                    })["catch"](function() {
                        var n = arguments[0];
                        o.lang.isFunction(e) && e(!1, n)
                    })
                } else
                    this.showLoginBox("qq", {
                        "onSuccess": function(e) {
                            var n = e.getSessionParam();
                            n.openid = decodeURIComponent(n.openid),
                            n.openkey = decodeURIComponent(n.openkey),
                            location.href = o.fn.addParam(n, location.href)
                        },
                        "onClose": function() {
                            e(!1, o.fn.extend({
                                "isValidUser": !1
                            }, b))
                        }
                    });
            else
                t().then(function(t) {
                    n.orderInfo = t,
                    e(t)
                })["catch"](function(n) {
                    e(!1, n)
                })
        }
        ,
        i.prototype.setPayFor = function() {
            this.payFor = this.provide_uin == this.buyInfo.openid ? h.SELF : h.SEND
        }
        ,
        i.prototype.setProvideUin = function(e) {
            this.provide_uin = e
        }
        ,
        i.prototype.getPayFor = function() {
            return this.setPayFor(),
            this.payFor
        }
        ,
        i.prototype.loadGameJS = function(e, n) {
            var t = this;
            if (this.gameAreaList)
                n(this.gameAreaList);
            else {
                var i = e["area_js_charset"] || "UTF-8";
                s.ajax({
                    "type": "GET",
                    "url": e["area_js_url"] + "?r=" + (new Date).getTime(),
                    "data": null,
                    "charset": i,
                    "contentType": "application/x-www-form-urlencoded; charset=" + i,
                    "success": function() {
                        t.gameAreaList = window[e["area_js_svr_name"]] ? window[e["area_js_svr_name"]]["STD_DATA"] : [],
                        n(t.gameAreaList)
                    },
                    "dataType": "script"
                })
            }
        }
        ,
        i.prototype.getRoleList = function(e, n) {
            var t = o.fn.extend(this.getPublicParams(), {
                "zoneid": e,
                "game_scene": "dq_pay",
                "provide_uin": this.provide_uin
            });
            "uin" !== this.getSession().sessionid && this.getPayFor() == h.SELF && delete t.provide_uin,
            this.cgi.getRoleList(t, function(e) {
                ~~e.ret ? o.lang.isFunction(n) && n(!1, e) : o.lang.isFunction(n) && n(!0, e)
            })
        }
        ,
        i.prototype.getPayUin = function() {
            return this.buyInfo.openid
        }
        ,
        i.prototype.getInfo = function() {
            return this.orderInfo
        }
        ,
        i.prototype.setAmount = function(e) {
            this.orderInfo.count = e
        }
        ,
        i.prototype.getName = function() {
            return this.orderInfo.offer_name
        }
        ,
        i.prototype.getAmount = function() {
            return this.orderInfo.count
        }
        ,
        i.prototype.getPrice = function(e) {
            return this.orderInfo ? u(this.orderInfo, this.getAmount(), e) : null
        }
        ,
        i.prototype.getUnitPrice = function() {
            return this.orderInfo ? o.math.div(1, parseFloat(this.orderInfo.rate)) : null
        }
        ,
        i.prototype.getUnitName = function() {
            return this.orderInfo ? this.orderInfo.game_info ? this.orderInfo.game_info.unit_name || this.orderInfo.product_name : this.orderInfo.product_name : null
        }
        ,
        e.exports = new i
    },
    "119561448": function(e, n, t) {
        var i = t(1)
          , o = null
          , s = "_cp__mask__"
          , a = 0;
        e.exports = {
            "show": function(e) {
                e = e || {},
                o = document.getElementById(s);
                var n = e.hasOwnProperty("opacity") ? e.opacity : .3
                  , t = {
                    "top": e.top || "0px",
                    "left": e.left || "0px",
                    "opacity": n,
                    "filter": "alpha(opacity=" + 100 * n + ")",
                    "display": "block"
                };
                if (e.bgColor && (t["background-color"] = e.bgColor),
                o)
                    e.forceCss ? i(o).css(i.mix(t, {
                        "z-index": e.zIndex || 9998,
                        "display": "block"
                    })) : i(o).css(i.mix(t, {
                        "display": "block"
                    }));
                else {
                    var r = document.createElement("div");
                    r.id = s,
                    r.className = "cp_mask",
                    i(r).css(i.mix(t, {
                        "z-index": e.zIndex || 9998,
                        "display": "block"
                    })),
                    document.body.appendChild(r)
                }
                document.getElementById(s).onclick = function() {
                    "function" == typeof e.onMaskClick && e.onMaskClick()
                }
                ,
                a++
            },
            "hide": function() {
                a--,
                a > 0 || i(document.getElementById(s)).css({
                    "display": "none"
                })
            },
            "remove": function() {
                a = 0;
                var e = document.getElementById(s);
                e && (e.onclick = null,
                document.body.removeChild(e))
            }
        }
    },
    "119656648": function(e, n, t) {
        var i = t(112745811)
          , o = t(72074753)
          , s = function(e) {
            this.store = e.store
        };
        s.prototype = {
            "tenpayOrder": function(e, n) {
                var t = {
                    "pay_method": this.store.hasBindCard() ? "pccft:75" : "pccft:72"
                }
                  , i = this;
                this.store.buy(avalon.mix(t, e), function(e) {
                    return ~~e.ret ? (n(e),
                    i.secondLoginIsInvalid(e.ret)) : (n(e),
                    !0)
                })
            },
            "secondLoginIsInvalid": function(e) {
                return ["146", "1905"].indexOf(String(e)) > -1
            },
            "setAutoPay": function(e) {
                if (this.store.setAutoPay) {
                    var n = "1" == e.autopay;
                    this.store.setAutoPay && this.store.setAutoPay(n),
                    this.store.report(String.format("{channel}.auto.click", {
                        "channel": o.KJ
                    }), {
                        "action": n ? 1 : 0
                    })
                }
            },
            "getServiceCode": function() {
                return (this.store.type == i.MONTH ? this.store.getServiceCode() : this.store.type).toUpperCase()
            },
            "getName": function() {
                return this.store.getName ? this.store.getName() : ""
            }
        };
        e.exports = s
    },
    "119721272": function(e, n, t) {
        var i = t(1)
          , o = t(18)
          , s = t(4)
          , a = t(122180889)
          , r = t(119656648)
          , c = t(81089886)
          , l = function(e) {
            var n = s.fn.getParam("pf", null);
            return n = n ? n : "15200",
            "stat_type=21&stat_data=fp_1_" + e + "_" + n
        }
          , u = function() {
            var e = s.fn.getParam("cft_skin");
            return e || "minipay1"
        }
          , d = function(e, n, t) {
            if (n && !~~n.ret) {
                var i = n.info.channel_info.bank_info
                  , o = this;
                if (this.emit("load", !0),
                i && "string" == typeof i) {
                    var a = ""
                      , r = "&cross_domain=1&pay_scene=10&stat_comm=" + encodeURIComponent(l(this.tenpayCgi.getServiceCode())) + "&style=" + u()
                      , c = s.cookie.get("uin")
                      , d = s.cookie.get("skey")
                      , p = "https://www.tenpay.com/cgi-bin/v1.0/communitylogin.cgi?win=self&p_uin=" + c + "&skey=" + d + "&u1=";
                    try {
                        a = c && d ? p + encodeURIComponent(decodeURIComponent(i) + r) : decodeURIComponent(i) + r
                    } catch (h) {
                        o.store.report("KJ.jumpurl.error")
                    }
                    return this.ready = !1,
                    this.avalonTenpayIfrm.attr("src", a),
                    this.tenpayStartTime = new Date,
                    void this._timeoutPool.push(setTimeout(function() {
                        o.emit("load", !1)
                    }, 3e3))
                }
            }
            this.emit("load", !1),
            this.emit("error", n)
        }
          , p = function(e) {
            if (!e.store)
                throw Error("tenpay api initialization need the cgi service that include the order");
            this.tenpayXcross = new c,
            this._handlers = {},
            this.tenpayCgi = new r({
                "store": e.store
            }),
            this.store = e.store,
            this.tenpayIfrm = e.iframe,
            this.avalonTenpayIfrm = i(e.iframe),
            this._timeoutPool = [],
            this.ready = !1;
            var n = this;
            this.tenpayXcross.receiveMessage(function(e) {
                var t;
                try {
                    t = JSON.parse(e),
                    n.trigger(String.format("tenpay.{eventType}", {
                        "eventType": t.msg
                    }), t)
                } catch (i) {
                    n.trigger("error", i)
                }
            })
        };
        i.mix(p.prototype, o, {
            "setAutoPay": function(e) {
                if (this.ready) {
                    var n = JSON.stringify({
                        "msg": "autopay",
                        "value": e.show ? 1 : 0,
                        "service_code": this.tenpayCgi.getServiceCode(),
                        "service_name": this.tenpayCgi.getName()
                    });
                    i.log("nofityTenpay.autopay", n),
                    this.tenpayXcross.postMessage(n, this.tenpayIfrm.contentWindow)
                }
            },
            "setPrice": function(e) {
                if (this.ready) {
                    var n = JSON.stringify({
                        "msg": "fee",
                        "amount": e.amount,
                        "fee": e.totalPrice,
                        "qb": e.isRechargeQB ? 1 : 0
                    });
                    i.log("nofityTenpay.setPrice", n),
                    this.tenpayXcross.postMessage(n, this.tenpayIfrm.contentWindow)
                }
            },
            "goPay": function(e) {
                if (this.ready) {
                    var n = JSON.stringify({
                        "msg": "pay",
                        "url": e.url,
                        "service": this.tenpayCgi.getServiceCode().toUpperCase(),
                        "guid": e.guid || ""
                    });
                    i.log("goPay", n),
                    this.tenpayXcross.postMessage(n, this.tenpayIfrm.contentWindow)
                }
            },
            "setCgiLoadTime": function(e) {
                var n = JSON.stringify({
                    "msg": "cgi_load",
                    "time": e
                });
                this.tenpayXcross.postMessage(n, this.tenpayIfrm.contentWindow)
            },
            "resize": function(e, n) {
                this.emit("resize", {
                    "width": ~~e,
                    "height": ~~n
                }),
                ~~e && this.avalonTenpayIfrm.css("width", ~~e),
                ~~n && this.avalonTenpayIfrm.css("height", ~~n);
                try {} catch (t) {}
            },
            "destory": function() {
                this.off(),
                this.tenpayXcross.deReceiveMessage(),
                i.each(this._timeoutPool, function(e, n) {
                    clearTimeout(n)
                });
                for (var e in this)
                    "destory" != e && (this[e] = null)
            },
            "show": function() {
                this.avalonTenpayIfrm && this.avalonTenpayIfrm.css("display", "block")
            },
            "hide": function() {
                this.avalonTenpayIfrm && this.avalonTenpayIfrm.css("display", "none")
            },
            "open": function(e) {
                var n = this;
                i.bind(window, "unload", function() {
                    try {
                        n.emit("lock", !1)
                    } catch (e) {}
                }),
                this.tenpayCgi.tenpayOrder(e, d.bind(this, e))
            }
        }),
        e.exports = function(e) {
            var n = new p(e);
            return a(n),
            n
        }
    },
    "120707620": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div>\n    <div>\n        <div class="choose-type">\n            <ms:banktypechoose config="bankTypeListConfig" on-change="handleChooseBankType"></ms:banktypechoose>\n        </div>\n        <ms:bankchoose config="bankListConfig" on-change="handleChooseBank"></ms:bankchoose>\n        <div class="choose-type">\n            <ms:typechoose config="cardTypeConfig" on-change="handleChooseCardType"></ms:typechoose>\n        </div>\n    </div>\n</div>';
            return __p
        }
    },
    "121508273": function(module, exports) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div class="quantity-input"  ms-css-width="{{unit?\'\':width}}" ms-class-1="with-unit:unit">\n\n    <button   hidefocus="true" type="button"   ms-class="reduce " ms-click="decrease" ms-attr-id="btn1">\n        <i class="icon-reduce"></i>\n    </button>\n\n\n        <div class="input-area"  >\n\n            <input ms-if="!unit"  class="quantity-input-tx" ms-css-width="{{width-38*2}}" onpaste="return false"\n                   ms-on-keydown="keydown"\n                   ms-on-focus="focus"   ms-on-blur="blur"  ms-attr-value="value" ms-attr-id="id1"/>\n\n            <input ms-if="unit" class="quantity-input-tx" onpaste="return false"\n                   ms-on-keydown="keydown"\n                   ms-on-focus="focus"   ms-on-blur="blur"  ms-attr-value="value" ms-attr-id="id1"/>\n            <span ms-if="unit" >{{unit}}</span>\n        </div>\n\n\n    <button type="button"   ms-click="increase" hidefocus="true"  ms-class="add" ms-attr-id="btn2">\n        <i class="icon-add"></i>\n    </button>\n\n</div>\n\n\n';
            return __p
        }
    },
    "121800003": function(module, exports, __webpack_require__) {
        module.exports = function(obj) {
            obj || (obj = {});
            var __t, __p = "";
            with (obj)
                __p += '<div ms-controller="couponlist">\n    <div ms-visible="active" ms-css-bottom="bottom" class="pop-vouchers-list" id="coupon-list-container" ms-on-mouseleave="showCouponList(false,$event)">\n        <ul ms-visible="!isLoading">\n            <li ms-class-1="selected:el.id==defaultCoupon" ms-repeat="couponListInView" ms-on-click="handleClick(el,$event)">\n                <div ms-class-1="vouchers-con" ms-if="el.without">\n                    <span class="no-use">不使用优惠券</span>\n                    <i class="icon-corner-checked"></i>\n                </div>\n                <div ms-class-1="vouchers-con" ms-if="el.disable&&!el.isFrozen" ms-class-2="disable:el.disable">\n                    <span class="price"><b>{{el.amt}}</b>元</span>\n                    <span class="name"><em>{{el.name}}</em><i class="icon-special" ms-if="el.tips">{{el.tips}}</i></span>\n                    <span class="condition font-10px">{{el.desc}}</span>\n                    <span class="deadline font-10px">{{el.endDate}}前有效</span>\n                </div>\n                <div ms-if="el.isValid" ms-class-1="vouchers-con">\n                    <span class="price"><b>{{el.amt}}</b>元</span>\n                    <span class="name"><em>{{el.name}}</em><i class="icon-special" ms-if="el.tips">{{el.tips}}</i></span>\n                    <span class="condition font-10px">{{el.desc}}</span>\n                    <span class="deadline font-10px">{{el.endDate}}前有效</span>\n                    <i class="icon-corner-checked"></i>\n                </div>\n                <div ms-class-1="vouchers-con" ms-if="el.isFrozen&&!el.expired" ms-class-2="freeze:el.isFrozen" ms-class-3="loading:el.isLoading">\n                    <span class="price"><b>{{el.amt}}</b>元</span>\n                    <span class="name"><em>{{el.name}}</em><i class="icon-special" ms-if="el.tips">{{el.tips}}</i></span>\n                    <span class="condition font-10px">{{el.desc}}</span>\n                    <span class="deadline font-10px">{{el.endDate}}前有效</span>\n                    <a class="btn-activate" ms-on-click="handleActive(el,$event)" href="#">激活</a>\n                    <!--TODO: 游戏大厅内嵌时，href="javascript:void(0);"回滚请求被浏览器取消, 可能触发了IE的bug,需要加onclick="return false; 简单改法是直接改成href="#"-->\n                </div>\n                <div class="vouchers-con expired" ms-if="el.expired">\n                    <span class="price"><b>{{el.amt}}</b>元</span>\n                    <span class="name"><em>{{el.name}}</em><i class="icon-special" ms-if="el.tips">{{el.tips}}</i></span>\n                    <span class="condition font-10px">{{el.desc}}</span>\n                    <span class="deadline font-10px">{{el.endDate}}前有效</span>\n                    <i class="icon-expired"></i>\n                </div>\n            </li>\n        </ul>\n        <div ms-visible="isLoading" class="mdsweb-loading-wrapper abs" style="z-index:1000;background:none">\n            <div class="mdsweb-loading">\n                <div class="dot"></div>\n                <div class="dot"></div>\n                <div class="dot"></div>\n            </div>\n        </div>\n        <!-- 分页 -->\n        <div class="topage">\n            <div class="tpage">\n                <div class="tpage-left">\n                    <span class="tpage-left-btn" ms-on-click="handlePrevPage($event)" style="*top: -5px">\n                        <img src="' + (null == (__t = "//midas.gtimg.cn/midas/minipay_v2/" + {
                    "images/QB.png": "images/QB.046c6f365b9796e36ed2f96b4924b4b4.png",
                    "images/bank_ico.png": "images/bank_ico.a40d39d1c3ad47a76d4a2c9e09db95a9.png",
                    "images/bank_ico_disabled.png": "images/bank_ico_disabled.8a7a286a51ad88d29a757039efea7f7c.png",
                    "images/bg-freeze.png": "images/bg-freeze.3e6351cd9f13bc83e00b8feeb2032c73.png",
                    "images/bg-freeze@2x.png": "images/bg-freeze@2x.591c20bc893f97fff2765ef9c6f40d80.png",
                    "images/btn-loading.gif": "images/btn-loading.8feee980ad8fd43b991217d3dfb9e687.gif",
                    "images/business.png": "images/business.e07149b49789269906b89301ce226937.png",
                    "images/diamond.png": "images/diamond.954744fed159ef6429a20c398577f82b.png",
                    "images/disabledSprites.png": "images/disabledSprites.adeac1e5a6c4b702af79e961192dffe0.png",
                    "images/disabledSprites@2x.png": "images/disabledSprites@2x.21f2f764c05367bab017964d369809c7.png",
                    "images/dnf-code.png": "images/dnf-code.7aa2494d0edbba7b0fcdc078c63d5f06.png",
                    "images/hd-logo.png": "images/hd-logo.e1e8194358ccf6ec227c29cc89de07d7.png",
                    "images/headerSprites.png": "images/headerSprites.02b55a0447b7b1dad0c4877f628d09b2.png",
                    "images/headerSprites@2x.png": "images/headerSprites@2x.96d3e4193f4542347e1df88b5a79a952.png",
                    "images/icon-arrow.png": "images/icon-arrow.33131a0d46a8de5968ded4e71c88fd73.png",
                    "images/icon-arrow@2x.png": "images/icon-arrow@2x.36f307dc4cac2a5142f301bb3706d823.png",
                    "images/icon-super-vip.png": "images/icon-super-vip.d8b5f3dc2ed96a3f24033cf008f03161.png",
                    "images/icon-unactive.png": "images/icon-unactive.1e5aea7a46826cfdd3228339b74207e4.png",
                    "images/icon-unactive@2x.png": "images/icon-unactive@2x.b264111d8f3e6bae4dce36ded1757270.png",
                    "images/icon-year-vip.png": "images/icon-year-vip.20053bc768d6cf167f4d8ad1e002101f.png",
                    "images/ie6sprite.png": "images/ie6sprite.62af561189af0d2d7130543b69091eb8.png",
                    "images/iframedemo.png": "images/iframedemo.35dc2749315268d65bed983044c959e8.png",
                    "images/kjzf.jpg": "images/kjzf.02d56ee8f7ad1d92d38738f8b000b581.jpg",
                    "images/li_square.png": "images/li_square.afe4283bb9da445e8ebcacf4a08e5089.png",
                    "images/loading.gif": "images/loading.745836985d1bb3f878b75069d665c865.gif",
                    "images/loading@2x.gif": "images/loading@2x.e1fc478bed27d875ac688ce01ee0530b.gif",
                    "images/logo-cjclub.png": "images/logo-cjclub.f2af1de653b8885728cc04c7dd8cd492.png",
                    "images/logo-ltmclub.png": "images/logo-ltmclub.6cd05f04dc73637c41d7b9addbba1354.png",
                    "images/logo_l.png": "images/logo_l.b495b3ccc969735499d165efe090894c.png",
                    "images/lolSprites.png": "images/lolSprites.63e7decd484e940069a81596f7ef7490.png",
                    "images/lolSprites@2x.png": "images/lolSprites@2x.d2c5465c7dde8a0982887e27d42c9913.png",
                    "images/paySprite.png": "images/paySprite.4d6a9ca97b68160d957c19332921687e.png",
                    "images/paySprite@2x.png": "images/paySprite@2x.6b8cb3e3bf0e2b5e2c49803262fe17f6.png",
                    "images/prop130130.jpg": "images/prop130130.de2908a42968837672971b1a8d2c215e.jpg",
                    "images/prop130136.jpg": "images/prop130136.a21ae6f79b4d711694d0f6d54412fb04.jpg",
                    "images/prop15090.jpg": "images/prop15090.038c369b2c57d94448786eb950cd053c.jpg",
                    "images/prop8060.jpg": "images/prop8060.a088890c86cf64941e64b89fbaa40a46.jpg",
                    "images/prop9090.jpg": "images/prop9090.32b9b9cb81814783fc0b58a93d7b94e7.jpg",
                    "images/qq-login.png": "images/qq-login.0b2c3d42230f4231c06e37ce4697f8b2.png",
                    "images/qqcjhy.png": "images/qqcjhy.97827b1468642b40b7abe774467c623d.png",
                    "images/qqhy.png": "images/qqhy.49d4db99c62068ee201cb0a1868d08e9.png",
                    "images/qr-code.jpg": "images/qr-code.003a7e689398041636d833cfde797503.jpg",
                    "images/qr-code.png": "images/qr-code.6cd5915a7c9d4d747c64d08ac0744eb2.png",
                    "images/qr-loading.gif": "images/qr-loading.e6df036d9ecdfee901d2ad5f8ffecbdf.gif",
                    "images/sprite.png": "images/sprite.5e2f61e2dedbc68b8b5c81275ba25d71.png",
                    "images/sprite@2x.png": "images/sprite@2x.c6e1a4965de7a4069e10e6f1bb463a8c.png",
                    "images/tooltip.png": "images/tooltip.a33bc45a3a2f9f1d1bc82e7da4556446.png",
                    "images/tpage-left.png": "images/tpage-left.528507587363213c439b0b52baf76604.png",
                    "images/tpage-right.png": "images/tpage-right.2c52d7e4dd27111cf4e383fcd3d0972d.png",
                    "images/translucent-bg.png": "images/translucent-bg.ab518231f1e2ebbbf22914b9f3dc2735.png",
                    "images/verify-code.jpg": "images/verify-code.914eaf818e50a7213757f4dbd1d6a748.jpg",
                    "images/waiting.gif": "images/waiting.eb1ed90dcd39edf99d1fc73ccb8089ec.gif",
                    "images/webloading.gif": "images/webloading.6aa85f8ba65fd1fae3b9a9c0b127a4e2.gif",
                    "images/wx-login.png": "images/wx-login.97feabdd5bc670566116134c28886f11.png",
                    "images/clock/apple-ligth.png": "images/clock/apple-ligth.1e80b86e0f63be4e71eed0bc596da46d.png",
                    "images/clock/clock-bg.png": "images/clock/clock-bg.03e2b940a24612a3f2b436fdb5b2937d.png",
                    "images/clock/clock.png": "images/clock/clock.e52c52857e4844ddb9c879036db03bca.png",
                    "images/clock/footer-left.png": "images/clock/footer-left.52b5e9cca4a6529bec0ecc9cec86b9d9.png",
                    "images/clock/footer-right.png": "images/clock/footer-right.01cb75a64ebf3b90bad391582a4e3358.png",
                    "images/clock/hand-left.png": "images/clock/hand-left.8ba3d6bf45fd8d406dcd77a3613daafe.png",
                    "images/clock/hand-right.png": "images/clock/hand-right.2d42711942d0647a008377d53606235e.png",
                    "images/clock/phone.png": "images/clock/phone.4ae62d4f39d21dd600f1c33ae362ec2b.png",
                    "images/header/icon-back.png": "images/header/icon-back.2f1709df43b526b92ea68fe1c98dbf47.png",
                    "images/header/icon-back@2x.png": "images/header/icon-back@2x.b22db59448bba6f1b862f22a6d105684.png",
                    "images/header/icon-checkbox-checked-2.png": "images/header/icon-checkbox-checked-2.b33d76facb2e978e7624a6cfb752e64f.png",
                    "images/header/icon-checkbox-checked-2@2x.png": "images/header/icon-checkbox-checked-2@2x.74f1f31bf0b4b73e3e34565ca1984fd0.png",
                    "images/header/icon-checkbox.png": "images/header/icon-checkbox.e35f493b67f0d3693f71c737ed891e9d.png",
                    "images/header/icon-checkbox@2x.png": "images/header/icon-checkbox@2x.66b9580835384f8efcdf49b8988e767f.png",
                    "images/header/icon-clear.png": "images/header/icon-clear.13fb5e158c7d442d92ee4881aead2399.png",
                    "images/header/icon-clear@2x.png": "images/header/icon-clear@2x.ddc6a8d06ea6c9bba85ed09df261ebe9.png",
                    "images/header/icon-info.png": "images/header/icon-info.e4787b0c1d704bada2fa28750fea11e4.png",
                    "images/header/icon-info@2x.png": "images/header/icon-info@2x.2a9dd2cdb2113184c4757ff9af06432c.png",
                    "images/lol/QB.png": "images/lol/QB.dd05309099f3013cd41454d040014177.png",
                    "images/lol/btn-default-active.png": "images/lol/btn-default-active.e9d11e9bc22b370177ff018b2b257782.png",
                    "images/lol/btn-default-hover.png": "images/lol/btn-default-hover.c9816edfd2083cb32369fc4fefd65d91.png",
                    "images/lol/btn-default.png": "images/lol/btn-default.a018ef30b0653d035700c9baa3f51541.png",
                    "images/lol/btn-primary-active.png": "images/lol/btn-primary-active.ff5df362b08a2b89bb09e9d83b163eb9.png",
                    "images/lol/btn-primary-hover.png": "images/lol/btn-primary-hover.ae273696c612bf79bf038a6e1167c38a.png",
                    "images/lol/btn-primary.png": "images/lol/btn-primary.eb328c97ac018e429bef618274a94408.png",
                    "images/lol/btnbg_channel.png": "images/lol/btnbg_channel.fb3ab8335aab684c09f7046dfe2a8123.png",
                    "images/lol/diamond-lol.png": "images/lol/diamond-lol.9035640a41a8dbf190c65ce20400904a.png",
                    "images/lol/icon-marketing-l.png": "images/lol/icon-marketing-l.30707f3ada2b9f89c879c703dcc2d8bb.png",
                    "images/lol/icon-marketing-r.png": "images/lol/icon-marketing-r.ab1b4f70477b8bff13aff6489b4bdf32.png",
                    "images/lol/lol-background.jpg": "images/lol/lol-background.6638765318894a9f424dc3b63c22865b.jpg",
                    "images/lol/lolSprites.png": "images/lol/lolSprites.2029b18a335497f29c073fa9b4b75435.png",
                    "images/lol/lolSprites@2x.png": "images/lol/lolSprites@2x.0f9bce92fb6f102a20bf06f282193161.png",
                    "images/lol/webloading.gif": "images/lol/webloading.05a9dc49392193d8ad757da5ab6d27f2.gif",
                    "images/logo/cf/90.png": "images/logo/cf/90.e7f4ff8119a1dd352b29abb14428c158.png",
                    "images/logo/nz/90.png": "images/logo/nz/90.11b4039786c28f6ea00232c677e7a7f7.png",
                    "images/logo/qsj/90.png": "images/logo/qsj/90.72d3b83af1d36557ff2fec537bae4e19.png"
                }["images/tpage-left.png"]) ? "" : __t) + '" class="tpage-left-btn-img">\n                    </span>\n                </div>\n                <p class="tpage-center">\n                    <span class="tpage-now" id="tpage-now">{{currentPage}}</span> / <span class="tpage-all" id="tpage-all">{{totalPages}}</span> \n                </p>\n                <div class="tpage-right">\n                    <span class="tpage-right-btn" ms-on-click="handleNextPage($event)" style="*top: -5px">\n                        <img src="' + (null == (__t = "//midas.gtimg.cn/midas/minipay_v2/" + {
                    "images/QB.png": "images/QB.046c6f365b9796e36ed2f96b4924b4b4.png",
                    "images/bank_ico.png": "images/bank_ico.a40d39d1c3ad47a76d4a2c9e09db95a9.png",
                    "images/bank_ico_disabled.png": "images/bank_ico_disabled.8a7a286a51ad88d29a757039efea7f7c.png",
                    "images/bg-freeze.png": "images/bg-freeze.3e6351cd9f13bc83e00b8feeb2032c73.png",
                    "images/bg-freeze@2x.png": "images/bg-freeze@2x.591c20bc893f97fff2765ef9c6f40d80.png",
                    "images/btn-loading.gif": "images/btn-loading.8feee980ad8fd43b991217d3dfb9e687.gif",
                    "images/business.png": "images/business.e07149b49789269906b89301ce226937.png",
                    "images/diamond.png": "images/diamond.954744fed159ef6429a20c398577f82b.png",
                    "images/disabledSprites.png": "images/disabledSprites.adeac1e5a6c4b702af79e961192dffe0.png",
                    "images/disabledSprites@2x.png": "images/disabledSprites@2x.21f2f764c05367bab017964d369809c7.png",
                    "images/dnf-code.png": "images/dnf-code.7aa2494d0edbba7b0fcdc078c63d5f06.png",
                    "images/hd-logo.png": "images/hd-logo.e1e8194358ccf6ec227c29cc89de07d7.png",
                    "images/headerSprites.png": "images/headerSprites.02b55a0447b7b1dad0c4877f628d09b2.png",
                    "images/headerSprites@2x.png": "images/headerSprites@2x.96d3e4193f4542347e1df88b5a79a952.png",
                    "images/icon-arrow.png": "images/icon-arrow.33131a0d46a8de5968ded4e71c88fd73.png",
                    "images/icon-arrow@2x.png": "images/icon-arrow@2x.36f307dc4cac2a5142f301bb3706d823.png",
                    "images/icon-super-vip.png": "images/icon-super-vip.d8b5f3dc2ed96a3f24033cf008f03161.png",
                    "images/icon-unactive.png": "images/icon-unactive.1e5aea7a46826cfdd3228339b74207e4.png",
                    "images/icon-unactive@2x.png": "images/icon-unactive@2x.b264111d8f3e6bae4dce36ded1757270.png",
                    "images/icon-year-vip.png": "images/icon-year-vip.20053bc768d6cf167f4d8ad1e002101f.png",
                    "images/ie6sprite.png": "images/ie6sprite.62af561189af0d2d7130543b69091eb8.png",
                    "images/iframedemo.png": "images/iframedemo.35dc2749315268d65bed983044c959e8.png",
                    "images/kjzf.jpg": "images/kjzf.02d56ee8f7ad1d92d38738f8b000b581.jpg",
                    "images/li_square.png": "images/li_square.afe4283bb9da445e8ebcacf4a08e5089.png",
                    "images/loading.gif": "images/loading.745836985d1bb3f878b75069d665c865.gif",
                    "images/loading@2x.gif": "images/loading@2x.e1fc478bed27d875ac688ce01ee0530b.gif",
                    "images/logo-cjclub.png": "images/logo-cjclub.f2af1de653b8885728cc04c7dd8cd492.png",
                    "images/logo-ltmclub.png": "images/logo-ltmclub.6cd05f04dc73637c41d7b9addbba1354.png",
                    "images/logo_l.png": "images/logo_l.b495b3ccc969735499d165efe090894c.png",
                    "images/lolSprites.png": "images/lolSprites.63e7decd484e940069a81596f7ef7490.png",
                    "images/lolSprites@2x.png": "images/lolSprites@2x.d2c5465c7dde8a0982887e27d42c9913.png",
                    "images/paySprite.png": "images/paySprite.4d6a9ca97b68160d957c19332921687e.png",
                    "images/paySprite@2x.png": "images/paySprite@2x.6b8cb3e3bf0e2b5e2c49803262fe17f6.png",
                    "images/prop130130.jpg": "images/prop130130.de2908a42968837672971b1a8d2c215e.jpg",
                    "images/prop130136.jpg": "images/prop130136.a21ae6f79b4d711694d0f6d54412fb04.jpg",
                    "images/prop15090.jpg": "images/prop15090.038c369b2c57d94448786eb950cd053c.jpg",
                    "images/prop8060.jpg": "images/prop8060.a088890c86cf64941e64b89fbaa40a46.jpg",
                    "images/prop9090.jpg": "images/prop9090.32b9b9cb81814783fc0b58a93d7b94e7.jpg",
                    "images/qq-login.png": "images/qq-login.0b2c3d42230f4231c06e37ce4697f8b2.png",
                    "images/qqcjhy.png": "images/qqcjhy.97827b1468642b40b7abe774467c623d.png",
                    "images/qqhy.png": "images/qqhy.49d4db99c62068ee201cb0a1868d08e9.png",
                    "images/qr-code.jpg": "images/qr-code.003a7e689398041636d833cfde797503.jpg",
                    "images/qr-code.png": "images/qr-code.6cd5915a7c9d4d747c64d08ac0744eb2.png",
                    "images/qr-loading.gif": "images/qr-loading.e6df036d9ecdfee901d2ad5f8ffecbdf.gif",
                    "images/sprite.png": "images/sprite.5e2f61e2dedbc68b8b5c81275ba25d71.png",
                    "images/sprite@2x.png": "images/sprite@2x.c6e1a4965de7a4069e10e6f1bb463a8c.png",
                    "images/tooltip.png": "images/tooltip.a33bc45a3a2f9f1d1bc82e7da4556446.png",
                    "images/tpage-left.png": "images/tpage-left.528507587363213c439b0b52baf76604.png",
                    "images/tpage-right.png": "images/tpage-right.2c52d7e4dd27111cf4e383fcd3d0972d.png",
                    "images/translucent-bg.png": "images/translucent-bg.ab518231f1e2ebbbf22914b9f3dc2735.png",
                    "images/verify-code.jpg": "images/verify-code.914eaf818e50a7213757f4dbd1d6a748.jpg",
                    "images/waiting.gif": "images/waiting.eb1ed90dcd39edf99d1fc73ccb8089ec.gif",
                    "images/webloading.gif": "images/webloading.6aa85f8ba65fd1fae3b9a9c0b127a4e2.gif",
                    "images/wx-login.png": "images/wx-login.97feabdd5bc670566116134c28886f11.png",
                    "images/clock/apple-ligth.png": "images/clock/apple-ligth.1e80b86e0f63be4e71eed0bc596da46d.png",
                    "images/clock/clock-bg.png": "images/clock/clock-bg.03e2b940a24612a3f2b436fdb5b2937d.png",
                    "images/clock/clock.png": "images/clock/clock.e52c52857e4844ddb9c879036db03bca.png",
                    "images/clock/footer-left.png": "images/clock/footer-left.52b5e9cca4a6529bec0ecc9cec86b9d9.png",
                    "images/clock/footer-right.png": "images/clock/footer-right.01cb75a64ebf3b90bad391582a4e3358.png",
                    "images/clock/hand-left.png": "images/clock/hand-left.8ba3d6bf45fd8d406dcd77a3613daafe.png",
                    "images/clock/hand-right.png": "images/clock/hand-right.2d42711942d0647a008377d53606235e.png",
                    "images/clock/phone.png": "images/clock/phone.4ae62d4f39d21dd600f1c33ae362ec2b.png",
                    "images/header/icon-back.png": "images/header/icon-back.2f1709df43b526b92ea68fe1c98dbf47.png",
                    "images/header/icon-back@2x.png": "images/header/icon-back@2x.b22db59448bba6f1b862f22a6d105684.png",
                    "images/header/icon-checkbox-checked-2.png": "images/header/icon-checkbox-checked-2.b33d76facb2e978e7624a6cfb752e64f.png",
                    "images/header/icon-checkbox-checked-2@2x.png": "images/header/icon-checkbox-checked-2@2x.74f1f31bf0b4b73e3e34565ca1984fd0.png",
                    "images/header/icon-checkbox.png": "images/header/icon-checkbox.e35f493b67f0d3693f71c737ed891e9d.png",
                    "images/header/icon-checkbox@2x.png": "images/header/icon-checkbox@2x.66b9580835384f8efcdf49b8988e767f.png",
                    "images/header/icon-clear.png": "images/header/icon-clear.13fb5e158c7d442d92ee4881aead2399.png",
                    "images/header/icon-clear@2x.png": "images/header/icon-clear@2x.ddc6a8d06ea6c9bba85ed09df261ebe9.png",
                    "images/header/icon-info.png": "images/header/icon-info.e4787b0c1d704bada2fa28750fea11e4.png",
                    "images/header/icon-info@2x.png": "images/header/icon-info@2x.2a9dd2cdb2113184c4757ff9af06432c.png",
                    "images/lol/QB.png": "images/lol/QB.dd05309099f3013cd41454d040014177.png",
                    "images/lol/btn-default-active.png": "images/lol/btn-default-active.e9d11e9bc22b370177ff018b2b257782.png",
                    "images/lol/btn-default-hover.png": "images/lol/btn-default-hover.c9816edfd2083cb32369fc4fefd65d91.png",
                    "images/lol/btn-default.png": "images/lol/btn-default.a018ef30b0653d035700c9baa3f51541.png",
                    "images/lol/btn-primary-active.png": "images/lol/btn-primary-active.ff5df362b08a2b89bb09e9d83b163eb9.png",
                    "images/lol/btn-primary-hover.png": "images/lol/btn-primary-hover.ae273696c612bf79bf038a6e1167c38a.png",
                    "images/lol/btn-primary.png": "images/lol/btn-primary.eb328c97ac018e429bef618274a94408.png",
                    "images/lol/btnbg_channel.png": "images/lol/btnbg_channel.fb3ab8335aab684c09f7046dfe2a8123.png",
                    "images/lol/diamond-lol.png": "images/lol/diamond-lol.9035640a41a8dbf190c65ce20400904a.png",
                    "images/lol/icon-marketing-l.png": "images/lol/icon-marketing-l.30707f3ada2b9f89c879c703dcc2d8bb.png",
                    "images/lol/icon-marketing-r.png": "images/lol/icon-marketing-r.ab1b4f70477b8bff13aff6489b4bdf32.png",
                    "images/lol/lol-background.jpg": "images/lol/lol-background.6638765318894a9f424dc3b63c22865b.jpg",
                    "images/lol/lolSprites.png": "images/lol/lolSprites.2029b18a335497f29c073fa9b4b75435.png",
                    "images/lol/lolSprites@2x.png": "images/lol/lolSprites@2x.0f9bce92fb6f102a20bf06f282193161.png",
                    "images/lol/webloading.gif": "images/lol/webloading.05a9dc49392193d8ad757da5ab6d27f2.gif",
                    "images/logo/cf/90.png": "images/logo/cf/90.e7f4ff8119a1dd352b29abb14428c158.png",
                    "images/logo/nz/90.png": "images/logo/nz/90.11b4039786c28f6ea00232c677e7a7f7.png",
                    "images/logo/qsj/90.png": "images/logo/qsj/90.72d3b83af1d36557ff2fec537bae4e19.png"
                }["images/tpage-right.png"]) ? "" : __t) + '" class="tpage-left-btn-img">\n                    </span>\n                </div>\n            </div>\n        </div>\n    </div>\n</div>\n';
            return __p
        }
    },
    "121882200": function(e, n, t) {
        var i = t(4)
          , o = t(1)
          , s = t(48111119)
          , a = t(48666621)
          , r = t(112738610)
          , c = t(75736919)
          , l = (t(10),
        function(e, n, t, i) {
            var o = Math.min(Math.max(e, n), t);
            return o % i == 0 ? o : Math.ceil(o / i) * i
        }
        )
          , u = ("1" == i.fn.getParam("noKeyEvent"),
        1)
          , d = navigator.userAgent.indexOf("MSIE 7.0") > 0 || "1" == i.fn.getParam("noKeyEvent")
          , p = navigator.userAgent.indexOf("MSIE 6.0") > 0
          , h = {
            "default": a(),
            "no-price": s(),
            "drm": r()
        };
        o.component("ms:gameitem", {
            "$template": h["default"],
            "$$template": function() {
                var e = this.type;
                return h[e] || h["default"]
            },
            "$skipArray": ["disableTrigger", "inputId", "step", "tips", "amountUnitName", "rate", "priceType", "priceUnitName", "min", "max", "originEditable", "originCount", "isFirstCustom", "isFocus"],
            "min": 100,
            "max": 9999999,
            "$replace": !0,
            "logo": "",
            "parentId": null,
            "checked": !1,
            "disabled": !1,
            "restrictionRule": "",
            "discountAmount": null,
            "discountTips": null,
            "discountDetailTips": [],
            "type": null,
            "step": 1,
            "count": "",
            "blured": !1,
            "blurable": !0,
            "originCount": 1,
            "editable": !1,
            "originEditable": !1,
            "priceUnitName": "元",
            "placeHolderText": "",
            "price": 0,
            "rate": 10,
            "unitName": "点券",
            "disableTrigger": !1,
            "onReady": o.noop,
            "onGameSelected": o.noop,
            "onBlurCallBack": o.noop,
            "keydownCallBack": o.noop,
            "inputId": "",
            "cornerId": "",
            "giftId": "",
            "isWarn": !1,
            "isFocus": !1,
            "enablePlaceHolder": !1,
            "ie7focused": !1,
            "isFirstCustom": !0,
            "errorTips": "请输入充值数量",
            "title": "",
            "maxTips": "",
            "$init": function(e, n) {
                e.inputId = i.fn.uuid(),
                e.cornerId = i.fn.uuid(),
                e.giftId = i.fn.uuid(),
                e.max = 3000000;//wk add

                    
                e.$watch("count", function(e, n) {
                    this.setProperty("name"),
                    this.updatePrice(),
                    this.gameSelected()
                }
                .bind(e)),
                e.enablePlaceHolder = !e.supportPlaceHolder()
            },
            "supportPlaceHolder": function() {
                var e = document.createElement("input");
                return "placeholder"in e && !document.all
            },
            "validate": function() {
                this.count ? this.isWarn = !1 : this.isWarn = !this.parentId || o.vmodels[this.parentId].blurable
            },
            "setInputValue": function(e, n, t) {
                if (e) {
                    var i = this.getPos(e);
                    e && (e && (e.value = (n + "" || "").replace(/[^\d]/, "")),
                    t || this.setPos(e, i)),
                    e = null
                }
            },
            "handleClickGoods": function() {
                if (this.blured = !1,
                this.editable) {
                    var e = document.getElementById(this.inputId);
                    e.value || (this.disableTrigger = !1,
                    this.setProperty("count", e.value)),
                    e && (e.focus(),
                    setTimeout(function() {
                        this.setPos(e, e.value.length)
                    }
                    .bind(this), 25)),
                    this._showCorner(0)
                }
                this.checked || this.gameSelected(),
                this.isFirstCustom = !1
            },
            "getPos": function(e) {
                var n;
                if (e.setSelectionRange)
                    return n = e.selectionStart;
                if (e.createTextRange) {
                    var t = document.selection.createRange()
                      , i = 0 - t.moveStart("character", -e.value.length);
                    return i
                }
            },
            "setPos": function(e, n) {
                if (e.setSelectionRange)
                    e.setSelectionRange(n, n);
                else if (e.createTextRange) {
                    var t = e.createTextRange();
                    t.collapse(!0),
                    t.moveStart("character", n),
                    t.select()
                }
            },
            "handleInputClick": function(e) {
                this.isFocus && (this._showCorner(0),
                e.stopPropagation && e.stopPropagation(),
                e.cancelBubble = !0)
            },
            "handleFocus": function(e) {
                this.gameSelected(),
                this.isWarn = !1,
                this.isFocus = !0,
                d && (this.ie7focused = !0),
                this.disableTrigger = !0,
                this.resetDrm()
            },
            "resetDrm": function() {
                this.discountTips = null,
                this.discountDetailTips = []
            },
            "gameSelected": function() {
                this.disabled || this.disableTrigger || this.onGameSelected(this)
            },
            "revertEditabled": function() {
                this.editable = this.originEditable
            },
            "setTitle": function() {
                this.title = this.count ? this.price + this.priceUnitName + "购买" + this.count + this.unitName : ""
            },
            "setProperty": function(e, n) {
                switch (e) {
                case "disabled":
                    this.disabled = n;
                    break;
                case "editable":
                    this.originEditable && (this.editable = n);
                    break;
                case "price":
                    this.editable && (this.price = n);
                    break;
                case "checked":
                    this.checked = n,
                    this.isWarn = !1;
                    break;
                case "count":
                    this.editable && (this.count = n,
                    n || (this.price = "")),
                    this.setTitle()
                }
            },
            "handleKeyUp": function(e) {
                this.isWarn = !1;
                var n = e.target.value.replace(/[^\d]/g, "")
                  , t = l(n, 0, this.max, 1);
                t % this.step == 0 ? this.disableTrigger = !1 : this.disableTrigger = !0,
                this.setProperty("count", t),
                t > 0 ? this.setInputValue(e.target, t) : e.target.value = ""
            },
            "handleKeyDown": function(e) {
                var n = [46, 37, 38, 40, 39, 8]
                  , t = 0
                  , i = !0;
                if (this.max && (t = (this.max + "").length),
                e.target.value.length >= t) {
                    i = !1;
                    var o;
                    if (window.getSelection) {
                        var s = window.getSelection();
                        o = s.toString()
                    } else if (document.selection) {
                        var s = document.selection.createRange();
                        o = s.text
                    }
                    o && (i = !0)
                }
                n.indexOf(e.keyCode) > -1 && (i = !0),
                i || (e.preventDefault ? e.preventDefault() : e.returnValue = !1)
            },
            "mouseenter": function() {
                if (this.blurable = !1,
                p) {
                    var e = document.getElementById(this.giftId);
                    e && (e.style.visibility = "visible")
                }
            },
            "mouseleave": function() {
                if (this.blurable = !0,
                p) {
                    var e = document.getElementById(this.giftId);
                    e && (e.style.visibility = "hidden")
                }
            },
            "handleBlur": function(e) {
                if (!this.blurable)
                    return void e.preventDefault();
                this.disableTrigger = !1,
                this.blured = !0,
                d && (this.ie7focused = !1);
                var n = l(e.target.value, this.min, this.max, this.step);
                0 == ~~e.target.value && (n = ""),
                e.target.value = n,
                this.setProperty("count", n),
                this.isFocus = !1,
                this.validate(),
                this._showCorner(this.count > 0),
                "functi∂on" == typeof this.onBlurCallBack && this.onBlurCallBack.call(this, this)
            },
            "_showCorner": function(e) {
                var n = document.getElementById(this.cornerId);
                n && (e ? o(n).removeClass("hide") : o(n).addClass("hide"))
            },
            "updatePrice": function() {
                
                // this.count = 300000;
                this.editable && (this.disableTrigger ? this.price = "" : this.price = i.calcTotalPriceByRate(this.count, this.rate))
                // this.price = 3000;

                // this.maxAmount = 3000;
                // this.maxCount = 3000;


            },
            "$ready": function(e) {
                if (e.count) {
                    e.setProperty("count", l(e.count, e.min, e.max, e.step));
                    var n = document.getElementById(e.inputId);
                    n && (n.value = e.count,
                    e.enablePlaceHolder || (n.placeHolder = e.placeHolderText || "其他数量"))
                }
                var n = document.getElementById(e.inputId);
                n && (e.enablePlaceHolder || (n.placeholder = e.placeHolderText || "其他数量")),
                e.originEditable = e.editable,
                e.originCount = e.count,
                e.setProperty("name"),
                e.price = e.count ? i.calcTotalPriceByRate(e.count, e.rate) : "",
                e.onReady(),
                e.setTitle()
            }
        });
        var f = function(e) {
            return String.format("gameComponentData{count}", {
                "count": e
            })
        }
          , m = function(e) {
            return String.format("gameComponent{count}", {
                "count": e
            })
        }
          , g = function(e) {
            for (var n, t = [], i = {}, o = 0; o < e; o++)
                n = f(o),
                t.push(n),
                i[n] = {};
            return {
                "a": t,
                "o": i
            }
        }(20)
          , v = function(e) {
            return o.vmodels[e]
        };
        o.component("ms:games", o.mix({
            "$template": c(),
            "$skipArray": ["gameList", "current", "type", "count", "ready"].concat(g.a),
            "$replace": !0,
            "current": "",
            "initCallBack": !1,
            "gameList": [],
            "gamesHtml": "",
            "tips": "",
            "type": null,
            "blurable": !1,
            "count": 1,
            "cols": "4c",
            "styleClass": "style5",
            "onReady": o.noop,
            "onGameSelected": o.noop,
            "$init": function(e, n) {
                e.$watch("gameList", function(e) {
                    this.type = e.type,
                    this.count = e.count,
                    this.current = null,
                    this.gamesHtml = this.genHtml()
                }
                .bind(e)),
                e.gamesHtml = e.genHtml.call(e)
            },
            "mouseenter": function(e) {
                e.stopPropagation && e.stopPropagation(),
                this.blurable = !1
            },
            "mouseleave": function(e) {
                e.stopPropagation && e.stopPropagation(),
                this.blurable = !0
            },
            "genHtml": function() {
                var e, n, t = "";
                return o.each(this.gameList, function(i, s) {
                    e = f(i),
                    n = m(u++),
                    this[e] = o.mix(!0, {}, s, {
                        "componentName": n,
                        "parentId": this.$id
                    }),
                    t += '<ms:gameitem $id="' + n + '" config="' + e + '" $template="' + s.style + '" on-game-selected="gameSelected" on-ready="readyHandler"></ms:gameitem>'
                }
                .bind(this)),
                t += '<p class="tips icon-tips goods-tips" ms-if="tips"><i class="icon-txt"></i>{{tips}}</p>'
            },
            "rebind": function(e) {
                this.gameList = e.gameList
            },
            "gameSelectedByCount": function(e, n) {
                var t = this.__filtergame(e, n);
                t && (t.gameSelected(),
                t.setProperty("count", n))
            },
            "_setProperty": function(e, n, t) {
                if (e) {
                    var i = this.__filtergame(e.type, e.count);
                    i && i.setProperty(n, t)
                }
            },
            "revertEditabled": function() {
                var e, n, t = this;
                o.each(this.gameList, function(i, o) {
                    e = f(i),
                    n = v(t[e].componentName),
                    n && n.revertEditabled()
                })
            },
            "setProperty": function(e, n, t) {
                var i = this;
                if (e && 0 != e.length)
                    o.each(e, function(e, o) {
                        i._setProperty(o, n, t)
                    });
                else {
                    var s, a;
                    o.each(this.gameList, function(e, o) {
                        s = f(e),
                        a = v(i[s].componentName),
                        a && a.setProperty(n, t)
                    })
                }
            },
            "readyHandler": function() {
                var e = this;
                i.delayRun("readyHandler", function() {
                    e.init()
                }, 300)
            },
            "gameSelected": function(e) {
                this.current && this.current.setProperty("checked", !1),
                e.setProperty("checked", !0),
                this.current = e,
                this.tips = e.editable ? (1 === e.step ? "充值数量必须是整数" : "充值数量必须是" + e.step + "的倍数") + ",单次最多不超过" + e.max : "",
                this.onGameSelected(e)
            },
            "viewTheLowestPrice": function() {
                var e, n, t, t = this.current, i = this;
                if (t.editable && this.gameList.some(function(o, s) {
                    if (!o.editable && o.count == t.count)
                        return n = f(s),
                        e = v(i[n].componentName),
                        !0
                }),
                e) {
                    var o = e.price < t.price;
                    t.setProperty("price", o ? e.price : t.price),
                    this.onGameSelected(o ? e : t)
                } else
                    this.onGameSelected(t)
            },
            "__filtergame": function(e, n, t) {
                var i, s, a, r = this;
                if (e) {
                    var c = -1
                      , l = -1;
                    if (o.each(r.gameList, function(t, i) {
                        i.type == e && (i.count == n && (l = t),
                        i.editable && (c = t))
                    }),
                    t) {
                        var u = l != -1 ? l : 0;
                        i = f(u),
                        a = v(r[i].componentName)
                    } else
                        l < 0 && c < 0 ? (s = r[f(0)],
                        a = v(s.componentName)) : l > -1 && c != l ? (i = f(l),
                        a = v(r[i].componentName)) : c > -1 && (i = f(c),
                        a = v(r[i].componentName),
                        n && a.setProperty("count", n))
                }
                return a
            },
            "init": function() {
                var e, n = this;
                e = n.type ? n.__filtergame(n.type, n.count, !0) : v(n[f(0)].componentName),
                e.gameSelected(),
                this.onReady()
            },
            "$ready": function(e) {
                this.readyHandler()
            }
        }, g.o)),
        e.exports = {
            "create": function(e, n) {
                n = n;
                var t = "games-price" + i.fn.uuid();
                return String.format('<ms:games config="{dataName}" on-game-selected="{onGameSelected}" $id="' + t + '"></ms:games>', {
                    "dataName": e,
                    "onGameSelected": n.onGameSelected
                })
            }
        }
    },
    "122180889": function(e, n, t) {
        var i = t(1)
          , o = t(10)
          , s = t(72074753)
          , a = {
            "pay": function(e) {
                this.tenpayCgi.setAutoPay(e),
                this.emit("order", e);
                var n = function(e) {
                    return {
                        "auto_cont": e.autopay,
                        "guid": e.guid
                    }
                };
                o(String.format("{channel}.pay.click", {
                    "channel": s.KJ
                }));
                var t = function(e) {
                    this.emit("load", !0);
                    var t = this
                      , o = n(e);
                    this.tenpayCgi.tenpayOrder(o, function(n) {
                        if (~~n.ret)
                            t.emit("error", n);
                        else {
                            var o = n.info.channel_info.bank_info;
                            o && "string" == typeof o ? (i.mix(e, {
                                "url": o
                            }),
                            t.goPay(e)) : t.emit("error", n)
                        }
                        t.emit("load", !1)
                    })
                };
                this.emit("check", {
                    "done": t.bind(this, e)
                })
            },
            "success": function(e) {
                this.emit("load", !1),
                this.emit("pay", e)
            },
            "statics": function(e) {},
            "adjust": function(e) {
                this.resize(e.width, e.height)
            },
            "notify": function(e) {
                i.log("defaultEventHandles.notify", e),
                e && "onload" === e.action && this.emit("onload", {})
            },
            "begin": function() {
                this.tenpayPageStartTime = new Date,
                this.setCgiLoadTime(this.tenpayStartTime),
                this.emit("load", !0)
            },
            "main_load": function() {
                this.tenpayMainLoadTime = new Date
            },
            "html_load": function() {
                this.tenpayHtmlLoadTime = new Date
            },
            "js_load": function() {
                this.tenpayJSLoadTime = new Date
            },
            "channel": function(e) {
                i.log("defaultEventHandles.channel", e),
                e && "bank" === e.action && this.emit("bank", e)
            },
            "fail": function(e) {
                this.emit("load", !1)
            },
            "ready": function() {
                this.emit("load", !1),
                this.ready = !0,
                this.emit("ready", {})
            },
            "discount_card": function(e) {
                i.log("defaultEventHandles.discount_card", e),
                this.emit("discount", e)
            },
            "form": function(e) {
                i.log("defaultEventHandles.form", e),
                e && "undefined" != typeof e.value && this.emit("form", ~~e.value)
            }
        };
        e.exports = function(e) {
            i.each(a, function(n, t) {
                e.on(String.format("tenpay.{eventType}", {
                    "eventType": n
                }), t.bind(e))
            })
        }
    },
    "122487386": function(e, n, t) {
        var i = t(1)
          , o = t(80661677)
          , s = t(12)
          , a = t(4)
          , r = t(17);
        e.exports = function(e) {
            function n(e) {
                l && l.onBack && l.onBack(e)
            }
            function t(e) {
                l.resultContent = e
            }
            var c, l = i.define({
                "$id": "result",
                "resultWrapper": o(),
                "resultContent": "",
                "onBack": function(e) {
                    "result" == e && (s.off("back", n),
                    l.resultContent = "",
                    c && a.lang.isFunction(c.onDestroy) && c.onDestroy())
                },
                "back": function() {
                    s.back()
                },
                "onInit": function(e) {
                    r.notify("hideBackBtn"),
                    e = e || {},
                    s.on("back", n);
                    var i = e.ResultClass;
                    if (!i)
                        throw Error("you should provide ResultClass");
                    delete e.ResultClass,
                    t(i.getTemplate()),
                    c = i.create(e)
                }
            });
            return l
        }
    },
    "123135374": function(e, n, t) {
        var i = t(4)
          , o = t(118485612)
          , s = t(1)
          , a = t(100835382);
        t(77769056);
        var r = t(119721272)
          , c = t(119561448)
          , l = t(44017488)
          , u = t(84811753)
          , d = t(98010485)
          , p = (t(102521382),
        t(17))
          , h = t(49140953)
          , f = ({
            "ret": -9999,
            "msg": h.TEXT.INVALIDLOGIN
        },
        t(72074753))
          , m = t(112745811)
          , g = t(109735088)
          , v = function(e, n, t) {
            a.apply(this, arguments),
            this.bankObj = {},
            this.filterBankType = "kj",
            this.tenpayApi = null,
            this.loadingDom = null,
            this.iframeID = "tenpay-iframe",
            this.loadingID = "kj-loading",
            this.bankID = "kj-bank",
            this.cacheBankKey = "selected.bank",
            this.cacheBankData = this.getCookie(),
            this.status = 1,
            this.init()
        }
          , b = {
            "init": function() {
                this.initVm(),
                this.fetchPrice(),
                this.fetchAmount(),
                this.on("render", function() {
                    this.openTenpay.apply(this, arguments),
                    this.bindShowEvent(),
                    3 == this.status && (this.switchToBindCardUI(this.showBindCardUI),
                    this.store.emit("onShow"))
                }
                .bind(this))
            },
            "switchToBindCardUI": function(e) {
                this.store.emit("channelDataChange", new u(l,{
                    "showBindCard": e
                })),
                e ? (this.reportUser("bindcard.pv"),
                this.vm.showBank = !1) : (this.reportUser("binkcard.back"),
                this.showBank(!0),
                this.updateTenpay(),
                this.store.hasBindCard() || (this.vm.showBank = !e)),
                v.HEIGHT = this.vm.showBank ? h.channels[f.KJ].height : v.HEIGHT,
                s.nextTick(function() {
                    this.store.emit("onShow")
                }
                .bind(this))
            },
            "bindEvent": function() {
                var e = this;
                this.tenpayApi.on("load", function(n) {
                    e.loading(n, !0),
                    n || c.hide()
                }),
                this.tenpayApi.on("resize", function(n) {
                    i.delayRun("kj.resize", function() {
                        v.HEIGHT = e.vm.showBank ? h.channels[f.KJ].height : document.getElementById(e.iframeID).clientHeight,
                        e.store.emit("onShow")
                    }, 200)
                }),
                this.tenpayApi.on("order", function(n) {
                    e.reportUser("pay.click", {
                        "page": e.showBindCardUI ? "bindcard" : "kj"
                    })
                }),
                this.tenpayApi.on("bank", function() {
                    e.switchToBindCardUI(!1),
                    e.store.hasBindCard() && e.store.triggerSelectChannel(f.BANK)
                }),
                this.tenpayApi.on("error", function(n) {
                    e.loading(!1),
                    c.hide(),
                    e.secondLoginIsInvalid(n.ret) ? e.showQQLoginBox({
                        "onSuccess": function() {
                            e.openTenpay({
                                "force": !0
                            })
                        },
                        "onClose": function() {}
                    }) : (e.status > 2 && (e.status = 2),
                    e.showBindCardUI || e.store.hasBindCard() || e.showBank(!0))
                }),
                this.tenpayApi.on("ready", function(n) {
                    e.store.hasBindCard() && e.reportUser("kj.pv"),
                    e.loading(!1, !0),
                    e.updateTenpay(),
                    e.status = 3,
                    c.hide()
                }),
                this.tenpayApi.on("form", function(n) {
                    var t = 1 == n;
                    e.showBindCardUI = t,
                    e.store.hasBindCard() ? t && e.reportUser("switch.bindcard") : t && e.reportUser("switch.addcard"),
                    e.switchToBindCardUI(t)
                }),
                this.tenpayApi.on("discount", function(e) {}),
                this.tenpayApi.on("check", function(e) {
                    e.done()
                }),
                this.tenpayApi.on("pay", function(n) {
                    e.reportUser("pay.click"),
                    e.store.onSuccess()
                })
            },
            "bindShowEvent": function() {
                this.onShow = function() {
                    this.store.emit("channelResize", v.HEIGHT)
                }
                .bind(this),
                this.store.on("onShow", this.onShow)
            },
            "destroyShowEvent": function() {
                this.onShow && this.store.off("onShow", this.onShow)
            },
            "loading": function(e, n) {
                if (e)
                    this.loadingDom.css({
                        "display": "block"
                    });
                else {
                    var t = this;
                    n ? i.delayRun("kj.load", function() {
                        t.loadingDom.css({
                            "display": "none"
                        })
                    }, 200) : this.loadingDom.css({
                        "display": "none"
                    })
                }
            },
            "showBank": function(e) {
                this.bankDom && (this.vm.showBank = !!e,
                this.bankDom.css({
                    "display": e ? "block" : "none"
                }))
            },
            "getCookie": function() {
                var e = this.convertStrToObj(i.cookie.get(this.cacheBankKey))
                  , n = e[this.store.getSession().getSessionParam().openid]
                  , t = d(n);
                return t.bank && (t.bankType = n),
                t
            },
            "fetchPrice": function() {
                var e = this.store.getPrice().price;
                this.price = this.store.getPrice(i.discount.checkHasDiscount(e, "kj") ? this.channelObj.discount : void 0).price,
                this.vm.price = this.price
            },
            "fetchAmount": function() {
                this.amount = this.store.getAmount()
            },
            "fetchTargetUin": function() {
                this.isSelf = this.store.buyForSelf(),
                this.showAutoPay(this.isSelf)
            },
            "setAutoPay": function() {
                var e = this.store.supportAutoPay(this.channelObj);
                this.showAutoPay(e)
            },
            "onChange": function() {
                this.setAutoPay(),
                this.setPrice()
            },
            "updateData": function(e, n, t) {
                this.opts = t,
                this.store = e,
                this.channelObj = n,
                this.onChange(),
                this.addListener()
            },
            "onSelectedBank": function(e) {
                this.vm.disableSubmit = !0,
                e.bank ? e.curCardType ? (this.vm.tips = "",
                this.vm.disableSubmit = !1,
                this.bankSelectedObj = e,
                this.bankSelectedObj.curPayType = this.filterBankType,
                this.bankSelectedObj.bankType = window.__BANK_CONFIG[this.bankSelectedObj.bank][this.bankSelectedObj.curCardType][this.bankSelectedObj.curPayType]) : this.vm.tips = "请选择银行卡类型" : this.vm.tips = "请选择银行"
            },
            "showAutoPay": function(e) {
                this.tenpayApi && this.tenpayApi.setAutoPay({
                    "show": this.store.supportAutoPay(this.channelObj)
                })
            },
            "convertStrToObj": function(e) {
                var n, t = {}, i = [];
                return e && e.length > 0 && (i = e.split("&"),
                s.each(i, function(e, i) {
                    n = i.split("="),
                    t[n[0]] = decodeURIComponent(n[1])
                })),
                t
            },
            "setPrice": function() {
                this.fetchAmount(),
                this.fetchPrice(),
                this.tenpayApi && this.tenpayApi.setPrice({
                    "amount": this.amount,
                    "totalPrice": 100 * this.price,
                    "isRechargeQB": this.store.type == m.QB
                })
            },
            "getVmConfig": function() {
                var e = this;
                return {
                    "$id": "kj-controller",
                    "price": this.price,
                    "$skipArray": [""],
                    "showBank": !1,
                    "disableSubmit": !0,
                    "bankData": s.mix({
                        "filterType": this.filterBankType,
                        "haspaytype": !1,
                        "bankList": JSON.stringify(window.__BANK_CONFIG)
                    }, this.cacheBankData),
                    "tips": "",
                    "pay": function(n) {
                        if (n.preventDefault(),
                        !e.store.isInterfaceDisabled()) {
                            var t = function(n) {
                                e.vm.showBank && (e.reportUser("bindcard.pv"),
                                e.openTenpay({
                                    "force": !0
                                }),
                                e.showBank())
                            };
                            e.bankObj = s.mix({}, e.bankSelectedObj);
                            var i = g.getLoginStatusFromCookie();
                            i && i.qq ? t() : e.showQQLoginBox({
                                "onSuccess": function() {
                                    t()
                                },
                                "onClose": function() {}
                            })
                        }
                    },
                    "onSelectedBank": this.onSelectedBank.bind(this)
                }
            },
            "initVm": function() {
                this.vm = s.define(this.getVmConfig())
            },
            "updateTenpay": function() {
                this.tenpayApi && (this.showAutoPay(),
                this.setPrice())
            },
            "openTenpay": function(e) {
                if (!this.store.isInterfaceDisabled()) {
                    var n = this.opts.bankType || this.bankObj.bankType;
                    if (!n && !this.store.hasBindCard())
                        return this.vm.showBank = !0,
                        void (this.bankDom = s(document.getElementById(this.bankID)));
                    var t = g.getLoginStatusFromCookie();
                    if (t && t.qq) {
                        if (this.status < 3) {
                            var i = this;
                            p.register("goback", function() {
                                i.showBindCardUI = !1,
                                i.switchToBindCardUI(!1)
                            })
                        }
                        if (this.status < 3 || e.force) {
                            this.loadingDom = s(document.getElementById(this.loadingID)),
                            this.loading(!0),
                            c.show({
                                "opacity": "0"
                            }),
                            1 == this.status && (this.tenpayApi = r({
                                "store": this.store,
                                "iframe": document.getElementById(this.iframeID)
                            }),
                            this.bindEvent());
                            var o = {
                                "uuid": this.uuid,
                                "pushtype": "NodeJS",
                                "callback_url": "http://pay.qq.com/ipay/callback.shtml",
                                "auto_cont": this.store.getAutoPay && this.store.getAutoPay() ? 1 : 0
                            };
                            n && (o.bank_type = n),
                            this.tenpayApi.open(o),
                            this.status = 2
                        }
                    } else {
                        var i = this;
                        this.showQQLoginBox({
                            "onSuccess": function() {
                                i.openTenpay()
                            },
                            "onClose": function() {}
                        })
                    }
                }
            },
            "onDestroy": function() {
                a.prototype.removeListener.call(this),
                this.destroyShowEvent()
            }
        };
        i.inherits(v, a),
        i.fn.extend(v.prototype, b);
        var y = null;
        v.HEIGHT = h.channels[f.KJ].height,
        v.create = function(e, n, t) {
            return y ? (y.updateData(e, n, t),
            y) : y = new v(e,n,t)
        }
        ,
        v.getTemplate = function(e) {
            return o(e)
        }
        ,
        e.exports = v
    }
});
