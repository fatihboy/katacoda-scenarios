# Federation Test'i

**RabbitMQ01** segmesi üzerinden açılan yönetim arayüzüne geçiş yapın. **Exchanges** segmesine geçiş yapın ve **lab.federation.ex**'i açın. **Publish message** bölümünde **Payload** alanına aşağıdaki değeri yazın.

`Enterprisecoding rabbitmq eğitimi örnek federation mesajı`{{copy}}

**Publish message** butonuna basarak mesajı yayınlayın. **Message published.** mesajını aldığınızı teyit edin. **Overview** bölümünde mesaja ilişkin **publish (in)** ve **publish (out)** grafiği oluştuğunu teyit edin.

**Queues** segmesine geçiş yapın. Burada listenen **lab.federation.queue** queue'su için **Messages** grubunda **Ready** başlığı altında bir mesaj olduğun teyit edin.

**RabbitMQ02** segmesi üzerinden açılan yönetim arayüzüne geçiş yapın. **Queues** segmesine geçiş yapın. Burada listenen **lab.federation.queue** queue'su için de **Messages** grubunda **Ready** başlığı altında bir mesaj olduğun teyit edin.

**Continue** butonuna basarak bir sonraki adımına geçebilirsiniz.