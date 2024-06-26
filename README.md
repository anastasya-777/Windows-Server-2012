# Windows-Server-2012
### Функционал системы
#### Из главных особенностей Windows Server 2012 представители Microsoft особо выделяют пулы накопителей и значительно расширенные возможности фирменного гипервизора [Hyper-V] для обслуживания виртуальных машин. В частности, была показана работа виртуальных серверов Hyper-V на 32 виртуальных процессорах и 120 Гб оперативной памяти. Теперь Hyper-V в составе Windows Server 2012 может поддерживать до 1 Тб памяти на одну виртуальную машину с одинаковой ценой лицензии для любых виртуальных машин – это значительный шаг вперед по сравнению со схемой лицензирования VMware, которая опирается на число используемых процессоров и поддерживает не более 12 ядер на одну лицензию. Кроме того, Hyper-V сможет поддерживать виртуальные диски размером до 64 Тб.
#### Также представители Microsoft обращают внимание на возможности виртуализации сетей в Windows Server 2012, которые позволяют обслуживать несколько виртуальных сетей на одном наборе оборудования. Эти виртуальные сети могут использовать одни и те же IP-адреса, сохраняя полную изоляцию друг от друга. Также была показана миграция работающей виртуальной машины с одной машины на другую по Ethernet-сети без общих накопителей или сетевых ресурсов с помощью встроенной утилиты Server Manager из комплекта Windows Server 2012.
#### В новом выпуске Windows Server нет опций Enterprise и Small Business Server, но присутствуют четыре новых версии, которые в ближайшее время будут поставляться в RTM-релизе.
#### По официальной информации Microsoft от 5 июля, Windows Server 2012 будет представлен в четырех вариантах, два из которых будут лицензироваться покупателям по числу процессоров.
#### Четыре ассортиментные позиции (SKU) продукта включают версии Foundation (предназначена только для OEM-производителей аппаратуры), Essentials, Standard и Datacenter. Версия Essentials ориентирована на малый и средний бизнес с ограничением в 25 пользователей. Вверху линейки находятся версии Standard и Datacenter. Ранее поставлявшаяся Windows Server Enterprise исключена из набора предлагаемых опций.

