import 'package:flutter/material.dart';

void main() {
  runApp(MaterialApp(
    home: Scaffold(
      appBar: AppBar(
        title: Text("Calculator"),
        backgroundColor: Colors.blue,
        centerTitle: false,
      ),
      body: Center(
        child: Container(
          height: 200,
          width: 200,
          decoration: BoxDecoration(
            borderRadius: BorderRadius.circular(10),
            color: Colors.blue,
          ),
          alignment: Alignment.center,
          child: Container(
            padding: EdgeInsets.all(10), // Moved inside the inner Container
            decoration: BoxDecoration(
              borderRadius: BorderRadius.circular(10),
              color: Colors.red,
            ),
            child: Text("Hello"),
          ),
        ),
      ),
    ),
  ));
}
