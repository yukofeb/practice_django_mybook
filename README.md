# practice_django

## References
[Python Django入門 (1) - Qiita](http://qiita.com/kaki_k/items/511611cadac1d0c69c54)  
[Virtualenvwrapperの導入 - Qiita](http://qiita.com/_rdtr/items/5f3a9a9e2cb5a24f284e)  

## Useful Commands
virtualenvwrapperの環境に入る
(作成方法は省略。詳細はReferencesの2番目を参照)

```
$ workon (env_name)
```

プロジェクト作成

```
$ django-admin.py startproject mybook
```

アプリケーション作成

```
$ python manage.py startapp (app_name)
```

dbのsuperuser作成

```
$ python manage.py createsuperuser
```

dbのmigrate

```
$ python manage.py makemigrations (app_name) #マイグレーションファイル作成
$ python manage.py sqlmigrate (app_name) (migrate id) #マイグレーション内容の確認（反映はしない）
$ python manage.py migrate #マイグレーション実行
```

開発用サーバ起動

```
$ python manage.py runserver
```
