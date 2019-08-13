# Estudos na Linguagem Flutter


<b>Packages Dart: https://pub.dartlang.org/flutter</b>

# Resumo

<b>Widgets
S�o componentes que podem ser adicionados no layout, s�o organizados em hierarquias para formar a tela. Consulta aos widgets: https://flutter.dev/docs/development/ui/widgets

<b>setState(() {} )
Fun��o necess�ria para poder se conseguir alterar o estado de um Widget na tela, qualquer coisa que altere o estado de um Widget deve estar dentro dela, se n�o, n�o ser� alterado. O flutter atualiza somente redenriza os componentes alterados.

<b>Statefull
Altera o estado ao longo da uso da aplica��o, o hot reload funciona nesses casos.

<b>Material design
Site: material.io

<b>Stateless
Mant�m o mesmo estado ao longo da aplica��o, caso o pai seja stateless, n�o funciona o hot reload nos filhos.


# Apps Desenvolvidos e conceitos utilizados.

<li>contador_de_pessoas : MaterialApp, StatefulWidget, setState, adi��o de imagem do resources (asset), Image.asset, Text, TextStyle, FlatButton, Padding, Stack, Column, debugPrint, Container, EdgeInsets, Colors;

<li>calculo_imc : TextEditingController, double.parse, .toStringAsPrecision(3), Scaffold, AppBar, IconButton, Icons, SingleChildScrollView, GlobalKey<FormState>, Form, TextFormField, TextInputType, RaisedButton, Column;

<li>conversor_de_moedas: async, FutureBuilder, Icon, Divider, Future, http, json, TextField, InputDecoration, OutlineInputBorder;

<li>lista_tarefas: initState, getApplicationDocumentsDirectory, File, Future.delayed, Row, ListView, Expanded, Dismissible, DateTime, Align, CheckboxListTile, SnackBar, SnackBarAction, Duration;

<li>buscador_gifs : debugShowCheckedModeBanner, separa��o das telas por arquivos, Image.network, CircularProgressIndicator, AlwaysStoppedAnimation, Alignment, AsyncSnapshot, GridView, SliverGridDelegateWithFixedCrossAxisCount, GestureDetector, FadeInImage, kTransparentImage, BoxFit, Navigator, MaterialPageRoute, Share;

<li>agenda_contatos: enum, PopupMenuButton, PopupMenuEntry, PopupMenuItem, FloatingActionButton, Card, BoxDecoration, BoxShape, DecorationImage, FileImage, AssetImage, showModalBottomSheet, BottomSheet, FlatButton, Navigator, sort, FocusNode, WillPopScope, FocusScope, ImagePicker, ImageSource, FileImage, AssetImage, showDialog, AlertDialog, FlatButton, Future.value, singleton, Database, fromMap, toMap;

<li>chat_online: ThemeData, GoogleSignIn, FirebaseAuth, GoogleSignInAccount, GoogleSignInAuthentication, Firestore, Theme.of(context).platform, SafeArea, StreamBuilder, CircularProgressIndicator, Divider, IconTheme, IconThemeData, IconButton, StorageUploadTask, FirebaseStorage, CupertinoButton, IconButton, CircleAvatar;

<li>loja_virtual (Screenshots): Model, notifyListeners, ScopedModel, ScopedModelDescendant, Color.fromARGB, SizedBox, ExpansionTile, Expanded, CircleAvatar, InkWell (para dar o effeito de ripple), SliverAppBar, SliverStaggeredGrid, CustomScrollView, FadeInImage.memoryNetwork, NeverScrollableScrollPhysics, drawer, VoidCallback;

<li>flare_test (Screenshots): FlareActor, SplashScreen;

<li>fluttertube (Screenshots): factory Video.fromJson, SearchDelegate, showSearch, Future.delayed(Duration.zero).then((_) => close(context, query)), FlutterYoutube, BlocBase, dispose, BlocProvider, StreamController, StreamBuilder, BehaviorSubject, MapEntry, SharedPreferences, cast, containsKey, remove, CircularProgressIndicator, AlwaysStoppedAnimation, Infinity scroll, stream, sink;

<li>animations (Screenshots): SingleTickerProviderStateMixin, AnimationController, void initState(), void dispose(), Animation, AnimatedWidget, animation.addStatusListener, animation.addListener, Tween, FlutterLogo, AnimatedBuilder, Curves.easeInOut, Curves.bounceIn, Curves.elasticOut, Curves.fastOutSlowIn, opacityTween.evaluate(animation).clamp(0.0, 1.0);

<li>animation (Screenshots): import 'package:flutter/scheduler.dart' show timeDilation;, SafeArea, IgnorePointer;

# Packages Utilizados
<li>http : requisi��es http para API Restful;

<li>path_provider : retorna o endere�o do arquivo no dispositivo;

<li>share : compartilha conte�do do app, mostra dialog do sistema para compartilhar;

<li>transparent_image : imagem transaparent para o FadeInImage;

<li>sqflite : banco de dados SQLite;

<li>url_launcher : abre aplicativos padr�o do sistema: navegador, discador, etc;

<li>image_picker : Obt�m uma imagem da camera ou da galeria;

<li>cloud_firestore : acesso ao db firestore;

<li>google_sign_in : login com o google;

<li>firebase_storage : acesso ao storage (blog de imagens);

<li>firebase_auth : autentica��o com o firebase;

<li>firebase_analytics : analytics do firebase;

<li>firebase_messaging : push notifications do firebase;

<li>font_awesome : icones do font awesome;

<li>flutter_staggered_grid_view : grid view staggered para flutter;

<li>carousel_pro : carrossel;

<li>scoped_model : conjunto de utilit�rios para passar dados de um Model para um Widget pai e seus filhos, permitindo ainda sua reconstru��o caso o Model seja atualizado;

<li>flare_flutter: pacote para permitir adicionar as anima��es do Flare no app Flutter;

<li>flutter_youtube: player para videos do youtube;

<li>shared_preferences: acessa as configura��es de usu�rio salvas no dispositivo;

<li>rxdart: reactive X para dart, utilizado para facilitar a implementa��o do BloC;

<li>bloc_pattern: ajuda na implementa��o do BloC pattern no flutter;