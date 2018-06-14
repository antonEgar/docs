
Подсистема Формирования отчетов
==================================

Подсистема формирования отчетов (далее по тексту Подсистема ПОФО) предназначена для хранения и аналитической обработки данных.

Подсистема ПОФО обеспечивает информационную поддержку деятельности пользователей Системы, формирование и визуализацию представления информации в табличном и графическом видах, выявление полезных тенденций в развитии туристской деятельности, необходимых для принятия решений.

В Подсистеме ПОФО ИС ЭП предусмотрены следующие функциональные возможности (функции):

* формирование аналитических отчетов;

* создание и сопровождение запросов периодической отчетности;

* формирование статистических данных по туроператорам и другим участникам рынка;

* предоставление доступа к результатам обработки и анализа данных.

Функция «Формирование аналитических отчетов»
*********************************************

В системы отчеты разделены на два виды:

* статические отчеты;

* OLAP отчеты.

В Системе реализована возможность формирования следующих отчетов:

* Отчет «Оперативное состояние туроператоров»;

* Отчет «Статистика по туроператорам»;

* Отчет «Отчет по туроператору»;

* Отчет «Статистика» по туроператору»;

* Отчет «Количество и объем туристических поездок»;

* Отчет «Популярные направления»;

* Отчет «Статистика загрузки ЭП»;

* Отчет «Статистика загрузки ЭП туроператора»;

* Отчет «Статистика загрузки ЭП за период»;

* Отчет «Количетво и объем туристическиъ поезжок между Китаем и Россией» (отчет формируется на основе данных получаемых из СИС Ростуризм);

* Отчет финансовой организации;

* Отчет по выявленным нарушениям;

* Отчет по обработке нарушений;

* Отчет «Активные туроператоры»;

* Отчет «Результаты обработки полученных обращений пользователей».

В качестве инициализации процесса формирования отчета должны использоваться действия пользователей через ПОДИР (например, выбор типа и критериев отчета, и нажатие кнопки «Сформировать отчет»). 

Функция реализует создание новых форм отчетов с использованием конструктора отчетных форм. Все создаваемые отчеты попадают в Реестр отчетов. Реестр отчетов хранит название и описание всех отчетов создаваемых на основе конструктора отчетных форм.

В качестве исходных данных для формирования отчетов используются сведения, хранящиеся в ПОСХД.

Функция также позволяет создание новых форм отчетов с использованием конструктора отчетных форм. 

Функция «Создание и сопровождение запросов периодической отчетности
********************************************************************

Функция создания и сопровождения запросов и периодической отчетности позволяет создать новые формы отчетов с использованием конструктора отчетных форм (шаблонов). Все создаваемые отчетные формы попадают в реестр отчетов с сохранением названия шаблона и параметров его формирования.

Используя созданный шаблон пользователь системы может сформировать запрос на периодическое формирование отчета, указав:

* параметры выборки;

* периодичность формирования отчета;

* адрес электронной почты для получения отчета;

тему отчета – уникальный идентификатор запроса на формирование периодического отчета, позволяющий создать несколько запросов на основе одного шаблона.

Параметры запроса на создание периодических отчетов сохраняются в базе данных системы.

В качестве инициализации процесса формирования отчета используются параметры периодичности формирования соответствующего отчета. Сформированный периодический отчет автоматически отправляется на электронные адреса, указанные в запросе.

В качестве исходных данных для формирования отчетов используются сведения, хранящиеся в Подсистеме сбора и хранения данных.

Параметры запроса на формирование периодического отчета могут быть скорректированы пользователем.

Функция «Формирование статистических данных по туроператорам и другим участникам рынка»
****************************************************************************************

Функция формирования статистических данных по туроператорам и другим участникам рынка позволяет сформировать определенные типы отчетов в различных разрезах на основе запросов пользователей.
В качестве исходных данных для формирования статистических данных по туроператорам и настроенных списков адресов рассылки используются сведения, хранящиеся в Подсистеме сбора и хранения данных.
В качестве инициализации процесса формирования отчета используются действия пользователей через Подсистему информирования и доступа к информационным ресурсам.

Данная функция реализована в виде конструктора отчетов. 

