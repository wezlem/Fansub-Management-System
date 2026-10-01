# Fansub Management System

A private management system designed to help fansub teams track and manage anime episode production workflows through Discord.

The system is designed to organize processes such as translation, editing, and encoding, notify team members about their assigned work, and maintain a history of completed tasks.

## Overview

Preparing an anime episode usually requires multiple people to work on different stages of the process. This system provides a centralized way to track these stages through Discord.

The general workflow is:

**New Episode → Translation → Editing → Encoding → Completion**

Each anime can have its own assigned team, allowing the system to keep track of who is responsible for each stage.

When a new episode is detected, the corresponding workflow can be initiated automatically.

## Core Features

* Anime-based team and task management
* Tracking of translation, editing, and encoding stages
* Automatic monitoring of new episodes
* Automatic notifications for relevant team members
* Overview of ongoing tasks
* History of completed work
* Statistics based on completed tasks and processing times
* Manual task management when necessary
* Centralized management through Discord

## How It Works

Each anime can have a designated production team. Team members are responsible for different stages of the episode workflow.

When a new episode is detected, the system identifies the relevant anime and episode and begins tracking the work.

As each stage is completed, the task moves to the next stage and the corresponding team member can be notified.

Once all required stages are completed, the episode is marked as finished and added to the completed history.

## Task Tracking

Each episode is tracked as an individual workflow.

The system can keep track of information such as:

* The anime associated with the task
* The episode being worked on
* The current stage of production
* The responsible team member
* The progress and completion history

This allows the team to keep track of the current state of their work without having to manage the process manually.

## Notification System

One of the main purposes of the system is to ensure that team members are informed when work requires their attention.

When a new task is created or an existing task moves to another stage, the relevant team member can receive a notification through Discord.

This allows the workflow to progress without requiring team members to constantly check the current task status.

## Statistics and History

Completed work is preserved as part of the system's history.

This history can be used to view statistics and processing times related to previous work.

As a result, the system can provide information about both current tasks and previously completed episodes.

## Manual Management

Although much of the workflow can be automated, the system also allows tasks to be managed manually when necessary.

These capabilities are intended for situations where the normal automated workflow requires intervention or a task needs to be handled separately.

## Privacy

This project is intended for use by a specific fansub team.

The source code, internal implementation, data structures, and other technical details are not included in the public documentation.

This documentation only describes the general purpose and user-visible workflow of the system.

## Limitations

The system was designed around a specific workflow and source structure. Compatibility with other workflows, teams, or data sources is therefore not guaranteed.

Certain special cases may also require manual intervention.

## Project Status

**Private Project**

This repository exists solely for documentation purposes. The actual source code and internal components of the project are not included in this repository.

---

# Fansub Yönetim Sistemi

Discord üzerinden fansub ekiplerinin anime bölüm süreçlerini takip etmesini ve yönetmesini sağlayan özel bir yönetim sistemidir.

Sistem; çeviri, redakte ve encode gibi aşamaların düzenli şekilde takip edilmesini, ekip üyelerinin görevlerden haberdar edilmesini ve tamamlanan çalışmaların geçmişinin tutulmasını amaçlar.

## Genel Bakış

Fansub çalışmalarında bir bölümün yayınlanmasına kadar birden fazla kişinin farklı aşamalarda çalışması gerekir. Bu sistem, bu sürecin Discord üzerinden merkezi şekilde takip edilmesini sağlar.

Temel süreç genel olarak:

**Yeni bölüm → Çeviri → Redakte → Encode → Tamamlanma**

şeklinde ilerler.

Her anime için ilgili ekip üyeleri belirlenebilir ve yeni bir bölüm tespit edildiğinde çalışma süreci otomatik olarak başlatılabilir.

## Temel Özellikler

