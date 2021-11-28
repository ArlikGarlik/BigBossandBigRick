(function(){/*

 Copyright The Closure Library Authors.
 SPDX-License-Identifier: Apache-2.0
*/
'use strict';var m;function aa(a){var b=0;return function(){return b<a.length?{done:!1,value:a[b++]}:{done:!0}}}
var ba="function"==typeof Object.defineProperties?Object.defineProperty:function(a,b,c){if(a==Array.prototype||a==Object.prototype)return a;a[b]=c.value;return a};
function da(a){a=["object"==typeof globalThis&&globalThis,a,"object"==typeof window&&window,"object"==typeof self&&self,"object"==typeof global&&global];for(var b=0;b<a.length;++b){var c=a[b];if(c&&c.Math==Math)return c}throw Error("Cannot find global object");}
var ea=da(this);function r(a,b){if(b)a:{var c=ea;a=a.split(".");for(var d=0;d<a.length-1;d++){var e=a[d];if(!(e in c))break a;c=c[e]}a=a[a.length-1];d=c[a];b=b(d);b!=d&&null!=b&&ba(c,a,{configurable:!0,writable:!0,value:b})}}
r("Symbol",function(a){function b(f){if(this instanceof b)throw new TypeError("Symbol is not a constructor");return new c(d+(f||"")+"_"+e++,f)}
function c(f,g){this.h=f;ba(this,"description",{configurable:!0,writable:!0,value:g})}
if(a)return a;c.prototype.toString=function(){return this.h};
var d="jscomp_symbol_"+(1E9*Math.random()>>>0)+"_",e=0;return b});
r("Symbol.iterator",function(a){if(a)return a;a=Symbol("Symbol.iterator");for(var b="Array Int8Array Uint8Array Uint8ClampedArray Int16Array Uint16Array Int32Array Uint32Array Float32Array Float64Array".split(" "),c=0;c<b.length;c++){var d=ea[b[c]];"function"===typeof d&&"function"!=typeof d.prototype[a]&&ba(d.prototype,a,{configurable:!0,writable:!0,value:function(){return fa(aa(this))}})}return a});
function fa(a){a={next:a};a[Symbol.iterator]=function(){return this};
return a}
function t(a){var b="undefined"!=typeof Symbol&&Symbol.iterator&&a[Symbol.iterator];return b?b.call(a):{next:aa(a)}}
function ha(a){if(!(a instanceof Array)){a=t(a);for(var b,c=[];!(b=a.next()).done;)c.push(b.value);a=c}return a}
var ja="function"==typeof Object.create?Object.create:function(a){function b(){}
b.prototype=a;return new b},ka;
if("function"==typeof Object.setPrototypeOf)ka=Object.setPrototypeOf;else{var la;a:{var ma={a:!0},na={};try{na.__proto__=ma;la=na.a;break a}catch(a){}la=!1}ka=la?function(a,b){a.__proto__=b;if(a.__proto__!==b)throw new TypeError(a+" is not extensible");return a}:null}var oa=ka;
function v(a,b){a.prototype=ja(b.prototype);a.prototype.constructor=a;if(oa)oa(a,b);else for(var c in b)if("prototype"!=c)if(Object.defineProperties){var d=Object.getOwnPropertyDescriptor(b,c);d&&Object.defineProperty(a,c,d)}else a[c]=b[c];a.N=b.prototype}
function pa(){this.u=!1;this.l=null;this.i=void 0;this.h=1;this.m=this.v=0;this.I=this.j=null}
function qa(a){if(a.u)throw new TypeError("Generator is already running");a.u=!0}
pa.prototype.A=function(a){this.i=a};
function ra(a,b){a.j={Oa:b,Ua:!0};a.h=a.v||a.m}
pa.prototype.return=function(a){this.j={return:a};this.h=this.m};
function w(a,b,c){a.h=c;return{value:b}}
pa.prototype.o=function(a){this.h=a};
function sa(a,b,c){a.v=b;void 0!=c&&(a.m=c)}
function ua(a,b){a.h=b;a.v=0}
function va(a){a.v=0;var b=a.j.Oa;a.j=null;return b}
function wa(a){a.I=[a.j];a.v=0;a.m=0}
function xa(a){var b=a.I.splice(0)[0];(b=a.j=a.j||b)?b.Ua?a.h=a.v||a.m:void 0!=b.o&&a.m<b.o?(a.h=b.o,a.j=null):a.h=a.m:a.h=0}
function ya(a){this.h=new pa;this.i=a}
function za(a,b){qa(a.h);var c=a.h.l;if(c)return Aa(a,"return"in c?c["return"]:function(d){return{value:d,done:!0}},b,a.h.return);
a.h.return(b);return Ba(a)}
function Aa(a,b,c,d){try{var e=b.call(a.h.l,c);if(!(e instanceof Object))throw new TypeError("Iterator result "+e+" is not an object");if(!e.done)return a.h.u=!1,e;var f=e.value}catch(g){return a.h.l=null,ra(a.h,g),Ba(a)}a.h.l=null;d.call(a.h,f);return Ba(a)}
function Ba(a){for(;a.h.h;)try{var b=a.i(a.h);if(b)return a.h.u=!1,{value:b.value,done:!1}}catch(c){a.h.i=void 0,ra(a.h,c)}a.h.u=!1;if(a.h.j){b=a.h.j;a.h.j=null;if(b.Ua)throw b.Oa;return{value:b.return,done:!0}}return{value:void 0,done:!0}}
function Ca(a){this.next=function(b){qa(a.h);a.h.l?b=Aa(a,a.h.l.next,b,a.h.A):(a.h.A(b),b=Ba(a));return b};
this.throw=function(b){qa(a.h);a.h.l?b=Aa(a,a.h.l["throw"],b,a.h.A):(ra(a.h,b),b=Ba(a));return b};
this.return=function(b){return za(a,b)};
this[Symbol.iterator]=function(){return this}}
function Da(a){function b(d){return a.next(d)}
function c(d){return a.throw(d)}
return new Promise(function(d,e){function f(g){g.done?d(g.value):Promise.resolve(g.value).then(b,c).then(f,e)}
f(a.next())})}
function z(a){return Da(new Ca(new ya(a)))}
function Ea(){for(var a=Number(this),b=[],c=a;c<arguments.length;c++)b[c-a]=arguments[c];return b}
r("Reflect.setPrototypeOf",function(a){return a?a:oa?function(b,c){try{return oa(b,c),!0}catch(d){return!1}}:null});
r("Promise",function(a){function b(g){this.h=0;this.j=void 0;this.i=[];this.u=!1;var h=this.l();try{g(h.resolve,h.reject)}catch(k){h.reject(k)}}
function c(){this.h=null}
function d(g){return g instanceof b?g:new b(function(h){h(g)})}
if(a)return a;c.prototype.i=function(g){if(null==this.h){this.h=[];var h=this;this.j(function(){h.m()})}this.h.push(g)};
var e=ea.setTimeout;c.prototype.j=function(g){e(g,0)};
c.prototype.m=function(){for(;this.h&&this.h.length;){var g=this.h;this.h=[];for(var h=0;h<g.length;++h){var k=g[h];g[h]=null;try{k()}catch(l){this.l(l)}}}this.h=null};
c.prototype.l=function(g){this.j(function(){throw g;})};
b.prototype.l=function(){function g(l){return function(n){k||(k=!0,l.call(h,n))}}
var h=this,k=!1;return{resolve:g(this.xa),reject:g(this.m)}};
b.prototype.xa=function(g){if(g===this)this.m(new TypeError("A Promise cannot resolve to itself"));else if(g instanceof b)this.hb(g);else{a:switch(typeof g){case "object":var h=null!=g;break a;case "function":h=!0;break a;default:h=!1}h?this.ma(g):this.v(g)}};
b.prototype.ma=function(g){var h=void 0;try{h=g.then}catch(k){this.m(k);return}"function"==typeof h?this.ib(h,g):this.v(g)};
b.prototype.m=function(g){this.A(2,g)};
b.prototype.v=function(g){this.A(1,g)};
b.prototype.A=function(g,h){if(0!=this.h)throw Error("Cannot settle("+g+", "+h+"): Promise already settled in state"+this.h);this.h=g;this.j=h;2===this.h&&this.gb();this.I()};
b.prototype.gb=function(){var g=this;e(function(){if(g.O()){var h=ea.console;"undefined"!==typeof h&&h.error(g.j)}},1)};
b.prototype.O=function(){if(this.u)return!1;var g=ea.CustomEvent,h=ea.Event,k=ea.dispatchEvent;if("undefined"===typeof k)return!0;"function"===typeof g?g=new g("unhandledrejection",{cancelable:!0}):"function"===typeof h?g=new h("unhandledrejection",{cancelable:!0}):(g=ea.document.createEvent("CustomEvent"),g.initCustomEvent("unhandledrejection",!1,!0,g));g.promise=this;g.reason=this.j;return k(g)};
b.prototype.I=function(){if(null!=this.i){for(var g=0;g<this.i.length;++g)f.i(this.i[g]);this.i=null}};
var f=new c;b.prototype.hb=function(g){var h=this.l();g.oa(h.resolve,h.reject)};
b.prototype.ib=function(g,h){var k=this.l();try{g.call(h,k.resolve,k.reject)}catch(l){k.reject(l)}};
b.prototype.then=function(g,h){function k(u,q){return"function"==typeof u?function(x){try{l(u(x))}catch(y){n(y)}}:q}
var l,n,p=new b(function(u,q){l=u;n=q});
this.oa(k(g,l),k(h,n));return p};
b.prototype.catch=function(g){return this.then(void 0,g)};
b.prototype.oa=function(g,h){function k(){switch(l.h){case 1:g(l.j);break;case 2:h(l.j);break;default:throw Error("Unexpected state: "+l.h);}}
var l=this;null==this.i?f.i(k):this.i.push(k);this.u=!0};
b.resolve=d;b.reject=function(g){return new b(function(h,k){k(g)})};
b.race=function(g){return new b(function(h,k){for(var l=t(g),n=l.next();!n.done;n=l.next())d(n.value).oa(h,k)})};
b.all=function(g){var h=t(g),k=h.next();return k.done?d([]):new b(function(l,n){function p(x){return function(y){u[x]=y;q--;0==q&&l(u)}}
var u=[],q=0;do u.push(void 0),q++,d(k.value).oa(p(u.length-1),n),k=h.next();while(!k.done)})};
return b});
function Fa(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
r("WeakMap",function(a){function b(k){this.h=(h+=Math.random()+1).toString();if(k){k=t(k);for(var l;!(l=k.next()).done;)l=l.value,this.set(l[0],l[1])}}
function c(){}
function d(k){var l=typeof k;return"object"===l&&null!==k||"function"===l}
function e(k){if(!Fa(k,g)){var l=new c;ba(k,g,{value:l})}}
function f(k){var l=Object[k];l&&(Object[k]=function(n){if(n instanceof c)return n;Object.isExtensible(n)&&e(n);return l(n)})}
if(function(){if(!a||!Object.seal)return!1;try{var k=Object.seal({}),l=Object.seal({}),n=new a([[k,2],[l,3]]);if(2!=n.get(k)||3!=n.get(l))return!1;n.delete(k);n.set(l,4);return!n.has(k)&&4==n.get(l)}catch(p){return!1}}())return a;
var g="$jscomp_hidden_"+Math.random();f("freeze");f("preventExtensions");f("seal");var h=0;b.prototype.set=function(k,l){if(!d(k))throw Error("Invalid WeakMap key");e(k);if(!Fa(k,g))throw Error("WeakMap key fail: "+k);k[g][this.h]=l;return this};
b.prototype.get=function(k){return d(k)&&Fa(k,g)?k[g][this.h]:void 0};
b.prototype.has=function(k){return d(k)&&Fa(k,g)&&Fa(k[g],this.h)};
b.prototype.delete=function(k){return d(k)&&Fa(k,g)&&Fa(k[g],this.h)?delete k[g][this.h]:!1};
return b});
r("Map",function(a){function b(){var h={};return h.previous=h.next=h.head=h}
function c(h,k){var l=h.h;return fa(function(){if(l){for(;l.head!=h.h;)l=l.previous;for(;l.next!=l.head;)return l=l.next,{done:!1,value:k(l)};l=null}return{done:!0,value:void 0}})}
function d(h,k){var l=k&&typeof k;"object"==l||"function"==l?f.has(k)?l=f.get(k):(l=""+ ++g,f.set(k,l)):l="p_"+k;var n=h.data_[l];if(n&&Fa(h.data_,l))for(h=0;h<n.length;h++){var p=n[h];if(k!==k&&p.key!==p.key||k===p.key)return{id:l,list:n,index:h,entry:p}}return{id:l,list:n,index:-1,entry:void 0}}
function e(h){this.data_={};this.h=b();this.size=0;if(h){h=t(h);for(var k;!(k=h.next()).done;)k=k.value,this.set(k[0],k[1])}}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var h=Object.seal({x:4}),k=new a(t([[h,"s"]]));if("s"!=k.get(h)||1!=k.size||k.get({x:4})||k.set({x:4},"t")!=k||2!=k.size)return!1;var l=k.entries(),n=l.next();if(n.done||n.value[0]!=h||"s"!=n.value[1])return!1;n=l.next();return n.done||4!=n.value[0].x||"t"!=n.value[1]||!l.next().done?!1:!0}catch(p){return!1}}())return a;
var f=new WeakMap;e.prototype.set=function(h,k){h=0===h?0:h;var l=d(this,h);l.list||(l.list=this.data_[l.id]=[]);l.entry?l.entry.value=k:(l.entry={next:this.h,previous:this.h.previous,head:this.h,key:h,value:k},l.list.push(l.entry),this.h.previous.next=l.entry,this.h.previous=l.entry,this.size++);return this};
e.prototype.delete=function(h){h=d(this,h);return h.entry&&h.list?(h.list.splice(h.index,1),h.list.length||delete this.data_[h.id],h.entry.previous.next=h.entry.next,h.entry.next.previous=h.entry.previous,h.entry.head=null,this.size--,!0):!1};
e.prototype.clear=function(){this.data_={};this.h=this.h.previous=b();this.size=0};
e.prototype.has=function(h){return!!d(this,h).entry};
e.prototype.get=function(h){return(h=d(this,h).entry)&&h.value};
e.prototype.entries=function(){return c(this,function(h){return[h.key,h.value]})};
e.prototype.keys=function(){return c(this,function(h){return h.key})};
e.prototype.values=function(){return c(this,function(h){return h.value})};
e.prototype.forEach=function(h,k){for(var l=this.entries(),n;!(n=l.next()).done;)n=n.value,h.call(k,n[1],n[0],this)};
e.prototype[Symbol.iterator]=e.prototype.entries;var g=0;return e});
function Ga(a,b,c){if(null==a)throw new TypeError("The 'this' value for String.prototype."+c+" must not be null or undefined");if(b instanceof RegExp)throw new TypeError("First argument to String.prototype."+c+" must not be a regular expression");return a+""}
r("String.prototype.endsWith",function(a){return a?a:function(b,c){var d=Ga(this,b,"endsWith");b+="";void 0===c&&(c=d.length);c=Math.max(0,Math.min(c|0,d.length));for(var e=b.length;0<e&&0<c;)if(d[--c]!=b[--e])return!1;return 0>=e}});
r("Array.prototype.find",function(a){return a?a:function(b,c){a:{var d=this;d instanceof String&&(d=String(d));for(var e=d.length,f=0;f<e;f++){var g=d[f];if(b.call(c,g,f,d)){b=g;break a}}b=void 0}return b}});
r("String.prototype.startsWith",function(a){return a?a:function(b,c){var d=Ga(this,b,"startsWith");b+="";var e=d.length,f=b.length;c=Math.max(0,Math.min(c|0,d.length));for(var g=0;g<f&&c<e;)if(d[c++]!=b[g++])return!1;return g>=f}});
function Ha(a,b){a instanceof String&&(a+="");var c=0,d=!1,e={next:function(){if(!d&&c<a.length){var f=c++;return{value:b(f,a[f]),done:!1}}d=!0;return{done:!0,value:void 0}}};
e[Symbol.iterator]=function(){return e};
return e}
r("Array.prototype.entries",function(a){return a?a:function(){return Ha(this,function(b,c){return[b,c]})}});
r("Object.setPrototypeOf",function(a){return a||oa});
var Ia="function"==typeof Object.assign?Object.assign:function(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(d)for(var e in d)Fa(d,e)&&(a[e]=d[e])}return a};
r("Object.assign",function(a){return a||Ia});
r("Set",function(a){function b(c){this.h=new Map;if(c){c=t(c);for(var d;!(d=c.next()).done;)this.add(d.value)}this.size=this.h.size}
if(function(){if(!a||"function"!=typeof a||!a.prototype.entries||"function"!=typeof Object.seal)return!1;try{var c=Object.seal({x:4}),d=new a(t([c]));if(!d.has(c)||1!=d.size||d.add(c)!=d||1!=d.size||d.add({x:4})!=d||2!=d.size)return!1;var e=d.entries(),f=e.next();if(f.done||f.value[0]!=c||f.value[1]!=c)return!1;f=e.next();return f.done||f.value[0]==c||4!=f.value[0].x||f.value[1]!=f.value[0]?!1:e.next().done}catch(g){return!1}}())return a;
b.prototype.add=function(c){c=0===c?0:c;this.h.set(c,c);this.size=this.h.size;return this};
b.prototype.delete=function(c){c=this.h.delete(c);this.size=this.h.size;return c};
b.prototype.clear=function(){this.h.clear();this.size=0};
b.prototype.has=function(c){return this.h.has(c)};
b.prototype.entries=function(){return this.h.entries()};
b.prototype.values=function(){return this.h.values()};
b.prototype.keys=b.prototype.values;b.prototype[Symbol.iterator]=b.prototype.values;b.prototype.forEach=function(c,d){var e=this;this.h.forEach(function(f){return c.call(d,f,f,e)})};
return b});
r("Object.entries",function(a){return a?a:function(b){var c=[],d;for(d in b)Fa(b,d)&&c.push([d,b[d]]);return c}});
r("Array.prototype.keys",function(a){return a?a:function(){return Ha(this,function(b){return b})}});
r("Array.prototype.values",function(a){return a?a:function(){return Ha(this,function(b,c){return c})}});
r("Array.from",function(a){return a?a:function(b,c,d){c=null!=c?c:function(h){return h};
var e=[],f="undefined"!=typeof Symbol&&Symbol.iterator&&b[Symbol.iterator];if("function"==typeof f){b=f.call(b);for(var g=0;!(f=b.next()).done;)e.push(c.call(d,f.value,g++))}else for(f=b.length,g=0;g<f;g++)e.push(c.call(d,b[g],g));return e}});
r("Number.isNaN",function(a){return a?a:function(b){return"number"===typeof b&&isNaN(b)}});
r("Number.MAX_SAFE_INTEGER",function(){return 9007199254740991});
r("Object.is",function(a){return a?a:function(b,c){return b===c?0!==b||1/b===1/c:b!==b&&c!==c}});
r("Array.prototype.includes",function(a){return a?a:function(b,c){var d=this;d instanceof String&&(d=String(d));var e=d.length;c=c||0;for(0>c&&(c=Math.max(c+e,0));c<e;c++){var f=d[c];if(f===b||Object.is(f,b))return!0}return!1}});
r("String.prototype.includes",function(a){return a?a:function(b,c){return-1!==Ga(this,b,"includes").indexOf(b,c||0)}});
var B=this||self;function C(a,b){a=a.split(".");b=b||B;for(var c=0;c<a.length;c++)if(b=b[a[c]],null==b)return null;return b}
function Ja(){}
function Ka(a){var b=typeof a;return"object"!=b?b:a?Array.isArray(a)?"array":b:"null"}
function La(a){var b=Ka(a);return"array"==b||"object"==b&&"number"==typeof a.length}
function D(a){var b=typeof a;return"object"==b&&null!=a||"function"==b}
function Ma(a){return Object.prototype.hasOwnProperty.call(a,Na)&&a[Na]||(a[Na]=++Oa)}
var Na="closure_uid_"+(1E9*Math.random()>>>0),Oa=0;function Pa(a,b,c){return a.call.apply(a.bind,arguments)}
function Qa(a,b,c){if(!a)throw Error();if(2<arguments.length){var d=Array.prototype.slice.call(arguments,2);return function(){var e=Array.prototype.slice.call(arguments);Array.prototype.unshift.apply(e,d);return a.apply(b,e)}}return function(){return a.apply(b,arguments)}}
function Ra(a,b,c){Function.prototype.bind&&-1!=Function.prototype.bind.toString().indexOf("native code")?Ra=Pa:Ra=Qa;return Ra.apply(null,arguments)}
function E(a,b){a=a.split(".");var c=B;a[0]in c||"undefined"==typeof c.execScript||c.execScript("var "+a[0]);for(var d;a.length&&(d=a.shift());)a.length||void 0===b?c[d]&&c[d]!==Object.prototype[d]?c=c[d]:c=c[d]={}:c[d]=b}
function F(a,b){function c(){}
c.prototype=b.prototype;a.N=b.prototype;a.prototype=new c;a.prototype.constructor=a;a.Pb=function(d,e,f){for(var g=Array(arguments.length-2),h=2;h<arguments.length;h++)g[h-2]=arguments[h];return b.prototype[e].apply(d,g)}}
function Sa(a){return a}
;function Ta(a,b){if(Error.captureStackTrace)Error.captureStackTrace(this,Ta);else{var c=Error().stack;c&&(this.stack=c)}a&&(this.message=String(a));void 0!==b&&(this.kb=b)}
F(Ta,Error);Ta.prototype.name="CustomError";function Ua(a){a=a.url;var b=/[?&]dsh=1(&|$)/.test(a);this.j=!b&&/[?&]ae=1(&|$)/.test(a);this.l=!b&&/[?&]ae=2(&|$)/.test(a);if((this.h=/[?&]adurl=([^&]*)/.exec(a))&&this.h[1]){try{var c=decodeURIComponent(this.h[1])}catch(d){c=null}this.i=c}}
;function Va(a){var b=!1,c;return function(){b||(c=a(),b=!0);return c}}
;var Wa=Array.prototype.indexOf?function(a,b){return Array.prototype.indexOf.call(a,b,void 0)}:function(a,b){if("string"===typeof a)return"string"!==typeof b||1!=b.length?-1:a.indexOf(b,0);
for(var c=0;c<a.length;c++)if(c in a&&a[c]===b)return c;return-1},G=Array.prototype.forEach?function(a,b,c){Array.prototype.forEach.call(a,b,c)}:function(a,b,c){for(var d=a.length,e="string"===typeof a?a.split(""):a,f=0;f<d;f++)f in e&&b.call(c,e[f],f,a)},Xa=Array.prototype.reduce?function(a,b,c){return Array.prototype.reduce.call(a,b,c)}:function(a,b,c){var d=c;
G(a,function(e,f){d=b.call(void 0,d,e,f,a)});
return d};
function Ya(a,b){b=Wa(a,b);var c;(c=0<=b)&&Array.prototype.splice.call(a,b,1);return c}
function Za(a){return Array.prototype.concat.apply([],arguments)}
function $a(a){var b=a.length;if(0<b){for(var c=Array(b),d=0;d<b;d++)c[d]=a[d];return c}return[]}
function ab(a,b){for(var c=1;c<arguments.length;c++){var d=arguments[c];if(La(d)){var e=a.length||0,f=d.length||0;a.length=e+f;for(var g=0;g<f;g++)a[e+g]=d[g]}else a.push(d)}}
;function bb(a,b){for(var c in a)b.call(void 0,a[c],c,a)}
function cb(a){var b=db,c;for(c in b)if(a.call(void 0,b[c],c,b))return c}
function eb(a,b){for(var c in a)if(!(c in b)||a[c]!==b[c])return!1;for(var d in b)if(!(d in a))return!1;return!0}
function fb(a){if(!a||"object"!==typeof a)return a;if("function"===typeof a.clone)return a.clone();if("undefined"!==typeof Map&&a instanceof Map)return new Map(a);if("undefined"!==typeof Set&&a instanceof Set)return new Set(a);var b=Array.isArray(a)?[]:"function"!==typeof ArrayBuffer||"function"!==typeof ArrayBuffer.isView||!ArrayBuffer.isView(a)||a instanceof DataView?{}:new a.constructor(a.length),c;for(c in a)b[c]=fb(a[c]);return b}
var gb="constructor hasOwnProperty isPrototypeOf propertyIsEnumerable toLocaleString toString valueOf".split(" ");function hb(a,b){for(var c,d,e=1;e<arguments.length;e++){d=arguments[e];for(c in d)a[c]=d[c];for(var f=0;f<gb.length;f++)c=gb[f],Object.prototype.hasOwnProperty.call(d,c)&&(a[c]=d[c])}}
;var jb;function kb(a,b){this.h=a===lb&&b||""}
kb.prototype.ha=!0;kb.prototype.ga=function(){return this.h};
function mb(a){return new kb(lb,a)}
var lb={};mb("");var nb=String.prototype.trim?function(a){return a.trim()}:function(a){return/^[\s\xa0]*([\s\S]*?)[\s\xa0]*$/.exec(a)[1]};
function ob(a,b){if(b)a=a.replace(pb,"&amp;").replace(qb,"&lt;").replace(rb,"&gt;").replace(sb,"&quot;").replace(tb,"&#39;").replace(ub,"&#0;");else{if(!vb.test(a))return a;-1!=a.indexOf("&")&&(a=a.replace(pb,"&amp;"));-1!=a.indexOf("<")&&(a=a.replace(qb,"&lt;"));-1!=a.indexOf(">")&&(a=a.replace(rb,"&gt;"));-1!=a.indexOf('"')&&(a=a.replace(sb,"&quot;"));-1!=a.indexOf("'")&&(a=a.replace(tb,"&#39;"));-1!=a.indexOf("\x00")&&(a=a.replace(ub,"&#0;"))}return a}
var pb=/&/g,qb=/</g,rb=/>/g,sb=/"/g,tb=/'/g,ub=/\x00/g,vb=/[\x00&<>"']/;function wb(a,b){this.h=b===xb?a:""}
m=wb.prototype;m.ha=!0;m.ga=function(){return this.h.toString()};
m.Ra=!0;m.Pa=function(){return 1};
m.toString=function(){return this.h.toString()};
var yb=RegExp('^(?:audio/(?:3gpp2|3gpp|aac|L16|midi|mp3|mp4|mpeg|oga|ogg|opus|x-m4a|x-matroska|x-wav|wav|webm)|font/\\w+|image/(?:bmp|gif|jpeg|jpg|png|tiff|webp|x-icon)|video/(?:mpeg|mp4|ogg|webm|quicktime|x-matroska))(?:;\\w+=(?:\\w+|"[\\w;,= ]+"))*$',"i"),zb=/^data:(.*);base64,[a-z0-9+\/]+=*$/i,Ab=/^(?:(?:https?|mailto|ftp):|[^:/?#]*(?:[/?#]|$))/i,xb={},Bb=new wb("about:invalid#zClosurez",xb);var Cb;a:{var Db=B.navigator;if(Db){var Eb=Db.userAgent;if(Eb){Cb=Eb;break a}}Cb=""}function H(a){return-1!=Cb.indexOf(a)}
;function Fb(){return(H("Chrome")||H("CriOS"))&&!H("Edge")||H("Silk")}
;var Gb={};function Hb(a,b,c){this.h=c===Gb?a:"";this.i=b;this.ha=this.Ra=!0}
Hb.prototype.Pa=function(){return this.i};
Hb.prototype.ga=function(){return this.h.toString()};
Hb.prototype.toString=function(){return this.h.toString()};
function Ib(a,b){if(void 0===jb){var c=null;var d=B.trustedTypes;if(d&&d.createPolicy){try{c=d.createPolicy("goog#html",{createHTML:Sa,createScript:Sa,createScriptURL:Sa})}catch(e){B.console&&B.console.error(e.message)}jb=c}else jb=c}a=(c=jb)?c.createHTML(a):a;return new Hb(a,b,Gb)}
;var Kb=RegExp("^(?:([^:/?#.]+):)?(?://(?:([^\\\\/?#]*)@)?([^\\\\/?#]*?)(?::([0-9]+))?(?=[\\\\/?#]|$))?([^?#]+)?(?:\\?([^#]*))?(?:#([\\s\\S]*))?$");function Lb(a){return a?decodeURI(a):a}
function Mb(a){return Lb(a.match(Kb)[3]||null)}
function Nb(a){var b=a.match(Kb);a=b[1];var c=b[2],d=b[3];b=b[4];var e="";a&&(e+=a+":");d&&(e+="//",c&&(e+=c+"@"),e+=d,b&&(e+=":"+b));return e}
function Ob(a,b,c){if(Array.isArray(b))for(var d=0;d<b.length;d++)Ob(a,String(b[d]),c);else null!=b&&c.push(a+(""===b?"":"="+encodeURIComponent(String(b))))}
function Pb(a){var b=[],c;for(c in a)Ob(c,a[c],b);return b.join("&")}
var Qb=/#|$/;function Rb(a,b){var c=a.search(Qb);a:{var d=0;for(var e=b.length;0<=(d=a.indexOf(b,d))&&d<c;){var f=a.charCodeAt(d-1);if(38==f||63==f)if(f=a.charCodeAt(d+e),!f||61==f||38==f||35==f)break a;d+=e+1}d=-1}if(0>d)return null;e=a.indexOf("&",d);if(0>e||e>c)e=c;d+=b.length+1;return decodeURIComponent(a.substr(d,e-d).replace(/\+/g," "))}
;function Sb(a){B.setTimeout(function(){throw a;},0)}
;function Tb(){return H("iPhone")&&!H("iPod")&&!H("iPad")}
;function Ub(a){Ub[" "](a);return a}
Ub[" "]=Ja;var Vb=H("Opera"),Wb=H("Trident")||H("MSIE"),Xb=H("Edge"),Yb=H("Gecko")&&!(-1!=Cb.toLowerCase().indexOf("webkit")&&!H("Edge"))&&!(H("Trident")||H("MSIE"))&&!H("Edge"),Zb=-1!=Cb.toLowerCase().indexOf("webkit")&&!H("Edge");function $b(){var a=B.document;return a?a.documentMode:void 0}
var ac;a:{var bc="",cc=function(){var a=Cb;if(Yb)return/rv:([^\);]+)(\)|;)/.exec(a);if(Xb)return/Edge\/([\d\.]+)/.exec(a);if(Wb)return/\b(?:MSIE|rv)[: ]([^\);]+)(\)|;)/.exec(a);if(Zb)return/WebKit\/(\S+)/.exec(a);if(Vb)return/(?:Version)[ \/]?(\S+)/.exec(a)}();
cc&&(bc=cc?cc[1]:"");if(Wb){var dc=$b();if(null!=dc&&dc>parseFloat(bc)){ac=String(dc);break a}}ac=bc}var ec=ac,fc;if(B.document&&Wb){var gc=$b();fc=gc?gc:parseInt(ec,10)||void 0}else fc=void 0;var hc=fc;var ic=Tb()||H("iPod"),jc=H("iPad");!H("Android")||Fb();Fb();var kc=H("Safari")&&!(Fb()||H("Coast")||H("Opera")||H("Edge")||H("Edg/")||H("OPR")||H("Firefox")||H("FxiOS")||H("Silk")||H("Android"))&&!(Tb()||H("iPad")||H("iPod"));var lc={},mc=null;
function nc(a,b){La(a);void 0===b&&(b=0);if(!mc){mc={};for(var c="ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz0123456789".split(""),d=["+/=","+/","-_=","-_.","-_"],e=0;5>e;e++){var f=c.concat(d[e].split(""));lc[e]=f;for(var g=0;g<f.length;g++){var h=f[g];void 0===mc[h]&&(mc[h]=g)}}}b=lc[b];c=Array(Math.floor(a.length/3));d=b[64]||"";for(e=f=0;f<a.length-2;f+=3){var k=a[f],l=a[f+1];h=a[f+2];g=b[k>>2];k=b[(k&3)<<4|l>>4];l=b[(l&15)<<2|h>>6];h=b[h&63];c[e++]=""+g+k+l+h}g=0;h=d;switch(a.length-
f){case 2:g=a[f+1],h=b[(g&15)<<2]||d;case 1:a=a[f],c[e]=""+b[a>>2]+b[(a&3)<<4|g>>4]+h+d}return c.join("")}
;var oc="function"===typeof Uint8Array;var pc="function"===typeof Symbol&&"symbol"===typeof Symbol()?Symbol(void 0):void 0;function qc(a){Object.isFrozen(a)||(pc?a[pc]|=1:void 0!==a.h?a.h|=1:Object.defineProperties(a,{h:{value:1,configurable:!0,writable:!0,enumerable:!1}}));return a}
;function rc(a){return null!==a&&"object"===typeof a&&a.constructor===Object}
var sc;function tc(a){switch(typeof a){case "number":return isFinite(a)?a:String(a);case "object":if(oc&&null!=a&&a instanceof Uint8Array)return nc(a)}return a}
;function uc(a,b){if(null!=a)return Array.isArray(a)||rc(a)?vc(a,b):b(a)}
function vc(a,b){if(Array.isArray(a)){for(var c=Array(a.length),d=0;d<a.length;d++)c[d]=uc(a[d],b);if(Array.isArray(a)){var e;pc?e=a[pc]:e=a.h;a=!!((null==e?0:e)&1)}else a=!1;a&&qc(c);return c}e={};for(c in a)e[c]=uc(a[c],b);return e}
function wc(a){a=tc(a);return Array.isArray(a)?vc(a,wc):a}
function xc(a){return oc&&null!=a&&a instanceof Uint8Array?new Uint8Array(a):a}
;var yc;function I(a,b,c){var d=yc;yc=null;a||(a=d);d=this.constructor.Tb;a||(a=d?[d]:[]);this.j=(d?0:-1)-(this.constructor.Sb||0);this.h=null;this.H=a;a:{d=this.H.length;a=d-1;if(d&&(d=this.H[a],rc(d))){this.l=a-this.j;this.i=d;break a}void 0!==b&&-1<b?(this.l=Math.max(b,a+1-this.j),this.i=null):this.l=Number.MAX_VALUE}if(c)for(b=0;b<c.length;b++)a=c[b],a<this.l?(a+=this.j,(d=this.H[a])?Array.isArray(d)&&qc(d):this.H[a]=zc):(Ac(this),(d=this.i[a])?Array.isArray(d)&&qc(d):this.i[a]=zc)}
var zc=Object.freeze(qc([]));function Ac(a){var b=a.l+a.j;a.H[b]||(a.i=a.H[b]={})}
function Bc(a,b,c){return-1===b?null:(void 0===c?0:c)||b>=a.l?a.i?a.i[b]:void 0:a.H[b+a.j]}
function Cc(a,b,c){c=void 0===c?!1:c;var d=Bc(a,b,c);null==d&&(d=zc);d===zc&&(d=qc(d.slice()),J(a,b,d,c));return d}
function J(a,b,c,d){(void 0===d?0:d)||b>=a.l?(Ac(a),a.i[b]=c):a.H[b+a.j]=c;return a}
function Dc(a,b){for(var c=0,d=0;d<b.length;d++){var e=b[d];null!=Bc(a,e)&&(0!==c&&J(a,c,void 0,!1),c=e)}return c}
function Ec(a,b,c,d,e){if(-1===c)return null;a.h||(a.h={});var f=a.h[c];if(f)return f;e=Bc(a,c,void 0===e?!1:e);if(null==e&&!d)return f;b=new b(e);return a.h[c]=b}
function Fc(a,b,c,d){a.h||(a.h={});var e=a.h[c];if(!e){d=Cc(a,c,void 0===d?!1:d);e=[];for(var f=0;f<d.length;f++)e[f]=new b(d[f]);a.h[c]=e}return e}
function Gc(a,b,c){var d;a.h||(a.h={});var e=c?c.H:c;a.h[b]=c;return J(a,b,e,void 0===d?!1:d)}
function Hc(a,b,c,d){var e=Fc(a,d,b);c=c?c:new d;a=Cc(a,b);e.push(c);a.push(c.H)}
I.prototype.toJSON=function(){var a=this.H;return sc?a:vc(a,wc)};
function Ic(a,b){return tc(b)}
I.prototype.toString=function(){return this.H.toString()};
I.prototype.clone=function(){var a=this.constructor,b=vc(this.H,xc);yc=b;a=new a(b);yc=null;Jc(a,this);return a};
function Jc(a,b){b.m&&(a.m=b.m.slice());var c=b.h;if(c){b=b.i;for(var d in c){var e=c[d];if(e){var f=!(!b||!b[d]),g=+d;if(Array.isArray(e)){if(e.length)for(f=Fc(a,e[0].constructor,g,f),g=0;g<Math.min(f.length,e.length);g++)Jc(f[g],e[g])}else(f=Ec(a,e.constructor,g,void 0,f))&&Jc(f,e)}}}}
;var Kc=window;mb("csi.gstatic.com");mb("googleads.g.doubleclick.net");mb("pagead2.googlesyndication.com");mb("partner.googleadservices.com");mb("pubads.g.doubleclick.net");mb("securepubads.g.doubleclick.net");mb("tpc.googlesyndication.com");/*

 SPDX-License-Identifier: Apache-2.0
*/
function Lc(a,b){this.width=a;this.height=b}
m=Lc.prototype;m.clone=function(){return new Lc(this.width,this.height)};
m.aspectRatio=function(){return this.width/this.height};
m.isEmpty=function(){return!(this.width*this.height)};
m.ceil=function(){this.width=Math.ceil(this.width);this.height=Math.ceil(this.height);return this};
m.floor=function(){this.width=Math.floor(this.width);this.height=Math.floor(this.height);return this};
m.round=function(){this.width=Math.round(this.width);this.height=Math.round(this.height);return this};
m.scale=function(a,b){this.width*=a;this.height*="number"===typeof b?b:a;return this};function Mc(a,b){bb(b,function(c,d){c&&"object"==typeof c&&c.ha&&(c=c.ga());"style"==d?a.style.cssText=c:"class"==d?a.className=c:"for"==d?a.htmlFor=c:Nc.hasOwnProperty(d)?a.setAttribute(Nc[d],c):0==d.lastIndexOf("aria-",0)||0==d.lastIndexOf("data-",0)?a.setAttribute(d,c):a[d]=c})}
var Nc={cellpadding:"cellPadding",cellspacing:"cellSpacing",colspan:"colSpan",frameborder:"frameBorder",height:"height",maxlength:"maxLength",nonce:"nonce",role:"role",rowspan:"rowSpan",type:"type",usemap:"useMap",valign:"vAlign",width:"width"};function Oc(a,b,c){var d=arguments,e=document,f=d[1],g=Pc(e,String(d[0]));f&&("string"===typeof f?g.className=f:Array.isArray(f)?g.className=f.join(" "):Mc(g,f));2<d.length&&Qc(e,g,d);return g}
function Qc(a,b,c){function d(h){h&&b.appendChild("string"===typeof h?a.createTextNode(h):h)}
for(var e=2;e<c.length;e++){var f=c[e];if(!La(f)||D(f)&&0<f.nodeType)d(f);else{a:{if(f&&"number"==typeof f.length){if(D(f)){var g="function"==typeof f.item||"string"==typeof f.item;break a}if("function"===typeof f){g="function"==typeof f.item;break a}}g=!1}G(g?$a(f):f,d)}}}
function Pc(a,b){b=String(b);"application/xhtml+xml"===a.contentType&&(b=b.toLowerCase());return a.createElement(b)}
function Rc(a,b){for(var c=0;a;){if(b(a))return a;a=a.parentNode;c++}return null}
;function Sc(a){var b=Tc;if(b)for(var c in b)Object.prototype.hasOwnProperty.call(b,c)&&a.call(void 0,b[c],c,b)}
function Uc(){var a=[];Sc(function(b){a.push(b)});
return a}
var Tc={xb:"allow-forms",yb:"allow-modals",zb:"allow-orientation-lock",Ab:"allow-pointer-lock",Bb:"allow-popups",Cb:"allow-popups-to-escape-sandbox",Db:"allow-presentation",Eb:"allow-same-origin",Fb:"allow-scripts",Gb:"allow-top-navigation",Hb:"allow-top-navigation-by-user-activation"},Vc=Va(function(){return Uc()});
function Wc(){var a=Xc(),b={};G(Vc(),function(c){a.sandbox&&a.sandbox.supports&&a.sandbox.supports(c)&&(b[c]=!0)});
return b}
function Xc(){var a=void 0===a?document:a;return a.createElement("iframe")}
;var Yc=(new Date).getTime();function Zc(a){if(!a)return"";if(/^about:(?:blank|srcdoc)$/.test(a))return window.origin||"";a=a.split("#")[0].split("?")[0];a=a.toLowerCase();0==a.indexOf("//")&&(a=window.location.protocol+a);/^[\w\-]*:\/\//.test(a)||(a=window.location.href);var b=a.substring(a.indexOf("://")+3),c=b.indexOf("/");-1!=c&&(b=b.substring(0,c));c=a.substring(0,a.indexOf("://"));if(!c)throw Error("URI is missing protocol: "+a);if("http"!==c&&"https"!==c&&"chrome-extension"!==c&&"moz-extension"!==c&&"file"!==c&&"android-app"!==
c&&"chrome-search"!==c&&"chrome-untrusted"!==c&&"chrome"!==c&&"app"!==c&&"devtools"!==c)throw Error("Invalid URI scheme in origin: "+c);a="";var d=b.indexOf(":");if(-1!=d){var e=b.substring(d+1);b=b.substring(0,d);if("http"===c&&"80"!==e||"https"===c&&"443"!==e)a=":"+e}return c+"://"+b+a}
;function $c(){function a(){e[0]=1732584193;e[1]=4023233417;e[2]=2562383102;e[3]=271733878;e[4]=3285377520;n=l=0}
function b(p){for(var u=g,q=0;64>q;q+=4)u[q/4]=p[q]<<24|p[q+1]<<16|p[q+2]<<8|p[q+3];for(q=16;80>q;q++)p=u[q-3]^u[q-8]^u[q-14]^u[q-16],u[q]=(p<<1|p>>>31)&4294967295;p=e[0];var x=e[1],y=e[2],A=e[3],M=e[4];for(q=0;80>q;q++){if(40>q)if(20>q){var N=A^x&(y^A);var P=1518500249}else N=x^y^A,P=1859775393;else 60>q?(N=x&y|A&(x|y),P=2400959708):(N=x^y^A,P=3395469782);N=((p<<5|p>>>27)&4294967295)+N+M+P+u[q]&4294967295;M=A;A=y;y=(x<<30|x>>>2)&4294967295;x=p;p=N}e[0]=e[0]+p&4294967295;e[1]=e[1]+x&4294967295;e[2]=
e[2]+y&4294967295;e[3]=e[3]+A&4294967295;e[4]=e[4]+M&4294967295}
function c(p,u){if("string"===typeof p){p=unescape(encodeURIComponent(p));for(var q=[],x=0,y=p.length;x<y;++x)q.push(p.charCodeAt(x));p=q}u||(u=p.length);q=0;if(0==l)for(;q+64<u;)b(p.slice(q,q+64)),q+=64,n+=64;for(;q<u;)if(f[l++]=p[q++],n++,64==l)for(l=0,b(f);q+64<u;)b(p.slice(q,q+64)),q+=64,n+=64}
function d(){var p=[],u=8*n;56>l?c(h,56-l):c(h,64-(l-56));for(var q=63;56<=q;q--)f[q]=u&255,u>>>=8;b(f);for(q=u=0;5>q;q++)for(var x=24;0<=x;x-=8)p[u++]=e[q]>>x&255;return p}
for(var e=[],f=[],g=[],h=[128],k=1;64>k;++k)h[k]=0;var l,n;a();return{reset:a,update:c,digest:d,mb:function(){for(var p=d(),u="",q=0;q<p.length;q++)u+="0123456789ABCDEF".charAt(Math.floor(p[q]/16))+"0123456789ABCDEF".charAt(p[q]%16);return u}}}
;function ad(a,b,c){var d=String(B.location.href);return d&&a&&b?[b,bd(Zc(d),a,c||null)].join(" "):null}
function bd(a,b,c){var d=[],e=[];if(1==(Array.isArray(c)?2:1))return e=[b,a],G(d,function(h){e.push(h)}),cd(e.join(" "));
var f=[],g=[];G(c,function(h){g.push(h.key);f.push(h.value)});
c=Math.floor((new Date).getTime()/1E3);e=0==f.length?[c,b,a]:[f.join(":"),c,b,a];G(d,function(h){e.push(h)});
a=cd(e.join(" "));a=[c,a];0==g.length||a.push(g.join(""));return a.join("_")}
function cd(a){var b=$c();b.update(a);return b.mb().toLowerCase()}
;var dd={};function ed(a){this.h=a||{cookie:""}}
m=ed.prototype;m.isEnabled=function(){if(!B.navigator.cookieEnabled)return!1;if(!this.isEmpty())return!0;this.set("TESTCOOKIESENABLED","1",{Da:60});if("1"!==this.get("TESTCOOKIESENABLED"))return!1;this.remove("TESTCOOKIESENABLED");return!0};
m.set=function(a,b,c){var d=!1;if("object"===typeof c){var e=c.Wb;d=c.secure||!1;var f=c.domain||void 0;var g=c.path||void 0;var h=c.Da}if(/[;=\s]/.test(a))throw Error('Invalid cookie name "'+a+'"');if(/[;\r\n]/.test(b))throw Error('Invalid cookie value "'+b+'"');void 0===h&&(h=-1);c=f?";domain="+f:"";g=g?";path="+g:"";d=d?";secure":"";h=0>h?"":0==h?";expires="+(new Date(1970,1,1)).toUTCString():";expires="+(new Date(Date.now()+1E3*h)).toUTCString();this.h.cookie=a+"="+b+c+g+h+d+(null!=e?";samesite="+
e:"")};
m.get=function(a,b){for(var c=a+"=",d=(this.h.cookie||"").split(";"),e=0,f;e<d.length;e++){f=nb(d[e]);if(0==f.lastIndexOf(c,0))return f.substr(c.length);if(f==a)return""}return b};
m.remove=function(a,b,c){var d=void 0!==this.get(a);this.set(a,"",{Da:0,path:b,domain:c});return d};
m.isEmpty=function(){return!this.h.cookie};
m.clear=function(){for(var a=(this.h.cookie||"").split(";"),b=[],c=[],d,e,f=0;f<a.length;f++)e=nb(a[f]),d=e.indexOf("="),-1==d?(b.push(""),c.push(e)):(b.push(e.substring(0,d)),c.push(e.substring(d+1)));for(a=b.length-1;0<=a;a--)this.remove(b[a])};
var fd=new ed("undefined"==typeof document?null:document);function gd(a){return!!dd.FPA_SAMESITE_PHASE2_MOD||!(void 0===a||!a)}
function hd(a,b,c,d){(a=B[a])||(a=(new ed(document)).get(b));return a?ad(a,c,d):null}
function id(a){var b=void 0===b?!1:b;var c=Zc(String(B.location.href)),d=[];var e=b;e=void 0===e?!1:e;var f=B.__SAPISID||B.__APISID||B.__3PSAPISID||B.__OVERRIDE_SID;gd(e)&&(f=f||B.__1PSAPISID);if(f)e=!0;else{var g=new ed(document);f=g.get("SAPISID")||g.get("APISID")||g.get("__Secure-3PAPISID")||g.get("SID");gd(e)&&(f=f||g.get("__Secure-1PAPISID"));e=!!f}e&&(e=(c=0==c.indexOf("https:")||0==c.indexOf("chrome-extension:")||0==c.indexOf("moz-extension:"))?B.__SAPISID:B.__APISID,e||(e=new ed(document),
e=e.get(c?"SAPISID":"APISID")||e.get("__Secure-3PAPISID")),(e=e?ad(e,c?"SAPISIDHASH":"APISIDHASH",a):null)&&d.push(e),c&&gd(b)&&((b=hd("__1PSAPISID","__Secure-1PAPISID","SAPISID1PHASH",a))&&d.push(b),(a=hd("__3PSAPISID","__Secure-3PAPISID","SAPISID3PHASH",a))&&d.push(a)));return 0==d.length?null:d.join(" ")}
;function jd(a){a&&"function"==typeof a.dispose&&a.dispose()}
;function kd(){this.l=this.l;this.v=this.v}
kd.prototype.l=!1;kd.prototype.dispose=function(){this.l||(this.l=!0,this.fa())};
kd.prototype.fa=function(){if(this.v)for(;this.v.length;)this.v.shift()()};function ld(a,b){this.type=a;this.h=this.target=b;this.defaultPrevented=this.j=!1}
ld.prototype.stopPropagation=function(){this.j=!0};
ld.prototype.preventDefault=function(){this.defaultPrevented=!0};function md(a){var b=C("window.location.href");null==a&&(a='Unknown Error of type "null/undefined"');if("string"===typeof a)return{message:a,name:"Unknown error",lineNumber:"Not available",fileName:b,stack:"Not available"};var c=!1;try{var d=a.lineNumber||a.line||"Not available"}catch(g){d="Not available",c=!0}try{var e=a.fileName||a.filename||a.sourceURL||B.$googDebugFname||b}catch(g){e="Not available",c=!0}b=nd(a);if(!(!c&&a.lineNumber&&a.fileName&&a.stack&&a.message&&a.name)){c=a.message;if(null==
c){if(a.constructor&&a.constructor instanceof Function){if(a.constructor.name)c=a.constructor.name;else if(c=a.constructor,od[c])c=od[c];else{c=String(c);if(!od[c]){var f=/function\s+([^\(]+)/m.exec(c);od[c]=f?f[1]:"[Anonymous]"}c=od[c]}c='Unknown Error of type "'+c+'"'}else c="Unknown Error of unknown type";"function"===typeof a.toString&&Object.prototype.toString!==a.toString&&(c+=": "+a.toString())}return{message:c,name:a.name||"UnknownError",lineNumber:d,fileName:e,stack:b||"Not available"}}a.stack=
b;return{message:a.message,name:a.name,lineNumber:a.lineNumber,fileName:a.fileName,stack:a.stack}}
function nd(a,b){b||(b={});b[pd(a)]=!0;var c=a.stack||"";(a=a.kb)&&!b[pd(a)]&&(c+="\nCaused by: ",a.stack&&0==a.stack.indexOf(a.toString())||(c+="string"===typeof a?a:a.message+"\n"),c+=nd(a,b));return c}
function pd(a){var b="";"function"===typeof a.toString&&(b=""+a);return b+a.stack}
var od={};var qd=function(){if(!B.addEventListener||!Object.defineProperty)return!1;var a=!1,b=Object.defineProperty({},"passive",{get:function(){a=!0}});
try{B.addEventListener("test",Ja,b),B.removeEventListener("test",Ja,b)}catch(c){}return a}();function rd(a,b){ld.call(this,a?a.type:"");this.relatedTarget=this.h=this.target=null;this.button=this.screenY=this.screenX=this.clientY=this.clientX=0;this.key="";this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.altKey=this.ctrlKey=!1;this.state=null;this.pointerId=0;this.pointerType="";this.i=null;a&&this.init(a,b)}
F(rd,ld);var sd={2:"touch",3:"pen",4:"mouse"};
rd.prototype.init=function(a,b){var c=this.type=a.type,d=a.changedTouches&&a.changedTouches.length?a.changedTouches[0]:null;this.target=a.target||a.srcElement;this.h=b;if(b=a.relatedTarget){if(Yb){a:{try{Ub(b.nodeName);var e=!0;break a}catch(f){}e=!1}e||(b=null)}}else"mouseover"==c?b=a.fromElement:"mouseout"==c&&(b=a.toElement);this.relatedTarget=b;d?(this.clientX=void 0!==d.clientX?d.clientX:d.pageX,this.clientY=void 0!==d.clientY?d.clientY:d.pageY,this.screenX=d.screenX||0,this.screenY=d.screenY||
0):(this.clientX=void 0!==a.clientX?a.clientX:a.pageX,this.clientY=void 0!==a.clientY?a.clientY:a.pageY,this.screenX=a.screenX||0,this.screenY=a.screenY||0);this.button=a.button;this.keyCode=a.keyCode||0;this.key=a.key||"";this.charCode=a.charCode||("keypress"==c?a.keyCode:0);this.ctrlKey=a.ctrlKey;this.altKey=a.altKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey;this.pointerId=a.pointerId||0;this.pointerType="string"===typeof a.pointerType?a.pointerType:sd[a.pointerType]||"";this.state=a.state;
this.i=a;a.defaultPrevented&&rd.N.preventDefault.call(this)};
rd.prototype.stopPropagation=function(){rd.N.stopPropagation.call(this);this.i.stopPropagation?this.i.stopPropagation():this.i.cancelBubble=!0};
rd.prototype.preventDefault=function(){rd.N.preventDefault.call(this);var a=this.i;a.preventDefault?a.preventDefault():a.returnValue=!1};var td="closure_listenable_"+(1E6*Math.random()|0);var ud=0;function vd(a,b,c,d,e){this.listener=a;this.proxy=null;this.src=b;this.type=c;this.capture=!!d;this.ra=e;this.key=++ud;this.ja=this.na=!1}
function wd(a){a.ja=!0;a.listener=null;a.proxy=null;a.src=null;a.ra=null}
;function xd(a){this.src=a;this.listeners={};this.h=0}
xd.prototype.add=function(a,b,c,d,e){var f=a.toString();a=this.listeners[f];a||(a=this.listeners[f]=[],this.h++);var g=yd(a,b,d,e);-1<g?(b=a[g],c||(b.na=!1)):(b=new vd(b,this.src,f,!!d,e),b.na=c,a.push(b));return b};
xd.prototype.remove=function(a,b,c,d){a=a.toString();if(!(a in this.listeners))return!1;var e=this.listeners[a];b=yd(e,b,c,d);return-1<b?(wd(e[b]),Array.prototype.splice.call(e,b,1),0==e.length&&(delete this.listeners[a],this.h--),!0):!1};
function zd(a,b){var c=b.type;c in a.listeners&&Ya(a.listeners[c],b)&&(wd(b),0==a.listeners[c].length&&(delete a.listeners[c],a.h--))}
function yd(a,b,c,d){for(var e=0;e<a.length;++e){var f=a[e];if(!f.ja&&f.listener==b&&f.capture==!!c&&f.ra==d)return e}return-1}
;var Ad="closure_lm_"+(1E6*Math.random()|0),Bd={},Cd=0;function Dd(a,b,c,d,e){if(d&&d.once)Ed(a,b,c,d,e);else if(Array.isArray(b))for(var f=0;f<b.length;f++)Dd(a,b[f],c,d,e);else c=Fd(c),a&&a[td]?a.Y(b,c,D(d)?!!d.capture:!!d,e):Gd(a,b,c,!1,d,e)}
function Gd(a,b,c,d,e,f){if(!b)throw Error("Invalid event type");var g=D(e)?!!e.capture:!!e,h=Hd(a);h||(a[Ad]=h=new xd(a));c=h.add(b,c,d,g,f);if(!c.proxy){d=Id();c.proxy=d;d.src=a;d.listener=c;if(a.addEventListener)qd||(e=g),void 0===e&&(e=!1),a.addEventListener(b.toString(),d,e);else if(a.attachEvent)a.attachEvent(Jd(b.toString()),d);else if(a.addListener&&a.removeListener)a.addListener(d);else throw Error("addEventListener and attachEvent are unavailable.");Cd++}}
function Id(){function a(c){return b.call(a.src,a.listener,c)}
var b=Kd;return a}
function Ed(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Ed(a,b[f],c,d,e);else c=Fd(c),a&&a[td]?a.h.add(String(b),c,!0,D(d)?!!d.capture:!!d,e):Gd(a,b,c,!0,d,e)}
function Ld(a,b,c,d,e){if(Array.isArray(b))for(var f=0;f<b.length;f++)Ld(a,b[f],c,d,e);else(d=D(d)?!!d.capture:!!d,c=Fd(c),a&&a[td])?a.h.remove(String(b),c,d,e):a&&(a=Hd(a))&&(b=a.listeners[b.toString()],a=-1,b&&(a=yd(b,c,d,e)),(c=-1<a?b[a]:null)&&Md(c))}
function Md(a){if("number"!==typeof a&&a&&!a.ja){var b=a.src;if(b&&b[td])zd(b.h,a);else{var c=a.type,d=a.proxy;b.removeEventListener?b.removeEventListener(c,d,a.capture):b.detachEvent?b.detachEvent(Jd(c),d):b.addListener&&b.removeListener&&b.removeListener(d);Cd--;(c=Hd(b))?(zd(c,a),0==c.h&&(c.src=null,b[Ad]=null)):wd(a)}}}
function Jd(a){return a in Bd?Bd[a]:Bd[a]="on"+a}
function Kd(a,b){if(a.ja)a=!0;else{b=new rd(b,this);var c=a.listener,d=a.ra||a.src;a.na&&Md(a);a=c.call(d,b)}return a}
function Hd(a){a=a[Ad];return a instanceof xd?a:null}
var Nd="__closure_events_fn_"+(1E9*Math.random()>>>0);function Fd(a){if("function"===typeof a)return a;a[Nd]||(a[Nd]=function(b){return a.handleEvent(b)});
return a[Nd]}
;function K(){kd.call(this);this.h=new xd(this);this.xa=this;this.I=null}
F(K,kd);K.prototype[td]=!0;K.prototype.addEventListener=function(a,b,c,d){Dd(this,a,b,c,d)};
K.prototype.removeEventListener=function(a,b,c,d){Ld(this,a,b,c,d)};
function Od(a,b){var c=a.I;if(c){var d=[];for(var e=1;c;c=c.I)d.push(c),++e}a=a.xa;c=b.type||b;"string"===typeof b?b=new ld(b,a):b instanceof ld?b.target=b.target||a:(e=b,b=new ld(c,a),hb(b,e));e=!0;if(d)for(var f=d.length-1;!b.j&&0<=f;f--){var g=b.h=d[f];e=Pd(g,c,!0,b)&&e}b.j||(g=b.h=a,e=Pd(g,c,!0,b)&&e,b.j||(e=Pd(g,c,!1,b)&&e));if(d)for(f=0;!b.j&&f<d.length;f++)g=b.h=d[f],e=Pd(g,c,!1,b)&&e}
K.prototype.fa=function(){K.N.fa.call(this);if(this.h){var a=this.h,b=0,c;for(c in a.listeners){for(var d=a.listeners[c],e=0;e<d.length;e++)++b,wd(d[e]);delete a.listeners[c];a.h--}}this.I=null};
K.prototype.Y=function(a,b,c,d){return this.h.add(String(a),b,!1,c,d)};
function Pd(a,b,c,d){b=a.h.listeners[String(b)];if(!b)return!0;b=b.concat();for(var e=!0,f=0;f<b.length;++f){var g=b[f];if(g&&!g.ja&&g.capture==c){var h=g.listener,k=g.ra||g.src;g.na&&zd(a.h,g);e=!1!==h.call(k,d)&&e}}return e&&!d.defaultPrevented}
;function Qd(a){var b,c;K.call(this);var d=this;this.A=this.j=0;this.K=null!==a&&void 0!==a?a:{L:function(e,f){return setTimeout(e,f)},
W:clearTimeout};this.i=null!==(c=null===(b=window.navigator)||void 0===b?void 0:b.onLine)&&void 0!==c?c:!0;this.m=function(){return z(function(e){return w(e,Rd(d),0)})};
window.addEventListener("offline",this.m);window.addEventListener("online",this.m);this.A||Sd(this)}
v(Qd,K);Qd.prototype.dispose=function(){window.removeEventListener("offline",this.m);window.removeEventListener("online",this.m);this.K.W(this.A);delete Qd.h};
Qd.prototype.D=function(){return this.i};
function Sd(a){a.A=a.K.L(function(){var b;return z(function(c){if(1==c.h)return a.i?(null===(b=window.navigator)||void 0===b?0:b.onLine)?c.o(3):w(c,Rd(a),3):w(c,Rd(a),3);Sd(a);c.h=0})},3E4)}
function Rd(a,b){return a.u?a.u:a.u=new Promise(function(c){var d,e,f;return z(function(g){switch(g.h){case 1:return d=window.AbortController?new window.AbortController:void 0,e=null===d||void 0===d?void 0:d.signal,f=!1,sa(g,2,3),d&&(a.j=a.K.L(function(){d.abort()},b||2E4)),w(g,fetch("/generate_204",{method:"HEAD",
signal:e}),5);case 5:f=!0;case 3:wa(g);a.u=void 0;a.j&&(a.K.W(a.j),a.j=0);f!==a.i&&(a.i=f,a.i?Od(a,"networkstatus-online"):Od(a,"networkstatus-offline"));c(f);xa(g);break;case 2:va(g),f=!1,g.o(3)}})})}
;function Td(){this.data_=[];this.h=-1}
Td.prototype.set=function(a,b){b=void 0===b?!0:b;0<=a&&52>a&&0===a%1&&this.data_[a]!=b&&(this.data_[a]=b,this.h=-1)};
Td.prototype.get=function(a){return!!this.data_[a]};
function Ud(a){-1==a.h&&(a.h=Xa(a.data_,function(b,c,d){return c?b+Math.pow(2,d):b},0));
return a.h}
;function Wd(a,b){this.j=a;this.l=b;this.i=0;this.h=null}
Wd.prototype.get=function(){if(0<this.i){this.i--;var a=this.h;this.h=a.next;a.next=null}else a=this.j();return a};
function Xd(a,b){a.l(b);100>a.i&&(a.i++,b.next=a.h,a.h=b)}
;var Yd;
function Zd(){var a=B.MessageChannel;"undefined"===typeof a&&"undefined"!==typeof window&&window.postMessage&&window.addEventListener&&!H("Presto")&&(a=function(){var e=Pc(document,"IFRAME");e.style.display="none";document.documentElement.appendChild(e);var f=e.contentWindow;e=f.document;e.open();e.close();var g="callImmediate"+Math.random(),h="file:"==f.location.protocol?"*":f.location.protocol+"//"+f.location.host;e=Ra(function(k){if(("*"==h||k.origin==h)&&k.data==g)this.port1.onmessage()},this);
f.addEventListener("message",e,!1);this.port1={};this.port2={postMessage:function(){f.postMessage(g,h)}}});
if("undefined"!==typeof a&&!H("Trident")&&!H("MSIE")){var b=new a,c={},d=c;b.port1.onmessage=function(){if(void 0!==c.next){c=c.next;var e=c.La;c.La=null;e()}};
return function(e){d.next={La:e};d=d.next;b.port2.postMessage(0)}}return function(e){B.setTimeout(e,0)}}
;function $d(){this.i=this.h=null}
$d.prototype.add=function(a,b){var c=ae.get();c.set(a,b);this.i?this.i.next=c:this.h=c;this.i=c};
$d.prototype.remove=function(){var a=null;this.h&&(a=this.h,this.h=this.h.next,this.h||(this.i=null),a.next=null);return a};
var ae=new Wd(function(){return new be},function(a){return a.reset()});
function be(){this.next=this.scope=this.h=null}
be.prototype.set=function(a,b){this.h=a;this.scope=b;this.next=null};
be.prototype.reset=function(){this.next=this.scope=this.h=null};function ce(a,b){de||ee();fe||(de(),fe=!0);ge.add(a,b)}
var de;function ee(){if(B.Promise&&B.Promise.resolve){var a=B.Promise.resolve(void 0);de=function(){a.then(he)}}else de=function(){var b=he;
"function"!==typeof B.setImmediate||B.Window&&B.Window.prototype&&!H("Edge")&&B.Window.prototype.setImmediate==B.setImmediate?(Yd||(Yd=Zd()),Yd(b)):B.setImmediate(b)}}
var fe=!1,ge=new $d;function he(){for(var a;a=ge.remove();){try{a.h.call(a.scope)}catch(b){Sb(b)}Xd(ae,a)}fe=!1}
;function ie(a,b){this.h=a[B.Symbol.iterator]();this.i=b;this.j=0}
ie.prototype[Symbol.iterator]=function(){return this};
ie.prototype.next=function(){var a=this.h.next();return{value:a.done?void 0:this.i.call(void 0,a.value,this.j++),done:a.done}};
function je(a,b){return new ie(a,b)}
;function ke(){this.blockSize=-1}
;function le(){this.blockSize=-1;this.blockSize=64;this.h=[];this.m=[];this.v=[];this.j=[];this.j[0]=128;for(var a=1;a<this.blockSize;++a)this.j[a]=0;this.l=this.i=0;this.reset()}
F(le,ke);le.prototype.reset=function(){this.h[0]=1732584193;this.h[1]=4023233417;this.h[2]=2562383102;this.h[3]=271733878;this.h[4]=3285377520;this.l=this.i=0};
function me(a,b,c){c||(c=0);var d=a.v;if("string"===typeof b)for(var e=0;16>e;e++)d[e]=b.charCodeAt(c)<<24|b.charCodeAt(c+1)<<16|b.charCodeAt(c+2)<<8|b.charCodeAt(c+3),c+=4;else for(e=0;16>e;e++)d[e]=b[c]<<24|b[c+1]<<16|b[c+2]<<8|b[c+3],c+=4;for(e=16;80>e;e++){var f=d[e-3]^d[e-8]^d[e-14]^d[e-16];d[e]=(f<<1|f>>>31)&4294967295}b=a.h[0];c=a.h[1];var g=a.h[2],h=a.h[3],k=a.h[4];for(e=0;80>e;e++){if(40>e)if(20>e){f=h^c&(g^h);var l=1518500249}else f=c^g^h,l=1859775393;else 60>e?(f=c&g|h&(c|g),l=2400959708):
(f=c^g^h,l=3395469782);f=(b<<5|b>>>27)+f+k+l+d[e]&4294967295;k=h;h=g;g=(c<<30|c>>>2)&4294967295;c=b;b=f}a.h[0]=a.h[0]+b&4294967295;a.h[1]=a.h[1]+c&4294967295;a.h[2]=a.h[2]+g&4294967295;a.h[3]=a.h[3]+h&4294967295;a.h[4]=a.h[4]+k&4294967295}
le.prototype.update=function(a,b){if(null!=a){void 0===b&&(b=a.length);for(var c=b-this.blockSize,d=0,e=this.m,f=this.i;d<b;){if(0==f)for(;d<=c;)me(this,a,d),d+=this.blockSize;if("string"===typeof a)for(;d<b;){if(e[f]=a.charCodeAt(d),++f,++d,f==this.blockSize){me(this,e);f=0;break}}else for(;d<b;)if(e[f]=a[d],++f,++d,f==this.blockSize){me(this,e);f=0;break}}this.i=f;this.l+=b}};
le.prototype.digest=function(){var a=[],b=8*this.l;56>this.i?this.update(this.j,56-this.i):this.update(this.j,this.blockSize-(this.i-56));for(var c=this.blockSize-1;56<=c;c--)this.m[c]=b&255,b/=256;me(this,this.m);for(c=b=0;5>c;c++)for(var d=24;0<=d;d-=8)a[b]=this.h[c]>>d&255,++b;return a};var ne="StopIteration"in B?B.StopIteration:{message:"StopIteration",stack:""};function oe(){}
oe.prototype.P=function(){throw ne;};
oe.prototype.next=function(){return pe};
var pe={done:!0,value:void 0};function qe(a){return{value:a,done:!1}}
function re(a){if(a.done)throw ne;return a.value}
oe.prototype.J=function(){return this};function se(a){if(a instanceof te||a instanceof ue||a instanceof ve)return a;if("function"==typeof a.P)return new te(function(){return we(a)});
if("function"==typeof a[Symbol.iterator])return new te(function(){return a[Symbol.iterator]()});
if("function"==typeof a.J)return new te(function(){return we(a.J())});
throw Error("Not an iterator or iterable.");}
function we(a){if(!(a instanceof oe))return a;var b=!1;return{next:function(){for(var c;!b;)try{c=a.P();break}catch(d){if(d!==ne)throw d;b=!0}return{value:c,done:b}}}}
function te(a){this.h=a}
te.prototype.J=function(){return new ue(this.h())};
te.prototype[Symbol.iterator]=function(){return new ve(this.h())};
te.prototype.i=function(){return new ve(this.h())};
function ue(a){this.h=a}
v(ue,oe);ue.prototype.P=function(){var a=this.h.next();if(a.done)throw ne;return a.value};
ue.prototype.next=function(){return this.h.next()};
ue.prototype[Symbol.iterator]=function(){return new ve(this.h)};
ue.prototype.i=function(){return new ve(this.h)};
function ve(a){te.call(this,function(){return a});
this.j=a}
v(ve,te);ve.prototype.next=function(){return this.j.next()};function xe(a,b){this.i={};this.h=[];this.j=this.size=0;var c=arguments.length;if(1<c){if(c%2)throw Error("Uneven number of arguments");for(var d=0;d<c;d+=2)this.set(arguments[d],arguments[d+1])}else if(a)if(a instanceof xe)for(c=ye(a),d=0;d<c.length;d++)this.set(c[d],a.get(c[d]));else for(d in a)this.set(d,a[d])}
function ye(a){ze(a);return a.h.concat()}
m=xe.prototype;m.has=function(a){return Ae(this.i,a)};
m.equals=function(a,b){if(this===a)return!0;if(this.size!=a.size)return!1;b=b||Be;ze(this);for(var c,d=0;c=this.h[d];d++)if(!b(this.get(c),a.get(c)))return!1;return!0};
function Be(a,b){return a===b}
m.isEmpty=function(){return 0==this.size};
m.clear=function(){this.i={};this.j=this.size=this.h.length=0};
m.remove=function(a){return this.delete(a)};
m.delete=function(a){return Ae(this.i,a)?(delete this.i[a],--this.size,this.j++,this.h.length>2*this.size&&ze(this),!0):!1};
function ze(a){if(a.size!=a.h.length){for(var b=0,c=0;b<a.h.length;){var d=a.h[b];Ae(a.i,d)&&(a.h[c++]=d);b++}a.h.length=c}if(a.size!=a.h.length){var e={};for(c=b=0;b<a.h.length;)d=a.h[b],Ae(e,d)||(a.h[c++]=d,e[d]=1),b++;a.h.length=c}}
m.get=function(a,b){return Ae(this.i,a)?this.i[a]:b};
m.set=function(a,b){Ae(this.i,a)||(this.size+=1,this.h.push(a),this.j++);this.i[a]=b};
m.forEach=function(a,b){for(var c=ye(this),d=0;d<c.length;d++){var e=c[d],f=this.get(e);a.call(b,f,e,this)}};
m.clone=function(){return new xe(this)};
m.keys=function(){return se(this.J(!0)).i()};
m.values=function(){return se(this.J(!1)).i()};
m.entries=function(){var a=this;return je(this.keys(),function(b){return[b,a.get(b)]})};
m.J=function(a){ze(this);var b=0,c=this.j,d=this,e=new oe;e.next=function(){if(c!=d.j)throw Error("The map has changed since the iterator was created");if(b>=d.h.length)return pe;var g=d.h[b++];return qe(a?g:d.i[g])};
var f=e.next;e.P=function(){return re(f.call(e))};
return e};
function Ae(a,b){return Object.prototype.hasOwnProperty.call(a,b)}
;var Ce=B.JSON.stringify;function De(){var a=this;this.promise=new Promise(function(b,c){a.resolve=b;a.reject=c})}
;function Ee(a){this.h=0;this.u=void 0;this.l=this.i=this.j=null;this.m=this.v=!1;if(a!=Ja)try{var b=this;a.call(void 0,function(c){Fe(b,2,c)},function(c){Fe(b,3,c)})}catch(c){Fe(this,3,c)}}
function Ge(){this.next=this.context=this.onRejected=this.i=this.h=null;this.j=!1}
Ge.prototype.reset=function(){this.context=this.onRejected=this.i=this.h=null;this.j=!1};
var He=new Wd(function(){return new Ge},function(a){a.reset()});
function Ie(a,b,c){var d=He.get();d.i=a;d.onRejected=b;d.context=c;return d}
Ee.prototype.then=function(a,b,c){return Je(this,"function"===typeof a?a:null,"function"===typeof b?b:null,c)};
Ee.prototype.$goog_Thenable=!0;Ee.prototype.cancel=function(a){if(0==this.h){var b=new Ke(a);ce(function(){Le(this,b)},this)}};
function Le(a,b){if(0==a.h)if(a.j){var c=a.j;if(c.i){for(var d=0,e=null,f=null,g=c.i;g&&(g.j||(d++,g.h==a&&(e=g),!(e&&1<d)));g=g.next)e||(f=g);e&&(0==c.h&&1==d?Le(c,b):(f?(d=f,d.next==c.l&&(c.l=d),d.next=d.next.next):Me(c),Ne(c,e,3,b)))}a.j=null}else Fe(a,3,b)}
function Oe(a,b){a.i||2!=a.h&&3!=a.h||Pe(a);a.l?a.l.next=b:a.i=b;a.l=b}
function Je(a,b,c,d){var e=Ie(null,null,null);e.h=new Ee(function(f,g){e.i=b?function(h){try{var k=b.call(d,h);f(k)}catch(l){g(l)}}:f;
e.onRejected=c?function(h){try{var k=c.call(d,h);void 0===k&&h instanceof Ke?g(h):f(k)}catch(l){g(l)}}:g});
e.h.j=a;Oe(a,e);return e.h}
Ee.prototype.I=function(a){this.h=0;Fe(this,2,a)};
Ee.prototype.O=function(a){this.h=0;Fe(this,3,a)};
function Fe(a,b,c){if(0==a.h){a===c&&(b=3,c=new TypeError("Promise cannot resolve to itself"));a.h=1;a:{var d=c,e=a.I,f=a.O;if(d instanceof Ee){Oe(d,Ie(e||Ja,f||null,a));var g=!0}else{if(d)try{var h=!!d.$goog_Thenable}catch(l){h=!1}else h=!1;if(h)d.then(e,f,a),g=!0;else{if(D(d))try{var k=d.then;if("function"===typeof k){Qe(d,k,e,f,a);g=!0;break a}}catch(l){f.call(a,l);g=!0;break a}g=!1}}}g||(a.u=c,a.h=b,a.j=null,Pe(a),3!=b||c instanceof Ke||Re(a,c))}}
function Qe(a,b,c,d,e){function f(k){h||(h=!0,d.call(e,k))}
function g(k){h||(h=!0,c.call(e,k))}
var h=!1;try{b.call(a,g,f)}catch(k){f(k)}}
function Pe(a){a.v||(a.v=!0,ce(a.A,a))}
function Me(a){var b=null;a.i&&(b=a.i,a.i=b.next,b.next=null);a.i||(a.l=null);return b}
Ee.prototype.A=function(){for(var a;a=Me(this);)Ne(this,a,this.h,this.u);this.v=!1};
function Ne(a,b,c,d){if(3==c&&b.onRejected&&!b.j)for(;a&&a.m;a=a.j)a.m=!1;if(b.h)b.h.j=null,Se(b,c,d);else try{b.j?b.i.call(b.context):Se(b,c,d)}catch(e){Te.call(null,e)}Xd(He,b)}
function Se(a,b,c){2==b?a.i.call(a.context,c):a.onRejected&&a.onRejected.call(a.context,c)}
function Re(a,b){a.m=!0;ce(function(){a.m&&Te.call(null,b)})}
var Te=Sb;function Ke(a){Ta.call(this,a)}
F(Ke,Ta);Ke.prototype.name="cancel";function L(a){kd.call(this);this.u=1;this.j=[];this.m=0;this.h=[];this.i={};this.A=!!a}
F(L,kd);m=L.prototype;m.subscribe=function(a,b,c){var d=this.i[a];d||(d=this.i[a]=[]);var e=this.u;this.h[e]=a;this.h[e+1]=b;this.h[e+2]=c;this.u=e+3;d.push(e);return e};
function Ue(a,b,c){var d=Ve;if(a=d.i[a]){var e=d.h;(a=a.find(function(f){return e[f+1]==b&&e[f+2]==c}))&&d.la(a)}}
m.la=function(a){var b=this.h[a];if(b){var c=this.i[b];0!=this.m?(this.j.push(a),this.h[a+1]=Ja):(c&&Ya(c,a),delete this.h[a],delete this.h[a+1],delete this.h[a+2])}return!!b};
m.ca=function(a,b){var c=this.i[a];if(c){for(var d=Array(arguments.length-1),e=1,f=arguments.length;e<f;e++)d[e-1]=arguments[e];if(this.A)for(e=0;e<c.length;e++){var g=c[e];We(this.h[g+1],this.h[g+2],d)}else{this.m++;try{for(e=0,f=c.length;e<f&&!this.l;e++)g=c[e],this.h[g+1].apply(this.h[g+2],d)}finally{if(this.m--,0<this.j.length&&0==this.m)for(;c=this.j.pop();)this.la(c)}}return 0!=e}return!1};
function We(a,b,c){ce(function(){a.apply(b,c)})}
m.clear=function(a){if(a){var b=this.i[a];b&&(b.forEach(this.la,this),delete this.i[a])}else this.h.length=0,this.i={}};
m.fa=function(){L.N.fa.call(this);this.clear();this.j.length=0};function Xe(a){this.h=a}
Xe.prototype.set=function(a,b){void 0===b?this.h.remove(a):this.h.set(a,Ce(b))};
Xe.prototype.get=function(a){try{var b=this.h.get(a)}catch(c){return}if(null!==b)try{return JSON.parse(b)}catch(c){throw"Storage: Invalid value was encountered";}};
Xe.prototype.remove=function(a){this.h.remove(a)};function Ye(a){this.h=a}
F(Ye,Xe);function Ze(a){this.data=a}
function $e(a){return void 0===a||a instanceof Ze?a:new Ze(a)}
Ye.prototype.set=function(a,b){Ye.N.set.call(this,a,$e(b))};
Ye.prototype.i=function(a){a=Ye.N.get.call(this,a);if(void 0===a||a instanceof Object)return a;throw"Storage: Invalid value was encountered";};
Ye.prototype.get=function(a){if(a=this.i(a)){if(a=a.data,void 0===a)throw"Storage: Invalid value was encountered";}else a=void 0;return a};function af(a){this.h=a}
F(af,Ye);af.prototype.set=function(a,b,c){if(b=$e(b)){if(c){if(c<Date.now()){af.prototype.remove.call(this,a);return}b.expiration=c}b.creation=Date.now()}af.N.set.call(this,a,b)};
af.prototype.i=function(a){var b=af.N.i.call(this,a);if(b){var c=b.creation,d=b.expiration;if(d&&d<Date.now()||c&&c>Date.now())af.prototype.remove.call(this,a);else return b}};function bf(){}
;function cf(){}
F(cf,bf);cf.prototype[Symbol.iterator]=function(){return se(this.J(!0)).i()};
cf.prototype.clear=function(){var a=Array.from(this);a=t(a);for(var b=a.next();!b.done;b=a.next())this.remove(b.value)};function df(a){this.h=a}
F(df,cf);m=df.prototype;m.isAvailable=function(){if(!this.h)return!1;try{return this.h.setItem("__sak","1"),this.h.removeItem("__sak"),!0}catch(a){return!1}};
m.set=function(a,b){try{this.h.setItem(a,b)}catch(c){if(0==this.h.length)throw"Storage mechanism: Storage disabled";throw"Storage mechanism: Quota exceeded";}};
m.get=function(a){a=this.h.getItem(a);if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeItem(a)};
m.J=function(a){var b=0,c=this.h,d=new oe;d.next=function(){if(b>=c.length)return pe;var f=c.key(b++);if(a)return qe(f);f=c.getItem(f);if("string"!==typeof f)throw"Storage mechanism: Invalid value was encountered";return qe(f)};
var e=d.next;d.P=function(){return re(e.call(d))};
return d};
m.clear=function(){this.h.clear()};
m.key=function(a){return this.h.key(a)};function ef(){var a=null;try{a=window.localStorage||null}catch(b){}this.h=a}
F(ef,df);function ff(a,b){this.i=a;this.h=null;var c;if(c=Wb)c=!(9<=Number(hc));if(c){gf||(gf=new xe);this.h=gf.get(a);this.h||(b?this.h=document.getElementById(b):(this.h=document.createElement("userdata"),this.h.addBehavior("#default#userData"),document.body.appendChild(this.h)),gf.set(a,this.h));try{this.h.load(this.i)}catch(d){this.h=null}}}
F(ff,cf);var hf={".":".2E","!":".21","~":".7E","*":".2A","'":".27","(":".28",")":".29","%":"."},gf=null;function jf(a){return"_"+encodeURIComponent(a).replace(/[.!~*'()%]/g,function(b){return hf[b]})}
m=ff.prototype;m.isAvailable=function(){return!!this.h};
m.set=function(a,b){this.h.setAttribute(jf(a),b);kf(this)};
m.get=function(a){a=this.h.getAttribute(jf(a));if("string"!==typeof a&&null!==a)throw"Storage mechanism: Invalid value was encountered";return a};
m.remove=function(a){this.h.removeAttribute(jf(a));kf(this)};
m.J=function(a){var b=0,c=this.h.XMLDocument.documentElement.attributes,d=new oe;d.next=function(){if(b>=c.length)return pe;var f=c[b++];if(a)return qe(decodeURIComponent(f.nodeName.replace(/\./g,"%")).substr(1));f=f.nodeValue;if("string"!==typeof f)throw"Storage mechanism: Invalid value was encountered";return qe(f)};
var e=d.next;d.P=function(){return re(e.call(d))};
return d};
m.clear=function(){for(var a=this.h.XMLDocument.documentElement,b=a.attributes.length;0<b;b--)a.removeAttribute(a.attributes[b-1].nodeName);kf(this)};
function kf(a){try{a.h.save(a.i)}catch(b){throw"Storage mechanism: Quota exceeded";}}
;function lf(a,b){this.i=a;this.h=b+"::"}
F(lf,cf);lf.prototype.set=function(a,b){this.i.set(this.h+a,b)};
lf.prototype.get=function(a){return this.i.get(this.h+a)};
lf.prototype.remove=function(a){this.i.remove(this.h+a)};
lf.prototype.J=function(a){var b=this.i.J(!0),c=this,d=new oe;d.next=function(){try{var f=b.P()}catch(g){if(g===ne)return pe;throw g;}for(;f.substr(0,c.h.length)!=c.h;)try{f=b.P()}catch(g){if(g===ne)return pe;throw g;}return qe(a?f.substr(c.h.length):c.i.get(f))};
var e=d.next;d.P=function(){return re(e.call(d))};
return d};function mf(a){I.call(this,a)}
v(mf,I);mf.prototype.getKey=function(){return Bc(this,1)};
mf.prototype.X=function(){return Bc(this,2===Dc(this,nf)?2:-1)};
mf.prototype.setValue=function(a){var b=Dc(this,nf);b&&2!==b&&null!=a&&(this.h&&b in this.h&&(this.h[b]=void 0),J(this,b,void 0));return J(this,2,a)};
var nf=[2,3,4,5,6];function of(a){I.call(this,a)}
v(of,I);function pf(a){I.call(this,a)}
v(pf,I);function qf(a){I.call(this,a)}
v(qf,I);function rf(a){I.call(this,a,-1,sf)}
v(rf,I);rf.prototype.getPlayerType=function(){return Bc(this,36)};
rf.prototype.setHomeGroupInfo=function(a){return Gc(this,81,a)};
var sf=[9,66,24,32,86,100,101];function tf(a){I.call(this,a,-1,uf)}
v(tf,I);var uf=[15,26,28];function vf(a){I.call(this,a)}
v(vf,I);vf.prototype.setToken=function(a){return J(this,2,a)};function wf(a){I.call(this,a,-1,xf)}
v(wf,I);wf.prototype.setSafetyMode=function(a){return J(this,5,a)};
var xf=[12];function yf(a){I.call(this,a,-1,zf)}
v(yf,I);var zf=[12];function Af(a){I.call(this,a)}
v(Af,I);function Bf(a){I.call(this,a)}
v(Bf,I);var Cf=[1,2];function Df(a){I.call(this,a,-1,Ef)}
v(Df,I);var Ef=[3];function Ff(a){I.call(this,a,1)}
v(Ff,I);var Gf,Hf,If,Jf=B.window,Kf=(null===(Gf=null===Jf||void 0===Jf?void 0:Jf.yt)||void 0===Gf?void 0:Gf.config_)||(null===(Hf=null===Jf||void 0===Jf?void 0:Jf.ytcfg)||void 0===Hf?void 0:Hf.data_)||{},Lf=(null===(If=null===Jf||void 0===Jf?void 0:Jf.ytcfg)||void 0===If?void 0:If.obfuscatedData_)||[];function Mf(){Ff.apply(this,arguments)}
v(Mf,Ff);new Mf(Lf);E("yt.config_",Kf);E("yt.configJspb_",Lf);function Nf(){var a=arguments;1<a.length?Kf[a[0]]=a[1]:1===a.length&&Object.assign(Kf,a[0])}
function O(a,b){return a in Kf?Kf[a]:b}
function Of(){return O("LATEST_ECATCHER_SERVICE_TRACKING_PARAMS",void 0)}
;var Pf=[];function Qf(a){Pf.forEach(function(b){return b(a)})}
function Rf(a){return a&&window.yterr?function(){try{return a.apply(this,arguments)}catch(b){Sf(b)}}:a}
function Sf(a,b,c,d){var e=C("yt.logging.errors.log");e?e(a,"ERROR",b,c,d):(e=O("ERRORS",[]),e.push([a,"ERROR",b,c,d]),Nf("ERRORS",e));Qf(a)}
function Tf(a,b,c,d){var e=C("yt.logging.errors.log");e?e(a,"WARNING",b,c,d):(e=O("ERRORS",[]),e.push([a,"WARNING",b,c,d]),Nf("ERRORS",e))}
;var Uf=0;E("ytDomDomGetNextId",C("ytDomDomGetNextId")||function(){return++Uf});var Vf={stopImmediatePropagation:1,stopPropagation:1,preventMouseEvent:1,preventManipulation:1,preventDefault:1,layerX:1,layerY:1,screenX:1,screenY:1,scale:1,rotation:1,webkitMovementX:1,webkitMovementY:1};
function Wf(a){this.type="";this.state=this.source=this.data=this.currentTarget=this.relatedTarget=this.target=null;this.charCode=this.keyCode=0;this.metaKey=this.shiftKey=this.ctrlKey=this.altKey=!1;this.rotation=this.clientY=this.clientX=0;this.scale=1;this.changedTouches=this.touches=null;try{if(a=a||window.event){this.event=a;for(var b in a)b in Vf||(this[b]=a[b]);this.scale=a.scale;this.rotation=a.rotation;var c=a.target||a.srcElement;c&&3==c.nodeType&&(c=c.parentNode);this.target=c;var d=a.relatedTarget;
if(d)try{d=d.nodeName?d:null}catch(e){d=null}else"mouseover"==this.type?d=a.fromElement:"mouseout"==this.type&&(d=a.toElement);this.relatedTarget=d;this.clientX=void 0!=a.clientX?a.clientX:a.pageX;this.clientY=void 0!=a.clientY?a.clientY:a.pageY;this.keyCode=a.keyCode?a.keyCode:a.which;this.charCode=a.charCode||("keypress"==this.type?this.keyCode:0);this.altKey=a.altKey;this.ctrlKey=a.ctrlKey;this.shiftKey=a.shiftKey;this.metaKey=a.metaKey}}catch(e){}}
Wf.prototype.preventDefault=function(){this.event&&(this.event.returnValue=!1,this.event.preventDefault&&this.event.preventDefault())};
Wf.prototype.stopPropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopPropagation&&this.event.stopPropagation())};
Wf.prototype.stopImmediatePropagation=function(){this.event&&(this.event.cancelBubble=!0,this.event.stopImmediatePropagation&&this.event.stopImmediatePropagation())};var db=B.ytEventsEventsListeners||{};E("ytEventsEventsListeners",db);var Xf=B.ytEventsEventsCounter||{count:0};E("ytEventsEventsCounter",Xf);
function Yf(a,b,c,d){d=void 0===d?{}:d;a.addEventListener&&("mouseenter"!=b||"onmouseenter"in document?"mouseleave"!=b||"onmouseenter"in document?"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"):b="mouseout":b="mouseover");return cb(function(e){var f="boolean"===typeof e[4]&&e[4]==!!d,g=D(e[4])&&D(d)&&eb(e[4],d);return!!e.length&&e[0]==a&&e[1]==b&&e[2]==c&&(f||g)})}
function Zf(a){a&&("string"==typeof a&&(a=[a]),G(a,function(b){if(b in db){var c=db[b],d=c[0],e=c[1],f=c[3];c=c[4];d.removeEventListener?$f()||"boolean"===typeof c?d.removeEventListener(e,f,c):d.removeEventListener(e,f,!!c.capture):d.detachEvent&&d.detachEvent("on"+e,f);delete db[b]}}))}
var $f=Va(function(){var a=!1;try{var b=Object.defineProperty({},"capture",{get:function(){a=!0}});
window.addEventListener("test",null,b)}catch(c){}return a});
function ag(a,b,c){var d=void 0===d?{}:d;if(a&&(a.addEventListener||a.attachEvent)){var e=Yf(a,b,c,d);if(!e){e=++Xf.count+"";var f=!("mouseenter"!=b&&"mouseleave"!=b||!a.addEventListener||"onmouseenter"in document);var g=f?function(h){h=new Wf(h);if(!Rc(h.relatedTarget,function(k){return k==a}))return h.currentTarget=a,h.type=b,c.call(a,h)}:function(h){h=new Wf(h);
h.currentTarget=a;return c.call(a,h)};
g=Rf(g);a.addEventListener?("mouseenter"==b&&f?b="mouseover":"mouseleave"==b&&f?b="mouseout":"mousewheel"==b&&"MozBoxSizing"in document.documentElement.style&&(b="MozMousePixelScroll"),$f()||"boolean"===typeof d?a.addEventListener(b,g,d):a.addEventListener(b,g,!!d.capture)):a.attachEvent("on"+b,g);db[e]=[a,b,c,g,d]}}}
;function bg(a,b){"function"===typeof a&&(a=Rf(a));return window.setTimeout(a,b)}
function cg(a){"function"===typeof a&&(a=Rf(a));return window.setInterval(a,250)}
;var dg=/^[\w.]*$/,eg={q:!0,search_query:!0};function fg(a,b){b=a.split(b);for(var c={},d=0,e=b.length;d<e;d++){var f=b[d].split("=");if(1==f.length&&f[0]||2==f.length)try{var g=gg(f[0]||""),h=gg(f[1]||"");g in c?Array.isArray(c[g])?ab(c[g],h):c[g]=[c[g],h]:c[g]=h}catch(p){var k=p,l=f[0],n=String(fg);k.args=[{key:l,value:f[1],query:a,method:hg==n?"unchanged":n}];eg.hasOwnProperty(l)||Tf(k)}}return c}
var hg=String(fg);function ig(a){var b=[];bb(a,function(c,d){var e=encodeURIComponent(String(d)),f;Array.isArray(c)?f=c:f=[c];G(f,function(g){""==g?b.push(e):b.push(e+"="+encodeURIComponent(String(g)))})});
return b.join("&")}
function jg(a){"?"==a.charAt(0)&&(a=a.substr(1));return fg(a,"&")}
function kg(a,b,c){var d=a.split("#",2);a=d[0];d=1<d.length?"#"+d[1]:"";var e=a.split("?",2);a=e[0];e=jg(e[1]||"");for(var f in b)!c&&null!==e&&f in e||(e[f]=b[f]);b=a;a=Pb(e);a?(c=b.indexOf("#"),0>c&&(c=b.length),f=b.indexOf("?"),0>f||f>c?(f=c,e=""):e=b.substring(f+1,c),b=[b.substr(0,f),e,b.substr(c)],c=b[1],b[1]=a?c?c+"&"+a:a:c,a=b[0]+(b[1]?"?"+b[1]:"")+b[2]):a=b;return a+d}
function lg(a){if(!b)var b=window.location.href;var c=a.match(Kb)[1]||null,d=Mb(a);c&&d?(a=a.match(Kb),b=b.match(Kb),a=a[3]==b[3]&&a[1]==b[1]&&a[4]==b[4]):a=d?Mb(b)==d&&(Number(b.match(Kb)[4]||null)||null)==(Number(a.match(Kb)[4]||null)||null):!0;return a}
function gg(a){return a&&a.match(dg)?a:decodeURIComponent(a.replace(/\+/g," "))}
;function Q(a){a=mg(a);return"string"===typeof a&&"false"===a?!1:!!a}
function ng(a,b){a=mg(a);return void 0===a&&void 0!==b?b:Number(a||0)}
function mg(a){var b=O("EXPERIMENTS_FORCED_FLAGS",{});return void 0!==b[a]?b[a]:O("EXPERIMENT_FLAGS",{})[a]}
function og(){var a=[],b=O("EXPERIMENTS_FORCED_FLAGS",{});for(c in b)a.push({key:c,value:String(b[c])});var c=O("EXPERIMENT_FLAGS",{});for(var d in c)d.startsWith("force_")&&void 0===b[d]&&a.push({key:d,value:String(c[d])});return a}
;var pg={Mb:"WEB_DISPLAY_MODE_UNKNOWN",Ib:"WEB_DISPLAY_MODE_BROWSER",Kb:"WEB_DISPLAY_MODE_MINIMAL_UI",Lb:"WEB_DISPLAY_MODE_STANDALONE",Jb:"WEB_DISPLAY_MODE_FULLSCREEN"};var qg={appSettingsCaptured:!0,visualElementAttached:!0,visualElementGestured:!0,visualElementHidden:!0,visualElementShown:!0,flowEvent:!0,visualElementStateChanged:!0,playbackAssociated:!0,youThere:!0,accountStateChangeSignedIn:!0,accountStateChangeSignedOut:!0},rg={latencyActionBaselined:!0,latencyActionInfo:!0,latencyActionTicked:!0,bedrockRepetitiveActionTimed:!0,adsClientStateChange:!0,streamzIncremented:!0,mdxDialAdditionalDataUpdateEvent:!0,tvhtml5WatchKeyEvent:!0,tvhtml5VideoSeek:!0,tokenRefreshEvent:!0,
adNotify:!0,adNotifyFilled:!0,tvhtml5LaunchUrlComponentChanged:!0,bedrockResourceConsumptionSnapshot:!0,deviceStartupMetrics:!0,mdxSignIn:!0,tvhtml5KeyboardLogging:!0,tvhtml5StartupSoundEvent:!0,tvhtml5LiveChatStatus:!0,tvhtml5DeviceStorageStatus:!0,tvhtml5LocalStorage:!0,directSignInEvent:!0,finalPayload:!0,tvhtml5SearchCompleted:!0,tvhtml5KeyboardPerformance:!0,adNotifyFailure:!0,latencyActionSpan:!0,tvhtml5AccountDialogOpened:!0,tvhtml5ApiTest:!0};function sg(){}
function tg(a,b){return ug(a,0,b)}
sg.prototype.L=function(a,b){return ug(a,1,b)};
function vg(a,b){ug(a,2,b)}
;function wg(){sg.apply(this,arguments)}
v(wg,sg);function xg(){wg.h||(wg.h=new wg);return wg.h}
function ug(a,b,c){void 0!==c&&Number.isNaN(Number(c))&&(c=void 0);var d=C("yt.scheduler.instance.addJob");return d?d(a,b,c):void 0===c?(a(),NaN):bg(a,c||0)}
wg.prototype.W=function(a){if(void 0===a||!Number.isNaN(Number(a))){var b=C("yt.scheduler.instance.cancelJob");b?b(a):window.clearTimeout(a)}};
wg.prototype.start=function(){var a=C("yt.scheduler.instance.start");a&&a()};var yg=xg();function zg(a){var b=Ag;a=void 0===a?C("yt.ads.biscotti.lastId_")||"":a;var c=Object,d=c.assign,e={};e.dt=Yc;e.flash="0";a:{try{var f=b.h.top.location.href}catch(ta){f=2;break a}f=f?f===b.i.location.href?0:1:2}e=(e.frm=f,e);try{e.u_tz=-(new Date).getTimezoneOffset();var g=void 0===g?Kc:g;try{var h=g.history.length}catch(ta){h=0}e.u_his=h;var k;e.u_h=null==(k=Kc.screen)?void 0:k.height;var l;e.u_w=null==(l=Kc.screen)?void 0:l.width;var n;e.u_ah=null==(n=Kc.screen)?void 0:n.availHeight;var p;e.u_aw=
null==(p=Kc.screen)?void 0:p.availWidth;var u;e.u_cd=null==(u=Kc.screen)?void 0:u.colorDepth}catch(ta){}h=b.h;try{var q=h.screenX;var x=h.screenY}catch(ta){}try{var y=h.outerWidth;var A=h.outerHeight}catch(ta){}try{var M=h.innerWidth;var N=h.innerHeight}catch(ta){}try{var P=h.screenLeft;var Jb=h.screenTop}catch(ta){}try{M=h.innerWidth,N=h.innerHeight}catch(ta){}try{var Vd=h.screen.availWidth;var Pj=h.screen.availTop}catch(ta){}q=[P,Jb,q,x,Vd,Pj,y,A,M,N];x=b.h.top;try{var ib=(x||window).document,ca=
"CSS1Compat"==ib.compatMode?ib.documentElement:ib.body;var ia=(new Lc(ca.clientWidth,ca.clientHeight)).round()}catch(ta){ia=new Lc(-12245933,-12245933)}ib=ia;ia={};ca=new Td;B.SVGElement&&B.document.createElementNS&&ca.set(0);x=Wc();x["allow-top-navigation-by-user-activation"]&&ca.set(1);x["allow-popups-to-escape-sandbox"]&&ca.set(2);B.crypto&&B.crypto.subtle&&ca.set(3);B.TextDecoder&&B.TextEncoder&&ca.set(4);ca=Ud(ca);ia.bc=ca;ia.bih=ib.height;ia.biw=ib.width;ia.brdim=q.join();b=b.i;b=(ia.vis={visible:1,
hidden:2,prerender:3,preview:4,unloaded:5}[b.visibilityState||b.webkitVisibilityState||b.mozVisibilityState||""]||0,ia.wgl=!!Kc.WebGLRenderingContext,ia);c=d.call(c,e,b);c.ca_type="image";a&&(c.bid=a);return c}
var Ag=new function(){var a=window.document;this.h=window;this.i=a};
E("yt.ads_.signals_.getAdSignalsString",function(a){return ig(zg(a))});Date.now();var Bg="XMLHttpRequest"in B?function(){return new XMLHttpRequest}:null;
function Cg(){if(!Bg)return null;var a=Bg();return"open"in a?a:null}
;var Dg={Authorization:"AUTHORIZATION","X-Goog-Visitor-Id":"SANDBOXED_VISITOR_ID","X-Youtube-Domain-Admin-State":"DOMAIN_ADMIN_STATE","X-Youtube-Chrome-Connected":"CHROME_CONNECTED_HEADER","X-YouTube-Client-Name":"INNERTUBE_CONTEXT_CLIENT_NAME","X-YouTube-Client-Version":"INNERTUBE_CONTEXT_CLIENT_VERSION","X-YouTube-Delegation-Context":"INNERTUBE_CONTEXT_SERIALIZED_DELEGATION_CONTEXT","X-YouTube-Device":"DEVICE","X-Youtube-Identity-Token":"ID_TOKEN","X-YouTube-Page-CL":"PAGE_CL","X-YouTube-Page-Label":"PAGE_BUILD_LABEL",
"X-YouTube-Variants-Checksum":"VARIANTS_CHECKSUM"},Eg="app debugcss debugjs expflag force_ad_params force_ad_encrypted force_viral_ad_response_params forced_experiments innertube_snapshots innertube_goldens internalcountrycode internalipoverride absolute_experiments conditional_experiments sbb sr_bns_address".split(" ").concat(ha("client_dev_mss_url client_dev_regex_map client_dev_root_url expflag jsfeat jsmode client_rollout_override".split(" "))),Fg=!1;
function Gg(a,b){b=void 0===b?{}:b;var c=lg(a),d=Q("web_ajax_ignore_global_headers_if_set"),e;for(e in Dg){var f=O(Dg[e]);!f||!c&&Mb(a)||d&&void 0!==b[e]||(b[e]=f)}if(c||!Mb(a))b["X-YouTube-Utc-Offset"]=String(-(new Date).getTimezoneOffset());if(c||!Mb(a)){try{var g=(new Intl.DateTimeFormat).resolvedOptions().timeZone}catch(h){}g&&(b["X-YouTube-Time-Zone"]=g)}if(c||!Mb(a))b["X-YouTube-Ad-Signals"]=ig(zg(void 0));return b}
function Hg(a){var b=window.location.search,c=Mb(a);Q("debug_handle_relative_url_for_query_forward_killswitch")||c||!lg(a)||(c=document.location.hostname);var d=Lb(a.match(Kb)[5]||null);d=(c=c&&(c.endsWith("youtube.com")||c.endsWith("youtube-nocookie.com")))&&d&&d.startsWith("/api/");if(!c||d)return a;var e=jg(b),f={};G(Eg,function(g){e[g]&&(f[g]=e[g])});
return kg(a,f||{},!1)}
function Ig(a,b){var c=b.format||"JSON";a=Jg(a,b);var d=Kg(a,b),e=!1,f=Lg(a,function(k){if(!e){e=!0;h&&window.clearTimeout(h);a:switch(k&&"status"in k?k.status:-1){case 200:case 201:case 202:case 203:case 204:case 205:case 206:case 304:var l=!0;break a;default:l=!1}var n=null,p=400<=k.status&&500>k.status,u=500<=k.status&&600>k.status;if(l||p||u)n=Mg(a,c,k,b.convertToSafeHtml);if(l)a:if(k&&204==k.status)l=!0;else{switch(c){case "XML":l=0==parseInt(n&&n.return_code,10);break a;case "RAW":l=!0;break a}l=
!!n}n=n||{};p=b.context||B;l?b.onSuccess&&b.onSuccess.call(p,k,n):b.onError&&b.onError.call(p,k,n);b.onFinish&&b.onFinish.call(p,k,n)}},b.method,d,b.headers,b.responseType,b.withCredentials);
if(b.onTimeout&&0<b.timeout){var g=b.onTimeout;var h=bg(function(){e||(e=!0,f.abort(),window.clearTimeout(h),g.call(b.context||B,f))},b.timeout)}}
function Jg(a,b){b.includeDomain&&(a=document.location.protocol+"//"+document.location.hostname+(document.location.port?":"+document.location.port:"")+a);var c=O("XSRF_FIELD_NAME",void 0);if(b=b.urlParams)b[c]&&delete b[c],a=kg(a,b||{},!0);return a}
function Kg(a,b){var c=O("XSRF_FIELD_NAME",void 0),d=O("XSRF_TOKEN",void 0),e=b.postBody||"",f=b.postParams,g=O("XSRF_FIELD_NAME",void 0),h;b.headers&&(h=b.headers["Content-Type"]);b.excludeXsrf||Mb(a)&&!b.withCredentials&&Mb(a)!=document.location.hostname||"POST"!=b.method||h&&"application/x-www-form-urlencoded"!=h||b.postParams&&b.postParams[g]||(f||(f={}),f[c]=d);f&&"string"===typeof e&&(e=jg(e),hb(e,f),e=b.postBodyFormat&&"JSON"==b.postBodyFormat?JSON.stringify(e):Pb(e));if(!(a=e)&&(a=f)){a:{for(var k in f){f=
!1;break a}f=!0}a=!f}!Fg&&a&&"POST"!=b.method&&(Fg=!0,Sf(Error("AJAX request with postData should use POST")));return e}
function Mg(a,b,c,d){var e=null;switch(b){case "JSON":try{var f=c.responseText}catch(g){throw d=Error("Error reading responseText"),d.params=a,Tf(d),g;}a=c.getResponseHeader("Content-Type")||"";f&&0<=a.indexOf("json")&&(")]}'\n"===f.substring(0,5)&&(f=f.substring(5)),e=JSON.parse(f));break;case "XML":if(a=(a=c.responseXML)?Ng(a):null)e={},G(a.getElementsByTagName("*"),function(g){e[g.tagName]=Og(g)})}d&&Pg(e);
return e}
function Pg(a){if(D(a))for(var b in a){var c;(c="html_content"==b)||(c=b.length-5,c=0<=c&&b.indexOf("_html",c)==c);if(c){c=b;mb("HTML that is escaped and sanitized server-side and passed through yt.net.ajax");var d=Ib(a[b],null);a[c]=d}else Pg(a[b])}}
function Ng(a){return a?(a=("responseXML"in a?a.responseXML:a).getElementsByTagName("root"))&&0<a.length?a[0]:null:null}
function Og(a){var b="";G(a.childNodes,function(c){b+=c.nodeValue});
return b}
function Lg(a,b,c,d,e,f,g){function h(){4==(k&&"readyState"in k?k.readyState:0)&&b&&Rf(b)(k)}
c=void 0===c?"GET":c;d=void 0===d?"":d;var k=Cg();if(!k)return null;"onloadend"in k?k.addEventListener("loadend",h,!1):k.onreadystatechange=h;Q("debug_forward_web_query_parameters")&&(a=Hg(a));k.open(c,a,!0);f&&(k.responseType=f);g&&(k.withCredentials=!0);c="POST"==c&&(void 0===window.FormData||!(d instanceof FormData));if(e=Gg(a,e))for(var l in e)k.setRequestHeader(l,e[l]),"content-type"==l.toLowerCase()&&(c=!1);c&&k.setRequestHeader("Content-Type","application/x-www-form-urlencoded");k.send(d);
return k}
;var Qg=ic||jc;function Rg(a){var b=Cb;return b?0<=b.toLowerCase().indexOf(a):!1}
;var Sg={},Tg=0;
function Ug(a,b,c,d,e){e=void 0===e?"":e;if(a)if(c&&!Rg("cobalt"))a&&(a instanceof wb||(a="object"==typeof a&&a.ha?a.ga():String(a),Ab.test(a)?a=new wb(a,xb):(a=String(a),a=a.replace(/(%0A|%0D)/g,""),a=(b=a.match(zb))&&yb.test(b[1])?new wb(a,xb):null)),a=a||Bb,a instanceof wb&&a.constructor===wb?a=a.h:(Ka(a),a="type_error:SafeUrl"),"about:invalid#zClosurez"===a||a.startsWith("data")?a="":(a instanceof Hb||(b="object"==typeof a,c=null,b&&a.Ra&&(c=a.Pa()),a=Ib(ob(b&&a.ha?a.ga():String(a)),c)),a instanceof
Hb&&a.constructor===Hb?a=a.h:(Ka(a),a="type_error:SafeHtml"),a=encodeURIComponent(String(Ce(a.toString())))),/^[\s\xa0]*$/.test(a)||(a=Oc("IFRAME",{src:'javascript:"<body><img src=\\""+'+a+'+"\\"></body>"',style:"display:none"}),(9==a.nodeType?a:a.ownerDocument||a.document).body.appendChild(a)));else if(e)Lg(a,b,"POST",e,d);else if(O("USE_NET_AJAX_FOR_PING_TRANSPORT",!1)||d)Lg(a,b,"GET","",d);else{b:{try{var f=new Ua({url:a});if(f.j&&f.i||f.l){var g=Lb(a.match(Kb)[5]||null);var h=!(!g||!g.endsWith("/aclk")||
"1"!==Rb(a,"ri"));break b}}catch(k){}h=!1}h?Vg(a)?(b&&b(),c=!0):c=!1:c=!1;c||Wg(a,b)}}
function Xg(){var a=void 0===a?"":a;Vg("/generate_204",a)||Ug("/generate_204",void 0,void 0,void 0,a)}
function Vg(a,b){try{if(window.navigator&&window.navigator.sendBeacon&&window.navigator.sendBeacon(a,void 0===b?"":b))return!0}catch(c){}return!1}
function Wg(a,b){var c=new Image,d=""+Tg++;Sg[d]=c;c.onload=c.onerror=function(){b&&Sg[d]&&b();delete Sg[d]};
c.src=a}
;var Yg=B.ytPubsubPubsubInstance||new L,Zg=B.ytPubsubPubsubSubscribedKeys||{},$g=B.ytPubsubPubsubTopicToKeys||{},ah=B.ytPubsubPubsubIsSynchronous||{};L.prototype.subscribe=L.prototype.subscribe;L.prototype.unsubscribeByKey=L.prototype.la;L.prototype.publish=L.prototype.ca;L.prototype.clear=L.prototype.clear;E("ytPubsubPubsubInstance",Yg);E("ytPubsubPubsubTopicToKeys",$g);E("ytPubsubPubsubIsSynchronous",ah);E("ytPubsubPubsubSubscribedKeys",Zg);var bh=window,R=bh.ytcsi&&bh.ytcsi.now?bh.ytcsi.now:bh.performance&&bh.performance.timing&&bh.performance.now&&bh.performance.timing.navigationStart?function(){return bh.performance.timing.navigationStart+bh.performance.now()}:function(){return(new Date).getTime()};var ch=ng("initial_gel_batch_timeout",2E3),dh=Math.pow(2,16)-1,eh=void 0;function fh(){this.j=this.h=this.i=0}
var gh=new fh,hh=new fh,ih=!0,jh=B.ytLoggingTransportGELQueue_||new Map;E("ytLoggingTransportGELQueue_",jh);var kh=B.ytLoggingTransportGELProtoQueue_||new Map;E("ytLoggingTransportGELProtoQueue_",kh);var lh=B.ytLoggingTransportTokensToCttTargetIds_||{};E("ytLoggingTransportTokensToCttTargetIds_",lh);var mh=B.ytLoggingTransportTokensToJspbCttTargetIds_||{};E("ytLoggingTransportTokensToJspbCttTargetIds_",mh);
function nh(a,b){if("log_event"===a.endpoint){var c=oh(a),d=jh.get(c)||[];jh.set(c,d);d.push(a.payload);var e=void 0===e?!1:e;b&&(eh=new b);a=ng("tvhtml5_logging_max_batch")||ng("web_logging_max_batch")||100;b=R();var f=e?hh.j:gh.j;d.length>=a?ph({writeThenSend:!0},Q("flush_only_full_queue")?c:void 0,e):10<=b-f&&(qh(e),e?hh.j=b:gh.j=b)}}
function rh(a,b){if("log_event"===a.endpoint){var c=oh(a),d=new Map;d.set(c,[a.payload]);b&&(eh=new b);return new Ee(function(e){eh&&eh.isReady()?sh(d,e,{bypassNetworkless:!0},!0):e()})}}
function oh(a){var b="";if(a.za)b="visitorOnlyApprovedKey";else if(a.da){b=a.da;var c={};b.videoId?c.videoId=b.videoId:b.playlistId&&(c.playlistId=b.playlistId);lh[a.da.token]=c;b=a.da.token}return b}
function ph(a,b,c){a=void 0===a?{}:a;c=void 0===c?!1:c;new Ee(function(d){c?(window.clearTimeout(hh.i),window.clearTimeout(hh.h),hh.h=0):(window.clearTimeout(gh.i),window.clearTimeout(gh.h),gh.h=0);if(eh&&eh.isReady())if(void 0!==b)if(c){var e=new Map,f=kh.get(b)||[];e.set(b,f);th(e,d,a);kh.delete(b)}else e=new Map,f=jh.get(b)||[],e.set(b,f),sh(e,d,a),jh.delete(b);else c?(th(kh,d,a),kh.clear()):(sh(jh,d,a),jh.clear());else qh(c),d()})}
function qh(a){a=void 0===a?!1:a;if(Q("web_gel_timeout_cap")&&(!a&&!gh.h||a&&!hh.h)){var b=bg(function(){ph({writeThenSend:!0},void 0,a)},6E4);
a?hh.h=b:gh.h=b}window.clearTimeout(a?hh.i:gh.i);b=O("LOGGING_BATCH_TIMEOUT",ng("web_gel_debounce_ms",1E4));Q("shorten_initial_gel_batch_timeout")&&ih&&(b=ch);b=bg(function(){ph({writeThenSend:!0},void 0,a)},b);
a?hh.i=b:gh.i=b}
function sh(a,b,c,d){var e=eh;c=void 0===c?{}:c;var f=Math.round(R()),g=a.size;a=t(a);for(var h=a.next();!h.done;h=a.next()){var k=t(h.value);h=k.next().value;var l=k=k.next().value;k=fb({context:uh(e.config_||vh())});k.events=l;(l=lh[h])&&wh(k,h,l);delete lh[h];h="visitorOnlyApprovedKey"===h;xh(k,f,h);yh(c);Q("send_beacon_before_gel")&&window.navigator&&window.navigator.sendBeacon&&!c.writeThenSend&&Xg();zh(e,"log_event",k,Ah(c,h,function(){g--;g||b()},function(){g--;
g||b()},d));
ih=!1}}
function th(a,b,c){var d=eh;c=void 0===c?{}:c;var e=Math.round(R()),f=a.size;a=t(a);for(var g=a.next();!g.done;g=a.next()){var h=t(g.value);g=h.next().value;var k=h=h.next().value;h=new Df;var l=Bh(d.config_||vh());Gc(h,1,l);for(l=0;l<k.length;l++)Hc(h,3,k[l],Af);(k=mh[g])&&Ch(h,g,k);delete mh[g];g="visitorOnlyApprovedKey"===g;Dh(h,e,g);yh(c);a:{sc=!0;try{var n=JSON.stringify(h.toJSON(),Ic);break a}finally{sc=!1}n=void 0}h=n;g=Ah(c,g,function(){f--;f||b()},function(){f--;
f||b()},void 0);
g.headers={"Content-Type":"application/json+protobuf"};g.postBodyFormat="JSPB";g.postBody=h;zh(d,"log_event","",g);ih=!1}}
function yh(a){Q("always_send_and_write")&&(a.writeThenSend=!1)}
function Ah(a,b,c,d,e){return{retry:!0,onSuccess:c,onError:d,Wa:a,za:b,Qb:!!e,headers:{},postBodyFormat:"",postBody:""}}
function xh(a,b,c){a.requestTimeMs=String(b);Q("unsplit_gel_payloads_in_logs")&&(a.unsplitGelPayloadsInLogs=!0);!c&&(b=O("EVENT_ID",void 0))&&(c=Eh(),a.serializedClientEventId={serializedEventId:b,clientCounter:String(c)})}
function Dh(a,b,c){J(a,2,b);if(!c&&(b=O("EVENT_ID",void 0))){c=Eh();var d=new Bf;J(d,1,b);J(d,2,c);Gc(a,5,d)}}
function Eh(){var a=O("BATCH_CLIENT_COUNTER",void 0)||0;a||(a=Math.floor(Math.random()*dh/2));a++;a>dh&&(a=1);Nf("BATCH_CLIENT_COUNTER",a);return a}
function wh(a,b,c){if(c.videoId)var d="VIDEO";else if(c.playlistId)d="PLAYLIST";else return;a.credentialTransferTokenTargetId=c;a.context=a.context||{};a.context.user=a.context.user||{};a.context.user.credentialTransferTokens=[{token:b,scope:d}]}
function Ch(a,b,c){if(Bc(c,1===Dc(c,Cf)?1:-1))var d=1;else if(c.getPlaylistId())d=2;else return;Gc(a,4,c);a=Ec(a,yf,1)||new yf;c=Ec(a,wf,3)||new wf;var e=new vf;e.setToken(b);J(e,1,d);Hc(c,12,e,vf);Gc(a,3,c)}
;var Fh=B.ytLoggingGelSequenceIdObj_||{};E("ytLoggingGelSequenceIdObj_",Fh);function Gh(){if(!B.matchMedia)return"WEB_DISPLAY_MODE_UNKNOWN";try{return B.matchMedia("(display-mode: standalone)").matches?"WEB_DISPLAY_MODE_STANDALONE":B.matchMedia("(display-mode: minimal-ui)").matches?"WEB_DISPLAY_MODE_MINIMAL_UI":B.matchMedia("(display-mode: fullscreen)").matches?"WEB_DISPLAY_MODE_FULLSCREEN":B.matchMedia("(display-mode: browser)").matches?"WEB_DISPLAY_MODE_BROWSER":"WEB_DISPLAY_MODE_UNKNOWN"}catch(a){return"WEB_DISPLAY_MODE_UNKNOWN"}}
function Hh(){var a=Gh();a=Object.keys(pg).indexOf(a);return-1===a?null:a}
;E("ytglobal.prefsUserPrefsPrefs_",C("ytglobal.prefsUserPrefsPrefs_")||{});var Ih={bluetooth:"CONN_DISCO",cellular:"CONN_CELLULAR_UNKNOWN",ethernet:"CONN_WIFI",none:"CONN_NONE",wifi:"CONN_WIFI",wimax:"CONN_CELLULAR_4G",other:"CONN_UNKNOWN",unknown:"CONN_UNKNOWN","slow-2g":"CONN_CELLULAR_2G","2g":"CONN_CELLULAR_2G","3g":"CONN_CELLULAR_3G","4g":"CONN_CELLULAR_4G"},Jh={CONN_DEFAULT:0,CONN_UNKNOWN:1,CONN_NONE:2,CONN_WIFI:3,CONN_CELLULAR_2G:4,CONN_CELLULAR_3G:5,CONN_CELLULAR_4G:6,CONN_CELLULAR_UNKNOWN:7,CONN_DISCO:8,CONN_CELLULAR_5G:9,CONN_WIFI_METERED:10,CONN_CELLULAR_5G_SA:11,
CONN_CELLULAR_5G_NSA:12,CONN_INVALID:31},Kh={EFFECTIVE_CONNECTION_TYPE_UNKNOWN:0,EFFECTIVE_CONNECTION_TYPE_OFFLINE:1,EFFECTIVE_CONNECTION_TYPE_SLOW_2G:2,EFFECTIVE_CONNECTION_TYPE_2G:3,EFFECTIVE_CONNECTION_TYPE_3G:4,EFFECTIVE_CONNECTION_TYPE_4G:5},Lh={"slow-2g":"EFFECTIVE_CONNECTION_TYPE_SLOW_2G","2g":"EFFECTIVE_CONNECTION_TYPE_2G","3g":"EFFECTIVE_CONNECTION_TYPE_3G","4g":"EFFECTIVE_CONNECTION_TYPE_4G"};function Mh(){var a=B.navigator;return a?a.connection:void 0}
;function Nh(){return"INNERTUBE_API_KEY"in Kf&&"INNERTUBE_API_VERSION"in Kf}
function vh(){return{innertubeApiKey:O("INNERTUBE_API_KEY",void 0),innertubeApiVersion:O("INNERTUBE_API_VERSION",void 0),Ba:O("INNERTUBE_CONTEXT_CLIENT_CONFIG_INFO"),Ca:O("INNERTUBE_CONTEXT_CLIENT_NAME","WEB"),ob:O("INNERTUBE_CONTEXT_CLIENT_NAME",1),innertubeContextClientVersion:O("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0),Ta:O("INNERTUBE_CONTEXT_HL",void 0),Sa:O("INNERTUBE_CONTEXT_GL",void 0),pb:O("INNERTUBE_HOST_OVERRIDE",void 0)||"",rb:!!O("INNERTUBE_USE_THIRD_PARTY_AUTH",!1),qb:!!O("INNERTUBE_OMIT_API_KEY_WHEN_AUTH_HEADER_IS_PRESENT",
!1),appInstallData:O("SERIALIZED_CLIENT_CONFIG_DATA",void 0)}}
function uh(a){var b={client:{hl:a.Ta,gl:a.Sa,clientName:a.Ca,clientVersion:a.innertubeContextClientVersion,configInfo:a.Ba}};navigator.userAgent&&(b.client.userAgent=String(navigator.userAgent));var c=B.devicePixelRatio;c&&1!=c&&(b.client.screenDensityFloat=String(c));c=O("EXPERIMENTS_TOKEN","");""!==c&&(b.client.experimentsToken=c);c=og();0<c.length&&(b.request={internalExperimentFlags:c});Oh(a,void 0,b);Ph(a,void 0,b);Qh(void 0,b);Rh(a,void 0,b);Sh(void 0,b);O("DELEGATED_SESSION_ID")&&!Q("pageid_as_header_web")&&
(b.user={onBehalfOfUser:O("DELEGATED_SESSION_ID")});a=Object;c=a.assign;for(var d=b.client,e={},f=t(Object.entries(jg(O("DEVICE","")))),g=f.next();!g.done;g=f.next()){var h=t(g.value);g=h.next().value;h=h.next().value;"cbrand"===g?e.deviceMake=h:"cmodel"===g?e.deviceModel=h:"cbr"===g?e.browserName=h:"cbrver"===g?e.browserVersion=h:"cos"===g?e.osName=h:"cosver"===g?e.osVersion=h:"cplatform"===g&&(e.platform=h)}b.client=c.call(a,d,e);return b}
function Bh(a){var b=new yf,c=new rf;J(c,1,a.Ta);J(c,2,a.Sa);J(c,16,a.ob);J(c,17,a.innertubeContextClientVersion);if(a.Ba){var d=a.Ba,e=new of;d.coldConfigData&&J(e,1,d.coldConfigData);d.appInstallData&&J(e,6,d.appInstallData);d.coldHashData&&J(e,3,d.coldHashData);d.hotHashData&&J(e,5,d.hotHashData);Gc(c,62,e)}(d=B.devicePixelRatio)&&1!=d&&J(c,65,d);d=O("EXPERIMENTS_TOKEN","");""!==d&&J(c,54,d);d=og();if(0<d.length){e=new tf;for(var f=0;f<d.length;f++){var g=new mf;J(g,1,d[f].key);g.setValue(d[f].value);
Hc(e,15,g,mf)}Gc(b,5,e)}Oh(a,c);Ph(a,c);Qh(c);Rh(a,c);Sh(c);O("DELEGATED_SESSION_ID")&&!Q("pageid_as_header_web")&&(a=new wf,J(a,3,O("DELEGATED_SESSION_ID")));a=t(Object.entries(jg(O("DEVICE",""))));for(d=a.next();!d.done;d=a.next())e=t(d.value),d=e.next().value,e=e.next().value,"cbrand"===d?J(c,12,e):"cmodel"===d?J(c,13,e):"cbr"===d?J(c,87,e):"cbrver"===d?J(c,88,e):"cos"===d?J(c,18,e):"cosver"===d?J(c,19,e):"cplatform"===d&&J(c,42,e);Gc(b,1,c);return b}
function Oh(a,b,c){a=a.Ca;if("WEB"===a||"MWEB"===a||1===a||2===a)if(b){c=Ec(b,pf,96)||new pf;var d=Hh();null!==d&&J(c,3,d);Gc(b,96,c)}else c&&(c.client.mainAppWebInfo=null!=(d=c.client.mainAppWebInfo)?d:{},c.client.mainAppWebInfo.webDisplayMode=Gh())}
function Ph(a,b,c){a=a.Ca;if(("WEB_REMIX"===a||76===a)&&!Q("music_web_display_mode_killswitch"))if(b){var d;c=null!=(d=Ec(b,qf,70))?d:new qf;d=Hh();null!==d&&J(c,10,d);Gc(b,70,c)}else if(c){var e;c.client.Va=null!=(e=c.client.Va)?e:{};c.client.Va.webDisplayMode=Gh()}}
function Qh(a,b){var c;if(Q("web_log_memory_total_kbytes")&&(null==(c=B.navigator)?0:c.deviceMemory)){var d;c=null==(d=B.navigator)?void 0:d.deviceMemory;a?J(a,95,1E6*c):b&&(b.client.memoryTotalKbytes=""+1E6*c)}}
function Rh(a,b,c){if(a.appInstallData)if(b){var d;c=null!=(d=Ec(b,of,62))?d:new of;J(c,6,a.appInstallData);Gc(b,62,c)}else c&&(c.client.configInfo=c.client.configInfo||{},c.client.configInfo.appInstallData=a.appInstallData)}
function Sh(a,b){a:{var c=Mh();if(c){var d=Ih[c.type||"unknown"]||"CONN_UNKNOWN";c=Ih[c.effectiveType||"unknown"]||"CONN_UNKNOWN";"CONN_CELLULAR_UNKNOWN"===d&&"CONN_UNKNOWN"!==c&&(d=c);if("CONN_UNKNOWN"!==d)break a;if("CONN_UNKNOWN"!==c){d=c;break a}}d=void 0}d&&(a?J(a,61,Jh[d]):b&&(b.client.connectionType=d));Q("web_log_effective_connection_type")&&(d=Mh(),d=null!==d&&void 0!==d&&d.effectiveType?Lh.hasOwnProperty(d.effectiveType)?Lh[d.effectiveType]:"EFFECTIVE_CONNECTION_TYPE_UNKNOWN":void 0,d&&
(a?J(a,94,Kh[d]):b&&(b.client.effectiveConnectionType=d)))}
function Th(a,b,c){c=void 0===c?{}:c;var d={"X-Goog-Visitor-Id":c.visitorData||O("VISITOR_DATA","")};if(b&&b.includes("www.youtube-nocookie.com"))return d;(b=c.Ob||O("AUTHORIZATION"))||(a?b="Bearer "+C("gapi.auth.getToken")().Nb:b=id([]));b&&(d.Authorization=b,d["X-Goog-AuthUser"]=O("SESSION_INDEX",0),Q("pageid_as_header_web")&&(d["X-Goog-PageId"]=O("DELEGATED_SESSION_ID")));return d}
;function Uh(a){a=Object.assign({},a);delete a.Authorization;var b=id();if(b){var c=new le;c.update(O("INNERTUBE_API_KEY",void 0));c.update(b);a.hash=nc(c.digest(),3)}return a}
;function Vh(a){var b=new ef;(b=b.isAvailable()?a?new lf(b,a):b:null)||(a=new ff(a||"UserDataSharedStore"),b=a.isAvailable()?a:null);this.h=(a=b)?new af(a):null;this.i=document.domain||window.location.hostname}
Vh.prototype.set=function(a,b,c,d){c=c||31104E3;this.remove(a);if(this.h)try{this.h.set(a,b,Date.now()+1E3*c);return}catch(f){}var e="";if(d)try{e=escape(Ce(b))}catch(f){return}else e=escape(b);b=this.i;fd.set(""+a,e,{Da:c,path:"/",domain:void 0===b?"youtube.com":b,secure:!1})};
Vh.prototype.get=function(a,b){var c=void 0,d=!this.h;if(!d)try{c=this.h.get(a)}catch(e){d=!0}if(d&&(c=fd.get(""+a,void 0))&&(c=unescape(c),b))try{c=JSON.parse(c)}catch(e){this.remove(a),c=void 0}return c};
Vh.prototype.remove=function(a){this.h&&this.h.remove(a);var b=this.i;fd.remove(""+a,"/",void 0===b?"youtube.com":b)};var Wh;function Xh(){Wh||(Wh=new Vh("yt.innertube"));return Wh}
function Yh(a,b,c,d){if(d)return null;d=Xh().get("nextId",!0)||1;var e=Xh().get("requests",!0)||{};e[d]={method:a,request:b,authState:Uh(c),requestTime:Math.round(R())};Xh().set("nextId",d+1,86400,!0);Xh().set("requests",e,86400,!0);return d}
function Zh(a){var b=Xh().get("requests",!0)||{};delete b[a];Xh().set("requests",b,86400,!0)}
function $h(a){var b=Xh().get("requests",!0);if(b){for(var c in b){var d=b[c];if(!(6E4>Math.round(R())-d.requestTime)){var e=d.authState,f=Uh(Th(!1));eb(e,f)&&(e=d.request,"requestTimeMs"in e&&(e.requestTimeMs=Math.round(R())),zh(a,d.method,e,{}));delete b[c]}}Xh().set("requests",b,86400,!0)}}
;var ai=function(){var a;return function(){a||(a=new Vh("ytidb"));return a}}();
function bi(){var a;return null===(a=ai())||void 0===a?void 0:a.get("LAST_RESULT_ENTRY_KEY",!0)}
;var ci=[],di=!1;function ei(a){di||(ci.push({type:"ERROR",payload:a}),10<ci.length&&ci.shift())}
function fi(a,b){di||(ci.push({type:"EVENT",eventType:a,payload:b}),10<ci.length&&ci.shift())}
;function gi(a){var b=Ea.apply(1,arguments);var c=Error.call(this,a);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.args=[].concat(ha(b))}
v(gi,Error);function hi(){try{return ii(),!0}catch(a){return!1}}
function ii(){if(void 0!==O("DATASYNC_ID",void 0))return O("DATASYNC_ID",void 0);throw new gi("Datasync ID not set","unknown");}
;function ji(a){if(0<=a.indexOf(":"))throw Error("Database name cannot contain ':'");}
function ki(a){return a.substr(0,a.indexOf(":"))||a}
;var S={},li=(S.AUTH_INVALID="No user identifier specified.",S.EXPLICIT_ABORT="Transaction was explicitly aborted.",S.IDB_NOT_SUPPORTED="IndexedDB is not supported.",S.MISSING_INDEX="Index not created.",S.MISSING_OBJECT_STORES="Object stores not created.",S.DB_DELETED_BY_MISSING_OBJECT_STORES="Database is deleted because expected object stores were not created.",S.UNKNOWN_ABORT="Transaction was aborted for unknown reasons.",S.QUOTA_EXCEEDED="The current transaction exceeded its quota limitations.",
S.QUOTA_MAYBE_EXCEEDED="The current transaction may have failed because of exceeding quota limitations.",S.EXECUTE_TRANSACTION_ON_CLOSED_DB="Can't start a transaction on a closed database",S.INCOMPATIBLE_DB_VERSION="The binary is incompatible with the database version",S),T={},mi=(T.AUTH_INVALID="ERROR",T.EXECUTE_TRANSACTION_ON_CLOSED_DB="WARNING",T.EXPLICIT_ABORT="IGNORED",T.IDB_NOT_SUPPORTED="ERROR",T.MISSING_INDEX="WARNING",T.MISSING_OBJECT_STORES="ERROR",T.DB_DELETED_BY_MISSING_OBJECT_STORES=
"WARNING",T.QUOTA_EXCEEDED="WARNING",T.QUOTA_MAYBE_EXCEEDED="WARNING",T.UNKNOWN_ABORT="WARNING",T.INCOMPATIBLE_DB_VERSION="WARNING",T),ni={},oi=(ni.AUTH_INVALID=!1,ni.EXECUTE_TRANSACTION_ON_CLOSED_DB=!1,ni.EXPLICIT_ABORT=!1,ni.IDB_NOT_SUPPORTED=!1,ni.MISSING_INDEX=!1,ni.MISSING_OBJECT_STORES=!1,ni.DB_DELETED_BY_MISSING_OBJECT_STORES=!1,ni.QUOTA_EXCEEDED=!1,ni.QUOTA_MAYBE_EXCEEDED=!0,ni.UNKNOWN_ABORT=!0,ni.INCOMPATIBLE_DB_VERSION=!1,ni);
function U(a,b,c,d,e){b=void 0===b?{}:b;c=void 0===c?li[a]:c;d=void 0===d?mi[a]:d;e=void 0===e?oi[a]:e;gi.call(this,c,Object.assign({name:"YtIdbKnownError",isSw:void 0===self.document,isIframe:self!==self.top,type:a},b));this.type=a;this.message=c;this.level=d;this.h=e;Object.setPrototypeOf(this,U.prototype)}
v(U,gi);function pi(a,b){U.call(this,"MISSING_OBJECT_STORES",{expectedObjectStores:b,foundObjectStores:a},li.MISSING_OBJECT_STORES);Object.setPrototypeOf(this,pi.prototype)}
v(pi,U);function qi(a,b){var c=Error.call(this);this.message=c.message;"stack"in c&&(this.stack=c.stack);this.index=a;this.objectStore=b;Object.setPrototypeOf(this,qi.prototype)}
v(qi,Error);var ri=["The database connection is closing","Can't start a transaction on a closed database","A mutation operation was attempted on a database that did not allow mutations"];
function si(a,b,c,d){b=ki(b);var e=a instanceof Error?a:Error("Unexpected error: "+a);if(e instanceof U)return e;a={objectStoreNames:c,dbName:b,dbVersion:d};if("QuotaExceededError"===e.name)return new U("QUOTA_EXCEEDED",a);if(kc&&"UnknownError"===e.name)return new U("QUOTA_MAYBE_EXCEEDED",a);if(e instanceof qi)return new U("MISSING_INDEX",Object.assign(Object.assign({},a),{objectStore:e.objectStore,index:e.index}));if("InvalidStateError"===e.name&&ri.some(function(f){return e.message.includes(f)}))return new U("EXECUTE_TRANSACTION_ON_CLOSED_DB",
a);
if("AbortError"===e.name)return new U("UNKNOWN_ABORT",a,e.message);e.args=[Object.assign(Object.assign({},a),{name:"IdbError",Vb:e.name})];e.level="WARNING";return e}
function ti(a,b,c){var d=bi();return new U("IDB_NOT_SUPPORTED",{context:{caller:a,publicName:b,version:c,hasSucceededOnce:null===d||void 0===d?void 0:d.hasSucceededOnce}})}
;function ui(a){if(!a)throw Error();throw a;}
function vi(a){return a}
function wi(a){this.h=a}
function V(a){function b(e){if("PENDING"===d.state.status){d.state={status:"REJECTED",reason:e};e=t(d.onRejected);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
function c(e){if("PENDING"===d.state.status){d.state={status:"FULFILLED",value:e};e=t(d.h);for(var f=e.next();!f.done;f=e.next())f=f.value,f()}}
var d=this;this.state={status:"PENDING"};this.h=[];this.onRejected=[];a=a.h;try{a(c,b)}catch(e){b(e)}}
V.all=function(a){return new V(new wi(function(b,c){var d=[],e=a.length;0===e&&b(d);for(var f={Z:0};f.Z<a.length;f={Z:f.Z},++f.Z)xi(V.resolve(a[f.Z]).then(function(g){return function(h){d[g.Z]=h;e--;0===e&&b(d)}}(f)),function(g){c(g)})}))};
V.resolve=function(a){return new V(new wi(function(b,c){a instanceof V?a.then(b,c):b(a)}))};
V.reject=function(a){return new V(new wi(function(b,c){c(a)}))};
V.prototype.then=function(a,b){var c=this,d=null!==a&&void 0!==a?a:vi,e=null!==b&&void 0!==b?b:ui;return new V(new wi(function(f,g){"PENDING"===c.state.status?(c.h.push(function(){yi(c,c,d,f,g)}),c.onRejected.push(function(){zi(c,c,e,f,g)})):"FULFILLED"===c.state.status?yi(c,c,d,f,g):"REJECTED"===c.state.status&&zi(c,c,e,f,g)}))};
function xi(a,b){a.then(void 0,b)}
function yi(a,b,c,d,e){try{if("FULFILLED"!==a.state.status)throw Error("calling handleResolve before the promise is fulfilled.");var f=c(a.state.value);f instanceof V?Ai(a,b,f,d,e):d(f)}catch(g){e(g)}}
function zi(a,b,c,d,e){try{if("REJECTED"!==a.state.status)throw Error("calling handleReject before the promise is rejected.");var f=c(a.state.reason);f instanceof V?Ai(a,b,f,d,e):d(f)}catch(g){e(g)}}
function Ai(a,b,c,d,e){b===c?e(new TypeError("Circular promise chain detected.")):c.then(function(f){f instanceof V?Ai(a,b,f,d,e):d(f)},function(f){e(f)})}
;function Bi(a,b,c){function d(){c(a.error);f()}
function e(){b(a.result);f()}
function f(){try{a.removeEventListener("success",e),a.removeEventListener("error",d)}catch(g){}}
a.addEventListener("success",e);a.addEventListener("error",d)}
function Ci(a){return new Promise(function(b,c){Bi(a,b,c)})}
function W(a){return new V(new wi(function(b,c){Bi(a,b,c)}))}
;function Di(a,b){return new V(new wi(function(c,d){function e(){var f=a?b(a):null;f?f.then(function(g){a=g;e()},d):c()}
e()}))}
;function Ei(a,b){this.h=a;this.options=b;this.transactionCount=0;this.j=Math.round(R());this.i=!1}
m=Ei.prototype;m.add=function(a,b,c){return X(this,[a],{mode:"readwrite",G:!0},function(d){return d.objectStore(a).add(b,c)})};
m.clear=function(a){return X(this,[a],{mode:"readwrite",G:!0},function(b){return b.objectStore(a).clear()})};
m.close=function(){var a;this.h.close();(null===(a=this.options)||void 0===a?0:a.closed)&&this.options.closed()};
m.count=function(a,b){return X(this,[a],{mode:"readonly",G:!0},function(c){return c.objectStore(a).count(b)})};
function Fi(a,b,c){a=a.h.createObjectStore(b,c);return new Gi(a)}
m.delete=function(a,b){return X(this,[a],{mode:"readwrite",G:!0},function(c){return c.objectStore(a).delete(b)})};
m.get=function(a,b){return X(this,[a],{mode:"readonly",G:!0},function(c){return c.objectStore(a).get(b)})};
function Hi(a,b){return X(a,["LogsRequestsStore"],{mode:"readwrite",G:!0},function(c){c=c.objectStore("LogsRequestsStore");return W(c.h.put(b,void 0))})}
m.objectStoreNames=function(){return Array.from(this.h.objectStoreNames)};
function X(a,b,c,d){var e,f,g,h,k,l,n,p,u,q,x,y;return z(function(A){switch(A.h){case 1:var M={mode:"readonly",G:!1,tag:"IDB_TRANSACTION_TAG_UNKNOWN"};"string"===typeof c?M.mode=c:Object.assign(M,c);e=M;a.transactionCount++;f=e.G?3:1;g=0;case 2:if(h){A.o(3);break}g++;k=Math.round(R());sa(A,4);l=a.h.transaction(b,e.mode);M=new Ii(l);M=Ji(M,d);return w(A,M,6);case 6:return n=A.i,p=Math.round(R()),Ki(a,k,p,g,void 0,b.join(),e),A.return(n);case 4:u=va(A);q=Math.round(R());x=si(u,a.h.name,b.join(),a.h.version);
if((y=x instanceof U&&!x.h)||g>=f)Ki(a,k,q,g,x,b.join(),e),h=x;A.o(2);break;case 3:return A.return(Promise.reject(h))}})}
function Ki(a,b,c,d,e,f,g){b=c-b;e?(e instanceof U&&("QUOTA_EXCEEDED"===e.type||"QUOTA_MAYBE_EXCEEDED"===e.type)&&fi("QUOTA_EXCEEDED",{dbName:ki(a.h.name),objectStoreNames:f,transactionCount:a.transactionCount,transactionMode:g.mode}),e instanceof U&&"UNKNOWN_ABORT"===e.type&&(c-=a.j,0>c&&c>=Math.pow(2,31)&&(c=0),fi("TRANSACTION_UNEXPECTEDLY_ABORTED",{objectStoreNames:f,transactionDuration:b,transactionCount:a.transactionCount,dbDuration:c}),a.i=!0),Li(a,!1,d,f,b,g.tag),ei(e)):Li(a,!0,d,f,b,g.tag)}
function Li(a,b,c,d,e,f){fi("TRANSACTION_ENDED",{objectStoreNames:d,connectionHasUnknownAbortedTransaction:a.i,duration:e,isSuccessful:b,tryCount:c,tag:void 0===f?"IDB_TRANSACTION_TAG_UNKNOWN":f})}
m.getName=function(){return this.h.name};
function Gi(a){this.h=a}
m=Gi.prototype;m.add=function(a,b){return W(this.h.add(a,b))};
m.autoIncrement=function(){return this.h.autoIncrement};
m.clear=function(){return W(this.h.clear()).then(function(){})};
m.count=function(a){return W(this.h.count(a))};
function Mi(a,b){return Ni(a,{query:b},function(c){return c.delete().then(function(){return c.continue()})}).then(function(){})}
m.delete=function(a){return a instanceof IDBKeyRange?Mi(this,a):W(this.h.delete(a))};
m.get=function(a){return W(this.h.get(a))};
m.index=function(a){try{return new Oi(this.h.index(a))}catch(b){if(b instanceof Error&&"NotFoundError"===b.name)throw new qi(a,this.h.name);throw b;}};
m.getName=function(){return this.h.name};
m.keyPath=function(){return this.h.keyPath};
function Ni(a,b,c){a=a.h.openCursor(b.query,b.direction);return Pi(a).then(function(d){return Di(d,c)})}
function Ii(a){var b=this;this.h=a;this.j=new Map;this.i=!1;this.done=new Promise(function(c,d){b.h.addEventListener("complete",function(){c()});
b.h.addEventListener("error",function(e){e.currentTarget===e.target&&d(b.h.error)});
b.h.addEventListener("abort",function(){var e=b.h.error;if(e)d(e);else if(!b.i){e=U;for(var f=b.h.objectStoreNames,g=[],h=0;h<f.length;h++){var k=f.item(h);if(null===k)throw Error("Invariant: item in DOMStringList is null");g.push(k)}e=new e("UNKNOWN_ABORT",{objectStoreNames:g.join(),dbName:b.h.db.name,mode:b.h.mode});d(e)}})})}
function Ji(a,b){var c=new Promise(function(d,e){try{xi(b(a).then(function(f){d(f)}),e)}catch(f){e(f),a.abort()}});
return Promise.all([c,a.done]).then(function(d){return t(d).next().value})}
Ii.prototype.abort=function(){this.h.abort();this.i=!0;throw new U("EXPLICIT_ABORT");};
Ii.prototype.objectStore=function(a){a=this.h.objectStore(a);var b=this.j.get(a);b||(b=new Gi(a),this.j.set(a,b));return b};
function Oi(a){this.h=a}
m=Oi.prototype;m.count=function(a){return W(this.h.count(a))};
m.delete=function(a){return Qi(this,{query:a},function(b){return b.delete().then(function(){return b.continue()})})};
m.get=function(a){return W(this.h.get(a))};
m.getKey=function(a){return W(this.h.getKey(a))};
m.keyPath=function(){return this.h.keyPath};
m.unique=function(){return this.h.unique};
function Qi(a,b,c){a=a.h.openCursor(void 0===b.query?null:b.query,void 0===b.direction?"next":b.direction);return Pi(a).then(function(d){return Di(d,c)})}
function Ri(a,b){this.request=a;this.cursor=b}
function Pi(a){return W(a).then(function(b){return b?new Ri(a,b):null})}
m=Ri.prototype;m.advance=function(a){this.cursor.advance(a);return Pi(this.request)};
m.continue=function(a){this.cursor.continue(a);return Pi(this.request)};
m.delete=function(){return W(this.cursor.delete()).then(function(){})};
m.getKey=function(){return this.cursor.key};
m.X=function(){return this.cursor.value};
m.update=function(a){return W(this.cursor.update(a))};function Si(a,b,c){return new Promise(function(d,e){function f(){u||(u=new Ei(g.result,{closed:p}));return u}
var g=void 0!==b?self.indexedDB.open(a,b):self.indexedDB.open(a);var h=c.blocked,k=c.blocking,l=c.vb,n=c.upgrade,p=c.closed,u;g.addEventListener("upgradeneeded",function(q){try{if(null===q.newVersion)throw Error("Invariant: newVersion on IDbVersionChangeEvent is null");if(null===g.transaction)throw Error("Invariant: transaction on IDbOpenDbRequest is null");q.dataLoss&&"none"!==q.dataLoss&&fi("IDB_DATA_CORRUPTED",{reason:q.dataLossMessage||"unknown reason",dbName:ki(a)});var x=f(),y=new Ii(g.transaction);
n&&n(x,function(A){return q.oldVersion<A&&q.newVersion>=A},y);
y.done.catch(function(A){e(A)})}catch(A){e(A)}});
g.addEventListener("success",function(){var q=g.result;k&&q.addEventListener("versionchange",function(){k(f())});
q.addEventListener("close",function(){fi("IDB_UNEXPECTEDLY_CLOSED",{dbName:ki(a),dbVersion:q.version});l&&l()});
d(f())});
g.addEventListener("error",function(){e(g.error)});
h&&g.addEventListener("blocked",function(){h()})})}
function Ti(a,b,c){c=void 0===c?{}:c;return Si(a,b,c)}
function Ui(a,b){b=void 0===b?{}:b;var c,d,e,f;return z(function(g){if(1==g.h)return sa(g,2),c=self.indexedDB.deleteDatabase(a),d=b,(e=d.blocked)&&c.addEventListener("blocked",function(){e()}),w(g,Ci(c),4);
if(2!=g.h)return ua(g,0);f=va(g);throw si(f,a,"",-1);})}
;function Vi(a){return new Promise(function(b){vg(function(){b()},a)})}
function Wi(a,b){this.name=a;this.options=b;this.l=!0;this.m=0;this.i=500}
Wi.prototype.j=function(a,b,c){c=void 0===c?{}:c;return Ti(a,b,c)};
Wi.prototype.delete=function(a){a=void 0===a?{}:a;return Ui(this.name,a)};
function Xi(a,b){return new U("INCOMPATIBLE_DB_VERSION",{dbName:a.name,oldVersion:a.options.version,newVersion:b})}
function Yi(a,b){if(!b)throw ti("openWithToken",ki(a.name));return a.open()}
Wi.prototype.open=function(){function a(){var f,g,h,k,l,n,p,u,q,x;return z(function(y){switch(y.h){case 1:return h=null!==(f=Error().stack)&&void 0!==f?f:"",sa(y,2),w(y,c.j(c.name,c.options.version,e),4);case 4:k=y.i;for(var A=c.options,M=[],N=t(Object.keys(A.ia)),P=N.next();!P.done;P=N.next()){P=P.value;var Jb=A.ia[P],Vd=void 0===Jb.ub?Number.MAX_VALUE:Jb.ub;!(k.h.version>=Jb.ya)||k.h.version>=Vd||k.h.objectStoreNames.contains(P)||M.push(P)}l=M;if(0===l.length){y.o(5);break}n=Object.keys(c.options.ia);
p=k.objectStoreNames();if(!(c.m<ng("ytidb_remake_db_retries",1))){y.o(6);break}c.m++;if(!Q("ytidb_remake_db_enable_backoff_delay")){y.o(7);break}return w(y,Vi(c.i),8);case 8:c.i*=2;case 7:return w(y,c.delete(),9);case 9:return ei(new U("DB_DELETED_BY_MISSING_OBJECT_STORES",{dbName:c.name,expectedObjectStores:n,foundObjectStores:p})),y.return(a());case 6:throw new pi(p,n);case 5:return y.return(k);case 2:u=va(y);if(u instanceof DOMException?"VersionError"!==u.name:"DOMError"in self&&u instanceof DOMError?
"VersionError"!==u.name:!(u instanceof Object&&"message"in u)||"An attempt was made to open a database using a lower version than the existing version."!==u.message){y.o(10);break}return w(y,c.j(c.name,void 0,Object.assign(Object.assign({},e),{upgrade:void 0})),11);case 11:q=y.i;x=q.h.version;if(void 0!==c.options.version&&x>c.options.version+1)throw q.close(),c.l=!1,Xi(c,x);return y.return(q);case 10:throw b(),u instanceof Error&&!Q("ytidb_async_stack_killswitch")&&(u.stack=u.stack+"\n"+h.substring(h.indexOf("\n")+
1)),si(u,c.name,"",null!==(g=c.options.version)&&void 0!==g?g:-1);}})}
function b(){c.h===d&&(c.h=void 0)}
var c=this;if(!this.l)throw Xi(this);if(this.h)return this.h;var d,e={blocking:function(f){f.close()},
closed:b,vb:b,upgrade:this.options.upgrade};return this.h=d=a()};var Zi=new Wi("YtIdbMeta",{ia:{databases:{ya:1}},upgrade:function(a,b){b(1)&&Fi(a,"databases",{keyPath:"actualName"})}});
function $i(a,b){var c;return z(function(d){if(1==d.h)return w(d,Yi(Zi,b),2);c=d.i;return d.return(X(c,["databases"],{G:!0,mode:"readwrite"},function(e){var f=e.objectStore("databases");return f.get(a.actualName).then(function(g){if(g?a.actualName!==g.actualName||a.publicName!==g.publicName||a.userIdentifier!==g.userIdentifier:1)return W(f.h.put(a,void 0)).then(function(){})})}))})}
function aj(a,b){var c;return z(function(d){if(1==d.h)return a?w(d,Yi(Zi,b),2):d.return();c=d.i;return d.return(c.delete("databases",a))})}
function bj(a,b){var c,d;return z(function(e){return 1==e.h?(c=[],w(e,Yi(Zi,b),2)):3!=e.h?(d=e.i,w(e,X(d,["databases"],{G:!0,mode:"readonly"},function(f){c.length=0;return Ni(f.objectStore("databases"),{},function(g){a(g.X())&&c.push(g.X());return g.continue()})}),3)):e.return(c)})}
function cj(a){return bj(function(b){return"LogsDatabaseV2"===b.publicName&&void 0!==b.userIdentifier},a)}
;var dj,ej=new function(){}(new function(){});
function fj(){var a,b,c;return z(function(d){switch(d.h){case 1:a=bi();if(null===a||void 0===a?0:a.hasSucceededOnce)return d.return(!0);var e;if(e=Qg)e=/WebKit\/([0-9]+)/.exec(Cb),e=!!(e&&600<=parseInt(e[1],10));e&&(e=/WebKit\/([0-9]+)/.exec(Cb),e=!(e&&602<=parseInt(e[1],10)));if(e||Xb)return d.return(!1);try{if(b=self,!(b.indexedDB&&b.IDBIndex&&b.IDBKeyRange&&b.IDBObjectStore))return d.return(!1)}catch(f){return d.return(!1)}if(!("IDBTransaction"in self&&"objectStoreNames"in IDBTransaction.prototype))return d.return(!1);
sa(d,2);c={actualName:"yt-idb-test-do-not-use",publicName:"yt-idb-test-do-not-use",userIdentifier:void 0};return w(d,$i(c,ej),4);case 4:return w(d,aj("yt-idb-test-do-not-use",ej),5);case 5:return d.return(!0);case 2:return va(d),d.return(!1)}})}
function gj(){if(void 0!==dj)return dj;di=!0;return dj=fj().then(function(a){di=!1;var b,c;null!==(b=ai())&&void 0!==b&&b.h&&(b=bi(),b={hasSucceededOnce:(null===b||void 0===b?void 0:b.hasSucceededOnce)||a},null===(c=ai())||void 0===c?void 0:c.set("LAST_RESULT_ENTRY_KEY",b,2592E3,!0));return a})}
function hj(){return C("ytglobal.idbToken_")||void 0}
function ij(){var a=hj();return a?Promise.resolve(a):gj().then(function(b){(b=b?ej:void 0)&&E("ytglobal.idbToken_",b);return b})}
;new De;function jj(a){if(!hi())throw a=new U("AUTH_INVALID",{dbName:a}),ei(a),a;var b=ii();return{actualName:a+":"+b,publicName:a,userIdentifier:b}}
function kj(a,b,c,d){var e,f,g,h,k,l;return z(function(n){switch(n.h){case 1:return f=null!==(e=Error().stack)&&void 0!==e?e:"",w(n,ij(),2);case 2:g=n.i;if(!g)throw h=ti("openDbImpl",a,b),Q("ytidb_async_stack_killswitch")||(h.stack=h.stack+"\n"+f.substring(f.indexOf("\n")+1)),ei(h),h;ji(a);k=c?{actualName:a,publicName:a,userIdentifier:void 0}:jj(a);sa(n,3);return w(n,$i(k,g),5);case 5:return w(n,Ti(k.actualName,b,d),6);case 6:return n.return(n.i);case 3:return l=va(n),sa(n,7),w(n,aj(k.actualName,
g),9);case 9:ua(n,8);break;case 7:va(n);case 8:throw l;}})}
function lj(a,b,c){c=void 0===c?{}:c;return kj(a,b,!1,c)}
function mj(a,b,c){c=void 0===c?{}:c;return kj(a,b,!0,c)}
function nj(a,b){b=void 0===b?{}:b;var c,d;return z(function(e){if(1==e.h)return w(e,ij(),2);if(3!=e.h){c=e.i;if(!c)return e.return();ji(a);d=jj(a);return w(e,Ui(d.actualName,b),3)}return w(e,aj(d.actualName,c),0)})}
function oj(a,b,c){a=a.map(function(d){return z(function(e){return 1==e.h?w(e,Ui(d.actualName,b),2):w(e,aj(d.actualName,c),0)})});
return Promise.all(a).then(function(){})}
function pj(){var a=void 0===a?{}:a;var b,c;return z(function(d){if(1==d.h)return w(d,ij(),2);if(3!=d.h){b=d.i;if(!b)return d.return();ji("LogsDatabaseV2");return w(d,cj(b),3)}c=d.i;return w(d,oj(c,a,b),0)})}
function qj(a,b){b=void 0===b?{}:b;var c;return z(function(d){if(1==d.h)return w(d,ij(),2);if(3!=d.h){c=d.i;if(!c)return d.return();ji(a);return w(d,Ui(a,b),3)}return w(d,aj(a,c),0)})}
;function rj(a){var b,c,d,e,f,g,h,k;this.h=!1;this.potentialEsfErrorCounter=this.i=0;this.handleError=function(){};
this.ba=function(){};
this.now=Date.now;this.ea=!1;this.eb=null!==(b=a.eb)&&void 0!==b?b:100;this.bb=null!==(c=a.bb)&&void 0!==c?c:1;this.Za=null!==(d=a.Za)&&void 0!==d?d:2592E6;this.Ya=null!==(e=a.Ya)&&void 0!==e?e:12E4;this.ab=null!==(f=a.ab)&&void 0!==f?f:5E3;this.s=null!==(g=a.s)&&void 0!==g?g:void 0;this.qa=!!a.qa;this.pa=null!==(h=a.pa)&&void 0!==h?h:.1;this.va=null!==(k=a.va)&&void 0!==k?k:10;a.handleError&&(this.handleError=a.handleError);a.ba&&(this.ba=a.ba);a.ea&&(this.ea=a.ea);this.B=a.B;this.K=a.K;this.C=a.C;
this.F=a.F;this.R=a.R;this.Ga=a.Ga;this.Fa=a.Fa;this.s&&(!this.B||this.B("networkless_logging"))&&sj(this)}
function sj(a){return z(function(b){if(1==b.h)return!a.s||a.ea?b.return():a.qa&&Math.random()<=a.pa?w(b,a.C.lb(a.s),2):b.o(2);tj(a);a.F.D()&&a.ka();a.F.Y(a.Ga,a.ka.bind(a));a.F.Y(a.Fa,a.Ka.bind(a));a.h=!0;b.h=0})}
m=rj.prototype;m.writeThenSend=function(a,b){var c=this;b=void 0===b?{}:b;if(this.s&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.C.set(d,this.s).then(function(e){d.id=e;c.F.D()&&uj(c,d)}).catch(function(e){uj(c,d);
vj(c,e)})}else this.R(a,b)};
m.sendThenWrite=function(a,b,c){var d=this;b=void 0===b?{}:b;if(this.s&&this.h){var e={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0};this.B&&this.B("nwl_skip_retry")&&(e.skipRetry=c);if(this.F.D()||this.B&&this.B("nwl_aggressive_send_then_write")&&!e.skipRetry){if(!e.skipRetry){var f=b.onError?b.onError:function(){};
b.onError=function(g,h){return z(function(k){if(1==k.h)return w(k,d.C.set(e,d.s).catch(function(l){vj(d,l)}),2);
f(g,h);k.h=0})}}this.R(a,b,e.skipRetry)}else this.C.set(e,this.s).catch(function(g){d.R(a,b,e.skipRetry);
vj(d,g)})}else this.R(a,b,this.B&&this.B("nwl_skip_retry")&&c)};
m.sendAndWrite=function(a,b){var c=this;b=void 0===b?{}:b;if(this.s&&this.h){var d={url:a,options:b,timestamp:this.now(),status:"NEW",sendCount:0},e=!1,f=b.onSuccess?b.onSuccess:function(){};
d.options.onSuccess=function(g,h){void 0!==d.id?c.C.aa(d.id,c.s):e=!0;c.F.V&&c.B&&c.B("vss_network_hint")&&c.F.V(!0);f(g,h)};
this.R(d.url,d.options);this.C.set(d,this.s).then(function(g){d.id=g;e&&c.C.aa(d.id,c.s)}).catch(function(g){vj(c,g)})}else this.R(a,b)};
m.ka=function(){var a=this;if(!this.s)throw ti("throttleSend");this.i||(this.i=this.K.L(function(){var b;return z(function(c){if(1==c.h)return w(c,a.C.Qa("NEW",a.s),2);if(3!=c.h)return b=c.i,b?w(c,uj(a,b),3):(a.Ka(),c.return());a.i&&(a.i=0,a.ka());c.h=0})},this.eb))};
m.Ka=function(){this.K.W(this.i);this.i=0};
function uj(a,b){var c,d;return z(function(e){switch(e.h){case 1:if(!a.s)throw c=ti("immediateSend"),c;if(void 0===b.id){e.o(2);break}return w(e,a.C.sb(b.id,a.s),3);case 3:(d=e.i)?b=d:a.ba(Error("The request cannot be found in the database."));case 2:if(wj(a,b,a.Za)){e.o(4);break}a.ba(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===b.id){e.o(5);break}return w(e,a.C.aa(b.id,a.s),5);case 5:return e.return();case 4:b.skipRetry||(b=xj(a,b));if(!b){e.o(0);break}if(!b.skipRetry||
void 0===b.id){e.o(8);break}return w(e,a.C.aa(b.id,a.s),8);case 8:a.R(b.url,b.options,!!b.skipRetry),e.h=0}})}
function xj(a,b){if(!a.s)throw ti("updateRequestHandlers");var c=b.options.onError?b.options.onError:function(){};
b.options.onError=function(e,f){var g;return z(function(h){switch(h.h){case 1:g=yj(f);if(!(a.B&&a.B("nwl_consider_error_code")&&g||a.B&&!a.B("nwl_consider_error_code")&&a.potentialEsfErrorCounter<=a.va)){h.o(2);break}if(!a.F.S){h.o(3);break}return w(h,a.F.S(),3);case 3:if(a.F.D()){h.o(2);break}c(e,f);if(!a.B||!a.B("nwl_consider_error_code")||void 0===(null===b||void 0===b?void 0:b.id)){h.o(6);break}return w(h,a.C.Ha(b.id,a.s,!1),6);case 6:return h.return();case 2:if(a.B&&a.B("nwl_consider_error_code")&&
!g&&a.potentialEsfErrorCounter>a.va)return h.return();a.potentialEsfErrorCounter++;if(void 0===(null===b||void 0===b?void 0:b.id)){h.o(8);break}return b.sendCount<a.bb?w(h,a.C.Ha(b.id,a.s),12):w(h,a.C.aa(b.id,a.s),8);case 12:a.K.L(function(){a.F.D()&&a.ka()},a.ab);
case 8:c(e,f),h.h=0}})};
var d=b.options.onSuccess?b.options.onSuccess:function(){};
b.options.onSuccess=function(e,f){return z(function(g){if(1==g.h)return void 0===(null===b||void 0===b?void 0:b.id)?g.o(2):w(g,a.C.aa(b.id,a.s),2);a.F.V&&a.B&&a.B("vss_network_hint")&&a.F.V(!0);d(e,f);g.h=0})};
return b}
function wj(a,b,c){b=b.timestamp;return a.now()-b>=c?!1:!0}
function tj(a){if(!a.s)throw ti("retryQueuedRequests");a.C.Qa("QUEUED",a.s).then(function(b){b&&!wj(a,b,a.Ya)?a.K.L(function(){return z(function(c){if(1==c.h)return void 0===b.id?c.o(2):w(c,a.C.Ha(b.id,a.s),2);tj(a);c.h=0})}):a.F.D()&&a.ka()})}
function vj(a,b){a.fb&&!a.F.D()?a.fb(b):a.handleError(b)}
function yj(a){var b;return(a=null===(b=null===a||void 0===a?void 0:a.error)||void 0===b?void 0:b.code)&&400<=a&&599>=a?!1:!0}
;var zj=C("ytPubsub2Pubsub2Instance")||new L;L.prototype.subscribe=L.prototype.subscribe;L.prototype.unsubscribeByKey=L.prototype.la;L.prototype.publish=L.prototype.ca;L.prototype.clear=L.prototype.clear;E("ytPubsub2Pubsub2Instance",zj);E("ytPubsub2Pubsub2SubscribedKeys",C("ytPubsub2Pubsub2SubscribedKeys")||{});E("ytPubsub2Pubsub2TopicToKeys",C("ytPubsub2Pubsub2TopicToKeys")||{});E("ytPubsub2Pubsub2IsAsync",C("ytPubsub2Pubsub2IsAsync")||{});E("ytPubsub2Pubsub2SkipSubKey",null);function Aj(a,b){Wi.call(this,a,b);this.options=b;ji(a)}
v(Aj,Wi);function Bj(a,b){var c;return function(){c||(c=new Aj(a,b));return c}}
Aj.prototype.j=function(a,b,c){c=void 0===c?{}:c;return(this.options.Ia?mj:lj)(a,b,Object.assign({},c))};
Aj.prototype.delete=function(a){a=void 0===a?{}:a;return(this.options.Ia?qj:nj)(this.name,a)};
function Cj(a,b){return Bj(a,b)}
;var Dj;
function Ej(){if(Dj)return Dj();var a={};Dj=Cj("LogsDatabaseV2",{ia:(a.LogsRequestsStore={ya:2},a),Ia:!1,upgrade:function(b,c,d){c(2)&&Fi(b,"LogsRequestsStore",{keyPath:"id",autoIncrement:!0});c(3);c(5)&&(d=d.objectStore("LogsRequestsStore"),d.h.indexNames.contains("newRequest")&&d.h.deleteIndex("newRequest"),d.h.createIndex("newRequestV2",["status","interface","timestamp"],{unique:!1}));c(7)&&b.h.objectStoreNames.contains("sapisid")&&b.h.deleteObjectStore("sapisid");c(9)&&b.h.objectStoreNames.contains("SWHealthLog")&&b.h.deleteObjectStore("SWHealthLog")},
version:9});return Dj()}
;function Fj(a){return Yi(Ej(),a)}
function Gj(a,b){var c,d,e,f;return z(function(g){if(1==g.h)return c={startTime:R(),transactionType:"YT_IDB_TRANSACTION_TYPE_WRITE"},w(g,Fj(b),2);if(3!=g.h)return d=g.i,e=Object.assign(Object.assign({},a),{options:JSON.parse(JSON.stringify(a.options)),interface:O("INNERTUBE_CONTEXT_CLIENT_NAME",0)}),w(g,Hi(d,e),3);f=g.i;c.wb=R();Hj(c);return g.return(f)})}
function Ij(a,b){var c,d,e,f,g,h,k;return z(function(l){if(1==l.h)return c={startTime:R(),transactionType:"YT_IDB_TRANSACTION_TYPE_READ"},w(l,Fj(b),2);if(3!=l.h)return d=l.i,e=O("INNERTUBE_CONTEXT_CLIENT_NAME",0),f=[a,e,0],g=[a,e,R()],h=IDBKeyRange.bound(f,g),k=void 0,w(l,X(d,["LogsRequestsStore"],{mode:"readwrite",G:!0},function(n){return Qi(n.objectStore("LogsRequestsStore").index("newRequestV2"),{query:h,direction:"prev"},function(p){p.X()&&(k=p.X(),"NEW"===a&&(k.status="QUEUED",p.update(k)))})}),
3);
c.wb=R();Hj(c);return l.return(k)})}
function Jj(a,b){var c;return z(function(d){if(1==d.h)return w(d,Fj(b),2);c=d.i;return d.return(X(c,["LogsRequestsStore"],{mode:"readwrite",G:!0},function(e){var f=e.objectStore("LogsRequestsStore");return f.get(a).then(function(g){if(g)return g.status="QUEUED",W(f.h.put(g,void 0)).then(function(){return g})})}))})}
function Kj(a,b,c){c=void 0===c?!0:c;var d;return z(function(e){if(1==e.h)return w(e,Fj(b),2);d=e.i;return e.return(X(d,["LogsRequestsStore"],{mode:"readwrite",G:!0},function(f){var g=f.objectStore("LogsRequestsStore");return g.get(a).then(function(h){return h?(h.status="NEW",c&&(h.sendCount+=1),W(g.h.put(h,void 0)).then(function(){return h})):V.resolve(void 0)})}))})}
function Lj(a,b){var c;return z(function(d){if(1==d.h)return w(d,Fj(b),2);c=d.i;return d.return(c.delete("LogsRequestsStore",a))})}
function Mj(a){var b,c;return z(function(d){if(1==d.h)return w(d,Fj(a),2);b=d.i;c=R()-2592E6;return w(d,X(b,["LogsRequestsStore"],{mode:"readwrite",G:!0},function(e){return Ni(e.objectStore("LogsRequestsStore"),{},function(f){if(f.X().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function Nj(){z(function(a){return w(a,pj(),0)})}
function Hj(a){if(!Q("nwl_csi_killswitch")&&.01>=Math.random()){var b=C("ytPubsub2Pubsub2Instance");b&&b.publish.call(b,"nwl_transaction_latency_payload".toString(),"nwl_transaction_latency_payload",a)}}
;var Oj={},Qj=Cj("ServiceWorkerLogsDatabase",{ia:(Oj.SWHealthLog={ya:1},Oj),Ia:!0,upgrade:function(a,b){b(1)&&Fi(a,"SWHealthLog",{keyPath:"id",autoIncrement:!0}).h.createIndex("swHealthNewRequest",["interface","timestamp"],{unique:!1})},
version:1});function Rj(a){return Yi(Qj(),a)}
function Sj(a){var b,c;z(function(d){if(1==d.h)return w(d,Rj(a),2);b=d.i;c=R()-2592E6;return w(d,X(b,["SWHealthLog"],{mode:"readwrite",G:!0},function(e){return Ni(e.objectStore("SWHealthLog"),{},function(f){if(f.X().timestamp<=c)return f.delete().then(function(){return f.continue()})})}),0)})}
function Tj(a){var b;return z(function(c){if(1==c.h)return w(c,Rj(a),2);b=c.i;return w(c,b.clear("SWHealthLog"),0)})}
;var Uj;function Vj(){Uj||(Uj=new Vh("yt.offline"));return Uj}
function Wj(a){if(Q("offline_error_handling")){var b=Vj().get("errors",!0)||{};b[a.message]={name:a.name,stack:a.stack};a.level&&(b[a.message].level=a.level);Vj().set("errors",b,2592E3,!0)}}
function Xj(){if(Q("offline_error_handling")){var a=Vj().get("errors",!0);if(a){for(var b in a)if(a[b]){var c=new gi(b,"sent via offline_errors");c.name=a[b].name;c.stack=a[b].stack;c.level=a[b].level;Sf(c)}Vj().set("errors",{},2592E3,!0)}}}
;var Yj=ng("network_polling_interval",3E4);function Y(){K.call(this);this.O=0;this.ma=this.m=!1;this.j=this.Aa();Q("use_shared_nsm")?(Qd.h||(Qd.h=new Qd(yg)),this.i=Qd.h):(Zj(this),ak(this))}
v(Y,K);function bk(){if(!Y.h){var a=C("yt.networkStatusManager.instance")||new Y;E("yt.networkStatusManager.instance",a);Y.h=a}return Y.h}
m=Y.prototype;m.D=function(){var a;return Q("use_shared_nsm")&&this.i?null===(a=this.i)||void 0===a?void 0:a.D():this.j};
m.V=function(a){var b;Q("use_shared_nsm")&&this.i?null===(b=this.i)||void 0===b?void 0:b.i=a:a!==this.j&&(this.j=a)};
m.tb=function(a){!Q("use_shared_nsm")&&(this.m=!0,void 0===a?0:a)&&(this.O||ck(this))};
m.Aa=function(){var a=window.navigator.onLine;return void 0===a?!0:a};
m.nb=function(){this.ma=!0};
m.Y=function(a,b){return Q("use_shared_nsm")&&this.i?this.i.Y(a,b):K.prototype.Y.call(this,a,b)};
function ak(a){window.addEventListener("online",function(){return z(function(b){if(1==b.h)return w(b,a.S(),2);a.ma&&Xj();b.h=0})})}
function Zj(a){window.addEventListener("offline",function(){return z(function(b){return w(b,a.S(),0)})})}
function ck(a){a.O=tg(function(){return z(function(b){if(1==b.h)return a.j?a.Aa()||!a.m?b.o(3):w(b,a.S(),3):w(b,a.S(),3);ck(a);b.h=0})},Yj)}
m.S=function(a){var b=this;return Q("use_shared_nsm")&&this.i?Rd(this.i,a):this.u?this.u:this.u=new Promise(function(c){var d,e,f;return z(function(g){switch(g.h){case 1:return d=window.AbortController?new window.AbortController:void 0,e=null===d||void 0===d?void 0:d.signal,f=!1,sa(g,2,3),d&&(b.A=yg.L(function(){d.abort()},a||2E4)),w(g,fetch("/generate_204",{method:"HEAD",
signal:e}),5);case 5:f=!0;case 3:wa(g);b.u=void 0;b.A&&yg.W(b.A);f!==b.j&&(b.j=f,b.j&&b.m?Od(b,"ytnetworkstatus-online"):b.m&&Od(b,"ytnetworkstatus-offline"));c(f);xa(g);break;case 2:va(g),f=!1,g.o(3)}})})};
Y.prototype.sendNetworkCheckRequest=Y.prototype.S;Y.prototype.listen=Y.prototype.Y;Y.prototype.enableErrorFlushing=Y.prototype.nb;Y.prototype.getWindowStatus=Y.prototype.Aa;Y.prototype.monitorNetworkStatusChange=Y.prototype.tb;Y.prototype.networkStatusHint=Y.prototype.V;Y.prototype.isNetworkAvailable=Y.prototype.D;Y.getInstance=bk;function dk(a){a=void 0===a?{}:a;K.call(this);var b=this;this.j=this.O=0;this.m="ytnetworkstatus-offline";this.u="ytnetworkstatus-online";Q("use_shared_nsm")&&(this.m="networkstatus-offline",this.u="networkstatus-online");this.i=bk();var c=C("yt.networkStatusManager.instance.monitorNetworkStatusChange").bind(this.i);c&&c(a.Na);a.sa&&!Q("use_shared_nsm")&&(c=C("yt.networkStatusManager.instance.enableErrorFlushing").bind(this.i))&&c();if(c=C("yt.networkStatusManager.instance.listen").bind(this.i))a.wa?
(this.wa=a.wa,c(this.u,function(){ek(b,"publicytnetworkstatus-online");Q("use_shared_nsm")&&a.sa&&Xj()}),c(this.m,function(){ek(b,"publicytnetworkstatus-offline")})):(c(this.u,function(){Od(b,"publicytnetworkstatus-online");
Q("use_shared_nsm")&&a.sa&&Xj()}),c(this.m,function(){Od(b,"publicytnetworkstatus-offline")}))}
v(dk,K);dk.prototype.D=function(){var a=C("yt.networkStatusManager.instance.isNetworkAvailable").bind(this.i);return a?a():!0};
dk.prototype.V=function(a){var b=C("yt.networkStatusManager.instance.networkStatusHint").bind(this.i);b&&b(a)};
dk.prototype.S=function(a){var b=this,c;return z(function(d){return(c=C("yt.networkStatusManager.instance.sendNetworkCheckRequest").bind(b.i))?d.return(c(a)):d.return(!0)})};
function ek(a,b){a.wa?a.j?(yg.W(a.O),a.O=yg.L(function(){a.A!==b&&(Od(a,b),a.A=b,a.j=R())},a.wa-(R()-a.j))):(Od(a,b),a.A=b,a.j=R()):Od(a,b)}
;var fk;function gk(){rj.call(this,{C:{lb:Mj,aa:Lj,Qa:Ij,sb:Jj,Ha:Kj,set:Gj},F:hk(),handleError:Sf,ba:Tf,R:ik,now:R,fb:Wj,K:xg(),Ga:"publicytnetworkstatus-online",Fa:"publicytnetworkstatus-offline",qa:!0,pa:.1,va:ng("potential_esf_error_limit",10),B:Q,ea:!hi()});this.j=new De;this.qa&&Math.random()<=this.pa&&this.s&&Sj(this.s);Q("networkless_immediately_drop_sw_health_store")&&jk(this);Q("networkless_immediately_drop_all_requests")&&Nj();qj("LogsDatabaseV2")}
v(gk,rj);function kk(){var a=C("yt.networklessRequestController.instance");a||(a=new gk,E("yt.networklessRequestController.instance",a),Q("networkless_logging")&&ij().then(function(b){return z(function(c){if(1==c.h)return a.s=b,w(c,sj(a),2);a.j.resolve();c.h=0})}));
return a}
gk.prototype.writeThenSend=function(a,b){b||(b={});hi()||(this.h=!1);rj.prototype.writeThenSend.call(this,a,b)};
gk.prototype.sendThenWrite=function(a,b,c){b||(b={});hi()||(this.h=!1);rj.prototype.sendThenWrite.call(this,a,b,c)};
gk.prototype.sendAndWrite=function(a,b){b||(b={});hi()||(this.h=!1);rj.prototype.sendAndWrite.call(this,a,b)};
function jk(a){var b;z(function(c){if(!a.s)throw b=ti("clearSWHealthLogsDb"),b;return c.return(Tj(a.s).catch(function(d){a.handleError(d)}))})}
function ik(a,b,c){var d;if(null===(d=b.postParams)||void 0===d?0:d.requestTimeMs)b.postParams.requestTimeMs=Math.round(R());c&&0===Object.keys(b).length?Ug(a):Ig(a,b)}
function hk(){fk||(fk=new dk({sa:!0,Na:!0}));return fk}
;var lk=0,mk=0,nk,ok=B.ytNetworklessLoggingInitializationOptions||{isNwlInitialized:!1,potentialEsfErrorCounter:mk};E("ytNetworklessLoggingInitializationOptions",ok);function pk(a,b){function c(d){var e=qk().D();if(!rk()||!d||e&&Q("vss_networkless_bypass_write"))sk(a,b);else{var f={url:a,options:b,timestamp:R(),status:"NEW",sendCount:0};Gj(f,d).then(function(g){f.id=g;qk().D()&&tk(f)}).catch(function(g){tk(f);
qk().D()?Sf(g):Wj(g)})}}
b=void 0===b?{}:b;Q("skip_is_supported_killswitch")?ij().then(function(d){c(d)}):c(hj())}
function uk(a,b){function c(d){if(rk()&&d){var e={url:a,options:b,timestamp:R(),status:"NEW",sendCount:0},f=!1,g=b.onSuccess?b.onSuccess:function(){};
e.options.onSuccess=function(h,k){void 0!==e.id?Lj(e.id,d):f=!0;Q("vss_network_hint")&&qk().V(!0);g(h,k)};
sk(e.url,e.options);Gj(e,d).then(function(h){e.id=h;f&&Lj(e.id,d)}).catch(function(h){qk().D()?Sf(h):Wj(h)})}else sk(a,b)}
b=void 0===b?{}:b;Q("skip_is_supported_killswitch")?ij().then(function(d){c(d)}):c(hj())}
function vk(){var a=hj();if(!a)throw ti("throttleSend");lk||(lk=yg.L(function(){var b;return z(function(c){if(1==c.h)return w(c,Ij("NEW",a),2);if(3!=c.h)return b=c.i,b?w(c,tk(b),3):(yg.W(lk),lk=0,c.return());lk&&(lk=0,vk());c.h=0})},100))}
function tk(a){var b,c,d;return z(function(e){switch(e.h){case 1:b=hj();if(!b)throw c=ti("immediateSend"),c;if(void 0===a.id){e.o(2);break}return w(e,Jj(a.id,b),3);case 3:(d=e.i)?a=d:Tf(Error("The request cannot be found in the database."));case 2:var f=a.timestamp;if(!(2592E6<=R()-f)){e.o(4);break}Tf(Error("Networkless Logging: Stored logs request expired age limit"));if(void 0===a.id){e.o(5);break}return w(e,Lj(a.id,b),5);case 5:return e.return();case 4:a.skipRetry||(a=wk(a));f=a;var g,h;if(null===
(h=null===(g=null===f||void 0===f?void 0:f.options)||void 0===g?void 0:g.postParams)||void 0===h?0:h.requestTimeMs)f.options.postParams.requestTimeMs=Math.round(R());a=f;if(!a){e.o(0);break}if(!a.skipRetry||void 0===a.id){e.o(8);break}return w(e,Lj(a.id,b),8);case 8:sk(a.url,a.options,!!a.skipRetry),e.h=0}})}
function wk(a){var b=hj();if(!b)throw ti("updateRequestHandlers");var c=a.options.onError?a.options.onError:function(){};
a.options.onError=function(e,f){var g;return z(function(h){switch(h.h){case 1:g=yj(f);if(!(Q("nwl_consider_error_code")&&g||!Q("nwl_consider_error_code")&&xk()<=ng("potential_esf_error_limit",10))){h.o(2);break}return w(h,qk().S(),3);case 3:if(qk().D()){h.o(2);break}c(e,f);if(!Q("nwl_consider_error_code")||void 0===(null===a||void 0===a?void 0:a.id)){h.o(5);break}return w(h,Kj(a.id,b,!1),5);case 5:return h.return();case 2:if(Q("nwl_consider_error_code")&&!g&&xk()>ng("potential_esf_error_limit",10))return h.return();
C("ytNetworklessLoggingInitializationOptions")&&ok.potentialEsfErrorCounter++;mk++;if(void 0===(null===a||void 0===a?void 0:a.id)){h.o(7);break}return 1>a.sendCount?w(h,Kj(a.id,b),11):w(h,Lj(a.id,b),7);case 11:yg.L(function(){qk().D()&&vk()},5E3);
case 7:c(e,f),h.h=0}})};
var d=a.options.onSuccess?a.options.onSuccess:function(){};
a.options.onSuccess=function(e,f){return z(function(g){if(1==g.h)return void 0===(null===a||void 0===a?void 0:a.id)?g.o(2):w(g,Lj(a.id,b),2);Q("vss_network_hint")&&qk().V(!0);d(e,f);g.h=0})};
return a}
function qk(){if(Q("use_new_nwl"))return hk();nk||(nk=new dk({sa:!0,Na:!0}));return nk}
function sk(a,b,c){c&&0===Object.keys(b).length?Ug(a):Ig(a,b)}
function rk(){return C("ytNetworklessLoggingInitializationOptions")?ok.isNwlInitialized:!1}
function xk(){return C("ytNetworklessLoggingInitializationOptions")?ok.potentialEsfErrorCounter:mk}
;function yk(a){var b=this;this.config_=null;a?this.config_=a:Nh()&&(this.config_=vh());tg(function(){$h(b)},5E3)}
yk.prototype.isReady=function(){!this.config_&&Nh()&&(this.config_=vh());return!!this.config_};
function zh(a,b,c,d){function e(x){x=void 0===x?!1:x;var y;if(d.retry&&"www.youtube-nocookie.com"!=h&&(x||Q("skip_ls_gel_retry")||"application/json"!==g.headers["Content-Type"]||(y=Yh(b,c,l,k)),y)){var A=g.onSuccess,M=g.onFetchSuccess;g.onSuccess=function(N,P){Zh(y);A(N,P)};
c.onFetchSuccess=function(N,P){Zh(y);M(N,P)}}try{x&&d.retry&&!d.Wa.bypassNetworkless?(g.method="POST",d.Wa.writeThenSend?Q("use_new_nwl")?kk().writeThenSend(q,g):pk(q,g):Q("use_new_nwl")?kk().sendAndWrite(q,g):uk(q,g)):(g.method="POST",g.postParams||(g.postParams={}),Ig(q,g))}catch(N){if("InvalidAccessError"==N.name)y&&(Zh(y),y=0),Tf(Error("An extension is blocking network request."));
else throw N;}y&&tg(function(){$h(a)},5E3)}
!O("VISITOR_DATA")&&"visitor_id"!==b&&.01>Math.random()&&Tf(new gi("Missing VISITOR_DATA when sending innertube request.",b,c,d));if(!a.isReady()){var f=new gi("innertube xhrclient not ready",b,c,d);Sf(f);throw f;}var g={headers:d.headers||{},method:"POST",postParams:c,postBody:d.postBody,postBodyFormat:d.postBodyFormat||"JSON",onTimeout:function(){d.onTimeout()},
onFetchTimeout:d.onTimeout,onSuccess:function(x,y){if(d.onSuccess)d.onSuccess(y)},
onFetchSuccess:function(x){if(d.onSuccess)d.onSuccess(x)},
onError:function(x,y){if(d.onError)d.onError(y)},
onFetchError:function(x){if(d.onError)d.onError(x)},
timeout:d.timeout,withCredentials:!0};g.headers["Content-Type"]||(g.headers["Content-Type"]="application/json");var h="";(f=a.config_.pb)&&(h=f);var k=a.config_.rb||!1,l=Th(k,h,d);Object.assign(g.headers,l);(f=g.headers.Authorization)&&!h&&(g.headers["x-origin"]=window.location.origin);var n="/youtubei/"+a.config_.innertubeApiVersion+"/"+b,p={alt:"json"},u=a.config_.qb&&f;Q("omit_innertube_api_key_for_bearer_auth_header")&&(u=u&&f.startsWith("Bearer"));u||(p.key=a.config_.innertubeApiKey);var q=kg(""+
h+n,p||{},!0);Q("use_new_nwl")||rk()?gj().then(function(x){e(x)}):e(!1)}
;function zk(a,b){var c=void 0===c?{}:c;var d=yk;O("ytLoggingEventsDefaultDisabled",!1)&&yk==yk&&(d=null);a:{c=void 0===c?{}:c;if(Q("lr_drop_other_and_business_payloads")){if(rg[a]||qg[a])break a}else if(Q("lr_drop_other_payloads")&&rg[a])break a;var e={},f=Math.round(c.timestamp||R());e.eventTimeMs=f<Number.MAX_SAFE_INTEGER?f:0;e[a]=b;a=C("_lact",window);a=null==a?-1:Math.max(Date.now()-a,0);e.context={lastActivityMs:String(c.timestamp||!isFinite(a)?-1:a)};Q("log_sequence_info_on_gel_web")&&c.cb&&
(a=e.context,b=c.cb,Fh[b]=b in Fh?Fh[b]+1:0,a.sequence={index:Fh[b],groupKey:b},c.Rb&&delete Fh[c.cb]);(c.Xb?rh:nh)({endpoint:"log_event",payload:e,da:c.da,za:c.za},d)}}
;var Ak=[{Ea:function(a){return"Cannot read property '"+a.key+"'"},
ta:{Error:[{regexp:/(Permission denied) to access property "([^']+)"/,groups:["reason","key"]}],TypeError:[{regexp:/Cannot read property '([^']+)' of (null|undefined)/,groups:["key","value"]},{regexp:/\u65e0\u6cd5\u83b7\u53d6\u672a\u5b9a\u4e49\u6216 (null|undefined) \u5f15\u7528\u7684\u5c5e\u6027\u201c([^\u201d]+)\u201d/,groups:["value","key"]},{regexp:/\uc815\uc758\ub418\uc9c0 \uc54a\uc74c \ub610\ub294 (null|undefined) \ucc38\uc870\uc778 '([^']+)' \uc18d\uc131\uc744 \uac00\uc838\uc62c \uc218 \uc5c6\uc2b5\ub2c8\ub2e4./,
groups:["value","key"]},{regexp:/No se puede obtener la propiedad '([^']+)' de referencia nula o sin definir/,groups:["key"]},{regexp:/Unable to get property '([^']+)' of (undefined or null) reference/,groups:["key","value"]},{regexp:/(null) is not an object \(evaluating '(?:([^.]+)\.)?([^']+)'\)/,groups:["value","base","key"]}]}},{Ea:function(a){return"Cannot call '"+a.key+"'"},
ta:{TypeError:[{regexp:/(?:([^ ]+)?\.)?([^ ]+) is not a function/,groups:["base","key"]},{regexp:/([^ ]+) called on (null or undefined)/,groups:["key","value"]},{regexp:/Object (.*) has no method '([^ ]+)'/,groups:["base","key"]},{regexp:/Object doesn't support property or method '([^ ]+)'/,groups:["key"]},{regexp:/\u30aa\u30d6\u30b8\u30a7\u30af\u30c8\u306f '([^']+)' \u30d7\u30ed\u30d1\u30c6\u30a3\u307e\u305f\u306f\u30e1\u30bd\u30c3\u30c9\u3092\u30b5\u30dd\u30fc\u30c8\u3057\u3066\u3044\u307e\u305b\u3093/,
groups:["key"]},{regexp:/\uac1c\uccb4\uac00 '([^']+)' \uc18d\uc131\uc774\ub098 \uba54\uc11c\ub4dc\ub97c \uc9c0\uc6d0\ud558\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4./,groups:["key"]}]}},{Ea:function(a){return a.key+" is not defined"},
ta:{ReferenceError:[{regexp:/(.*) is not defined/,groups:["key"]},{regexp:/Can't find variable: (.*)/,groups:["key"]}]}}];var Ck={U:[],T:[{jb:Bk,weight:500}]};function Bk(a){if("JavaException"===a.name)return!0;a=a.stack;return a.includes("chrome://")||a.includes("chrome-extension://")||a.includes("moz-extension://")}
;function Dk(){this.T=[];this.U=[]}
var Ek;function Fk(){if(!Ek){var a=Ek=new Dk;a.U.length=0;a.T.length=0;Ck.U&&a.U.push.apply(a.U,Ck.U);Ck.T&&a.T.push.apply(a.T,Ck.T)}return Ek}
;var Gk=new L;function Hk(a){function b(){return a.charCodeAt(d++)}
var c=a.length,d=0;do{var e=Ik(b);if(Infinity===e)break;var f=e>>3;switch(e&7){case 0:e=Ik(b);if(2===f)return e;break;case 1:if(2===f)return;d+=8;break;case 2:e=Ik(b);if(2===f)return a.substr(d,e);d+=e;break;case 5:if(2===f)return;d+=4;break;default:return}}while(d<c)}
function Ik(a){var b=a(),c=b&127;if(128>b)return c;b=a();c|=(b&127)<<7;if(128>b)return c;b=a();c|=(b&127)<<14;if(128>b)return c;b=a();return 128>b?c|(b&127)<<21:Infinity}
;function Jk(a,b,c,d){if(a)if(Array.isArray(a)){var e=d;for(d=0;d<a.length&&!(a[d]&&(e+=Kk(d,a[d],b,c),500<e));d++);d=e}else if("object"===typeof a)for(e in a){if(a[e]){var f=a[e];var g=b;var h=c;g="string"!==typeof f||"clickTrackingParams"!==e&&"trackingParams"!==e?0:(f=Hk(atob(f.replace(/-/g,"+").replace(/_/g,"/"))))?Kk(e+".ve",f,g,h):0;d+=g;d+=Kk(e,a[e],b,c);if(500<d)break}}else c[b]=Lk(a),d+=c[b].length;else c[b]=Lk(a),d+=c[b].length;return d}
function Kk(a,b,c,d){c+="."+a;a=Lk(b);d[c]=a;return c.length+a.length}
function Lk(a){try{return("string"===typeof a?a:String(JSON.stringify(a))).substr(0,500)}catch(b){return"unable to serialize "+typeof a+" ("+b.message+")"}}
;var Mk=new Set,Nk=0,Ok=0,Pk=0,Qk=[],Rk=["PhantomJS","Googlebot","TO STOP THIS SECURITY SCAN go/scan"];var Sk={};function Tk(a){return Sk[a]||(Sk[a]=String(a).replace(/\-([a-z])/g,function(b,c){return c.toUpperCase()}))}
;var Uk={},Vk=[],Ve=new L,Wk={};function Xk(){for(var a=t(Vk),b=a.next();!b.done;b=a.next())b=b.value,b()}
function Yk(a,b){var c;"yt:"===a.tagName.toLowerCase().substr(0,3)?c=a.getAttribute(b):c=a?a.dataset?a.dataset[Tk(b)]:a.getAttribute("data-"+b):null;return c}
function Zk(a){Ve.ca.apply(Ve,arguments)}
;function $k(a){this.h=a||{};a=[this.h,window.YTConfig||{}];for(var b=0;b<a.length;b++)a[b].host&&(a[b].host=a[b].host.toString().replace("http://","https://"))}
function Z(a,b){a=[a.h,window.YTConfig||{}];for(var c=0;c<a.length;c++){var d=a[c][b];if(void 0!==d)return d}return null}
function al(a,b,c){bl||(bl={},ag(window,"message",function(d){a:{if(d.origin===Z(a,"host")){try{var e=JSON.parse(d.data)}catch(f){e=void 0;break a}if(d=bl[e.id])d.u=!0,d.u&&(G(d.v,d.sendMessage,d),d.v.length=0),d.Ja(e)}e=void 0}return e}));
bl[c]=b}
var bl=null;function cl(a,b,c){this.m=this.h=this.i=null;this.j=0;this.u=!1;this.v=[];this.l=null;this.I={};if(!a)throw Error("YouTube player element ID required.");this.id=Ma(this);this.A=c;this.setup(a,b)}
m=cl.prototype;m.setSize=function(a,b){this.h.width=a.toString();this.h.height=b.toString();return this};
m.getIframe=function(){return this.h};
m.Ja=function(a){dl(this,a.event,a)};
m.addEventListener=function(a,b){var c=b;"string"===typeof b&&(c=function(){window[b].apply(window,arguments)});
if(!c)return this;this.l.subscribe(a,c);el(this,a);return this};
function fl(a,b){b=b.split(".");if(2===b.length){var c=b[1];a.A===b[0]&&el(a,c)}}
m.destroy=function(){this.h&&this.h.id&&(Uk[this.h.id]=null);(0,jd)(this.l);if(this.m){var a=this.h,b=a.parentNode;b&&b.replaceChild(this.m,a)}else(a=this.h)&&a.parentNode&&a.parentNode.removeChild(a);bl&&(bl[this.id]=null);this.i=null;a=this.h;for(var c in db)db[c][0]==a&&Zf(c);this.m=this.h=null};
m.Ma=function(){return{}};
function gl(a,b,c){c=c||[];c=Array.prototype.slice.call(c);b={event:"command",func:b,args:c};a.u?a.sendMessage(b):a.v.push(b)}
function dl(a,b,c){a.l.l||(c={target:a,data:c},a.l.ca(b,c),Zk(a.A+"."+b,c))}
function hl(a,b){var c=document.createElement("iframe");b=b.attributes;for(var d=0,e=b.length;d<e;d++){var f=b[d].value;null!=f&&""!==f&&"null"!==f&&c.setAttribute(b[d].name,f)}c.setAttribute("frameBorder","0");c.setAttribute("allowfullscreen","1");c.setAttribute("allow","accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture");c.setAttribute("title","YouTube "+Z(a.i,"title"));(b=Z(a.i,"width"))&&c.setAttribute("width",b.toString());(b=Z(a.i,"height"))&&c.setAttribute("height",
b.toString());var g=a.Ma();g.enablejsapi=window.postMessage?1:0;window.location.host&&(g.origin=window.location.protocol+"//"+window.location.host);g.widgetid=a.id;window.location.href&&G(["debugjs","debugcss"],function(h){var k=Rb(window.location.href,h);null!==k&&(g[h]=k)});
window.yt_embedsTokenValue&&(g.embedsTokenValue=encodeURIComponent(window.yt_embedsTokenValue),delete window.yt_embedsTokenValue);c.src=Z(a.i,"host")+("/embed/"+Z(a.i,"videoId"))+"?"+Pb(g);return c}
m.Xa=function(){this.h&&this.h.contentWindow?this.sendMessage({event:"listening"}):window.clearInterval(this.j)};
function il(a){al(a.i,a,a.id);a.j=cg(a.Xa.bind(a));ag(a.h,"load",function(){window.clearInterval(a.j);a.j=cg(a.Xa.bind(a))})}
m.setup=function(a,b){var c=document;if(a="string"===typeof a?c.getElementById(a):a)if(c="iframe"===a.tagName.toLowerCase(),b.host||(b.host=c?Nb(a.src):"https://www.youtube.com"),this.i=new $k(b),c||(b=hl(this,a),this.m=a,(c=a.parentNode)&&c.replaceChild(b,a),a=b),this.h=a,this.h.id||(this.h.id="widget"+Ma(this.h)),Uk[this.h.id]=this,window.postMessage){this.l=new L;il(this);b=Z(this.i,"events");for(var d in b)b.hasOwnProperty(d)&&this.addEventListener(d,b[d]);for(var e in Wk)Wk.hasOwnProperty(e)&&
fl(this,e)}};
function el(a,b){a.I[b]||(a.I[b]=!0,gl(a,"addEventListener",[b]))}
m.sendMessage=function(a){a.id=this.id;a.channel="widget";a=Ce(a);var b=[Nb(this.h.src||"").replace("http:","https:")];if(this.h.contentWindow)for(var c=0;c<b.length;c++)try{this.h.contentWindow.postMessage(a,b[c])}catch(A){if(A.name&&"SyntaxError"===A.name){if(!(A.message&&0<A.message.indexOf("target origin ''"))){var d=void 0,e=A;d=void 0===d?{}:d;d.name=O("INNERTUBE_CONTEXT_CLIENT_NAME",1);d.version=O("INNERTUBE_CONTEXT_CLIENT_VERSION",void 0);var f=d||{};d="WARNING";d=void 0===d?"ERROR":d;if(e){e.hasOwnProperty("level")&&
e.level&&(d=e.level);if(Q("console_log_js_exceptions")){var g=e,h=[];h.push("Name: "+g.name);h.push("Message: "+g.message);g.hasOwnProperty("params")&&h.push("Error Params: "+JSON.stringify(g.params));g.hasOwnProperty("args")&&h.push("Error args: "+JSON.stringify(g.args));h.push("File name: "+g.fileName);h.push("Stacktrace: "+g.stack);window.console.log(h.join("\n"),g)}if(!(5<=Nk)){g=void 0;var k=f,l=md(e);f=l.message||"Unknown Error";h=l.name||"UnknownError";var n=l.stack||e.i||"Not available";if(n.startsWith(h+
": "+f)){var p=n.split("\n");p.shift();n=p.join("\n")}p=l.lineNumber||"Not available";l=l.fileName||"Not available";var u=0;if(e.hasOwnProperty("args")&&e.args&&e.args.length)for(g=0;g<e.args.length&&!(u=Jk(e.args[g],"params."+g,k,u),500<=u);g++);else if(e.hasOwnProperty("params")&&e.params){var q=e.params;if("object"===typeof e.params)for(g in q){if(q[g]){var x="params."+g,y=Lk(q[g]);k[x]=y;u+=x.length+y.length;if(500<u)break}}else k.params=Lk(q)}if(Qk.length)for(g=0;g<Qk.length&&!(u=Jk(Qk[g],"params.context."+
g,k,u),500<=u);g++);navigator.vendor&&!k.hasOwnProperty("vendor")&&(k["device.vendor"]=navigator.vendor);g={message:f,name:h,lineNumber:p,fileName:l,stack:n,params:k,sampleWeight:1};f=Number(e.columnNumber);isNaN(f)||(g.lineNumber=g.lineNumber+":"+f);if("IGNORED"===e.level)e=0;else a:{e=Fk();f=t(e.U);for(h=f.next();!h.done;h=f.next())if(h=h.value,g.message&&g.message.match(h.Ub)){e=h.weight;break a}e=t(e.T);for(f=e.next();!f.done;f=e.next())if(f=f.value,f.jb(g)){e=f.weight;break a}e=1}g.sampleWeight=
e;e=g;g=t(Ak);for(f=g.next();!f.done;f=g.next())if(f=f.value,f.ta[e.name])for(p=t(f.ta[e.name]),h=p.next();!h.done;h=p.next())if(l=h.value,h=e.message.match(l.regexp)){e.params["params.error.original"]=h[0];p=l.groups;l={};for(n=0;n<p.length;n++)l[p[n]]=h[n+1],e.params["params.error."+p[n]]=h[n+1];e.message=f.Ea(l);break}e.params||(e.params={});g=Fk();e.params["params.errorServiceSignature"]="msg="+g.U.length+"&cb="+g.T.length;e.params["params.serviceWorker"]="false";B.document&&B.document.querySelectorAll&&
(e.params["params.fscripts"]=String(document.querySelectorAll("script:not([nonce])").length));mb("sample").constructor!==kb&&(e.params["params.fconst"]="true");window.yterr&&"function"===typeof window.yterr&&window.yterr(e);if(0!==e.sampleWeight&&!Mk.has(e.message)){"ERROR"===d?(Gk.ca("handleError",e),Q("record_app_crashed_web")&&0===Pk&&1===e.sampleWeight&&(Pk++,g={appCrashType:"APP_CRASH_TYPE_BREAKPAD"},Q("report_client_error_with_app_crash_ks")||(g.systemHealth={crashData:{clientError:{logMessage:{message:e.message}}}}),
zk("appCrashed",g)),Ok++):"WARNING"===d&&Gk.ca("handleWarning",e);if(Q("kevlar_gel_error_routing")){g=d;h=e;b:{f=t(Rk);for(p=f.next();!p.done;p=f.next())if(Rg(p.value.toLowerCase())){f=!0;break b}f=!1}if(f)f=void 0;else{p={stackTrace:h.stack};h.fileName&&(p.filename=h.fileName);f=h.lineNumber&&h.lineNumber.split?h.lineNumber.split(":"):[];0!==f.length&&(1!==f.length||isNaN(Number(f[0]))?2!==f.length||isNaN(Number(f[0]))||isNaN(Number(f[1]))||(p.lineNumber=Number(f[0]),p.columnNumber=Number(f[1])):
p.lineNumber=Number(f[0]));f={level:"ERROR_LEVEL_UNKNOWN",message:h.message,errorClassName:h.name,sampleWeight:h.sampleWeight};"ERROR"===g?f.level="ERROR_LEVEL_ERROR":"WARNING"===g&&(f.level="ERROR_LEVEL_WARNNING");p={isObfuscated:!0,browserStackInfo:p};l={pageUrl:window.location.href,kvPairs:[]};O("FEXP_EXPERIMENTS")&&(l.experimentIds=O("FEXP_EXPERIMENTS"));n=Of();k=(k=Kf.EXPERIMENT_FLAGS)?k.web_disable_gel_stp_ecatcher_killswitch:void 0;if(!k&&n)for(u=t(Object.keys(n)),k=u.next();!k.done;k=u.next())k=
k.value,l.kvPairs.push({key:k,value:String(n[k])});if(h=h.params)for(n=t(Object.keys(h)),k=n.next();!k.done;k=n.next())k=k.value,l.kvPairs.push({key:"client."+k,value:String(h[k])});h=O("SERVER_NAME",void 0);n=O("SERVER_VERSION",void 0);h&&n&&(l.kvPairs.push({key:"server.name",value:h}),l.kvPairs.push({key:"server.version",value:n}));f={errorMetadata:l,stackTrace:p,logMessage:f}}f&&(zk("clientError",f),("ERROR"===g||Q("errors_flush_gel_always_killswitch"))&&ph())}if(!Q("suppress_error_204_logging")){f=
e;g=f.params||{};d={urlParams:{a:"logerror",t:"jserror",type:f.name,msg:f.message.substr(0,250),line:f.lineNumber,level:d,"client.name":g.name},postParams:{url:O("PAGE_NAME",window.location.href),file:f.fileName},method:"POST"};g.version&&(d["client.version"]=g.version);if(d.postParams){f.stack&&(d.postParams.stack=f.stack);f=t(Object.keys(g));for(h=f.next();!h.done;h=f.next())h=h.value,d.postParams["client."+h]=g[h];if(g=Of())for(f=t(Object.keys(g)),h=f.next();!h.done;h=f.next())h=h.value,d.postParams[h]=
g[h];g=O("SERVER_NAME",void 0);f=O("SERVER_VERSION",void 0);g&&f&&(d.postParams["server.name"]=g,d.postParams["server.version"]=f)}Ig(O("ECATCHER_REPORT_HOST","")+"/error_204",d)}try{Mk.add(e.message)}catch(M){}Nk++}}}}}else throw A;}else console&&console.warn&&console.warn("The YouTube player is not attached to the DOM. API calls should be made after the onReady event. See more: https://developers.google.com/youtube/iframe_api_reference#Events")};function jl(a){return(0===a.search("cue")||0===a.search("load"))&&"loadModule"!==a}
function kl(a){return 0===a.search("get")||0===a.search("is")}
;function ll(a,b){cl.call(this,a,Object.assign({title:"video player",videoId:"",width:640,height:360},b||{}),"player");this.M={};this.playerInfo={}}
v(ll,cl);m=ll.prototype;m.Ma=function(){var a=Z(this.i,"playerVars");if(a){var b={},c;for(c in a)b[c]=a[c];a=b}else a={};window!==window.top&&document.referrer&&(a.widget_referrer=document.referrer.substring(0,256));if(c=Z(this.i,"embedConfig")){if(D(c))try{c=JSON.stringify(c)}catch(d){console.error("Invalid embed config JSON",d)}a.embed_config=c}return a};
m.Ja=function(a){var b=a.event;a=a.info;switch(b){case "apiInfoDelivery":if(D(a))for(var c in a)a.hasOwnProperty(c)&&(this.M[c]=a[c]);break;case "infoDelivery":ml(this,a);break;case "initialDelivery":D(a)&&(window.clearInterval(this.j),this.playerInfo={},this.M={},nl(this,a.apiInterface),ml(this,a));break;default:dl(this,b,a)}};
function ml(a,b){if(D(b))for(var c in b)b.hasOwnProperty(c)&&(a.playerInfo[c]=b[c])}
function nl(a,b){G(b,function(c){this[c]||("getCurrentTime"===c?this[c]=function(){var d=this.playerInfo.currentTime;if(1===this.playerInfo.playerState){var e=(Date.now()/1E3-this.playerInfo.currentTimeLastUpdated_)*this.playerInfo.playbackRate;0<e&&(d+=Math.min(e,1))}return d}:jl(c)?this[c]=function(){this.playerInfo={};
this.M={};gl(this,c,arguments);return this}:kl(c)?this[c]=function(){var d=0;
0===c.search("get")?d=3:0===c.search("is")&&(d=2);return this.playerInfo[c.charAt(d).toLowerCase()+c.substr(d+1)]}:this[c]=function(){gl(this,c,arguments);
return this})},a)}
m.getVideoEmbedCode=function(){var a=Z(this.i,"host")+("/embed/"+Z(this.i,"videoId")),b=Number(Z(this.i,"width")),c=Number(Z(this.i,"height"));if(isNaN(b)||isNaN(c))throw Error("Invalid width or height property");b=Math.floor(b);c=Math.floor(c);a=ob(a,void 0);return'<iframe width="'+b+'" height="'+c+'" src="'+a+'" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>'};
m.getOptions=function(a){return this.M.namespaces?a?this.M[a]?this.M[a].options||[]:[]:this.M.namespaces||[]:[]};
m.getOption=function(a,b){if(this.M.namespaces&&a&&b&&this.M[a])return this.M[a][b]};
function ol(a){if("iframe"!==a.tagName.toLowerCase()){var b=Yk(a,"videoid");b&&(b={videoId:b,width:Yk(a,"width"),height:Yk(a,"height")},new ll(a,b))}}
;E("YT.PlayerState.UNSTARTED",-1);E("YT.PlayerState.ENDED",0);E("YT.PlayerState.PLAYING",1);E("YT.PlayerState.PAUSED",2);E("YT.PlayerState.BUFFERING",3);E("YT.PlayerState.CUED",5);E("YT.get",function(a){return Uk[a]});
E("YT.scan",Xk);E("YT.subscribe",function(a,b,c){Ve.subscribe(a,b,c);Wk[a]=!0;for(var d in Uk)Uk.hasOwnProperty(d)&&fl(Uk[d],a)});
E("YT.unsubscribe",function(a,b,c){Ue(a,b,c)});
E("YT.Player",ll);cl.prototype.destroy=cl.prototype.destroy;cl.prototype.setSize=cl.prototype.setSize;cl.prototype.getIframe=cl.prototype.getIframe;cl.prototype.addEventListener=cl.prototype.addEventListener;ll.prototype.getVideoEmbedCode=ll.prototype.getVideoEmbedCode;ll.prototype.getOptions=ll.prototype.getOptions;ll.prototype.getOption=ll.prototype.getOption;
Vk.push(function(a){var b=a;b||(b=document);a=$a(b.getElementsByTagName("yt:player"));var c=b||document;if(c.querySelectorAll&&c.querySelector)b=c.querySelectorAll(".yt-player");else{var d;c=document;b=b||c;if(b.querySelectorAll&&b.querySelector)b=b.querySelectorAll(".yt-player");else if(b.getElementsByClassName){var e=b.getElementsByClassName("yt-player");b=e}else{e=b.getElementsByTagName("*");var f={};for(c=d=0;b=e[c];c++){var g=b.className,h;if(h="function"==typeof g.split)h=0<=Wa(g.split(/\s+/),
"yt-player");h&&(f[d++]=b)}f.length=d;b=f}}b=$a(b);G(Za(a,b),ol)});
"undefined"!=typeof YTConfig&&YTConfig.parsetags&&"onload"!=YTConfig.parsetags||Xk();var pl=B.onYTReady;pl&&pl();var ql=B.onYouTubeIframeAPIReady;ql&&ql();var rl=B.onYouTubePlayerAPIReady;rl&&rl();}).call(this);