Функция «Предоставление доступа к результатам обработки и анализа данных»
**************************************************************************
Функция предоставления доступа к результатам обработки и анализа данных подразумевает отображение в визуализированной форме отчетов через Подсистему информирования и доступа к информационным ресурсам.
Функция позволяет формировать файлы отчетов в визуализированных формах: таблицы, графические диаграммы.
Функция позволяет формировать файлы экспорта отчетности в следующие форматы электронных документов: CSV или PDF.
Для доступа к функциям подсистемы используются АРМ «Ростуризм», АРМ «Туроператор» и АРМ «Филиал (подразделение)Туроператора».

Отчет «Оперативное состояние туроператоров»
**************************************************************************

Данный отчет является статическим.

В данном отчете осуществляется сортировка по следующим полям:

* Код туроператора;

* Дата Окончания действия финансового обеспечения,

* Размер баланса,

* Доля баланса.

В отчет входят следующие колонки:

* Номер ТО;

* Срок финансовой гарантии – ближайший срок окончания финансовой гарантии ТО;

* ФГ ЕФРТ – размер финансовых гарантий из ЕФРТ;

* Уровень ФО – уровень финансового обеспечения;

* Оплачено – сумма оплат по соответствующим ЭП;

* Размер баланса = Размер финансового обеспечения – Сумма оплат (путевок) всего;

* Доля баланса = Размер баланса / Уровень ФО.

Система включает в отчет всех туроператоров и информацию о их действующих финансовых гарантиях. В случае если у туроператора несколько действующих финансовых гарантий введенных фин.гарантом, данные гарантии суммируются и в колонке «Срок финансовой гарантии» выводится ближайший срок окончания гарантии . В случае если у туроператора нет фин.гарантий введенных фин.гарантом, в колонку Уровень ФО дублируются гарантии из ЕФРТ. В колонке «Оплачено» выводится сумма всех ЭП данного туроператора со статусом «Подтверждена», "Забронирована" и статусом оплаты "Оплачено".

Отчет собирается из куба vw_tour_operators_operational_status

SQL запрос отчета
::

 SELECT sss.tour_operator_id,
    sss.tour_operator_registry_id,
    sss.tour_operator_abbreviated_name,
    sss.financial_security_total_amount_from_registry,
    sss.financial_security_total_amount,
    sss.vouchers_paid_total,
    sss.financial_security_closest_end_date,
    COALESCE(sss.financial_security_total_amount, 0::numeric) - COALESCE(sss.vouchers_paid_total, 0::numeric) AS balance
   FROM ( SELECT ss.tour_operator_id,
            ss.tour_operator_registry_id,
            ss.tour_operator_abbreviated_name,
            sum(fisregistry.amount) AS financial_security_total_amount_from_registry,
            sum(COALESCE(fistotal.amount, 0::bigint) + COALESCE(fisregistry.amount, 0::bigint)) AS financial_security_total_amount,
            ss.vouchers_paid_total,
            ss.financial_security_closest_end_date
           FROM ( SELECT t.id AS tour_operator_id,
                    t.registry_id AS tour_operator_registry_id,
                    t.abbreviated_name AS tour_operator_abbreviated_name,
                    sum(o.cost) AS vouchers_paid_total,
                    fsi.valid_to AS financial_security_closest_end_date
                   FROM tour_operator t
                     LEFT JOIN vouchers v ON t.id = v.tour_operator_id AND (v.voucher_status_id IN ( SELECT voucher_status.id
                           FROM voucher_status
                          WHERE voucher_status.codeiata::text = ANY (ARRAY['CF'::text, 'RD'::text])))
                     LEFT JOIN orders o ON v.order_id = o.id AND o.pay_status = 2
                     LEFT JOIN ( SELECT fsi_1.tour_operator_id,
                            min(fsi_1.valid_to) AS valid_to
                           FROM financial_security_info fsi_1
                          WHERE now() >= fsi_1.valid_from AND now() <= fsi_1.valid_to
                          GROUP BY fsi_1.tour_operator_id) fsi ON fsi.tour_operator_id = t.id
                  GROUP BY t.id, t.registry_id, t.abbreviated_name, fsi.valid_to) ss
             LEFT JOIN financial_security_info fisregistry ON fisregistry.tour_operator_id = ss.tour_operator_id AND now() >= fisregistry.valid_from AND now() <= fisregistry.valid_to AND fisregistry.financial_organization_id IS NULL
             LEFT JOIN financial_security_info fistotal ON fistotal.tour_operator_id = ss.tour_operator_id AND now() >= fistotal.valid_from AND now() <= fistotal.valid_to AND fistotal.financial_organization_id IS NOT NULL
          GROUP BY ss.tour_operator_id, ss.tour_operator_registry_id, ss.tour_operator_abbreviated_name, ss.vouchers_paid_total, ss.financial_security_closest_end_date) sss;



