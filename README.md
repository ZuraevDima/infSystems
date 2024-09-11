# @startuml
left to right direction
actor "Клиент" as fc
rectangle Автомойка{
  usecase "Найти автомойку" as UC1
  usecase "Выбрать дату и время" as UC2
  usecase "Оплатить" as UC3
  usecase "Выбрать услугу" as UC4
  usecase "Отменить запись" as UC5
  usecase "Тех поддержка" as UC6
}

rectangle Оплата as pl{
  usecase "Наличка" as UC7
  usecase "Картой" as UC8
}

fc --> UC1
fc --> UC2
fc --> UC3
fc --> UC4
fc --> UC5
fc --> UC6
UC3 <-- pl
@enduml
