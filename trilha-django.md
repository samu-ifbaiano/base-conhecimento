
---

# 🚀 **Trilha de Django e Django REST Framework**  

A documentação do Django é bem completa, use-a como base e utilize as *fontes de conhecimento* como materiais alternativos


### 🔹 **1. Fundamentos do Django (6 horas)**  
🔸 O que é Django e como ele funciona?  
🔸 Instalando Django e criando um projeto  
🔸 Estrutura do projeto Django  
🔸 Configuração básica e primeiro app  
🔸 Criando modelos (`models.py`) e aplicando migrações  
🔸 Criando e registrando uma `view` básica  

📌 **Atividade prática:**  
Crie um projeto Django chamado `blog` e adicione um app `posts`.  

🔗 **Fontes de conhecimento:**  
🎥 **Vídeo:** [Crie um projeto completo com Django - TreinaWeb](https://youtu.be/MsUL3Pgofl4?si=dBzZaqztAIb1lIbd)  
📚 **Texto:** 
- [Documentação Django - Introdução](https://docs.djangoproject.com/pt-br/4.2/intro/)
- [Introdução ao Django - GeeksForGeeks](https://www.geeksforgeeks.org/getting-started-with-django/)

---

### 🔹 **2. Trabalhando com Banco de Dados no Django (6 horas)**  
🔸 Criando modelos (`models.py`) e definindo campos  
🔸 Registrando modelos no Django Admin  
🔸 Criando e rodando migrações  
🔸 Trabalhando com o ORM do Django  

📌 **Atividade prática:**  
Crie um modelo `Post` com os campos `titulo`, `conteudo` e `data_criacao`, e exiba os posts no Django Admin.  

🔗 **Fontes de conhecimento:**  
🎥 **Vídeo:** [Python Django Models and Migrations](https://youtu.be/5DW4Ky1Um4o?si=CIrFz9p31TGvmxSS)  
📚 **Texto:** 
- [Django Models - W3Schools](https://www.w3schools.com/django/django_models.php)  
- [Django Models - GeeksForGeeks](https://www.geeksforgeeks.org/django-models/)

---

### 🔹 **3. URLs, Views e Templates (6 horas)**  
🔸 Criando rotas no `urls.py`  
🔸 Criando views e retornando respostas HTTP  
🔸 Templates e Template Tags  
🔸 Trabalhando com formulários no Django  

📌 **Atividade prática:**  
Crie uma view que exiba uma lista de posts na página inicial usando um template.  

🔗 **Fontes de conhecimento:**  

📚 **Texto:** 
- [Django Views - GeeksForGeeks](https://www.geeksforgeeks.org/views-in-django-python/)
- [Django URLs - GeeksForGeeks](https://www.geeksforgeeks.org/django-url-dispatcher-tutorial/)
- [Django templates - GeeksForGeeks](https://www.geeksforgeeks.org/django-templates/)

---

### 🔹 **4. Django REST Framework - Fundamentos (6 horas)**  
🔸 O que é Django REST Framework (DRF)?  
🔸 Criando uma API no Django  
🔸 Serializers e Models  
🔸 Criando rotas de API  

📌 **Atividade prática:**  
Transforme o modelo `Post` em uma API que retorna posts em formato JSON.  

🔗 **Fontes de conhecimento:**  
🎥 **Vídeo:** [Curso de Django REST Framework - UB Social](https://youtube.com/playlist?list=PLnPZ9TE1Tj4BMN4I4Dce6HZ8pXiw99-gq&si=tA0-a9B37_IvJu0B)  
📚 **Texto:** [Django REST Framework - Documentação](https://www.django-rest-framework.org/tutorial/quickstart/)  

---

### 🔹 **5. Autenticação e Permissões no DRF (6 horas)**  
🔸 Criando sistema de login e logout na API  
🔸 Protegendo endpoints com autenticação JWT  
🔸 Criando permissões personalizadas  

📌 **Atividade prática:**  
Crie uma API onde apenas usuários autenticados podem criar posts.  

🔗 **Fontes de conhecimento:**  
🎥 **Vídeo:** 
- [Autenticação e Permissões no DRF - Pedro Impulcetto](https://youtu.be/LFV4MLe0ZzM?si=DfpFuu57p3dpn7F4)
- [Curso de Django API REST: 7.Autenticação via token - UB Social](https://youtu.be/yLnSsHaD2go?si=ZnKc2VPi3cZz-Ufo).


📚 **Texto:** [DRF Authentication - DRF Docs](https://www.django-rest-framework.org/api-guide/authentication/)  

---

### 🎯 **Projeto Final: API de Blog com Django e DRF**  
Crie uma **API REST** para um blog, onde usuários podem:  
✅ Criar, visualizar, atualizar e deletar posts  
✅ Fazer login e acessar posts privados  
✅ Filtrar posts por data de criação  

🔗 **Fontes de conhecimento para o projeto:**  
🎥 **Vídeo:** [Projeto Django API Completa - Pythonando](https://youtu.be/Q2tEqNfgIXM?si=8oBj1dbM7JtJTEAB)  
📚 **Texto:** [Tutorial DRF Oficial](https://www.django-rest-framework.org/tutorial/1-serialization/)  