Отчет «Статистика по туроператорам»
**************************************************************************

Данный отчет является OLAP отчетом.

Отчет должен формироваться для выбранного периода времени. В отчет должны включаться туроператоры, количество путевок  за данный период времени, типы путевок. 

Правила отчета сортировки:

* Краткое наименование ТО;

* Тип путевки.

В отчет включаются ЭП всех типов со статусом:

* CF – подтверждена;

* US – использована.

В отчеты должны входить следующие колонки:

* Туроператор;

* Тип путевки;

* Количество путевок.

Отчет собирается из куба vw_statistics_touroperators

SQL запрос отчета
::

SELECT row_number() OVER () AS id,
    tour_operator.id AS touroperator_id,
    tour_operator.abbreviated_name AS touroperator,
    voucher_type.name_rus AS vouchertype,
    c1.code_num AS destination_country,
    c1.short_name_rus AS destination_country_name,
    c2.code_num AS leaving_country,
    count(vouchers.id) AS countvouchers,
    vouchers.created_date::date AS createdate
   FROM vouchers
     LEFT JOIN voucher_type ON vouchers.vouchertype_id = voucher_type.id
     LEFT JOIN tour_operator ON vouchers.tour_operator_id = tour_operator.id
     LEFT JOIN country c1 ON vouchers.destination_country_id = c1.id
     LEFT JOIN country c2 ON vouchers.leaving_country_id = c2.id
  WHERE vouchers.voucher_status_id = 2 OR vouchers.voucher_status_id = 5
  GROUP BY tour_operator.id, tour_operator.abbreviated_name, voucher_type.name_rus, c1.code_num, c1.short_name_rus, c2.code_num, vouchers.created_date;


Отчет «Отчет по туроператору»
**************************************************************************

Данный отчет является OLAP отчетом.

Отчет формируется для выбранного туроператора. В отчет включается информация по сумме путевок со статусом «Подтверждена», "Забронирована" и статусом оплаты "Оплачено" данного туроператора, странам путешествия данных путевок и финансовом обеспечении туроператора. 

В отчет входят следующие колонки:

* Срок гарантии – ближайший срок окончания финансовой гарантии ТО;

* Уровень ФО – уровень финансового обеспечения;

* ФГ ЕФРТ – размер финансовых гарантий из ЕФРТ;

* Размер баланса = Размер финансового обеспечения – Сумма оплат (путевок) всего;

* Доля баланса = Размер баланса / Уровень ФО;

* Страна – страна путешествия ЭП;

* Оплачено – сумма оплат по соответствующим ЭП.

Система включает в отчет выбранного туроператора и информацию о его действующих финансовых гарантиях. В случае если у туроператора несколько действующих финансовых гарантий, данные гарантии суммируются и в колонке «Срок финансовой гарантии» выводится ближайший срок окончания гарантии. В колонке «Оплачено» выводится сумма всех ЭП данного туроператора со статусом «Подтверждена», "Забронирована" и статусом оплаты "Оплачена" по стране путешествия данной строки.

Отчет собирается из куба vw_statistics_touroperators

SQL запрос отчета
::

CREATE OR REPLACE VIEW public.vw_report_for_touroperator AS 
 SELECT row_number() OVER () AS id,
    tour_operator.id AS touroperator_id,
    c1.name_rus AS dstcountry,
    count(v.id) AS vouchercount,
    sum(o.cost) AS cost,
    date_part('year'::text, v.trip_start_date) AS year
   FROM vouchers v
     LEFT JOIN tour_operator ON v.tour_operator_id = tour_operator.id
     LEFT JOIN country c1 ON v.destination_country_id = c1.id
     LEFT JOIN orders o ON v.order_id = o.id
  WHERE (v.voucher_status_id IN ( SELECT voucher_status.id
           FROM voucher_status
          WHERE voucher_status.codeiata::text = ANY (ARRAY['CF'::text, 'RD'::text]))) AND o.pay_status = 2
  GROUP BY (date_part('year'::text, v.trip_start_date)), c1.name_rus, tour_operator.id;

