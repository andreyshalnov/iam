# iam — Андрей Шальнов: услуги + CV (RU/EN/中文)

## Структура
| URL | Что |
|---|---|
| `/` | RU — лендинг услуг (закупки Китай→РФ, инспекции, запуск 0→серия) |
| `/en/` | EN — services landing |
| `/cn/` | 中文 — 服务落地页 |
| `/cv/` | RU — полное CV |
| `/en/cv/` | EN — full CV |
| `/cn/cv/` | 中文 — 完整简历 |
| `/sitemap.xml`, `/robots.txt` | SEO |

Переключатель языков — в правом верхнем углу каждой страницы.

## Резервные копии / откат
- Тег `backup/v1.3-pre-business` — сайт до превращения в трёхъязычный (бизнес-версии).
- Zip: локальная копия в /home/z/my-project/download/iam_backup_v1.3_pre_business.zip
- Откат на любую версию: `git checkout <tag> -- . && git commit -m "Rollback to <tag>" && git push`
- Список тегов: `git tag`

## Публикация
Push в main → GitHub Pages. Дизайн: тема Travel-блога abb-des.blogspot.com (белый лист, зубчатый край, фон-небо).
