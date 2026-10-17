160+ — GitHub Pages + Supabase starter

ამ ZIP-ში:
- ამოღებულია კატისა და ძაღლის ფოტოები.
- წაშლილია საწყისი/demo პოსტები; ახალი საიტი ცარიელი feed-ით იწყება.
- მთავარ გვერდზე ხარის თავის დეკორაცია არ გამოიყენება.
- დამატებულია შესვლის/რეგისტრაციის/პაროლის აღდგენის UI და Supabase Auth-ის საწყისი კოდი.

მნიშვნელოვანი:
ავტორიზაცია ჯერ არ იმუშავებს, სანამ Supabase პროექტის მონაცემებს ჩასვამ. საერთო პოსტების შენახვა/ფოტო-ვიდეო ატვირთვა ასევე შემდეგ ეტაპზე უნდა დავუკავშიროთ Supabase Database + Storage-ს. მარტო localStorage საერთო საიტისთვის საკმარისი არ არის.

დაყენება:
1. გახსენი index.html და მოძებნე SUPABASE_URL და SUPABASE_ANON_KEY.
2. Supabase-ში: Project Settings > API — დააკოპირე Project URL და anon/public key და ჩასვი ამ ორ ცვლადში.
3. არასოდეს ჩასვა service_role key საჯარო საიტის კოდში.
4. Supabase Authentication > URL Configuration-ში, Site URL და Redirect URLs-ში ჩაწერე გამოქვეყნებული GitHub Pages-ის სრული მისამართი.
5. GitHub-ში ატვირთე ZIP-ის შიგნით არსებული 160plus-final საქაღალდის შიგთავსი (index.html, README.txt და assets საქაღალდე) repository-ის root-ში.

ჯერ კიდევ დასაკავშირებელია:
- Supabase Database-ში საერთო პოსტების ცხრილი და უსაფრთხოების RLS პოლიტიკები.
- Supabase Storage bucket ფოტო/ვიდეოებისთვის და upload policies.
- Duel-ის რიგითობის/ხმების საერთო მონაცემები.
