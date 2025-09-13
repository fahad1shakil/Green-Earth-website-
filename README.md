❓1) What is the difference between var, let, and const?
What is the difference between var, let, and const?

var, let, এবং const এর মধ্যে পার্থক্য
var
ES5 পর্যন্ত ব্যবহার হতো।
Function scoped (ফাংশনের ভেতর সীমাবদ্ধ)।
একই নাম দিয়ে একাধিকবার ডিক্লেয়ার করা যায়।
Hoisting হয় (উপরে টেনে নেয়), তবে মান থাকে undefined।

let
ES6 এ এসেছে।
Block scoped ({} এর ভেতর সীমাবদ্ধ)।
একই নাম দিয়ে আবার ডিক্লেয়ার করা যায় না।
Hoisting হয় কিন্তু মান থাকে না (Temporal Dead Zone এ পড়ে)।

const

ES6 এ এসেছে।
Block scoped।
একবার ডিক্লেয়ার করলে পরে পরিবর্তন করা যায় না।
সাধারণত কনস্ট্যান্ট ভ্যালু রাখার জন্য ব্যবহার করা হয়।

❓2) What is the difference between map(), forEach(), and filter()?

map(), forEach(), এবং filter() এর মধ্যে পার্থক্য :
   
forEach()
Array এর প্রতিটি আইটেমের ওপর লুপ চালায়।
নতুন কোনো array রিটার্ন করে না, শুধু কাজ করে।

map()
প্রতিটি আইটেমের ওপর কাজ করে এবং নতুন একটি array রিটার্ন করে।
প্রতিটি উপাদানকে পরিবর্তন করে নতুন array তৈরি করা যায়।

filter()
নির্দিষ্ট শর্ত (condition) মিললে সেই আইটেমগুলোকে নতুন একটি array আকারে রিটার্ন করে।
মূল array অপরিবর্তিত থাকে।

❓3) What are arrow functions in ES6?

Arrow Functions in ES6 :

ES6 এ আসা সংক্ষিপ্ত ফাংশন লেখার একটি নতুন সিনট্যাক্স।
function কীওয়ার্ড ব্যবহার করতে হয় না।
this ভ্যালুকে বাইরের scope থেকে ধরে রাখে।

❓4) How does destructuring assignment work in ES6?
কোনো array বা object থেকে সহজে ভ্যালু আলাদা করে ভেরিয়েবলে রাখা যায়।

❓5) Explain template literals in ES6. How are they different from string concatenation?

ES6 এ `` (backtick) ব্যবহার করে লেখা হয়।
${} দিয়ে ভেরিয়েবল বা এক্সপ্রেশন বসানো যায়।
একাধিক লাইনে লেখা যায়।
Difference with String Concatenation:
আগে + দিয়ে জোড়া দিতে হতো।
Template literals এ সহজে ${variable} ব্যবহার করে লেখা যায়।
