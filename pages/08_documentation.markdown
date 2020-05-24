---
layout: page
title: Документація
permalink: /documentation/
---

# Документація по проекту
{: style="text-align: center;"}

## Схема БД
{: style="text-align: center;"}
![database schema]({{site.site_url}}/assets/img/schema.png)


## Entities
* **CourseEntity** - збергаігає данні про сам предмет
* **EmployeeEntity** - зберігає дані про працівника навчального закладу
* **PersonEntity** - збергає особисті данні учасника системи
* **Responsibility** - зв'язує курс та працівників
* **StudentEntity** - збергігає специфічні данні для студентів

## Java EE beans
* **CourseBean** - слугує для додавання працівників до курсу та пошуку курсів в БД
* **EmployeeBean** - слугує для отримання працівників з БД
* **EntityGeneratorBean** - слугує для генерації початкових даних
* **StudentBean** - слугує для отримання студентів з БД, а також додавання чи видалення їх з курсів

## JSF beans
* **CourseEmployee** - слугує для роботи між курсами та працівниками
* **EntityGenerator** - слугує для виклику методів генерації даних
* **Subject** - слугує для отримання даних предмету
* **SubjectStudent** - слугує для роботи між курсами та студентами

## Залежності проекту
* **Java EE API** - реалізація платформи Java EE
* **Eclipse Link** - ORM для роботи з БД, реалізує Java EE JPA специфікацію
* **Primefaces** - бібліотека візуальних компонентів
* **Faker** - бібліотека для генерації фейкових даних
