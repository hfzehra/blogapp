# Blogapp

Django ile kodlanmış bu site yazılımla alakalı bir blog sitesidir. Geliştirilmeye açık bir sitedir. Bu sitede kullanıcılar kendi profillerini oluşturup kendi bloglarını yazıp paylaşabilirler. 

### Proje temelde **2** ana kısımdan oluşur:
- Admin paneli
- Blog paneli 

#### Admin paneli yalnızca yönetici kişilerin giriş yapabildiği paneldir. Bu panelde:
- Blogları sil / güncelle / ekle
- Kullanıcıları görüntüleme 
- Yazılım kategorilerini düzenleme işlemleri yapılabilir.

 Aşağıda uygulamanın kısımları görsel olarak verilmiştir.
 
![Adsız tasarım](https://user-images.githubusercontent.com/64837576/197019834-adc3ba71-41e5-45ca-abb3-936f1e335554.gif)

## İndirilen kod nasıl çalıştırılır ? 

Öncelikle uygulamanın olduğu ![image](https://user-images.githubusercontent.com/64837576/196895472-b4ba0ec2-812c-4049-8928-e5fff6483730.png)
kısmından ;

![image](https://user-images.githubusercontent.com/64837576/196895597-0c75d0cd-5a00-4e17-a1b1-27973b91a2ce.png)

clone kısmını kopyalayın . Daha sonra VS code IDE'sinde projeyi açabilirsiniz.

Terminalden kendinize python için sanal makine oluşturun :


>python -m ven myenv

myenv kısmını istediğiniz gibi adlandırabilirsiniz .

<hr>

#### Sanal makinaya girme (windows için) : 
>myenv\Scripts\activate.bat

#### Sanal makinaya girme (linux için) : 
>source tutoriol-env/bin/activate

Projenin çalışması için projeyle alakalı paketlerin sanal makine içersine yüklemesi gereklidir. Sanal makine dizine girdikten sonra projenin içersinde bulunan requriment.txt dosyası projeye entegre edilmelidir. Aşağıda verilen kod ile bu işlem yapılır .

>pip install -r requirements.txt

Kodunuzu aşağıdaki kod ile çalıştırabilirsiniz:
> python manage.py runserver
