# Портфолио

Наумов Иван

## Автономный программатор

В рамках дипломного проекта мной разработан автономный программатор (АП) для микроконтроллеров. Устройство позволяет прошивать целевые МК без подключения к ПК (используя образы, сохранённые во внутренней Flash-памяти), а также работает как стандартный отладочный зонд DAPLink при подключении к компьютеру.

Ключевые задачи, решённые в проекте:
- Полный цикл проектирования цифрового и силового тракта в Altium Designer.
- Разработка firmware на C для STM32L433CC (USB MSC/CDC, драйверы SWD, QSPI Flash).
- Проектирование 2-слойной печатной платы с учётом дифференциальных пар (USB 90 Ом).
- Создание 3D-модели корпуса и анализ теплового режима / вибропрочности ПП.
- Изготовление и испытание опытного образца.

### Э3
Разработана схема электрическая принципиальная в Altium Designer. Центральный элемент – STM32L433CC, внешняя QSPI Flash для хранения образов прошивок, интерфейс USB Type-C, BMS для аккумулятора
<img width="1125" height="326" alt="image" src="https://github.com/user-attachments/assets/4825bcbf-ddaa-4f76-b614-2955a84d1acd" />

### ПП
2-слойная ПП класса точности 4. Дифференциальная пара USB с волновым сопротивлением 90 Ом
<img width="600"  alt="image" src="https://github.com/user-attachments/assets/9983a6ba-bd5c-414e-b49a-3aae3ae0c99a" />
<img width="600"  alt="image" src="https://github.com/user-attachments/assets/8cec44a8-fbd5-450a-8614-1063cb8b5fce" />

### Корпус
Корпус состоит из 2 деталей - основание и корпус. В основание впаиваются резьбовые втулки и световоды на этапе производства
<img width="468" height="341" alt="image" src="https://github.com/user-attachments/assets/27496da0-2c71-4111-ae09-ebc1870dd86b" />
<img width="468" height="306" alt="image" src="https://github.com/user-attachments/assets/cb8bb39a-8cf4-46e9-a981-1eab69f75a42" />
<img width="468" height="286" alt="image" src="https://github.com/user-attachments/assets/8d62cc69-1d28-49d9-8d06-c0967d140d91" />

### 3D вид
3D-вид платы с установленными компонентами
<img width="452" height="120" alt="image" src="https://github.com/user-attachments/assets/6e465842-cfd3-4758-a793-81eca2606139" />
<img width="468" height="131" alt="image" src="https://github.com/user-attachments/assets/ae4847e7-2a0b-4016-930a-e4b366c8ee72" />

### Готовое устройство в разобранном виде
<img width="468" height="169" alt="image" src="https://github.com/user-attachments/assets/8f262271-3561-480b-9593-d6d2462be7bf" />
<img width="468" height="159" alt="image" src="https://github.com/user-attachments/assets/056fae57-5d56-46b2-8660-afe4bd014c46" />
<img width="418" height="259" alt="image" src="https://github.com/user-attachments/assets/b0d9d625-8d92-46f4-b8d8-7b438566b95d" />
