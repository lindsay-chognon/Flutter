# Flutter

J’ai compris que Flutter permet de créer des applications pour Android, iOS, Linux, Mac et Windosw. 
Je ne peux pas créer un exécutable iOS sur mon Linux mais je pourrais prendre mon code et le compiler sur un mac pour obtenir une application iOS. 
Ce concept permet de baisser les coûts de développement. 

Le framework utilise le langage de programmation Dart (on dirait un dérivé de Javascript). 
Tout ce qui est affiché est codé dans un widget et peuvent réagir à des interactions avec l’utilisateur. 
Il y a des widgets stateless et stateful. Un widget stateless ne change pas d’état. 
Ca peut être par exemple une icône. Un widget stateful peut lui changer d’état. 
Il interagit avec l’utilisateur comme par exemple lors du remplissage d’un formulaire. 

Toutes les applications commencent par : 
import packages: 'flutter/material.dart';
Il s’agit de l’importation d’une bibliothèque.
Il y a ensuite un point d’entrée : void main => runApp(Myapp()); 
Ce point d’entrée permet de lancer l’application. 
