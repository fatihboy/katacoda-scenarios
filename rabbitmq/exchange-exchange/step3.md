# Arayüz üzerinden Binding Oluşturma

Yönetim arayüzünde **Exchanges** segmesine geçiş yapın. **anaExchange** exchange'i açın ve **Bindings** bölümünü açın.

Açılan bölümde **Add binding from this exchange** alanına **To exchange** değerine **personelExchange** yazın. **Routing key** alanına **personel.#.#** değerini yazın ve **Bind** butonuna basın.

Binding bölümünde yeni oluşturduğunuz binding'in olduğunu teyit edin.

Yeniden yönetim arayüzünde **Exchanges** segmesine geçiş yapın. **personelExchange** exchange'i açın ve **Bindings** bölümünü açın.

Açılan bölümde **Add binding from this exchange** alanına **To exchange** değerine **personel-ayrilma-is-emirleri** yazın. **Routing key** alanına **personel.is-emri.ayrilma** değerini yazın ve **Bind** butonuna basın.

Binding bölümünde yeni oluşturduğunuz binding'in olduğunu teyit edin.

Yeniden **Bindings** bölümünü gelin. Açılan bölümde **Add binding from this exchange** alanına **To queue** değerine **personel-baslama-is-emirleri** yazın. **Routing key** alanına **personel.is-emri.baslama** değerini yazın ve **Bind** butonuna basın.

Binding bölümünde yeni oluşturduğunuz binding'in olduğunu teyit edin.

**Continue** butonuna basarak sıradaki adıma geçebilirsiniz.