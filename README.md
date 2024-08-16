# জাভাস্ক্রিপ্টের চিটশিট

> Click ★ if you like the project. Your contributions are heartily ♡ welcome.


### সূচীপত্র

<table>
  <thead align="center" width="100" >
    <tr border: none;>
      <td><b>অধ্যায়</b></td>
      <td><b>বিষয়</b></td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="#ব্যাসিক">ব্যাসিক</a></td>
      <td>জাভাস্ক্রিপ্টের আলু পাতা</td>
    </tr>
  </tbody>
</table>


### ব্যাসিক

0. জাভাস্ক্রিপ্ট একটি সিঙ্গেল-থ্রেডেড Asynchronous প্রোগ্রামিং ল্যাঙ্গুয়েজ।
1. সিঙ্গেল-থ্রেডেড ল্যাঙ্গুয়েজ, তার মানে হল জাভাস্ক্রিপ্ট একসাথে একই সময়ে একটা মাত্র কাজ  করতে পারে। Asynchronous বিষয়টা জাভাস্ক্রিপ্ট ল্যাঙ্গুয়েজের কোন বিষয় না, এটি নিয়ন্ত্রিত হয় ব্রাউজার Enviornment এর মাধ্যমে ।
2. ১৯৯৫সালে নেটস্কেপের প্রকৌশলী Brendan Eich জাভাস্ক্রিপ্ট তৈরি করেন, যেটা মুক্তি পায় ১৯৯৬।
3. JavaScript কে সংক্ষেপে JS নামে ডাকা হয়।
4. এটি ওবজেক্ট-ওরিয়েন্টেড, ডায়নামিক প্রোগ্রামিং ভাষা।
5. ECMA Script- European Computer Manufacturer’s Association. জাভাস্ক্রিপ্ট এর স্ট্যান্ডার্ড মেইনটেইন করে এবং Rules সেট করে।
6. জাভাস্ক্রিপ্ট Unicode  character set ব্যবহার করে।
7. সকল জাভাস্ক্রিপ্ট আইডেন্টিফায়ার Case Sensitive.
8. জাভাস্ক্রিপ্টে কোন "Integer" ধরণের টাইপ নাই । বাস্তবে integer গুলোকে ৩২-বিট ইন্টেজার ধরে নিয়ে কাজ করে জাভাস্ক্রিপ্ট।
9. 
10. 
11. জাভাস্ক্রিপ্ট একটি ওবজেক্ট-ওরিয়েন্টেড, ডায়নামিকপ্রোগ্রামিংভাষা ।
12. "Java" এবং "JavaScript" উভয় প্রোগ্রামিং ভাষাই Oracle কোম্পানির ট্রেডমার্ক হিসেবে নিবন্ধিত । জাভাস্ক্রিপ্টের সাথে  Java programming language কে গুলিয়েফেলবেন না । এই দুই প্রোগ্রামিং ভাষার syntax এবং ব্যবহার একেবারেই আলাদা।
13. JS ব্রাউজার ছাড়াও অন্যান্য জায়গায় ব্যবহার করা হয়, যেমন node.js and Apache CouchDB. 
14. জাভাস্ক্রিপ্ট এ যেকোন Function আসলে একেককটি অবজেক্ট ! ফাংশনে আপনি কোড রাখতে পারবেন, আরো পারবেন অবজেক্টের মত কোডের এক জায়গা থেকে আরেক জায়গায় পাস (pass) করাতে ।
15. 
16. JavaScript হল prototype-based, multi-paradigm, supporting object-oriented, imperative, and declarative styles, ডায়নামিক প্রোগ্রামিং ভাষা ।
17. জাভাস্ক্রিপ্টে কোড Left থেকে Right দিকে code এক্সিকিউশন করে 
    Example: 
        let ="javaScript"+15+16; Output: 'javaScript1516'
        let =15+16+"javaScript"; OutPut: '31javaScript'
18. Library
    jQuery, Angular js-(RxJS), Json, React-(Flus, Redux, Mobx), Vue.js


### ভ্যারিয়েবল

