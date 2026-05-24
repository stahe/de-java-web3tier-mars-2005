# Dreistufige Webarchitekturen und MVC mit Struts, Spring und Java

🔗 **Verwandtes Dokument:**
[Dreistufige Architekturen und MVC mit Struts, Spring und Java](https://stahe.github.io/de-java-web3tier-mars-2005/)

---

## 📘 Einleitung

Dieses Repository enthält den Inhalt von zwei Artikeln, die zwischen März und Juli 2005 auf Developpez.com veröffentlicht wurden.
Sie behandeln Java-Webarchitekturen anhand eines didaktischen und schrittweisen Ansatzes:

1. **Spring IoC**
   Eine Einführung in **Inversion of Control (IoC)**, auch bekannt als **Dependency Injection (DI)**, unter Verwendung des Spring-Frameworks.

2. **Drei Beispiele für dreistufige Webarchitekturen**
   Vorstellung einer vereinfachten Webanwendung zur Verwaltung von Online-Einkäufen, die unter Verwendung einer **MVC-Architektur (Model–View–Controller)** implementiert und in drei technischen Varianten präsentiert wird.

---

## 🏗️ Behandelte Architekturen

Die Beispielanwendung ist nach einer **dreistufigen** Architektur aufgebaut:

* **Präsentationsschicht**
* **Geschäftslogikschicht**
* **Datenzugriffsschicht**

Das **MVC**-Modell wird auf drei verschiedene Arten implementiert:

### 1️⃣ Servlet + JSP

* Ein **Servlet-Controller**
* **JSP-Seiten** für die Ansichten
* Manuelle MVC-Architektur

### 2️⃣ Struts

* MVC-Implementierung basierend auf dem **Struts**-Framework
* Zentralisierte Steuerung über `ActionServlet`
* Deklarative Zuordnung der Aktionen

### 3️⃣ Spring MVC

* Verwendung des **Spring MVC**-Frameworks
* Integration mit dem Spring IoC-Container
* Konfiguration mit Fokus auf Dependency Injection

---

## 🎯 Lernziele

* Das Prinzip der **dreistufigen Architektur** verstehen
* Das **MVC-Modell in einer Java-Webumgebung** beherrschen
* Die **Inversion of Control (IoC)** und die Abhängigkeitsinjektion kennenlernen
* Verschiedene Ansätze zur MVC-Implementierung vergleichen
* Die Vorteile von Frameworks gegenüber einer manuellen Implementierung verstehen

---

## 🧩 Verwendete Technologien
* Java
* Servlet
* JSP
* Struts
* Spring Framework
* Spring MVC
---
## 📚 Zielgruppe
Dieses Material richtet sich an:

* Java-Entwickler, die traditionelle Webarchitekturen verstehen möchten
* Alle, die „manuelles“ MVC und frameworkbasiertes MVC vergleichen möchten

---

## 🏷️ Historischer Kontext

Diese Artikel stammen aus dem Jahr 2005 und spiegeln den damaligen Stand der Java-Webpraktiken wider.

