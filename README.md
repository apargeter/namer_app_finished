# namer_app

https://codelabs.developers.google.com/codelabs/flutter-codelab-first#4

Finished tutorial

If you feel adventurous, try to do this step by yourself. Your goal is to show the list of favorites in a new stateless widget, FavoritesPage, and then show that widget instead of the Placeholder.

Here are a few pointers:

    When you want a Column that scrolls, use the ListView widget.
    Remember, access the MyAppState instance from any widget using context.watch<MyAppState>().
    If you also want to try a new widget, ListTile has properties like title (generally for text), leading (for icons or avatars) and onTap (for interactions). However, you can achieve similar effects with the widgets you already know.
    Dart allows using for loops inside collection literals. For example, if messages contains a list of strings, you can have code like the following:

On the other hand, if you're more familiar with functional programming, Dart also lets you write code like messages.map((m) => Text(m)).toList(). And, of course, you can always create a list of widgets and imperatively add to it inside the build method.

The advantage of adding the Favorites page yourself is that you learn more by making your own decisions. The disadvantage is that you might run into trouble that you aren't yet able to solve by yourself. Remember: failing is okay, and is one of the most important elements of learning. Nobody expects you to nail Flutter development in your first hour, and neither should you.

See bottom of https://codelabs.developers.google.com/codelabs/flutter-codelab-first#7
