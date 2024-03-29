# Linux

## Установка и обновления системы Linux. Основы администрирования

### Администрирование - это, если не вдаваться в подробности, поддержка и улучшение работы всего компьютерного и офисного оборудования, периферийных устройств, сетевого подключения и т.д. При администрировании Linux большая часть работы протекает в терминале, поэтому стоит начать с использования базовых утилит.

- Выполненные задания:
    
    - Установка ОС:
        
        * Установи **Ubuntu 20.04 Server LTS** без графического интерфейса. (Используем программу для виртуализации - VirtualBox).
    
    - Создание пользователя:
        
        * Создай пользователя, отличного от пользователя, который создавался при установке. Пользователь должен быть добавлен в группу `adm`.
    
    - Настройка сети ОС:
        
        * Задай название машины вида user-1.
        
        * Установи временную зону, соответствующую твоему текущему местоположению.
        
        * Выведи названия сетевых интерфейсов с помощью консольной команды.
        
        * Определи и выведи на экран внешний ip-адрес шлюза (ip) и внутренний IP-адрес шлюза, он же ip-адрес по умолчанию (gw).
        
        * Задай статичные (заданные вручную, а не полученные от DHCP сервера) настройки ip, gw, dns (используй публичный DNS серверы, например 1.1.1.1 или 8.8.8.8).
        
        * Перезагрузи виртуальную машину. Убедись, что статичные сетевые настройки (ip, gw, dns) соответствуют заданным в предыдущем пункте.

    - Обновление ОС:
        
        * Обнови системные пакеты до последней на момент выполнения задания версии.
    
    - Использование команды **sudo**.

        * Разреши пользователю user-1, выполнять команду sudo.

    - Установка и настройка службы времени:
        
        * Настрой службу автоматической синхронизации времени.
    
    - Установка и использование текстовых редакторов:
        
        * Установи текстовые редакторы **VIM** (+ любые два по желанию **NANO**, **MCEDIT**, **JOE**).
        
        *    Используя каждый из трех выбранных редакторов, создай файл *test_X.txt*, где X -- название редактора, в котором создан файл. Напиши в нём свой никнейм, закрой файл с сохранением изменений.
        
        * Используя каждый из трех выбранных редакторов, открой файл на редактирование, отредактируй файл, заменив никнейм на строку «21 School 21», закрой файл без сохранения изменений.
        
        * Используя каждый из трех выбранных редакторов, отредактируй файл ещё раз (по аналогии с предыдущим пунктом), а затем освой функции поиска по содержимому файла (слово) и замены слова на любое другое.
    
    - Установка и базовая настройка сервиса **SSHD**:
        
        * Установи службу SSHd.
        
        * Добавь автостарт службы при загрузке системы.
        
        * Перенастрой службу SSHd на порт 2022.
        
        * Используя команду ps, покажи наличие процесса sshd. Для этого к команде нужно подобрать ключи.
        
        * Перезагрузи систему.
    
    - Установка и использование утилит **top**, **htop**:
    
    - Использование утилиты **fdisk**:
        
        * Запусти команду fdisk -l.
        
    - Использование утилиты **df**:

        * Запусти команду df.
        
        * Запусти команду df -Th.
    
    - Использование утилиты **du**:
        
        * Запусти команду du.
        
        * Выведи размер папок /home, /var, /var/log (в байтах, в человекочитаемом виде)
        
        * Выведи размер всего содержимого в /var/log (не общее, а каждого вложенного элемента, используя *)
    
    - Установка и использование утилиты **ncdu**:

        * Установи утилиту ncdu.
        
        * Выведи размер папок /home, /var, /var/log.
    
    - Работа с системными журналами:
        
        * Открой для просмотра:
            
            1. /var/log/dmesg
            2. /var/log/syslog
            3. /var/log/auth.log
    
    - Использование планировщика заданий **CRON**:
        
        * Используя планировщик заданий, запусти команду uptime через каждые 2 минуты.
        
        * Удали все задания из планировщика заданий.              