**HLP** <sup><sup>*Hosting Provider*</sup></sup>
-------------
Становясь нашим клиентом, Вы доверяете нам часть своей репутации. Именно поэтому мы не работаем с чужим оборудованием, взятым в аренду. Все наши серверы и оборудование обслуживаются нашими специалистами, поддерживающими его и регулярно осуществляющими мониторинг. Именно это позволяет всегда держать уровень надежности и контроля наших решений – того продукта, за который Вы в итоге платите средства и ожидаете качественного результата. Мы одни из немногих, кто на уровне договора с абонентом гарантирует аптайм и время работы онлайн на уровне не менее 99%. Нам смело можно доверить как небольшие сайты-визитки, так и большие порталы, комплексы игровых серверов, большие высоконагруженные игровые и корпоративные проекты. 

**VDS** <sup><sup>*KVM*</sup></sup>
-------------
**VDS** (*Virtual Dedicated Server*) — услуга хостинга, при которой клиенту выделяется виртуальный сервер целиком с полными административными правами, которые дают возможность установить на сервер любое программное обеспечение. Наши VDS базируются на технологии аппаратной виртуализации, а именно - **Kernel-based Virtual Machine**. KVM позволяет виртуальным машинам использовать немодифицированные образы дисков QEMU, VMware и других, содержащие операционные системы. Каждая виртуальная машина имеет своё собственное виртуальное аппаратное обеспечение: сетевые карты, диск, видеокарту и другие устройства.


**VPS** <sup><sup>*LXC*</sup></sup>
-------------
**VPS** (*Virtual Private Server*) — это виртуальный частный сервер. Технология, на основе которой реализована эта услуга, выглядит следующим образом: есть физический сервер, на котором работает n-ное количество независимых виртуальных серверов. У каждого виртуального сервера имеется своя конфигурация, то есть набор технических характеристик (оперативная память, дисковое пространство, процессор и т.д). Виртуализация происходит за счёт изолированных **LXC** контейнеров. Пользователям выдаётся гостевой доступ, а вариативность образов сборки слегка урезана.


**Shared** <sup><sup>*Docker*</sup></sup>
-------------
**Shared Hosting** (*Виртуальный хостинг*) — это вид хостинга, при котором ресурсы сервера разделены между учетными записями, в каждой из которых может быть размещено несколько игровых серверов или сайтов. При этом на сервере установлено программное обеспечение, необходимое для работы окружения. Для виртуального хостинга характерно наличие как выделенных (дисковое пространство), так и разделяемых с другими пользователями ресурсов (процессорное время, ОЗУ, трафик). Идеальный вариант для небольшого игрового сервера, либо незамысловатого сайта (до 5 тысяч посещений/сутки).

<table align="center">
<thead>
  <tr>
    <th rowspan="2" align="center">План</th>
    <th rowspan="2" align="center">Virt</th>
    <th rowspan="2" align="center">BIOS</th>
    <th rowspan="2" align="center">Root</th>
    <th rowspan="2" align="center">SSH</th>
    <th rowspan="2" align="center">Docker</th>
    <th rowspan="2" align="center">Keitaro</th>
    <th colspan="2" align="center">Debian</th>
    <th colspan="2" align="center">Ubuntu</th>
    <th align="center">CentOS</th>
    <th align="center">FreeBSD</th>
  </tr>
  <tr>
    <th align="center">10</th>
    <th align="center">11</th>
    <th align="center">20.04</th>
    <th align="center">22.04</th>
    <th align="center">7 (x64)</th>
    <th align="center">13.1</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td align="left">VDS</td>
    <td align="center">KVM</td>
    <td align="center">SeaBIOS</td>
    <td align="center">✔️</td>
    <td align="center">✔️</td>
    <td align="center">✔️</td>
    <td align="center">✔️</td>
    <td align="center">✔️</td>
    <td align="center">✔️</td>
    <td align="center">✔️</td>
    <td align="center">✔️</td>
    <td align="center">✔️</td>
    <td align="center">✔️</td>
  </tr>
    <tr>
    <td align="left">VPS</td>
    <td align="center">LXC</td>
    <td align="center">❌</td>
    <td align="center">❌</td>
    <td align="center">✔️</td>
    <td align="center">❌</td>
    <td align="center">❌</td>
    <td align="center">✔️</td>
    <td align="center">✔️</td>
    <td align="center">✔️</td>
    <td align="center">✔️</td>
    <td align="center">✔️</td>
    <td align="center">❌</td>
  </tr>
    <tr>
    <td align="left">Shared</td>
    <td align="center">K8N</td>
    <td align="center">❌</td>
    <td align="center">❌</td>
    <td align="center">❌</td>
    <td align="center">❌</td>
    <td align="center">❌</td>
    <td align="center">❌</td>
    <td align="center">❌</td>
    <td align="center">✔️</td>
    <td align="center">❌</td>
    <td align="center">❌</td>
    <td align="center">❌</td>
  </tr>
</tbody>
</table>