Отчет «Статистика» по туроператору»
**************************************************************************

Данный отчет является OLAP отчетом.

В отчет включаются ЭП всех типов со статусом:

* CF – подтверждена;

* US – использована.

В отчеты должны входить следующие колонки:

* Страна;

* Тип путевки;

* Количество путевок.

Отчет собирается из куба vw_statistics_touroperators

SQL запрос отчета
::

SELECT row_number() OVER () AS id,
    tour_operator.id AS touroperator_id,
    tour_operator.abbreviated_name AS touroperator,
    voucher_type.name_rus AS vouchertype,
    c1.code_num AS destination_country,
    c1.short_name_rus AS destination_country_name,
    c2.code_num AS leaving_country,
    count(vouchers.id) AS countvouchers,
    vouchers.created_date::date AS createdate
   FROM vouchers
     LEFT JOIN voucher_type ON vouchers.vouchertype_id = voucher_type.id
     LEFT JOIN tour_operator ON vouchers.tour_operator_id = tour_operator.id
     LEFT JOIN country c1 ON vouchers.destination_country_id = c1.id
     LEFT JOIN country c2 ON vouchers.leaving_country_id = c2.id
  WHERE vouchers.voucher_status_id = 2 OR vouchers.voucher_status_id = 5
  GROUP BY tour_operator.id, tour_operator.abbreviated_name, voucher_type.name_rus, c1.code_num, c1.short_name_rus, c2.code_num, vouchers.created_date;


Отчет «Количество и объем туристических поездок»
**************************************************************************

Данный отчет является OLAP отчетом.

Система включает в отчет данные по вьехавшим в (выехавшим из) Россию туристам. 

В отчет включаются ЭП всех типов со статусом:

* CF – подтверждена;

* US – использована.

В отчетвходят следующие колонки:

* Страна;

* Тип путевки;

* Количество путевок.

Отчет собирается из куба vw_popdestinationstatistic

SQL запрос отчета
::

SELECT row_number() OVER () AS id,
    s._year AS year,
    s._quarter AS quarter,
    s._month AS month,
    s.src_country,
    s.src_country_code,
    s.dst_country,
    s.dst_country_code,
    count(1) AS cnt,
    s.voucher_type
   FROM ( SELECT date_part('year'::text, v.trip_start_date) AS _year,
            date_part('quarter'::text, v.trip_start_date) AS _quarter,
            date_part('month'::text, v.trip_start_date) AS _month,
            src_country.name_rus,
            src_country.short_name_rus AS src_country,
            src_country.code AS src_country_code,
            dst_country.short_name_rus AS dst_country,
            dst_country.code AS dst_country_code,
            vt.name_rus AS voucher_type
           FROM vouchers v
             LEFT JOIN voucher_type vt ON v.vouchertype_id = vt.id
             LEFT JOIN voucher_status vs ON v.voucher_status_id = vs.id
             LEFT JOIN country src_country ON v.leaving_country_id = src_country.id
             LEFT JOIN country dst_country ON v.destination_country_id = dst_country.id
          WHERE vs.code::text = 'used'::text) s
  GROUP BY s._year, s._quarter, s._month, s.src_country, s.src_country_code, s.dst_country, s.dst_country_code, s.voucher_type;

Отчет «Популярные направления»
**************************************************************************

Отчет формируется для выбранного периода времени. В отчет включаются страны (прибытия или отправления в зависимости от отчета), количество туристов вьехавших(выехавших) в РФ за данный период времени. 

В отчет включаются ЭП всех типов со статусом:

* CF – подтверждена;

* US – использована.

В отчеты входят следующие колонки:

* Страна;

* Тип путевки;

* Количество путевок.

Отчет собирается из куба vw_popdestinationstatistic

SQL запрос отчета
::

