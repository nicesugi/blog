# blog : 블로그 / 5월 31일 / 제한시간 1시간

1. Django 프로젝트를 생성하고, blog 라는 앱을 만들어서 [settings.py](http://settings.py) 에 등록해보세요.
</br></br>
2. [Models.py](http://Models.py) 에 <글 제목, 글 카테고리, 글 내용>이 들어갈 수 있는 `Article` 이라는 모델을 만들어보세요.
</br></br>
3. [Models.py](http://Models.py) 에 <카테고리 이름, 설명>이 들어갈 수 있는 `Category` 라는 모델을 만들어보세요.
</br></br>
4. Article 모델의 글 카테고리에는, Category 모델에 존재하는 카테고리만 들어갈 수 있도록 만들어보세요. (힌트: Foreign Key)
</br></br>
5. Admin 페이지를 통해서, Category 모델에 ‘영화’, ‘드라마’, ‘예능’ 이라는 카테고리를 각각 생성해보세요.
</br></br>
6. 새 글을 작성할 수 있도록, templates 폴더 안에 form 태그가 존재하는 `new.html` 을 만들고, [Views.py](http://Views.py) 과 [Urls.py](http://Urls.py) 에 적절한 코드를 작성해보세요.
</br></br>
7. 카테고리 목록을 볼 수 있도록, templates 폴더 안에 카테고리 이름을 리스팅하는 `category.html` 을 만들고, [Views.py](http://Views.py) 과 [Urls.py](http://Urls.py) 에 적절한 코드를 작성해보세요.
</br></br>
8. 작성된 글 목록을 볼 수 있도록, templates 폴더 안에 글 제목을 리스팅하는 `article.html` 을 만들고, 사용자가 `category.html` 에서 클릭한 카테고리에 해당하는 글만 필터링하여 보여주도록 [Views.py](http://Views.py) 과 [Urls.py](http://Urls.py) 에 적절한 코드를 작성해보세요.
</br></br>
9. 특정한 글의 내용을 볼 수 있도록, templates 폴더 안에 글의 제목과 내용을 보여주는 `detail.html` 을 만들고, 사용자가 `article.html` 에서 클릭한 글에 해당하는 제목과 내용을 보여주도록 [Views.py](http://Views.py) 와 [Urls.py](http://Urls.py) 에 적절한 코드를 작성해보세요.
</br></br>
10. (심화) `category.html` 에서 카테고리 목록을 보여줄 때, 카테고리 별 글의 개수까지 함께 보여줄 수 있도록 코드를 수정해보세요.**
</br></br>
참고1.내가 만든 카테고리 이름으로 url 을 접근할 수 있음 (docu 카테고리의 경우, admin 페이지에서 즉석으로 만들었고, 이후에 따로 [urls.py](http://urls.py) 를 편집해주지 않았음에도 해당 페이지로 접근이 됨)</br>
참고2. admin 페이지에서 새 카테고리를 만들자마자, 카테고리 페이지에서 해당 카테고리에 해당하는 글의 개수와 카테고리 이름을 볼 수 있음
