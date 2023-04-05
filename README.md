# Что это.

Русский перевод игры Aegean Kai No Shizuku для PC-98. Своего рода ранний японский ответ знаменитому Myst.

# Как установить?

Процесс установки описан на странице [Releases](https://github.com/Svipur/AegeanKaiNoShizukuPC98-RUS/releases). Там же находятся и все нужные файлы.

# Зачем нужен изменённый шрифт?

В стандартном шрифте PC-98 отсутствуют символы кириллицы полуразмерной ширины, из-за чего текст на кириллице смотрится громоздко. В игре присутствует собственный шрифт (файл EGEE24.FNT) - это шрифт размером 24, который используется в других играх Illusion Soft для крупного текста. К сожалению, в отличие от тех игр, где этот шрифт действительно используется (и его можно было бы легко заменить на кириллицу), в этой игре этот файл шрифта не используется ни разу. А код, обращающийся к этому файлу или хотя бы загружающий его в память, отсутствует полностью.