SELECT row_number() OVER () AS id,
    s._year AS year,
    s._quarter AS quarter,
    s._month AS month,
    s.src_country,
    s.src_country_code,
    s.dst_country,
    s.dst_country_code,
    count(1) AS cnt,
    s.voucher_type
   FROM ( SELECT date_part('year'::text, v.trip_start_date) AS _year,
            date_part('quarter'::text, v.trip_start_date) AS _quarter,
            date_part('month'::text, v.trip_start_date) AS _month,
            src_country.name_rus,
            src_country.short_name_rus AS src_country,
            src_country.code AS src_country_code,
            dst_country.short_name_rus AS dst_country,
            dst_country.code AS dst_country_code,
            vt.name_rus AS voucher_type
           FROM vouchers v
             LEFT JOIN voucher_type vt ON v.vouchertype_id = vt.id
             LEFT JOIN voucher_status vs ON v.voucher_status_id = vs.id
             LEFT JOIN country src_country ON v.leaving_country_id = src_country.id
             LEFT JOIN country dst_country ON v.destination_country_id = dst_country.id
          WHERE vs.code::text = 'used'::text) s
  GROUP BY s._year, s._quarter, s._month, s.src_country, s.src_country_code, s.dst_country, s.dst_country_code, s.voucher_type;


Отчет «Статистика загрузки ЭП»
**************************************************************************

Отчет формируется для всех путевок. В отчет включается информация о загрузке ЭП туроператорами, включаются успешные и неуспешные попытки за 30 дневный период. 

Система включает в отчет информацию о загрузке туроператорамипутевок за 30 дневный период до момента формирования отчета.

В отчет входят следующие колонки:

* Дата загрузки;

* Всего заявок;

* Успешная загрузка;

* Ошибка загрузки.

Отчет собирается из куба vw_load_voucherstat_period

SQL запрос отчета
::

SELECT row_number() OVER () AS id,
    rh.request_date,
    sum(
        CASE
            WHEN rh.request_status::text = 'SUCCESS'::text THEN 1
            ELSE 0
        END) AS success,
    sum(
        CASE
            WHEN rh.request_status::text = 'ERROR'::text THEN 1
            ELSE 0
        END) AS error,
    count(*) AS total
   FROM request_history rh
  WHERE rh.request_date >= (now() - '30 days'::interval)::date
  GROUP BY rh.request_date;


Отчет «Статистика загрузки ЭП туроператора»
**************************************************************************

Отчет формируется для выбранного туроператора. В отчет включается информация о загрузке ЭП туроператором, должны включаться успешные и неуспешные попытки за 30 дневный период. 

Система включает в отчет информацию о загрузке туроператором путевок за 30 дневный период до момента формирования отчета.

В отчет входят следующие колонки:

* Дата загрузки;

* Всего заявок;

* Успешная загрузка;

* Ошибка загрузки.

Отчет собирается из куба vw_load_voucherstatistic

SQL запрос отчета
::

SELECT row_number() OVER () AS id,
    tour_operator.id AS touroperator_id,
    tour_operator.abbreviated_name AS touroperator,
    tour_operator.registry_id AS touroperator_registry,
    tour_operator.inn AS touroperator_inn,
    ( SELECT count(rh2.id) AS count
           FROM request_history rh2
          WHERE rh2.request_status::text = 'SUCCESS'::text AND rh2.tour_operator_id = tour_operator.id AND rh2.request_date >= (now() - '30 days'::interval)::date) AS success,
    ( SELECT count(rh3.id) AS count
           FROM request_history rh3
          WHERE rh3.request_status::text = 'ERROR'::text AND rh3.tour_operator_id = tour_operator.id AND rh3.request_date >= (now() - '30 days'::interval)::date) AS error,
    count(rh.id) AS total
   FROM request_history rh
     LEFT JOIN tour_operator ON rh.tour_operator_id = tour_operator.id
  WHERE rh.request_date >= (now() - '30 days'::interval)::date
  GROUP BY tour_operator.id;

Отчет «Статистика загрузки ЭП за период»
**************************************************************************

Система включает в отчет информацию о загрузке туроператорами путевок за за выбранный период времени.

В отчет входят следующие колонки:

* Краткое наименование туроператора;

* Количество успушных загрузок;

* Количество ошибок при загрузках;

* Общее количество заявок.

Отчет собирается из куба vw_load_voucherstat_period

SQL запрос отчета
::

SELECT row_number() OVER () AS id,
    tour_operator.id AS touroperator_id,
    tour_operator.abbreviated_name AS touroperator,
    tour_operator.registry_id AS touroperator_registry,
    tour_operator.inn AS touroperator_inn,
    sum(
        CASE
            WHEN rh.request_status::text = 'SUCCESS'::text THEN 1
            ELSE 0
        END) AS success,
    sum(
        CASE
            WHEN rh.request_status::text = 'ERROR'::text THEN 1
            ELSE 0
        END) AS error,
    count(*) AS total,
    rh.request_date
   FROM request_history rh
     LEFT JOIN tour_operator ON rh.tour_operator_id = tour_operator.id
  GROUP BY tour_operator.id, rh.request_date;

