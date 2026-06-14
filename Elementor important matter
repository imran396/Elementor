Elementor Layout ও Width সম্পর্কিত গুরুত্বপূর্ণ পর্যবেক্ষণ
১. Elementor Full Width Structure

Elementor-এর Full Width কন্টেইনার সাধারণত পুরো স্ক্রিনের উপলব্ধ প্রস্থ (100%) ব্যবহার করে।

যদি Width = 100% হয়, তাহলে কন্টেইনার পুরো স্ক্রিন জুড়ে বিস্তৃত হবে।
যদি Max Width সেট করা থাকে, তাহলে কন্টেইনার সর্বোচ্চ সেই প্রস্থ পর্যন্ত বড় হবে এবং তার বেশি হবে না।

উদাহরণ:

Width: 100%
Max Width: 1280px

এক্ষেত্রে বড় স্ক্রিনেও কন্টেইনারের প্রস্থ 1280px-এর বেশি হবে না।

২. Elementor Boxed Width Structure

Boxed Layout-এ কন্টেইনারটি একটি বক্সের মতো আচরণ করে।

ভেতরের কনটেন্ট নির্দিষ্ট একটি Max Width-এর মধ্যে সীমাবদ্ধ থাকে।
সাধারণত margin: auto ব্যবহার করে কনটেন্টকে মাঝখানে রাখা হয়।
তবে বাইরের মূল কন্টেইনার (wrapper) অনেক সময় Full Width-এ থাকে।

এ কারণে Boxed Container-এ Background Color দিলে সেটি পুরো স্ক্রিন জুড়ে দেখা যেতে পারে, যদিও ভেতরের কনটেন্ট নির্দিষ্ট প্রস্থের মধ্যে সীমাবদ্ধ থাকে।

৩. একই সাথে Fixed Width এবং Percentage Width ব্যবহার করা সবসময় ভালো Practice নয়

একই Row-এর মধ্যে Fixed Width (px) এবং Percentage Width (%) একসাথে ব্যবহার করলে Overflow হওয়ার সম্ভাবনা থাকে।

উদাহরণ:

Container Width = 1200px

Left Column = 700px
Right Column = 50%

তাহলে:

Left = 700px
Right = 600px (1200-এর 50%)

মোট Width = 1300px

কিন্তু Parent Container-এর Width মাত্র 1200px।

ফলে 100px Overflow হবে।

তাই যতটা সম্ভব Percentage ভিত্তিক Layout ব্যবহার করা ভালো। তবে ছোট আইকন, বাটন বা নির্দিষ্ট সাইজের উপাদানের ক্ষেত্রে Fixed Width ব্যবহার করা যেতে পারে।

৪. কোনো এক পাশের Width স্থির রাখতে চাইলে Flex Settings ব্যবহার করা উচিত

ধরুন বাম পাশের Width সবসময় একই রাখতে হবে।

তাহলে:

Left Side

Flex Grow: 0
Flex Shrink: 0

Right Side

Flex Grow: 1
Flex Shrink: 1

এভাবে Left Side তার নির্ধারিত Width বজায় রাখবে এবং Right Side অবশিষ্ট জায়গা ব্যবহার করবে।

৫. সাধারণভাবে Width 100% রাখা ভালো

বেশিরভাগ ক্ষেত্রে Container-এর Width 100% রাখা উচিত।

যখন Width নিয়ন্ত্রণ করার প্রয়োজন হয়, তখন সরাসরি Width নির্ধারণ না করে Max Width ব্যবহার করা ভালো।

উদাহরণ:

Width: 100%
Max Width: 1280px

এতে ছোট স্ক্রিনে Container ছোট হবে এবং বড় স্ক্রিনে 1280px-এর বেশি হবে না।

৬. Content-এর প্রকৃত সাইজ অনুযায়ী Width রাখতে চাইলে fit-content ব্যবহার করা ভালো

যখন কোনো Element-এর Width তার ভেতরের Content-এর সমান রাখতে চান, তখন fit-content ব্যবহার করা একটি ভালো সমাধান।

উদাহরণ:

width: fit-content;

এক্ষেত্রে Element অপ্রয়োজনীয়ভাবে বড় হবে না এবং Content অনুযায়ী Width গ্রহণ করবে।

সাধারণত Button, Badge, Tag, Label বা ছোট Content Block-এর ক্ষেত্রে fit-content খুবই কার্যকর।