* Anime bazında ekip ve görev takibi
* Çeviri, redakte ve encode süreçlerinin takibi
* Yeni bölümlerin otomatik olarak takip edilmesi
* İlgili ekip üyelerine otomatik bildirim gönderilmesi
* Devam eden çalışmaların görüntülenebilmesi
* Tamamlanan çalışmaların geçmişinin tutulması
* Çalışma süreleri ve geçmiş üzerinden istatistikler
* Gerektiğinde görevlerin manuel olarak yönetilebilmesi
* Discord üzerinden merkezi yönetim

## Çalışma Mantığı

Sistemde her anime için bir çalışma ekibi bulunur. Bu ekip, bölümün hazırlanması sırasında farklı aşamalardan sorumlu kişilerden oluşur.

Yeni bir bölüm bulunduğunda sistem ilgili animeyi ve bölüm bilgisini takip eder. Çalışma sırasıyla ilgili ekip üyelerine aktarılır.

Bir aşama tamamlandığında sonraki aşamadan sorumlu kişi bilgilendirilir. Böylece bölümün hangi aşamada olduğu ve sıradaki işlemin ne olduğu takip edilebilir.

Süreç tamamlandığında bölüm tamamlanmış olarak geçmişe aktarılır.

## Görev Takibi

Her bölüm kendi çalışma süreci içerisinde takip edilir.

Görevler üzerinden:

* Hangi animeye ait olduğu
* Hangi bölüm üzerinde çalışıldığı
* Hangi aşamada bulunduğu
* Görevden sorumlu kişinin kim olduğu
* Çalışmanın ne zaman başladığı ve tamamlandığı

gibi bilgiler takip edilebilir.

Bu yapı sayesinde ekip içerisindeki bölüm durumunun ayrıca manuel olarak takip edilmesine gerek kalmaz.

## Bildirim Sistemi

Sistemin önemli amaçlarından biri, ekip üyelerinin kendilerine düşen işlerden zamanında haberdar edilmesidir.

Yeni bir çalışma başladığında veya mevcut çalışma bir sonraki aşamaya geçtiğinde ilgili kişiye Discord üzerinden bildirim gönderilebilir.

Böylece ekip üyelerinin sürekli olarak görev durumunu kontrol etmesine gerek kalmadan süreç takip edilebilir.

## İstatistik ve Geçmiş

Tamamlanan çalışmalar geçmişte tutulur.

Bu geçmiş üzerinden ekip çalışmalarına ilişkin çeşitli istatistikler ve süre bilgileri görüntülenebilir.

Böylece yalnızca mevcut görevler değil, daha önce tamamlanmış çalışmalar da takip edilebilir.

## Manuel Yönetim

Otomatik süreçlerin yanında gerektiğinde görevlerin manuel olarak yönetilmesine de olanak sağlanır.

Bu özellikler özellikle otomatik sürecin dışında kalan veya özel olarak müdahale edilmesi gereken durumlarda kullanılmak üzere tasarlanmıştır.

## Gizlilik

Bu proje, belirli bir fansub ekibinin kullanımına yönelik özel bir sistemdir.

Kaynak kodu, sistemin iç çalışma yapısı, veri yapısı ve uygulamaya ilişkin teknik ayrıntılar kamuya açık bir dokümantasyon kapsamında sunulmaz.

Bu dokümantasyon yalnızca sistemin genel amacını ve kullanıcı açısından görülebilen çalışma mantığını açıklamaktadır.

## Sınırlamalar

Sistem belirli bir çalışma düzeni ve kaynak yapısı dikkate alınarak geliştirilmiştir. Bu nedenle farklı çalışma modellerine veya farklı veri kaynaklarına doğrudan uyumlu olması garanti edilmez.

Ayrıca bazı özel durumlarda manuel müdahale gerekebilir.

## Proje Durumu

**Özel proje / Private Project**

Bu repository yalnızca dokümantasyon amacıyla oluşturulmuştur. Projenin asıl kaynak kodu ve dahili bileşenleri bu repository içerisinde bulunmaz.