Daily Deal — গুগল সার্চ / শেয়ার ব্যানার সেটআপ (একবারের কাজ)

১) GitHub রিপোর (যেখান থেকে GitHub Pages চলে) রুটে এই ফাইলগুলো index.html এর পাশে আপলোড করুন:
   og-image.png, icon-512.png, icon-512-maskable.png, favicon.ico, favicon-48x48.png,
   favicon-96x96.png, favicon-192x192.png, apple-touch-icon.png,
   site.webmanifest, robots.txt, sitemap.xml
   (index.html আগের মতোই replace করুন)

২) Google Search Console (search.google.com/search-console):
   - "URL prefix" দিয়ে https://dailydeal.world/ যোগ করুন
   - "HTML tag" যাচাই বেছে নিন, ট্যাগটি index.html এর <head> এর ভেতর
     "google-site-verification" কমেন্টের জায়গায় বসান (কমেন্ট চিহ্ন <!-- --> সরিয়ে)
     অথবা DNS যাচাই করুন (ডোমেইন প্রোভাইডারে TXT রেকর্ড)
   - Verify চাপুন, তারপর Sitemaps এ "sitemap.xml" সাবমিট করুন
   - URL Inspection এ হোম পেজ দিয়ে "Request indexing" দিন

৩) ফেসবুক/হোয়াটসঅ্যাপ প্রিভিউ রিফ্রেশ: developers.facebook.com/tools/debug এ লিংক দিয়ে "Scrape Again"

৪) ঐচ্ছিক: ফেসবুক পেজের লিংক index.html এর Organization "sameAs" তালিকায় যোগ করুন।

বি.দ্র. গুগল রেজাল্টের লেআউট (লোগো, টাইটেল, বর্ণনা, সাইটলিংক) গুগল নিজে ঠিক করে। ইন্ডেক্স হতে কয়েক দিন থেকে কয়েক সপ্তাহ লাগতে পারে।