Отчет «Количетво и объем туристическиъ поезжок между Китаем и Россией» 
**************************************************************************

Данный отчет формируется на основе данных получаемых из СИС Ростуризм.

Отчет формируется для выбранного периода времени. В отчет включаются регионы, количество путевок, количество туристорв вьехавших(выехавших) в Китай за данный период времени.  

В отчет включаются ЭП всех типов со статусом:

* CF – подтверждена;

* US – использована.

В отчеты должны входить следующие колонки:

* Регион;

* Группа;

* Туристы.

Система включает в отчет данные по вьехавшим(выехавшим из) в Россию туристам из(в) Китая. Данные берутся на основе информация СИС Ростуризм (сущность sis_rostourism_statistics). Последней строкой отчетов являются данные взятые из ИС ЭП (в колонке регион должно указываться «Данные ИС ЭП» в остальных колонках количество туристов и путевок за заданный период).  

Отчет собирается из куба vw_chinastatistic

SQL запрос отчета
::

SELECT row_number() OVER () AS id,
        CASE sis_rostourism_statistics.group_type
            WHEN 1 THEN 1
            ELSE 0
        END AS exit_tour,
        CASE sis_rostourism_statistics.group_type
            WHEN 2 THEN 1
            ELSE 0
        END AS entry_tour,
    sis_rostourism_statistics.region_name AS region,
    sum(sis_rostourism_statistics.groups_count) AS groups,
    sum(sis_rostourism_statistics.members_count) AS tourists,
    sis_rostourism_statistics.date_from::date AS begin_period,
    sis_rostourism_statistics.date_to::date AS end_period
   FROM sis_rostourism_statistics
  GROUP BY sis_rostourism_statistics.group_type, sis_rostourism_statistics.region_name, sis_rostourism_statistics.date_from, sis_rostourism_statistics.date_to
UNION
 SELECT row_number() OVER () AS id,
    1 AS exit_tour,
    0 AS entry_tour,
    'ЭП Россия-Китай'::character varying AS region,
    count(v1.id) AS groups,
    count(vp1.id) AS tourists,
    v1.trip_start_date AS begin_period,
    v1.trip_end_date AS end_period
   FROM vouchers v1
     LEFT JOIN voucher_person vp1 ON v1.id = vp1.id
  WHERE v1.leaving_country_id = 116 AND v1.destination_country_id = 197 AND (v1.voucher_status_id = 2 OR v1.voucher_status_id = 5)
  GROUP BY v1.trip_start_date, v1.trip_end_date
UNION
 SELECT row_number() OVER () AS id,
    0 AS exit_tour,
    1 AS entry_tour,
    'ЭП Китай-Россия'::character varying AS region,
    count(v2.id) AS groups,
    count(vp2.id) AS tourists,
    v2.trip_start_date AS begin_period,
    v2.trip_end_date AS end_period
   FROM vouchers v2
     LEFT JOIN voucher_person vp2 ON v2.id = vp2.id
  WHERE v2.leaving_country_id = 197 AND v2.destination_country_id = 116 AND (v2.voucher_status_id = 2 OR v2.voucher_status_id = 5)
  GROUP BY v2.trip_start_date, v2.trip_end_date;

Отчет финансовой организации
**************************************************************************

Отчет формируется для выбранной финансовой организации и для выбранного периода времени. В отчет включаются гарантии, срок действия которых входит в заданный период 

В отчет входят следующие колонки:

* Номер ТО;

* Наименование ТО;

* Дата начала действия ФО;

* Дата окончания действия ФО;

* Уровень ФО.

Система включает в отчет все финансовые гарантии выданные данной организацией фин.гаранта за выбранный период времени. 

Отчет собирается из куба vw_finorgreport

SQL запрос отчета
::

