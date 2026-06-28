
##  DOM API (Document Object Model API) কি?

DOM API (Document Object Model API) হলো ব্রাউজারের দেওয়া methods এবং properties, যেগুলো ব্যবহার করে JavaScript দিয়ে ওয়েবপেজের HTML structure (DOM Tree) কে read, change, add, delete বা control করা যায়।

---

## DOM API কোথায় কাজ করে?

DOM API ব্রাউজারের তৈরি করা **DOM (Document Object Model)** এর উপর কাজ করে।

 অর্থাৎ, HTML পেজ যখন ব্রাউজারে লোড হয়, তখন সেটাকে ব্রাউজার একটি **tree structure (DOM tree)** এ রূপান্তর করে  
এবং DOM API সেই tree কে control করে।

---

##  DOM API কিভাবে JavaScript access করে?

ব্রাউজার একটি global object তৈরি করে যার নাম:

 `window`

এই `window` object এর ভিতরে থাকে:
- DOM API 
- অন্যান্য browser APIs

JavaScript এই `window` object এর মাধ্যমে DOM API ব্যবহার করে।

### উদাহরণ:
```js
window.document
document.querySelector("div")