# Домашнее задание к занятию 2. «Применение принципов IaaC в работе с виртуальными машинами» - Пугач Евгений.


---

## `Задание 1`

### Ответ:

1. Применение на практике IaaC паттернов позволяет ускорить процесс разработки, снизить  
трудозатраты на поиск и устранение дефектов, организовать непрерывную поставку продукта.  
Основные преимущества применения IaaC паттернов:  
— принцип CI предполагает постоянное слияние рабочих веток в общую основную ветку разработки  
  и частую автоматизированную сборку проекта и запуск тестов, позволяет избавить разработчиков  
  от ручных действий и выявлять проблемы на этапе пересборки.  
— принцип CD (delivery) позволяет отправлять соответствующие требованиям доработки небольшими  
  партиями по нажатию кнопки, в случае обнаружения дефектов можно легко откатиться до предыдущей  
  стабильной версии.  
— принцип CD (deployment) предполагает полную автоматизацию непрерывного развёртывания доработок,  
  при этом релиз в production всё ещё находится под ручным управлением, что способствует  
  минимизации бизнес-рисков.  
Преимуществом является возможность один раз описав инфраструктуру, многократно её воспроизводить,  
производить развёртывание идентичных сред для тестирования, разработки, масштабирования при  
необходимости. Также автоматизация рутинных действий приводит к снижению трудозатрат на их  
выполнение, как следствие повышается скорость разработки, выявления и устранения дефектов,  
за счёт более раннего их обнаружения и тестирования на этапе сборки. Автоматизация поставки  
позволяет сократить время от этапа разработки до внедрения. Паттерны IaaC позволяют  
стандартизировать развёртывание инфраструктуры, что снижает вероятность появления ошибок и  
дефектов, связанных с человеческим фактором.

2. Основополагающим принципом IaaC является идемпотентность. Идемпотентность обеспечивает  
идентичный результат при повторном и последующих выполнениях каких-либо операций.

---

## `Задание 2`

### Ответ:


1. Ansible выгодно отличается от других систем управления конфигурациями тем, что реализован  
как open source решение, не требует установки агентов на клиентах, использует SSH соединение,  
имеет низкий порог входа, осуществляет поддержку декларативного и императивного подхода, описание  
конфигурации осуществляется в довольно удобном и понятном формате YAML, поддерживает широкий набор  
модулей, позволяющих управлять конфигурацией как ОС, так и различным ПО и сетевым оборудованием.  
Также имеется публичный репозиторий Ansible Galaxy, в котором размещается огромное количество  
готовых ролей Ansible. В сети можно найти много примеров использования и подробную документацию.

2. Основная разница между методами push и pull заключается в том, кто инициирует изменения  
на гостевой машине.  

На мой взгляд, более надёжным методом работы систем конфигурации является push, который позволяет  
избежать ситуации, когда десятки или сотни гостевых машин начинают одновременно запрашивать изменения  
с мастер-сервера, так же метод push позволяет проконтролировать доставку изменений и результат  
применения.

---

## `Задание 3`

- VirtualBox

![Скриншот 1](https://github.com/PugachEV72/Images/blob/master/2023-05-26_00-31-14.png)

- Vagrant

![Скриншот 2](https://github.com/PugachEV72/Images/blob/master/2023-05-26_00-32-03.png)

- Terraform

![Скриншот 3](https://github.com/PugachEV72/Images/blob/master/2023-05-26_00-32-22.png)

- Ansible

![Скриншот 4](https://github.com/PugachEV72/Images/blob/master/2023-05-26_00-33-33.png)

---

### Дополнительные задания (со звездочкой*)

## `Задание 4`

![Скриншот 5](https://github.com/PugachEV72/Images/blob/master/2023-05-27_00-36-52.png)

![Скриншот 6](https://github.com/PugachEV72/Images/blob/master/2023-05-27_04-04-34.png)

![Скриншот 7](https://github.com/PugachEV72/Images/blob/master/2023-05-27_04-05-09.png)

![Скриншот 8](https://github.com/PugachEV72/Images/blob/master/2023-05-27_04-06-01.png)

---