CREATE OR REPLACE VIEW public.vw_finorgreport AS 
 SELECT row_number() OVER () AS id,
    financial_organization.title AS financial_organization,
    financial_organization.id AS financial_organization_id,
    tour_operator.registry_id AS number_to,
    tour_operator.abbreviated_name AS name_to,
    financial_security_info.amount AS financial_security_amount,
    financial_security_info.valid_from AS start_date,
    financial_security_info.valid_to AS end_date
   FROM tour_operator
     RIGHT JOIN financial_security_info ON tour_operator.id = financial_security_info.tour_operator_id
     LEFT JOIN financial_organization ON financial_organization.id = financial_security_info.financial_organization_id
  WHERE financial_security_info.financial_organization_id IS NOT NULL
  GROUP BY financial_organization.title, financial_organization.id, tour_operator.registry_id, tour_operator.abbreviated_name, financial_security_info.amount, financial_security_info.valid_from, financial_security_info.valid_to;


Отчет по выявленным нарушениям
**************************************************************************

Отчет формируется для выбранного периода времени и выбранного туроператора (турагента). В отчет включаются нарушения (информация о стране, регионе, количестве туристов, типе путевки, количестве нарушений) за данный период времени. 

В отчет входят следующие колонки:

* Страна – страна путешествия путевки, связанной с нарушением

* Тип путевки –тип путевки, связанной с нарушением

* Регион – регион путевки, связанной с нарушением

* Количество туристов связанных с нарушниями;

* Количество нарушений.

Отчет собирается из куба vw_processing_violations

SQL запрос 
::

SELECT row_number() OVER () AS id,
    n.created_date::date AS createdate,
    count(n2.id) AS confirmed,
    count(n3.id) AS not_confirmed,
    count(n4.id) AS sent_violation,
    count(n5.id) AS measure_no_taken,
    count(n6.id) AS amountprocessed
   FROM notice n
     LEFT JOIN notice n2 ON n.id = n2.id AND n2.created_date::date = n.created_date::date AND n2.processed IS NOT NULL AND n2.status = 1
     LEFT JOIN notice n3 ON n.id = n3.id AND n3.created_date::date = n.created_date::date AND n3.processed IS NOT NULL AND n3.status = 0
     LEFT JOIN notice n4 ON n.id = n4.id AND n4.created_date::date = n.created_date::date AND n4.processed IS NOT NULL AND n4.activity = 1
     LEFT JOIN notice n5 ON n.id = n5.id AND n5.created_date::date = n.created_date::date AND n5.processed IS NOT NULL AND n5.activity = 0
     LEFT JOIN notice n6 ON n.id = n6.id AND n6.created_date::date = n.created_date::date AND n6.processed = true
  WHERE n.processed IS NOT NULL
  GROUP BY (n.created_date::date);


Отчет по обработке нарушений
**************************************************************************

Отчет должен формироваться для выбранного периода времени. В отчет должна включаться информация о обработке нарушений (информация о подтверждении, не подтверждении, отправлено уведомление, меры не приняты, обработано) за данный период времени. 

В отчет входят следующие колонки:

* Дата;

* Подтвержденных – подтвержденных нарушений за данный день;

* Не подтвержденных –  не подтвержденных нарушений за данный день;

* Отправлено уведомлений – выполнено действий за данный день;

* Мер не принято – выполнено действий за данный день;

* Обработанных – обработанных нарушений за данный день.

Отчет собирается из куба vw_processing_violations

SQL запрос
::

SELECT row_number() OVER () AS id,
    n.created_date::date AS createdate,
    count(n2.id) AS confirmed,
    count(n3.id) AS not_confirmed,
    count(n4.id) AS sent_violation,
    count(n5.id) AS measure_no_taken,
    count(n6.id) AS amountprocessed
   FROM notice n
     LEFT JOIN notice n2 ON n.id = n2.id AND n2.created_date::date = n.created_date::date AND n2.processed IS NOT NULL AND n2.status = 1
     LEFT JOIN notice n3 ON n.id = n3.id AND n3.created_date::date = n.created_date::date AND n3.processed IS NOT NULL AND n3.status = 0
     LEFT JOIN notice n4 ON n.id = n4.id AND n4.created_date::date = n.created_date::date AND n4.processed IS NOT NULL AND n4.activity = 1
     LEFT JOIN notice n5 ON n.id = n5.id AND n5.created_date::date = n.created_date::date AND n5.processed IS NOT NULL AND n5.activity = 0
     LEFT JOIN notice n6 ON n.id = n6.id AND n6.created_date::date = n.created_date::date AND n6.processed = true
  WHERE n.processed IS NOT NULL
  GROUP BY (n.created_date::date);