![image](https://github.com/anastasya-777/Windows-Server-2012/assets/152620467/b430d2ec-1508-47a3-986c-01aa9138f5f8)

- Публичные сервисы Microsoft Azure Services: категории сервисов, предоставление вычислительных мощностей в аренду (Compute Services), сервисы хранения (Data Services) и службы приложений (App Services).
- Сервисы по созданию частных инфраструктур виртуализации на базе продуктов семейства System Center 2012 R2, включая такие компоненты как: App Controller, Virtual Machine Manager, Operations Manager, -Configuration Manager, Service Manager, Orchestrator, Data Protection Manager и Azure Pack.
- Сервисы платформы Windows Server 2012 R2, включая следующие технологии и составляющие: Storage Spaces, Data Deduplication, Resilient File System, SMB Transparent Failover, Storage Quality of Service, Generation 2 Virtual Machines, Online VHDX Resize, Enhanced Session Mode, Live Migration, Failover Clustering, Cluster Shared Volumes, Scale-Out File Server, Shared Virtual Hard Disks, Hyper-V Extensible Switch, Remote Desktop Services, SMB Direct, SMB Multi-channel и NIC Teaming.
  
 ###  Datacenter — содержит все функциональные возможности. Предназначена для крупных организаций, широко использующих виртуализацию. Позволяет работу неограниченного числа виртуальных машин. Лицензируется по количеству процессоров + CAL (Client access license, лицензия на клиентский доступ). Одна лицензия Datacenter покрывает до двух физических процессоров;
### Standart — содержит все те-же возможности что и Datacenter, однако позволяет запуск не более двух виртуальных машин. Предназначена для организаций, в которых мало или совсем не используется виртуализация. Лицензируется по количеству процессоров + CAL. Одна лицензия Standart покрывает до двух физических процессоров на сервере. Также при необходимости можно увеличить разрешенное количество запускаемых виртуальных машин путем назначения серверу дополнительных лицензий (каждая лицензия Standart разрешает запуск двух виртуальных машин);
### Essential — имеет ограниченный функционал. Предназначена для небольших организаций (до 25 человек). Не позволяет запуск виртуальных машин. Лицензируется на сервер и может использоваться на серверах с одним или двумя процессорами. Лицензия Essential не требует покупки клиентских лицензий CAL и разрешает подключение до 25 пользователей. Редакция Essentials может быть запущена в физической или виртуальной среде (или то, или другое);
### Foundation — самая ограниченная редакция. Предназначена для организаций с количеством сотрудников не более 15 человек. Не позволяет запуск виртуальных машин. Может использоваться только на однопроцессорных серверах и поставляется только вместе с серверами. Foundation не требует покупки клиентских лицензий CAL и разрешает подключение до 15 пользователей. Редакция Foundation не может быть запущена в виртуальной среде.
![image](https://github.com/anastasya-777/Windows-Server-2012/assets/152620467/e63f3589-55f9-46f7-8084-04564f2218de)


И для полноты картины сравнительный обзор основных ролей сервера для каждой редакции.


![image](https://github.com/anastasya-777/Windows-Server-2012/assets/152620467/b4f8f820-3da8-4c05-a883-5ef03c04cc87)

1. Редакция Windows Server 2012 Standard. Включает в себя все роли и компоненты, доступные для платформы Windows Server 2012, поддерживает до 64 процессорных разъемов, до 4 Тбайт оперативной памяти и предусматривает две лицензии для виртуальных машин.
2. Редакция Windows Server 2012 Datacenter. Включает все роли и компоненты, доступные для платформы Windows Server 2012, поддерживает до 64 процессорных разъемов, до 640 ядер процессоров и до 4 Тбайт оперативной памяти. Предусматривает неограниченное количество лицензий для запуска виртуальных машин на этом же оборудовании.
3. Редакция Windows Server 2012 Foundation. Поставляется только вместе с серверным аппаратным обеспечением, поддерживает 15 пользователей; сервер не может быть включен в домен. Поддерживает один процессор, 32 Гбайт оперативной памяти и только часть служебных ролей сервера.
4. Windows Server 2012 Essentials. Служит в качестве замены редакции Small Business Server в предыдущих версиях. Не может запускать роль Hyper-V, участвовать в формировании отказоустойчивого кластера, устанавливаться в режиме ядра server core или быть сервером служб удаленных рабочих столов remote desktop services. Поддерживает подключение до 25 пользователей и 50 устройств, два процессора и 64 Гбайт оперативной памяти. Сервер с этой редакцией должен быть основным (root) сервером в домене.
5. Microsoft Hyper-V Server 2012. Автономная редакция Hyper-V для виртуальных машин без пользовательского интерфейса. Не требует лицензии для хостовой операционной системы, виртуальные машины при этом лицензируются как обычно. Поддерживает 64 процессорных разъема и 4 Tбайт оперативной памяти. Может подключаться к домену. Не поддерживает другие роли Windows Server 2012.
6. Windows Storage Server 2012 Workgroup. Поставляется только вместе с аппаратным обеспечением. Система хранения начального уровня. Поддерживает до 50 пользователей, один процессор и 32 Гбайт оперативной памяти. Возможно подключение к домену.
7. Windows Storage Server 2012 Standard. Поддерживает 64 процессора, но лицензируется с шагом в два. Поддерживает 4 Tбайт оперативной памяти. Включает две лицензии на виртуальные машины. Предполагает включение в домен. Поддерживает некоторые роли, например DNS и DHCP Server, но не поддерживает: Active Directory Domain Services (AD DS), Active Directory Certificate Services (AD CS) и Active Directory Federation Services (AD FS).
8. Windows MultiPoint Server 2012 Standard. Предусматривает доступ нескольких пользователей к одному хостовому компьютеру напрямую, при этом каждый из них использует свою мышь, клавиатуру и монитор. Поддерживает один процессор, 32 Гбайт оперативной памяти и максимум 12 сессий. Поддерживает некоторые роли, например DNS и DHCP Server roles, но не поддерживает AD DS, AD CS и AD FS. Включение в домен невозможно.
9. Windows MultiPoint Server 2012 Premium. Поддерживает доступ нескольких пользователей к одному хостовому компьютеру напрямую, при этом каждый работает со своей мышью, клавиатурой и монитором. Поддерживает 2 процессора, 4 Тбайт оперативной памяти и максимум 22 сессии. Предполагается использование некоторых ролей, например DNS и DHCP Server; не поддерживаются AD DS, AD CS и AD FS. Допускается подключение к домену.
Требования к аппаратной части Windows Server 2012 зависят от количества ролей и пользователей, подключающихся к серверу. Каждая роль и каждый установленный компонент, в свою очередь, увеличивают общую нагрузку на жесткий диск, процессор, память. При установке Windows Server 2012 в виртуальной среде требования к аппаратной части не меняются, установка возможна на платформу виртуализации Hyper-V, а также на некоторые платформы сторонних разработчиков. Минимальные требования к аппаратному обеспечению представлены в таблице.


![image](https://github.com/anastasya-777/Windows-Server-2012/assets/152620467/53dab914-b26b-4fe8-9bcf-3cdc95cfaa13)


#### При рассмотрении вопроса об обновлении или миграции на Windows Server 2012 следует учитывать особенности, описанные ниже.
### Установка через обновление
#### При установке методом обновления сохраняются файлы, настройки и приложения, установленные на исходном сервере. Вы выполняете обновление в случае, если хотите продолжать использовать то же самое серверное оборудование. Вы можете обновить имеющуюся версию до Windows Server 2012 только с x64 версий Windows Server 2003, Windows Server 2003 R2, Windows Server 2008 и Windows Server 2008 R2.
### Установка посредством миграции
#### Используйте миграцию, когда вы хотите перейти от x86 версии Windows Server 2003, Windows Server 2003 R2 или Windows Server 2008. При миграции можно задействовать компонент Windows Server Migration Tools, входящий в состав Windows Server 2012 для переноса файлов и настроек с компьютеров, работающих под управлением Windows Server 2003, Windows Server 2003 R2, Windows Server 2008, Windows Server 2008 R2.
#### Кроме представленных выше редакций Windows Server 2012 поддерживает установку в режимеServer Core (минимальный вариант установки Windows Server 2012). При этом работа с сервером осуществляется из командной строки либо с удаленного компьютера, с помощью установленных средств администрирования. Подобный подход имеет ряд преимуществ.
##### -Поскольку сервер в режиме Server Core имеет меньшее количество компонентов, он требует меньшего количества обновлений, что сокращает время обслуживания сервера системными администраторами.
##### -Набор функций минимален, требуется меньшее количество оперативной памяти и меньше места на диске.
##### -Меньшее количество приложений сокращает площадь атаки на сервер.
#### Возможны два варианта установки Server Core. Первый — стандартный вариант установки. По умолчанию все графические инструменты администрирования находятся в состоянии «Удалены» (Removed). Управление осуществляется локально, только из командной строки, либо путем подключения с удаленной системы с помощью графических средств. Вы можете преобразовать Server Core до полной версии Windows Server 2012 с графическими инструментами администрирования только при наличии всех файлов установки.
#### Второй вариант — установка в режиме Server Core с инструментами управления. Этот вариант также известен как Server Core-Full Server. Данная редакция работает подобно Windows Server 2012 с графическими инструментами управления. При этом все графические компоненты уже скопированы на диск, но не установлены. Вы можете конвертировать Server Core-Full Server до Windows Server 2012 без дополнительных файлов установки.
### Пробежимся по установке
#### Обычная установка Windows Server 2012 (если вы ее осуществляете без использования файла ответов) включает следующие шаги.
1. Подключение к источнику установки. При этом возможны варианты:
- начать установку с DVD-ROM;
- начать установку с диска USB;
- произвести загрузку по сети (PXE boot), после чего подключиться к серверу WDS и начать установку.
2. На первой странице Windows Setup Wizard необходимо выбрать:
- язык установки;
- формат времени и валюты;
- раскладку и методы ввода.
3. На второй странице мастера Windows Setup Wizard следует выбрать вариант «Установить» (Install now). Также на этой странице вы можете выбрать вариант «Восстановить» (Repair Your Computer). Эту возможность следует выбирать в том случае, если вы не можете загрузить уже установленную версию Windows Server 2012.
4. На странице выбора версии операционной системы указывается версия для установки. По умолчанию задан режим Server Core.
5. На странице лицензионного соглашения необходимо ознакомиться с ним и принять для продолжения установки.
6. На странице выбора типа установки доступны следующие варианты:
- обновление (Upgrade); выбирайте этот вариант, если требуется выполнить обновление до Windows Server 2012 с уже установленной версии Windows Server;
- Custom; выбирайте этот вариант, если нужно выполнить новую установку.
7. На странице выбора места для установки укажите диск, на который необходимо произвести установку. На данном этапе вы можете отформатировать диск, разбить его на разделы, создать диск VHD для установки операционной системы на него. После нажатия кнопки «Далее» начнется процесс копирования файлов, и компьютер будет несколько раз перезагружен. Время установки в первую очередь зависит от аппаратных характеристик компьютера.
8. На странице настроек Settings необходимо ввести пароль для локальной учетной записи администратора, после чего вы сможете выполнить регистрацию в системе для выполнения дополнительных настроек.
### От ядра
#### Одной из новых функций Windows Server 2012 является возможность перехода от версии Core к полноценной версии с графическим интерфейсом без переустановки всей операционной системы. Для этого потребуется выполнить следующие действия:
- создать папку для монтирования образа. Для этого в командной строке выполним команду mkdir c:\mount
- смонтировать образ полной версии Windows Server 2012 — dism.exe /mount-image /ImageFile:d:\sources\install.wim /Index:4 /Mountdir:c:\mount /readonly
- импортировать графические модули, выполнив следующие команды:
- PowerShell.exe
- Import-Module ServerManagerInstall-WindowsFeature -IncludeAllSubfeature User-Interfaces-Infra -Source:c:\mount\windows\
и далее выполнить перезагрузку — Shutdown /r /t 5
#### После проведения этой процедуры вы получите полноценную версию Windows Server 2012 с графическими инструментами управления (см. экран).

![image](https://github.com/anastasya-777/Windows-Server-2012/assets/152620467/10fa26bd-de54-439c-9572-ede7d291e4e2)

#### Экран. Окно Windows Server 2012 с графическими инструментами управления.

#### Для обратного преобразования необходимо выполнить следующие команды:

- Powershell.exe
- Import-Module ServerManager
- Uninstall-WindowsFeature User-Interfaces-Infra
- Shutdown /r /t 5.
### Преимущества
- Комплексная платформа виртуализации
- Повышенная масштабируемость и производительность
- Интеграция с публичными облачными сервисами
- Доступ с любого устройства, из любой точки мира
- Полнофункциональная Windows-среда в любой момент
- Повышенная безопасность и защищенность данных
#### Соответствие внутренним стандартам безопасности или требованиям законодательства, а так же необходимость защитить бизнес-критичные или персональные данные от утечки продолжают быть приоритетными для бизнеса и корпоративной ИТ-службы. Одним из ключевых требований для соответствия стандартам и требованиям является контроль того, кто имеет доступ к информации, и возможность получения отчета, кто именно использовал конкретную информацию.
#### Windows Server 2012 помогает быть уверенным в повышенной безопасности данных и соответствии требованиям, предлагая грануляцию доступа к информации и корпоративным ресурсам на основе надежной идентификации и проверки статуса безопасности устройств, а так же за счет упрощенного конфигурирования и администрирования удаленного доступа. С Windows Server 2012 ИТ-специалисты получают более удобные инструменты для контроля доступа к важной информации компании и хранимым персональным данным, которые делают управление авторизацией и аудит доступа более централизованными, гибкими и естественными.
#### Windows Server 2012 предлагает динамичную платформу с разделяемой архитектурой, которая позволяет выйти за пределы традиционной виртуализации и обеспечивает свободу выбора в построении серверной инфраструктуры, будь то собственный ЦОД, частное облако, в том числе и для оказания услуг, или организация взаимодействия с публичными облачными сервисами. Мощь многих серверов, простота одного инструмента. Используя Windows Server 2012, вы сможете создать высокодоступную мультисерверную платформу с высокой степенью автоматизации и простым управлением без значительных финансовых вложений. Любое приложение на любой платформе. Windows Server 2012 — наиболее универсальная, масштабируемая и эластичная платформа для web и приложений. Вы получаете гибкие возможности создания и развертывания приложений, как на собственных ресурсах, так и в облачных сервисах или в любой их комбинации, используя единый набор инструментов. Современный стиль работы. Позволяет легко, удобно и безопасно обеспечить пользователей доступом к привычной рабочей среде независимо от используемого устройства и местоположения.
####  Одним из самых главных преимуществ, является единство платформы для многих приложений и задач. "Server 2012 трансформирует центры обработки данных в единое пространство, поддерживает множество приложений и позволяет работать с данными любого характера". "Платформа открывает новые возможности персонификации информационных технологий. Это единая платформа, как для ЦОД, так и для сервис-провайдера".
#### Среди уникальных возможностей платформы гибкость разработки для различных сред, единый инструмент разработки и управления, интегрированную виртуализацию и целостность платформы данных.


### Ключевые функции Windows Server 2012
#### Следующие функции помогают ИТ-специалистам достичь одной или нескольких целей для обеспечения современного стиля работы:

- Централизованная консоль управления предоставляет единую точку доступа для контроля всех аспектов развертывания удаленных рабочих столов и управления ими.
- Упрощенное развертывание и обновление инфраструктуры виртуальных рабочих столов, как в рамках пулов, так и для персонального использования.
- SMB streaming, который предоставляет для Hyper-V производительность, сравнимую с SAN, но при более низкой стоимости.
- Расширенная функциональность DirectAccess объединена со службой маршрутизации и удаленного доступа (RRAS), и формирует службу унифицированного удаленного доступа. Это сочетание позволяет использовать DirectAccess и VPN совместно. Так же применена упрощенная модель развертывания DirectAccess, ориентация на ActiveDirectory.
- Улучшения в функционале BranchCache: упрощенная модель развертывания, управляемость, и масштабируемость на несколько серверов, которые делают его готовым к использованию вместе с облачными средами.
- RemoteFX для WAN теперь дает пользователям удаленных рабочих столов возможность работать в полноценной среде даже через WAN-соединения, включая использование USB-портов, поддержку интерфейсов Aero и 3D,
- Возможности мультимедиа, а так же использование сенсорного экрана с технологией Multi-touch. А функция RemoteFX Network Auto Detect определяет ширину доступной полосы пропускания между клиентом и сервером, и автоматически оптимизирует работу.
- Персонализация удаленных рабочих столов при помощи поддержки диска пользовательского профиля (User Profile Disk), в котором хранятся персональные настройки пользователя и кэш приложений между подключениями.
- Улучшенная инфраструктура обеспечения безопасности одновременно использует классификацию данных и централизованные политики доступа, а так же позволяет проводить аудит доступа к данным. Так же может применяться высокопроизводительное шифрование - выборочное на основе классификации файлов или полное, на уровне жестких дисков.
- Определение принадлежности устройства пользователю позволяет администраторам определять основные устройства или группы устройств для пользователей или их групп. При их использовании пользователям будут доступны их перемещаемый профиль и перенаправленные папки. При входе с других устройств, доступен будет только локальный профиль, который автоматически удалится после выхода.

