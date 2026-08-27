# Clowns & Relationships — сайт-визитка

Одностраничный самодостаточный сайт программы «The Four Classic Clown Relationships»
(Lisbon Playground · Pedro Fabião, октябрь 2026 — январь 2027).
Фото и стили вшиты внутрь `index.html` — никаких дополнительных файлов не нужно.

## Как опубликовать на GitHub Pages

1. Создай репозиторий (например `clowns-relationships`).
2. Загрузи в него файл `index.html` (кнопка **Add file → Upload files**).
3. Открой **Settings → Pages**.
4. В разделе **Build and deployment → Source** выбери **Deploy from a branch**.
5. Branch: `main`, папка: `/ (root)` → **Save**.
6. Через ~1 минуту сайт будет доступен по адресу:
   `https://<твой-ник>.github.io/clowns-relationships/`

## Свой домен (по желанию, можно позже)

1. **Settings → Pages → Custom domain** — впиши домен, напр. `clowns.lisbonplayground.com`, нажми **Save**.
2. У регистратора домена добавь DNS-запись:
   - поддомен (`clowns.…`): **CNAME** → `<твой-ник>.github.io`
   - «голый» домен (`lisbonplayground.com`): **A**-записи на IP GitHub Pages
     (`185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`)
3. Оставь включённой галочку **Enforce HTTPS** — сертификат GitHub выпустит сам.

## Как обновить текст потом

Просто замени `index.html` в репозитории новой версией — адрес сайта не изменится.
