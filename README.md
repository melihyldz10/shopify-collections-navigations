# shopify-collections-navigations
Shopify Collections Navigasyon Button


Shopify dosya yapınızda, Sections veya Snippets klasörüne özel bir dosya ekleyebilirsiniz. Örneğin, Snippets içinde menu-buttons.liquid adında bir dosya oluşturun.

Snippets klasörüne gidin. Eğer Snippets klasörü içinde menu-buttons.liquid yoksa:
	•	Snippets klasörüne sağ tıklayın ve “Add a new snippet” seçeneğiyle menu-buttons adında yeni bir dosya oluşturun.
	•	İçine aşağıdaki kodu ekleyin:

Eğer Sections içinde oluşturduysanız, çağırırken şu şekilde değiştirmeniz gerekir:
{% section 'menu-buttons' %} 
2. collection.liquid İçinde Çağırma
{% render 'menu-buttons' %}


Elbise Menüsünü Shopify’dan Düzenleme
Shopify yönetim panelinde:
	•	Online Store > Navigation sekmesine gidin.
	•	Yeni bir menü oluşturun ve adını elbise-menu yapın.
	•	Etek & Şort ve Eşofman Altı gibi öğeleri ekleyin.
Böylece, elbise koleksiyonunda dinamik olarak istediğiniz butonlar görüntülenecektir.
