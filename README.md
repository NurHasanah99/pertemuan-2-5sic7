# pertemuan -3 - Latihan

import 'package:flutter/material.dart';

void main() {
  runApp(new MaterialApp( 
    debugShowCheckedModeBanner: false,
      title: 'Nurhasanah 5sic7',
    home: new ClassCoba(),
  ));
}

class ClassCoba extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(),
      body: new Column(
        mainAxisAlignment: MainAxisAlignment.center,
        children: <Widget>[
          new Row(
            mainAxisAlignment: MainAxisAlignment.spaceEvenly,
            children: <Widget>[
              Text("Budi",
                  style:
                      
                      TextStyle(fontSize: 25, fontFamily: "times new roman")),
              Text("Rini",
                  style:
                      TextStyle(fontSize: 25, fontFamily: "times new roman")),
            ],
          ),
        ],
      ),
    );
  }
}
