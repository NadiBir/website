---
title: "Основные группы сообщества"
date: 2023-1-09T00:19:20-08:00
---

# Сообщество Akash Network

Доброго пожаловать в сообщество Akash Network!

Это отправная точка для присоединения к Akash Network и участия в ее создании — внесение кода, написание документации, тестирование функций продукта и сообщение об ошибках, организация встреч, предложение идей для новых функций и многое другое.

## Знакомство

- Информация о типах общественных групп размещена ниже этого документа.
- Полный список текущих групп сообщества Akash Network смотри здесь: [community/cg-list](cg-list)
- Информация о нашей продуктовой стратегии и системе определения приоритетов расположена здесь: [community/product-strategy](product-strategy)
- Cписок проектов, над которыми работают или находятся на рассмотрении, смотри здесь: [community/project-list](projects-list)

## Начало работы

Сообщество Akash Network приветствует участие членов сообщества с разным уровнем технических знаний и знакомства с Akash. Если вы заинтересованы в участии проекта, сначала прочитайте раздел «Знакомство». Затем присоединяйтесь к нашему discord и обратитесь к таблице ниже, чтобы выбрать начальную точку в зависимости от вашего набора навыков.

| Ваш опыт | Предлагаемая стартовая точка для вклада |
| --- | --- |
| Нетехнический, Никогда не использовал Akash | [Просмотреть документ](https://docs.akash.network/) и попытаться развернуть игру тетрис на Akash. Предложите какие-либо изменения или улучшения в документации, решив проблему в [sig-документации](sig-documentation). |
| Frontend (нода, JS) разработчик, Никогда не использовал Akash | [Просмотреть документ](https://docs.akash.network/) и развернуть предложение. Просмотрите основу кода консоли Akash или Cloudmos Deploy, настройте локальную среду. Просмотрите открытые проблемы для любого проекта, выберите то, что вас интересует (например, простое исправление ошибки), и добавьте комментарий или отправьте PR на рассмотрение. |
| Backend (Go) разработчик, Никогда не использовал Akash | [Просмотреть документ](https://docs.akash.network/) и развернуть приложение на Akash с помощью CLI. Просмотрите основу кода для Akash CLI и Provider Services, настройте локальную среду разработки. Просмотрите открытые проблемы для любой базы кода и прокомментируйте потенциальное решение любой проблемы и / или отправьте PR на рассмотрение. |
| Технический разработчки, Есть опыт построения на Akash | Рассмотрите возможность присоединения к одной из наших групп [SIGs](https://akash.network/community/core-groups/cg-list/). [WGs](https://akash.network/community/core-groups/cg-list/) и написания спецификации для одного из проектов в списке или предложения нового проекта для добавления в  [список проектов](projects-list). |

## Группы сообщества

Группы сообщества Akash Network вдохновлены проектом [Kubernetes](https://github.com/kubernetes/community) и в настоящее время имеют определенную структуру групп. По мере развития нашего сообщества мы, возможно, рассмотрим изменение этой структуры. Все групп ниже открыты, и кто заинтересован, за исключением «Комитетов», в которых есть заранее назначенные члены, могут принять в них участие.

Блок-схема групп сообщества](akash-community-groups-block-diagram.png)

### Группы по интересам (SIGs)

SIG — это вертикально специализированные группы сообщества, которые работают над основополагающими элементами сети Akash, внедряя и поддерживая продукты, определенные рабочими группами, или идеи с более мелкими функциями. **SIG обычно могут участвовать как в определении (спецификации), так и в создании конкретных продуктов и функций. SIG являются постоянными группами в том смысле, что они существуют вечно.**

### Working Groups (WGs)

WGs are horizontally aligned community groups that pursue significantly large cross-cutting initiatives involving multiple SIGs. **WGs do not work on implementing features or projects but will be involved in defining (PRD-style) large projects with multiple components across the entire stack** and potentially involving non-Akash partners and stakeholders as well. **Working groups may be active for days, weeks or months but are generally not considered “persistent” like SIGs.**

### User Groups (UGs)

UGs are for facilitating open communication and discovery of topics that may end up in WGs or SIGs. These may also be groups discussing broad use cases like ML/AI or Big Data. Lastly, these may be things that we don’t prioritize for product development based on our current strategy but still things that people want to discuss.

### Committees

Committees are named sets of people that are chartered to take on sensitive topics. This group is encouraged to be as open as possible while achieving its mission but, because of the nature of the topics discussed, private communications are allowed. Examples of committees include the Steering Committee and things like 'security' or 'code of conduct.'

- #### Steering Committee
  
    The [Steering Committee](committee-steering/README) is a special SIG that periodically evaluates the list of projects, prioritizes/adds/removes items and decides which SIG or WG is best suited to tackle the project. The Steering Committee also regularly meets to incorporate learnings to improve how the Akash Network community operates and will perform conflict resolution as necessary.

### Examples

To see a list of projects being worked on or under consideration see [community/project-list](projects-list)

- - A “wg-gpu” that works on end-to-end execution of what it will take for Akash Network to support GPUs. This may include specifications for changes to Deployments (SDL) and Providers, deciding on what vendors and models of GPUs fit with our customer use cases, figure out the best partnerships for sourcing GPU inventory for those models, decide whether we need to solve bandwidth pricing, running alpha/beta testing, etc.  The GPU-WG's work will potentially result in multiple projects being created for the “Providers-SIG”, the “Deployments-SIG”, the “Economics-SIG” and so on. These SIGs will define a lower-level spec for their specific area (based on the overall high-level spec defined by the GPU-SIG), and implement it.
  
- An “wg-ethereum” that is focused on understanding how Akash Network can be adopted by the Ethereum ecosystem. They would define a strategy that includes: technical requirements for node operators and developers, along with non-technical things like events and Discord communications. These would also result in multiple projects for various SIGs.

- Projects like the “provider microservices split” do not require a working group as they only pertain to the provider's code base and, as such, are just handled by the “sig-provider.”

- Support for Authorized Spend in Console would be handled by the “sig-clients” and does not need a dedicated work group.
