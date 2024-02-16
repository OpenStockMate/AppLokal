# OpenStockMate
Python ve Django kullanılarak geliştirilmiş özel kullanıma uygun tek kullanıcılı bir envanter uygulamasıdır. Bu uygulama, kullanıcıların envanterlerini yönetmelerine ve takip etmelerine olanak tanır. Tek kullanıcılı için lokal olarak tasarlanmış, özel kullanıma uygun Django altyapısı ile Python dili kullanılarak kodlanmıştır.

## Katkılar
Katkılarınızı memnuniyetle karşılıyoruz. Lütfen önerilerinizi veya hataları GitHub üzerinden bildirin.

## Özellikler
- Ürünlerin eklenmesi, düzenlenmesi ve silinmesi
- Stok takibi
- Ürün kategorileri
- Kullanıcı dostu arayüz

## Kurulum

1. Depoyu klonlayın:
   
3. Sanal bir ortam oluşturun ve bağımlılıkları yükleyin:

cd openstockmate
python -m venv env
**Windows kullanıcıları için: env\Scripts\activate
**
source env/bin/activate 
pip install -r requirements.txt
3. Veritabanını oluşturun ve örnek verileri yükleyin:
python manage.py migrate

5. Sunucuyu başlatın:
python manage.py runserver

7. Tarayıcınızda `http://127.0.0.1:8000` adresine gidin ve uygulamayı görüntüleyin.

## Kullanım

1. Tarayıcınızda `http://127.0.0.1:8000` adresine gidin.
2. Giriş yapın.
3. Ürünlerinizi ekleyin, düzenleyin veya silebilirsiniz.



### Stok Sayfası
![Stok Sayfası](https://github.com/OpenStockMate/DjangoApp/blob/main/homepage.png?raw=true)

## popup 
![Popup](https://github.com/OpenStockMate/DjangoApp/blob/main/popup.png?raw=true)

## modeller
![Models](https://raw.githubusercontent.com/OpenStockMate/DjangoApp/main/new_models.png)

