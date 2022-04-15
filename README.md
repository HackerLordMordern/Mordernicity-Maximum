# Mordernicity-Maximum
Ultimate Mod 
// ==UserScript==
// @name         Mordernicity Maximum
// @namespace    Hacker Lord Mordern
// @version      Mordern.Ultimate
// @description  I am ultimate rest are inferior
// @author       Hacker Lord Mordern
// @match        *://moomoo.io/*
// @match        *://dev.moomoo.io/*
// @match        *://sandbox.moomoo.io/*
// @match        *://*.moomoo.io/*
// @require      https://code.jquery.com/jquery-3.3.1.slim.min.js
// @require      https://cdnjs.cloudflare.com/ajax/libs/socket.io/1.4.5/socket.io.min.js
// @require      http://code.jquery.com/jquery-3.3.1.min.js
// @require      https://cdn.jsdelivr.net/npm/msgpack-lite@0.1.26/dist/msgpack.min.js
// @require      https://cdn.jsdelivr.net/npm/fontfaceobserver@2.1.0/fontfaceobserver.standalone.min.js
// @grant        none
// @license      GNU PUBLIC LISCENSE V3
// ==/UserScript==
setInterval(() => window.follmoo && follmoo(), 10);
var spikeType;
console.log("Mod starting");
document.getElementById('gameName').innerHTML = 'Mordernicity Maximum';
document.getElementById('loadingText').innerHTML = 'I am Ultimate';
document.getElementById('diedText').innerHTML = "YOu got defeated by a inferior what a shame!";
document.getElementById('diedText').style.color = "#ff0000";
document.title = 'Mordernicity Maximum';
document.getElementById("leaderboard").append ('Mordernicity Maximum');
document.querySelector("#pre-content-container").remove();
document.getElementById("enterGame").addEventListener('click', autohide);
document.getElementById("storeHolder").style = "height: 1000px; width: 480px;";
function autohide(){
    $("#ot-sdk-btn-floating").hide();
var autoreloadloop;
var autoreloadenough = 0;
 
autoreloadloop = setInterval(function () {
    if (autoreloadenough < 200) {
        if (document.getElementById("loadingText").innerHTML == `disconnected<a href="javascript:window.location.href=window.location.href" class="ytLink">reload</a>`) {
            document.title = "Disconnected? NP";
            clearInterval(autoreloadloop);
            setTimeout(function () {document.title = "Moo Moo";}, 1000)
            location.reload();
        }
        autoreloadenough++;
    }
    else if (autoreloadenough >= 300) {
        clearInterval(autoreloadloop);
        document.title = "MOOMOO.IO";
        setTimeout(function () {document.title = "Moo Moo";}, 1000)
    }
}, 50);
function Hat (id){
    storeBuy(id);
    storeEquip(id);
}
 
document.addEventListener('keydown', function(e) {
    if (e.keyCode == 27 && document.activeElement.id.toLowerCase() !== 'chatbox') { // ESC for Unequip
        Hat(0);
    }
    if (e.keyCode == 66 && document.activeElement.id.toLowerCase() !== 'chatbox') { // B for Soldier
        Hat(6);
    }
    if (e.keyCode == 71 && document.activeElement.id.toLowerCase() !== 'chatbox') { // G for Turret gear
        Hat(53);
    }
    if (e.keyCode == 16 && document.activeElement.id.toLowerCase() !== 'chatbox') { // SHIFT for booster hat
        Hat(12);
    }
    if (e.keyCode == 188 && document.activeElement.id.toLowerCase() !== 'chatbox') { // "," for snow hat
        Hat(15);
    }
    if (e.keyCode == 60 && document.activeElement.id.toLowerCase() !== 'chatbox') { // < for flipper hat
        Hat(31);
    }
    if (e.keyCode == 90 && document.activeElement.id.toLowerCase() !== 'chatbox') { // Z for tank gear
        Hat(40);
    }
    if (e.keyCode == 74 && document.activeElement.id.toLowerCase() !== 'chatbox') { // J for emp helmet
        Hat(22);
    }
    if (e.keyCode == 84 && document.activeElement.id.toLowerCase() !== 'chatbox') { // T for samurai
        Hat(20);
    }
    if (e.keyCode == 89 && document.activeElement.id.toLowerCase() !== 'chatbox') { // Y for Bull Helmet
        Hat(7);
    }
});
 setTimeout( () => {
                newSend(["6", [4]]);//katana
            }, 35);
 
            setTimeout( () => {
                newSend(["6", [15]]);//musket
                autosecondary = true;
                newSend(["5", [secondary, true]]);
                newSend(["13c", [1, 53, 0]]);
                newSend(["13c", [0, 53, 0]]);
            }, 50);
//Katana And Musket Above
if(a.keyCode == 46 && document.activeElement.id.toLowerCase() !== 'chatbox') {
        newSend(["6", [4]]);
        newSend(["15", [15]]);
}
if (a.keyCode == 76 && document.activeElement.id.toLowerCase() !== 'chatbox') {//reverse insta
        autoprimary = false;
        autosecondary = true;
        autoaim = true;
        doinsta = true;
        newSend(["13c", [0, 0, 1]]);
        newSend(["5", [secondary, true]]);
        newSend(["7", [1]]);
        newSend(["13c", [1, 53, 0]]);
        newSend(["13c", [0, 53, 0]]);
        newSend(["13c", [1, 21, 1]]);
        newSend(["13c", [0, 21, 1]]);
        setTimeout( () => {
            autoprimary = true;
            autosecondary = false;
            newSend(["13c", [1, 7, 0]]);
            newSend(["13c", [0, 7, 0]]);
            newSend(["13c", [0, 21, 1]]);
            newSend(["5", [primary, true]]);
        }, 40);
}
 if (a.keyCode == 32 && document.activeElement.id.toLowerCase() !== 'chatbox') {
     newSend(["ch", ['Project Infinite Insta!']]);
        Hat(7);
        acc(21);
        setTimeout( () => {
            place(spikeType, myPlayer.dir + toRad(45));
            place(spikeType, myPlayer.dir - toRad(45));
        }, 40);
        setTimeout( () => {
            Hat(53);
        }, 50);
console.log("Insta Is Complete!");
 }
const CanvasAPI = document.getElementById("gameCanvas")
CanvasAPI.addEventListener("mousedown", buttonPressD, false);
//2 - right
//1 - scroll wheel
//0 - left
function buttonPressD(e) {
    if (document.getElementById("click").checked) {
        if (e.button == 2) {
            if(secondary == 10){
                newSend(["5", [secondary, true]]);
            }
            hat(40);
            acc(21);
            newSend(["7", [1]]);
            setTimeout( () => {
                if(secondary == 10){
                    newSend(["5", [primary, true]]);
                }
                acc(11);
                if (myPlayer.y < 2400) {
                    hat(15);
                } else {
                    if (myPlayer.y > 6850 && myPlayer.y < 7550) {
                        hat(31);
                    } else {
                        hat(12);
                    }
                }
                newSend(["7", [1]]);
            }, 100);
        }
    }
}
let mouseX;
let mouseY;
let width;
let height;
function aim(x, y){
    var cvs = document.getElementById("gameCanvas");
    cvs.dispatchEvent(new MouseEvent("mousemove", {
        clientX: x,
        clientY: y
    }));
}
let coreURL = new URL(window.location.href);
window.sessionStorage.force = coreURL.searchParams.get("fc");
var foodType;
var millType;
var boostType;
var spikeType;
var ws;
var msgpack5 = msgpack;
let myPlayer = {
    id: null,
    x: null,
    y: null,
    dir: null,
    object: null,
    weapon: null,
    clan: null,
    isLeader: null,
    hat: null,
    accessory: null,
    isSkull: null
};
let healSpeed = 100;
let healToggle = 1;
document.msgpack = msgpack;
function n(){
    this.buffer = new Uint8Array([0]);
    this.buffer.__proto__ = new Uint8Array;
    this.type = 0;
}
WebSocket.prototype.oldSend = WebSocket.prototype.send;
WebSocket.prototype.send = function(m){
    if (!ws){
        document.ws = this;
        ws = this;
        socketFound(this);
    }
    this.oldSend(m);
};
function socketFound(socket){
    socket.addEventListener('message', function(message){
        handleMessage(message);
    });
}
function handleMessage(m){
    let temp = msgpack5.decode(new Uint8Array(m.data));
    let data;
    if(temp.length > 1) {
        data = [temp[0], ...temp[1]];
        if (data[1] instanceof Array){
            data = data;
        }
    } else {
        data = temp;
    }
    let item = data[0];
    if(!data) {return};
    if(item === "io-init") {
        let cvs = document.getElementById("gameCanvas");
        width = cvs.clientWidth;
        height = cvs.clientHeight;
        $(window).resize(function() {
            width = cvs.clientWidth;
            height = cvs.clientHeight;
        });
        cvs.addEventListener("mousemove", e => {
            mouseX = e.clientX;
            mouseY = e.clientY;
        });
    }
    if (item == "1" && myPlayer.id == null){
        myPlayer.id = data[1];
    }
    if(item == "h" && data[1] == myPlayer.id) {
        if(data[2] < 90 && healToggle == 1) {
            setTimeout(() => {
                place(foodType, null);
                place(foodType, null);
                place(foodType, null);
            }, healSpeed);
        }
    }
    update();
}
function doNewSend(sender){
    ws.send(new Uint8Array(Array.from(msgpack5.encode(sender))));
}
function hold(id) {
    doNewSend(["5", [id]]);
}
function place(id, angle = Math.atan2(mouseY - height / 2, mouseX - width / 2)) {
    doNewSend(["5", [id, null]]);
    doNewSend(['c', [1, angle]]);
    doNewSend(['c', [0, angle]]);
    doNewSend(['5', [myPlayer.weapon, true]]);
}
document.addEventListener('keydown', (e)=>{
    if(e.keyCode == 80 && document.activeElement.id.toLowerCase()!== 'chatbox') {
    	healToggle = (healToggle + 1) % 2;
        if(healToggle == 1) {
        	document.title = "Autoheal On";
        } else {
        	document.title = " Autoheal Off";
        }
    }
    if(e.keyCode == 86 && document.activeElement.id.toLowerCase()!== 'chatbox') {
    	place(spikeType);
    }
    if(e.keyCode == 70 && document.activeElement.id.toLowerCase()!== 'chatbox') {
    	place(boostType);
    }
    if(e.keyCode == 78 && document.activeElement.id.toLowerCase()!== 'chatbox') {
    	place(millType);
    }
})
 
function isElementVisible(e) {
    return (e.offsetParent !== null);
}
function toRad(angle) {
    return angle * 0.01745329251;
}
function update() {
    for (let i=16;i<19;i++){
        if (isElementVisible(document.getElementById("actionBarItem" + i.toString()))){
            foodType = i - 16;
        }
    }
    for (let i=22;i<26;i++){
        if (isElementVisible(document.getElementById("actionBarItem" + i.toString()))){
            spikeType = i - 16;
        }
    }
    for (let i=26;i<29;i++){
        if (isElementVisible(document.getElementById("actionBarItem" + i.toString()))){
            millType = i - 16;
        }
    }
    for (let i=31;i<33;i++){
        if (isElementVisible(document.getElementById("actionBarItem" + i.toString()))){
            boostType = i - 16;
        }
    }
}
}
