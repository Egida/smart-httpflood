# smart-httpflood
Простой http флуддер(DoS) на Go

This script supports HTTP Version, Cookie and Post Data.
<h4>Поддерживает:</h4>
HTTP, куки, POST запросы
Установка:
Зависит от вашей платформы. Поддерживает Termux и Linux
<b>Termux:</b>
<code>pkg install golang</code>

<b>Manjaro Linux(Arch дистры):</b>
<code>sudo pacman -S go</code>

<b>Kali Linux(Debian дистры, если что Ubuntu к ним относится):</b>
<code>sudo apt install golang</code>

Далее для всех платформ одинаковые команды:
<code>git clone https://github.com/ret7020/smart-httpflood/</code>
<code>cd smart-httpflood</code>
<code>go build</code>

<h4>Использование</h4>

<b>Формат команды:</b>
<code>./StresserUS version=<version> host=<host> domain=<host header> limit=<rs-ip> time=<time> list=<proxies.txt> threads=<threads> mode=GET/POST cookie=<ddos=true> data=<post=true></code>

  Пример команды:
 <code>./StresserUS version=2 host=https://pizza-delivery.com limit=64 time=120 list=proxy.txt threads=1000 mode=GET</code>
