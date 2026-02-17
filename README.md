1) What is the difference between null and undefined?
Ans : Null: ডেভেলপার ম্যানুয়ালি কোনো ভেরিয়েবলকে খালি (empty) বা “no value” হিসেবে সেট করে।
Undefined: কোনো ভেরিয়েবল ডিক্লেয়ার করা হলেও এর মান দেওয়া না হলে এটি স্বয়ংক্রিয়ভাবে undefined হয়।

2) What is the use of the map() function in JavaScript? How is it different from forEach()?
Ans : map(): Array-এর প্রতিটি এলিমেন্টে কাজ করে এবং একটি নতুন Array রিটার্ন করে।
forEach(): Array-এর প্রতিটি এলিমেন্টে কাজ করে কিন্তু কোনো মান রিটার্ন করে না।

3) What is the difference between == and ===?
Ans : == (Equality): মান (value) তুলনা করে, টাইপ কনভার্সন করে।
=== (Strict Equality): মান ও টাইপ দুটোই একই কিনা চেক করে।

4) What is the significance of async/await in fetching API data?
Ans : Async/Await: asynchronous কাজগুলোকে synchronous-এর মতো লেখার সুবিধা দেয়।
এটা ডেটা fetch করার সময় কোডকে readable এবং error handling সহজ করে।

5) Explain the concept of Scope in JavaScript (Global, Function, Block).
Ans : Global Scope: সব জায়গা থেকে access করা যায়।
Function Scope: শুধু সেই function-এর ভিতর থেকে access করা যায়।
Block Scope: {} এর ভিতরের ভেরিয়েবল শুধুমাত্র সেই block-এর মধ্যে valid থাকে (let/const)।
