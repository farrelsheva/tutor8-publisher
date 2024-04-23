1. How many data your publlsher program will send to the message broker in one run?
5 Kali. setiap pemanggilan methopd publish_event instance crosstownBus

2. The url of: “amqp://guest:guest@localhost:5672” is the same as in the subscriber program, what does it mean?

Kedua URI sama, namun pada kasus publisher akan mengirim messsage ke queue, sedangkan subscriber akan mengambil message dari queue tersebut.

![rabbitmq screenshot](Image-1.png)