0. value সংরক্ষন করার কাজে ভ্যারিয়েবল ব্যবহার করা হয়।
00. ভ্যারিয়েবলের মধ্যে মান রাখার জন্য সমান(=) চিহ্ন ব্যবহার করা হয় ।
1. সকল ভ্যারিয়েবলগুলোকে স্ক্রিপ্টের প্রথমেই ঘোষণা করা প্রোগ্রামিং-এ ভাল অভ্যাস।
2. var, let, const কিওয়ার্ডের মাধ্যমে জাভাস্ক্রিপ্টে ভ্যারিয়েবল ডিক্লেয়ার করা হয়।
3. var/const/let  কিওয়ার্ডের মাধ্যমে শুরু করুন এবং কমা(,) দ্বারা ভ্যারিয়েবলগুলো আলাদা করুন, সবশেষে সেমিকোলন(;) দিন
4. ভ্যারিয়েবলে কোন ভ্যালু এসাইন না করলে সেটা Undefined টাইপ হয়ে বসে থাকে।
5. জাভাস্ক্রিপ্ট ভ্যারিয়েবলকে পুনরায় ঘোষণা করলেও আগের মান হারায় না ।  var Name = "Satt";  var Name;
6. জাভাস্ক্রিপ্ট  কিওয়ার্ডগুলো সংরক্ষিত শব্দ যেগুলো ভ্যারিয়েবলের নামের জন্য ব্যবহার করা যাবেনা ।
7. Null & Undefined data  - আনডিফাইন্ড ভেরিয়েবল এবং ভেরিয়েবলের মান হিসেবে Null ব্যবহার করা হয়     var tk = null;    var tk = 100;
8.  false, 0, শূন্য স্ট্রিং (""), NaN, null, এবং undefined এগুলাকে বুলিয়ানে কনভার্ট করলে false পাওয়া যাবে । অন্য যেকোন টাইপের ভ্যলু বুলিয়ানে কনভার্ট করলে true পাওয়া যায়
9. Falsey Value :  false, 0, শূন্য স্ট্রিং (""), NaN, null, এবং Undefined
10.   tilde ( ~ ),  back-tick ( ` )  Uses: `I am $(varibleName) for React` ;
11.  Variable এবং টেক্সট একসাথে লেখার নিয়ম  `I am $(varibleName) for React` ;


<table>
  <tbody>
    <tr>
      <td>ভেরিয়েবল এসাইন্ড করার পদ্ধতি</td>
      <td>
          1. var a=2, var b=2, var c=2, var d=4;  or a=b=c=2, d=4; <br>
          4.  Replace হওয়ায় দুইটাই Undefine দেখাবে , Variable ()over right var ab=10, bc=20, cd; ab = cd;
          console.log(ab);  // Undefined,  console.log(cd);  // Undefined <br>
      </td>
    </tr>
    <tr>
      <td>আইডেন্টিফায়ার </td>
      <td>সকলজাভাস্ক্রিপ্ট ভ্যারিয়েবল অবশ্যই একটি ইউনিক নামের মাধ্যমে সনাক্ত করতে হবে । এইই উনিক নাম গুলোকে আইডেন্টিফায়ার বলে ।</td>
    </tr>
    <tr>
      <td>ভ্যারিয়েবল  স্কোপ </td>
      <td>
        ভ্যারিয়েবল টা যেই ফাংশনে আছে, পুরা ফাংশনে এই ভ্যারিয়েবলের একটাই স্কোপ থাকে। তাই যদি কোন if বা লুপের মধ্যে কোন ভ্যারিয়েবল তৈরি করেন তাহলে পুরা ফাংশনেই সেটার স্কোপ থাকবে। <br>
        1. স্কোপ হলো আপনি এক্সেস করতে পারেন এমন ভ্যারিয়েবলের সেট। <br>
        2. আপনি এক্সেস করতে পারেন এমন ভ্যারিয়েবল, অবজেক্ট এবং ফাংশনের সেটকে জাভাস্ক্রিপ্টে স্কোপ বলা হয় । <br>
      </td>
    </tr>
    <tr>
      <td>গ্লোবাল ভ্যারিয়েবল</td>
      <td>
        1. ফাংশনের বাইরে যে ভ্যারিয়েবলকে ডিক্লেয়ার করা হয় । <br>
        2. সকল স্ক্রিপ্ট এবং ফাংশন একে এক্সেস করতে পারে। <br>
        3. গ্লোবাল ভেরিয়েবল যে কোন স্ক্রিপ্ট বা ফাংশনে এক্সেস করা যাবে। <br>
      </td>
    </tr>
    <tr>
      <td>স্বয়ংক্রিয়ভাবে গ্লোবাল</td>
      <td>
            1.যদি আপনি কোন ভ্যারিয়েবলকে ডিক্লেয়ার না করে ভ্যালু এসাইন করেন তাহলে ভ্যারিয়েবলটি সয়ংক্রিয়ভাবে একটি গ্লোবাল ভ্যারিয়েবলে পরিণত হবে।প্রয়োজন ছাড়া গ্লোবাল ভ্যারিয়েবল তৈরি না করাই উত্তম। <br>
      </td>
    </tr>
    <tr>
      <td>HTML গ্লোবাল ভ্যারিয়েবল</td>
      <td>
        1. এইচটিএমএলে উইন্ডো অবজেক্ট হচ্ছে গ্লোবাল স্কোপ। সকল গ্লোবাল ভ্যারিয়েবল উইন্ডো অবজেক্টে অন্তর্গত থাকে। <br>
        2. গ্লোবাল ভ্যারিয়েবল(বা ফাংশন) উইন্ডো ভ্যারিয়েবলকে(বা ফাংশন) মুছে ফেলতে পারে। <br>
        3. উইন্ডো অবজেক্টসহ যেকোন ফাংশন, আপনার গ্লোবাল ভ্যারিয়েবল এবং ফাংশনকে মুছে ফেলতে পারে। <br>
      </td>
    </tr>
    <tr>
      <td>ভ্যারিয়েবলের জীবনকাল</td>
      <td>
        1. ভ্যারিয়েবল ডিক্লেয়ার করা হলে এর জীবনকাল শুরু হয়। <br>
        2. ফাংশনের কার্য সম্পন্ন হলে লোকাল ভ্যারিয়েবল মুছে যায়। <br>
        3. ওয়েব পেজ বন্ধ করলে গ্লোবাল ভ্যারিয়েবল মুছে যায়। <br>
      </td>
    </tr>
    <tr>
      <td>ফাংশন আর্গুমেন্ট</td>
      <td>
       ফাংশন আর্গুমেন্ট	ফাংশন আর্গুমেন্ট (প্যারামিটার) ফাংশনের ভিতরে লোকাল ভ্যারিয়েবল হিসেবে কাজ করে ।<br>
      </td>
    </tr>
    <tr>
      <td>সাধারণ নিয়মগুলো</td>
      <td>
        0. নামের মধ্যে অক্ষর (x, y, z), ডিজিট (1, 2, 3),  আন্ডারস্কোর (_) এবং  ডলার($) চিহ্ন থাকতে পারে <br>
        2. নাম অবশ্যই Letter দিয়ে শুরু হবে ।<br>
        3. $ এবং _ দিয়ে ও নাম শুরু হতে পারে ।<br>
        4. নাম গুলো কেসসেন্সিটিভ (যেমন x এবং X দুটি আলাদা ভ্যারিয়েবল) সংরক্ষিত শব্দগুলোকে(যেমন- জাভাস্ক্রিপ্ট কিওয়ার্ড ) কখনো নাম হিসাবে ব্যবহার করা যাবে না ।<br>
        5. জাভাস্ক্রিপ্ট আইডেন্টিফায়ার গুলো কেসসেন্সিটিভ।<br>
        6. same নামে একাধিক বার কোন ভেরিয়েবল var দিয়ে ডিক্লেয়ার করলে তার রিপ্লেস হয়ে যায়,সবার নিচে যে ভ্যারিয়েবেল টা থাকবে তার ভ্যালু  দিয়ে রিপ্লেস হবে ।<br>
      </td>
    </tr>
  </tbody>
</table>


### আইডেন্টিফায়ার

0. আইডেন্টিফায়ার সমূহ হচ্ছে নাম
1. জাভাস্ক্রিপ্টে ভ্যারিয়েবল,কীওয়ার্ড এবং ফাংশনের নাম দেওয়ার জন্য আইডেন্টিফায়ার ব্যবহার করা হয়।
2. .জাভাস্ক্রিপ্টে প্রথম ক্যারেক্টারটি অবশ্যই অক্ষর, আন্ডারস্কোর(_) অথবা ডলার($) চিহ্ন হবে।পরের ক্যারেক্টারগুলো অক্ষর(characters), সংখ্যা, আন্ডারস্কোর(_) অথবা ডলার($) চিহ্ন হতে পারে।
3. প্রথম অক্ষরটি কখনো সংখ্যা হবে না।
4. 

<table>
  <thead align="center">
    <tr border: none;>
      <td><b>Let</b></td>
      <td><b>Const</b></td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        1. আমরা সাধারণত let এবং const ইউজ করব var টিকে আপাতত ইগনোর করবো , এটি একটি Best প্রেক্টিস বলা যেতে পারে । <br>
        2. let দিয়ে যে ভেরিয়েবল ডিক্লেয়ার করা হয় তার ভ্যালু একবারই ডিক্লার করতে হয়, কিন্তু var দিয়ে বারবার ডিক্লেয়ার করা যায় । <br>
        3. let and const যদি ব্লক এর মধ্যে ডিক্লেয়ার করা হয় তাহলে {} ব্লক এর বাইরে থেকে অ্যাক্সেস করা যাবে না, কিন্তু var দিয়ে যে ভেরিয়েবল ডিক্লেয়ার করা হবে তাকে বাইরে থেকে অ্যাক্সেস করা যাবে । <br>
        4. let দিয়ে যে ভেরিয়েবল Defined করা হবে same ভেরিয়েবল কে Redefined - পুনরায় ডিফাইন্ড  করা যাবে না । let x=3, let x=10| <br>
        আলাদা আলাদা ব্লকে Let দিয়ে সেই Defined করা যায় । { let x=2 },{let x=3}| <br>
        5. Re-declear করা যাবেনা but value সেট  করা যাবে । let a, a=5;a=50; Note Allow:- let a,let a;| <br>
        6. Let ফাংশন ছাড়া কারলিব্রাস {} এর মধ্যে ডিক্লেয়ার করতে হবে । <br>
        7. Re-declear করা যাবে না বাট রি এসাইন্ড করা যাবে । <br>
      </td>
      <td>
        0. let and const যদি ব্লক এর মধ্যে ডিক্লেয়ার করা হয় তাহলে {} ব্লক এর বাইরে থেকে অ্যাক্সেস করা যাবে না । <br>
        1. let এর ক্ষেত্রে let a,then values Assign a = 15 এইভাবে করা যাবে , কিন্তু const এর ক্ষেত্রে আলাদা আলাদাভাবে করা যাবে না, ডিক্লারেশন এবং এসাইন্ড একই সাথে করতে হবে const a, const a=20[Note Allowed ] , const a=5;| <br>
        2. var এবং let হোস্টেড হয় কিন্তু var অ্যাসাইন করে undefined করে রাখে কিন্তু let সেটা করেনা আন ডিফারেন্ট সেট করে না । <br>
        3. Re-assigned করা যাবে না রিডিক্লেয়ার করা যাবে না, সেম নামে ডিফারেন্ট স্কূপে ব্যবহার করতে পারবেন । <br>
        4. হোস্টেড হয় কিন্তু undefined সেট করে না । <br>
      </td>
    </tr>
  </tbody>
</table>

1. let, const function scoped হওয়ায় এদের নিজস্ব ফাংশনের বাইরে থেকে অ্যাক্সেস করা যায়না । <br>

function test() {
let a = 1;
const b = 2;
}
console.log(a, b); // ReferenceError

3. আবার এরা block scoped হওয়ায় test ফাংশনের ভেতর থাকার পরেও reference error দিবে । <br>
function test() {
{
let a = 1;
const b = 2;
}
console.log(a, b);
}
test(); // ReferenceError

4. const এ ভ্যালু reassign করা যায়না। কিন্তু const variable এ থাকা object এর ভ্যালু আপডেট করা যায়। কারণ const, ভ্যারিয়েবলের reference\memory address ধরে রাখে, ভ্যালু না। reassign মানে নতুন reference অ্যাসাইন করা। নিচের কোড type error দিবে কারণ এখানে সরাসরি a এর reference পাল্টানোর চেষ্টা করা হয়েছে । <br>

const a = 1;
a = 2; // TypeError

<table>
    <thead align="center">
      <tr border: none;>
        <td><b></b></td>
        <td><b>var</b></td>
        <td><b>Let</b></td>
        <td><b>Const</b></td>
      </tr>
    </thead>
    <tbody>
        <tr>
            <td><b>Stored in Global Scope</b></td>
            <td>Yes</td>
            <td>No</td>
            <td>No</td>
        </tr>
        <tr>
            <td><b>Function Scoped</b></td>
            <td>Yes</td>
            <td>Yes</td>
            <td>Yes</td>
        </tr>
        <tr>
            <td><b>Block Scoped</b></td>
            <td>No</td>
            <td>Yes</td>
            <td>Yes</td>
        </tr>
        <tr>
            <td><b>Reassignable</b></td>
            <td>Yes</td>
            <td>Yes</td>
            <td>No</td>
        </tr>
        <tr>
            <td><b>Redeclarable</b></td>
            <td>Yes</td>
            <td>No</td>
            <td>No</td>
        </tr>
        <tr>
            <td><b>Can be Hoisted</b></td>
            <td>Yes</td>
            <td>No</td>
            <td>No</td>
        </tr>
        <tr>
            <td><b>Hoisting Behavior</b></td>
            <td>Initialized with undefined</td>
            <td>Uninitialized</td>
            <td>Uninitialized</td>
        </tr>
    </tbody>
</table>

### Literals এবং Destructuring

### Template Literals
জাভাস্ক্রিপ্টে  সিঙ্গেল  quote অথবা  ডাবল  quote ব্যবহার করে স্ট্রিং অপারেশন অথবা স্ট্রিং এ কোনো ভ্যারিয়েবলক লিখতে চাইলে ‘+’ সাইন  ব্যবহার করলে যে সমস্যাগুলা তৈরী হয়, সেগুলা সলভ করার জন্য quote এর জায়গায় ` (ব্যাকটিক ওর একিউট সিম্বল) ব্যবহার করাকে, এবং ভ্যারিয়েবলকে ${} এর ভেতর লেখাকে Template Literal বলে । <br>

console.log(`My name is ${name} and I\’m ${age}years old! Currently I\’m a ${work}`);
এখানে খেয়াল করলে আমরা বুঝতে পারবো, Template Literal ব্যাপারটাকে কত সহজ করে ফেলেছে। এমনকি Template Literal এর ভেতরে আমরা Arithmetic অপারেশন এবং মেথডস ও ব্যবহার  করতে পারি । <br>

### Object Literals

জাভাস্ক্রিপ্ট এ কারলি ব্রাকেট এর ভিতর name-value pair করে অবজেক্ট বানানোকে Object Literal বলে। যেমন: 
let jaberInfo = {‘name’: ‘Jaber Al Nahian’, ‘company’: ‘Dhaka Ltd’}  <br>
 
উপরে Object Literal সিনটেক্স ব্যবহার করে একটি Object ডিক্লেয়ার করা হয়েছে।  আর তাছাড়াও অবজেক্ট ডিক্লেরেশন আরো অনেক ভৱে করা যায়, যেমন:  <br>
let newObj = new Object();  <br>
let newObj = {};  <br>


### Assignment Destructuring
যখন আমরা একটি অবজেক্ট  অথবা array এর sub-item গুলোকে অন্য  ভ্যারিয়েবল এ এসাইন করি, তখন যদি আমরা চাই শুধু কিছু নির্দিষ্ট আইটেম কে নিতে, সেটা Destructuring Assignment এর মাধ্যমে সম্ভব। যদিও সেটা ডট অপারেটর দিয়ে করা যায়। যেমন:  <br>

const companyInfo = {  <br>
 name: “Dhaka”,  <br>
 service: “Software Development”,  <br>
 loc: “Dhaka, BD”,  <br>
};
const { name: companyName, loc: companyLocation } = companyInfo;  <br>
console.log(companyName); // Dhaka  <br>
console.log(companyLocation); // Dhaka, BD  <br>

### Text Case
Lowercase – Bangladesh , Uppercase – BANGLADESH , CamelCase – banglaDesh
## ক্যামেল কেস
প্রোগ্রামাররা একের অধিক শব্দকে এক শব্দে লেখার জন্য সচারচর তিনটি পদ্ধতি ব্যবহার করে <br>
<b>হাইফেন(-)</b>   first-name, last-name, master-card, inter-city <br>
<b>আন্ডারস্কোর(_)</b>   first_name, last_name, master_card, inter_city <br>
<b>ক্যামেল কেস</b>  FirstName, LastName, MasterCard, InterCity ক্যামেল কেস ছোট হাতের অক্ষর দিয়ে শুরু হয় firstName, lastName, masterCard, interCity.

### JavaScript Scope

1. এক্সেস করতে পারে এমন ভ্যারিয়েবলের সেট। <br>
2. ফাংশনের মধ্যে স্কোপ পরিবর্তিত হয়। <br>
3. ভ্যারিয়েবলের জীবনকাল <br>
    A.  জাভাস্ক্রিপ্ট ভ্যারিয়েবল ডিক্লেয়ার করা হলে এর জীবনকাল শুরু হয়। <br>
    B. ফাংশনের কার্য সম্পন্ন হলে লোকাল ভ্যারিয়েবল মুছে যায়। <br>
    C. ওয়েব পেজ বন্ধ করলে গ্লোবাল ভ্যারিয়েবল মুছে যায়। <br>



### JavaScript has 3 types of scope:
1.	Block scope
2.	Function scope
3.	Global scope



<table>
  <thead align="center">
    <tr border: none;>
      <td><b>Block scope</b></td>
      <td><b>Function scope</b></td>
      <td><b>Global scope</b></td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
          Let and cosnt block scope <br>
          {   let x = 2;  }
      </td>
      <td>
          0. ফাংশনের মধ্যে যে ভ্যারিয়েবল ডিক্লেয়ার করা হয় তাকে লোকাল ভ্যারিয়েবল বলে। যা শুধুমাত্র ফাংশনের মধ্যেই এক্সেস করা সম্ভব। <br>
          2. যেহেতু লোকাল ভ্যারিয়েবল শুধুমাত্র একটি ফাংশনের ভিতরে এক্সেস করা যায়, তাই একই নামের ভ্যারিয়েবল বিভিন্ন ফাংশনের ভিতরে ব্যবহার করা যেতে পারে। <br>
          3. যখন ফাংশনকে কল করা হয় তখন লোকাল ভ্যারিয়েবল তৈরি হয় এবং ফাংশনের কাজ সম্পন্ন হলে লোকাল ভ্যারিয়েবলগুলো ডিলেট হয়ে যায়। <br>
          ফাংশন আর্গুমেন্ট  (প্যারামিটার ) ফাংশনের ভিতরে লোকাল ভ্যারিয়েবল হিসেবে কাজ করে। <br>
      </td> 
      <td>
          0. var গ্লোবাল স্কোপ , ফাংশন ছাড়া যে কোন জায়গায় var লিখলে এটি গ্লোবাল scope থাকে । <br>
          1. ফাংশনের বাইরে যে ভ্যারিয়েবলকে ডিক্লেয়ার করা হয় তাকে গ্লোবাল ভ্যারিয়েবল বলে। <br>
          3. ওয়েব পেজের সকল স্ক্রিপ্ট এবং ফাংশন একে এক্সেস করতে পারে। <br>
          4. প্রয়োজন ছাড়া গ্লোবাল ভ্যারিয়েবল তৈরি না করাই উত্তম। "Strict Mode" এ স্বয়ংক্রিয়ভাবে গ্লোবাল ভ্যারিয়েবলকে এড়িয়ে চলা হয়। <br>
          গ্লোবাল ভ্যারিয়েবল(বা ফাংশন) উইন্ডো ভ্যারিয়েবলকে(বা ফাংশন) মুছে ফেলতে পারে।
          উইন্ডো অবজেক্টসহ যেকোন ফাংশন, আপনার গ্লোবাল ভ্যারিয়েবল এবং ফাংশনকে মুছে ফেলতে পারে।
      </td>
    </tr>
  </tbody>
</table>

### Data Types in JavaScript

Tow Types of Data
  1. Primitive Data
  2. Composite/complex data types <br>

1. ধরনের ডাটা টাইপ রয়েছে যাদের ভ্যালু নেইঃ - Null, Undefined <br>
2. ধরনের ডাটা টাইপ রয়েছে যাদের মধ্যে ভ্যালু থাকে String, number, boolean, object, function <br>
3. অবজেক্ট 6 ধরনের হয় Object ,Date, Array, String, Number, Boolean <br>
4.

### Primitive Data
	String -   'single quit'Or"Double quit "
	Number- 1,2,45,1.3,3.4, 102,22
	Boolean- True, false
	Undefined, Null, Empty Values

### Composite/complex data types
Object, function, Array, Date ,RegExp


<table>
  <tbody>
    <tr>
      <td>
          typeof "John"                 // Returns "string" <br>
          typeof 3.14                   // Returns "number" <br>
          typeof NaN                    // Returns "number" <br>
          typeof false                  // Returns "boolean" <br>
          typeof [1,2,3,4]              // Returns "object" <br>
          typeof {name:'John', age:34}  // Returns "object" <br>
          typeof new Date()             // Returns "object" <br>
          typeof function () {}         // Returns "function" <br>
          typeof myCar                  // Returns "undefined" * <br>
          typeof null                   // Returns "object" <br>
          NB: javascript এ function এর  type হচ্ছে object কিন্তু typeof() করলে তারা টাইপ function দেখাবে  <br>
          Data Type of typeof : <br>
          1. এটি একটি operator , অপারেটরদের ( + - * / ) কোনো Data type নেই। <br>
          2. typeof() অপারেটর একটি variable নয়।  <br>
          3. typeof অপারেটর সর্বদা একটি স্ট্রিং Return করে । <br>
      </td>
      <td>
          NaN type number <br>
          array type object <br>
          date type object <br>
          null type object <br>
          object type object <br>
          undefined variable type undefined not assigned type undefined
      </td>
    </tr>
  </tbody>
</table>


<table>
  <thead align="center">
    <tr border: none;>
      <td><b>NonePremetive</b></td>
      <td><b>Premetive</b></td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        0. এদের মাঝে মৌলিক পার্থক্য হচ্ছে যে প্রিমিটিভ ডাটা immutable বা অপরি বর্তনীয় এবং নন-প্রিমিটিভ ডাটা mutable বা পরিবর্তনীয়।
        1.প্রমিটিভ ডাটা immutable বা অপরি বর্তনীয় ডাটা টাইপ হিসাবে পরিচিত কারণ এই ডাটা একবার তৈরি হয়ে গেলেএটি পরিবর্তন করার কোন পথ নেই।
        2.প্রিমিটিভ ডাটাটাইপ গুলোএকেঅপরের সাথে তাদের ভ্যালু দ্বারা তুলনা করে।
        3.যখন আমরা কোন প্রিমিটিভ ডাটা টাইপকে অন্য কোন ভেরিয়েবলে অ্যাসাইন করি, তখন তার ভ্যালু কপি হয়ে নতুন ভেরিয়েবলে অ্যাসাইন হয়।
      </td>
      <td>
          1. নন-প্রিমিটিভ ডাটা mutable বা পরিবর্তনীয়।
          2.  একটি অবজেক্ট তৈরি হয়ে যাওয়ার পরে ও অবজেক্টের ভ্যালু পরিবর্তন হতে পারে
          3. যখন কোন নন-প্রিমিটিভ ডাটা তৈরি করি, তখন সেই ডাটার জন্যে মেমোরিতে একটা অ্যাড্রেস তৈরি হয়  এবং সেই অ্যাড্রেসটা কেমনে রেখে কোন এক জায়গায়
          ভ্যালু গুলোকে স্ট্রোর করে রাখে।তার পর আমাদের যখন দরকার পরে তখন সে ঐ অ্যাড্রেস কে কল করে এবং আমাদের ডাটা প্রদান করে।
          4. নন-প্রিমিটিভ বারে ফারেন্স ডাটাগুলো সব সময় তাদের রেফারেন্স পাস করে।যখন আমরা কোন রেফারেন্স ডাটাকে অন্য কোন ভেরিয়েবলে অ্যাসাইন করি, তখন তার রেফারেন্স কপি হয়।মানে arr1 কেযখনআমরা arr2 তে অ্যাসাইন করি তখন তার রেফারেন্স বা অ্যাড্রেসটাকে কপি করে বাম নেরাখেতার ভ্যালুকেনা।তাই দুইটা ভেরিয়েবলের অ্যাড্রেস একই থাকে।তাই যখন আমরা কোন একটি ভেরিয়েবলের ভ্যালু পরিবর্তন করি, তখন দুইটা ভেরিয়েবলের ইভ্যালু পরিবর্তন হয়ে যায়।
      </td>
    </tr>
  </tbody>
</table>

### Type Conversion

1. জাভাস্ক্রিপ্ট ভ্যারিয়েবলকে একটি নতুন ভ্যারিয়েবল এবং অন্য ডাটা টাইপে রূপান্তরিত যায় ,
 ফাংশন ব্যবহার করে , Automatically/স্বয়ংক্রিয়ভাবে জাভাস্ক্রিপ্টের মাধ্যমে <br>

<table>
  <thead align="center">
    <tr border: none;>
      <td><b>Original Value</b></td>
      <td>Converted <b>Number</b></td>
      <td>Converted <b>String</b></td>
      <td>Converted <b>Boolean</b></td>
    </tr>
  </thead>
   <tbody>
      <tr>
          <td>false</td>
          <td>0</td>
          <td>"false"</td>
          <td>false</td>
      </tr>
      <tr>
          <td>true</td>
          <td>1</td>
          <td>"true"</td>
          <td>true</td>
      </tr>
      <tr>
          <td>0</td>
          <td>0</td>
          <td>"0"</td>
          <td>false</td>
      </tr>
      <tr>
          <td>1</td>
          <td>1</td>
          <td>"1"</td>
          <td>true</td>
      </tr>
      <tr>
          <td>"0"</td>
          <td>0</td>
          <td>"0"</td>
          <td>true</td>
      </tr>
      <tr>
          <td>"000"</td>
          <td>0</td>
          <td>"000"</td>
          <td>true</td>
      </tr>
      <tr>
          <td>"1"</td>
          <td>1</td>
          <td>"1"</td>
          <td>true</td>
      </tr>
      <tr>
          <td>NaN</td>
          <td>NaN</td>
          <td>"NaN"</td>
          <td>false</td>
      </tr>
      <tr>
          <td>Infinity</td>
          <td>Infinity</td>
          <td>"Infinity"</td>
          <td>true</td>
      </tr>
      <tr>
          <td>-Infinity</td>
          <td>-Infinity</td>
          <td>"-Infinity"</td>
          <td>true</td>
      </tr>
      <tr>
          <td>""</td>
          <td>0</td>
          <td>""</td>
          <td>false</td>
      </tr>
      <tr>
          <td>"20"</td>
          <td>20</td>
          <td>"20"</td>
          <td>true</td>
      </tr>
      <tr>
          <td>"twenty"</td>
          <td>NaN</td>
          <td>"twenty"</td>
          <td>true</td>
      </tr>
      <tr>
          <td>[]</td>
          <td>0</td>
          <td>""</td>
          <td>true</td>
      </tr>
      <tr>
          <td>[20]</td>
          <td>20</td>
          <td>"20"</td>
          <td>true</td>
      </tr>
      <tr>
          <td>[10,20]</td>
          <td>NaN</td>
          <td>"10,20"</td>
          <td>true</td>
      </tr>
      <tr>
          <td>["twenty"]</td>
          <td>NaN</td>
          <td>"twenty"</td>
          <td>true</td>
      </tr>
      <tr>
          <td>["ten","twenty"]</td>
          <td>NaN</td>
          <td>"ten,twenty"</td>
          <td>true</td>
      </tr>
      <tr>
          <td>function(){}</td>
          <td>NaN</td>
          <td>"function(){}"</td>
          <td>true</td>
      </tr>
  </tbody>
</table>

### String
1. string কে Double Quotation অথাবা Single Quotation এরভিতরেরাখতেপারি var a = "Tasnim"; <br>   
2. যে কোন ডাটা টাইপ এর ডাটা রাখা যায় । <br>
3.স্ট্রিংয়ের মধ্যে বিশেষ অক্ষর ব্যবহার করতে চাইলে আপনাকে ব্যাকস্ল্যাশ(\) ব্যবহার করতে হবেঃ <br>

### String Method
<table>
   <tbody>
      <tr>
        <td>length</td>
        <td>slice()</td>
        <td>substring()</td>
        <td>substr()</td>
        <td>concat()</td>
        <td>padStart()</td>
      </tr>
      <tr>
        <td>replace()</td>
        <td>replaceAll()</td>
        <td>toUpperCase()</td>
        <td>toLowerCase()</td>
        <td>padEnd()</td>
        <td>trim()</td>
      </tr>
      <tr>
        <td>trimStart()</td>
        <td>trimEnd()</td>
        <td>charCodeAt()</td>
        <td>charAt()</td>
        <td>split()</td>
      </tr>
  </tbody>
</table>

### String Search Methods
<table>
   <tbody>
      <tr>
        <td>indexOf()</td>
        <td>lastIndexOf()</td>
        <td>search()</td>
      </tr>
      <tr>
        <td>match()</td>
        <td>matchAll()</td>
        <td>includes()</td>
      </tr>
      <tr>
        <td>startsWith()</td>
        <td>endsWith()</td>
      </tr>
  </tbody>
</table>

### Template Literals
<table>
   <tbody>
      <tr>
        <td>indexOf()</td>
        <td>lastIndexOf()</td>
        <td>search()</td>
      </tr>
      <tr>
        <td>match()</td>
        <td>matchAll()</td>
        <td>includes()</td>
      </tr>
      <tr>
        <td>startsWith()</td>
        <td>endsWith()</td>
      </tr>
  </tbody>
</table>

### String HTML Wrapper Methods
<table>
   <tbody>
      <tr>
        <td>anchor()</td>
        <td>big()</td>
        <td>blink()</td>
        <td>bold()</td>
         <td>link()</td>
      </tr>
      <tr>
        <td>fixed()</td>
        <td>fontcolor()</td>
        <td>fontsize()</td>
        <td>italics()</td>
      </tr>
      <tr>
        <td>small()</td>
        <td>strike()</td>
        <td>sub()</td>
        <td>sup()</td>
      </tr>
  </tbody>
</table>

### Escape Character

 <table>
   <thead align="center">
    <tr border: none;>
        <th><b>Escape Sequence </b></th>
        <th><b>Result </b></th>
        <th~><b>Description </b></th~>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td>\'</td>
            <td>'</td>
            <td>Single quote</td>
        </tr>
        <tr>
            <td>\"</td>
            <td>"</td>
            <td>Double quote</td>
        </tr>
        <tr>
            <td>\\</td>
            <td>\</td>
            <td>Backslash</td>
        </tr>
        <tr>
            <td>\n</td>
            <td>(new line)</td>
            <td>New line</td>
        </tr>
        <tr>
            <td>\r</td>
            <td>(carriage return)</td>
            <td>Carriage return</td>
        </tr>
        <tr>
            <td>\t</td>
            <td>(tab space)</td>
            <td>Tab space</td>
        </tr>
        <tr>
            <td>\b</td>
            <td>(backspace)</td>
            <td>Backspace</td>
        </tr>
        <tr>
            <td>\f</td>
            <td>(form feed)</td>
            <td>Form feed</td>
        </tr>
    </tbody>
</table>

### String Method
1. সকল স্ট্রিং মেথডই একটি নতুন স্ট্রিং রিটার্ন করে। তারা মূল স্ট্রিংকে পরিবর্তন করে না। <br>
2. স্ট্রিং অপরিবর্তনীয়ঃ স্ট্রিংগুলো পরিবর্তন করা যাবে না শুধুমাত্র প্রতিস্থাপন করা যায়। <br>
3. স্ট্রিংকে অ্যারের মত করে এক্সেস করা নিরাপদ নয় , আপনি হয়তো স্ট্রিংকে অ্যারের মত করে এক্সেস করা দেখতে পারেন , যদি আপনি একটি স্ট্রিংকে অ্যারে আকারে পড়তে চান, প্রথমে একে অ্যারেতে রূপান্তর করুন। <br>

<table>
    <thead align="center">
      <tr border: none;>
          <th><b>Method</b></th>
          <th><b>Description </b></th>
      </tr>
    </thead>
    <tbody>
        <tr>
            <td>Length()</td>
            <td>একটি স্ট্রিংয়ের দৈর্ঘ্য নির্ধারন করে। স্ট্রিংটি কয়টি ক্যারেক্টার নিয়ে গঠিত তা রিটার্ন করে।</td>
        </tr>
        <tr>
            <td>charAt()</td>
            <td>স্ট্রিং ক্যারেক্টারকে ভাগ করার দুইটি পদ্ধতি রয়েছেঃ 1. charAt(position) 2. charCodeAt(position) নির্দিষ্ট ইনডেক্স(পজিশনের) ক্যারেক্টারকে রিটার্ন করে।</td>
        </tr>
        <tr>
            <td>charCodeAt()</td>
            <td>নির্দিষ্ট ইনডেক্সের ক্যারেক্টারের ইউনিকোড রিটার্ন করে।</td>
        </tr>
        <tr>
            <td>concat()</td>
            <td>স্ট্রিংকে যুক্ত করে এবং একটি নতুন স্ট্রিং তৈরি করে।</td>
        </tr>
        <tr>
            <td>endsWith()</td>
            <td>একটি স্ট্রিং নির্দিষ্ট স্ট্রিং বা ক্যারেক্টার দিয়ে শেষ হয় কিনা তা চেক করে।</td>
        </tr>
        <tr>
            <td>fromCharCode()</td>
            <td>ইউনিকোড ভ্যালুকে ক্যারেক্টারে পরিনত করে।</td>
        </tr>
        <tr>
            <td>includes()</td>
            <td>একটি স্ট্রিংয়ের মধ্যে নির্দিষ্ট স্ট্রিং বা ক্যারেক্টার আছে কিনা তা চেক করে।</td>
        </tr>
        <tr>
            <td>indexOf()</td>
            <td>একটি স্ট্রিংয়ের মধ্যে নির্দিষ্ট একটি ভ্যালুর প্রথম পজিশন রিটার্ন করে।</td>
        </tr>
        <tr>
            <td>lastIndexOf()</td>
            <td>একটি স্ট্রিংয়ের মধ্যে নির্দিষ্ট একটি ভ্যালুর শেষ পজিশন রিটার্ন করে।</td>
        </tr>
        <tr>
            <td>localeCompare()</td>
            <td>দুইটি স্ট্রিংয়ের মধ্যে তুলনা করে।</td>
        </tr>
        <tr>
            <td>match()</td>
            <td>একটি রেগুলার এক্সপ্রেশনে একটি স্ট্রিং খুজে বের করে এবং রেজাল্ট দেখায়।</td>
        </tr>
        <tr>
            <td>repeat()</td>
            <td>স্ট্রিংকে পরিবর্তন করে না। এটা নতুন একটি স্ট্রিং রিটার্ন করে।</td>
        </tr>
        <tr>
            <td>replace()</td>
            <td>একটি স্ট্রিংয়ের মধ্যে একটি নির্দিষ্ট ভ্যালু অথবা একটি রেগুলার এক্সপ্রেশন খুজে বের করে, তা প্রতিস্থাপন করে এবং যেখানে নির্দিষ্ট ভ্যালু প্রতিস্থাপিত হয়েছে তার একটি নতুন স্ট্রিং তৈরি করে।</td>
        </tr>
        <tr>
            <td>search()</td>
            <td>একটি স্ট্রিংয়ের মধ্য়ে একটি নির্দিষ্ট ভ্যালু অথবা একটি রেগুলার এক্সপ্রেশন খুজে বের করে এবং তার পজিশন রিটার্ন করে।</td>
        </tr>
        <tr>
            <td>slice()</td>
            <td>স্ট্রিংয়ের একটি অংশকে ভাগ করে এবং বিভক্ত অংশটিকে নতুন একটি স্ট্রিংয়ে রিটার্ন করে। মেথডটি দুইটি প্যারামিটার গ্রহন করে: শুরুর অবস্থান(start index) এবং শেষের অবস্থান(end index)।</td>
        </tr>
        <tr>
            <td>split()</td>
            <td>একটি স্ট্রিংকে অ্যারেতে রূপান্তরিত করা যেতে পারে।</td>
        </tr>
        <tr>
            <td>startsWith()</td>
            <td>একটি স্ট্রিং নির্দিষ্ট ক্যারেক্টার দিয়ে শুরু হয়েছে কিনা তা চেক করে।</td>
        </tr>
        <tr>
            <td>substr()</td>
            <td>মেথডটি slice() মেথডের মতই। পার্থক্য হচ্ছে দ্বিতীয় প্যারামিটারটিতে কতটি ক্যারেক্টার ভাগ করতে চান তা উল্লেখ করতে হবে।</td>
        </tr>
        <tr>
            <td>substring()</td>
            <td>মেথডটি slice() মেথডের মতই। পার্থক্য হচ্ছে substring() মেথড ঋনাত্মক ইন্ডেক্স ভ্যালু গ্রহণ করে না।</td>
        </tr>
        <tr>
            <td>toLocaleLowerCase()</td>
            <td>লোকাল হোস্টের উপর ভিত্তিকরে স্ট্রিং কে ছোট হাতের অক্ষরে(lower case) রপান্তর করে।</td>
        </tr>
        <tr>
            <td>toLocaleUpperCase()</td>
            <td>লোকাল হোস্টের উপর ভিত্তিকরে স্ট্রিং কে বড় হাতের অক্ষরে(Upper case) রপান্তর করে।</td>
        </tr>
        <tr>
            <td>toLowerCase()</td>
            <td>একটি স্ট্রিংকে ছোট হাতের অক্ষরে রপান্তর করে।</td>
        </tr>
        <tr>
            <td>toString()</td>
            <td>স্ট্রিং অবজেক্টের ভ্যালু রিটার্ন করে।</td>
        </tr>
        <tr>
            <td>toUpperCase()</td>
            <td>স্ট্রিংকে বড় হাতের অক্ষরে রপান্তর করে।</td>
        </tr>
        <tr>
            <td>trim()</td>
            <td>একটি স্ট্রিংয়ের উভয়দিকের স্পেস মুছে দেয়।</td>
        </tr>
        <tr>
            <td>valueOf()</td>
            <td>একটি স্ট্রিং অবজেক্টের প্রিমিটিভ ভ্যালু রিটার্ন করে।</td>
        </tr>
    </tbody>
</table>


### String HTML Wrapper Methods


<table>
    <thead>
        <tr>
            <th>Method</th>
            <th>Description</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>anchor()</td>
            <td>অ্যাংকর তৈরি করে।</td>
        </tr>
        <tr>
            <td>big()</td>
            <td>স্ট্রিংয়ের ফন্টের আকার বড় করে প্রদর্শন করে।</td>
        </tr>
        <tr>
            <td>blink()</td>
            <td>ব্লিংকিং স্ট্রিং প্রদর্শন করে।</td>
        </tr>
        <tr>
            <td>bold()</td>
            <td>স্ট্রিংকে বোল্ড করে প্রদর্শন করে।</td>
        </tr>
        <tr>
            <td>fixed()</td>
            <td>fixed-pitch ফন্ট ব্যবহার করে একটি স্ট্রিং প্রদর্শন করে।</td>
        </tr>
        <tr>
            <td>fontcolor()</td>
            <td>নির্দিষ্ট কালার ব্যবহার করে স্ট্রিং প্রদর্শন করে।</td>
        </tr>
        <tr>
            <td>fontsize()</td>
            <td>নির্দিষ্ট সাইজ ব্যবহার করে স্ট্রিং প্রদর্শন করে।</td>
        </tr>
        <tr>
            <td>italics()</td>
            <td>স্ট্রিংকে ইতালিক অক্ষরে প্রদর্শন করে।</td>
        </tr>
        <tr>
            <td>link()</td>
            <td>স্ট্রিংকে হাইপার লিংক হিসেবে প্রদর্শন করে।</td>
        </tr>
        <tr>
            <td>small()</td>
            <td>ছোট ফন্ট ব্যবহার করে একটি স্ট্রিং প্রদর্শন করে।</td>
        </tr>
        <tr>
            <td>strike()</td>
            <td>স্ট্রিংয়ের মাঝে দাগ কেটে স্ট্রিংকে প্রদর্শন করে।</td>
        </tr>
        <tr>
            <td>sub()</td>
            <td>স্ট্রিংয়ের টেক্সটকে সাবস্ক্রিপ্ট টেক্সট হিসেবে প্রদর্শন করে।</td>
        </tr>
        <tr>
            <td>sup()</td>
            <td>স্ট্রিংয়ের টেক্সটকে সুপারস্ক্রিপ্ট টেক্সট হিসেবে প্রদর্শন করে।</td>
        </tr>
    </tbody>
</table>

###  Search Methods

0. জাভাস্ক্রিপ্টে স্ট্রিংয়ের অবস্থান শূন্য থেকে গণনা করা হয়।
1. স্ট্রিং-এ ০(শূন্য) হচ্ছে প্রথম অবস্থান, ১ হচ্ছে দ্বিতীয় অবস্থান আর ২ হচ্ছে তৃতীয় অবস্থান এবং এইভাবে চলতে থাকে।
2. উভয় মেথডই দ্বিতীয় একটি প্যারামিটার গ্রহণ করে।

<table>
    <tbody>
      <tr>
          <td>indexOf()</td>
          <td>মেথডটি একটি স্ট্রিংয়ের মধ্যে একটি নির্দিষ্ট টেক্সটের প্রথম অবস্থান রিটার্ন করেঃ</td>
      </tr>
      <tr>
          <td>lastIndexOf()</td>
          <td>মেথডটি একটি স্ট্রিংয়ের মধ্যে একটি নির্দিষ্ট টেক্সটের শেষ অবস্থান রিটার্ন করেঃ যদি টেক্সটটি না পাওয়া যায় indexOf() এবং lastIndexOf() উভয় মেথডই -1 রিটার্ন করে।</td>
      </tr>
      <tr>
          <td>search()</td>
          <td>indexOf() এবং search() উভয় মেথড একই। মেথডটি একটি স্ট্রিংয়ের মধ্যে একটি নির্দিষ্ট ভ্যালু অনুসন্ধান করে। তারা উভয়ই একই আর্গুমেন্ট(arguments) বা প্যারামিটার ভ্যালু গ্রহন করে এবং একই মান রিটার্ন করে। দুটি মেথড একই, কিন্তু search() মেথডটি অনেক বেশি শক্তিশালী।</td>
      </tr>
      <tr>
          <td>Backslash (\)</td>
          <td>স্ট্রিংয়ের মধ্যে বিশেষ অক্ষর ব্যবহার করতে চাইলে আপনাকে ব্যাকস্ল্যাশ(\) ব্যবহার করতে হবে। উদাহরণ: var a = "Welcome To \"Satt\" Academy" (Output: Welcome To "Satt" Academy)</td>
      </tr>
      <tr>
          <td>replace()</td>
          <td>মেথডটি স্ট্রিংয়ের নির্দিষ্ট একটি মানকে অন্য একটি ভ্যালু দ্বারা প্রতিস্থাপন করে। replace() মেথড অনুসন্ধান ভ্যালু হিসাবে রেগুলার এক্সপ্রেশনও নিতে পারে। স্বাভাবিকভাবে replace() মেথডটি অনুসন্ধানকৃত অংশকে প্রথম যেখানে পাবে তাকেই প্রতিস্থাপন করবে। যদি সবগুলোকে প্রতিস্থাপন করতে চান সেক্ষেত্রে রেগুলার এক্সপ্রেশনের g ফ্ল্যাগ(গ্লোবাল সার্চের জন্য) ব্যবহার করতে হবেঃ</td>
      </tr>
      <tr>
          <td>object</td>
          <td>স্ট্রিংকে অবজেক্টে হিসেবেও ডিফাইন করা যায়ঃ var b = new String("Tamim")। স্ট্রিংকে অবজেক্ট হিসাবে তৈরি করবেন না। এটি এক্সিকিউশনের গতিকে ধীর করে দেবে। স্ট্রিং এবং অবজেক্টের সাথে কখনো তুলনা করা ঠিক নয়।</td>
      </tr>
      <tr>
          <td>Dynamic Data Type</td>
          <td>একই ভ্যারিয়েবলে বিভিন্ন টাইপের ডাটা রাখা যায়। উদাহরণ: var a; // এখানে a হচ্ছে undefined; var a = 9; // এখানে a হচ্ছে সংখ্যা (Number); var a = "Tamim"; // এখানে a হচ্ছে স্ট্রিং (String)</td>
      </tr>
      <tr>
          <td>JS Boolean</td>
          <td>বুলিয়ানের শুধুমাত্র দুইটি মান থাকে: true অথবা false। 0 দ্বারা false এবং 1 দ্বারা True নির্দেশিত হয়। বুলিয়ান টাইপ ডাটা বাইনারি ডাটাকে বোঝায়। Condition Test করার জন্য প্রায়ই বুলিয়ান ব্যবহার করা হয়। Boolean() ব্যবহার করে একটি এক্সপ্রেশন সত্য কিনা যাচাই করা যেতে পারে। উদাহরণ: Boolean(4 > 2); Boolean(4); (number ) True; Boolean( {} ); True; Boolean( [] ); True; Boolean(""); false; Boolean("dhjj"); Boolean(NaN);</td>
      </tr>
      <tr>
          <td>typeof Operator</td>
          <td>typeof অপারেটর দ্বারা ভ্যারিয়েবল, অবজেক্ট, ফাংশন, অথবা এক্সপ্রেশন এর টাইপ বুঝায়। উদাহরণ: typeof "Tahmid" // string; typeof 3.14 // number; typeof a // undefined; typeof false // boolean; typeof new Date() // object</td>
      </tr>
      <tr>
          <td>Empty Values</td>
          <td>খালি মান(value) এবং অসজ্ঞায়িত দুটি ভিন্ন জিনিস। খালি স্ট্রিং-এর ভ্যালু এবং টাইপ(type) দুইটাই থাকে। উদাহরণ: var member = " "; // typeof হচ্ছে string</td>
      </tr>
      <tr>
          <td>Null</td>
          <td>জাভাস্ক্রিপ্টে null দ্বারা বুঝায় "কিছুই না"। এটি বোঝায় যে, কোনো অস্তিত্ব নাই। জাভাস্ক্রিপ্টে, null এর ডাটা টাইপ হচ্ছে অবজেক্ট(object)। typeof null // মান হচ্ছে null, কিন্তু টাইপ এখনো অবজেক্ট।</td>
      </tr>
  </tbody>
</table>




<!-- background color

`command`

 -->

<!-- Link and live url && link image

<a href="https://sai4ul.github.io/init-html-starter-kit/componet.html" target="_blank">Live</a>

<img src="./assets/images/Team_preview.png" width="100%" align="left"/> 

-->


<!-- Dot point
    - SCSS Support
 -->

 <!-- Copy plate 
 
    ```.gitconfig

    
    ```
  -->



<!-- Variable

18. single Quotation এবং Double Quotation একসাথে ব্যবহার করার নিয়ম

    "I 'am' porgrammer"
    'I "am" programmer'

19. Single quotation এর ভিতরে Double Quotation  লেখা
    var = '  "Hellow" mister ';
    var = '  //Hellow mister ';
20. কয়টা ক্যারেকটার আছে স্ট্রিং এজানতে হলে length প্রোপার্টি ব্যবহার করুন "hello".length
     -->
